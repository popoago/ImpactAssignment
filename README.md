# ImpactAssignment

dataset used: tiny-imagenet
files:

resnet.ipynb: contains the implementation of the Resnet architecture

lr_finder.py: contains the immplementation of lr_finder similar to that of fastai taken from https://github.com/davidtvs/pytorch-lr-finder

Test1.ipynb: contains implementations of Resnet56, Resnet32 and Resnet20 architectures trained for 90 epoch with batch_size of 1000. Best accuracy of 59% was achieved in the 90 epochs for the Resnet56.

Test2.ipynb: contains implementation of Resnet56 with a batch_size of 32 and a smaller learning rate which resulted in slow movement of the training accuracy.

Test3.ipynb: contains implementation of Resnet56 trained with a step learning rate scheduler(initialized with values same as the pytorch documentation) and an Adam optimizer.
