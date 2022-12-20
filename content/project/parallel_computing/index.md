---
title: Parallel Computing Toolbox 
summary: Implementation of PCA algorithms for image compression using C++/Cuda and parallel Monte Carlo algorithm using OpenMP and MPI from scratch
tags:
- Parallel Computing
- Computer Vision
# date: "2019-05-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Comparison of Robot poses before and after optimization
  focal_point: Smart

url_code: "https://github.com/UditSinghParihar/Parallel_Computing_Solutions"
url_pdf: ""
url_slides: "https://github.com/UditSinghParihar/Parallel_Computing_Solutions/blob/master/pca/results/pca_slides.pdf"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

Implemented following functionality in the parallel computing toolbox:   

1. **Project 1** :
	1. Matrix multiplication and storage schemes.
	2. LU Decomposition and `Ax = b` solution.
	3. QR Decomposition and `Ax = b `solution.

2. **Project 2** :
	1. Parallelization based on OpenMP.
	2. For compiling any program:
		1. `gcc -fopenmp file.c`
	3. Solutions on:
		1. `For loop` scheduling.
		2. Parallel Monte carlo for PI digits calculation.
		3. Parallel Jacobi solver for generating new matrix with values containing mean of 4 neighbours.
		4. Example of race condition
	4. Resources:
		1. [IIT M OpenMP slides](http://www.cse.iitm.ac.in/~rupesh/teaching/hpc/jun16/4-openmp.pdf)
		2. [Jaka's Blog](http://jakascorner.com/blog/2016/06/omp-for-reduction.html)

3. **Project 3** :
	1. Parallel implementation of PCA for image compression from scratch.