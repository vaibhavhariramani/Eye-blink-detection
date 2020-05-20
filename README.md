# Eye-blink-detection
Eye blink detection with OpenCV, Python, and dlib
# Overview
In this we will find number of blinks occurs using the popular [dlib](http://dlib.net/) library

for further information checkout my blog: [Facial landmarks with dlib, OpenCV, and Python](https://sites.google.com/view/geeky-traveller/computer-vision/facial-landmarks-detection). 
 
# Requirements:

dlib, cv, imutils

# Link:
https://sites.google.com/view/geeky-traveller/computer-vision/facial-landmarks-detection

# Run:
Download the detector model [here](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2)
# Dependencies
You also need shape detector, you can download it by 
```
wget http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
```
 ## **Commands to run the detection:**
 ```
$ python detect_blinks.py --shape-predictor shape_predictor_68_face_landmarks.dat --image images/example_01.jpg

## **Results:**
The results are awesome. We can see pretty accurate Eye Blink detections.

![final_video_screencap](https://github.com/vaibhavhariaramani/hog--svm-vehicle-detector-and-Object-Detection/blob/master/images/final_bounding_boxes.png)

[Click here to watch the final video](https://youtu.be/YpYyPmpBJNU) with bounding boxes drawn around eyes.

# Resources 

To learn more about these Resources you can Refer to some of these articles written by Me:-

https://sites.google.com/view/geeky-traveller/computer-vision/facial-landmarks-detection

### Made with ❤️ by Vaibhav Hariramani
#### About me

I am an Actions on Google, Internet of things, Alexa Skills, and Image processing developer.
I have a keen interest in Image processing and Andriod development.
I am Currently studying at  Chandigarh University, Punjab.

You can find me at:-
[Linkedin](https://www.linkedin.com/in/vaibhav-hariramani-087488186/) or [Github](https://github.com/vaibhavhariaramani) .

Happy coding ❤️ .
