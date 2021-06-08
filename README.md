# Introduction
Implementation of "Xor" function with MLP
# XOR gate
XOR gate (sometimes EOR, or EXOR and pronounced as Exclusive OR) is a digital logic gate that gives a true (1 or HIGH) output when the number of true inputs is odd. It behaves according to the truth table provided below.

<img src="Image/Table.png" width="200" class="center" />

# MultiLayer Perceptron 

A "single-layer" perceptron can't implement XOR. The reason is because the classes in XOR are not linearly separable. You cannot draw a straight line to separate the points (0,0),(1,1) from the points (0,1),(1,0).

<img src="Image/AB.png" width="400" class="center" />

The architecture of network is like the below picture.

<img src="Image/MLP.png" width="300" class="center" />

# Code 

You can run this code from your terminal/prompt/shell with typing
```python
Python MLP.py
```
