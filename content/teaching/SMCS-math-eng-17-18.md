+++
# Date this page was created.
date = "2018-06-07"

# Project title.
title = "Statistical Mechanics of Complex Systems"

# Project summary to display on homepage.
summary = "Mathematical Engineering, academic year 2017-2018"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["past-courses"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""
+++

[Here](http://en.didattica.unipd.it/off/2018/LM/IN/IN2191/001PD/INP5070381/N0) you can find the course page on the university database.

Please send the exercises to <a href="mailto:suweis@pd.infn.it">suweis@pd.infn.it</a> with object "Exercise Ing 2018".

## Some notes on stochastic processes
[Here](/files/IM2017/notes/notes-maritan1.pdf) you can find notes on stochastic processes.
[Here](/files/IM2017/notes/notes-maritan2.pdf) you can find notes on persistence times of a birth-death process.


## Introduction to Monte Carlo methods
* Generation of sequences of **uniformly distributed** (pseudo)random numbers, using different simple congruent methods, illustrating their performance. [Source code](/files/IM2017/code/random_uniform.py).
* Generation of **exponentially distributed** random numbers, using the inverse method. [Source code](/files/IM2017/code/random_exp.py).
* Generation of **Gaussian** random numbers, using the Box-Muller method. [Source code](/files/IM2017/code/random_gauss.py).
* [Exercises](/files/IM2017/exercises.txt).


## Maxwell-Boltzmann distribution for ideal gases
* Calculation of the **pressure from microscopic collisions** with the wall (Ex. 3.4 Sethna).
We run a simulation and compute the histogram of collisions in the right wall during an interval of time, as a function of the moment carried by the particles. [Source code](/files/IM2017/code/ideal_gas_pressure.py) (need to be improved!).


## Introduction to Complex Networks
* [Some slides](/files/IM2017/notes/Introduction_Complex_Networks.pdf).
* Simulation: how to generate random [Erdős–Rényi](https://inst.eecs.berkeley.edu/~ee126/fa14/lab/Lab9_RandomGraphs.pdf) and small world networks (Ex. 3.7 Sethna).
* HOMEWORK (to submit by Thursday 12 April): Analyze the [Marvel-Heros Social Network](/files/IM2017/Marvel-Heros-Social-Network-exercise.rtf)! If the network is too large, and you have problem in analyzing it, you can instead study the following [brain network](static/files/IM2017/brainWeightedAdj.dat) (see Exercise 2 in the homework); it is a .dat file describing the weighted adjacency matrix, so it is very easy to upload and start to work on it.


## Fractals
* Summary of the Mathematica program discussed in class (.cdf can be read also without having Mathematica: you can download CDF viewer for free in the Wolfram website) [CDF Mathematica Notebook](/files/IM2017/Lezione-Frattali-to-upload.cdf).
* HOMEWORK: [exercise](/files/IM2017/Fractal-Excercise-ING2018.pdf) on fractals.


## Monte Carlo simulation of equilibrium processes
* [Summary and Exercise](/files/IM2017/Ising-simulation.pdf). Deadline: 1 June 2018.
* Simulation: Metropolis algorithm for the Ising model in a 2D-lattice. [Source code](/files/IM2017/code/markov_ising_movie.py).
* Simulation: Cluster algorithm for the Ising model in a 2D-lattice. [Source code](/files/IM2017/code/cluster_ising_movie.py).
* Notes and Simulation: Fractal in the Ising Model. [Source code](/files/IM2017/notes/fractal-ising.zip).

**Bibliography**: W. Krauth, [Cluster Monte Carlo algorithms](/files/IM2017/cluster-ising.Krauth.pdf).


## Stochastic Interacting Particle Models and applications
* [Review](/files/IM2017/notes/RevModPhys.88.035003.pdf) on the application of the Voter Model in Ecology.
* [Voter Model code](http://demonstrations.wolfram.com/VoterModel/) from Wolfram Demonstration Project.
* [Notes and code](/files/IM2017/notes/gillespie.zip) on stochastic reactions formalism and Gillespie algorithm.
* [Notes](/files/IM2017/notes/diffusion1D.pdf) on how to solve diffusion Equation for the voter model.

**Bibliography**: D. Gillespie, [Stochastic Simulation of Chemical Kinetics](/files/IM2017/notes/gillespie2007.pdf), Annual Review of Physical Chemistry.


## [Examples](/files/IM2017/old_exams.zip) of exams of previous years
