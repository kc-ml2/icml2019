# icml2019

## Notes on some interesting works from ICML2019

[**Manifold Mixup**](https://arxiv.org/abs/1806.05236)

Alex Lamb et al.

* This work focuses on the enhancement in so called the manifold of the hidden layers and the final output in classification problem. 
* The problem with current methods is that the boundary is too close to the data points in the hidden layers.
* The suggested method relaxes this problem by linearly interpolating the manifolds, forcing them to be trained in a linear manner.
* the results show clearer decision boundary and enhanced performance in mnist, cifar10, cifar100, etc.

[**Multi-Object Representation Learning with Iterative Variational Inference**](https://arxiv.org/abs/1903.00450)

Kaufman et al.

* This work focuses on multi-object representation learning.
* Multi-object representation refers to learning individual representation of objects within the visual input separately. 
* The work achieves this by having k-slots for different representations for each input. 
* Each representation is then iteratively refined in parallel so that sum of mask reconstruction of each representation succesfully reconstructs the original input scene. 
* The take-away from this work is using separate slots and mask to reconstruct each object separately, achieving ability to focus in specific region of the input image. 

