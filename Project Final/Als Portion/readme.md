Here is my attempt at working on the Final Project

I've used jupyter notebook but I think it should be all reproducible

The first file is my attempt at trying to grab the game_description column and the copies it sold from the steam API and the gamanalytics API and mergine together into one single API, i did some cleaning here and there and the data-frame came out okay

I exported it into a data-frame called Games2

The next file is my attempt at doing text-classification with the dataframe, I did some more cleaning here and there i.e

converting the copies_sold into a classification column
removing na observations
and removing unnecessary columns
Then I did some text-preprocessing

Removed stopwords
Tokenized the words
Removed puncations
For the ML part I have applied a bunch of transformation on the text (Word-Vector, Bag of Words, and TF-IDF) and I have used the support Vector algorithm

TLDR: The classifier I made were not that good and the only one that worked slightly were the Word-Vector Transformation
