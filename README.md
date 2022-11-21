README:

NOTE: numba does not work with Python 3.11, so all @jit decorators must be commented out in that case.

REQUIRED PACKAGES:
numpy (1.22.3)
scipy (1.9.3)
numba (0.56.4)
tqdm (4.64.0)

All our results can be obtained by running the notebook, as seeds were used.

ABSTRACT:
The area of the fractal known as the Mandelbrot set was determined by examining divergence of coordinate points within a given space. Various sampling methods were used to obtain these points, upon which the Mandelbrot formula was applied for a number of iterations. To highlight the effect of different sampling techniques, the random sampling, Latin hypercube sampling and orthogonal sampling methods were compared in the context of Monte Carlo methods. Statistical evaluation of area approximations were performed through these methods. A variance reduction technique in the form of control variates was implemented.
