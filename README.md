# Sign-Language-Estimation-by-Tensorflow
Sign-Language-Estimation-by-Tensorflow
  
  
## Introduce  
Use Device : Logitech HD C310 Webcam  
Step 1:  
###Estimate ASL 1 to 9  
Demo Video: <https://youtu.be/TGZtH-XYFBk>  
  
I divide the webcam frame to two part:  
A detect right hand & detect left hand, and just detect right hand in this step.  
![readmeimg1](https://github.com/PohanYang/Sign-Language-Estimation-by-Tensorflow/blob/master/readme_img/cut2.png)  
Training data is 4013 RGB pictures in RGB color.  
Use tensorflow CNN model to build it.  
