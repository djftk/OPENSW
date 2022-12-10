# OPENSW Open the webcam with OpenCV and recognize and mosaic the eyes
> Mosaic Handler with OpenCV and Python. This project is inspired from his blog: [blog](https://jinho-study.tistory.com/231)
We have included the author's code and the one we wrote my self as well.

# Key Points 
<step>
1. Open labtop webcam to run 
2. Crop the image after detecting eye image
3. Collapse the cropped eye image
4. Zoom in on the cropped eye image
5. Mosaic the detected eye image and display it on the webcam.
6. Outputs the number of detected eye areas at the same time.

# Requirements: (woth versions i tested on)
1. python (3.7.4)
2. opencv (4.6.0)
3. numpy(1.21.6)
4. haarcascade_eye.xml

# Commands to run the detection:
python eyes_mosaic.py

# Results & Limitations :
When you touch your face to the webcam screen, 
it automatically recognizes your eyes and mosaic them.
In some cases, the mouth is recognized when speaking 
with the mouth open. Even if you wear a mask, 
you can only recognize your eyes.
![result](https://user-images.githubusercontent.com/113023190/206858506-8933faf7-13eb-4530-b0b5-1dbcdf52d987.png)


