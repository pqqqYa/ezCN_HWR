# ezCN_HWR

Using a simple convolutional neural network to recognize the digits 0-9 in Arabic numerals.

使用pytorch实现简单的卷积神经网络实现对阿拉伯数字0-9的识别，保存模型为cnn_model.pth。

[详细介绍](https://pqqqya.github.io/2024/11/06/PytorchFundamental/)

~~~
ezCN_HWR
├─ main.ipynb           //主文件
├─ mian_CUDA.ipynb      //使用CUDA加速的主文件
├─ model_path           //模型保存路径
│  └─ cnn_model.pth     //模型文件
└─ datasets             //数据集，使用MINIST数据集，可以为空，代码会自行下载
~~~

使用MINIST对模型进行训练，整体的训练可能花费5分钟左右，使用CUDA加速后大约1分钟。
