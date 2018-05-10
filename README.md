# User-Verification-System-Via-Face-Recognition

The following repository is the result of a semester long Capstone project by
Timothy Hamling, Karolina Fik, and Mitchell Rifkind. It involves an Arduino Uno
connected to a computer running Linux Ubuntu which is also connected to an
external web camera. A button press on the Arduino triggers the camera to
capture an image which is then passed through to the software on the computer
running a comparison of the face of the user with all faces saved in a Mongo DB
instance. There is an accompanying GUI allowing administrators and developers
with the proper credentials the ability to add or remove faces as well as run
recognition results by the developer.

The following dependancies and libraries were used in the development and
execution of the code:

Local database instance:

MongoDB

Python Libraries:

easygui
os
shutil
PIL
face_recognition
sys
numpy
pymongo
time
datetime
cv2
dlib
serial
struct

Operating System:

Linux Ubuntu Version 17.10

Development Environments:

gedit
Arduino IDE

Version Control:

Google Team Drive
