# qLiNGAM

## Overview
qLiNGAM is an algorithm that uses a quantum kernel for the independence measure of DirectLiNGAM, one of the causal discovery algorithms. By using qLiNGAM, it may be possible to estimate a reasonable causal structure even with a smaller amount of data.<br>
For more information, please refer to the following:<br>
https://arxiv.org/abs/2110.04485


## Description
Here, the source code for the qLiNGAM is provided in ipynb format.

### Data Preparation
UCI Heart Disease Data Set is available at the following URL (Data used is "processed.cleveland.data").<br>
https://archive.ics.uci.edu/ml/datasets/Heart+Disease <br>
Pima Indians Diabetes Database is available at the following URL. <br>
https://www.kaggle.com/uciml/pima-indians-diabetes-database

### Requirement
Python3 <br><br>
cirq　　　　　 0.7.0 <br>
cirqqulacs　 　 0.0.3 <br>
graphviz　　　 0.8.4 <br>
lingam　　　 　 1.3 <br>
matplotlib 　　3.1.3 <br>
numpy　　　 1.18.1 <br>
pandas　　 　 1.0.1 <br>
qiskit　　　　0.30.1 <br>
qiskit-aer　　　0.9.0 <br>
qiskit-aqua　　 0.9.5 <br>
qiskit-ibmq-provider　0.16.0 <br>
qiskit-ignis　　0.6.0 <br>
qiskit-terra　　0.18.3 <br>
Qulacs　　　　0.1.10.1 <br>
scikit-learn　　0.22.1 <br>

### Notes
Some of the source code for qLiNGAM was created by modifying the source code at the URL:<br>
https://github.com/cdt15/lingam <br><br>
The license for the above is as follows: <br>

Copyright (c) 2019 T.Ikeuchi, G.Haraoka, M.Ide, W.Kurebayashi, S.Shimizu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


