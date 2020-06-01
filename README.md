# super_dino_automated
this is a super Dino ---> the automated Dino. 

 ----------DISCRIPTION-----------
 
🦕🦕🦕🦕🦕🦕🦕🦕🦕


This is a simple python bot that plays Chrome Dino Game without user interaction .

 Here i'm not using any machine learning or artificial intelligence to counter this problem
 but i'm using simple image/screen processing.🎇
----------------------------------------------------------------------------------------------------------------------------------------

 We will work with Pyautogui and PIL (Python Imaging Library) for implementation.
 
 This project is very basic and consists of only about 50 lines of code but its result will make you surprise.

Some libraries used are: 
PIL : Python Imaging Library (PIL) is a free library for the Python programming language that adds support for opening, manipulating, and saving many different image file formats.

Pyautogui : PyAutoGUI is a Python module for programmatically controlling the mouse and keyboard without any user interaction.

Time : Python “Time” Module which allows us to handle various operations regarding time, its conversions and representations, which find its use in various applications in life.

Numpy :NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, 
along with a large collection of high-level mathematical functions to operate on these arrays.

------------------ALGORITHM----------------------

Click on the restart button using Pyautogui library using “ ISCOLLIDE ” coordinates.

Calculate the sum of all white pixels values present in the box in front of Dinosaur.

If the sum of pixels values present at any time in the box becomes less than the sum of white pixels values, it means either “bush” or “bird” is coming. 
So either we have to make our Dino jump or bend down.

In order to protect Dino from “Bush”, we make a jump.

In order to protect Dino from “Bird”, we always keep our Dino down. 
