# Camera Calibration

## 1. Download the calibration [file](http://wiki.ros.org/camera_calibration/Tutorials/MonocularCalibration?action=AttachFile&do=get&target=check-108.pdf) and print it.

## 2. Open the usb camera

### 2.1 Open a terminal and run:

```
$ roslaunch usb_cam usb_cam-test.launch
```

## 3. Open the calibration windows

```
$ sudo apt install ros-melodic-camera-calibration
$ rosrun camera_calibration cameracalibrator.py --size 8x6 --square 0.0245 image:=/usb_cam/image_raw camera:=/usb_cam
```

## 3. Move the calibration sdsd until the CALIBRATE become green and click it.

## 4. Click the COMMIT
