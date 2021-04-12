### AML 1

# Launch a discord moderator bot that helps members post in the right channel. The bot will detect if a member has posted in the correct channel. If it finds that the post is in the wrong channel, it will suggest a correct channel from among the channels in the Community or Help categories. The bot will be active in discord for one week after project deadline, but can stay alive if members like it. 

# Acceptance Criteria 
For the bot to be enabled in our community, it must meet the threshold of 5% false positives on detecting posts in the wrong channel and 90% accuracy in suggesting the correct channel. A test dataset of 50 utterances has been withheld and will be used to evaluate your project upon submission. The test dataset has 3 fields: utterance, guessed-channel, true-channel. Your bot (or model) must determine if guessed channel is false with 95% specificity, and identify the true channel with 90% accuracy. There will be a leaderboard showing the performance rankings of all participants. 

## Datasets 
In this repo is utterance-channel-dataset.csv, a dataset consisting of 300 posts and the corresponding appropriate channel for each post. 

## Content 
Attached is a link to the DSEG wiki. It contains a section with recommended content for this project: https://docs.google.com/document/d/17WaVbR1xaKK5xb4F-SneId0Kgu36Bec0e01Yrs1tBB0/edit?usp=sharing

