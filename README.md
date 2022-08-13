# CS231n/CS131问答
- 这里收录了在完成CS231n和CS131作业过程中遇到的问题集
- 新问题可以在issue中加或者提交pr
- QQ群：780340688
***
## Q1
1. 描述
    ```python
    No such file or directory: 'cs231n/datasets/cifar-10-batches-py\\data_batch_1'
    ```
1. 原因
   - 下载的作业中没有cifar-10数据集
2. 方法
   - Windows
        - 从[链接](http://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)下载数据集
        - 解压得到 `cifar-10-batches-py`文件夹
        - 将整个文件放到作业中的`assignment1/cs231n/datasets/`路径下
   - Linux
        - 进入`assignment1/cs231n/datasets/`路径下，在终端中运行以下代码
            ```bash
            wget http://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz -O cifar-10-python.tar.gz
            tar -xzvf cifar-10-python.tar.gz
            rm cifar-10-python.tar.gz
            ```
***
