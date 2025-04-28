# Residual Networks (ResNets)

This project implements a deep residual network (ResNet) from scratch to address vanishing gradient problems and enable the training of very deep convolutional neural networks.  
It is part of **Week 2 (Course 4: Convolutional Neural Networks)** from the **Deep Learning Specialization** by **Andrew Ng** on Coursera.

##  Description

In this lab, I built a simplified version of a **Residual Neural Network (ResNet)** architecture.  
ResNets introduce **skip connections** that allow gradients to propagate more easily through very deep networks, solving the vanishing gradient problem and enabling successful training of deep models.

To keep the repository lightweight and within GitHub's upload limits, the large pretrained model file (`resnet50.h5`) has been excluded.  
If needed, you can easily download a standard ResNet-50 pretrained model from public sources like the [Keras Applications Repository](https://keras.io/api/applications/resnet/#resnet50-function) or from the official deep learning model hubs.

### Key Concepts Covered:
- Deep Convolutional Neural Networks (CNNs)
- Residual Blocks and Skip Connections
- Forward and Backward Propagation in ResNets
- Identity and Convolutional Shortcut Paths
- Building Deep Architectures Without Vanishing Gradients

##  Files Included

- `Residual_Networks.ipynb`: Jupyter notebook implementing a simple ResNet
- `resnets_utils.py`: Helper functions for building and training residual blocks
- `test_utils.py`, `outputs.py`, `public_tests.py`: Testing and utility scripts
- `datasets/`, `images/`, `models/`: (if present) supporting data and models

> ⚠️ This repository contains only my own implementation and strictly follows Coursera’s Honor Code.

##  Tools Used

- Python 3
- TensorFlow/Keras
- NumPy
- Matplotlib
- Jupyter Notebook

##  Course Info

This project is part of:
> [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)  
> Instructor: **Andrew Ng**  
> Course 4: Convolutional Neural Networks  
> Week 2: Residual Networks (ResNets)

##  License

This repository is intended for educational and portfolio purposes only.  
Please avoid using it for direct assignment submissions.

---

 Feel free to star this repository if you are passionate about building deep and efficient neural networks!
