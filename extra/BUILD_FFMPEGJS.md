# How to build ffmpegjs

1. checkout https://github.com/ffmpegjs/FFmpeg commit 0deba716e237a538
2. replace `build-js.sh` with the `build-js.sh` from this directory
3. patch the cloned repository with `aeafix.patch`
4. run `build-with-docker.sh`
5. copy `dist/ffmpeg-core.js` to this project `public` folder
