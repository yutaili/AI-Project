# AI in Social Science Application_Final Project
Group member: Yutai Li, Coco Yu

## Project Sketch
In this project, we aim to build machine learning models to classify facial images into seven categories (i.e., emotions)—anger, disgust, fear, happiness, sadness, surprise and neutral. Recognizing the limitations of conventional FER algorithms’ subject dependency by virtue of illumination variation, the current project is aimed at examining the efficacy to improve model performance by using color-scale images as input features, in comparison to conventional gray-scale ones.

## Data Source
Facial Expression Recognition Challenge Dataset: https://www.kaggle.com/datasets/debanga/facial-expression-recognition-challenge \
MMA Facial Expression Dataset: https://www.kaggle.com/datasets/mahmoudima/mma-facial-expression

## Environment
All files were run on Google Colab with a GPU instance.

## File Descriptions: 
<a href="https://github.com/yutaili/AI-Project/blob/main/Color%20Image%20Processing.ipynb">`Color image Processing.ipynb`</a>: transfer the color image dataset into image array and store in .json or .csv file. <br>
<a href="https://github.com/yutaili/AI-Project/blob/main/FER%20Project.ipynb">`FER Project.ipynb`</a>: Data processing and initial model run file. Code has been included in other files as well. Please feel free to skip.<br>
<a href="https://github.com/yutaili/AI-Project/blob/main/FER_Project%20(1).ipynb">`FER_Project(1).ipynb`</a>: Model training and model evluation file. Confusion Matrices and data visualizations are included in this file. <br>
<a href="https://github.com/yutaili/AI-Project/blob/main/FER_Project.ipynb">`FER_Project.ipynb`</a>: A copy of FER_Project(1).ipynb, please feel free to ignore. <br>
<a href="https://github.com/yutaili/AI-Project/blob/main/color.csv">`color.csv`</a>: color images that has been stored as (48, 48, 3) image arries in csv. <br>
<a href="https://github.com/yutaili/AI-Project/blob/main/test.csv">`test.csv`</a>: gray-scale test image array without truth labels.<br>
<a href="https://github.com/yutaili/AI-Project/blob/main/project%20sketch.docx">`project sketch.docx`<a/>: a sketch of the background, research question, and methods of the project. <br>
<a href="https://github.com/yutaili/AI-Project/blob/main/Color_training%20(1).ipynb">`Color_training (1).ipynb`</a>: Data processing and model training and validation for MMA dataset.

The raw image files, the .json files that store the color image array are not uploaded to the github repo because they are too large to upload. If the grading criteria requires to upload the data file, please contact any of the group members. 
