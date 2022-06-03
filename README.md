# Image-Classification-with-Tensorflow-tflite-on-Android-Studio
simple example creating image classification app on android studio using tensorflow lite model

Step per step
1. Create new file 
2. import tensorflow lite model to android studio (if use custom another model) File>New>Other>TensorflowLiteModel
3. copy activity_main.xml, MainActivity.java, AndroidManifest.xml to your file
4. if u use your custom another model u can coustomize "classifyImage" function on MainActivity.java by changing the variable by calling the new tflite file you are using and you must customize global variable "imageSize" on MainActivity.java by the image size you use in your tflite model
