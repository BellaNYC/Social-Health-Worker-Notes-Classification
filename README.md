# Social-Health-Worker-Notes-Classification
# Project problem: 
What do community health workers’ case notes tell us about the challenges of helping patients adopt healthy behavior to prevent diabetes?

# Data notes includes 200 patients from Bellevue: 
1. Why is a healthy lifestyle important to you?

2. What does being healthy look like to you?

3. Have you tried to make healthy changes before? How did that work out? What did you learn?

4. Are there any goals that you would like to work on? Let's discuss a few goals we can set for you

# Methods:
### Preprocessing: Bag of words
1. Stopwords, tokenization, lemmatization and stemming

2. After all above steps, move to build a vocabulary. (vocab = All final features after cleaning, removing stop words etc)

3. Vectorization: convert the words we finalized into vectors
#### Drawbacks of BaW: 
Say 'She is a nice person', if we were talking about importance, 'a' is as important as 'nice', but is it 'a' tells you more about context of the sentence compared to 'nice'?
So we use Tf-idf to solve and improve preprocessing.
### Tf-idf
1. Clean data / Preprocessing — Clean data (standardise data) , Normalize data( all lower case) , lemmatize data ( all words to root words ).
2. Tokenize words with frequency
3. Find TF for words
4. Find IDF for words
5. Vectorize vocab
### K-means clustering
### LDA
### Visualization 




# References:
https://medium.com/swlh/bag-of-words-code-the-easiest-explanation-of-nlp-technique-using-a-python-8a4fdfb8598c
<br>
https://medium.com/analytics-vidhya/tf-idf-term-frequency-technique-easiest-explanation-for-text-classification-in-nlp-with-code-8ca3912e58c3
