# Python Notebook

## What is Python?  
Python is an **interpreted**, **object-oriented**, **high-level** programming language with **dynamic semantics**.   

Its high-level built in data structures, combined with **dynamic typing** and **dynamic binding**, make it very attractive for **Rapid** Application Development, as well as for use as a scripting or glue language to connect existing components together.   

Python's **simple**, **easy** to learn syntax emphasizes readability and therefore **reduces the cost of program maintenance**. Python supports **modules** and packages, which encourages program modularity and code reuse.  

The Python interpreter and the extensive standard library are available in **source** or **binary** form without charge for **all major platforms**, and can be freely distributed.

## Installation

### Only Python
Go to the [Python Download Website](https://www.python.org/downloads/), download the `python.exe` based on the release version.

### Using Anaconda
Download [Miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links) / [Anaconda](https://www.anaconda.com/products/distribution), using conda to manage Python environment, basically like this:   
```bash
conda create -n my_python_env_name python=3.7
conda activate my_python_env_name
```
If new Python modules needed, using `pip` or `conda` to install them.
```bash
pip install numpy
```  
or  
```bash
conda install numpy
```
Actually, in conda environment, `mamba` is also recommended, the usage of `mamba` is basically the same as `conda`.
```bash
conda install mamba
mamba install numpy
``` 

## Reference

1. https://docs.python.org/3/
2. https://numpy.org/doc/stable/user/quickstart.html
3. https://matplotlib.org/stable/tutorials/introductory/pyplot.html 
