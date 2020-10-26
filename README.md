# Abalone-SVM
Implementation of libsvm on the abalone dataset from UC Irvine.

This is my solution to part of a [homework](https://cs.nyu.edu/~mohri/ml20/hw2.pdf) for Professor Mohri's Fall 2020 Foundations of Machine Learning.

The libsvm software can be found [here](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) and the
abalone dataset can be found [here](http://archive.ics.uci.edu/ml/datasets/Abalone).

# Running the code.
Running `script3.sh`, `script4.sh`, `script5.sh`, and `script6.sh`
in order will execute my code when `libsvm-3.24` is manually included
by downloading it from [here](https://www.csie.ntu.edu.tw/~cjlin/libsvm/).

# .gitignore
Most of the output files appear in this repository 
except for `6.train`, `6.test`, `6scaled.train`, `6scaled.test`,
and `6.model` due to their size.
I do not include the `libsvm-3.24` folder also because of its size.
