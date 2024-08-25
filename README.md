# Assigmnt-05

def max_of_three(a, b, c):
    if a >= b and a >= c:
        return a
    elif b >= a and b >= c:
        return b
    else:
        return c
a= max_of_three(5,10,20)
print(a)
