# updated-webm
It contains some .webm files for file transfer for sfu server.

Commands used for generation of these file are 

ffmpeg -i video.mp4 -b:v 192k -b:a 192k output1.webm
ffmpeg -i video.mp4 -b:v 100k -b:a 100k output2.webm
ffmpeg -i video.mp4 -b:v 150k -b:a 150k output3.webm
ffmpeg -i video.mp4 -b:v 200k -b:a 100k output4.webm
ffmpeg -i video.mp4 -b:v 100k -b:a 200k output5.webm
