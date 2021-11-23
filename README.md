# UROP_CV_HELMETDETECTION

## Install all dependencies

In the yolov5-master folder, use the following command to install all dependencies:

```bash
python3 -m pip install -r requirements.txt
```

## Try out the detector on photos:

Four trained weights from four iterations are available for testing.
In the yolov5-master folder, with env1 activated, use this command:

```bash
python detect.py --source test.png --weights yolo5s.pt --img 640
```
![alt text](https://github.com/Chenanism777/UROP_CV_HELMETDETECTION/blob/main/test_batch0_labels.jpg?raw=true)

## Try out the detector on YouTube videos:

In the yolov5-master folder, with env1 activated,to analyze the youtube video properly, install 2 packages

```
pip install pafy
pip install install youtube-dl==2020.12.2
```

Then use this command:

```
python detect.py --source 'https://www.youtube.com/watch?v=oHEWcefPWws' --weights yolo5s.pt
```
![alt text](https://github.com/Chenanism777/UROP_CV_HELMETDETECTION/blob/main/video_test.jpg?raw=true)

## Try out the detector on camera streaming:

In the yolov5-master folder, with env1 activated, use this command:

```
python detect.py --source 0 --weights [weight_name].pt
```


