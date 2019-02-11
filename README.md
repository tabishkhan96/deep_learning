# deep_learning
This repository would be used to keep track of my mini-projects in machine learning. Most of the code would be in [PyTorch](https://github.com/pytorch/pytorch) for now.
I would be using the [fastai](http://www.fast.ai) library from Jeremy Howard's fastai course. So you will need to download the fastai library from [here](https://github.com/fastai/fastai).
I would be trying to implement some of fastai's functionality with pytorch from scratch for learning purpose. 


## Table of Contents

### 1. pytorch_projects
#####  cifar10_pytorch_transfer_learning.ipynb
Using cifar10 as the dataset, this notebook takes you through the basic steps of:
 - Loading and exploring data
 - Use of custom models and loading weights
 - Freezing different sections of layers in the model
 - Modify existing trained model to accommodate new data
##### cifar10_pytorch_SGDR.ipynb
Implement SGDR technique from this [paper](https://arxiv.org/pdf/1608.03983.pdf). Also explore other concepts such as model snapshots ensemble, incremental data size for training, etc.  The model's performance is around 92.3%.
##### cifar100_preprocess.ipynb.ipynb
Simple demonstration to show how to extract subset of classes from a given dataset.

#### 2. kaggle - (using fastai)
* dogcats - simple example of classifying dogs and cats
* dogbreeds - classify around 120 types of breeds
* planets_kaggle - classify satellite image on Amazon rainforest


## Getting Started

If any notebook needs the fastai library, you need the place the **fastai** folder under the same directory of the notebook.
You can get fastai from [here](https://github.com/fastai/fastai).
