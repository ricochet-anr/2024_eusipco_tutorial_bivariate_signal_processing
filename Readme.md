# Welcome to the 2024 Eusipco tutorial on bivariate signal processing!

This repository accompanies the bivariate signal processing tutorial presented at [Eusipco 2024](https://eusipcolyon.sciencesconf.org) in Lyon, France on Monday, 26th August. 

> **T-AM3 - An introduction to bivariate signal processing: polarization, quaternions and geometric representations**
> **Organizers**: Nicolas Le Bihan (CNRS, Université Grenoble-Alpes, Gipsa Lab) and Julien Flamant (CNRS, Université de Lorraine, CRAN)
>
<details>
  <summary>Click to expand Abstract</summary>
  
An important task of data science is to represent and evidence the interrelation between coupled observables. The simple case of two observables that vary in time or space leads to bivariate signals. Those appear in virtually all fields of physical sciences, whenever two quantities of interest are related and jointly measured, such as in seismology (e.g. horizontal vs vertical ground motion), optics (transverse coordinates of the electric field), oceanography (components of current velocities), or underwater acoustics (horizontal vs vertical particle displacements) to cite a few.<br/>

Bivariate signals describe trajectories in a 2D plane whose geometric properties (e.g. directionality) have a natural interpretation in terms of the physical notion of polarization usually used for waves. As an example, according to Einstein’s theory of general relativity, the recently detected gravitational waves (GWs) are characterized by two degrees of freedom, that are connected to the bivariate space-time strain signal measured by the detectors. The polarization state of the observed signal is directly connected to that of the wave, which in turn provides key insights into the underlying physics of the source. Polarization is thus a central concept for the analysis of bivariate signals.<br/>

Two usual representations exist for analyzing and processing bivariate signals. The first one is based on 2D real-valued vectors, where a bivariate signal is seen as a special case of a more general multivariate signal. The second one relies on a complex representation, where the real and imaginary parts of a univariate complex signal correspond to the two components of the above 2D real-valued vector signal. Both representations have their merits; however, these two approaches do not provide straightforward descriptions of bivariate signals or filtering operations in terms of polarization properties. To this purpose, the tutorial speakers (and their collaborators) have introduced a new and generic approach for the analysis and filtering of bivariate signals. It relies on the one hand on the natural embedding of bivariate signals – viewed as complex-valued signals – into the set of quaternions and, on the other hand, the definition of a dedicated quaternion Fourier transform to enable a meaningful spectral representation and analysis of bivariate signals. 

This quaternion representation lays down the first building blocks of a signal processing methodology that simultaneously provides: (i) straightforward geometric and physical interpretations (ii) mathematically grounded tools and (iii) efficient numerical implementations.
This tutorial aims at providing insights into the specificity of the bivariate signal processing and its deep connections with the physics of polarization. Emphasis on the geometric interpretation of bivariate signal processing will be made and illustrated with tutorial examples based on the BiSPy toolbox.
</details>

# Notebooks
Numerical experiments are provided troughout the tutorial thanks to the python package [BiSPy](https://github.com/jflamant/bispy). If you use ``pip`` the package (and its dependencies) can be simply installed from PyPi using ``pip install bispy-polar``. 

In the folder ``notebooks/`` you'll find three companion notebooks for the tutorial. They are designed to run online in Google Colab. You can also download them and run them locally if you prefer.

1. BiSPy basics and the monochromatic signal example  [.ipynb file](https://github.com/ricochet-anr/2024_eusipco_tutorial_bivariate_signal_processing/blob/main/notebooks/I_BiSPy_basics.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://githubtocolab.com/ricochet-anr/2024_eusipco_tutorial_bivariate_signal_processing/blob/main/notebooks/I_BiSPy_basics.ipynb)

2. Spectral analysis and linear filtering  [.ipynb file](https://github.com/ricochet-anr/2024_eusipco_tutorial_bivariate_signal_processing/blob/main/notebooks/II_spectral_analysis.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://githubtocolab.com/ricochet-anr/2024_eusipco_tutorial_bivariate_signal_processing/blob/main/notebooks/II_spectral_analysis.ipynb)

3. Time-frequency analysis  [.ipynb file](https://github.com/ricochet-anr/2024_eusipco_tutorial_bivariate_signal_processing/blob/main/notebooks/III_timefrequency_analysis.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://githubtocolab.com/ricochet-anr/2024_eusipco_tutorial_bivariate_signal_processing/blob/main/notebooks/III_timefrequency_analysis.ipynb)

To go further, you can also check BiSPy's tutorials and documentation [here](https://bispy.readthedocs.io/en/latest/).

# Slides

Slides of the tutorial are available in pdf format in the ``slides/`` folder. 

# References 

Main references used throughout the tutorial are:

- "*A general approach for the analysis and filtering of bivariate signals*", J. Flamant, Phd thesis, Lille University, 2018.
[HAL link](https://hal.science/tel-01926941)
- "*Spectral analysis of stationary random bivariate signals*", J. Flamant, N. Le Bihan and P. Chainais, IEEE Transactions on Signal Processing (TSP), vol. 65, num. 23, pp. 6135-6145, 2017.
[HAL link](https://hal.science/hal-01655097/document)
- "*A Complete Framework for Linear Filtering of Bivariate Signals*", J. Flamant, P. Chainais and N. Le Bihan, IEEE Transactions on Signal Processing (TSP), vol. 66, num. 17, pp.4541-4552, 2018.
[HAL link](https://arxiv.org/pdf/1802.02469)
- “*Time-frequency analysis of bivariate signals*”, J. Flamant, N. Le Bihan and P. Chainais., Applied and Computational Harmonic Analysis (ACHA), vol. 46, issue 2, pp. 351-383, 2019.
[HAL link](https://hal.science/hal-01362586/file/1609.02463v1.pdf)
