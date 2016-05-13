# Bengali-Word-Embedding
------------------------------
## WHAT?
**Word embedding** is a laguage modeling and feature learning techniques in *Natural Language Processing(NLP)*.
It can represent every word or phrase as a set of numbers or like i say a real valued vector.
As each word has a real valued vector,it's easy to appaly many machine learning method in NLP task.

Bengali-Word-Embedding is done by using *word2vec* language model. 
*worde2vec* is a neural-networks based model designed by googel.
If you want to know about word2vec try [google word2vec](https://code.google.com/archive/p/word2vec/).
Want to know about 'How does word2vec work ?' try [quora-how] (https://www.quora.com/How-does-word2vec-work)

## WHY?
Word Embedding can be used in many NLP task in Bengali language.Some short list given below ---

1. Words Simililarity
2. Parts of Speech Tag
3. News/Documents Classification
4. News/Documents Clustaring
5. Sentiment Analysis
6. Name Entity Recognition

## HOW ?

### install dependency
I used gensim libary. Gensim is a python based machine learning library.To install it try it from [here](http://junya906.blogspot.com/2015/10/install-gensim-on-ubuntu-1404.html) or their official site.

### bd word embedding_train.py

This file is used for train a model.Our corpus folder is *bd_corpus* , model saved on *bd_save_model*
To generate word vector---- change in 'output_test(model,path)' function
**On terminal run:** python bd_word_embedding_train.py
    
### bd word embedding_retrain.py

Think a situation like you trained a model by using some corpus-data.
But after that some new data are added for embedding.
One soluation is to run the model again by giving all data on model [time consumming].
Second soluation is to train the model by loading saved model and retrain model by giving only new data.
This file can be done the second soluation for you.
You just have to change the *bd_corpus_path* and give the *saved_model_path*
**On terminal run: ** python bd_word_embedding_retrain.py
    
##THEN?






