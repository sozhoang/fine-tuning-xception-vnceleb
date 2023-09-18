# Fine-tuning Xception model with VN-Celeb dataset

VN-Celeb is a dataset consists of 23,105 faces of over 1,000 Vietnamese individuals. All images have been cropped to extract the facial region and has 128x128 pixels RGB. Currently, the dataset has been fully publicly released for educational and research purposes [here](https://drive.google.com/drive/folders/1I3KXcGpmm6zpw_y07p-7wIKt5K08iOgc).

The fine-tuning model was written by Python in TensorFlow. The model was trained on the Google Colab platform and used the Triplet loss function.

After the training process, the model obtained evaluation results as follows:

![result](result.png)

The checkpoint model after 25 epochs has been released in [here](https://drive.google.com/drive/folders/1Gpcth0OSgYP84T9KUe4ebWWBrb7SIJ-R?usp=sharing).