# Notebook guide

[Back to overview](../README.md) · [Getting started](GETTING_STARTED.md) · [Full notebook](../HandsOnMachineLearning.ipynb)

Five topics, with direct links to individual sections in Colab. The numbering here describes the reading order in this repository; it does not reproduce the book's chapter numbering.

## Choose a starting point

| If you want to… | Start here |
| :--- | :--- |
| Follow a complete prediction workflow | [End-to-end ML project](#1-end-to-end-machine-learning) |
| Understand how to evaluate a classifier | [Classification](#2-classification) |
| See the mathematics behind linear regression | [Linear models](#3-linear-models) |
| Understand an interpretable model visually | [Decision trees](#4-decision-trees) |
| Explore deep learning with PyTorch | [Neural networks](#5-neural-networks-with-pytorch) |

**Before running a linked subsection:** execute its chapter setup and prerequisite cells. Jump links are reading shortcuts, and do not run earlier code.

## 1. End-to-end machine learning

Build a housing price prediction workflow, from exploration and preprocessing to model selection and evaluation.

**[Open chapter in Colab](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=Ha7F9sFme49U)**

- [Explore and visualize the data](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=ebWWD8g5vHfs)
- [Prepare features and preprocessing pipelines](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=70hGsqUw2ZMt)
- [Tune models](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=MpH7VMrYGuJy)
- [Estimate uncertainty in the test error](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=6ea5d810)
- [Combine preparation and prediction](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=mBB_YCoxMG9e)
- [Save and reload a model](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=gFzKFqySMR2b)
- [Explore randomized search distributions](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=Ki0dTtixMgfG)

## 2. Classification

Explore MNIST digit classification and compare how different evaluation methods describe model behavior.

**[Open chapter in Colab](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=QquaoL3ut1ZQ)**

- [Load and explore MNIST](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=j83kC_WVzNFD)
- [Train a binary classifier](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=qlShiVSg1QtJ)
- [Compare ROC curves](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=qgKgZHTU-DcU)
- [Multiclass classification](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=Q_wQ83Kg-vy5)
- [Multilabel classification](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=3LkBbHinIHCt)
- [Multioutput classification](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=c7s4WL8rIYzv)
- [Compare a dummy baseline](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=XcM1p8jGOJxy)
- [Use nearest neighbors](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=VOLEkBPwO5Vf)
- [Explore the KNN tuning exercise](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=MShq7KQIQfJ0)

## 3. Linear models

Fit linear regression with the normal equation, scikit-learn, least squares, and the pseudoinverse.

**[Open chapter in Colab](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=5GlGHQBQTsFs)**

- [Linear regression and the normal equation](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=3ISqSbk2WZ8l)
- [Least squares and the pseudoinverse](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=CID78EoUtSFo)

## 4. Decision trees

Visualize tree decisions and explore probability estimates, regularization, regression, and sensitivity to the training process.

**[Open chapter in Colab](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=TUfjgfuQrTU9)**

- [Train and visualize an Iris decision tree](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=sae_fxNCrt_3)
- [Estimate class probabilities](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=VVJTun39y4QU)
- [Regularize a tree](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=-pYXQTgizDVq)
- [Use trees for regression](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=WpN9Zw46NzlC)
- [Explore model variance](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=6FocU-H-QXg-)

## 5. Neural networks with PyTorch

Move from tensor operations and automatic differentiation to regression networks, mini-batch training, and evaluation.

**[Open chapter in Colab](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=STAGa9Ea7urp)**

- [Work with tensors](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=F9saFQTA80ZM)
- [Select hardware acceleration](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=26Y9Lusb-GyT)
- [Understand autograd](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=2qshG4OC_I7I)
- [Build regression with tensors and autograd](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=8Evt-Bno_2Yd)
- [Use the high-level neural network API](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=9fh1FTx8A2Rs)
- [Build a regression MLP](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=xWZlgw8GBcLj)
- [Train with DataLoaders](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=RxdWGUdUCL9v)
- [Evaluate models and learning curves](https://colab.research.google.com/github/AgentQ1/HandsOnMachineLearning.ipynb/blob/main/HandsOnMachineLearning.ipynb#scrollTo=Htl2OvrKCvle)

## About the notebook

All 317 original code cells and their 253 saved output records are retained. The presentation update adds navigation, organizes markdown headings, and removes three empty or placeholder markdown cells.

The README figure previews come from the Iris decision-boundary example and the final PyTorch training/validation learning-curve example. They represent saved notebook output, not new benchmark runs.

See [Getting started](GETTING_STARTED.md#execution-notes) for the current execution status and how to run a clean validation.
