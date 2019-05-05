## 概要

`scikit-learnとTensorFlowによる実践機械学習`の第10章に登場する、
TensorFlowによるMNIST分類タスク実装
<https://github.com/ageron/handson-ml/blob/master/10_introduction_to_artificial_neural_networks.ipynb>

を、TensorFlowを使わずにPythonとNumpyで実装し替えたものです。

`handsonml_tf_mnist.ipynb` : 「実践機械学習」の元notebookの抜粋

`my_np_mnist.ipynb` : python + numpyによる自前の実装


## ネットワーク内容

* 3層全結合ネットワーク

* 入力層ノード数 :  (28 * 28)
* 中間層ノード数(1) : 300
* 中間層ノード数(2) : 100
* 出力層ノード数 : 10

* 活性化関数(中間層) : Relu
* 活性化関数(出力層) : Softmax

* 誤差関数 : Cross Entropy
