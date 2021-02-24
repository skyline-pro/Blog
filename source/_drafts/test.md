---
title: hello world
date: 2021-02-24 21:18:02
tags:
    - fdsafsdaf
password: Mike
---

## 正项级数

<!--more-->

**定义**

&emsp;&emsp;若$u_n\geq 0$,则称级数$\sum_{n=1}^\infty u_n$为正项级数

**收敛的充要条件**

&emsp;&emsp;正项级数的部分和$S_n$有上限，且存在常数$M$，使得对一切$n\in N$,都有$S_n\leq M$。

## 收敛的判别方法

### 比较判别法

**一般形式**

&emsp;&emsp;设$\sum_{n=1}^\infty u_n$,$\sum_{n=1}^\infty v_n$都是<font color=red>正项级数</font>,且$u_n \leq v_n(n\in N^+)$,

&emsp;&emsp; 1.若$\sum_{n=1}^\infty v_n$收敛，则$\sum_{n=1}^\infty u_n$收敛

&emsp;&emsp; 2.若$\sum_{n=1}^\infty u_n$发散，则$\sum_{n=1}^\infty v_n$发散

**极限形式**

&emsp;&emsp;设$\sum_{n=1}^\infty u_n$,$\sum_{n=1}^\infty v_n$都是<font color=red>正项级数</font>。并且有
$$\lim_{n\to \infty}\frac{u_n}{v_n} = l$$
   1.若$0<l<+\infty$,两个级数同时收敛或者同时发散

   2.当$l=0$时，若$\sum_{n=1}^\infty v_n$收敛，则$\sum_{n=1}^\infty u_n$收敛

   3.当$l = +\infty$时，若$\sum_{n=1}^\infty u_n$发散，则$\sum_{n=1}^\infty v_n$发散