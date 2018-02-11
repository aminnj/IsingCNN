## Ising model phase transition with CNN

This is a short notebook to reproduce some results from [this paper](https://arxiv.org/pdf/1605.01735.pdf).

More details are in the python notebook, but in brief, 2D Ising model spin lattices are used to train
a convolutional neural network to determine the critical temperature for phase transition simply by
having the neural network learn which of 2 phases (high or low) a system is in, given the lattice of spins.

### Instructions
* Fairly common dependencies: numpy, matplotlib, scikit, scipy, keras, tqdm
* For keras, there are a few lines that assume tensorflow as the backend, but they are easily modified
* Clone and run with something like `jupyter --no-head`

