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
- What parameters are crucial for modeling and predicting deer movement patterns using an artificial neural network (ANN), and how much does the deers gender influence these models?

- Does the articifical neural network differentiate significantly between the deers movement in different kind of landscape spaces, for example forest vs on an open grass field.

## Results / products
<!-- What do you expect, anticipate? -->
Based on the data and available data related to vegetation, a passable model that can moderate the next moving points with statistically reasonable accuracy is expected. Depending on how well we can include the the actual real world landscape into the model, the predicted movement might result in unrealistic movements (e.g. movement through water bodies or through a town).

## Data
For this project we use the data set with the movement data of the deer which was provided. In addition, we will use data with vegetation information and/or other landuse, either geodata from the canton of Zurich or the raster values from the Swiss "Arealstatistik". Which data will be used must first be compared with the literature on deer to know which vegetation / type of landscape has an influence on deer and how strong. 

## Analytical concepts
<!-- Which analytical concepts will you use? What conceptual movement spaces and respective modelling approaches of trajectories will you be using? What additional spatial analysis methods will you be using? -->

With our approach the amount of analytical concepts connected to movement will be rather small as the idea of the artificial neural network is that it finds those movement patterns and models of trajectories itself. It will be interesting to then analyse the results of the predictions depending on the parameters to see if there are any to us known concepts of movement or trajectory modelling. 

## R concepts
<!-- Which R concepts, functions, packages will you mainly use. What additional spatial analysis methods will you be using? -->

For this paper, the main focus will be set on using R, especially the "caret"- packege which includes data training functions, including methods for implying ANN's. Futhermore the 10- fold cross validation will be used for an optimal model selection, depending on the different parameters used in the algorithm. 

## Risk analysis
<!-- What could be the biggest challenges/problems you might face? What is your plan B? -->

The biggest problem in the approach of this paper will be the parameter selection and evaluation. As movement prediction is of great difficulty, it will be hard to determine how strong a parameter should be weighted and integrated in the model. The plan B, is to alter between different algorithms, such as the k-nearest neighbors - random forest or decision tree algorithm. Additionaly the involvement of vegetation parameters can be altered.

## Questions? 
<!-- Which questions would you like to discuss at the coaching session? -->

- Are there any more variables you can think of other than the landscape type that impacts the deers movement which could be implemented into the ANN? 
