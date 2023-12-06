# Training-Linear-Regression
Regression Task over "Tourist Behavior Dataset"- Training Linear Regression

#Abstract
This project focuses on analyzing and predicting Season-Wise Long-term travel Spots using a dataset containing information about tourist behavior. 
The dataset, initially comprising 36,547 entries across 7 features, required careful preprocessing to handle missing values. 
After cleaning, 12,016 entries remained for further analysis.

The primary objective was to develop a predictive model using Linear Regression to forecast the total path count of tourists visiting these spots. 
The model was trained on a subset of the data, and its performance was evaluated on a test set. 
The results indicate a Mean Absolute Error (MAE) of 2.77 and a Mean Squared Error (MSE) of 53.62, demonstrating reasonable predictive accuracy in terms of absolute errors.

However, the R-squared value of 0.0001 suggests that the model has limited explanatory power, indicating that the selected features may not sufficiently capture the underlying patterns in tourist behavior. 
The cleaning process and subsequent modeling efforts are discussed, emphasizing the need for further exploration, feature engineering, or alternative modeling approaches to enhance the project's overall predictive performance and interpretability.

The methodology for analyzing Season-Wise Long-term travel Spots and predicting path counts involves a well-structured process comprising data loading, exploratory analysis, data cleaning, feature selection, model training, and evaluation. 

#Dataset:
A real-time data based on the mobile tourist is gathered for the year 2017-2018 for different locations of Jeju Island, South Korea. 
The data is collected from the wifi routers installed on every location. 
The data has attributes like date of the connection. 
The date is split across month, half and quarter for granularity purposes. 
Apart from this the move path is recorded showing the tourist movements across different locations. 
Additionally, number of tourist is counted for the route and the duplicate count is also noted down which the number of tourist who travels part of the recorded route is. 
The Dataset includes 36547 rows and 7 columns.

#Model Selecrtion
Linear Regression is a fundamental and widely used statistical technique in machine learning for predicting a continuous outcome variable based on one or more predictor variables. 
It assumes a linear relationship between the independent variables (features) and the dependent variable (target). 
Linear Regression assumes a linear relationship between the input features and the output. 
It models this relationship through a linear equation, where the change in the output is proportional to the change in the input.
Why Linear Regression for this Project: Given the nature of the project, interpretability is crucial for understanding the factors influencing tourist path counts. 
Linear Regression provides clear insights into how each selected feature contributes to the prediction. 
Linear Regression is computationally efficient, making it suitable for large datasets. 
Given the size of the dataset in this project, efficiency is a valuable consideration. 
While Linear Regression is a powerful tool, its effectiveness depends on the underlying assumptions and the complexity of the relationships within the data. 
If the relationship between features and path counts is highly nonlinear or contains intricate patterns, more advanced models may be explored in later stages of the project.

In summary, Linear Regression was chosen for its interpretability, simplicity, and suitability as a baseline model for predicting tourist path counts in Season-Wise Long-term travel Spots. 
Its results provide valuable insights into the initial understanding of the factors influencing tourist behavior.

#Results and Analysis
The results obtained after training the Linear Regression model on the Season-Wise Long-term travel Spots dataset provide valuable insights into the predictive performance and the impact of data preprocessing. 
The key metrics and observations are as follows: 
Model Performance Metrics:
Mean Absolute Error (MAE): 2.77
Mean Squared Error (MSE): 53.62
R-squared (R²): 0.0001

Analysis:
MAE Interpretation:
The Mean Absolute Error of approximately 2.77 suggests that, on average, the model's predictions deviate by around 2.77 units from the actual total path counts. This metric provides a measure of the model's accuracy in predicting tourist flow.
MSE Interpretation:
The Mean Squared Error of 53.62 indicates the average squared difference between predicted and actual values. A lower MSE is desirable, and its magnitude provides insights into the variability in prediction errors.
R-squared Interpretation:
The R-squared value, a measure of the model's explanatory power, is close to zero (0.0001). This implies that the linear regression model explains a very small proportion of the variance in the total path counts. It suggests that the selected features may not capture the complexity of tourist flow accurately.
Impact of Data Cleaning:
The dataset underwent a significant reduction in size during the cleaning process, from (36547, 7) to (12016, 7). This reduction highlights the presence of missing values in a substantial portion of the original dataset. The decision to remove rows with missing values was made to ensure a cleaner and more manageable dataset for modeling.

![image](https://github.com/Sherzo21/Training-Linear-Regression/assets/98465904/af378c5b-a441-4eea-a574-615fdd9107d4)

