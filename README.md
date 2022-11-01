
# Tensorflow_Object_detection_API-Custom_Faster_RCNN
A sample project to detect the custom object using Tensorflow object detection API


#"""Model performances """
+----------------+----------+------------+
|     Model      | Map@0.50 | Iterations |
+----------------+----------+------------+
|     YOLOV4     |   0.91   |    2000    |
|     YOLOV2     |   0.84   |    100     |
| SSD_ReseNet101 |   0.99   |   10000    |
| SSD_MobileNet  |   0.98   |   10000    |
+----------------+----------+------------+

## Folder Structure for YOLO models 
- Tensorflow_API-Custom_object_detection
  - pre_trained_models
    - *downloaded files for the choosen pre-trained model will come here* 
  - dataset
    - Annotations
      - *Annotations for your training images will come here*
    - JPEGImages
      - *all of your images for training will come here*
    - testImages
      - *all your images for testing will come here*
    - obj.names
    -obj.data

   - IG
     - *inference graph of the trained model will be saved here*
   - CP
     - *checkpoints of the trained model will be saved here*

   - *config file for the choosen model*

## Folder Structure for Tensorflow_API models (SSD_ReseNet101,SSD_MobileNet)
- Tensorflow_API-Custom_object_detection
  - pre_trained_models
    - *downloaded files for the choosen pre-trained model will come here* 
  - dataset
    - Annotations
      - *Annotations for your training images will come here*
    - JPEGImages
      - *all of your images for training will come here*
    - testImages
      - *all your images for testing will come here*
    - lable.pbtxt
    - train.record
   - IG
     - *inference graph of the trained model will be saved here*
   - CP
     - *checkpoints of the trained model will be saved here*
   - *config file for the choosen model*