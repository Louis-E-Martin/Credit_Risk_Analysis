# Credit_Risk_Analysis
## Overveiw
In this module it was our goal to use suprvised machine learning to try and predict bad loans. We used 6 diffrent methods of machine learing to see which method would work best to be able to detect bad loans.

## Results
* Naive Random Oversampling
  * balanced accuracy score = 63%
  * precision score = 1%
  * recall score = 57%

* SMOTE Oversampling
  * balanced accuracy score = 63%
  * precision score = 1%
  * recall score = 62%

* Undersampling
  * balanced accuracy score = 51%
  * precision score = 1%
  * recall score = 59%

* Combination (Over and Under) Sampling
  * balanced accuracy score = 64%
  * precision score = 1%
  * recall score = 70%

* Balanced Random Forest Classifier
  * balanced accuracy score = 67%
  * precision score = 73%
  * recall score = 34%

* Easy Ensemble AdaBoost Classifier
  * balanced accuracy score = 66%
  * precision score = 61%
  * recall score = 32%

## Summary
As you can see above none of the models we made where amazing at detecting the bad loans. Depending on what you wanted to do I would recomend diffrent models. If your goal is to stop and bad loans from happeing I would go with the Combination model. This model is realtively unlikely to miss any loans that could be bad there will just be a large number of loans that wouldent be bad that you will also be missing out on. If you wanted the model that would be the most correct then the Balanced Random Forest Classifier model would be the best suited to your needs. This model has a high persiosion it just misses a fair number of the loans that are bad. If I had to make a recomendation I would say that none of these models are good enough to imploy. Having models only have a accuracy score in the 60% is quite low and you would want to see those numbers higher before you want to rely on them as you method of looking for bad loans.
 

