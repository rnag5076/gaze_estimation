# gaze_estimation
Python program trying to estimate the position of pupil as well as perform blink detection on videos containing eye recordings.

#### Features
 - Gaze Estimation System can be used in tracking pupil and estimating the number of blinks. 
 - The system that this project came up with will be useful for security in a fixed restriction area.Therefore, the background of the targeted area is assumed to be non-moving and considerations of sudden change in lightings are ignored as well. 
 - The idea here is to compute the difference between two frames apply a threshold to separate the pixels that have changed from the others and display them.

#### Under the hood
 - OpenCV library is used for capturing the video through webcam and reading the frames as well as finding contours on it to analyze the area occupied by pupil.
 - Gaussian blur is used to blur the frames to improve detections and we tried to binarize the frames.
 - We also tried to calculate the aspect ratio of eyes through opencv functions.

#### OUTPUT VIDEO FRAME SAMPLE

<img src="https://github.com/rnag5076/gaze_estimation/blob/main/sample.jpg" width="375" height="315">
