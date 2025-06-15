This repository is my attempt at the image number classifying of the MNIST dataset. I use the code I had written in my Neural-Networks repository where I repurposed and improved both 
the Numpy-only and PyTorch codes to work as classifiers fo the MNIST dataset. The improvement came from instead of training with one data sample at a time, I train the neural networks
with mini-batches of 128 data samples at a time which greatly decreases computation time. Both the Numpy-only and PyTorch neural networks achieve accuracies of around 98%.
