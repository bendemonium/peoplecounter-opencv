# People Counter using OpenCV

People counters are employed pretty much everywhere to gauge the number of people in a given space, for business statisics or emergency security measures.

This is a direction sensitive people counter which tracks the number of people moving in and out of said space. It is a direct application of OpenCV and adopts pre-trained machine-learning models.

![image](https://user-images.githubusercontent.com/77619512/126186041-8b53faea-592b-4f7f-85e4-82de8a628963.png width="500" height="500")

This project is based on the people counter by PyImageSearch University, with a couple of changes.

# Running Instructions

Step 1: Download the prerequisites directory.
Step 2: Download the main program.
Step 3: Head on to the command line in the same directory as your downloads.

ON THE COMMAND LINE:

$ python people_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel

MORE OPTIONS:

--input : Optional input video file path. If no path is specified, your webcam will be utilized.
--output : Optional output video path. If no path is specified, a video will not be recorded.
--confidence : With a default value of 0.4 , this is the minimum probability threshold which helps to filter out weak detections.
--skip-frames : The number of frames to skip before running our DNN detector again on the tracked object.

# References

https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/
https://medium.com/secure-and-private-ai-writing-challenge/creating-a-direction-sensitive-people-counter-with-opencv-and-mobilenetssd-454627fe3c84
https://viso.ai/applications/people-counting-system/
https://data-flair.training/blogs/python-project-real-time-human-detection-counting/
