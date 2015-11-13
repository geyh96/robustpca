# ROSL

Last updated: 13/11/2015

C++ implementation of Robust Orthonormal Subspace Learning (ROSL)[1] using the Armadillo linear algebra library.

> [1] Xianbiao Shu, Fatih Porikli, Narendra Ahuja. "Robust Orthonormal Subspace Learning: Efficient Recovery of Corrupted Low-rank Matrices". 
> *Proc. of International Conference on Computer Vision and Pattern Recognition (CVPR)*, **2014**

## Contents

+ [Installation](#installation)
+ [Using ROSL](#using-rosl)

## Installation

**Dependencies**

ROSL makes use of the **[Armadillo](http://arma.sourceforge.net)** C++ linear algebra library, 
which needs to be installed first. It is recommended that you use a high-speed replacement for
LAPACK and BLAS such as OpenBLAS, MKL or ACML; more information can be found in the [Armadillo
FAQs](http://arma.sourceforge.net/faq.html#dependencies).

**Building from source**

To build ROSL, unpack the source and `cd` into the unpacked directory, then type `make`:

```
$ tar -xzf rosl.tar.gz
$ cd rosl
$ make
```

This will generate a C++ library called `librosl.so`, which is called by the Python module `pyrosl`.
Included are an example usage, and a simple Python test suite to check the implementation:

```
$ python example.py
$ python test.py
```

## Using ROSL

*Description to go here*
