# Board Game Still Image Webcam Server

## Requirements

apt fswebcam
pip simple-http-server

make a 777 folder called images

## Notes

For nginx:

```
cd  /var/www/html`
sudo mount -t tmpfs -o size=128m images ./images/`
fswebcam -r 1920x1080 -l 1 -S 49 --title "dagoncam" --rotate 180 --jpeg 95 --timestamp "%H:%M:%S" --line-colour 00FFFFFF -q images/image.jpg
```