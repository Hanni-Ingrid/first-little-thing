
# command line

## file paths


| | |
| -| -|
|`img/logo.png` |relative path: resolved relative to current working directory |
|`/usr/bin/bash` | absolute path: resolved relative to the file system root |
|`.` | Current working directory  |
| `..`| Parent working directory|
| `~`| user home directory |

## Browsing the file system

|||
|-|-|
|pwd| print working directory|
|cd|change working directory to home directory , equivalent to `cd ~`|
|`cd <path>`| change working directory to <path>|
|ls| list files in working directory|
|ls <path>|list the files in path|
|ls -l|list files in **long format**, including file permissions, owner, change date, files|
|ls -a| list **all** files including hidden files|
|cat <file>| print <file> to stdout, interpreted as a plain text|
|hexdump <file>| print Bytes in <file> using hexadecimal digits|
