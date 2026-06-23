# 行列式

## 一、定义

1.  $ \det(A_{n \times n}) = \sum_{j_1 \cdots j_n} (-1)^t (j_1 \cdots j_n) a_{1 j_1} a_{2 j_2} \cdots a_{n j_n} $. 共 n 项

2.  $ =\sum_{j=1}^{n} a_{ij} A_{ij} $ 对应  $ =\sum_{i=1}^{n} a_{ij} A_{ij} $. 其中  $ A_{ij}=(-1)^{ij} $  $ M_{ij} $

3. 视为以这 n 个向量为邻边的 n 维图形的测度

det=0 可理解为高维测度低维的结果为0（比如：平面无体积；共线成低维）

如右图， $ S_{\square OABC}=|OA||OC|\sin(\beta-\alpha)=|OA|\cos\alpha|OC|\sin\beta-|OA|\sin\alpha|OC|\cos\beta=a_{11}a_{22}-a_{12}a_{21} $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//ee1a03cf-8a0d-499e-ba17-c1efc7842817/markdown_0/imgs/img_in_image_box_868_318_1094_482.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A48Z%2F-1%2F%2F55c558de02d9f71adc1a8ba003741ccdf175f7697e9bf2853c6b69fd4890ac83" alt="Image" width="18%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//ee1a03cf-8a0d-499e-ba17-c1efc7842817/markdown_0/imgs/img_in_image_box_868_318_1094_482.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A48Z%2F-1%2F%2F55c558de02d9f71adc1a8ba003741ccdf175f7697e9bf2853c6b69fd4890ac83" alt="Image" width="18%" />

 $ \overrightarrow{a_{1}}=[a_{11}a_{22}] $

 $ a_{22}=[a_{21}a_{22}] $

 $ a_{11}=[a_{11}a_{22}] $

 $ a_{21}=a_{22} $

</div>


</div>


二、性质  $ \rightarrow $ 行列地位等价  $ \rightarrow $ 低维 边的倍乘  $ \rightarrow $ 拆边 测度方向改变  $ \rightarrow $ 共线

 $ |A|=|A^{\top} $ ②零行 $ \Rightarrow $det=0 ③一行的k可外提 ④一行可拆成和式 ⑤互换变号 ⑥两行成比例 $ \Rightarrow $det=0 ⑦倍加不变

2. 常见行列式

①A的线性组合  $ k_{1}A_{i1}+\cdots+k_{n}A_{in}=\begin{vmatrix} k_{1}k_{2}\cdots k_{n} \\ * \end{vmatrix}^{k_{n}^{2}} $ (A照抄，M有土)

②  $ \nabla \Delta \backslash = \prod_{i=1}^{n} a_{ii} \quad \nabla \Delta \neq = (-1)^{\frac{n(n-1)}{2}} \frac{n}{i=1} a_{i} a_{n+1} (c=(n-1)+1=\frac{n(n-1)}{2}) $

③  $ \vert A C\vert = \vert A \vert \vert B $  $ \vert C A\vert = (-1)^{mn} \vert A \vert \vert B $ (A的m列都依次交换n次到左边对应位置)

④  $ \left|\begin{array}{c}1 \\ x_{1} x_{2} \cdots x_{n} \\ x_{1}^{m} x_{2}^{m} \cdots x_{n}^{m}\end{array}\right| = \prod_{i \neq j} (x_{j} - x_{i}) $ (j > i) (右-左; 下一上) 范德蒙德

⑤下  $ \begin{vmatrix} a b b b \\ b a b b \\ b b a \end{vmatrix} = \left[ a + (n-1)b \right](a-b)^{n-1} $

 $ \left| a + x_{1} a \cdots a \right| = \frac{n}{i-1} a_{i} \left( 1 + a \sum_{i=1}^{n} \frac{1}{x_{i}} \right) $

 $ \left| a_{1} + b a_{n} \cdots a_{n} \right| = b^{n-1} (b + \sum_{i=1}^{n} a_{i}) $

行和主一副

 $ \left|\begin{array}{ccc} b b \cdots b a \\ b a a \\ b \end{array}\right| = (-1)^{\frac{n(n-1)}{2}} \left|\begin{array}{ccc} a a & b \\ b & a \end{array}\right| $ （每次将最后一列换到左侧， $ (n-1)+\cdots+H=\frac{n(n-1)}{2} $）

 $ \left|\begin{array}{ccc} a_{1} & b_{2} \cdots b_{n} \\ c_{2} & a_{2} \cdots a_{n} \\ c_{n} & 0 \cdots a_{n} \end{array}\right| = \prod_{i=2}^{n} a_{i} \left(a_{1} - \sum_{i=2}^{n} \frac{b_{i} c_{i}}{a_{i}}\right) $

⑥ n所递归可试着第n行(列)展开，可能更容易找规律

3.罕见行列式

①X  $ \left|a_{2}b\right|_{a} $  $ =(a^{2}-b^{2})^{n} $  $ \left|\frac{a_{1}}{b_{2n}}\right|_{a_{2n}} $  $ \left|b_{1}\right|_{a_{2n}} $  $ =\frac{n}{i=1}(a_{i}a_{2nH-i}-b_{i}b_{2nH-i}) $

下标之和为 $ 2nH $，分组为 $ (1,2n),(2,2n-1),\ldots,(n,nH) $

②  $ \left|\begin{array}{cc} a & b \\ c & a \end{array}\right| = \frac{b(a-c)^{n}-c(a-b)^{n}}{b-c} $ (b≠c)

③  $ \begin{vmatrix} b a \\ c a \\ c b \end{vmatrix} = \begin{cases} (n+1) \cdot \left(\frac{b}{2}\right)^{n} & \Delta = 0 \\ \frac{(b+\sqrt{\Delta})^{2n}-(b-\sqrt{\Delta})^{2n}}{2^{n}\sqrt{\Delta}} & \Delta \neq 0 \end{cases} $，其中  $ \Delta = b^{2} - 4ac $

### 4. 一些应熟知的形式

 $ Ax=b $  $ X_{1}\overrightarrow{d_{1}}+\cdots+X_{n}\overrightarrow{d_{n}}=[\overrightarrow{d_{1}},\ldots,\overrightarrow{d_{n}}][\frac{x_{1}}{x_{n}}] $

 $ \alpha\beta^{T} $  $ [a_{n}] $  $ [b_{1}\cdots b_{n}] $ =  $ \left[\begin{array}{ccc}a_{1}b_{1}&\cdots&a_{1}b_{n}\\a_{n}b_{1}&\cdots&a_{n}b_{n}\end{array}\right] $ 每一列都是 $ \left[\begin{array}{c}a_{1}\\a_{n}\end{array}\right] $乘上系数 $ b_{i} $

 $ \alpha^{T}\alpha $  $ \alpha^{T}d=0\Leftrightarrow\sum_{i=1}^{n}a_{i}^{2}=0\Leftrightarrow\overrightarrow{a}=\overrightarrow{0} $

### 5克拉默法则  $ D=\left|A\right| $

D=0⇔Ax=0无穷多解⇔Ax=b无解或无穷多解 D≠0⇔Ax=0仅零解⇔Ax=b有唯一解 $ x_{i}=\frac{D_{i}}{D} $

# 行列式 - A

1.  $ \left|\frac{2}{7}-\frac{5}{7}-\frac{3}{4}-\frac{2}{7}\right| $

解用±1消为零  $ \det=\left|\begin{matrix}-7&16&0&10\\-7&7&-4&14\\-8&22&0&25\end{matrix}\right|=\left|\begin{matrix}-7&16&10\\1&5&15\\-8&22&25\end{matrix}\right| $ k先提  $ =5\left|\begin{matrix}-7&16&2\\-8&22&5\end{matrix}\right|=5\left|\begin{matrix}-7&5&23\\-8&6&29\end{matrix}\right|=-5\left|\begin{matrix}5&1&23\\6&2&11\end{matrix}\right|=-5\left|\begin{matrix}7&-1&11\\6&1&11\end{matrix}\right|=-265 $

2. 因式分解 (1) $ \left|\frac{1-\lambda-2}{2}\frac{4}{3\lambda-1}\right| $ (2) $ \left|\frac{\lambda-2}{5}\frac{1-2}{x+3}\right| $ (3) $ \left|\frac{\lambda-2}{2}\frac{2}{x+4}\frac{2}{x+3}\right| $ (4) $ \left|\frac{k}{4}\frac{x-2}{x+1}-\frac{2}{k}\right| $

解: (1)  $ D=\left|\begin{matrix}\frac{3-\lambda}{2}\frac{0-6\lambda}{3-\lambda}\\\frac{1}{2}\frac{1}{1-1-\lambda}\end{matrix}\right|=\left|\frac{3-\lambda}{2}\frac{0}{3-\lambda}\right|=\lambda(\lambda-2)(3-\lambda) $ (2)  $ D\xlongequal{[1+2]-\lambda}[3] $  $ \left|\frac{\lambda-1}{2}\frac{1}{x+3}-\frac{2}{3}\right|=\left(\lambda+1\right)\left|\frac{1}{0}\frac{1}{x+2}\right|=\left(\lambda+1\right)^{3} $

(3)  $ D=\left|\frac{\lambda-2}{2}\frac{2-2\lambda}{4-4}\frac{0}{x+1}\right|=\left|\frac{\lambda+4}{2}\frac{1-0}{4-4}\right|=\lambda-1(\lambda-36) $ (4) 能消未知参数  $ D=\left|\frac{\lambda-1}{2}\frac{2}{x+1}-\frac{2}{3}\right|=\left|\frac{\lambda-1}{2}\frac{2-2}{x+1}\right|=\left(\lambda-1\right)\left(\lambda+1\right)^{2} $

3.  $ \begin{vmatrix} 1+x_{1}^{2} & x_{1}x_{2} & \cdots & x_{n}x_{n} \\ x_{2}x_{4} & 1+x_{3}^{2} & \cdots & x_{n}x_{n} \\ x_{m}x_{n} & x_{m}x_{4} & \cdots & 1+x_{m}^{2} \end{vmatrix} $

解：找下方的公共元素加边  $ D = \begin{vmatrix} 1 & x_{1} & x_{2} & \cdots & x_{n} \\ 0 & 1+x_{1}^{2} & x_{1}x_{2} & \cdots & x_{n}x_{n} \\ 0 & x_{2}x_{4} & \cdots & 1+x_{m}^{2} \end{vmatrix} = \begin{vmatrix} 1 & x_{1} & x_{2} & \cdots & x_{n} \\ -x_{1} & 1 & 0 & \cdots & 0 \\ -x_{m} & 0 & \cdots & 1 \end{vmatrix} = \begin{vmatrix} 1 + \frac{m}{2}x_{1}^{2} & x_{1} & \cdots & x_{m} \\ 1 & \cdots & 1 \end{vmatrix} = 1 + \frac{n}{2}x_{1}^{2} $

4.  $ |A|=\begin{vmatrix}0.1&\frac{0}{2}&\cdots&\frac{0}{2}\\ \frac{0}{4}&\frac{0}{2}&\cdots&\frac{0}{2}\end{vmatrix} $，求所有元素代数余子式之和

解  $ \left|A\right|=-\frac{1}{4} $， $ A^{*}=-\frac{1}{4}\left[\begin{array}{c}0.0044\\0.200\end{array}\right] $，EA_{ij}=-\frac{5}{12} 求已A_{i}一般就是求 $ A^{*} $

## 5. 求展开式的负项个数

