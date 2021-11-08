# 🏠 House Sales Prediction
`House Sales Prediction` is the linear regression model, which predicts the price of the house based on its living area.

# 📜 Table of contents
* [About The Project](#about-the-project)
* [Visualization](#visualization)
* [Technologies](#technologies)
* [License](#license)


<h1 id="about-the-project"> 📓 About The Project </h1>
In this project given dataset is analyzed and the table with the highest correlation with price table is picked as the feature of the linear regression model. Then, the dataset is divided into two sets: training and test datasets. Afterwards, the model is built and trained on training dataset. In the model Root Mean Squared Error is used as a loss function. At the end trained model is used to predict the prices in the test dataset and the accuracy of predictions is determined by the coefficient of determination called R squared.

The project was built to learn the basics of linear regression and expand my knowledge of machine learning.

<h1 id="visualization"> 📈 Visualization </h1>

The first graph shows the sample of 250 points and the linear function matched by the trained model.

![as](https://user-images.githubusercontent.com/67509491/140822350-c059d19c-f9ee-4974-a29d-6f6e6291b1f6.PNG)

This graph represents the loss function during training.

![1234](https://user-images.githubusercontent.com/67509491/140822703-e487f849-1a27-40a4-b416-9edb66d311fe.PNG)

The accuracy of the model is 49.26%. It is not that bad for linear regression with one variable, but certainly can be improved by using multivariable linear regression.



<h1 id="technologies"> 👨‍💻 Technologies </h1>

Project was created with:
- **Python**: version 3.8.8
- **Tensorflow**: version 2.3.0
- **NumPy**: version 1.21.2
- **Pandas**: version 1.3.3
- **Seaborn**: version 0.11.2
- **Matplotlib**: version 3.4.2

<h1 id ="license"> ⚖️ License </h1>

<img alt="GitHub" src="https://img.shields.io/github/license/CN-28/House-Sales-Prediction?color=orange">
