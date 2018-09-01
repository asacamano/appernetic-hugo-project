# How to extract just the right images from the Dropbox download

On Termux

```sh
unzip -l ~/storage/downloads/Initiatives\ to\ Address\ Misconduct\ and\ Harm.zip  | grep -v 'MACOSX' | grep -e '8-7-18' -e '7-30-18' | cut -c 31- | awk '{print "\""$0"\""}' | xargs unzip ~/storage/downloads/Initiatives\ to\ Address\ Misconduct\ and\ Harm.zip 
```
