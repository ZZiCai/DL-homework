# 2. 函数拟合

## 问题描述：

​	理论和实验证明，一个两层的ReLU网络可以模拟任何函数[1~5]。请自行定义一个函数, 并使用基于ReLU的神经网络来拟合此函数。




## 要求: 

 	

- 请自行在函数上采样生成训练集和测试集，使用训练集来训练神经网络，使用测试集来验证拟合效果。
- 可以使用深度学习框架来编写模型，如tensorflow、pytorch、keras等。
  - 如果不使用上述框架，直接用NumPy实现可以最高加5分的附加分。
- 提交时请一并提交代码和报告。
  - 代码建议注释清楚（5分）
  - 报告至少应包含以下部分：（5分）
    - 函数定义、数据采集、模型描述、拟合效果。



## 参考文献： 

[1] G. Cybenko. 1989. Approximation by superpositions of a sigmoidal function.

[2] K. Hornik, M. Stinchcombe, and H. White. 1989. Multilayer feedforward networks are universal approximators.

[3] Moshe Leshno, et al. 1993. Multilayer feedforward networks with a nonpolynomial activation function can approximate any function

[4] Vinod Nair and Geoffrey E. Hinton. 2010. Rectified linear units improve restricted boltzmann machines.

[5] Xavier Glorot, Antoine Bordes, Yoshua Bengio. 2011. Deep Sparse Rectifier Neural Networks. PMLR 15:315-323.

