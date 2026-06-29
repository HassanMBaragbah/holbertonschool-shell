# Shell, I/O Redirection and Filters

This project is part of the shell curriculum and focuses on understanding I/O redirections, pipelines, and basic command-line filters in Ubuntu 20.04 LTS.

## Requirements
* All scripts are written in Bash and are exactly 2 lines long.
* The first line of all scripts is `#!/bin/bash`.
* All files end with a new line.
* All files are executable.

## Files Description

| File Name | Description |
| --- | --- |
| `0-hello_world` | A script that prints "Hello, World", followed by a new line to the standard output. |
| `1-confused_smiley` | A script that displays a confused smiley `"(Ôo)'`. |
| `2-hellofile` | A script that displays the content of the `/etc/passwd` file. |
| `3-twofiles` | A script that displays the content of both `/etc/passwd` and `/etc/hosts` files. |
| `4-lastlines` | A script that displays the last 10 lines of the `/etc/passwd` file. |
| `5-firstlines` | A script that displays the first 10 lines of the `/etc/passwd` file. |
| `6-third_line` | A script that displays the third line of the file `iacta` without using `sed`. |
| `7-file` | A script that creates a file with a complex name containing special characters and writes "Best School" into it. |
| `8-cwd_state` | A script that writes the result of the command `ls -la` into the file `ls_cwd_content`, overwriting it if it already exists. |
| `9-duplicate_last_line` | A script that duplicates the last line of the file `iacta` and appends it to the end of the file. |
| `10-no_more_js` | A script that deletes all regular files with a `.js` extension in the current directory and all its subfolders. |
| `11-directories` | A script that counts the number of directories and sub-directories in the current directory (excluding `.` and `..`). |
| `12-newest_files` | A script that displays the 10 newest files in the current directory, sorted from newest to oldest, one per line. |
| `13-unique` | A script that takes a list of words as input and prints only the words that appear exactly once, sorted. |
| `14-findthatword` | A script that displays lines from the file `/etc/passwd` containing the pattern "root". |
| `15-countthatword` | A script that displays the number of lines containing the pattern "bin" in the file `/etc/passwd`. |
