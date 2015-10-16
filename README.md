# MCpermanent
A python module written in C++ to compute the permanent of a numpy matrix upto given accuracy  using random Monte Carlo method.

Installing:
python setup.py build
sudo python setup.py install

Usage:

import numpy as np

from mcpermanent import mcpermanent 

a=np.random.rand(3,3)

mcpermanent(a,1e-3)