解：观察知展开式中仅有1，-1，设个数分别为  $ m_{1}, n_{1} $，则  $ \left\{\begin{array}{l} \det = m - n \\ 4! = m + n \end{array}\right. $， $ \left\{\begin{array}{l} m = 8 \\ n = 16 \end{array}\right. $ 展开式项的个数

6.3维列向量 $ d_{1}\sim d_{4} $.  $ A=(d_{1},d_{2},d_{2}+2d_{3}+d_{4}) $,  $ B=(d_{1},d_{2},d_{3}) $,  $ C=(d_{1}+d_{2}+d_{4},d_{1}-2d_{2}+4d_{4},d_{1}+3d_{2}+9d_{4}) $.  $ |B|=5,|C|=30 $, 求  $ \{A\} $ 解.  $ |A|=|d_{1},d_{2},2d_{3}+d_{4}|=2|B|+|d_{1},d_{2},d_{4}| $ 又  $ |C|=|d_{1},d_{2},d_{4}| $  $ |\frac{1-2}{4}|=1 $ 知  $ |d_{1},d_{2},d_{4}|=-1 $ 故  $ |A|=10-1=9 $

7. 求  $ \left[\begin{array}{cc} 1+a & 1 \\ 0 & -2 \end{array}\right. $ 的特征值

解:  $ A = B + aE = \left[\frac{15}{0.2}\right] + aE $,  $ \lambda_{B} = 0, 1, 6 $ 则  $ \lambda_{A} = a, 1 + a, 6 + a $

8 证明 Vandermonde 行列式  $ D_{n} = \sum_{i=1}^{n} x_{i} - x_{i} - x_{i} $ 边法

解  $ D_{2} = x_{2} - x_{1} $ 成立. 设  $ D_{n} = \sum_{i=1}^{n} x_{i} - x_{1} $,  $ (x_{i} - x_{j}) $ 则  $ D_{n} = \begin{vmatrix} 0 & x_{1} - x_{1} & \cdots & x_{n} - x_{1} \\ 0 & x_{2}^{n-1} - x_{2} - x_{1} & x_{2}^{n-2} - x_{1} \end{vmatrix} = (x_{2} - x_{1}) \cdots (x_{n} - x_{1}) \begin{vmatrix} x_{1} & \cdots & x_{n} \\ \vdots & \ddots & \vdots \\ x_{n}^{n-2} & \cdots & x_{n}^{n-2} \end{vmatrix} $

 $ = (x_{2} - x_{1}) \cdots (x_{n} - x_{1}) \cdot \sum_{i=1}^{n} x_{i} - x_{1} - x_{2} = \sum_{i=1}^{n} x_{i} - x_{1} - x_{2} $

从第n行，依次把上一行-x倍加至下一行

9.  $ A = \left[\begin{array}{ccc} 1 & 2 & 3 \\ 3 & 4 & 5 \\ 5 & 5 & 5 \end{array}\right] $，求  $ \frac{4}{5} = \frac{4}{5} A_{ij} $

解  $ A_{11} + A_{21} + A_{31} + A_{41} = |A| = 12 $,  $ A_{12} + A_{22} + A_{32} + A_{42} = \left| \begin{array}{ccc} 1 & 2 & 3 \\ 3 & 4 & 5 \\ 5 & 5 & 5 \end{array} \right| = 0 $,  $ \ldots $ 已知  $ A_{ij} = 12 + 0 + 0 + 0 = 12 $

解  $ A_{11}+A_{21}+A_{31}+A_{41}=|A|=12 $,  $ A_{12}+A_{22}+A_{32}+A_{42}=|1| \therefore \frac{y}{f_{2}} = 0 $, ... 已知  $ A_{ij} = 12 + 0 + 0 + 0 = 12 $

# 矩阵

## 一、基本运算

1. 反对称矩阵  $ A^{T} = -A $，有  $ a_{ii} = 0 $

逆矩阵  $ AB = E $

行阶梯形

数量阵 kE 对应行乘对应列为列否则为0 → Aij 在  $ a_{ji} $ 位置上

伴随矩阵  $ AA^{*} = A^{*}A = |A|E $，有  $ A^{*} = \begin{bmatrix} A_{11} & A_{12} & \cdots & A_{nn} \end{bmatrix} $

行最简阶梯形

初等矩阵

倍乘  $ E_{i}(k) $ (k≠0) 行 k 逆  $ E_{i}(\frac{1}{k}) $ 转 自身 n  $ E_{i}(k^{n}) $

互换 Eij 列式 -1 矩阵自身 置自身次幂  $ \{E_{ij}, n=2k-1\} $

倍加  $ E_{ij}(k) $ it=k+1  $ E_{ij}(-k) $  $ E_{ji}(k) $ Eij(nk)

### 2. 初等变换

①  $ A \cong B $  $ PAQ = B $，称A，B等价。A的等价标准形为 $ \left[\frac{E_{1}}{0} \quad \frac{0}{0}\right] $  $ A \subseteq B \Rightarrow \det(A) = \det(B) $

② A可逆⇔ A可表示为有限个初等矩阵的乘积. ⇔ A≌E

③求逆： $ [A:E]\xrightarrow{仅行}[E:A^{-}] $， $ [A]\xrightarrow{仅列}[E] $ 求秩：混用 求方程组的解仅行 求det:混用

### 3. 常用结论

①  $ (A^{\top})^{\top}=A $  $ (A^{\top})^{\top}=A $  $ (A^{*})^{*}=|A|^{n-2}A $  $ (A^{\top})^{\top}=(A^{\top})^{\top} $  $ (A^{\top})^{*}=(A^{*})^{\top} $  $ (A^{\top})^{*}=(A^{*})^{\top} $

②  $ (kA)^{\mathrm{T}}=kA^{\mathrm{T}} $  $ (kA)^{-1}=\frac{A^{-1}}{k} $  $ (kA)^{*}=k^{n+1}A^{*} $

③  $ (AB)^{\top}=B^{\top}A^{\top} $  $ (AB)^{\top}=B^{\top}A^{\top} $  $ (AB)^{\star}=B^{\star}A^{\star} $

④  $ (A+B)^{T}=A^{T}+B^{T} $ (det. -1, 尤无此结论)  $ A^{-1}=\frac{A^{*}}{|A|} $

⑤  $ \vert kA\vert=k^{n}\vert A\vert $  $ \vert A^{T}\vert=\vert A\vert $  $ \vert A^{-1}\vert=\frac{1}{\vert A\vert} $  $ \vert A^{+}\vert=\vert A\vert^{n-1} $

⑥  $ A \neq B $  $ \Rightarrow |A| \neq |B| $，即  $ A \neq 0 $  $ \Rightarrow |A| \neq 0 $ (矩阵到行列式的映射是多对一)

 $ A=\left[\frac{1}{1-1}\right], B=\left[\frac{1}{1-1}\right] $ 满足： $ AB\neq BA,\ AB=O $ 且  $ A,B\neq0 $

 $ A = \left[c^{\frac{1}{d}}\right], A^{-1} = \frac{1}{ad - bc} \left[\frac{d - b}{c - a}\right] $ 主对调，副变号  $ \left[\frac{A_{1}}{A_{2}} - A_{k}\right]^{-1} = \left[\frac{A_{1}}{A_{k}} - A_{k}\right], \left[\frac{A_{1}}{A_{k}} - A_{k}\right]^{-1} = \left[\frac{A_{1}}{A_{k}} - A_{k}\right] $

 $ \left[\frac{D}{C}\right]^{-1} = \left[\frac{CD_{B}^{-1}C}{B^{-1}D}\right]^{-1} = \left[\frac{D}{C}\right]^{-1} = \left[\frac{D}{C}\right]^{-1} = \left[\frac{D}{C}\right]^{-1} = \left[\frac{D}{C}\right]^{-1} = \left[\frac{D}{C}\right]^{-1} = \left[\frac{D}{C}\right]^{-1} $ (看0): 主对调，副不变

(复杂项): 与0一列的作为第一项

⑨  $ \gamma(A_{n\times0})=D $, AB=AC, 则 B=C

 $$ A^{2}-(A^{*})^{2}=(A+A^{*})(A-A^{*}) $$ 

## 二、可逆/满秩/非奇异

 $ |A|=0 \Leftrightarrow A^{*} $每一列为 $ A X=0 $的解

2. 一定要先判n阶，否则可能有 $ A_{2\times3}B_{3\times2}=E_{2} $但A不可逆

## 三、AB

1.  $ A, B \neq 0, AB = 0 \Rightarrow |A| = |B| = 0 $ 证：① 设  $ A $ 可逆，则  $ B = A^T O = O $ 矛盾 ②  $ y(B) \geq (1 \Rightarrow y(A) \leq n - r(B) < n $ ③  $ A x = 0 $ 有非零解， $ B x $ 也有非零解

2. AB=0 且  $ r(A)_{\max}=D \Rightarrow B=0 $ 证： $ r(A)+r(B) \leq D \Rightarrow y(B)=0 $ 推论： $ AB=AC $ 且  $ r(A)=D \Rightarrow B=C $

3. AB的列向量组可由A的列向量组线性表示推论： $ [A, AB] \xrightarrow{列}[A, 0], [A, BA] \xrightarrow{行}[A] $

 $ B_{n \times D_2} = A_{n \times D_1} C_{D_1 \times D_2} $ 且  $ d_{1 \times D_1} $ 无关，则  $ \beta_{1 \times D_2} $ 无关  $ \Leftrightarrow \gamma(c) = D_2 $ (3) 满秩)

四、 $ \gamma(A)=1 $

1.  $ \gamma(A)=1\Leftrightarrow A=\alpha\beta^{T} $  $ \alpha $可取为列向量的最大公因数， $ \beta^{T} $取相除结果  $ \operatorname{tr}(A)=\beta^{T}\alpha=\alpha^{T}\beta $

 $$ 2.\lambda_{A} = \text{tr}(A), \underbrace{0, \ldots, 0}_{n-1 个} $$ 

## 五、 $ A^{n} $

1.  $ \gamma(A)=1 $，则 $ A^{n}=\left(\beta^{T}d\right)^{n-1}A=\left[\left[\gamma(A)\right]^{n}\right]^{n-1}A $

2.  $ \left[\begin{array}{l} B^{0}\\0c\end{array}\right]^{n}=\left[\begin{array}{l} B^{n}\\0c^{n}\end{array}\right] $

 $ \left[\begin{array}{l}1a\\01\end{array}\right]^{n}=\left[\begin{array}{l}1na\\01\end{array}\right] $

3. A为上下三角矩阵，则 $ A^{n}=(E+B)^{n}=E+nB+CnB^{2}+\cdots+nB^{n}+B^{n} $ 证：AB=BAB时，有 $ (A+B)^{n}=\sum_{k=0}^{n}C_{n}^{k}B^{k}A^{n-k} $（共 $ n+1 $项）

4. 相似对角化， $ A = P \Lambda P^{-1} $， $ f(A) = P f(N)P^{-1} $ （ $ P $不一定得求出来，因为 $ f(N) $可能=0）

#### 矩阵-A

1、证明满足一定条件时， $ AB=BA $（乘积可交换）（1）均为diag (2)  $ A=E $ (3)  $ A=B $ (4)  $ A,B,A+B $均是幂等阵 (5)  $ A,B $为对称阵，则 $ AB $是对称阵  $ \Leftrightarrow AB=BA $

证：(1)  $ N(3) $ 略 (4)  $ (A+B)^{2}=A^{2}+AB+BA+B^{2}=A+B $，则  $ AB+BA=0 $，右乘  $ A:AB+BA=0 \Rightarrow AB=BA $

(5)  $ \Rightarrow $ :  $ (AB)^{T} = BA^{T}A^{T} = BA $，则 AB = BA  $ \Leftrightarrow $ :  $ (AB)^{T} = BA = AB $，则 AB 为对称阵

(6) A有n个位不相同的λ，则 $ A, B $有相同的 $ \Rightarrow AB=BA $，而 $ AB=BA\Rightarrow A $的纯是 $ B $的 $ \Rightarrow $

证：(6) 由 A 的 n 个  $ \lambda $ 不同，则  $ P^{-1}AP = \lambda_{1} $ (P 可逆). ①：由 S 相同，则 B 也有 n 个线性无关的 S，则  $ P^{-1}BP = \lambda_{2} $ (P 与 A 中的 S 相同  $ P^{-1}ABP = P^{-1}APP^{-1}BP = \lambda_{1} $,  $ \lambda_{2} $，同理  $ P^{-1}BAQP = \lambda_{2} $,  $ \lambda_{1} $，显然 AB = BA. ② 对  $ \forall A S = \lambda S $，有  $ AB S = BA S = \lambda B S $，(ii)  $ B S = P $ 因而  $ B S $ 亦为  $ \lambda $ 对应的 S，又由特征值为单根，故  $ B S = K S $ (iii)  $ B S = 0 $，则  $ B S = 0 - S $

注：②中的反例为 $ B=E $，则 $ \forall n $有 $ B\cap\gamma=\gamma(\lambda=1,n) $，即 $ \forall n\left\{\gamma\right\}=\gamma^{n} $，然而A的约只张成直线，故 $ n>\gamma $时，取 $ \gamma=\frac{\gamma_{1}+\gamma_{2}}{2} $时，可同时对角化

 $ B\eta=\gamma $，但 $ A\eta=\frac{1}{2}(\lambda_{1}s_{1}+\lambda_{2}s_{2}) $显然不是特征向量。请注意：①②都说用A、B共享一组共同的 $ \gamma=n $的特征向量基准限制特征空间的自由度记为k但n个线性无关的为n个不同的入，因此仅当B的入互不相同时，B的约才是A的，若B的某个人重数大于1，

因此：A有n个互不相同的入且 $ AB=BA $，则 $ P^{-1}AP=\Lambda_{1}\Rightarrow P^{-1}BP=\Lambda_{2} $ ①由P的列向量均为A的3知，其亦为B的3，因而 $ P^{-1}BP=\Lambda_{2} $ ②取B=E，则P可取任意可逆阵，因而P的列向量不一定为A的3

补充： $ \alpha_{1}, \alpha_{2} $线性相关 $ \Leftrightarrow d_{1}, d_{2} $共线(坐标成比例) $ \Leftrightarrow r=1 $， $ d_{1}, d_{2}, d_{3} $线性相关 $ \Leftrightarrow d_{1}, d_{2}, d_{3} $共面 $ \Leftrightarrow r=2 $或1

2. 抽象矩阵求逆 (1) AB = A + B, 求  $ (A - E)^{-1} $ (2)  $ A^{K} = O $, 求  $ (E - A)^{-1} $ (3) A, B,  $ A + B^{-1} $ 可逆, 求  $ (A + B)^{-1} $

(4) B, E + AB 可逆，求  $ (E + BA)^{+} $

解：(1)①构造 $ A-E $:  $ (A-E)B=A $ ②右侧应为 $ E $:  $ (A-E)B-A+E=E $ ③合并 $ (A-E)(B-E)=E $，即 $ (A-E)^{2}=B-E $

(2)  $ E - A^{k} = E $. 故  $ (E - A)(E + A + -A^{k+1})E $

(3)  $ A + B = A + AA^{-1}B = A(E + A^{-1}B) = A(B^{-1} + A^{-1})B $.  $ (A + B)^{-1} = B^{-1}(A^{-1} + B^{-1})^{-1}A^{-1} $

(4) AB转为BA需要 $ B(AB)B^{+} $，因此 $ (E+BA)=B(B^{+}+A)=B(E+AB)B^{+} $若(又知 $ E+AB $可逆，则 $ (E+BA)^{-1}=E-B(E+AB)^{-1}A $

3.  $ A=\begin{bmatrix}a & b \\ b & a\end{bmatrix} $，求  $ Y(A) $

解:  $ A \Rightarrow \begin{bmatrix} \frac{a}{b-a} & \frac{a}{b-b} & \frac{a}{b-a} & 0 \\ \frac{a}{b-a} & \frac{a}{b-a} & \frac{a}{b-a} & 0 \\ 0 & 0 & 0 & 0 \end{bmatrix} = \begin{bmatrix} a + b\delta & \frac{b}{a} & \frac{b}{a} & \frac{b}{a} & \frac{b}{a} \\ 0 & \frac{a}{a} & \frac{b}{a} & 0 & 0 \\ 0 & 0 & 0 & 0 & 0 \end{bmatrix} $，故  $ \left\{\begin{array}{l} a=b=0, \\ a=b \neq 0, \\ a=4 \neq 0, \\ a \neq B \neq A \neq -4b, \\ \end{array}\right. $  $ r(A)=0 $ 动态全0矩阵

4.  $ a = \left[\frac{1}{2}\right] $,  $ B = \left[\frac{2}{3}\right] $,  $ A = \left[\frac{-1}{30}\frac{2}{1}\right] $,  $ B = A d B^{T} $, 求  $ B^{n} $

解：显然应该找 $ B^{n} $中为常数的项，由于 $ \beta^{T} $行数为1，故取 $ \beta^{T}\Delta d $，则 $ B^{n}=(-3)^{n+1}A d B^{T} $

5.  $ P=\left[\frac{1}{2}\frac{2}{1}\frac{-2}{1}\right] $, 求  $ P^{-1} $

解 注意到  $ Q=\frac{P}{3} $ 正交，则  $ P^{-1}=\frac{1}{3}Q^{T}=\frac{1}{4}P^{T}=\frac{1}{9}\left[\frac{1}{2}\frac{2}{4}\frac{2}{1}\frac{2}{2}\right] $

6.  $ A = [1, 1', 1] $, 求  $ A^{2}, A^{4} $

解  $ A^{2}=\left[\frac{1}{1-1}\right]\left[\frac{1}{1-1}\right] $ 记为  $ \left[\begin{array}{c}0\ E_{1}\\ 1\ 0\end{array}\right]\left[\begin{array}{c}0\alpha\\ 0\ B\end{array}\right]=\left[\begin{array}{c}0\ B\\ 0\alpha\end{array}\right]=\left[\begin{array}{c}1\\ 1\end{array}\right] $,  $ A^{4}=\left[\begin{array}{c}E_{2}\\ E_{1}\end{array}\right]\left[\begin{array}{c}E_{2}\\ E_{2}\end{array}\right]=\left[\begin{array}{c}E_{2}\\ E_{2}\end{array}\right]=\left[\begin{array}{c}1\\ 1\end{array}\right] $

注：左边的A分成1列、3列，后边的A则必须分成1行、3行.

7. A、B为n阶正交矩阵且 $ |A|+|B|=0 $，证明： $ (A+B)=0 $

证： $ \vert A+B\vert=\vert BB^{\mathrm{T}}A+BA^{\mathrm{T}}A\vert=\vert B\vert\vert B^{\mathrm{T}}+A^{\mathrm{T}}\vert A\vert=\vert B\vert\vert(A+B)^{\mathrm{T}}\vert A\vert=-\vert B\vert^{2}\vert A+B\vert $ 由 $ \vert B\vert^{2}=\vert B\vert\Rightarrow(A+B)=0 $

8. 已知 A 为 n 所正交矩阵，证明  $ A^{*} $ 是正交矩阵

证:  $ AA^{T}=E $, 则  $ |A^{*}|=|A||A^{-1}|=|A||A^{T} $  $ A^{*}(A^{*})^{T}=|A|A^{T}\cdot|A|\cdot A=|A|^{2}A^{T}A=E $

9. 由初等行变换求  $ \left[\begin{array}{l} A C \\ O B \end{array}\right] $ 的逆，其中 A、B 可逆

解:  $ [D,E]=\left[\begin{array}{l} A C E O \\ O B O E \end{array}\right]\xrightarrow[左乘]{行}\left[\begin{array}{l} E A^{1} C A^{1} O \\ O E O B^{1} \end{array}\right]\rightarrow\left[\begin{array}{l} E^{0} A^{1} \\ O E O \end{array}\right.\rightarrow\left[\begin{array}{l} A^{1} C B^{1} \\ O B^{1} \end{array}\right] $$ 

10. A、B为n阶矩阵，证明： $ \left|\frac{AB}{BA}\right|=\left|A+B\right|\cdot\left|A-B\right| $

解：由  $ \left[\begin{array}{c} E \\ O E \end{array}\right]\left[\begin{array}{c} A B \\ B A \end{array}\right] $  $ [E-E] $ =  $ \left[\begin{array}{ccc} A+B & A+B \\ B & A \end{array}\right]\cdot\left[\begin{array}{cc} E & -E \\ O & E \end{array}\right]=\left[\begin{array}{ccc} A+B & O & \\ B & A-B \end{array}\right] $ 可证

11. A n阶正定，B n阶反对称. 证明  $ A-B^{2} $ 可逆

11. A n阶正定，B n阶反对称. 证明 A-B 可逆

证明： $ \left\{\begin{array}{l} A^{T}=A \\ B^{T}=B \end{array}\right. $  $ (A-B)^{T}=(A+B^{T}B)^{T}=A+B^{T}B=A-B^{T} $ (对称性). 而  $ x^{T}(A-B)x=x^{T}Ax+(Bx)^{T}Bx>0 $, 则  $ \left|A-B\right|>0 $

(2) 一类  $ \operatorname{tr}(AXx)^{\top}(1) $  $ \operatorname{tr}(AXx^{\top}) $ (2)  $ \begin{vmatrix} 0 & x^{T} \\ -x & A \end{vmatrix} $ (3)  $ A^{T}=A $,  $ tv(ABxx^{\top})+(v_{1}xx^{\top}AB) $ (4)  $ \begin{vmatrix} A & -x \\ x^{\top} & 0 \end{vmatrix} $

解：(1) 由  $ \frac{1}{x}\gamma(A_{B})_{x\times x} $ 知  $ \operatorname{tr}(BA) $ 知  $ \operatorname{tr}(AXx^{\top}) = \gamma(AXx) = x^{T}AX $

注： $ \operatorname{tr}(AB) = \sum_{i=1}^{m}\sum_{j=1}^{n}a_{ij}b_{ji} $,  $ \operatorname{tr}(BA) = \sum_{j=1}^{n}\sum_{i=1}^{m}b_{ji}a_{ij} $

(2)  $ \begin{vmatrix} 0 & x^{T} \\ -x & A \end{vmatrix} = \begin{vmatrix} x^{T}Ax & x^{T} \\ 0 & A \end{vmatrix} = (AXx^{T}A^{-1}x = x^{T}A^{*}x $

(3)  $ =t\gamma(x^{T}ABx) + t\gamma(B^{T}AXx^{T}) = x^{T}ABx + t\gamma(x^{T}B^{T}A^{T}x) = (A^{T}x)^{T}BX + (BX)^{T}A^{T}x = (AX)^{T}BX + (BX)^{T}A^{T}x = 2(AX)^{T}BX $

(4) 将一x化为0:  $ \det = \begin{vmatrix} A & -x \\ x^{T} & 0 \end{vmatrix} \bigg| \begin{vmatrix} E & A^{T}x \\ 0 & 1 \end{vmatrix} = \begin{vmatrix} A & 0 \\ x^{T} & x^{T}A^{T}x \end{vmatrix} = (A) x^{T}A^{T}x = x^{T}A^{*}x $

13. n阶A, $ \gamma(A)=\gamma $. 证明:  $ A^{2}=A \Leftrightarrow $ 3列满秩 $ C_{n \times r} $ 使 A=CB, BC=E_{r} $

证$\Leftrightarrow A=CBCB=CB=A\Rightarrow A(A-E)=0$ 由$\gamma(E)=\gamma(A-(A-E))\leq\gamma(A)+\gamma(A-E)\leq n$ 知取等号 $\lambda=0$ 对应有 $n-r$ 个，$\lambda=1$ 对应 $n-r(A-E)$ 共和为 $n$，知 $A\sim\Lambda$，即 $A=P^{1}\begin{bmatrix}E_{r}&0\\0&0\end{bmatrix}P=P^{1}\begin{bmatrix}E_{r}&0\\0\end{bmatrix}\left[E_{r},0\right]P=CB$ 且 $BC=\left[E_{r},0\right]P P^{-1}\left[E_{r}\right]=E_{r}$ 成立

14.  $ f(x)= $ 阶导连续， $ |A|=\left|\begin{matrix}1&x_{1}&f(x_{1})\\1&x_{2}&f(x_{2})\\1&x_{3}&f(x_{3})\end{matrix}\right| $ ( $ 0<x_{1}<x_{2}<x_{3} $)，证明： $ f''(x)>0 $ 日对  $ |A|>0 $， $ f''(x)<0 $ 时  $ |A|<0 $

证： $ \left|A\right|=\left|\begin{matrix}x_{1}&f(x_{1})\\0&x_{2}-x_{1}&f(x_{2})-f(x_{1})\\0&x_{3}-x_{2}&f(x_{3})-f(x_{2})\end{matrix}\right|=(x_{1}-x_{1})(x_{3}-x_{2})\left[f^{\prime}(\xi_{2})-f^{\prime}(\xi_{1})\right] $ ( $ 0<x_{1}<x_{2}<x_{3} $) 于是  $ f^{\prime\prime}>0 $ 日对  $ f^{\prime}(\xi_{2})-f^{\prime}(\xi_{1})\Rightarrow|A|>0 $  $ f^{\prime\prime}<0 $ 同理

##### (12. 数一)

### 15 3维单位列向量  $ \alpha $，3阶单位矩阵 E， $ \gamma(E - \alpha d^{T}) = 0 $

解: ①  $ \alpha d^{T} $ 的  $ \lambda = 1, 0, 0 $ 故实对称  $ E - \alpha d^{T} $ 的  $ \lambda = 0, 1, 1 $. 即  $ \boldsymbol{Q}^{-1} (E - \alpha d^{T}) \boldsymbol{Q} = (0, 1) $ 故  $ \gamma = 2 $

解：$\alpha d_{1}^{\prime}\alpha=1,0^{\circ}$ 故实对称 $E-\alpha d_{1}^{\prime}\alpha=0,1,1$ 即 $Q^{\prime}(E-\alpha d_{1}^{\prime})Q=(1,1)$ 故 $\gamma=2$

② $\left|E-\alpha d_{1}^{\prime\prime}\right|=\left|\frac{1-\alpha^{2}}{1-\alpha^{2}}-\alpha d_{1}d_{2}-d_{2}d_{3}\right|=\left|\frac{1}{0}\frac{d_{1}}{1-\alpha^{2}}-\cdots-\frac{d_{1}}{0}\frac{d_{2}}{1-\alpha^{2}}\cdots\frac{d_{3}}{0}\right|=\left|\frac{1}{0}\frac{d_{1}}{1-\alpha^{2}}-\cdots-\frac{d_{1}}{0}\frac{d_{2}}{1-\alpha^{2}}\cdots\frac{d_{3}}{0}\right|=1-\alpha_{1}^{2}-\alpha_{2}^{2}-\alpha_{3}^{2}-\cdots-\alpha_{n}^{2}-\alpha_{n+1}^{2}-\cdots=\left|\frac{1}{0}\frac{d_{1}}{1-\alpha_{1}^{2}}-\cdots-\frac{d_{1}}{0}\frac{d_{2}}{1-\alpha_{2}^{2}}-\cdots-\frac{d_{2}}{0}\frac{d_{3}}{1-\alpha_{3}^{2}}-\cdots\right|=0$ 知 $\gamma(E-d d_{1}^{T})\leq2$

又 $\gamma(E-d d_{1}^{T})\geq\gamma(E)-\gamma(d^{\prime}d^{\prime\prime})=2$ 知 $\gamma=2$

# 向量组

## 一、正交

### ±β都满足，不可漏土

1. 正交： $ \alpha^{T}\beta=0 $ 标准正交： $ \alpha^{T}\beta=0 $ 且  $ \|\alpha\|=\|\beta\|=1 $ 个(前位后七.两两正交)

2. 正交矩阵  $ \Leftrightarrow A^{T}A = E \Leftrightarrow A^{T} = A^{T} \Leftrightarrow A $ 的行列向量组是规范正交基  $ \Rightarrow |A| = \pm1 $

A. B正交 $ \Rightarrow A^{T}, A^{-1}, A^{*}, AB $正交

## 二、向量组

1. 以下记  $ A_{n \times D_1} = [d_1, \ldots, d_D] $,  $ B_{n \times D_2} = [\beta_1, \ldots, \beta_D] $,  $ \overrightarrow{x}_{D \times 1} = [\overrightarrow{k}_1, \ldots, \overrightarrow{k}_D] $ 且  $ \overrightarrow{x} \neq \overrightarrow{0} $,  $ \overrightarrow{b} = [\overrightarrow{b}_1, \ldots, \overrightarrow{b}_D] $, 以  $ d_{n \times D} $ 表示向量组  $ d_1, \ldots, d_D $

2. 线性相关  $ k_{1}\overrightarrow{a_{1}}+\cdots+k_{n}\overrightarrow{a_{n}}=\overrightarrow{0} $，即  $ A\overrightarrow{x}=0 $ 线性无关 仅有  $ \overrightarrow{x}=\overrightarrow{0} $ 时才有  $ A\overrightarrow{x}=\overrightarrow{0} $

线性表示  $ \overrightarrow{b}=k_{1}\overrightarrow{d_{1}}+\cdots+k_{D}\overrightarrow{d_{D}} $，即  $ A\overrightarrow{x}=b $

3. 七大定理

无关  $ \rightarrow V $ 不可由

①可表出  $ d_{mod} $ 线性相关  $ \Leftrightarrow $  $ \exists d_{i} $ 可由其余 n-1 个向量表示

②唯一表出  $ d_{100} $ 线性无关且  $ \overrightarrow{b}, d_{100} $ 线性相关  $ \Leftrightarrow A\overrightarrow{x} = \overrightarrow{b} $ 且  $ \overrightarrow{x} $ 唯一证:  $ D = \gamma(A) \leq \gamma(A, \beta) < D H \Rightarrow \gamma(A, \beta) = D = \gamma(A) $

③以少表多，多的相关若 $ \beta_{1} $可由 $ \alpha_{1} $表出，则 $ \left\{\begin{array}{l}D_{2}>D_{1}\Rightarrow P_{1}wD_{2} \\ B_{1}wD_{2}\end{array}\right. $线性无关 $ \Rightarrow D_{1}\geq D_{2} $（高维表示低维）

个数④部分&整体 部分相关⇒整体相关，整体无关⇒部分无关

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//cb70abd2-6f58-4082-a5c2-27ad1731bea0/markdown_4/imgs/img_in_image_box_858_708_1055_781.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A53Z%2F-1%2F%2F36056ab68bc29bff18b4bbb025794b4a39e5670b00b9d8ecff7a68d50ed74e5e" alt="Image" width="16%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//cb70abd2-6f58-4082-a5c2-27ad1731bea0/markdown_4/imgs/img_in_image_box_858_708_1055_781.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A53Z%2F-1%2F%2F36056ab68bc29bff18b4bbb025794b4a39e5670b00b9d8ecff7a68d50ed74e5e" alt="Image" width="16%" />

n  $ \xrightarrow{D} $ 无关  $ \xrightarrow{加量(整体)} $

</div>


</div>


维数⑤延长&缩短 原来无关→延长无关，原来相关→缩短相关

D  $ \xrightarrow{} $ 大量  

无关 (整体)

(延长) 升维  $ \downarrow $ 无关

⑥  $ Ax=0 $  $ d_{1}wD $ 相关  $ \Leftrightarrow $  $ Ax=0 $ 有非零解  $ \Leftrightarrow $  $ \gamma(A) < D $  $ d_{1}wD $ 无关  $ \Leftrightarrow $  $ Ax=0 $ 仅零解  $ \Leftrightarrow $  $ \gamma(A)=D $

① $ Ax=b $ ∵可由 $ d_{1} $表示 $ \Leftrightarrow Ax=b $有解 $ \Leftrightarrow y[A:b]=y(A) $ (增广=系数)

### 4. 等价向量组

1. 极大线性无关组  $ \alpha_{mod} $ 中若有  $ \alpha $ 满足: ①  $ \alpha $ 线性无关 ②  $ \forall d_{mod} $ 均可由  $ \alpha $ 线性表示  $ \alpha_{mod} \subseteq \alpha $

2. 等价向量组  $ \alpha_{1}w_{1}D_{1} \subseteq \beta_{1}w_{2} $  $ \Leftrightarrow $  $ \alpha_{1}w_{1}, \beta_{1}w_{2} $ 可相互线性表示  $ \Leftrightarrow $  $ \gamma(A) = \gamma(B) = \gamma(A'B) $  $ \Leftrightarrow $  $ \gamma(A) = \gamma(B) $ 且可单方向表示矩阵等价要同型+同秩，向量组等价要同维 (行数 n 相等，不必有  $ D = D_{2} $) + 上述条件

## 三、向量空间

1. 坐标  $ \overrightarrow{b} = k_{1}\overrightarrow{d_{1}} + \cdots + k_{n}\overrightarrow{d_{n}} = A\overrightarrow{X}_{n \times 1} $，称  $ \overrightarrow{d_{wn}} $ 为  $ R^{n} $ 的一个基， $ \overrightarrow{x} $ 为  $ \overrightarrow{b} $ 在该基下的坐标

2. 基变换  $ BC = A $ 称为  $ \beta_{100} $ 到  $ d_{100} $ 的基变换公式，C 为过渡矩阵（可逆）.

3. 坐标变换 若  $ \overrightarrow{b} = B\overrightarrow{x} = A\overrightarrow{y} $，则  $ \overrightarrow{x} = C\overrightarrow{x} $  $ \xrightarrow{B\to A} $ 证：由  $ B = AC^{+} $，则  $ AC^{+}\overrightarrow{x} = A\overrightarrow{y} $，即  $ \overrightarrow{C}\overrightarrow{x} = \overrightarrow{y} $

4. 将规范正交基化为规范正交基的过渡矩阵为正交矩阵

## 四、施密特正交化

对 $ \overrightarrow{a}_{1} $和 $ \overrightarrow{a}_{2} $，令 $ \overrightarrow{a}_{1}\cdot\overrightarrow{a}_{2}=\overrightarrow{a}_{1} $

 $$ \overrightarrow{\alpha_{2}}\overrightarrow{\beta_{2}}=\overrightarrow{\alpha_{2}}-\frac{\left(\overrightarrow{\beta_{1}},\overrightarrow{\alpha_{2}}\right)}{\left(\overrightarrow{\beta_{1}},\overrightarrow{\beta_{1}}\right)}\overrightarrow{\beta_{1}} $$ 

证： $ \overrightarrow{a}_{m} $ 应减去在  $ \beta_{m-1} $ 上的投影

 $$ \overrightarrow{\alpha_{3}}\quad\overrightarrow{\beta_{3}}=\quad\overrightarrow{\alpha_{3}}-\frac{\left(\overrightarrow{F_{1}}\cdot\overrightarrow{\alpha_{2}}\right)}{\left(\overrightarrow{F_{2}}\cdot\overrightarrow{\beta_{1}}\right)}\overrightarrow{\beta_{1}}-\frac{\left(\overrightarrow{F_{2}}\cdot\overrightarrow{\alpha_{3}}\right)}{\left(\overrightarrow{F_{2}}\cdot\overrightarrow{\beta_{2}}}\overrightarrow{\beta_{2}}\right) $$ 

在  $ \overrightarrow{B_{1}} $ 上的投影为  $ \vert\overrightarrow{a}\vert\vert\cos\theta\cdot\frac{\overrightarrow{B_{1}}}{\vert\overrightarrow{B_{1}}\vert\vert}=\vert\overrightarrow{B_{1}}\vert\vert\vert\vert\overrightarrow{a}\vert\vert\cos\theta\vert\vert\overrightarrow{B_{1}}\vert $

 $ =(\overrightarrow{B_{1}},\overrightarrow{a})\cdot\frac{\overrightarrow{B_{1}}}{(\overrightarrow{B_{1}},\overrightarrow{b})} $ 长度 方向

(每列只出现一次文)

或可由 $ (\overrightarrow{a}_{2}-x_{21}\overrightarrow{b}_{1})^{\top}\overrightarrow{b}_{1}=0 $解得 $ x_{21}=\frac{\overrightarrow{a}_{2}^{\top}\overrightarrow{b}_{1}}{\overrightarrow{b}_{1}^{\top}\overrightarrow{b}_{1}}=\frac{(\overrightarrow{b}_{1},\overrightarrow{a}_{2})}{(\overrightarrow{b}_{1},\overrightarrow{b}_{1})} $

## 五、秩  $ \exists r $ 阶子式  $ \neq 0 $， $ \forall r+1 $ 阶子式 = 0

 $ 0 < \gamma(A_{m0}) = \text{行秩} = \text{列秩} \leq \min\{n, D\} $  $ \gamma(A) = 0 \Leftrightarrow A = 0 $

2.  $ \gamma(A)=\gamma(A^{\top})=\gamma(A^{\top}A)=\gamma(AA^{\top}) $ 注： $ \gamma\left[(A^{\top},B^{\top})\binom{A}{B}\right]=\gamma(A^{\top},B^{\top}) $

3.  $  r(A^{*}) = \left\{ \begin{array}{ll} n &  r(A) = n \\ 0 &  r(A) = n - 1 \end{array} \right.  $

4.  $ V(A) + V(B) - N \leq V(AB) \leq \min\{V(A), V(B)\} $

5.  $ \gamma(A)-\gamma(B)\leq\max\{\gamma(A),\gamma(B)\}\leq\gamma([A,B])\leq\gamma(A)+\gamma(B) $

b  $ A_{n \times D} B_{0 \times S} = 0 \Rightarrow \gamma(A) + \gamma(B) \leq D $ (由4可得)

7. 若  $ A \xrightarrow{仅行} B $，则 A, B 行向量组等价，任何相应列向量组有相同的线性相关性 (AX = 0 与 BX = 0 同解) 即:  $ \left[\alpha_{1}^{T}\right] \xrightarrow{行} \left[\beta_{1}^{T}\right] \Rightarrow \gamma\left([\alpha_{1}, \alpha_{2}]\right) = \gamma\left([\beta_{1}, \beta_{2}]\right) = \gamma\left([\alpha_{1}, \alpha_{2}, \beta_{1}, \beta_{2}]\right) $

8.  $ \frac{r(A,B)}{r(A)} \leq r(A)+r(B) \leq r(A^0) \leq r(B^0) $  $ \gamma(A^0) = \gamma(A) + \gamma(B) $

9.  $ V(A_{n \times 0}) = D $，则  $ r(AB) = B $

10.  $ \gamma(A, AB) = \gamma(A) $,  $ \gamma(A, BA) \geq \gamma(A) $

### 向量组

1. 证明： $ \beta $ 可由  $ d_{1\sim D} $ 线性表出且表出式唯一  $ \Rightarrow d_{1\sim D} $ 线性无关

证: 若  $ \gamma < D $，则  $ A \times = \beta $ 解不唯一 ② 若相关，则  $ \left\{\begin{array}{l} k_{1}d_{1} + \cdots + k_{D}d_{D} = 0 \\ \lambda_{1}d_{1} + \cdots + \lambda_{D}d_{D} = \beta \end{array}\right. $ 则  $ \beta = \frac{\gamma}{2} $ ( $ k_{1} + \lambda_{1} + \lambda_{D} = 0 $)，必有  $ k_{1} + \lambda_{1} + \lambda_{D} $，即表出不唯一

2. 4维 $ \alpha_{1,2} $线性无关，与 $ \beta_{1,2} $正交. 证明： $ \beta_{1,2} $线性相关

证：令 $ A=\begin{bmatrix}\frac{\partial f}{\partial x} \\ \frac{\partial f}{\partial y}\end{bmatrix}_{3\times4} $，则 $ \gamma(A)=3 $且 $ A\beta_{i}=0 $，则 $ \gamma(\beta_{1},\beta_{2})\leq n-\gamma(A)=1 $

3. 设  $ \alpha_{1}\alpha_{1} $ 可由  $ \beta_{1}\alpha_{1} $ 线性表出，且  $ r(\alpha_{1}\omega_{1}) = r(\beta_{1}\omega_{1}) $，证明： $ \alpha_{1}\omega_{1} $ 与  $ \beta_{1}\omega_{1} $ 等价

证：设极大线性无关组分别为  $ \alpha_{1}\omega r $， $ \beta_{1}\omega r $，由  $ \alpha_{1}\omega r $ 可由  $ \beta_{1}\omega r $ 表出，则  $ r(d_{1}\omega r, \beta_{1}\omega r) = r(\beta_{1}r) = r $，又  $ \alpha_{1}\omega r $ 无关，为  $ \alpha_{1}\omega r $， $ \beta_{1}\omega r $ 的极大线性无关组，则  $ \beta_{1}\omega r $ 可由  $ d_{1}\omega r $ 表出。

4. n维向量组  $ d_{1} $ 与  $ d_{2} $ 有相同的秩，证明： $ \beta $ 可由  $ d_{1} $ 与  $ d_{2} $ 线性表出

解 $ ^{①} $这相当于 $ r(d_{1}\cos)=\gamma(d_{1}\cos,\beta) $，即 $ \gamma(A)=\gamma(A:\beta) $，显然有解

②设 $ d_{mr} $为 $ d_{ins} $的极大无关组，显然它亦为 $ d_{ins} $， $ \beta $的极大无关组，故 $ \beta $可由 $ d_{mr} $表出

5.3维列向量 $ d_{1},d_{2} $无关， $ P_{1}P_{2} $无关.证明：∃ $ \overrightarrow{r_{1}} $使 $ \overrightarrow{r_{2}} $既可由 $ d_{1,2} $，又可由 $ \beta_{1,2} $表出

证：4>3，故 $ d_{1,2} $， $ \beta_{1,2} $必相关。设 $ k_{1}d_{1}+k_{2}d_{2}+\mu_{1}\beta_{1}+\mu_{2}\beta_{1}=\overrightarrow{0} $，由反证法知 $ k_{1},k_{2} $不全为0，故 $ k_{1}\overrightarrow{0}+k_{2}\overrightarrow{0}+\overrightarrow{0} $，故可取 $ \overrightarrow{r}=k_{1}\overrightarrow{0}+k_{2}\overrightarrow{0}=-\mu_{1}-\mu_{2}\overrightarrow{0} $。注：一般而言由①式可解出 $ k_{1}=f(k_{2}) $，从而得出 $ \overrightarrow{r} $的具体数值

6. 若  $ \gamma(A) = D $，则  $ \gamma(A_{n \times 0} B_{DXS}) = \gamma(B) $

证： $ A\xrightarrow{行}E_{D} $，即可逆 $ P,\quad PA=\left[\frac{E_{0}}{0}\right]_{n \times 0} $ 则 $ PAB=\left[\frac{E_{0}}{0}\right]B=\left[\frac{B}{0}\right] $ 故 $ \gamma(AB)=\gamma(PAB)=\gamma(\frac{B}{0})=\gamma(B) $

7. n阶非零实矩阵 $ A: A^{T} + A = 0 $. n阶矩阵 $ B: \begin{pmatrix} A E \\ - B B \end{pmatrix}, \begin{pmatrix} A - E & 0 \\ A & A B \end{pmatrix}, \begin{pmatrix} A + E & 0 \\ B & A - E \end{pmatrix} $的秩 $ \gamma_{1}, \gamma_{2}, \gamma_{3} $

解: 若点  $ (A-E)x=0 $，则  $ Ax=x $， $ x^TAx=x^T x $， $ x x^T A x=x^T (-A^T)x=-(Ax)^T x=-x^T A x $，则  $ x^T A x=0 $ 故  $ x^T x=0 $，故  $ (A-E)x=0 $ 仅 0 解，故 A-E 可逆。同理  $ (A+E)x=0 $ 有  $ Ax=-x $， $ x^T Ax=-x^T x=0 $。于是  $ r_1=r\left(\begin{array}{c}A+E \\ 0\end{array}\right)\left(\begin{array}{c}A+E \\ 0\end{array}\right)=n+r(B) $， $ r_2=r\left(\begin{array}{c}A-E \\ A-E\end{array}\right)=n+r(AB) $， $ r_3=2n $。于是  $ r_3\geq r_1\geq r_2 $。

注： $ A^{T}+A=0 $ 时， $ x^{T}Ax=0 $， $ y(A+E)=y(A-E)=n $ ①还可由 $ y(A+E)=y(-A^{T}+E) $ 装置  $ y(-A+E)=y(A-E) $ 得出

8. 证明: (1)  $ \gamma(A+B) \leq \gamma(A, B) \leq \gamma(A) + \gamma(B) $ (2)  $ \gamma(AB) \leq \gamma(B) $ (3)  $ \gamma(\frac{A}{O B}) = \gamma(A) + \gamma(B) $ (4)  $ \gamma(\frac{A}{O B}) \geq \gamma(A) + \gamma(B) $

(5)  $ \gamma(\frac{A}{BA}) = \gamma(A) $,  $ \gamma(A, AB) = \gamma(A) $ (6)  $ A^{*}=\begin{cases} n, & n=0 \\ \frac{1}{1}, & n=1 \\ \gamma_{2n-1} & \end{cases} $ (7)  $ \gamma(AB) \leq \min(\gamma(A), \gamma(B)) $

证：由 $ A+B=[a_{1}+b_{1},\ldots,a_{n}+b_{n}] $，其中 $ a_{i}+\beta_{i} $均可由 $ \alpha_{i}\sim\alpha_{i} $， $ \beta_{i}\sim\beta_{i} $线性表出，故 $ r(A+B)\leq r(A,\beta) $。设A,B的列向量极大无关组为 $ \alpha_{1}\sim\alpha_{1} $， $ \beta_{1}\sim\beta_{1} $，而 $ [A,B] $的极大无关组可由 $ \alpha_{1}\sim\alpha_{1} $扩展为 $ \alpha_{1}\sim\alpha_{1} $， $ \beta_{1}\sim\beta_{1} $，显然 $ t\leq q $，则 $ r(A,B)=p+q\leq p+q=r(A)+r(B) $

(2) 按行向量，则  $ AB = C $ 可化为  $ \begin{bmatrix} a_{n1} & a_{nD} \\ a_{n1} & a_{nD} \end{bmatrix} \begin{bmatrix} \beta_{1} \\ \beta_{D} \end{bmatrix} = \begin{bmatrix} \gamma_{1} \\ \gamma_{n} \end{bmatrix} $，即  $ \gamma_{i} = \sum_{k=1}^{D} a_{ik} \beta_{k} $，因为  $ AB $ 行向量均可由  $ B $ 的行向量表出，故  $ \gamma_{AB} \leq \gamma_{CB} $

(3)  $ Y_{A}Y_{B}=0 $ 显然成立，以下讨论  $ Y_{A}Y_{B}\neq0 $ ① 子式 显然有  $ Y_{A}+Y_{B} $ 所子式  $ \left|A^{\prime}B^{\prime}\right|=|A^{\prime}|\left|B^{\prime}\right|\neq0 $，若取  $ Y>Y_{A}+Y_{B} $ 阶子式，则必在 A 中取大于  $ Y_{A} $ 的行数（或  $ B $ 中大于  $ Y_{B} $），此时  $ \det=0 $ ② 初等变换 由  $ \left[\begin{array}{l}A^{0}\\0\end{array}\right]\xrightarrow{ 行 }\left[\begin{array}{l}A^{\prime}0\\0\end{array}\right] $，其非零行数为  $ Y_{A}+Y_{B} $

(4)同(3)只讨论 $ Y_{A}Y_{B}\neq0 $，显然有 $ Y_{A}+Y_{B} $阶子式 $ \left|\begin{matrix}A^{*}\\ O B^{*}\end{matrix}\right|=|A^{\prime}|\left|B^{\prime}\right|\neq0 $，从而 $ Y\geq Y(A+Y(B)) $

可逆  $ \leftarrow[\frac{E^{0}}{B_{E}}][\frac{A}{B_{A}}]=[\frac{A}{0}][A,AB][\frac{E}{0}E]=[A,0] $ 同理还可由  $ \left[\frac{AAB}{OA^{T}}\right]=\left[\frac{A^{0}}{OA^{T}}\right]\left[\frac{E}{0}\right] $ 得  $ \gamma\left(\frac{A}{O}AB\right)=\gamma(A)+x(A)=2x(A) $. 记住列变换右乘行变换左乘即可

(6)① $ r=n $，取逆可证② $ r=n-1 $，即A中有 $ n-1 $阶式不为0，即 $ r(A^{*})=1 $， $ x(A)+r(A^{*})\leq n $，则 $ r(A^{*})=n-1 $。③ $ r<n-1 $，则 $ \forall n-1 $阶子式均为0，即 $ A^{*}=0 $

(7) 由  $ Bx=0 $ 的任一解都为  $ ABx=0 $ 的解，则  $ D_{2}-Y(B)\leq D_{2}-Y(AB) $，即  $ \gamma(AB)\leq\gamma(B) $.  $ \gamma(AB)=\gamma(B^{\top}A)^{\top}\leq\gamma(A^{\top})=Y(A) $

# 向量组 -A

 $ \overrightarrow{d_{1}}=(\frac{1}{5}),\overrightarrow{d_{2}}=(\frac{1}{2}),\overrightarrow{B_{1}}=(\frac{5}{5}),\overrightarrow{B_{2}}=(\frac{4}{5}) $ 求  $ \overrightarrow{d_{1}} $ 达到  $ \overrightarrow{B_{1}} $ 的过渡矩阵

解  $ \left[\frac{1}{5}\frac{1}{2}\frac{5}{10}\frac{4}{5}\right]\rightarrow\left[\frac{1}{5}\frac{0}{3}\right] $，即 $ \overrightarrow{B_{1}}=5\overrightarrow{d_{2}} $， $ \overrightarrow{B_{2}}=\overrightarrow{d_{1}}+3\overrightarrow{d_{2}} $。 $ C=\left[5\frac{1}{3}\right] $ A不可逆时，求出 $ \beta_{j}=\overrightarrow{C}k_{i}d_{i} $，则 $ C=\left[k_{ij}\right] $

2.  $ z_{1} = \frac{x - a_{2}}{a_{1}} = \frac{y - b_{2}}{b_{1}} = \frac{z - c_{2}}{c_{1}} $,  $ z_{2} = \frac{x - a_{3}}{a_{2}} = \frac{y - b_{3}}{b_{2}} = \frac{z - c_{3}}{c_{2}} $ 交于一点  $ \overrightarrow{d_{1}} = (\frac{a_{1}}{b_{1}})^{2} $，证： $ d_{1} $ 可由  $ d_{1}, d_{2} $ 线性表示

解：①记  $ \frac{x - a_{2}}{a_{1}} = \cdots = k^{0} $， $ \frac{x - a_{3}}{a_{2}} = \cdots = k^{1} $，由①得  $ x = ka_{1} + a_{2} $ 代入②知  $ a_{3} = ka_{1} + (1 + k)a_{2} $，故  $ \overrightarrow{a_{1}} = k\overrightarrow{a_{1}} + (1 + k)\overrightarrow{a_{2}} $

②由相交一点知  $ a_{1} \neq a_{2} $，不共线  $ (r=2) $ 为作图，不妨取  $ \overrightarrow{a_{1}} = (\overrightarrow{f_{1}}, \overrightarrow{a_{2}} = (\frac{1}{2}) $，为使  $ l_{1}, l_{2} $ 交于一点，不妨在  $ l_{1} $ 上取一点 A，则  $ l_{2} $ 被点 A 与方向所确定，因此  $ a_{3}^{2} $ 必在虚线上且可沿  $ \overrightarrow{(a_{1})} $ 或  $ \overrightarrow{l_{1}(a_{2})} $ 方向移动，故可由  $ l_{2} $ 表示  $ (r=2) $

③记  $ \beta = (\frac{a_{3} - a_{2}}{a_{1} - a_{2}}) = a_{3} - a_{2} $，由于  $ \beta $ 相当于  $ l_{1}, l_{2} $ 上两点相连，故  $ a_{1}, a_{2}, \beta $ 共面  $ \Leftrightarrow $ 混和积  $ = O \Leftrightarrow \begin{cases} a_{1}, b_{1}, c_{1} \\ a_{2}, b_{2}, c_{2} \end{cases} = a_{1} \Leftrightarrow d_{1}, d_{2}, 3 $ 相关

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//4280ca79-3d6c-4258-a660-7d093edfad9e/markdown_3/imgs/img_in_image_box_906_381_1077_527.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A55Z%2F-1%2F%2Faab20d54d3de326281cceb12775499af3fb7a9319848d1807fd7764364d1885a" alt="Image" width="14%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//4280ca79-3d6c-4258-a660-7d093edfad9e/markdown_3/imgs/img_in_image_box_906_381_1077_527.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A55Z%2F-1%2F%2Faab20d54d3de326281cceb12775499af3fb7a9319848d1807fd7764364d1885a" alt="Image" width="14%" />

 $ z_{1}(\overrightarrow{z_{1}})=\overrightarrow{z_{2}} $

 $ A $

 $ z_{3} $

 $ z_{1}(\overrightarrow{z_{1}})=\overrightarrow{z_{1}} $

</div>


</div>


④综合②③，因为 $ a_{3}=a_{2}+\beta $， $ \beta $与 $ \alpha_{1},\alpha_{2} $共面，故 $ \alpha_{3} $与 $ \alpha_{1},\alpha_{2} $共面

3.(98.数一)设$\left\{\begin{array}{l}\frac{a_{1}}{a_{2}}=\frac{b_{1}}{b_{2}}\\ \frac{c_{1}}{c_{2}}=\frac{d_{1}}{d_{2}}\end{array}\right.$满项，则$z_{1}:\frac{x-a_{1}}{a_{1}-a_{2}}=\frac{x-b_{3}}{b_{1}-b_{2}}=\frac{z-c_{3}}{a_{1}-c_{2}}$与$z_{2}:\frac{x-a_{1}}{a_{2}-a_{3}}=\frac{y-b_{1}}{b_{2}-b_{3}}=\frac{z-c_{1}}{c_{2}-c_{3}}$A.相交于一点B重合C平行但不重合D.异面

①$\overrightarrow{c}_{12}$共线$\Rightarrow z_{1}, z_{2}$平行/重合

$\overrightarrow{c}_{12}$不共线$\Rightarrow z_{1}, z_{2}$相交/异面显然$\overrightarrow{a_{1}}-\overrightarrow{a_{2}}$与$\overrightarrow{a_{2}}-\overrightarrow{a_{3}}$不共线类似20年，考虑$\overrightarrow{b}=\overrightarrow{a_{1}-\overrightarrow{a_{2}}}$，显然$\overrightarrow{a_{1}}-\overrightarrow{a_{2}},\overrightarrow{a_{2}}-\overrightarrow{a_{3}}$是否共面（因为$z_{1}, z_{2}$共面时，上述三向共面）即$\left|\begin{array}{ccc}a_{1}-a_{2}&b_{1}-b_{3}&c_{1}-c_{2}\\a_{1}-a_{2}&\cdots&\end{array}\right|=\frac{v_{2}+v_{3}}{a_{2}-a_{3}}=\frac{b_{1}-b_{2}}{b_{1}-b_{3}}=\frac{c_{1}-c_{2}}{a_{2}-a_{3}}=0$故共面A

②同20年①有 $ x-a_{3}=k(a_{1}-a_{2}) $， $ x-a_{1}=\lambda(a_{2}-a_{3}) $，二者x相等，故 $ a_{1}-a_{3}+k(a_{2}-a_{1})+\lambda(a_{2}-a_{3})=0 $，由 $ r(\beta_{2},\beta_{3})=r(\beta_{2},\beta_{3},-\beta_{1})=2 $

知有唯一解  $ k=1, \lambda=-1 $

③显然  $ \overrightarrow{a} \cdot \overrightarrow{b} = 23 $ 张成一个立体  $ (r=3) $，其对应顶点 A、B、C 围成一个平面  $ \triangle ABC $。由  $ \overrightarrow{a} - \overrightarrow{a_2} = \overrightarrow{OA} - \overrightarrow{OB} = \overrightarrow{BA} $， $ \overrightarrow{a_2} - \overrightarrow{a_3} = \overrightarrow{OB} - \overrightarrow{OC} = \overrightarrow{CB} $ 可在图中作出  $ l_2, l_2 $。因为  $ l_1, l_2 $ 各自与  $ \triangle ABC $ 夹面，故  $ l_1, l_2 $ 共面。

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//4280ca79-3d6c-4258-a660-7d093edfad9e/markdown_3/imgs/img_in_image_box_855_844_1023_958.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A55Z%2F-1%2F%2Fc7de2d54325f7bfe0d35b8fd6304afc7c18f4f2d75f921faac80725812377e92" alt="Image" width="14%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//4280ca79-3d6c-4258-a660-7d093edfad9e/markdown_3/imgs/img_in_image_box_855_844_1023_958.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A55Z%2F-1%2F%2Fc7de2d54325f7bfe0d35b8fd6304afc7c18f4f2d75f921faac80725812377e92" alt="Image" width="14%" />

A
B
C

</div>


</div>


且 $ d_{3}\neq0 $，证明：

4.(14.数一次)3维 $ d_{1,2,3} $.对 $ \forall k,l,d_{1}+kd_{3},d_{2}+2d_{3} $无关 $ \Rightarrow d_{1,2,3} $无关

且 $ k_{1} $不全为0

证：$\Leftarrow(d_{1},d_{2},d_{3})\left(\frac{10}{k_{2}}\right)$, 则 $r=r(k_{2}^{\frac{10}{1}})=2$, 无关 $\Rightarrow$ 不妨设相关。由于令 $k=2=0$ 和 $d_{1,2}$ 无关，故有 $d_{3}=k_{1}d_{1}+k_{2}d_{2}$ ✓

于是 $(d_{1},d_{2})\left(\frac{1+k_{1}k}{k_{2}k}\frac{k_{1}k}{1+k_{2}k}\right)$，$|1+k_{1}k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k^{k}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}}))}}))}}))}}))}}))}}))}}))

