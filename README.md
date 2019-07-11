# Learning Scientific Software using Jupyter notebooks

We are exploring HPC Algorithms used in large scale scientific experiments using Jupyter notebooks.

We have learned about the following scientific software projects:

 - Software used for the analysis of gravitational waves
 - Software designed for the square kilometer array (SKA)

 
## Getting Started

These instruction guide you to get the Jupyter notebook up and running on your local machine.

### Prerequisites 

To run the Jupyter notebooks on your machine you need to install the following software packages and libraries. 

-   [Python](https://python.org/)  2.7, or 3.4 or greater
-   [`astropy`](http://www.astropy.org/)  `>=  1.1.1`
-   [`dateutil`](https://pypi.python.org/pypi/python-dateutil/)
-   [`dqsegdb2`](https://dqsegdb2.readthedocs.io/)
-   [`enum34`](https://bitbucket.org/stoneleaf/enum34)  (Python 2.7 only)
-   [|gwdatafind|_](https://gwpy.github.io/docs/stable/install/#id3)
-   `gwosc`  `>=  0.3.1`
-   [`h5py`](http://docs.h5py.org/en/latest/)  `>=  1.3.0`
-   [`ligo-segments`](https://lscsoft.docs.ligo.org/ligo-segments/)  `>=  1.0.0`
-   [`ligotimegps`](https://github.com/gwpy/ligotimegps/)  `>=  1.2.1`
-   [`matplotlib`](https://matplotlib.org/)  `>=  1.2.0`
-   [](http://numpy.org/)[`numpy`](https://docs.scipy.org/doc/numpy/reference/index.html#module-numpy "(in NumPy v1.16)")  `>=  1.7.1`
-   [`scipy`](http://www.scipy.org/)  `>=  0.12.1`
-   [`six`](https://six.readthedocs.io/)  `>=  1.5.0`
-   [`tqdm`](https://github.com/tqdm/tqdm)  `>=  4.10.0`


#### Anaconda 

We highly recommend to use Anaconda in order to get a stable environement for Jupyter-Notebook  <br>
[Download Anaconda](https://www.anaconda.com/distribution/)


### Installation

GWpy is a package that makes the analysis of gravitational waves easy for beginners. 

To install GWpy, run the following command from terminal:
```
pip install gwpy
```

### References and materials

We mostly based our studies around this project 

https://github.com/minrk/ligo-binder <br>

It is a tutorial on how the LIGO team analysed their data to find evidences of gravitational events.

Here are some other interesting link we used :

### How to run the tutorials of LIGO

open the Gravitational Waves Analysis\LOSC_Event_tutorial.ipynb and follow the step

**The Gravitational Wave Open Science Center**

Where most of out ressources were found.<br>
https://www.gw-openscience.org/start/<br>
It is a website dedicated to help get citizen started in gravitational wave studies.
It provides data of events and tutorials on how to analyse them.

**gwosc**

It is a set of tool to fetch data and analyse gravitational events.
It can be installed using your python distribution :

```sh
python -m pip install "gwosc"
```

To get used to **gwosc** we followed the tutorials at : <br>
https://github.com/gw-odw


**GWpy** <br>

GWpy is a python package that is a collection of tool that are generally used to study data from gravitational wave detectors. <br>

The package is easy to use and well documented.<br>

The official documentation for GWpy can be found at https://gwpy.github.io/docs/stable/


**sample_data**

The results for the code run are in the Gravitational Waves Folder and include the following material.

The 4 samples are used in tutorias; GW150914, GW151226, GW170104 LVT151012.

Each folder include the results of analysis 


### Authors

 -Ilgwon Park -Gangmin Park -Cyril Briand - Umar Farooq

 ### Acknowledgements

Our project would not have been possible without the help and guidance from all the mentors in the Software for Science summer school team.
