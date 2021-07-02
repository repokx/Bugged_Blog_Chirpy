---
layout: post
title:  核信息获取处理 Chapter 3
author: Hairtaxless, Repo Xu
date:   2021-07-02 19:35:00 +0800
categories: [Courses, 核信息获取与处理]
tag: [Course Review]
math: true
mermaid: true
pin: true
---

# 第3章

******
## 名词解释

1. 电离
   当入射带电粒子与介质原子较远时，使介质的原子产生电离或激发。
   
2. 击出
    当入射带电粒子与介质原子距离 ≈ 原子大小$（10^{-8} cm）$时，粒子与原子的电子相互碰撞，使电子从原子中发射出来

3. 库仑散射
    当入射带电粒子与介质原子距离 < 原子半径，粒子在核的库仑场中受到核的库仑散射，并伴随弱的电磁辐射。

4. 轫致辐射
    当入射粒子为电子时，将受到核的阻尼而发出光子

5. 切伦科夫辐射
    当入射带电粒子速度超过光在介质中的相速度时，粒子会辐射出可见光。

6. 穿越辐射
    当高速带电粒子穿过两种折射系数不同的界面时，辐射出X光。

7. 同步辐射
    当电子在磁场中偏转时，相当于受到加速而产生辐射。

8. 电离和激发

     + 电离：原子的轨道电离发生库伦相互作用而损失能量，轨道电子获得能量。当电子获得能量足以客服原子核的束缚，则电子就脱原子成为自由电子，这就是电离。

     + 激发：当电子获得能量较少，不足以克服原子核的束缚成为自由电子，将跃迁到较高的能级，这就是原子的激发。

9. 介质的辐射长度
    电子平均能量因为轫致辐射而减少为e分之一的物质厚度。初始能量为E的电子，在穿过物质厚度X后的平均能量： 

$$ <E> = E_0e^{-X/X_0} \tag{3.1} $$

$X_0$称为辐射长度
10. 临界能量
辐射损失与电离损失相等时的粒子能量称为该介质的临界能量。

$$ E_c = \frac{800(MeV)}{Z+1.2} \tag{3.2} $$

对于电子：
	$E > E_c$ 轫致辐射损失为主 
	$E < E_c$ 电离损失为主

******
## 填空题
1. 入射粒子能量损失的相对论上升时由于入射粒子将很大部分能量传递给少数几个电子，而这些电子又从介质中逸出，则在介质吸收层沉积的能量就接近一个常熟值，这个常数值称为费米坪。
2. 在粒子能量损失大的区域有很长的尾巴眼神，这是因为产生了一个或几个能量很高的δ电子，这种分布通常称为朗道分布。
3. 电子在磁场中偏转时，相当于受到加速而产生的辐射称之为同步辐射
4. 穿越辐射经典的发射角为1/γ
5. 根据光子能量不同，可以发生不同的相互作用，在几个 看 keV 到几百个 keV 能区，主要以康普顿效应为主。
6. 康普顿效应时光子在自由电子上的散射，因此又称为康普顿散射。

******
## 简答题
1. 有Bathe-Bloch公式得出粒子通过物质的平均电离能损的规律。Bathe-Bloch公式为：

$$ -\frac{\partial E}{\partial x} = 4πN_ar_e^2m_ec^2\frac{Z}{A}\frac{1}{β^2}\ln{\frac{2m_ec^2γ^2β^2}{I}-β^2-\frac{δ}{2}} \tag{3.3}  $$

其中, 
	$β = \frac{v}{c},$
	$γ=\frac{1}{\sqrt{1-β^2}}$

2. 简述混合物和化合物的电离能量损失（Bragg求和法则）
混合物和化合物可以看作时由各种元素在混合物或化合物中各自的比分的薄层组成，在此情况下：

$$ Bragg Sum Law：\frac{\partial E}{\partial x} = \sum w_j\overline{ (\frac{\partial E}{\partial x})_j} \tag{3.4} $$

$\overline{ (\frac{\partial E}{\partial x})_j}$：第j种元素的平均电离能量损失率，单位 $MeV·g·cm^{-2}$
$w_j$：第j种元素的权重因子，即原子数之比

******
## 论述题
1. γ射线与X射线的区别

******
## 计算题
1. 以 $^{55}Fe$ 发射的 5.9 keV 的 X 射线与 Ar 气体的作用过程描述 γ 射线的光电效应。（$Ar: E_k=3.2keV， E_L=0.287keV$）
常用来对正比室或多丝室作检测，其能量与最小电离粒子在几 cm 气体中的能损相近
对于Ar：
$E_k=3.20keV,E_L=0.287keV$
$E_1=5.90-E_k=2.70keV$
特征 X 射线$E^,_γ=E_k-E_L=2.91keV$
俄歇电子$E_2=E^,_r-E_L=2.63keV$
全能峰$E=E_1+E_2=5.33keV$
逃逸峰$E_1=2.70keV$
对于He：
仅有2个 K 层电子，只有全能峰，无逃逸峰