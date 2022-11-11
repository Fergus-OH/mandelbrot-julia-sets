# mandelbrot-julia-sets
<p align="center">
  <img src= "assets/Mandelbrot_4320pts_1000threshold.png" width="1000">
</p>

Consider the recurrence relation $z_{n+1} = z_n^2 + c$ where $c$ is a complex number.
The Mandelbrot set is a fractal, defined by the set of complex numbers $c$ for which this recurrence relation, with initial value $z_0 = 0$, does not diverge.
Another interesting type of set, which are related to the Mandelbrot set, are Julia sets and are defined for a specific complex number $c$.
To keep things brief, we will just establish the definition of a filled-in Julia set and do so in the following way:
The filled-in Julia set of a complex number $c$ is the set of initial values $z_0$ for which the previously mentioned recurrence relation does not diverge.
Not every filled-in Julia set is a fractal, but for almost all complex numbers $c$, they are.
This project contains an implementation to generate images and videos relating to the Mandelbrot set and Julia sets.

<p align="center">
  <img src="assets/zoom_(10004407000,-0,7436439059192348,-0,131825896951)_5000thresh_480pts_300frames_30fps.gif">
  <img src="assets/julia_spin2.gif" width="500">
</p>

## Getting Started
First clone this project by running the following command in a terminal:
```
git clone https://github.com/Fergus-OH/mandelbrot-julia-sets.git
```
The dependencies can be found in the [requirements.txt](./requirements.txt) file.
It is recommended to create a virtual environment using conda or venv and install the dependencies by running the following:
```
pip install -r requirements.txt
```

<!-- ```
Fractal().
```


A notebook with demos can be found [here](https://nbviewer.org/github/Fergus-OH/mandelbrot-julia-sets/blob/numba/demos.ipynb)

<a href="https://nbviewer.org/github/Fergus-OH/mandelbrot-julia-sets/blob/numba/demos.ipynb"><img src="https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg" alt="Render nbviewer" /></a> -->