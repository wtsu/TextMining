# TextMining
Text Mining Related Projects

Normalizing Messy Medical Data - Using Regular Expressions, I extract date variants from a list of medical notes. I normalize the data and then sort the list of medical notes by ascending chronological order. Use data set `dates.txt`

Spelling Recomender - I use nltk to explore the Herman Melville novel Moby Dick. Then I create a spelling recommender function that uses nltk to find words similar to mispellings found in the novel. The correct spelling to use is calculated using either Jaccard Distance on the trigrams of two words, Jaccard Distance on the 4-grams of the two words, and Edit distance on the two words with transpositions. Use data set `moby.test`.

Spam Message Classifier - I explore text message data. I then use sklearn to create a Naive Bayes Classifier model, a Support Vector Classification model, and a Logistic Regression Model to predict if a message is spam or not. I determine performance of models using AUC score. Use data set `spam.csv`
