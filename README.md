# Visualizing Data Assimilation process for Lorenz 63 equation

## Animation using plotly
Animation of the time series of the following values:
- true state $u$
- observation $y$
- estimate (mean) $\overline{v}$ of the EnKF
- estimate (ensemble) $v^{(k)}$ of EnKF

See the [demo](https://kotatakeda.github.io/lorenz_da_vis/index.html) page.

## requirements
Using https://github.com/KotaTakeda/da_py.
```
pip install git+https://github.com/KotaTakeda/da_py.git
pip install -r requirements.txt
```
