# Vector3 – SIMD 3D-vector C++ implementation

This is a simple C++ library implementing a mathematical 3D-vector class using
[SIMD](http://www.wikiwand.com/en/SIMD) instructions. It based on [this
version](http://fastcpp.blogspot.fr/2011/12/simple-vector3-class-with-sse-support.html).

## Supported operations

The provided class name is Vector3. All values are in floating-point precision.

* Element-wise addition
* Element-wise subtraction
* Element-wise multiplication
* Element-wise division
* Scalar addition
* Scalar subtraction
* Scalar multiplication
* Scalar division
* Dot product
* Normalization
* Norm computing
* Equality testing

The exhaustive list is int [vector3.h](vector3.h).

## Compiler flags

You need to enable SSE2, SEE3 and SSE4 instructions on your compiler. GCC
/ Clang use `-msse4` to enable the needed instruction sets.


## Compatibility notes

* This version uses SSE4 instructions and is not meant to be backward
  compatible.
* It is supposed to work on Linux, OS X and Windows, although it has not been
  extensively tested on every operating system.


## License

The MIT License (MIT)

Copyright (c) 2015 Thomas Pelletier

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
