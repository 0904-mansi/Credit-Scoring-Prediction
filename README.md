# Fibe- Hack the Vibe Hackathon Solution Submission

## Credit-Scoring-Prediction


## Theme 1
The objective of this challenge is to create a robust machine-learning model to predict which individuals are most likely to default on their loans, based on their historical loan repayment behavior and transactional activities.

# Solution Description
I have used a random forest classifier for two reasons: firstly, because it would allow us to quickly and easily change the output to a simple binary classification problem. Secondly, because the predict_proba functionality allows us to output a probability score (probability of 1), this score is what we will use for predicting the probability of 90 days past due delinquency or worse in 2 years time.

Furthermore, I will predominantly be adopting a quantiles based approach in order to streamline the process as much as possible so that hypothetical credit checks can be returned as easily and as quickly as possible.

This model lead to an accuracy rate of **0.800498** on Kaggle's unseen test data.

I deem this accuracy rate to be acceptable given that we used a relatively simple quantile based approach and in light of the fact that no parameter optimization was undertaken.


# Analysis Graphs for overview

<img width="400" alt="Screenshot 2023-04-08 at 3 02 18 PM" src="https://user-images.githubusercontent.com/81081105/230714474-9c9e2b2b-3df8-46c3-908a-79098e157282.png">
<img width="400" alt="Screenshot 2023-04-08 at 3 02 01 PM" src="https://user-images.githubusercontent.com/81081105/230714479-c6b2bf41-36c1-462b-9810-b08e975d4721.png">
<img width="400" alt="Screenshot 2023-04-08 at 3 01 04 PM" src="https://user-images.githubusercontent.com/81081105/230714482-5251b58b-c605-465f-8e35-f39fdb551cbb.png">
<img width="400" alt="Screenshot 2023-04-08 at 3 00 36 PM" src="https://user-images.githubusercontent.com/81081105/230714486-fffe138c-7573-4f6a-a4e3-b7208b870383.png">
