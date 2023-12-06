# Classification-Project

# project description with goals - 
<!-- - Discover drivers of churn using telco customer data.
- Use drivers to develop a machine learning model to classify customers that end up churning or not. -->

# initial hypotheses and/or questions you have of the data, ideas -
<!-- - I asked four questions of the customer data regarding churn in this section.
- Q1: Does having paperless billing affect whether or not someone churned?
- Q2: Does being male affect whether or not someone churned?
- Q3: Does having dependents affect whether or not someone churned?
- Q4: Does being a senior citizen affect whether or not someone churned? -->

# data dictionary - 
<!-- - Total Charges - the amount each customer has been charged since using the company.
- Tenure - amount of time in months the customer has been with Telco.
- Churn - yes or no, whether the customer leaves the company or not.
- Paperless Billing - yes or no, the method in which the customer is informed of the billed charges of service.
- Partner - yes or no, whether the customer is married or not.
- Senior Citizen - yes or no, whether or not the customer's age is above 65.
- Monthly Charges - the amount each customer is billed each month as data type float64. -->

# project planning (lay out your process through the data science pipeline) - 
<!-- - Plan, acquire, prepare, explore, model, and deliver the data. I made a plan and documented key deadlines and target dates for deliverables. Use a function to acquire the data. Drop any unhelpful columns, handle null values, split the data, and encode the categorical columns to prepare. Hypothesize, ask questions, use stats test, and visualization to answer the questions. Use at least three models to train the data. Publish my findings in an easy to read final jupyter notebook. -->

# instructions or an explanation of how someone else can reproduce your project and findings (What would someone need to be able to recreate your project on their own?) - 
<!-- - To reproduce my project and findings you would need your own env file, and to use the same random state/random seed as I did which was '123' to recreate the data split phase. -->

# key findings, recommendations, and takeaways from your project - 
<!-- - Modeling Summary
The logistic regression model had the worst accuracy which was par with the baseline accuracy on train and validate.

The decision tree model had a slightly better accuracy than the baseline on train and validate.

Finally, the best model of all turned out to be the random forest model with the highest accuracy of the three models. When modeling on test data it had an accuracy of about 80%.

- Reccomendations
To help reduce churn, lowering monthly charges for senior citizens without dependents and with paperless billing could perhaps get them to stay.

- Next Steps
Cluster together "streaming_tv" and "streaming_movies" into "streaming_services" to reduce the number of columns in the data.

If I had more time to explore the data I would look to see if customers with partners were more inclined to churn. -->