# Data-Analysis-of-House-Sales-in-King-County-USA
This Jupyter Notebook File is built to determine the market price of a house given a set of features as well as analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on.
<br>
<br>1: Display the data types of each column.
<br>2: Drop the columns "id" and "Unnamed: 0" from axis 1 then obtain a statistical summary of the data.
<br>3: Count the number of houses with unique floor values, and convert it to a dataframe.
<br>4: Determine whether houses with a waterfront view or without a waterfront view have more price outliers using the function boxplot in the seaborn library.
<br>5: Determine if the feature sqft_above is negatively or positively correlated with price using the function regplot in the seaborn library.
<br>6: Fit a linear regression model to predict the 'price' using the feature 'sqft_living' then calculate the R^2. 
<br>7: Fit a linear regression model to predict the 'price' using the list of features: 
<br>features = ["floors", "waterfront", "lat", "bedrooms", "sqft_basement", "view", "bathrooms", "sqft_living15", "sqft_above", "grade", "sqft_living"]
<br>8: Use the list to create a pipeline object to predict the 'price', fit the object using the features in the list features, and calculate the R^2.
<br>9: Create and fit a Ridge regression object using the training data, set the regularization parameter to 0.1, and calculate the R^2 using the test data.
<br>10: Perform a second order polynomial transform on both the training data and testing data. Create and fit a Ridge regression object using the training data, set the regularisation parameter to 0.1, and calculate the R^2 utilising the test data provided.
