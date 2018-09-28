# Facial Emotion Recognition

## Table of contents:
1. Introduction.  
2. Prerequisites.  
3. How to run:  
 a. Replicating the model.    
 b. Live Emotion Recognition.  
4. Future Iterations.  

## 1. Introduction.
A baby is able to recognize it's parent's faces when it is about a couple of weeks old. The baby grows and matures and by the time it is about two months old, it starts to display social cues. It is able to understand basic emotions like a smile.

This project involves training a neural network to do just that, recognize facial emotions. We owe our ability to do that to the wonderful process of evolution. Replicating this is certainly not easy but possible.

![Emotion Recognition](https://cdn-images-1.medium.com/max/750/1*rSOC2rIKZ3NSkE3j1MetdQ.png)  
Image only for representational purposes only and actual implementation may vary.

For this project, I will be using Google Colab. For those who are unaware, it is a research project created to disseminate ML education and you can train your neural networks on their Tesla K80 GPUs. It sure speeds up the entire training process.

On running Live-Emotion-Recognition.py, your webcam fires up and starts locating faces in real-time, these faces are extracted and are assessed by the model we trained.

## 2. Prerequisites.  
Make sure that you install the following libraries:
  + matplotlib
  + numpy
  + sklearn
  + keras

## 3. How to run.
### a. Replicating the model:
If you are interested in modifying this model and training it yourself, then please feel free to do so.    
i. Download the IPython Notebook.  
ii. Open [google Colaboratory.](https://colab.research.google.com/ "Colab time")  
iii. Upload this notebook from your system.  
iv. Download the dataset and upload it into your GDrive.
v. Get creative and aim for better results.

### b. Live emotion recognition.
Make sure that you have installed all the aforementioned libraries..
Due to Github's upload limit on file sizes, I was unable to upload the weights of my trained neural network. Make sure you download [this folder](https://drive.google.com/open?id=1-gEWdcFL0tpkIbYKzLoYXRA4qeG-6Ot6) and place it in the root directory.
Then download and execute the python file and you are good to go.

## 4. Future Iterations.
I am closing this project for now, even though the accuracy obtained was barely A-division. Though as I will learn more, I will keep implementing new techniques and models to improve the accuracy for facial emotion recognition. Also, I will be updating the UI of the Live Face Recognition program.
