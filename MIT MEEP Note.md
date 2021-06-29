# MIT MEEP 学习笔记

<center>
    Raphael 2021年6月29日
</center>

## MEEP介绍

 Meep是一个开源的FDTD（Finite Difference Time Domain，有限差分时域）仿真方法，用于Computational Electromagnetics 计算电磁场领域的研究。

> FDTD是一种广泛使用的技术，将空间划分为一个离散的网格，并使用离散的时间步长对场进行演化(evovle)——随着网格和时间步长越来越精细，仿真就变得越来越接近真正的连续方程，人们可以基本准确地模拟许多实际问题。

官方介绍[可以点击这里](https://meep.readthedocs.io/en/latest/Introduction/)。

### 边界条件和对称性 Boundary Conditions and Symmetries

