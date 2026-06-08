# Generative AI & Probabilistic Models 

## Overview

This repository contains implementations of various Generative AI, Deep Learning, and Probabilistic Graphical Models using TensorFlow, PyTorch, Scikit-Learn, and PGMPY.

The experiments cover Generative Adversarial Networks (GANs), Variational Autoencoders (VAEs), Bayesian Networks, Hidden Markov Models (HMMs), Gaussian Mixture Models (GMMs), Transfer Learning with Pre-trained Models, and other generative architectures.

---

## Repository Structure

```text
.
├── BayesianNetwork.ipynb
├── ConditionalGAN.ipynb
├── DeepCNN.ipynb
├── GenMultilayerNetwork.ipynb
├── GMM.ipynb
├── HMM.ipynb
├── PretrainedModel.ipynb
├── VariationalWithFashion.ipynb
├── README.md
```

---

### 1. Bayesian Network

**File:** `BayesianNetwork.ipynb`

* Implements a Bayesian Network using PGMPY.
* Defines variables, dependencies, and Conditional Probability Distributions (CPDs).
* Performs probabilistic inference using Variable Elimination.

**Concepts Covered**

* Probabilistic Graphical Models
* Conditional Probability
* Bayesian Inference

---

### 2. Conditional GAN (CGAN)

**File:** `ConditionalGAN.ipynb`

* Implements a Conditional Generative Adversarial Network using PyTorch.
* Generates images conditioned on class labels.
* Trains Generator and Discriminator simultaneously.

**Concepts Covered**

* Conditional Image Generation
* Adversarial Training
* Deep Generative Models

---

### 3. DCGAN (Deep Convolutional GAN)

**File:** `DeepCNN.ipynb`

* Implements a Deep Convolutional GAN for image generation.
* Uses convolutional layers for both Generator and Discriminator.
* Produces realistic synthetic images.

**Concepts Covered**

* Convolutional Neural Networks
* GAN Architecture
* Image Synthesis

---

### 4. Generative Multilayer Network

**File:** `GenMultilayerNetwork.ipynb`

* Implements a multilayer neural network for generative modeling.
* Uses TensorFlow/Keras.
* Generates image samples from latent vectors.

**Concepts Covered**

* Neural Networks
* Latent Space Representation
* Image Generation

---

### 5. Gaussian Mixture Model (GMM)

**File:** `GMM.ipynb`

* Uses Scikit-Learn's GaussianMixture class.
* Performs clustering on sample data.
* Visualizes cluster assignments and probabilities.

**Concepts Covered**

* Unsupervised Learning
* Probabilistic Clustering
* Expectation-Maximization (EM)

---

### 6. Hidden Markov Model (HMM)

**File:** `HMM.ipynb`

* Implements a basic Hidden Markov Model.
* Defines transition and emission probabilities.
* Demonstrates sequence probability calculations.

**Concepts Covered**

* Sequential Data Modeling
* State Transitions
* Probabilistic Inference

---

### 7. Pre-trained GPT-2 Model

**File:** `PretrainedModel.ipynb`

* Uses Hugging Face Transformers.
* Loads a pre-trained GPT-2 model.
* Generates text from user-provided prompts.

**Concepts Covered**

* Transfer Learning
* Large Language Models (LLMs)
* Natural Language Generation

---

### 8. Variational Autoencoder (VAE) with Fashion-MNIST

**File:** `VariationalWithFashion.ipynb`

* Implements a Variational Autoencoder using TensorFlow/Keras.
* Trains on the Fashion-MNIST dataset.
* Learns latent representations and reconstructs images.

**Concepts Covered**

* Variational Inference
* Representation Learning
* Deep Generative Models

---

## Technologies Used

* Python
* TensorFlow / Keras
* PyTorch
* NumPy
* Matplotlib
* Scikit-Learn
* PGMPY
* Hugging Face Transformers

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/generative-ai-lab.git
cd generative-ai-lab
```

Install dependencies:

```bash
pip install tensorflow torch torchvision numpy matplotlib scikit-learn pgmpy transformers
```

---

## Running the Notebooks

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open any notebook and run the cells sequentially.

---

## Learning Outcomes

By completing these experiments, you will understand:

* Generative Adversarial Networks (GANs)
* Conditional Image Generation
* Variational Autoencoders (VAEs)
* Bayesian Networks
* Hidden Markov Models
* Gaussian Mixture Models
* Transfer Learning using Pre-trained Models
* Deep Learning for Generative AI

---

## Author

**Vedant Khadye**

Final Year B.E. Artificial Intelligence & Data Science

---

## License

This project is intended for educational and academic purposes.
