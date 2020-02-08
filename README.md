# This code is from https://www.cnblogs.com/shouhuxianjian/p/10567201.html

Because it is Chinese , I just try to translate it in English..

# Environmet:
*1. python3.5.6
*2. keras 2.2.4；\n
*3. tensorflow-gpu 1.12.0. 

 
# Example 1 yolov3_darknet_to_keras
```
python yolov3_darknet_to_keras.py -cfg_path text.cfg -weights_path yolov3.weights -output_path yolov3c_d2k.h5
```
Result:

<img src="https://github.com/YuXiuChen/Darknet-yolov3.cfg-and-yolov3.weights-transform-to-keras.h5/blob/master/darknet_to_keras.png" width="40%" height="40%">

<img src="https://github.com/YuXiuChen/Darknet-yolov3.cfg-and-yolov3.weights-transform-to-keras.h5/blob/master/darknet_to_keras_2.png" width="40%" height="40%">

# Example 2: keras_to_yolov3_darknet

```
python yolov3_keras_to_darknet.py -cfg_path text.cfg -h5_path yolov3c_d2k.h5 -output_path yolov3c_d2k_k2d.weights
```
<img src="https://github.com/YuXiuChen/Darknet-yolov3.cfg-and-yolov3.weights-transform-to-keras.h5/blob/master/keras_to_yolov3_darknet.png" width="40%" height="40%">
