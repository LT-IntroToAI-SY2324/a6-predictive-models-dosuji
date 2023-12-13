# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
The R squared coefficient for the model is 0.86. This means that the model is relatively consistent to the data.

2. Is your model accurate? Why or why not?
The model is relatively accurate since the predicted values are only off by 1000-2000 miles and the values are consistent.

3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
The model predicts that a 10-year-old car with 89000 miles is worth $14,016.12 and the 20-year-old car with 150000 is worth $10,133.95.

4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
The original value of the car is lower than the other values in the data, so any significant difference or margin of error causes the predicted value to become below zero.