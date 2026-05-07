# Audio Multi-Layer Perceptron Model 

With the rise of AI mechanisms in music streaming platforms, optimizing user experiences is easier than ever. Having algorithms that can classify music into different genres and make song recommendations based on what a user’s favorite genre can be powerful tool for user retention. This repo focuses on streamlining genre classification for audio clips, with an end goal of our model to classify genres for newly released music. 

**DATA DESCRIPTION**

The train data set came from the GTZAN audio dataset, which is a widely used audio dataset that contains 30sec instrumental .wav files and spectrogram images for 10 different genres. The test set came from real-world music, clipped into 30sec .wav files for the same 10 genres that was reflected in the GTZAN dataset. 


**MODEL DESCRIPTION**

Multi-layer perceptron model, inputting .wav audio clips and outputting predicted genre classification. Because of the disconnect between GTZAN audio clips (train set) and real world song clips (test set), the model architecture is very generalizable for more accurate genre predictions for real-world songs.
