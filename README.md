# SMS-Clasifier
Both Multinomial &amp; Bernoulli Methods are Used

Full-fledged implementation of the Naive Bayes classifier in python on the ‘SMS dataset’.
We’ll build an SMS spam classifier and compare the results of Multinomial NB and Bernoulli NB.

Sensitivity implies that out of all the actual Spam's, how many of them were correctly predicted by the model as Spam. 

 Specificity implies that out of all the genuine SMS's, how many of them were correctly predicted as legitimate by the model.

 If we look back to the problem statement, We are fine if some of the Spams are classified as Hams, but it will not be good if an important Ham is classified as Spam by our model. So our motive is to maximise Specificity.
 
 In Bernoulli's case, we wanted the False positives i.e the ham being classified as spam as low as possible which you could achieve by using Bernoulli Naive Bayes classifier even though the overall accuracy and sensitivity was less than Multinomial Naive Bayes classifier.
