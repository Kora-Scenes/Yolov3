# Yolov3

# Dataset Used:
    Pedestrian Detection Data set
  
  https://www.kaggle.com/datasets/karthika95/pedestrian-detection/download?datasetVersionNumber=1 

# Missing files:
    yolov3.weights
    
  https://pjreddie.com/media/files/yolov3.weights
  
# Dependencies:
  
    pip3 install -r requirements.txt
   
# Steps to run:
    
    Download dataset from link
    Download yolov3.weights from the link
    Pip install dependecies
    Create python3 virtual environment and run-  pip3 install -r requirements.txt
    
    
    iou.py -> to calculate iou for predicted boxes and ground truth
    
    Run these sequentially
    python3 yolov3_to_csv.py             This creates an output.csv of model predictions, save it in a different path
    python3 yolov3_to_csv_full.py        This opens ouput.csv and does mapping of persons in image predictions to ground truth
    python3 iou_seperate.py              To view the bounding boxes around each individual person in the image
    
    python3 iou_sampleBox.py             To view the iou mapping of each image
    
    Change image path wherever necessary to run locally from downloaded dataset
