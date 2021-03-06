# FF Video Converter
Simple video converter with cutting and cropping functionality, powered by the ffmpeg project

[Youtube demo](https://youtu.be/F1RwbC_K_4o)

## Features

- Encode video files in H264 and H265 and export them in mp4 or mkv format
- Experimental support for Nvidia H264 and H265 hardware accelerated encoders (only on RTX video cards, because  of lack of B-frame support on older gpus) <p align="center"><img width="700" src="https://i.imgur.com/QASTmmD.png"></p>
- Experimental support for Intel H264 and H265 hardware accelerated encoders; on computers with a dedicated GPU, Intel iGPU must be manually enabled for QuickSync to work
- Change framerate and resolution
- Cut video, with or without re-encoding it (with possibility of cutting at keyframes)
- Visually crop video
- Rotate video
- Preview encoding quality settings with before-after clips
- Open network media (direct url to media file) and convert it while it's still downloading <p align="center"><img width="700" src="https://i.imgur.com/71B5ixJ.gif"></p>
- Open videos from Reddit and Twitter posts at every quality
- Open videos from Facebook and Instagram posts
- Open Youtube videos at every audio and video quality<p align="center"><img width="700" src="https://i.imgur.com/VuYrnTr.gif"></p>
- Queue system

## Current Issues/Limitations

- Opening a Reddit or Youtube video won't play audio in the internal player, because the original video stream has no audio; when converting, however, audio will be included


## Credits
- [FFmpeg](https://www.ffmpeg.org/)
- [FFME](https://github.com/unosquare/ffmediaelement)
- [Youtube Explode](https://github.com/Tyrrrz/YoutubeExplode)
