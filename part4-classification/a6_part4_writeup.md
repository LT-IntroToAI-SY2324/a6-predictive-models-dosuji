# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
Without the standardscaler the model is still relatively inaccurate but with the scaler it centers the values around the mean of the dataset and then provides more accurate values/predictions.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
With the Standard Scaler, the model is more accurate than when it was without the standard scaler.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
The model did not do the best but it was not the worst. I could not assess whether there was a pattern of inaccuracy. 

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
No they cant.
