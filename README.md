# Source

ffmpeg -f avfoundation -framerate 30 -video_size 640x480 -i "FaceTime HD Camera" -vcodec libx264 -profile:v baseline -preset ultrafast -pix_fmt yuv420p -f rawvideo http://localhost:8081

# Node

1. install packages
2. node wsrelay
