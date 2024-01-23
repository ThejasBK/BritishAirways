# British Airways Job simulation

This repository is one the solutions for British Airways job simulation. This is a certification offered by Forage. To complete the certification, I had to perfform 2 tasks.
* The first task was to visualize the data after performing web scraping from the websites provided by them. No unethical data was used to perform this operation.
* The next task was to implment an interpretable predictive model to understand if a user is going to buy a ticket after logging in. The main problem with this type of dataset is that the final target is imbalanced and need to handle that in an efficient way. I have used the class weights within the logistic model to handle this, there are many other ways like over/under saampling to perform the same operation.

> Note: Other models like XGBoost and Random Forest Classifier provided better results but are not interpretable.