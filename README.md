# Position and Orientation Detection of LEGO Shuttle Assembly

## Team 8 AAI-521: Applied Computer Vision for AI

**Project Title:** Position and Orientation Detection of LEGO Shuttle Assembly

**Project Status:** Active

## Project Intro/Objective

The detection of orientation of pieces of an assembly is a crucial task for manufacturing and both human and robotic building and inspection tasks. If the placement of a camera is known relative to an environment, person, larger structure the piece is being mounted to, or another piece, the orientation data becomes meaningful, and can be contextualized as being in the correct or incorrect orientation relative to the camera and other known parts. This task has broad applications to aerospace engineering, vehicle manufacture, industrial environments, assembly of medical devices and others. As the proprietary and specific nature of the parts in these domains can make them difficult to source, placeholder representations of these were used in the form of LEGO shuttle partially assembled pieces.

## Contributors

- **Ahmad Milad**
- **Elan Wilkinson**
- **Pallav Kamojjhala**

## Methods Used

- Data Capture
- Synthetic Data Generation
- Randomization
- Data Annotation
- Data Preprocessing
- Train Test Split
- Transfer Learning
- Model Training
- Two-stage Model
- Bounding Boxes
- Cropping
- Residual Neural Network
- Metrics
- Live Data Integration

## Technologies

- **Programming Language:** Python
- **Models and Libraries:** 
  - transformers
  - PIL
  - OpenCV
  - PyTorch
  - YOLOv5
  - OpenCV detractraction
  - WandDB
  - FASTER RCNN
  - ResNet
- **Applications:**
  - Scaniverse
  - Blender
  - Unity3D

## Video Sample
  

https://github.com/user-attachments/assets/43b66cd2-53b1-48c0-86ef-15c5c899971b



  
## Project Description

A 3-dimension model was captured of the LEGO shuttle parts by an iPhone 13 mini using Gaussian splatting using the application Scaniverse. The texture and model was then cleaned up in the 3D content tool Blender and then taken into the real-time 3D visualization and game engine tool Unity 3D using the Perception package for synthetic data generation. This synthetic data was used to train a two-stage architecure, consisting of a first half that determines the bounding box of the object within the image and then passes a cropped image to the second half, a residual neural network model that leverages transfer learning in addition to training on the generated dataset to determine an orientation in Euler degrees.  This approach is trained entirely on synthetic data but tested on real world data captured with iPhones and webcams with relatively high accuracy, and was chosen for its scalability in training models for other parts in a stream-lined approach. After validating the models on static annotated real world images, the models were then tested in a live context from streamed camera data with high accuracy and performance that demonstrated confident capability for use in live applications.

Our thanks and appreciation go to our professor **Siamak Aram**.
