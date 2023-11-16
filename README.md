# YOLOv8-Custom-Dataset-Image-Detection

image detection with YOLOv8 using a custom dataset (manual labeling).
YOLOv8 library and documentation : https://github.com/ultralytics/ultralytics

The dataset is in the form of images (.jpg) which were labeled with label-studio, containing 5 classes (painting, chair, sofa, plant, table).

how to run : 
1. just clone this github repo or download.
2. makesure path configuration on yolov8n.yaml is right.
3. run main.ipynb and you can set number of epoch according to your needs.
   ( my default is epoch=100 )
4. the latest training stages carried out will be automatically saved in runs/detect.
   **ps : my latest training run is runs/detect/train5 , which has 0.6597 precision.**
5. if you want to test the training results, use detect-image.ipynb for testing images and detect-videos.ipynb for detection testing with video.
6. to carry out testing with the latest and best training results, move the 'best.pt' file from the latest training folder carried out. and copy the path as a testing model.
   **ps : my current best.pt is from runs/detect/train5
**
