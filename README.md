# Automatic classification of protein structure by using Gauss integrals 

## Laboratory of Computational Physics - Part B


**Title**: Automatic Protein Classification using gaussian integrals.

**Authors**: Alessandro Fella, Lucia Depaoli, Lorenzo Mandolito and Simone Mistrali

We where inspired by Peter Røgen and Boris Fain, in their [paper](https://doi.org/10.1073/pnas.2636460100), to tackle this problem we compare two different measure of similarity: the one proposed by the authors (scaled Gauss metric, SGM) and a novel one which is faster, but seems to not separate the proteins chain as well as the first one in this new topologic space.

We will use three different approach:

1. Clustering using `DBSCAN`.
2. Clustering using `KNeighborsClassifier`.
3. Classification via some simple Neural Networks architectures.
## Requirements & Contact

To properly run this project please clone this directory and from a terminal run this command:

``` python3 -m pip install -r requirements.txt```

Contact Simone Mistrali at simone.mistrali at gmail.com for any questions or comments.