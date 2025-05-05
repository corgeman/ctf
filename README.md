# ctf
A repository of every CTF challenge I've released

### difficulty descriptions
Difficulty is subjective, so here's what each ranking means to me.

| name   | difficulty                                                                                                                        |
| ------ | --------------------------------------------------------------------------------------------------------------------------------- |
| baby   | Doesn't require much thought, should be solvable by someone new to the category.                                                       |
| easy   | Requires a little thinking, but I imagine ChatGPT would oneshot it. The steps to solve this challenge can be easily found online. |
| medium | You shouldn't be able to solve this without research. The tactic will be novel or have little documentation.                      |
| hard   | You will have to invent something *uniquely* novel, something that hasn't been done despite previous research in its area.        |
| insane | This is a bad challenge to put in a CTF-- there's too much to do in too little time. It's likely nobody would solve this.         |


# BuckeyeCTF 2024

| Name                                                                                                    | Category  | Idea                                                                                                                                                | Difficulty |
| ------------------------------------------------------------------------------------------------------- | --------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| [no_handouts](https://github.com/cscosu/buckeyectf-2024-public/tree/master/pwn/no_handouts)             | pwn       | Read a flag in a shell-less docker container.                                                                                                       | easy       |
| [sailing_the_c](https://github.com/cscosu/buckeyectf-2024-public/tree/master/pwn/sailing_the_c)         | pwn       | Leak the base of everything inside /proc/self/maps with an arbitrary read vulnerability.                                                            | medium     |
| [infrequentc](https://github.com/cscosu/buckeyectf-2024-public/tree/master/pwn/infrequentc)             | pwn       | Spot and exploit a sneaky OOB bug in a very short frequency analysis program.                                                                       | medium     |
| [flagwatch](https://github.com/cscosu/buckeyectf-2024-public/tree/master/rev/flagwatch)                 | rev       | Reverse an AHK macro compiled with [ahk2exe](https://github.com/AutoHotkey/Ahk2Exe)                                                                 | baby       |
| [reduce_recycle](https://github.com/cscosu/buckeyectf-2024-public/tree/master/forensics/reduce_recycle) | forensics | Abuse ZipCrypto to determine the 12-character password used to encrypt a `.zip`                                                                     | medium     |
| [the_cia](https://github.com/cscosu/buckeyectf-2024-public/tree/master/forensics/the_cia)               | forensics | Open a PDF using legacy 40-bit encryption.                                                                                                         | medium     |
| [gentleman](https://github.com/cscosu/buckeyectf-2024-public/blob/master/misc/gentleman/README.md)      | misc      | Get RCE with Python's [format string bug](https://podalirius.net/en/articles/python-format-string-vulnerabilities/), previously thought impossible. | hard       |

