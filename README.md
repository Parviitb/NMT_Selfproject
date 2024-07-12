Hello all, I am Parv Maheshwari and this is a project for developing a neural machine translator that translates german sentences to english. 
I have used a Seq2Seq architecture with LSTM layers. Firstly employing tokenization and padding to properly preprocess the data, procured from a public website linked in the project. I
have used tokenization to convrt German and English sentences into sequences of integers using Keras' Tokenizer.
The Encoder is an Embedding layer followed by an LSTM layer that processes German sentences and the decoder is an LSTM layer followed by a Dense layer that generates English translations.
Then I have optimized the model using RMSprop and sparse categorical crossentropy. I trained the model for 30 epochs with a batch size of 512, saving 
the best model based on validation loss.

Overall, the project focuses on building a basic NMT model using a Seq2Seq architecture and training it on a German-English dataset.
