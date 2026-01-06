# Some utils:

### Convert .mov animation to .mp4 video using ffmpeg

```bash
ffmpeg -i FileName.mov -c:v libx264 -pix_fmt yuv420p -crf 18 -preset slow FileName.mp4
```
