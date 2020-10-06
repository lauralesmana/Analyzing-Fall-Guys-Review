# Final Project
This project will analyze the reviews for Fall Guys that are posted in the game's Steam page. 

# The Goals
1. Understand users’ sentiments towards the game (positive/ negative)
2. Understand the game’s brand image among the users
3. Efficiently gather users’ opinion to find out possible future implementations
4. Prioritize which issues need to be handled as soon as possible in order to minimize users’ uninstalling or to avoid the loss of new potential users due to game’s bad issues. 

# The Methods
1. Download data from Fall Guys’ Steam review page (PC only)
2. Create topic label using LDA
3. Make unsupervised sentiment analysis model using VADER

# The Results
1. Reviews posted in Fall Guys mostly have positive sentiment
2. Users think that the game is fun and has potential but it has issues such as cheaters and server connection
3. Users mostly complains that the cheaters, server connection and some stages ruin the game's fun

# Future Improvements
1. Improving the text cleaning so the topic labels can be more accurate
2. The unsupervised model with the current reviews resulted in 75% accuracy, while the False Positive Rate is 40%. It might be better to find another model or improve the dataset
