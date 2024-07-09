# Shrec 2024: Recognition of hand motions molding clay (Baseline: Modified DD-Net)
This repository contains the baseline method for the SHREC 2024 track: "Recognition of hand motions molding clay" which is a customized version of DD-Net from [Fan Yang et al DD-Net](https://github.com/fandulu/DD-Net).

## Description (from [shrec.net](https://www.shrec.net/SHREC-2024-hand-motion/))
This contest will focus on trying to recognize different highly similar hand motions from a professional potter. Participants will try to recognize the hand motions from coordinate data of both potters hands. This track is made to see if hand recognition systems can recognize similar hand motions of two hands. These motions are all recorded using a Vicon system and pre-processed into a coordinate system using Blender and Vicon shogun Post.

## Dataset (from [shrec.net](https://www.shrec.net/SHREC-2024-hand-motion/))
We recorded hand motions of an experienced potter who sculpted the same pot with and without clay. We captured our data using a Vicon System containing 14 Vantage Cameras that will track reflective markers on the subject's hands. The motions are processed to be saved as a text file where each row represents the data of a specific frame with 28 coordinate floats (14 per hand) (x;y;z positions) of the markers.The dataset is split into a training and testing set (70/30). 

- **Centering** the clay.
- **Making a hole** in the clay.
- **Pressing** the clay to make it stick to the pottery wheel.
- **Raising** the base structure of the clay.
- **Smoothing** the walls.
- Using the **sponge** to make the clay more moist.
- **Tightening** the cylinder of the clay.

The ground truth is manually added based on the motions we have captured. The motion class can be found in the filename and folder.

[Data split (Train/Test)](https://www.shrec.net/SHREC-2024-hand-motion/Data/Data%20Split.rar) for the data split in a train and test set.

## To run:
Requires Skeletal coordinate data (for example the data used in this challenge).
Change Folder locations of the data.
Adjust Configuration class.

