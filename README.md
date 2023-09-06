# yolov8-object-tracking
#### Implementation of Yolov8l tracking with tflite in C++


### Phase:
currently make yolov8l tracking integrated with quantized tflite pretrain(finished)
then converst everythiong to C++ to achieve faster speed

### Features
- Object Tracks
- Different Color for every track
- Video/Image/WebCam/External Camera/IP Stream Supported

### Coming Soon
- Selection of specific class ID for tracking
- Development of dashboard for YOLOv8

### Steps to run Code

- Clone the repository
```
https://github.com/yide1235/Yolov8-tracking-tflite-CPP.git
```

### Results
Initial result using yolov8l quantized tflite pretrain model for stereo images:
![](./assets/sheared_image11.jpg)
![](./assets/sheared_image22.jpg)
![](./assets/sheared_image1.jpg)
![](./assets/sheared_image2.jpg)


### References
- https://github.com/abewley/sort
- https://github.com/ultralytics/ultralytics
- https://github.com/RizwanMunawar/yolov8-object-tracking.git
