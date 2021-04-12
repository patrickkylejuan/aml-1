# AML 1

### Launch a DSEG moderator bot in discord that helps members post in the right channel. The bot will detect if a member has posted in the correct channel. If it finds that the post is in the wrong channel, it will suggest a correct channel from among the channels in the Community or Help categories. The bot will be active in discord for one week after project deadline, but can stay alive if members like it. 

## Acceptance Criteria 
For the bot to be enabled in DSEG, it must meet the threshold of 5% false positives on detecting posts in the wrong channel and 90% accuracy in suggesting the correct channel. A test dataset of 50 utterances has been withheld and will be used to evaluate your project upon submission. The test dataset has 3 fields: utterance, guessed-channel, true-channel. Your bot (or model) must determine if guessed channel is false with 95% specificity, and identify the true channel with 90% accuracy. There will be a leaderboard showing the performance rankings of all participants. 

## Datasets 
In this repo is utterance-channel-dataset.csv, a dataset consisting of 300 posts and the corresponding appropriate channel for each post. 

## Plan 
The plan is to preprocess your text data using TF-IDF (NLP), build a classifier using an SVM (ML), run your code in a Jupyter notebook, and leverage functions from SKLearn. 
Resources are available below to explain all the above concepts. If you have the time and motivation, a good challenge is to implement SVMs with stochastic gradient descent from scratch. 
If there is time permitting build a Flask, run it in AWS, use the Discord API, and deploy your moderator bot in our server. Keep in mind that at the halfway point and at completion you will present your work to the community. Make sure to have some progress and work to show at each point to stay accountable and to provide teaching for more novice members of the community. 

## Content 
Attached is a link to the DSEG wiki. It contains a section with recommended content for this project: https://docs.google.com/document/d/17WaVbR1xaKK5xb4F-SneId0Kgu36Bec0e01Yrs1tBB0/edit?usp=sharing

