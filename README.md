ImageQuilting.jl
================

*A Julia package for fast 3D image quilting simulation.*

[![][travis-img]][travis-url] [![][julia-pkg-img]][julia-pkg-url] [![][codecov-img]][codecov-url] [![][docs-stable-img]][docs-stable-url] [![][docs-latest-img]][docs-latest-url]

![3D Quilting Animation](docs/src/images/quilting.gif)

Installation
------------

Get the latest stable release with Julia's package manager:

```julia
Pkg.add("ImageQuilting")
```

Documentation
-------------

- [**STABLE**][docs-stable-url] &mdash; **most recently tagged version of the documentation.**
- [**LATEST**][docs-latest-url] &mdash; *in-development version of the documentation.*

Contributing
------------

Contributions are very welcome, as are feature requests and suggestions.

Please [open an issue](https://github.com/juliohm/ImageQuilting.jl/issues) if you encounter any problems.

Citation
--------

If you find ImageQuilting.jl useful in your work, please consider citing the following paper:

```latex
@ARTICLE{Hoffimann2017,
  title={Stochastic Simulation by Image Quilting of Process-based Geological Models},
  author={Hoffimann, J{\'u}lio and Scheidt, C{\'e}line and Barfod, Adrian and Caers, Jef},
  journal={Computers \& Geosciences},
  publisher={Elsevier BV},
  volume={106},
  pages={18-32},
  ISSN={0098-3004},
  DOI={10.1016/j.cageo.2017.05.012},
  url={http://dx.doi.org/10.1016/j.cageo.2017.05.012},
  year={2017},
  month={May}
}
```

Research papers and presentations
---------------------------------

- Talk at JuliaCon 2017

[![JuliaCon2017](https://img.youtube.com/vi/YJs7jl_Y9yM/0.jpg)](https://www.youtube.com/watch?v=YJs7jl_Y9yM)

- Hoffimann et al. 2017. *Stochastic Simulation by Image Quilting of Process-based Geological Models*
[:link:](https://www.researchgate.net/publication/317151543_Stochastic_Simulation_by_Image_Quilting_of_Process-based_Geological_Models)

- Hoffimann et al. 2015. *Geostatistical Modeling of Evolving Landscapes by Means of Image Quilting*
[:link:](https://www.researchgate.net/publication/295902985_Geostatistical_Modeling_of_Evolving_Landscapes_by_Means_of_Image_Quilting)

[travis-img]: https://travis-ci.org/juliohm/ImageQuilting.jl.svg?branch=master
[travis-url]: https://travis-ci.org/juliohm/ImageQuilting.jl

[julia-pkg-img]: http://pkg.julialang.org/badges/ImageQuilting_0.6.svg
[julia-pkg-url]: http://pkg.julialang.org/?pkg=ImageQuilting

[codecov-img]: https://codecov.io/gh/juliohm/ImageQuilting.jl/branch/master/graph/badge.svg
[codecov-url]: https://codecov.io/gh/juliohm/ImageQuilting.jl

[docs-stable-img]: https://img.shields.io/badge/docs-stable-blue.svg
[docs-stable-url]: https://juliohm.github.io/ImageQuilting.jl/stable

[docs-latest-img]: https://img.shields.io/badge/docs-latest-blue.svg
[docs-latest-url]: https://juliohm.github.io/ImageQuilting.jl/latest
