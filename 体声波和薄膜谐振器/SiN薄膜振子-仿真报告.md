
# SiN 薄膜COMSOL仿真

## COMSOL设置步骤
- **新建** 
在新建窗口中，单击模型向导。
(1) 模型向导 : 在模型向导窗口中，单击三维。 
(2) 在选择物理场树中选择结构力学 > 膜 (mbrn)。
(3) 单击添加。 
(4) 单击$\rightarrow$研究。 
(5) 在选择研究树中选择一般研究 > 特征频率。 
(6) 单击 完成。

- **参数**
(1) 在模型开发器窗口的全局定义节点下，单击参数 。
(2) 在参数的设置窗口中，定位到参数栏。 
(3) 在表中输入表1参数。

- 定义
![输入图片说明](/imgs/2024-07-10/qRwmXuO1EKmG3Awv.png)
工作平面 1 (wp1)> 可以画出自己需要的几何形状。

![输入图片说明](/imgs/2024-07-10/lLTyhAZ8mqjfYu5O.png)

![输入图片说明](/imgs/2024-07-10/nghErenkAsgnki7O.png)
![输入图片说明](/imgs/2024-07-10/dIEhai1pNpgpzlBd.png)

参考资料 [[薄膜振动COMSOL仿真: https://cn.comsol.com/model/vibrating-membrane-12587]](https://cn.comsol.com/model/vibrating-membrane-12587)

## 参数设置
- SiN薄膜谐振器材料参数
表1 参数表
![输入图片说明](/imgs/2024-07-10/UTlxS2LYaBYPSBoj.png)

## 仿真结果
本征频率: 一阶（755.94kHz），二阶（1195.3kHz），三阶（1524.3kHz），四阶（1690.8kHz）。

- 一阶本征频率: 755.94kHz

**$xyz$**:

![输入图片说明](/imgs/2024-07-10/fgHHfMAoN292pbI6.png)

**$xy$**:

![输入图片说明](/imgs/2024-07-10/w35QJ9gVfR207Xhk.png)

**$yz$**:

![输入图片说明](/imgs/2024-07-10/7h7E8rM5rDD6Jtr9.png)

- 前四阶本征频率振动图:

![输入图片说明](/imgs/2024-07-10/hcuODBGH97tSUYkH.png)

### 测试
- 多普勒分析仪

![输入图片说明](/imgs/2024-07-11/5FWBFc6aZWWgWROT.png)

测出一阶频率


对于SiN-测试一阶本征频率




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc2NjEyODAyOV19
-->