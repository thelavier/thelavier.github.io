---
title: "An immersed boundary vector potential-vorticity meshless solver of the incompressible Navier–Stokes equation"
collection: publications
permalink: /publications/2022-Immersed-Boundary
excerpt: ''
date: 2022-08-29
venue: 'Int J Numer Meth Fluids'
paperurl: ''
citation: 'Bourantas GC, Zwick BF, Lavier TP, et al. An immersed boundary vector potential-vorticity meshless solver of the incompressible Navier–Stokes equation. Int J Numer Meth Fluids. 2023; 95(1): 143–175. doi:10.1002/fld.5146'
---
We present a strong form meshless solver for numerical solution of the nonstationary, incompressible, viscous Navier–Stokes equations in two (2D) and three dimensions (3D). We solve the flow equations in their stream function-vorticity (in 2D) and vector potential-vorticity (in 3D) formulation, by extending to 3D flows the boundary condition-enforced immersed boundary method, originally introduced in the literature for 2D problems. We use a Cartesian grid, uniform or locally refined, to discretize the spatial domain. We apply an explicit time integration scheme to update the transient vorticity equations, and we solve the Poisson type equation for the stream function or vector potential field using the meshless point collocation method. Spatial derivatives of the unknown field functions are computed using the discretization-corrected particle strength exchange method. We verify the accuracy of the proposed numerical scheme through commonly used benchmark and example problems. Excellent agreement with the data from the literature was achieved. The proposed method was shown to be very efficient, having relatively large critical time steps.

[Download paper here](https://onlinelibrary.wiley.com/doi/full/10.1002/fld.5146)