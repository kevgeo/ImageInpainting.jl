# ImageInpainting.jl

[![Build Status](https://travis-ci.org/JuliaImages/ImageInpainting.jl.svg?branch=master)](https://travis-ci.org/JuliaImages/ImageInpainting.jl)
[![CodeCov](https://codecov.io/gh/JuliaImages/ImageInpainting.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/JuliaImages/ImageInpainting.jl)

Image inpainting algorithms in Julia.

For those situations where we need to remove undesired elements from the scene...

![trump](imgs/trump.png)
![lighthouse](imgs/lighthouse.png)

## Installation

Get the latest stable release with Julia's package manager:

```julia
Pkg.add("ImageInpainting")
```

## Usage

```julia
using ImageInpainting

# inpaint image within mask using algorithm
inpaint(img, mask, algo)
```

## Algorithms

| Algorithm type | References |
|----------------|------------|
| `Crimisini` | Crimisini, A., Pérez, P., Toyama, K., 2004. Region Filling and Object Removal by Examplar-based Image Inpainting. |

## Contributing

Contributions are very welcome, as are feature requests and suggestions.

Please [open an issue](https://github.com/JuliaImages/ImageInpainting.jl/issues) if you encounter
any problems.
