##  Epitaxial bulk acoustic wave resonators as highly coherent multi-phonon sources for quantum acoustodynamics

### Abstract

固态量子声动力 (QAD) 系统通过将声学声子源与超导或自旋量子比特耦合，为量子信息存储和处理提供了一个紧凑的平台。 多模复合高泛音体声波谐振器 (HBAR) 是一种非常适合 QAD 的流行声子源。 然而，复合换能器中的缺陷、晶界和界面/表面粗糙度的散射严重限制了溅射沉积器件中的声子弛豫时间。 在这里，我们在 SiC 衬底上生长了外延 HBAR，它由金属 NbN 底部电极和压电 GaN薄膜组成。 声阻抗匹配的 Epi-HBAR 从换能器到声子腔的功率注入效率 $>99\%$。 光滑的界面和低缺陷密度减少了声子损耗，产生 ($f×Q$) 和声子寿命分别高达 $1.36 × 10^{17} Hz$和 $500 µs$。 GaN/NbN/SiC epi-HBAR 是一种电驱动的多模声子源，可直接与基于 NbN 的超导量子比特或基于 SiC 的自旋量子比特连接。

### 引言

晶格中声子的速度比电磁波慢约 $10^5$ 倍。 较慢的速度使量子态（因此量子信息）能够保存更长的时间； 只要声子腔具有高$Q$值。使用微型声换能器作为声子源和腔，可以实现芯片级制造和电气驱动/感测/控制系统，与关闭的声子换能器相比，显着减少占地面积、功耗和复杂性。

微加工声换能器，包括弯曲梁谐振器、表面声波 (SAW) 和体声波 (BAW) 空腔谐振器，可以轻松地用作 QAD 系统中的声子源。

- 外延与沉积的区别:
生长原理：外延生长通常温度较高，例如气象外延，其反应室是热壁的，得到的是单晶。而沉积的生长温度一般较低，得到的多是多晶。


### 理论与设计
- **外延 HBAR(Epi-HBAR)**
具有声阻抗匹配的外延 HBAR。 HBAR（传统溅射沉积或外延）由较厚的低损耗基板上的电极/压电/电极换能器组成（图1a）。
压电换能器谱效应-Piezoelectric Transducer Spectral Response:

$f_n=\frac{\omega_n}{2\pi}=(2n+1)(\frac{v_r}{2t_r})$

$n\in N$, $ω$、$v$和$t$表示径向频率、纵向速度和厚度，下标$r$表示压电材料。 当连接到具有有限厚度的基板（由下标$s$ 表示）时，压电换能器将声能发射到基板中，该基板充当声子法布里-珀罗腔。 腔体限制了所有$m$ 声子模式，波长$\lambda_m$:

$f_m=\frac{\omega_m}{2\pi}=(\frac{v_s}{\lambda_m})=m\times(\frac{v_s}{2t_s})$

HBAR 的频谱响应是由厚基板加载的压电换能器的传递函数，从而产生梳状声子频谱（图 1b）。 连续 HBAR 模式之间的自由光谱范围 (FSR) 是基板厚度的反函数。 底部电极 (BE) 和基板之间的界面对于从声子源（换能器）到声子腔（基板）的有效功率传输至关重要。

![输入图片说明](/imgs/2024-07-09/knR04BsSowiotnL6.png)
图 1 Epi-HBAR 作为量子声动力系统的通用且高效的多模声子源。
 a 描绘由薄外延压电换能器产生并限制在基板中的 epi-HBAR 的声子腔模式。 声子-量子比特耦合可以通过平面/垂直 NbN-based 超导量子比特或 SiC 衬底中的自旋量子比特实现。 b Epi-HBAR 的净光谱响应（红色）是电极/压电/电极换能器的换能包络（蓝色）和基板的腔模式（灰色）的叠加。 c 作为底部**电极刚度和质量密度**函数的**菲涅尔声功率反射** $Γ$ 的参数空间，归一化为 SiC 衬底的值。 Epi-HBAR 中的所有外延材料，尤其是关键的 NbN 底部电极，在声学上与基底匹配（即功率反射系数 $Г$ < 0.01），从而将有效的声功率注入 (1 − $Г$) 到声子腔中 。 将 (d) NbN 和 (e) Al 底部电极的计算 FSR 谱与具有 SiC 底部电极的普通解决方案（声阻抗完全匹配）进行比较，证明了阻抗匹配和不匹配条件之间的差异。 计算得出的 **Al/GaN/NbN/SiC** epi-HBAR 的 FSR 分布与图 2 中的实验数据非常一致。请注意，(d)、(e) 没有相同的 Y 轴缩放。

