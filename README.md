### Deep Curve-dependent PDEs for affine rough volatility

This repository reproduces the results of [A. Jacquier and M. Oumgari (2023)](https://arxiv.org/pdf/1906.02551).  

We implement: 
- hybrid scheme à la [M. Bennedsen, A. Lunde, M. S. Pakkanen (2017)](https://arxiv.org/pdf/1507.03004) to generate trajectories of the rough Heston model,
- an Adams scheme to solve the fractional Riccati-Volterra equation and compute the characteric function in the rough Heston model, 
- a backward algorithm (BSDE-inspired) to price an european option in affine rough volatility models. 

### Examples of illustrations 

![iv](assets/joint_iv.png)

![all_prices](assets/all_prices.png)

### Disclaimer 
Source code is available upon request. Please contact me directly. 