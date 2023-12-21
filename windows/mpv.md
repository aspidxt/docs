# MPV
https://mpv.io/manual/master/


### [mpvNET](https://github.com/mpvnet-player/mpv.net)
MPV fork with minimal and fast GUI. Has minimal differences and compatible with vanilla MPV. 
Use instead of vanilla MPV.


### Interface tweaks
[uosc](https://github.com/tomasklaen/uosc)

[thumbfast](https://github.com/po5/thumbfast) 
require mpv binary


Video device output config on Windows:
```conf
vo = gpu-next
# Fast and modern, required for many features

gpu-context = d3d11
# Tear-free and fast

# `audio` - sunc with audio track, `display-resample` resample audio to match video
video-sync = display-resample
```


### Save state
`mpv.conf`:
```conf
save-position-on-quit = yes
watch-later-options = start,speed,aid

keepaspect-window = no
snap-window = yes
```

* [autosave](https://gist.github.com/Hakkin/5489e511bd6c8068a0fc09304c9c5a82) Periodically saves "watch later" data during playback

## Binaries
* [mpv](https://sourceforge.net/projects/mpv-player-windows/files/64bit-v3/) original mpv binaries
* [yt-dlp](https://github.com/yt-dlp/yt-dlp) allow to watch videos from YouTube, etc. Require ffmpeg binary
* [ffmpeg](https://www.gyan.dev/ffmpeg/builds/#release-builds) allow decoding and processing streams

