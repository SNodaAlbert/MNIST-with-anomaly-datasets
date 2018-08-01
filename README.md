# MNIST-with-anomaly-datasets
MNIST with anomaly datasets

動作環境：

* Python3
* Chainer3

![result](clusters.png)

[詳しい解説][1]

## データセット

train.zip - ラベル付けされたMNISTの手書き数字画像21,038枚

test.zip - ラベル付けされたMNISTの手書き数字画像20,962枚

anomaly.zip - ラベル付けされていない画像28,000枚で、内MNISTの手書き数字画像が27,990枚、例外画像10枚

## プログラム

autoencoder.py - オートエンコーダーで分散表現化

find_anomaly.py - Metric Learningによる例外画像の検出

[1]: https://cocon-corporation.com/cocontoco//find_anomaly_values/
