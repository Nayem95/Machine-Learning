# Text-summarization
The objective of this project is to build a model that can create relevant summaries for reviews written about fine foods sold on Amazon. This dataset contains above 500,000 reviews, and it is hosted on Kaggle.
To build our model we will use a two-layered bidirectional RNN(reccurent nueral networks) with LSTMs(long short term memory) on the input data and two layers, each with an LSTM using bahdanau attention on the target data. Jaemin Cho's tutorial for seq2seq was really helpful to get the code in working.
The sections of this project are:

1.Inspecting the Data
2.Preparing the Data
3.Building the Model
4.Training the Model(training part is not added yet)
5.Making Our Own Summaries

