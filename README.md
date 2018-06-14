# Following the 12 Steps to Navier-Stokes: Building a CFD Solver in Python.

![Alt text](/images/poisson.png "Poisson's Equation in 2D. As seen in Step 10.")

This repo contains my work done to build a simple CFD solver in Python following the interactive module [12 Steps to Navier Stokes](https://github.com/barbagroup/CFDPython) created by Professor [Lorena Barba](http://lorenabarba.com/). I wrote a brief article on my website that goes over the background for this project and showcases some of the skills I picked up on the process which you can take a look at [here](http://www.aortiz.me/portfolio/4_project/). The main goal of the project was to build a Navier-Stokes solver in Python that will serve as the foundation for all of my future endeavours into CFD. I learned much in the process and even set out to not only complete the course but give it my own spin. With that in mind I set off to animate all of the plots that we build in the course so that you can have a better understanding of the time history evolution of the simulations.

## Showcase of Simulations

Here's a few of my favorite animations::

![Alt text](/gifs/NSCavityLid2.gif "2D Cavity Flow")

![Alt text](/gifs/1dBurgers.gif "1D Burgers Equation")

![Alt text](/gifs/2dDiff.gif "2D Diffusion")

## Contents 

This repo includes Jupyter Notebooks of each lesson structured in the same way as Prof. Barba's module 12 Steps to Navier Stokes. You can find my own version of those lessons in the lessons folder or check them out directly below. My most significant addition to this project was the inclusion of animation code for each of the lessons. They link to a NBViewer version of the plot so you can look at the embedded animation and the LaTeX formatting as it was intended:

* [Step 1: 1D Linear Convection](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S01_1D_Linear_Convection.ipynb)
* [Step 2: 1D Non-Linear Convection](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S02_Non-linear_convection.ipynb)
* [Step 3: 1D Diffusion](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S03_1D_Diffusion_Equation.ipynb)
* [Step 4: 1D Burgers Equation](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S04_Burgers_EQ.ipynb)
* [Step 5: 2D Linear Convection](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S05_2D_Linear_Convection.ipynb)
* [Step 6: 2D Non-Linear Convection](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S06_2D_Nonlinear_Convection.ipynb)
* [Step 7: 2D Diffusion](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S07_2D_Diffusion.ipynb)
* [Step 8: 2D Burger's Equation](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S08_2D_Burgers_EQ.ipynb)
* [Step 9: 2D Laplace's Equation](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S09_2D_Laplace_Equations.ipynb)
* [Step 10: 2D Poisson Equation](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S10_2D_Poisson_Eq.ipynb)
* [Step 11: Cavity Flow with Navier-Stokes](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S11_Cavity_Flow_W_NS.ipynb)
* [Step 12: Channel Flow with Navier-Stokes](https://nbviewer.jupyter.org/github/Angelo1211/CFDPython/blob/master/Lessons/S12_Channel_Flow_W_NS.ipynb)

## References

* http://lorenabarba.com/blog/cfd-python-12-steps-to-navier-stokes/ml
* https://github.com/barbagroup/CFDPython
* https://eli.thegreenplace.net/2016/drawing-animated-gifs-with-matplotlib/
* https://www.grc.nasa.gov/www/k-12/airplane/nseqs.html







