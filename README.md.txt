Requirements Check: check the requrements file first.

Runinng the program.

1- open Testing.ipynb file
2-run the code
at the intialization of variable classifier replace the existed path with your actual path of Keras_model.h5
#classifier = Classifier("C:/Users/20109/OneDrive/Desktop/Rudy/Sign-Language-detection/Model/keras_model.h5" , "Model/labels.txt")

#replace C:/Users/20109/OneDrive/Desktop/Rudy/Sign-Language-detection/Model/keras_model.h5 with your actual path of Keras_model.h5 at your disk.

Handling Labels:

#leave "Model/labels.txt" as it is.
variable labels represent the words in the file labels.txt at the Model Folder, if there any trouble and error msg said "out of index" just go to labels.txt and identfy the list correct with right index at labels.txt.
# just example: if labels.txt has this:
0 Bed
1 Child
2 Cigarette
3 Drink
the list should be like this:
labels=["Bed","Child","Cigarette","Drink"].
and so on.

3- the webcam wil open.

Testing the program:
you will test the program on already traind data and the tarind file at folder Model under name "Keras_model.h5".

If you want to exit enter "q" from keyboard.

#Creating Your Own Data

1-open file CollectingData.ipynb

2-creat a new folder Data and inside Folder Data add another folder to represent a word.

3-at the intialization of variable folder replace the existed path with your actual path of the folder of your word.

#example 
folder = "C:/Users/20109/OneDrive/Desktop/Rudy/Sign-Language-detection/Data/Yup"
i added the path of my folder yub that i want to add frames in it.
so replace it with your actual path.

4-the camera will open and you will be taking frames py pressing "s" at the keyboard. and the counter will show you how many frames you took.
#if you want to exit enter "q" from keyboard.

5- to train the data you just collected, open Teachable Machine open-source site, this is the link:https://teachablemachine.withgoogle.com/train/image 

and add your data, each class at the site represent the folder that represent word in sign language, and upload the frames. 

6- train your model, after the site train your data there will be a file, extract it and added it to the Model folder.