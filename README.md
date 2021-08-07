# PersonDetectionAndCount
The project implements YOLO v4 to detect persons and count them. It also draws the bounding box around the person detected.
YOLO v4 is implemented on Google Colab and yolov4_final_weights file is generated. This weight file can be found on this link: https://drive.google.com/file/d/1o51EXLjKrkJqx93CsEW5wkbBmsw6cRPK/view?usp=sharing
This weight file along with yolo-v4-train.cfg was used to compute the outputs and draw labels and bounding box using OpenCV.
The input can be an image, webcam feed or a video. 
YOLO v4 is ultra fast and works on COCO dataset with real time speed of 65 FPS.

The dataset used was downloaded from https://www.kaggle.com/karthika95/pedestrian-detection
Since, the annotations are in .xml formal, it can be converted into .txt format using the file convertxmltotxt.py I have provided. The Google Colab has been provided to train your own Custom Dataset with YOLO v4.

