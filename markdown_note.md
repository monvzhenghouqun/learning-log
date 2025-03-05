# Part 1


## 1. Dimensions and Units
### 1.1 The International System of Units（国际单位制）
a.物理中的常用单位，如时间(s)、长度(m)、质量等(kg)
b.单位的前缀，如$peta-$ : $10^{15}$、$tera-$ : $10^{12}$、$pico-$ : $10^{-12}$、 $nan0-$ : $10^{-9}$

### 1.2 StandardsofLength,Time,andMass（长度、时间和质量的标准）
a.长度：1 c = 299792458 米/秒 $\Rightarrow$ 光年：光行驶一年的长度单位
b.时间：1 s = 一个铯原子进行 9,192,631,770 次振荡以发射特定波长辐射所需的时间
c. 质量：(1)1 kg = 保存在法国计量局的铂铱合金圆柱体的质量
(2)1 u = $(1.660 540 2±0.000 001 0) × 10^{−27} kg$

### 1.3 DimensionalAnalysis（维度分析）
a.一维：L  $\;$  二维：L$^{2}$  $\;$  三维: L$^{3}$
b.
$$
{L \over T} = {L \over T} + {L \over T^{2}} × T = {L \over T} + {L \over T} 
$$
因此表达式 $v = v_{0} + at$ 在维度上正确
c.感悟：通过表达式中元素的单位可以推出结果的单位
$\color{red}{通过结果的单位可以推出固定表达式中元素的幂}$


## 2 Vector（向量）
### 2.1 Vectors andScalars（向量和标量）
a.向量：大小、方向（速度，加速度，位移等）
b.标量：大小（路程等）

### 2.2 Properties of Vectors（向量的属性）
a.向量相等：大小、方向相等
b.向量相加：平行四边形相加法则，加法交换律，加法结合率
c.向量的负数：大小相等、方向相反

### 2.3 矢量分量和单位响亮
a.矢量分量：将一个二维向量分为和x、y轴两部分
$$
A^{2} = A^{2}_{x} + A^{2}_{y}  {\quad}和{\quad}  \color{red}θ = tan^{-1}({A_{y} \over A_{x}})
$$
b.单位向量：长度为1的向量
$$
\overrightarrow{A} = A_{x}\overrightarrow{i} + A_{y}\overrightarrow{j}
$$

### 2.4 MultiplyingVectors（乘法向量）
a.向量乘标量：相当于把向量取反，增大或缩小
b.标量积：
$$
\overrightarrow{A} \cdot \overrightarrow{B} = ABcosθ
$$
c.向量积：
$$
\overrightarrow{C} = \overrightarrow{A} \times \overrightarrow{B} = ABsinθ (向量A、B分别与C垂直)
$$
平行相乘为0，服从分配率

### 2.5 Section 2.2 Properties ofVectors（第2.2节向量的属性）
a.主要讲解了二维和三维向量的分解与合并



# Part 2


## 3 Motion in One Dimension（一维运动）

### 3.1 Position and Displacemen（位置和位移）
需要参照物（坐标轴等）
a.位置：标量
b.位移：向量

### 3.2 Average Velocity and Average Speed（平均速度和平均速率）
a.平均速度（矢量）：位移 / 时间
b.平均速率（标量）：路程 / 时间

### 3.3 Instantaneous Velocity and Speed（瞬时速度和速率）
a.瞬时速度（矢量）：位移变化 / 时间间隔
    位置-时间图的斜率，正负取决于斜率
b.速率：定义为其速度大小

### 3.4 Acceleration（加速度）
a.平均加速度（矢量）：速度变化 / 时间间隔
b.瞬时加速度（矢量）：当t接近0时 v / t 的极限值
$$
\color{red}a = {dv \over dt} = {d^{2}x \over dt^{2}} = v_{f} - v_{i} = \int_{t_{i}}^{t_{f}}adt
$$

### 3.5 Constant Acceleration（恒定加速度）
常见的一维运动：平均加速度 = 瞬时加速度
此时：
$$
v = v_{0} + at
\qquad
x - x_{0} = v_{0}t + {1 \over 2}(v_{0} + v)t = v_{0}t + {1 \over 2}at^{2}
\qquad
v^{2} = v_{0}^{2} + 2a(x - x_{0})
$$

### 3.6 Free Fall（自由落体）
地球表面附近的物体且空气阻力影响非常小时 $\Rightarrow$ 自由落体运动
此时g = 9.8 $m/s^{2}$


## 4 Motion in Two Dimension（二维运动）

### 4.1  Position,Displacement,Velocity,and AccelerationVectors（位置，位移，速度和加速度矢量）
a.置换向量：位移向量 = 最终位置向量 - 初始位置向量
b.平均速度：v的维度是长度除以时间，是一个向量，大小和方向沿位移矢量
c.瞬时速度：位移变化 / 时间间隔
d.平均加速度：速度变化 / 时间间隔
e.瞬时加速度：当t接近0时 v / t 的极限值
（将数值换成向量，且：
$$
\color{red}\overrightarrow{a} = a_{x}\overrightarrow{i} + a_{y}\overrightarrow{j}
$$

### 4.2  Projectile Motion（弹射物运动）
重力引起的加速度恒定、空气阻力不计：
1.水平和垂直运动独立
2.弹丸轨迹总是抛物线
a.抛体的水平运动
$$
x = v_{xo}t = (v_ocosθ_o)t
$$
b.弹射物的垂直运动
$$
y = v_{yo}t - {1 \over 2}gt^2 = (v_osinθ_o)t - {1 \over 2}gt^2\\ 
v_y^2 = v_{yo}^2 - 2gy = (v_osinθ_o)^2 - 2gy
$$
c.水平射程投射物
$$
T = {2v_osinθ_o \over g}\\
R = {v_o^2sin2θ_o \over g}, 0 \leq θ_o \leq π/2
$$
d.发射物的最大高度
$$
H = {v_o^2sin^2θ_o \over g}, 0 \leq θ_o \leq π/2
$$
e.轨迹方程式
$$
y = {-g \over 2v_o^2sin^2θ_o}x^2 + (tanθ_o)x, 0 \leq θ_o \leq π/2
$$

### 4.3 UniformCircular Motion（均匀圆周运动）
$$
a_r = {v^2 \over r} （向心加速度）\\
T = {2πr \over v} （周期）
$$

### 4.4 Tangential andRadialAcceleration（切向加速度和径向加速度）
粒子速度的方向和大小都发生变化时可解析为两个分量向量：$\color{red}切向分量向量$和$\color{red}径向分量向量$
$$
\overrightarrow{a} = \overrightarrow{a_t} + \overrightarrow{a_r}
$$

### 4.5  Non-uniformCircular Motion（非均匀圆周运动）
$$
\overrightarrow{a} = \overrightarrow{a_t} + \overrightarrow{a_r} = {dv \over dt}\overrightarrow{θ} - {v^2 \over r}\overrightarrow{r}
$$


## 5 Force and Motion（力和运动）

### 5.1 The Cause of Acceleration and Newton’s Laws（加速度的成因和牛顿定律）
