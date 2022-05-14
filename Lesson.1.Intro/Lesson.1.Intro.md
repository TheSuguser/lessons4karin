# Lesson 1

## Intro

### Python和传统C语言的区别

* 解释型语言和编译型语言的区别
  * 编译型：需要整个工程进行编译 -> 翻译成机器语言 -> 运行
  * 解释型：每一行代码可以单独运行（基于这个特性，有了常用的IPython -> Jupyter notebook）
* 优缺点
  * 编译型：需要大量的编译时间，不够灵活；运行效率高
  * 解释型：运行效率低；开发效率高，相对灵活


### 为什么Python成为数据科学的常用语言

1. 写的快 -> 因为是解释型的语言
2. 语法简单好学
3. 生态成熟 
   1. Numpy, SciPy -> 数值运算（矩阵运算，向量运算）参考 MATLAB
   2. Pandas -> 数据处理（结构化数据）参考 Excel
   3. Matplotlib, Seaborn -> 数据可视化  参考Tabular, MATLAB, Excel
   4. Sklearn -> 机器学习
   5. Pytorch, Tensorflow -> 神经网络、高性能计算

3. 优秀的封装语言
   1. 在上层调用C++等语言写的代码，提供便于交互的API
      * 例如Pytorch, Tensorflow
4. 开源
   1. MATLAB也很好用，但是要钱



### 常用的开发工具

#### 环境管理工具
conda 

https://www.jianshu.com/p/d3266678851f

##### conda Ananconda pip
* conda是一个**环境**管理工具
* Anaconda是一个基于conda，同时预安装好的部分数据科学需要的package和应用的商业发行版软件
* pip是一个**包**管理工具

##### 为什么要用conda
1. 方便、简单
2. 更高效
3. 对于数据科学友好

##### conda的常用命令
1. 创建新环境
```shell
conda create -n 环境名 python==版本号
```

2. 切换到新环境
```shell
conda activate 环境名
```

3. 查看当前所有环境

```shell
conda env list
```

4. 返回初始环境

```shell
conda deactivate
```

5. 安装包

```shell
conda install 包名
```

#### IDE, 文本编辑器, Notebook

* IDE: 集成开发环境 -> Pycharm, Spyder, IDLE(自带)
* 文本编辑器：sublimetext, vscode, 记事本
* Notebook: Ipython -> Jupyter (Julia, Python, R)

#### 为什么推荐VSCODE

https://code.visualstudio.com/download

1. 轻量化
2. 定制性强
3. 和Jupyter Notebook整合度高
4. 跨平台能力强

### 一些需要避免的问题

不要依赖于jupyter notebook

1. 可以用于实验，但不能用于实际的项目
2. 熟悉jupyter notebook，但不能只会用jupyter notebook



**https://www.kaggle.com/competitions/bi-attrition-prediction/overview**

**https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales/overview**