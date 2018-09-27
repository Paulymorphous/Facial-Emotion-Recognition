# Facial Emotion Recognition

## Table of contents:
1. Introduction.
2. How to run:
   a. replicate the model.
   b. Live Emotion Recognition
3. Future Iterations.

## 1. Introduction
A baby is able to recognize it's parent's faces when it is about a couple of weeks old. The baby grows and matures and by the time it is about two months old, it starts to display social cues. It is able to understand basic emotions like a smile.

This project involves training a neural network to do just that, recognize facial emotions. We owe our ability to do that to the wonderful process of evolution. Replicating this is certainly not easy but possible.

![Emotion Recognition](https://cdn-images-1.medium.com/max/750/1*rSOC2rIKZ3NSkE3j1MetdQ.png)

For this project, I will be using Google Collab. For those who are unaware, it is a research project created to disseminate ML education and you can train your neural networks on their Tesla K80 GPUs. It sure speeds up the entire training process.

Live-Emotion-Recognition.py identifies faces and creates a bounding box around them. Then it extracts the face to identify the emotion it is showing.
