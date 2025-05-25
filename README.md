# HeinLab_VideoPipeline
Video data filtering pipeline for Hein Lab of Computational Ecology at Cornel

**Tianyi Chen, January 2025**

Objective: Program for Abigail Grassick, Phd student at Hein Lab of Computational Ecology at Cornell University.
This program will be utilized to sift through thousands of clips of marine video data within zip files. The program will extract and filter the most accurate video data to train a computer vision model. 

The program will:

**Part 1**
1. Asks for then accesses a Zip File. Precondition: Zip File is filled with valid video files, all of which are titled (not untitled).
2. Sorts videos by length (largest file size to smallest file size).
3. Assigns index numbers to each video by creating a dataframe of video title to corresponding index number.
4. Creates a list with the 20 longest video *titles*.
5. Selects a random 20 videos from the remaining videos (not 20 longest).
6. Appends the 20 randomly chosen video *titles* to the list.

The returned list will be a list of 40 video *titles*

**Part 2**
1. Create a new folder and put those video files in it
2. Asks for user input for folder name
