# LatexOCR 

<img src="https://i.sstatic.net/bjrWg.png" alt="Latex" width="300"/>


## Table of Contents

1. [Background](#background)
2. [Project Description](#project-description)
3. [Team Members](#team-members)


## Background

Converting mathematical expressions into LaTeX code is a challenging task in the field of Optical Character Recognition (OCR). Traditional OCR methods often struggle with the complex spatial relationships and diverse symbols found in mathematical notation1. Recent advancements in deep learning, particularly in computer vision and natural language processing, have opened new avenues for tackling this problem.

Our project builds upon these advancements by implementing two state-of-the-art approaches:

**CNN-based model:** Inspired by the work of Deng et al. (2016), we use a Convolutional Neural Network to extract image features, followed by a recurrent neural network for decoding the LaTeX output.

**Vision Transformer (ViT):** Leveraging the success of transformers in various domains, we implement a ViT model that treats the input image as a sequence of patches and directly predicts the LaTeX code. 

## Project Description

- This LaTeX OCR system aims to accurately convert images of mathematical equations into their corresponding LaTeX representations. Key features include:

- Support for both printed and handwritten mathematical expressions

- Handling of complex mathematical notation and symbols

- Comparison of CNN and ViT architectures for this task

- Evaluation using metrics such as accuracy and BLEU score

- The project utilizes a dataset of equation images paired with their LaTeX ground truth, similar to the approach used in previous works3. We preprocess the images and implement data augmentation techniques to improve model generalization.

- Our implementation is built using Python and popular deep learning frameworks. We provide scripts for training, evaluation, and inference, allowing users to easily experiment with the models and generate LaTeX code from new equation images.

## Team Members
- [Eunice Pak](https://github.com/eunicepak)
- [Emily Huang](https://github.com/emilyjhuang)
- [Finn Eskeland](https://github.com/FinnEsk)
