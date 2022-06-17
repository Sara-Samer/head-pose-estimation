# Head Pose Estimation
In this [notebook](https://colab.research.google.com/drive/1aeiQp6tqTvjpx6A7yLeVCWn_QWVc71ip?usp=sharing) I try to build three models that predict the `YAW`, `PITCH` and `ROLL` angles of the head
at the start of the notebook we'll download the AFLW2000 dataset and save it to our drive
this notebook consists of two parts
1. Using dlib to predict the angles
2. Using MediaPipe to predict the angles
## dlib
dlib accuracies were not the bes case and resulted in a video with a lot of errors

https://user-images.githubusercontent.com/36432332/174283743-de0cd811-a44b-493f-aabc-6a013b842332.mp4

## MediaPipe
After converting the data to mediapipe points instead of dlib points the accuarcies improved significantly as we can see here


https://user-images.githubusercontent.com/36432332/174283972-0a48bada-f38c-4fbe-ae95-8190505ec201.mp4

