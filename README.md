# LatexOCR 

<img src="https://i.sstatic.net/bjrWg.png" alt="Latex" width="300"/>


## Table of Contents

1. [Background](#background)
2. [Project Description](#project-description)
3. [Team Members](#team-members)
4. [Sources](#sources)


## Background

As students we have had hard times writing down latex code for homeworks. The process is time consuming and overall not productive to the end goal. Thus, we attempted to create two OCR models that can enable future students and reserachers to be able to take a picture of their math either from their noteboook or online resources and be given the corresponding latex formula. While there are some promising models out there that attempt at this problem we decided to give it a try ourselves to create simplified latex document creation. We created two models:

**CNN-RNN based model:** Inspired by the work of Deng et al. (2016), we use a Convolutional Neural Network to extract image features, followed by a recurrent neural network for decoding the LaTeX output.

**Vision Transformer (ViT):** The rise of Transformers could not be ignored and we decided to attempt at our own implementation that treats the input image as a sequence of patches that then predicts the Latex code. 

## Project Description

This LaTeX OCR system aims to accurately convert images of mathematical equations into their corresponding LaTeX representations. Key features include:

- Support for both printed and handwritten mathematical expressions

- Handling of complex mathematical notation and symbols

- Comparison of CNN and ViT architectures for this task

- Evaluation using metrics such as accuracy and test loss

- Dataset of equation images paired with their LaTeX ground truth, similar to the approach used in previous works. 

## Team Members
- [Eunice Pak](https://github.com/eunicepak)
- [Emily Huang](https://github.com/emilyjhuang)
- [Finn Eskeland](https://github.com/FinnEsk)

## Sources
Thanks to the following previous works that helped us with ours!

[Tensorflow Image Captioning](https://www.tensorflow.org/text/tutorials/image_captioning)

[Pix2Tex](https://github.com/lukas-blecher/LaTeX-OCR)

[Attention Maps](https://github.com/lukemelas/PyTorch-Pretrained-ViT/issues/19)
