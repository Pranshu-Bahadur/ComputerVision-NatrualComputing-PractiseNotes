# Computer Vision Practise:

The purpose of this repository is to not fall half asleep while learning fundamental concepts in Computer Vision.

It's active learning!
 
- Let R denote the set of Reals, and U denote the set Union operation.

- Let R^{n} denote an N dimensional Euclidean Space (A Vector Space w/ the dot product operation).

- Note: A Vector Space E over Field R is the set of all Vectors with Production Rules: 
	- v+u in E | v, u in E // Vector-Vector Addition
	- vxr in E | v in E, r in R //'x' denotes Vector-Scalar Multiplication

Defn 1 - An Image can be defined as:

F in U R^{ixNxM} | N in Z+, M in Z+, i in [1, 3]


What is an edge-detector?

What is an edge in an Image?

An edge is an ordered-set of pixels in an image with high intra-similarity & inter-dissimilarity.

// An edge is can be defined as a cluster e and inter-dissimlarity b/w edge clusters can be calculated using centroids & Euclidean Distance as a measure.

An Edge Detector is a method to derive the most valid subset of image-clusters (ordered-sets of pixels) by using image-filtering (i.e. maximizing for intra-cluster similarity, and minimizing for inter-cluster similarity) and then picking the most valid subset of clusters.


DFS for edge detection?



What is Noise?





Edge Detectors:

- [ ] Formal Definition

- [ ] Laplacian 

- [ ] Canny Edge 

- [ ] Harris Corner 

- [ ] Gaussian 

Histogram of Gradients


SIFT

Points and patches

Feature based alignment

Least squares

RANSAC

References:

1. [Qn: Vector Space as a Grammar? Soln: "Dragon Fire"](https://arxiv.org/pdf/1901.10723.pdf)



Don't why anyone would wanna clone this...It's literally notes.