注： $ \alpha_{3}=\overrightarrow{O} $时 $ \Rightarrow $不成立

5.(23数一改) $ d_{1,2}=\left(\frac{1}{3}\right),\left(\frac{2}{1}\right),\quad\beta_{1,2}=\left(\frac{2}{5}\right),\left(\frac{1}{1}\right) $ 既可由 $ d_{1},d_{2} $表示，又可由 $ \beta_{1},\beta_{2} $表示，求 $ x $

解: ① 记  $ \overrightarrow{n}_{1} = \alpha_{1} \times \overrightarrow{n}_{2} = (-1, 5, -3) $， $ \overrightarrow{n}_{2} = \beta_{1} \times \beta_{2} = (5, 7, -5) $。由  $ \alpha_{1} $ 生成平面  $ S_{1} $， $ \beta_{1} $ 生成  $ S_{2} $ 则  $ \gamma $ 既在  $ S_{1} $ 上又在  $ S_{2} $ 上，由  $ \overrightarrow{n}_{1} \times \overrightarrow{n}_{2} = (-4, -20, 32) $ 知  $ \overrightarrow{r}_{1} = (-\frac{4}{32})^{2} $ 共线，即  $ \overrightarrow{r}_{1} = k(\frac{1}{3}) (k \in \mathbb{R}) $ ② 令  $ k, d_{1} + k_{2}, d_{2} = 2, \beta_{1} + 2, \beta_{2} = k(\frac{k_{1}}{3}) = k(\frac{3}{4}) $ 故  $ \overrightarrow{r}_{1} = 3k(\frac{1}{3}) - k(\frac{1}{3}) = k(\frac{1}{3}) $

# 方程组

一、线性方程组

→行向量与解向量正交， $ \overrightarrow{a_{i}}\overrightarrow{x}=0\Rightarrow\overrightarrow{x}\overrightarrow{a_{i}}=0\Rightarrow $ 解向量作齐次方程组的行向量时，A的行向量即为解向量

1. 齐次  $ A_{n \times D} \overrightarrow{x} = \overrightarrow{0} $ 非齐次  $ A_{n \times D} \overrightarrow{x} = \overrightarrow{0} $ 增广矩阵  $ [A \in \mathbb{B}] $ = [系数矩阵自由项]

2. 齐次

y: 独立方程、独立自变量个数

①  $ \gamma(A)=D $ 仅零解  $ \gamma(A)<D $ 无穷多解 (D-γ个线性无关解) D-γ: 自由未知量个数解空间的基

不带K ②基础解系①是 $ A X=0 $的解②线性无关③任一解均可由 $ S_{1} $与 $ D-Y $线性表示(一般证个数=D-Y)

③  $ Ax=0 $ 有非零解  $ \Leftrightarrow d_{lim} $ 相关  $ \Leftrightarrow r<D $

不是 $ S_{1}\sim D-V $的等价向量组（可能线性相关）

3. 非齐次

