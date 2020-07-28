# bob_dylan_lyric_generator
A Neural Net that predicts lyrics inspired by Bob Dylan

This is a test idea to see if a neural net can be trained to predict lyrics inspired by Bob Dylan.
The first notebook first scrapes bob dylan lyrics from metrolyrics.com and cleans it up to feed it to a NN.
It then tokenizes it and trains on a simple Embedding and LSTM network.
The model has been trained over multiple sessions on Google colab for GPU access. That is why epochs start training at 80%. 
It's just an inital implementation of the idea, I plan to work on it more in the future and improve the model.
