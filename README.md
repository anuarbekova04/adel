# adel
room for practice
import numpy as np

text = open("hw1.txt")
x_val = np.array("")

for i in range(100):
    x = text.readline(i)
    print(i , x)
print(x_val)
text.close()
