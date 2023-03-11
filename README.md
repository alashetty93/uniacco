## Problem: Lead Scoring Model

Selling something is not an easy task. A business might have many potential customers, commonly referred as leads, but not enough resources to cater them all. Even most of the leads won’t turn into actual bookings. So there is a need for a system that prioritises the leads, and sorts them on the basis of a score, referred to here as lead score. So whenever a new lead is generated, this system analyses the features of the lead and gives it a score that correlates with chances of it being converted into booking. Such ranking of potential customers not only helps in saving time but also helps in increasing the conversion rate by letting the sales team figure out what leads to spend time on.

Here you have a dataset of leads with their set of features and their status. You have to build a ML model that predicts the lead score as an OUTPUT on the basis of the INPUT set of features. This lead score will range from 0-100, so more the lead score means more chances of conversion of lead to WON.
NOTE: The leads with STATUS other than ‘WON’ or ‘LOST’ can be dropped during training.
NOTE: Treat all columns as CATEGORICAL columns
NOTE: This '9b2d5b4678781e53038e91ea5324530a03f27dc1d0e5f6c9bc9d493a23be9de0' represents NaN and could be present in more than one column.
Steps should be:
Data Cleaning ( including Feature Selection)
Training ( on Y percent of data)
Testing ( on (100-Y) percent of data)
Evaluate the performance using metrics such as accuracy, precision, recall and F1-score.
