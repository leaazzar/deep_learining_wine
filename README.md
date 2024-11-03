# deep_learning Dog Breeds classification
 # Dog Breed Classification

## Introduction

This project involves building a simple feedforward neural network to classify dog breeds based on images. The objective is for this model to identify one of 6 breeds of a dog from a given picture.

## Dataset
The original dataset contains images of **120 different dog breeds** from  [http://vision.stanford.edu/aditya86/ImageNetDogs/] For this project,I have selected **6 dog breeds** out of the original 120 to simplify the classification task. You can expand the model to include more breeds by following the same methodology.

**Breeds Included:**
1. Maltese dog
2. Shih Tzu
3. Rhodesian Ridgebakc
4. Afghan hound
5. Beagle
6. Basset


## Model
- Input Layer accepts flattened images resized to 64x64 pixels.
- First Hidden Layer is a Fully Connected Layer of 128 neurons
- Second Hidden Layer also fully connected with 64 neurons
- Output Layer of 6 Neurons.
