# bmp-to-jpg
It is exactly what it says. It's a bash script that converts bmp images to jpg images. It converts every bmp image in the current working directory.

It's specific tho, but helpful.

To get the program working just copy the `bmp_to_jpg` file to where your images are and run it:
```bash
./bmp_to_jpg
```

The application uses the `magick` command from https://imagemagick.org. If you got an error that the command isn't found, you need to install it.
