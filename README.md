# psut-nlp-project
__Note__: Conda requirements are for an Ubuntu 18.04 environment.

Code repository for the assignments required in the Natural Language Processing master's course at PSUT.


### Assignments 
The given 10 txt files contain various Arabic tweets. Each file consists of two columns: tweet ID and tweet string. Most tweets contain unwanted emoji or hashtags which should be excluded first. For some tasks you can consider some files as training data and the remaining files as testing data.

* __Task 1__: Select a training data to build a bigram language model that can help you in text sequence generation for sequence data. You should implement a python class with multiple methods to do the following jobs:
    * The class name is LanguageModel.
    * A constructor to get the text file name and open that file.
    * A method called Clean to process the text (Tokenization, Lemmatization)! Don’t remove stop words.
    * A method called LMBigram to build 2-D Language Model Matrix with Laplace smoothing using NLTK. This method saves generated matrix in an instance variable.
    * A method called Run that takes a part of sentence from user and returns the expected next word using the constructed matrix from the previous step.

* __Task 2__: Use NLTK and/or Camel libraries to build “Named Entity Extraction” Model that can be used to extract name of person, country, organization, events...etc. The model can be trained on training data and tested on different data.

* __Task 3__: Use google BERT word embedding model to build sentiment analysis model.

* __Task 4__: Prepare a presentation on an NLP task. (I chose "Topic Modelling" and experimented with the Latent Dirichlet Allocation (LDA) Topic Modeller).

