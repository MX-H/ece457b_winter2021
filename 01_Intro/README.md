# ECE 457B: Programming Tools

The first lab will serve as an introduction to the various tools we will be using within this course.

## Preparing your system

Python is a general purpose programming language that has gained a lot of popularity recently due to its code readability and ease of learning.
It is currently the most popular programming for Machine Learning algorithms and Neural Networks (also known as the more fancy word: "Deep Learning").
This is due to the great community support it receives from both individuals and large technology companies and the open-source nature of many frameworks.

So using Python for such applications translates into: Pay less (or nothing), and get more!

### Prepare your Virtual Environment
A virtual environment allows you to keep your various Python projects separate as different projects have different dependencies (packages and versions) to be able to run.
This protects your various projects from interfering with each other. 

First, create a virtual environment for the course. 

* Anaconda
```
conda create -n env_name python=x.x anaconda

conda activate env_name
```

* Pip
```
python3 -m venv env_name
``` 
    
1. Windows
```
.\pathtofolder\env_name\Source\activate
```

2. Linux/macOS
```
source ./pathtofolder/env_name/bin/activate
```


**Install Tensorflow**:

* Pip
```
pip install --ignore-installed --upgrade tensorflow==2.0.0
```

* Anaconda
```
conda install -c conda-forge tensorflow==2.0.0
```

**Check installed packages**
Run python and import the following packages

```python
import numpy as np

import matplotlib.pyplot as plt

import tensorflow as tf
    
```
