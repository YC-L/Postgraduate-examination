## 概率与数理统计### Random-events&probabilities(随机事件和概率)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Random-events&probabilities.png)- 注意，概率与事件不是单纯数学上集合的关系，概率指的是事件发生的概率### 随机事件和样本空间#### 随机试验- 对随机现象进行观察或实验称为随机试验，简称试验，记作E- 可以在相同条件下重复进行- 所得的可能结果不止一个，所有可能结果都能事前已知- 每次具体试验之前无法预知出现什么结果#### 样本空间- 随机试验的每一可能结果称为**样本点**，记作ω 由所有样本点全体组成的集合称为样本空间Ω- 样本点是组成样本空间的元素，记作 ω∈Ω#### 随机事件- 样本空间的子集称为随机事件，常用字母A，B，C表示- **随机事件**，由样本空间中的元素即样本点组成，是样本空间的**子集**#### 典型例题![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Random-events-instance.png)#### 基本事件- 由一个**样本点组成的子集**是最简单事件- 随机事件由基本事件组成- 如果一次试验的结果为某一基本事件出现，称该基本事件出现或发生- 如果组成事件A的一个基本事件出现或发生，也称事件A出现或发生#### 必然事件- 把Ω看成一事件，则每次试验必有Ω中某一基本事件(样本点)发生，也就是每次试验Ω必然发生#### 不可能事件- 不包含任何样本点的空集Ø看成一个事件，每次试验Ø必不发生，称Ø为不可能事件ai### 事件间的关系与运算- 事件的包含，如果事件A必然导致事件B发生，称事件B包含事件A，或称事件A包含于事件B，记为A⊆B或B⊇A- 从集合关系来看，A⊆B就是A中的每一个样本点都属于B### 事件的相等- 如果A⊇B与B⊇A同时成立，则称事件A与事件B相等，记作A=B- A=B表示事件A与事件B有完全相同的样本点### 事件的交- 如果事件A与事件B同时发生，则称为事件A与事件B的**交**或**积**，记为A∩B 或 AB- 集合A∩B是由同时属于A与B的公共样本点构成- 推广到无穷多个事件- A1A2A3...An...### 互斥事件- 如果事件A与事件B满足关系AB=Ø，即A与B同时发生是不可能事件，则称事件A和事件B互斥或互不相容- 互斥的两事件**没有公共样本点**- 事件的互斥可以推广到优先多个事件或可数无穷多个事件的情形- A1,A2,...,An,... 中任意两个事件均互斥，即 AiAj=Ø，i≠j，i,j=1,2,...,n,...- 称这可数无穷多个事件两两互斥或两两互不相容### 事件的并集- 如果事件A与事件B至少有一个发生，则称这样一个事件为事件A与事件B的并或和，记为A∪B- 集合A∪B是由属于A与B的所有样本点构成- 事件的并可推广到有限多个事件或可数无穷多个事件的情形- A1∪A2∪...∪An，### 对立事件- 如果事件A与事件B有且仅有一个发生，则称事件A与事件B为对立事件或互逆事件![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Opposite-event.png)- 如果A与B为对立事件，则A，B不能同时发生，且必有一个发生，即A，B满足A∪B=Ω且A∩B=Ø![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Opposite-event-1.png)### 事件的差- 事件A发生而事件B不发生的事件称为事件A与事件B的差，记为A-B![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Poor-event.png)- 韦恩图![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Venn-diagram.png)### 事件运算规律- 交换律，A∪B=B∪A,  A∩B=B∩A- 结合律，A∪(B∪C)=(A∪B)∪C，A∩(B∩C)=(A∩B)∩C- 分配律，A∩(B∪C)=(A∩B)∪(A∩C)，A∪(B∩C)=(A∪B)∩(A∪C)- 对偶律![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Dual-law.png)### 概率公理- 一个样本空间中，**两两互斥**的可数无穷个事件A1，A2，...，An，...有- P(A1∪A2...∪An∪...)=P(A1) + P(A2) + ... + P(An) + ... 称P(A)为事件A的概率### 概率性质- P(Ø)=0- 若A1,A2,...,An两两互斥，则有 P(A1∪A1∪...∪An)=P(A1) + P(A2) + ... + P(An)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Probabilistic-nature.png)- A⊆B，则P(A)≤P(B)- 0≤P(A)≤1### 条件概率- 设A，B为两个事件，且P(A)>0，称 P(B|A)=P(AB)/P(A)- 为在事件A发生的条件下事件B发生的条件概率#### 典型例题![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Conditional-Probability-instance.png)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Conditional-Probability-instance-1.png)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Conditional-Probability-instance-2.png)### 事件独立性- 设A，B两个事件满足等式 P(AB)=P(A)P(B)，则称A与B相互独立- 推广到多个事件- P(A1A2A3...Ak)=P(A1)P(A2)...P(Ak)，则称A1,A2,...,An为相互独立的事件- 事实上，n个事件相互独立需要 C(2 n) + C(3 n) + ... + C(n n) = 2^n - n - 1个等式成立#### 典型例题- 独立的定义![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Independent-definition.png)### 相互独立的性质![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Independent.png)- 将相互独立的n个事件任何几个事件换成它们相应的对立事件，则新组成的n个事件也相互独立- 当 0<P(A)<1时，A与B**独立等价于**P(B|A)=P(B)或P(B|A)=P(B|A拔)成立- 若A1，A2，...，An相互独立，则A1,A2,...,An必两两独立- 反过来，若A1,A2,...,An两两独立，则A1,A2,...,An不一定相互独立- 当A1,A2,...,An相互独立时，它们的部分事件也是相互独立的#### 典型例题![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Independence-example.png)#### 加法公式- P(A∪B)=P(A) + P(B) - P(AB)- P(A∪B∪C)=P(A) + P(B) + P(C) - P(AB) - P(CB) - P(AC) + P(ABC)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Addition-formula-instance.png)#### 减法公式- P(A-B)=P(A)-P(AB)#### 乘法公式- 当P(A)>0时，P(AB)=P(A)P(B|A)- 当P(A1A2...An-1)>0时，P(A1A2...An)=P(A1)P(A2|A1)...P(An|A1A2...An-1)#### 全概率公式- 设B1，B2，...，Bn为Ω的概率均不为零的一个完备事件组，则对任意事件A，有- P(A)=∑P(Bi)P(A|Bi)#### 贝叶斯公式- 设B1, B2, ..., Bn为Ω的概率军部为零的一个完备事件组，则对任意事件A，且P(A)>0，有- P(Bj|A)=P(Bj)P(A|Bj)/∑P(Bi)P(A|Bi)，j=1,2,...,n### 古典概型- 当试验结果为有限n个样本点，且每个样本点的发生具有相等的可能性，称这种有限等可能试验为古典概型- 此时如果时间A由nA各样本点组成，则事件A的概率为 P(A)=nA/n=A中包含的样本点数/Ω中样本点总数### 几何型概率- 当试验的样本空间时某区域(一维，二维，三维)，以L(Ω)表示样本空间Ω的几何度量(长度，面积，体积)- L(Ω)有限，且试验结果出现在Ω中任何区域的可能性只与该区域几何度量成正比，称这种拓展至几何度量上有限等可能试验为几何概型- 如果事件A的样本点表示的区域为ΩA，则事件A的概率为- P(A)=L(ΩA)/L(Ω)=ΩA的几何度量/Ω的几何度量### n重伯努利试验- 把一随机试验独立重复作若干次，即各次试验所联系的事件之间相互独立- 同一事件在各个试验中出现的概率相同，称为**独立重复试验**- 如果每次试验只有两个结果A和A拔，称这种试验是**伯努利试验**- 设在每次试验中，概率P(A)=p(0<p<1)，则在n重伯努利试验中事件A发生k次的概率- 又称二项概率公式C(k n)p^k(1-p)^n-k,k=1,1,2,...,n![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Common-probability-formula.png)## Random-variables&their-distribution(随机变量及其分布)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Random-variables&their-distribution.png)### 随机变量及其分布#### 随机变量- 在样本空间Ω上的实值函数X=X(ω)，ω∈Ω称为随机变量，简记为X，常用X，Y，Z表示随机变量- 随机变量定义域是Ω#### 分布函数- 对于任意实数x，记为函数F(x)=P{X≤x}，-∞<x<+∞，称F(x)为随机变量X的分布函数- 分布函数F(x)是定义在(-∞，+∞)上的一个实值函数- F(x)的值等于随机变量X在区间(-∞，x]上取值的概率，即事件"X≤x"的概率#### 分布函数性质- 0≤F(x)≤1，F(x)是单调不减函数，当x1<x2时，F(x1)≤F(x2)- limx->-∞ F(x)=0，记为F(-∞)=0；limx->+∞F(x)=1，记为F(+∞)=1- F(x)是右连续的，即F(x+0)=F(x)- 对任意x1<x2，有P{x1<X≤x2}=F(x2 - x1)- 对任意的x，P{X=x}=F(x)-F(x-0)- 由F(x)单调性和F(-∞)=0，F(+∞)=1，推出0≤F(x)≤1，推出性质如下- **F(x)单调非减**- **F(-∞)=0，F(+∞)=1**- **F(x)是右连续的**- 以上三条性质是F(x)称为某一随机变量的分布函数的**充分必要条件**- 当F(x)在x处连续，F(x)-F(x-0)=0，根据性质有 P{X=x}=0### 离散型随机变量- 如果一个随机变量的可能取值是有限多个或可数无穷多个，称它为离散型随机变量#### 离散型随机变量X的概率分布- 设离散型随机变量X的可能取值是x1,x2,...,xn,...，X 取各可能值得概率为 - P{X=xk}=pk,k=1,2,... 称上式为离散型随机变量X的概率分布或分布律![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/List-form-of-distribution-law.png)- 分布律的列表形式#### 分布律性质- pk≥0，k=1,2,...- ∑pk=1=1- 以上性质是分布律的**充分必要条件**#### 离散型随机变量X的分布函数- 设X的分布律为P{X=xk}=pk,k=1,2,...,则X的分布函数为- F(x)=P{X≤x}=∑pk ![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Distribution-function-of-discrete-random-variables.png)- 离散型随机变量分布函数另一种形式### 连续型随机变量- 如果对随机变量X的分布函数F(x)，存在一个非负可积函数f(x)，使得对任意实数x，都有![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Distribution-function-of-continuous-random-variables.png)- 称X为连续性随机变量，函数f(x)称为X的概率密度#### 典型例题![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Distribution-function-to-find-probability-density.png)- **不能说连续的F(x)对应的X一定是连续型随机变量**![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Distribution-function-instance.png)### 概率密度f(x)的性质- f(x)≥0![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Continuous-random-variable.png)- 以上两条是函数f(x)成为某一连续型随机变量的概率密度的**充分必要条件**![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Continuous-random-variable-1.png)- 在f(x)的连续点处有F'(x)=f(x)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Continuous-random-variable-2.png)### 常用分布#### 0-1分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/0-1.png)- 连续型的 0-1分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Continuous-two-point-distribution.png)#### 二项分布- 如果随机变量X有分布律 P{X=k}=C(k n)p^kq(n-k)，k=0,1,2...,n，其中 0<p<1，q=1-p- 则称X服从参数为n，p的二项分布，记作X\~B(n, p)- 在n重伯努利试验中，若每次试验成功率为p(0<p<1)，则在n次独立重复试验中成功的总次数X服从二项分布- 当n=1时，不难验证二项分布就退化成0-1分布，0-1分布记为B(1, p)#### 几何分布- 如果随机变量X的分布律为 P{X=k}=pq^k-1，k=1,2,...，其中0<p<1，q=1-p，称X服从参数为p的几何分布- 在独立重复做一系列伯努利试验中，若每次试验成功率为p(0<p<1)，则在**第k次试验时才首次试验成功**的概率服从几何分布#### 超几何分布- 如果随机变量X的分布律为 P{X=k}=C(k M)C(n-k N-M)/C(n N), k=l1,...l2- 其中l1=max(0, n-N+M), l2=min(M,n)，称随机变量X服从参数为n，N，M的超几何分布- 如果N件产品中含有M件次品，从中任意一次取出n件(或者一件一件不放回取出)- 令X=抽取的n件产品中的次品件数，则X服从参数为n，N，M的超几何分布- 如果N件产品中含有M件次品从中一件解一件有放回地取n次(放回抽样)，X服从B(n, M/N)#### 泊松分布- 如果随机变量X地分布律为 P{X=k}=λ^k/k!*e^-λ，k=0,1,2,...，其中λ>0为常数- 称随机变量X服从参数为λ地泊松分布，记作X\~P(λ)#### 均匀分布- 如果连续型随机变量X的概率密度为![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Evenly-distributed.png)- 则称X再区间[a,b]上服从均匀分布，记作X\~U[a,b] - 如果概率密度为 ![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Evenly-distributed-1.png)- 则称X再区间(a, b)上服从均匀分布，记作X\~U(a, b)- 无论 X\~U[a, b]或 X\~U(a,b)，它们的分布函数均为![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Evenly-distributed-2.png)#### 指数分布- 如果连续型随机变量X的概率密度为![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Index-distribution.png)- 称X服从参数为λ的指数分布，记作X\~E(λ)- 设X\~E(λ)，则X的分布函数为![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Index-distribution-1.png)- 指数分布有无记忆性#### 正态分布- 如果随机变量X的概率密度为![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Normal-distribution.png)- 称X为服从参数μ, σ的正态分布，记作X\~N(μ, σ^2)，当μ=0，σ^2=1时，即X\~N(0, 1)，称X服从标准正态分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Standard-normal-distribution.png)### 常用性质#### 均匀分布- 设X\~U[a, b]，则对a≤c<d≤b，有P{c≤X≤d}=d-c/b-a- 随机变量落入[a,b]中某区间[c,d]的概率等于该区间长度与[a,b]长度之比- 此结论对开区间或半开半闭区间也成立#### 指数分布- 设X\~E(λ)，则有![image](![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Index-distribution-2.png)- 上述性质称为指数分布具有"无记忆性"#### 正态分布![image](![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Normal-distribution-1.png)#### 典型例题![image](![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Normal-distribution-instance.png)#### 泊松定理- 在伯努利试验中，pn代表事件A在试验中出现的概率，它与试验总数n有关- 如果 limn->+∞ np=λ，可以用二项分布无限逼近泊松分布![image](![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Approximate-binomial-distribution.png) ### 随机变量函数的分布#### 离散型随机变量的函数分布- 设X的分布律为 P{X=xk}=pk, k=1,2,...- X的函数Y=g(X)的分布律为 P{Y=g(xk)}=pk, k=1,2,...- 如果在g(xk)中有相同的数值，将它们相应的概率和作为Y取该值的概率#### 连续型随机变量的函数分布##### 公式法- 设X是一个具有概率密度函数fX(x)的随机变量，又设y=g(x)是单调、导数不为零的可导函数，h(y)为它的反函数，则Y=g(X)的概率密度为![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Continuous-probability-density.png) - 其中(α,β)是函数g(X)在X可能取值的区间上的值域##### 定义法![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Continuous-probability-density-1.png) - 用公式法时，应要求条件较多：单调、可导、导数不为零、反函数存在，求解比较麻烦- 用定义法时**掌握好y变化的范围**即可，不同范围和不同积分限的求积## (Multidimensional random variables and their distribution)多维随机变量及其分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Multidimensional-random-variables&their-distribution.png)### 二维随机变量及其分布- 设X=X(ω)，Y=Y(ω)是定义在样本空间Ω上的两个随机变量，则称向量(X, Y)为二维随机变量或随机向量#### 二维随机变量(X, Y)的分布- F(x,y)=P{X≤x，Y≤y}，-∞<x<+∞，-∞<y<+∞#### F(x,y)的性质- 对任意x，y，均有0≤F(x, y)≤1- F(-∞, y)=F(x, -∞)=F(-∞, -∞)=0，F(+∞，+∞)=1- F(x, y)关于x和关于y均单调不减- F(x, y)关于x和关于y是**右连续**的- P{a<X≤b，c<Y≤d}=F(b,d)-F(b,c)-F(a,d)+F(a,c) - 注意多减了一个正方形，要补回来![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-random-variables&their-distribution.png)#### 二维随机变量的边缘分布- 设二维随机变量(X, Y)的分布函数为F(x, y)，分别称FX(x)=P{X≤x}和FY(y)=P{Y≤y}为(X, Y)关于X和关于Y的边缘分布函数- FX(x)=P{X≤x}=P{X≤x，Y<+∞}=F(x, +∞)- Y(y)=P{Y≤y}=P{X<+∞，Y≤y}=F(+∞，y)- F(x, +∞)，即limy->+∞F(x, y)#### 二维随机变量的条件分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-random-variable-conditional-distribution.png)- 称此极限在条件Y=y下X的条件分布函数，记作FX|Y(x|y)或P{X≤x|Y=y}#### 二维离散型随机变量- 如果随机变量(X, Y)可能取值为有限个或可数无穷个(xi, yj),i,j=1,2,...,则称(X,Y)为二维离散型随机变量#### 二维离散型随机变量的概率分布- 二维离散型随机变量(X, Y)可能取值为(xi, yj)(i, j=1,2,...)，则称P{X=xi, Y=yj}=pij,i,j=1,2,...为二维离散型随机变量(X,Y)的概率分布或分布律![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-random-distribution-law.png)#### P{X=xi, Y=yj}=pij的性质- pij≥0，i,j=1,2,...- ∑∑pij=1#### 二维离散型随机变量的边缘分布- pi.=P{X=xi}, i=1,2,...，p.j=P{Y=yj}, j=1,2,...- 分别称为(X,Y)关于X和关于Y的边缘分布- 边缘分布pi.和p.j与二维概率分布pij有如下关系![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Discrete-edge-distribution-law.png)#### 二维离散型随机变量的条件分布- 对给定的j，如果P{Y=yj}>0，则称![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Discrete-edge-distribution-law-1.png)- 为在Y=yj条件下随机变量X的条件分布#### 二维连续型随机变量及其概率密度- 如果对随机变量(X, Y)的分布F(x, y)，存在非负可积函数f(x, y)，使得对于任意实数x和y，都有![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-continuous-random-variable.png)- 则称(X,Y)为二维连续型随机变量，函数f(x,y)称为(X,Y)的概率密度![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Continuous-edge-probability-density.png)- 边缘概率密度![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-random-variable-properties.png)#### 二维连续型随机变量的边缘密度![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-random-edge-probability.png)#### 二维连续型随机变量的条件密度![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-random-conditional-probability.png)### 随机变量独立性- 如果对任意x，y都有 P{X＜x，Y≤y}=P{X≤x}P{Y≤y}，F(x,y)=FX(x)FY(y)，即随机变量X与Y相互独立#### 随机变量相互独立充要条件- 离散型随机变量X和Y相互独立的充要条件: 对任意i,j=1,2,...，有P{X=xi, Y=yj}=P{X=xi}P{Y=yi}, pij=pi.p.j- 连续型随机变量X和Y相互独立的充要条件: 对任意的x,y，有f(x,y)=fX(x)fY(y)，可将两个随机变量的独立性推广到两个以上随机变量的情形#### 二维均匀分布和二维正态分布- 二维均匀分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-uniform-distribution.png)- 二维正态分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-normal-distribution.png)- 重要性质![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-uniformity.png)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-dimensional-normal.png)### 两个随机变量函数X=g(X,Y)的分布- X,Y均为离散型随机变量- X,Y均为连续型随机变量- Fz(z)的求法，可用公式 ![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Z=g(XY).png)- 特别当Z=X+Y时![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Z=X+Y.png)#### 当X和Y相互独立时- 卷积公式 f(x,y)=fX(x)\*fY(y)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Convolution-formula.png)#### 典型例题![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Convolution-formula-instance.png)- 当Z=X*Y![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Xy-continuous.png)- 当Z=Y/X![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Yx-continuous.png)- 若X和Y相互独立![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Xy-independence.png)#### 当X1,X2,...Xn相互独立且具有相同分布函数F(x)时有- Fmax(z) = [F(z)]^n- Fmin(z) = 1 - [1-Fz(z)]^n### X为离散型随机变量、Y为连续型随机变量- 对离散型随机变量X的各种可能驱逐用全概率公式展开，将Xi作为条件概率![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Continuous&discrete.png)## Random variable digital feature(随机变量的数字特征)![image](![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Random-variable-digital-feature.png)### 随机变量的数学期望#### 离散型随机变量的数学期望![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Mathematical-expectations-of-discrete-random-variables.png)#### 连续型随机变量的数学期望![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Mathematical-expectation-of-continuous-random-variables.png)#### 数学期望的性质- 设C是常数，则有E(C)=C- 设X是随机变量，C是常数，则有 E(CX)=CE(X)- 设X和Y是任意两个随机变量，则有 E(X±Y)=E(X)±E(Y)- 设X与Y是任意两个随机变量，则 E(XY)=E(X)E(Y) 成立的充要条件是X与Y不相关#### 随机变量X的函数Y=g(X)的数学期望![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Z=g(XY)-mathematical-expectation.png)### 随机变量的方差#### 方差定义，D(X)=E{[X-E(x)]^2}存在#### 标准差，[D(X)]^1/2为随机变量X的标准差或均方差，记作σ(X)#### 方差计算公式- D(X)=E(X^2)-[E(X)]^2#### 方差性质- 设C为常数，则D(C)=0，反过来，从**D(X)=0不能的出X为常数**的结论- 设X是随机变量，a和b是常数，则有 D(aX+b)=a^2D(X)- 设X与Y是任意两个随机变量，则 D(X±Y)=D(X)+D(Y)，成立的充要条件是X和Y不相关### 常用随机变量的数学期望和方差- 0-1分布, E(X)=p, D(X)=p(1-p)- 二项分布，X\~B(n, p), E(X)=np, D(X)=np(1-p)- 泊松分布，X\~P(λ), E(X)=λ, D(X)=λ- 几何分布 P{X=k}=p(1-p)^k-1, k=1,2,.., 0<p<1 E(X)=1/p, D(X)=(1-p)/p^2- 均匀分布，X\~U(a, b), E(X)=(a+b)/2, D(X)=(b-a)^2/12- 指数分布，X\~E(λ), E(X)=1/λ, D(X)=1/λ^2- 正态分布，X\~N(μ, σ^2), E(X)=μ, D(X)=σ^2### 矩、协方差和相关系数#### 矩- 设X是随机变量，如果E(X^k), k=1,2... 存在，则称之为X的k阶原点矩- 设X是随机变量，如果 E{[X-E(X)]^k}, k=2,3... 存在，则称之为Xk阶中心矩- 设X和Y是两个随机变量， 如果 E(X^kY^l), k,l=1,2,...存在，称之为X和Y的k+l阶混合矩- 设X和Y是两个随机变量，如果 E{[X-E(X)]^k[Y-E(Y)]^k}, k,l=1,2,...存在，称为X和Y的k+l阶混合中心矩#### 协方差- 对于随机变量X和Y，如果E{[X-E(X)][Y-E(Y)]}存在，则称之为X和Y的协方差，记作Cov(X, Y)- 即Cov(X,Y)=E{[X-E(X)][Y-E(Y)]}#### 相关系数![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Correlation-coefficient.png)#### 不相关- 如果随机变量X和Y的相关系数 ρXY=0，则称X和Y不相关#### 协方差的公式和性质- Cov(X, Y)=E(XY)-E(X)E(Y)- D(X±Y)=D(X)+D(Y)±2Cov(X,Y)#### 协方差性质- 交换律，Cov(X, Y)=Cov(Y, X)- 提取常数，Cov(aX, bY)=abCov(X, Y)，其中a,b是常数- 分配律，Cov(X1 + X2, Y)=Cov(X1, Y) + Cov(X2, Y)#### 相关系数性质- |ρXY|≤1- |ρXY|=1的充分必要条件是存在常数a和b，其中a≠0，使得 P{Y=aX+b}=1#### 独立与不相关- 如果随机变量X和Y相互独立，则X和Y必不相关；反过来，X和Y不相关时，X和Y却不一定相互独立- 对**二维正态随机变量**(X, Y)，X和Y相互独立的**充分必要**条件是 ρ=0- 对二维正态随机变量(X, Y)，X和Y相互独立与X和Y不相关是等价的## 大数定律和中心极限定理### 切比雪夫不等式- 设随机变量X的数学期望E(X)和方差D(X)存在，则对任意的ε>0，总有 P{|X-E(X)|≥ε}≤D(X)/ε^2### 依概率收敛- 设X1，X2，...，Xn，...是一个随机变量序列，A是一个常数，如果对任意ε>0，有 limn->∞P{|Xn-A|<ε}=1- 则称随机变量序列X1,X2,...,Xn,...依概率收敛于常数A![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Convergence-by-probability.png)### 大数定律#### 切比雪夫大数定律(两两不相关的随机变量序列的样本均值依概率收敛于期望的均值)- 设X1,X2,...,Xn,...为两两不相关的随机变量序列，其期望E(Xi)与方差D(Xi)均存在，且存在常数C，使D(Xi)≤C(i=1,2,...)- 对任意ε>0 ![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Chebyshev-law-of-large-numbers.png)#### 伯努利大数定律(二项分布的随机变量Xn/n依概率收敛于p)- 设随机变量 Xn\~B(n, p)，n=1,2,...,则对于任意ε>0，有 ![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Bernoulli-law-of-large-numbers.png)#### 辛钦大数定律(独立同分布的样本均值依概率收敛于μ)- 设随机变量X1, X2, ..., Xn,... 独立同分布，具有数学期望E(Xi)=μ, i=1,2,..., 对任意 ε>0，有![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Xin-Qin-law-of-large-numbers.png)### 中心极限定理#### 隶莫弗-拉普拉斯中心极限定理- 设随机变量Xn~B(n, p)(n=1,2,...)，则对于任意实数x，有 ![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Laplace-central-limit-theorem.png)- 其中Φ(x)是标准正态分布函数- 当n充分大时，服从B(n, p)的随机变量Xn经标准化后的式子，近似服从标准正态分布N(0, 1)，或者说Xn近似服从N(np, np(1-p))#### 列维-林德伯格中心极限定理- 设随机变量X1, X2, ..., Xn, ... **独立同分布**，具有数学期望与方差，E(Xn)=μ，D(Xn)=σ^2，n=1,2,...，- 对于任意实数x，![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Lindberg-center-limit-theorem.png)- 定理表明当n充分大时，∑Xi的标准化近似服从标准正态分布(0,1)，或者说∑Xi近似服从N(nμ, nσ^2)## (Basic-concepts-of-mathematical-statistics)数理统计的基本概念![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Basic-concepts-of-mathematical-statistics.png)### 总体和样本- 所研究对象的某项数量指标X的全体称为总体，总体中的每个元素称为个体- 样本![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Sample.png)### 统计量和样本数字#### 统计量T- 样本X1,X2,...,Xn的不含未知参数的函数T=T(X1,X2,...,Xn)称为统计量- 如果x1, x2,..., xn是样本X1,X2,...,Xn的样本值- 则数值T(x1, x2, ..., xn)为统计量T(X1, X2, ..., Xn)的观测值#### 典型例题![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Statistics-instance.png)#### 样本X1,X2,...,Xn的数字特征- 样本均值![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Sample-mean.png)- 样本方差![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Sample-variance.png)- 标准方差![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Standard-variance.png)#### 样本数字特征的性质![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Sample-digital-feature.png)### 常用统计抽样分布和正态总体的抽样分布#### 卡方分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Chi-square-distribution.png)#### 卡方分布性质- 上α分位点![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Chi-square-distribution-quantile.png)- E=n，D=2n![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Chi-square-distribution-expectation&variance.png)- 可加性![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Chi-square-distribution-additivity.png)#### t分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/T-distribution.png)#### t分布性质- t分布的概率密度f(x)是偶函数，即f(x)=f(-x)- 当n充分大时，t(n)分布近似于N(0,1)分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Approximate-nature-of-t-distribution.png)- 上α分位点![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/T-distribution-quantile.png)- t分布双侧分位点![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/T-distribution-bilateral-quantile.png)#### F分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/F-distribution.png)#### F分布性质- F分布分位点![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/F-distribution-quintile.png)- F分布的倒数与自由度的关系![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/The-relationship-between-the-reciprocal-of-F-distribution&the-degree-of-freedom.png)### 一个正态总体的抽样分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Normal-population-distribution-sampling.png)### 两个正态总体的抽样分布![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Two-normal-population-distribution-sampling.png)### 常用的概念![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Summary.png)## 参数估计### 点估计![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Point-estimate.png)- 无偏估计量![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Unbiased-estimator.png)- 更有效估计量![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/More-effective-estimate.png)- 一致估计量![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Consistent-estimator.png)### 估计量的求法#### 矩估计法- 用样本矩估计相应的总体矩，用样本矩的函数估计总体矩相应的函数，然后求出要估计的参数#### 矩估计法步骤![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Moment-estimation-method.png)#### 最大似然估计法![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Maximum-likelihood-estimation.png)![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Maximum-likelihood-estimation-instance.png)#### 典型例题![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Maximum-likelihood-estimation-instance-1.png)### 区间估计#### 置信区间![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Confidence-interval.png)#### 一个正态总体参数的区间估计![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Interval-Estimation-of-Normal-Population-Parameters.png)#### 两个正态总体参数的区间估计![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Interval-Estimation-of-Two-Normal-Population-Parameters.png)## Hypothetical-test(假设检验)### 两类错误- 第一类错误，拒绝实际真的假设H0(弃真)- 第二类错误，接受实际不真的假设H0(纳伪)### 显著性检验#### 显著性水平 - 在假设检验中**允许犯第一类错误的概率**，记为α(0<α<1)- 则α称为检验的显著水平或检验水平，它表达了对**H0的弃真程度**#### 显著性检验- 只控制第一类错误概率α的统计检验，称为显著性检验- 显著性检验的一般步骤![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/General-steps-for-significance-testing.png)### 正态总体参数的假设检验- μ已知的情况![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/μ-is-known.png)- σ^2已知的情况![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/σ-is-known.png)- μ1-μ2已知的情况![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/μ1-μ2-is-known.png)- σ1^2=σ2^2![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/σ1^2=σ2^2-is-known.png)- Sω![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Sw.png)#### 典型例题![image](https://github.com/YC-L/Postgraduate-examination/blob/Probability-mathematical-statistics/imgs/Hypothetical-test-instance.png)  