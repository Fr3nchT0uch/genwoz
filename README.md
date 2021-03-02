# GenWoz

A command-line tool to generate an "empty" WOZ image file heavely based on DSK2WOZ (c) 2018 Thomas Harte.

v0.30
[Custom 32 sectors/128 bytes with custom GAPS]

**Code:** GROUiK (FRENCH TOUCH) / Thomas Harte


MIT License
<br/>
<br/>
## Usage:

genwoz.exe [-v] -t "0 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1"

- -v verbose mode (optional)
- -t "track table format" with 0:standard | 1: custom for each of the 35 tracks
<br/>
<br/>
## Building Instructions:

Open solution under Visual Studio Community (Windows 10).  
Can probably be ported to other platforms very easily.
<br/>
<br/>
## Disclaimer:

This tool has been written to help Apple II cross-development on PC and is made to be executed from a command line.   
It is not optimized and probably buggy under certain circumstances.  
Use it at your own risk!