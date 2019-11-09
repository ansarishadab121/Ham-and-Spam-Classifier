# Ham-and-Spam-Classifier
This is a ham-spam classification problem in which ham and spam email texts are classified using Natural Language Processing.
Random Forest is used for predictive modelling.
Confusion matrix is used as an evaluation metric for accuracy assessment.
The steps involved in NLP are:
1. Data Cleaning and preprocessing
1.1. Case Normalization: Required some information that if upper case and lower case words are in same category or different.
1.2. Removing Stopwords: Stopwords are words that can be excluded from texts without loosing information such as I, Be, Because, Being,etc.
1.3. Removing Punctuation: Punctuations such as ',.,!,etc, has to be removed from texts.
1.4. Tokenization: It is done to seperate each words.
1.5. Stemming/Lemmatising: Both of these techniques reduce inflection forms to normalise words with the same lemma.he difference between lemmatising and stemming is that lemmatising performs this reduction by considering the context of the word while stemming does not.
2. Vectorizing Data: Frequency of a particular word in the total document. TF-IDF is used for vectorizing. TF-IDF is term frequency is (no. of times term i is used in document)/(total number of terms in documents) and IDF is logarithm of TF and TF-IDF is TF*IDF.
2.1. Vectorizing data n-gram: combination of n alternate terms is called n grams.
3. Feature Engineering
New features are created such as length of text after removing white space and percentage of punctuation in total texts.
Final predictive model is built with random forest.




