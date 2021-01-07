# yolov4-tiny project with custom-dataset (faces)

## **Object detection tutorial**

1. Create your own dataset with [Roboflow](https://roboflow.com/).
   - Annotate your images with [labelImg](https://github.com/mathieu34/yolov4_custom-dataset_webcam/tree/master/labelImg).
   - Think to use data augmentation for small datasets.
2. Train your model in google colaboratory using [Roboflow models](https://models.roboflow.com/) (*I choose YOLOv4-tiny Colab Notebook*).  
   - The related file is [YOLOv4_tiny_Darknet_Roboflow.ipynb](https://github.com/mathieu34/yolov4_custom-dataset_webcam/blob/master/YOLOv4_tiny_Darknet_Roboflow.ipynb). You get a result like this :  

![alt text](https://github.com/mathieu34/yolov4_custom-dataset_webcam/blob/master/predictions.png?raw=true)

3. Do Webcam real time object detection with the yolov4-tiny model train before. 
   - The related file is [real_time_detection_webcam.ipynb](https://github.com/mathieu34/yolov4_custom-dataset_webcam/blob/master/real_time_detection_webcam.ipynb) (*Don't forget to convert the .avi video to .gif*). You get a result like this :  
   
![caption](https://github.com/mathieu34/yolov4_custom-dataset_webcam/blob/master/myface.gif)

