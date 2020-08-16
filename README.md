## Dance Pose Estimation Using PoseNet 

One of the many applications of Computer Vision is Pose Estimation.</br>
With the help of powerful machine learning model like PoseNet developed by Google team this made the task easier.</br>
With the help of captureStream method and MediaStream Recording API to capture canvas and record media.</br>
Using pretrained posnet model from tensorflow.js repository the pose of a dance video was captured.</br>


## GIF of the output 
![Alt Text](https://github.com/frh02/PoseNet_Dance/blob/master/Dance_Pose.gif)

## Steps to follow 

* Clone the repository</br>
* In case you want to use your own video, make sure to have the path as same as where you save this repository.</br>
* Open commandline and navigate to the folder of the downloaded repository.</br>
* Run the command <code>**python -m http.server 1337**</code>in the commandline, so as to create a local server on your local machine so as to host the HTML file.</br> 
* In a new chrome tab navigate to <code>**localhost:1337/index.html**</code> .</br> 
* If the FPS tab on the upper left corner is showing zero, refresh the page to load the model again.</br>
* Play the loaded video to observe the estimated pose.</br>
* Pause the video whenever you get the desired output and this will download a <code>**.WEBM**</code> file automatically.</br>
* For playing the <code>**.WEBM**</code>file drag it to a new chrome tab.</br>
* If there is more than one person then switch to multipose Estimation using the slidebar drawer in the right corner of the window. </br>


## Description 

* <code>*camera.js*</code> is used to generate a camera feed for recording the video and using SinglePose and MultiPose estimation for single and multiple person respectively.
* <code>*demo_util.js*</code> generates a canvas and plots the joints and lines for real-time human pose estimation.
* <code>*index.html*</code> creates a web page for running the model using local host server. 


## Result 

The result to this project is given in file <code>**Demo_Video**</code> in the name of <code>https://github.com/frh02/PoseNet_Dance/blob/master/Demo_Video/pose_estimated_dance.mp4</code>. </br>
