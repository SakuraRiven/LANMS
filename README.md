## Locality-Aware Non-Maximum Suppression (LANMS)

This repo is from https://github.com/Parquery/lanms, which has provided a python package for the compiled version of the LANMS. However, the original code has a bug in ```normalize_poly``` that the ref vertices are not fixed when looping the p's ordering to calculate the minimum distance. 

In this repo, we fixed the bug so that anyone could compile the correct .whl for installation.

**Update 07-2021** (@doem97) Use averaged confidence for merged bounding boxes, while in original paper the confidence score is an accumulated score. (Later one causes problem that more bbox or longer text would have higher confidence)

## Installation

```
python setup.py bdist_wheel
```
