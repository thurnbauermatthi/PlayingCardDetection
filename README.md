# PlayingCardDetection
Disclaimer: This was my first real object detection project where I got in contact with Yolo which was created in the scope of a semestral project.

## Project Description
The task was to search for an Object Detection project on your own and implement it with the framework of our choice. We had to use two differenct approaches and then present some differences in the result. I was using YoloV3 and YoloV5 to tackle this project.

## Dataset description
The dataset used for this project was created by myself. For that I've used bavarian playing cards called "Schafkopf, Bayerisches Blatt" (see https://en.wikipedia.org/wiki/Schafkopf). There are 36 cards in total with 4 different colors but normally only 32 cards are used because cards of the rank "6" are removed. So in total I created 32 different classes although we could have created a classifier which detects only the rank and one which detects only the color. I've created 137 images in total and labelled them with roboflow. The train/val/test split is 120, 11 and 6, respectively.

## Result
The result for both approaches was okay-ish but it could've been definitelly improved by using more training data.

## YoloV3
Result image for a test image:

![alt text](https://github.com/thurnbauermatthi/PlayingCardDetection/blob/main/detection_result_image_yolov3.PNG?raw=true)

## YoloV5
Result image for a test image:

![alt text](https://github.com/thurnbauermatthi/PlayingCardDetection/blob/main/detection_result_image_yolov5.jpg?raw=true)
