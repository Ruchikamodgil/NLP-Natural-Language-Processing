# NLP-Natural-Language-Processing

## Text-Preprocessing
#### -> Tokenization 
  Tokenization is the process by which big quantity of text is divided into smaller parts called tokens. <br>
  These tokens are very useful for finding such patterns as well as is considered as a base step for stemming and lemmatization. <br>
  For example, <br>
  
  
  ``` “It is raining”``` can be tokenized into ‘It’, ‘is’, ‘raining’<br>
  <br>
#### -> Stemming 
Stemming is the process of reducing inflection in words to their root forms such as mapping a group of words to the same stem even if the stem itself is not a valid word in the Language. <br>
<br>
#### -> Stopwords
These words are filtered out from search queries because they return a vast amount of unnecessary information. Each programming language will give its own list of stop words to use. Mostly they are words that are commonly used in the English language such as 'as, the, be, are' etc.
<br>
<br>
#### -> Lemmatization
Lemmatization, unlike Stemming, reduces the inflected words properly ensuring that the root word belongs to the language. In Lemmatization root word is called Lemma. A lemma is the canonical form, dictionary form, or citation form of a set of words.
<br>
<br>

#### -> N-Grams
There are set of co-occurring or continuous sequence of n items from a sequence of large text or sentence. The item here could be words or letters.<br>
1-gram is also called as unigrams are the unique words present in the sentence. Bigram(2-gram) is the combination of 2 words. Trigram(3-gram) is 3 words etc.
<br>
<br>
#### -> Bag of Words
It creates a set of vectors containing the count of word occurrences in the document.<br>
As it convert to data where all features have equal importance and TF-IDF is used to overcome this problem.
Bag of Words vectors are easy to interpret. However, TF-IDF usually performs better in machine learning models.
<br>
<br>

#### -> TF-IDF Term Frequency-Inverse Document Frequency
tf=no. of particular word in sentence / Total number of words in sentence <br>
idf=no. of sentences / no. of sentences containing particular word <br>
resultant tfidf = tf * idf
<br>
<br>
## Email Spam Classifier
<br>
Model which classifies the message as spam and non spam using Naive Bayes Classifier and using NLP Data Preprocessing to convert the dataset into suitable format.
