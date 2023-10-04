# ckks-demo

A simple MATLAB implementation of (essential parts of) the Cheon-Kim-Kim-Song
(CKKS, a.k.a. HEAAN) RLWE-based homomorphic cryptosystem for educational
purposes.

**Important:** Please note that the implementation shared here is intended to
help understanding the functional principle and provide an exemplary
demonstration of the main concepts underlying the CKKS cryptosystem. It is not
necessarily secure or complete and should not be deployed in any practical
application.

## License

The source code in this repository is shared under the MIT license. See the
[LICENSE](./LICENSE) file.

## Acknowledgements

The contents of this repository were developed as part of projects with
financial support from the German Research Foundation (DFG) and the Daimler and
Benz Foundation under the grants SCHU 2940/4-1 and 32-08/19, respectively.

## How to use

### Installing

Download or clone this repository, e.g. using

```bash
git clone https://github.com/Control-and-Cyberphysical-Systems/ckks-demo.git
```

Then, make the toolbox available for the current session by executing

```matlab
addpath(genpath('path/to/ckks-demo'))
```

in MATLAB (replace `'path/to/ckks-demo'` with the actual path to the directory
which you saved the repository to earlier). To add the toolbox permanently to
your path, also run

```matlab
savepath
```

### Examples

For an extensive user-facing demo (including explanations), open and run
`Demo.mlx` (MATLAB Live Script, tested with MATLAB R2021b).
