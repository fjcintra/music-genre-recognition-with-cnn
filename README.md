# Music Genre Recognition with Tensorflow

This personal project intends to develop a model capable of recognizing music genres.

The first model was built with three dense layers. The use of L2 regularizers and Dropout technique were used to avoid 
overfitting.

The second model uses convolutional neural networks (CNN). By passing a MFCC spectrogram the model was able to identify 
patterns on the audio tracks and achieve better accuracy than the MLP model.

The third and last trained model uses layers based on LSTM cells. The results were similar to the CNN model but with
far greater computational cost.

# Next steps

As the next step to this project, I intend to try some data augmentation techniques in order to create a bigger training
dataset since we have only 100 samples for each genre.