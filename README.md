# Applied-Predictive-Analytics-Sose20

Uplift models were mainly used for conversion setting where the outcome variable is binary, for instance, the model tells us if a customer will buy a product or not, but there are not so many of them deal with continuous outcome, that is, instead of only predicting yes or no, the model gives prediction on how much money the customer is going to spend due to the campaign, or say, treatment. Except from the target variable, we also want to cope with multiple treatment cases instead of single treatment. Consider the email marketing example, instead of having only two groups --treatment and control, we would like to have different versions of promotion emails that are going to be sent to the potential target customers, in this case, we want to know not only if the email would increase the sales or not, but also which email would do so the best.
On that account, the goal of this project is to develop an uplift model that handles the case of both multiple treatments and continuous outcome. Our model has its foundation based on the Contextual Treatment Selection (CTS) developed by Zhao 2017,  combined with AdaBoost algorithms. Boosting often dramatically improves performance of classification models, so we make use of this property and aim to improve the uplift model performance under multiple treatments and continuous outcome.

## Getting Started
First of all, in the Model_Code file, you will find the code to our model building, presdicting, and curve drawing.
In the Paper_Image file, the images needed for our final paper is included, and the paper can be found in the paper folder.
Last but not least, the dataset we used for our project is also uploaded. Enjoy!

## Authors

* Jessica Ströbel
* Shih-Chi Ma
