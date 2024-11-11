Fluorescent Microscope Image Analysis

This repository contains Python code for analyzing fluorescent microscope images to measure green fluorescence intensity, which can be used to assess neuroinflammation levels. This analysis can be performed using sample images and the code provided here, which is designed to run in Jupyter Notebook.

Repository Contents
Code for Image Analysis: Code to upload, quantify, and analyze images for green fluorescence intensity, along with plotting functions for visual comparison of different image groups.
Sample Images: A compressed .zip file containing sample images for testing the code.
Instructions: Step-by-step guide on running the analysis in Jupyter Notebook.
Getting Started
Clone this repository or download it as a .zip file.
Extract the sample_images.zip file to access sample images.
Open the Jupyter Notebook and run each code cell step-by-step.
How to Run the Code
Part 1 - Single Image Analysis:
Use the file upload widget to select a sample image.
The code will display the uploaded image alongside its green fluorescence channel and print the total green intensity.
Part 2 - Batch Image Analysis:
Set the image_directory variable to the folder containing your sample images.
Run the batch analysis code to calculate and display the green fluorescence intensity for each image.
Quantified data will be displayed in a table, showing intensity for each file.
Data Grouping & Statistical Analysis:
Organize the images into groups based on user-defined criteria.
Compare fluorescence intensity between groups using statistical tests such as ANOVA and t-tests.
Dependencies
This code requires the following Python libraries:

cv2
numpy
matplotlib
pandas
scipy
Example Output
The code provides visual output for each image’s green fluorescence channel, group bar charts, and statistical test results to help interpret the data.
