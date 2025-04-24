# Introduction to Data Analysis, With Python and Jupyter

These are course notes and resources for Physics 89L, Introduction to Data Analysis, With Python and Jupyter

## Course Descriptions

Welcome to Physics 89L. The main goal of this course is to teach you how to draw a conclusion from data. In practice, this involves learning fundamental data analysis techniques and statistics. This is intended to prepare you for conducting research in physics or astronomy, but we believe that the concepts are applicable broadly to anything that requires you to look at data.

**We believe an active learning approach, where we spend more time understanding and discussing the problems that these methods are intended to solve will help you to a deeper understanding of both the tools, and why we use them for data analysis.**

## Course Objectives

Top level goals – you will learn how to:

  1. use python and jupyter notebooks to do simple data analysis and make plots
  2. assign an uncertainty to an experimental measurement
  3. have a defensible result from an experiment
  4. identify and quantify statistical and systematic uncertainties in an experimental measurement

Techniques to learn that will help reach the goal:

  1. finding mean, variance, standard deviation of discrete and continuous data sets
  2. uncertainty propagation
  3. least squares curve fitting
  4. use distributions to predict statistical spreads in data (in this class, primarily Gaussian and Poisson distributions)

## Course Contents

Start by looking at the materials under the "Getting Started" bullet
point to understand how this course works, and get up and running with
the software tools that you will be using in the course.

* __Getting Started__
  * [Syllabus](syllabus.md)
  * [Software setup](setup.md)
  * [Social guidelines and expectations](social.md)

The content for lab sections, including some introductory materials and 
lists of important new python functions that you might encounter, are 
included below. Content is separated by week, with links to relevant slides, 
as well as the notebooks that we will work with for a particular week.

