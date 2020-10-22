# Linearly Converging Error Compensated SGD
Code for the paper "Linearly Converging Error Compensated SGD" by Eduard Gorbunov, Dmitry Kovalev, Dmitry Makarenko and Peter Richtárik.

To run the experiments one should download the data from LIBSVM https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html
and save the datasets in .txt format in the folder called "datasets". Also one should create folders "dump" and "plot".

Use jupyter notebooks that we prepared in order to repeat/check our experiments.

distrib_algs.py -- file with implementation of methods

utils.py -- file with useful tools for saving results and making plots

functions.py -- file with implementation of oracles and compression/quantization operators that we use
