## (Singe 2) Arcade Xperience Vol.2

**The Pantheon** - **The Animatrix** - **X-Story** - **Alleycats** - **Cyan Eyed**

Encode mp4 with:

    ffmpeg -i Arcade_Xperience_Vol2.mp4 -qscale:v 4 -b:v 6000k -codec:v mpeg2video -vf tpad=stop_mode=clone:stop_duration=2,scale=1280:720 ~/.daphne/singe/arcadex2/arcadex2.m2v

    ffmpeg -i Arcade_Xperience_Vol2.mp4 -vn -c:a libvorbis -ar 44100 -map a -b:a 160k  ~/.daphne/singe/arcadex2/arcadex2.ogg