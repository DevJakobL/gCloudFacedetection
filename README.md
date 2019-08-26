# gCloudFacedetection
1. Install the requirements

2. Download the wieder-face data set from [here](http://shuoyang1213.me/WIDERFACE/) and save them in ./data 

3. Prepare the wieder-face data set for the object detection API.
```
python data/wider_to_tfrecord/wider_to_tfrecord.py 
```
4. [Using object detection API] (https://github.com/DevJakobL/gCloudFacedetection/blob/master/object_detection/README.md)   

5. Download my trained models from [Google Drive](https://drive.google.com/open?id=1Y0DnhJiIRuHLa-S3qd1jhoO0_wfLE6Az) to play with that.