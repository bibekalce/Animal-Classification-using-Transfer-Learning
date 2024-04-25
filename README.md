# **Animal Classification using Transfer Learning**

This repository contains the code for a deep learning project focused on classifying images of animals into 151 different categories using transfer learning techniques. The project utilizes the Animal dataset, which consists of 6270 RGB images of animals, each with a resolution of 224x224 pixels.

## **Dataset:**
The Animal dataset can be accessed from the following link: [Animal Dataset](link_to_dataset)
git clone https://github.com/your_username/animal-classification.git


The dataset contains images of 151 different animal types, with each animal category represented by a separate folder containing images belonging to that category.

## **Dependencies:**
- PyTorch
- Torchvision
- EfficientNet-PyTorch
- MobileNetV2 (included in torchvision)

This code trains the model using transfer learning with MobileNetV2 and EfficientNet-b4 architectures. The training process will automatically download the required pre-trained weights for EfficientNet-b4.

Once training is complete, you can test the trained model using the test script:

animal-classification/
│
├── data/                  # Directory containing the Animal dataset
│   ├── acinonyx\-jubatus/
│   ├── aethia\-cristatella/
│   ├── ...
│   └── vultur\-gryphus/
│
├── models/                # Directory containing model definitions
│   ├── mobilenetv2.py
│   └── efficientnet.py
│
├── train.py               # Script for training the model
├── test.py                # Script for testing the trained model
└── README.md              # This README file
