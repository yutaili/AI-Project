# AI in Social Science Application_Final Project
Group member: Yutai Li, Coco Yu

## Project sketch
In this project, we aim to build machine learning models to classify facial images into seven categories (i.e., emotions)—anger, disgust, fear, happiness, sadness, surprise and neutral. Recognizing the limitations of conventional FER algorithms’ subject dependency by virtue of illumination variation, the current project is aimed at examining the efficacy to improve model performance by using color-scale images as input features, in comparison to conventional gray-scale ones.

## File Descriptions: 
**Color image Processing.ipynb:** transfer the color image dataset into image array and store in .json or .csv file.
**FER Project.ipynb:** Data processing and initial model run file. Code has been included in other files as well. Please feel free to skip.
**FER_Project(1).ipynb**: Model training and model evluation file. Confusion Matrices and data visualizations are included in this file.
**FER_Project.ipynb**: A copy of FER_Project(1).ipynb, please feel free to ignore. 
**color.csv**: color images that has been stored as (48, 48, 3) image arries in csv. 
**test.csv**: gray-scale test image array without truth labels.
**project sketch.docx**: a sketch of the background, research question, and methods of the project. 

The raw image files, the .json files that store the color image array are not uploaded to the github repo because they are too large to upload. If the grading criteria requires to upload the data file, please contact any of the group members. 
