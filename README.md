This repository contains my attempt to classify handwritten digits from the MNIST dataset. I reused and refined the code from my Neural-Networks repository, adapting both the NumPy-only and PyTorch implementations to serve as MNIST classifiers.

The key improvement was switching from single-sample training to mini-batches of 128 samples, which greatly reduced computation time. Both the NumPy-only and PyTorch networks achieve about 98 % accuracy.
