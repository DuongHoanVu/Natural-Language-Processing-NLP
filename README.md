# Natural Language Processing (NLP)

### Natural Language Processing

    1/ What is NLP:     An area of Computer Science and Artificial Intelligence concerned with interaction between human and computer
    2/ Spacy vs NLTK:   Choosing Spacy over NLTK library for combination of speed and accuracy. 
                        However Spacy does not include pre-created model for application like sentiment analysis. 
                        NLTK is easier to use.   
    3/ Tokenization:    A process of breaking up the original text into component pieces (tokens/unigrams/2word combination = bigram)
    4/ Stemming:        A method for cateloging related words.
                        Choppong of letter from the word until reaching the stem.
                        Spacy have no stemmer, because it totally relies on Lemmatization. 
                        There are several stemming algorithms such as Porter stemmer, Snowball stemmer, Lancaster, ...
                        All stemming algorithms get problems with overstemming and understemming
                            Overstemming:   is too much of a word cut off
                                            Ex: university -> universe
                            Understemming:  is not stemmed to the same root, which should have been
                                            Ex: alumnus -> alumnu
    5/ Lemmatization:   Look beyond word reduction, do not categorize phrases
                        Given part of speech, Lemmatization consider language vocab to apply morphological analysis to words
                        Ex:     is, are -> be
                                meeting -> meet or meeting (based on context)
    6/ Stop Words:      Words like: 'a', 'the' occur frequently.
                        Search engine has been programmed to ignore those stop words.
                        Filtering stop words would improve performance for reducing vocabulary array.
    7/ Phrash Matching: Identifying and labeling specific words, phrases that match pattern defined. 

### Part of Speech Tagging and Named Entity Recognition
   
   1/ Part of Speech Tagging
    2/ Named Enity Recognition
    3/ Sentence Segmentation

### Text Classification
   
    1/ Text Feature Extraction
    2/ Text Classification

### Semantics and Sentiment Analysis
    
    1/ Semantics and Word Vectors
    2/ Sentiment Analysis

### Topic Modeling
    
    1/ What is Topic Modeling
    2/ Latent Dirchlet Allocation
    3/ Non-negative Matrix Factorization

### Deep Learning for NLP
    
    1/ Text Generation with LSTM using Keras framwork
    2/ Creating Chat Bots
