# PWM_logo
This is a simple script displays the familar Position Weight Matrix logo from from a frequency matrix in python. 
Example usage is below and requires only matplotlib. Please let me know of any questions! 

# Usage
'''
import draw_logo
import matplotlib.pyplot as plt
A=[[ 0.356611,0.085184,0.455087,0.103118],
       [ 0.217352,0.033832,0.616781,0.132036],
       [ 0.411544,0.053398,0.486295,0.048762],
       [ 0.026776,0.902577,0.020027,0.050619],
       [ 0.773107,0.016504,0.055813,0.154576],
       [ 0.121956,0.027309,0.046496,0.804239],
       [ 0.010707,0.015609,0.947804,0.025881]]
ax       = plt.gca()
L        = draw_logo.logo(A, name="P53")
L.draw(ax=ax)
plt.show()
'''

The input matrix can be normalized or unnormalized, a numpy array or a list of lists. Importantly the column order show be:
A,C,G,T

![Alt text](https://github.com/azofeifa/PWM_logo/blob/master/images/example.png)
