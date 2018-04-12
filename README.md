# jMetalPy: Python version of the jMetal framework
[![Build Status](https://travis-ci.org/jMetal/jMetalPy.svg?branch=master)](https://travis-ci.org/jMetal/jMetalPy)
[![PyPI](https://img.shields.io/pypi/l/jMetalPy.svg)]()
[![PyPI](https://img.shields.io/pypi/v/jMetalPy.svg)]()

> jMetalPy is currently under heavy development!  

I started a new project called jMetalPy in February 2017. The initial idea was not to write the whole jMetal proyect in Python but to use it as a practical study to learn that programming language, although due to the interest of some researchers the goal of an usable jMetal version in Python is an ongoing work.

Any ideas about how the structure the project, coding style, useful tools (I'm using PyCharm), or links to related projects are welcome (see [CONTRIBUTING](https://github.com/jMetal/jMetalPy/blob/master/CONTRIBUTING.md)). The starting point is the jMetal architecture:

![jMetal architecture](resources/jMetal5UML.png)

---

# Table of Contents
- [Installation](#installation)
	- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

# Installation
To download jMetalPy just clone the Git repository hosted in GitHub:
```bash
$ git clone https://github.com/jMetal/jMetalPy.git
$ python setup.py install
```

Alternatively, you can install with `pip`:
```bash
$ pip install jmetalpy
```

## Dependencies
With Python 3.6 installed, run:
```bash
$ pip install -r requirements.txt
```

# Usage
Examples of configuring and running all the included algorithms are located in the [jmetalpy.runner](https://github.com/jMetal/jMetalPy/tree/master/jmetalpy/runner) folder.

# Contributing
Please read [CONTRIBUTING](CONTRIBUTING.md) for details on how to contribute to the project.

# License
This project is licensed under the terms of the MIT - see the [LICENSE](LICENSE) file for details.
