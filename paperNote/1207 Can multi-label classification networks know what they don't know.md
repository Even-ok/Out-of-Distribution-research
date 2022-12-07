### *1207 Can multi-label classification networks know what they don't know?*

1. **文章中的主要思想：**

使用多个标签的联合能量，而不是MaxLogit，能够更好地将ID和OOD区分开来，而且也能给ID之间带来较大的差距

![image-20221207113228647](C:\Users\liangyiwen\AppData\Roaming\Typora\typora-user-images\image-20221207113228647.png)

2. 文章的主要贡献：

- 提出jointEnergy这一方法，提升了FPR95，能够用理论证明
- 做了ablation，包括：aggregation function, OOD scoring function, compatibility
- 在三大真实世界多标签数据集中做了验证



------

课题简介中可以写OOD对于真实世界的意义：对于这个开放世界的环境很重要，OOD会带来不确定性，特别是应用在一些自动驾驶等真实场景中。在医学领域、自动驾驶领域均有对于OOD的应用！医学中是用来检测多种abnormality! 

