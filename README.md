# Detecting Alzheimer's Using Modern Attention based models
This project was a part of Computer Vision Course (CSCI-B 657) at Indiana University Bloomington

## Project Abstract:

Alzheimer’s disease is the most common cause for dementia (loss of memory and other cognitive abilities). Alzheimer’s disease is caused when some part of the brain cells is not working well. This is mainly by plaques and tangles. Plaques are deposits of a protein called “beta-amyloid” in spaces between nerve cells and tangles are twisted fibers of protein called “tau” that build inside neurons. These deposits can be seen in MRI scans but in the early stages it is very difficult to see them with naked eye. We propose a comparative study between attention models like Vision Transformer and Compact Convolutional transformer and state-of-the-art models like VGGNet, ResNet, and AlexNet to classify MRI images into 4 categories. Compact Convolutional Transformer gives better testing accuracy than vision transformers which show that convolutions work better than image patching. Out of all the models, VGGNet gives the highest accuracy of 74.59%. Attention models require a lot of data. We had limitations of data for this project and hence, attention models are not performing to their optimum.

## Introduction:
The aim of the project was to classify MRI scans into different categories of Alzheimer using attention models and state-of-the-art transformer models for computer vision. The goal was to understand how attention models work and know their advantages and disadvantages. Further we compared the performace of these transformer models with models which already have a strong hold in the field like VGGNet, ResNet and AlexNet and are known to perform very well for the past decade on medical images.
We used 2 transformer models called :- 
1. **_Vision Transformer (ViT)_** - Popularized by the paper Alexey Dosovitskiy and others (https://arxiv.org/abs/2010.11929), which stated that "The ViT model divides the input image into a sequence of non-overlapping patches and flattens them into a sequence of 1D vectors. These vectors are then fed into a Transformer encoder, which processes them to capture the spatial relationships between patches. The self-attention mechanism within the Transformer enables the model to attend to both local and global information within the image."
2. **_Compact Convolutional Transformer (CCT)_** - Compact Convolutional Transformers (CCT) are a variant of the Transformer model that combines convolutional neural networks (CNNs) with self-attention mechanisms. The CCT model aims to leverage the strengths of both architectures for efficient and effective image processing. It introduces compact convolutional layers, which reduce the computational complexity of standard convolutions. These layers are then integrated with the self-attention mechanism of Transformers to capture long-range dependencies in images. The CCT model has shown promising results in various image recognition tasks, offering a more compact and computationally efficient alternative to traditional CNNs while still benefiting from the expressive power of self-attention.

## File Structure:

Files:
1. The paper.pdf file contains a detailed report of the project. It gives information about the data, methods, and results of the project.
2. poster.pptx is the presentation file used ro presenting at school/conference
3. materials/cv_vit.ipynb :- Notebook for the ViT model
4. materials/cv_cct.ipynb :- Notebook for the CCT model
5. materials/cv_cnn_vggpret.ipynb :- Notebook for the 5 layered CNN network and VGG pretrained on Imagenet weights model
6. materials/cv_vgg.ipynb :- Notebook for the VGG model trained from scratch
7. materials/cv_alex.ipynb :- Notebook for the Alexnet model trained from scratch
8. materials/cv_resnet.ipynb :- Notebook for the pretrained Resnet on Imagenet weights model
9. The data used in this project is contained in the material/Data folder
10. Authors of this project are in the file authors.txt


## How to Run the files:
### Steps:
1. Replace/remove the mention of the colab/google drive
2. Place the folder path to the dataset in your local systems. NOTE: Some places we are using separate images for the purpose of visualization so please change the path there also.
3. All the notebooks are ready to run on a single command and not much changes are required

## About the data:
- The data is divided into 3 folders.
- First is the training set where we have made changes so as to generate more data for the minority class and another is train2 folder which has duplicate images as examples for 2 classes which have the least examples to try and cover the lack of data. What we observed is that although there is redundancy in information available the models learn pretty well in presence of duplicate data.


<img width="822" alt="poster" src="https://github.com/coderop2/Detecting-Alzheimer-s-Using-Modern-Attention-based-models/blob/main/materials/poster.png">
