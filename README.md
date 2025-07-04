🧠 Next Word Prediction Using LSTM

This project aims to develop a deep learning model for predicting the next word in a given sequence of words using Long Short-Term Memory (LSTM) networks — a type of Recurrent Neural Network (RNN) that excels at learning long-term dependencies in sequential data.
We train the model on the rich and stylistically complex text of Shakespeare's Hamlet , providing a compelling challenge for language modeling tasks.

🚀 Project Overview
1. Data Collection
    We use the full text of Hamlet by William Shakespeare as our training dataset. This provides a rich source of structured English prose ideal for sequence prediction.

2. Data Preprocessing
    Tokenize the text into individual words.
    Convert sequences of words into numerical representations.
    Pad sequences to ensure uniform input lengths.
    Split the data into training and testing sets.
   
4. Model Building
    An LSTM-based architecture is used:

    Embedding Layer : Converts word indices into dense vectors.
    LSTM Layers : Two stacked LSTM layers to capture sequential context.
    Dense Output Layer : Softmax-activated layer to predict the probability distribution over the vocabulary.
   
4. Model Training
    Trained using categorical cross-entropy loss .
    Includes Early Stopping to prevent overfitting by monitoring validation loss.
5. Model Evaluation
    The model is evaluated using custom test sentences to assess its ability to predict the next word accurately.

6. Deployment
    A web interface is built using Streamlit , allowing users to input a sequence of words and receive real-time predictions from the trained model.

APP URL : https://3-lstm-rnn-next-word-prediction.streamlit.app/
