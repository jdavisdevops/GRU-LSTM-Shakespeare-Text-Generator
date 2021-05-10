# LSTM-Shakespeare-Text-Generator
LSTM-Shakespeare-Text-Generator is a GPU and TF.Data API boosted model that creates new unique text based off of Shakespearian works hosted at https://storage.googleapis.com/download.tensorflow.org/data/shakespeare.txt

It uses an LSTM layer and returns final sequences through the Keras Model Subclassing API to define the forward pass to the final Dense layer to predict the next word of a sentence. It is able to create newly formed and well formatted paragraphs in the playwright's style.
