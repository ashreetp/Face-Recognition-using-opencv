# Face-Recognition-using-opencv

A Face Recogniser recognize face using HaarCascade and detect faces

## Instructions:
Requirements:

	1) openCV-python
	2) opencv_contrib_python
	3) numpy

Note: 1) while training image,input the name in quotes. i.e,, example Enter your name : 'Ashreet'
      2) Must create a folder name "people_folder"
      
### You get 3 options:

## 1) Add a new face to the dataset of known people :
  
## 2)  This option is for live recognition:

## 3) Finally on pressing 3, the exe file stops and you exit!:

  

_______________________________________________________________________________________________________________________________________



## How does it work :question:

### 1) It takes in 20 images per face(person). :camera:
  
   i) Finds the face in the frame using a HAAR cascade. <br />
  ii) Trims the unnecessary parts of the face. <br />
 iii) Does histogram equalization and resizes the images to 100 x 100. <br /><br />
 
 These images are saved in the current working directory
 ### 2) For live recognition: :+1:
   i) Creates a LBHP face recogniser and trains it on the existing dataset. <br />
   ii) Finds faces in live video stream, does the same pre-processing as point 1. <br />
  iii) Finds the face in our dataset with the closest likeness to the current face within a certain threshold. <br />
   iv) Displays the face along with the name of the person and draws a rectangle around their face.<br /><br /><br />
