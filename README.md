1. 执行代码所需环境在requirements.txt中

2. 全部代码都存储在code.ipynb中，其中包括了LSTM+VGGNet_19和Bi-LSTM+ResNet_50两个多模态融合模型。

3. test_bilstm_resnet.txt存储了Bi-LSTM+ResNet_50模型的结果；test_lstm_vgg.txt存储了LSTM+VGGNet_19模型的结果。

   另外：由于每次结果划分具有随机性，导致每次测验的结果都不尽相同，两个结果文件存储的是，在验证集上表现最好的模型在测试集上的结果。

4. 代码运行的方式就是直接在Notebook里run即可。

5. 主要用到的库是keras。

6. github仓库地址：https://github.com/lisiqi00/AI-lab5
