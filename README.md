# Empirical IO 

Python implementations of workhorse structural models in empirical industrial
organization, including the classic Rust (1987) and BLP (1995) models. 



## What's here

| Notebook | Model | Method | 
|---|---|---|
| `Rust.ipynb` | Bus-engine replacement (1987) | Nested fixed point (NFXP) | 
| `Su_and_Judd.ipynb` | Same model, estimated via MPEC | Constrained optimization | 
| `BLP.ipynb` | Random coefficients demand (1995) | Generalized Method of Moments (GMM) |


## Setup

​```bash
pip install -r requirements.txt
​```

Note that `Rust.ipynb` generates the simulated panel (`rust.csv`) used by
`Su_and_Judd.ipynb` and so needs to be run first. 

## References
- Berry, S., Levinsohn, J., and Pakes, A. 1995. “Automobile Prices in Market Equilibrium.” *Econometrica* 63(4),  841–90.
- Dube, J.P., Fox, J. and Su, C.-L (2012). "Improving the Numerical Performance of Static and Dynamic Aggregate Discrete Choice Random Coefficients Demand Estimation." *Econometrica* 80(5): 2231-2267
- Rust, J. (1987). "Optimal Replacement of GMC Bus Engines: An Empirical Model of Harold Zurcher." *Econometrica* 55(5), 999–1033.
- Su, C.-L. & Judd, K. (2012). ""Constrained Optimization Approaches to Estimation of Structural Models." *Econometrica* 80(5), 2213–2230.