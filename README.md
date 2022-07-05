# Closed-Form Diffeomorphic Transformations for Time Series Alignment

[Iñigo Martinez], [Elisabeth Viles], [Igor G. Olaizola]

## Abstract

Time series alignment methods call for highly expressive, differentiable and invertible warping functions which preserve temporal topology, i.e diffeomorphisms. Diffeomorphic warping functions can be generated from the integration of velocity fields governed by an ordinary differential equation (ODE). Gradient-based optimization frameworks containing diffeomorphic transformations require to calculate derivatives to the differential equation's solution with respect to the model parameters, i.e. sensitivity analysis. Unfortunately, deep learning frameworks typically lack automatic-differentiation-compatible sensitivity analysis methods; and implicit functions, such as the solution of ODE, require particular care. Current solutions appeal to adjoint sensitivity methods, ad-hoc numerical solvers or ResNet's Eulerian discretization. In this work, we present a closed-form expression for the ODE solution and its gradient under continuous piecewise-affine (CPA) velocity functions. We present a highly optimized implementation of the results on CPU and GPU. Furthermore, we conduct extensive experiments on several datasets to validate the generalization ability of our model to unseen data for time-series joint alignment. Results show significant improvements both in terms of efficiency and accuracy.

## ICML 2022

Click on the following links to access the paper or download the poster and the presentation slides from ICML 2022.

* [📝 Paper]
* [🖼️ Poster] 
* [📊 Slides]
* [🎥 Video] 
* [📦 Code] 

## Support or Contact

If you are having problems executing the experiments or the tutorials, do not hesitate to contact us.

[//]: # (References)
   [Iñigo Martinez]: <https://scholar.google.es/citations?user=_VGGVEgAAAAJ>
   [Elisabeth Viles]: <https://scholar.google.es/citations?user=-pRUC-8AAAAJ>
   [Igor G. Olaizola]: <https://scholar.google.es/citations?user=TihmWmAAAAAJ>
   [📝 Paper]:  <https://arxiv.org/abs/2206.08107>
   [🖼️ Poster]: <https://inigo.tech/closed-diffeomorphic/assets/poster.pdf>
   [📊 Slides]: <https://inigo.tech/closed-diffeomorphic/assets/slides.pdf>
   [🎥 Video]:  <https://recorder-v3.slideslive.com/?share=69811&s=6ff59166-61cf-4cb8-99be-4b2f662bd538>
   [📦 Code]:  <https://github.com/imartinezl/difw>
