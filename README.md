# YOLOUdacityDatasetObjDetSFLombard
Implement YOLO to detect objects like cars, pedestrians, and traffic lights.  Similar to Chris Gundling's yolo light github repository.
I modify it to include traffic light color classification and add another weight file for pedestrian detection for detecting pedestrians
closer to the ego car.

Instruction to run the YOLO object detection executable command: 
1)Before running the executable file, download the tiny-yolov2-udacity.tar.gz from this link: https://drive.google.com/file/d/0B2K7eATT8qRAY0g0aWhjdkw0bEU/view . Unzip the zip file and copy into the scripts/ckpt directory. We will use the checkpoint for our YOLO object detection. 
2) In the scripts directory in linux or ubuntu, type the executable command: ./YOLOobjectDetect and from windows anaconda prompt or linux or ubuntu prompt in the same directory type: jupyter notebook pedestrianDetection.ipynb. This command will produce YOLO object detection videos from the videos I took from the San Francisco Sunset District.

See my youtube link here:
https://youtu.be/_nxiYXDC4og
