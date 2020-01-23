# Scalable Metropolis-Hastings for Exact Bayesian Inference with Large Datasets

Code to reproduce results of <https://arxiv.org/abs/1901.09881>.

To set up, do the following steps:

0) Update and upgrade

`sudo apt-get update && sudo apt-get upgrade`

1) Install `scons` via apt:

`sudo apt install scons`

2) Install the following package dependencies:

`sudo apt-get install pkg-config libeigen3-dev libgsl-dev libjsoncpp-dev libboost-all-dev libhdf5-serial-dev`


To run, use:

`scons && python3 run_plots.py`
