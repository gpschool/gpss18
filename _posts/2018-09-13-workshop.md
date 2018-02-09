---
title:  "Advances in Approximate Inference with GPs"
layout: multitrack
tagline: "Workshop"
show_abstracts: true
room: "PLB-DS05, Pam Liversidge Building"
talks:
- title: "Arrivals"
  start: "8:00"
  end: "9:00"
- title: "Welcome"    
  abstract:
  author:
  - family: Lawrence
    given: Neil 
    url: "http://inverseprobability.com"
    institute: "University of Sheffield"   
  start: "9:00"
  end: "9:15"
  youtube: https://www.youtube.com/watch?v=jKNAPoVfzvo&list=PLpTp0l_CVmgwyAthrUmmdIFiunV1VvicM&index=9
- title: "TBA"
  abstract:
  author:
  - family: Saul
    given: Alan 
    url: "http://www.alansaul.com/"
    institute: "University of Sheffield"
  start: "9:15"
  end: "10:15"
  slides:  
  youtube: https://www.youtube.com/watch?v=jKNAPoVfzvo&list=PLpTp0l_CVmgwyAthrUmmdIFiunV1VvicM&index=10
- title: "Coffee Break"
  start: "10:15"
  end: "10:30"  
- title: "Probabilistic Programming with GPs"  
  abstract: "Probabilistic modeling is a powerful approach for analyzing empirical information. In   this talk, I will provide an overview of Edward, a software library for probabilistic modeling. Formally, Edward is a probabilistic programming system built on computational graphs, supporting compositions of both models and inference for flexible experimentation. Edward is also integrated into TensorFlow, enabling large-scale experiments on multi-GPU, multi-machine environments. In
particular, I will show how to apply Gaussian processes in Edward for two purposes: to build deep probabilistic models for representation learning and to build flexible variational approximations for accurate Bayesian inference."
  author: 
  - family: Tran
    given: Dustin
    url: "http://dustintran.com/"
    institute: "Open AI and Columbia University"   
  start: "10:30"
  end: "11:30"
  slides:  
  youtube: https://www.youtube.com/watch?v=jKNAPoVfzvo&list=PLpTp0l_CVmgwyAthrUmmdIFiunV1VvicM&index=11
- title: "On Bayesian model selection and model averaging"
  abstract: "I will provide overview of some recent advances in Bayesian model selection and model averaging in the M-open setting in which the true
data-generating process is not one of the candidate models. I will
discuss more specific implementation issues of these methods in case
of Gaussian process models."
  author:
  - family: Vehtari 
    given: Aki 
    url: "https://users.aalto.fi/~ave/"
    institute: "Aalto University"  
  start: "11:30"
  end: "12:30"
  youtube: https://www.youtube.com/watch?v=jKNAPoVfzvo&list=PLpTp0l_CVmgwyAthrUmmdIFiunV1VvicM&index=12
- title: "Lunch"
  start: "12:30"
  end: "13:30"
  youtube:
- title: "Implicit Models and Posterior Approximations"
  abstract: "Probabilistic generative models tell stories about how data were generated. These stories uncover hidden patterns (latent states) and form the basis for predictions. Traditionally, probabilistic generative models provide a score for generated samples via a tractable likelihood function. The requirement of the score limits the flexibility of these models. For example, in many physical models we can generate samples, but not compute their likelihood --- such models defined only by their sampling process are called implicit models. In the first part of the talk I will present a family of hierarchical Bayesian implicit models. The main computational task in working with probabilistic generative models is computing the distribution of the latent states given data: posterior inference. Posterior inference cast as optimization over an approximating family is variational inference. The accuracy of variational inference hinges on the expressivity of the approximating family. In the second part of this talk, I will explore the role of implicit distributions in forming variational approximations."
  author:
  - family: Ranganath 
    given: Rajesh
    url: "https://www.cs.princeton.edu/~rajeshr/"
    institute: "Princeton University"    
  start: "13:30"
  end: "14:30"
  youtube: https://www.youtube.com/watch?v=jKNAPoVfzvo&list=PLpTp0l_CVmgwyAthrUmmdIFiunV1VvicM&index=13
- title: "Tea Break"
  start: "14:30"
  end: "15:00"
- title: "A Unifying Framework for Sparse Gaussian Process Approximation using Power Expectation Propagation"
  abstract: "The application of GPs is limited by computational and analytical intractabilities that arise when data are sufficiently numerous or when employing non-Gaussian models. A wealth of GP approximation schemes have been developed over the last 15 years to address these key limitations. Many of these schemes employ a small set of pseudo data points to summarise the actual data. We have developed a new pseudo-point approximation framework using Power Expectation Propagation (Power EP) that unifies a large number of these pseudo-point approximations. The new framework is built on standard methods for approximate inference (variational free-energy, EP and power EP methods) rather than employing approximations to the probabilistic generative model itself. In this way all of approximation is performed at `inference time' rather than at `modelling time' resolving awkward philosophical and empirical questions that trouble previous approaches. Crucially, we demonstrate that the new framework includes new pseudo-point approximation methods that outperform current approaches on regression, classification and state space modelling tasks in batch and online settings."
  author:
  - family: Turner 
    given: Richard
    url: "http://www.eng.cam.ac.uk/profiles/ret26"
    institute: "University of Cambridge"
  start: "15:00"
  end: "16:00"
  youtube: https://www.youtube.com/watch?v=jKNAPoVfzvo&list=PLpTp0l_CVmgwyAthrUmmdIFiunV1VvicM&index=14
  slides: richard_sparse_gps.pdf
- title: "Panel and Dicussion"
  start: "16:00"
  end: "17:00"
  
---
