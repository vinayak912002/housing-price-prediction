## Housing price prediction model

* we have used the extreme gradient boosting as our model.<br/>

### Approach 1

* Imputed the missing values.
* one-hot encoded the categorical variables.

### Approach 2

* removed the columns with missing values.
* one-hot encoded the categorical variables.

### Future improvements

* There is a bit variance in the predictions during cross-validatioin which may be due to outliers. Figuring out how to deal with them will help.
* Increasding the accuracy of the model without overfitting.