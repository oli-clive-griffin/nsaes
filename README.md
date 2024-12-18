# Hyper Sparse Autoencoders

Sparse autoencoders can be thought of as extracting a 1 dimensional subspace in high-dimensional space
(and cleaning up interference with a ReLU). Why can't the same idea work for higher-dimensional features?

Hyper-SAEs attempt to do this. By allowing hidden features to be n > 1 dimensional (hence "hyper"), and
applying bias and relu in the 1d subspace of the feature's direction.
