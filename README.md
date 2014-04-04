logsince
========

Logsince - A log reader that remembers where you last read

```
usage: logsince [-h] [--start START] [--length LENGTH] [--clean] [--debug]
                [--test]
                logfile

Print log from last line printed, creates hidden .logsince and .logsince.LCK
files

positional arguments:
  logfile          the logifle to parse

optional arguments:
  -h, --help       show this help message and exit
  --start START    use start instead of last position
  --length LENGTH  number of lines to read, defaults to end of file
  --clean          clean up hidden files
  --debug          turn debug on
  --test           do not write to .logsince file, only read from it
```
