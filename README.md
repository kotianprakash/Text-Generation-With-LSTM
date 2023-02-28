
# Text Generation using LSTM

In this project, I have taken first four chapters of moby dick as my dataset and divided them into small sequences of 26 words where 25 words are used as X and one word as y. I have trained the model on these short sequences to predict the next word. Atlast, I output user provided number of words after a selected sequence. For eg. The model can predict next 5 words after a given sequence.

#### Note: These results are obtained after hours of model training with different parameters. The model shared with this code is not fully optimized one so results will vary.


To use the LSTM model for text generation, follow these steps:

Prepare your training data: The LSTM model requires a corpus of text data to be trained on. You can use any text data that you have available, such as books, articles, or tweets.

Preprocess the data: Before training the LSTM model, you will need to preprocess the text data. This involves converting the text into a numerical representation that can be fed into the LSTM. You can use tools like Tokenization and Word Embeddings to help with this task.

Train the LSTM model: Once the data has been preprocessed, you can train the LSTM model. The model will learn the patterns in the text data and use these patterns to generate new text.

Generate new text: After the LSTM model has been trained, you can use it to generate new text. To do this, you will need to provide a starting seed for the model to generate text from. The model will then generate a sequence of text based on the patterns it has learned.