# Sign-Language-Generation-From-Video-using-YOLOV5-master
ipynb created in colab
STEPS:

1. capture the images using camera for object detection : capture_image.py
2. label the images with labelImg.exe
3. create the directories: save the train and test data, data.yml class defination file
4. zip the test,train and class defination file
  
5. clone git "https://github.com/ultralytics/yolov5.git"  
6. travese to yolov5 directory
  - install the requrirements.
  - choose the suitable model.
  - load the custom dataset with yml
  - define model configuration and architecture
  - train custom yolo5 detector
  - Evaluate
    - ground truth training data
    - ground truth augmented training data
    - run inference with trained weights run inferecnce with pretrained checkpoint on new content/images
      - using test data
    display inference on all teset images.
  - Export trained weights for future inferences

