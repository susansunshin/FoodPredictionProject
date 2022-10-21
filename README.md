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
  - Once tuned, R^2 scores were 60% with an improved RMSE score
- Based on the above, the recomended model was the Regression Tree.

#### Sku Counts
![](https://github.com/susansunshin/FoodPredictionProject/blob/main/Sku%20Count.png)
> This graph shows the breadth and depth of the assortment at this particular chain of outlets
> 

#### Sales by Fat Content
![](https://github.com/susansunshin/FoodPredictionProject/blob/main/Fat%20Content.png)

> This visualization allows us to see how disparate the sales are between Low Fat and Regular items.
> The sales for these two types of products are relatively evenly split,


## Limitations & Next Steps
- There are limitations to this data as we do not know the specifics behind the attributes; particularly for the outlet types
- The next steps would be to understand location attributes so that we are better able to understand how to fill in missing values

### For further information

For any additional questions, please contact **susansunshin@gmail.com**
