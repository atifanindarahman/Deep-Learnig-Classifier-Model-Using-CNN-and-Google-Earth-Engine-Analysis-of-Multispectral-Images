# XRay Image Classifier Using CNN (ResNet50)

## Overview
This project involves designing and training a **deep learning classifier** to detect lung conditions from X-ray images. The model classifies chest X-ray images into four categories:

- **COVID-19 Positive**  
- **Normal**  
- **Lung Opacity**  
- **Viral Pneumonia**

The primary objective was to develop a model that accurately identifies these conditions from X-ray images, assisting in rapid diagnosis and healthcare support.


## Dataset
The model was trained, tested, and validated on the **COVID-19 Radiography Database**, which consists of approximately **21,165 X-ray images** spanning the four classes mentioned above.


## Model Architecture
The deep learning model was implemented using **ResNet50**, a state-of-the-art convolutional neural network (CNN) architecture known for strong performance in image classification tasks.

- **Input:** X-ray images  
- **Output:** One of four classes (COVID-19, Normal, Lung Opacity, Viral Pneumonia)  
- **Training Steps:** 10 steps per epoch  
- **Epochs:** 30  
- **Validation Steps:** 16

The model’s performance was evaluated using standard image classification metrics and visualized through a **confusion matrix**.


## Performance
- **Accuracy:** ~80.76%  
- The model demonstrates strong capability in distinguishing between COVID-19, Viral Pneumonia, Lung Opacity, and Normal lung X-rays.


## Platform
- **Environment:** Jupyter Notebook  
- **Libraries:** TensorFlow, Keras, NumPy, Pandas, Matplotlib, and other standard Python ML libraries


## Notes
- This project is intended for **educational and research purposes**.  
- The model performance may vary depending on system configurations and dataset availability.  
- Proper preprocessing of images is crucial for maintaining model accuracy.
