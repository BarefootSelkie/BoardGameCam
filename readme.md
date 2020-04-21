# Board Game Still Image Webcam Server

## Requirements

apt fswebcam
pip simple-http-server

make a 777 folder called images

## Notes

sudo mount -t tmpfs -o size=128m images ./images/
fswebcam -r 1920x1080 -l 1 -S 100 images/image.jpg
python -m SimpleHTTPServer