- **Epi-HBAR 的测量和模拟** 
制造的 Epi-HBAR 安装在氦流低温恒温器探针站 (Lakeshore Cryotronics) 中。 将低温恒温器抽至低于 $10^{−6}$ Torr 的压力，冷却至可达到的最低基础温度 (7.2 K)，并使其稳定。 具有**接地-信号-接地**配置的单个微波探头用于接触厚 CPW(共面波导) 输入**并将电输入施加到 Epi-HBAR**。 电气输入和读数由带有 50 Ω 端口终端的Keysight矢量网络分析仪 (VNA) 提供。 通过使用校准标准和短开路负载 (SOL) 校准序列可以消除微波探头和电缆的影响。 需要注意，所有光谱测量均按原样呈现，没有去嵌入或去除寄生元件。 通过优化电极的厚度/电阻率可以进一步降低电阻，并且可以通过在超导状态下运行来消除电阻。 为了获得足够的光谱分辨率，此处显示的宽光谱测量结果是使用 LabVIEW 对 VNA 进行自动控制所采集的多个连续扫描的组合。 每次扫描的跨度在 250 kHz 到 250 MHz 之间，每次扫描包含 32001 个数据点（受 VNA 限制），采集速度为 1 kHz。 在室温下获得的微波测量结果如**（文献的补充图 7）**所示。 此处提供的所有结果均针对 -15 dBm (31.62 µW) 的微波输入功率，在输入功率高达 0 dBm (1 mW) 的情况下，结果中未观察到显着变化或非线性。 我们模拟了未连接到任何基板的假设的 Al/GaN/NbN 换能器的光谱响应（**文献补充图 1**）。 这实际上是一种具有自由机械边界条件的薄膜体声谐振器。 这是为了验证在大约正确的频率下观察到适当薄膜厚度的换能器模式$f_{r,i}$ 的光谱响应。 使用 COMSOL Multiphysics 进行有限元分析。 没有 NbN 电极的对照样品（**来自补充图 3 和补充表 1**）用于与 Al/GaN/AlN/NbN/SiC epi-HBAR 进行比较。 此外，在控制样品上制造了具有不同波长的叉指型 SAW 腔器件。 该比较有两个目的：(a) 验证 Epi-HBAR 中 $f$< 2.5 GHz 范围内不需要的模式（可能是 SAW 模式）的存在和近似频率；(b) **证明在没有 NbN (BE) 的情况下，HBAR 模式根本不被激活**，从而产生干净的 SAW 响应。 **补充图4b**中的各种SAW模式对应于Rayleigh（$R_Λ$）和Sezawa（$S_Λ$）模式，其中SAW波长由$Λ \in [3,4,5] µm$。 分别对 Epi-HBAR（**补充图 4c**）和对照样本（**补充图 4d**）进行有限元模拟，验证 BE 的存在或不存在会对器件的声学行为产生显着变化。
[[文献补充文件-补充图]](https://static-content.springer.com/esm/art%3A10.1038%2Fs41467-020-15472-w/MediaObjects/41467_2020_15472_MOESM1_ESM.pdf)


### 实验结果

- **频谱测量**
![输入图片说明](/imgs/2024-07-09/9WWDrm5qjR8w6ZX4.png)
图 2 Epi-HBAR 在 7.2 K 下的微波测量。
a Epi-HBAR 从 1 到 17 GHz（包括 m = 52 到 m= 897）的微波反射光谱 ($S_{11}(ω)$)。 $S_{11}(ω)$谱展示了换能包络和腔模式的叠加。 换能包络线包含 Al/GaN/NbN 换能器的三个奇数模式。 在低频 (<2.5 GHz) 下，不需要的 SAW 或剪切模式的存在会稍微扭曲光谱响应。 b $S_{11}(ω)$ 的放大范围清楚地显示了周期性、尖锐的 Epi-HBAR 声子模式，其平均 FSR 为约 18.95 MHz。 c 机电阻抗 $|Z_{11}(ω)|$具有全局双曲线响应（来自静态电容），由 Epi-HBAR 声子模式的阻抗覆盖。$d|Z_{11}(ω)|$ 的放大部分 图示了对应于最小（最大）阻抗的串联（并联）谐振$f_s$ ($f_p$)。 相邻谐振之间的模式间隔$Δf_s$（或 $Δf_p$）是 Epi-HBAR 的自由光谱范围 (FSR)。 e 由于 epi-HBAR 的复合性质，FSR 在整个频谱上不是恒定的，但良好的声阻抗匹配可确保平滑的正弦依赖性和良好的功率传输，如图 1c-e 中所述。 f $S_{11}(ω)$  的快速傅里叶变换产生 Epi-HBAR 的时域响应，它由$t →0$ 处的电磁反射信号组成，后面是由模式延迟 $Δt=(Δf)^{-1}=52.77ns$ 分隔的声子脉冲序列 。

- **Q值和弛豫时间**

![输入图片说明](/imgs/2024-07-09/B1rxZMyf6ClayiqI.png)
图 3 Epi-HBAR 的高机械品质因数和声子寿命。
 a 在 7.2 K 下测得的 Epi-HBAR 品质因数（对于至少表现出半功率带宽的声子模式）大于 **1000 万($10^7$)**（频率大于 10 GHz），这是迄今为止 BAW 谐振器测得的一些最佳值。 b $f × Q$ 乘积表明 $(f × Q) ∝ f$，非简声声子散射的朗道-鲁默体系特征。 虚线表示线性拟合，串联和并联模式的拟合优度 (R2) 值分别为 0.93 和 0.88。 c 测量的 epi-HBAR 的声子弛豫时间 (τ) 高达 500 µs。 声子弛豫时间有效地设置了 QAD 系统中可以存储或操纵量子态的时间上限。 d 使用巴特沃斯-范戴克 (BVD) 等效电路对多模机械谐振器进行建模。 每个机械分支都被建模为代表单个声子模式的虚拟谐振电路； 电气分支对与 Epi-HBAR 和共面波导相关的所有电磁损耗和馈通进行建模。 面板 (e–g) 显示了三种 Epi-HBAR 模式（m= 164、m= 476 和 m= 529）（蓝色）的测量 $S_{11}(ω)$ 以及相应的 BVD 模型拟合（红色）。 对每种模式测量和建模的品质因数和弛豫时间（方法）验证了高 $f × Q$ 和 $τ$，证明 Al/GaN/NbN 中 7.2 K 微波声子的 $f × Q >1017 Hz$ 和 $τ > 500 μs$ /SiC Epi-HBAR。

![输入图片说明](/imgs/2024-07-09/03kX15NBPTyapGmW.png)
图 4 Epi-HBAR 的情况。 
本工作中选定的 Epi-HBAR 声子模式（星形）的 (a) $f× Q$ 乘积和 (b) 声子弛豫时间 (τ) 与泛音模式固体 BAW 谐振器（厚、毫米级单层）的公布值的比较 -晶体块器件）（正方形）和溅射沉积HBAR（低损耗基板上的薄膜多晶换能器）（五边形）。 每个数据点的测量温度用颜色表示。 只有使用光机械转换并在低温下测量的大型平凸石英体谐振器6,7 表现出比 Epi-HBAR 更高的声子弛豫时间，后者在微波频率下表现出 $τ > 500 μs$。 c 对 EpiHBAR 和溅射 HBAR（均以 SiC 作为衬底）进行比较，证实即使使用低损耗衬底，换能器异质结构的质量对于实现高声子寿命也至关重要。 d 仅对各种低损耗基板上的溅射沉积 HBAR 进行的研究并不能清楚地表明任何特定基板材料的优越性。
(**Epi-HBAR相比于溅射沉积HBAR,Q值和弛豫时间有较大提升(至少10倍性能提升),且排除不同衬底的原因**)

文章中预计散射损失将在某种程度上继续影响 Epi-HBAR，使 $T^{-4}$的进一步改善变得不切实际的乐观。 然而，如果 Epi-HBAR 在毫开尔文温度条件下运行，即使保守改进 $T^{-1}$ 倍，也会导致 $Q →10^{10}$、$f × Q→10^{21} Hz$ 和 $τ→10s$ 的微波声子。

### 总结




**文献:**  Gokhale, V.J., Downey, B.P., Katzer, D.S. _et al._ Epitaxial bulk acoustic wave resonators as highly coherent multi-phonon sources for quantum acoustodynamics.  ***Nat. Commun.*** 11, 2314 (2020). [[*Nat. Commun.* 11, 2314 (2020)]](https://doi.org/10.1038/s41467-020-15472-w)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NzQ1OTk2OCwxNTYyNTI0ODAwXX0=
-->