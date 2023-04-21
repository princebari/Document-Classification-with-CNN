# Document-Classification-with-CNN

![image](https://user-images.githubusercontent.com/115543070/233545740-bb4db35c-4796-4569-aecd-8dc047b80586.png)


In this project, we have implemented two models for document classification using Convolutional Neural Networks (CNNs). The first model is a 1D CNN with word embedding, and the second model is a 1D CNN with character embedding. Both models were trained on the preprocessed dataset containing a total of 18,828 text documents categorized into 20 classes. The objective of using two models is to compare their performance and identify the optimal approach for document classification.

The 1D CNN with word embedding model involves training the CNN on the preprocessed text data, where each word is represented by a dense vector. The word embedding layer helps to capture the semantic meaning of words, which can improve the accuracy of the classification model. On the other hand, the 1D CNN with character embedding model involves representing each character in the text with a dense vector, which is then fed into the CNN model. This approach is useful when dealing with out-of-vocabulary words or misspelled words that are not recognized by a word embedding layer.

Dataset link : https://drive.google.com/file/d/1rxD15nyeIPIAZ-J2VYPrDRZI66-TBWvM/view
