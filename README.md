# What drives the resale value of a used car?
The objective of this project is to identify the factors affecting the resale value of the used cars. A dataset of 426K records was used in the analysis to determine whether there is a relationship between factors such as the age of the car, manufacturer, condition, fuel type, transmission type, mileage, color, etc., and car resale value.

The top factors that impact the car price are the age of the car, number of cylinders, fuel type, mileage, drive type, and its condition.

The study had limitations that may be revisited in the future:
- There are a large number of records with missing values for some of the features. These values may be imputed by a smart imputation technique.
- The dataset could be enhanced by pulling data from publicly available data sources. For example, features such as gas mileage, number of doors, etc., can be pulled online using the car's model.
- The interaction between the variables should be revisited. The model with 2-polynomial features gave some promising results on the train sample.
- Building separate models for cars and trucks can also be considered.

You can find the Jupyter notebook in this location: https://github.com/SunaHafizogullari/BerkeleyMLCertificate-CarSalePrice/blob/main/prompt_II.ipynb
