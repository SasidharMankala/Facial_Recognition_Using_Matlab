# Facial_Recognition_Using_Matlab
Facial recognition using MATLAB


First step of making this project done is to creating a Database. 
Using the file 'imagecapturing.m' create a database 
Add a folder named database(whatever name you wanted) and create subfolders with the names of the persons where the images are going to be added in.
Now run the code of the file ImageCapturing.m in the folder you wanted to add images.
Let me explain this step clearly
  Take the example as the database I provided 
    I have made 2 database named Raju and Sasidhar
    If I want to add my images as my name is Sasidhar I have to be in that folder in Matalab, you can see it in the current folder section
    So I have to navigate to the folder named Sasidhar in Database and run the code there so the images captured will stored there
    For running the code there you need to copy the file in the database subfolders but for alot of databassubfolder it is not ideal
    So you can navigate to the subfolder and open a new script without saving it paste the code and select the code and right click you can see evalutate selected
    This will create the database
   
Now traning part just verify that the name of the database main folder that I mentioned to use whatever you want in the 7th line same as the name in the 'traning.m' file
Then you are good to go. This process may take a while according to your device specifications
After done with training run the 'imageverification.m' file this will give you the output as the name of the person and if there is no face detected it will promt as No Face Detected


NOTE:
Make sure you are in well lit environtment while creating database
The code that provided is working fine for only 2 people if you wanna add more people database just change the training.m file's 5th line from fullConnectedLayer(2) to fullConnectedLayer(3)
Untill training it works fine later that while verification you may get some errors which I didn't verified the errors
If you are able to figure out the error please let me know
Credit: https://www.youtube.com/watch?v=BU4NHgxPyLE&list=PLvBx-4zpF8TA9UR6PVrpzPTxKYomU__KY&index=4&t=4s
