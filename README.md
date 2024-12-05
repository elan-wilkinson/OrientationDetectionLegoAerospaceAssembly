# Orientation Detection of Lego Aerospace Assembly

## Team 8 AAI-521: Applied Computer Vision for AI

**Project Title:** Position and Orientation Detection of Lego Shuttle Assembly

**Project Status:** Active

## Project Intro/Objective

Music is a form of art that is ubiquitous and has a rich history. Different composers have created music with their unique styles and compositions. However, identifying the composer of a particular piece of music can be a challenging task, especially for novice musicians or listeners. The proposed project aims to use deep learning techniques to identify the composer of a given piece of music accurately.

The primary objective of this project is to develop a deep learning model that can predict the composer of a given musical score accurately. The project aims to accomplish this objective by using two deep learning techniques: Long Short-Term Memory (LSTM) and Convolutional Neural Network (CNN). Classification will be performed for .mid files for four composers; Bach, Beethoven, Chopin, and Mozart.

## Contributors

- **Pallav Kamojjhala**
- **Elan Wilkinson**
- **Ahmad Milad**

## Methods Used

- Data Cleaning, Preparation, and Preprocessing
- Long Short-Term Memory
- Convolutional Neural Networks
- Classification
- Deep Learning

## Technologies

- **Programming Language:** Python
- **Libraries:** 
  - Pretty_Midi
  - Music21
  - Matplotlib
  - Tensorflow
  - Keras

## Project Description

Data was preprocessed into notes by instrument as well as the average of notes on a 10 frames per second interval. Overrepresented classes were undersampled, and sequence lengths were padded and clipped to create a homogenous data shape for processing. Input data was subsequently fed into separate LSTM and CNN models, and further evaluation and hyperparameter tuning was performed in the pursuit of optimal correct classification of the composer giving a piece of music stored in a .mid file.
## Acknowledgments

Our thanks and appreciation go to our professor **Siamak Aram**.
