# BirdCLEF2021
Bird classification

These are Kaggle notebooks related to the BirdCLEF2021 competition (https://www.kaggle.com/c/birdclef-2021).

- bird-dataset-20s.iypnb: used to obtain a mel spectrogram dataset, composed of 20s long audio samples
- bird_classificator.iypnb: it's the main code, where data is prepared and the model is trained
- load_model.iypnb: the code used to submit a trained model to the kaggle competition
- ResNet34.pt, ResNet50.pt: the best models produced:
- - ResNet34.pt: on test set identifies 6.5% birds and 91% nocalls; private leaderboard score F1 = 0.497
- - ResNet50.pt: on test set  identifies 10% birds and 91% nocalls; private leaderboard score F1 = 0.489
- Birdcall_identification.pdf: written report
