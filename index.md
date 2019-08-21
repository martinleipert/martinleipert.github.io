---
layout: page
title: Martin Leipert 
subtitle: - Medical Engineering MSc Graduate
---

Hi I am Martin Leipert,
being a passionate Coder, I am looking for new opportunities. Always open to new topics, especially in the area of Medical Informatics. You will find my CV and some example projects of mine here.

You will finde my CV [here](curriculum) or you can download it here as [PDF](files/curriculum.pdf).

# Example Projects

What I already worked with? The answer is here. 

## Augmented Reality 

I developed a Unity visualization for a robotic simulation. The simulation uses untextured CAD Files. 
From the visulization I created a 

## Deep Learning

In my research intern at the Pattern Recognition Lab at FAU Erlangen-Nuremberg I trained Neural Networks to retrieve medieval notary documents from a large document collection. In the collection only about 3.2 % are notary documents, so in training and retrieval class imbalance is quite severe. Additionally I trained a network (U-Net) to segment them. In both settings I used oversampling, different (dynamic) augmentations and loss functions (Cross Entropy, Negative Log Likelihood) to counter the class imbalance in segmentation and retrieval. 

### Best Settings for Classification

Network         | Augmentation    | Loss                        | Sensitivity   | Specifity | F-Value   | 
---------------:|:---------------:|:---------------------------:|:-------------:|:---------:|:---------:|
ResNet 50       | moderate warp   | Cross-Entropy               | 0.938         | 0.959     | 0.949     |
DenseNet 121    | moderate warp   | Negative Log Likelihood     | 0.942         | 0.971     | 0.956     |

### Selected Segmentation Results

![Focal Loss](img/0745_focal.png =250x)
![BCE Loss](img/0745_bce.png =250x)
![Dice Loss](img/0745_dice.png =250x)

Red is background, green is text and blue is the notary sign.
Although the result of Focal Loss seem bad at first glance, after applying the softmax they were equal / better than bce and dice loss.
 

## Image Registration

In my Bachelor's thesis I worked on a modification of an image registration algorithm. It is designed for real time 2D-2D-Registration in Digital Subtraction Angiography.
