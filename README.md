[![Build Status](https://travis-ci.org/epfl-lasa/mathlib.svg?branch=master)](https://travis-ci.org/epfl-lasa/mathlib)

# mathlib

This the `mathlib` package of the robottoolkit. Since many recent packages of LASA only depends on `mathlib` from
RobotToolkit, this package is separated into this repository, so you can avoid including unnecessary packages.

Agnostic non-catkin dependent version of `mathlib`, for use in other environments. To install the library with CMake, do
```bash
git clone -b agnostic --single-branch https://github.com/epfl-lasa/mathlib.git \
  && mkdir -p mathlib/build \
  && cd mathlib/build \
  && cmake .. \
  && make -j \
  && make install
```
