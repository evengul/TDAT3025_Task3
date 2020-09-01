#TDAT3025 - Task 3
#a
After adding another Conv2d layer from the [initial model](https://gitlab.com/ntnu-tdat3025/cnn/mnist/-/blob/master/nn_sequential.py) (64@14x14) and a Max-Pool (64@7x7),
we reach a max accuracy of 98.630% (13 epochs)
#b
After adding a linear layer that goes to 1x1024 before going to 1x10,
we achieve an accuracy of 98.310% after 6 epochs.
#c
After adding several ReLU layers [current model](abc.py), we achieved a total of 99.110% after
17 epochs.
#d
With the [following model](d.py) consisting of two conv2d layers with relu activations,
and pooling layers between, as well as a second linear layer before the final classification,
we achieve a max accuracy of 91.640% within 19 epochs.

