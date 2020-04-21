# Board Game Still Image Webcam Server

## Requirements

apt fswebcam
pip simple-http-server

make a 777 folder called images

## Notes

fswebcam -r 1920x1080 -S 2 images/image.jpg
sudo mount -t tmpfs -o size=128m images ./images/