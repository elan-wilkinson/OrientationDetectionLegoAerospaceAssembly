# Position and Orientation Detection of LEGO Shuttle Assembly

## Team 8 AAI-521: Applied Computer Vision for AI

**Project Title:** Position and Orientation Detection of LEGO Shuttle Assembly

**Project Status:** Active

## Project Intro/Objective

The detection of orientation of pieces of an assembly is a crucial task for manufacturing and both human and robotic building tasks. If the placement of a camera is known relative to an environment, person, larger structure the piece is being mounted to, or another piece, the orientation data becomes meaningful, and can be contextualized as being in the correct or incorrect orientation relative to the camera and other known parts. This task has broad applications to aerospace engineering, vehicle manufacture, industrial environments, assembly of medical devices and others. As the proprietary and specific nature of the parts in these domains can make them difficult to source, placeholder representations of these were used in the form of LEGO shuttle partially assembled pieces.

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
