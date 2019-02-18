# Handwriting Analysis<br/>
Developed a linear regression model(using Stochastic Gradient Descent) and logistic regression model to find similarity between the handwritten samples of the word “and” with the known and the questioned writer by using Human Observed Dataset and Gradient Structural Concativity datasets.<br/>

# Data Pre-processing<br/>
# Human Observed Dataset<br/>
To construct the dataset to feed the model, 791 same writer pairs and 1500 different writer pairs are considered. Two types of dataset was built by two methods:<br/>
• Concatenation of the features found for each image id which results in 18 features in total for a particular row. Each row contains the concatenated features of two image id’s which are considered. While performing data pre processing, the rows are shuffled to make the dataset better. The target values are maintained in a separate file. 
•Subtraction of the features of the two image id’s results in 9 features for a particular row. Each row contains the subtracted features of two image id’s which are considered. While performing data pre-processing, the rows are shuffled to make the dataset better. The target values are maintained in a separate file.<br/>

# Gradient Structural Concativity <br/>
Gradient Structural Concativity algorithm generates 512 sized feature vector for an input handwritten ANDimage. The dataset is named as GSC-Features-Data. The entire dataset consists of 71,531 same writer pairs and 762,557 different writer pairs(rows). The dataset was built using GSC-Features- Data.csv, same pairs.csv and diffn pairs.csv. The two types of dataset was built by two methods.<br/>
• Concatenation of the features found for each image id which results in 1024 features in total for a particular row. Each row contains the concatenated features of two image id’s which are considered. While performing data pre processing, the rows are shuffled to make the dataset better. The target values are maintained in a separate file.<br/>
• Subtraction of the features of the two image id’s results in 512 features for a particular row. Each row contains the subtracted features of two image id’s which are considered. While performing data pre-processing, the rows are shuffled to make the dataset better. The target values are maintained in a separate file.<br/>

Solutions: Linear Regression using Stochastic Gradient Descent, Logistic Regression<br/>
Datasets: Human Observed Dataset, Gradient Structural Concativity <br/>
Skills: Python, TensorFlow
