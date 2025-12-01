# MiniCourse-DifferentiableSimulation

A short course on JAX, automatic differentiation, the adjoint state method and differentiable simulators.

Author: Dr Aidan Crilly (ac116@ic.ac.uk)

**Course details:**

**Date:**
Wednesday 25th June

**Short description:**
The course aims to describe how to add trainable data-driven terms to physics-based differential equation models.

**Length:**
Half-day (4-5 hours with break), starting 10am

**Pre-requisites:**
Some Python knowledge (Imperial Physics undergraduate course level)
Bring a laptop, course will be on Google colab (so just browser based and cloud computing so doesn't need to be good laptop).

**Learning outcomes:**
The course aims to teach how we can use automatic differentiation (a tool developed for machine learning) to gain linear sensitivity information about ODE and PDE numerical solutions. We can then use this information to add trainable terms to these models. For example, learn the thermal conductivity from temperature data and the heat equation. To do this you will learn the basic use of the following libraries: JAX, diffrax, optax, equinox

**Course Materials**

The course includes lecture material and four Google colab notebooks:

 - An introduction to JAX: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidancrilly/MiniCourse-DifferentiableSimulation/blob/main/00_JAXIntro.ipynb) (and extended version [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidancrilly/MiniCourse-DifferentiableSimulation/blob/main/Extended00_JAXIntro.ipynb))

 - Computational graphs and implementing adjoint methods by hand: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidancrilly/MiniCourse-DifferentiableSimulation/blob/main/01_ComputationalGraphsAndAdjointMethods.ipynb)

 - Use of differentiable programming libraries to create differentiable simulators: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidancrilly/MiniCourse-DifferentiableSimulation/blob/main/02_DifferentiableSimulatorsAndOptimisation.ipynb)

 - Summary exercises to test and consolidate your knowledge: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidancrilly/MiniCourse-DifferentiableSimulation/blob/main/03_SummaryExercises.ipynb)

This is based on a similar [course](https://github.com/aidancrilly/AIMSLecture) given to the 'AI in Sciences' masters program at the African Institute of Mathematical Sciences (AIMS).
