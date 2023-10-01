# Curriculum Vitae

[![compile-pdf](https://github.com/r9y9/cv/workflows/compile-pdf/badge.svg?event=push)](https://github.com/r9y9/cv/actions)

These are the Latex sources for my academic CV.

**Download** the latest compiled PDF:
[ryuichi_cv.pdf](https://github.com/r9y9/cv/raw/gh-pages/ryuichi_cv.pdf)

## Building

I use [Tectonic](https://tectonic-typesetting.github.io) to build the PDF from
the sources.
It's very convenient, can be installed from
[conda-forge](https://github.com/conda-forge/tectonic-feedstock),
and is faster than using a normal LaTeX compiler.
There are many ways to install it (see their website for instructions).

I highly recommend using the `Makefile`:

* `make`: builds the PDF
* `make show`: opens the PDF on the default viewer
* `make clean`: removes the built PDF and any other generated files

## Deploying

A PDF is compiled automatically by GitHub Actions with every commit to the
*main* branch and uploaded to the *gh-pages* branch.

## License

This repostiory used the template from https://github.com/leouieda/cv.

All LaTeX template source code is distributed under the
[BSD 3-clause License](https://opensource.org/licenses/BSD-3-Clause).
