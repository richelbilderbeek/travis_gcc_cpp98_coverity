# travis_gcc_cpp98_coverity

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp98_coverity.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp98_coverity)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: manual
 * C++ compiler: `gcc`
 * C++ version: `C++98`
 * Libraries: `STL` only
 * Code coverage: none
 * Static code analysis: Coverity Scan
 * Source: one single file, `main.cpp`

More complex builds:
 * No Coverity Scan: [travis_qmake_gcc_cpp98](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98)
