# wm01-tiger

## Introduction

This is the course material for WM-01, Summer Semester 2022 (year of the Tiger),
Faculty of Biology, University of Freiburg. The instructors are Prof.
Dr. Andrew Straw, Dr. Wolfgang Maier, and Yonatan Cohen.

## Run interactively at https://strawlab-rp2.zoologie.uni-freiburg.de

We strongly recommend that you install Anaconda Python on your own computer -
this gives you the tools to run your own code after the class is over on your
own PC. We will help you install Anaconda python and the packages we use in the
course. While we are doing that, for the first few days (or for the entire
course), you may use our server. This will be taken offline shortly after the
course is done.

Login details to https://strawlab-rp2.zoologie.uni-freiburg.de will be discussed
in class.

## Installation with Anaconda

Download the Anaconda Individual Edition from
[here](https://www.anaconda.com/products/individual).

We will demonstrate how to setup an Anaconda environment in class. Use our
[`environment.yml`](https://raw.githubusercontent.com/strawlab/wm01-tiger/main/environment.yml)
file to setup your `wm01-tiger` environment in Anaconda. **Failure to use the
`environment.yml` file for the class may result in incompatibility with the
exercises in the course.**

## Links

## The Python Tutor - extremely highly recommended

http://pythontutor.com/

## Some useful Python data science cheat sheets

- https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf
- http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf

## Run on your computer with anaconda

```
conda env create -f environment.yml
conda activate wm01-tiger
# Alternatively, try "source activate wm01-tiger"
jupyter notebook
```

## Troubleshooting

### Note for macOS users

Before starting `jupyter notebook` from the command line, you may like to type:

    ulimit -n 4096

This will solve [OSError: [Errno 24] Too many open files](https://github.com/jupyterlab/jupyterlab/issues/6727).

## Code of conduct

Anyone who interacts with this software in any space, including but not limited
to this GitHub repository, must follow our [code of
conduct](code_of_conduct.md).
