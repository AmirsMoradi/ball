Green Ball Tracking with OpenCV

This project is a program to track a green ball using Python and the OpenCV and imutils libraries.
The program runs using a webcam (Camera) and draws the ball's path on the image.

Features

Detect green color in image (HSV color space)

Find largest green object in image

Draw circle around ball and its center point

Draw ball's path with consecutive lines

Can stop program execution by pressing q key


Installation and Setup
Cloning the Repository
git clone https://github.com/AmirsMoradi/ball.git
cd ball


Installing Prerequisites

Required libraries are defined in the requirements.txt file


Note:

Make sure your webcam is enabled before running.

To exit the program, press the q key.




Example Run

During program execution:

The green ball is marked with a yellow circle.

The center of the ball is shown with a red circle.

The path of the ball is drawn with red lines.




Future plans

Adding the ability to track multiple colors simultaneously

Saving video with the ball's trajectory

Optimizing speed for weaker systems



License

This project is released under the MIT License.



