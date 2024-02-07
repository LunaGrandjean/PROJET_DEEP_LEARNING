# Deep Learning Project: Marine Species Identification

### Overview
This project aims to develop a deep learning model for the identification of marine species present at specific locations. The project is conducted in collaboration with an environmental conservation association. The dataset consists of images of several marine species, annotated with bounding boxes.

### Dataset
The dataset used in this project is available for download here. It includes images of various marine species classified by their Latin names. The images are annotated with bounding boxes, facilitating object detection tasks.

### Project Structure
- Data Preparation:
  -   The dataset is preprocessed, and images are cropped to contain only one species per image based on the annotated bounding boxes.
- Classification:
  - From Scratch: A convolutional neural network (CNN) model is developed from scratch using TensorFlow to classify each species individually.
  - Transfer Learning: Transfer learning is applied using pre-trained models such as VGG16 to improve classification performance.
  - Data Augmentation: External libraries or TensorFlow's image data augmentation capabilities are used to augment the dataset, enhancing model generalization.
  - Object Detection: A separate model is trained for object detection tasks using TensorFlow or YOLOv8, utilizing annotated bounding boxes for training.
  - Evaluation: The models are evaluated on a separate test dataset, and performance metrics are calculated to assess model effectiveness.

### Technologies Used
- TensorFlow
- Keras
- Python
- OpenCV
- ImageDataGenerator

### Contributors
- AKHBARI Darius
- ADDI Mohammed
- GRANDJEAN Luna
