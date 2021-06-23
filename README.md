# Draw on Screen

## Introduction

This project aims to draw/color anything on the screen depending on the color of the object used.

## Dependencies

* [Python 3](https://www.python.org/)
* [OpenCV](https://opencv.org/)
* [Numpy](https://numpy.org/)

If you dont have Python installed in your PC ,it can be installed from here [python](https://www.python.org/downloads/).

Hit the command in CMD/Terminal if you don't have it already installed:

    pip install opencv-python

   (OR)
   
 Install OpenCV via anaconda
  
    conda install -c menpo opencv
    
## How to run the code
Clone the Repository and extract the files

1. Go to the folder where main.py file is present
2. Type cmd in the file path 
3. Run the code with command `python main.py`
4. Wait for the terminal to load up and start drawing!

## Steps

* First, we need to get the hsv color ranges for the colored object that you want to draw with. Use my trackbar for tuning the values and note down the values in the main file.

* We need to find the Contours around the object and get only the tip of the object( say for example the tip of the pen)

* To generate the lines/points, simply open a for loop and iterate through and print the points (x,y). You can print it as a circle, square anything! I've used a circle here.

* After you've had enough fun, press q to exit the window.

## Example Output

![Estimated Score](Faceblur.png)
