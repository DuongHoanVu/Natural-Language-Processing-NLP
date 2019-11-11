# Natural Language Processing (NLP)

### Natural Language Processing

    1/ What is NLP:     An area of Computer Science and Artificial Intelligence concerned with interaction between human and computer
    2/ Spacy vs NLTK:   Choosing Spacy over NLTK library for combination of speed and accuracy. 
                        However Spacy does not include pre-created model for application like sentiment analysis. 
                        NLTK is easier to use.   
    3/ Tokenization:    A process of breaking up the original text into component pieces (tokens/unigrams/2word combination = bigram).
    4/ Stemming:        A method for cateloging related words.
                        Choppong of letter from the word until reaching the stem.
                        Spacy have no stemmer, because it totally relies on Lemmatization. 
                        There are several stemming algorithms such as Porter stemmer, Snowball stemmer, Lancaster, ...
                        All stemming algorithms get problems with overstemming and understemming.
                            Overstemming:   is too much of a word cut off
                                            Ex: university -> universe
                            Understemming:  is not stemmed to the same root, which should have been.
                                            Ex: alumnus -> alumnu
    5/ Lemmatization:   Look beyond word reduction, do not categorize phrases
                        Given part of speech, Lemmatization consider language vocab to apply morphological analysis to words.
                        Ex:     is, are -> be
                                meeting -> meet or meeting (based on context)
    6/ Stop Words:      Words like: 'a', 'the' occur frequently.
                        Search engine has been programmed to ignore those stop words.
                        Filtering stop words would improve performance for reducing vocabulary array.
    7/ Phrash Matching: Identifying and labeling specific words, phrases that match pattern defined. 

### Part of Speech Tagging and Named Entity Recognition
   
    1/ Part of Speech Tagging(POS): Using linguistic knowledge to get useful information.
    2/ Named Enity Recognition(NER):Seeking to classify named entity mentions in unstructed text into predefined categories.
                                    Ex: 'I went to Canada in 2018', 
                                    where 'I' is classified as 'person', 'Canada' is classified as 'country', '2018' is classified as 'time'.
    3/ Noun Chunk:              Base noun phrases, in form of adverb + adjective + noun
                                Do not overlap other attributes like NER.
                                Components when dealing with Noun chunk: 
                                    chunk.text, chunk.root.text, chunk.root.dep, chunk.head.text. 
    4/ Sentence Segmentation:   Defining each sentence to end with dot(.).
                                Redefining seach sentence as it ends with any special symbols like !, @, #, ...

### Text Classification
   
    1/ Text Feature Extraction: Machine Learning do not take in raw text.
                                Perform feature extraction from raw text to pass numerical features to Machine Learning algorithm.
    2/ Text Classification:     There are some techniques to differentiate documents:
                                    1.  Count Vectorizer(Bag of Words, Vectorization) & Document Term Matrix(DTM).
                                        This calculates term frequency.
                                    2.  Tfid Vectorizer (Term frequency inverse document frequency value).
                                        This diminishes weight of term frequently occuring, raises that of term rarely occuring.
                                        Because a word occuring so often in different documents is unimportant.
                                        Our goal is to differentiate documents.

### Semantics and Sentiment Analysis
    
    1/ Semantics and Word Vectors:  
    2/ Sentiment Analysis:          

### Topic Modeling
    
    1/ What is Topic Modeling:          
    2/ Latent Dirchlet Allocation:      
    3/ Non-negative Matrix Factorization: 

### Deep Learning for NLP
    
    1/ Text Generation with LSTM:   
    2/ Creating Chat Bots:          
