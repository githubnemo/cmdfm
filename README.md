# Native bash Jukebox based on cmd.fm

![alt tag](https://raw.github.com/llaine/cmdfm/master/images/img.png)

## How to 

1. `chmod +x jukebox.sh`
2. `./jukebox.sh`


### Usage argv
```bash

 -a         --> display all the musical genre .
 -g <style> --> launch a playlist the selected musical genre.

```


## Requirements

1. [mplayer](http://doc.ubuntu-fr.org/mplayer)
2. [curl](http://curl.haxx.se/)
3. Unix system

### Bug 

1. The cmd.fm API sometime does not render a proper song, mplayer is trying to stream a not found song. In that case, the script freeze