# YelpStarClassifier

Welcome to the NLP Project. In this NLP project, I've attempted to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews using the pipeline methods for more complex tasks.

We will use the [Yelp Review Data Set from Kaggle](https://www.kaggle.com/c/yelp-recsys-2013).

## Dataset Description

Each observation in this dataset is a review of a particular business by a particular user.

- The **"stars"** column is the number of stars (1 through 5) assigned by the reviewer to the business. (Higher stars is better.) In other words, it is the rating of the business by the person who wrote the review.
- The **"cool"** column is the number of "cool" votes this review received from other Yelp users. All reviews start with 0 "cool" votes, and there is no limit to how many "cool" votes a review can receive. In other words, it is a rating of the review itself, not a rating of the business.
- The **"useful"** and **"funny"** columns are similar to the "cool" column.

## Methodology

### 1. Importing Libraries

First, we import the necessary libraries required for data manipulation, visualization, and building the logistic regression model.

### 2. Exploratory Data Analysis (EDA)

We perform EDA to understand the dataset better. This involves visualizing the distribution of various features and understanding the relationships between them.

### 3. Finding Out the Missing Data Attributes

We identify any missing data in the dataset. This is crucial as missing data can significantly affect the performance of the model.

### 4. Cleaning the Data

We handle the missing data by either imputing with appropriate values or dropping the missing values. This step ensures that our dataset is clean and ready for model training.

### 5. Converting Categorical Features

We convert categorical features into numerical values using techniques such as one-hot encoding. This step is essential as machine learning models require numerical input.

### 6. Building a Logistic Regression Model

We build and train a logistic regression model using scikit-learn. This involves splitting the dataset into training and testing sets, fitting the model, and making predictions.

### 7. Evaluating the Results

We evaluate the model's performance using various metrics such as accuracy, precision, recall, and ROC curve. This helps us understand how well our model is performing and identify areas for improvement.

## Usage

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook file `yelp_star_classifier.ipynb`.
3. Follow the steps in the notebook to load the dataset, preprocess the data, and train the logistic regression model.
4. Use the trained model to make predictions on the test data.

## Project Steps

1. **Data Exploration**: Understanding the dataset and exploring the relationships between features.
2. **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
3. **Model Training**: Implementing logistic regression using scikit-learn.
4. **Model Evaluation**: Evaluating the model's performance using metrics such as accuracy, precision, recall, and the ROC curve.
5. **Prediction**: Using the trained model to predict star ratings on the test data.

## Conclusion

This project demonstrates the implementation of logistic regression for a binary classification task using the Yelp Review dataset. It covers data preprocessing, model training, and evaluation, providing a comprehensive introduction to natural language processing with a real-world dataset.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- The [Yelp Review Data Set](https://www.kaggle.com/c/yelp-recsys-2013) from Kaggle for providing the data.
- The open-source community for the development of tools and libraries used in this project.
