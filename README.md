# travis_gcc_cpp98_coverity

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)|[![Codecov logo](Codecov.png)](https://www.codecov.io)
---|---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp98_coverity.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp98_coverity)|[![codecov.io](https://codecov.io/github/richelbilderbeek/travis_gcc_cpp98_coverity/coverage.svg?branch=master)](https://codecov.io/github/richelbilderbeek/travis_gcc_cpp98_coverity/branch/master)
coverity_scan|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp98_coverity.svg?branch=coverity_scan)](https://travis-ci.org/richelbilderbeek/travis_gcc_cpp98_coverity)|[![codecov.io](https://codecov.io/github/richelbilderbeek/travis_gcc_cpp98_coverity/coverage.svg?branch=coverity_scan)](https://codecov.io/github/richelbilderbeek/travis_gcc_cpp98_coverity/branch/coverity_scan)

<a href="https://scan.coverity.com/projects/richelbilderbeek-travis_gcc_cpp98_coverity">
  <img alt="Coverity Scan Build Status"
       src="https://scan.coverity.com/projects/12045/badge.svg"/>
</a>

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
