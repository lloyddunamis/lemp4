@echo on
SET Picture=looplist.txt
SET /p Audio= Audio=
"C:\Program Files\MeGUI\tools\ffmpeg\ffmpeg.exe" -f concat -safe 0 -i %Picture% -i %Audio% -c:v copy -c:a copy -shortest -threads 1 %Audio%.mp4
pause
