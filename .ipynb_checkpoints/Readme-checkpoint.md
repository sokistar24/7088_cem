# 7088CEM - Artificial Neural Networks 

This section of the Lab would cover Convolutional Neural Networks(CNNs) and Reinforcement Learning
## Table of Contents

1. [Introduction to Convultional Neural  Networks](#Image classification)
2. [Introduction to Reinforcement Learning](#Introduction to MNIST Handwritten digit classification)
3. [Installation](#installation)
4. [Usage](#usage)

## For the CNN section what we would cover
1. [Mnist handwritten digits classification ](#MNIST)
2. [Cifar10 data  classification ](#Cifar10 )
3. [Using Kaggle and other data sources ](#Kaggle)


## For the RL section what we would cover
1. [Qlearning using frozen lake environemnt ](#frozen lake)
2. [Deep Reinforcement Learning for continous state and action space](#Carpole )

<div style="text-align: center;">
  <img src="images/DQN_learning_circle.png" alt="Reinforcement Learning" title="Reinforcement Learning" width="500" height="auto" />
</div>

### Prerequisites
For the RL section of the lab, you will need to have anaconda or mini conda already installed:
the Anaconda_setup.pdf include a step by step guid on installation of anaconda and creating a virtual environment

### Installing Dependencies
The codes for the lab can be found in Aula under the CNN and RL section alternatively clone this repo 
```bash
git clone https://github.com/sokistar24/7088_cem.git
```
```bash
conda create --name intro_to_rl python=3.9 jupyterlab numpy matplotlib pytorch
```
Activate the environment uisng 
```bash
conda activate intro_to_rl

```
```bash
pip install swig
```
Open a notebook and run the code cell below to install the gymnasium API for frozen lake

```bash
pip install gymnasium[toy-text]
```
```bash
pip install gymnasium[box2d]
```
## Usage 
To start the JupyterLab server, run the following command 
in the terminal or command prompt:
```bash
jupyter-lab
```
Alternatively this code provided still work on google colab, however please note you may not be able to visualize the trained agent  