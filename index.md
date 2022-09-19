

## UvA - An Introduction to Group Equivariant Deep Learning

Welcome to the public page for the mini-course on Group Equivariant Deep Learning. The course is currently still a work in progress, so please forgive me for the occasional sloppyness in the provided materials. In the upcoming months I will regularly update them. The most important piece of material in this course are the lecture notes. 

*Erik Bekkers*

<br/><br/>

![](/lnandslides.gif)

<br/><br/>

Tutorials and other deep learning topics:
* See [Deep Learning 2 Course Website](https://uvadl2c.github.io) for our GEDL tutorials, but also for materials on other interesting topics such as Bayesian Deep Learning, Deep Probabilstic Models, Causality, Dynamical Systems, etc. Please check them out as well!

Youtube playlist:
* [Youtube playlist](https://youtube.com/playlist?list=PL8FnQMH2k7jzPrxqdYufoiYVHim8PyZWd)

Lecture slide deck:
* Lecture 1: Regular group convolutional neural networks
  * [Lecture 1.1](lectures_pdf/Lecture_1_1_Motivation.pdf) - Introduction
  * [Lecture 1.2](lectures_pdf/Lecture_1_2_GroupTheory.pdf) - Group theory: Groups, group product, inverse, action, representation, affine groups G = Rd ⋊ H
  * [Lecture 1.3](lectures_pdf/Lecture_1_3_RegularGroupConvolutions.pdf) - Regular group convolutions: Template matching viewpoing
  * [Lecture 1.4](lectures_pdf/Lecture_1_4_Example.pdf) - SE(2) Equivariant NN Example: histopathology
  * [Lecture 1.5](lectures_pdf/Lecture_1_5_History.pdf) - A brief history of G-CNNs
  * [Lecture 1.6](lectures_pdf/Lecture_1_6_GroupTheory.pdf) - Group Theory: Transitive action, homogeneous space, quotient space
  * [Lecture 1.7](lectures_pdf/Lecture_1_7_GConvsAreAllYouNeed.pdf) - Group convolutions are all you need! (Equivariant linear layers between feature maps are group convolutions)

* Lecture 2: Steeragble group convolutional neural networks
  * [Lecture 2.1](lectures_pdf/Lecture_2_1_SteerableBasis.pdf) - Steerable kernels/basis functions (Definition and SO(2) example)
  * [Lecture 2.2](lectures_pdf/Lecture_2_2_RegularGConvInSteerableBasis.pdf) - Revisiting regular G-convs with steerable kernels (Motivating the Fourier transform)
  * [Lecture 2.3](lectures_pdf/Lecture_2_3_GroupTheoryIrrepsFourier.pdf) - Group Theory: Irreducible representations and Fourier transform
  * [Lecture 2.4](lectures_pdf/Lecture_2_4_GroupTheoryFeatureFields.pdf) - Group Theory: Induced representations and feature fields
  * [Lecture 2.5](lectures_pdf/Lecture_2_5_SteerableGConvs.pdf) - Steerable group convolutions, and how to use them
  * [Lecture 2.6](lectures_pdf/Lecture_2_6_ActivationFunctions.pdf) - Activation functions for steerable G-CNNs
  * [Lecture 2.7](lectures_pdf/Lecture_2_7_HarmonicNetworks.pdf) - Derivation of Harmonic networks from regular g-convs

* Lecture 3: Equivariant graph neural networks
  * [Lecture 3.1](lectures_pdf/Lecture_3_1_Motivation.pdf) - Motivation for SE(3) equivariant graph NNs
  * [Lecture 3.2](lectures_pdf/Lecture_3_2_EquivariantMessagePassing.pdf) - Equivariant message passing as non-linear convolution
  * [Lecture 3.3](lectures_pdf/Lecture_3_3_ConditionalLinear.pdf) - Tensor products as conditional linear layers (and MLPs)
  * [Lecture 3.4](lectures_pdf/Lecture_3_4_GroupTheorySO3IrrepsClebschGordan.pdf) - Group Theory: SO(3) irreps (Wigner-D matrices), Clebsch-Gordan TP
  * [Lecture 3.5](lectures_pdf/Lecture_3_5_Literature3DSteerable.pdf) - Literature: 3D Steerable (graph) convolutions
  * [Lecture 3.6](lectures_pdf/Lecture_3_6_Literature3DRegular.pdf) - Literature: Regular (as opposed to steerable) equivariant graph NNs
  * [Lecture 3.7](lectures_pdf/Lecture_3_7_GaugeEquivariant.pdf) - Literature: Gauge equivariant graph NNs

Lecture notes (work in progress...):
* [Lecture notes](GroupConvLectureNotes.pdf)

Slides and lecture recording (summer school):
* [Slides](GEDL_slides.pdf) and corresponding [link to recorded talk](https://geometric-deep-learning.compute.dtu.dk/talks-and-materials/)
* [Slides talk at Lorentz Center](2021-10-16 - Lorentz Center.pdf)

Colab assignments (to be updated...):
* [Library demos] Please check out these amazing libraries: [e2cnn](https://github.com/QUVA-Lab/e2cnn) and [e3nn](https://e3nn.org)
* [Colab Assigment 1 (SE(2) gconvs)](https://colab.research.google.com/drive/1DfUuk-NZtW5d0toMnL752dYEMSVuNWgM?usp=sharing): Thanks to Gabriele Cesa for providing these! These assignments were used in the [Geometric-Deep Learning Course](https://geometricdeeplearning.com/lectures/)  
* [Colab Assigment 2 (SE(3) steerable gconvs](https://colab.research.google.com/drive/1ZtV6_U6lt7URvTHC71SwbUNCiEfK6aD1?usp=sharing)

