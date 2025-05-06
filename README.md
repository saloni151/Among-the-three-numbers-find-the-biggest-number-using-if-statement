# Among-the-three-numbers-find-the-biggest-number-using-if-statement

#  Find the Biggest of Three Numbers Using `if` Statement in Python

# Description

This repository contains a simple Python program that accepts **three numbers from the user** and finds the **largest (biggest)** number using the `if` statement.


---

# User Input

- Aceept **three numeric values** (integers or floats) from the users.
- These values are compared using `if` statements to determine which one is the largest.

- # Input from the user
a = float(input("Enter first number: "))

b = float(input("Enter second number: "))

c = float(input("Enter third number: "))

---

# Program Logic

# First logic to find the biggest among the three numbers

```python
big=a
if(b>big):
   big=b
if(c>big):
    big=c
print("the biggest number among {},{},{} is {}".format(a,b,c,big))
```

**or**

# Second logic to find the biggest among the three numbers

```python

if(a>b and b>c):
    print("a {} is the biggest number".format(a))
if(a>b and b<c and a>c):
    print ("a {} is the biggest number".format(a))
if(a<b and a>c):
    print("b {} is the biggest number".format(b))
if(a<b and a<c and b>c):
    print("b {} is the biggest number".format(b))
if(c>a and a>b):
    print("c {} is the biggest number".format(c))
if(c>a and a<b and c>b):
    print("c {} is the biggest number".format(c))
```

**or**

# Third logic to find the biggest among the three numbers

```python

if((a>b and b>c)or(a>b and b<c and a>c)):
    print("a {} is the biggest number".format(a))
if((a<b and a>c)or(a<b and a<c and b>c)):
    print("b {} is the biggest number".format(b))
if((c>a and a>b)or(c>a and a<b and c>b)):
    print("c {} is the biggest number".format(c))
```

**or**


# Fourth logic to find the biggest among the three numbers

```python
if (a >= b and a >= c):
    print("The biggest number is:", a)
if (b >= a and b >= c):
    print("The biggest number is:", b)
else:
    print("The biggest number is:", c)
```

