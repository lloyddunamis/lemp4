@echo on
SET /p Picture= Picture=
"C:\Program Files\MeGUI\tools\ffmpeg\ffmpeg.exe" -framerate 30 -loop 1 -i %Picture% -c:v libx264 -r 30 -pix_fmt yuv420p -t 10 -threads 1 -r 30 -g 300 -bf 8 %Picture%.mp4
pause
