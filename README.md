# Convert Multiple Videos With FFMPEG

1. You need download [FFMPEG](https://ffmpeg.org/download.html).
2. Add to `Enviroment Variables` on your OS.
3. Create a `*.bat` (ex: convert.bat) file for **Windows**. If are you using **Linux**/**macOS** create `*.sh` (ex: convert.sh) file.

Now, we need to add this code.

```
ffmpeg -i [current_video_1_path] [new_video_1_path]
ffmpeg -i [current_video_2_path] [mew_video_2_path]
...
ffmpeg -i [old_video_n_path] [new_video_n_path]
```

Save and exit.

Execute on `CMD` or `Terminal`.

# Example

`convert.bat`
```
ffmpeg -i video1.mkv video1.mp4
ffmpeg -i video2.mkv video2.mp4
ffmpeg -i video3.mkv video3.mp4
ffmpeg -i video4.mkv video4.mp4
ffmpeg -i video5.mkv video5.mp4
```

Have a fun. 😎
