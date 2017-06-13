title: Generalized Matryoshka: Computational Design of Nesting Objects
author: Alec Jacobson
html header:   
css: style.css

# Generalized Matryoshka: Computational Design of Nesting Objects _SGP 2017_

<div class=authors>

Alec Jacobson

University of Toronto

</div>

![](matryoshka-teaser.jpg)

## Abstract

This paper generalizes the self-similar nesting of _Matryoshka_ dolls ("Russian
nesting dolls") to arbitrary solid objects. We introduce the problem of finding
the largest scale replica of an object that _nests_ inside itself. Not only
should the nesting object fit inside the larger copy without interpenetration,
but also it should be possible to cut the larger copy in two and remove the
smaller object without collisions. We present a GPU-accelerated evaluation of
nesting feasibility. This test can be conducted at interactive rates, providing
feedback during manual design. Further, we may optimize for some or all of the
nesting degrees of freedom (e.g., rigid motion of smaller object, cut
orientation) to maximize the smaller object's scale while maintaining a
feasible nesting. Our formulation and tools robustly handle imperfect geometric
representations and generalize to the nesting of dissimilar objects in one
another. We explore a variety of applications to aesthetic and functional shape
design.

## Downloads

 - [Paper](generalized-matryoshka-computational-design-of-nesting-objects-sgp-2017-compressed-jacobson.pdf)
 - [Paper (low res)](generalized-matryoshka-computational-design-of-nesting-objects-sgp-2017-jacobson.pdf )

## Animations

![](matryoshka-bunnies.gif)

## BibTeX

```
@article{Jacobson:GM:2017,
  title = {Generalized Matryoshka: Computational Design of Nesting Objects},
  author = {Alec Jacobson},
  year = {2017},
  journal = {Computer Graphics Forum}, 
}
```
## Acknowledgements 

This work is funded in part by NSERC Discovery Grants (RGPIN-2017-05235 &
RGPAS-2017-507938), the Connaught Fund (NR-2016-17), and a gift by Adobe
Systems Inc. Thank you to David Levin for illuminating discussions and Kevin
Gibson, Masha Shugrina, Michael Tao, and Alex Tessier for early draft reviews.
