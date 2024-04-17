---
layout: posterpage
categories: [poster]
posternumber: P48
speaker: Stefan Heinen
location: 'Laboratory for High Performance Ceramics, Empa, Swiss Federal Laboratories for Materials Science and Technology, 8600 Dübendorf'
title: 'QMLcode 2.0, the Pythony way: Installable across platforms'
authors: 'S. Heinen, K. Karandashev, D. Khan, J. Weinreich, G. Blugan, A. O. von Lilienfeld'
abstract: "To ensure reproducibility we introduce an updated, publicly available, and maintained kernel ridge 
regression (KRR) code extending capabilities of both QMLcode1.0 and QMLightning, offering researchers a robust 
tool for quantum machine learning applications. Transitioning from the original implementation in FORTRAN, 
encapsulated by a Python wrapper, the project is entirely rewritten in Python. This not only facilitates a 
seamless installation across platforms, but also integrates the latest representations (FJK, MBDF, DF, and cMBDF),
an improved wrapper, as well as a novel GPU kernel implementation, including CUDA support. Key innovations in 
QMLcode 2.0 encompass the integration of PyTorch and GPyTorch, enhancing GPU-accelerated KRR operations, such 
as hyperparameter optimization and gradient calculations. Despite moving from FORTRAN to Python, we meticulously
preserve computational performance by leveraging the NumPy and Numba libraries, ensuring minimal speed loss. 
Additionally, the introduction of the CuPy library optimizes global and custom local kernel computations by 
executing C in the background, further bridging the performance gap if not surpassing the original code in speed. 
Incorporating a diverse array of libraries capable of running on both CPU and GPU architectures, allows for the 
selection of the optimal method for executing the code based on the available infrastructure. Despite introducing 
a new wrapper that facilitates the Compound class, hyperparameter scan, training, and predicting, QML code 2.0 
remains backward compatible, offering function-based operability to accommodate scripts developed for the original 
version. Showing numerical evidence for atomization energies using the QM7 dataset confirms QMLcode 2.0's accuracy
is unchanged, with a slight speed reduction balanced by major new features, broadening its utility in kernel ridge
regression."
---
