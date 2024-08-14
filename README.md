# Synthesis of Medical Images using Generative Adversarial Networks for Dataset Augmentation

In this project, I train a Deep Convolutional Generative Adversarial Network (DCGAN) to generate synthetic images of brain tumors from MRI scans. This is useful for medical image data augmentation for datasets that are too small to test machine learning algorithms on. 

This is based off the DCGAN tutorial from the [Tensorflow website](https://www.tensorflow.org/tutorials/generative/dcgan) which is then applied to Brain MRI Images from [this Kaggle dataset](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection). I used the Keras Sequential API to build this DCGAN.

<p align="center">
    <img src="https://github.com/user-attachments/assets/8e7a7b17-7471-4b6e-893c-c6c869439125" alt="Description" width="500"/>
</p>
<p align="center">Figures 1. A GIF of 16 generated brain scans through 150 epochs of training. This model is highly sensitive to the choice of hyperparamters (learning rate and batch size for example) and requires a more serious look to further improve the GAN architecture, choice of loss functions, and, importantly, how to address the small size (~150 images) of this dataset.</p>
