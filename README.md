# Introduction to Neural Networks
A small talk on Introduction to Neural Networks given to students of Technical University Nurnberg that introduces basic concepts of Neural Networks and then plays a fun exercise where we train the Chrome Browser's TRex game.

Inspired from [this](https://github.com/asingh33/SupervisedChromeTrex/blob/master/README.md) implementation of the same game that was created to work on a Mac.

This version works on Linux and uses the following libraries - 

Key Requirements:
Python 2.7.13
OpenCV 2.4.8
Keras 2.0.2
Theano 0.9.0
pynput
pyscreenshot
pykeyboard
PIL

# Usage

The primary entry point is main.py which gives you three options - 

1. To play the game using the pre-trained model
	This may not work for everyone because in my experience the screenshot size is very important and might depend on the screen where the game runs. As a result, I created a self-explanatory tutorial using a Jupyter notebook that the students could execute as we move along
2. To train the model using the images present in the 'imgfolder-new' path
3. To create a training dataset that captures screenshot images whenever you press the Up arrow key (JUMP) and Right arrow key (NOJUMP)
	Please note to change the settings of the screenshot to be captured specifically for your display

The trained model itself proved to be very large to be uploaded directly to git and I had to use Git Large File System - so you should be able to download using the link in modelParameters.hdf5 in this repo.

# Slides

The slides used for this short talk are also available in PDF and PPT format.

All comments, feedback and improvements are welcome.