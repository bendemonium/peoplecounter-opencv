# People Counter using OpenCV

People counters are employed pretty much everywhere to gauge the number of people in a given space, for business statisics or emergency security measures. <br />

This is a direction sensitive people counter which tracks the number of people moving in and out of said space. It is a direct application of OpenCV and adopts pre-trained machine-learning models. <br />

![image](https://user-images.githubusercontent.com/77619512/126187899-7ebe3b97-308b-4165-b067-775d25f7c010.png)

This project is based on the people counter by PyImageSearch University, with a couple of changes.

# Running Instructions

Step 1: Download the prerequisites directory. <br />
Step 2: Download the main program. <br />
Step 3: Head on to the command line in the same directory as your downloads. <br />

ON THE COMMAND LINE:

$ python people_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel

MORE OPTIONS:

--input : Optional input video file path. If no path is specified, your webcam will be utilized. <br />
--output : Optional output video path. If no path is specified, a video will not be recorded. <br />
--confidence : With a default value of 0.4 , this is the minimum probability threshold which helps to filter out weak detections. <br />
--skip-frames : The number of frames to skip before running our DNN detector again on the tracked object. <br />

# References

https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/ <br />
https://medium.com/secure-and-private-ai-writing-challenge/creating-a-direction-sensitive-people-counter-with-opencv-and-mobilenetssd-454627fe3c84 <br />
https://viso.ai/applications/people-counting-system/ <br />
https://data-flair.training/blogs/python-project-real-time-human-detection-counting/
