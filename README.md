# -Sentiment-Analysis-NLP-for-Marketting

It is a model which analyze reviews comments on video games on amazon by rating it from 1 to 5

# Dataset
it is amazon dataset on video games consists of:
- overall	
- verified	
- reviewTime	
- reviewerID	
- asin	
- reviewerName	
- reviewText	
- summary	
- unixReviewTime	
- vote	
- style	
- image
we used reviewText and over all and drops other columns\

Data has 497577 we use only 20000 and split it to 15000 train & 5000 validation due to colab resources

# Model
We use BERT from ktrain library 

# Accuracy
the model has poor accuracy because of poor data\
accuraccy on validation data = 67.38 % on 5 epochs more than that model suffers from overfitting
