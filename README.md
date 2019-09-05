# Snake-MP3-Player-Python-PyQt
Video: https://www.youtube.com/watch?v=Vd1OPLN2QAk

Exe: http://www.mediafire.com/file/o27jt6unxwwzcai/Snake_MP3_Player_Setup.exe/file

A project I made for university but never got to actually show it to my lecturer. It's a MP3/M3U music player with all the basic functionality.

In order to start it you'll need to do the following installs first:
pip install PySide --only-binary :all:
pip install pygame
pip install mutagen
pip install PyLyrics

If you'd like to have it as a normal .exe (as it was in the video) then all you need is this: 
1. Google Chrome (https://www.google.com/chrome/)
2. 'pywin32-221.win-amd64-py3.4.exe' from here: https://sourceforge.net/projects/pywin32/files/pywin32/Build%20221/
3. 'auto-py-to-exe' from here: https://github.com/brentvollebregt/auto-py-to-exe
4. Do 'pip install -r requirements.txt' from inside the 'py-exe Converter' folder.
5. Do 'python run.py' from inside the 'auto-py-to-exe-master' folder.
6. Select the options you want via the GUI window.
7. Click on 'CONVERT .PY TO .EXE NOW'.
PS: If there is an 'utf-8' error, go to 'run.py' file and change 'utf-8' to 'latin-1' on line 67.
