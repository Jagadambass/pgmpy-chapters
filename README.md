# pgmpy-chapters
pgmpy
=====
[![Build Status](https://api.travis-ci.com/pgmpy/pgmpy.svg?branch=dev)](https://travis-ci.com/pgmpy/pgmpy)
[![Appveyor](https://ci.appveyor.com/api/projects/status/github/pgmpy/pgmpy?branch=dev)](https://www.appveyor.com/)
[![codecov](https://codecov.io/gh/pgmpy/pgmpy/branch/dev/graph/badge.svg)](https://codecov.io/gh/pgmpy/pgmpy)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/78a8256c90654c6892627f6d8bbcea14)](https://www.codacy.com/gh/pgmpy/pgmpy?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=pgmpy/pgmpy&amp;utm_campaign=Badge_Grade)
[![Downloads](https://img.shields.io/pypi/dm/pgmpy.svg)](https://pypistats.org/packages/pgmpy)
[![Join the chat at https://gitter.im/pgmpy/pgmpy](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/pgmpy/pgmpy?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

pgmpy is a python library for working with Probabilistic Graphical Models.  

Documentation  and list of algorithms supported is at our official site http://pgmpy.org/  
Basic tutorial on Probabilistic Graphical models using pgmpy: https://github.com/Jagadambass/pgmpy-chapters/tree/main/notebooks

Our mailing list is at https://groups.google.com/forum/#!forum/pgmpy .

We have our community chat at [gitter](https://gitter.im/pgmpy/pgmpy).

Dependencies
=============
pgmpy has following non optional dependencies:
- python 3.6 or higher
- networkX
- scipy 
- numpy
- pytorch

Some of the functionality would also require:
- tqdm
- pandas
- pyparsing
- statsmodels
- joblib


If you face any problems during installation let us know, via issues, mail or at our gitter channel.

Development
============

Code
----
Our latest codebase is available on the `dev` branch of the repository.

Contributing
-----------
Before opening a pull request, please have a look at our [contributing guide](
https://github.com/Jagadambass/pgmpy-chapters/blob/main/Contributing.md

Contributing guide contains some points that will make our life's easier in reviewing and merging your PR.

If you face any problems in pull request, feel free to ask them on the mailing list or gitter.

If you want to implement any new features, please have a discussion about it on the issue tracker or the mailing
list before starting to work on it.

Testing
-------

After installation, you can launch the test form pgmpy
source directory (you will need to have the ``pytest`` package installed):
```bash
$ pytest -v
```
to see the coverage of existing code use following command
```
$ pytest --cov-report html --cov=pgmpy
```

Documentation and usage
=======================

The documentation is hosted at: http://pgmpy.org/

We use sphinx to build the documentation. To build the documentation on your local system use:
```
$ cd /path/to/pgmpy/docs
$ make html
```
The generated docs will be in _build/html

Examples
========
We have a few example jupyter notebooks here: https://github.com/Jagadambass/pgmpy-chapters/tree/main/notebooks
For more detailed jupyter notebooks and basic tutorials on Graphical Models check: https://github.com/Jagadambass/pgmpy-chapters

Citing
======
Please use the following bibtex for citing `pgmpy` in your research:
```
@inproceedings{ankan2015pgmpy,
  title={pgmpy: Probabilistic graphical models using python},
  author={Ankan, Ankur and Panda, Abinash},
  booktitle={Proceedings of the 14th Python in Science Conference (SCIPY 2015)},
  year={2015},
  organization={Citeseer}
}
```

License
=======
pgmpy is released under Apaches 2.0 License. You can read about our license at .

