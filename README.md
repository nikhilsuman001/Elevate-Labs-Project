# Elevate-Labs-Project
<br>
# Steganography Tool for Image/File Hiding

This project hides secret text messages inside PNG images using Least Significant Bit (LSB) encoding.

## Features
- Encode and decode messages in PNG images.
- Simple GUI using Tkinter.
- Command-line usage for automation.

## Usage
### CLI:
python stego.py encode input.png "secret message" output.png
python stego.py decode output.png

### GUI:
python gui_stego.py

## Requirements
- Python 3.x
- Pillow library (pip install pillow)
