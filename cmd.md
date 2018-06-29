# How-To
  - Convert each file in a directory with FFmpeg:
    ```
    for /f "tokens=*" %f in ('dir /b *.flac') do (ffmpeg -i "%f" "%~nf.mp3")
    ```
  - Rename each file in a directory to lowercase:
    ```
    for /f "tokens=*" %f in ('dir /l/b/a-d') do (rename "%f" "%f")
    ```

# Useful Utilities
  - `F7`: Show a list of previous commands
  - `tree [/f]`: Show tree of current directory