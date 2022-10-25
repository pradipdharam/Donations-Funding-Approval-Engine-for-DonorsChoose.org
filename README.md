# Donations Funding Approval Engine for DonorsChoose.org

DonorsChoose.org receives hundreds of thousands of project proposals each year for classroom projects in need of funding. Right now, a large number of volunteers is needed to manually screen each submission before it's approved to be posted on the DonorsChoose.org website.

Next year, DonorsChoose.org expects to receive close to 500,000 project proposals. 

As a result, model to solve below problem statement is build.

How to scale current manual processes and resources to screen 500,000 projects so that they can be posted as quickly and as efficiently as possible?

The goal of the competition is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school. DonorsChoose.org can then use this information to identify projects most likely to need further review before approval.


### Results:
Check the jupyter notebook in this repo for more details related to preprocessing and model building.

* LSTM - Model1 __ Test Score - 127.6 __ Test AUC  - 99.05 
* LSTM - Model2 __ Test Score - 66.0  __ Test AUC  - 92.32 
* LSTM - Model3 __ Test Score - 77.62 __ Test AUC  - 92.36 



Observations:

    All three models are overfitting
    Model 1 looks good performer in comparison on other models

#### Disclaimer: This problem statement is been solved purely for purpose of learning and not to earn money.
