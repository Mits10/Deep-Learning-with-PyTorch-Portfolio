# 🧠 Deep Learning with PyTorch --- Portfolio

This repository showcases my implementations of core deep learning
concepts using PyTorch, including CNNs, RNNs, and Transformers. Each
project focuses on both theoretical understanding and practical
application.

------------------------------------------------------------------------

## 🚀 Skills Demonstrated

-   PyTorch (custom models, training loops, datasets)
-   Neural network architectures (MLP, CNN, RNN, Transformer)
-   Data preprocessing and loading
-   Model evaluation and visualization
-   Experimentation and debugging

------------------------------------------------------------------------

## 📂 Repository Structure

    .
    ├── projects/          # Individual deep learning projects
    ├── notebooks/         # Exploratory analysis and experiments
    ├── common/            # Shared utilities (training loops, helpers)
    ├── assets/            # Images, plots, demo outputs
    ├── requirements.txt   # Dependencies
    └── README.md

------------------------------------------------------------------------

## 📌 Projects Overview
```
  -----------------------------------------------------------------------
  Project           Description               Key Concepts
  ----------------- ------------------------- ---------------------------
  MNIST Classifier  Compare MLP vs CNN on     CNN, training loops
                    digit classification      

  Image Classifier  CNN on CIFAR-10 dataset   Conv layers, augmentation

  Text Generator    Character-level RNN for   RNN, sequence modeling
                    text generation           

  Transformer       Basic transformer         Attention, embeddings
                    implementation            
  -----------------------------------------------------------------------
```
------------------------------------------------------------------------

## 📁 Example Project Structure

    projects/01_mnist_classifier/
    ├── model.py
    ├── train.py
    ├── config.yaml
    ├── README.md
    └── results/

Each project includes: - Problem description - Model architecture -
Training approach - Results and visualizations - Instructions to run

------------------------------------------------------------------------

## ⚙️ Installation

``` bash
git clone https://github.com/Mits10/Deep-Learning-with-PyTorch-Portfolio.git
cd Deep-Learning-with-PyTorch-Portfolio
pip install -r requirements.txt
```

------------------------------------------------------------------------

## ▶️ How to Run

Example:

``` bash
python projects/01_mnist_classifier/train.py
```

(Optional: include arguments)

``` bash
python train.py --model cnn --epochs 10
```

------------------------------------------------------------------------

## 📊 Results

Training/validation loss curves - Accuracy
plots - Sample predictions

Example:

![Accuracy Plot](assets/images/accuracy.png)

------------------------------------------------------------------------

## 🧪 Experiments & Learnings

 - CNN significantly outperformed MLP on
image data - Regularization improved generalization - Hyperparameter
tuning impacted convergence speed

------------------------------------------------------------------------

## 📈 Future Improvements

-   Added more advanced architectures (e.g., ResNet, BERT)
-   Implemented experiment tracking (e.g., TensorBoard)
-   Improved model performance with tuning

------------------------------------------------------------------------

## ⭐ Notes

This repository is part of my learning journey in deep learning.\
Code is written from scratch to reinforce understanding of core
concepts.
