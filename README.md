# Empirical IO 

Python implementations of workhorse structural models in empirical industrial
organization, including the classic Rust (1987) and BLP (1995) models. 



## What's here

| Notebook | Model | Method | 
|---|---|---|---|
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
- Rust, J. (1987). *Econometrica* 55(5), 999–1033.
- Berry, Levinsohn & Pakes (1995). *Econometrica* 63(4), 841–890.
- Su, C.-L. & Judd, K. (2012). *Econometrica* 80(5), 2213–2230.