①  $ \gamma(A) \neq \gamma([A,b]) $ 无解  $ \gamma(A) = \gamma([A,b]) $  $ \left\{\begin{array}{l}=0 \\ <0\end{array}\right. $ 唯一解无穷多解

②设 $ S_{m}t $为 $ Ax=b $的解，则 $ \sum_{i=1}^{T}Ki_{i}S_{i} $为 $ Ax=b $的解 $ \Leftrightarrow\Sigma k=1 $（与 $ 7-k=-10-3 $一致）

4. 最简形式  $ \left[\begin{array}{ccc}(a-1)(a-2)&0\\1-a&a-1\end{array}\right]_{x}\rightarrow\left[\begin{array}{ccc}1-a&a-1\\0&(a-1)(a-2)\end{array}\right] $

## 二、公共解

1. 求解  $ [A]_{B}\vec{x}=[a]_{B} $ 纵向拼接

2 求出  $ k_{1}\overrightarrow{S_{1}}+\cdots+k_{n-r}\overrightarrow{S_{n-r}} $，代入 Bx=0 得  $ k_{1} $ 之间的关系，将此关系代入 Ax=0 的通解

3. 求出二者的解，令  $ k_{1}\overrightarrow{s_{1}}+\cdots+k_{D-y}\overrightarrow{s_{D-y}}=\lambda_{1}\overrightarrow{n_{1}}+\cdots+\lambda_{D-y}\overrightarrow{n_{D-y}} $，得  $ k_{i} $ (或  $ \lambda_{i} $) 之间的关系，代回通解.

## 三、同解

1. 同解  $ \Leftrightarrow $  $ \overrightarrow{S} $ 满足  $ Bx=0 $ 且  $ \overrightarrow{y} $ 满足  $ Ax=0 $  $ \Leftrightarrow $  $ \gamma(A)=\gamma(B) $ 且  $ \left\{\begin{array}{l}\frac{3}{5} 满足 Bx=0\\ 或 \gamma 满足 Ax=0\end{array}\right. $  $ \Leftrightarrow $  $ \gamma(A)=\gamma(B)=\gamma\left(\begin{array}{c}A\\ B\end{array}\right) $

2. 实矩阵A:  $ AX = O $ 与  $ A^{T}AX = O $ 同解 实对称阵A:  $ AX = O $ 与  $ A^{2}X = O $ 同解 P可逆:  $ \left\{\begin{array}{l}AX = O, PAX = O \\AX = O, PAX = PB\end{array}\right. $ 同解  $ Y(AB) = Y(B) \Leftrightarrow ABX = O $ 与  $ BX = O $ 同解

## 四、 $ A^{T}A $

 $ \alpha^{T}A^{T}A\alpha=0\Leftrightarrow(A\alpha)^{T}A\alpha=0\Leftrightarrow A\alpha=0\Leftrightarrow|A|=0 $ (设  $ \alpha\neq\overrightarrow{0} $)

# 方程组 -A

1. 设  $ A_{n \times n} $,  $ \overrightarrow{d_{n \times 1}} $, 若  $ Y\left(\frac{A}{a^{T}} \circ \frac{A}{b}\right) = Y(A) $, 则()

A.  $ Ax = d $ 必有无穷多解 B.  $ Ax = d $ 必有唯一解 C.  $ \left[\frac{A}{a^{T}} \circ \frac{A}{b}\right] \left[\frac{x}{y}\right] = \overrightarrow{0} $ 仅有零解 D.  $ \left[\frac{A}{a^{T}} \circ \frac{A}{b}\right] \left[\frac{x}{y}\right] = \overrightarrow{0} $ 必有非零解

解:  $ \gamma(A) \leq \gamma(A, \alpha) \leq \gamma\left(\frac{A}{a^{T}} \circ \frac{A}{b}\right) = \gamma(A) $，故  $ \gamma(A) = \gamma(A, \alpha) $，即  $ Ax = d $ 有解（但不知  $ \gamma(A) = n $ 还是  $ \gamma(A) < n $），A、B 均应为有可能。由  $ \gamma\left(\frac{A}{a^{T}} \circ \frac{A}{b}\right) = \gamma(A) \leq n < n+1 $，故  $ \alpha $ 有非零解

2.  $ A_{3 \times 3} $ 第一行是  $ [a, b, c] $， $ a, b, c $ 不全为 0， $ B = \begin{bmatrix} \frac{1}{2} & \frac{2}{4} \\ 3 & k \end{bmatrix} $ （ $ k $ 为常数）且  $ AB = 0 $，求  $ Ax = 0 $ 的通解

解： $ r(A) + r(B) \leq 3 $， $ r(A) \geq 1 $ ①  $ k \neq 9 $， $ r(B) = 2 \Rightarrow r(A) = 1 $，由  $ AB = 0 $ 知  $ \overrightarrow{x} = k_1 \left( \frac{1}{3} \right) + k_2 \left( \frac{3}{6} \right) $ ②  $ k = 9 $， $ r(B) = 1 \Rightarrow r(A) = 2 $ 或  $ 1 $

(i)  $ r(A) = 2 $， $ \overrightarrow{x} = k \left( \frac{1}{3} \right) $ (ii)  $ r(A) = 1 $， $ Ax = 0 \Leftrightarrow [a, b, c] \left[ \frac{x}{x_0} \right] = 0 $，故  $ \overrightarrow{x} = k_1 \left( \frac{3}{a^2} \right) + k_2 \left( \frac{c}{a^2} \right) $

3.(1996·三) 设  $ A = \begin{bmatrix} a_{1} & a_{2} & \cdots & a_{n} \\ a_{n}^{n-1} & a_{2}^{n-1} & \cdots & a_{n}^{n-1} \end{bmatrix}, \overrightarrow{x} = \begin{bmatrix} x_{1} \\ \vdots \\ x_{n} \end{bmatrix} $,  $ B = \begin{bmatrix} \vdots \\ \vdots \end{bmatrix} $,  $ a_{i} \neq a_{j} $ (if  $ i=1,2,\ldots n $), 则  $ A^{T}x = B $ 的解是

解:  $ D = \prod_{i \leq j \leq i \leq n}(a_{i} - a_{j}) \neq 0 $, 用克拉默,  $ x_{1} = \frac{D_{1}}{D} = 1 $,  $ x_{2} = \frac{\left| \begin{array}{c} 1 \\ 1 \end{array} \right| \cdots \left| \begin{array}{c} a_{n}^{n-1} \\ a_{n}^{n-1} \end{array} \right|}{D} = 0 $, … 故  $ \overrightarrow{x} = \left( \frac{1}{0} \right) $

4. (2004.一)  $ \left\{\begin{array}{l}(1+a)x_{1}+x_{2}+\cdots+x_{n}=0\\2x_{1}+(2+a)x_{1}+2x_{2}=0\\nx_{1}+nx_{2}+\cdots+(n+a)x_{n}=0\end{array}\right. $ (n≥2)，a为何值时有非零解，并求解

解： $ \left[\begin{array}{ccc}1+a&1&\cdots&1\\2&2+a&\cdots&2\\n&\cdots&\ddots&n+a\end{array}\right]\rightarrow\left[\begin{array}{ccc}1+a&1&\cdots&1\\-2a&a&\cdots&0\\-na&0&\cdots&a\end{array}\right] $ ① $ a=0,\overrightarrow{x}=k_{1}\left(\frac{1}{0}\right)+k_{1}\left(\frac{1}{0}\right)+k_{2}\left(\frac{1}{0}\right)+k_{3}\left(\frac{1}{0}\right) $ ② $ a\neq0 $，则 $ A\rightarrow\left[\begin{array}{ccc}1+a&1&\cdots&1\\-2&1&\cdots&0\\\vdots&0&\cdots&1\end{array}\right]\rightarrow\left[\begin{array}{ccc}a+\frac{n(n+1)}{2}&0&\cdots&0\\-2&1&\cdots&0\\-n&0&\cdots&1\end{array}\right] $ 则 $ a=-\frac{n(n+1)}{2},\quad\overrightarrow{x}=k\left(\frac{1}{n}\right) $

5.  $ A_{4 \times 5} $ 行向量线性无关，对  $ \overrightarrow{v} $,  $ A^{T} \overrightarrow{x} = \overrightarrow{v} $ 必有唯一解吗？

解:  $ \gamma(A)=4 $ 但  $ \gamma(A\cdot\overrightarrow{b}) $ 可能为5. 或者说  $ A^{T} $ 的列向量只有4个无关的5维向量, 无法张成  $ R^{5} $

6.(2002.四)四元齐次方程组(I)，(Ⅱ)的基础解系 $ \overrightarrow{a}_{1}=\left(\frac{3}{2}\right)\overrightarrow{a}_{1}^{2} $， $ \overrightarrow{b}_{1}=\left(\frac{2}{a_{1}^{2}}\right) $，求(I)、(Ⅱ)的非零公共解

解：设 $ \overrightarrow{r}=k_{1}\overrightarrow{a}_{1}+k_{2}\overrightarrow{a}_{2}=M\overrightarrow{p}_{1}+M\overrightarrow{p}_{2} $， $ A=\left[\alpha_{1},\alpha_{2},-\beta_{1},-\beta_{2}\right]\rightarrow\begin{bmatrix}10^{-a_{1}}-\frac{4}{a_{1}}\\0.5-3a+2a+2\\0.5a+5-4a-3\end{bmatrix}\xrightarrow{a=1}\begin{bmatrix}10^{-1}-4\\0.5-3a+2a+2\\0.5a+5-4a-3\end{bmatrix}\overrightarrow{r}=\lambda_{1}\left(\frac{1}{0}\right)+\lambda_{2}\left(\frac{4}{9}\right)=\left(\frac{\lambda_{1}+4\lambda_{2}}{\lambda_{1}+7\lambda_{2}}\right)

则 $ \overrightarrow{r}=(\lambda_{1}+4)\overrightarrow{a}_{1}+(\lambda_{1}+7)\lambda_{2}\overrightarrow{a}_{2}=\lambda_{1}\overrightarrow{p}_{1}+\lambda_{2}\overrightarrow{p}_{2}=\lambda_{1}\left(\frac{2}{1}\right)+\lambda_{2}\left(\frac{1}{4}\right) $ ( $ \lambda_{1} $， $ \lambda_{2} $，不全为0)

7.  $ A = \begin{bmatrix} \frac{1}{2} & \frac{1}{3} \\ 1 \end{bmatrix} $,  $ B = \begin{bmatrix} \frac{1}{4} & \frac{1}{2} & 0 \\ 0 & 0 & 1 \end{bmatrix} $. (1) A经列变换得到B，求AP=B(P可逆) (2) A是否可由行变换得到B

解：(1) $ (A,B)\rightarrow\begin{bmatrix}102-1-3\\0002-21\end{bmatrix}P=\begin{bmatrix}1-2k_{1}\\2+k_{1}\\k_{1}\end{bmatrix}\begin{bmatrix}-3-2k_{2}\\2+k_{2}\\k_{2}+k_{3}\\k_{3}\end{bmatrix} $

 $ 5k_{1}-3k_{2}+k_{3}\neq0 $ (2) ①  $ r[A]=3\neq r(A)=r(B)=2 $

故A、B行向量组不等价 ② QA=B,  $ A^{T}Q^{T}=B^{T} $，而 $ A^{T}Q^{T}=B^{T} $无解

8. 3阶矩阵A，3维非零列向量 $ \overrightarrow{b} $，则①若Ax=b有解，则 $ \left(\overrightarrow{a}^{T}\right)x=\left(1^{0}\right) $有解②∴无解③若 $ \left(\overrightarrow{a}^{T}\right)x=\left(1^{0}\right) $有解，则Ax=0有非零解

④“无解…只有零解”

解：①②  $ Y(A) = Y(A, b) $，则  $ Y(A^{\mathrm{T}}) = Y(\frac{A^{\mathrm{T}}}{b}) $，则  $ Y(\frac{A^{\mathrm{T}}}{b^{\mathrm{T}}}) $  $ Y(A^{\mathrm{T}}) = Y(A^{\mathrm{T}}) + 1 > Y(\frac{A^{\mathrm{T}}}{b^{\mathrm{T}}}) $ ③ 反证：若 Ax = 0 仅有 0 解，则  $ Y(A) = 3 $，故 Ax = b 有解，由①②知  $ \left(\frac{A^{\mathrm{T}}}{b^{\mathrm{T}}}\right)x = \left(\frac{1}{1}\right)^{\frac{1}{b^{\mathrm{T}}}} $ 无解 ④ 取  $ A = \left(\frac{0.00}{1.11}\right), b = \left(\frac{0}{1}\right) $ ②③

9.  $ \gamma(BA) < \gamma(AB) $ (3阶). 判断①  $ ABx = 0 $ 与  $ BAx = 0 $ 有非零公共解 ②  $ ABAx = 0 $ 与  $ BABx = 0 $ 有非零公共解

解: (1)  $ \gamma(AB) = \gamma(BA) + 1 $，因  $ \gamma(BA) = 2 $ 时  $ |BA| = 0 $， $ \gamma(AB) = 3 $ 时  $ |AB| \neq 0 $，矛盾。故  $ \gamma(BA) \leq 1 $， $ \gamma(AB) \leq 2 $，则  $ \gamma(\frac{AB}{BA}) \leq \gamma(AB) + \gamma(BA) \leq \gamma(AB) \leq \gamma(AB) + \gamma(BA) \leq \gamma(BA) + \gamma(BA) \leq 2 $，则①不一定。②一定 (2)  $ \gamma(AB) = \gamma(BA) + 2 $，同理  $ R $ 可能  $ \gamma(BA) = 0 $， $ \gamma(AB) = 2 $，即  $ \gamma(\frac{AB}{BA}) \leq 2 $， $ \gamma(\frac{AB}{BA}) \leq 0 $ 则①②均成立 (3)  $ \gamma(AB) = \gamma(BA) + 3 $ 该情况不成文

10.(18.数一)  $ A=\begin{pmatrix} \frac{1}{2} & \frac{2}{3} & \frac{a}{a} \end{pmatrix} $ 经初等列变换化为  $ B=\begin{pmatrix} \frac{1}{a} & \frac{2}{3} & \frac{a}{a} \\ \frac{1}{a} & \frac{2}{3} & \frac{a}{a} \\ \frac{1}{a} & \frac{2}{3} & \frac{a}{a} \end{pmatrix} $ (1) 求  $ a $ (2) 求  $ AP=B $ 的可逆  $ P $

解(1)(A,B) $ \rightarrow $ $ \begin{pmatrix}1&0&3a&3&3a-2&4\\0&1&-a&-1&-a&-1\\0&0&0&0&a-2&0\end{pmatrix} $ a=2 12 P= $ \begin{pmatrix}-6k_{1}+3&-6k_{2}+4&-6k_{3}+4\\2k_{1}-1&2k_{2}-1&2k_{3}-1\\k_{1}&k_{2}&k_{3}\end{pmatrix} $，由 $ \vert P\vert=k_{3}-k_{2} $知 $ k_{2}\neq k_{3} $

注：形如  $ A O = B $ 的式子，即使未说求出全部○，也要求出全部(解方程即可)

# 特征值

## 一、 $ \lambda $ 与  $ \overrightarrow{S} $

 $ (\lambda E-A)\vec{x}=0 $有非零解

1.  $ A\overrightarrow{\xi}=\lambda\overrightarrow{\xi}\iff|\lambda E-A|=0 $ 其中  $ |AE-A|=\lambda^{3}-(a_{11}+a_{22}+a_{33})\lambda^{2}+(A_{11}+A_{22}+A_{33})\lambda-|A| $

若 $ \vert aA+bE\vert=0 $，则 $ \lambda=-\frac{b}{a} $证： $ \vert bE-(-aA)\vert=(-a)^{n}\vert-\frac{b}{a}E-A\vert=0 $， $ \lambda=-\frac{b}{a} $与求解 $ a\lambda+b=0 $之值相等

 $ 2\lambda|A|=\lambda_{1}\cdots\lambda_{n} $.  $ \operatorname{tr}(A)=\lambda_{1}+\cdots+\lambda_{n} $

K阶主子式之和 = 任意 k 个特征值乘积之和

 $$ \because a_{1},a_{2}+a_{3},a_{4},a_{5}=a_{11}+a_{22}+a_{33}=|a_{32},a_{33}|+|a_{31},a_{33}|+|a_{4},a_{12}| $$ 

3.  $ \overrightarrow{s} $ ①  $ \lambda_{1} + \lambda_{2} \Rightarrow \overrightarrow{s}_{1}, \overrightarrow{s}_{2} $ 线性无关且  $ k_{1} \overrightarrow{s}_{1} + k_{2} \overrightarrow{s}_{2} $ 不是 A 的特征向量 ( $ k_{1}, k_{2} $ 均 \neq 0)

②  $ \lambda_{1}=\lambda_{2}\Rightarrow K_{1}\overrightarrow{S_{1}}+K_{2}\overrightarrow{S_{2}} $ 仍为  $ \lambda_{12} $ 对应的特征向量  $ (K_{1},K_{2} $ 不全为 0 $

说明：入只能与对应的特定子空间配对，将该空间上的向量放缩为入倍.

1个线性无关的弦张成直线，A只能在作用于此直线时才有入的效果.

2个线性无关的弦张成平面，A作用在此平面上的会有入的效果



<table border=1 style='margin: auto; word-wrap: break-word;'><tr><td style='text-align: center; word-wrap: break-word;'>4.</td><td style='text-align: center; word-wrap: break-word;'>A</td><td style='text-align: center; word-wrap: break-word;'>$  f(A) \quad A^\dagger \quad A^{*}  $</td><td style='text-align: center; word-wrap: break-word;'>$  P^\dagger A P  $</td><td style='text-align: center; word-wrap: break-word;'>$  A^\top  $</td><td style='text-align: center; word-wrap: break-word;'>$  P^\dagger A^{*} P  $</td></tr><tr><td style='text-align: center; word-wrap: break-word;'>若 $ \lambda $则</td><td style='text-align: center; word-wrap: break-word;'>$  f(\lambda) \quad \frac{1}{x} \quad \frac{|A|}{\lambda}  $</td><td style='text-align: center; word-wrap: break-word;'>$ \lambda $</td><td style='text-align: center; word-wrap: break-word;'>$ \lambda $</td><td style='text-align: center; word-wrap: break-word;'>$ \frac{|A|}{\lambda} $</td><td style='text-align: center; word-wrap: break-word;'></td></tr><tr><td style='text-align: center; word-wrap: break-word;'>$ \overrightarrow{m} $</td><td style='text-align: center; word-wrap: break-word;'>均为 $ \overrightarrow{m} $</td><td style='text-align: center; word-wrap: break-word;'>$ P^\dagger \overrightarrow{m} $</td><td style='text-align: center; word-wrap: break-word;'>未知</td><td style='text-align: center; word-wrap: break-word;'>$ P^\dagger \overrightarrow{m} $</td><td style='text-align: center; word-wrap: break-word;'></td></tr></table>

 $$ P^{-1}A^{*}P P^{-1}S=P^{-1}A\S=P^{1}\frac{A}{x}\S $$ 

5.  $ E_{n}:\lambda=1 $ (n重),  $ \overrightarrow{s} $ 为任意非零向量  $ D=\mathrm{diag}(d_{1}, \ldots, d_{n}):\lambda=d_{1}, \ldots, d_{n}, \overrightarrow{s}=\binom{1}{0}, \binom{0}{0}, \binom{0}{0} $

6.  $ f(A) = g(A) \Leftrightarrow f(A) - g(N) = 0 $ 证：由  $ A S = \lambda S $ 得  $ \left\{\begin{array}{l} f(A) S = f(N) \\ g(A) S = g(N) \end{array}\right. $ 相减得  $ [f(N) - g(N)] S = 0 $，由  $ S \neq 0 $ 得  $ f(N) - g(N) = 0 $

## 二、相似

1.  $ A \sim B $ 可逆P，使 $ P^{+}AP = B $ 相似⇒等价

2. 性质 相似变换的不变量是 各阶主子式之和

①  $ |A|=|B| $  $ \gamma(A)=\gamma(B) $  $ \operatorname{tr}(A)=\operatorname{tr}(B) $  $ \lambda_{A}=\lambda_{B} $  $ |\lambda E-A|=|\lambda E-B|\leq\lambda E-A\sim\lambda E-B $

A, B各项主子式之和分别相等

转化为 $ A-E\sim B-E $

注： $ A=[\cdot,1] $， $ B=[\cdot,1] $ 满足上述性质但不相似. 设 $ (A-E)P=P(B-E) $，容易得出P的第4列全为0，不可逆，矛盾

②若 $ A\sim B $，则 $ f(A)\sim f(B) $， $ A^{-1}\sim B^{-1} $， $ A^{*} \sim B^{*} $， $ A^{T} \sim B^{T} $， $ [A^{0}B]^{C} \sim [C^{0}D]^{0} $， $ AP \sim BP $

 $$ P^{t}A P P=B P $$ 

3. 相似对角化 可验算  $ t r(A) = \frac{n}{n+1} \lambda_{i} $ 特征向量定义式

①  $ P^{-1}AP = \Lambda = \text{diag}(\lambda_1, \ldots, \lambda_n) $ 变形： $ AP = P\Lambda $.  $ A = P\Lambda P^{-1} $,  $ A^k = P\Lambda^k P^{-1} $

② n个不同入  $ \Rightarrow $ A可相似对角化  $ \Leftrightarrow $ 有 n 个线性无关的  $ \overrightarrow{s} $

实对称  $ \Rightarrow $ 每个 k 重特征值都有 k 个线性无关的特征向量

③实对称矩阵

实对称  $ \left\{\begin{array}{l}\lambda_{1} + \lambda_{2} \Rightarrow \text{或} \bot \frac{\sqrt{2}}{2} \\ \lambda_{1} = \lambda_{2} \Rightarrow \left\{\begin{array}{l} \frac{\sqrt{2}}{2} \bot \frac{\sqrt{2}}{2} \\ \text{或线性无关} \end{array}\right. \end{array}\right. $ 一般  $ \left\{\begin{array}{l}\lambda_{1} + \lambda_{2} \Rightarrow \text{线性无关} \\ \lambda_{1} = \lambda_{2} \Rightarrow \left\{\begin{array}{l}\text{无关} \\ \text{或相关}\end{array}\right.\end{array}\right. $

是实数，是实向量

 $ A \subset B \Leftrightarrow \lambda $ 相同

一般矩阵不存在正交矩阵Q使 $ Q^{T}AQ=\Lambda $ 证：设 $ \left\{\begin{array}{l}A^{\prime}\neq A\\Q^{T}AQ=\Lambda\end{array}\right. $，则 $ A=Q\wedge Q^{T} $， $ A^{T}=Q\wedge^{T}Q^{T}=Q\wedge Q^{T}=A $，矛盾

#### 特征值

证明(1) A的 $ \lambda_{1}, \lambda_{2} (\lambda_{1} \neq \lambda_{2}) $对应的两个特征向量线性无关 (2) A的K个不同的入对应的S也线性无关

证：(1) 对  $ K_{1}\xi_{1} + K_{2}\xi_{2} = 0 $ 左乘 A:  $ K_{1}\lambda_{1}\xi_{1} + K_{2}\lambda_{2}\xi_{2} = 0 $，左乘  $ \lambda_{1} $:  $ K_{1}\lambda_{1}\xi_{1} + K_{2}\lambda_{2}\xi_{2} = 0 $，相减得  $ K_{2}(\lambda_{2} - \lambda_{1})\xi_{2} = 0 \Rightarrow K_{2} = 0 = K_{1} = 0 $

(2) 数归: K=1 成立设 K=1 成立证 K 成立: 对  $ \frac{k}{2}M_{1}\xi_{1} = 0 $ 左乘 A:  $ \sum_{i=1}^{k}M_{i}\lambda_{i}\xi_{i} = 0 $，左乘  $ \lambda_{k} $:  $ \sum_{i=1}^{k}M_{i}\lambda_{k}\xi_{i} = 0 $，相减得

 $ \sum_{i=1}^{k-1}M_{i}(\lambda_{i} - \lambda_{k})\xi_{i} = 0 $，由  $ \sum_{i=k-1}^{k}M_{i} = 0 $ 无关知  $ \mu_{i} = 0 $ ( $ i = 1, 2, \ldots, k-1 $)  $ \Rightarrow M_{k} = 0 \Rightarrow \mu_{i} = 0 $ ( $ i = 1, 2, \ldots, k $)

2.(请分解) 实对称  $ A $ 的  $ \lambda_{1n} $ 对应标准正交特征向量  $ \overrightarrow{s}_{1,n} $，则  $ A = \sum_{i=1}^{n} \lambda_{i} s_{i} \sum_{i}^{T} $

证： $ A = Q \wedge Q^{T} = [s_{1}, \ldots, s_{n}] \left[ \begin{array}{c} \lambda_{1} \\ \vdots \\ s_{n} \end{array} \right] \left[ \begin{array}{c} \sum_{i=1}^{T} \\ s_{1} \end{array} \right] = \lambda_{1} s_{1} s_{1}^{T} + \cdots + \lambda_{n} s_{n} s_{n}^{T} $

推论：对于正交特征向量  $ \overrightarrow{s}_{1,n} $， $ A = \sum_{i=1}^{n} \frac{\lambda_{i}}{s_{i}^{T} s_{i}} \sum_{i}^{T} s_{i} \sum_{i=1}^{T} \sum_{i=1}^{T} s_{i} s_{i} $

注：若  $ \lambda = -1, 1, 1, s_{1} = \left(\frac{0}{1}\right) $，则  $ \lambda_{A-1} = -2, 0, 0 $， $ A-E = \frac{\mu_{1}}{(s_{0}, s_{1})} \sum_{i=1}^{T} s_{i} \sum_{i=1}^{T} = \frac{-2}{2} \left(\frac{0}{1}\right)(0, 1) = -\left[\begin{array}{c} \frac{0}{1} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T} \frac{0}{1} \\ 0 \end{array} \right] \Rightarrow A = \left[\begin{array}{c} \frac{1}{0} \sum_{i=1}^{T

3. A的 $ \lambda=1,2,\ldots,n $.证明：AB和BA有相同的特征值且AB $ \sim $BA

解：A可逆，由 $ A^{+}(AB)A=BA\Rightarrow AB\sim BA=\lambda_{AB}=\lambda_{BA} $。或由 $ |\lambda E-AB|=|A(\lambda A^{+}-B)|=|A|\left(\lambda E-BA\right)\left|A^{-1}\right|=|\lambda E-BA| $，特征多项式相同 $ \Rightarrow $

 $ \lambda $相同 注：一般 $ AB\neq BA $，取 $ A=\begin{bmatrix}1&1\\ 1&1\end{bmatrix} $， $ B=\begin{bmatrix}1&1\\ 1&1\end{bmatrix} $， $ \gamma(AB)=0\neq1=\gamma(BA) $ (12-k---3-7) A可逆时就有 $ AB\sim BA $

 $ AB\neq BA $ 补：取 $ A=[\begin{matrix}1&1\\ 1&1\end{matrix}] $， $ B=[\begin{matrix}1&1\\ 1&1\end{matrix}] $更方便记忆

4. 证明：n阶实矩阵A, B，有AB与BA特征值相同

解: 令  $ P = \begin{pmatrix} E & 0 \\ A & E \end{pmatrix} $,  $ Q = \begin{pmatrix} E & \lambda B \\ A & E \end{pmatrix} $ 有  $ PQ = \begin{pmatrix} E & \lambda B \\ 0 & E \end{pmatrix} $,  $ QP = \begin{pmatrix} E - \lambda BA & \lambda B \\ 0 & E \end{pmatrix} $, 由  $ \vert PQ\vert = \vert QP\vert $ 知  $ \vert E - \lambda AB\vert = \vert E - \lambda BA\vert $

①  $ \lambda \neq 0 $ 时, 同除  $ \lambda^{n} $ 有  $ \left| \frac{1}{x} E - AB \right| = \left| \frac{1}{x} E - BA \right| $, 从而特征多项式相同, 即特征值相同

②  $ \lambda = 0 $ 时,  $ \vert AB - O E\vert = \vert AB\vert = \vert BA\vert = \vert BA - O E\vert $

5.(2022数一改)证明：A的属于不同特征值的特征向量正交是A可对角化的既不充分又不必要条件

解: 取  $ P = \left(\frac{1}{0.01}\right) $  $ N = (-1, 0) $ 有反例  $ A = P \cap P^{-1} = \left(\frac{1}{0.01}, \frac{1}{0.01}\right) $. 取  $ A = \left(\frac{1}{0.01}, \frac{1}{0.01}\right) $ 不可 ~ A 但其正交

注：实对称  $ \Rightarrow $ 不同入的红交

# 特征值-A

1.  $ A^{2}=A, B^{2}=B, A\neq0, B\neq0, AB=BA=0 $，证明：(1) O，1必是A，B的特征值 (2) 若对应  $ \lambda_{A}=1 $，则对应  $ \lambda_{B}=0 $

证：(1)  $ \left\{\begin{array}{l}(A-E)A=0 \Rightarrow |A-E|=0 \Rightarrow \lambda=1\\AB=0 \Rightarrow |A|=0 \Rightarrow \lambda=0\end{array}\right. $，B同理 (2)  $ A\leq-3 $，则  $ B\leq-BA\leq0 $

2. 三阶矩阵A，有 $ A^{2}=5A $且 $ \gamma(A)=2 $。证明：A必可相似对角化

证：①不妨设 $ \alpha_{1},\alpha_{2} $无关，由 $ A[\alpha_{1},\alpha_{2},\alpha_{3}]=5[\alpha_{1},\alpha_{2},\alpha_{3}] $知 $ \left\{\begin{array}{l}A\alpha_{1}=5\alpha_{1}\\A\alpha_{2}=5\alpha_{2}\end{array}\right. $又Ax=0必有非零解，则 $ \exists $3个无关的特征向量

② $ A(A-5E)=0\Rightarrow Y(A)+Y(A-5E)\leq3 $，又 $ Y(A)+Y(A-5E)\geq Y[A-(A-5E)]=3\Rightarrow Y(A-5E)=1\Rightarrow\lambda=5 $对应2个无关

3 设  $  A = (\alpha_1, \alpha_2, \alpha_3)  $ 且每行元素和为 1，已知  $  \alpha_1 - \alpha_2 = \overrightarrow{0}  $， $  \alpha_1 + \alpha_3 = \overrightarrow{0}  $，求  $  f(x)  $ A X 对应的标准型（正交变换 x = 0）

解：未说实对称，故不可认为  $  \lambda = 0  $ 对应  $  (\frac{1}{2})  $ 与  $  (\frac{1}{6})  $ 与  $  \lambda = 1  $ 对应  $  (1)  $。事实上，由  $  \alpha_1 + \alpha_2 + \alpha_3 = (1)  $ 和  $  A = (1, 1, 1)  $，于是由  $  \begin{bmatrix} 1 & 0 \\ 0 & -1 \end{bmatrix}  $ 知  $  \lambda = -1, 0, 2  $

4. 三阶实矩阵 A， $ a_{ij}=2A_{ij} $ 且  $ a_{ii}=\frac{1}{2} $，证明：A 有一个  $ \lambda=\frac{1}{2} $

解： $ A^{*}=\frac{1}{2}A^{T} $ 知  $ |A|=0 $ 或  $ \frac{1}{2} $ 又由  $ \left|A\right|=\frac{1}{2}a_{11}^{2}+\frac{1}{2}a_{12}^{2}+\frac{1}{2}a_{13}^{2}>0 $ 知  $ \left|A\right|=\frac{1}{8} $，即  $ \frac{1}{8}+\frac{1}{2}a_{12}^{2}+\frac{1}{2}a_{13}^{2}=\frac{1}{8} $，故  $ a_{12}, a_{13}=0 $ 同理  $ a_{21}=a_{31}=0 $，显然 A 形如  $ \left(\frac{1}{6}, \frac{0}{6}, \frac{0}{6}\right) $，故有  $ \lambda=\frac{1}{2} $

# 二次型

## 一、二次型

1.  $ f(\overrightarrow{x})=\overrightarrow{x}^{\top}A\overrightarrow{x} $，A为实对称矩阵.  $ r=p+q $

2. 标准形:  $ d_{1}X_{1}^{2}+\cdots+d_{m}X_{m}^{2} $ 规范形:  $ d=0,\pm1 $. x=cy时标准形不唯一, x=qy时标准形唯一

## 二、合同  $ A^{T}=A $ 时相似实合同

1.  $ A \simeq B $ 可逆 C, 使  $ C^{T} A C = B $ 注:  $ \overrightarrow{x} = C \overrightarrow{y} $, 有  $ f = (C \overrightarrow{y})^{\top} A C \overrightarrow{y} = \overrightarrow{y}^{\top} C^{\top} A C \overrightarrow{y} $

2. 性质 A, B 表征在不同参照系，对下同一事物的不同形态

 $ r(A)=r(B) $  $ P_{A}=P_{B}, q_{A}=q_{B} $

### 3. 对任何实对称 A，必存在

可逆矩阵 C，使  $ C^{T}AC = \Lambda $ （配方法 x = cy） C 一般不为  $ \frac{2}{3} $，d 一般不为  $ \lambda $ 平方项与混合项一次性配完；  $ \left\{\begin{array}{l} x_{1} = y_{1} + y_{2} \\ x_{2} = y_{1} - y_{3} \end{array}\right. $

正交矩阵 Q，使  $ Q^{T}AQ=\Lambda $ (正交变换 x=qy)  $ \Lambda $ 一般不为 0 土(规范形)

4.  $ f \supseteq q \Leftrightarrow A \supseteq B \Leftrightarrow A, B $ 有相同的  $ P, q $

## 三、正定 实对称 +  $ \alpha, \lambda > 0 $ 前提 不可忘记证明

1. 对  $ \forall x \neq 0 $ 均有  $ x^{n} A x > 0 $ 此时令  $ f = a (a > 0) $，其几何图形封闭

2. 必要条件 主对角元素 > 0  $ |A| > 0 $

3. 充要条件

隐含  $ P = y = n $ 由  $ A \supseteq E $，则  $ A + C^{T} + C^{-1} $，故令  $ D = C^{-1} $ 即可，其实就是可逆线性变换时  $ \left\{\begin{array}{l} y_{1} = a_{1}x_{1} + b_{1}x_{1} + c_{1}x_{1} \\ \cdots \end{array}\right. $ 的系数矩阵  $ \left\{\begin{array}{l} a_{1}b_{1}c_{1} \\ \cdots \end{array}\right. $

f 正定  $ \Leftrightarrow $  $ P = n $  $ \Leftrightarrow $ 可逆  $ D, A = D^{T}D $  $ \Leftrightarrow $  $ A \simeq E $  $ \Leftrightarrow $  $ \lambda $ 均 > 0  $ \Leftrightarrow $ 全部顺序主子式均大于 0

4. 子式：任意k行k列 主子式：行列标号相同 顺序主子式：前k行前k行

 $ A_{n \times D} $ 一共有 $ C_{n}^{k}C_{D}^{k} $个子式

所选出的行列式的主对角线的元素的行列下标相等

5.  $ A^{T} = -A $ 时，对  $ \forall x $，均有  $ x^{T}Ax = 0 $

## 四、二次型的秩

1. 若  $ f(x) $ 可化为  $ a x^{2} + b x_{1} y_{2} + c x_{2}^{2} $，令  $ \Delta = b^{2} - 4ac $，则  $ \left\{\begin{array}{l}\Delta > 0 \\ \Delta = 0, a > 0 \\ \Delta < 0, a > 0\end{array}\right. $  $ P = 1, q = 0 $

2.  $ f(x) $ 可化为  $ (a_{1}x_{1}+\cdots+a_{n}x_{n})(b_{1}x_{1}+\cdots+b_{n}x_{n})\Leftrightarrow $  $ \left\{\begin{array}{l} \alpha, \beta \text{线性相关: } r=1 \\ \alpha, \beta \text{线性无关: } r=2, p=q=1 \end{array}\right. $，其中  $ \alpha, \beta $ 为非零向量

简证:  $ \Rightarrow $ ①  $ \overrightarrow{a} = k\overrightarrow{b} $ 时  $ f = k(a_{1}x_{1}+\cdots+a_{n}x_{n})^{2} $，设  $ a_{1} \neq 0 $，则  $ \left\{\begin{array}{l} a_{1}x_{1}+\cdots+a_{n}x_{n}=y_{n} \\ x_{1}^{2}=y_{2} \\ x_{n}^{2}=y_{n} \end{array}\right. $ 有  $ f = kx_{1}^{2} $，故  $ r(t)=1 $

②无关时: 设  $ \left\{\begin{array}{l} a_{1}a_{1} \\ a_{2}a_{2} \\ a_{3}a_{3} \end{array}\right. $ 令  $ \left\{\begin{array}{l} a_{1}x_{1}+\cdots+a_{n}x_{n}=y_{1} \\ b_{1}x_{1}+\cdots+b_{n}x_{n}=y_{2} \\ x_{1}=x_{1}, x_{2}=x_{2} \end{array}\right. $ 得  $ f=x_{1}y_{2}=z_{2}^{2}-z_{2}^{2} $，故  $ p=q=1 $

例： $ 2x_{1}x_{2}-2x_{2}x_{3}=2x_{1}x_{2}-x_{2}x_{3}=x^{2} $

例： $ 2x_{1}x_{2}-2x_{1}x_{3}=2x_{1}(x_{2}-x_{3})\leq z_{1}^{2}-z_{2}^{2} $

#### 二次型

1. 证明：(1)  $ x^{T}Ax = \frac{n}{2-1} \frac{n}{j-1} a_{ij} x_{i} x_{j} $ (2)  $ x^{T}A^{-1}x = \frac{n}{r-1} \frac{n}{j-1} \frac{A}{|A|} x_{i} x_{j} $

证：(1) 右边  $ a_{11}x_{1}^{2} + a_{12}x_{1}x_{2} + \cdots + a_{1n}x_{1}x_{n} = x_{1}(a_{11}x_{1} + a_{12}x_{2} + \cdots + a_{1n}x_{n}) + x_{2}(a_{21}x_{1} + \cdots + a_{2n}x_{n}) + \cdots + x_{n}(a_{n1}x_{1} + \cdots + a_{nn}x_{n}) $

 $ \left[a_{n1}x_{1} + a_{12}x_{2} + \cdots + a_{nn}x_{n}\right] = x_{1}x_{1}x_{2} \cdots x_{n} $

 $ \left[a_{n1}x_{1} + \cdots + a_{nn}x_{n}\right] = \left[\frac{a_{11}}{a_{n1}} \cdots \frac{a_{12}}{a_{n1}} \cdots \frac{a_{1n}}{a_{n1}}\right]\left[\frac{x_{1}}{x_{n}}\right] $

① 提  $ x_{1}, x_{2}, \ldots, x_{n} $ ② 下的写成矩阵 X 向量的形式

(2) 右边  $ \frac{1}{|A|} \frac{n}{k-1} \left(A_{11} x_{1} x_{1} + A_{12} x_{1} x_{2} + \cdots + A_{1n} x_{1} x_{n}\right) = \frac{1}{|A|} \frac{n}{k-1} \left[A_{11} x_{1} x_{1}, A_{12} x_{1} x_{2}, \ldots, A_{1n} x_{1} x_{n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{|A|} \left(A_{11} \frac{n}{k-1} x_{1} [A_{12} \ldots A_{n}] \right)\left[\frac{x_{1}}{x_{n}}\right] $

 $ \left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{|A|} \left[A_{11} x_{1} x_{1}, A_{12} x_{1} x_{2}, \ldots, A_{1n} x_{1} x_{n}\right] = \frac{1}{|A|} \left[A_{11} x_{1} x_{1}, A_{12} x_{1} x_{2}, \ldots, A_{1n} x_{1} x_{n}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} x_{1} x_{1}, A_{12} x_{1} x_{2}, \ldots, A_{1n} x_{1} x_{n}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} x_{1} x_{1}, A_{12} x_{1} x_{2}, \ldots, A_{1n} x_{1} x_{n}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} x_{1} x_{1}, A_{12} x_{1} x_{2}, \ldots, A_{1n} x_{1} x_{n}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} x_{1} x_{1}, A_{12} x_{1} x_{2}, \ldots, A_{1n} x_{1} x_{n}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A_{n2} \cdots A_{n n}\right]\left[\frac{x_{1}}{x_{n}}\right] = \frac{1}{(A)} \left[A_{11} \cdots A_{1n} \cdots A_{n1} \cdots A_{n2} \cdots A

2. A, B为n阶实对称阵，证明或举反例(1)  $ A \sim B \Rightarrow A \simeq B $ (2)  $ A \simeq B \Rightarrow A \sim B $

证: (1)  $ A \sim B \Rightarrow \lambda_{A} = \lambda_{B} \Rightarrow Q_{1}^{T} A Q_{1} = \Lambda = Q_{2}^{T} A Q_{2} $ 而又  $ Q = Q_{1} Q_{2}^{-1} $，则  $ Q^{T} A Q = B $ (2)  $ A = [1, 2] $,  $ B = [1, 1] $,  $ C = [1, \frac{1}{2}] $ 有  $ C^{T} A C = B $ 但显然不相似

注：实对称 $ A, B $有 $ A \sim B \Leftrightarrow A, B $有相同的特征多项式或特征值

3. A为n阶正定阵，证明：∃正定阵B使 $ A=B^{2} $ (矩阵的开方)

证： $ Q^{T}AQ=\left[\lambda_{n}\right]=\lambda $（其中 $ \lambda_{i}>0 $），则 $ A=Q\wedge Q^{-1}=Q\left[\sqrt{\Delta_{1}}-\sqrt{\Delta_{n}}\right]Q^{-1}Q\left[\sqrt{\Delta_{1}}-\sqrt{\Delta_{n}}\right]Q^{-1} $

4. A为n阶实对称阵，证明或举反例(1)若 $ |A|<0 $，则 $ \overrightarrow{a} $使 $ f=\overrightarrow{f}A\overrightarrow{f}<0 $ (2)若 $ |A|>0 $，则 $ \overrightarrow{a} $，使 $ f=\overrightarrow{f}A\overrightarrow{f}>0 $

证：(1) 奇数个  $ \lambda < 0 $ ，不妨取  $ \lambda_{1} < 0 $ ，则  $ \overrightarrow{s}_{1} \cdot A \overrightarrow{s}_{1} = \overrightarrow{s}_{1} (\lambda \overrightarrow{s}_{1}) = \lambda \overrightarrow{s}_{1} \overrightarrow{s}_{1} < 0 $ (2) 偶数个  $ \lambda < 0 $ ，故不成立

5.(瑞利高Rayleigh quotient)标准瑞利商 $ R(A,x)=\frac{x^{\prime}A x}{x^{\prime \times}x} $，广义瑞利商 $ R(A,B,x)=\frac{x^{\prime}A x}{x^{\prime}B x} $，其中A实对称，B实对称正定证明： $ (1)\max_{x\neq0}R(A,x)=\lambda\max(A,\min_{x\neq0}R(A,x))=\lambda\max(A,x) $  $ (2)\max_{x\neq0}R(A,B,x)=\lambda\max(A,B),\min_{x\neq0}R(A,B,x)=\lambda\min(A,B) $其中 $ \lambda(A) $为A的特征值， $ \lambda(A,B) $为广义特征值 $ A x=\lambda B x $，相当于 $ \lambda(A,B)=\lambda(B^{-}A) $

证明：(1) 由  $ A = Q \wedge Q^{T} $ 与  $ x \cdot QY $ 得  $ R(A, x) = \frac{x^{T}Q \wedge Q^{T}x}{y^{T}Q^{T}QY} = \frac{y^{T}A Y}{y^{T}Y} = \frac{x_{1}^{T} \lambda_{1} y_{1}}{x_{2}^{T} y_{2}^{T}} $ (权重为  $ \frac{y_{1}}{y_{2}^{T}} \lambda_{2} $ 且和为1)，因此  $ \lambda_{\min}(A) \leq R(A, X) \leq \max(A) $

(2) 考虑  $ 5, t \cdot x^{T} B X = 1 $，构造  $ F(x, \lambda) = x^{T} A X - \lambda (x^{T} B X - 1) $，则  $ \frac{\partial F}{\partial x} = 2 A X - 2 \lambda B X = 0 $ 故  $ A X = \lambda B X $

存在冗余（等比缩放不影响  $ R(A, B, X) $ 的值）

①处的严谨证明如下：首先注意到  $ R(A, B, K) = R(A, B, X) $ (R度不变性)，又对  $ \forall x \neq 0 $，若令  $ y = \sqrt{x^{T} B X} $，则有  $ R(A, B, X) = \left( \frac{x}{\sqrt{x^{T} B X}} \right)^{T} A \left( \frac{x}{\sqrt{x^{T} B X}} \right) = y^{T} A Y $，且  $ y^{T} B Y = \frac{x^{T} B X}{x^{T} B X} = 1 $，因此  $ \min_{x \neq 0} \min_{x^{T} B X} \frac{x^{T} A X}{x^{T} B X} \leftrightarrow \min_{x \neq 0} \min_{y^{T} B Y} y^{T} A Y $

②对B进行Cholesky分解： $ B = LL^{T} $（可逆L为下三角矩阵），定义 $ Z = L^{T}X $，则 $ X = (L^{T})^{\perp}Z $，代入得 $ R(A, B, X) = \frac{Z^{T}L^{-1}A(L^{-1})Z}{Z^{T}L^{T}L^{T}L^{T}Z} = \frac{Z^{T}C Z}{Z^{T}Z} $ 其中 $ C = L^{-1}A(L^{-1})^{T} $，原命题等价为 $ \lambda_{max}(C) $，注意到 $ C Z = \mathbb{R}^{2} $时 $ L^{-1}A(L^{-1})^{T}L^{T}X = \lambda_{max}^{T}X \Rightarrow A X = \lambda_{max}L^{T}X = \lambda_{B}X $

②:事实上  $ \lambda_{\max}(C) \Leftrightarrow \lambda_{\max}(B^{-1}A) \Leftrightarrow \lambda_{\max}(B^{-\frac{1}{2}}AB^{-\frac{1}{2}}) $ 因为  $ B^{-\frac{1}{2}}(B^{-2}AB^{-\frac{1}{2}})B^{\frac{1}{2}} = B^{-1}A $ 知  $ B^{-\frac{1}{2}}AB^{-\frac{1}{2}} \sim B^{1}A $

③由B对称正定，则 $ B=(\frac{1}{2})^{2} $，令 $ z=B^{\frac{1}{2}}x $，则 $ R(A,B,x)=\frac{z^{T}(B^{-2})^{T}A(B^{-2}z)}{z^{T}(B^{-2})^{T}BB^{-2}z}=\frac{z^{T}B^{-\frac{1}{2}}AB^{-2}z}{z^{T}B^{-\frac{1}{2}}B^{2}z}=\frac{z^{T}B^{2}AB^{-2}z}{z^{T}z} $

 $ B^{\frac{1}{2}} $唯一且对称正定 $ (B^{\frac{1}{2}}=a\Lambda^{\frac{1}{2}}a^{T}) $  $ (B^{\frac{1}{2}})^{T}=B^{\frac{1}{2}} $

6. A、B正定，AB=BA. 证明：AB正定

证： $ (AB)^{\mathrm{T}}=B^{\mathrm{T}}A^{\mathrm{T}}=BA=AB $ (对称) 对  $ AB\overrightarrow{d}=\lambda\overrightarrow{d} $ ( $ \overrightarrow{d}\neq\overrightarrow{0} $) 有  $ B\overrightarrow{d}=\lambda A^{\dagger}\overrightarrow{d} $， $ \alpha^{T}B d=\lambda d^{T}A^{\dagger}\alpha $ 由  $ \alpha^{T}B d>0 $， $ \alpha^{T}A^{-1}d>0 $  $ \left(\frac{1}{10}\right)_{\Delta B}>0 $

7. 证明：可逆实矩阵可分解为正交矩阵  $ \times $ 正定矩阵  $ (A = CB) $

解由 $ \lambda_{A}\neq0 $知 $ \lambda_{A}TA>0 $于是 $ \overrightarrow{A A}=Q\wedge Q^{T} $，取 $ B=Q\wedge\frac{1}{2}Q^{T} $有 $ B^{2}=A^{T}A $，代入A=CB得 $ B^{2}=B^{T}C^{T}CB $，由 $ C^{T}C=E $与 $ B^{T}B $知C存在，即取 $ C=AB^{-1} $

8.  $ A = d d^{T} + \beta\beta^{T} $， $ d, \beta $ 为正交三维单位列向量，证明： $ A + A^{*} $ 既正交又正定

证：不难知道  $ \lambda_{A}=1,1,0 $ 对应  $ \alpha,\beta,\gamma $  $ (\gamma=\alpha\times\beta $ 与  $ \alpha,\beta $ 正交 $ 于是正交 Q 使  $ Q^{T}AQ=(1,0) $， $ Q^{T}A^{*}Q=(0,1) $，则  $ Q^{-1}(A+A^{*})Q=E $  $ A+A^{*}=QEQ^{-1}=E $ 显然正交且正定

# 二次型-A

1.  $ A=\begin{bmatrix}a_{1}&a_{1}&a_{1}\\a_{1}&a_{1}+a_{3}&a_{1}+a_{2}\\a_{1}&a_{1}+a_{2}&a_{1}+a_{3}\end{bmatrix}, B=\begin{bmatrix}a_{1}\\a_{2}\\a_{3}\end{bmatrix} $，可逆C使 $ C^{T}AC=B $，求C.

解:  $ f(A)=x^{2}AX=2ax_{1}x_{2}+2ax_{1}x_{3}+2(a_{1}+a_{2})x_{3}+2ax_{1}x_{3}x_{2}+2ax_{1}x_{2}x_{3} $

 $ a_{1}x_{1}^{2}+(a_{1}+a_{2})x_{2}^{2}+(a_{1}+a_{2}+a_{3})x_{3}^{2}=a_{1}(x_{1}+x_{2}+x_{3})^{2}+a_{2}(x_{2}+x_{3})^{2}+a_{3}x_{3}^{2} $

 $ \therefore \sum_{y_{3}=x_{3}}^{}x_{3}=x_{2}+x_{3} $

则  $ f=a_{1}x_{1}^{2}+a_{2}x_{2}^{2}+a_{3}x_{3}^{2} $，其中  $ x=c $

显然  $ C=\left[\begin{array}{c}1 \\ 1 \\ 1\end{array}\right]^{-1}=\left[\begin{array}{c}1 \\ 1 \\ 1\end{array}\right] $

② 注意到  $ \left[\begin{array}{c}1 \\ 1 \\ 1\end{array}\right]\left[\begin{array}{c}1 \\ 1 \\ 1\end{array}\right] $  $ A=\left[\begin{array}{c}a_{1}a_{2}a_{3}\\a_{2}a_{3}\\a_{3}\end{array}\right] $ 与  $ \left[\begin{array}{c}a_{1}a_{2}a_{3}\\a_{2}a_{3}\\a_{3}\end{array}\right]\left[\begin{array}{c}1 \\ 1 \\ 1\end{array}\right]\left[\begin{array}{c}1 \\ 1 \\ 1\end{array}\right]=B $，则  $ C=\left[\begin{array}{c}1 \\ 1 \\ 1\end{array}\right]\left[\begin{array}{c}1 \\ 1 \\ 1\end{array}\right]=\left[\begin{array}{c}1 \\ 1 \\ 1\end{array}\right] $

2.  $ A = \begin{pmatrix} -1 \\ 1 \end{pmatrix} $, 非零  $ \overrightarrow{a} $, 则  $ \begin{pmatrix} A + a d a^{T} & \alpha \\ a^{T} & 1 \end{pmatrix} $ x 的规范形为

解  $ \left(\frac{E}{0}, -\alpha\right)\left(\frac{A+a k^{T}}{a^{T}}, \alpha\right)\left(\frac{E}{-\alpha^{T}}, \frac{\overrightarrow{0}}{1}\right)=\left(\frac{A}{\overrightarrow{0}}, \frac{\overrightarrow{0}}{1}\right) $ 则  $ f\leq\left(\frac{-1}{0}, \frac{1}{0}\right) $.  $ (\lambda-1)(k^{2}-2)=0 $

 $ x^{2}+y^{2}-y^{2} $

3. 实矩阵 $ A \subseteq B $，证明或证为(1)A的行向量组与B的行向量组等价 (2) 若 $ B \sim \Lambda $，则 $ A \sim \Lambda $

解：(1)  $ A = (0, 0)^{0} $,  $ B = (1, 1) $, P=1, q=0 (但A与B等价) (2)  $ A = (1, 1) $, 取 $ P = (0, 2) $,  $ \dot{B} = P^{T} A P = (1, 1)^{2} $, 则 $ B \sim \Lambda $ 但 $ A \neq \Lambda $ × (B实对称时成立)

4. n阶方阵A (1) A的全部顺序主式为正  $ \Rightarrow $ A正定 (2)  $ A \sim \Lambda $ 则  $ A \approx \Lambda $

解：(1)需对称.反例 $ [0,1]\times(2) $需对称，反例 $ [1,4]\sim[1,1] $

5(2024·数一) 实矩阵  $ A = \begin{pmatrix} a + 1 & a \\ a & a \end{pmatrix} $. 若对  $ \forall $ 实向量  $ \overrightarrow{a} = \begin{pmatrix} x_{1} \\ x_{2} \end{pmatrix} $,  $ \overrightarrow{b} = \begin{pmatrix} x_{1} \\ x_{2} \end{pmatrix} $,  $ (\alpha^{T} A \beta)^{2} \leq \alpha^{T} A d \cdot \beta^{T} A \beta $ 都成立，则  $ \alpha $ 的取值范围是

解：①由左边非负，故右侧两数同号.(i) A半正定 $ \left\{\begin{array}{l}a+1\geq0\\a\geq0\end{array}\right. $， $ a\geq0 $ (ii) A半负定，则-A半正定 $ \left\{\begin{array}{l}-a-1\geq0\\-a\geq0\end{array}\right. $无解.故必要条件为A半正定 $ (a\geq0) $. 下证充分性：A半正定时，记 $ \sqrt{A}=C $，则 $ \alpha^{T}A\beta=\alpha^{T}C^{2}\beta=\alpha^{T}C^{T}C\beta=(Cd,CB) $， $ \alpha^{T}Ad=(Cd,Cd)=\|Cd\|^{2} $ 由柯西不等式 $ \left|(\alpha,\beta)\right|\leq\|d\|\|B\| $和 $ \left|(Cd)^{T}CB\right)^{2}\leq\|Cd\|^{2}\|C\beta\|^{2} $

②  $ P = (1^0) + P^\top A P = (1^0) a $ 记  $ P x = d $,  $ P x = \beta $. 则  $ r_1 = (\omega_1) + r_2 = (\frac{\beta}{2})_1 $ 求为任意向量.  $ d^\top A B = r_1^2 P^\top A P x_1 = \omega_1 z_1 + a \omega_2 z_2 $,  $ d^\top A d = \omega_1^2 + a \omega_2^2 $,  $ \beta^T A \beta = z_1^2 + a z_2^2 $ 故  $ (w_1, z_1 + a \omega_1, z_2)^2 = (\omega_1^2 + a \omega_2^2)(z_1^2 + a z_2^2) $ 即  $ a (\omega_1 z_1 - \omega_2 z_1) \geq 0 $, 即  $ a \geq 0 $

③  $ a^\top A \beta d^\top A \beta - a^\top A \alpha \beta^\top A \beta \leq 0 $, 即  $ a^\top A (\beta d^\top - \alpha \beta^\top) A \beta \leq 0 $, 由  $ \beta d^\top - \alpha \beta^\top = (x_1, x_2, x_3, x_4) \geq 0 $ 记  $ x_1, x_2, x_3, x_4 $ 记为  $ \left(\frac{x_1}{x_2}, \frac{x_2}{x_3}, \frac{x_3}{x_4}\right) $ 和  $ A (\beta d^\top - \alpha \beta^\top) A = (a \beta, a \beta) $

于是  $ a^\top A (\beta d^\top - \alpha \beta^\top) A \beta = a x_1 x_2 x_3 - a x_1 x_2 x_3 = -a^2 \beta^2 $ 故  $ a \geq 0 $

6.  $ f = (a_1 x_1 + a_2 x_2 + a_3 x_3) \left[ (a_1 - b_1) x_1 + (a_2 - b_2) x_2 + (a_3 - b_3) x_3 \right] $ 且单位向量  $ \alpha = \left( \frac{a}{a_0}, \beta \right) $ 正交. 证明： $ f = 1 $ 可逆线性变换为双曲柱面

证： $ f = x^{\gamma} \alpha^{T} x - \beta^{T} x = x^{\gamma} \alpha \alpha^{T} \alpha \beta^{T} x $ 故  $ A = \alpha \alpha^{T} - \frac{\alpha \beta^{T} + \beta \alpha^{T}}{2} $ 令  $ \overrightarrow{\gamma} = \frac{\overrightarrow{\alpha} \times \overrightarrow{\beta}}{\overrightarrow{\gamma} + \overrightarrow{\beta} + \overrightarrow{\alpha}} $ 400 与  $ \overrightarrow{\alpha}, \overrightarrow{\beta} $ 正交， $ A \overrightarrow{\gamma} = O(\lambda = 0) $ 由  $ \alpha, \beta, \gamma $ 是规范正交，故对  $ \beta $，有  $ \beta + k \beta + k \gamma $ 由实对数知  $ \gamma^{\gamma} \leq 0 $ 故  $ k \geq 0 $ 设  $ S = k \alpha + \beta $ ( $ \alpha + k \beta $ 同理) 由  $ A(k \alpha + \beta) = (k - \frac{1}{2}) \alpha - \frac{k}{2} \beta $ 知  $ \lambda = \frac{k}{2} $， $ k - \frac{1}{2} = -\frac{k}{2} $，即  $ k = \pm \sqrt{2} $， $ \lambda = \frac{1}{2} \neq \frac{\sqrt{2}}{2} $ 故  $ \lambda_A = 0 $， $ \frac{16\sqrt{2}}{2}, \frac{1-\sqrt{2}}{2} $

# 随机事件

## 一. 事件

相容:  $ AB \neq \phi $

1. 互斥 AB =  $ \phi \Rightarrow P(AB) = 0 $ 互不相容 exclusive, in compatible  $ P(A \cup B) = P(A) + P(B) $

对立  $ AB=\phi $ 且  $ A \cup B=\varnothing \Leftrightarrow B=\overline{A} $ 互逆 complementary

逆 A为A的逆对立事件.

 $$ A-B=A-A B=A\overline{B} $$ 

完备事件组  $ \bigcup_{i=1}^{n}A_{i}=\varnothing, A_{i}A_{j}=\varnothing $ 不重不漏，全集分解

ACB: B包含A, A包含于B

### 2. 分配律  $ A \cap (B-C) = (A \cap B) - (A \cap C) $

 $ A=\phi\xrightarrow{P}(A)=0 $  $ A=\Lambda\xrightarrow{P}(A)=1 $

若 $ A\subset B $，则 $ P(B-A)=P(B)-P(A)\Rightarrow P(B)\geq P(A) $

加法  $ P(A \cup B) = P(A) + P(B) - P(AB) = P(A\overline{B}) + P(AB) + P(B\overline{A}) $ 减法  $ P(A - B) = P(A) - P(AB) = P(A\overline{B}) $

条件概率  $ P(B|A)=\frac{P(AB)}{P(A)} $ 概率的性质对  $ P(A) $ 都适用，就像视 |A不存在，如  $ P((B-c)|A)=P(B|A)-P(BC|A) $

乘法  $ P(AB)=P(A)P(B|A) $  $ P(A_{1}\cdots A_{n})=P(A_{1})P(A_{2}|A_{1})\cdots P(A_{n}|A_{1}\cdots A_{n-1}) $

全根无率  $ B = U^{n} A_{i} B $  $ P(B) = \sum_{i=1}^{n} P(A_{i}) P(B|A_{i}) $ (加权平均)

贝叶斯  $ P(A|B)=\frac{P(AB)}{P(B)}=\frac{P(B|A)P(A)}{P(A)P(B|A)} $

用分类问题去理解，设为特征，C为类别， $ P(C|X)=\frac{P(X|C)P(C)}{P(X)} $

### 3. 古典概型

1.  $ A_{n}^{m} = \frac{n!}{(n-m)!} $  $ C_{n}^{m} = \frac{A_{n}^{m}}{m!} = \frac{n!}{m!(n-m)!} $

2. 随机占位 任意:  $ N^{n} $ 每位置至多一个:  $ A_{N}^{n} $

3. 随机抽样 有放回:  $ N^{n} $ 无放回:  $ A_{N}^{n} $ 一次性任取:  $ C_{N}^{n} $

有序(有先后) 无序

若P的分子、分母都不在意顺序时，可一起从 $ A_{n}^{n} $转为 $ C_{n}^{n} $比如无放回取2球至少1白=任取2球至少一白

## 二、独立

### 1. 事件的独立性

①独立： $ P(AB)=P(A)P(B) $ 相互有利 $ P(AB)>P(A)P(B)\Rightarrow P(B|A)>P(B) $ 相互抑止 $ P(B|A)<P(B) $

② 相互独立  $ \Rightarrow $ 两两独立，前者还需  $ P(A_{1}A_{2}A_{3}) = P(A_{1})P(A_{2})P(A_{3}) $ n 个事件相互独立需  $ C_{n}^{2} + C_{n}^{3} + \cdots + C_{n}^{n} = 2^{n} - n - 1 $ 等式成立.

③ A, B独立  $ \Leftrightarrow $ A,  $ \overline{B} $  $ \Leftrightarrow $  $ \overline{A} $, B  $ \Leftrightarrow $  $ \overline{A} $,  $ \overline{B} $独立

④ 作不含相同事件的运算 所得的新事件组仍独立，如 A 与 BC-D

⑤  $ P(A)=0 $ 或  $ P(A)=1 $，则 A 与任意 B 独立. 常数与任意 B 独立.

 $ 0 \leq P(AB) \leq P(A) = 0 \rightarrow 0 \leq P(B \setminus A) \leq P(A) = 0 $, 则  $ P(B) - P(AB) = 0 $

⑥ A, B有利⇔  $ \overline{A} $,  $ \overline{B} $有利 ⇔ A,  $ \overline{B} $抑止 ⇔  $ \overline{A} $, B抑止

若 $ 0<P(A)<1 $，则 $ \left\{\begin{array}{l} 独立\Leftrightarrow P(B|\overline{A})=P(B|A) \\ 有利\Leftrightarrow P(B|A)>P(B|\overline{A}) \end{array}\right.\Leftrightarrow P(B|A)+P(B|\overline{A})=1 $  $ (2|P-T_{1}) $

若 $ 0<P(A),P(B)<1 $，则 $ \left\{\begin{array}{l}AB=\phi\Rightarrow 抑止 \\ A\leq B\Rightarrow 有利\end{array}\right. $ A、B互斥且独立 $ \Leftrightarrow P(A)=0 $或 $ P(B)=0 $

### 2. 随机变量的独立性

① X, Y独立  $ F(x, y) = F_{x}(x) F_{y}(y) \Leftrightarrow f(x, y) = f_{x}(x) f_{y}(y) $

 $ x_{1}, \ldots, x_{n} $ 独立  $ F(x_{1}, x_{2}, \ldots, x_{n}) = F_{1}(x_{1}) \cdots F_{n}(x_{n}) \Leftrightarrow f(x_{1}, \ldots, x_{n}) = f(x_{1}) \cdots f_{n}(x_{n}) $ （与1-2不同，这里仅需一个式子）

 $ (X_{1}, X_{2}) $ 与  $ (Y_{1}, Y_{2}) $ 独立  $ F(X_{1}, \ldots, X_{n}, Y_{1}, \ldots Y_{m}) = F_{1}(X_{1}, \ldots, X_{n}) F_{2}(Y_{1}, \ldots, Y_{m}) $

② $ x_{1} $... $ x_{n} $独立 $ \Rightarrow $任意K个X也独立类似向量组，整体无关部分无关  $ x_{1}+100 $时左边= $ F(x_{2},x_{3}) $，右边= $ F(x_{1})F(x_{3}) $

 $ x_{1}Y $独立  $ \Rightarrow $  $ f(x|y)=f(x) $  $ (f_{1}(x)>0) $

 $ x_{1} $... $ x_{n} $独立 $ \Rightarrow g_{1}(x_{1}) $... $ g_{n}(x_{n}) $独立 同1-4，施以不含相同随机变量的连续函数仍相互独立

③独立=>不相关 若 $ (x,y)\sim $二维正态，则XY独立 $ \Leftrightarrow $不相关 若 $ \left\{\begin{array}{l}x\sim B(1,p)\\y\sim B(1,p)\end{array}\right. $，则XY独立 $ \Leftrightarrow $不相关 P=P，即可证

④判不独立：①相关⇒不独立 ②取 $ x_{0}, y_{0} $使 $ P(x \leq x_{0}) \cap (y \leq y_{0}) \neq P(x \leq x_{0}, y \leq y_{0}) $，常有ACB或BCA或AB= $ \phi $

⑤定义在矩形区域内的 $ f(x,y) $，有X,Y独立 $ \Leftrightarrow f(x,y) $可分离变量 $ \Leftrightarrow $∃可积函数 $ g(x,h(y)) $使 $ f(x,y)=g(x)h(y) $

#### 随机事件

1. 证日明:  $ P(AB) = P(A)P(B) \Leftrightarrow P(B|A) = P(B) = P(B|\overline{A}) \Leftrightarrow P(B|\overline{A}) + P(B|A) = 1 \Leftrightarrow P(A|B) + P(\overline{A}|\overline{B}) = 1 $  $ (o < P(A), P(B) < 1) $

证: ①处: 由  $ \frac{P(AB)}{P(A)} = \frac{P(B) - P(AB)}{1 - P(A)} $ 展开 ②由  $ P(\overline{B}|A) = P(B|W) $ 可化为①式 ③由  $ P(\overline{A}|\overline{B}) = P(A|\overline{B}) $ 可化为①式下一行

# 随机事件-A

1. 从5双不同的鞋子中任取4只，求取得4只鞋子中至少有2只配成一双的概率.

解：①  $ P = 1 - \frac{C_{5}^{4} \cdot 2^{4}}{C_{10}^{4}} = \frac{13}{21} $ ②  $ \frac{C_{5}^{1} \cdot C_{4}^{2} \cdot 2^{2} + C_{5}^{2}}{C_{10}^{4}} = \frac{13}{21} $ ③  $ \frac{C_{5}^{1} \cdot (C_{8}^{2} - C_{4}^{1}) + C_{5}^{2}}{C_{10}^{4}} = \frac{13}{21} $

2. 在0至9这+个整数中任取四个，能排成一个四位偶数的概率.

解：用个位偶千位任意减去个位偶千位0： $ P=\frac{C_{5}^{1}A_{9}^{3}-C_{4}^{1}A_{8}^{2}}{A_{10}^{4}}=\frac{41}{90} $

一、二、三班总人数，献血人数为16，12，23，2，20.随机抽一个班，所以该班任取2人.第一次抽到的走

南水血学生的概率 (2)若第二次抽到未南水血学生，求第一次抽到已南水血学生的概率.

解：(1)  $ P = \frac{1}{3} \left( \frac{3}{4} + \frac{3}{5} + \frac{4}{5} \right) = \frac{43}{60} $ (2) ①  $ P(= \frac{1}{3} \left( \frac{1}{4} + \frac{2}{5} + \frac{1}{5} \right) = \frac{17}{60} $，则  $ P(- \frac{1}{25} | 2) = \frac{\frac{1}{3} \cdot \frac{4}{5}}{60} = \frac{15}{5} $， $ P_{2} = \frac{24}{5} $ 同理  $ \left( \frac{24}{5} + \frac{12}{5} \right) $

 $ q = \frac{15}{51} \cdot \frac{12}{15} + \frac{24}{51} \cdot \frac{15}{24} + \frac{12}{51} \cdot \frac{20}{24} = \frac{37}{51} $ ②  $ P(- \frac{1}{25} | -25) = \frac{12}{16} \times \frac{4}{15} = \frac{1}{5} $， $ P_{2} = \frac{1}{3} \left( \frac{1}{5} + \frac{4}{5} + \frac{1}{6} \right) = \frac{37}{51} $

注：本题不可用  $ \frac{1}{3} (\frac{12}{15} + \frac{15}{24} + \frac{20}{24}) $，因为二未这一信息影响了三个班的概率，若记  $ P(- \frac{1}{25} | 2) = P(B_1 | A) $，则  $ P(C | A) = \frac{3}{k+1} P(C | A, B_2) P(B_1 | A) $，其中  $ P(B_2 | A) \neq \frac{1}{3} $。②中则将二未这一信息放入“因”中，因而仍为  $ \frac{1}{3} $。

但①中班级均为变化的量，①将二未作为“果”来乘班级的“因”，用班级的后验来求一未。②将班级作为“果”，此时无信息，所以概率为  $ \frac{1}{3} $ (与①不同) 王式安错误在于认为条件在随机抽一个班之后(不影响班的概率)

4.  $ AB = \overline{A B} $, 则( ) A.  $ A U B = \phi $ B.  $ A U B = \pi $ C.  $ A U B = A $ D.  $ A U B = B $ 结论

解由 $ \left\{\begin{array}{l}AB\cup A\overline{B}=A\\\overline{AB}\cup A\overline{B}=\overline{B}\end{array}\right. $与 $ AB=\overline{A B} $知 $ A=\overline{B}\Leftrightarrow A,B $对立 B ②由 $ \left\{\begin{array}{l}AB\cap\overline{A B}=AB\cap AB=AB\\\overline{A B}\cap\overline{A B}=\overline{A B}\cap\overline{A B}=\overline{A B}\end{array}\right. $与 $ AB\cap\overline{A B}=\phi $知 $ \left\{\begin{array}{l}AB=\phi\\\overline{A B}=\overline{A B}=\pi\end{array}\right.\Rightarrow A=\overline{B} $ ③由 $ A\cap AB=A\cap\overline{A B}=\phi $知 $ AB=\phi\Rightarrow\overline{A B}=\phi $

5.(1990.三)从0~9中任取3个不同的数字，求：(1)P(不含0和5) (2)P(不含0或5) (3)P(含0不含5)

解：(1)  $ P = \frac{C_{8}^{3}}{C_{10}^{3}} = \frac{7}{15} $ (2)  $ P = 1 - \frac{C_{8}^{1}}{C_{10}^{3}} = \frac{14}{15} $ (3)  $ P = \frac{C_{8}^{2}}{C_{10}^{3}} = \frac{7}{30} $

注：考查P: 含0，Q: 含5. 则  $ 7(P\Lambda Q)=7PV7Q $， $ 7(PVQ)=7P\Lambda_{7}Q $。故不含0和 $ 5\Leftrightarrow $ 不含0或不含5，不含0或 $ 5\Leftrightarrow $ 不含0且不含5

6. 长为1的线段上任取两个点，求分成的三段能构成一个三角形的概率

解:①注意到最长边 $ L_{M}<\frac{1}{2} $即可,故 $ P=C_{2}^{1}\cdot\int_{0}^{\frac{1}{2}}(\frac{1}{2}-x)dx=\frac{1}{4} $ 划线处可取点2: $ C_{2}^{1}\cdot(\frac{1}{2}-x) $

②基本事件  $ \left\{\begin{array}{l}0<x<1\\0<y<1\\0<-x-y<1\end{array}\right. $，构成三角形  $ \left\{\begin{array}{l}x+y>1-x-y\\x+1-x-y>y\\y+1-y>x\end{array}\right\} $  $ \left\{\begin{array}{l}0<x,y<1\\1<x+y<1\end{array}\right. $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//26615fd0-a8ac-4646-a8b0-88fb0b7af924/markdown_0/imgs/img_in_image_box_619_1219_741_1355.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A51Z%2F-1%2F%2Fdac1fe05091fc6be2feda34c74755761ac462df9d92dfbd5ec5cb9ed95c7e268" alt="Image" width="10%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//26615fd0-a8ac-4646-a8b0-88fb0b7af924/markdown_0/imgs/img_in_image_box_619_1219_741_1355.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A51Z%2F-1%2F%2Fdac1fe05091fc6be2feda34c74755761ac462df9d92dfbd5ec5cb9ed95c7e268" alt="Image" width="10%" />

 $ x \xrightarrow{\frac{1}{2}} \frac{1}{2} $

点1

</div>


</div>


 $$ P(\text{阴影})=\frac{\frac{1}{8}}{\frac{1}{2}}=\frac{1}{4} $$ 

7. 等腰Rt $ \triangle ABC $中(C为直角顶点)(1)点M在边AB上(2)过C在 $ \angle ACB $内部作射线CM交AB于M，求P(AM>AC)

解：(1) 取AD=AC，则M在BD上， $ P=\frac{\sqrt{2}-1}{\sqrt{2}}=1-\frac{\sqrt{2}}{2} $

(2) 取 AD = AC，则 M 在 BD 上， $ P = \frac{\angle DCB}{\angle ACB} = \frac{90^{\circ} - 67.5^{\circ}}{90^{\circ}} = \frac{1}{4} $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//26615fd0-a8ac-4646-a8b0-88fb0b7af924/markdown_1/imgs/img_in_image_box_761_246_897_352.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A53Z%2F-1%2F%2F58be054299fc29ce7c2237e68d76c5d6e00b3a325eeb39022ece0c3a33ba5b2e" alt="Image" width="11%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//26615fd0-a8ac-4646-a8b0-88fb0b7af924/markdown_1/imgs/img_in_image_box_761_246_897_352.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A53Z%2F-1%2F%2F58be054299fc29ce7c2237e68d76c5d6e00b3a325eeb39022ece0c3a33ba5b2e" alt="Image" width="11%" />

A  $ \triangleleft $ B

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//26615fd0-a8ac-4646-a8b0-88fb0b7af924/markdown_1/imgs/img_in_image_box_900_245_1036_340.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A53Z%2F-1%2F%2F5b8cf825369b535e61ab14505fc8584ce42d2208f30f7e95258e237b6bb8bb1a" alt="Image" width="11%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//26615fd0-a8ac-4646-a8b0-88fb0b7af924/markdown_1/imgs/img_in_image_box_900_245_1036_340.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A53Z%2F-1%2F%2F5b8cf825369b535e61ab14505fc8584ce42d2208f30f7e95258e237b6bb8bb1a" alt="Image" width="11%" />

C
A D M B

</div>


</div>


注：①中是先找点后得线，基本事件为线段，②中是先找线再得点，基本事件为角因为三等分角与三等分边对应的点不是同一个，故概率不同.

8. 证明： $ \overline{(A-B)U(B-C)}=\overline{AB}UBC $

证左边 =  $ \overline{AB} \cap \overline{BC} = (\overline{A} \cup B) \cap (\overline{B} \cup C) = (\overline{A} \cap \overline{B}) \cup (\overline{A} \cup B) \cap C $ =  $ \overline{AB} \cup \overline{AC} \cup BC = \overline{AB} \cup (\overline{A} \overline{B} \cup \overline{C}) \cup BC = \overline{AB} \cup BC $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//26615fd0-a8ac-4646-a8b0-88fb0b7af924/markdown_1/imgs/img_in_image_box_176_555_260_614.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A53Z%2F-1%2F%2F427b6e8d687849c07b3b8806e1a600ba3934734b15af58b94b0529e9fbbf6c58" alt="Image" width="7%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//26615fd0-a8ac-4646-a8b0-88fb0b7af924/markdown_1/imgs/img_in_image_box_176_555_260_614.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A09%3A53Z%2F-1%2F%2F427b6e8d687849c07b3b8806e1a600ba3934734b15af58b94b0529e9fbbf6c58" alt="Image" width="7%" />

Q

</div>


</div>


9. 一盒2红白，二盒一半红一半白。从两盒各任取一球放在一起，再任取一球，求P（第一盒取出是红球|该球为红球）

解： $ P=\frac{1}{2}\times\frac{2}{3}+\frac{1}{2}\times\frac{1}{2}=\frac{7}{12} $  $ P(-\text{红}(红))=\frac{P(-\text{红且红})}{P_{红}}=\frac{1\cdot P(-\text{红}=红)+\frac{1}{2}\cdot P(-\text{红}=白)}{12}=\frac{1\cdot\frac{1}{3}+\frac{1}{2}\cdot\frac{1}{3}}{\frac{1}{12}}=\frac{\frac{1}{2}}{\frac{1}{12}}=\frac{6}{7} $

注：①还可拆成 $ P(红)=0 $， $ P(-白=白)+\frac{1}{2}P(-白=红)+\frac{1}{2}P(-红=白)+1\cdot P(-红=红)=0-\frac{1}{6}+\frac{1}{2}\cdot\frac{1}{6}+\frac{1}{2}\cdot\frac{1}{3}+1\cdot\frac{1}{3}=\frac{7}{12} $

0.  $ \alpha $ 白 $ \beta $ 黑，不放回取  $ a+b $ 个，恰有  $ a $ 白  $ b $ 黑的概率  $ (a \leq a, b \leq \beta) $

解  $ P = \frac{C_{a}^{a} C_{B}^{B}}{C_{a}^{a + B}} $ 注：有放回时  $ P = C_{a + b}^{a} \left( \frac{\alpha}{\alpha + \beta} \right)^{a} \left( \frac{\beta}{\alpha + \beta} \right)^{b} $

11. 两盒火柴各N根，每次任取一盒用一根，当一盒用完时，另一盒还有 $ R(R \leq N) $根的概率

解：等价于第N次成功前恰失败N-R次， $ P = C_{2}^{1} \cdot \left( C_{N-1+N-R}^{N-1} \left( \frac{1}{2} \right)^{N-1} \cdot \left( \frac{1}{2} \right)^{N-1} \cdot \frac{1}{2} \right) = C_{2N-R-1}^{N-1} \left( \frac{1}{2} \right)^{2N-R-1} $

选一盒之前成功N-1次，失败N-R次

12.  $ x \sim B(n, p) $，求成功次数是奇数的概率

解：$\left\{\begin{array}{l}P(奇)+P(偶)=\frac{n}{k}=0 \\ P(偶)-P(\frac{n}{k})=\frac{n}{k}=0\end{array}\right.\quad C_{n}^{k}P^{k}(1-p)^{n-k}=(p+q)^{n}=1$

故 $P(奇)=\frac{1-(1-2p)^{n}}{2}$

13. 从  $ 1 \sim 9 $ 中可重复取 n 个数字，求其乘积能被 10 整除的概率

解: 记B: 至少一个偶(2,4,6,8). C: 至少一个5

 $ =1-\left(\frac{5}{9}\right)^{n}-\left(\frac{8}{9}\right)^{n}+\left(\frac{4}{9}\right)^{n}=1+\frac{4^{n}-5^{n}-8^{n}}{9^{n}} $

 $$ A=B C,P(A)=1-P(\overline{A})=1-P(\overline{B}\cup\overline{C})=1-P(\overline{B})-P(\overline{C})+P(\overline{B}\overline{C}) $$ 

14. 每回胜者得1分，甲胜 $ \alpha $，乙胜 $ \beta $， $ (d+\beta=1) $，有一人比对方多2分时获胜。求甲获胜的概率。

解: 记  $ P_{1} $ 为甲企领先乙 i 分时获胜的概率, 有  $ \left\{\begin{array}{l} P_{2}=1 \\ P_{2}=0 \end{array}\right. $ 且  $ P_{1}=d P_{1 H}+\beta P_{1 H}(i=0,t) $ 即  $ \left\{\begin{array}{l} P_{1}=\alpha+\beta P_{1} \\ P_{0}=\alpha P_{1}+\beta P_{1} \\ P_{1}=\alpha P_{0}+0 \end{array}\right. $ 解得  $ P_{0}=\frac{\alpha^{2}}{1-2x B} $

 $$ \frac{a^{2}}{1-2a\beta} $$ 

②两回视为一轮 比赛只可能在偶数回结束，只有3种情况  $ \left\{\begin{array}{l} 甲: \alpha,  AB \\ 乙: \beta,  折 \\  甲: 2\alpha,  乙: 2\alpha\beta\end{array}\right. $ 复原，故  $ P = \alpha^{2} + 1 + \beta^{2} + (2\alpha\beta)P $ 或者甲在2n回获胜，则2n-2回是各赢一回，2n-1~2n均为甲赢， $ P(2n) = 2^{n-1} \alpha^{m} \beta^{n-1} = \alpha^2 (2\alpha\beta)^{n-1} = \frac{\alpha^2}{1-2\alpha\beta} $

③赌徒破产将分差平移2，相当于Y=0时破产，Y=4时获胜，对于 $ 0<i<N $有 $ P_{i}=\alpha P_{i+1}+\beta P_{i+1} $，即 $ \alpha P_{i+1}-P_{i}+\beta P_{i+1}=1 $设 $ P_{i}=r^{2} $有 $ \alpha\cdot r^{2}-r^{2}+\beta r^{2}=0 $，即特征方程 $ d\gamma^{2}-r+\beta=0 $得 $ \alpha^{2}\neq\beta $时 $ r=1 $或 $ \frac{\beta}{d} $，故 $ P_{i}=A+B(\frac{\beta}{d})^{2} $代入 $ P_{0}=0 $， $ P_{N}=1 $得 $ A=\frac{1}{1-(\frac{\beta}{d})^{2}} $， $ B=-A $，故 $ P_{i}=\frac{1-(\frac{\beta}{d})^{2}}{1-(\frac{\beta}{d})^{2}} $，当 $ i=2,N=4 $时 $ P_{2}=\frac{1-(\frac{\beta}{d})^{2}}{1-(\frac{\beta}{d})^{2}}=\frac{1}{1+(\frac{\beta}{d})^{2}}=\frac{d^{2}}{d^{2}+\beta^{2}}=\frac{d^{2}}{1-2\alpha\beta} $

② $ d=\beta $时，重根 $ r=1 $， $ P_{i}=A+B\cdot i=\frac{1}{N}\cdot i $， $ P_{2}=\frac{1}{2} $，满足 $ R=\frac{d^{2}}{1-2\alpha\beta} $

# 随机变量

## 一、F, f (维)

1. 分布函数  $ F(x) = P\{X \leq X\} $，记为  $ X \sim F(X) $

单调不减 → 后连续，因此  $ F(x) $ 为分段函数时，区间一般为左闭右右

充要满足：①  $ \forall x_{1} < x_{2} $，有  $ F(x_{1}) \leq F(x_{2}) $ ②  $ \lim_{x \to x_{0}^{+}} F(x) = F(x_{0} + \theta) = F(x_{0}) $ ③  $ F(-\infty) = 0 $,  $ F(-\infty) = 1 $

 $ P\{a < x \leq b\} = F(b) - F(a) $ 若非左开闭，应用  $ \lim_{x \to x_{0}^{-}} f(x) $ 代替，如  $ P\{a < x < b\} = F(b - \theta) - F(a) $

比如  $ F(x) $ 是左连续，不是分布函数

2. 根无率密度  $  F(x) = \int_{-\infty}^{x} f(t) dt  $

满足：①  $ f(x) \geq 0 $ ②  $ \int_{0}^{+\infty} f(x) dx = 1 $ 比如  $ \sqrt{f(x) + f(x)} < \frac{f(x) + f(x)}{2} (f, f, f) $ 可知  $ \int_{0}^{+\infty} \sqrt{f(x) + f(x)} < 1 $ 不是概率密度

## 二、F、f(多维)

1. 分布函数  $  F(x_{1}, \ldots, x_{n}) = P\{X_{1} \leq x_{1}, \ldots, x_{n} \leq x_{n}\}  $，记为  $ (x_{1}, \ldots, x_{n}) \sim F(x_{1}, \ldots, x_{n}) $

满足：①关于x,y单调不减 ②关于x,y右连续 ③ $ F(-x,y)=F(x,-x)=F(-x,-x)=0 $,  $ F(x+x,0)=1 $

 $$ P\left\{\chi_{1}\leq X\leq\chi_{2}, \gamma_{1}\leq Y\leq Y_{2}\right\}=F\left(\chi_{2},y_{2}\right)-F\left(\chi_{1},y_{2}\right)-F\left(\chi_{2},y_{1}\right)+F\left(\chi_{1},y_{1}\right)\geq0\quad(相同下标为+，不同为-) $$ 

注： $ P(x > a, y > b) = 1 - F_{x}(a) - F_{y}(b) + F(a, b) $

2. 边缘分布  $ F_{x}(x) = F(x, +\infty) = \int_{-\infty}^{x} f_{x}(x) dx = \int_{-\infty}^{x} dx \int_{-\infty}^{+\infty} f(x, y) dy $

3. 根无率密度  $ F(x,y)=\int_{-\infty}^{y}dy\int_{-\infty}^{x}f(x,y)dx $ 若  $ f(x,y) $ 在点  $ (x,y) $ 处连续，则  $ \frac{\partial^{2}F(x,y)}{\partial x\partial y}=f(x,y) $

4. 边缘根无率密度  $ f_{x}(x)=\int_{-\infty}^{+\infty}f(x,y)dy $ (曲面面积)

理解为 $ x=x $

5. 条件概率密度  $ f_{Y1X}(y|x)=\frac{f(x,y)}{f_{X}(x)} $ ( $ f_{X}(x)>0 $) 条件 =  $ \frac{平均值}{边缘} $. 新定义域可能为原区域去掉边界(分母=0)

条件分布  $ F_{Y1X}(y|x)=\int_{-\infty}^{y}f(y|x)dy=\int_{-\infty}^{y}\frac{f(x,y)}{f(x)}dy=\lim_{\varepsilon\to0^{+}}\frac{p(y\leq x,x-\varepsilon\leq x\leq x+\varepsilon)}{p(x-\varepsilon\leq x\leq x+\varepsilon)} $

理想气体  $ x=x_{0} $ 时  $ Y\leq y $

## 三、常见分布

 $$ P M F/P D F $$ 

EX DX

伯努利  $ x \sim B(1, p) $

 $$ P(x=1)=P,P(x=0)=1-P(0<P<1) $$ 

P  $ P(rP) $

二项  $ x \sim B(n, p) $

 $$ P(x=k)=C_{n}^{k}P^{k}(1-P)^{n-k} $$ 

np np(rp)

泊松  $ x \sim P(\lambda) $

 $$ P(x=k)=\frac{\lambda^{k}}{k!}e^{-\lambda} $$ 

 $ x $

 $ x $

几何  $ x \sim a(p) $

 $$ P(x=k)=(1-P)^{k-1}P $$ 

 $$ \frac{1}{P}\frac{1-P}{P^{2}} $$ 

超几何  $ X \sim H(n, N, M) $

 $$ P(x=k)=\frac{C_{n}^{k}C_{n-m}^{n}}{C_{n}^{m}} $$ 

 $$ \frac{n M}{N} $$ 

 $$ \frac{n M(N-M)(N-n)}{N^{2}(N-1)} $$ 

均匀  $ x \sim u(a, b) $

 $$ f(x)=\frac{1}{b-a}(a<x<b)F(x)=\frac{x-a}{b-a}(a<x<b)\frac{a+b}{2}\frac{(b-a)^{2}}{12} $$ 

指数  $ x \sim E(\lambda) $

 $$ f(x)=e^{-2x}(x>0),f(x)=1-e^{-2x}(x\geq0) $$ 

 $$ \frac{1}{\lambda} $$ 

正态  $ X \sim N(\mu, \sigma^{2}) $

 $$ f(x)=\frac{1}{\sqrt{2\pi}\sigma}e^{-\frac{(x-\mu)^{2}}{2\sigma^{2}}} $$ 

 $$ \mu $$ 

 $$ \mathcal{O}^{2} $$ 

 $$ f(x)=\frac{x}{\sigma^{2}}e^{-\frac{x^{2}}{2\sigma^{2}}}(x>0) $$ 

瑞利

 $$ \sqrt{\frac{\pi}{2}}\sigma $$ 

 $$ (2-\frac{\pi}{2})\sigma^{2} $$ 

二维均匀

 $$ f(x,y)=\frac{1}{S_{D}} $$ 

二维正态

 $$ f(x,y)=\frac{1}{2\pi\sigma_{1}\sigma_{2}\sqrt{1-p^{2}}}\exp\left\{-\frac{1}{2(1-p)^{2}}\left[\left(\frac{x-\mu_{1}}{\sigma_{1}}\right)^{2}-2p\left(\frac{x-\mu_{1}}{\sigma_{1}}\right)\left(\frac{y-\mu_{2}}{\sigma_{2}}\right)+\left(\frac{y-\mu_{2}}{\sigma_{2}}\right)^{2}\right]\right\} $$ 

1.  $ B(n,p) $  $ \left\{\begin{array}{l} n>0, p<0.1, np\leq10 \text{时 } B(n,p) \approx P(n), 即 } C_{n}^{k}P^{k}(1-p)^{n-k} \approx \frac{\lambda^{k}}{k!} e^{-\lambda} \lambda=np \\ p<0.1, np\geq10 \text{时 } P(a<x<b) \approx \Phi\left(\frac{b-EX}{\sqrt{0.x}}\right) - \Phi\left(\frac{a-EX}{\sqrt{0.x}}\right) \end{array}\right. $

 $ \sum_{k=0}^{n}C_{n}^{k}P^{k}(H)^{n+k} $ 为二项式 $ (P+Q)^{n} $ 的展开式  $ k=\left[(n+1)P\right] $ 取得 max

### 2. P(N) 稀有事件发生的次数

 $ \sum_{k=0}^{\infty}\frac{\lambda^{k}}{k!}=e^{\lambda} $

3.  $ a(p) $ 首次出现即停止时的次数  $ P(x > n) = \sum_{k=n+1}^{\infty} (1-p)^{k-1} P = \frac{P(1-p)^n}{1-1-p} = (1-p)^n $

无记忆性  $ P(x > a + n | x > a) = P(x > n) = (1 - P)^{n} $  $ P(x = a + n | x > a) = P(x = n) = P(1 - P)^{n-1} $

#####  $ H(n,N,M) $

4. N个产品中M个不合格，不放回抽n次所得不合格个数

 $$ n\ll N\text{时}H(n,N,M)\approx B(n,P)P=\frac{M}{N} $$ 

5.  $ E\alpha $ 无记忆性  $ P(x \geq a + t \mid x \geq a) = P(x \geq t) = e^{-\lambda t} $  $ P(x < a + t \mid x > a) = P(x < t) = 1 - e^{-\lambda t} $

6.  $ N(\mu, \sigma^{2}) $  $ f(x)_{\max} = f(M) = \frac{1}{\sqrt{2\pi}\sigma} $ 拐点  $ (M \pm \sigma, \frac{1}{\sqrt{2\pi}\sigma} e^{-\frac{1}{2}}) $

 $ \Phi(-x) = 1 - \Phi(x) $  $ P(|x| < a) = 2\Phi(a) - 1 $ （事实上任意偶函数均满足此结论）

 $$ \Sigma_{1-d}=-\Sigma_{d}P(x>\Sigma_{1-d})=1-P(x>\Sigma_{1})=P(x>-\Sigma_{d}) $$ 

 $$ 7.N(\mu_{1},\mu_{2};\sigma_{1},\sigma_{2};\rho) $$ 

①多元正态  $ f(\overrightarrow{x})=\frac{\exp\left[-\frac{1}{2}(\overrightarrow{x}-\overrightarrow{m})^{\prime}\overrightarrow{z}^{\prime}(\overrightarrow{x}-\overrightarrow{m})\right]}{(2\pi)^{\frac{3}{2}}|\overrightarrow{z}|^{\frac{1}{2}}} $，exp化马式距离为 similarity，分母为归一化.

当  $ D=2 $ 时  $ \overrightarrow{x}=\left(\overrightarrow{y}\right)^{\prime},\overrightarrow{y}=\left(\overrightarrow{y}\right)^{\prime\prime} $  $ \overrightarrow{z}=\left[\overrightarrow{p}\overrightarrow{a}\overrightarrow{a}\cdot\overrightarrow{a}\overrightarrow{a}\right] $，有  $ |\overrightarrow{z}|=(\overrightarrow{p})^{2}\overrightarrow{a}^{2}\overrightarrow{a}^{2} $ 与  $ \overrightarrow{z}^{-1}=\frac{1}{1-p^{2}}\left[\frac{\overrightarrow{a}^{2}}{\overrightarrow{a}\overrightarrow{a}}\cdot\frac{\overrightarrow{p}}{\overrightarrow{a}^{2}}\right] $，则  $ f(x,y)=\frac{1}{2\pi\cdot\sqrt{1-p^{2}}\overrightarrow{\sigma}\cdot\overrightarrow{a}}\exp\left\{-\frac{1}{2}\cdot\frac{1}{1-p^{2}}\left[\frac{1}{\overrightarrow{a}^{2}}(x-M_{1})^{2}-\frac{2\overrightarrow{p}}{\overrightarrow{a}\overrightarrow{a}}(x-M_{1})(y-M_{2})+\frac{1}{\overrightarrow{a}^{2}}(y-M_{2})^{2}\right]\right\} $

②若 $ (X,Y)\sim N(\mu_{1},\mu_{2};\sigma_{1}^{2},\sigma_{2}^{2};P) $

 $ (k_{1,2} $不全为0 $

① $ X\sim N(\mu_{1},\sigma_{1}^{2}),Y\sim N(\mu_{2},\sigma_{2}^{2}) $

 $ k_{1}X+k_{2}Y\sim N(k_{1}M_{1}+k_{2}M_{2},k_{1}^{2}\sigma_{1}^{2}+2k_{1}k_{2}\sigma_{1}\sigma_{2}P+k_{2}^{2}\sigma_{2}^{2}) $

②  $ x, y $ 独立  $ \Leftrightarrow $ 不相关  $ \Leftrightarrow p = 0 $

③  $ Z_{1}=a_{1}x+a_{2}Y, Z_{2}=b_{1}x+b_{2}Y $ 且  $ \left|\frac{a_{1}}{b_{1}}\frac{a_{2}}{b_{2}}\right| \neq 0 \Rightarrow (Z_{1}, Z_{2}) \sim N $

④条件分布仍正态.  $ Y=y $ 时  $ X\sim N\left(\mu_{1}+\rho\frac{\sigma_{1}}{\sigma_{2}}(y-\mu_{2}),(-p)^{2}\sigma_{1}^{2}\right) $.  $ X=x $ 时  $ Y\sim N\left(\mu_{2}+\rho\frac{\sigma_{2}}{\sigma_{1}}(x-\mu_{1}),(-p)^{2}\sigma_{2}^{2}\right) $

③若 $ X_{1}\sim N(\mu_{1},\sigma_{1}^{2}),X_{2}\sim N(\mu_{2},\sigma_{2}^{2}) $且 $ x_{1},x_{2} $独立 $ \Rightarrow(x_{1},x_{2})\sim N(\mu_{1},\mu_{2};\sigma_{1}^{2},\sigma_{2}^{2};0) $

④若 $ X_{1,2} $记 $ N(\mu,\sigma) $， $ Y_{1}=aX_{1}+bX_{2} $， $ Y_{2}=aX_{1}-bX_{2}\Rightarrow\left\{\begin{array}{l}EY_{1}=(a+b)\mu\\EY_{2}=(a-b)\mu\end{array}\right. $， $ \left\{\begin{array}{l}DY_{1}=(a^{2}+b^{2})\sigma^{2}\\=DY_{2}\end{array}\right. $， $ \cos(Y_{1}Y_{2})=(a^{2}-b^{2})\sigma^{2} $， $ P_{Y_{1}Y_{2}}=\frac{a^{2}-b^{2}}{a^{2}+b^{2}} $

⑤  $ X \sim N, Y \sim N $ 且  $ X, Y $ 不相关  $ \Rightarrow $ X, Y 独立  $ X \sim N, Y \sim N \Rightarrow C(X + C_{2})Y \sim N $

## 四、变量函数的分布

1. 定义  $ F_{Y}(y) = P(Y \leq y) = P(g(x) \leq y) = \int g(x) dx $

公式 若  $ y = g(x) $ 在  $ a < x < b $ 上严格单调可导，反函数  $ x = h(y) $，则  $ f_{Y}(y) = \begin{cases} f_{X}[h(y)] \cdot |h'(y)|, & a < y < B \\ 0, & a, B = \lim\limits_{x \to 0} g(x) \text{ 或 } \lim\limits_{x \to 0} g(x) \end{cases} $

证：①  $ g(x) \uparrow, F(y) = P(x \leq h(y)) = \int_{-\infty}^{h(y)} f_{x}(x) dx $ ②  $ g(x) \downarrow, F(y) = P(x \geq h(y)) = \int_{h(y)}^{+\infty} f_{x}(x) dx $ （此时  $ f(y) = f_{x}[h(y)] \cdot [-h'(y)] $）

2. 若  $ F_{x}(x) $ 在正概率密度区间上严格单调增加时， $ Y = F_{x}(x) \sim U(0,1) $

3. 定义  $ F(z) = P(g(x, y) \leq z) = \iint\limits_{g(x, y) \leq z} f(x, y) \, dx \, dy $

雅可比 设  $ u, v $ 有一阶连续偏导， $ \left\{\begin{array}{l} x=x(u,v) \\ y=y(u,v) \end{array}\right. $ 是  $ \left\{\begin{array}{l} u=u(x,y) \\ v=v(x,y) \end{array}\right. $ 唯一反函数，则  $ f(u,v) = f[x(u,v), y(u,v)] - |J| = f(x,y) - |J| $

其中转换系数  $ J = \left|\frac{\partial x}{\partial u} \frac{\partial x}{\partial v}\right| = \left|\frac{\partial u}{\partial x} \frac{\partial u}{\partial y}\right| \neq 0 $，且有  $ f(u) = \int_{-\infty}^{+\infty} f[x(u,v), y(u,v)] |J| dv = \int_{-\infty}^{+\infty} f(x,y) |J| dv $， $ f(v) = \int_{-\infty}^{+\infty} f(x,y) |J| du $

证： $ F(u,v)=P(u(x,y)\leq u,v(x,y)\leq v)=\iint_{D}f(x,y)dx dy=\iint_{D}f[x(u,v),y(u,v)]|J|du dv $

和  $ Z = X + Y $,  $ f(z) = \int_{-\infty}^{+\infty} f(x, z-x) dx = \int_{-\infty}^{+\infty} f(z-x, y) dy \stackrel{\text{独立}}{\leq} \int_{-\infty}^{+\infty} f_{x}(x) f_{y}(z-x) dx = \int_{-\infty}^{+\infty} f_{x}(z-y) f_{y}(y) dy $

证：令  $ \left\{\begin{array}{l} u = ax + by \\ v = y \end{array}\right. $，则  $ \left\{\begin{array}{l} x = \frac{4 - 6v}{a} \\ y = v \end{array}\right. $， $ |J| = \left|\left|\frac{1}{a} - \frac{1}{a}\right|\right| = \left|\frac{1}{a}\right| $，则  $ f(u, v) = f_{x}\left(\frac{u - bv}{a}\right) f_{y}(v) \cdot \frac{1}{|a|} $， $ f(z) = f(u) = \int_{-\infty}^{+\infty} f_{x}\left(\frac{u - bv}{a}\right) f_{y}(v) \cdot \frac{1}{|a|} dv $

 $ \int_{-\infty}^{+\infty} f_{x}\left(\frac{z - bv}{a}\right) f_{y}(y) \cdot \frac{1}{|a|} dy $。事实上，与偏导  $ \frac{\partial^{2} \frac{z - by}{a}}{\partial z} = \frac{1}{a} $ 的结果一致（加绝对值）

差  $ Z = x - y $,  $ f(z) = \int_{-\infty}^{+\infty} f(x, x-z) \, dx = \int_{-\infty}^{+\infty} f(y+z, y) \, dy $

积  $ Z = XY $,  $  f(z) = \int_{-\infty}^{+\infty} \frac{1}{|x|} f(x, \frac{2}{x}) dx = \int_{-\infty}^{+\infty} \frac{1}{|x|} f(\frac{2}{x}, y) dy  $

 $ \left\{\begin{array}{l} u = xy \\ v = y \end{array}\right. $,  $ J = \left|\frac{1}{0} - \frac{u}{v^{2}}\right| = \frac{1}{V} $

商  $ Z = \frac{x}{4} $,  $ f(z) = \int_{-\infty}^{+\infty} |y| f(yz, y) dy $

 $ \left\{\begin{array}{l} u = \frac{x}{4} \\ v = y \end{array}\right. $,  $ J = \left|\frac{V}{0}\right| = V $

 $$ \max f_{\max}(x)=[f(x)]^{n},f_{\max}(x)=n f(x)[f(x)]^{n-1} $$ 

min  $ \int_{\min}(x)=1-\left[1-F(x)\right]^{n}, f_{\min}(x)=n f(x)\left[1-F(x)\right]^{n-1} $

#### 可加性 设 $ x, y $独立，则

①  $ X \sim B(n, p) $,  $ Y \sim B(m, p) \Rightarrow X + Y \sim B(n+m, p) $ ②  $ X \sim P(\lambda_{1}) $,  $ Y \sim P(\lambda_{2}) \Rightarrow X + Y \sim P(\lambda_{1} + \lambda_{2}) $

③  $ X \sim N(\mu_{1}, \sigma_{1}^{2}), Y \sim N(\mu_{2}, \sigma_{2}^{2}) \Rightarrow X + Y \sim N(\mu_{1} + \mu_{2}, \sigma_{1}^{2} + \sigma_{2}^{2}) $ ④  $ X \sim \chi^{2}(n), Y \sim \chi^{2}(m) \Rightarrow X + Y \sim \chi^{2}(n+m) $

⑤ $ X\sim E(\lambda_{1}),Y\sim E(\lambda_{2})\Rightarrow\min\{x,y\}\sim E(\lambda_{1}+\lambda_{2}) $

#### 五数字特征

Riemann: 设  $ x_{n} $ 条级则对  $ \forall a \in [-100, 100] $ 以存在更序数列满足  $ x_{n}^{\prime} = a $

1. EX中心  $ EX = \int_{-\infty}^{+\infty} x f(x) dx $ 绝对收敛时称EX存在  $ E[g(x)] = \int_{-\infty}^{+\infty} g(x) f(x) dx $

 $ E(ax + by) = aEx + bEY $

x, y 不相关  $ \Leftrightarrow EXY = EXEY $

 $ (EXY)^{2} \leq EX^{2}EY^{2} $

波动

2. DX  $ DX = E\left[(x - Ex)^{2}\right] = Ex^{2} - E^{2}x $

证： $ D X=E\left[X^{2}-2X\cdot E X+E^{2}X\right]=E X^{2}-2E X\cdot E X+E^{2}X=E X^{2}-E^{2}X $

 $$ O(x)=\sqrt{D x} $$ 

 $$ 当x=\frac{x-E x}{\sqrt{D x}}时E x=0,D x=1 $$ 

 $ D X=O\Leftrightarrow X $几乎处处为 $ C\Leftrightarrow P\{X=C\}=1 $

 $$ D(a x+b)=a^{2}D x $$ 

 $$ D(x\pm Y)=D X+D Y\pm2c o v(x,y) $$ 

 $$ D(\sum\limits_{i=1}^{n}a_{i}x_{i})=\sum\limits_{i=1}^{n}a_{i}^{2}D x_{i}+2\sum\limits_{1\leq i\leq j\leq n}a_{i}a_{j}c o v(x_{i},x_{j}) $$ 

若 $ X,Y $独立，则 $ D(aX+bY)=a^{2}Dx+b^{2}DY $，一般地， $ X_{mn} $独立时 $ D\left[\sum_{i=1}^{n}g_{i}(x_{i})\right]=\sum_{i=1}^{n}D\left[g_{i}(x_{i})\right] $

对  $ \forall C $，有  $ DX = E[(x - EX)^{2}] \leq E[(x - C)^{2}] $ 证：右边  $ = EX^{2} - 2CEX + C^{2} = f(c) $，则  $ f'(c) = 2c - 2EX \Rightarrow C = EX $

3.  $ E[g(x,y)] $  $ E[g(x,y)] = \int_{-\infty}^{+\infty} \int_{-\infty}^{+\infty} g(x,y) f(x,y) dx dy $  $ E_{x} = \int_{0}^{+\infty} f(x,y) dx dy $ 而一定非得用  $ E_{x} = \int_{-\infty}^{+\infty} x f_{x}(x) dx $

偏差

4.  $ \operatorname{cov}(x,y) $  $ \operatorname{Cov}(x,y) = E[(x-Ex)(y-EY)] = EXY - EXEY $

 $$ c o v(a X,b Y)=a b c o v(x,y)c o v(x_{1}+x_{2},y)=c o v(x_{1},Y)+c o v(x_{2},Y) $$ 

→标准化

5.  $ P_{XY} =  $ 线性关系  $ P_{XY} = \text{COV}(X^{*}, Y^{*}) = \text{COV}(\frac{(X-EX)}{\sqrt{DX}}, \frac{Y-EY}{\sqrt{DY}}) = \frac{\text{COV}(X-EX, Y-EY)}{\sqrt{DX}\sqrt{DY}} = \frac{\text{COV}(X, Y)}{\sqrt{DX}\sqrt{DY}} $ DXY=0时， $ P_{XY}=0 $

 $ P=0 \Leftrightarrow $ 不相关  $ P_{XY}=1 \Leftrightarrow P(Y=aX+b)=1 $ (a>0)  $ P_{XY}=-1 \Leftrightarrow P(Y=aX+b)=1 $ (a<0)

几乎处处成立

6.  $ EX^{k}(k=1,2,\ldots) $ 为 K 阶原点矩  $ EX^{k}Y^{2}(k,l=1,2,\ldots) $ 为 K+2 阶混合原点矩

 $ E\left[(x-EX)^{k}\right](k=2,3,\ldots) $ 为 K 阶中心矩

 $ EX: k=2 $

 $ E\left[(x-EX)^{k}(y-EY)^{2}\right](k,l=1,3,\ldots) $ 为 K+2 阶混合中心矩

 $ \rightarrow COV: k=2,l=1 $

 $$ \int\limits_{0}^{+\infty}x^{n}e^{-x}d x=n! $$ 

 $$ \int_{-\infty}^{+\infty}x^{2}e^{-a x^{2}}d x=\frac{\sqrt{\pi}}{2a^{2}} $$ 

 $$ \int_{-\infty}^{+\infty}e^{-x^{2}}dx = \sqrt{\pi},\quad \int_{-\infty}^{+\infty}x^{2n}e^{-ax^{2}}dx = \frac{(2n-1)!!}{(2n+1)!!}\sqrt{\pi} $$ 

8.  $ \sum_{i=1}^{n}(x_{i}-\overline{x})^{2}=\sum_{i=1}^{n}x_{i}^{2}-n\overline{x}^{2}=\sum_{i=1}^{n}(x_{i}-\mu)^{2}-n(\overline{x}-\mu)^{2} $

### 随机变量

证明： $ n \ll N $时，取 $ P = \frac{M}{N} $，有 $ H(n, N, M) \approx B(n, p) $

证： $ P(x=k)=\frac{C_{m}^{k}C_{n-m}^{n-k}}{C_{n}^{n}}=\frac{\frac{A_{m}^{k}}{k!}\cdot\frac{A_{n-m}^{n-k}}{(n-k)!}}{\frac{A_{n}^{k}}{n!}}=\frac{n!}{k!(n-k)!}\cdot\frac{M^{k}(N-M)^{n-k}}{N^{n}}\cdot\frac{A_{m}^{k}}{M^{k}}\cdot\frac{A_{n-m}^{n-k}}{(N-M)^{n-k}}=C_{n}^{k}(\frac{M}{N})^{k}(1-\frac{M}{N})^{n-k} $

这是因为 $ n \ll N, k \ll M, n-k \ll N-M $时，因式 $ ① \approx 1 $

2. 证明：若 $ x, y $独立，则 $ DXY = DXDY + DX^{2}Y + DYEX^{2} \geq DXDY $

2. 证明：若  $ X, Y $ 独立，则  $ DXY = DXDY + DX EY + DYEX \geq DXY $

证： $ X, Y $ 独立  $ \Rightarrow X^{2}, Y^{2} $ 独立。则  $ DXY = EX^{2}Y^{2} - EXY \xlongequal{独立} EX^{2}EY^{2} - (EXEY)^{2} = (DX + EX)(DY + E^{2}Y) - EX^{2}EY = DX + EX^{2}DY + E^{2}YDX $

3. 证明： $ X \sim P(\lambda t) $，则相邻两次事件发生的时间间隔  $ Y \sim E(\lambda) $

证： $ F(y)=P(y \leq y)=P(y $时间内发生 $ )=1-P(y $时间内无事发生 $ )=1-P(x=0)=1-e^{-\lambda y} $

注： $ X \sim P(\lambda t) $ 表示  $ [t_0, t_0 + t] $ 内事件发生的个数服从  $ P(\lambda t) $，故  $ y $ 时间内  $ X \sim P(\lambda y) $， $ P(X=0) = e^{-\lambda y} P(X=k) = \frac{(t_0)^2}{k!} e^{-\lambda t} $

4.  $ (x,y) \sim f(x,y) $，用分布函数法求  $ Z = x + Y $ 的密度函数  $ f_{2}(z) $.

解： $ F_{2}(z)=\int_{-\infty}^{+\infty}dx\int_{-\infty}^{z-x}f(x,y)dy\stackrel{y=u-x}{=}\int_{-\infty}^{+\infty}dx\int_{-\infty}^{z}f(x,u-x)du=\int_{-\infty}^{z}du\int_{-\infty}^{+\infty}f(x,u-x)dx $，故 $ f(z)=\int_{-\infty}^{+\infty}f(x,z-x)dx $

5. 证明：若 $ (x,y)\sim N(\mu_1,\mu_2;\sigma_1^2,\sigma_2^2,\rho) $，则 $ x,y $独立  $ \Leftrightarrow $  $ \rho=0 $

证：由 $ (x,y)\sim N $知 $ x\sim N(\mu_1,\sigma_1^2) $， $ y\sim N(\mu_2,\sigma_2^2) $。若 $ f(x,y)=f_1(x)f_2(y) $，令 $ x=\mu_1,y=\mu_2 $得 $ \frac{1}{\sqrt{1-p}}=1\Rightarrow\rho=0 $。若 $ \rho=0 $，不难验证 $ f(x,y)=f(x)f(y) $对 $ \forall x,y $都成立。

### 6. 证明  $ B(n,p) $、 $ P(\lambda) $ 的可加性

证： $ X \sim B(n, p) $， $ Y \sim B(n, p) $，则  $ P(Z = k) = \sum_{i=0}^{k} P(X = i) P(Y = k - i) = \sum_{i=0}^{k} C_{n_1} P^i q^{n_1 - i} C_{n_2} P^{k - i} q^{k - i} n_2 k + i^2 = \sum_{i=0}^{k} C_n_1 C_{n_2} P q^{n_1 + n_2 - k} = C_{n_1 + n_2}^k P^k q^{n_1 + n_2 - k} \sim B(n_1 + n_2 p) $。其中， $ C_{n_1 + n_2}^n = \sum_{k=0}^{n} C_{n_1}^k C_{n_2}^{n-k} $ 证明如下：注意到  $ (Hx)^{n_1 + n_2} $ 的  $ x^n $ 的系数为  $ C_{n_1 + n_2}^n $，而  $ (Hx)^n (Hx)^{n_1} $ 中  $ x^n $ 系数为  $ \sum_{k=0}^{n} C_{n_1}^k C_{n_2}^{n-k} $，二者必然相等。

 $ x \sim P(\lambda_1), y \sim P(\lambda_2) $，则  $ P(z = k) = \sum_{i=0}^{k} P(x = i) P(Y = k - i) = \sum_{i=0}^{k} \frac{\lambda_i^2}{i!} e^{-\lambda_i} \frac{\lambda_2^{k-i}}{(k - i)!} e^{-\lambda_2} = \frac{e^{-(i + \lambda_2)}}{k!} \sum_{i=0}^{k} C_{n_1} \lambda_i^2 \lambda_2^{k-i} $

 $ = \frac{a_1 + \lambda_2 k}{k!} e^{-(\lambda_1 + \lambda_2)} $，其中，注意到  $ (\lambda_1 + \lambda_2)^n = \sum_{k=0}^{n} C_n^k \lambda_1^k \lambda_2^{n-k} $ 即可

7. 证明： $ D(x+y)=Dx+Dy+2\cos(x+y) $

证：左边： $ E(x+Y)^{2}-E^{2}(x+Y)=E\left(X^{2}+2XY+Y^{2}\right)-\left(EX+EY\right)^{2}=EX^{2}-EX^{2}+EY^{2}-EY^{2}+2\left[EXY-EXEY\right]= $右边.其中 $ \cos\theta=E\left[(x-EX)(y-EY)\right] $

8. 证明协方差的有界性： $ [\cos(x,y)]^{2}\leq D(x)D(y) $，等号成立当且仅当X，Y存在线性关系(a.s.)

证：令 $ f(t)=E\left[(x-\mu_{1})t+(y-\mu_{2})\right]^{2}=E(x-\mu_{1})^{2}t^{2}+2E(x-\mu_{1})t(y-\mu_{2})+E(y-\mu_{2})^{2}=t^{2}Dx+2t\cos(x,y)+Dy $

由 $ f(t)\geq0 $知 $ \Delta\leq0 $，即 $ 4[c\cos(x,y)]^{2}-4DxDy\leq0 $。等号成立时， $ \cos(x,y)=\pm\sqrt{2}Dx $，代入得 $ f(t)=t^{2}Dx $

 $ \pm2t\sqrt{DxDy}+Dy=(t\sqrt{x}\pm\sqrt{y})^{2} $ 取 $ t_{0}=-\frac{\sqrt{2}Dx}{\sqrt{Dx}} $时， $ f(t)=0 $ 因此 $ E\left[(x-\mu_{1})t_{0}+(y-\mu_{2})\right]^{2}=0\Rightarrow(x-\mu_{1})t_{0}+(y-\mu_{2})=0(ax) $

若 $ y=ax+b $，则 $ \cos(x,y)=aDx=\sqrt{ax}\sqrt{xy} $

注：可证得 $ \rho\leq1 $

a.s.: almost surely P(命题成立)-1，无论在零极集中集不成立

9. 若  $ x \sim N(0,1) $，求  $ E X^{2}, D X^{2}, E |x| $， $ D |x| $

解：由 $ x^{2}\sim x^{2}(1) $知  $ Ex^{2}=1, Dx^{2}=2 $  $ E(x)=\int_{-\infty}^{+\infty}|x|\frac{1}{\sqrt{2\pi}}e^{-\frac{x}{2}}dx $  $ E(x)=\sqrt{\frac{2}{\pi}}, D|x|=1-\frac{2}{\pi} $

注： $ EX^{k}=\left\{\begin{array}{l}(k-1)!!\\0\end{array}\right. $， $ k $偶， $ k $奇（由 $ EX^{k}=(k-1)EX^{k-2} $可推）

# 随机变量A

1. 证明： $ x^{2}(1) $ 的概率密度为  $ f(x)=\frac{1}{\sqrt{2\pi}}x^{-\frac{1}{2}}e^{-\frac{x}{2}} $ (x>0)

证：考虑定义： $ x \sim N(0,1) $， $ y = x^2 \sim X^2(1) $。又 $ f(y) = \frac{1}{2\sqrt{y}} \left[ f_x(\sqrt{y}) + f_x(-\sqrt{y}) \right] = \frac{1}{2\sqrt{y}} \left( \frac{1}{\sqrt{2\pi}} e^{-\frac{y}{2}} + \frac{1}{\sqrt{2\pi}} e^{-\frac{y}{2}} \right) = \frac{1}{\sqrt{2\pi y}} e^{-\frac{y}{2}}(y > 0) $

2.  $ f(x,y)=\left\{\begin{array}{l}\frac{1+xy}{4},|x|<1,|y|<1 \\ 0\end{array}\right. $. 证明：X,Y不独立， $ x^{2},y^{2} $独立

证： $ f_{X}(x)=\int_{1}^{1}\frac{1+xy}{4}dy=\frac{1}{2}(-1<x<1) $， $ f_{Y}(y)=\frac{1}{2}(-1<y<1) $。而 $ f_{U}(u)=f_{X}(\sqrt{u})\frac{1}{2\sqrt{u}}+f_{X}(\sqrt{u})\frac{1}{2\sqrt{u}}=\frac{1}{2\sqrt{u}} $（或由 $ F(u)=\int_{\sqrt{u}}^{\sqrt{u}}du=\sqrt{u} $）， $ f_{V}(V)=\frac{1}{2\sqrt{V}}(0\leq V\leq1) $。与 $ F(u,v)=\int_{-\sqrt{u}}^{\sqrt{u}}dx\int_{\sqrt{u}}^{\sqrt{v}}\frac{1+xy}{4}dy=\sqrt{uv} $知 $ f(u,v)=\frac{\sqrt{u}}{3u\sqrt{v}}=\frac{1}{4\sqrt{uv}} $知 $ x^{2},y^{2} $独立

3.(2007.) 设  $ (x,y) \sim f(x,y) = \left\{ \begin{array}{ll} 2 - x - y & 0 < x < 1, 0 < y < 1 \\ 0 & \text{其他} \end{array} \right. $ 令  $ z = x + y $，求  $ f_{2}(z) $

3.(2001.)设 $ (x_{1}/x_{1}+x_{2})=1 $ 其他.令 $ z=x+1 $,求有(2)

解：①  $ 0 < z < 2 $，由  $ \left\{\begin{array}{l}0 < x < 1 \\ 0 < z < 1\end{array}\right. $ 得  $ \left\{\begin{array}{l}0 < x < 1 \\ z - 1 < x < z\end{array}\right. $ 故  $ 0 < z < 1 $ 时， $ f_{2}(z) = \int_{0}^{2} f(x, z - x) dx = \int_{0}^{\frac{z}{2}} 2 - z dx = z(z - z) $  $ 1 \leq z < 2 $ 时， $ f_{2}(z) = \int_{2}^{1} 2 - z dx = (z - z)^{2} $  $ f_{2}(z) = \left\{\begin{array}{ll}(2 - z)^{2} & 0 < z < 1 \\ (2 - z)^{2} & 1 < z < 2 \\ 0 & 其他\end{array}\right. $ ②画图知  $ 0 \leq z < 1 $ 时  $ F(z) = \int_{0}^{2} dx \int_{0}^{2x} 2 - x - dy = 2 - \frac{2}{3} $

 $ 1 \leq z < 2 $ 时  $ F(z) = 1 - \int_{2}^{1} dx \int_{2}^{1} x^{2} - 2 - x - dy = 1 - \frac{1}{3}(2 - z)^{3} $

4. X, Y独立， $ X \sim U[0,1] $， $ Y \sim F_{Y}(y) $，令  $ Z = \left\{ \begin{array}{l} Y, x \leq \frac{1}{2} \\ x, x > \frac{1}{2} \end{array} \right. $，求  $ F_{Z}(z) $

解： $ F_{2}(z)=P(x\leq\frac{1}{2},y\leq z)+P(x\leq z,x>\frac{1}{2})=\left\{\begin{array}{l}\frac{1}{2}F_{Y}(z)\\\frac{1}{2}F_{Y}(z)+z-\frac{1}{2},\frac{1}{2}\leq z+1\\\frac{1}{2}F_{Y}(z)+\frac{1}{2},\frac{1}{2}z+1\end{array}\right. $

注：不必化为 $ P(\frac{1}{2}\leq x\leq z|x>\frac{1}{2})\cdot P(x>\frac{1}{2}) $给自己找麻烦

5  $ F(x,y)=\left\{\begin{array}{l}1, x+y\geq1 \\ 0, x+y<1\end{array}\right. $ 能否成为 $ (x,y) $的分布函数.

解 由  $ F(1,1) + F(0,0) - F(1,0) - F(0,1) = -1 < 0 $，故不能

注：常取跳跃点(不连续处)来构造反例

6. X, Y独立， $ X \sim N(\mu, \sigma^{2}) $， $ Y \sim [-\pi, \pi] $， $ Z = X + Y $，求  $ f_{2}(z) $

解：①  $ f(x) $ 在  $ [- \pi, \pi] $ 取非零值，则  $ f_{2}(z) = \int_{\pi}^{\pi} f(z,y) f_{1}(y) dy = \frac{1}{2\pi} \int_{\pi}^{\pi} \frac{1}{\sqrt{2\pi}\sigma} e^{-\frac{(z-y)^{2}}{2\sigma^{2}}} dy = \frac{1}{2\pi} \int_{\frac{z-\pi-y}{2\pi}\sqrt{\pi}}^{\pi+\pi-y} \frac{1}{\sqrt{2\pi}} e^{-\frac{t^{2}}{2}} dt = \frac{1}{2\pi} \left[ \Phi \left( \frac{z+\pi-y}{\sigma} \right) - \Phi \left( \frac{z-\pi-y}{\sigma} \right) \right] $

② 由  $ -\pi \leq z - x \leq \pi $，则  $ f_{2}(z) = \frac{1}{z-\pi} \int_{\pi-\pi-y}^{\pi+\pi-y} e^{-\frac{(z-y)^{2}}{2\sigma^{2}}} dx = \frac{1}{2\pi} e^{-\frac{t^{2}}{2}} dx $

7.  $ x, y $ 独立,  $ x \sim B(4, \frac{1}{2}), y \sim P(1) $, 则  $ P\{1 < \max\{x, y\} \leq 3\} =  $

解:  $ P = P(\max \leq 3) - P(\max \leq 1) = (1 - \frac{1}{16}) \cdot \frac{8}{3} e^{-1} - \frac{5}{16} \cdot 2 e^{-1} = \frac{15}{8 e} $

8. 证明:  $ \{X \sim B(n, p)\} $ 时  $ EX = np $ (2)  $ X \sim G(p) $ 时  $ EX = \frac{1}{p} $

证: (1)  $ EX = \sum_{k=0}^{n} K C_{n}^{k} p^{k}(1-p)^{n-k} = \sum_{k=1}^{n} k \frac{n!}{k!(n-k)!} p^{k}(1-p)^{n-k} = np^{n-k} = np \sum_{k=0}^{n-1} \frac{(n-1)! p^{k}}{k!(n-k)!} p^{k}(1-p)^{n-k-1} $

注意到  $ (p + p)^{n-1} = \sum_{k=0}^{n-1} C_{n}^{k} p^{k}(1-p)^{n-k-1} = 1 $ (2)  $ EX = \sum_{k=1}^{n} k q^{k-1} p = p \left( \frac{p^{k}}{k-1} q^{k} \right)^{1} = p \left( \frac{1}{1-q} - 1 \right)^{1} = \frac{1}{(1-q)^{2}} = \frac{1}{p} $

9.(1)  $ X \sim p(N) $,  $ Y = X^{2} $, 求 EY

(2)  $ X \sim B(n, p) $,  $ Y = e^{3x} - 1 $, 求 EY

解: (1)  $ E Y = \sum_{k=0}^{\infty} k^{2} \frac{\lambda^{k}}{k!} e^{-\lambda} = \sum_{k=1}^{\infty} \frac{k}{(k-1)!} \lambda^{k} e^{-\lambda} = \sum_{k=1}^{\infty} \frac{k+1}{(k-1)!} \lambda^{k-2} \cdot \lambda^{2} e^{-\lambda} + \sum_{k=1}^{\infty} \frac{1}{(k-1)!} \lambda^{k-1} e^{-\lambda} = \lambda^{2} + \lambda $

(2)  $ E Y = \sum_{k=0}^{\infty} (e^{3k} - 1) C_{n}^{k} p^{k} (1 + p)^{n-k} = \sum_{k=0}^{\infty} C_{n}^{k} (e^{3p})^{k} (1 - p)^{n-k} - 1 = (e^{3p} + 1 - p)^{n-1} $

10. X的样本 $ x_{1}, x_{2}, x_{3} $，求 $ P\left\{\max(x_{1}, x_{2}) < x_{3}\right\} $

解:  $ I=\int_{-\infty}^{+\infty}f(x_{3})dx_{3}\int_{-\infty}^{x_{3}}f(x_{2})dx_{2}\int_{-\infty}^{x_{3}}f(x_{1})dx_{1}=\int_{-\infty}^{+\infty}F(x_{3})f(x_{2})dx_{2}=\left.\frac{1}{3}F(x_{3})\right|_{-\infty}^{+\infty}=\frac{1}{3} $

11.20客，10站等可能、独立下车.无客下车则不停车.记X为停车次数，求EX

解第站有人下车 $ P=1-\left(\frac{9}{10}\right)^{20} $.故 $ E_{X}=10\left[1-\left(\frac{9}{10}\right)^{20}\right] $

11.  $ x \sim N(M, \sigma^{2}) $, 求  $ \int_{-\infty}^{+\infty} f(x) \ln f(x) dx $

解:  $ I = \int_{-\infty}^{+\infty} f(x) \ln \frac{1}{\sqrt{2\pi}\sigma} dx + \int_{-\infty}^{+\infty} f(x) \ln e^{-\frac{(x-M)^{2}}{2\sigma^{2}}} dx = \ln \frac{1}{\sqrt{2\pi}\sigma} - \int_{-\infty}^{+\infty} f(x) \frac{(x-M)^{2}}{2\sigma^{2}} dx $ 其中  $ I_{2} = \frac{1}{2\sigma^{2}} E[x - M^{2}] = \frac{1}{2\sigma^{2}} \left[ E^{2}(x - M) + D(x - M) \right] $

 $ = \frac{1}{2\sigma^{2}} (0 + \sigma^{2}) = \frac{1}{2} $ 于是  $ I = \ln \frac{1}{\sqrt{2\pi}\sigma} - \frac{1}{2} $

12.  $ x \sim U(0,1) $，当  $ x = x_{0} $ 时， $ Y \sim B(2, x) $，求  $ P_{XY} $

解： $ f(x,y)=P\{y=y|x=x\} $  $ f(x) $，则 $ f(x,0)=P\{y=0|x=x\}=C_{2}^{0}x^{0}(-x)^{2}=(1-x)^{2} $， $ f(x,1)=2x(1-x) $， $ f(x,2)=x^{2} $

则 $ EXY=\frac{2}{y-0}\int_{0}^{1}xyf(x,y)dx=\int_{0}^{1}O\cdot x(1-x)^{2}+1\cdot x\cdot2x(1-x)+2x\cdot x^{2}dx=\frac{2}{3} $ 又由 $ P(Y=0)=\int_{0}^{1}(1-x)^{2}dx=\frac{1}{3} $， $ P(Y=1)=\int_{0}^{1}2x(1-x)dx=\frac{1}{3} $， $ P(Y=2)=\int_{0}^{1}x^{2}dx=\frac{1}{3} $ 知 $ EY=1 $， $ DY=\frac{2}{3} $，又 $ EX=\frac{1}{2} $， $ DX=\frac{1}{12} $ 知 $ P=\frac{\sqrt{2}}{\sqrt{1+x^{2}}}=\frac{\sqrt{2}}{2} $

13. 判断(1)  $ \int_{x}^{x+1} f(t) dt $ 必不为某个随机变量的概率密度 (2)  $ \int_{x}^{x+1} F(t) dt $ 必为…的分布函数

解：(1) × 如取  $ x \sim u[0,1] $ 有  $ F(x+1) - F(x) = \begin{cases} xH, & -1 \leq x < 0 \\ -x, & 0 \leq x < 1 \\ 0, & \text{else} \end{cases} $ 则  $ \int_{x_0}^{x_0} F(x+1) dx = 1 $

(2) √  $ G'(x) \geq 0 $，右连续， $ \lim_{x \to -\infty} G(x) = F(x) $:  $ \lim_{x \to \infty} F(x) = 0, \lim_{x \to \infty} G(x) = 1 $

# 随机变量-B

1. X, Y服从P(x=n, Y=m) =  $ \frac{e^{-14}(214)^{m}(6.86)^{n-m}}{m!(n-m)!} $，n=0,1, $ \ldots $; m=0,1, $ \ldots $ n(1)求边缘分布率 (2)求条件分布率

解令 $ a=7.14 $, b=6.86 则 $ a+b=14 $ (1)  $ P(x=n)=\sum_{m=0}^{n}\frac{e^{-14}a^{m}b^{n-m}}{m!(n-m)!} $. 注意到下标m，右侧类似二项式展开式

由 $ (a+b)^{n}=\sum_{m=0}^{n}C_{n}^{m}a^{m}b^{m-n}=\sum_{m=0}^{n}n!=\sum_{m=0}^{a^{m}}n!\cdot(n-m)! $ 则 $ P(x=n)=\frac{e^{-14}}{n!}\cdot(n=0,1,\ldots) $

 $ P(Y=m)=\sum_{n=m}^{\infty}\frac{e^{-14}}{n!}\cdot\frac{a^{m}b^{n-m}}{m!(n-m)!} $

 $ \sum_{n=0}^{\infty}\frac{e^{-14}}{n!}\cdot\frac{a^{m}b^{m-n}}{m!}=\sum_{n=0}^{\infty}\frac{e^{-14}}{n!}\cdot\frac{b^{n}}{n!}=\frac{e^{-14}}{m!}\cdot e^{b}=\frac{e^{-214}}{m!}\cdot\frac{7.14}{m!}(m=0,1,\ldots) $ 因为m≤n，故n从m开始

上述方法差异的原因是  $ P(x=n) $ 中 m, n 的多项式难以变形，而二者 coexist 的情况就是二项式展开， $ P(y=m) $ 中应先化下标为 0，再发现可以提出无关因式 (m). (2)  $ P(x=n)/y=m $ :  $ \frac{e^{-14} a^{m} b^{n-m}}{m \cdot (n-m)!} \cdot \frac{m!}{a^{m} e^{-24}} = \frac{e^{-6.86} \cdot 6.86^{n-m}}{(n-m)!} (n=m, m+1, \ldots) $  $ P(y=m)(x=n) = \frac{e^{-14} a^{m} b^{n-m}}{m \cdot (n-m)!} \cdot \frac{n!}{e^{-14} \cdot 14^{n}} = C_{n}^{m} \left( \frac{a}{a+b} \right)^{n} \left( \frac{b}{a+b} \right)^{n-m} = C_{n}^{m} a \cdot 5^{m} a \cdot 49 $ (m=0,1,\ldots n)

2.(14.数一)连续型 $ x_{1},x_{2} $独立，方差均存在，概率密度 $ f_{1}(x),f_{2}(x) $.Y_{1}概率密度 $ f_{y_{1}}(y)=\frac{1}{2}[f_{1}(y)+f_{2}(y)] $,  $ Y_{2}=\frac{1}{2}(x_{1}+x_{2}) $证： $ EY_{1}=EY_{2} $,  $ DY_{1}>DY_{2} $

证： $ EY_{1}=\int_{-\infty}^{+\infty}yf_{y}(y)dy=\int_{-\infty}^{+\infty}\frac{1}{2}yf_{1}(y)dy+\int_{-\infty}^{+\infty}\frac{1}{2}yf_{2}(y)dy=\frac{EX_{1}+EX_{2}}{2}=\frac{\mu_{1}+\mu_{2}}{2} $.  $ EY_{1}^{2}=\int_{-\infty}^{+\infty}\frac{1}{2}yf_{1}(y)dy+\int_{-\infty}^{+\infty}\frac{y^{2}}{2}f_{2}(y)dy=\frac{EX_{1}^{2}+EX_{2}^{2}}{2}=\frac{\mu_{1}^{2}+\mu_{2}^{2}}{2} $. 则  $ DY_{1}=\frac{1}{2}(\sigma_{1}^{2}+\sigma_{2}^{2})+\frac{1}{4}(\mu_{1}-\mu_{2})^{2} $.  $ EY_{2}=\frac{\mu_{1}+\mu_{2}}{2} $,  $ DY_{2}=\frac{\sigma_{1}^{2}+\sigma_{2}^{2}}{4} $

注：取 $ x_{1,2}\sim N(0,1) $知 $ Y_{1}\sim N(0,1) $， $ Y_{2}\sim N(0,\frac{1}{2}) $可作为判断大小关系的思路.

3.  $ \ln n $, n个球. 任取1球, 若1号则得1分且停止取球; 若号(记2)则得1分且放回重新取. 求平均总分数

解:  $ EX = \frac{1+2+\cdots+n}{n} + \frac{n-1}{n} EX $, 故  $ EX = \frac{n(n+1)}{2} $

# 数理统计

## 一、根无率规律

1. 依概率收敛 设  $ X $ 与  $ \{X_n\} $，若对  $ \forall \varepsilon > 0 $，有  $ \lim_{n \to \infty} P\{|X_n - X| \geq \varepsilon\} = 0 $ 或  $ \lim_{n \to \infty} P\{|X_n - X| < \varepsilon\} = 1 $，则称  $ \lim_{n \to \infty} X_n = X(P) $ 或  $ n \to \infty, X_n \xrightarrow{P} X $ 而不是  $ |X_n - X| < \varepsilon $

若 $ x_{n}\rightarrow x $， $ y_{n}\rightarrow y $， $ g(x) $连续，则 $ g(x_{n},y_{n})\xrightarrow{P}g(x,y) $

2. 切比雪夫不等式 若  $ E(x, Dx) $ 存在，则  $ \forall \varepsilon > 0 $，有  $ P(|x - E x| \geq \varepsilon) \leq \frac{Dx}{\varepsilon^{2}} $， $ P(|x - E x| < \varepsilon) \geq 1 - \frac{Dx}{\varepsilon^{2}} $

### 3. 大数定律  $ \overrightarrow{x} \xrightarrow{P} EX $

①切比雪夫①独立 ② $ DX \leq C $ (有上界)，则  $ \frac{1}{n}\sum_{i=1}^{n}X_{i} \xrightarrow{P} \frac{1}{n}\sum_{i=1}^{n}EX_{i} $，即： $ \overline{x} \xrightarrow{P} EX $

②伯努利 ① $ x\sim B(n,p),0<p<1 $ 则对 $ \forall\varepsilon>0, $有 $ \lim_{n\to\infty}p\left(\left|\frac{M_n}{n}-p\right|<\varepsilon\right)^{2}=1, $即 $ \frac{M_n}{n}\rightarrow p, $其中 $ M_n $为事件发生次数

③辛钦 ① i.i.d ②  $ EX_{i}=M $ (存在)，则对  $ \forall \varepsilon > 0 $，有  $ \lim_{n \to \infty} P\left(\left|\frac{\sqrt[n]{x_{i}}}{n}-M\right| < \varepsilon\right\} = 1 $，即： $ \frac{\sqrt[n]{x_{i}}}{n} \rightarrow M = EX $

### 4. 中心极限定理  $ \exists x \sim N $

①列维-林德伯格 ①i.i.d ② $ EX_{i}=\mu,DX_{i}=\sigma^{2}>0 $，则 $ \lim_{n\to\infty}P\left(\frac{23}{n-1}X_{i}-nM}{\sqrt{n}\sigma}\leq x $= $ \Phi(x) $，即 $ \frac{n}{21}X_{i}\sim N(n\mu,n\sigma^{2}) $

②棣莫弗-拉普拉斯 ①  $ X_{n} \sim B(n, p) (0 < p < 1, n \geq 1) $，则  $ \lim_{n \to \infty} P\left(\frac{X_{n} - np}{\sqrt{np(p)}} \leq X\right) $ 亚  $ (x) $，即  $ x_{n} \sim N(np, np(1-p)) $

其实相当于  $ B(1, p) $ 的  $ \frac{n}{2} $

5. 经马金分布函数  $ F_{n}(x)=\frac{x_{1}\ldots x_{n}}{n} $ 中  $ \leq x $ 的样本值个数  $ =\left\{\begin{array}{ll}\frac{k}{n} & x_{k}\leq x<x_{k+1} \\ 1 & x>x_{n}\end{array}\right. $ 可作为分布函数的近似  $ E[f_{n}(x)]=F(x) $

## 二、统计量

1. 样本 样本 $ (x_{1}, \ldots, x_{n}) $ 满足  $ X_{i} \textcircled{1} F(x) $ 具体数值  $ (x_{1}, \ldots, x_{n}) $ 称为样本的一个观测值/样本值  $ f(x_{1}, \ldots, x_{n}) = \frac{\prod_{i=1}^{n} f(x_{i})}{x_{1} \ldots x_{n}} $

2. 统计量 不含任何未知参数的  $ g(x_{1}, \ldots, x_{n}) $ 称为样本的一个统计量， $ g(x_{1}, \ldots, x_{n}) $ 称为观测值

样本均值，下同

 $$ 样本均值 =\frac{1}{n-1}\left(\sum_{i=1}^{n} x_{i}^{2}-n\overline{x}^{2}\right) $$ 

②方差  $ S^{2}=\frac{1}{n-1}\sum_{i=1}^{n}(x_{i}-\bar{x})^{2} $ 标准差  $ S=\sqrt{\frac{1}{n-1}\sum_{i=1}^{n}(x_{i}-\bar{x})^{2}} $

①均值  $ \overline{x} = \frac{1}{n} \sum_{i=1}^{n} x_{i} $

③ K阶(原点)矩  $ A_{k}=\frac{1}{n}\sum_{i=1}^{n}X_{i}^{k}(k=1,2,\ldots) $ K阶中心矩  $ B_{k}=\frac{1}{n}\sum_{i=1}^{n}(x_{i}-\overline{x})^{k}(k=2,3,\ldots) $

### 3. 三大分布

① $ x^{2} $ 若 $ x_{i}\stackrel{id}{\sim}N(0,1) $，则 $ x=\sum_{i=1}^{n}x_{i}^{2}\sim x_{i}^{2}(n) $，n为自由度（和式中独立变量的个数） $ E X=n $， $ D X=2n $

若 $ x_{1}\sim x_{1}^{2}(n_{1}) $， $ x_{2}\sim x_{2}^{2}(n_{2}) $且独立，则 $ x_{1}+x_{2}\sim x_{2}^{2}(n_{1}+n_{2}) $.

②t 若 $ x\sim N(0,1) $， $ Y\sim\chi^{2}(n) $且 $ X,Y $独立，则 $ t=\frac{x}{\sqrt{n}}\sim t(n) $

 $ E(x=0, Dx=\frac{n}{n-2}) $

 $ t_{t-d}(n)=-t_{d}(n) $  $ t_{d}(n) $上分位数 若 $ P(X\geq x_{d})=d $，则称横坐标 $ x_{d} $为上 $ d $分位数

③F 若  $ x \sim f(n, n) $,  $ y \sim f(n, n) $ 且  $ x, y $ 独立, 则  $ F = \frac{\frac{1}{m}}{n} \sim F(n, n) $  $ \frac{1}{F} = \frac{\frac{y}{n}}{x} \sim F(n, n) $

 $ F_{0}(n, n) = F_{1-d}(n, n_2) = \frac{1}{F_{0}(n_2, n_1)} $ 证设  $ F \sim F(n_2, n_1) $，则  $ P(F \leq F_{0}(n_2, n_1)) = 1 - d $，即  $ P\left(\frac{1}{F} \geq \frac{1}{F_{0}(n_2, n_1)}\right) = 1 - d $，因而  $ \frac{1}{F_{0}(n_2, n_1)} = F_{1-d}(n_1, n_2) $

 $ t^2 \sim F(1, n) $ 证： $ t = \frac{x}{d} $， $ t^2 = \frac{x^2}{n} \sim F(1, n) $. 注意：服从相同分布的随机变量并不一定相同，如  $ x \sim U(0, 1) $

4. 正态总体  $ N(u, \sigma^{2}) $

 $ E\overline{x}=EX=\mu $  $ D\overline{x}=\frac{1}{n}DX=\frac{a^{2}}{n} $  $ ES^{2}=DX=a^{2} $  $ DS^{2}=\frac{2a^{4}}{n-1} $  $ \mu=0 $时 $ \varepsilon\overline{x}^{2}=\frac{a^{2}}{n} $， $ D\overline{x}^{2}=\frac{2a^{4}}{n^{2}} $

①  $ \overline{x} \sim N(u, \frac{\sigma^{2}}{n}) $  $ \frac{\overline{x} - u}{\frac{\sigma}{\sqrt{n}}} \sim N(0,1) $

 $$ \textcircled{2}\frac{1}{\sigma^{2}}\sum_{i=1}^{n}(x_{i}-\mu)^{2}\sim\chi^{2}_{(n)} $$ 

证： $ \left(\frac{x_{i}-\mu}{\sigma}\right)^{2}\sim x_{1}^{2}(1) $

 $$ \textcircled{3}\frac{(n-1)S^{2}}{\sigma^{2}}=\frac{n}{2}\left(\frac{x_{i}-\bar{x}}{\sigma}\right)^{2}\sim\chi^{2}(n-1) \quad (1 \text{未知}) $$ 

④  $ \overline{x} $ 与  $ S^{2} $ 独立， $ \frac{\sqrt{n}(\overline{x}-\mu)}{S}=t(n-1) $ ( $ \sigma $ 未知)

注： $ \overline{x} $ 与  $ \frac{1}{n} $ 密  $ (x_{i}-\mu)^{2} $ 不独立

⑤  $ \frac{n(\overline{x}-\mu)^{2}}{S^{2}}\sim F(1,n-1) $

证： $ \frac{\left(\frac{\sqrt{x}-M}{\sigma/\sqrt{n}}\right)^{2}/1}{\frac{(n-4)\sqrt{x}}{\sigma^{2}}/n-1}\sim\frac{(N(0,1))}{x^{2}(n-1)}=F(1,n-1) $，其实就是 $ t^{2} $

①  $ \overline{x}-\overline{y}\sim N(M_{1}-M_{2},\frac{a_{1}^{2}}{n_{1}}+\frac{a_{2}^{2}}{n_{2}}) $

②  $ \frac{(n-1)S_{1}^{2}}{a^{2}} + \frac{(n-1)S_{2}^{2}}{a_{2}^{2}} \sim x^{2}(n_{1} + n_{2} - 2) $

③  $ \frac{S_{1}^{2}}{a_{1}^{2}}/\frac{S_{2}^{2}}{a_{2}^{2}}\sim F(n_{1}-1,n_{2}-1) $

④  $ \frac{1}{2} \cos^{2} \theta + \cos^{2} \theta}{(\overline{x} - \overline{y}) - (\mu_{1} - \mu_{2})} \sim t(n_{1} + n_{2} - 2) $

 $ \sqrt{\frac{(n_{1} + 1)S_{1}^{2} + (n_{2} - 1)S_{2}^{2}}{n_{1} + n_{2} - 2}} \sqrt{\frac{1}{n_{1}} + \frac{1}{n_{2}}} $

### 三估计量

1. 称统计量  $ \theta(x_{1}, \ldots, x_{n}) $ 为  $ \theta $ 的估计量，称值  $ \theta(x_{1}, \ldots, x_{n}) $ 为  $ \theta $ 的估计值

2. 设 $ \theta $是 $ \theta $的最大似然估计且 $ u=u(\theta) $有反函数 $ \Rightarrow\hat{u}=u(\hat{\theta}) $是 $ u(\theta) $的最大似然估计

3. 无偏性  $ E\hat{Q} $  $ E\hat{Q}=\theta $

有效性 $ D\theta $ (最小方差性) 若 $ E\theta_{1}=E\theta_{2}=\theta $ 且 $ D\theta_{1}<D\theta_{2} $，则 $ a_{1} $比 $ a_{2} $有效 一般有 $ \lim_{n\to\infty}D(\hat{\theta})=0 $ 1.1.1.1.

### 4. 区间估计

精度可靠度，落入 $ (\hat{O},\hat{Q}) $的概率

若 $ P(\theta_{1}<\theta<\theta_{2})=1-\alpha $，则称 $ (\theta_{1},\theta_{2}) $为 $ \theta $的置信度为 $ -\alpha $的置信区间， $ \alpha $为显著性水平

 $$ \frac{\Delta}{\sigma/\sqrt{n}}=2\frac{\Delta}{2} $$ 

①  $ \mu\int\sigma^{2}已知\left(\overline{x}-\frac{\sigma}{\sqrt{n}}\Sigma\frac{\alpha}{2},\overline{x}+\frac{\sigma}{\sqrt{n}}\Sigma\frac{\alpha}{2}\right)\Delta=\frac{\sigma}{\sqrt{n}}\Sigma\frac{\alpha}{2} $ 证： $ P(\overline{x}-\Delta<\mu<\overline{x}+\Delta)=1-\alpha\Leftrightarrow P(|\overline{x}-\mu|<\Delta)=1-\alpha\Leftrightarrow P(|\frac{\overline{x}-\mu}{\sigma/\sqrt{n}}|<\frac{\Delta}{\sigma/\sqrt{n}})=1 $

 $ \sigma^{2} $未知： $ \left(\overline{x}-\sqrt{\frac{S}{n}}t_{\frac{d}{2}}(n-1),\overline{x}+\frac{S}{\sqrt{n}}t_{\frac{d}{2}}(n-1)\right)\Delta=\sqrt{\frac{S}{n}}t_{\frac{d}{2}}(n-1) $ 证： $ P\left(\left|\frac{\sqrt{x}-M}{S/\sqrt{n}}\right|<\frac{\Delta}{S/\sqrt{n}}\right)=-d\Leftrightarrow\frac{\Delta}{S/\sqrt{n}}=t_{\frac{d}{2}}(n-1) $

②$\sigma^{2}$从已知：$\left(\frac{\sum_{i=1}^{n}(x_{i}-\mu)^{2}}{\sum_{i=1}^{n}(n-1)}\right)^{2}$ 证：$P\left(x_{1}<\sigma^{2}<x_{2}\right)=-1-\alpha\Leftrightarrow P\left(\frac{1}{x_{2}}<\frac{1}{2^{2}}<\frac{1}{x_{1}}\right)=1-\alpha\Leftrightarrow P\left(\frac{\sum_{i=1}^{n}(x_{i}-\mu)^{2}}{x_{2}}<\frac{\sum_{i=1}^{n}(x_{i}-\mu)^{2}}{\sigma^{2}}<\frac{1}{x_{1}}\right)$

从未知：$\left(\frac{\sum_{i=1}^{n}(n-1)S^{2}}{\sum_{i=1}^{n}(n-1)}\right)^{2}$ 证：$P\left(\frac{\sum_{i=1}^{n}(x_{i}-\mu)^{2}}{x_{1}}<\frac{\sum_{i=1}^{n}(x_{i}-\mu)^{2}}{\sigma^{2}}<\frac{\sum_{i=1}^{n}(x_{i}-\mu)^{2}}{x_{1}}\right)=1-\alpha$

$x_{1}=\frac{1}{2}(n-1)$

$x_{2}=\frac{1}{2}(n-1)$

注意下标的差异：

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c85f1810-ae17-41e2-9e3a-0da4e02da551/markdown_0/imgs/img_in_image_box_304_762_464_861.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A10%3A08Z%2F-1%2F%2F79723ecc74c88d117f5e8748317d042529cb55accb155645ad91cfe17ec4d8e7" alt="Image" width="13%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c85f1810-ae17-41e2-9e3a-0da4e02da551/markdown_0/imgs/img_in_image_box_304_762_464_861.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A10%3A08Z%2F-1%2F%2F79723ecc74c88d117f5e8748317d042529cb55accb155645ad91cfe17ec4d8e7" alt="Image" width="13%" />

 $ \frac{\alpha}{2} $  $ \uparrow $  $ \rightarrow $  $ \uparrow $  $ \rightarrow $  $ \uparrow $  $ \rightarrow $  $ \uparrow $  $ \rightarrow $  $ \uparrow $  $ \rightarrow $  $ \uparrow $

 $ z_{\frac{\alpha}{2}} $

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c85f1810-ae17-41e2-9e3a-0da4e02da551/markdown_0/imgs/img_in_image_box_531_765_701_866.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A10%3A08Z%2F-1%2F%2F23d6cc35bbd066ccafc7664de97ec73294471d6546b29bdc54bbf4f009a99689" alt="Image" width="14%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c85f1810-ae17-41e2-9e3a-0da4e02da551/markdown_0/imgs/img_in_image_box_531_765_701_866.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A10%3A08Z%2F-1%2F%2F23d6cc35bbd066ccafc7664de97ec73294471d6546b29bdc54bbf4f009a99689" alt="Image" width="14%" />

 $ M\alpha $  $ \rightarrow $  $ x_{1-\alpha}^{1-\alpha} $  $ \rightarrow $  $ x_{2-\alpha}^{2-\alpha} $

</div>


</div>


亦可由 $ P(x_{1-\frac{\alpha}{2}}^{2}(n-1)<x_{1}^{2}<x_{2-\frac{\alpha}{2}}^{2}(n-1))=1-a $

再代入 $ \frac{(n-1)S^{2}}{a^{2}}=x^{2} $即可

5. 假设检验  $ \rightarrow $ 小概穿(d)事件发生了，力拒绝 $ H_{0} $ (样本观测值落入拒绝域)

1. 不轻易否定的假设： $ H_{0} $（原基本零假设），其否定的陈述： $ H_{1} $（对立备择假设）

2. 弃真  $ \alpha = P $ (拒绝  $ H_{0} $  $ H_{0} $ 为真) 取伪  $ \beta = P $ (接受  $ H_{0} $  $ H_{0} $ 为假)  $ H_{0} $ 为假  $ = H_{0} $ 为真，但  $ \alpha + \beta \neq 1 $ ∴ 看样本均值

3. 拒绝域形式上与  $ H_{1} $ 一致 如： $ \sigma^{2} $ 已知， $ H_{0}: M \leq M_{0} $ (或写  $ M = M_{0} $)， $ H_{1}: M > M_{0} $，拒绝域： $ [M_{0} + \frac{\sigma}{\sqrt{n}} Z_{n}, +\infty) $ 是否在这里面

4. 正态总体的检验 (取  $ H_{0} $  $ M = M_{0} $ 或  $ M = M_{0} $ 或  $ \sigma^{2} = \sigma_{0}^{2} $) 接受域为置信度为1-x的置信区间  $ M_{0} $：假设值

①  $ \mu\left\{\begin{array}{l}\sigma^{2}已知: z=\frac{\overline{x}-\mu_{0}}{\sqrt{\frac{\sigma}{\sqrt{n}}}}\sim N(0,1)\\\sigma^{2}未知: t=\frac{\overline{x}-\mu_{0}}{\sqrt{\frac{s}{\sqrt{n}}}}\sim t(n-1)\end{array}\right. $  $ \vert z\vert\geq\bar{z}\frac{\alpha}{2}\rightarrow $ 拒绝域

 $$ a_{1}^{2}, a_{2}^{2}  已知: \ z=\frac{\overrightarrow{x}-\overrightarrow{y}}{\sqrt{\frac{a_{1}^{2}}{n_{1}}+\frac{a_{2}^{2}}{n_{2}}}}\sim N(0,1) $$ 

 $$ \begin{array}{l} a_{1}^{2} = a_{2}^{2}  未知：t=\frac{\overline{X} - \overline{Y}}{\sqrt{\frac{(n_{1}-1)S_{1}^{2}+(n_{2}-1)S_{2}^{2}}{n_{1}+n_{2}-2}}\sqrt{\frac{1}{n_{1}}+\frac{1}{n_{2}}}}\sim t(n_{1}+n_{2}-2)\end{array} $$ 

②  $ \sigma^{2} $ 已知:  $ x^{2}=\frac{\frac{n}{2}\left(x_{1}-M\right)^{2}}{0^{2}}\sim x(n) $  $ x^{2}\geq x_{2}^{2}(n) $ 或  $ x^{2}\leq x_{1}^{2}\frac{a}{2}(n) $

未知:  $ x^{2}=\frac{(n-1)s^{2}}{0^{2}}\sim x(n-1) $  $ x^{2}\geq x_{2}^{2}(n-1) $ 或  $ x^{2}\leq x_{1}^{2}\frac{a}{2}(n-1) $ 单边检验时  $ \frac{d}{2} $ 改为 d

 $$ t_{1} \geqslant t_{\frac{1}{2}}(n_{1}+n_{2}-2) $$ 

# 数理统计

证明切比雪夫不等式： $ P(|x-\mu|\geq\varepsilon)\leq\frac{\sigma^{2}}{\varepsilon^{2}} $

证： $ DX=E\left[(x-Ex)^{2}\right]=\int_{-\infty}^{+\infty}(x-\omega)^{2}f(x)dx $。由 $ \frac{(x-\mu)}{\varepsilon}\geq1 $，则左边= $ \int_{x-\mu\geq\varepsilon}f(x)dx\leq\int_{x-\mu\geq\varepsilon}\frac{(x-\mu)^{2}}{\varepsilon^{2}}f(x)dx\leq\int_{-\infty}^{+\infty}\frac{(x-\omega)^{2}}{\varepsilon^{2}}f(x)dx $两次放大导致精度误差

2证明：(1)伯努利： $ x \sim B(n, p) $， $ \lim_{n \to \infty} p(|\frac{ln n}{n} - p| < \varepsilon) = 1 $

(2)切比雪夫：独立、方差有界， $ \lim_{n \to \infty} p(|\frac{ln n}{n} - x_i| - \frac{n}{n} \sum_{i=1}^{n} E x_i | < \varepsilon) = 1 $

证：(1)记 $ x_i = \begin{cases} 1, & \text{第次发生} \\ 0, & \text{第次不发生} \end{cases} $，则 $ p(|\frac{ln n}{n} - p| \geq \varepsilon) = p(|\frac{ln n}{n} - \frac{n}{n} \sum_{i=1}^{n} E x_i| \geq \varepsilon) = p(|\frac{ln n}{n} - x_i| - E \sum_{i=1}^{n} x_i| \geq n \varepsilon) \leq \frac{D(\sum_{i=1}^{n} x_i)}{n^2 \varepsilon^2} = \frac{np \varepsilon}{n^2 \varepsilon^2} = \frac{1}{n} \frac{p \varepsilon}{E} \rightarrow 0 $

(2)  $ D(x) \leq C $.  $ p(|\frac{ln n}{n} - \frac{1}{n} E \sum_{i=1}^{n} x_i| \geq \varepsilon) \leq \frac{1}{n^2 \varepsilon^2} $， $ D_{\frac{n}{n} \geq 1}^{n} x_i \leq \frac{C}{n^2 \varepsilon^2} \rightarrow 0 $

3. 如何理解样本方差  $  S^{2} = \frac{1}{n-1} \sum_{i=1}^{n} (X_{i} - \overline{X})^{2}  $ 中的  $  \frac{1}{n-1}  $？

解①无偏性  $ ES^{2}=\frac{1}{n-1}E\left[\sum_{i=1}^{n}(x_{i}-\overline{x})^{2}\right]=\frac{1}{n-1}E\left[\sum_{i=1}^{n}(x_{i}^{2})-n\overline{x}^{2}\right]=\frac{1}{n-1}\left[\sum_{i=1}^{n}(Dx_{i}+E^{2}x_{i})-n(D\overline{x}+E^{2}\overline{x})\right]=\frac{1}{n-1}\left[n(\sigma^{2}+\mu^{2})-n(\sigma^{2}+\mu^{2})\right]=\sigma^{2} $

②自由度二次型  $ f(x)=\sum_{i=1}^{n}(x_{i}-\overline{x})^{2}=\sum_{i=1}^{n}x_{i}^{2}-n\overline{x}^{2}=\sum_{i=1}^{n}x_{i}^{2}-\frac{1}{n}\left(\sum_{i=1}^{n}x_{i}\right)^{2}=1-\frac{1}{n}) $  $ \frac{n}{2} $  $ x_{i}^{2}-\frac{2}{n}\sum_{i=1}^{n}x_{i}x_{i} $，则  $ A=\begin{bmatrix}1-\frac{1}{n}&-\frac{1}{n}&\cdots&-\frac{1}{n}\\-\frac{1}{n}&1-\frac{1}{n}&\cdots&-\frac{1}{n}\\-\frac{1}{n}&-\frac{1}{n}&\cdots&1-\frac{1}{n}\end{bmatrix} $， $ y(A)=n-1 $ 为自由度

# 数理统计-A

 $ (\sqrt{2N-1})\times\sqrt{N}(\mu,\sigma^{2})(\sigma>0) $，样本 $ X_{1},X_{2},\ldots,X_{2n}(n\geq2) $，样本均值 $ \overline{x}=\frac{\sqrt{21}X_{1}}{2n} $，求统计量 $ Y=\sum_{i=1}^{n}(X_{i}+X_{n+1}-2\overline{X})^{2} $的EY.

解：①视 $ X_{i} $， $ X_{n+1} $ ( $ 1\leq i\leq n $)为 $ N(2\mu,2\sigma^{2}) $的样本，则新样本均值为 $ \frac{1}{n}\sum_{i=1}^{n}(X_{i}+X_{n+1})=2\overline{X} $，由样本方差为 $ \frac{Y}{n-1} $与 $ E\frac{Y}{n-1}=2\sigma^{2} $知 $ EY=2(n-1)\sigma^{2} $ ② $ EY=D(X_{1}+X_{n+1}-2\overline{X})+0=DX_{1}+DX_{n+1}+4D\overrightarrow{X}+2\cos(X_{1},X_{n+1})-4\cos(X_{2},\overline{X})-4\cos(X_{n+1},\overline{X}) $

2.  $ X \sim N(\mu, \sigma_{0}^{2}) $,  $ Y \sim N(\mu, \sigma_{0}^{2}) $ 为检验总体 X 的均值大于 Y 的均值，应作检验的假设为

解： $ H_{0} $ 通常包含等号，为检验  $ \mu_{1} > \mu_{2} $，故  $ H_{1}: \mu_{1} > \mu_{2} $,  $ H_{0}: \mu_{1} \leq \mu_{2} $

3.  $ x \sim N $, n=36,  $ \overline{x}=66.5 $ 且 S=15. 分别在 d=0.05 或 0.1 下，可以认为 (1)  $ M \geq 70 $ (2)  $ \mu \leq 70 $ (3)  $ \mu > 70 $ (4)  $ \mu < 70 $ 吗？

注： $ t_{0.95}(35)=1.6896 $,  $ t_{0.90}(35)=1.3062 $

解:① $ V \cup X \cup X \cup X $ ①  $ T = \frac{x - M_0}{S/\sqrt{n}} = \frac{66.5 - 70}{1.5\sqrt{36}} = -1.4 $ (1)  $ H_0: M \geq 70 $,  $ W: T \leq -t_{t-d}(n-1) = -1.6896 < -1.4 $ 不属于拒绝域

(2)  $ H_0: M \leq 70 $,  $ W: T \geq 1.6896 > -1.4 $, 不属于  $ W $ (3)  $ H_0: M \leq 70 $ 由 (2) 知接受  $ H_0 $, 故不接受  $ H_1 $ ( $ M > 70 $)

(4)  $ H_{0}: M \geq 70 $，由(1)知接受 $ H_{0} $ ②  $ T = -1.4 $ 。(1)  $ H_{0}: M \geq 70 $， $ W: T \leq -t_{1-d}(n-1) = -1.3062 $， $ T = -1.4 $ 落入W中

(2)  $ H_{0}: M \leq 70 $， $ W: T \geq 1.3062 $，接受 $ H_{0} $ (3) 由(2)知拒绝 $ M > 70 $ (4) 由(1)知接受 $ M < 70 $

注：(1)与(3)的 $ H_{0} $、 $ H_{1} $一致 $ (H_{0}:M\geq70,H_{1}:M\geq70) $ (2)与(4)的 $ H_{0} $、 $ H_{1} $一致 $ (H_{0}:M\leq70,H_{1}:M>70) $

 $ d=0.05 $时七值不显著，接受 $ M\geq70 $和 $ M\leq70 $同时成立 $ (u=70) $ d时便拒绝了 $ M\geq70 $ ( $ \alpha\uparrow $,  $ w\uparrow $, 更容易拒绝 $ H_{0} $)

4.  $ x \sim N(\mu, \sigma_{0}^{2}) $,  $ \sigma_{0}^{2} $ 已知， $ x_{i,mn} $ 为样本.  $ H_{0}: \mu = \mu_{0}, H_{i}: \mu_{i} > \mu_{0} $. 当检验水平为 d 时，犯第二类错误的概率为

解：$\beta=P(接受\vert H_{0}\vert真实均值为\mu_{1})=P(\bar{z}\leq\bar{z}_{d}\vert\mu_{2}\vert)=P(\frac{\bar{x}-\mu_{0}}{\sqrt{\frac{\sigma}{\mu_{0}}}}\leq\bar{z}_{d})=P(\bar{x}-\mu_{0}\leq\bar{z}_{d}\vert\frac{\sigma}{\sqrt{\mu_{0}}})=P(\bar{x}<\mu_{0}+\bar{z}_{d},\frac{\sigma}{\sqrt{\mu_{0}}})\\=P(\frac{\bar{x}-\mu_{1}}{\sqrt{\mu_{1}}}\leq\frac{\mu_{0}-\mu_{1}+\bar{z}_{d}\frac{\sigma}{\sqrt{\mu_{1}}}}{\sqrt{\frac{\sigma}{\mu_{1}}}}\vert)说明\bar{x}\sim\mu(\mu_{1},\frac{\sigma}{\sqrt{\mu_{1}}})\quad\Phi(\frac{\sqrt{\mu_{1}}(\mu_{0}-\mu_{1})}{\sigma_{0}}+\bar{z}_{d})\]

5. 红球: 黑球 =  $ \gamma $，有放回抽n次(一次一球)，共取出k个红球，求 $ \gamma $的最大似然估计

解： $ P(红)=\frac{红}{红土黑}=\frac{r}{r+1} $， $ L(r)=C_{n}^{k}P^{k}(r-p)^{n+k}=C_{n}^{k}\frac{r^{k}}{(r+r)^{n}} $ 于是 $ \frac{d[nL(r)]}{dr}=\frac{k}{r}-\frac{n}{1+r}=0 $知 $ \hat{r}=\frac{k}{n-k} $

6.  $ x_{nn} $ 是  $ N(\mu, \sigma^{2}) $ 的样本， $ \mu, \sigma^{2} $ 未知.  $ \overline{x} = \frac{\sum X_{i}}{n} $,  $ Q^{2} = \frac{n}{2n}(X_{i} - \overline{X})^{2} $，则  $ H_{0}: \mu = 0 $ 的 t 检验使用统计量  $ t = $ 解： $ t = \frac{\overline{X} - \mu_{0}}{\frac{S}{\sqrt{n}}} $ 由  $ \mu_{0} = 0 $,  $ S^{2} = \frac{Q^{2}}{n-1} $ 知  $ t = \frac{\overline{X}}{Q} \cdot \sqrt{n(n-1)} $

