
# Iris Flower Type Prediction.

In this project, I am writing a alogrithm for a ml model to predict the type of iris flower present in the data . The data inorder to give the predictions contain sepal widith and height, petal width and height. According to this features the machine learing model predict which type of flower it is. The type of problem this model solves is Classifiaction type. The Algorithm used is Logistic_Regression. 



## Author

- [@abhipnair](https://github.com/abhipnair)


## Features

- Easy to use.
- Can recoginise iris flower type just by loading the model (Iris_Flower_Predicter) provided in the code.
- You can predict things upto an accuracy of 100%


## Importing Model


To load the model and use this line of code in a Python Script :

```python
  # To load the model we can use joblib.
    import joblib
    model = joblib.load("Iris_Flower_Type_Predicter")
    model.predict(Testing_Data)  # to know how to predict just go through the code
    # for prediction array_must contain [['sepal length (cm)', 'sepal width (cm)', 'petal length (cm)', 'petal width (cm)']]
    # use double square brackets eg: model.predict([[5.1 3.5 1.4 0.2]])
```
To load the model of support vector machine into your code use. 
```python
  # To load the model we can use joblib.
    import joblib
    model = joblib.load("Model_Iris")
    model.predict(Testing_Data)  # to know how to predict just go through the code
    # for prediction array_must contain [['sepal length (cm)', 'sepal width (cm)', 'petal length (cm)', 'petal width (cm)']]
    # use double square brackets eg: model.predict([[5.1 3.5 1.4 0.2]])
```



## 🚀 About Me
I am a tech enthusiast passionate about Coding, Hacking, AI, and the exciting world of futuristic technology....


## 🛠 Skills
Python, HTML, CSS, Bash, Linux, C++, C, OPENCV...
