MMBN Table Files
================
Character table files for the Mega Man Battle Network games, to be used for text modding.

Notes
-----
* In the general sense, adhere to the Table File Format as described here: 
* For Latin characters in Japanese table files, use the standard Latin alphabet Unicode characters; do not use full-width or half-width letter characters.
* For Japanese characters in Japanese table files, use their full-width versions.
* Try to use the same Unicode characters across all table files.
* In case of duplicate characters, add [brackets] around the characters that are NOT used by the game.
* Use single-character Unicode symbols as much as possible. For instance:
  * For "...", don't put three periods, but rather put the dedicated Unicode ellipsis character (U+2026).
  * For a "middle dot", don't put [middledot], but rather put the dedicate Unicode middle dot character (U+00B7).
* There are some exceptions to this:
  * In the case of shape symbols where no suitable Unicode symbol exists, put a brief description between brackets.
  * If such a symbol is grouped with other symbols that DO have suitable Unicode symbols, preferably put bracket descriptions for all of them.
* In case a byte maps to an ACTUAL bracket character ('[' or ']'), escape it with a backslash, like so: \\[

Progress
--------
| Game                                      | File             |          |        | Done    | Status                         |
| ----------------------------------------- | ---------------- |--------- | ------ | --------| ------------------------------ |
| Mega Man Battle Network                   | bn1-utf8.tbl     | EN       | GBA    | 147/147 | Done.                          |
| Mega Man Battle Network 2                 | bn2-utf8.tbl     | EN       | GBA    | 104/104 | Done.                          |
| Mega Man Battle Network 3                 | bn3-utf8.tbl     | EN       | GBA    | 127/127 | Done.                          |
| Mega Man Battle Network 4                 | bn4-utf8.tbl     | EN       | GBA    | 112/112 | Done.                          |
| Mega Man Battle Network 5                 | bn5-utf8.tbl     | EN       | GBA    | 434/434 | Done.                          |
| Mega Man Battle Network 6                 | bn6-utf8.tbl     | EN       | GBA    | 460/460 | Done.                          |
| Mega Man Battle Chip Challenge            | bcc-utf8.tbl     | EN       | GBA    | 0/0     | Not started.                   |
| Mega Man Battle Network 5: Double Team DS | bn5ds-utf8.tbl   | EN       | NDS    | 0/0     | Should be similar to BN5 GBA.  |
| Battle Network Rockman EXE 1              | exe1-utf8.tbl    | JP       | GBA    | 0/0     | Not started.                   |
| Battle Network Rockman EXE 2              | exe2-utf8.tbl    | JP       | GBA    | 0/0     | Not started.                   |
| Battle Network Rockman EXE 3              | exe3-utf8.tbl    | JP       | GBA    | 0/0     | Not started.                   |
| Rockman EXE 4                             | exe4-utf8.tbl    | JP       | GBA    | 0/0     | Not started.                   |
| Rockman EXE 4.5: Real Operation           | exe45-utf8.tbl   | JP       | GBA    | 441/441 | Done.                          |
| Rockman EXE 5                             | exe5-utf8.tbl    | JP       | GBA    | 0/0     | Not started.                   |
| Rockman EXE 6                             | exe6-utf8.tbl    | JP       | GBA    | 415/475 | Mostly done, some kanji left.  |
| Rockman EXE Battle Chip GP                | exebcgp-utf8.tbl | JP       | GBA    | 0/0     | Not started.                   |
| Rockman EXE WS                            | exews-utf8.tbl   | JP       | WSC    | 0/0     | Not started.                   |
| Rockman EXE N1 Battle                     | exen1b-utf8.tbl  | JP       | WSC    | 0/0     | Not started.                   |
| Rockman EXE 5 DS: Twin Leaders            | exe5ds-utf8.tbl  | JP       | NDS    | 0/0     | Should be similar to EXE5 GBA. |
| Rockman EXE: Operate Shooting Star        | exeoss-utf8.tbl  | JP       | NDS    | 0/0     | Probably similar to EXE1 GBA.  |

Credits
-------
* Prof. 9
* cornshot

Mega Man, Rockman, Mega Man Battle Network and Rockman EXE are (c) Capcom 1987 - 2014.