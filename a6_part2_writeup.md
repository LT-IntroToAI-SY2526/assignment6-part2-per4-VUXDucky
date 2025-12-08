# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Age
2. Sqft
3. bedrooms
4. Least Important: bathrooms

**Explanation:**
I determined this ranking basically due the amount the data can vary for example the age graph is scattered all around the data set and it would very difficult to make a line of best fit from the data, and then i went from descending order of that idea which went to Sqft, bedrooms, and then bathrooms.


---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
the model_intercept_:.2f is basically the average int price of the house before the rest of the factors like sqft or bedrooms affect its price. That int price is $85,706

**Feature 2:**


---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
The R^2 model score is 99.36%, what this tells me about the model's ability to predict house prices is that it's capable of predicting house prices 99% to their actual price. Yes theres still room for improvement because it isn't 100% and its off by $4477.



---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Garage

**Why it would help:**
It might increase the price of the house the more garage spaces there are.

**Feature 2:**
Crime rate 

**Why it would help:**
The price of the house might decrease based on how high the crime rate is in that neighborhood.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
No because the graph doesn't have any data on houses past 3 bathrooms so it wouldn't know how to make a fair judgement and the amount of sq ft is also past the range on the graph.


