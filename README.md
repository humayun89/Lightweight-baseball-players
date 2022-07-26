# Lightweight-baseball-players
o subset both regular Python lists and numpy arrays, you can use square brackets:

x = [4 , 9 , 6, 3, 1]
x[1]
import numpy as np
y = np.array(x)
y[1]
For numpy specifically, you can also use boolean numpy arrays:

high = y > 5
y[high]
The code that calculates the BMI of all baseball players is already included. Follow the instructions and reveal interesting things from the data!

Create a boolean numpy array: the element of the array should be True if the corresponding baseball player’s BMI is below 21. You can use the < operator for this. Name the array light.
