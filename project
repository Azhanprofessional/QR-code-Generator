# pyqrcode for generating QR codes.
# png is used by pyqrcode for saving images.
# os is used for executing system commands.
import pyqrcode,os,png

# The URL that the QR code will encode.
link='https://www.jetbrains.com/pycharm/'

# Generates the QR code from the link.
image=pyqrcode.create(link)

# Saves the QR code as a PNG with a size of 10.
image.png('link.png',scale=10)

# Open the image (Windows only).
os.system('start link.png')
