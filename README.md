# Toth-2D
Beta update of ToTh-1D for surface fitting
1-D Generalization of Townsend breakdown

All files are added for a simulation.
* Run GaussianFit.mlx to:
  1. Create a 2-D Gaussian distribution.
  1. Sample the distribution. 
  1. Add noise to the sample.
  1. Fit a surface and determine the coefficient of the Gaussian distribution. 
* Run SurfaceFit.mlx to:
  1. Create a solution to the solution of Paschen curves in Townsend breakdown concentric spheres in atmospheres.
  1. Sample the solution.
  1. Add noise to the sample.
  1. Fit the solution to retrieve the constants, $A$, $B$, and $D$ for the reduced effective ionization and mobility, $\alpha/p = A\exp(-Bp/E)$ and $\mu\times p = C (E/p)^D$, respectively.
  1. Plot the original distribution, the noisy sample, and the fitted solution.
  1. Export the plot as a gltf file for 3-D plots.
 
Many thanks to Rohan Chabukswar for help with the gltf file:
* https://github.com/rohan-collins/MATLAB-GLTF.git
* https://mathworks.com/matlabcentral/fileexchange/123955
