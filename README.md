# Ad Barricade
## Ad blocking bash shell script inspired by AdAway

### Table of Contents
* [Warning](#warning)
* [Usage](#usage)

### Warning
This script was written for fun and it hasn't been tested for edge cases, use at your own risk.

### Usage
Get help by typing
```
./adbr -h
```
```
Ad blocking bash shell script inspired by AdAway

Usage: adbr [-b] [-r] [-v] [-h]
-b    Backup the current hosts file manually
-r    Restore the original hosts file from the backup
-v    Print versioning information
-h    Print this help message
```
You need to populate the URL file with ad server URLs.
A good place to start is [Steven Black's hosts](https://github.com/StevenBlack/hosts).

Afterwards run the script without arguments to generate and install the hosts file
```
./adbr
```
