# HarryPotterCloak
Harry Potter invisibility cloak with the help of OpenCV and Python

Special thanks to Steve Nouri from whom I got the idea and guidance.

The logic is very simple. I am extracting each frame of the video, with the help of segmentation. I separate the background and foreground of the image. I replace the foreground of a particular color with the background which gives the illusion of getting disappeared.

The workflow of this project will be:

1. Importing needed libraries and generate the output video
2. Recording and caching the background for each frame.
3. detecting the red portion in each frame
4. Replacing the red portion with a mask image in each frame
5. Producing the surprising output
