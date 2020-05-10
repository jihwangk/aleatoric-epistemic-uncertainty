# PyTorch Implementation of Aleatoric and Epistemic Uncertainty

This repository is not the official repository for the paper [1], but an implementation of the uncertainties as classification loss functions with CIFAR-10 / CIFAR-100. For the model architecture, I used PyramidNet [2] by Han et al. and modified the structure to include dropout and custom loss functions.

## How to Run

Git clone or download the uncertainty.ipynb file and upload it to your Google Drive. Open the file with Google Colaboratory to see the file in correct format. Simply follow the instructions and run cells afterward. Due to slow performance, I set the number of epochs to 5 for now. Try changing it to 300, like recommended in [2].

## References

[1] ["What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision". NIPS 2017](https://arxiv.org/abs/1703.04977)
[2] [PyramidNet](https://github.com/dyhan0920/PyramidNet-PyTorch)


## Notes

In current version, only epistemic uncertainty is implemented. 
