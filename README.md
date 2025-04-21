[![Download the latest version](https://img.shields.io/badge/Download-Latest%20version-orange)](https://github.com/burianvlastimil/root-shell/releases/latest) &nbsp; &nbsp; &nbsp; &nbsp; [![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/burianvlastimil/root-shell/?tab=MIT-1-ov-file)

# Become superuser, but prevent nested root shells

Description: `root-shell` is a POSIX shell script to prevent nested root shells, which means it will not allow you to go for example `sudo -i` and again `sudo -i`, etc.

Usage: I recommend aliasing it, for example as `alias sup='/path/to/root-shell'` in Bash, or similarly in other shells.
