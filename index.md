---
jupytext:
  text_representation:
    format_name: myst
kernelspec:
  display_name: Python 3
  name: python3
---

# NumPy课程

numpy是Python中负责科学计算的第三方库，它提供了$n$维数组ndarray的各类操作。numpy的效率很高，这个评价包含了两层含义：首先，由于numpy基于C编写，在调用底层库的同时做了大量的性能优化，Python语言绝大多数情况下只负责接口的实现；其次，编写numpy代码需要具备向量化的思维模式，这种模式在本节介绍的广播机制中尤其重要，精确简明地使用numpy的各类函数能够使数据处理与分析更为高效便捷。下面，我们将从数组的构造、变形、切片、广播与常用函数这5个方面来介绍numpy的使用。

```{toctree}
:maxdepth: 2
:hidden:
:caption: Task-1 np数组的构造

1-1-从列表转换为数组
1-2-等差序列
1-3-特殊数组
1-4-随机数组
```

```{toctree}
:maxdepth: 2
:hidden:
:caption: Task-2 np数组的变形

2-1-变形的两种方式
2-2-元素重构
2-3-合并与拆分
```

```{toctree}
:maxdepth: 2
:hidden:
:caption: Task-3 np数组的切片

3-1-切片的概念
3-2-逐元素索引
3-3-布尔切片
3-4-切片的简记
3-5-np.newaxis对象
```

```{toctree}
:maxdepth: 2
:hidden:
:caption: Task-4 广播机制

4-1-案例引入
4-2-广播规则
4-3-案例引伸
```

```{toctree}
:maxdepth: 2
:hidden:
:caption: Task-5 常用函数

5-1-计算函数
5-2-逻辑函数
5-3-索引函数
```
