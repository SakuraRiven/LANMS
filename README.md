## Locality-Aware Non-Maximum Suppression (LANMS)

This repo is from https://github.com/Parquery/lanms, which has provided a python package for the compiled version of the LANMS. However, the original code has a bug in ```normalize_poly``` that the ref vertices are not fixed when looping the p's ordering to calculate the minimum distance. 

In this repo, we fixed this bug so that anyone could compile the correct .whl for installation.

## Installation

```
python setup.py bdist_wheel
```
