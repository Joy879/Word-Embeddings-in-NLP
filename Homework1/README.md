_Based on CBoW implementation_

![cbpw](https://user-images.githubusercontent.com/70502261/178653742-41533817-83f2-43a3-9275-3ae017f0242f.png)

### Questions


#### 1. What is the difference between Sigmoid and Softmax activation?

||Sigmoid|Softmax|
|---|---|---|
|Use cases|Used for _binary classification_|used for _multiclass classification_|
|Probabilities|the _sum of probabilities does not have to be one_ When using it for classification, the class to be selecetd will not necessarily have a higher probability than the other class.|the _sum of all probabilities has to be 1_. When using it for multiclass classification, the class to be selecetd will have a higher probability than other classes.|


#### 2. How does cross-entropy loss function change for Binary Classification task vs Multi-Class Classification task?

#### 3. On the Lab Notebook, try running the code with a different dataset of your choice.


   [Answers](https://github.com/Joy879/Word-Embeddings-in-NLP/blob/main/Homework1/CBoW_training_new_data.ipynb)

#### 4. Apply PCA/T-SNE or both to reduce the N dimensions to 2D space and visualize the word embeddings. Please write-up your observations on the same.
[T-SNE reference](https://www.kaggle.com/code/jeffd23/visualizing-word-vectors-with-t-sne/notebook)
[PCA reference](https://towardsdatascience.com/visualization-of-word-embedding-vectors-using-gensim-and-pca-8f592a5d3354)
