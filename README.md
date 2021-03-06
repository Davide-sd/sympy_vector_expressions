# Vector Expressions for Sympy

## Motivation

With Sympy we can write general symbolic expression by using symbols, functions, numbers,...., which are instances of the class `Expr`.

Similarly, we can write symbolic matrix expression using instances of the class `MatrixExpr`. We can also substitute dense or sparse matrices into those symbolic expressions.

Unfortunately, vector expressions (involving dot and cross products, magnitude, divergence, curl, ...) are not implemented yet. This is a highly experimental module to implement **vector expressions**. At the moment, only basic functionalities and printing are implemented. Take a look at the Jupyter notebooks **Tutorial** to learn how to use it. Also, feel free to help with the development.

![Vector equations image](imgs/img-1.png)

## Update

I feel like the current implementation is not good enough to be extended anymore. In order to use matrices-tensors, the module need to be re-engineered and rewritten.

Take a look at the `tests` folder to see example of this module usage.

## Features

### Derivatives

![Derivatives](imgs/img-9.png)

### Identities

![identities](imgs/img-2.png)

![identities](imgs/img-3.png)

![identities](imgs/img-10.png)

### Expansion

![Expansion](imgs/img-4.png)

### Collection

![Collection](imgs/img-5.png)

### Simplification

![Simplification](imgs/img-6.png)

![Simplification](imgs/img-7.png)

![Simplification](imgs/img-8.png)

## TODO

* Operation precedence.
* Printing need some works.
* Integrals of vector expressions.
* Solve for vector expressions.
* Gradient: the gradient of a vector field is a tensor (matrix). Is it possible to implement them in this module? Specifically, is it possible to substitute a tensor/matrix into a vector expression and perform the evaluation? Is it possible to integrate them with tensor and linear algebra modules?