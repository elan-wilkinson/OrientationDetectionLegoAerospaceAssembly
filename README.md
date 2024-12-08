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

- Data Capture
- Synthetic Data Generation
- Randomization
- Data Annotation
- Train Test Split
- Model Training
- Data Normalization
- Transfer Learning
- Bounding Boxes
- Data Preprocessing
- Cropping
- Gradient Clipping
- Metrics

## Technologies

- **Programming Language:** Python
- **Libraries:** 
  - transformers
  - torchnn
  - YOLOv5
  - OpenCV detractraction
  - WandDB
  - CNN
  - FASTER RCNN
  
## Project Descriptio

A 3-dimension model was captured of the LEGO shuttle parts by iPhone 13 mini using Gaussian splatting using the application Scaniverse. The texture and model was then cleaned up in the 3D content tool Blender and then taken in the real time 3D visualization and game engine tool Unity 3D using the Perception package for synthetic data generation. This synthetic data was used to train a two-stage architecure, consisting of a first half that determines the bounding box of the object within the image and then passes a cropped image to the second half, a residual neural network model that leverages pretraining to learn features to determine an orientation in Euler degrees.  This approach is trained entirely on synthetic data but tested on real world data captured with iPhones and webcams with relatively high accuracy, and was chosen for its scalability in training models for other parts in a stream-lined approach.

Our thanks and appreciation go to our professor **Siamak Aram**.
