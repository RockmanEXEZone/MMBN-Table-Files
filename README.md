MMBN Table Files
================
Character table files for the Mega Man Battle Network games, to be used for text modding.

Notes
-----
* For byte sequences that have yet to be identified, put a placeholder like so: [$00] or [$E400].
* For Latin characters in Japanese table files, use the standard Latin alphabet Unicode characters; do not use full-width or half-width letter characters, unless the game has a clear distinction between the two.
* For Japanese characters in Japanese table files, use their full-width versions.
* Try to use the same Unicode characters across all table files.
* In case of duplicate characters, add [brackets] around the characters that are NOT used by the game. If there is more than one duplicate, put a number behind all duplicates past the first, before the end bracket ].
* Use single-character Unicode symbols as much as possible. For instance:
	* For "...", don't put three periods, but rather put the dedicated Unicode ellipsis character (U+2026).
	* For a "middle dot", don't put [middledot], but rather put katakana middle dot (U+30FB) for consistency with the Japanese versions.
* There are some exceptions to this:
	* In the case of shape symbols where no suitable Unicode symbol exists, put a brief description between brackets.
	* If such a symbol is grouped with other symbols that DO have suitable Unicode symbols, preferably put bracket descriptions for all of them.
	* In case a byte maps to an ACTUAL bracket character ('[' or ']'), escape it with a backslash, like so: \\[
* Because of the above, also escape backslash characters ('\') with another backslash, like so: \\\\

Progress
--------
| Game                                           | File             |    |     | Status				|
|------------------------------------------------|------------------|----|-----|--------------------------------|
| Mega Man Battle Network                        | bn1-utf8.tbl     | EN | GBA | Done.				|
| Mega Man Battle Network 2                      | bn2-utf8.tbl     | EN | GBA | Done.				|
| Mega Man Battle Network 3                      | bn3-utf8.tbl     | EN | GBA | Done.				|
| Mega Man Battle Network 4                      | bn4-utf8.tbl     | EN | GBA | Done.				|
| Mega Man Battle Network 5                      | bn5-utf8.tbl     | EN | GBA | Done. DS is identical.		|
| Mega Man Battle Network 6                      | bn6-utf8.tbl     | EN | GBA | Done.				|
| Mega Man Battle Chip Challenge                 | bcc-utf8.tbl     | EN | GBA | Mostly done, some kanji left.	|
| Mega Man Battle Network 5: Double Team DS (EU) | bn5dse-utf8.tbl  | EN | NDS | Done.				|
| Mega Man Star Force                            | sf1-utf8.tbl     | EN | NDS | Done.				|
| Mega Man Star Force 2                          | sf2-utf8.tbl     | EN | NDS | Done.                          |
| Mega Man Star Force 3                          | sf3-utf8.tbl     | EN | NDS | Done.				|
| Battle Network Rockman EXE                     | exe1-utf8.tbl    | JP | GBA | Done.				|
| Battle Network Rockman EXE 2                   | exe2-utf8.tbl    | JP | GBA | Done.				|
| Battle Network Rockman EXE 3                   | exe3-utf8.tbl    | JP | GBA | Done.				|
| Rockman EXE 4                                  | exe4-utf8.tbl    | JP | GBA | Done.				|
| Rockman EXE 4.5: Real Operation                | exe45-utf8.tbl   | JP | GBA | Done.				|
| Rockman EXE 5                                  | exe5-utf8.tbl    | JP | GBA | Done.				|
| Rockman EXE 6                                  | exe6-utf8.tbl    | JP | GBA | Done.				|
| Rockman EXE Battle Chip GP                     | exebcgp-utf8.tbl | JP | GBA | Mostly done, some kanji left.	|
| Rockman EXE WS                                 | exews-utf8.tbl   | JP | WSC | Some kanji left.		|
| Rockman EXE N1 Battle                          | exen1b-utf8.tbl  | JP | WSC | Not started.			|
| Rockman EXE 5 DS: Twin Leaders                 | exe5ds-utf8.tbl  | JP | NDS | Done.				|
| Rockman EXE: Operate Shooting Star             | exeoss-utf8.tbl  | JP | NDS | Done.				|
| Ryuusei no Rockman                             | rnr1-utf8.tbl    | JP | NDS | Done.				|
| Ryuusei no Rockman 2                           | rnr2-utf8.tbl    | JP | NDS | Done.                          |
| Ryuusei no Rockman 3                           | rnr3-utf8.tbl    | JP | NDS | Done.				|

Mega Man, Rockman, Mega Man Battle Network and Rockman EXE are (c) Capcom.
