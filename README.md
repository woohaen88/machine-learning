# machine-learning

To learn how to train your first CNN with PyTorch, just keep reading. Throughout the reminder of this tutorial, you will learn how to train your first CNN using the PyTorch framework.
We’ll start by configuring our development environment to install both torch and torchvision, followed by reviewing our project directory structure.
I’ll then show you the KMNIST dataset (a drop-in replacement for the MNIST digits dataset) that contains Hiragana characters. Later in this tutorial, you’ll learn how to train a CNN to recognize each of the Hiragana characters in the KMNIST dataset.
We’ll then implement three Python scripts with PyTorch, including our CNN architecture, training script, and a final script used to make predictions on input images.
Configuring your development environment to follow this guide, you need to have PyTorch, OpenCV, and scikit-learn installed on your system.Luckily, all three are extremely easy to install pip:

PyTorch: Training your first Convolutional Neural Network (CNN)
```bash class:"lineno"
$ pip install torch torchvision
$ pip install opencv-contrib-python
$ pip install scikit-learn
