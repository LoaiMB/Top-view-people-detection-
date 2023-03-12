# Fixed-Wing-
# Detection Model 
In this project, we used YOLOv4-tiny algorithm to perform top-view people detection with transfer learning (fine tuning). We utilized a pre-trained YOLOv4-tiny model that was trained on COCO dataset for object detection. Transfer learning allowed us to train the model to recognize people in top-view images.

## Dataset: 
We used a dataset of top-view images that contained people in different positions and orientations. The dataset was manually labeled using LabelImg tool, which allowed us to create bounding boxes around the people in the images. The labels were saved in the YOLO format, which consists of a text file for each image with a line for each labeled object, including the class label and the coordinates of the bounding box.

YOLOv4-tiny Model: 

We chose to use the YOLOv4-tiny model because it is an updated version of YOLOv3-tiny model, and it is known for its improved accuracy and performance. The pre-trained model was downloaded from https://github.com/AlexeyAB/darknet. To train the model for top-view people detection, we performed transfer learning by fine tuning the pre-trained YOLOv4-tiny model. The trained weight and cfg files can be find above in this repositry. 

Evaluation:

We evaluated the model on a separate test set that was not used during training or validation. We used the mean average precision (mAP) metric to measure the performance of the model. Where we achived a mAP arounf 0.75-0.80.  
