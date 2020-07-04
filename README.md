# First-file
The first file in github
#Title of the project: plot of $sinx/x$ between -4*pi to 4*pi
%matpoltlib inspace
import matplotlib.pyplot as plt 
import numpy as np 
pi = np.pi
x = np.linspace(-4*pi, 4*pi, 1000)
plt.plot(x, np.sin(x)/x)
plt.show()
