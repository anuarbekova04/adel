# adel
room for practice

import numpy as *


text = open("hw1.txt")
x_val = np.array("")

for i in range(100):
    x = text.read(i)
    print(i , x)

text.close()
