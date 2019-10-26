## 导数与微分![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Derivative%26Differentiation.png)### 连续- 左极限=右极限=极限值，则连续### 导数- 凑导数定义，两种形式，增量式和单点式 - 左导数，右导数存在，一定连续- 左导数=右导数，可导- 可导必连续- 脱帽法，保号性，利用邻域内函数值的正负性，可以用在判断极值和凹凸性之上- 单调性，f'(x)<0，f(x)单调递减；f'(x)>0，f(x)单调递增- 极值点，f'(x0)=0且当x<x0与x>x0时的f'(x)值异号，即f'(x0)在某邻域内满足零点定理</br>或者 f''(x0)!=0，f''(x0)>0，极小值；f''(x0)<0，极大值</br>判断**极值**和**最值**要注意**边界**(开区间与闭区间)- 凹凸性，f''(x)<0，凸；f''(x)>0，凹</br>定义：在区间[a, b]上，[f(a)+f(b)]/2 > f((a+b)/2)，凹</br>[f(a)+f(b)]/2 < f((a+b)/2)，凸 - 拐点，f''(x0)=0且当x<x0与x>x0时的f''(x)值异号，即f''(x0)在某邻域内满足零点定理</br>若二阶导为0，三阶导数不为0时，为拐点- 切线，切线斜率- 渐近线</br>斜渐近线，a = lim y/x，x->∞，b = lim(y-ax)，x->∞，y = ax+b</br>水平就渐近线，lim y=某个实数的值，x->∞</br>垂直渐近线，lim y=∞，x->某个实数的值#### 数缺形时少直观,形少数时难入微；数形结合百般好,隔离分家万事休### 微分- 全微分### 数列- 单调有限准则</br>求数列极限，做差，做比值，证明存在极限，套用算几不等式(算术平均值大于等于几何平均值)## 极限![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Limit.png)- 注意乘积取极限不能拆开为极限取乘积- 取极限的时候 0/0和∞/∞型 的极限值为常数，**反推**分子或分母的值## 微分中值定理![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Mean-value-theorem.png)- 曲率(曲率圆半径的倒数)</br>K=1/R= |y''|/(1 + y^2)^3/2### 连续函数的性质(为了理解方便，放在一起)#### 有界性与最大值最小值定理- 在闭区间上连续的函数在该区间上有界且一定能取得它的最大值和最小值#### 介值定理(中间值定理)- 设函数f(x)在闭区间[a,b]上连续，且在区间的端点取不同的函数值，</br>对于A与B之间的任意一个数C，在开区间(a,b)内至少有一点ξ，使得 f(ξ)=C，(a<ξ<b)- 推论</br>函数f(x)在闭区间[a，b]上连续，f(x)一定介于最大值和最小值之间### 零点定理- f(x)在闭区间[a,b]连续，并且有f(a)·f(b)<0,则f(x)在区间(a,b)内有零点- 存在c∈(a,b),使得f(c)=0- c是方程f(x)=0的一个根#### 做题的时候注意条件，例如存在η∈(a,b)，使得f(η)=η### 罗尔定理- f(x)在**闭区间**[a,b]**连续**，在**开区间(a,b)**可导**，f(a)=f(b)=0- 则至少存在ξ∈(a,b)，使得 f'(ξ)=0#### 做题的时候注意构造函数 e^kxf(x)，e^(kx^2)f(x)，等等### 拉格朗日中值定理(拉氏，柯西中值定理的一个特例)- f(x)在**闭区间**[a,b]**连续**，在**开区间(a,b)**可导**- 则存在ξ∈(a,b)，使得 [f(b)-f(a)]/b-a=f'(ξ)#### 做题的时候注意区分区间### 柯西中值定理(拉式的推广)- f(x)，g(x)在闭区间[a,b]连续，开区间(a,b)可导，∀x∈(a,b)，g'(x)!=0- 则至少存在一点ξ∈(a,b)，使得 [f(b)-f(a)]/[g(b)-g(a)]=f'(ξ)/g'(ξ)### 泰勒中值定理### 麦克劳林展开始### 微积分基本公式- F(b) - F(a) = 对f(x)dx在a到b上的积分#### 积分中值定理(由拉格朗日中值定理推出)- f(x)在闭区间[a,b]上连续，在开区间(a,b)内至少存在一点ξ，使得</br>a到b上对f(x)dx的积分=f(ξ)(b - a)</br>证明：对闭区间[a,b]上的函数F(x)运用拉氏，F(b)-F(a)=F'(ξ)(b-a)</br>由微积分基本定理，a到b上对f(x)dx的积分=f(ξ)(b-a)## 不定积分![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Definite-integral.png)## 定积分![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Indefinite-integral.png)## 多重积分![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Multiple-integrals.png)### 二重积分- 体积- 质量- 质心- 转动惯量### 三重积分- 柱坐标(对z轴分量在xOy极坐标运算)</br>  dz rdrdθ，根据情况，先一后二(柱体法)或者先二后一(切面法)- 球坐标</br> r^2sinθdrdθdφ，适合于被积函数为球体的情况## 空间向量解析几何![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Spatial-vector-analytic-geometry.png)### 直线与平面- 直线的对称式方程，分母是方向向量，令三个比值为t，得到直线的参数方程- **直线与直线的夹角**，**两直线方向向量**的夹角，用数量积公式求得 cos θ- **直线与平面夹角**，**直线方向向量**与**平面法向量**夹角，用数量积公式求得 sin φ=cos θ，θ = π/2 - φ- 平面的点法式方程- **两平面夹角**，两个法向量的夹角，转化为两直线夹角- 平面束方程</br> A1x + B1y + C1z + D1 = 0；A2x + B2y + C2z = 0</br> 过两平面交线的平面的方程  A1x + B1y + C1z + D1 + λ(A2x + B2y + C2z + D2) = 0- 三向量共面的充要条件 混合积=0 即[abc]=axb·c### 曲面### 隐式方程的情形 F(x, y, z)=0#### 法向量- 曲面在点 M(x0, y0, z0) 的法向量- n = F'x(x0, y0, z0) + F'y(x0, y0, z0) + F'z(x0, y0, z0) #### 切平面- 切向量，x=x(t)，y=y(t)，z=z(t)</br>T = (x'(t), y'(t), z'(t))- 切平面</br>F'x(x0, y0, z0)(x - x0) + F'y(x0, y0, z0)(y - y0) + F'z(x0, y0, z0)(z - z0) #### 法线方程，法向量作为方向向量的直线对称式方程### 显式方程的情形 z=f(x, y)，令 F(x, y, z) = f(x, y) - z，点M(x0, y0, z0)#### 法向量- n = ±(f'x(x0, y0)， f'y(x0, y0)，-1)- 如果假定法向量方向向上，n = (-f'x(x0, y0)， -f'y(x0, y0)，1)- α，β，γ 分别是x轴，y轴，z轴分量与坐标轴的夹角，各方向余弦如下 - cos α = -fx/(1+fx^2+fy^2)^1/2- cos β = -fy/(1+fx^2+fy^2)^1/2- cos γ = -1/(1+fx^2+fy^2)^1/2#### 切平面方程f'x(x0, y0)(x - x0) + f'y(x0, y0)(y - y0) - (z - z0)=0#### 法线方程- (x - x0)/f'x(x0, y0) = (y-y0)/f'y(x0, y0) = (z - z0)/-1![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Normal-vector-of-surface.png)- 椭圆![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/%E5%B8%B8%E7%94%A8%E7%9A%84%E5%87%BD%E6%95%B0%E5%9B%BE%E5%83%8F/Ellipse(%E6%A4%AD%E5%9C%86).png)- 椭球面![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/%E5%B8%B8%E7%94%A8%E7%9A%84%E5%87%BD%E6%95%B0%E5%9B%BE%E5%83%8F/Ellipsoid(%E6%A4%AD%E7%90%83%E9%9D%A2).png)- 椭圆锥面![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/%E5%B8%B8%E7%94%A8%E7%9A%84%E5%87%BD%E6%95%B0%E5%9B%BE%E5%83%8F/conical-surface(%E6%A4%AD%E5%9C%86%E9%94%A5%E9%9D%A2).png)- 椭圆抛物面![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/%E5%B8%B8%E7%94%A8%E7%9A%84%E5%87%BD%E6%95%B0%E5%9B%BE%E5%83%8F/(Elliptical-%20Paraboloid)%E6%A4%AD%E5%9C%86%E6%8A%9B%E7%89%A9%E9%9D%A2.png)- 单叶双曲面![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/%E5%B8%B8%E7%94%A8%E7%9A%84%E5%87%BD%E6%95%B0%E5%9B%BE%E5%83%8F/Hyperboloid(%E5%8D%95%E5%8F%B6%E5%8F%8C%E6%9B%B2%E9%9D%A2).png)- 双叶双曲面![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/%E5%B8%B8%E7%94%A8%E7%9A%84%E5%87%BD%E6%95%B0%E5%9B%BE%E5%83%8F/hyperboloid-of-two-sheets(%E5%8F%8C%E5%8F%B6%E5%8F%8C%E6%9B%B2%E9%9D%A2).png)- 双曲抛物面![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/%E5%B8%B8%E7%94%A8%E7%9A%84%E5%87%BD%E6%95%B0%E5%9B%BE%E5%83%8F/Hyperbolic--paraboloid(%E5%8F%8C%E6%9B%B2%E6%8A%9B%E7%89%A9%E9%9D%A2).png)## 多元函数微分学![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Multivariate-function-differential.png)- 导数的定义- 判断极限是否存在，类似于y=kx的形式，算出极限值，观察是否与k有关- 可导不一定连续- 可微必连续，可微必定可导，反之不成立- 一阶偏导连续 => 可微- 保号性的运用，同一元函数微分学- 叠加原理:全微分=两个偏微分之和- 链式求导法则- 隐函数求导</br> 二元 F(x, y)，且F(x0, y0)=0，Fy(x0, y0)≠0，dy/dx = -Fx/Fy</br> 三元 F(x, y, z)，且F(x0, y0, z0)=0，Fz(x0, y0, z0)≠0，∂y/∂z=-Fx/Fz，∂z/∂y=-Fy/Fz- 偏积分(没有这个名词，但是可以这么做)- 二元函数某区域内求极值</br>A=fxx，B=fxy，C=fyy，AC-B^2>0，存在极值，A>0，极小值，A<0，极大值- 二元函数在边界上的最值</br>化为一元函数，求解，最后比较区域内的最值和边界上的最值取最大或最小值- 有条件极值，拉格朗日乘数法### 全微分- Δz = f(x + Δx, y + Δy) - f(x, y)，如果 Δz = AΔx + BΔy + o(ρ)，ρ=[(Δx)^2 + (Δy)^2]^1/2- 全微分：dz = AΔx + BΔy- 如果函数在区域D内各点处可微分，称在该区域内可微### 方向导数- 方向余弦：一个向量的三个方向余弦费别是这向量与三个坐标轴之间的角度的余弦- 方向导数：l方向化单位向量el，对函数的x，y，z三个分量求导，各分量的导数乘以各自对应的el的分量(方向余弦)- 方向余弦：el=(cos α, cos β, cos γ)，可以通过各方向余弦求出el### 梯度- 函数对 x，y，z 三个分量的偏导数 - 方向导数各个分量除以对应的方向余弦## 曲线积分与曲面积分![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Curve-integral&-surface-integral.png)### 第一类曲线积分(对弧长的曲线积分)- 几何意义，若被积函数 f>=0，关于弧长的曲线积分表示密度为f曲线形构件的质量![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/First-type-of-curve-integral.png)- 特别，被积函数f(x,y,z)≡1时，闭合曲线积分是曲线Γ的弧长![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Curve-length.png)- 直角坐标弧微分![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Cartesian-coordinate-system-arc-differential.png)- 带参数的弧微分![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Parameter-arc-differential.png)- 极坐标弧微分![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Polar-arc-differential.png)### 第二类曲线积分(对坐标的曲线积分)![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Second-type-of-curve-integral.png)### 两类曲线积分之间的关系- 由方向余弦将二者关联起来![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/The-relationship-between-two-types-of-curve-integrals.png)### 第一类曲面积分(对面积的曲面积分)![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/First-type-surface-integral.png)- 投影到xOy面上![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/First-type-surface-integral-xOy.png)- 投影到yOz面上![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/First-type-surface-integral-yOz.png)- 投影到xOz面上![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/First-type-surface-integral-xOz.png)### 第二类曲面积分(对坐标的曲面积分)- 通过方向余弦从面积微元推出坐标![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Second-type-surface-integral.png)- 符号锐正钝负(曲面法向量对相应坐标轴的夹角)- 投影到xOy面上![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Second-type-surface-integral-xOy.png)- 投影到yOz面上![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Second-type-surface-integral-yOz.png)- 投影到xOz面上![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Second-type-surface-integral-xOz.png)- 流量(面积 x 流速(向量场函数))![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Flow-rate.png)### 两类曲面积分之间的关系- 由方向余弦将二者关联起来![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/The-relationship-between-two-types-of-surface-integral.png)### 格林公式- 简单区域上(单连通)的格林公式![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Green-formula-on-a-single-connected-region.png)- 复连通区域上的格林公式![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Green-formula-on-a-complex-connected-region.png)- 复连通区域**小圈**扣出来是因为被积函数在该点**无意义**(例如分母为零)- 平面曲线积分与路径无关的条件，四种等价说法![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Four-equivalent-statements-of-Green-formula.png)- 格林公式计算投影平面的面积![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Green-formula-to-calculate-the-area-of-the-projection-area.png)### 斯托克斯公式- 斯托克斯公式![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Stokes-formula.png)- 旋度![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Curl.png)- 旋度的力学意义![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Rotational-mechanical-significance.png)- 环流量![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Ring-flow.png)- 空间曲线积分与路径无关的条件，四种等价说法![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Four-equivalent-statements-of-Stokes-formula.png)### 高斯公式 - 高斯公式![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Gaussian-formula.png)- 变形原理![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Principle-of-deformation.png)### 流量(通量)![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Flow.png)### 散度(通量对体积的变化率)![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Divergence.png)## 无穷级数![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Infinite-series.png)### 常数项级数- 级数收敛定义![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Definition-of-series-convergence.png)- 调和数列，各项倒数所成的数列（不改变次序）为等差数列- 调和级数，是各项倒数为等差数列的级数，从第2项起，它的每一项是前后相邻两项的调和平均(**倒数平均**)，故名调和级数- 交错级数，正负项交替出现- 交错调和级数，正负项交替出现的调和级数- P级数，∑ 1/n^p，当p<=1时，级数发散，其中当p=1时，级数为调和级数；当p>1时，级数收敛- 等比级数#### 收敛级数的基本性质- 级数 ∑u 和 级数 ∑v 分别收敛于s、σ, 级数 σ(u±v)也收敛，s±σ- 收敛级数中**去掉**、**加上**或**改变有限项**，不会改变级数的**收敛性**- 级数 ∑u 收敛，对该级数的项**任意加括号**后所成的级数 (u1+...+uk1) + (uk1 + ... + ukn) + (...) **仍收敛**，其和**不变**- 上面这条性质是，**充分非必要条件**，如果加括号后级数收敛，不能说明加括号前级数收敛- 级数收敛**必要非充分**条件，级数收敛的必要条件是通项an趋于0#### 外部审敛法- 比较审敛法![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Comparison-test.png)- 比较审敛法极限形式![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Comparison-test-limit-form.png)#### 内部审敛法- 极限审敛法![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Extreme-convergence-method.png)- 比值审敛法(达朗贝尔判别法)![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/D-Alembert-test.png)- 根值审敛法![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Root-test.png)#### 交错级数审敛法- 莱布尼兹审敛法![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Leibnitz-theorem.png)- 绝对收敛和条件收敛(概率中的离散型的期望必须要绝对收敛)![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Absolute-convergence&conditional-convergence.png)- 绝对收敛级数的性质 - 绝对收敛级数经改变项的位置后构成的级数也收敛，且与原级数有相同的和具有可交换性 - 无限和在性质很好的时候表现的像有限和一样可交换- 条件收敛级数，含有一个发散至正无穷的子列，也含有一个发散至负无穷的子列，换顺序后级数发散### 幂级数- 阿贝尔定理![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Abel-theorem.png)- 求收敛半径和收敛域![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Calculation-of-power-series-convergence-radius.png)- 两个幂级数同样的幂函数，它们的和、差、乘积在公共收敛区间(-R, R)都绝对收敛，且和、差、乘积的收敛半径R=min{R1, R2}- 幂级数在收敛域内逐项可积，逐项可导- 幂级数可以由另一级数逐项积分或逐项求导得到，收敛半径相等- 幂级数的和函数S(x)在其收敛区间上收敛### 函数展开成幂级数- 常用的级数![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/imgs/Commonly-used-series.png)### 傅里叶级数### 常用图像- 心形线![image](https://github.com/YC-L/Postgraduate-examination/blob/Advanced-Mathematics/%E5%B8%B8%E7%94%A8%E7%9A%84%E5%87%BD%E6%95%B0%E5%9B%BE%E5%83%8F/Cardioid.png) 