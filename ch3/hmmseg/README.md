# 隐马尔可夫中文分词器

如果使用本书附带的[docker镜像](https://hub.docker.com/r/chatopera/qna-book/)，所有依赖已经安装好，不需要再次安装。使用docker镜像运行程序的方式详见[文档](https://github.com/l11x0m7/book-of-qna-code/blob/master/README.md)。

进入ch3/hmmseg后，执行下列命令：

## UML

模块之间的关系

<img src="./packages.png" width="200">

核心类的接口和类之间的关系

<img src="./classes.png" width="400">

## 训练模型
```
python train.py
```

## 测试分词器
```
python test.py
```

## 分词器评测
使用黄金标准进行评测

```
./evaluate.sh
```