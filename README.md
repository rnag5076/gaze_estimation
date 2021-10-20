# gaze_estimation
Computer Vision technique helps to trace the position of pupil as well as perform blink detection on pre-recorded videos.

#### Features
 - Gaze Estimation System can be used in tracking pupil and estimating the number of blinks. 
 - This is beneficial for people who cannot speak or use their hands to communicate.
 - It can be useful in identifying diseases such as Parkinson's Disease etc.

#### Under the hood
 - OpenCV library is used for capturing the video through webcam and reading the frames as well as finding contours on it to analyze the area occupied by pupil.
 - Gaussian blur is used to blur the frames to improve detections and we tried to binarize the frames.
 - We also tried to calculate the aspect ratio of eyes through opencv functions.

#### OUTPUT VIDEO FRAME SAMPLE

<img src="https://github.com/rnag5076/gaze_estimation/blob/main/sample.jpg" width="650" height="315">
