# Neural-networks-and-deep-learning
All my assignments from the Deeplearning.AI specialization course
Some packages you will need to install are:
import numpy as np 
  mathematical and scientifical library in python, all scientific functions are included, plus we play with matrices in it.
import h5py
  for loading and handling datasets
import matplotlib.pyplot as plt
  python plotting library
import random
  very important for generating random numbers, will be used in initialization of weights and biases
import scipy
  will be used fopr linear algebra, integration, derivation, differential equation solving, etc.
from PIL import Image
  for working with images


moreover the are many files that will be imported, like lr_utils.py, dnn_utils.py, etc 
all files are provided
if you want your python to search for these files to import them, that is not a big issue, just write the following commands.

import sys
sys.path()
#this will give all the directories which python uses while searching for modules
#just append the path of the working directory where you downloaded the files like lr_utils, etc.
path = input("please enter the complete path of the files: ")
sys.path.append(path)
