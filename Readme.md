# Proposal for Data Challenge

**Patterns & Trends in Environmental Data / Computational Movement
Analysis Geo 880**

| Semester:      | FS22                              |
|----------------|---------------------------------- |
| **Data:**      | Roe Deer Movement Data           |
| **Title:**     | Prediction of future movement in Roe Deer        |
| **Student 1:** | Tim Fässler              |
| **Student 2:** | Gregory Biland                 |

## Abstract (50-60 words)

## Research Questions (50-60 words)
- What parameters are crucial for modeling and predicting deer movement patterns using an artificial neural network (ANN), and how much does the deers gender influence these models? (26 words)

- 

## Results / products
<!-- What do you expect, anticipate? -->

Based on the data and available data related to vegetation, a passable model that can moderate the next moving points with statistically reasonable accuracy is expected.

## Data
For this project we use the data set with the movement data of the deer which was provided. In addition, we will use data with vegetation information, either geodata from the canton of Zurich or the raster values from the Swiss "Arealstatistik". Which data will be used must first be compared with the literature on deer to know which vegetation has an influence on deer and how strong. 

## Analytical concepts
<!-- Which analytical concepts will you use? What conceptual movement spaces and respective modelling approaches of trajectories will you be using? What additional spatial analysis methods will you be using? -->

## R concepts
<!-- Which R concepts, functions, packages will you mainly use. What additional spatial analysis methods will you be using? -->

For this paper, the main focus will be set on using R, especially the "caret"- packege which includes data training functions, including methods for implying ANN's. Futhermore the 10- fold cross validation will be used for an optimal model selection, depending on the different parameters used in the algorithm. 

## Risk analysis
<!-- What could be the biggest challenges/problems you might face? What is your plan B? -->

The biggest problem in the approach of this paper will be the parameter selection and evaluation. As movement prediction is of great difficulty, it will be hard to determine how strong a parameter should be weighted and integrated in the model. The plan B, is to alter between different algorithms, such as the k-nearest neighbors - random forrest or decision tree algorithm. Additionaly the involvement of vegetation parameters can be altered.

## Questions? 
<!-- Which questions would you like to discuss at the coaching session? -->


