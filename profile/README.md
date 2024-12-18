<p align="center">
  <img src="https://github.com/user-attachments/assets/234fa15c-e628-4ed9-8597-f104d5cc450c" width="200"><br>
</p>

# SpeedyWeather
We are an organisation!

## Projects

- [SpeedyWeather.jl](https://github.com/SpeedyWeather/SpeedyWeather.jl), a spectral atmospheric model with simple physics
- [RingGrids](https://speedyweather.github.io/SpeedyWeather.jl/dev/ringgrids/) a library for iso-latitude grids on the sphere (and extended into N-dimensional arrays) and their interpolation for SpeedyWeather.jl
- [LowerTriangularMatrices](https://speedyweather.github.io/SpeedyWeather.jl/dev/lowertriangularmatrices/) a library for lower triangular matrices (and extended into N-dimensional arrays) used for the spherical harmonics in SpeedyWeather.jl
- [SpeedyTransforms](https://speedyweather.github.io/SpeedyWeather.jl/dev/speedytransforms/) a library for the spherical harmonic transform between spectral space (using LowerTriangularMatrices) and grid-point space (using RingGrids) used by SpeedyWeather.jl

## Repositories for model setups

- [StochasticStir.jl](https://github.com/SpeedyWeather/StochasticStir.jl), for stochastic stirring of vorticity in mid-latitudes with a jetstream-dependent drag term.
- [ManyZonalJets.jl](https://github.com/SpeedyWeather/ManyZonalJets.jl) as initial conditions for SpeedyWeather's shallow-water model with each jet following [Galewsky, 2004](https://doi.org/10.3402/tellusa.v56i5.14436).

## Repositories for SpeedyWeather analysis

- [RainMaker.jl](https://github.com/SpeedyWeather/RainMaker.jl), a repository to analyse and document the rainfall in one location
- [WilliamsonTests.jl](https://github.com/SpeedyWeather/WilliamsonTests.jl), a repository for the Williamson et al. 1992 tests for solving the shallow water equations on the sphere
