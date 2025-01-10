# transfer-learning-fine-tuning-dogs-vs-cats

This repository demonstrates transfer learning with fine-tuning using the pre-trained VGG16 model for binary classification of "Dogs vs. Cats" images. Fine-tuning is applied selectively to higher layers (from block5_conv1 onwards), while earlier layers are frozen to leverage pre-learned features.

The project highlights:

1.Dataset Handling:

Automatic download and extraction of the "Dogs vs. Cats" dataset.
Preprocessing and normalization for training and validation datasets.

2.Transfer Learning:

Fine-tuning layers of the VGG16 model starting from block5_conv1.
Additional dense layers for binary classification.

3.Training:

RMSprop optimizer with a low learning rate for stable fine-tuning.
Training and validation over multiple epochs.

4.Visualization:

Plots of training and validation accuracy/loss to track the model's performance.
