# Randomised-Smoothing

Certified_Robustness_Randomised_Smoothing.ipynb contains the code that can be used to reproduce the results of the Science Research Project. 
The first code cells define the class VGG which implements the VGG model architecture proposed in [2]. The subsequent training procedure for this model includes adding random Gaussian noise to the images to make it robust against this type of perturbations. 
The following code implements Randomised Smoothing as a method for certifying robustness. This code includes portions that have been adapted or directly copied from the following paper:

[1] Jeremy M. Cohen, Elan Rosenfeld, and J. Zico Kolter, Certified adversarial robustness via randomized smoothing, CoRR abs/1902.02918 (2019).

Please refer to the paper for a detailed description and original implementation (http://github.com/locuslab/smoothing). 


Further references:
[2] Karen Simonyan and Andrew Zisserman, Very deep convolutional networks for large-scale image
recognition., ICLR (Yoshua Bengio and Yann LeCun, eds.), 2015.
