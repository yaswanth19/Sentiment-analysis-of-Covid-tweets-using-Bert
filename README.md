# Sentiment-analysis-of-Covid-tweets-using-Bert

## Dataset Information
The dataset is taken from kaggle and it contains 6 columns User Id , TweetIn , Sentiment , Location , Screen Name

## Methodology
Out of the all the columns onli two columns were considered namely TweetsIn and Sentiment.Then thorough data cleaning was performed to remove the emoji's,hashtags,mentions and other media,links.On,further cleaning maximum Non-english sentences were remove and the dataframe was made ready for modeling.

## Model
The model used was **BERT** which stands for Bidirectional Encoder Representations from Transformers.The pre-trained Bert Model was imported from Hugging Face🤗 transformer library.

## Results
```bash
training accuracy: 0.9522 
validation accuarcy:0.9255
```
### The Confusion matrix for the predictions on Test set
![2022-01-13](https://user-images.githubusercontent.com/82788246/149298564-ff92430d-b082-4e45-8df8-c5cb1891609f.png)
