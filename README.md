# STAT4365FinalProj

## Initial Plan

### Objective:
  We want to uncover and understand how different factors in the health risk of an individual person affects the amount they are charged in health insurance. This isn’t strictly limited to numerical variables like a person’s age or the number of children they have, but also includes categorical variables, like their gender or whether they smoke. Revealing the extent to which each variable in a person’s health affects their health insurance charges will allow us to make accurate predictions of the charges for future use.

### Area of Interest: 
Health insurance plays a vital role in an individual’s ability to afford medical care, but can also represent a major personal expense depending on how at risk an insured is of having health issues. We hope to use this data to find what aspect of a person’s life plays the largest role in having to pay higher expenses.

### Data: 
We’ll use a dataset whose response variable is total charges on health insurance, and which takes the following variables as predictors for total charges: age, sex, bmi, number of children, whether an individual is a smoker, and the region they live in. This dataset comes from public access on Kaggle.

### Methods: 
We plan to use methods and tools like encoding dummy values into categorical variables alongside dropping rows with null values to clean the data and make it suitable for regression testing. For our actual prediction, we plan to use multiple linear regression and train test splitting to find how health insurance is impacted by each predictor variable while ensuring the model we utilize for our training data can also be applied to similar, separate data successfully. 

### Expectations: 
We expect to be able to find the extent to which each predictor variable impacts the response variable in health insurance charges through the methods we described above. The coefficients attached to our predictor variables should not be affected by rows which have incomplete cases, and we should be able to include categorical variables, especially variables like smoking which can have a major impact on a person’s health and what they are charged as a result.

### Showcase: 
We plan to use a GitHub repo to showcase our project.

## Final Results

Throughout our time working with our dataset revolving around health insurance, we undertook various methods of testing and modeling to help find which variables could best help predict charges for health insurance. This involved using the various tools described previously in the methods section of the intiial plan, alongside new tools like weighted regression and various plots detailing the relationship between certain variables and resulting health insurance charges.
