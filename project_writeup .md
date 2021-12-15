# classification model to classify stars category  :
___
> - In this project my task was to get a dataset to build a classification model to classify stars category ,
I chose to analyze a dataset obtained from a kaggle that contains several features of Stars.
The dataset will be obtained from the website below the dataset contains 39553 rows and 7 columns .
> - KAGGLE Website <a href="https://www.kaggle.com/vinesmsuic/star-categorization-giants-and-dwarfs?select=Star39552_balanced.csv"> Data Source</a>

___
# Data description:
### Feature:
> - Vmag:Visual Apparent Magnitude of the Star.
> - Plx:Distance Between the Star and the Earth.
> - e_Plx:Standard Error of `Plx`.
> - B-V:B-V color index.
> - SpType:Spectral type.
> - Amag:Absolute Magnitude of the Star.
> - TargetClass:Whether the Star is Dwarf (0) or Giant (1).

 # Tools:
___
> - Jupyter.
> - Matplotlib.
> - Seaborn.
> - Pandas.
> - sklearn.
> - numpy.
> - pickle.


___
## Goals

> -Build a classification models to predict stars category

> -Choose the model that give us the best predict. 

___

___
## EDA
1- Removing Null 
2-Removing duplicate rows 
3-Removing outliers
4-Convert categorical data to dummies
___

___

## Conclusion
After building different models, svm and Logistic Regression give me the highest accuracy in both train and validation set. but Logistic Regression slightly better than svm .

___


___

## Future work:
> -Collect more data

> -Explore different models

> -Add additional  memory to solve memory error 

___


