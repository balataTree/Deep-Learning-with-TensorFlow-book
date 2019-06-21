# Deep-Learning-with-TensorFlow-book

合三人之力，让我们的名字永远铭刻在历史的封面上！

拒绝失败！拒绝拖拉！

# Project Progress
| DDL 	| 任务     	| 龙良曲 	| 陈浩 	| 李国豪 	|
|------	|----------	|--------	|------	|--------	|
| 6-23 	| 任务分配 	|  第二部分（除掉TF基础那一部分），无监督学习      	|   第一部分，TF基础  	|  有监督学习，RL      	|
| 7-28     	|   约完成20%       	|  回归问题，分类问题      	|  TF基础    	|    卷积神经网络    	|
|      	|   约完成40%         	|        	|      	|        	|
|      	|    约完成60%        	|        	|      	|        	|
|      	|   约完成80%         	|        	|      	|        	|
|  12-31    	|     100%     	|   合并成书并校验     	| 校验     	| 校验       	|

>目前作者按着团队加入顺序排序，成书后按着成员贡献顺序排序。

>第四部分可以稍后安排编写。

>文章中引用的观点、数据、素材请自己在每章后List出来，到时要不要附录到书中另行讨论。

# 备选书名

中文名：深度学习与TensorFlow 

英文名：Deep Learning with TensorFLow

# 编写工具
现在出版社只接受MS Word，所以大家还是用MS word 2013以后的版本编写吧，一章保存为一个docx文件。不定期push到各个子目录中，方便交流与备份。

# 目录

层级概念：部分->章->节->小点

## 第一部分：导论

* 人工智能简介
  * 人工智能的发展
  * 人工智能、机器学习、深度学习
  * 深度学习的应用
  
* 深度学习
  * 深度学习需要的基础知识
  * 怎么学习深度学习 
  * 深度学习框架比较
  * 本书学习线路

## 第二部分：深度学习基础

* 回归问题

由二元一次方程组引入，介绍怎么处理连续值预测问题，包含误差的构建、计算公式的构建、误差的优化等；并通过一个简单的回归实战让读者对连续值预测问题有一个初步的印象。

* 分类问题

介绍完连续值预测，进而介绍离散值预测。首先解决分类问题的误差构建，前向传播的构建；最后通过一个MNIST小实战介绍给读者深度学习的第一印象，为接下来介绍TensorFlow铺垫。

* TensorFlow基础
  * 数据类型
  * 张量创建
  * 索引与切片
  * 维度变换
  * Broadcasting
  * 数学运算
  * 前向传播实战
  * 合并与切割
  * 张量统计
  * 张量排序
  * 填充与复制
  * 数据限幅
  * 其他高阶操作
  * 测试实战-准确度

* 神经网络
  * 全连接层
  * 网络输出方式
  * 误差函数
  * 自动求导
  * 优化方法
  * MNIST全连接层实战

* 反向传播算法
  * 导数、梯度的概念
  * 基本函数的梯度计算
  * 激活函数的梯度
  * 损失函数的梯度
  * 感知机的梯度
  * 链式法则
  * 反向传播算法
  * MNIST反向传播实战-张量模式

* 过拟合
  * 过拟合与欠拟合
  * Train-val-test/交叉验证
  * Regularization
  * 学习率与动量
  * Dropout, Early Stopping等

## 第三部分：有监督学习

* 卷积神经网络

* 循环神经网络

* ResNet实战

* 情感分类问题实战

## 第三部分：无监督学习

* 自编码器

* 对抗生成网络

* VAE生成图片实战

* GAN生成图片实战

* WGAN-GP实战

## 第三部分：增强学习

* Value-based
  * DQN
* Policy-based
  * Reinforce
  * TRPO
  * PPO
* Actor-Critic
  * A3C

* DQN实战
* PPO实战



## 第四部分：大型案例实战



* 迁移学习+自定义数据集实战

* NLP某个案例实战

* 图卷积神经网络实战

* DARTS网络结构搜索实战

* 某个有趣的游戏RL实战

* Attention+Transformer

* 等等


# 参考资料

书中大部分代码都可以参考这里，不必自己从新写： https://github.com/dragen1860/TensorFlow-2.x-Tutorials
