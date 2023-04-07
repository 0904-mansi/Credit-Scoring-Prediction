# Fibe- Hack the Vibe Hackathon Solution Submission

## Credit-Scoring-Prediction


## Theme 1
The objective of this challenge is to create a robust machine-learning model to predict which individuals are most likely to default on their loans, based on their historical loan repayment behavior and transactional activities.

# Solution Description
I have used a random forest classifier for two reasons: firstly, because it would allow us to quickly and easily change the output to a simple binary classification problem. Secondly, because the predict_proba functionality allows us to output a probability score (probability of 1), this score is what we will use for predicting the probability of 90 days past due delinquency or worse in 2 years time.

Furthermore, I will predominantly be adopting a quantiles based approach in order to streamline the process as much as possible so that hypothetical credit checks can be returned as easily and as quickly as possible.

This model lead to an accuracy rate of **0.800498** on Kaggle's unseen test data.

I deem this accuracy rate to be acceptable given that we used a relatively simple quantile based approach and in light of the fact that no parameter optimization was undertaken.
