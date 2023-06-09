# Detecting Alzheimer's Using Modern Attention based models
This project was a part of Computer Vision Course (CSCI-B 657) at Indiana University Bloomington

The aim of the project was to classify MRI scans into different categories of Alzheimer using attention models and state-of-the-art transformer models for computer vision. The goal was to understand how attention models work and know their advantages and disadvantages. Further we compared the performace of these transformer models with models which already have a strong hold in the field like VGGNet, ResNet and AlexNet and are known to perform very well for the past decade on medical images.
We used 2 transformer models called :- 
1. **_Vision Transformer (ViT)_** - Popularized by the paper Alexey Dosovitskiy and others (https://arxiv.org/abs/2010.11929), which stated that "The ViT model divides the input image into a sequence of non-overlapping patches and flattens them into a sequence of 1D vectors. These vectors are then fed into a Transformer encoder, which processes them to capture the spatial relationships between patches. The self-attention mechanism within the Transformer enables the model to attend to both local and global information within the image."
2. **_Compact Convolutional Transformer (CCT)_** - Compact Convolutional Transformers (CCT) are a variant of the Transformer model that combines convolutional neural networks (CNNs) with self-attention mechanisms. The CCT model aims to leverage the strengths of both architectures for efficient and effective image processing. It introduces compact convolutional layers, which reduce the computational complexity of standard convolutions. These layers are then integrated with the self-attention mechanism of Transformers to capture long-range dependencies in images. The CCT model has shown promising results in various image recognition tasks, offering a more compact and computationally efficient alternative to traditional CNNs while still benefiting from the expressive power of self-attention.

File Structure:

1. The paper.pdf file contains a detailed report of the project. It gives information about the data, methods, and results of the project.
2. The files in the materials folder contains all the models that were used for this project.
3. The materials folder also contains the dataset for this project.

<img width="822" alt="poster" src="https://github.com/coderop2/Detecting-Alzheimer-s-Using-Modern-Attention-based-models/blob/main/materials/poster.png">
