# Food Sales Prediction Project
Data Science Bootcamp Project 1

**Author**: Susan Shin

### Goal:
The goal of this project is to build a model to predict outlet food sales using multiple regression models.


### Data:
The data includes sales by item by outlet location.
Metrics include MRP and Item Sales.
Attributes include Item Weight, Item Fat Content, Item Visibility, Item Type, Outlet Size, Location Type, and Outlet Type.


## Methods
- Data was preprocessed using column transfer and simple imputer pipelines.
  - Missing objects were filled using the most frequent occurance.
  - Missing numbers were filled using mean.
  
- Two models were run for this project: Linear Regression and a Regression Tree Model.
- After being tuned, metrics (RMSE and r^2) were compared to decide which model would be the recommended model.

## Results
- The Linear Regression Model resulted in a low R^2 score (around 50%) with a train RMSE score of $1,094.  
- The Regression Tree model was initially underfit and required tuning.
  - Once tuned, R^2 scores were 60%
### Here are examples of how to embed images from your sub-folder


#### Visual 1 Title
![sample image](project1_sample_image.png)

> Sentence about visualization.

#### Visual 2 Title

## Model

Describe your final model

Report the most important metrics

Refer to the metrics to describe how well the model would solve the business problem

## Recommendations:

More of your own text here


## Limitations & Next Steps

More of your own text here


### For further information


For any additional questions, please contact **email**
