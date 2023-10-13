# SIHOBJECT
git clone https://github.com/HanumanTheHacker/SIHOBJECT.git
cd YOLOv8-DeepSORT-Object-Tracking
pip install -e .[dev]
cd ultralytics/yolo/v8/detect
https://drive.google.com/drive/folders/1kna8eWGrSfzaR6DtNJ8_GchGgPMv3VC8?usp=sharing
After downloading the DeepSORT Zip file from the drive, unzip it go into the subfolders and place the deep_sort_pytorch folder into the yolo/v8/detect folder
ultralytics/yolo/v8/detect - insert a test3.mp4 file here name should be same
same directory just run - python predict.py model=yolov8l.pt source="test3.mp4" show=True 
