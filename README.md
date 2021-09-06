# Sentiment_Analysis_Using_Tensorflow
 
 Sentiment analysis is a NLP technique used to interpret the emotion behind the text
 IMDb dataset is used here which has reviews of the movies in one column and sentiments as labels in another column.
 After preprocessing the data , word embeddings of length 16 was done with the help of preprocessing function of Keras.
 
 Model used has four layers: Word embedding layer, global average pooling layer, the head having the dense layers with sigmoid activation function in the output layer.
