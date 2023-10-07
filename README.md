# Sales Prediction Using Python
![](https://miro.medium.com/v2/resize:fit:1000/1*OB6ODKHJN_IfS2IC3rIlQg.png) 


## Author: Md Mahfooz Alam Ansari
## Batch: September
## Domain: Data Science

### Aim

The aim of this project is to predict sales based on advertising expenditure using the given dataset. The dataset contains information about advertising spending on different platforms (TV, Radio, and Newspaper) and the corresponding sales amount.

### Libraries Used

The following important libraries were used for this project:

- `numpy`
- `pandas`
- `matplotlib.pyplot`
- `seaborn`
- `sklearn.model_selection.train_test_split`
- `sklearn.linear_model.LinearRegression`

### Dataset

The dataset was loaded using pandas as a DataFrame from the file "advertising.csv."

### Data Exploration and Preprocessing

- The shape and descriptive statistics for the dataset were displayed using `df.shape` and `df.describe()`.

- A pair plot was created to visualize the relationship between advertising expenditure on TV, Radio, Newspaper, and sales using `seaborn.pairplot`.

- Histograms were plotted to observe the distribution of advertising expenditure on TV, Radio, and Newspaper using `matplotlib.pyplot.hist`.

### Correlation Analysis

- A correlation matrix heatmap was plotted to observe the correlation between advertising expenditure on TV, Radio, Newspaper, and sales using `seaborn.heatmap`.

### Model Training

- The data was split into training and testing sets using `train_test_split`.

- A linear regression model was trained on the training data using `sklearn.linear_model.LinearRegression`.

### Model Prediction

- The model was used to predict sales based on advertising expenditure on TV for the test set using `model.predict(X_test)` and the corresponding advertising expenditure on TV in the test set.

- The model coefficients and intercept were obtained using `model.coef_` and `model.intercept_`.

- The predictions and actual sales values were plotted using `matplotlib.pyplot.plot` and `matplotlib.pyplot.scatter`.

For further details and code implementation, please refer to the project files and code documentation.

### Contact

If you have any questions or need further assistance, feel free to contact the author, Md Mahfooz Alam Ansari.

Thank you for using the Sales Prediction Using Python model!
