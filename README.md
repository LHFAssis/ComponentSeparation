# ComponentSeparation
This repository was created with the aim of maintaining and adapting codes for component separation methods and wavelet transforms. At the moment, it's main purpose is to reproduce [BINGO's radiotelescope](https://bingotelescope.org/) configuration for separation of 21cm hidrogen line emissions from foregrounds and noise.

### Credits and Thanks

I would like to thank [Alessandro Marins](https://github.com/marinscosmo) and [Isabella Carucci](https://github.com/isab3lla) for providing the codes necessary to start working with the techniques.

I would like to thank **Filipe Abdalla**, **Karin Fornazier**, **Alessandro Marins** and **Julia Leite** for academic discussions and teaching of component separation methods and signal processing in cosmology.

# Methods and wavelets
1. Component Separation Methods  
    1.1. Generalized Morphological Component Analysis ([GMCA](https://github.com/isab3lla/gmca4im/blob/master/README.md)) by Jerome Bobin and Isabella Carucci  
    1.2. Fast Independent Component Analysis (FastICA) by scikit-learn python package  
2. Wavelet Transforms  
    2.1 Starlet (Isotropic Undecimated Wavelet Transform) by Starck  
    2.2 Pywavelets by pywavelets python package  
    2.3 Axisymmetric Wavelet Transform by McEwen  
    2.4 Directional Wavelet Transform by McEwen  

### Requirements and Libraries

+ [python](https://www.python.org/)
+ [jupyter](https://jupyter.org/)
+ [matplotlib](https://matplotlib.org/)
+ [pandas](https://pandas.pydata.org/)
+ [numPy](https://numpy.org/)
+ [healpy](https://healpy.readthedocs.io/en/latest/)
+ [astropy](https://www.astropy.org/)
+ [scipy](https://www.scipy.org/)
+ [h5py](https://www.h5py.org/)
+ [scikit-learn](https://scikit-learn.org/stable/)
+ [pywavelets](https://pypi.org/project/PyWavelets/)
+ [pys2let](https://pypi.org/project/pys2let/)
+ [mtneedlet](https://javicarron.github.io/mtneedlet/index.html#)
+ [progressbar2](https://pypi.org/project/progressbar2/)
+ [Extension4BINGO](https://github.com/marinscosmo/CHISEL-Co-HI-Signals-Extraction-from-Line-intensity-mapping/tree/main/scripts)

### Contacts
If you have any question, commentary or suggestion:
+ alessandro.marins@usp.br
+ karin.fornazier@gmail.com
+ filipe.abdalla@gmail.com
+ julialeite.carvalho@usp.br
+ luiz.henrique.assis@usp.br
