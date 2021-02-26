# Hackerearth_Deep_Leraning: 'Tis STILL the season to be jolly

## Problem statement

An e-commerce platform is getting all geared up for a season clearance sale and plans to leverage social media as the primary channel to reach their audiences. 
The campaign’s target group are individuals/families that have recently posted a picture of their indoor Christmas decor or are traveling during the holidays. 

## Task

You work at a leading social media platform and your team has been tasked to build a product recommendation engine for consumers. As part of the development team, 
your role is to use Deep Learning to develop a model that classifies images based on elements within the picture. These elements should be related to decor or 
holiday season vacations, such as a snowman, a Christmas tree, flights, and the like.

## Dataset

The dataset consists of over 6000 images.The data folder consists of two folders and one .csv file. The details are as follows:
train: Contains 6469 images for 6 classes
test: Contains 3489 images
train.csv
You are given the following six categories. You are required to classify the images in the dataset based on these categories.

Miscellaneous
Christmas_Tree
Jacket
Candle
Airplane
Snowman

## Evaluation metric
Score = 100*f1_score(actual_values, predicted_values, average='weighted')

## Submission format
You are required to write your predictions in a .csv file and upload it.
