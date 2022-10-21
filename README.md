# Predicting Data Breaches Using Human Factors
Authors: Nhat Pham, Lakshyana KC
Data source: Kaggle dataset “Food.com - Recipes and Reviews” (https://www.kaggle.com/irkaal/foodcom-recipes-and-reviews)

<h2>I/ Background: </h2>
<h3>1. Motivation </h3>
- Understanding what constitutes a high-rated recipe helps us study eating habits at a societal level <br />
- Food creators can use the prediction to modify their recipe content to improve its reception and visibility online <br />
- Little research on predicting the online ratings of recipes <br />
- Research focuses on developing recipe recommendation systems based on previous ratings <br />
- We are curious to learn if there are specific combinations of ingredients or instruction features that have an influence on how much the users like the recipe <br />
<br />


<h3>2. Dataset</h3>
The data includes a list of 500k+ recipes and a list of 1.4M reviews dated from 1999 to 2020. We chose this dataset because of its recency and large size. It contains rich text data including description, ingredients, cooking instructions, and users’ reviews, as well as numeric data on nutritional values, cooking time, and other features.
  
![dessert](https://user-images.githubusercontent.com/87089936/197110859-3c87f2b0-a837-4944-9bba-5a208f739593.PNG)
![dessert2](https://user-images.githubusercontent.com/87089936/197110883-6c41ded6-00b1-40f3-af42-c4a5540c303c.PNG)
<br />
  
<h3>3. Objectives</h3>
The objective of this project was to train and compare multi-class classification models for predicting the rating of an online recipe using the ingredients, recipe instructions, nutrition and healthiness, complexity, description and title attributes. We also trained a Doc2Vec embedding model using the concatenated recipes’ ingredients and instructions text. We performed some visualizations of the recipe embedding models to better understand the dataset and characterize the embedding vectors for the recipes. We then trained multiple statistical models such as Naive Bayes (NB), Logistic Regression, Support Vector Machine (SVM), and Random Forest using different combinations of text and numerical features.<br />
We also trained a feedforward classification model using the pre-trained embedding model weights to compare its performance with the other models. We will then evaluate the model performances using a common test dataset, and evaluation metrics such as the F1 score, Precision, Recall, and Accuracy metrics.<br />

<h2>II/ Results</h2>
★ Data Processing <br />
![neural](https://user-images.githubusercontent.com/87089936/197111121-5d7dc39c-9a15-4694-9782-0735d9458ae4.PNG)
<br />
★	Embedding Model <br />
![image](https://user-images.githubusercontent.com/87089936/197197165-0c335767-a699-48b4-a5c6-804046a67294.png)<br />

![image](https://user-images.githubusercontent.com/87089936/197197264-19e0da15-41f7-4287-9c59-2293a502070e.png)<br />


★	Non-neural Network Model <br />
- Random Forest <br />
- Logistic Regression <br />
- Naive Bayes <br />
- Support Vector Machine <br />
![nonneural1](https://user-images.githubusercontent.com/87089936/197198326-3683473d-b7c2-4f69-977d-955eef2c716a.PNG)<br />

★	Feedforward Neural Network Model <br />
![neural1](https://user-images.githubusercontent.com/87089936/197198504-2f532145-9ff3-4a53-8c45-1d1749ce4ac2.PNG)
![nerual](https://user-images.githubusercontent.com/87089936/197198530-ff8d21f7-f1f9-4011-94bc-df8072dde418.PNG)

Please see our Final Presentation for details.<br />

 
