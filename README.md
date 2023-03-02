# Machine Learning Cycling Counter Predictions based on Urban Environment Characteristics

The code in this repository was created as part of Master's thesis and includes a notebook to extact a variety of built environment variables from a single coordinate pair. The variables are extracted from OpenStreetMap and Google Earth Engine and can be converted into numeric variables through the definition of a specific buffer size. 

The notebooks in the 'models' folder include code to use these built environmental variables in combination with observed cycling counts at the given location to model the relationship between the two. This is done using Linear Regression, Random Forest, XGBoost and SVM models. The outcomes are then ablet to be illustrated using the 'generating figures' notebook. 
