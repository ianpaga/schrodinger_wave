Two-dimensional Schrodinger wavepacket evolution in a squared potential well 
====

Description: Simulates the time evolution of a wave packet in a 2D potential well using the Crank-Nicolson method.

## Figures:

![schrodinger_wave](https://github.com/ianpaga/Ising_model_2D/assets/57350668/a1d6335c-3a41-4018-9413-69c2447fc592)

## Parameters:

- Lx : float
    size of the system in the x-direction
- Ly : float
    size of the system in the y-direction
- Nx : int
    number of spatial grid points in the x-direction
- Ny : int
    number of spatial grid points in the y-direction
- dx : float
    spatial step size in the x-direction
- dy : float
    spatial step size in the y-direction
- dt : float
    time step size.
- timesteps : int
    number of time steps
- x0 : float
    initial x-coordinate of the wave packet
- y0 : float
    initial y-coordinate of the wave packet
- kx0 : float
    initial wavevector in the x-direction
- ky0 : float
    initial wavevector in the y-direction
- sigma : float
    width parameter of the Gaussian wave packet
- hbar : float
    reduced Planck constant
- m : float
    particle mass

## Requirements:

- Python
- numpy, matplotlib
- Jupyter notebooks 
