# Data-science-project-by-Agbaje-Tobi-Emmanuel

# Data Science Coding Challange!
As a learner i want to be challenge and evaluate my skills to get ready for job opportunities so i selected these data science course to show my skills to solve one of the most industry-relevant maching learning problems with a unique dataset that was provided to tackle the churn prediction problem on a very unique and interesting group of subscribers on a video streaming service.
The dataset is a sample of subscriptions that were initiated in 2021, Subscription cancellation can happen for a multitude of reasons, including:
(1) the customer completes all content they were interested in, and no longer need the subscription
(2) the customer finds themselves to be too busy and cancels their subscription until a later time
(3) the customer determines that the streaming service is not the best fit for them, so they cancel and look for something better suited

Regardless the reason, this video streaming company has a vested interest in understanding the likelihood of each individual customer to churn in their subscription so that resources can be allocated appropriately to support customers

In this challenge, i used machine learning toolkit to do just that

### Dataset descriptions
Both `train.csv` and `test.csv` contain one row for each unique subscription. For each subscription, a single observation (`CustomerID`) is included during which the subscription was active. 

In addition to this identifier column, the `train.csv` dataset also contains the target label for the task, a binary column `Churn`.

Besides that column, both datasets have an identical set of features that was be used to train my model to make predictions.

## How i Submitted my Predictions
I followed the steps below to explore the data, train a model using the data in `train.csv`, and then i scored the model using the data in `test.csv`. My final submission is a dataframe and i called it `prediction_df` with two columns and exactly 104,480 rows (plus a header row). The first column is `CustomerID` and the second column is called `predicted_probability`. it was in a numeric column representing the __likellihood that the subscription will churn__.

