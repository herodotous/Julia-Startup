# Implementing Matrix Functions


### Introduction
This repository addresses the Julia issue [5840](https://github.com/JuliaLang/julia/issues/5840) and raises relevant concerns and steps taken to 
tackle the problem. 


### Description
Julia is parallel distributed interpreted language, which supports high level mathematical computation, on par with _Matlab, Mathematica, Scilab_ etc. Project aims to implement matrix functions raised in above issue. Estimating condition number and Frechet derivatives(i.e sensitivity analysis), comprise an important role in stability analysis of numerical algorithms. Our main goal is to deliver robust and efficient implementation of Frechet derivatives in julia. 
Following is the compact list of functions that will be implemented. 

1. Frechet Derivatives
..* Exponential function
..* Logarithmic function
..* Real matrix of power
..* Complex matrix function
2. Condition number estimation
..*Block matrix 1-norm estimator

As addressed in paper by [Higham and Deadman](http://eprints.ma.man.ac.uk/2102/01/covered/MIMS_ep2014_8.pdf), goal is to implement all variants to compute above functions.

Matrix Sqrt function

+        via Newton’s method

+        via Denman-Beavers iteration

Convergence tolerance for matrix iterations

logm

+        Pade approximation

+       Inverse scaling and squaring method

expm

+        Pade approximation

+        Quadrature function

 

After implementing following algorithms, the goal is to benchmark with corresponding algorithms from MATLAB, Scipy and NAG library.   








### Coding
 


### Timeline
I structure this project into short steps of duration two weeks

- **Week 1-2**  Getting familiar with julia codebase and reading relevant papers
- **Week 3-4**  Implementing squrtm and expm class of functions
- **Week 5-6**  Implementing logm and convergence tolerance class of functions.
- **Week 7-8**  Restructuring implemented code to get Fretchet derivatives and condition number estimation
- **Week 9-10** Final along testing with Documenting code.

 

### Deliverables

1.  
2.   

### Why Julia
I picked this project, because the project has a huge learning curve, and one which I can possibly use  in my thesis work. I’ve been following Jiaho Chen, who first pointed out the problem in ideas list. Since he seems to have a handle on issues, I would be interested in working along with him. 
 
---

###About me
I’m Dhruv Data, pursuing masters in Computer Science at IIIT Hyderabad. I’ve been doing my research in **CCNSB** (_Centere for Computational Nautral Science and Biology_). I have no previous experience in programming julia, however I've been interested in topic of perturbation in multi-grid algebraic solver. And in a way, I'm excited about implementing this project, and would like to make it robust and 

Email | data.dhrub@gmail.com |
------|----------------------
Github Handle|  herodotous 
IRC Handle | herodotous 


###Logistics
I will be availiable from May to August and I would be able to contribute 40 hours per week to the project. I'm interested in implementation aspect of project, where testing and programmign with new architectures is intriguing.
