# CAPSTONE_PROJECT
CAPSTONE is an AI Image Captioning Predictor, it uses CNN-Resnet50 and LSTM for training on Flicker8k dataset of images to generate captions for them.

The Model contains:

    Image model: for reducing image of high dimensions into selected features.
    Language model: for creating output as embeddings to reduce complexity of model.
    Final model: which will concatenate results of both this model and will use LSTM layer and Time 		Distributed layer for doing final_predicttions.

One of example of final prediction:

![Alt text](test_image.jpg?raw=true "Title")

Two dogs running running white dog dog a brown dog the grass .
