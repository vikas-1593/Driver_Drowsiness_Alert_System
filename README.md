#Introduction

The project aims to alert the driver whenever he/she feels drowsi during the driving.
First this project uses OpenCV to detect the face of the driver using a webCam and then it extract eyes from it, and then apply machine learning algorithm called CNN to detect whether the eyes are closed or open and calculate Score.
If the eyes remained closed for certain duration and score exceeds a thresold value then it will alert the driver by buzzing the alarm.

The repositories contains 5 ipynb files out of which 4 are machine learning models namely CNN from scratch, VGG16, ResNet50 and InceptionV3.
To run the project, follow the following steps:
1 - Download all the files including the alarm.wav.
2 - Download the models from the google drive link:- https://drive.google.com/drive/folders/1jxj7FKOd58f1xmsRapseGztisxV0Fztv?usp=drive_link
3 - Either copy the model path.
4 - Open the main.ipyn file to run the project and change path of the model to the location where you have put the models in the load_model function.
5 - run all the cells.
6 - check the comments for the appropriate score values to run project smoothly different model give result on different score values.

Thank you.