* __Notes for Week 1__: 
  * Topics: Introduction, histograms, descriptive statistics
  * [Class Slides](https://docs.google.com/presentation/d/1oONrehiWppdOPcdKFqAiprrtvHAZW3NNBZTkdjiGZjY/edit?usp=drive_link)
  * [Background and reference](Week1.md)
  * [Notebook 1: "Look at this figure"](https://github.com/KIPAC/Physics89L/blob/main/nb/01_01_Look%20At%20This%20Figure.ipynb)
  * [Notebook 2: "Dice rolls and histograms"](https://github.com/KIPAC/Physics89L/blob/main/nb/01_02_Dice_Rolls_and_Histograms.ipynb)
  * [Notebook 3: "Hubble constant measurements"](https://github.com/KIPAC/Physics89L/blob/main/nb/01_03_Hubble_Measurements.ipynb)

* __Notes for Week 2__: 
  * Topics: Weighted averages and Poisson statistics
  * [Class Slides](https://docs.google.com/presentation/d/10oGu6gCkJHGlzFacibRNGO9N9UCMHZs2D8onFtHvj1U/edit?usp=drive_link)
  * [Background and reference](Week2.md)
  * [Notebook 1: "Hubble constant uncertainties"](https://github.com/KIPAC/Physics89L/blob/main/nb/02_01_Hubble_Constant_Uncertainties.ipynb)
  * [Notebook 2: "Counting muons"](https://github.com/KIPAC/Physics89L/blob/main/nb/02_02_Counting_Muons.ipynb)

* __Notes for Week 3__: 
  * Topics: Uncertainty propagation
  * [Class Slides](https://docs.google.com/presentation/d/1KYdIyR7Fsi8EjeLXtAEkIC6XE6a-BLAJ-hWVVxcbbhM/edit?usp=drive_link)
  * [Background and reference](Week3.md)
  * [Notebook 1: "Propagation of Uncertainty"](https://github.com/KIPAC/Physics89L/blob/main/nb/03_01_Propagation_of_Uncertainty.ipynb)
  * [Notebook 2: "More propagation of Uncertainties"](https://github.com/KIPAC/Physics89L/blob/main/nb/03_02_More_Uncertainty_Propagation.ipynb)


* __Notes for Week 4__: 
  * Topics: Gaussians and p-values
  * [Class Slides](https://docs.google.com/presentation/d/1w_4uGckpBr8uVEaR15bQtk4VeMH32Zndq_uqovBuSdI/edit?usp=drive_link)
  * [Background and reference](Week4.md)
  * [Notebook 1: "Let's make a Gaussian"](https://github.com/KIPAC/Physics89L/blob/main/nb/04_01_Lets_Make_A_Gaussian.ipynb)
  * [Notebook 2: "Vela pulsar"](https://github.com/KIPAC/Physics89L/blob/main/nb/04_02_Vela_Pulsar.ipynb)


<!-- 

  
* Notes for Week 5: 
  * Topics: Covariance, correlation, chi-square fitting
  * [Class Slides](https://docs.google.com/presentation/d/1CE4O-7-3nmCA5gCCSP0jctQhJQ6hbJWk50GfUwRc2DM/edit?usp=drive_link)
  * [Background and reference](Week5.md)
  * [Notebook 1: "Correlations"](https://github.com/KIPAC/Physics89L/blob/main/nb/05_01_Correlations.ipynb)
  * [Notebook 2: "Fitting a line to data"](https://github.com/KIPAC/Physics89L/blob/main/nb/05_02_Fitting_A_Line_to_Data.ipynb)


* Notes for Week 6: 
  * Topics: Minimizers and fitting
  * [Class Slides](https://docs.google.com/presentation/d/1j0wjFUgtc2soVB9F4MYKADD8ZciIHu4oSPVdy2MAtCA/edit?usp=drive_link)
  * [Background and reference](Week6.md)
  * [Notebook 1: "Optimizing a fit and how to do it wrong"](https://github.com/KIPAC/Physics89L/blob/main/nb/06_01_Optimizing_a_fit_and_how_to_do_it_wrong.ipynb)
  * [Notebook 2: "SDSS Spectra"](https://github.com/KIPAC/Physics89L/blob/main/nb/06_02_SDSS_Spectra.ipynb)


* Notes for Week 7: 
  * Topics: Data selection, efficiency, leakage, and rare event searches
  * [Class Slides](https://docs.google.com/presentation/d/1bUFvjURaFfh8noQgN8aniutybcj8ZFD86HQS8SyYLK0/edit?usp=drive_link)
  * [Background and reference](Week7.md)
  * [Notebook 1: "Optimizing selections"](https://github.com/KIPAC/Physics89L/blob/main/nb/07_01_Cuts_Acceptance_Leakage.ipynb)
  * [Notebook 2: "Performing a dark matter search"](https://github.com/KIPAC/Physics89L/blob/main/nb/07_02_Performing_a_Dark_Matter_Search.ipynb)


* Notes for Week 8: 
  * Topics: Frequency analysis
  * [Class Slides](https://docs.google.com/presentation/d/1qtrlylFrjuZ-4gW7CGqLBHZMTaFwV9tr8LRbnJbtHls/edit?usp=drive_link)
  * [Background and reference](Week8.md)
  * [Notebook 1: "Introduction to Fourier Analysis"](https://github.com/KIPAC/Physics89L/blob/main/nb/08_01_Intro_Fourier_Analysis.ipynb)
  * [Notebook 2: "Ripples in 2D Electron Gas"](https://github.com/KIPAC/Physics89L/blob/main/nb/08_02_Ripples_in_2D_Electron_Gas.ipynb)


* Final Projects:
  * [Class Slides](https://docs.google.com/presentation/d/1k2FrQduyliD4SHFxkTNZp1OavsTBbc2UtjZyiGl7kJE/edit?usp=drive_link)
  * [Overview](Projects.md) 
-->


## Contact and Legal

All materials Copyright 2021 Eric Charles, Ryan Linehan and Benjamin
Navid Safvati and distributed for copying and extension under the
GPLv3 License, unless otherwise noted.

Mod. Physics 89L Spring 2023 Ann Wang, George Halal, Drew Ames

Mod. Physics 89L Spring 2025 Charles Blakemore

If you have any feedback for us, please write us an issue.

<!--  LocalWords:  jupyter setup.md Linehan
 -->
