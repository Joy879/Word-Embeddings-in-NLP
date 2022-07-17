## Tasks

#### 1. Implement the code provided below
[blog](https://machinelearningmastery.com/use-word-embedding-layers-deep-learning-keras/) 

#### 2. Implement the code provided below
[blog](https://machinelearningmastery.com/sequence-classification-lstm-recurrent-neural-networks-python-keras/)


#### 3. Please prepare notes comparing Word2Vec, GloVe and FastText word embedding comparison.


| Word2Vec       | GloVe           | FastText      |
|----------------|:---------------:|--------------:|
|obtained by using a neural network to predict missing words in sentences, and taking the coefficient of the last layer of the neural network as the elements of the word vector  |  focuses on capturing the similarity in context between words. It is lighter and more efficient than word2vec.           |    works with sub-word tokenization and, as a consequence, can handle out-of- vocabulary words.        |
|  |             |            |

### Comparing Word2Vec and GloVe 

|Word2vec| GloVe|
|---|---|
Word2vec leverages co-occurance within local context (neighbouring words).| Glove model is based on leveraging global word to word co-occurance counts leveraging the entire corpus.| 


### Comparing Word2Vec and FastText

|Word2Vec|FastText|
|---|---|
|If you give it a word which is not in the vocabulary used to train the model, it cannot give you similar words. | if you feed Fasttext a word that it has not been trained on, it will look at substrings for that word and see if that appears in the corpus. This is because it is built on not just using the words in the vocabulary but also substrings of these words.|
