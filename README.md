# h1 Face Detection / Eye localization software

A small script for face detection and eye localization I made while I had access to a Raspberry Pi. I wanted to play with
it a bit, so I created this script as at the time I was involved in some AI work at college.

It was my first experience using Raspberry Pi, which I ended up running headless using VNC Viewer/Putty due to certian technical limitations
at the time.

It uses a pretrained haarcascade model imported from cv2.

## Running the code

cv2 as well as NumPy are needed to run the code.
If you're using `pip` make sure it's up to date with the latest version (`pip install --upgrade pip`).

Simply install them in the directory where you've pulled the code to with `pip install opencv-python` and `pip install numpy`.

After that, run the program with `python main.py`.

**The device you're running it on needs to have a camera connected/integrated for the code to run successfuly.**
