# Programation
import numpy as np

a = np.array([12, 45, 28, 77, 66, 35])

b = len(a)
rr = range(b)   #Python 2 se podía utilizar arrange (números flotantes) y range (no flotantes)
                #Python 3 se unifico se quedo solo con range
"""
for i in rr:
    if a[i] == 66:
        print("Hola")
    elif a[i] == 77:
        print("Lazo de continuidad")
    elif a[i] <= 28:
        print("2do Lazo de continuidad")
    else:
        print("Chao")
"""

b = np.array(["Mk", "Mn", "Ms", "Md"])
l2 = len(b)
r2 = range(l2)

for i in r2:
    if b[i] == "Mk":
        print("Hola otra vez")
    elif b[i] >= "Mn":
        print("1er Lazo")
    else:
        print("error no cumple condición")
