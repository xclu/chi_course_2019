
[![Binder](http://mybinder.org/badge_logo.svg)](http://beta.mybinder.org/v2/gh/johnhw/chi_course_2019/master)

<img src="imgs/chi2019_logo_final.png">

# Course on Computational Interaction with Bayesian Methods
### Nikola Banovic, Per Ola Kristensson, Antti Oulasvirta, John Williamson


* 0900 - 1720 Wednesday 8 May 2019, Glasgow, UK

[See the course website for full details](http://pokristensson.com/chicourse19/)

----

## [Launch the notebooks on Binder](http://beta.mybinder.org/v2/gh/johnhw/chi_course_2019/master)


## Notebooks

* 0900-1020 [01_intro_to_bayesian_methods/](01_intro_to_bayesian_methods/Introduction_to_Bayesian_Methods_in_HCI.ipynb) Introduction to Bayesian methods in HCI and Bayesian filtering to estimate state
* 1100-1220 [02_decoding_symbols/](02_decoding_symbols/DecodingTutorial.ipynb)
* 1400-1520 [03_bayesian_optimisation/](03_bayesian_optimisation/Introduction_to_Bayesian_Optimization_CHI2019.ipynb)
* 1600-1720 [04_modeling_behavior/](04_modeling_behavior/modeling_behavior.ipynb)
    
## Topic
The course focuses on optimization and inference and on applying these techniques to concrete HCI problems. The course will specifically look at Bayesian methods for solving decoding, adaptation, learning and optimization problems in HCI. The lectures center on hands-on Python programming interleaved with theory and practical examples grounded in problems of wide interest in human-computer interaction.

## Instructors
The following faculty members will teach the course:

* [Nikola Banovic](http://www.nikolabanovic.net/), University of Michigan, USA
* [Per Ola Kristensson](http://pokristensson.com/), University of Cambridge, UK
* [Antti Oulasvirta](http://users.comnet.aalto.fi/oulasvir/), Aalto University, Finland
* [John Williamson](http://www.dcs.gla.ac.uk/~jhw/), University of Glasgow, UK    

---

## Local install instructions
If you are not using `mybinder.org`, then you can download and install a local version:

* [Install Anaconda 3.7 for your platform](https://www.anaconda.com/distribution/) if you don't already have it installed

* Clone the repository somewhere on your machine

        git clone https://github.com/johnhw/chi_course_2019.git

* At the terminal, enter the directory where you cloned the repo
* Create a new conda environment with the prerequisites

        conda env create -f environment.yml

* Activate the environment with

        conda activate chi-course-2019
        
* Start the notebook server with 

      jupyter notebook
    
* and then open `index.ipynb`
