# Deep_Learning_Applications

This repository contains a collection of deep learning projects, each demonstrating different architectures, techniques, and applications. Below is a summary of each project:

---

## 1. Chatbot using Transformer

A conversational AI chatbot built using the Transformer architecture, trained on the Cornell Movie-Dialogs Corpus.  
- **Features:**  
  - Full input pipeline: preprocessing, data loading, masking, embeddings, multi-head attention, encoder/decoder, and training.
  - Visual explanations of positional encoding, attention, optimizer, and architecture.
- **How to Run:**  
  - Open `Chatbot_using_Transformer.ipynb` in Google Colab (GPU recommended).
  - Dataset: Cornell Movie-Dialogs Corpus (included in the subfolder).
- **Main File:**  
  - `Chatbot_using_Transformer.ipynb`

---

## 2. Feature Maps Visualization (ResNet18 & VGG16)

Visualizes feature maps from intermediate layers of pretrained ResNet18 and VGG16 models.
- **Features:**  
  - Shows how input images are transformed at different layers.
  - Useful for understanding CNN internals.
- **How to Run:**  
  - Open the respective notebooks in each folder.
- **Main Files:**  
  - `Visualize_filter_learning_2.ipynb` (ResNet18)
  - `Visualize_filter_learning.ipynb` (VGG16)

---

## 3. Mini ResNet16 From Scratch

Implements a 16-layer ResNet from scratch.
- **Features:**  
  - Custom architecture, image augmentation, learning rate scheduling.
  - Training and test accuracy logs, overfitting analysis.
- **How to Run:**  
  - Open `ResNet_16_layer.ipynb` in a Jupyter environment.
- **Main File:**  
  - `ResNet_16_layer.ipynb`

---

## 4. Neural Network From Scratch

A simple neural network built using only NumPy, trained on the `make_moons` dataset.
- **Features:**  
  - Manual implementation of forward and backward propagation.
  - Visualizes loss and decision boundaries.
- **How to Run:**  
  - Open `Neural_Network_with_numpy.ipynb`.
- **Main File:**  
  - `Neural_Network_with_numpy.ipynb`

---

## 5. Simple Diabetes Check

A feedforward neural network for binary classification of diabetes presence.
- **Features:**  
  - Data normalization, custom PyTorch dataset, and dataloader.
  - Multi-layer perceptron with sigmoid/tanh activations.
- **How to Run:**  
  - Open `FFNN_Application.ipynb`.
  - Uses `diabetes.csv` as input data.
- **Main File:**  
  - `FFNN_Application.ipynb`

---

## 6. Transfer Learning

Binary image classification (ants vs. bees) using transfer learning with pretrained ResNet-18.
- **Features:**  
  - Only the final layer is retrained.
  - StepLR scheduler for learning rate decay.
  - High test accuracy, no overfitting.
- **How to Run:**  
  - Open `Transfer_Learning.ipynb`.
  - Dataset: `hymenoptera_data` (included).
- **Main File:**  
  - `Transfer_Learning.ipynb`

---

## 7. Variational AutoEncoder

Implements a Variational AutoEncoder (VAE) for unsupervised learning and generative modeling.
- **Features:**  
  - Custom VAE architecture, loss function combining BCE and KL divergence.
  - Visualizes reconstructions and generated samples at different epochs.
- **How to Run:**  
  - Open `Variational_Auto_Encoder.ipynb`.
- **Main File:**  
  - `Variational_Auto_Encoder.ipynb`

---

## General Notes

- All projects are implemented as Jupyter notebooks for easy experimentation and visualization.
- Most projects include sample images, logs, and results for reference.
- For best results, use Google Colab or a local environment with GPU support for training deep models.