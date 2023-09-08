# Diabetes Classifier - Classification with deep learning
- This project is designed to classify which patients have diabetes, given some biological data about the patients.
- The dataset used in the project comes from [Kaggle](https://www.kaggle.com/datasets/ashishkumarjayswal/diabetes-dataset?resource=download).
- This project included data exploration and visualisation using several Python libraries such as Seaborn, Matplotlib, Pandas and NumPy.
- Image of the headmap of correlations below.

![](Picture_6.png)

- Using sklearn, I created a logistic regression model that I then tested using a train test split. The logistic regression model has an accuracy of **0.79**. A reasonable degree of accuracy given there are only eight columns of biological data within the dataset.
- Image of the confusion matrix.

![](Picture_7.png)

- After looking at the logistic regression model, I tried to find an improved model using deep learning.
- Using TensorFlow and Keras, I developed a classification model.
- Image of the loss and val_loss plot.

![](Picture_8.png)

- This new model has the same accuracy of **0.79**. However, it might be a better model to use in some medical contexts as it is more likely to predict that people have diabetes. Therefore, it may be better than the logistic regression model as an initial warning for diabetes in patients.
- Image of the confusion matrix.

![](Picture_9.png)

- If I could spend more time on this project, I would try to optimise the model more. I would also collect additional patient data as this could help to refine the model.
