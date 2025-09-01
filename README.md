
# Intro to Generative Modeling with Flow and Diffusion-Based Models

Welcome👋! This repository is a collection of **tutorial materials on modern generative modeling**, including notes, slides, and code examples (currently only notes are available).  
It is designed as an accessible yet rigorous guide for students, researchers, and practitioners who want to build a solid foundation in generative models.

## Introduction

In machine learning, **generative modeling** refers to the task of learning the underlying statistical properties of data distributions from observed samples.

From a probabilistic perspective, data are seen as outcomes of a random variable, and generative modeling is about defining a new random variable—called a *model*—whose distribution is aligned with that of the data via training procedures.

Building on this probabilistic view, modern generative models extend these ideas in powerful ways. However, the mathematical machinery behind many of these methods can be demanding, making it difficult for newcomers to engage with the field.

The aim of this tutorial is to **lower the entry barrier** for students and researchers who may not have a strong mathematical background, by connecting key concepts with the underlying mathematics and helping readers develop familiarity with the required machinery. This tutorial introduces the essential ideas for unfamiliar readers and clarifies how the development of modern diffusion and flow-based models can be motivated in terms of fundamental probabilistic concepts and key design criteria in generative modeling.

The material is especially aimed at readers with an engineering or science background (undergraduate or early graduate level), and is intended to serve as a **gateway into research-level generative modeling**.

Much of this tutorial is adapted from my PhD thesis. Technical details such as architectures or optimization tricks are discussed only when they are directly relevant to the theoretical discussion.


## Planned Chapters

This tutorial will be developed in parts, and the repository will grow as more content is added.  
Currently, Chapters **1, 2, 3, 5, 6, A, and B** are prepared. Others will be added progressively.

### Part I
- [x] 1. Introduction  
- [x] 2. Modeling CRV  
- [x] 3. VAE  
- [ ] 4. Normalizing flows and neural ODEs  
- [x] 5. SM and DAE  
- [x] 6. Diffusion-based models  
- [ ] 7. Consistency models  
- [ ] 8. Sampling  
- [ ] 9. Adjoint matching  

### Part II
- [ ] 10. Bridge matching  
- [ ] 11. Flow matching  
- [ ] 12. Schrödinger Bridge  

### Part III
- [ ] 13. Diffusion on Hilbert space  
- [ ] 14. Discrete diffusions  
- [ ] 15. Jump diffusions  
- [ ] 16. Continuous-time Markov processes  

### Appendix
- [x] A. Probability Theory  
- [ ] B. Beyond Euclidean spaces  
- [ ] C. Stochastic integral and Brownian motions  



## Repository Structure

```
intro-to-generative-models/
├── notes/        # Written notes (LaTeX, PDFs, Markdown)
├── slides/       # Lecture slides
├── code/         # Code examples and exercises
├── resources/    # References and supplementary materials
└── README.md     # Overview and navigation
```



## Feedback

This tutorial is a work in progress. Feedback and suggestions are always welcome. If you notice missing references, unclear explanations, or areas for improvement, please feel free to open an issue. While feedback is appreciated, please note that pull requests may not be accepted.

## Citation
```
@misc{lim2025generative_tutorial,
  author       = {Jae Hyun Lim},
  title        = {An Introduction to Generative Modeling with Flow-Based and Diffusion-Based Models},
  year         = {2025},
  howpublished = {\url{https://github.com/lim0606/intro-to-generative-models}},
  note         = {Version 0.1}
}
```
