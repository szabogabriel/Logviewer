# Logviewer
A small log viewing utility written in bash.

## Usage
The script should be called from a webserver with CGI support (tested with Apache). It parses all the necessary CGI parameters and lists the target folders / files. There is a search and marking option. 

## Dependencies
The script builds upon standard Linux toolset (`bash`, `dd`, `sed`, `grep`, `cat`, `awk`, `echo`). These must be installed on the target machine. There is no binding on a given version of these tools.

## Todo
There are cookies used but no settings for them and no disclaimer shown on the webpage.
