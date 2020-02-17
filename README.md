# License-Plate-Detector
This project uses YOLO to detect and draw bounding boxes around License Plates of cars in image/video. Made using Darknet(www.pjreddie.com) and trained on Google Colab.



Find the pre-trained weights at https://drive.google.com/open?id=1sBNjFr1531kwMe0UQsZE3KV4I4V2_YNC.


HOW TO INSTALL
1. Download all files in the repository and the pre-trained weights.
2. Put all of these files in your darknet folder. (follow instructions here www.pjreddie.com to download and build darknet on your computer)
3. open a terminal in the darknet folder and type,
   ./darknet detector test obj.data plate-yolov3-tiny.cfg  yolov3-tiny_last.weights sample.jpg

