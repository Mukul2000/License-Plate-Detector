### License-Plate-Detector
This project uses YOLO to detect and draw bounding boxes around License Plates of cars in image/video. Made using Darknet(www.pjreddie.com/darknet) and trained on Google Colab.

### Software Packs Needed

* <a href='https://www.anaconda.com/download/'>Anaconda 3</a> (**Tool comes with most of the required python packages along with python3 & spyder IDE**)<br>
* <a href='https://github.com/tesseract-ocr/tesseract'>Tesseract Engine</a> (**Must need to be installed**)<br>

### Python Packages Needed

* <a href='https://github.com/tensorflow/tensorflow'>Tensorflow</a><br>
* <a href='https://github.com/skvark/opencv-python'>openCV</a><br>
* <a href='https://github.com/madmaze/pytesseract'>pytesseract</a><br>
* <a href='https://github.com/tzutalin/labelImg'>labelImg</a><br>


Find the pre-trained weights at https://drive.google.com/open?id=1sBNjFr1531kwMe0UQsZE3KV4I4V2_YNC.


HOW TO INSTALL
1. Install the requirements.txt using your terminal.
2. Download all files in the repository and the pre-trained weights.
3. Put all of these files in your darknet folder. (follow instructions here www.pjreddie.com/darknet to download and build darknet on your computer)
4. open a terminal in the darknet folder and type,
   ./darknet detector test obj.data plate-yolov3-tiny.cfg  yolov3-tiny_last.weights sample.jpg

