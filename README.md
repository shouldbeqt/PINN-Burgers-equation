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

![lhs_vs_macc_0_1](https://github.com/user-attachments/assets/d995b84b-cd21-4303-b7f8-2d883c20016f)


![random_vs_maccor_0_01](https://github.com/user-attachments/assets/0479249f-3f56-4b9b-b7bb-17508688fd4a)

MSE and MAPE error value can find in compare.txt
