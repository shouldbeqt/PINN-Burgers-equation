# PINN-Burgers-equation
**PINN which compare sampling type for learning**
PINN has 5 layers with 25 neuron and hyperbolic tanh

First of all, trying to find best sampling method by compare: discrete, random, lhs:
![image](https://github.com/user-attachments/assets/8c2bd328-9dca-48a5-9f65-02b67fbdb533)

How we can see, if you have 10000 collacation points, it is doesnt matter which type you are choosing. 
If you have small sample: choose random or lhs
Lhs more effictive if you should calculate a  lot option (like Monte Carlo methods)
Random sampling could clastering your sample
Discrete type can do your model so linear

Second objective to compare PINN and FDM methods for PDE solution (FDM solution can find: https://github.com/shouldbeqt/Burgers-equation-FDM-solution):
![image](https://github.com/user-attachments/assets/ec8b7cdf-8db5-437d-9dbb-07619bac6fd4)

![image](https://github.com/user-attachments/assets/fa798520-b606-4850-b0ae-df1cfac02956)

MSE and MAPE error value can find in compare.txt
