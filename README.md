# TeaSeis

[![](https://img.shields.io/badge/docs-stable-blue.svg)](https://ChevronETC.github.io/TeaSeis.jl/stable)
[![](https://img.shields.io/badge/docs-dev-blue.svg)](https://ChevronETC.github.io/TeaSeis.jl/dev)
[![Build Status](https://travis-ci.org/ChevronETC/TeaSeis.jl.svg?branch=master)](https://travis-ci.org/ChevronETC/TeaSeis.jl)
[![Coverage Status](https://coveralls.io/repos/github/ChevronETC/TeaSeis.jl/badge.svg?branch=master)](https://coveralls.io/github/ChevronETC/TeaSeis.jl?branch=master)

TeaSeis.jl is a Julia library for reading and writing JavaSeis files (The name `TeaSeis.jl` was chosen instead of `JavaSeis.jl` due to potential trademark issues).  The JavaSeis file format is used in various software projects including [SeisSpace](https://www.landmark.solutions/seisspace-promax).  The original library is written in [Java](http://sourceforge.net/projects/javaseis).  There are also [C++](http://www.jseisio.com>C++) and [Python](https://github.com/asbjorn/pyjavaseis) implementations available.  Similar to the C++ library, TeaSeis.jl is a stripped down version of the original Java library.  In particular, the intent is to only supply methods for reading and writing from and to JavaSeis files.
