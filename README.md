# bmp-to-jpg
It is exactly what it says. It's a bash script that converts bmp images to jpg images. It converts every bmp image in the current working directory.

It's specific tho, but helpful.

To get the script working just copy the `bmp_to_jpg` file to where your images are and run it:
```bash
./bmp_to_jpg
```

The script uses the `magick` command from https://imagemagick.org for most of it's functionality. That said, the command may or may not be installed in your system and you need it installed for the script to work.
