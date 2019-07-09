# BiPolar 

* This is my attempt to learn how to:

1. Speed-up native Python code using JIT (e.g. `Numba`)
2. Interface between Python and C/C++ (hence "Bi"-Polar)
    - `Python/C API`, `Ctypes`, `Cython`, `PyBind11`, etc.
3. Write decent unit tests (following the [LSST/DM developer guide](https://developer.lsst.io/index.html)
4. Learn how to use `Sphinx` document and setup a document website.

* The goal is to have a simple function to convert a 2-D image from Cartesian coordinate into a polar coordinate. But I will try to achieve this in many different ways, using both Python or C/C++ as "core". I will profile them and do benchmark test on them.

* This is a side project, so can only make slow progress.

## Reference 

* [Interfacing with C from the Scipy lectures](https://scipy-lectures.org/advanced/interfacing_with_c/interfacing_with_c.html)
	- This is a very good guide for beginners. 
* [Tutorial on how to use Cython to optimize Python code by Adrian Price-Whelan](https://github.com/adrn/cython-tutorial)


### For individual method or tools

* [Document for `pybind11`](https://pybind11.readthedocs.io/en/master/basics.html)
