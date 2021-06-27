# Volume-Controller-using-OpenCV

 This project is simiar to Hand-gesture-recognition but it can do something more than the former one, I used the gestures to control the volume of the system or a media player.
 
 ## [Image_Generator.py](https://github.com/Annamalaisaravanan/Volume-Controller-using-OpenCV/blob/main/Image_Generator.py)
 Using this code, you can generate the colored dataset on your own. Gestures that are shown inside the ROI box can be stored by pressing the respective class button(say 0 or 1 or 2) in the keyboard.
 
 ## [Model_training.ipynb](https://github.com/Annamalaisaravanan/Volume-Controller-using-OpenCV/blob/main/Model_training.ipynb)
 Seeing this notebook will let you the clear cut idea of how training has been done. Image dataset was feed to the 8-layer CNN Sequential Model. I used [adam](https://keras.io/api/optimizers/adam/) optimizer and my loss function is [Categorical_crossentropy](https://keras.io/api/losses/probabilistic_losses/#categoricalcrossentropy-class) because i have three classes at the output.
 
 
 ## [app.py](https://github.com/Annamalaisaravanan/Volume-Controller-using-OpenCV/blob/main/app.py)
 Here the Real-time predictions are made using OpenCV. After making the predictions of which class the hand gesture belongs, Using pyautogui respective buttons are pressed via software command which triggers the required action we need.  
     
