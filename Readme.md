# Introduction to Reinforcement Learning using the Frozen Lake Environment

Welcome to this introductory reinforcement learning project, where we will explore reinforcement learning algorithms using the Frozen Lake environment from the OpenAI Gym library.

## Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)


## Overview

In this project, we will use the 
Frozen Lake environment to demonstrate reinforcement
learning algorithm (Q learning )

## Installation
The environment simulates a frozen lake where an 
agent must navigate from the start position to the goal without falling into holes.
<div style="text-align: center;">
  <img src="images/frozen_lake.png" alt="Frozen Lake" title="Frozen Lake" width="500" height="auto" />
</div>
image source : https://medium.com/mlearning-ai/a-deep-dive-into-reinforcement-learning-q-learning-and-deep-q-learning-on-a-10x10-frozenlake-c76d56810a46
Author : Nandan Grover



### Prerequisites

To run this project, you will need to have anaconda or mini conda already installed:
create a virtual environment with the following.

### Installing Dependencies
for detailed code walk through  clone this repo 
```bash
git clone https://github.com/sokistar24/7088_cem_rl.git
```
```bash
conda create --name intro_to_rl python=3.9 jupyterlab numpy matplotlib torch
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
pip install gymnasium[classic-control]
```
```bash
pip install gymnasium[box2d]
```
```bash
pip install stable-baselines3
```
## Usage 
To start the JupyterLab server, run the following command 
in the terminal or command prompt:
```bash
jupyter-lab
```
Alternatively this code provided still work on google colab, however please note you may not be able to visualize the trained agent  