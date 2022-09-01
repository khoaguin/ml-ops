# Full Stack Deep Learning 2022
Welcome to my repo for the course [Full Stack Deep Learning (2022)](https://fullstackdeeplearning.com/course/). Here you will find my notes, labs and project for the course.
## Outline
* [Course Overview](#course-overview-and-notes)
* [Labs](#labs)
* [Project](#project)
* [Resources](#resources)
***

## Course Overview and Notes
![banner](./images/banner.png "course banner")

There are many great courses on training deep learning models, but it is only one part of the deep learning stack. This course focuses on the other part of the stack, which is building and shipping ML-powered products.

### [Course Notes (on Notion, in English)](https://khoaguin.notion.site/Full-Stack-Deep-Learning-2022-UC-Berkeley-8c2b19cf721e453b86a3e20fd209c7c3)

## Labs
![labs-banner](./images/labs-banner.png)  

As part of Full Stack Deep Learning 2022, we will incrementally develop a complete deep learning codebase through the labs to create and deploy a model that understands images of hand-written paragraphs and outputs the text in the images. The labs can be run on Google Colab, and there are also accompanied walkthrough videos that you can find [here](https://github.com/full-stack-deep-learning/fsdl-text-recognizer-2022-labs).

### [Lab 00: Overview](./labs/Lab00-Overview.ipynb) 
In the first lab, we go through the overview of the text recognizer app that demonstrates core principles and tools of an ML-powered application.

![text-recognizer-app](./images/text-recognizer-app.png)  

The figure below shows in more details how the app works.

![text-recognizer-app2](./images/text-recognizer-app2.png)  

The diagram below shows the entire process, tools and frameworks needed to train and run the text recognizer app. 

![text-recognizer-app](./images/app-diagram.png)  

### [Lab 01: PyTorch](./labs/Lab01-PyTorch.ipynb)
At its core, [`PyTorch`](https://pytorch.org/) is a library for doing math on arrays with automatic calculation of gradients. It also makes it easy to accelerate computations with GPUs and distribute over computing nodes.  

In this lab, we will learn
- How to write a basic neural network from scratch in PyTorch
- How the submodules of `torch`, like `torch.nn` and `torch.utils.data`, make writing performant neural network training and inference code easier

### [Lab 02a: PyTorch Lightning](./labs/Lab02a-PyTorchLightning.ipynb)
[`PyTorch Lightning`](https://github.com/Lightning-AI/lightning) is a designed to organize PyTorch code in a more intuitive and easy-to-read way, making deep learning experiments easier to reproduce. It is also a useful tool to create scalable deep learning models that can easily run on distributed hardware while keeping the models hardware agnostic.

In this lab, we will learn:
- The core components of a PyTorch Lightning training loop: `LightningModules` and `Trainers`.
- Useful quality-of-life improvements offered by PyTorch Lightning: `LightningDataModules`, `Callbacks`, and `Metrics`
- How we use these features in the FSDL codebase

### [Lab 02b: Training a CNN on Synthetic Handwriting Data](./labs/Lab02b-CNN.ipynb)
In this lab, we will learn
- Fundamental principles for building neural networks with convolutional components
- How to use Lightning's training framework via a command line interface (CLI) to train CNNs on EMNIST and EMNISTLines datasets.


### [Lab 03: Transformers and Paragraphs](./labs/Lab02b-CNN.ipynb)
In this lab, we will learn
- The fundamental reasons why the Transformer is such a powerful and popular architecure
- Core intuitions for the behavior of Transformer architectures
- How to use a convolutional encoder and a Transformer decoder to recognize entire paragraphs of text

### [Lab 04: Experiment Management](./labs/Lab04-Experiments.ipynb)
In this lab, we will learn
- How experiment management brings observability to ML model development
- Which features of experiment management we use in developing the Text Recognizer
- Workflows for using [Weights & Biases](https://wandb.ai/site) in experiment management, including metric logging, artifact versioning, and hyperparameter optimization

### [Lab 05: Troubleshooting & Testing](./labs/)
In this lab, we will learn
- Practices and tools for testing and linting Python code in general: [`black`](https://github.com/psf/black), [`flake8`](https://flake8.pycqa.org/en/latest/index.html), [`precommit`](https://pre-commit.com/), [`pytests`](https://docs.pytest.org/) and [`doctests`](https://docs.python.org/3/library/doctest.html)
- How to implement tests for ML training systems in particular
- What a PyTorch training step looks like under the hood and how to troubleshoot performance bottlenecks

## Project

## Resources
- https://fullstackdeeplearning.com/course/2022/
- https://github.com/full-stack-deep-learning/fsdl-text-recognizer-2022-labs