cmake-example
=============

This project is a C++ template project with cmake.
The project contains tests and cmake configures for the tests.

Build process
-------------
First, clone the project from
[GitHub](https://github.com/iBenza/cmake-example).

```
$ git clone https://github.com/iBenza/cmake-example
```

Then create build directory

```
$ mkdir cmake-example-build
```

and generate Makefile in the build directory, and build the project.

```
$ cd cmake-example-build
$ cmake ../cmake-example
$ make
```

You can run the tests with make.

```
$ make test
```

Travis CI
---------
You can get the cooperation with Travis CI from `.travis.yml`.
The results of the tests are on
[here](https://travis-ci.org/iBenza/cmake-example).

LICENCE
-------
MIT
