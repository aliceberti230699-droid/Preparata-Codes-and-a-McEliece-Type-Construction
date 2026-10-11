# SageMath Implementations for a Master's Thesis in Mathematics

This repository contains the SageMath implementations developed for a Master's thesis on error-correcting codes and their applications to public-key cryptography.

The code covers the classical McEliece cryptosystem based on binary Goppa codes and an exploratory McEliece-type construction based on Preparata codes.

## Repository Contents

* **`A worked example of the McEliece cryptosystem.sage`**
  Implementation of binary Goppa codes and the classical McEliece cryptosystem. The file also contains the computations needed to reproduce the worked example presented in the thesis.

* **`Towards a McEliece-type scheme based on Preparata codes.sage`**
  Implementation of Preparata codes and the corresponding McEliece-type construction, together with the computational experiments carried out as part of the thesis.

## Requirements

* SageMath 10.8

The code was developed and tested using SageMath 10.8.

## Running the Code

Each file contains the implementation and the corresponding computations in sequence. To reproduce the results, open the relevant file in a SageMath environment and execute the code from beginning to end.

The first file focuses on the classical McEliece cryptosystem and its worked example, while the second contains the Preparata code implementation and the associated computational experiments.

## Scope and Limitations

The implementation of the classical McEliece cryptosystem is intended to illustrate its main components and the role of binary Goppa codes.

The Preparata-based construction is an exploratory investigation into the use of Preparata codes in a McEliece-type framework. The computational experiments are intended to investigate the behaviour of the implemented procedures and should not, by themselves, be interpreted as a security proof or as a general assessment of the security of the construction.

## Reference

This repository accompanies a Master's thesis in Mathematics. The version corresponding to the thesis is identified by the associated GitHub release.

