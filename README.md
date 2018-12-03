# Docker samples

This is an sample repository for SEL@KIT.

## mining\_base

Base image for repository mining

- Base: [python](https://hub.docker.com/_/python/):3.7.0-alpine3.8
- Installed modules
    - [GitPython](https://github.com/gitpython-developers/GitPython)
    - [requests](https://github.com/requests/requests)
    - [matplotlib](https://github.com/matplotlib/matplotlib)
    - [tqdm](https://github.com/tqdm/tqdm)
    - [joblib](https://github.com/joblib/joblib)
- working dir: `/opt/proj`

## chainer\_base

Base image for deep learning with chainer.

- Base: [chainer/chainer](https://hub.docker.com/r/chainer/chainer/):v4.5.0-python3
- Installed modules
    - [chainer](https://github.com/chainer/chainer)
    - [cupy](https://github.com/cupy/cupy)
    - [numpy](https://github.com/numpy/numpy)
    - [pandas](https://github.com/pandas-dev/pandas)
    - [xlrd](https://github.com/python-excel/xlrd)
    - [matplotlib](https://github.com/matplotlib/matplotlib)
    - [tqdm](https://github.com/tqdm/tqdm)
    - [joblib](https://github.com/joblib/joblib)
    - [python-dotenv](https://github.com/theskumar/python-dotenv)
- working dir: `/opt/proj`

## copy\_in\_dockerfile

A sample for the strategy that copy local file into image.

- Base: [python](https://hub.docker.com/_/python/):3.7.0-alpine3.8
- working dir: `/project`

