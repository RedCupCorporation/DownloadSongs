# DownloadSongs

#### A ruby command-line tool for downloading mp3 files from the *INTERNET*

Enter one or multiple search queries and the script will fetch a matching song.  For each search query passed in, the script finds and downloads the highest quality matching song.

```
$ ./download.rb -h
Usage: download.rb [options] song1 song2 ...
    -p, --play                       Play song after downloading
    -o, --open                       Open song after downloading
    -q, --quality [KBPS]             Minimum quality mp3 in KBPS
    -v, --verbose                    Output more information
    -l, --logfile FILE               Write log to FILE
    -d, --path PATH                  Save mp3 file to PATH
    -h, --help                       Display help
```
