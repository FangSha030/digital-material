# 规范答题

1、必须写C为任意常数（包括填空题）

2 抽象型级数、积前要说明收敛域内

3、极大似然函数要写成  $ L(\theta)=\left\{\begin{array}{ll}\cdots & \text { 其他 } \end{array}\right. $

4.  $ x^{2} $、t、F分布要先证独立

5. 取值范围写成  $ \{k \vert k \in \mathbb{R} \text{且} k \neq -1\} $， $ \{1\} $ 这样的或者  $ [0, +\infty) $

6. 有奇点在说明  $ \frac{\partial Q}{\partial x} = \frac{\partial P}{\partial y} $ 时应标注：当  $ (x, y) \neq (0, 0) $ 时

7. 投影曲线别态写  $ z=0 $

# 扣分的十大行为

讨论不周  $ y^{1}+ay^{1}+y=0 $ 每个解在  $ [0,+\infty) $ 上有界， $ a\geq0 $ ( $ \Delta<0 $ 时实部应  $ \leq0 $)

2. 没有注意力  $ a_{n+1} = \ln(e^{-a_n}) $，则  $ \sum_{n=1}^{\infty} a_n = e-1 $ （ $ e^{a_n} - a_n = e^{a_{n+1}} $，则  $ \sum_{n=1}^{\infty}(e - e^{a_{n+1}}) = e - e^{a_{n+1}} = e-1 $） $ x_n e^{x_{n+1}} = e - 1 $，则  $ e^{x_{n+1}} = \frac{e^{x_n} - 1}{x_n} \xlongequal{ 找中 } e^{x_n} < e^{x_n} $ 18 数一

3. 根号的平方  $ \int_{0}^{2\pi} d\theta \int_{0}^{\sqrt{2x}} \frac{r}{r^{2}+x^{2}} dx $ 写成了  $ \pi [\ln(2x^{2}+x^{2})-\ln x^{2}] $ 应为  $ 2x $

4. 二阶导求错  $ y' = \frac{1 - \ln x}{x^{2}} $，写成了  $ y' = \frac{-x + 2x\ln x}{x^{4}} $ 应为  $ \frac{-x + 2x(1 - x - 1)}{x^{4}} $

5. 隐含条件未用  $ f(x)=\left\{\begin{array}{ll}\frac{\beta x}{\alpha^{2}}, & 0 \leq x \leq d \\ 0, & \text{else}\end{array}\right. $ 和  $ \beta=2 $ (填空题中写  $ \beta x-5 $ 分子)

6参数隐含范围解向量个数满足： $ k \leq n $

 $ f \geq 0 $，求出  $ y = cx^{3} $ 要写 C > 0 20. 数二

7. 实际问题的边界条件 18. 数一事实上为  $ 2\pi r + 4x + 3y = 2 $,  $ r \geq 0 $,  $ x \geq 0 $,  $ y \geq 0 $ 的有界闭区域，故还要讨论  $ r = 0 $;  $ x = 0 $;  $ y = 0 $ 这三种情况

在其他基下可能还不同坐标

8. 向量、坐标 15: 数一  $ \overrightarrow{3}(\neq0) $ 在  $ d_{13} $,  $ \beta_{13} $ 坐标相同，写  $ \overrightarrow{x}=C(\overrightarrow{0}) $ 不对，这是坐标，应写为  $ C(d_{1}-d_{3}) $ 或写为  $ C(\beta_{1}-\beta_{3}) $

# 易忽视的点

实对称一定不与非实对称合同26.李六.1

2.  $ \{x_{2n}\} $ 与  $ \{x_{2n-1}\} $ 都收敛于同一值才说明  $ \{x_{n}\} $ 收敛 24. 超越.2

3. 已知  $ A = 2dd^{T} + \beta\beta^{T} $，其中  $ \alpha, \beta $ 正交且均为特征向量，则取  $ \overrightarrow{\gamma} = \frac{\alpha \times \beta}{\| \alpha \times \beta \|} $ 可得  $ P = (\alpha, \beta, \gamma) $ 为正交阵 13. 数一

4. 若  $ \lim_{x \to +\infty} y = \lim_{x \to -\infty} y $ 相同的有限值，则只算一条水平渐近线 12. 数一

5 设 $ f(x)=0 $的n重根，即 $ f(x)=(x-x_{0})^{n}g(x) $且 $ g(x_{0})\neq0 $， $ g(x) $有n阶导数，则 $ x_{0} $是 $ f^{(k)}(x)=0 $的n-k重根 $ (k=1,\ldots,n-1) $且数一

注：求一次导，根的重数减少一次。由此 $ f(x)=(x-1)(x-2)(x-3)^{3}(x-4)^{4} $满足 $ f(3)=0,f(3)\neq0 $，故 $ (3,0) $是拐点

6.  $ T=\frac{N_{2}+N_{3}}{n} $，则  $ DT=D(1-\frac{N_{1}}{n})=\frac{1}{n^{2}}DN_{1}=\frac{\theta(1-\theta)}{n} $ 而非  $ DT=\frac{DN_{2}+DN_{3}}{n^{2}} $，因为  $ N_{2}, N_{3} $ 不独立（相关） 10. 数一

7. $ d_{1,2,3} $ 两两正交为  $ d_{1,2,3} $ 线性无关 (如令  $ d_{1}=(\frac{a}{2}) $) 注: 向量组两两正交且无  $ \overrightarrow{0} $. 则线性无关

8.  $ AB = C $ ( $ B \neq 0 $, A, B, C为n阶方阵) 且A、C列向过组等价B可逆 ( $ 如取B = A^{T} $) 注：能得出 $ \gamma(A) = \gamma(C) = \gamma(AB) \leq \gamma(B) $

9. $ \gamma(A)=\gamma(B)\Rightarrow A,B $等价（需同型） $ AB=E $为A为B的逆矩阵（需方阵）

# 高中知识

## 一、小知识点

1.  $ A \Rightarrow B $. A是B的充分条件

2.  $ A \Rightarrow B $，则  $ \overrightarrow{B} \Rightarrow \overrightarrow{A} $

3. 数学归纳法 (1) 验 n=1 成立 (2) 设  $ n=k(k+1) $ 成立 (3) 证  $ n=k+1 $ 成立

4. 等比  $ S_{n} = \frac{a_{1}(q^{n}-1)}{q-1} $

## 二、常用公式 使用不等式链要验等号可否取到

1. 因式分解  $ a^{3} \pm b^{3} = (a \pm b)(a^{2} \pm ab + b^{2}) $  $ a \pm b = (\sqrt[3]{a} \pm \sqrt[3]{b})(a^{\frac{2}{3}} + \sqrt[3]{a b} + b^{\frac{2}{3}}) $  $ \frac{1}{n(n+1)(n+2)} = \frac{1}{2}\left[\frac{1}{n(n+1)} - \frac{1}{(n+1)(n+2)}\right] $

 $ n \in N_{+} $:  $ a^{n} - b^{n} = (a-b)(a^{n+1} + a^{n-2}b + \cdots + ab^{n-2} + b^{n+1}) $ 则降序

 $ n \in N_{odd} $:  $ a^{n} + b^{n} = (a+b)(a^{n+1} - a^{n-2}b + \cdots - ab^{n-2} + b^{n+1}) $ 首尾为正

2.  $ \frac{n}{k=1}k^{2}=\frac{n(n+1)(2n+1)}{6} $  $ \frac{n}{k=1}k^{3}=\left[\frac{n(n+1)}{2}\right]^{2} $

或 $ \vert a-b\vert $

3.  $ \vert|a|-|b|\vert\leq|a+b|\leq|a|+|b| $ a.b到原点距离之差的绝对值  $ \leq a,b $ 距离  $ \leq a,b $ 到原点距离之和

 $ a-b \leq 0 $ 取等  $ a-b \geq 0 $ 取等 (可以推广到向量，将1.1改为范数  $ 11 \cdot 11_{p}(p \geq 1) $， $ 11a \cdot 11_{p} = (1a_{1}^{p} + \cdots + (a_{n})^{p})^{\frac{1}{p}} $)

4. 柯西  $ \left(\sum_{i=1}^{n}a_{i}^{2}\right)\left(\sum_{i=1}^{n}b_{i}^{2}\right)\geq\left(\sum_{i=1}^{n}a_{i}b_{i}\right)^{2} $ 取  $ b_{i}=1 $ 得  $ \sum a_{i}^{2}\cdot n\geq(\sum a_{i})^{2} $，即： $ \frac{\sum a_{i}^{2}}{n}\geq\left(\frac{\sum a_{i}}{n}\right)^{2}=\left(\frac{1}{a}\right)^{2} $

 $ \overrightarrow{a} $ 古线性相关取等

 $ \rightarrow $ 不超过  $ x $ 的最大整数 ( $ x $ 的整数部分)

5. 取整函数  $ [x+n]=[x]+n $  $ x-1<[x]\leq x $  $ x-[x] $ 为  $ x $ 的小数部分，如 -1.99 的为 0.01

 $ 6\sqrt{ab}\leq\frac{a+b}{2}\leq\sqrt{\frac{a+b}{2}}(a,b\geq0) $  $ \sqrt[3]{abc}\leq\frac{a+b+c}{3}\leq\sqrt{\frac{a+b+c}{3}}(a,b,c\geq0) $ A G 不等式  $ A_{m}=\frac{a+\cdots+a_{n}}{n}\geq\sqrt[n]{a_{1}\cdots a_{n}}=G_{m} $

 $ \frac{1}{1+x}<\ln(1+\frac{1}{x})<\frac{1}{x} $ 或  $ \frac{x}{1+x}<\ln(1+x)<x $ (x>0)

 $ x<\tan x<\frac{4}{π}x $ (0<x<\frac{π}{4})  $ \frac{2}{π}x<\sin x<x $ (0<x<\frac{π}{2})

## 三、三角函数

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_132_234_315_361.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2Fd9c9a71bd2fc5ae70752e2c22fcbb8c1adb6f643f6007d97863048eb64729ae5" alt="Image" width="15%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_132_234_315_361.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2Fd9c9a71bd2fc5ae70752e2c22fcbb8c1adb6f643f6007d97863048eb64729ae5" alt="Image" width="15%" />

arccosx  $ \uparrow\pi $  $ \frac{\pi}{2} $  $ (\frac{\pi}{2},\frac{\pi}{4}) $

arcsinx

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_368_234_565_354.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2F8f465e0624fa463bdefefe686fbae6c4468db0838347daa5e8f43dca72fa863a" alt="Image" width="16%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_368_234_565_354.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2F8f465e0624fa463bdefefe686fbae6c4468db0838347daa5e8f43dca72fa863a" alt="Image" width="16%" />

\

</div>


</div>


 $$ \arcsin x+\arccos x=\frac{\pi}{2}(-\leq x\leq1) $$ 

 $$ \arctan x+\arccot x=\frac{\pi}{2} $$ 

 $$ \cos(\arcsin x)=\sqrt{1-x^{2}}\quad(1 \leq x \leq 1) $$ 

 $$ \sin(\arctan x)=\frac{x}{\sqrt{x+1}} $$ 

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_118_363_381_536.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2Fbd098268db68ef0f4704f4141ff84fcc15698142bd6594d7556239cf27776e9a" alt="Image" width="22%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_118_363_381_536.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2Fbd098268db68ef0f4704f4141ff84fcc15698142bd6594d7556239cf27776e9a" alt="Image" width="22%" />

\tan(\arctan x)

\arctan(\tan x) = x - \left[\frac{x + \pi}{T}\right]T

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_430_370_664_509.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2Facc2af794fc428185c74f7edff0dcacd94afe7ca73898b05f742891d2c694b7b" alt="Image" width="19%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_430_370_664_509.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2Facc2af794fc428185c74f7edff0dcacd94afe7ca73898b05f742891d2c694b7b" alt="Image" width="19%" />

 $ \frac{\pi}{2} $  $ \arcsin(\sin x) $

 $ \sin(\arcsin x) $

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_688_374_965_502.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2Fb16aae8eb234d6ce97ba1b984d4d80cf4a6076885fd50c8968caf7d86663564f" alt="Image" width="23%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//2da4b7c2-5b39-4ed0-868c-39c4798fc0a6/markdown_4/imgs/img_in_image_box_688_374_965_502.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A53Z%2F-1%2F%2Fb16aae8eb234d6ce97ba1b984d4d80cf4a6076885fd50c8968caf7d86663564f" alt="Image" width="23%" />

 $ \pi \rightarrow \pi \arccos(\cos x) $
 $ \cos(\arccos x) $

</div>


</div>


 $$ =x-\left[\frac{x+\frac{9}{2}}{\pi}\right]\pi(x\neq(k+\frac{1}{2})\pi) $$ 

 $$ 1+\tan^{2}d=\frac{1}{\cos^{2}d} $$ 

 $$ 1+c o t^{2}d=\sin^{2}d $$ 

 $$ \sqrt{\sin^{2}d-\cos^{2}x}=\sqrt{1-\cos^{2}d-\cos^{2}x}=\sqrt{\sin^{2}x-\cos^{2}d} $$ 

和差化积  $ \sin\alpha+\sin\beta=2\sin\frac{\alpha+\beta}{2}\cos\frac{\alpha-\beta}{2} $

 $$ \sin\alpha-\sin\beta=2\cos\frac{\alpha+\beta}{2}\sin\frac{\alpha-\beta}{2} $$ 

 $$ \cos\alpha+\cos\beta=2\cos\frac{\alpha+\beta}{2}\cos\frac{\alpha-\beta}{2} $$ 

 $$ \cos\alpha-\cos\beta=-2\sin\frac{\alpha+\beta}{2}\sin\frac{\alpha-\beta}{2} $$ 

积化和差  $ \sin\alpha\cos\beta=\frac{1}{2}\left[\sin(d+\beta)+\sin(d-\beta)\right] $

 $$ \sin\alpha\sin\beta=-\frac{1}{2}\left[\cos(\alpha+\beta)-\cos(\alpha-\beta)\right] $$ 

 $$ \cos d\cos\beta=\frac{1}{2}\left[\cos(d+\beta)+\cos(d-\beta)\right] $$ 

反正切

证：令左边 $ a+b $，则 $ \tan(a+b)=\frac{xy}{1-xy} $

 $$ \arctan x + \arctan y = \begin{cases} \arctan\frac{x+y}{1-xy} & (x \leq 1) \\ \pi + \arctan\frac{x+y}{1-xy} & (x > 0, x \geq 1) \\ \pi + \arctan\frac{x+y}{1-xy} & (x \leq 0, x \geq 1) \end{cases} $$ 

 $ (arcsin $等做法与此类似)

特别地， $ \arctan x + \arctan \frac{1}{x} = \frac{\pi}{2} $ (x > 0)

常见化简： $ \cos^{4}x+\sin^{4}x=(\cos^{2}x+\sin^{2}x)^{2}-2\sin^{2}x\cos^{2}x=1-\frac{1}{2}\sin^{2}x=\frac{3}{4}+\frac{1}{4}\cos^{4}x $

## 四、坐标系变换

1. 平移设 $ 0^{\prime} $在xy的坐标为 $ (a,b) $，则新 $ \left[\frac{x}{y}\right]=\left[\frac{x}{y}\right]-\left[\frac{a}{b}\right] $

2. 逆转 $ \theta $  $ [X] = [\cos\theta, \sin\theta][X] $，即  $ [X] = [\cos\theta, -\sin\theta][X] $

证明： $ \left\{\begin{array}{l}\cos\varphi=\frac{x}{r},\sin\varphi=\frac{y}{r}\\\cos\varphi=\frac{x}{r},\sin\varphi=\frac{y}{r}\end{array}\right. $，由 $ \varphi=\theta+\varphi' $可得 $ x=r\cos\theta=r\cos(\theta+\varphi') $， $ \theta=\frac{r}{r} $变量 $ \rightarrow r\cos\varphi\cos\theta-r\sin\varphi\sin\theta=x\cos\theta-y\sin\theta $未知量

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//08a449e7-68ca-4376-abd5-a31ab705baa9/markdown_0/imgs/img_in_image_box_769_206_1045_403.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A36Z%2F-1%2F%2Ff863fead05eb1a5decbd29e8cd0a421be842b9a822fe94ff01c5d6195469a1d6" alt="Image" width="23%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//08a449e7-68ca-4376-abd5-a31ab705baa9/markdown_0/imgs/img_in_image_box_769_206_1045_403.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A36Z%2F-1%2F%2Ff863fead05eb1a5decbd29e8cd0a421be842b9a822fe94ff01c5d6195469a1d6" alt="Image" width="23%" />

 $ Y \uparrow $
 $ M(x, y) $
 $ y $
 $ p $
 $ D(x', y') $

</div>


</div>


同理  $ y = r\sin\varphi = r\cos\varphi'\sin\theta + r\sin\varphi'\cos\theta = x\sin\theta + y\cos\theta $ 例： $ xy = 1 $ 逆转  $ \frac{\pi}{4} $ 得  $ \frac{x^{2}}{2} - \frac{y^{2}}{2} = 1 $

3. 极坐标系  $ \gamma > 0, 0 \leq \theta < 2\pi $

(1) 过点  $ A(a, \alpha) $，倾角  $ \beta $ 的直线： $ \frac{a}{\sin[\pi-(\theta-\beta)]}=\frac{\rho}{\sin(\alpha-\beta)} $，即  $ \rho=\frac{a\sin(\alpha-\beta)}{\sin(\theta-\beta)} $

(2) 圆心  $ A(a, d) $，半径  $ \gamma $ 的圆： $ \gamma^{2} = \rho^{2} + a^{2} - 2a\rho \cos(\alpha - \theta) $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//08a449e7-68ca-4376-abd5-a31ab705baa9/markdown_0/imgs/img_in_image_box_549_484_763_624.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A36Z%2F-1%2F%2F552256584c8d9dfbe17935639aca1a60aeac06a50900be3590bebfda820ad630" alt="Image" width="17%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//08a449e7-68ca-4376-abd5-a31ab705baa9/markdown_0/imgs/img_in_image_box_549_484_763_624.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A36Z%2F-1%2F%2F552256584c8d9dfbe17935639aca1a60aeac06a50900be3590bebfda820ad630" alt="Image" width="17%" />

 $ A(a,d) $

 $ M(P,\theta) $

 $ P $

 $ Q $

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//08a449e7-68ca-4376-abd5-a31ab705baa9/markdown_0/imgs/img_in_image_box_816_481_1014_611.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A36Z%2F-1%2F%2F26d4635b93b244636c63d3adb26048dd8a7c0e9151ec4f7c6003a3741e15418f" alt="Image" width="16%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//08a449e7-68ca-4376-abd5-a31ab705baa9/markdown_0/imgs/img_in_image_box_816_481_1014_611.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A36Z%2F-1%2F%2F26d4635b93b244636c63d3adb26048dd8a7c0e9151ec4f7c6003a3741e15418f" alt="Image" width="16%" />

 $ A(a,\alpha) $

 $ M(P,\theta) $

</div>


</div>


## 五 有理根定理

对整数多项式  $ f(x)=a_{n}x^{n}+\cdots+a_{1}x+a_{0} $，若有理数  $ \frac{p}{q} $ (P、q 互斥) 为多项式的根，则必有：

P为常数项 $ a_{0} $的因数，q为首项系数 $ a_{n} $的系数.

特别地，若 $ a_{n}=1 $，则 $ q=\pm1 $，则根必为整数且为 $ a_{0} $的因数.

证：将 $ \frac{p}{q}(p,q $互乘代入 $ f(x)=0 $得 $ a_{n}P^{n}+\cdots+a_{1}PQ^{n-1}+a_{0}q^{n}=0 $，即： $ \left\{\begin{array}{l}a_{n}P^{n}=-q(a_{n+1}P^{n+}+\cdots+a_{n}Q^{n+})\\a_{0}Q^{n}=-p(a_{1}Q^{n+}+\cdots+a_{n+1}P^{n+})\end{array}\right. $

对①，因为P、q互质，故q为 $ a_{n} $的因数；对②同理，P为 $ a_{0} $的因数

# 高中知识

(1) 证明： $ x > -1, n \in N_{+} $ 时， $ (|t x |^{n} \geq |t n x|) $

(2)  $ n > 1, n \in N_{+} $ 时，证明： $  n! < \left( \frac{n+1}{2} \right)^{n}  $

解：(1) x=0 或 n=1 时取等. n=2 时显然. 设  $ n=k(k \geq 2) $ 时  $ (|x|)^{k}>1+kx $，当  $ n=k+1 $ 时  $ (|x|)^{k+1}>(1+kx)(1+x)=1+(k+1)x+kx^{2}>1+(k+1)x $. QED.

(2) 对比  $ K! < \left(\frac{k+1}{2}\right)^k $ 与  $ (k+1)! $  $ \leq \left(\frac{k+1}{2}\right)^{k+1} $，由  $ (k+1)! $ 满足  $ \frac{(k+1)^{k+1}}{2^k} $，下证  $ 2(k+1)^{k+1} < (k+2)^{k+1} $，即  $ (1 + \frac{1}{k+1})^{k+1} > 2 $。该式可由(1)证得，亦可令  $ t = k+1 > 2 $， $ F(t) = t \ln(1 + \frac{1}{t}) $ 求导  $ F'(t) = \frac{-1}{t(1+t)} < 0 \Rightarrow F'(t) \geq F(1 + \infty) = 0 \Rightarrow F(t) > F(y) = \ln 2 $

2. 证明对数均值不等式:  $ \frac{2ab}{a+b} < \sqrt{ab} < \frac{a-b}{\ln a-\ln b} < \frac{a+b}{2} < \frac{a^{2}+b^{2}}{2a} $

解.②③处等式可令 $ t=\frac{b}{a}>1 $，由 $ \sqrt{t}<\frac{t+1}{nt}<\frac{1+t}{2} $可证；若令 $ x=b $，将 $ a $视为常量亦可证

①④处等式显然. 另外，④可由 $ \frac{a-b}{\ln a-\ln b}=\frac{1}{\frac{1}{3}}(a<3<b) $得其 $ <b<\frac{a^{2}+b^{2}}{2a} $，更简洁

# 函数

## 一、反函数

1. 充分条件：严格单调 充要：单射  $ (x_{1} \neq x_{2} $ 时  $ f(x_{1}) \neq f(x_{2}) $ ) (作水平线，与  $ f(x) $ 至多一个交点)

2.  $ y = f(x) $ 与  $ x = f^{-1}(y) $ 图形重合， $ y = f(x) $ 与  $ y = f^{-1}(x) $ 关于  $ y = x $ 对称.

3.  $ f[f'(x)] = x $  $ f^{-1}[f(x)] = x $

4.  $ y=\ln(x+\sqrt{x+1}) $  $ \frac{x}{2} $  $ y=\frac{e^x-e^{-x}}{2} $ ①  $ \left\{\begin{array}{l} e^y=x+\sqrt{x+1} \\ e^{-y}=\sqrt{x+1}-x \end{array}\right.\Rightarrow x=\frac{e^y-e^{-y}}{2} $

②令 $ e^{x}=t $，则 $ 2y=t-t $， $ t=y+\sqrt{x+1} $（负值舍）， $ x=\ln(y+\sqrt{x+1}) $

 $$ y=\ln(x+\sqrt{x^{2}-1})(x\geq1)\xleftarrow{反}y=\frac{e^{x}+e^{-x}}{2}(x\geq0) $$ 

5.  $ y = f(x) $ 在  $ I_{x} $ 单调且连续，则  $ x = \varphi(0) $ 在对应区间  $ I_{y} $ 上连续且有相同的单调性

充分非必要. 反例:  $ F=(x-y)^{2} $ 在  $ (0,0) $ 处  $ F_{y}^{\prime}(0,0)=0 $

## 二、隐函数

但F=0可确定隐函数 $ y=x $

视为 $ F'(x,y) $ (对位置求偏导,视为常数)

1. 对 $ F(x,y)=0 $，当 $ F_{y}^{1}(x,y)\neq0 $时隐函数 $ y=f(x) $存在， $ \frac{dy}{dx}=-\frac{F_{x}(x,y)}{F_{y}^{1}(x,y)} $这与视 $ y $为函数的 $ 1\cdot F_{x}^{1}+\frac{dy}{dx}\cdot F_{y}^{1}=0 $不同，另外该式也证明了 $ \frac{dy}{dx}=-\frac{F_{x}^{1}}{F_{y}^{1}} $

2. 对 $ F(x,y,z)=0 $，当 $ F_{z}^{1}(x,y,z)\neq0 $时隐函数 $ z=f(x,y) $存在， $ \frac{\partial z}{\partial x}=-\frac{F_{x}^{1}(x,y,z)}{F_{z}^{1}(x,y,z)} $， $ \frac{\partial z}{\partial y}=-\frac{F_{y}^{1}(x,y,z)}{F_{z}^{1}(x,y,z)} $

切线方程： $  F_{x}^{\prime} \cdot (x - x_{0}) + F_{y}^{\prime} \cdot (y - y_{0}) = 0  $ 二阶导  $  y_{xx}^{\prime\prime} = -\frac{F_{x}^{\prime\prime} F_{y}^{\prime\prime}^{2} - 2F_{z}^{\prime\prime} F_{x}^{\prime\prime} F_{y}^{\prime\prime} + F_{z}^{\prime\prime} F_{x}^{\prime\prime} F_{y}^{\prime\prime}^{2}}{(F_{z}^{\prime\prime})^{3}}  $

⑥  $ [a,b]\setminus\{x\} $ 连续且  $ x=x_{0} $ 是第一类间断点，则  $ \{x\in[a,b]\} $ 有界（极限存在：有界性）

## 三、函数特性

1. 有界性  $ \exists M > 0, \forall x \in I, |f(x)| \leq M $

极限存在(是局部有界的充分非必要条件)(反例： $ \lim_{x \to a} \sin x $不存在但有界)

②  $ [a, b] $ 上连续  $ \Rightarrow $  $ [a, b] $ 上有界

③ $ (a,b) $内连续， $ \lim_{x\to a^{+}}f(x) $与 $ \lim_{x\to b^{-}}f(x) $存在 $ \Rightarrow $(a,b)内有界

2. 单调性  $ (x_{2}-x_{1})[f(x_{2})-f(x_{1})]>0 $

④有界函数的+,-x

⑤  $ f(x) $ 在有限区间 I 上有界  $ \Rightarrow f(x) $ 在 I 上有界

3. 奇偶性 D 关于原点对称且  $ \left\{\begin{array}{l} f(-x)=-f(x) \\  或 f(-x)=f(x) \end{array}\right. $  $ \forall f(x) $，有  $ f(x)=\frac{f(x)+f(-x)}{2} $ 偶  $ \frac{f(x)-f(-x)}{2} $ 奇

 $ f[\varphi(x)] $ 内偶则偶，内奇同外 求导一次，奇偶互换

4. 周期性  $ \exists T>0,\forall x\in D,x+T\in D $，有  $ f(x+T)=f(x) $  $ f(x) $: T，则  $ f(ax+b):\frac{T}{|a|} $  $ f(x) $: T，则  $ f'(x) $: T

f(x): T, 则  $ g[f(x)] $: 是周期函数

f(x): T 且  $ \int_{0}^{T} f(x) dx = 0 $, 则  $ \int_{0}^{x} f(t) dt = T $

遇分式先通分,  $ \angle CM (\frac{2}{3}, 1, \frac{1}{4}) $

 $ =1 (M (\frac{8}{3}, \frac{11}{3}, \frac{3}{4})) = \frac{24}{4} $

 $ 2\cos(\frac{8}{12},\frac{12}{12},\frac{3}{12})=\frac{24}{12}=2 $

5.  $ f(x) $ 可导  $ \Rightarrow $ 连续  $ \Rightarrow $ 可积  $ \Rightarrow $ 有界

6. 定义域  $ D_{f} $ domain 值域 range  $ R_{f} $

7. 有限区间： $ f'(x) $ 有界  $ \Rightarrow f(x) $ 有界.  $ f(x) $ 无界  $ \Rightarrow f'(x) $ 无界 无穷区间：没有  $ f $、 $ f' $ 有无界的结论（反例： $ \frac{f=x}{t=\frac{\sin x^{3}}{x}} $）

## 函数-A

1. (2012) 证明:  $ x \ln \frac{1+x}{1-x} + \cos x \geq 1 + \frac{x^{2}}{2} (-1 < x < 1) $

解：①令 $ f(x)=x\vert\frac{1+x}{x}+\cos x-1-\frac{x^{2}}{2} $为偶函数，故只用证 $ 0\leq x<1 $时 $ f(x)\geq0 $.

 $ f(x)=\ln\frac{1+x}{1-x}+\frac{2x}{1-x^{2}}-\sin x-x\geq0+2x-\sin x-x\geq0 $ 与  $ f(0)=0\Rightarrow f(x)\geq0 $

②同上，只用证 $ 0 \leq x < 1 $。注意到 $ \cos x \geq 1 - \frac{x^{2}}{2} $泰勒，故只用证 $ \ln \frac{14x}{x} \geq x $，求导显然。

2. 证明： $ \frac{\arctan x}{\ln(1+x)} \leq \frac{\sqrt{2}+1}{2} $ (x>0)

解：柯中：左边： $ \frac{\arctan x - \arctan 0}{\ln(1 + x) - \ln(1 + 0)} = \frac{1 + 3}{1 + 3^{2}} $ (370)，求导后易得  $ F(3)_{\max} = F(\sqrt{2} - 1) = \frac{\sqrt{2} + 1}{2} $

3.  $ \vert f(x)\vert $ 在  $ x_{0} $ 处取得最大值，证明： $ f(x) $ 在  $ x_{0} $ 处取得极值

证：① $ f(x)=0 $，则 $ |f(x)|\leq|f(x_0)|=0\Rightarrow f(x)\equiv0 $ 极小且极大值 ② $ f(x_0)>0 $， $ (i)f(x)\geq0 $，则 $ f(x)\leq f(x_0) $  $ (ii)-f(x)<0 $

则 $ f(x)<0<f(x_0) $ ③ $ f(x_0)>0 $同理 注意并不要求 $ f(x) $连续

注： $ f(x) $在 $ x_{1} $处取 $ \min $不能得出 $ f(x) $在 $ x_{1} $处取极值，如 $ f(x)=x $在 $ x_{1}=0 $处

# 极限与连续

## 一、函数极限

1. 邻域 $\mathcal{S}$ 邻域 $U(x_{0},\delta)=\{x\mid|x-x_{0}|<\delta\}$ 去心邻域 $U(x_{0},\delta)=\{x\mid0<|x-x_{0}|<\delta\}$

2. 定义  $ \lim_{x \to x_{0}} f(x) = A \Leftrightarrow \forall \varepsilon > 0, \exists \delta > 0 $ 当  $ 0 < |x - x_{0}| < \delta $ 时，有  $ |f(x) - A| < \varepsilon $ 与  $ f(x_{0}) $ 无关

 $ x \neq x_{0} $

右极限改为  $ 0 < x - x_{0} < \delta $  $ x \to \infty $ 改为  $ |x| > x $  $ f(x) \to \infty $ 改为  $ |f(x)| > M $

### 3. 超实数  $ R $ 与  $ x^* $ 与  $ \frac{1}{x^*} $

实数系R中，若 $ \forall n\in N $，均有 $ \vert x\vert<\frac{1}{n} $，则 $ x=0 $。描述不出它到0的距离到底是多少

若 $ \forall n\in N $，均有 $ \left|x\right|<\frac{1}{n} $且 $ x^{*}≠0 $，则 $ x^{*} $为非零无穷小量， $ \frac{1}{x^{*}} $为无穷大量.

超实数 $ x^{*} $

记  $ X^{*} = X_{0} + X^{*} = \text{std}(X^{*}) + [X^{*} - \text{std}(X^{*})] $，则  $ \lim_{x \to x_{0}} f(x) = A \leftrightarrow f(x) = A + d(x) \lim_{x \to x_{0}} d(x) = 0 $

光环 宋数(核) 非零无剂量 即X_{0} 即x^{*}  $ \lim_{x\rightarrow\infty}f(x) $: 控核运算 实数x_{0} 超实数x^{*}

以等价无穷小为例： $ \frac{1-\cos x}{x^{2}}=\frac{\frac{1}{2}x^{2}}{x^{2}}\cdot\frac{1-\cos x}{\frac{1}{2}x^{2}} $  $ \lim_{x\to0}\frac{1-\cos x}{x^{2}}=\lim_{x\to0}\frac{\frac{1}{2}x^{2}}{x^{2}}\cdot\lim_{x\to0}\frac{1-\cos x}{\frac{1}{2}x^{2}} $

趋核速度相同 实数运算(提出极限非0因式，恒等变形) 越核运算

### 4. 性质

唯一性 局部有界性  $ \exists M > 0, \delta > 0 $，使  $ 0 < |x - x_{0}| < \delta $ 时，有  $ |f(x)| \leq M $ 证： $ \vert f(x) - A \vert < \varepsilon $，则  $ \vert f(x) \vert = \vert f(x) - A \vert + A $

局部保号性若 $ \lim_{x\to x_{0}}f(x)=A>0 $，则 $ \delta>0 $，使 $ 0<|x-x_{0}|<\delta $时，有 $ f(x)>0 $。若 $ x_{0} $在 $ \mathbb{U} $内 $ f(x)\geq0 $且 $ \lim_{x\to x_{0}}f(x)=A $，则 $ A\geq0 $与A的距离无限小←超常数标准实数部分证： $ |f(x)-A|<\varepsilon $中取 $ \varepsilon=\frac{A}{2}\therefore f(x)>\frac{A}{2}>0 $

### 5.无穷小  $ f(x)=0(1)(x\rightarrow x_{0}) $

若  $ \lim_{x\to0}f(x)=0 $，则称  $ f(x) $ 为  $ x\to x_{0} $ 时的无穷小

①  $ f(x)=0 $  $ \rightarrow $ O 是最高阶的无穷小

② 极限趋于 0

 $ \lim\frac{d(x)}{B(x)}=\left\{\begin{aligned}&1& 等价  \\ &C\neq0& 同阶 \\ &0& 高阶 \\ &\infty& 低阶 \\ & 不存在& 不可比阶\end{aligned}\right. $

若  $ \lim\frac{d(x)}{[B(x)]^{k}}=C\neq0, k>0 $ , 则称  $ (x) $ 为  $ R^{k} $ 的  $ k $ 阶无穷小

 $$  存在 |f(x)|>M $$ 

## 6.无穷大一定无界，但无界还可能为无界变量

若 $ \lim\limits_{x\rightarrow0}\vert f(x)\vert>M(0,1) $，则称 $ f(x) $为 $ x\to x_{0} $时的无穷大 f(x)为无穷小且 $ f(x)\neq0 $时，无无穷大

### 7. 规则

①f、g极限均存在，则可+,-x÷(n÷0). f、g恰一个不存在，则f±g不存在极限，其余情况均为不可确定

②洛必达（去心邻域内可导）

③泰勒  $ f(x)=f(x_{0})+f'(x_{0})(x-x_{0})+\cdots+\frac{f^{(n)}(x_{0})}{n!}(x-x_{0})^{n}+O((x-x_{0})^{n}) $

④  $ \ln n \ll n^{\beta} \ll a^{n} \ll n! $  $ \ll n^{n} $ ( $ d, \beta > 0, a > 1, n \to +\infty $)  $ e^{-x} \ll \frac{1}{x^{d}} \ll \frac{1}{\ln^{p}x} $ ( $ d, \beta > 0, x \to +\infty $)

⑤  $ O(x^{m}) \pm O(x^{n}) = O(x^{\min\{m, n\}}) $ 无穷小次数越低越大  $ O(x^{m}) = O(kx^{m}) = k \cdot O(x^{m}) $  $ (k \neq 0) $

 $ O(x^{m}) \cdot O(x^{n}) = O(x^{m+n}) \cdot x^{m} \cdot O(x^{n}) = O(x^{m+n}) $

⑥夹逼 若  $ h(x) \leq f(x) \leq g(x) $,  $ \lim g(x)=A $,  $ \lim h(x)=A $, 则  $ \lim f(x) $ 存在且 = A.

不能改为 $ \lim[g(x)-h(x)]=0 $。反例： $ h=x+\frac{1}{x+1} $， $ f=x+\frac{2}{x+1} $， $ g=x+\frac{3}{x+1} $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//f100d86d-bf6f-4971-ae2b-1ecd792cec44/markdown_0/imgs/img_in_image_box_130_399_422_540.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A37Z%2F-1%2F%2F636808d44c52c30eda0e01b0cc6875918099273a10ea36781b441a1eff898516" alt="Image" width="24%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//f100d86d-bf6f-4971-ae2b-1ecd792cec44/markdown_0/imgs/img_in_image_box_130_399_422_540.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A37Z%2F-1%2F%2F636808d44c52c30eda0e01b0cc6875918099273a10ea36781b441a1eff898516" alt="Image" width="24%" />

 $ e\uparrow $  $ y=(1+\frac{1}{x})^{x}\uparrow $  $ y=(1+x)^{\frac{1}{x}}\downarrow $

</div>


</div>


⑧  $ \lim_{x \to 0^{+}} x^{\alpha} \ln^{\beta} x = 0 $ ( $ \alpha, \beta > 0 $)

⑨ 连续，则  $ \lim_{n\to\infty}x_n=x_0\Rightarrow\lim_{n\to+\infty}f(x_n)=f(x_0) $ 反例：单调性/连续性临界点左右两侧/值相同的x

单调且连续，则  $ \lim_{n\to\infty}x_n=x_0\Leftrightarrow\lim_{n\to+\infty}f(x_n)=f(x_0) $ 其单调可弱化为  $ f(x)=f(x_n) $ 在定义域内只有唯一解  $ x=x_n\Leftrightarrow $ 伯成立

单调且连续且  $ \{x_n\} $ 和  $ \{f(x_n)\} $ 均不以无穷为极限，则  $ \{x_n\} $ 收敛  $ \Leftrightarrow \{f(x_n)\} $ 收敛.  $ \{x_n\} $ 发散  $ \Leftrightarrow \{f(x_n)\} $ 发散

⑩  $ \{a_{n}\} $ 单调且某一子列  $ \{a_{n_{k}}\} $ 收敛，则  $ \{a_{n}\} $ 收敛

## 二、函数连续与间断

 $$ \lim\Delta y=\lim\Delta x\rightarrow0\cdot[-f(x+\Delta x)-f(x_{0})]=0 $$ 

1. 连续  $ f(x) $ 在点  $ x_{0} $ 的某一邻域内有定义且  $ \lim_{x\to x_{0}}f(x)=f(x_{0}) $，则称  $ f(x) $ 在点  $ x_{0} $ 处连续

设 $ f(x) $在 $ x_{0} $处连续且 $ f(x_{0})>0 $，则 $ \exists\delta>0 $使 $ |x-x_{0}|<\delta $时， $ f(x)>0 $

[a,b]上连续指a处右连续，b处左连续

一点处连续→该点附近连续

例： $ f(x)=x^{2}D(x) $ 仅在  $ x=0 $ 连续， $ D(x)= $ 无理数

前提： $ \hat{u}(x_{0},\delta) $内有定义且在 $ x_{0} $处不连续

2. 间断只看无定义点和分段点，区间端点不考虑间断

可去  $ \lim\limits_{x\to x_{0}}f(x)=A\neq f(x_{0}) $ 均存在

至少个

lim

不存在

跳跃  $ \lim_{x \to x_{0}} f(x) \neq \lim_{x \to x_{0}} f(x) $，与  $ f(x_{0}) $ 无关

无穷  $ \lim\limits_{x\to x_{0}}f(x) $ 与  $ \lim\limits_{x\to x_{0}^{+}}f(x) $ 至少一个为  $ \infty $

振荡  $ f(x) $ 振荡不存在

## 三、数列极限

可通过求解 $ \vert x_{n}-a\vert<\varepsilon $求出N

1. 定义  $ \exists a, \forall \varepsilon > 0, \exists N \in \mathbb{N}_{+} $，当  $ n > N $ 时， $ |x_{n} - a| < \varepsilon $ 恒成立，则  $ \lim_{n \to \infty} x_{n} = a $

2. 若  $ \{a_{n}\} $ 收敛，则其任何子列  $ \{a_{n}\} $ 也收敛，且  $ \lim_{k\to\infty}a_{n_k}=\lim_{n\to\infty}a_n $ 可通过逆否命递归发散

3.  $ \lim_{n\to\infty}a_n=A\Rightarrow\lim_{n\to\infty}|a_n|=|A| $  $ |a_n|+|A|\leq|a_n-A|<\varepsilon $  $ \lim_{n\to\infty}a_n=0 $  $ \Leftrightarrow $ $ \lim_{n\to\infty}|a_n|=0 $

### 4. 性质

唯一性 有界性 若 $ \lim_{n\to\infty}x_{n} $存在，则 $ \{x_{n}\} $有界

保号性 若  $ \lim_{n\to\infty}x_n=a>b $ ，则  $ \exists N>0 $ ，当  $ n>N $ 时，有  $ x_n>b $ 若  $ \{x_n\} $ 从某项起  $ x_n\geq b $ 且  $ \lim_{n\to\infty}x_n=a $ ，则  $ a\geq b $

### 5. 海涅定理(归结原则)

设 $ f(x) $在 $ \mathring{U}(x_{0},S) $内有定义，则 $ \lim_{x\to x_{0}}f(x)=A $  $ \Leftrightarrow $ 任何 $ \mathring{U}(x_{0},S) $内以 $ x_{0} $为极限的数列 $ \{x_{n}\}_{n\to\infty} $， $ \lim_{n\to\infty}f(x_{n})=A $

例： $ \lim_{x\to0}f(x)=A\Rightarrow\lim_{n\to\infty}f(\frac{1}{n})=A $  $ \lim_{x\to a}f(x)=A\Leftrightarrow x_{n}\to a $且 $ x_{n}\neq a $， $ \lim_{n\to\infty}f(x_{n})=A $

### 6. 来逼准则

$\exists n_{0}\in N_{4}$, 当$n>n_{0}$时, $y_{n}\leq x_{n}\leq z_{n}$, $\lim_{n\to\infty}y_{n}=a$, $x_{n\to\infty}^{lim}z_{n}=a$, 则 $k\lim_{n\to\infty}x_{n}$存在且 $a$.

如何放缩？ $ \left\{\begin{array}{l} n \cdot u_{\min} \leq u_{1} + u_{2} + \cdots + u_{n} \leq n \cdot u_{\max} \\ 1 \cdot u_{\max} \leq u_{1} + u_{2} + \cdots + u_{n} \leq n \cdot u_{\max} \quad (u_{i} \geq 0) \end{array}\right. $ 无限项在放缩时仍要保留其无穷的特性

### 7. 压缩映射

①若 $ \exists K\in(0,1) $使 $ \vert x_{n+1}-a\vert\leq k\vert x_{n}-a\vert $，则 $ \{x_{n}\} $收敛于 $ a $  $ 0\leq\vert x_{n+1}-a\vert\leq k\vert x_{n}-a\vert\leq\cdots\leq k^{n}\vert x_{1}-a\vert=0 $

②若 $ X_{mn}=f(x_n) $， $ a $是 $ f(x)=x $的唯一解且 $ \forall x $，有 $ |f(x)|\leq k<1 $，则 $ \{x_n\} $收敛于 $ a|x_{mn}-a|=|f(x_n)-f(x)|=|f'(x)||x_n-a|\leq k|x_n-a| $

### 8. 单调有界准则

 $ x_{n+1} = f(x_n) $  $ \left\{\begin{array}{l} f'(x) > 0 \Rightarrow \{x_n\} 单调 \\ f'(x) < 0 \Rightarrow \{x_n\} 不单调 \end{array}\right. $  $ \left\{\begin{array}{l} x_2 > x_1 \Rightarrow \{x_n\} \uparrow \\ x_2 < x_1 \Rightarrow \{x_n\} \downarrow \end{array}\right. $  $ \rightarrow x_3 = f(x_2) > f(x_1) = x_2 $ 此时夹推

此时多用单调有界

 $ \rightarrow $ 摆动(不等号逐个变号)，设  $ x_1 < x_2 $，则  $ x_3 = f(x_2) < f(x_1) = x_2 $，出现摆动

此时多用压缩映射原理

### 9. 收敛速度

不依赖于n的任意小的正数

数列极限定义里的 $ \varepsilon $不体现收敛速度，只体现收敛目的

例： $ \forall k \in N_{+}, \exists N, n > N $ 时  $ \left| x_{n} - a \right| \leq \frac{1}{2^{k}} $  $ \Leftrightarrow $  $ \{x_{n}\} $ 收敛于  $ a $

 $ \exists N, n>N $ 时  $ \left|x_{n}-a\right|\leq\frac{1}{n} $  $ \Rightarrow $  $ \{x_{n}\} $ 收敛于  $ a $ 反例:  $ x_{n}=a+\frac{1}{\sqrt{n}} $

10. 公式

10. 公式无穷时当写为上确果 $ \sin\{a_{n}, a_{n}\} $更准确

①  $ \lim_{n\to\infty}\sqrt[n]{a_{1}^{n}+a_{2}^{n}+\cdots+a_{m}^{n}}=\max\{a_{1},\ldots,a_{m}\}(a_{1\cdots m}均\geq0) $

 $ \lim_{n\to\infty}x_n=a\Rightarrow\lim_{n\to\infty}|x_n|=|a|\quad\lim_{n\to\infty}x_n=0\Leftrightarrow\lim_{n\to\infty}|x_n|=0 $

③ 若  $ \alpha \to 0 $,  $ \alpha \beta \to 0 $, 则  $ (1 + \alpha)^{\beta} - 1 \sim \alpha \beta $ 注： $ \alpha(x) $,  $ \beta(x) $ 是  $ x $ 的函数，简记为  $ d.\beta $。这是  $ (1 + x)^{\alpha} - 1 \sim \alpha x $ 的推广。若  $ \alpha \to 0 $,  $ \beta \to \infty $,  $ \alpha \beta \to A $, 则  $ \lim(1 + \alpha)^{\beta} = e^{A} $

若  $ -f(x) \sim x^{f} $,  $ g(x) \sim x^{g} $, 则  $ \int_{0}^{g(x)} f(t) dt \sim \int_{0}^{x^{g}} t^{f} dt = \frac{1}{f+1} x^{g(f+1)} $

#### 极限速查



<table border=1 style='margin: auto; word-wrap: break-word;'><tr><td style='text-align: center; word-wrap: break-word;'>tanx</td><td style='text-align: center; word-wrap: break-word;'></td><td style='text-align: center; word-wrap: break-word;'>$ a^x - 1 \sim x \ln d $  $ (|+x|)^{-1} \sim a^x $</td><td style='text-align: center; word-wrap: break-word;'>$ 1 - (\cos x)^d \sim \frac{d}{2} x^2 $</td></tr><tr><td style='text-align: center; word-wrap: break-word;'>arcsinx</td><td style='text-align: center; word-wrap: break-word;'></td><td style='text-align: center; word-wrap: break-word;'>$ \ln(x + \sqrt{1+x^2}) \sim x - \frac{x^3}{6} $</td><td style='text-align: center; word-wrap: break-word;'>$ (|+x|)^{\frac{1}{x}} - e \sim -\frac{e}{2} x $</td></tr><tr><td style='text-align: center; word-wrap: break-word;'>1.5  $ \sin x $</td><td style='text-align: center; word-wrap: break-word;'></td><td style='text-align: center; word-wrap: break-word;'></td><td style='text-align: center; word-wrap: break-word;'></td></tr><tr><td style='text-align: center; word-wrap: break-word;'>arctanx</td><td style='text-align: center; word-wrap: break-word;'></td><td style='text-align: center; word-wrap: break-word;'></td><td style='text-align: center; word-wrap: break-word;'></td></tr></table>

 $$ \lim_{n\to\infty}X^{n}=\left\{\begin{array}{ll}0&|x|<1\\  不存在&x=1\end{array}\right.\quad\lim_{n\to\infty}e^{nx}=\left\{\begin{array}{ll}0&x<0\\ 1&x=0\\ +\infty&x>0\end{array}\right.\quad\lim_{n\to\infty}n^{x}=\left\{\begin{array}{ll}0&x<0\\ 1&x=0\\ +\infty&x>0\end{array}\right.\quad\lim_{n\to\infty}nX^{2n}=\left\{\begin{array}{ll}0&|x|<1\\ +\infty&|x|\geq1\end{array}\right. $$ 

 $$ \lim_{x\to0^{+}}x^{a}=\left\{\begin{array}{ll}+\infty&a<0\\ 1&a=0\\ 0&a>0\end{array}\right. $$ 

出现 $ x^{n}, x^{n} $时应先同乘 $ x^{n} $化简，如 $ f(x)=\lim_{n\to\infty}\frac{x^{n+2}-x^{-n}}{x^{n}+x^{-n}}=\lim_{n\to\infty}\frac{x^{2n+2}-1}{x^{2n}+1}=\begin{cases}-1 & 0<|x|<1 \\ 0 & |x|=1 \\ x-1 & (x\neq0)\end{cases} $

# 极限与连续

##### ⑩ trick

1. 求极限化多为一  $ \ln x - 1 = \ln \frac{x}{e} $ 例： $ \lim_{x \to \infty} x \left[ \ln (e + \frac{1}{x}) - 1 \right] = \lim_{x \to \infty} x \left[ \ln \frac{e + \frac{1}{x}}{e} \right] = \lim_{x \to \infty} x \cdot \frac{1}{e x} = \frac{1}{e} $ 中值定理化一为多  $ \ln (1 + \frac{1}{x}) = \ln (x + 1) - \ln x $ 例：可证  $ \frac{1}{x + 1} < \ln (1 + \frac{1}{x}) < \frac{1}{x} $ (x > 0)

2. 拆项  $ \lim_{x \to 0} \left( \frac{1 + \sin x}{x} - \frac{1}{e^x - 1} \right) = \lim_{x \to 0} \left( \frac{1}{x} - \frac{1}{e^x - 1} \right) + \lim_{x \to 0} \frac{\sin x}{x} $

抓大来  $ \lim_{x \to -\infty} \frac{\sqrt{4x^2 + x - 1} + x - 1}{\sqrt{x^2 + \sin x}} = \frac{1}{1 \times 1} = -\frac{2x + x}{x} = 1 $ （一般方法为 I =  $ -\frac{\sqrt{4 + \frac{1}{x} - \frac{1}{x^2}} + 1}{-\sqrt{1 + \frac{1}{x^2}}} = \frac{-2 + 1}{1} $ 容易写漏负号）

化简  $ x - \sin x \cos x \cos 2x = x - \frac{1}{4} \sin 4x $

### 3. 等价无穷小代换原则

乘除 若  $ d \sim \alpha_{1}, \beta \sim \beta_{1} $，则  $ \lim \frac{d}{B} = \lim \frac{d_{1}}{B_{1}} $ 例： $ \lim_{x \to 0} (\arcsin x)^{\tan x} = e^{\lim_{x \to 0} \tan x \ln (\arcsin x)} = e^{\lim_{x \to 0} x \ln (\arcsin x)} = e^{\lim_{x \to 0} \sin \tan t} = e^{\tan t} = e^{\tan x} = e^{\tan x} = e^{\tan x} = e^{\tan x} = e^{\tan x} $

若  $ d \sim \beta $ 则不能换

加减 若  $ \lim \frac{d}{B} = A \neq 1 $，才有  $ d - \beta \sim d_{1} - \beta_{1} $；同理  $ \lim \frac{d}{B} = A \neq -1 $，才有  $ d + \beta \sim d_{1} + \beta_{1} $ （因为在高阶项可能有差异）

4. 无穷小中的x应视为 $ f(x) $

例： $ \lim_{x \to 0} \frac{\tan x - \sin(\tan x)}{x^{3}} = \lim_{x \to 0} \frac{\frac{1}{6}(\tan x)^{3}}{x^{3}} = \frac{1}{6} $ 这里将 $ x - \sin x \sim \frac{1}{6}x^{3} $中的x换为 $ \tan x $

## 6. 复合运算

设 $ \lim_{x\to x_{0}}g(x)=a,\lim_{u\to a}f(u)=A $，则 $ \left\{\begin{array}{l}g(x)\neq a\\f(u)\text{在}u=a\text{处连续}\end{array}\right.\Rightarrow\lim_{x\to x_{0}}f[g(x)]=A $

证：由已知可得  $ 0 < |u - a| < \delta_{1} $ 时  $ |f(u) - f(a)| < \varepsilon_{1} $， $ 0 < |x - x_{0}| < \delta_{2} $ 时， $ |g(x) - a| < \varepsilon_{2} $。

若  $ g(x) \neq a $，则可取  $ \varepsilon_{2} $ 使  $ 0 < |g(x) - a| < \varepsilon_{2} < \delta_{1} $，令  $ u = g(x) $，有  $ |f[g(x)] - f(a)| < \varepsilon_{1} $

若 f 在 u = a 处连续，则  $ g(x) \neq a $ 时同上， $ g(x) = a $ 时  $ \lim_{x \to +\infty} f[g(x)] = f(a) = \lim_{u \to a} f(u) $

② 设  $ u_{n} \in $ 有限区间 I，若  $ f(x) $ 在 I 上严格单调且  $ \lim_{n \to \infty} f(u_n) $ 存在，则  $ \lim_{n \to \infty} u_n $ 存在。反例：设正项数列  $ \{a_n\} $ 单调增加，且  $ \left\{\frac{\ln a_n}{a_n}\right\} \to 0 $，则  $ a_n \to -1 $ 或  $ a_n \to +\infty $。

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//f100d86d-bf6f-4971-ae2b-1ecd792cec44/markdown_3/imgs/img_in_image_box_887_1075_1031_1158.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A39Z%2F-1%2F%2F7719ce63cfea325768980b28c071a303a9370700332343c9f5979790931ef131" alt="Image" width="12%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//f100d86d-bf6f-4971-ae2b-1ecd792cec44/markdown_3/imgs/img_in_image_box_887_1075_1031_1158.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A39Z%2F-1%2F%2F7719ce63cfea325768980b28c071a303a9370700332343c9f5979790931ef131" alt="Image" width="12%" />

 $ x_{1} $  $ \rightarrow +\infty $

</div>


</div>


6. 存在极限：极限为有限值（∞属于不存在的情形）

7.  $ x_{n+1} = (x_n) $ 大观

恒成立  $ \left\{\begin{array}{l} x_{2} > x_{1} :  t \\ x_{1} > x_{2} :  \downarrow \end{array}\right. $

单调性  $ \left\{\begin{array}{l} ① f(x) \geq 0 \\ ② f(x) < 0 \end{array}\right. $ 非恒成立 考虑  $ n > N $ ( $ X_{N} $ 的范围可能比  $ X_{11} $ 小进而使其单调) 转③ (往往更简单)

③不等式放缩

① 放缩

有界性

②若已证 $ x_{n+1}\leq x_{n} $，则可由 $ f(x_{n})\leq x_{n} $解出 $ x_{n} $范围

 $ g(x_{n}, x_{n+1}) > C $ 模型

令  $ f(x)=g(x,x) $，一般有  $ c=\frac{f(x)_{\min}}{\max} $，则  $ g(x_{n},x_{n+1})>c=f(x)_{\max}\geq f(x_{n})=g(x_{n},x_{n}) $ 一般可消去  $ x_{n} $ 从而得  $ x_{n+1} $ 与  $ x_{n} $ 的大小关系

如： $ 0 < x_{n} < 1, (1 - x_{n+1}) x_{n} > 4 $ 有  $ (1 - x_{n+1}) x_n \geq (1 - x_n) x_n $ 即  $ x_n \geq x_{n+1} $,  $ \lim_{n \to \infty} \frac{1}{2} $

# 极限与连续-M

1.  $ \lim_{x \to 0} \left( \frac{2 - e^x}{1 + e^x} + \frac{\sin x}{|x|} - a[x] \right) $ 存在，求 a.

解： $ \lim_{x\to0^{-}}=2-1+a $  $ \lim_{x\to0^{+}}=\lim_{x\to0^{+}}\frac{2e^{-x}-1}{e^{-x}+e^{+}}+1=1 $ 则 $ |+a|=1 $ ∴ $ a=0 $

 $$ 3-11\equiv1 $$ 

2. 设  $  f(x) \in C[-\ell, \ell]  $，在  $  x = 0  $ 处可导且  $  f'(0) \neq 0  $，不难证明： $ \forall x \in (0, \infty) $，至少  $ \exists \theta \in (0, \infty) $ 使  $ \int_{0}^{x} f(t) dt + \int_{0}^{-x} f(t) dt = x $  $ [f(\theta x) - f(-\theta x)] $ 请说明下述做法的错误：同除  $ x $，则  $ \int_{0}^{x} f(t) dt + \int_{0}^{-x} f(t) dt = f(\theta x) - f(-\theta x) $，由洛必达法在  $ x \to 0^{+} $处

解: 不妨考虑简单命题:  $ x \neq 0 $,  $ x^{2} = 2\theta x^{2} $，同除  $ x: \frac{x^{2}}{x} = 2\theta x \Rightarrow 2x = 2\theta x \Rightarrow \theta = 1 $。问题出在①处，因为取极限过程需要两边同时进行，①应该为  $ \lim_{x \to 0} + \frac{x}{x} = \lim_{x \to 0} 2\theta x \Rightarrow 2x = 0 $，① 错在右边没有同时  $ \lim $ 反思：① 不要省步骤 ② 没有同阶的时候等式两侧为 0 = 0 或  $ 0 = \infty $，求不出参数，同时参数的影响才会体现出来。这里是  $ k(0) = 0 $，在  $ k(0) $ 时即可体现差异。若  $ k(0) = 0 $，则应考虑  $ k'(0) $ 的形式。

3.  $ f(x)=\frac{(x+1)(x-1)}{e^{\frac{1}{x-2}}\ln|x|} $ 的可去间断点的个数为() A.1 B.2 C.3 D.4

解:  $ \lim_{x\to0}f(x)=0\quad\lim_{x\to1}f(x)=\begin{cases}2e(1^x),&x\geq-2\sqrt[3]{e},\\-2e(1^{-x}),&x<0\end{cases}=-2\sqrt[3]{e} $  $ \lim_{x\to1}f(x)=\begin{cases}0,&x\geq1\\-\infty,&x<0\end{cases} $

# 极限与连续-A

 $$ 1.(1998\cdot\text{三})\lim\limits_{x\rightarrow1}(1-x^{2})\tan\frac{\pi}{2}x $$ 

解: ①洛:  $ L = \lim_{x \to 1} 2 \cdot \frac{\tan \frac{\pi}{2} x}{\frac{1}{1 - x}} = \pi \lim_{x \to 1} \frac{(1 - x)^2}{\cos^2 \frac{\pi}{2} x} = \pi \lim_{x \to 1} \frac{2(x - 1)}{2 \cos \frac{\pi}{2} x \cdot (-\frac{\pi}{2}) \sin \frac{\pi}{2} x} = -2 \lim_{x \to 1} \frac{x - 1}{\cos \frac{\pi}{2} x} = \frac{4}{\pi} \lim_{x \to 1} \frac{1}{\sin \frac{\pi}{2} x} = \frac{4}{\pi} $

②有理运算要彻底：①中难在 $ \tan $洛后仍复杂，考虑出 $ Hx=2 $的思路，将加 $ \frac{\pi}{2}x $也拆开，即

 $ L=\lim_{x\to1}(1+x)(1-x)\frac{\sin\frac{\pi}{2}x}{\cos\frac{\pi}{2}x}=2\lim_{x\to1}\frac{1-x}{\cos\frac{\pi}{2}x} $，恰为①

 $$ \textcircled{3}\tan\frac{\theta}{2}=\frac{\sin\theta}{1+\cos\theta}=\frac{1-\cos\theta}{\sin\theta}\quad L=2\lim_{x\to0}\left(-x\right)\tan\frac{\pi}{2}(x+1)\textcircled{1}2\lim_{x\to0}\frac{x\sin\pi x}{1-\cos\pi x}=2\lim_{x\to0}\frac{\pi x^{2}}{\frac{1}{2}x^{2}}=\frac{4}{\pi}\textcircled{1}处\quad\tan\frac{\pi}{2}(x+1)=\frac{\sin(\pi(x+1))}{1+\cos(\pi(x+1))} $$ 

教训：由于 $ \tan\frac{\pi}{2}x\rightarrow\infty $，本身不宜等价无穷小；故用 $ t=x-1 $代换后只能拆开\tan $为 $ \sin $， $ \cos $的组合，才能化简

 $$ \lim\limits_{x\rightarrow0}\frac{1-\cos x\cos2x\cdots\cos10x}{x^{2}} $$ 

解：①泰勒： $ \frac{1-(\vert1-\frac{x^{2}}{2}\vert)(1-\frac{4x}{2})\cdots(\vert1-\frac{100x^{2}}{2}\vert)}{x^{2}}=\frac{1}{2}\frac{10}{2^{23}}t^{2}=\frac{385}{2} $

②导： $ \frac{\sin x(\cos 2x - \cos 10x) + 2\sin 2x(\cos x - \cos 10x) + \cdots}{2x} = \frac{\sin x + 2\sin 2x + \cdots + \cos 10x}{2x} = \frac{1}{2} \cdot \frac{10}{2} \cdot i^{2} = \frac{385}{2} $

 $$ :L=\frac{1-\cos x+\cos x-\cos x\cos2x+\cos x\cos2x-\cdots-\cos x-\cos10x}{x^{2}}=\frac{1-\cos x}{x^{2}}+\cos x\frac{1-\cos2x}{x^{2}}+\cdots+\cos x-\cos2x\frac{1-\cos10x}{x^{2}}=\frac{1}{2}\frac{10}{21}t^{2}=\frac{385}{2} $$ 

3.  $ \lim_{x \to 0} \frac{e^{\tan(\sin x)} - e^x}{x^3} $

解：①  $ L = \lim_{x \to 0} \frac{e^x [e^{\tan(\sin x)} - x]}{x^3} = \lim_{x \to 0} \frac{\tan(\sin x) - x}{x^3} = \lim_{x \to 0} \frac{(x - \frac{x}{6}) + \frac{(x - \frac{x}{6})^3}{3} - x}{x^3} = -\frac{1}{6} + \frac{1}{3} = \frac{1}{6} $

②无穷小的x应视为f(x) =  $ \lim_{x \to 0} \frac{\tan(\sin x) - \sin x}{x^3} + \lim_{x \to 0} \frac{\sin x - x}{x^3} = \lim_{x \to 0} \frac{\tan(\sin x) - \sin x}{\sin^3 x} - \frac{1}{6} = \frac{1}{3} - \frac{1}{6} = \frac{1}{6} $

 $ 2k-4 $

4.  $ \lim_{n\to\infty}\cos\frac{x}{2}\cos\frac{x}{2^{2}}\cdots\cos\frac{x}{2^{n}} $

 $$ \textcircled{1}x=0,L=1\textcircled{2}x\neq0,L=\lim_{n\rightarrow\infty}\frac{\cos\frac{x}{2}-\cos\frac{x}{2^{n}}-2^{n}\sin\frac{x}{2^{n}}}{2^{n}\sin\frac{x}{2^{n}}}=\lim_{n\rightarrow\infty}\frac{\sin x}{2^{n}\sin\frac{x}{2^{n}}}=\frac{\sin x}{x}\lim_{n\rightarrow\infty}\frac{x}{2^{n}\sin\frac{x}{2^{n}}}=\frac{\sin x}{x} $$ 

5.  $ \lim_{n\to\infty}\frac{n^{n}}{n!} $

解①  $ L = \lim_{n \to \infty} \left( \frac{1}{n} \cdot \frac{2}{n} - \frac{n}{n} \right)^{\frac{1}{n}} = e^{\lim_{n \to \infty} \frac{1}{n} \cdot \sum_{i=1}^{n} \ln \frac{i}{n}} = e^{\int_{0}^{1} \ln x \, dx} = e^{-1} $ 遇连乘且分母为n，提进去

 $$ \textcircled{2} \ln L=\lim\limits_{n\rightarrow\infty}\frac{1}{n}\ln n!-\ln n=\lim\limits_{n\rightarrow\infty}\frac{1}{n}\sum_{i=1}^{n}\ln\frac{i}{n}=\int_{0}^{1}\ln x dx=-1\Rightarrow L=e^{-1} $$ 

6.  $ f(x)=\lim_{t\to x}\left(\frac{\sin x}{\sin t}\right)^{\frac{t}{\sin x-\sin t}} $ (x≠0), 求  $ f(x) $

解 $ f(x)=e^{\frac{t\ln\frac{\sin x}{\sin t}}{\sin x-\sin t}}=e^{\frac{t\frac{\sin x-\sin t}{\sin t}}{\sin x-\sin t}}=e^{\frac{t}{\sin t}}=e^{\frac{x}{\sin x}} $

 $$ f(x)=\left[(1+\frac{\sin x-\sin t}{\sin t})^{\frac{\sin t}{\sin x-\sin t}}\right]^{\frac{t}{\sin t}}=e^{\frac{t}{\sin t}}=e^{\frac{x}{\sin x}} $$ 

7.  $ \lim_{x \to +\infty} \left( \frac{1}{x} \cdot \frac{a^{x} - 1}{a - 1} \right)^{\frac{1}{x}} $ (a > 0, a ≠ 1)

解：不妨先利用题中所给a的范围估计 $ \lim_{x\to+\infty}Q<a<1 $时， $ a\to0 $，则 $ \sqrt[x]{(a-1)x}\to1 $。② $ a>1 $时， $ a^{x}\to+\infty $，则 $ \sqrt[x]{x(a-1)}\to0 $。

因此分范围讨论是必要的。由 $ e^{\frac{\ln x-1}{x}(a-0)}=\frac{e^{\frac{x}{a-1}}}{x}=e^{\frac{x}{a-1}}=e^{\frac{x}{a-1}}=\begin{cases}e^{\ln a} & (a>1)\\e^0 & (0<a<1)\end{cases}=\begin{cases}a & (a>1)\\1 & (0<a<1)\end{cases} $处可洛的原因：由 $ \ln $连续，则 $ \lim_{x\to+\infty}\ln x(a-1)=\ln\lim_{x\to+\infty}\frac{a-1}{x(a-1)}=\ln\lim_{x\to+\infty}\frac{a^x\ln a}{x-1}\to+\infty $。并且洛的时候先拆开： $ \frac{\ln|a-1|-hx-ln|a-1|}{x} $

8.(1) $ \lim_{n\to\infty}\left[\frac{1}{n^{2}}\sum_{k=1}^{n}k\ln(n+k)-\frac{n+1}{2n}\ln n\right] $ (2) $ \lim_{n\to\infty}\sqrt[n]{\frac{1}{2}\cdot\frac{3}{4}\cdots\frac{2n-1}{2n}} $

解：(1)①尝试凑定积分.  $ I=\lim_{n\to\infty}\frac{1}{n}\left[\sum_{k=1}^{\infty}\frac{k}{n}\ln(n+k)-\frac{n+1}{2}\ln n\right] $，其中 $ \ln(n+k) $缺少 $ \ln n $，注意到 $ \frac{n+1}{2}\ln n=\frac{n(n+1)}{2}\ln n=\frac{1}{n}\sum_{k=1}^{n}k\ln n $，则 $ I=\lim_{n\to\infty}\frac{1}{n}\left[\sum_{k=1}^{n}\frac{k}{n}\ln(n+k)-\sum_{k=1}^{n}\frac{k}{n}\ln n\right]=\int_{0}^{1}x\ln(kx)dx=\frac{1}{4} $

②单刀直入，为在 $ \ln(n+k) $中凑出 $ \ln(1+\frac{k}{n}) $，需减去 $ \ln n $，则 $ \frac{1}{n^{2}}\sum_{k=1}^{n}k\ln(n+k)=\frac{1}{n}\left[\sum_{k=1}^{n}k\left[\ln(n+k)-1\right]+\sum_{k=1}^{n}k\ln n\right] $，而后一项恰为 $ \frac{1}{n^{2}}\cdot\frac{n+1}{2}\ln n=\frac{n+1}{2n}\ln n $ 利用多余项拼凑和式

(2) 显然  $ I \leq 1 $，又  $ I = \sqrt{\frac{3}{2} \cdot \frac{5}{4}} \cdots \frac{2n-1}{2n-2} \cdot \frac{1}{2n} \geq \sqrt{\frac{1}{2n}} = 1 $ 知  $ I = 1 $ “平移”分子进行放缩

9.(高阶项的处理)(1) $ \lim_{x\to+\infty}\left[\left(x^{n}+x^{4}+1\right)^{m}-x\right]=b $，(2) $ 4,b\neq0 $，求 $ n,m,b $ (2)设 $ \lim_{n\to\infty}\frac{n^{2023}}{n^{d}-(n-1)^{d}}=\beta\neq0 $，求 $ d,\beta $

解：(1)由 $ n>4 $，则 $ x^{n}+7x^{4}+1\sim x^{n} $，因此 $ mn=1 $，由 $ b=\lim_{x\to+\infty}\left[\left(x^{n}+x^{4}+1\right)^{\frac{1}{n}}-x\right]=\lim_{x\to+\infty}x\left[(1+\frac{1}{x^{n}}+\frac{1}{x^{4}})^{n-1}\right]=\lim_{x\to+\infty}x\cdot\frac{1}{n}\left(\frac{1}{x^{4}}+\frac{1}{x^{n}}\right)\neq0 $ 得 $ n=5,m=\frac{1}{5},b=\frac{7}{5} $ (2) $ \beta=\lim_{n\to\infty}\frac{n^{2023}}{n^{d}\left[1-(\frac{1}{n}-\frac{1}{n})^{d}\right]}=\lim_{n\to\infty}\frac{n^{2023}}{n^{d}\cdot\frac{1}{n}}=\frac{1}{d}\lim_{n\to\infty}\frac{n^{2023}}{n^{d-1}} $，则 $ d=2024 $， $ \beta=\frac{1}{2024} $

提公因式化为  $ f(x)\left[g(x)-1\right] $ 的形式比正整数幂展开  $ (n-1)^{\alpha}=n^{d}-dn^{\alpha-1} $ 更通用

 $ 10^{\frac{(1)}{n+100}}\frac{\ln\left(\frac{\pi}{2}-\arctan x\right)}{\ln x} $ (2) $ \lim_{x\to+\infty}\left[\sqrt[3]{x^{3}+x^{2}+x+1}-\sqrt{x^{2}+x+1}\frac{\ln(e^{x}+x)}{x}\right] $

7. 思想类似于3.A.4(1中方法②)

解(1)洛. $ \angle=\lim_{x\to+\infty}\frac{1}{2-\arctan x}(-\frac{1}{1+x^{2}})^{\frac{1}{2}}=\lim_{x\to+\infty}\frac{\frac{1}{2}}{\arctan x-\frac{x}{2}}=\frac{1}{2} $ ①处若不先将转化为文，将会复杂很多： $ \lim_{x\to+\infty}\frac{x}{(x+1)\arctan x-x} $

 $ \lim_{x\to+\infty}\frac{1}{2x(a\arctan x-x)+1}=\lim_{x\to+\infty}\frac{x}{2(a\arctan x-x)+\frac{1}{x}}=\lim_{x\to+\infty}\frac{-\frac{1}{x}}{-\frac{1}{x}}=\frac{-1}{2-1}=- $

(2)考虑 $ \frac{\ln(e^{x}+x)}{x}=1+\frac{\ln(1+\frac{x}{e^{x}})}{x} $，则 $ \angle=\lim_{x\to+\infty}\sqrt{x^{2}+x^{2}+x+1}-\sqrt{x^{2}+x+1}-\lim_{x\to+\infty}\sqrt{x^{2}+x+1}\cdot\frac{\ln(1+\frac{x}{e^{x}})}{x}=\lim_{x\to+\infty}x\left(\sqrt[3]{1+\frac{1}{x}+\frac{1}{x-1}}-\sqrt{1+\frac{1}{x-1}}\right)=0 $

 $ \lim_{x\to+\infty}x\left[\frac{1}{3}\left(\frac{1}{x}+\frac{1}{x-1}\right)-\frac{1}{2}\left(\frac{1}{x}+\frac{1}{x-1}\right)\right]=\frac{1}{3}-\frac{1}{2}=-\frac{1}{6} $ ①处是将 $ \frac{\ln(e^{x}+x)}{x}\sim1 $严谨化

11. 证明： $ \lim_{x \to 0} \frac{\int_{0}^{x} \sin \frac{1}{x} \cos t^{2} dt}{x} $ 不存在

解:  $ I=\lim_{x \to 0} \sin \frac{1}{x} \lim_{x \to 0} \cos x^{2} = \lim_{x \to 0} \sin \frac{1}{x} $，取  $ x_{n} = \frac{1}{2n\pi} $， $ y_{n} = \frac{1}{2n\pi + \pi} $ 有  $ \lim_{n \to \infty} \sin \frac{1}{x_{n}} = 0 $， $ \lim_{n \to \infty} \sin \frac{1}{y_{n}} = 1 $，故  $ \lim_{x \to \infty} \sin \frac{1}{x} $ 不存在

12.  $ \lim_{x \to a} f(x) = \lim_{x \to a} g(x) = \lim_{x \to a} f'(x) = \lim_{x \to a} g'(x) = 0 $ 且  $ f'(x) \sim f(x) $,  $ g'(x) \sim g(x) $ (x \neq a), 证明: (1)  $ \lim_{x \to a} \frac{f(x)}{g(x)} = y $ 或  $ \lim_{x \to a} \frac{f(x)}{g(x)} = 0 $ 时  $ f(x) - g(x) \sim f'(x) - g'(x) $ (x > a) (2)  $ 0 < |x - a| < \delta $ 时,  $ f(x) - f'(x) > 0 $, 有  $ \lim_{x \to a} f(x) = \lim_{x \to a} \frac{g(x)}{f'(x)} - g'(x) $ (lim  $ \frac{f(x)}{g(x)} = 1 $

证：(1)  $ y \neq 0 $ 时  $ \lim_{x \to a} \frac{f-g}{x^2a} = \lim_{x \to a} \frac{f(1-\frac{x}{2})}{f^2(1-\frac{x}{2^2})} = \lim_{x \to a} \frac{1-\frac{x}{2}}{1-\frac{x}{2^2}} = \lim_{x \to a} \frac{1-\frac{x}{2}}{1-\frac{x}{2}} = 1 $ (2)  $ \lim_{x \to a} \frac{\ln f}{1-f^2} = \lim_{x \to a} \frac{x^2}{1-f^2} = 0 + 1 = 1 $  $ \lim_{x \to a} f^2 = \lim_{x \to a} e^2 = \lim_{x \to a} e $  $ g' = \lim_{x \to a} f + \ln f = \lim_{x \to a} e $  $ g' = \lim_{x \to a} f + \ln f = \lim_{x \to a} e $

13. 若  $ \{a_{n}\} $ 严格单增，则  $ \{a_{n}\} $ 无最大值；…减，…无最小值

证：设  $ \exists a_{k}=M $，由  $ a_{k+1}>a_{k}=M $，矛盾

注：① 非严格时令  $ a_{n} \equiv c $ 为反例（个或↓且有 min, Max）

②考查其余非单调数列时，若 $ \lim_{n\to\infty}a_n=k $落在有限项 $ [a_t,a_t] $中，则有 $ \min,M_{ax} $

14.  $ x_{n}=1+\frac{1}{\sqrt{2}}+\cdots+\frac{1}{\sqrt{n}}-2\sqrt{n} $，证： $ \lim_{n\to\infty}x_n $ 存在

证： $ X_{n+1}-X_n=\sqrt{\frac{1}{n+1}}-2\sqrt{n+1}+2\sqrt{n}=\frac{1}{\sqrt{n+1}}-\frac{2}{\sqrt{n+1}+\sqrt{n}}<0 $。又由 $ \sqrt{\frac{1}{k}}>\frac{2}{\sqrt{k}+\sqrt{k+1}}=2(\sqrt{k+1}-\sqrt{k}) $知 $ X_n>2\sqrt{n+1}-2-2\sqrt{n}>-2 $

#### 来逼

1. 求  $ \lim_{x \to +\infty} \frac{\int_{0}^{x} t \left| \sin t \right| dt}{x^2} $

解： $ \int_{0}^{n\pi} t \left| \sin t \right| dt = \int_{0}^{n\pi} (n\pi - t) \left| \sin t \right| dt = \frac{n\pi}{2} \int_{0}^{n\pi} \left| \sin t \right| dt = n^2\pi $，则  $ n\pi \leq x < (n+1)\pi $ 时，有  $ n^2\pi < \int_{0}^{x} t \left| \sin t \right| dt < (n+1)^2\pi $，则  $ \frac{n^2\pi}{(n+1)^2\pi^2} < I < \frac{(n+1)^2\pi}{n\pi} $，夹逼得  $ I = \frac{1}{\pi} $

2.(1)  $ \lim_{n \to \infty} \left( \frac{\sin \frac{\pi}{n}}{n+1} + \frac{\sin \frac{2\pi}{n}}{n+\frac{1}{2}} + \cdots + \frac{\sin \frac{n\pi}{n}}{n+\frac{1}{n}} \right) $

(2)  $ \lim_{n \to \infty} \frac{n}{n + \frac{1}{n+1}} \cdot \frac{1}{n + \frac{2\pi}{n}} $

解：(1) 放缩  $ \frac{1}{1+\frac{1}{n}} $ 为  $ (\frac{1}{1+\frac{1}{n}}, 1) $ 考虑  $ L = \lim_{n \to \infty} \frac{1}{n} \cdot \frac{1}{2n+1} \cdot \frac{\sin(\pi - \frac{1}{n})}{1 + \frac{1}{2n}} $，由  $ i \geq 1 $，则  $ L \geq \lim_{n \to \infty} \frac{1}{1 + \frac{1}{n}} \cdot \frac{1}{n} \cdot \frac{1}{2n+1} \sin(\pi - \frac{1}{n+1}) $

 $ = \lim_{n \to \infty} \frac{1}{1 + \frac{1}{n}} \cdot \int_{0}^{1} \sin n x \, dx = \frac{3}{2} $，由  $ \frac{1}{1 + n} > 0 $，则  $ L \leq \lim_{n \to \infty} \frac{1}{n} \cdot \frac{1}{2n+1} \sin \frac{\pi}{n} = \frac{3}{2} $，当然亦可理解为  $ \frac{1}{n+1} \leq \frac{1}{n+ \frac{1}{2}} \leq \frac{1}{n} $ 来放缩

(2) 放缩  $ i^2 + 1 $ 为  $ (i^2, (i+1)^2) $ 考虑  $ L \geq \lim_{n \to \infty} \frac{n}{n+1} \cdot \frac{1}{n + \frac{(n+1)^2}{n}} = \lim_{n \to \infty} \frac{n}{n+1} \cdot \frac{1}{n} - \frac{1}{n+1} + \frac{1}{n+ \frac{(n+1)^2}{n}} = \int_{0}^{1} \frac{dx}{1 + x^2} = \frac{\pi}{4} $

与  $ L \leq \lim_{n \to \infty} \frac{1}{n + \frac{2\pi}{n}} = \frac{\pi}{4} $，或者可以凑  $ \frac{n + \frac{2}{n}}{n + \frac{2}{n}} < \frac{n + 1}{n} < \frac{n + 1}{n + \frac{2}{n}} $

多了  $ i = 1 $ 少了  $ i = n + 1 $

结论：抓住分母中的主体部分与变化部分，同量级用积分，次量级先放缩再来逼或积分。例如 (2) 中考察  $ n $ 与  $ \frac{i^{2}+1}{n} $，取  $ i_{\max}=n $，由  $ \lim_{n\to\infty}\frac{n}{n+1}=1 $ 知同量级，故应在同量级上适当放缩，丢去  $ i^{2} $ 中的1不影响向量级，故可朝此方向放缩。(1) 中显然次量级，亦丢去  $ n+\frac{1}{i} $ 中的  $ \frac{1}{i} $

分母次数比分子高一次且分子、分母为齐次式时便于积分

3.  $ \lim_{n\to\infty}\frac{n!}{(a+1)(a+2)\cdots(a+n)}\quad(a>0) $

解： $ L=\lim_{n\to\infty}\frac{1}{a+1}\cdot\frac{2}{a+2}\cdots\frac{n}{a+n}=\lim_{n\to\infty}\frac{1}{a+1}\cdot\frac{1}{\frac{a}{2}+1}\cdots\frac{1}{\frac{a}{n}+1}\leq k^{n}=0 $，其中 $ \frac{1}{a+1}<\cdots<\frac{1}{n+1}\leq k<1 $

4. (1)  $ \lim_{n \to \infty} \frac{M^n}{n!} (M > 0) $ (2)  $ \lim_{n \to \infty} \frac{x_n}{n!} $，其中  $ x_n $ 有界

解：(1)  $ \exists k \in \mathbb{N}_+ $ 且  $ k \geq M $，则  $ | > \frac{M}{k+1} > \frac{M}{k+2} > \cdots $ 故  $ 0 < I < \frac{M}{1} - \frac{M}{k} (1, 1, \cdots) \frac{M}{n} < \frac{M}{k+1} \cdot \frac{1}{n} \to 0 $ (2)  $ |x_n| \leq M $

 $ \lim_{n \to \infty} \sqrt[n]{2 \cdot 4 \cdot 6 \cdots} \cdot \frac{(2n-1)}{2n} $ (2)  $ \lim_{n \to \infty} \frac{(2n)!!}{(2n+1)!!} $

 $ 5.(1) \quad \lim_{n \to \infty} \sqrt[n]{1 \cdot 3 \cdot 5 \cdots} \cdot \frac{(2n-1)}{2n} $

解：(1) T-2A8(2) (2)  $ a_n = \frac{2}{3} \cdot \frac{4}{5} \cdots \frac{2^n}{2n+1} > \frac{1}{2} \cdot \frac{3}{4} \cdots \frac{2n-1}{2n} = \frac{(2n-1)!!}{(2n)!!} = \frac{1}{2n+1} \cdot \frac{1}{a_n} $， $ a_n = \frac{2}{3} \cdot \frac{4}{5} \cdots \frac{2n}{2n+1} < \frac{3}{4} \cdot \frac{5}{6} \cdots \frac{2n+1}{2n+2} = 2 \cdot \frac{(2n+1)!!}{2n+2!!} = \frac{1}{n+1} \cdot \frac{1}{a_n} $，故  $ \frac{1}{\sqrt{2n+1}} < a_n < \frac{1}{\sqrt{n+1}} $，即  $ a_n \to 0 $

#### 递推数列

1.(求通)(1) $ x_{1}=2 $， $ x_{m+1}=2+\frac{1}{x_{n}}(n=1,2,\ldots) $，求 $ \lim_{n\to\infty}x_{n} $ (2)  $ f(x) $可微， $ 0<f(x)\leq\frac{1}{2+x^{2}} $， $ x_{0}=A $， $ x_{n}=f(x_{n-1})(n=1,2,\ldots) $，证明： $ \lim_{n\to\infty}x_{n} $存在

解：(1)令 $ a=2+\frac{1}{a} $，则 $ a=1+\sqrt{2} $（ $ \sqrt{2} $舍），注意到 $ \left|x_{n}-a\right|=\left|\frac{1}{2}+\frac{1}{x_{n-1}}\right|-\left(2+\frac{1}{a}\right) $

 $ \frac{1}{2^{n-1}}\left|x_{1}-a\right|\rightarrow0 $，则 $ \lim_{x\to\infty}x_{n}=a=1+\sqrt{2} $，夹缩映射时 $ x_{n} $ a都要换，否则①处变为 $ \left|x_{n}-(1+\sqrt{2})\right|=\left|2+\frac{1}{x_{n-1}}-(1+\sqrt{2})\right| $

 $ =\left|\frac{1+(1-\sqrt{2})x_{n-1}}{x_{n-1}}\right|=\left|\frac{(1+\sqrt{2})-x_{n-1}}{x_{n-1}-(1+\sqrt{2})}\right|\leq\frac{1}{2(1+\sqrt{2})}\left|x_{n-1}-(1+\sqrt{2})\right| $，在凑 $ \left|x_{n-1}-a\right| $时复杂很多

(2)① $ x_{n}-x_{n-1}=\left|f(x_{n-1})-f(x_{n-2})\right|\leq\frac{1}{2}\left|x_{n-1}-x_{n-2}\right|\leq\left(\frac{1}{2}\right)^{n-1}\left|x_{1}-x_{1}\right| $，由 $ \sum_{n=2}^{\infty}\left(\frac{1}{2}\right)^{n}x_{n} $收敛知 $ \sum_{n=2}^{\infty}(x_{n}-x_{n-1}) $收敛，则 $ \lim_{n\to\infty}x_{n} $存在

更进一步，设 $ \lim_{x\to\infty}x_n=a $，则 $ a=f(a) $。设 $ g(a)=x-f(x) $，则 $ g'(x)>0 $知 $ a $是 $ f(x)=x $的唯一实根

② $ \left|x_{n}\right|=\left|f(x_{n-1})\right|=\left|f(x_0)\right|+\lim_{x_0}\left|f(x_0)d x\right|=\left|f(x_0)\right|+\left|\int_{x_0}^{x_{n-1}}f(x)d x\right|\leq\left|f(x_0)\right|+\int_{-\infty}^{\infty}\frac{dx}{2+x^2} $，有界，又 $ f(x)>0 $知单调，故 $ \lim_{x\to\infty}f(x) $存在

③不妨设 $ f(a)=a^{2} $，则 $ \left|x_{n}-a\right|=\left|f(x_{n-1})-f(a)\right|=\left|f(x)\right|\left|x_{n-1}-a\right|\leq\cdots\leq\left|x^{n-1}\right|\left|x_{1}-a\right|=0\Rightarrow\lim_{x\to\infty}x_n=a $ ②处其实认为 $ f(x)=x $有解

证明如下： $ x\geq0 $ 时， $ f(x)-f(0)=\int_{0}^{x}f(t)dt\leq\int_{0}^{\frac{1}{x}}\frac{1}{2+x}dx=\frac{1}{\sqrt{2}}\arctan\frac{x}{\sqrt{2}} $，同理  $ x<0 $ 时， $ f(x)-f(0)\geq\frac{1}{\sqrt{2}}\arctan\frac{x}{\sqrt{2}} $

则 $ \left|f(x)-f(0)\right|\leq\frac{1}{\sqrt{2}}\arctan\frac{x}{\sqrt{2}}\leq\frac{\pi}{2\sqrt{2}}\Rightarrow f(x) $有界，因而 $ F(x)=f(x)-x $在 $ (-∞,+\infty) $至少一根（又 $ F>0 $知唯一）

③处类(以于:  $ f(0)=1 $,  $ f(x)=1 $, 证:  $ \lim_{x\to\infty}f(x)\leq1\geq\frac{\pi}{2} $, 这由  $ f(x)=f(0)+\int_{0}^{x}f(t)dt\leq1+\int_{0}^{\infty}\frac{1}{1+x^{2}}dx $ 可得

2.  $ \{x_{n}\} $， $ \{y_{n}\} $ 满足 $ \left\{\begin{array}{l}x_{1}=y_{1}=\frac{1}{2}\\x_{m+1}=\sin x_{m}\\y_{m+1}=y_{n}^{2}\end{array}\right. $，证明： $ n=1,2,\ldots $，证明： $ n=100 $时 $ y_{n} $是 $ x_{n} $的高阶无穷小。(2) $ \left\{\begin{array}{l}x_{1}=y_{1}=\frac{1}{2}\\x_{m+1}=1-\cos x_{m}\\y_{m+1}=y_{n}^{2}\end{array}\right. $，(n=1,2,\ldots)，证明： $ \lim_{n\to\infty}\frac{x_{n}}{x_{m}}=0 $

证明：(1) 令  $ Z_{n}=\frac{y_{n}}{x_{n}} $，由  $ \lim_{n\to\infty}\frac{z_{n+1}}{z_{n}}=\lim_{n\to\infty}\frac{y_{n+1}}{x_{n+1}}\cdot\frac{x_{n}}{y_{n}}=\lim_{n\to\infty}\frac{y_{n}^{2}}{x_{n}}\cdot\frac{x_{n}}{y_{n}}=0 $ 知  $ \lim_{n\to\infty}z_{n}=0 $

(2) 由泰勒知  $ \cos x > 1 - \frac{x^{2}}{2} $，故  $ x_{n+1} < \frac{x_{n}^{2}}{2} $，故  $ 0 < \frac{x_{n+1}}{x_{n+1}} < \frac{\frac{x_{n}^{2}}{2}}{x_{n}^{2}} = \frac{1}{2}\left(\frac{x_{n}}{x_{n}}\right)^{2} < \frac{1}{2}\left[\frac{1}{2}\left(\frac{x_{n}}{x_{n}}\right)^{2}\right]^{2} < \cdots < \left(\frac{1}{2}\right)^{2-1}\left(\frac{x_{1}}{x_{1}}\right)^{2n} \rightarrow 0 $

得到①后可以单独对  $ x_{n} $ 放缩。令  $ \Sigma_{1} = \frac{1}{2} $， $ \Sigma_{n+1} = \frac{3n^{2}}{2} $，则  $ \Sigma_{n} = 2^{n-1} $（数归）， $ x_{n} < \Sigma_{n} $，则  $ 0 < \frac{x_{n}}{y_{n}} < \frac{\Sigma_{n}}{y_{n}} = \frac{1}{2^{n-1-1}} \rightarrow 0 $

3.(19.数)设 $ a_{n}=\int_{0}^{1}x^{n}\sqrt{1-x^{2}}dx $ (n=0,1,...) 证明： $ \{a_{n}\} $单减且 $ a_{n}=\frac{n-1}{n+2}(n=2,3,\ldots) $ (2)求 $ \lim_{x\to0}\frac{a_{n}}{a_{n-1}} $

解：(1)  $ a_{n+1}-a_{n}=\int_{1}^{1}(x^{n+1}-x^n)\sqrt{1-x^2}dx<0 $ 由  $ a_{n}=\int_{1}^{\frac{\pi}{2}}\sin^{n}t\cos^{2}tdt=\int_{0}^{\frac{\pi}{2}}\sin^{n}tdt-\int_{0}^{\frac{\pi}{2}}\sin^{n+2}tdt=\int_{0}^{\frac{\pi}{2}}\sin^{n}tdt+\sin^{n}t\cos^{2}t|_{0}^{\frac{\pi}{2}}-\int_{0}^{\frac{\pi}{2}}(n+1)\sin^{n}t\cos^{2}tdt $

 $ \int_{0}^{\frac{\pi}{2}}\sin^{n}tdt=-(n+1)a_{n} $ 知  $ (n+2)a_{n}=\int_{0}^{\frac{\pi}{2}}\sin^{n}tdt $ 又由  $ \int_{0}^{\frac{\pi}{2}}\sin^{n}tdt=-\sin^{n}t\cos t\in\left[\frac{\pi}{2}+\frac{\pi}{2}\right] $ (n-1) $ \sin^{n+2}t=\cos^{2}t $ (n-1) $ a_{n-2} $ 故  $ a_{n}=\frac{n+2}{n+2}a_{n-2} $

(2) 由  $ \frac{n-1}{n+2} = \frac{a_n}{a_{n-2}} < \frac{a_n}{a_{n-1}} < \frac{a_n}{a_{n-1}} = ( $ 由夹通知  $ \lim_{n \to \infty} $

4. (14) 数)  $ 0 < a_{n} < \frac{\pi}{2} $,  $ 0 < b_{n} < \frac{\pi}{2} $,  $ \cos a_{n} - a_{n} = \cos b_{n} $ 且  $ \frac{\infty}{n+1} b_{n} $ 收敛证(1)  $ \lim_{n \to \infty} a_{n} = 0 $ (2)  $ \sum_{n=1}^{\infty} \frac{a_{n}}{a_{n}} $ 收敛

证：(1)①  $ \cos a_{n} - \cos b_{n} = a_{n} > 0 $ 故  $ 0 < a_{n} < b_{n} $，求通 ②  $ a_{n} = \cos a_{n} - \cos b_{n} < 1 + (\frac{b_{n}^{2}}{2} - 1) = \frac{b_{n}^{2}}{2} $，同样求通

(2)①  $ \lim_{n\to\infty}\frac{a_{n}}{b_{n}}=\lim_{n\to\infty}\frac{a_{n}}{2(1-\cos b_{n})}=\lim_{x\to0}\frac{x}{2(1-(\cos x-x))}=\frac{1}{2} $ ②  $ \frac{a_{n}}{b_{n}}=\frac{a_{n}(1-\cos b_{n})}{b_{n}(1-\cos b_{n})}<\frac{a_{n}}{b_{n}(1-\cos b_{n})}\cdot\frac{b_{n}^{2}}{2}<\frac{1}{2}\cdot\frac{a_{n}}{\cos a_{n}-\cos b_{n}}\cdot b_{n}=\frac{b_{n}}{2} $

③  $ \frac{Q_{0}}{R_{0}}=\frac{\cos a_{n}-\cos b_{n}}{b_{n}}=\frac{\sin x_{n}(a_{n}-2)}{\sqrt{a_{n}}}\leq\frac{\sin x_{n}}{b_{n}}\cdot b_{n}<\frac{x_{n}}{b_{n}} $ ④  $ \frac{Q_{3}}{b_{3}}=\frac{\cos a_{n}-\cos b_{n}}{b_{n}}=2\frac{\sin\frac{a_{n}+b_{n}}{2}\sin\frac{b_{n}+d_{n}}{2}}{\sqrt{a_{n}}}<\frac{2\frac{a_{n}+b_{n}}{2}}{2}=\frac{\sqrt{a_{n}-a_{n}}}{2\sqrt{a_{n}}}<\frac{2}{2\sqrt{a_{n}}}<\frac{2}{2\sqrt{a_{n}}} $

⑤由(1)知  $ \frac{a_{0}}{a_{0}}<\frac{2}{3} $ (Q≤  $ \frac{1}{3}a_{n}b_{n} $)

5.  $ f(x)=\frac{1}{2}\cos x-\frac{1}{3} $,  $ x_{1}=\frac{\pi}{3} $,  $ x_{NH}=f(x_{N}) $ ( $ n=1,2,\ldots $) 证明：(1)  $ \sum_{n=1}^{\infty}(x_{NH}-x_{N}) $ 绝敛 (2)  $ \lim_{n\to\infty}x_n=a\in(0,\frac{1}{6}) $

(3)  $ x_{n} \neq 0 $ ( $ n \in N_{+} $) 且  $ \sum_{n=1}^{\infty}\left(\frac{1}{x_{n}} - \frac{1}{x_{n+1}}\right) $ 绝对收敛

证：(1)  $ \vert X_{n+1}-X_{n}\vert \leq k^{n+1} $  $ \vert x_{2}-x_{1}\vert \leq k \leq \frac{1}{2} $ (2) 由收敛知  $ \lim_{n \to \infty} F(N)=f(x)-x $ 由  $ F^{1}<0, F(0)>0, F(\frac{1}{6})<0 $ 知唯一  $ a \in (0,\frac{1}{6}) $

(3)  $ x_{2} = -\frac{1}{12} $,  $ x_{3} = \frac{1}{2}\cos(-\frac{1}{12}) - \frac{1}{3} > \frac{1}{2}\cos\frac{\pi}{6} - \frac{1}{3} > 0 $. 下证  $ n \geq 3 $ 时  $ x_{n} > 0 $. 设  $ x_{n} > 0 $, 则由  $ -\frac{5}{6} \leq f(x) \leq \frac{1}{6} $ 知  $ 0 < x_{n} \leq \frac{1}{6} < \frac{\pi}{6} $

于是  $ x_{n+1} > \frac{\sqrt{3}}{4} - \frac{1}{3} > 0 $, 即  $ x_{n} > 0 (n \geq 3) $, 即  $ x_{n} \neq 0 (n \in \mathbb{N}_{+}) $ 由  $ \lim_{n \to \infty} \frac{|\frac{1}{x_n} - \frac{1}{x_{n+1}}|}{|x_{n+1} - x_n|} = \lim_{n \to \infty} \frac{1}{|x_n x_{n+1}|} = \frac{1}{a^2} $ 知绝欧

# 一元微分

## 一、导数的概念

1. 定义  $ \frac{dy}{dx}|_{x=x_{0}} = f'(x_{0}) = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_{0}+\Delta x)-f(x_{0})}{\Delta x} = \lim_{x \to x_{0}} \frac{f(x)-f(x_{0})}{x-x_{0}} $ 在x_{0}处可导/可微

2. 微分  $ \Delta y = f(x_{0} + \Delta x) - f(x_{0}) = A\Delta x + O(\Delta x) $ 曲线增量

 $ dy = A\Delta x = A\mathrm{d}x $ ( $ A = f(x_{0}) $) 切线增量

 $$ \Delta y-d y=0(\Delta x) $$ 

3. 可导  $ \Rightarrow $ 连续 可导  $ \Leftrightarrow $ 可微  $ \rightarrow $ 证：二者定义中的  $ \Delta y $ 代入即可

证：可导  $ \Rightarrow \lim_{\Delta x \to 0} f(x_0 + \Delta x) - f(x_0) = \lim_{\Delta x \to 0} f'(x_0) \cdot \Delta x = 0 \Rightarrow f(x_0) = \lim_{\Delta x \to 0} f(x_0 + \Delta x) $

4. 3种等价语句：①  $ f(x) $ 在点  $ x_{0} $ 处可导 ②  $ f(x) $ 在点  $ x_{0} $ 处导数存在 ③  $ f'(x_{0})=A $ (有限数)

5. 比  $ f(x) $ 有更强性质的  $ f'(x) $

①  $ \lim_{x\to x_{0}}\lim_{x\to x_{0}}f(x)=a\Leftrightarrow f(x) $ 在  $ \%_{0} $ 连续

 $$ \text{证:}f^{\prime}(x_{0})=\lim\limits_{x\rightarrow x_{0}}\frac{f(x)-f(x_{0})}{x-x_{0}}=\lim\limits_{x\rightarrow x_{0}}f^{\prime}(x)=a $$ 

 $ f(x) $可导且知 $ f'(x)=a\Rightarrow f'(x) $在 $ x_{0} $处连续

②介值性  $ f(x) $ 存在  $ \Rightarrow f(x) $ 有介值性  $ f'(x) $ 存在  $ \Rightarrow f'(x) $ 有介值性  $ \rightarrow $ 达布定理

③保号性  $ f(x) $ 存在且  $ \neq0 \Rightarrow f(x) $ 恒正或恒负 (由②可反证)  $ \Rightarrow f(x) $ 单调

④  $ f(x) $ 在  $ x_{0} $ 处存在  $ \Rightarrow $  $ \% $ 不可能是  $ f'(x) $ 的第一类间断点

⑤  $ f(x) $ 可导  $ \Rightarrow f(x) $ 连续或含有振荡间断点

⑥ 求导会使点之间的靠近程度降低 可导说明 Y 之间靠近的程度比 X 一样或更高

数直级一样→高阶无穷小

6.  $ \vert f(x)\vert $

①连续性  $ f(x) $ 连续  $ \Rightarrow $  $ |f(x)| $ 连续 (在点  $ \%0 $ 处)

②可导 设  $ f(x) $ 在  $ x_{0} $ 处可导，则  $ \left\{\begin{array}{l} f(x_{0}) \neq 0 \Rightarrow |f(x)| \text{可导且 } [f(x)]'|_{x=x_{0}} = \left\{\begin{array}{l} f'(x_{0}) \\ -f'(x_{0}) \end{array}\right. \quad f(x_{0}) > 0 \\ f(x_{0}) = 0 \Rightarrow |f(x)| \text{可导且 } [f(x)]'|_{x=x_{0}} = 0 \end{array}\right. $

7. 高阶导数

 $$ f^{\prime \left(n\right)}\left(x_{0}\right)=\lim_{x_{1} \to x_{0}} \frac{f^{\left(n\right)}\left(x\right)-f^{\left(n\right)}\left(x_{0}\right)}{x-x_{0}} $$ 

 $ f^{(N)}(x_{0}) $ 存在  $ \Rightarrow f^{(N)}(x)\sim f(x) $ 在  $ x_{0} $ 附近有定义且在  $ x_{0} $ 处连续

8. 切线

曲线上一点Q趋于某点P时，割线PQ的极限位置，若存在且唯一，则为切线

导数存在  $ \Leftrightarrow $ 切线存在  $ x_{0} $ 处左右切线不同  $ (f_{1}^{\prime}(x_{0})\neq f_{2}^{\prime}(x_{0}))\Rightarrow $ 不可导  $ (x_{0}\neq0) $

 $ \{f_{+}^{\prime}(x_{0})\neq f_{-}^{\prime}(x_{0})} $，则 $ f(x) $在 $ x_{0} $处不可导，没有切线

例： $ |x| $ 在 x=0 处无切线

①改写为 $ \left\{\begin{array}{l}x=t^{3}\\x=t\end{array}\right. $，则方向向量 $ \overrightarrow{c}=(3t^{2},1) $

例:  $ x^{\frac{1}{3}} $ 在 x=0 处切线 x=0

 $ f'(x_{0})=\infty $ 时有切线无导数

②改写为 $ F(x,y)=y^{3}-x=0 $，则 $ \overrightarrow{n}=(-1,3y^{2}) $  $ l=(-1,0) $为法线方向，故切线为竖直方向

9. 等式的传递性  $ \rightarrow $ 等式两侧性质一致

若 $ f(a)=g(a) $且 $ f(a) $可导，则 $ g(a) $可导.证： $ f'(a)=\lim_{h\to0}\frac{f(a+h)-f(a)}{h}=\lim_{h\to0}\frac{g(a+h)-g(a)}{h}=g(a) $

## 二、导数的计算

1.  $ (\ln|x|)^{\prime}=\frac{1}{x} $  $ [\ln(x+\sqrt{x+1})]^{\prime}=\frac{1}{\sqrt{x+1}} $

 $$ (c o t x)^{1}=-\frac{1}{\sin^{2}x}(s e c x)^{\prime}=\frac{\tan x}{\cos x}=s e c x\tan x(c s c x)^{\prime}=-\frac{1}{\sin x\tan x}=-c s c x\cot x $$ 

C开头的带负号

 $$ (\arcsin x)^{\prime}=\sqrt{\frac{1}{1-x^{2}}}\quad(\arccos x)^{\prime}=-\frac{1}{\sqrt{1-x^{2}}}\quad(\arctan x)^{\prime}=\frac{1}{1+x^{2}}\quad(\arccot x)^{\prime}=-\frac{1}{1+x^{2}} $$ 

2. 复合函数

 $ (f[g(x)])^{1}=\frac{df[g(x)]}{dx}=\frac{df[g(x)]}{d\theta(x)}\cdot g'(x) $ 若 $ f(u_{0}) $与 $ g(x_{0}) $都存在，则 $ \frac{df[g(x)]}{dx}=x_{0}=f[u_{0}]\cdot g(x_{0}) $ 若至少一个不存在， $ f[g(u)] $在 $ x=x_{0} $处并非一定不可导

### 3. 分段函数

①在分段点x_{0}用导数定义 ②用导数公式一般只用于非分段点，否则很容易忽略分段点导数不存在的情况

4. 反函数  $  (t^{-1})'(y) = \lim_{x \to +\infty} \frac{t^{-1}(y) - t^{-1}x_0}{y - y_0} = \lim_{x \to +\infty} \frac{x - x_0}{t(x_0 - t + x_0)} = \frac{1}{t + x_0}  $

 $$ \frac{d x}{d y}=\frac{1}{\frac{d y}{d x}}\quad\frac{d^{2}x}{d y^{2}}=-\frac{\frac{d y}{d x^{2}}}{(\frac{d y}{d x})^{3}}=-\frac{y^{4}}{(y)^{3}}\quad 证：\frac{d x}{d y^{2}}=\frac{d\frac{d x}{d y}}{d y}=\frac{d\frac{1}{d x}}{d x}\cdot\frac{d x}{d y}=-\frac{d^{2}x}{\left(\frac{d y}{d x}\right)^{2}}\cdot\frac{1}{d x} $$ 

### 5. 参数方程

 $ \left\{\begin{array}{l}x=x(t)\\y=y(t)\end{array}\right. $  $ \frac{dx}{dx}=\frac{y'(t)}{x'(t)} $  $ \frac{dy}{dx}=\frac{y^{4}x^{1}-y^{4}x^{4}}{(x^{4})^{3}} $ 正： $ \frac{dx}{dx^{2}}=\frac{d(\frac{y^{4}(t)}{x(t)})}{dx}=\frac{d(\frac{y^{4}}{x})}{dt}\cdot\frac{dt}{dx}=\frac{y^{4}x^{1}-y^{4}x^{4}}{(x^{4})^{2}}\cdot\frac{1}{x^{4}} $

若  $ \frac{dy}{dx}=\varphi(t) $，则  $ \frac{d^{2}y}{dx^{2}}=\frac{d\varphi(t)}{dt}\cdot\frac{dt}{dx}=\frac{\varphi'(t)}{x'(t)} $ 分子可写为  $ \left|y\right|^{x} $ 这与  $ \int e^{ax}\sin\beta x dx $ 很像

## 6. 对数求导法

设  $ y = f(x) > 0 $,  $  y' = (e^{my})^1 = e^{my}(\ln y)' = y(\ln y)'  $

### 7. 高阶导数

①  $ \left[\sin(ax+b)\right]^{(n)} = a^{n}\sin(ax+b+\frac{n\pi}{2}) $  $ \left[\cos(ax+b)\right]^{(n)} = a^{n}\cos(ax+b+\frac{n\pi}{2}) $  $ \left[(ax+b)^{(n)}\right] = d\beta(\beta-1)\cdot(\beta-1)(ax+b) $

 $ \left(\frac{1}{ax+b}\right)^{(n)} = \frac{(-1)^{n}a^{n}n!}{-(ax+b)^{n-1}}\rightarrow3项勾漏 \left[\ln(ax+b)\right]^{(n)} = \frac{(-1)^{n+1}a^{n}(n-1)!}{(ax+b)^{n}}\rightarrow\text{除}a^{n}\text{外，}n\text{均换为}n-1 $

②苯布尼兹公式  $ (uv)^{(n)}=\sum_{k=0}^{n}C_{n}^{k}u^{(n+k)}v^{(k)} $ 注： $ (u+v)^{(n)}=u^{(n)}+v^{(n)} $

③泰勒展开的唯一性  $ \frac{t^{(n)}(0)}{n!} $ 对应写出的展开式中  $ x^{n} $ 的系数

④奇偶性例： $ f(x)=\frac{1}{2^{x}+1} $，求 $ f^{(4)}(0) $。注意到 $ f(x)+f(-x)=1 $  $ \therefore f(x)-\frac{1}{2}+f(-x)-\frac{1}{2}=0 $  $ \therefore $构造 $ g(x)=f(x)-\frac{1}{2} $为奇函数  $ \therefore f^{(4)}(0)=g^{(4)}(0)=0 $

## 三、几何应用与物理应用

### 1. 极值

### 1. 极值  左右邻域均有定义，因此不考虑端点

横坐标

对 $ U(x_{0},\delta) $中 $ \forall x $均有 $ f(x)\leq f(x_{0}) $，则称点 $ x_{0} $为 $ f(x) $的极大值点， $ f(x_{0}) $为 $ f(x) $的极大值

必要：只有马主点，不可导点可能为 $ f(x) $的极值点 因为 $ f(x)-f(x_{0}) $为 $ x-x_{0} $的高阶无穷小不能说明 $ f(x)=f(x_{0}) $

充分1：设 $ f(x) $在 $ x_{0} $处连续， $ f(x_{0},\delta) $可导，若 $ \left\{\begin{array}{l}f(x)>0 \\ f(x)<0\end{array}\right. $  $ (x_{0}-\delta<x<x_{0}) $ 则 $ f(x) $在 $ x_{0} $处取得极大值

充分2：设 $ f(x) $在 $ x_{0} $处=P(可导且 $ f^{2}(x_{0})=0 $，若 $ f^{2}(x_{0})<0 $，则 $ f(x) $在 $ x_{0} $处取得极大值注意：极大值 $ \Rightarrow f^{1}(x_{0})\leq0 $

充分3: 设  $ f(x) $ 在  $ \mathbb{X}_{0} $ 处 n 阶可导且  $ f'(x_{0})=\cdots=f^{(n-1)}(x_{0})=0 $ 且 n 为偶数，若  $ f^{(n)}(x_{0})<0 $，则  $ f(x) $ 在  $ \mathbb{X}_{0} $ 处取得极大值

证明2:  $ f'(x)=\lim_{x\to x_0}\frac{f(x)}{x-x_0}<0 $ 由保号性可化为“充分”. 注:  $ \hat{u}(x_0)= $ 阶可导且  $ \lim_{x\to x_0}f''(x)<0 $ 亦可推, 用一阶泰勒(拉格朗日除项)可证

证明3: 令  $ n=2k\lim_{x\to x_{0}}\frac{f(x)-f(x_{0})}{(x-x_{0})^{2k}}=\lim_{x\to x_{0}}\frac{f^{\prime}(x)}{2k(x-x_{0})^{2k-1}}=\lim_{x\to x_{0}}\frac{f^{(2k+1)}(x)}{(2k)!(x-x_{0})}=\lim_{x\to x_{0}}\frac{f^{(2k+1)}(x)-f^{(2k)}(x)}{(2k)!(x-x_{0})}=\frac{f^{\prime}(x)}{2k!}<0\therefore\frac{f(x)-f(x_{0})}{(x-x_{0})^{2k}}<0 $ 即  $ f(x)f(x_{0}) $

### 2. 单调性  $ f(x_{0}) > 0 \Rightarrow x_{0} $ 邻域内↑

设  $  f \in C([a, b]) \cap D((a, b))  $，若  $ (a, b) $ 内  $  f'(x) \geq 0  $ 且等号仅在有限点处成立，则  $  f(x)  $ 在  $ [a, b] $ 上严格单调增加

3. 凹凸性  $ f'(x_0) > 0 \Rightarrow x_0 $ 邻域内凹  $ f(x_1 + \lambda_2 x_2) < \lambda_1 f(x_1) + \lambda_2 f(x_2) $ 且  $ \left\{\lambda_1 + \lambda_2 = 1\right\} $

 $ \cup f\left(\frac{x_{1}+x_{2}}{2}\right)<\frac{f(x_{1})+f(x_{2})}{2} $

 $ f(x_{0})+f'(x_{0})(x-x_{0})<f(x) $

 $ f''(x)>0 $

### 4. 拐点

##### 间断点不可能为拐点

连续曲线的凹弧与凸弧的分界点

必要：只有 $ f'(x_{0})=0 $，不存在 $ f'(x_{0}) $可能为 $ f(x) $的拐点

充分：设 $ f(x) $在 $ \chi_{0} $处连续， $ \hat{u}(x_{0},\delta) $可二阶导，若 $ \chi_{0} $左右邻域内 $ f''(x) $变号，则 $ (x_{0},f(x_{0})) $为 $ f(x) $的拐点

充分2: 设  $ t(x) $ 在  $ x_{0} $ 邻域内三阶可导，若  $ t'(x_{0})=0 $,  $ t'(x_{0})\neq0 $，则拐点  $ f''(x_{0})>0 $ 则左凸右凹

充分3：设 $ f(x) $在 $ x_{0} $处 $ n $阶可导，若 $ f'(x_{0})=\cdots=f^{(n)}(x_{0})=0 $且 $ n $为奇数且 $ f^{(n)}(x_{0})\neq0 $，则拐点

证明2:  $ f''(x_0)=\lim_{x\to x_0}\frac{f''(x)}{x-x_0}\neq0 $, 分  $ f''(x_0)>0 $, <0 讨论 (保别性) 证明3:  $ \lim_{x\to x_0}\frac{f''(x)}{(x-x_0)^2}\leq\lim_{x\to x_0}\frac{f^{(2x)}(x)}{(2k-1)(x-x_0)}=\frac{f^{(2k+1)}(x_0)}{(2k-1)!}\neq0 $

### 5. 结论

①可导点不可同时为极值点和拐点，不可导点才可能.

设  $  f(x) = (x - a)^{n} g(x)  $ ( $  n > 1  $) 且  $  g(a) \neq 0  $. 则  $ \left\{ \begin{array}{l} x = a \text{为极值}, n \text{偶} \\ (a, 0) \text{为拐点}, n \text{奇} \end{array} \right. $

③设  $ f(x)=(x-a_{1})\cdots(x-a_{k}) $，记  $ k_{1} $ 为  $ n=1 $ 的个数， $ k_{2} $ 为  $ n>1 $ 且得的个数，则极值点  $ k_{1}+2k_{2}+k_{3}-1 $ 个，拐点  $ k_{1}+2k_{2}+3k_{3}-2 $ 个

④设 $ f'(x)>0 $， $ a<x<b $， $ f(a)=f(b)=0 $，则 $ f(x)<0 $证： $ f'(x)=0 $而 $ f'(x)>0 $，故 $ (a,b) $上 $ f'(x)<0 $， $ (b,b) $上 $ f(x)>0 $

### 6. 最值

若 $ \forall x\in D $均有 $ f(x)\leq f(x_{0}) $，则称 $ f(x_{0}) $为 $ f(x) $的最大值

若 $ f(x) $在工上有最值点 $ x_{0} $，且 $ x_{0} $不是工的端点，则 $ x_{0} $是 $ f(x) $的一个极值点

求法：求驻点，不可导点， $ \lim_{x\to a^{+}}(f(x),\lim_{x\to b^{-}}(f(x)(I=f[a,b])) $，比较上述函数值

定义为 $ \epsilon_{n} $

若f(x)在I内连续且有唯一极值点 $ x_{0} $，则x_{0}为最值点。否则反例： $ \overrightarrow{x} $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//d724aa48-1ede-43e3-bf96-554fa9ff6155/markdown_0/imgs/img_in_image_box_916_334_992_377.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A51Z%2F-1%2F%2F9d73c382bf20ef0916fa5054eabbca0dcf7af3704d8bcb4af4d1995115db5cd8" alt="Image" width="6%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//d724aa48-1ede-43e3-bf96-554fa9ff6155/markdown_0/imgs/img_in_image_box_916_334_992_377.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A51Z%2F-1%2F%2F9d73c382bf20ef0916fa5054eabbca0dcf7af3704d8bcb4af4d1995115db5cd8" alt="Image" width="6%" />

$\uparrow n\downarrow$

</div>


</div>


7. 渐近线 参数方程看  $ t \rightarrow ? $ 时  $ x \rightarrow \infty $

铅直  $ \lim_{x\to x_{0}}f(x)=\infty $ 或  $ \lim_{x\to x_{0}^{-}}f(x)=\infty $  $ x_{0} $ 为无定义点/端点/分段点

水平  $ \lim_{x\to+\infty}f(x)=G $ 或  $ \lim_{x\to-\infty}f(x)=G $

斜  $ \lim\limits_{x\to+\infty}\frac{f(x)}{x}=a_{1}\neq0 $ 且  $ \lim\limits_{x\to+\infty}f(x)-a_{1}x=b_{1} $  $ ++\infty,-\infty $ 中某个若有水平就不会有斜

8. 曲率

 $$ k=\frac{|y^{\prime \prime}|}{(1+(y^{\prime})^{2})^{\frac{3}{2}}} $$ 

 $$ R=\frac{1}{k}(y\neq0) $$ 

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//d724aa48-1ede-43e3-bf96-554fa9ff6155/markdown_0/imgs/img_in_image_box_862_536_1011_664.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A51Z%2F-1%2F%2Fd1012cd84f1bac9ffb6d6244f4b8d39d27f367a0e8c06c490c20d5f0b9683894" alt="Image" width="12%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//d724aa48-1ede-43e3-bf96-554fa9ff6155/markdown_0/imgs/img_in_image_box_862_536_1011_664.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A51Z%2F-1%2F%2Fd1012cd84f1bac9ffb6d6244f4b8d39d27f367a0e8c06c490c20d5f0b9683894" alt="Image" width="12%" />

 $ f(x) $ 曲线

洗线

</div>


</div>


9. 物理应用

含S、V不含t  $ a(t)=\frac{dv}{dt}=\frac{dv}{ds}\cdot\frac{ds}{dt}=\frac{dv}{ds}\cdot V(t) $

导数定义：线密度  $ P(x) = m'(x) $ 电流强度  $ I(t) = Q'(t) $ 比热  $ C(T) = q'(T) $ 功率  $ P(t) = W'(t) $ 质量 电量 热量 工功

## 四、中值定理 由点来研究区间

1. 有界与最值定理  $ f \in C([a, b]) $，则  $ m \leq f(x) \leq M $

2. 介值定理  $ f \in C([a, b]) $,  $ m \leq \mu \leq N $, 则  $ \exists \xi \in [a, b] $, 使  $ f(\xi) = \mu $

3. 平均值定理  $ f \in C([a, b]) $,  $ a < x_{i} < b $, 则  $ \exists \xi \in [x_{i}, x_{n}] $, 使  $ f(\xi) = \frac{\sum_{i=1}^{n} f(x_{i})}{n} $

4. 零点定理  $ f \in C([a, b]) $,  $ f(a) \cdot f(b) < 0 $, 则  $ \exists \xi \in (a, b) $, 使  $ f(\xi) = 0 $

推论 实系数奇次方程

 $ f \in C((a, b)) $,  $ \lim_{x \to a} f(x) \cdot \lim_{x \to b} f(x) < 0 $, 则  $ \exists \xi \in (a, b) $, 使  $ f(\xi) = 0 $

5. 费马定理 点  $ t $ 在点  $ x_{0} $ 处可导且取极值，则  $ f'(x_{0})=0 $

6. 罗尔定理 开  $ f\in C([a,b])\cap D((a,b)) $ 且  $ f(a)=f(b) $，则  $ \exists S(a,b) $，使  $ f^{\prime}(s)=0 $

7. 拉格朗叶值定理开  $ f\in C([a,b])\cap D((a,b)) $，则  $ \exists\xi\in(a,b) $，使  $ f'(\xi)=\frac{f(b)-f(a)}{b-a} $  $ \xi=a+\theta(b-a) $ ( $ 0<\theta<1 $)

8. 柯西中值定理  $ \forall f\in C([a,b])\cap D((a,b)) $ 且  $ g'(x)\neq0 $，则  $ \exists S\in(a,b) $，使  $ \frac{f(3)}{g'(3)}=\frac{f(b)-f(a)}{g(b)-g(a)} $ 拉格朗日

9. 泰勒公式 f在x₀某邻域内n+1阶可导，对该邻域内Bx:  $ f(x)=f(x_0)+f'(x_0)(x-x_0)+\ldots+\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n+\left\{\frac{f^{(n)}(x)}{(n+1)!}(x-x_0)^n\right\}) $ f在x₀处n阶可导，存在x₀的一个邻域Bx:  $ f(x)=f(x_0)+f'(x_0)(x-x_0)+\ldots+\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n+\left\{\frac{f^{(n)}(x)}{(n+1)!}(x-x_0)^n\right\}) $

佩亚诺

 $ x_{0}=0 $时称为麦克劳林公式

 $$ e^{x}=1+x+\frac{x^{2}}{2!}+\cdots+\frac{x^{n}}{n!}+o(x^{n}) $$ 

下标从1开始

 $$ \ln(1+x)=x-\frac{x^{2}}{2}+\frac{x^{3}}{3}-\cdots+\frac{(-1)^{n+1}x^{n}}{n}+o(x^{n})-1<x\leq1 $$ 

 $$ \sin x=x-\frac{x^{3}}{3!}+\cdots+\frac{(-1)^{n}x^{2n+1}}{(2n+1)!}+o(x^{2n+1}) $$ 

 $$ \cos x=1-\frac{x^{2}}{2!}+\frac{x^{4}}{4!}-\cdots+(-1)^{n}x^{2n}\div(2n)!+o(x^{2n}) $$ 

 $$ \frac{1}{1-x}=4x+x^{2}+\cdots+x^{n}+o(x^{n})-1<x<1 $$ 

 $$ (1+x)^{d}=1+d x+\frac{d(d-1)}{2}x^{2}+\cdots+\frac{d(d-1)\cdots(d-n+1)}{n!}x^{n}+o(x^{n}) $$ 

 $$ \tan x=x+\frac{x^{3}}{3}+\frac{2x^{5}}{15}+\cdots $$ 

10. 拉格朗日余项  $ R_{n}(x) $  $ e^{\frac{x}{n(n+1)}} \times \frac{e^{\theta x}}{(n+1)!} \ln(1+x)\frac{(-1)^{n}}{(n+1)(1+\theta x)^{n+1}} \times \frac{(-1)^{n}}{(n+1)!} \frac{d(d-1)\cdots(d-n)}{(n+1)!} \frac{d^{n-n-1}}{x^{n+1}} $ 均有  $ 0 < \theta < 1 $

 $ \sin x \cdot \frac{(-1)^{n}\cos\theta x}{(2n+1)!} \times \frac{2^{n+1}}{\cos x} \cdot \frac{(-1)^{n+1}\cos\theta x}{(2n+2)!} \times \frac{2^{n+2}}{x^{n+2}} $

10. 推论

①阶数换根数若 $ f^{(n)}(x)=0 $至多有k个根，则 $ f(x)=0 $至多有 $ k+n $个根

②罗尔之构造

(i)乘积形式  $ f(x)f'(x) \rightarrow f'(x) $  $ [f'(x)]^{2} + f(x)f'(x) \rightarrow f(x)f'(x) $  $ -[f'(x)]^{2} + f(x)f''(x) \rightarrow \frac{f'(x)}{f(x)} $ 或  $ \ln f(x) $

(ii) 多项式形式 \(f'(x) + p(x)f(x) + q(x) \rightarrow e^{\int p(x)f(x)dx} + \int q(x)e^{\int p(x)dx} \rightarrow e^{\int q(x)dx} + \int q(x)e^{\int q(x)dx} + \int q(x)e^{\int q(x)dx} + \int q(x)e^{\int q(x)dx} = e^{\int p(x)p(x)} + e^{\int q(x)

③取点如： $ 0 < p < 1 $，取 $ q = \frac{p+1}{2} $有 $ 0 < p < q < 1 $，即在P与(之间取到一点

### 11. 常见反例

 $ f(x)=|x| $ 满足 $ \lim_{x\to0}f(x)-\frac{f(-x)}{x}=0 $但 $ f(0) $不存在  $ \quad f(x)=\begin{cases}1&x\neq0\\0&x=0\end{cases} $满足 $ \lim_{x\to0}\frac{f(2x)-f(x)}{x}=0 $但 $ f(0) $不存在

 $ f(x)=\left\{\begin{array}{l}x^{2}, & x \text{有理数}\\-x, & x \text{无理数}\end{array}\right. $ 只在 $ x=0 $处可导，其他点都不连续、不可导

 $ f(x)=\begin{cases}d x+x^{2}\sin\frac{1}{x}, & x\neq0 \\ 0, & x=0\end{cases} $ 在区间上可导，但 $ f(0)=d>0 $ 不能推出该点任何邻域内的单调性

 $ f(x)=\begin{cases}2-x^{2}(2\sin x),x\neq0\\2,x=0\end{cases} $ 在  $ x=0 $ 处有极大值，但左邻域不  $ \downarrow $ ，右邻域不  $ \downarrow $ （若  $ f $ 在  $ x_{0} $ 取极大，则  $ -f $ 在  $ x_{0} $ 取极小）

 $ f(x)=\begin{cases}x^{2}\sin^{2}x,x\neq0\\0,x=0\end{cases} $， $ f(0)=0 $ 但不是极值点，拐点

 $ x=0 $ (x_{0}=0是驻点)

#### 一元微分-P

1.(1) (导数零点定理) 设  $ f(x) $ 在  $ [a, b] $ 可导，证明： $ f_{+}(a) \cdot f_{-}^{\prime}(b) < 0 $ 时， $ \exists \xi (a, b) $，使  $ f^{\prime}(\xi) = 0 $

(2) (达布定理) 设  $ f(x) $ 在  $ [a, b] $ 可导， $ f_{+}(a) \neq f_{-}^{\prime}(b) $，证明：对任意  $ f \in F_{+}(a) $ 与  $ f_{-}^{\prime}(b) $ 之间  $ u, \exists \xi (a, b) $ 使  $ f^{\prime}(\xi) = u $

解：(1)不妨设 $ f_{+}^{\prime}(a)>0 $， $ f_{-}^{\prime}(b)<0 $，则 $ \lim_{x\to a^{+}}\frac{f(x)-f(a)}{x-a}>0 $，故 $ \exists\delta_{1}>0 $，在 $ (a,a+\delta_{1}) $有 $ f(x)>f(a) $。同理在 $ (-b-\delta_{2},b) $有 $ f(x)>f(b) $。因此 $ f(a) $， $ f(b) $均不是 $ f(x)_{\max} $，即最大值在 $ (a,b) $内取得，由费马定理知该点 $ f^{\prime}(\xi)=0 $

(2) 令  $  F(x) = f(x) - u x  $，不妨设  $  f_{+}^{\prime}(a) < u < t^{\prime}(b)  $，则  $  F_{+}^{\prime}(a) < 0  $， $  F_{+}^{\prime}(b) > 0  $，由 (1) 得  $  F^{\prime}(\xi) = 0  $，即  $  f^{\prime}(\xi) = u  $.

2.(1) 证明：若  $ F(x) $ 在  $ [x_{0}, x_{0} + \delta) $ ( $ \delta > 0 $) 连续，在  $ (x_{0}, x_{0} + \delta) $ 内可导，当  $ \lim_{x \to x_{0}^{+}} f'(x) $ 存在 A 时，有  $ F_{+}'(x_{0}) = A $

(2)  $ (x_{0} - \delta, x_{0}] $  $ (x_{0} - \delta, x_{0}) $  $ \lim_{x \to x_{0}^{-}} F'(x) $ 连续 A  $ F'(x_{0}) = A $

解: (1)  $ F_{+}^{\prime}(x_{0})=\lim_{x\to x_{0}^{+}}\frac{F(x)-F(x_{0})}{x-x_{0}}\stackrel{\text{洛}}{\longrightarrow}\lim_{x\to x_{0}^{+}}\frac{F(x)}{1}=A $ (2) 同(1)

注： $ \lim_{x\to x_{0}^{+}}F(x) $ 不存在时， $ F(x_{0}) $ 亦可能存在。如  $ F(x)=f_{0}^{x_{0}} $  $ x\neq0 $。 $ F(x)=2x\sin\frac{1}{x}-\cos\frac{1}{x} $， $ \lim_{x\to x_{0}}\frac{F(x)-F(x)}{x-x_{0}}=0 $ 知  $ F_{+}^{\prime}(0)=0 $ ①处亦可用拉中  $ F(x)(x-x_{0}) $， $ x_{0}<\xi<x $

注：若分段函数连续且导函数的极限存在，则不必用定义求单侧导数，即 $ f(x)=\frac{g(x),x^{x}}{(x+1)(x-x_{0})+x} $处连续，有 $ f(x)=g(x),f(x)=1 $

3 设  $ f(x) = u(x)v(x) $，证明： $ f'(x) = u'(x)v(x) + u(x)v'(x) $

解  $ f'(x)=\lim_{\Delta x\to0}\frac{f(x+x)-f(x)}{\Delta x}=\lim_{0\to0}\frac{u(x+x)v(x+x)-u(x)v(x+x)+u(x)v(x)-u(x)v(x)}{\Delta x}+\lim_{\Delta x\to0}\frac{u(x+x)-u(x)}{u(x)}v(x+x)+ $ 可导并连续，等于  $ v(x) $

 $ \lim_{\Delta x\to0}\frac{V(x+x)-V(x)}{\Delta x}=u'(x)V(x)+u(x)V'(x) $ 由答案反推变换

4.(原创)求F，使F中含有因式 $ f(x)+p(x)f(x)+Q(x) $

解：类似7-p-T_{1}的思想，注意到  $ e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} f'(x) + e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} p(x) f(x) + e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} q(x) = [e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} f(x)] + e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} Q(x) $

因此可令  $ F = e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} f(x) + \int q(x)e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} $，显然  $ F' = e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} [f'(x) + p(x)f(x) + q(x)] $

注：其中 $ e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} $可这样注意到：若 $ f'(x)+p(x)f(x)=0 $，则 $ \frac{f(x)}{x^{2}}+p(x)=0 $，即 $ \left[\ln f(x)\right]^{\prime}+\left[\rho_{Nx}dx\right]^{\prime}=0 $，即 $ \left[\ln f(x)+\ln e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}}\right]^{\prime}=0 $或由 $ F=f(x)q(x) $， $ F^{\prime}=f^{\prime}q+q^{\prime}f $知 $ f^{\prime}+p $应转为 $ f^{\prime}q+pq $，即 $ q^{\prime}=pq $，故 $ \ln|q|=\rho_{Nx}dx+c $，即 $ q(x)=c $。 $ e^{\frac{\rho_{Nx}dx}{\rho_{Nx}dx}} $

5 证明： $ f(x)=x^{2}D(x) $ 仅在  $ x=0 $ 处连续，仅在  $ x=0 $ 处可导，其中  $ D(x)=\left\{\begin{aligned}&1\quad x\in Q\\ &0\quad x\neq Q\end{aligned}\right. $ (狄利克雷，divichlet)

证： $ x\to0 $ 时， $ |f(x)|\leq x^{2}\to0 $，但  $ x=a\neq0 $ 时，总有无理数列  $ \{x\}\to a $，即  $ f(x)=0 $，亦有有理数列  $ \{x_{n}\}\to a $，即  $ f(x_{n})=a^{2} $ 由  $ a^{2}\neq0 $，则  $ \lim_{x\to0} $，不存在，即不连续，不可导。 $ f(0)=\lim_{x\to0}\frac{\sqrt[3]{x}(x-0)}{x-0}=0 $

注： $ f(x) $在 $ x=x_{0} $处连续  $ \Rightarrow $ 在 $ \mathring{u}(x_{0},\delta) $内连续  

(可导) (可导)

6.(原创)曲率curvature是描述平面曲线在某一点处弯曲程度的几何量，定义为：单位切向量相对弧长的变化率。依此求证  $ K=\frac{|y^{\prime}|}{(1+y^{\prime}^{2})^{\frac{3}{2}}} $ 并计算出曲率中心的坐标为  $ C_{x}=x-\frac{y^{\prime}(Hy)^{2}}{y^{n}}, C_{y}=y+\frac{1+y^{\prime}^{2}}{y^{n}} $

解：对于 $ y=y(x) $，切向量 $ \overrightarrow{c}=(1,y) $，法向量 $ \overrightarrow{n}=(-y^{\prime},1) $，由题知 $ k=\|\frac{d\overrightarrow{c}}{ds}\| $，其中 $ \overrightarrow{c}=\frac{(1,y^{\prime})}{\sqrt{1+y^{\prime}^{2}}} $

由 $ ds=\sqrt{(1+y^{\prime}^{2})dx} $知 $ \frac{dx}{dx}=\frac{dx}{ds}=\left(\frac{-\frac{1}{2}\cdot2\cdot y^{\prime}^{2}}{(1+y^{\prime}^{2})^{\frac{3}{2}}}\cdot\frac{y^{\prime\prime}\sqrt{(1+y^{\prime}^{2}-y^{\prime}\frac{y^{\prime}y^{\prime}}{1+y^{\prime}^{2}}}}{1+y^{\prime}^{2}}\right)\cdot\frac{1}{\sqrt{1+y^{\prime}^{2}}}=(-y^{\prime}y^{\prime\prime},y^{\prime\prime})\cdot\frac{1}{(1+y^{\prime}^{2})^{2}} $

故 $ k=\frac{\sqrt{y^{2}+1}(y^{\prime})^{2}}{(y^{\prime}^{2}+1)^{2}}=\frac{|y^{\prime}|}{1} $

则半径 $ R=\frac{(1+y^{\prime}^{2})^{\frac{3}{2}}}{1y^{\prime}^{4}} $，当 $ y^{\prime}>0 $时， $ (C_{x},C_{y}) $在该点上侧，故 $ (C_{x},C_{y})=\left(x,y\right)+R\cdot\overrightarrow{n}_{0} $，当 $ y^{\prime}<0 $时， $ (C_{x},C_{y})=\left(x,y\right)-R\cdot\overrightarrow{n}_{0} $，可统一为 $ (C_{x},C_{y})=\left(x,y\right)+R\cdot\overrightarrow{n}_{0}\cdot\operatorname{sign}(y) $，其中 $ \operatorname{sign}(y)=\frac{y^{\prime\prime}}{1y^{\prime}} $，再将 $ \overrightarrow{n}_{0}=\frac{1}{\sqrt{1+y^{\prime}^{2}}}\cdot(-y^{\prime}) $代入，则 $ R\cdot\overrightarrow{n}_{0}\cdot\operatorname{sign}(y)=\frac{(1+y^{\prime}^{2})^{\frac{3}{2}}}{1y^{\prime}^{4}}\cdot\frac{(-y^{\prime},1)}{\sqrt{1+y^{\prime}^{2}}}\cdot\frac{y^{\prime\prime}}{1y^{\prime}}\cdot\frac{(1+y^{\prime})^{2}}{y^{\prime}}\cdot(-y^{\prime},1) $

因此 $ (C_{x},C_{y})=\left(x,y\right)+\frac{1}{y^{\prime\prime}}(-y^{\prime},1) $

同理可得  $ x = g(y) $ 时  $ k = \frac{|x^2|}{|x + y|^2} $  $ \overrightarrow{t} = (x', y) $,  $ ds = \sqrt{x^2 + y^2} dy $  $ \left\{ \begin{array}{l} x = x(t) \\ y = y(t) \end{array} \right. $ 时  $ k = \frac{|y^2 x^2 - y^2 x^2|}{(x^2 + y^2)^2} $  $ \overrightarrow{t} = (x', y') $,  $ ds = \sqrt{x^2 + y^2} dt $

 $ y = r(\theta) $ 时  $ k = \frac{|r^2 + 2r^2 - r^2 r^2|}{(r^2 + r^2)^2} $ 视为  $ \left\{ \begin{array}{l} x = r \cos \theta \\ y = r \sin \theta \end{array} \right. $，则  $ x' = r^2 \cos \theta - r \sin \theta $ 代入上式即可

### 7.(三大可导充要条件)(1) $ f(x_{0})\neq0 $， $ f(x) $在 $ x=x_{0} $连续，则 $ f(x) $在 $ x_{0} $可导 $ \Leftrightarrow $  $ |f(x)| $在 $ x_{0} $可导

(2)  $ f(x)=0, f(x) $ 在  $ x=x_{0} $ 可导，则  $ f(x_{0})=0 \Leftrightarrow |f(x)| $ 在  $ x_{0} $ 可导

(3)  $  F(x) = g(x)\psi(x)  $,  $ \psi(x) $ 在 x = a 连续但不可导,  $  g'(a)  $ 存在, 则  $  g(a) = 0 \Leftrightarrow F(x)  $ 在 x = a 可导且  $  F'(a) = g'(a)\psi(a)  $

证: (1)  $ f(x_{0}) \neq 0 \Rightarrow f(x_{0}) > 0 $ 或 < 0, 又由保号性知  $ u(x_{0}, \delta) $ 内  $ f(x) $ 不变号  $ \Rightarrow (\lim_{x \to x_{0}^{+}} \geq 0, \lim_{x \to x_{0}^{-}} \leq 0) $

(2) 可导  $ \Leftrightarrow \lim_{x\to x_{0}}\frac{|f(x)|-|f(x_{0})|}{x-x_{0}} $ 存在  $ \Leftrightarrow \lim_{x\to x_{0}}\frac{|f(x)|}{x-x_{0}} $ 存在  $ \Leftrightarrow \lim_{x\to x_{0}}\frac{|f(x)|}{x-x_{0}}=0 \Leftrightarrow \lim_{x\to x_{0}}\frac{|f(x)-f(x_{0})|}{x-x_{0}}=0 \Leftrightarrow f(x_{0})=0 $

(3) ①  $  g(a) = 0  $ 时,  $  F'(a) = \lim_{x \to a} \frac{g(x) \varphi(x)}{x - a} = \lim_{x \to a} \frac{g(x) - g(a)}{x - a} \varphi(x) = g(a) \neq 0  $ 时,  $  \varphi(x) = \frac{F(x)}{g(x)}  $ 在  $  x = a  $ 可导, 矛盾 (设  $  F  $ 在  $  x = a  $ 可导)

# 中值定理

## 一、构造函数

1. 对于  $ f'(x) + p(x)f(x) + Q(x) $，构造  $ F(x) = e^{\int p(x) dx} f(x) + \int Q(x)e^{\int p(x) dx} $

如： $ f'(x) + t^2(x) \rightarrow F = f(x)e^{\int t^2(t)dt} $ (视  $ f(x) $ 为  $ P(x) $)  $ f(x) $ 与  $ \int a^x f(t) dt $，令  $ g(x) = \int a^x f(t) dt $， $ g'(x) = f(x) $

一般地，可考虑如下形式的辅助函数： $ e^{yx}f(x) $  $ e^{\pm f(x)}g(x) $  $ f(x)\int a^x g(t) dt $  $ \int a^x f(t) dt\int a^x g(t) dt $  $ f'(x)g(x) - f(x)g'(x) $

2. 对于  $ f'(x) - f(x) = 0 $，构造  $ F = e^{x}[f'(x) - f(x)] $ 或  $ F = e^{-x}[f'(x) + f(x)] $

对于  $ \frac{f}{g} = \frac{f''}{g'} $，化为  $ fg'' - f''g = 0 $，构造  $ F = fg' - fg $

3. 含积分的，令其为 F，再用常规方式.

eg.  $ x_{1}f(x_{0})=\int_{x_{0}}^{1}f(x)dx $，令  $ F=\int_{x_{0}}^{1}f(x)dx $，则  $ -x_{0}F'(x_{0})=F(x_{0}) $，令  $ G=xF(x) $

 $$ f^{\prime}(x) \geqslant 0 \Leftrightarrow f\left(\frac{a+b}{2}\right) \leqslant \frac{\int_{a}^{b} f(x) dx}{2-a} \leqslant \frac{f(a) + f(b)}{2} $$ 

## 二、经典结论

1. (又中值)  $  f(x) \in C[0,1] \cap D(0,1)  $,  $  f(0) = 0, f(0) = 1  $, 在  $ [0,1] $ 严格个，证明： $ \exists \xi \in (0,1) $ ( $ \{x \in \mathbb{N}\} $, 使得  $ \frac{1}{f(x)} + \cdots + \frac{1}{f(\xi)} = n $)

证：显然  $ \exists 0 < C_1 < C_{n+1} \leq 1 $ 使  $  f(x_1) = \frac{n+1}{n}, \ldots, f(x_{n+1}) = \frac{n+1}{n}  $ (仅值)，由拉中  $ \left\{\begin{array}{l} f(x_1) = -f(0) = -f(\xi_1) - C_1 \\ f(x_1) = -f(0) = -f(\xi_1) - C_1 \end{array}\right. $

 $  f(\xi_1) = n C_1, \ldots, n C_n  $

 $  f(\xi_n) = n(1 - C_n)  $，相加得  $ \frac{1}{f(\xi_1)} + \cdots + \frac{1}{f(\xi_n)} = n $

 $ 2. (=0) \left\{ f(x) \in D[0,1], f(0)=0, \text{又} |f(x)| \leq p |f(x)| \right. $ (0<p<1), 证明： $  f(x) \equiv 0  $ (0<x≤1)

证：记 $ M=\max_{0\leq x\leq1}\left|f(x)\right|=\left|f(c)\right| $，则 $ M=\left|f(c)\right|=\left|f(c)-f(0)\right|=\left|f(1)\right|\cdot C\leq\left|f(1)\right|\leq PM\Rightarrow M=0\Rightarrow f(x)\equiv0 $

3.  $ \left(\vert f'(s)\vert\right)f(x)\in D^{2}[a,b] $ 且  $ f'(a)=f'(b)=0 $，证明： $ \exists s\in(a,b) $，使得  $ \vert f''(s)\vert\geq\frac{4\vert f(b)-f(a)\vert}{(b-a)^{2}} $

证： $ \left\{\begin{array}{l}f(a)+\frac{f^{\prime}(s)}{2}\left(\frac{a+b}{2}-a\right)^{2}(a<s<\frac{a+b}{2}<s<b), 相减得 f(b)-f(a)=\frac{(b-a)^{2}}{8}\left[f^{\prime}(s)-f^{\prime}(s_{2})\right], 即 \\ f(b)+\frac{f^{\prime}(s)}{2}\left(\frac{a+b}{2}-b\right)^{2}\end{array}\right. $

 $ \vert f(b)-f(a)\vert\leq\frac{(b-a)^{2}}{8}\left[\vert f^{\prime}(s)\vert+\vert f^{\prime}(s_{2})\vert\right] $，取  $ s=\arg\max\left\{\vert f^{\prime}(s)\vert,\vert f^{\prime}(s_{2})\vert\right\} $

4.(凸凹性) $ f(x)\in C[a,b] $， $ f''(x)>0 $，取前 $ \in[a,b] $ ( $ |x|\leq n $)，设 $ k_{1}>0 $且 $ \frac{n}{k_{1}}=1 $，证明： $ f\left(\frac{n}{k_{1}}k_{1}x_{1}\right)\leq\frac{n}{k_{1}}k_{1}+f(x_{1}) $

证：令 $ x_{0}=\frac{n}{k_{1}}k_{1}x_{1} $，由 $ f^{n}(x)>0 $，则 $ f(x)=f(x_{0})+f'(x_{0})(x-x_{0}) $，因此有

 $ \left\{\begin{array}{l}f(x_{0})=f(x_{0})+\frac{n}{k_{1}}k_{1}x_{1}(x_{1}-x_{0})\\f(x_{0})=f(x_{0})+\frac{n}{k_{1}}k_{1}x_{1}(x_{1}-x_{0})\\f(x_{0})=f(x_{0})+\frac{n}{k_{1}}k_{1}x_{1}(x_{1}-x_{0})\\\end{array}\right.\Rightarrow\left\{\begin{array}{l}k_{1}f(x_{0})=k_{1}f(x_{0})+k_{1}f(x_{0})(x_{1}-x_{0})\\\vdots\\k_{n}f(x_{0})=k_{n}f(x_{0})+k_{n}f(x_{0})(x_{1}-x_{0})\\\end{array}\right. $ 相加得 $ \frac{n}{k_{1}}k_{1}f(x_{0})\geq\frac{n}{k_{1}}k_{1}f(x_{0})+f'(x_{0})\left[\frac{n}{k_{1}}k_{1}x_{1}-\frac{n}{k_{1}}k_{1}x_{0}\right]=0 $ 即 $ \sum_{i=1}^{n}k_{i}f(x_{i})\geq\frac{1}{f(x_{0})} $

5. (双)  $ \int_{a}^{b} f(x) \in C[a, b] $ 且  $ \int_{a}^{b} f(x) dx = \int_{a}^{b} x f(x) dx = 0 $，证明： $ f(x) $ 在  $ (a, b) $ 内至少有 2 个不同零点

证：令  $  F(x) = \int_{a}^{x} f(t) \, dt  $，由  $  F(a) = F(b) = 0  $ 知  $  f(x, 0) = 0  $ ( $  a < x < b  $). 设仅  $  x_{0}  $ 一个零点，则  $  f(x)  $ 在  $  (a, x_{0})  $ 与  $  (x_{0}, b)  $ 异号不妨设  $  x \in (a, x_{0})  $ 时  $  f(x) \geq 0  $，则  $  \int_{a}^{x_{0}} (x - x_{0}) f(x) dx > 0  $， $  \int_{x_{0}}^{b} (x - x_{0}) f(x) dx > 0  $，这与  $  \int_{a}^{b} (x - x_{0}) f(x) dx = 0  $ 矛盾

 $ 6(\downarrow) $ 设  $ f(x) \in C(0,+\infty) $ 且单调递减，证明： $ \int_{1}^{n} f(x) dx \leq \sum_{k=1}^{n} f(k) \leq f(1) + \int_{1}^{n} f(x) dx $

证：由  $ \int_{n}^{m+1} f(x) dx \leq \int_{n}^{m+1} f(x) dx \leq \int_{m+1}^{n} f(x) dx $ 可证.

7. (↑)  $  f(x) \in [a, b]  $ 且  $  f(x)  $ 单调递增，证明： $ \int_{a}^{b} x f(x) dx = \frac{a + b}{2} \int_{a}^{b} f(x) dx $

证明：①  $ \int_{a}^{x} t f(x) dx = \int_{a}^{x} t f(t) dt - \frac{a + b}{2} \int_{a}^{x} t f(t) dt $，则  $ \varphi'(x) = \frac{x - a}{2} f(x) - \frac{1}{2} \int_{a}^{x} t f(t) dt = \frac{x - a}{2} [f(x) - f(x)] \geq 0 $，故  $ \varphi(b) \geq \varphi(a) = 0 $

②  $ \varphi(x) = (x - \frac{a + b}{2}) [f(x) - f(\frac{a + b}{2})] $，由  $ f(x) $ 知  $ \varphi(x) \geq 0 $，即  $ \int_{a}^{b} (\varphi(x) dx) \geq 0 $，即  $ \int_{a}^{b} (x - \frac{a + b}{2}) f(x) dx - f(\frac{a + b}{2}) \int_{a}^{b} (x - \frac{a + b}{2}) dx \geq 0 $

③  $ \int_{a}^{b} (x - \frac{a + b}{2}) f(x) dx = \int_{a}^{2a} x f(x + \frac{a + b}{2}) dx = \int_{a}^{2a} x [f(x + \frac{a + b}{2}) - f(-x + \frac{a + b}{2})] dx \geq 0 $

④  $ \int_{a}^{b} (x - \frac{a + b}{2}) f(x) dx = \int_{a}^{2a} \frac{x + \frac{a + b}{2}}{2} f(x) dx = f(x) \int_{a}^{b} (x - \frac{a + b}{2}) dx + f(x) dx = \frac{(b - a)^{2}}{8} [f(x_{2}) - f(x_{1})] \geq 0 $

8. (f(x)在 $ [0,1] $上连续可导且 $ f(0)=f(x)=0 $，证明： $ \vert\int_{0}^{1}f(x)dx\vert\leq\frac{1}{4}\max_{0\leq x\leq1}\vert f'(x)\vert $)

证：记 $ \max_{0\leq x\leq1}\vert f(x)\vert=M $，则 $ \begin{cases}f(x)-f(0)=f'(3)x&0<\xi<x\\f(x)-f(0)=f'(4)(x-1)&x<4\end{cases} $，故 $ \vert f(x)\vert\leq Mx $与 $ \vert f(x)\vert\leq M(1-x) $，故左边 $ \leq\int_{0}^{1}\vert f(x)\vert dx\leq\int_{0}^{\frac{1}{2}}Mx dx+\int_{\frac{1}{2}}^{1}M(1+x)dx=\frac{M}{4} $

9.  $ f(x) \in C[0,1] $， $ f(0) = f(1) $，证明： $ \forall n \in \mathbb{N}_{+}, n \geq 2 $，必  $ \exists x_n \in [0,1] $ 使  $ f(x_n) = f(x_n + \frac{1}{n}) $

证：①令 $ F(x)=f(x+\frac{1}{n})-f(x) $，若 $ F(x)\neq0 $，不妨设 $ f(x+\frac{1}{n})>f(x) $，则 $ f(0)>f(\frac{n-1}{n})>f(\frac{n-2}{n})>\cdots>f(0) $，矛盾

②注意到 $ F(0)+F(\frac{1}{n})+\cdots+F(\frac{n-1}{n})=\left[f(\frac{1}{n})-f(0)\right]+\left[f(\frac{3}{n})-f(\frac{n}{n})\right]+\cdots+\left[f(0-f(0)=0, 若 F(x)\neq0, 不妨设F(x)>0, 这与\sum_{i=0}^{n-1}F(\frac{i}{n})=0 $矛盾

10.  $ (f'' $原函数构造 $ \forall C\in D[0,1] $且 $ \forall f(0)=f'(0)=f''(0)=f(1)=0 $，证明： $ \exists f(0,1) $使 $ f''(\xi)\xi^{2}-2f(\xi)=0 $

证：先化为 $ x^{2}f(x)-2f(x)=0 $，由 $ \int x^{2}f'(x)dx=x^{2}f'(x)-2x-f(x)+2f(x)dx $知令 $ F(x)=x^{2}f'(x)-2x-f(x) $，则 $ F'(x)=0 $为证连续

待证式再令 $ G(x)=\left\{\begin{array}{l}\frac{f(x)}{x^{2}} \\ 0\end{array}\right. $知 $ \lim_{x\to0}\frac{(x+1)}{(x+1)} $知 $ G(x)=G(0)=0=G(1)\Rightarrow G'(C_{1})=0\Rightarrow F(C_{1})=0=F(0)\Rightarrow F'(3)=0 $

(1)(逆推法)(1)设 $ f(x)\in[0,1] $， $ D(0,1) $且 $ f(0)=0 $， $ f(1)=1 $，证：① $ a,b>0 $， $ \exists s,\eta\in(0,1) $且纵使 $ \frac{a}{f(s)}+\frac{b}{f(h)}=a+b $② $ Aa_{1},a_{1}>0 $

 $ \exists0<\xi<\xi_{n}<1 $使 $ \frac{a_{1}}{f(s)}+\cdots+\frac{a_{n}}{f(s)}=a_{1}+\cdots+a_{n} $

(2) $ f(x)\in D[0,a] $ (a20)且 $ f(0)=1 $， $ f(a)=0 $，证： $ \exists0<x_{1}<x_{2}<a $使 $ f(x_{1})f(x_{2})=\frac{1}{a^{2}} $

证: (1) 不妨令  $ f'(s) = \frac{f(c) - f(0)}{c} $,  $ f'(n) = \frac{f(1) - f(c)}{1 - c} $, 代入得  $ \frac{ac}{f(c)} + \frac{bc(1 - c)}{1 - f(c)} = a + b $, 不妨视 C 为任意值并令  $ f(c) = x $, 则有  $ \frac{f\left(\frac{a}{x} - \frac{b}{x}\right)}{f\left(\frac{b}{x} - a + b\right)} = \frac{c}{a + b} $

②同样地，取  $ f(x_{1}) = \frac{1}{\sqrt{2k}} a_{k} $

(2)  $ \frac{f(c) - 1}{c} - \frac{f(c)}{a - c} = \frac{1}{a^{2}} $, 则  $ f(c) - f(c) = \frac{c(a - c)}{a^{2}} $

 $ f(c)\left[1 - f(c)\right] = \frac{c}{a}(1 - \frac{c}{a}) $, 则  $ f(c) = \frac{c}{a} $ 或  $ 1 - \frac{c}{a} $. 再令  $ F(x) = a + f(x) - x $ 与  $ G(x) = f(x) + \frac{x}{a} $ 知取  $ f(x) = \frac{c}{a} $

12. ( $ \exists 0 $)  $ f(x) \in D[0,+\infty) $,  $ f(0)=0 $,  $ |f(x)| \leq |f(x)| $, 证明:  $ f(x) \equiv 0 $

证：①  $ x \in (0,1) $ 时，记  $ [0,x] $ 上最大值为  $ \left|f(x_0)\right| = M_x $，则  $ M_x = \left|f(x_0) - f(0)\right| = \left|f'(x_0)\right| \times 0 \leq M x_0 $，由  $ \left\{\begin{array}{l}0 \leq x_0 < 1 \\ M_x \geq 0\end{array}\right. $ 和  $ M_x = 0 $，即  $ [0,1) $ 上  $ f(x) = 0 $ 又由连续知  $ f(x) = \lim_{x \to 1} f(x) = 0 $。类（以可证  $ f(x) = 0, x \in [n, n+1] $ （ $ n=1,2,\ldots $）②  $ \forall x \in (0,1) $，有  $ \left|f(x)\right| = \left|f(x_0)\right| \times \leq \left|f(x_0)\right| \times x_0 $  $ \leq \left|f(x_0)\right| \times x^2 \leq \cdots \leq \left|f(x_0)\right| \times x^n \leq M \cdot x^n = 0 $ 后同①  $ 0 < x_1 < x $ KOKUYO

(3)  $ (f(x)^{2}) $ f(x) 在  $ [0,1] $ 连续可导，f(0)=0，证明：(1)  $ \int_{0}^{1}f(x)dx \leq \frac{1}{2}\int_{0}^{1}f'(x)dx $ (2) 若  $ f(1)=0 $，则  $ \int_{0}^{1}f(x)dx \leq \frac{1}{8}\int_{0}^{1}f'(x)dx $

证：(1) 由  $ f(x)=\int_{0}^{x}f'(t)dt $ 知  $ f'(x)=[\int_{0}^{x}1\cdot f'(t)dt]^{2}=\int_{0}^{x}1^{2}dt\int_{0}^{x}f'(t)dt\leq x\int_{0}^{1}f'(t)dt $，左边  $ \leq\int_{0}^{x}x dx\int_{0}^{x}f'(t)dt=\frac{1}{2}\int_{0}^{1}f'(t)dt $

(2) 由  $ f(x)=\int_{0}^{x}f'(t)dt=\int_{0}^{1}x f'(t)dt $，则  $ 0<x\leq\frac{1}{2} $ 时， $ f'(x)\leq x\int_{0}^{\frac{1}{2}}f'(t)dt $， $ \frac{1}{2}<x<1 $ 时  $ f'(x)\leq\int_{x}^{1}1^{2}dt\int_{x}^{1}f'(t)dt $

 $ \leq(1-x)\int_{\frac{1}{2}}^{2}f'(t)dt $，则左边 $ \leq\int_{0}^{\frac{1}{2}}x dx\int_{0}^{\frac{1}{2}}f'(t)dt+\int_{\frac{1}{2}}^{1}1-x dx\int_{\frac{1}{2}}^{1}f'(t)dt=\frac{1}{8}\int_{0}^{1}f'(t)dt $

注：①处若写为 $ f(x)=\int_{0}^{x}f'(t)dt $，则 $ \int_{0}^{2}x^{2}dt\int_{0}^{x}f'(t)dt=(x-1)\int_{0}^{x}f'(t)dt=(1-x)\int_{0}^{1}f'(t)dt $

14.(凹)凹函数  $ f: [0,1] \rightarrow R $ 满足  $ \int_{0}^{1} f(x) dx = 0 $，证明： $ \left\{\begin{array}{l} f(x) \leq \max f(10), \\ f(x) \leq \min f(10), \end{array}\right. $

证: 由图象知  $ f(x)_{\max} = \max \{f(0), f(1)\} $  $ {}^{①} $，那么只需证明:  $ -\min_{t \in [0,1)} f(t) \leq M $，不妨认为  $ -m \leq M $  $ {}^{②} $ 显然①由凹

可证:  $ f[(1-t)x_{1}+t x_{2}] \leq (1-t)t(x_{1})+t f(x_{2}) $  $ {}^{③} $ 令  $ x=0, x_{2}=1 $ 有  $ f(t) \leq (1-t)f(0)+t f(1) $，显然  $ f(t) \leq M $。而②由

 $ \int_{0}^{1} f(x) dx $ 约束，因此对③式两边积分  $ \int_{0}^{1} f[(1-t)x_{1}+t x_{2}] dt \leq \frac{f(x_{1})+f(x_{2})}{2} $ 得  $ \frac{\int_{x_{1}}^{x_{2}} f(x) dx}{x_{2}-x_{1}} \leq \frac{f(x_{1})+f(x_{2})}{2} $ ④

设  $ f(x_{m}) = m, f(x) \leq \max f(x_{m-1}, x_{m-2}, x_{m-3}) $ 得  $ \left\{\begin{array}{l} x_{1}=0 \\ x_{2}=m \end{array}\right. $ 得  $ \left\{\begin{array}{l} x_{1}=m \\ x_{2}=1 \end{array}\right. $ 得  $ \left\{\begin{array}{l} x_{1}=m \\ x_{2}=1 \end{array}\right. $ 得  $ \left\{\begin{array}{l} \frac{f(x_{m})+f(0)}{2} \geq \int_{0}^{x_{m}} f(x) dx \text{ 与 } (1-x_{m}) \frac{f(x)}{2}+f(x_{m}) \geq \int_{x_{m}}^{1} f(t) dt \end{array}\right. $

二式相加，有  $ x_{m}(m+f(0)) + (1-x_{m})(f(1)+m) \geq 0 $ 即  $ -m \leq x_{m} f(0) + (1-x_{m}) f(1) \leq M $

注 $ ^{①} $是常识：凹函数在闭区间上的最大值一定落在满点上

④来源于Hermite-Hadamard不等式  $ f(\frac{a+b}{2}) \leq \frac{\int_{a}^{b} f(x) dx}{b-a} \leq \frac{f(a) + f(b)}{2} $

补(法2)①干单调[0，]且然M在端点取得②不单调.由 $ f''>0 $和 $ f $先↓后↑，不妨设 $ f(x)_{\max}=f(3) $ (显然<0)，故只用证 $ -f(3)\leq\max $ 不妨设 $ f(x)>f(0) $，用反证法(设 $ -f(3)>f(0)>f(0) $)，在 $ f(x)<f(0)+\frac{f(3)-f(0)}{3}x $ ， $ (f(1) $上， $ f(x)<f(3)+\frac{f(1)-f(0)}{1-3}(x-3) $，于是 $ \int_{0}^{1}[f(x)]dx<\int_{0}^{3}x\cdots+\int_{3}^{1}x\cdots=\frac{f(0)+f(3)}{2}+\frac{1-3}{2}[f(1)+f(3)]<0 $ ，矛盾.故 $ -f(3)\leq f(1) $成立

## 三、习题

1. (θ)  $  f(x) \in D[-a,a]  $ 且  $  f(0) \neq 0  $. 证日日:  $ \forall x \in (0,a], \exists \theta \in (0,1) $ 使  $ \int_{0}^{x} f(t) dt + \int_{0}^{x} f(t) dt = x [f(\theta x) - f(-\theta x)] $ 并求  $ \lim_{x \to 0} \theta $

解: 由  $ \int_{0}^{x} f(t) dt = -\int_{0}^{x} f(-t) dt $，则左边  $ =\int_{0}^{x} [f(t) - f(-t)] dt $ 积分中值  $ x [f(\theta x) - f(-\theta x)] = $ 右边

右侧仅一个θ，故左侧必须凑成同一积分（上下限一致）联系题中  $ f(0) = 0 $，凑定义

两边同除  $ x^{2} $ 后，左边  $ =\lim_{x \to 0} \frac{f(x) - f(-x)}{2x} = \frac{1}{2} \lim_{x \to 0} \frac{f(x - f(0))}{x} + \frac{f(x - f(0))}{x} = f(0) $，右边  $ = \lim_{x \to 0} \theta \left[ \frac{f(\theta x) - f(0)}{\theta x} + \frac{f(-\theta x) - f(0)}{\theta x} \right] = 2 f(0) \lim_{x \to 0} \theta $，因而  $ \lim_{x \to 0} \theta = \frac{1}{2} $

2.  $ |f(x)| $ 一辆汽车从开始启动  $ (V=0) $ 到刹车停止，用单位时间走完单位路程，证明：至少有一个时间点， $ |a|\geq4 $

解：化为数学描述，记运动方程为  $ S=S(t) $，则  $ \left\{\begin{array}{l}V=S'(t) \\ a=S'(t)\end{array}\right. $，即  $ \left\{\begin{array}{l}S(0)=0 \\ S(1)=1\end{array}\right. $， $ \left\{\begin{array}{l}S(0)=0 \\ S(1)=0\end{array}\right. $，由3-H=-3的结论，有  $ |a|\geq\frac{4(1-0)}{(1-0)^{2}}=4 $

3. ( $ |f(x)| $)  $ f(x) \in C[a, b] \cap D(a, b) $ 且  $ y = f(x) $ 非直线，证明： $ \exists \xi \in (a, b) $，使  $ |f(x)| > \frac{f(b) - f(a)}{b - a} $

解：注意到  $ F(x) = f(x) - f(a) - \frac{f(b) - f(a)}{b - a}(x - a) $ 时有  $ F(a) = F(b) = 0 $，由  $ f(x) $ 非直线和  $ F(x) $ 不恒为 0，不妨设事实上令  $ G(x) = f(x) - \frac{f(b) - f(a)}{b - a}x $ 也行，而由  $ G(a) = G(b) = \frac{f(a) - a}{b - a} $，则令  $ F(x) = G(x) - \frac{f(a) - a}{b - a} = G(x) - \frac{f(a) - a}{b - a} $

 $ \varphi(c) > 0 $，则由拉中得  $ \varphi(c) = \frac{\varphi(c) - \varphi(a)}{c - a} > 0 $， $ \varphi(c) = \frac{\varphi(b) - \varphi(a)}{b - c} < 0 $，即  $ f(c) > \frac{f(b) - f(a)}{b - a} $， $ f(c) < \frac{f(b) - f(a)}{b - a} $

当  $ \frac{f(b) - f(a)}{b - a} > 0 $ 时，满足当  $ \frac{f(b) - f(a)}{b - a} < 0 $ 时，满足

①当 $ \frac{f(b)-f(a)}{b-a}>0 $时，≤满足②当 $ \frac{f(b)-f(a)}{b-a}<0 $时，≤满足

4. $ (S+5\frac{1}{4}) $ (1) 设  $ f(x) $ 在  $ [0,1] $ 上可积且  $ 0 < m \leq f(x) \leq M $，证明： $ \int_{0}^{1} f(x) dx \int_{0}^{1} \frac{1}{f(x)} dx \leq \frac{(m+M)^{2}}{4m M} $

(2) 设  $ f(x) \in C[a, b] $ 且  $ f(x) > 0 $，证明： $ \int_{a}^{b} f(x) dx \int_{a}^{b} \frac{1}{f(x)} dx \geq (b-a)^{2} $

解：(1) 由  $ [f(x)-m][f(x)-M]\leq0 $，同除  $ f(x) $ 有  $ \frac{[f(x)-m][M-f(x)]}{f(x)}\geq0 $，即  $ f(x)+\frac{mM}{f(x)}\leq m+M $，两边积分  $ \int_{0}^{1}f(x)dx+mM\int_{0}^{1}\frac{1}{f(x)}dx\leq m+M $，即  $ m+M\geq A+mM $,  $ B\geq2\sqrt{A\cdot m\cdot M\cdot AB} $ 故  $ AB\leq\frac{(m+M)^{2}}{4mM} $ 认为 A

(2) 注意到  $ [f(x)-f(y)]\left[\frac{1}{f(x)}-\frac{1}{f(y)}\right]\leq0 $，故  $ \int_{a}^{b}dx\int_{a}^{b}\left[2-\frac{f(x)}{f(y)}-\frac{f(y)}{f(x)}\right]dy\leq0 $，即  $ \int_{a}^{b}f(x)dx\int_{a}^{b}\frac{1}{f(x)}dy+\int_{a}^{b}\frac{1}{f(x)}dx\int_{a}^{b}f(x)dy\geq2(b-a)^{2} $，显然左边两项均等于  $ \int_{a}^{b}f(x)dx\int_{a}^{b}\frac{1}{f(x)}dx $，因此得证

②由柯西， $ I \geq (\int_{a}^{b}\sqrt{f(x)}\cdot\frac{1}{\sqrt{+(x)}}dx)^{2}=(b-a)^{2} $

 $$ I=\iint\frac{f(x)}{f(y)}d y=\frac{1}{2}\iint\frac{f(x)}{f(y)}+\frac{f(y)}{f(x)}d x d y=\iint\frac{f^{2}(x)+f^{2}(y)}{2f(x)+f(y)}d x d y\geq f(d x)d y=(b-a)^{2} $$ 

设 $ f(x)\in C[0,1] $且 $ f(x) $单调递减，证明：对 $ \forall d\in(0,1) $，有 $ \int_{0}^{d}f(x)dx\geq d\int_{0}^{1}f(x)dx $

解：①  $ \int_{0}^{d}f(x)dx\xlongequal{x=\alpha t}\alpha\int_{0}^{1}f(\alpha t)dt\geq\alpha\int_{0}^{1}f(t)dt $

②  $ \int_{0}^{d}f(x)dx - \alpha\int_{0}^{1}f(x)dx = (1-\alpha)\int_{0}^{d}f(x)dx - \alpha\int_{\alpha}^{1}f(x)dx = (1-\alpha)d\left[f(\xi_{1}) - f(\xi_{2})\right] \geq 0 $ ( $ 0 < \xi_{1} < d < \xi_{2} < 1 $)

6.(估值) 设  $ f(x) \in C[a,b] $，证明： $ \left|f(c)\right| \leq \left|\frac{\int_{a}^{b} f(x) dx}{b-a}\right| + \int_{a}^{b} |f(x)| dx $ ( $ a < c < b $)

解：由  $ \frac{\int_{a}^{b} f(x) dx}{b-a} = f(x_0) $， $ f(c) - f(x_0) = \int_{x_0}^{c} f(x) dx $ 知  $ f(c) = -f(x_0) + \int_{x_0}^{c} f(x) dx $，故左边  $ \leq |f(x)| + \int_{x_0}^{c} |f(x)| dx \leq \left|\frac{\int_{a}^{b} f(x) dx}{b-a}\right| + \int_{a}^{b} |f(x)| dx $ 由C的任意性，即  $ |f(x)| $ 相当于  $ \left|f(x)\right| $，故左边可写成  $ \max_{a \leq k \leq b} |f(x)| $

7. 泰勒+积分 设  $ f'(x) \in C[2,4] $， $ f(3)=0 $，证明  $ \exists \xi \in (2,4) $，使得  $ f'(\xi)=3\int_{2}^{4} f(x) dx $

解得  $ F(x)=\int_{2}^{x} f(t) dt $，则  $ F(3)=f(3)=0 $，即  $ \left\{\begin{array}{l}F(2)=F(3)+\frac{F''(3)}{2}-\frac{F''(4)}{6}, \\F(4)=F(3)+\frac{F''(3)}{2}+\frac{F''(4)}{6}\end{array}\right. $ 故  $ F(4)-F(2)=\frac{f''(2)+f''(3)}{6} $，设  $ m \leq f'(N) \leq M $，则  $ F(4)-F(2) \in \left[\frac{M}{3}, \frac{M}{3}\right] = \frac{f''(3)}{3} $ （ $ S_1 \leq S_2 $）

注：亦可由  $ f(x) = f'(3)(x-3) + \frac{f'(3)}{2}(x-3)^2 $ 积分得  $ \int_{2}^{4} f(x) dx = \int_{2}^{4} \frac{f'(3)}{2}(x-3)^2 dx $，类似上面由  $ m \leq f'(N) \leq M $ 可证.

8.(二重耗一重)  $  f(x) \in C[0,a]  $，证明： $ \int_{0}^{a} f(x) dx \int_{x}^{a} f(x) dy = \frac{1}{2} \left[ \int_{0}^{a} f(x) dx \right]^{2} $

证:①换序换序  $ I=\int_{0}^{a}f(x)dx\int_{0}^{y}f(x)dx\stackrel{\text{换x,y}}{=}\int_{0}^{a}f(x)dx\int_{0}^{x}f(x)dy=\frac{1}{2}\int_{0}^{a}f(x)dx\int_{0}^{a}f(x)dy= $ 右边

②变限令 $ F(x)=\int_{0}^{x}f(t)dt $，左边 $ \int_{0}^{a}f(x)\left[f(a)-f(x)\right]dx=F(a)\int_{0}^{a}f(x)dx-\int_{0}^{a}F(x)dx-F(x)=\frac{1}{2}F^{2}(a)= $右边

9.(M) 设  $ 0 < a < b $，证明： $ \frac{e^{b} - e^{a}}{b - a} > e^{\frac{a + b}{2}} $

证⑪令 $ m=\frac{a+b}{2} $，t=b-a，则要证 $ e^{\frac{m+b}{2}}-\frac{e^{m-b}}{t}>e^{m} $ 这相当于 $ \frac{e^{\frac{b}{2}}-e^{-\frac{b}{2}}}{t}>1 $， $ F(t)=e^{\frac{b}{2}}-e^{-\frac{b}{2}}-t $， $ F'(t)=\frac{e^{\frac{b}{2}}+e^{-\frac{b}{2}}}{2}-1\geq0 $

故  $ F(t) > F(0) = 0 $

注：左右侧都含中点这一因式，故令  $ m = \frac{a + b}{2} $ 对问题降维  $ (a, b, t) $

②令 $ m=\frac{a+b}{2} $，由 $ f(x)=f(m)+f'(m)(x-m) $得 $ \int_{a}^{b}e^{x}dx\geq\int_{a}^{b}e^{m}e^{m}(x-m)dx $，即 $ e^{b}-e^{a}=(b-a)e^{m} $

注：若这里用中值定理，右边 $ -e^{\frac{a}{2}} $难以证明 $ \frac{a+b}{2} $因为中值定理仅精确到一所导，且难以确定S的范围

③由Jensen不等式，则 $ \int_{a}^{b}\frac{e^{x}}{b-a}dx > \exp\left(\int_{a}^{b}\frac{x}{2-a}dx\right) = e^{\frac{a+b}{2}} $，①处证明如下：令 $ m=\int_{a}^{b}\frac{x}{b-a}dx=\frac{a+b}{2} $，由 $ f(x)\geq f(m)+f(m)x-m $得 $ e^{x}=e^{m}(1+x-m) $，则 $ e^{b}-e^{a}\geq e^{m}\int_{a}^{b}1+x-m dx=e^{m}\left[(1-a)+(1-a)m-m\cdot(1-a)\right]=(b-a)e^{\frac{a+b}{2}} $，仅在 $ x=m $取等，故积分后为>Jensen不等式：对凹函数，有 $ \sum_{i=1}^{n}\lambda_{i}f(x_{i})\geq f(\sum_{i=1}^{n}\lambda_{i}x_{i}) $ ( $ \lambda_{30} $且 $ \lambda_{1}=1 $)。 $ E[f(x)]\geq f(E(x)) $

离散形式在二-T4已证，下证积分形式：设 $ M=EX $， $ \beta=f(y) $，则有 $ f(x)\geq f(M)+\beta(x-M) $即 $ E[f(x)]\geq E[f(M)]+\beta\cdot E[x-M]=f(M) $当f严格凹时，≥改为>.

注：同理为证 $ e^{ax}-1<a(e^{x}-1) $，可令 $ f(x)=e^{x}-1 $，有 $ f(ax)=f[ax+(-a-1)]<a(f(x)+(1-a)f(0))=a f(x) $

 $ |0|_{2} $  $ (1+x)^{\frac{1}{x}}+(1+\frac{1}{x})^{x}\leq a $  $ (a>0) $，求  $ a $ 的最小值

解: 易证  $ f = (1 + x)^{1 + x} $ 为凸函数, 由  $ \lambda f(x_{1}) + (1 - \lambda)f(x_{2}) \leq f[\lambda x_{1} + (1 - \lambda)x_{2}] $ 取  $ x_{1} = x, x_{2} = \frac{1}{x} $,  $ \lambda = \frac{1}{1 + x} $ 得  $ \frac{1}{1 + x} f(x) + (1 - \frac{1}{1 + x}) f(x) \leq f(\frac{x}{1 + x} + \frac{x}{1 + x} \cdot \frac{1}{x}) = f(1) = 4 $ 故  $ a_{min} = 4 $

11.(构造)  $ f(x) $ 在  $ [a, b] $ 中所有可导， $ M = \max_{x \in [a, b]} \{|f(x)|\} $，证明： $ \forall x \in (a, b) $ 均有  $ \left|\frac{f(x) - f(a)}{x - a} - \frac{f(b) - f(a)}{b - a}\right| \leq \frac{m}{2}(b - x) $

证：令  $ F(t) = \frac{t(t - t(a))}{t - a} $， $ F'(t) = \frac{(t - a)f'(t) - [f(t) - f(a)]}{(t - a)^2} $。于是  $ F(x) - F(b) = (x - b)F'(x) $，令  $ a(t) = (t - a)f'(t) - [f(t) - f(a)] $， $ H(t) = (t - a)^2 $，则  $ \frac{a(3) - a(a)}{H(3) - H(a)} = \frac{a'(a)}{H'(a)} = \frac{f'(a)}{2} $，于是左边  $ = \left|\frac{x - b}{2} + f'(a)\right| \leq $ 右边

②插值：注意到 $ G(x)=f(x)-P(x) $

 $ P(x)=f(a)+\frac{f(b)-f(a)}{b-a} $

 $ \frac{f(t)-f(t)}{1-a}(x-b) $

 $ P(x-a)(x-b) $ 时  $ (a<t<b) $，满足  $ G'(a)=G(t)=G(b)=0 $

且  $ G''=f''(x)-2\frac{f(t)-f(t)}{(t-a)(t-b)}=-f'(x)-2k=0 $ 代回  $ G(x)=f(x)-P(x)-\frac{f'(x)}{2}(x-a)(x-b) $，即左边  $ |1\frac{t-a}{2}(x-b)|< $ 右边

注： $ P(x) $ 是线性插值函数，过点  $ (a,f(a)) $ 与  $ (b,f(b)) $，显然若令  $ H(x)=f(x)-P(x) $，有  $ H(a)=H(b)=0 $，但为了使用罗尔得到  $ t^{2} $ 的形式，还应找到一点  $ t\in(a,b) $ 使  $ H(t)=0 $，因此需要再加上  $ K(x-a)(x-b) $ 这一项，即令  $ G(x)=H(x)-K(x-a)(x-b) $，再令  $ G(t)=0 $ 解得  $ f(t)-P(t)=K(t-a)(t-b) $。由于  $ G'(x)=f'(x)-2k $ 加上罗尔，知  $ G''(x)=0 $ 即  $ t''(x)=2k $，代入得  $ G(x)=f(x)-f(a)-\frac{f(b)-f(a)}{b-a}(x-a)-\frac{f''(b)}{2}(x-a)(x-b) $ 且满足  $ G(t)=0 $。由于  $ t $ 的任意性可知，对  $ t\in(a,b) $ 均有  $ G(t)=0 $，即  $ \frac{f(t)-f(a)}{t-a}-\frac{f(b)-f(a)}{b-a}=\frac{f'(x)}{2}(t-b) $

12.(3的比较)  $ f(x) $ 在  $ [a,b] $ 可导.  $ C\in(a,b) $,  $ f(c)-f(a)=f'(c)-(a) $ ( $ f(a,c) $), 证明:  $ \exists\eta\in(a,b) $ 使  $ f(b)-f(a)=f'(b)-f(a) $ 且  $ h>3 $

证: ①  $ \frac{f(b)-f(a)}{b-a}=f(b)-f(c)+f(c)-f(a)=\frac{f(b)-f(c)}{b-a}\cdot\frac{b-c}{b-a}+\frac{f(c)-f(a)}{c-a}\cdot\frac{c-a}{b-a}=f'(r)\frac{b-c}{b-a}+f'(s)\frac{c-a}{b-a} $ ( $ c<r<b $)

令  $ t=\frac{b-c}{b-a} $，则  $ 1-t=\frac{c-a}{b-a} $ ( $ 0<t<1 $)，于是  $ \frac{f(b)-f(a)}{b-a}=+f'(r)+(1-t)f'(s) $ 介值  $ f'(h) $ ( $ a<s<c<r<b, s<h<r $)

 $$ t^{\prime}(r)=t^{\prime}(3) $$ 

②  $ \left\{\begin{array}{l} f(c) - f(a) = t(s) ((-a)) \\ f(b) - f(c) = t(n) (b - c) \end{array}\right. $  $ (a < s < c < n, < b) $ (i)  $ f(n_1) = t^2(s) $，取  $ n = n_1 > 3 $ (ii)  $ f(n_1) > t^2(s) $， $ ① + ② $ 得  $ t(s) - t(a) > t^2(s) $ (b - a)， $ f(b) - f(a) < t^2(n_1) (b - a) $，于是  $ t^2(s) < t^2(n_1) < t^2(n_1) $，由此  $ n \in (s, n_1) $ (iii)  $ t^2(n_1) < t^2(s) $，同理有  $ f(n_1) < t^2(n_1) < t^2(s) $，由此  $ n \in (s, n_1) $

13.  $ f(x)= $ 阶导连续， $ x\in[0,+\infty) $， $ f(x)\leq1 $，证明：(1)  $ \int_{0}^{1}f(x)dx-f(\frac{1}{2})\leq\frac{1}{24} $ (2)  $ f(x)=f(x+1) $ 且  $ n\in N $ 时，有： $ \left|\int_{0}^{x}f(x)dx\right|\leq n\left[\frac{1}{6}+\left|f(x)\right|\right] $

证：(1)  $ x $ 处的导数显然，其中  $ \frac{1}{2}\int_{0}^{x}(x-\frac{1}{2})dx=\frac{1}{24} $ (2)  $ f(x)=f(x+1) $，故  $ \left\{\begin{array}{l}f(0)=f(x) \\ f(0)=f(1)\end{array}\right. $， $ \int_{0}^{x}f(x)dx=n\int_{0}^{1}f(x)dx $。在  $ x=0 $ 处索勒并积分，相加得

 $ 2\int_{0}^{1}f(x)dx=f(0)+f(1)+\frac{1}{2}\left[\int_{0}^{1}f(x)dx^{2}dx+\int_{0}^{1}f^{\prime}(x)dx\right] $，于是  $ \left\{\begin{array}{l}f(x)=f(x+1)\\f(x)=f(x-1)\end{array}\right. $ 是  $ \left\{\begin{array}{l}f^{\prime}(x)=f(x+1)\\f^{\prime}(x)=f(x-1)\end{array}\right. $ 故  $ \left\{\begin{array}{l}f(x)=f(x+1)\\f(x)=f(x-1)\end{array}\right. $ 故  $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(x)=f(x-1) $， $ f^{\prime}(x)=f(x+1) $， $ f^{\prime}(

14. f(x)在 $ [a,b] $连续可导，证： $ \int_{a}^{b}|f(x)|dx \leq \max\left\{(b-a),|f(x)|dx\right\} $， $ \left|\int_{a}^{b} f(x) dx\right| \leq \left|\frac{\int_{a}^{b} f(x) dx}{b-a}\right| + \int_{a}^{b} |f(x)| dx $

证：(1) ①  $ f $ 不变， $ \int_{a}^{b}|f(x)|dx = \int_{a}^{b}|f(x)|dx $ ② 变，则  $ \exists x_{0} \in (a, b) $ 使  $ f(x_{0}) = 0 $， $ |f(x)| = |f(x) - f(x_{0})| = \left|\int_{x_{0}}^{x} f(t) dt\right| \leq \int_{a}^{b}|f(t)| dt $  $ \int_{a}^{b}|f(x)|dx \leq (b-a)\int_{a}^{b}|f(t)|dt $

(2)  $ \vert f(x)\vert=\vert\int_{3}^{x}f'(t)dt+f(x)\vert\leq\int_{a}^{b}\vert f'(t)\vert dt+\vert f(x)\vert=\int_{a}^{b}\vert f(t)\vert dt+\left|\frac{\int_{a}^{b}f(x)dx}{b-a}\right| $ (其中，取的满足  $ f(3):\frac{\int_{a}^{b}f(x)dx}{b-a} $) 由x的任意性和  $ \max\vert f(x)\vert $ 左右边

(5).  $ f(x) $ = 所可导 (1) = 阶导连续且  $ \left|\int_{a}^{b} f(x) dx\right| < \int_{a}^{b} |f(x)| dx $. 记  $ M_{1} = \max_{x \in [a, b]} |f'(x)| $,  $ M_{2} = \max_{x \in [a, b]} |f''(x)| $. 证:  $ \left|\int_{a}^{b} f(x) dx\right| $

 $ \leq \frac{M_{1}}{2}(b-a)^{2} + \frac{M_{2}}{3}(b-a)^{3} $

(2)  $ f(a) = f(b) = 0 $, 证:  $ \left|\int_{a}^{b} f(x) dx\right| \leq \frac{(b-a)^{3}}{12} \max_{x \in [a, b]} |f''(x)| $

证：(1)  $ f\overrightarrow{a}\frac{b}{c} $，故  $ \exists x=c, f(c)=0 $。即  $ \left|\int_{a}^{b}f(x)dx\right|\leq f'(c)\left|\int_{a}^{b}(x-c)dx\right|+\frac{M_{2}}{2}\int_{a}^{b}(x-c)^{2}dx\leq\frac{M_{1}}{2}(b-a)\left|b+a-2c\right|+\frac{M_{2}}{6}\left[(b-\delta)^{2}+(c-a)^{2}\right]\leq\frac{M_{1}}{2}(b-a)^{2}+\frac{M_{2}}{6}(b-a)^{3} $

(2)  $ 0 = \int_{a}^{b} f(x) dx = \int_{a}^{b} f(x) dx + \int_{a}^{b} f'(x)(a-x) dx + \int_{a}^{b} \frac{f'(x)}{2}(a-x)^{2} dx $.  $ I_{2} = (a-x) f(x) \bigg|_{a}^{b} + \int_{a}^{b} f(x) dx $，代回得  $ \int_{a}^{b} f(x) dx = -\frac{1}{4} \int_{a}^{b} f''(x)(a-x)^{2} dx $，故左边  $ \leq \frac{1}{4} M \int_{a}^{b} (a-x)^{2} dx = \frac{(b-a)^{3}}{12} M $

# 一元微分-A

1. (2020·) 设  $ f(x) $ 在  $ (-1,1) $ 上有定义，且  $ \lim_{x \to 0} f(x) = 0 $，则

A. 当  $ \lim_{x \to 0} \frac{f(x)}{\sqrt{x}} = 0 $ 时， $ f(x) $ 在 x = 0 处可导 B. 当  $ \lim_{x \to 0} \frac{f(x)}{x^2} = 0 $ 时， $ f(x) $ 在 x = 0 处可导 C. 当  $ f(x) $ 在 x = 0 处可导时， $ \lim_{x \to 0} \frac{f(x)}{\sqrt{x}} = 0 $ D. 当  $ f(x) $ 在 x = 0 处可导时， $ \lim_{x \to 0} \frac{f(x)}{x^2} = 0 $

解：先写定义， $ f'(0)=\lim_{x\to0}\frac{f(x)-f(0)}{x} $，若 $ f(0)=0 $，则B正确，但这要求 $ f(x) $在 $ x=0 $处连续，因此可单反例 $ f(x)=\begin{cases}x^{3}, & x\neq0 \\ 1, & x=0\end{cases} $，对于C，可导 $ \Rightarrow $连续，则 $ L=f(0)\cdot\lim_{x\to0}\frac{x}{x}=0 $ 反例的思路 C

2.(原创) 令  $ f(x)=\ln(x+\sqrt{x^{2}+1}) $，求  $ f^{(5)}(0) $

解：考虑  $ f'(x)=\frac{1}{\sqrt{x-1}}=1-\frac{1}{2}x^{2}+\frac{3}{8}x^{4}+\cdots $，则  $ f(x)=x-\frac{1}{6}x^{3}+\frac{3}{40}x^{5}+\cdots $，即  $ f^{(10)}=\frac{3}{40}\cdot5!=9 $

事实上， $ f^{(2n+1)}(0) $ 可由  $ (1+x)^{-\frac{1}{2}} $ 的  $ x^{n} $ 系数得出， $ f^{(2n)}(0)=0 $ （奇函数）（类似地，可求得  $ \arctan x=x-\frac{x^{3}}{3}+\frac{x^{5}}{5}+\cdots+\frac{(-1)^{n}x^{2n+1}}{2n+1} $）

3. 设  $  f(x) = e^{x} \sin x  $，求  $  f^{(n)}(x)  $

解  $ f(x)=e^{x}(\sin x + \cos x) = \sqrt{2} e^{x} \sin(x + \frac{\pi}{4}) $  $ f'(x) = \sqrt{2} e^{x} [\sin(x + \frac{\pi}{4}) + \cos(x + \frac{\pi}{4})] = (\sqrt{2})^{2} e^{x} \sin(x + \frac{2\pi}{4}) $，归纳知  $ f^{(n)}(x) = (\sqrt{2})^{n} e^{x} \sin(x + \frac{n\pi}{4}) $

4.(1)  $ f(x)= $阶可导， $ f'(0)=0 $， $ f''(0)=2 $，求 $ \lim_{x\to0}\frac{f(x)-f[\ln(1+x)]}{x^3} $

(2)  $ f(x) $可导，且 $ f(0)=0 $， $ f'(0)=2 $，求 $ \lim_{x\to0}\frac{\sqrt{x^2+\left(x-1\right)^2}}{x^2} $

解：(1)  $ L=\lim_{x\to0}\frac{f(x)-f(1+x)}{x^3}=\frac{1}{2}\cdot\lim_{x\to0}\frac{f(x)-f(1)}{x}=\frac{1}{2}f(0)\lim_{x\to0}\frac{x}{x} $ 由  $ \left\{\begin{array}{l}x<0: \ln(1+x)<\frac{3}{2}<x: \left\{\frac{\sqrt{3}}{2}<\ln(1+x)\right. \\ x>0: \ln(1+x)<\frac{3}{2}<x: \ln(1+x)<\frac{3}{2}<1\end{array}\right.\Rightarrow\lim_{x\to0}\frac{x}{x}=1 $

因而 $ L=\frac{1}{2}\cdot2\cdot1=1 $ 注意拉中使用时两侧的范围可能需要讨论

 $$ (2)\textcircled{1}L=\lim_{x\rightarrow0}\frac{\frac{1}{2}\int\limits_{0}^{x}f(t)d t}{x^{2}\int\limits_{0}^{x}f(t)d t}=\lim_{x\rightarrow0}\frac{\frac{1}{2}\cdot2x f(x)}{2x\int\limits_{0}^{x}f(t)d t+x^{2}f(x)}=\lim_{x\rightarrow0}\frac{f(x)}{x^{2}}\cdot\frac{1}{2\int\limits_{0}^{x}f(x)d t+\frac{f(x)}{x}}=f^{\prime}(0)\cdot\frac{\lim\limits_{x\rightarrow0}\frac{1}{2\cdot f(x)}}{2\cdot\frac{f(x)}{f(0)}}=\frac{1}{2} $$ 

②注意到 $ \lim_{x\to0}\frac{\int_{0}^{x^{2}}(t+1)dt}{x^{4}}=\frac{\lim_{x\to0}x}{4}\frac{f(x)}{x^{3}}=\frac{1}{2}f(0) $与 $ \lim_{x\to0}\frac{\int_{0}^{x}f(t)dt}{x^{2}}=\frac{1}{2}f(0) $，则 $ L=\frac{1}{2}\cdot\frac{\frac{1}{2}f(0)}{\frac{1}{2}f(0)}=\frac{1}{2} $

①中难在洛，②中分开洛更简单.因为 $ \int_{0}^{x}f(u)du $求导后为 $ 2xf(x) $，要凑 $ \frac{1}{x^{2}} $，即凑 $ \frac{2xf(x)}{2x^{3}} $，即 $ \frac{\int_{0}^{x}f(u)du}{\frac{1}{2}x^{4}} $ ( $ =f(0) $)

5.  $ f(x) $ 可导,  $ \varphi(x)=\left\{\begin{array}{ll}x^{3}\sin\frac{1}{x} & x \neq 0 \\ 0 & x=0\end{array}\right. $, 求  $ F(x)=f(\varphi(x)) $ 在  $ x=0 $ 的导数  $ F'(0) $

解  $ \varphi_{(0)}^{\prime}=\lim_{x\to0}x^{3}\sin\frac{1}{x}=0 $，则  $ F^{\prime}(x)=f(0)\varphi^{\prime}(0)=0 $

注①：若 $ g'(x_{0}) $与 $ f(u_{0}) $都存在，则 $ \frac{d}{dx}\frac{f(u_{0})}{g(x_{0})}\bigg|_{x=u_{0}}=f(u_{0})g(x_{0}) $。若至少大不存在， $ f[g(x)] $并非一定在 $ x_{0} $处不可导。

注② $ F_{10}^{1}=\lim_{x\to0}f\left(\frac{x^{3}\sin x}{x}\right)=\lim_{x\to0}\frac{f(x^{3}\sin x)-f(1)}{x^{3}\sin x}\cdot\lim_{x\to0}\frac{x^{3}\sin x}{x}=0 $错，因为 $ x=\frac{1}{n} $存在于任意的 $ x=0 $去心迎域内。则 $ \lim_{x\to0}\frac{f(x^{3}\sin x)-f(x)}{x^{3}\sin x} $不存在。类似地， $ \lim_{x\to0}\varphi(x)=0\Rightarrow\lim_{x\to0}\frac{\sin\varphi(x)}{\varphi(x)}=1 $

 $ f''(x) $连续， $ (x-1)f'(x)-2(x-1)f'(x)=1-e^{-x} $，若 $ f'(1)=0 $，问： $ f(1) $是否为极值？

(2)  $ |x| < \sqrt{3} + f(x) + a $  $ [f(x)]^2 = g(x) $ 且  $ f(0) = 0, a > 0 $.  $ g(x) $ 在  $ [x] < 1 $ 时可导且  $ g(0) = 0, g(0) > 0 $, 问： $ f(0) $ 是否为极值？

解: (1)  $ f^{\prime}(x)-2f(x)=\frac{1-e^{-x}}{x-1} $，两边得  $ f(0)=1>0 $，故为极小值

(2)  $ f'(x) + 2a + i\pi + i(x) = g'(x) $，则  $ f''(0) = g'(0) > 0 $ 又  $ f'(0) = 0 $，故不是极值（而是拐点）

7.  $ f(x)= $ 阶可导且  $ \lim_{h\to0}\frac{f(x_0+h)-f(x_0)-f(x_0)}{h^2}=a\neq0 $，问： $ f(x) $ 在  $ x_0 $ 点处是否取得极值？

解：①显然  $ f'(x_0)=0 $ ，再洛： $ \lim_{h\to0}\frac{f'(x_0+h)}{2h}=\frac{1}{2}f'(x_0)=a $ ，即： $ \left\{\begin{array}{l}a>0: 极小值  \\ a<0: 极大值\end{array}\right. $ ①洛的时候注意  $ f(x_0) $ 是常数（因为极限为  $ h\to0 $）②不妨设  $ a>0 $ ，对  $ \lim_{h\to0}\frac{f(x_0+h)-f(x_0)}{h^2}=a>0 $ 用保号惟知  $ f(x_0+h)-f(x_0)>0 $ ，即极小值

8. 求  $ y^{(n)}(1) $  $ y = \frac{x^{n}}{1 + x} $ (2)  $ y = \frac{1 + x}{\sqrt{1 - x}} $

解(1)①n奇:  $ X+1=(X+y)(x^{n+1}-x^{n+2}+\cdots-x+y) $,  $ y=\frac{x^{n}+1-1}{1+x}=x^{n-1}-x^{n+1}-1-\frac{1}{1+x} $,  $ y^{(n)}=-(\frac{1}{1+x})^{(n)}=\frac{n!}{(1+x)^{n+1}}\Rightarrow y^{(n)}=\frac{n!}{(1+x)^{n+1}} $

②n偶:  $ X^{n}-1=(x+y)(x^{n-1}-x^{n-2}+\cdots+x-1) $,  $ y=\frac{x^{n-1}+1}{1+x}=x^{n-1}-x^{n-2}+\cdots-1+\frac{1}{1+x} $,  $ y^{(n)}=(\frac{1}{1+x})^{(n)}=\frac{n!}{(1+x)^{n+1}} $

 $$ \begin{array}{l} (2) y=\frac{2-(\vert x\vert)}{\sqrt{1-x}}=2(\vert x\vert)^{-\frac{1}{2}}-(\vert -x\vert)^{\frac{1}{2}}, \quad y^{10}=2-(\pm\sqrt[n]{(-\frac{1}{2})(-\frac{1}{2}-1)}\cdots(-\frac{1}{2}-n+1)(\vert x\vert)^{-\frac{1}{2}-n}-(\pm\sqrt[n]{(-\frac{1}{2})(\frac{1}{2}-1)})\cdots(\frac{1}{2}-n+1)(\vert -x\vert)^{\frac{1}{2}-n}\\ =(\frac{2n-1)!}{2^{n-1}}(\vert -x\vert)^{-\frac{1}{2}-n}+(\frac{2n-3)!}{2^{n}}(\vert -x\vert)^{\frac{1}{2}-n} \end{array} $$ 

9. 求  $ f(x) = e^{x} \sin x $ 在 x = 0 处带拉格朗日余项的泰勒公式

解由 $ T_{3} $和 $ f^{(W)}(x)=(\sqrt{2})^{n}e^{x}\sin(x+\frac{\pi}{4}) $，故 $ f(x)=\sum_{k=0}^{n}\frac{f^{(k)}(x)}{k!}x^{k}+\frac{f^{(m)}(\theta x)}{(m+1)!}x^{m}=\sum_{k=1}^{n}(\sqrt{2})^{k}\sin\frac{k\pi}{4}x^{k}+\frac{(\sqrt{2})e\sin(\theta x+\frac{\pi k\pi}{4})}{(n+1)!}x^{n+1} $ ( $ 0<\theta<1 $)

 $ 10 $设 $ \sqrt{x^{2}+y^{2}}=e^{\arctan\frac{y}{x}} $，求 $ y^{2} $ (2) $ y^{2}e^{y}=1 $，求 $ y^{2} $

解由 $ \frac{1}{2}\ln(x^{2}+y^{2})=\arctan\frac{y}{x} $知 $ \frac{x\cdot dx+y\cdot dy}{x^{2}+y^{2}}=\frac{x\cdot dy-y\cdot dx}{x^{2}y^{2}} $， $ y^{2}=\frac{x+y}{xy} $，不难求得 $ y^{2}=\frac{2(x^{2}+y^{2})}{(x-y)^{2}} $

(2)  $ y = x \ln y \Rightarrow y' = \frac{y \ln y}{y - x} $， $ y^{2} \ln^{2} y + (y - x)^{3} y' = (y^{2} - xy) \ln y^{2} + 2(y^{2} - xy) \ln y \Rightarrow y'' = 2y^{2} \ln y - 2xy \ln y - xy \ln y^{2} y $

 $ y = \frac{x \ln y}{y - x} $ ( $ \frac{(y - 2x)y \ln y}{(y - x)^{3}} $) 注：导数式子有分母时，先消去分母

11.  $ \lim f(x) $ 与  $ \lim f(x) $ 设  $ f(0) $ 在  $ (0, +\infty) $ 可导，判断  $ (1) $  $ x \neq +\infty $  $ f(x) $ 存在  $ \Rightarrow $  $ \lim_{x \to +\infty} f'(x) $ 存在  $ f(x) $ 存在  $ \Rightarrow $  $ \lim_{x \to +\infty} f(x) $ 存在

(3)  $ \lim_{x \to +\infty} f(x) = 0 \Rightarrow f(x) $ 在  $ x \to +\infty $ 时有界 (4)  $ \lim_{x \to +\infty} [f(x) + f'(x)] $ 存在  $ \Rightarrow \lim_{x \to +\infty} f'(x) = 0 $ (5)  $ f(x) $ 有界且二阶可导， $ \lim_{x \to +\infty} f'(x) $ 存在  $ \Rightarrow \lim_{x \to +\infty} f(x) $ 存在

(6)  $ \lim_{x \to +\infty} f(x) = \infty \Rightarrow \lim_{x \to 0^{+}} f'(x) = 0 $ (7)  $ \lim_{x \to 0^{+}} f'(x) = 0 \Rightarrow \lim_{x \to 0^{+}} f(x) = 0 $

解: (1)  $  f(x) = \frac{\sin x^{2}}{x}  $ (2)  $  f(x) = x  $ (3)  $  f(x) = \sqrt{x}  $ ( $  \ln x  $ 亦可) 注:  $ \lim_{x \to +\infty} f'(x) = a \neq 0 \Rightarrow f(x) $ 在  $ x \neq +\infty $ 无界. 因  $ a > 0 $ 则  $  f(x) = f(x_0) + \int_{x_0}^{x} f(t) \, dt > f(x_0) + \frac{a}{2}(x - x_0)  $

(4)  $ \sqrt{x+1} $  $ \lim_{x\to+\infty}f(x)=\lim_{x\to+\infty}\frac{f(x)e^x}{e^x}\stackrel{\text{洛}}{=}\lim_{x\to+\infty}\left\{\left[f(x)+f'(x)\right]\right\}=\lim_{x\to+\infty}f'(x)=0 $ (5)  $ x $ 取  $ f=\sin\sqrt{x}, f''=-\frac{\sin\sqrt{x}-\frac{1}{\sqrt{x}}\cos\sqrt{x}}{4x}\rightarrow0 $

(6)  $  f(x) = \frac{1}{x} + \sin\frac{1}{x}  $ 取  $  x_n = \frac{1}{(2n+1)\pi}  $ 与  $  y_n = \frac{1}{2n\pi}  $ 有  $  f' \to 0, -\infty  $ 故  $  \lim_{x \to 0} f'  $ 不存在 (7)  $  f(x) = \sqrt{x}  $

### 12.  $ f(x) $ 在  $ (0, +\infty) $ 有界且可导， $ f(x) $ 单增，证明： $ \{f(n)\}, \{n \in \mathbb{N}\} $ 均收敛

证：(1) 由  $ f(x) $ 保号性知  $ f(x) $ 单调 (2)  $ \left\{\begin{array}{l}f(2x)-f(x)=xf(3) \\ f(x)-f(x)=\frac{x}{2}f(4)\end{array}\right. $ ( $ \frac{x}{2}<\eta<x<3<2x $) 由  $ (u\sin\lim_{x\to+\infty}f(2x)-f(x)=0 $ 于是  $ \lim_{x\to+\infty}x\cdot f(3)=0 $，同理  $ \lim_{x\to-\infty}x\cdot f(\eta)=0 $。由夹逼知  $ \lim_{x\to+\infty}x\cdot f(x)=0 $

13. 判断： $ f(x) $ 在 x=0 处连续且  $ \lim_{n\to+\infty}\frac{f\left(\frac{1}{n}\right)}{\frac{1}{n}} $ 存在，那么  $ f(x) $ 在 x=0 处右导数存在？

解：取  $ f(x)=\left\{\begin{array}{l}x, x=\pm\pi \\ x, x\neq\pm\pi\end{array}\right. $ 右导数不存在

14.  $ f(x) $ 在  $ [a, b] $ 上有定义， $ (a, b) $ 内可导. 判断  $ (1) $  $ f(a)f(b) < 0 \Rightarrow \exists \xi \in (a, b) $ 使  $ f(\xi) = 0 $  $ (2) $  $ \forall \xi \in (a, b), \lim_{x \to \xi} [f(x) - f(b)] = 0 $

(3)  $ \exists S \in (a, b) $ 使  $ f(b) - f(a) = f'(S)(b - a) $

解：(1)(3) $ \times $不知 $ [a,b] $上连续 (2) $ \sqrt{(a,b)} $内连续

# 一元积分

## 一、不定积分

1. 根无念 处处可导，连续

 $ x\in I $，若∃可导函数 $ F(x) $，对 $ \forall x\in I $都有 $ F'(x)=f(x) $，则称 $ F(x) $是 $ f(x) $在 $ I $上的一个原函数称 $ f(x)dx=F(x)+C $为 $ f(x) $在 $ I $上的不定积分→全体原函数

### 2. 原函数存在定理

(1) 连续函数必有原函数证:  $ \Delta F = F(x + \Delta x) - F(x) = \int_{a}^{x} f(t) dt - \int_{a}^{x} f(t) dt = \int_{x}^{x + \Delta x} f(t) dt = f(x) \cdot \Delta x $

 $ F'(x) = \lim_{\Delta x \to 0} \frac{\Delta F}{\Delta x} = \lim_{\Delta x \to 0} f(x) = \lim_{x \to x} f(x) \cdot \frac{1}{x} $

①处利用f(x)连续

推论： $ f(x) $连续 $ \Rightarrow\left\{\begin{array}{l} \int f(x) dx=\int_{a}^{x} f(t) dt+C \\ \left[\int_{a}^{x} f(t) dt\right]^{\prime}=f(x) \end{array}\right. $

(2) 含有第一类间断点和无穷间断点的t在包含该间断点的区间内，必没有原函数

证：①  $ F_{+}^{1}(x_{0})=\lim_{x\rightarrow x_{0}^{+}}\frac{F(x)-F(x_{0})}{x-x_{0}}\stackrel{\text{洛}}{=}\lim_{x\rightarrow x_{0}^{+}}F(x)\neq\lim_{x\rightarrow x_{0}^{-}}F(x)=F^{1}(x_{0})\Rightarrow $ 导数不存在

②  $ F'(x_{0}) = \log = \lim_{x \to x_{0}} F'(x) = \infty $ 方法同 3-P-T2

(3) 含有振荡间断点的不确定

例：有界振荡  $ f(x)=\left\{\begin{array}{ll}2x\sin\frac{1}{x}-\cos\frac{1}{x}(x\neq0)\\0\quad(x=0)\end{array}\right. $  $ F(x)=\left\{\begin{array}{ll}\frac{2}{x}\sin\frac{1}{x}(x\neq0)\\0\quad(x=0)\end{array}\right. $

无界振荡  $ f(x)=\left\{\begin{array}{ll}\frac{1}{x}\sin\frac{1}{x}&(x\neq0)\\0&(x=0)\end{array}\right. $ 不存在  $ F(x) $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//48c6e723-947b-437c-8e8e-99ddc1db4561/markdown_1/imgs/img_in_image_box_662_729_787_822.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A51Z%2F-1%2F%2F40a2971998a3c90ce374c1b7b9ece617551a7bc93142a688c2e47222bf2b8cf6" alt="Image" width="10%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//48c6e723-947b-437c-8e8e-99ddc1db4561/markdown_1/imgs/img_in_image_box_662_729_787_822.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A51Z%2F-1%2F%2F40a2971998a3c90ce374c1b7b9ece617551a7bc93142a688c2e47222bf2b8cf6" alt="Image" width="10%" />

 $ W $

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//48c6e723-947b-437c-8e8e-99ddc1db4561/markdown_1/imgs/img_in_image_box_835_722_947_819.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A51Z%2F-1%2F%2F877155bb1db67c0932704db6002c62008a862a766043a89797bb84f4922802bd" alt="Image" width="9%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//48c6e723-947b-437c-8e8e-99ddc1db4561/markdown_1/imgs/img_in_image_box_835_722_947_819.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A51Z%2F-1%2F%2F877155bb1db67c0932704db6002c62008a862a766043a89797bb84f4922802bd" alt="Image" width="9%" />

 $ P_{1} $

</div>


</div>


3.  $ \mathrm{d}\int f(x)dx = f(x)dx $  $ \int\mathrm{d}f(x) = f(x) + C $

4. 原函数非初等函数： $ \frac{\sin x}{x}, \frac{\cos x}{x}, \sin x^{2}, \cos x^{2}, e^{-x^{2}}, \frac{1}{\ln x}, \frac{x}{\ln x}, \frac{\ln x}{x+1}, \frac{e^{x}}{x}, \sqrt{1+x^{2}}, \sqrt{1+x^{4}} $

## 二、定积分  $ \int_{a}^{b}f(x)dx=\lim_{x\to0}\frac{n}{2x}+f(1) $ 可为  $ \frac{n-1}{2} $

1.  $ \int_{a}^{b}f(x)dx=\lim_{n\to\infty}\left(\frac{n}{n-1}\right)\frac{1}{n} $  $ f(a+\frac{b-a}{n}i)\frac{b-a}{n} $

 $ \frac{i}{n} $: 刚上的x, 即  $ S_{i} $

 $ \int_{0}^{1}f(x)dx=\lim_{n\to\infty}\sum_{i=1}^{n}f(\frac{i}{n})\frac{1}{n} $， $ \frac{1}{n} $:0到1上的dx，即 $ \Delta x_{i} $

2. 定积分存在定理/一元函数的常义可积性

闭区间 + 有限个一类  $ \Rightarrow $ 有界

(1) 充分条件 连续/单调/有界且只有有限个间断点/有限个第一类间断点

(2)必要条件 可积函数必有界 → 没有无空间断点 反例： $ f(x)=\left\{\begin{array}{l}1, x\in Q \\ 1, x\in R/Q\end{array}\right. $ 有  $ \lim\limits_{x\rightarrow0}\frac{n}{x+1}+f(x)\Delta x_{i}=\left\{\begin{array}{l}b-a \\ -b-a\end{array}\right. $

3. 性质

 $$ \int_{a}^{b}f(x)d x=f(\varsigma)(b-a) $$ 

 $$ \vert\int_{a}^{b}f(x)d x\vert\leq\int_{a}^{b}\vert f(x)\vert d x $$ 

4. 可积  $ \Leftrightarrow $ 有原函数

 $ sgn x = \begin{cases} 1, & x > 0 \\ 0, & x = 0 \end{cases} $ 在  $ [-1, 1] $ 可积无原函数(跳跃间断点)

 $ f(x)=\left\{\begin{array}{l}2x\sin\frac{1}{x^{2}}-\frac{2}{x}\cos\frac{1}{x^{2}},x\neq0\\0,x=0\end{array}\right. $ 有原函数 $ F(x)=\left\{\begin{array}{l}x\sin\frac{1}{x^{2}},x\neq0\\0,x=0\end{array}\right. $ 但不可积 $ (x_{1}=\frac{1}{\sqrt{2\pi}}\pi $ 时  $ f\rightarrow-\infty) $

## 三变限积分

### 1. 性质

(1)  $  F(x) = \int_{a}^{x} f(t) dt  $ 若存在，则一定连续

是原山(2)  $ f(x) $ 在 I 上连续，则  $ F(x) $ 在 I 上可导且  $ F'(x) = f(x) $

不是(3)若 $ \%0 $是 $ f(x) $的跳跃间断点，则 $ F(x) $在 $ \%0 $处不可导且 $ \left\{\begin{array}{l}F_{1}^{\prime}(x_{0})=\lim\limits_{x\rightarrow x_{0}^{-}}\frac{f(x)}{f(x_{0})}, 则 \lim\limits_{x\rightarrow x_{0}^{+}}\frac{f(x)}{f(x_{0})}=0 \\ F_{1}^{\prime}(x_{0})=\lim\limits_{x\rightarrow x_{0}^{+}}\frac{f(x)}{f(x_{0})}, F(x)\text{不是}f(x)\text{的原函数}\end{array}\right. $

(4) 若  $ x $ 是  $ f(x) $ 的可去间断点，则  $ F(x) $ 在  $ x_0 $ 处可导，且  $ F'(x_0) = \lim_{x \to x_0} f(x) \neq f(x_0) $

证1:  $ f(x) $ 可积  $ \Rightarrow |f(x)| \leq M $ 有界，则  $ 0 \leq |F(x + \Delta x) - F(x)| = |\int_{x}^{x + \Delta x} f(t) dt| \leq M |\Delta x| \rightarrow 0 $ 即  $ \lim_{\Delta x \to 0} F(x) = \Delta x $

 $$ \lim\limits_{\Delta x\to0}\frac{F(\Delta x+x)-F(x)}{\Delta x}=\lim\limits_{\Delta x\to0}\frac{\int\limits_{x}^{x+x}f(t)d t}{\Delta x}=\lim\limits_{\Delta x\to0}\frac{f(3)\Delta x}{\Delta x}=\lim\limits_{\Delta x\to0}f(3)\stackrel{①}{=}f(x) $$ 

①处利用了 $ f(x) $连续

 $$ 2.\left(\int_{\arcsin x}^{\arccos x} f(x,t) dt\right)^{\prime}=\int_{\arcsin x}^{\arccos x}\frac{\partial f(x,t)}{\partial x}dt+\int_{b(x)}^{1}(x,b(x))-a^{\prime}(x)f(x,a(x)) $$ 

## 四、反常积分 广义可积

1. 计算无穷  $ \int_{a}^{+\infty} f(x) dx = \lim_{x \to +\infty} F(x) - F(a) $ 无界函数  $ \int_{a}^{b} f(x) dx = F(b) - \lim_{x \to a} F(x) $

①等号右边两个积分都收敛时才称反常积分收敛. 只要有一个发散就发散

②一个积分只能有一个奇点，否则需拆分。奇点：∞和瑕点。瑕点：使 $ f(x) $在 $ x_{0} $邻域内无界的点。

③反常积分收敛时才能用偶倍奇零

### 2、判别

(1) 比较判别法仅含一个奇点的区间上，若  $ 0 \leq f(x) \leq g(x) $，则  $ f(x) $ 更易收敛

(2)比较判别法的极限形式

设f_{1}, g在工上连续， $ f(x) \geq 0, g(x) > 0 $，则 $ \lim_{x \to \infty} \frac{f(x)}{g(x)} = \begin{cases} 0: & f(x) \text{更易敛} \\ \neq 0, \neq \infty: & \text{同敛散} \\ \infty: & f(x) \text{更易散} \end{cases} $  $ \rightarrow $ 同阶无穷小/大

(3)  $ \int_{0}^{\frac{1}{2}}\frac{dx}{x^{p}} $ 收敛  $ 0<p<1 $ 收敛  $ P>1 $ 收敛  $ P\leq1 $ 收敛  $ P>1 $ 收敛  $ P\leq1 $ 收敛  $ P>1 $ 收敛  $ P\leq1 $ 收敛  $ P\leq1 $ 收敛  $ P>1 $ 收敛  $ P\leq1 $ 收敛  $ P\leq1 $ 收敛  $ P>1 $ 收敛  $ P\leq1 $ 收敛  $ P\leq1 $ 收敛  $ P

## 五、计算

### 1. 积分公式大观

 $$ \int\frac{d x}{\cos x}=|\ln|\frac{1}{\cos x}+\tan x|+C $$ 

 $$ \int\frac{d x}{\sin x}=\ln\vert\frac{1}{\sin x}-\frac{1}{\tan x}\vert+C $$ 

 $$ \tan x d x=-\ln\vert\cos x\vert+C\quad\int\frac{d x}{\sin^{2}x}=-\frac{1}{\tan x}+C\quad\int\frac{\tan x d x}{\cos x}=\frac{1}{\cos x}+C\quad\int\frac{d x}{\sin x\tan x}=-\frac{1}{\sin x}+C $$ 

 $$ \tan^{2}x d x=\int\frac{1}{\cos^{2}x}+d x=\tan x-x+c $$ 

 $$ \int\frac{d x}{\sqrt{a^{2}-x^{2}}}=\arcsin\frac{x}{a}+c\quad\int\frac{d x}{x^{2}-a^{2}}=\frac{1}{2a}\ln\left|\frac{x-a}{x+a}\right|+c $$ 

 $$ \int_{\sqrt{x^{2}\pm a^{2}}}^{\frac{dx}{\sqrt{x^{2}\pm a^{2}}}}=\vert\ln\vert x+\sqrt{x^{2}\pm a^{2}}\vert+C $$ 

 $$ \int_{\sqrt{a^{2}-x^{2}}}d x=\frac{a^{2}}{2}\arcsin\frac{x}{a}+\frac{x}{2}\sqrt{a^{2}-x^{2}}+C(x=a\sin t\text{时}\frac{a^{2}}{2}(t+\frac{\sin2t}{2})+C) $$ 

 $$ \int e^{ax}\sin b x dx=\frac{\left(e^{ax}\right)^{\prime}\left(\sin b x\right)^{\prime}}{a^{2}+b^{2}}+c=\frac{1}{a^{2}+b^{2}}\left(a e^{ax}\sin b x-b e^{ax}\cos b x\right)+c $$ 

 $$ \int e^{a x}\cos b x d x=\frac{\left|e^{a x}\cos b x\right|^{2}}{a^{2}+b^{2}}+C=\frac{1}{a^{2}+b^{2}}(a e^{a x}\cos b x+b e^{a x}\sin b x)+C $$ 

 $$ \left\{\begin{array}{l}\frac{x \pm 1}{x^{2}} = 1 \pm \bcancel{x}^2 \rightarrow d (x \mp \frac{1}{x}) \quad \sin 2x \rightarrow d \sin^2 x = -d \cos^2 x \\ 1 + \ln x \rightarrow d (x \ln x) \quad \cos 2x \rightarrow d \sin x \cos x = \frac{1}{2} d \sin 2x \\ 1 + \tan^2 x \rightarrow d \tan x \end{array}\right. $$ 

### 2. 积分法

(1) 凑微分  $ \int f[g(x)]g(x)dx\stackrel{u=g(x)}{=}\int f(u)du $

找简单但落单的项，如 $ \int\frac{\sqrt{x}dx}{\sqrt{4-x^{2}}}  $全 $ t=x^{\frac{3}{2}} $得 $ I=\frac{2}{3}\arcsin\frac{x^{\frac{3}{2}}}{2}+C $

(2)换元法  $ \int f(x)dx \xlongequal{x=g(u)} \int f[g(u)]g'(u)du $

① ∫内有平方： $ \sqrt{a^{2}-x^{2}}\rightarrow x=a\sin t $， $ |t|<\frac{\pi}{2} $。  $ \sqrt{a^{2}+x^{2}}\rightarrow x=a\tan t $， $ |t|<\frac{\pi}{2} $。  $ \sqrt{x^{2}-a^{2}}\rightarrow x=a\sec t $， $ \begin{cases}0<t<\frac{\pi}{2}&(x>0)\\\frac{\pi}{2}<t<\pi&(x<0)\end{cases} $

②√无平方：复杂项=t 或者如 $ \sqrt{1-\cos t}=\sqrt{2}|\sin\frac{1}{2}| $

③分母比分子高2次及以上：倒代换

(3) 分部积分  $ \int u \, dv = uv - \int v \, du $

表格法：导到 $ x^{3}+2x+6 $  $ 3x^{2}+2 $  $ 6x $ 6 0 则 $ \int(x^{3}+2x+6)e^{2x}dx=\frac{x^{3}+2x+6}{2}e^{2x}-\frac{3x^{2}+2}{4}e^{2x}+\frac{6x}{8}e^{2x}-\frac{6}{16}e^{2x} $

(4)有理函数

 $$ (a x+b)^{k}\rightarrow\frac{A_{1}}{a x+b}\sim\frac{A_{k}}{(a x+b)^{k}}\quad(p x^{2}+q x+r)^{k}\rightarrow\frac{A_{1}x+B_{1}}{p x^{2}+q x+r}\sim\frac{A_{k}x+B_{k}}{(p x^{2}+q x+r)^{k}} $$ 

①展开式中可为x赋使零为0的值

②对 $ I_{m}=\int\frac{dx}{(x^{2}+a)^{m}} $有 $ I_{m}=\frac{x^{2}}{2a^{2}(m-1)(x^{2}+a)^{m+1}}+\frac{2m-3}{2a^{2}(m-1)}I_{m-1} $ (由 $ I_{m}=\frac{x}{(x^{2}+a^{2})^{m}}-\int\frac{x(-2mx)dx}{(x^{2}+a^{2})^{m+1}}=\frac{x}{(x+a)^{m}}+2mI_{m-2ma}^{2}I_{m+1} $可得)

(5)三角函数

 $$ \rightarrow R(\sin x,\cos x)=-R(-\sin x,\cos x) $$ 

 $$ R(\sin x,\cos x)=R(-\sin x,-\cos x) $$ 

① 关于  $ \sin x $ 为奇函数，令  $ \cos x = t $；否则令  $ \tan x = t $

②令 $ t=\tan\frac{x}{2} $，则 $ \int R(\sin x,\cos x)dx=\int R(\frac{2t}{1+t^{2}},\frac{1-t^{2}}{1+t^{2}})\frac{2}{1+t^{2}}dt $

 $$ \textcircled{3}\int_{0}^{\frac{\pi}{2}}\sin^{n} x dx=\int_{0}^{\frac{\pi}{2}}\cos^{n} x dx=\left\{\begin{array}{ll}\frac{n-1}{n}\cdot\frac{n-3}{n-2}&\cdots\frac{2}{3}\cdot1\rightarrow 下记为A\\\frac{n-1}{n}\cdot\frac{n-3}{n-2}&\cdots\frac{1}{2}\cdot\frac{\pi}{2}\rightarrow 下记为B\end{array}\right.\quad\textcircled{1} \int_{0}^{\pi}\sin^{n} x dx=2\int_{0}^{\frac{\pi}{2}}\sin^{n} x dx $$ 

 $$ \int_{0}^{2\pi}\cos^{n} x d x=\int_{0}^{2\pi}\sin^{n} x d x=\left\{\begin{array}{ll}0&(n奇)\\ 4b&(n偶)\end{array}\right.\quad\int_{0}^{\pi}\int_{0}^{2\pi}为0或2,4倍 $$ 

④  $ a\frac{\sin x + b\cos x}{\sin x + \cos x} = \frac{1}{2} \frac{(a+b)(\sin x + \cos x) + (b-a)(\cos x - \sin x)}{\sin x + \cos x} $ 系数与其后式子在形式上一致

 $ \int_{0}^{\frac{\pi}{2}} \frac{\sin^{p}x}{\sin^{p}x + \cos^{p}x} dx = \int_{0}^{\frac{\pi}{2}} \frac{1}{1 + \tan^{p}x} dx = \frac{1}{2} \int_{0}^{\frac{\pi}{2}} dx = \frac{\pi}{4} $ ( $ \frac{1}{2}x = \frac{\pi}{2} - t $)

⑤  $ \int\sin^{n}xdx $. n奇:凑微分. n偶:降幂

#### (6) 定积分

①连续函数 $ f(x) $以T为周期，则∀a均有 $ \int_{a}^{a+T}f(x)dx=\int_{0}^{T}f(x)dx $

证：左边  $ = \int_{a}^{0} + \int_{0}^{T} + \int_{T}^{a+T} f(x) dx $，而  $ \int_{T}^{a+T} f(x) dx = \int_{0}^{a} f(t+T) dt = \int_{0}^{a} f(t) dt $ ∴ 在边  $ = \int_{0}^{T} f(x) dx $ 推论：连续函数是以T为周期的奇函数，则  $ \int_{0}^{T} f(x) dx = 0 $

 $$ \int_{0}^{T}t(x)dx\xlongequal{周期}\int_{-T}^{0}t(x)dx,\int_{0}^{T}t(x)dx\xlongequal{奇}\int_{0}^{T}t(x)dx $$ 

②区间再现： $ \int_{a}^{b}f(x)dx=\int_{a}^{b}f(a+b-x)dx $

推论： $ \int_{0}^{\pi}x f(\sin x)dx=\frac{\pi}{2}\int_{0}^{\pi}f(\sin x)dx=\pi\int_{0}^{\frac{\pi}{2}}f(\sin x)dx=\pi\int_{0}^{\frac{\pi}{2}}f(\cos x)dx $  $ \int_{0}^{\frac{\pi}{2}}x[f(\sin x)+f(\cos x)]dx=\frac{\pi}{2}\int_{0}^{\frac{\pi}{2}}f(\sin x)dx $

③类奇偶性：设  $ \left\{\begin{array}{l} f(-x)+f(x)=A \\ g(-x)=g(x) \end{array}\right. $，则  $ \int_{-a}^{a} f(x)g(x) dx = A \int_{0}^{a} g(x) dx $ 例： $ \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}(\arctan e^{x})\sin^{2}x dx = \frac{\pi}{2}\int_{0}^{\frac{\pi}{2}}\sin^{2}x dx = \frac{\pi^{2}}{8} $

(7) 变限积分

①  $ F'(x)=\frac{d}{ax}\left[\int_{4(x)}^{4x}(f(t)dt)\right]=f\left[\varphi_{1}(x)\right]\varphi_{2}(x)-f\left[\varphi_{1}(x)\right]\varphi_{1}^{\prime}(x) $，其中 $ f(x) $连续  $ \rightarrow $ 即 $ \int_{0}^{a}f(t)dt=0 $，故 $ F(0)=F(a)=0 $

②  $ f $ 奇  $ \Rightarrow $  $ \int_{a}^{x}f(t)dt $ 偶  $ f $ 偶  $ \Rightarrow $  $ \int_{a}^{x}f(t)dt $ 或  $ \int_{a}^{x}f(t)dt=\int_{0}^{x}f(t)dt $ 奇

 $ F(0)=0 $  $ \Rightarrow $  $ \int_{a}^{x}f(t)dt $ (a not an  $ \int_{a}^{x}f(t)dt $  $ \neq $  $ \int_{0}^{x}f(t)dt $) 非奇非偶

f 以 T 为周期，则  $ \int_{0}^{x}f(t)dt $ 以 T 为周期  $ \Leftrightarrow $  $ \int_{0}^{T}f(x)dx=0 $ 一个周期的面积为 0

(8) 反常积分

①  $ I(x)=\int_{0}^{+\infty}x^{d-1}e^{-x}dx\stackrel{x-t^{2}}{=}2\int_{0}^{+\infty}t^{2d-1}e^{-t^{2}}dt $  $ \int_{0}^{+\infty}x^{n}e^{-x}dx=n! $  $ I'(d+1)=dI'(d) $

 $ I'(\frac{1}{2})=\int_{0}^{+\infty}x^{-\frac{1}{2}}e^{-x}dx=\sqrt{\pi} $ 此时才可能发散

 $ \alpha>0 $ 时 I(d) 收敛 证：因为  $ \int_{0}^{+\infty}x^{d-1}e^{-x}dx $ ②  $ d-1<0 $ 时  $ \int_{0}^{+\infty}\frac{e^{-x}}{x^{d-1}}dx\sim\int_{0}^{1}\frac{dx}{x^{d-1}}\therefore a<|-d|\therefore a<d-1 $

 $ B(p,q)=\int_{0}^{1}x^{p-1}(1-x)^{q-1}dx=\frac{I(p)I(q)}{I(p+q)} $  $ (p,q>0) $ 注：贝塔分布  $ f=\frac{x^{p+1}(1-x)^{q-1}}{B(p,q)} $

## 六、几何应用与物理应用

1. 面积  $ S d\sigma $

 $$ S_{扇}=\frac{1}{2}r^{2}\theta $$ 

 $$ S=\int\limits_{a}^{b}\vert y_{1}(x)-y_{2}(x)\vert d x $$ 

 $$ S=\frac{1}{2}\int\limits_{d}^{\beta}\vert\gamma_{1}^{2}(\theta)-\gamma_{2}^{2}(\theta)\vert d\theta $$ 

将 $ \left\{\begin{array}{l} y=f\left[x(t)\right]=y(t) \\ x=x(t) 代入 \end{array}\right. $

 $$ S=\int\limits_{\alpha}^{\beta}\left|y_{1}(t)-y_{2}(t)\right|x^{\prime}(t)d t $$ 

2. 体积  $ 2\pi\iint\limits_{V}(x,y)d\sigma $ 如：绕  $ y=y_{0} $ 转： $ 2\pi\iint\limits_{V_{0}-V}d\sigma=2\pi\int_{a}^{b}1y_{0}-y_{1}d\gamma\int_{x_{0}(y)}^{x_{2}(y)}dx $

知道y但绕x转  $ V_{x}=\int_{a}^{b}\pi y^{2}(x)dx $ 知道y绕y转  $ V_{y}=2\pi\int_{a}^{b}x|y(x)|dx $ 绕极轴  $ V=\frac{2\pi}{3}\int_{a}^{b}r^{3}(\theta)\sin\theta d\theta $  $ y=f(x) $绕 $ Ax+By+C=0 $转  $ V=\frac{\pi}{(A^{2}+B)^{2}}\int_{a}^{b}\left[Ax+Bf(x)+C\right]^{2}\left|Af'(x)-B\right|dx $

3. 弧长

 $$ S=\int_{a}^{b}\sqrt{1+y^{2}}(x)d x $$ 

 $$ S=\int_{d}^{B}\sqrt{r^{2}(\theta)+r^{\prime}^{2}(\theta)}\ d\theta $$ 

 $$ S=\int\limits_{\alpha}^{\beta}\sqrt{x^{2}(t)+y^{2}(t)}\ dt $$ 

4. 旋转侧面积  $ 2\pi|y(x)|\cdot\text{弧长} $

 $$ S=2\pi\int\limits_{L}\gamma d s $$ 

 $$ S=2\pi\int_{a}^{b}|y|\sqrt{1+y^{2}(x)}d x $$ 

 $$ S=2\pi\int\limits_{d}^{B}\vert r(\theta)\sin\theta\vert\sqrt{r^{2}(\theta)+r^{2}(\theta)}d\theta $$ 

 $$ \rightarrow a \leqslant x \leqslant b, 0 \leqslant y \leqslant t (x) $$ 

 $$ S=\int\limits_{d}^{\beta}2\pi|y(t)|\sqrt{x^{2}(t)+y^{2}(t)}d t $$ 

5. 曲边梯形的形心

 $$ \overline{x}=\frac{\int_{a}^{b}xf(x)dx}{\int_{a}^{b}f(x)dx}\quad\overline{y}=\frac{\frac{1}{2}\int_{a}^{b}f(x)dx}{\int_{a}^{b}f(x)dx}\quad 证 \quad:\overline{x}=\frac{\int_{a}^{b}x d\sigma}{\int_{a}^{b}d\sigma}=\frac{\int_{a}^{b}dx\int_{0}^{f(x)}x dy}{\int_{a}^{b}dx\int_{0}^{f(x)}dy}\quad\overline{y}=\frac{\iint y d\sigma}{\iint d\sigma}=\frac{\int_{a}^{b}dx\int_{0}^{f(x)}y dy}{\int_{a}^{b}dx\int_{0}^{f(x)}dy} $$ 

### 6. 物理应用

(1) 变力沿直线做功  $ W = \int_{a}^{b} F(x) dx $  $ dw = F(x) dx $

(2) 抽水做功  $ W = p g \int_{a}^{b} x \, S(x) \, dx $  $ dF = g \cdot dm = p g \, dv = p g S(x) \, dx $  $ dw = dF x = p g x S(x) \, dx $

(3) 静水压力  $ F = P g \int_{a}^{b} x [f_{1}(x) - f_{2}(x)] dx $  $ P = \rho g x $,  $ dS = [f_{1}(x) - f_{2}(x)] dx $,  $ dF = P \cdot dS = \rho g x [f_{1} - f_{2}] dx $

(4) 引力  $ \xrightarrow{2\quad a\quad M_{x}} $  $ F=\int_{-2}^{0}\frac{G m\ M}{(a-x)^{2}}dx $ M:线密度

### 7. 古尔金定理

S绕不与它相交的轴旋转一周的旋转体体积 = S × 重心划出的圆周长

例： $ x^{2}+(y-a)^{2}=R^{2} $ (R<a)绕x轴转一周， $ V=\pi R^{2}\cdot2\pi a=2\pi^{2}aR^{2} $

## 七、中值定理

1.  $ f \in C([a, b]) $，则  $ \exists S \in (a, b) $ 使  $ \int_{a}^{b} f(x) dx = f(s)(b - a) $

如： $ \lim_{x \to +\infty} \int_{x}^{x+2} f(t) dt = C - \lim_{x \to +\infty} f(s) $

 $ f, g \in C([a, b]) $ 且  $ g $ 不变号，则  $ \exists S \in (a, b) $ 使  $ \int_{a}^{b} f(x) g(x) dx = f(s) $  $ \int_{a}^{b} g(x) dx $

注： $ \int_{0}^{x} f(t) dt $ 在  $ x > 0, x < 0 $ 都可  $ \int_{0}^{x} f(t) dt = x f(x) $，但  $ \xi $ 位于  $ 0, x $ 之间， $ \left\{\begin{array}{l} x > 0: 0 < \xi < x \\ x < 0: x < \xi < 0 \end{array}\right. $，不可  $ R $ 考虑  $ 0 < \xi < x $

2.  $ (\int_{a}^{b} f(x) g(x) dx)^{2} \leq \int_{a}^{b} f(x) dx \int_{a}^{b} g(x) dx $  $ (t, g \in C[a, b]) $

注：由 $ \overrightarrow{a}\cdot\overrightarrow{b}=||\overrightarrow{a}||||\overrightarrow{b}||\cos\theta\leq||\overrightarrow{a}||||\overrightarrow{b}|| $知 $ (a,b_{1}+a_{2}b_{2})^{2}\leq(a_{1}^{2}+a_{2}^{2})(b_{1}^{2}+b_{2}^{2}) $

## 八、容易做复杂的积分

1.  $ \int\frac{1}{\sin t\cos t}dt = \int\frac{\sin^{2}t + \cos^{2}t}{\sin^{2}t\cos t}dt = |\ln|\frac{1}{\cos t} + \tan t| - \frac{1}{\sin t} + C $

注： $ \int\frac{d\sin t}{\sin^{2}t(1-\sin^{2}t)} = -\frac{1}{\sin t} + \frac{1}{2}|\ln|\frac{\sin t+1}{\sin t-1}| + C $

2.  $ \int\frac{a^{2}}{x^{2}\sqrt{1+x^{2}}}dx = \int\frac{a^{2}}{x^{3}\sqrt{1+(\frac{a}{x})^{2}}} = -\sqrt{1+(\frac{a}{x})^{2}} + C $

注： $ \int\frac{a^{2} + x^{2} - x^{3}}{x^{2}\sqrt{1+x^{2}}}dx = \int\frac{\sqrt{x+a^{2}}}{x^{3}}dx - \int\frac{1}{\sqrt{x^{2}+a^{2}}}dx = \ln(x + \sqrt{x^{2}+a^{2}}) - \frac{\sqrt{x+a^{2}}}{x} $

 $ -\ln(x + \sqrt{x^{2}+a^{2}}) + C = -\frac{\sqrt{x+a^{2}}}{x} $，其中  $ \sqrt{x^{2}+a^{2}} $ 令  $ x = \tan t $ 即为  $ T_{1} $

①处认为  $ x > 0 $，若分类讨论亦可得  $ I = -\frac{\sqrt{x^{2}+a^{2}}}{x} + C $

3.  $ \int\frac{1}{x\sqrt{x+x}}dx = \int\frac{dx}{x^{2}\sqrt{1+x}} = -2\sqrt{1+\frac{1}{x}} + C $

注：①处认为  $ x > 0 $，而  $ x < 1 $ 时  $ I = 2\sqrt{1+x} + C $，故应统一为  $ -\frac{2}{x}\sqrt{x+x} + C $

4.  $ \int\frac{x^{2}}{1+t}dt + \int\frac{\frac{1}{x^{2}}\ln t}{1+t^{2}}dt = \frac{1}{2}\ln^{2}x $

注：第二项令  $ u = \frac{1}{2}t $

## 九、难算但不难的积分

1.  $ \int\ln(1+\sqrt{\frac{1+x}{x}})dx(x>0)=x\ln(1+\sqrt{\frac{1+x}{x}})+\frac{1}{2}\ln(\sqrt{1+x}+\sqrt{x})-\frac{1}{2}\frac{\sqrt{x}}{\sqrt{1+x}+\sqrt{x}}+C $

注： $ \sqrt{\frac{1+x}{x}}=t $， $ I=\frac{\ln(1+t)}{t-1}-\int\frac{1}{t-1}\cdot\frac{1}{t+1}dt $

##### 一元积分

1. 设  $ f(x) \in C([a,b]) $，证明： $ \exists S \in (a,b) $ 使  $ \int_{a}^{b} f(x) \, dx = f(3)(b-a) $ （积分中值定理）

解：法1：设 $ F(x)=\int_{a}^{x}f(t)dt $，由拉中： $ F(b)-F(a)=F'(3)(b-a) $得证

法2：设 $ k=\frac{\int_{a}^{b}f(x)dx}{b-a} $， $ F(x)=\int_{a}^{x}f(t)dt-k(x-a) $，则 $ F'(x)=f(x)-k $，由 $ F(b)=F(a)=0\Rightarrow F'(3)=0 $

注：若改为 $ \{a,b\} $，才可这样证： $ m\leq f(x)\leq M $，则 $ m\leq\frac{\int_{a}^{b}f(x)dx}{b-a}\leq M $，有 $ f(3)=\frac{\int_{a}^{b}f(x)dx}{b-a} $

2. 设  $ f(x), g(x) \in C([a, b]) $，且  $ g(x) $ 在  $ [a, b] $ 上不变号，证明： $ \exists S \in (a, b) $ 使  $ \int_{a}^{b} f(x) g(x) dx = f(S) \int_{a}^{b} g(x) dx $

解：①  $ g(x)=0 $ 成立 ②  $ g(x)\neq0 $，不妨设  $ g(x)>0 $。设  $ F(x)=\int_{a}^{x}f(t)g(t)dt $， $ g(x)=\int_{a}^{x}g(t)dt $，由柯中， $ \frac{\int_{a}^{b}f(x)g(x)dx^{\prime}-0}{\int_{a}^{b}g(x)dx-0}=\frac{f(x)}{g(x)}=f(x) $

注：同栈若改为 $ f(a,b) $，才可这样证： $ m \leq f(x) \leq M $，则 $ m \leq \frac{\int_{a}^{b}f(x)g(x)dx}{\int_{a}^{b}g(x)dx} \leq M \Rightarrow f(x) $

3. 证明柯西不等式：设  $ f(x), g(x) \in C[a, b] $，则  $ (\int_{a}^{b} f(x) g(x) dx)^{2} \leq \int_{a}^{b} f(x) dx \int_{a}^{b} g(x) dx $

解 $ ^{①} $注意到：对 $ \forall t\in\mathbb{R} $均有 $ [t f(x)+g(x)]^{2}\geq0 $，展开并积分，有 $ [\int_{a}^{b}f(x)dx]t^{2}+2\left[\int_{a}^{b}f(x)g(x)dx\right]t+\int_{a}^{b}g(x)dx\geq0 $

①若 $ \int_{a}^{b}f(x)dx=0 $，则 $ f(x)=0 $，显然成立②若 $ \int_{a}^{b}f(x)dx>0 $，则由 $ \Delta\leq0 $可证得

②令 $ F(t)=\int_{a}^{t}f^{2}\int_{a}^{t}g^{2}-[\int_{a}^{t}fg]^{2} $，由 $ F'(t)=f^{2}\int_{a}^{t}g^{2}+g^{2}\int_{a}^{t}f^{2}-2fg\int_{a}^{t}fg=f_{a}^{2}f(t)g_{a}^{2}g+g_{a}^{2}(t+f(x))-2f(t)g(t+f(x))g_{a}dx $

 $ \int_{a}^{b}[f(t)g(x)-f(x)g(t)]^{2}dx\geq0 $ 知 $ F(t)\geq F(a)=0 $

4.  $ f(x) \in C[0,1] $,  $ \int_{0}^{1} f(x) dx = A $, 证明:  $ \int_{0}^{1} dx \int_{x}^{1} f(x) f(y) dy = \frac{A^{2}}{2} $

证:  $ I = \int_{0}^{1} dy \int_{y}^{1} f(x) f(y) dx $ ① 压换序  $ \int_{0}^{1} dx \int_{0}^{x} f(x) f(x) dx = \frac{1}{2} \int_{0}^{1} dx (\int_{0}^{x} f(x) dy = \frac{1}{2} \int_{0}^{1} f(x) dx \int_{0}^{1} f(x) dy) $

②  $ I = \frac{1}{2} \left[ \int_{0}^{1} \int_{x}^{1} f(x) dx + \int_{0}^{1} \int_{y}^{1} f(x) dx \right] = \frac{1}{2} \int_{0}^{1} \int_{x \leq y \leq z} f(x) f(y) dx dy = \frac{A^{2}}{2} $ 被积函数相同，积分区域叠加

5.  $  f(x) \in C  $. 证明:  $ \int_{0}^{x} f(x-y) \, dx \, dy = \int_{-A}^{A} f(t) \left( (A-1)t \right) dt $ D:  $ \left| x \right| \leq \frac{A}{2}, |y| \leq \frac{A}{2} $

证： $ I=\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}dx\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}f(x-y)dy=\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}dx\int_{x-\frac{\pi}{2}}^{x+\frac{\pi}{2}}f(u)du=\int_{-A}^{0}du\int_{-\frac{\pi}{2}}^{u+\frac{\pi}{2}}f(u)dx+\int_{0}^{A}du\int_{u-\frac{\pi}{2}}^{\frac{\pi}{2}}f(u)dx $

 $ \int_{-A}^{0}f(u)(A+u)du+\int_{0}^{A}f(u)(A-u)du=\int_{-A}^{A}f(u)(A-u)du $

6. 设  $ f(x) $ 在  $ x^{2}+y^{2}\leq1 $ 上有连续一阶偏导且在边界上取值为 0. 证明： $ f(0,0)=\lim_{\varepsilon\to0^{+}}-\frac{1}{2\pi}\iint_{D}x\frac{dx^{1}+y\frac{dy}{dy}}{x^{2}+y^{2}}dx dy $，其中， $ D:\varepsilon^{2}\leq x^{2}+y^{2}\leq1,\varepsilon>0 $

 $ f(\cos\theta, r\sin\theta) = -\ln2\pi $

7. 严谨证明： $ f(x) $ 在  $ [a, b] $ 连续， $ F(x) $ 在  $ [a, b] $ 连续， $ \lim_{x \to c} F(x) $ 与  $ \lim_{x \to c} F(x) $ 存在且  $ F'(x) = f(x) $ ( $ a < x < b, x \neq c $)，则  $ \int_{a}^{b} f(x) dx = F(x) \bigg|_{a}^{c-a} + F(x) \bigg|_{c+a}^{b} = F(b) - F(c+0) + F(-c-0) - F(a) $

证：引理1：f，F在 $ [a,b] $连续且F(x)是f(x)在 $ (a,b) $上的原函数，则 $ \int_{a}^{b}f(x)dx=F(b)-F(a) $。这是因为，

 $ F_{+}^{1}(a)=\lim_{x\to a^{+}}\frac{F(x)-F(a)}{x-a}\stackrel{ 洛 }{=}\lim_{x\to a^{+}}f(x)=f(a) $，同理 $ F_{-}^{1}(b)=f(b) $，故F(x)是f(x)在 $ [a,b] $上的原函数（开转闭区间）

引理2：f在 $ [a,b] $连续且F(x)是f(x)在 $ (a,b) $上的原函数且 $ \lim_{x\to a^{+}}F(x) $与 $ \lim_{x\to b^{+}}F(x) $都存在，则 $ \int_{a}^{b}f(x)dx= $

 $ F(x)\mid_{a=0}^{b-0} $。这是因为构造 $ G(x)=\begin{cases}F(x)&(x=a)\\F(x)&(a<x<b)\end{cases} $，则 $ G(x) $连续且 $ a<x<b $时 $ G(x)=F(x)=f(x) $，由1则可证。

综合以上，将 $ \int_{a}^{b}f(x)dx $拆成 $ \int_{a}^{b}f(x)dx+\int_{b}^{c}f(x)dx $即证毕。例： $ \int_{-1}^{1}\frac{d a\cdot x\cdot c\cdot a\cdot x}{d x}dx=-\frac{\pi}{2} $

8.  $ f(x) $ 不恒为 0，有连续导数且  $ \int_{0}^{x} f(x) dx = 0 $，记  $ M = \max_{x \in [0, +\infty)]} |f(x)| $ (1)  $ \forall x \in [0, +\infty) $ 有  $ |f(x)| \leq \frac{M}{2} $ (2)  $ \left|\int_{0}^{x} f(x) dx dy\right| \leq \frac{M}{8} $ (3)  $ 0 \leq x \leq 1, 0 \leq y \leq x $

证：(1) 反证法，不失一般性，设  $ f(x) > \frac{M}{2} $，由  $ |f(x)| \leq M \neq 0 $ (1)  $ x > \frac{M}{2} - M(x-h) $ ( $ h \leq x \leq 1 $) 则  $ \int_{0}^{x} f(x) dx > \int_{0}^{1} \cdots + \int_{0}^{1} \cdots = \frac{M}{2} - 2\ln(1-h) \geq 0 $ 矛盾

② 设  $ f(x) = \int_{0}^{x} f(t) dt $，则  $ \left\{\begin{array}{l}0 = F(1-x) + F(x)(1-x) + \frac{1}{2}F'(x) + (1-x)^2 \\0 = F(0) = F(1-x) + F'(x)(1-x) + \frac{1}{2}F''(x) + (1-x)^2\end{array}\right. $ 于是  $ |f(x)| = \frac{1}{2}\left|F''(x)(1-x)^2 - F'(x)(1-x)^2 + x^2\right| \leq \frac{M}{2} $

(2)  $ I = \int_{0}^{1} dy \int_{y}^{1} f(x) dx = \int_{0}^{1}(1-x)f(x) dx = \int_{0}^{1} \frac{1}{x-2} - y f(x) dy $ 故左边  $ \leq \frac{M}{2}\int_{0}^{1} \left|\frac{1}{x-2}\right| dy = \frac{M}{8} $

9. 证明： $ f(x)=\begin{cases}\frac{1}{\sqrt{x}}, & 0 < x \leq 1 \\ 0, & x=0\end{cases} $ 在 $ [0,1] $不可积

解: 在  $ [0,\frac{1}{n}] $ 上取  $ s_{1}=\frac{1}{n} $，其余  $ n-1 $ 个区间  $ \left[\frac{21}{n},\frac{1}{n}\right] $ 上取  $ S_{1}=\frac{1}{n} $ ( $ i=2,3\ldots n $). 则  $ S_{n}=\frac{1}{n}\cdot n^{2}+\frac{1}{n}\left(\sqrt{\frac{n}{2}}+\cdots+\sqrt{\frac{n}{n}}\right)=n+\frac{1}{\sqrt{n}}\left(\frac{1}{n^{2}}+\cdots+\frac{1}{n^{n}}\right)>n+\frac{1}{\sqrt{n}}\cdot\frac{n-1}{\sqrt{n}}\rightarrow0 $

# 一元积分-M

1. 设  $ f'(e^{x}) = \begin{cases} 1 & x < 0 \\ x + 1 & x \geq 0 \end{cases} $ 且  $ f(1) = 2 $，求  $ f(x) $

解： $ f(x)=\left\{\begin{aligned}&1&x<1\\ &mx+1&x\geq1\end{aligned}\right. $ 则 $ f(x)=\left\{\begin{aligned}&x+1,&x<1\\ &x\ln x+2,&x\geq1\end{aligned}\right. $ 注意定义域

2. 交换积分次序: (1)  $ I = \int_{0}^{2} dx \int_{x^{2}}^{x} f(x, y) dy $ (2)  $ I = \int_{-\frac{\pi}{4}}^{\frac{\pi}{2}} d\theta \int_{0}^{2a\cos\theta} f(r\cos\theta, r\sin\theta) rdr(a > 0) $

解: (3)  $ I = \int_{0}^{1} dx \int_{x^{2}}^{x} dy - \int_{1}^{2} dx \int_{x}^{x^{2}} dy = \int_{0}^{1} dy \int_{y}^{\sqrt{y}} dy - \int_{1}^{2} dy \int_{y}^{\sqrt{y}} fdx - \int_{2}^{4} dy \int_{\sqrt{y}}^{2} fdx $

 $$ (2) I = \int_{0}^{2a} r dr \int_{-\frac{\pi}{4}}^{\arccos\frac{r}{2a}} r d\theta + \int_{\sqrt{2a}}^{2a} r dr \int_{-\arccos\frac{r}{2a}}^{arccos\frac{r}{2a}} r d\theta $$ 

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//7aaf7c1b-8da3-4bab-a537-7a3e0986078d/markdown_1/imgs/img_in_image_box_598_515_851_630.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2Fa298fc995ce5287127d0d4150c8d73e661d253d8e2fc5a8915d097affe29ff8c" alt="Image" width="21%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//7aaf7c1b-8da3-4bab-a537-7a3e0986078d/markdown_1/imgs/img_in_image_box_598_515_851_630.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2Fa298fc995ce5287127d0d4150c8d73e661d253d8e2fc5a8915d097affe29ff8c" alt="Image" width="21%" />

x↑

 $ \rightarrow x $ 更清晰
临界 $ \theta=-\frac{\pi}{4}, r=\sqrt{2}a $

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//7aaf7c1b-8da3-4bab-a537-7a3e0986078d/markdown_1/imgs/img_in_image_box_857_371_1050_619.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2Fa90e1e83ab010872bd2241fc342f13aaa79aa66324dcc65330bb7f0942802859" alt="Image" width="16%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//7aaf7c1b-8da3-4bab-a537-7a3e0986078d/markdown_1/imgs/img_in_image_box_857_371_1050_619.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2Fa90e1e83ab010872bd2241fc342f13aaa79aa66324dcc65330bb7f0942802859" alt="Image" width="16%" />

 $ dv(a>0) $
 $ r=2a\cos\theta $

</div>


</div>


#### 元积分 - A

1. (1945.3)  $  f(x) = \int_{0}^{\frac{2\pi}{n-4}} dt  $，计算  $  J_0 f(x) dx  $

解：① 显然为二重积分  $  \int_{0}^{\pi} \frac{\sin t}{t} dx = \int_{0}^{\pi} \int_{t}^{+\infty} dx = \int_{0}^{\pi} \sin t dt = 2  $

② 分部： $  I = x f(x) \int_{0}^{\pi} - \int_{0}^{\pi} x \frac{\sin x}{\pi - x} dx = \pi \int_{0}^{\pi} \frac{\sin x}{\pi - x} dx - \int_{0}^{\pi} \frac{x \sin x}{\pi - x} dx = \int_{0}^{\pi} \sin x dx = 2  $

③ 凑  $  O: I = \int_{0}^{\pi} f(x) dx - \pi = (x - \pi) f(x) \int_{0}^{\pi} - \int_{0}^{\pi} (x - \pi) \frac{\sin x}{\pi - x} dx = 0 + \int_{0}^{\pi} \sin x dx = 2  $

该思想分常用！

2. (1)  $  \int_{1}^{+\infty} dx  $

(2)  $  \int_{\frac{\pi}{4}}^{\frac{\pi}{2}} dx  $

(3)  $  \int_{\frac{\pi}{4}}^{\frac{\pi}{2}} dx  $

注： $  \int_{0}^{+\infty} \frac{x^2}{1 + x^2} dx = \int_{0}^{+\infty} \frac{dx}{1 + x^2} = \frac{\sqrt{2}}{4} \pi  $

解：(1) 注意到  $  I = \frac{1}{2} \left( \int_{\frac{1}{4} \pi^2} \frac{x^2 + 1}{1 + x^2} dx - \int_{\frac{1}{4} \pi^2} \frac{x^2 + 1}{1 + x^2} dx \right) = \frac{1}{2} \left( \int_{0}^{1} \frac{x^2 + 1}{1 + x^2} dx - \int_{1}^{1} \frac{x^2 + 1}{1 + x^2} dx \right) = \frac{\sqrt{2}}{4} \arctan \frac{x - \frac{1}{2}}{\sqrt{2}} - \frac{\sqrt{2}}{8} \ln \left| \frac{x + \frac{1}{2} - \sqrt{2}}{x + \frac{1}{2} + \sqrt{2}} \right| + C  $

背下来。类似还有  $  \int \frac{e^{x}}{e^{x} + e^x} dx = \int \frac{e^x + e^{-x}}{e^x + e^{-x} + 1} = \frac{1}{2^2} \arctan \frac{e^x - e^{-x}}{\sqrt{3}} + C  $

(2)  $  I \xlongequal{x \geq \sin t} \int \frac{\cos^2 t}{\sin^2 t} dt  $，因为  $  \int_{\sin^2 t} t  $ 不易积，考虑  $  \int \frac{1}{\sin^2 t + \tan t} dt  $，由  $  d \frac{1}{t} \tan t = -\frac{1}{2} \sin^2 t  $，则  $  I = \int_{\tan t} \frac{1}{t} d \tan t = -\frac{1}{2} \left( \frac{1}{\tan t} \right)^3 = -\frac{(4-x)^2}{12} + C  $

(3) 因为对数单身狗，故  $  R  $ 能留  $  \ln x  $ 单独导，即  $  \int_{\sqrt{1 + x^2}} \frac{1}{\sqrt{1 + x^2}} dx  $ 就得积，由  $  \int_{\sqrt{1 + x^2}} \frac{dx}{1 + x^2} = \sin t C = \frac{x}{\sqrt{1 + x^2}} + C  $，则  $  I = \frac{x}{\sqrt{1 + x^2}} \ln x - \int_{\sqrt{1 + x^2}} \frac{x}{\sqrt{1 + x^2}} = \frac{x \ln x}{\sqrt{1 + x^2}} - \ln (x + \sqrt{x^2}) + C  $

类似地， $  \int \frac{\ln (x + \sqrt{x^2})}{(1 + x^2)^2} dx = \int \ln (x + \sqrt{x^2}) d \frac{x}{\sqrt{1 + x^2}} = \frac{x \ln (x + \sqrt{x^2})}{\sqrt{1 + x^2}} - \frac{x \ln (x + \sqrt{x^2})}{\sqrt{1 + x^2}} = \frac{x \ln x}{\sqrt{1 + x^2}} + C  $

3. (1)  $  \int \frac{(1 + \cos x)e^x}{1 + \cos x} dx  $

(2)  $  \int \frac{dx}{1 + \cos x}  $

(3)  $  \int \frac{dx}{1 + \sin x + \cos x}  $

(4)  $  \int \frac{dx}{1 + 2 \tan x}  $

解：(1)  $  I = \int \frac{(1 + 2 \sin \frac{x}{2} \cos \frac{x}{2}) e^x}{2 \cos^2 \frac{x}{2}} = \int (\tan \frac{x}{2} + \frac{1}{2} \cos \frac{x}{2}) e^x dx = \int e^x \tan \frac{x}{2} dx + \int e^x \tan \frac{x}{2} = e^x \tan \frac{x}{2} + C  $

(2)  $  I = \int \frac{dx}{\cos^2 x + \tan x} = \int \frac{d \tan x}{2 + \tan^2 x} = \frac{1}{2} \arctan \frac{\tan x}{2} + C  $

补： $  \int \frac{dx}{1 + \cos x} = \int \frac{dx}{2 \cos^2 \frac{x}{2}} = \tan \frac{x}{2} + C  $

(3) ①  $  I = \int \frac{-\sin x - \cos x}{2 \sin x \cos x} dx = \frac{1}{2} \int \frac{\cos x}{2} dx + \frac{1}{\sin x} - \frac{1}{\sin x \cos x} dx = \frac{1}{2} \ln | \sec x + \tan x | + \frac{1}{2} \ln | \csc x - \cot x | - \frac{1}{2} \ln | \csc 2x - \cot 2x | + C  $

②  $  I = \int \frac{dx}{1 + \cos x + \sin x} = \int \frac{\cos x}{2 \cos^2 x + 2 \sin^2 x} dx = \int \frac{d(\tan x)}{1 + \tan^2 x} = \ln | 1 + \tan x | + C  $ (与(1)方法一致，见HCOX立即推  $  2 \cos^2 \frac{x}{2}  $)

(4)  $  I = \int \frac{\cos x}{2 \sin x + \cos x} dx = \int \frac{1}{2} (\sin x + \cos x) + \frac{1}{2} (\cos x - \sin x) dx = \frac{x}{2} + \frac{1}{2} \ln | 2 \sin x + \cos x | + C  $

②  $  I = \int_{\frac{1}{4} \pi^2}^{\frac{\pi}{4}} \frac{dx}{1 + \cos x + \sin x} = \frac{1}{2} \ln | 2 \sin x - \sin x | - \frac{1}{2} \ln | 1 + 2 \sin x - \cos x | + \frac{1}{2} \arctan x + C = \uparrow  $

(2) 解  $  I = \int_{0}^{\frac{x}{2}} \frac{1}{1 + \cos x} dx + \int_{1}^{2} \frac{\sin x}{1 + \cos x} dx = \int_{0}^{\frac{x}{2}} \frac{e^x}{1 + \cos x} + \frac{e^x \sin x}{1 + \cos x} - \int_{0}^{\frac{x}{2}} \frac{e^x \sin x}{(1 + \cos x)^2} dx = \frac{e^x \sin x}{1 + \cos x} + C  $

4. (1)  $  \int_{0}^{\frac{1}{2}} \ln \frac{1}{\tan^2 x} dx  $

(2)  $  \int_{0}^{\frac{\pi}{2}} \ln (\sin x) dx  $

(3)  $  \int_{0}^{\frac{\pi}{4}} \ln (1 + \tan x) dx  $

(4)  $  \int_{0}^{\frac{\pi}{4}} \ln (\tan x) dx = \int_{0}^{\frac{\pi}{4}} \frac{1}{1 + \tan x} dx = \int_{0}^{\frac{\pi}{4}} \frac{1}{1 + \cos x} dx = \int_{0}^{\frac{\pi}{4}} \frac{1}{1 + \cos x} dx = \frac{1}{2} \int_{0}^{\frac{\pi}{4}} \frac{1}{1 + \cos x} dx = \frac{1}{2} \int_{0}^{\frac{\pi}{4}} \frac{1}{1 + \cos x} dx = \frac{1}{2} \int_{0}^{\frac{\pi}{4}} \frac{1}{1 + \cos x} dx = \frac{1}{2} \int_{0}^{\frac{\pi}{4}} \ln (\cos x) dx = \frac{1}{2} \int_{0}^{\frac{\pi}{4}} \ln (\sin x) dx = \frac{1}{2} \int_{0}^{\frac{\pi}{4}} \ln 2 - \ln 2 = -\frac{\pi}{4} \ln 2 + \frac{1}{4} \int_{0}^{\pi} \ln \sin x dx  $

 $  = \int_{0}^{\pi} \ln (\cos x) dx = \int_{0}^{\pi} \ln 2 + \frac{1}{2} \ln 2 + \frac{1}{2} \ln 2  $

(3)  $  I = \frac{1}{2} \int_{0}^{\pi} \left[ \ln (1 + \tan x) + \ln (1 + \tan(\frac{\pi}{4} - x)) \right] dx = \frac{\pi}{8} \ln 2  $

(4)  $  I = \frac{1}{2} \tan x - \int_{0}^{\pi} \ln (1 + \tan x) dx = \frac{\ln 2}{8} \ln 2  $

 $$ 5.\int\frac{d x}{1+x^{6}} $$ 

解：组合积分法令  $ I_{1}=\int\frac{dx}{1+x^{2}} $， $ I_{2}=\int\frac{x^{4}}{1+x^{6}} $， $ I_{2}-I_{1}=\int\frac{x^{4}}{1+x^{6}}dx=\int\frac{(x^{2}+1)(x^{2}-1)dx}{(x^{2}+1)(x^{2}-x^{2}+1)}=\int\frac{x^{2}-1}{x^{2}-x^{2}+1}dx=\int\frac{dx(x+\frac{1}{2})}{(x+1)^{2}-3} $

 $ =\frac{1}{2\sqrt{3}}|n|\frac{x+\frac{1}{2}-\sqrt{3}}{x+1+\sqrt{3}}|+C $， $ I_{1}+I_{2}=\int\frac{x^{4}-x^{2}+1+x^{2}}{(x^{2}+1)(x^{2}-x^{2}+1)}dx=\int\frac{1}{1+x^{2}}dx+\int\frac{x^{2}}{1+x^{2}}dx=\arctan x+\frac{1}{3}\arctan x^{3}+C $，相减得

 $ I_{1}=\frac{1}{2}\arctan x+\frac{1}{6}\arctan x^{3}-\frac{4\sqrt{3}}{4}\ln\left|\frac{x+\frac{1}{2}-\sqrt{3}}{x+\frac{1}{2}+\sqrt{3}}\right|+C $

配凑  $ I=\frac{1}{3}\int\frac{1}{1+x^{2}}-\frac{x^{2}-2}{x^{2}+x^{4}}dx=\frac{1}{3}\int\frac{1}{1+x^{2}}dx+\frac{1}{6}\int\frac{x^{2}+1}{x^{2}+x^{4}}dx-\frac{1}{2}\int\frac{x^{2}-1}{x^{2}-x^{4}}dx=\frac{1}{3}\arctan x+\frac{1}{6}\arctan(x-x)-\frac{1}{4\sqrt{3}}\ln\left|\frac{x+\frac{1}{2}-\sqrt{3}}{x+\frac{1}{2}+\sqrt{3}}\right|+C $

配凑  $ I=\frac{1}{2}\int\frac{(1+x^{4}-x^{2})+x^{2}+(1-x^{4})}{(1+x^{2})(1+x^{4}-x^{2})}dx=\frac{1}{2}\int\frac{dx}{1+x^{2}}+\frac{1}{2}\int\frac{x^{2}}{1+x^{4}}dx+\frac{1}{2}\int\frac{1-x^{2}}{1+x^{4}-x^{2}}dx $

注：①拆项时可视为 $ 1^{3}+(x^{2})^{3}=(16x^{2})(1-x^{2}+x^{4}) $ ②配凑还可以 $ \int\frac{1+x^{2}-x^{2}}{1+x^{4}}dx=\int\frac{1}{1-x^{2}+x^{4}}dx-\int\frac{x^{2}}{1+x^{4}}dx $，再将 $ \int\frac{1}{1+x^{2}+x^{4}} $拆成 $ \frac{1}{2}\int\frac{1-x^{2}+1+x^{2}}{1-x^{2}+x^{4}} $ ③对于 $ \int\frac{1+x^{2}}{1+x^{4}+x^{4}}dx $，先同除 $ x^{2} $，再换元 $ t=x\pm\frac{1}{2} $（分子奇数次幂时凑微分）

④  $ \int\frac{1}{1+x^{2}}dx=\frac{1}{3}\int\frac{1}{1+x}dx-\frac{1}{3}\int\frac{x-2}{x^{2}-x+1}dx=\frac{1}{3}\ln|1+x|-\frac{1}{6}\ln\left(x^{2}-x+1\right)+\frac{\sqrt{3}}{3}\arctan\left[\frac{x-1}{2\sqrt{3}}\right]+C $

⑤ 对于  $ \int\frac{dx}{1+e^{x}} $ dx，(i) 尝试同乘  $ e^{-x}(e^{x}) $ 使分子变为  $ e^{-x}(e^{x}) $，分母变为  $ e^{-x}+c(e^{x}+c) $。如  $ \int\frac{dx}{1+e^{2x}}=\int\frac{e^{-2x}dx}{1+e^{-2x}} $

 $ =-\frac{1}{2}\ln(1+e^{-x})+C $ 或  $ =\int\frac{e^{2x}}{e^{x}(1+e^{x})} $ dx  $ \xrightarrow{拆项}\frac{2}{2}\ln\frac{e^{2x}}{1+e^{2x}}+C $

6.(1) $ \lim_{n\to\infty}n\int_{0}^{1}x^{n}\sqrt{1+x^{2}}dx $ (2)说明下述做法的错误: $ \lim_{n\to\infty}\int_{0}^{1}x^{n}\sqrt{1+x^{2}}dx=\lim_{n\to\infty}\xi^{n}\sqrt{1+\xi^{2}} $ (0<x<1)=0.有界量=0

解集由  $ \int_{0}^{x^{n}}\sqrt{1+x^{2}}dx=\int_{0}^{1}\sqrt{x^{2n}+x^{2n+1}}dx $ 则  $ n\int_{0}^{1}\sqrt{x^{2n+1}+x^{2n+2}}dx<n\int_{0}^{1}x^{n}\sqrt{1+x^{2}}dx<n\int_{0}^{1}\sqrt{x^{2n}+x^{2n}}dx $ 即  $ \sqrt{2n}\int_{0}^{1}x^{n+1}dx<I<\sqrt{2n}\int_{0}^{1}x^{n}dx\xrightarrow{夹逼}I=\sqrt{2} $

(2)  $ 0 < \xi_{n} < 1 $ 时， $ (\xi_{n})^{n} $ 不一定  $ \rightarrow 0 $ （ $ x_{n} = \frac{n}{n+1} $），事实上，一般情况下不能假设  $ \xi_{n} \rightarrow 0 $ 或  $ \rightarrow 1 $

本题应该 $ ^{①}0\leq I<\sqrt{2}\int_{0}^{1}x^{2}dx=0 $ ② $ I=\sqrt{1+\frac{1}{2n}}\int_{0}^{1}x^{2}dx= $ 有界量0=0

7.(点火失灵) $ \int_{0}^{\frac{\pi}{4}}\sin^{4}x dx $

解：①考虑补充区间由 $ \left(\int_{0}^{\frac{\pi}{4}}+\frac{\pi}{4^{2}}\right)\sin^{4}x dx=\frac{3}{16}\pi $，即 $ \int_{0}^{\frac{\pi}{4}}\sin^{4}x dx+\int_{0}^{\frac{\pi}{4}}\cos^{4}x dx=\frac{3}{16}\pi $，显然要考虑工-丁

 $ \int_{0}^{\frac{\pi}{4}}\sin^{4}x-\cos^{4}x dx=\int_{0}^{\frac{\pi}{4}}(\sin^{2}x+\cos^{2}x)(\sin^{2}x-\cos^{2}x)dx=-\int_{0}^{\frac{\pi}{4}}\cos2x dx=-\frac{1}{2} $，故  $ I=\frac{1}{2}\left(\frac{3}{16}\pi-\frac{1}{2}\right) $ 组合积分

②降幂 欧拉公式  $ \cos nx = \frac{1}{2}(a^{n} + \frac{1}{a^{n}}) \sin nx = \frac{1}{2i}(a^{n} - \frac{1}{a^{n}}) $，其中  $ a = e^{2x} $

因此  $ \cos^{4}x = \left[\frac{1}{2}(a + \frac{1}{a})\right]^{4} = \frac{1}{16}(a^{4} + 4a^{2} + 6 + \frac{4}{a^{2}} + \frac{1}{a^{4}}) = \frac{1}{8}(\cos^{4}x + 4\cos^{2}x + 3) $

 $ \sin^{4}x = \left[\frac{1}{2i}(a - \frac{1}{a})\right]^{4} = \frac{1}{16}(a^{4} - 4a^{2} + 6 - \frac{4}{a^{2}} + \frac{1}{a^{4}}) = \frac{1}{8}(\cos^{4}x - 4\cos^{2}x + 3) $

这为组合积分提供了思路

8.  $ \int \frac{x \cos^{4} \frac{x}{2}}{\sin^{2} x} dx $

 $$ I=\frac{1}{8}\int\frac{x\cos\frac{x}{2}}{\sin\frac{1}{2}}d x=-\frac{1}{8}x\cdot\frac{1}{\sin^{2}\frac{x}{2}}+\int\frac{d x}{\sin^{2}\frac{x}{2}}=-\frac{1}{8}\frac{x}{\sin^{2}\frac{x}{2}}-\frac{1}{4}\cot\frac{x}{2}+C $$ 

9.  $ \int_{0}^{1}\frac{x^{6}-x^{4}}{\ln x}dx(a,b>0) $

解  $ I=\int_{0}^{1}dx\int_{a}^{b}x^{y}dy=\int_{a}^{b}dx\int_{0}^{1}x^{y}dy=\int_{a}^{b}\frac{1}{y+1}dy=\ln\frac{b+1}{a+1} $

 $ f^{\prime}>0, f^{\prime}<0 $. 证明： $ I_{1}=\int_{-\pi}^{\pi}f(x)\sin x dx>0, I_{2}=\int_{-\pi}^{\pi}f(x)\cos x dx $

证： $ x\in(0,\pi) $时 $ f(x)>f(-x) $， $ I_{1}=\int_{0}^{\pi}[f(x)-f(-x)]\sin x dx>0 $， $ I_{2}=f(x)\sin x\Big|_{-\pi}^{\pi}-\int_{-\pi}^{\pi}f(x)\sin x dx=-\int_{0}^{\pi}[f(x)-f(-x)]\sin x dx>0 $

1.  $ \int_{0}^{2\pi}\sqrt{2-2\sin t}\,dt $

解： $ I=\sqrt{2}\int_{0}^{2\pi}\left|\sin\frac{t}{2}-\cos\frac{t}{2}\right|dt=2\sqrt{2}\left(\int_{0}^{\frac{\pi}{4}}\cos t-\sin t dt+\int_{\frac{\pi}{4}}^{\pi}\sin t-c\cos t dt\right)=2\sqrt{2}(\sqrt{2}-1+\sqrt{2}+1)=8 $

# 积分应用

1.(2011=)一容器内侧由曲线绕y轴旋转一周.(1)求容积(2)盛满水从顶部抽出所做功 $ (p=10^{3}kg/m^{3}) $ 解：(1) $ V=2\int_{-1}^{\frac{1}{2}}\pi x^{2}dy=2\pi\int_{-1}^{\frac{1}{2}}(1-y)^{2}dy=\frac{9\pi}{4} $ (2) $ W=10^{3}g\left[\int_{-1}^{\frac{1}{2}}\pi(1-y^{2})(2-y)dy+\int_{\frac{1}{2}}^{2}\pi(2y-y^{2})(2-y)dy\right]=\frac{27}{8}\times10^{3}\pi g(5) $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_0/imgs/img_in_image_box_940_154_1062_280.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2F49f8344fb0c611b8fffc3a21bc291bb6e4e5400ca482ae50b02c110fc07aef1b" alt="Image" width="10%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_0/imgs/img_in_image_box_940_154_1062_280.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2F49f8344fb0c611b8fffc3a21bc291bb6e4e5400ca482ae50b02c110fc07aef1b" alt="Image" width="10%" />

 $ x^{2} + y^{2} = 2y $

 $ x^{2} + y^{2} = 1 $

</div>


</div>


2. 由  $ x^{2}+y^{2}=\frac{a^{2}}{2} $ 外  $ (x^{2}+y)^{2}=a^{2}(x^{2}-y^{2}) $ 内所围成的区域的面积.

解：由  $ \frac{a^{2}}{2} $ 与  $ r^{2}=a^{2}\cos2\theta $ 得  $ \theta=\frac{\pi}{6} $，则  $ S=4\int_{0}^{\frac{\pi}{6}}d\theta\int_{\frac{\pi}{2}}^{\frac{a\sqrt{2}\cos2\theta}}{\gamma}rdr=2\int_{0}^{\frac{\pi}{6}}a^{2}(\cos2\theta-\frac{1}{2})d\theta=(\frac{\sqrt{3}}{2}-\frac{\pi}{6})a^{2} $

3. 设  $ y = f(x) $ 非负连续 ( $ 0 \leq x \leq 1 $) (1) 证明:  $ \exists C \in (0,1) $ 使  $ [0, c] $ 上以  $ f(c) $ 为高的矩形面积等于  $ [c, 1] $ 上以  $ x = f(x) $ 为曲边的曲边梯形的面积 (2) 设  $ f(x) \in D(0,1) $ 且  $ f'(x) > -\frac{2f(x)}{x} $，证明 (1) 中的 C 是唯一的.

解(1) 即证  $ C f(x) = \int_{0}^{x} f(t) dt $，相当于  $ \varphi(x) = x f(x) - \int_{0}^{x} f(t) dt = 0 $，考虑题中 C 为开闭间，需用罗尔定理，令  $ F(x) = x \int_{0}^{x} f(t) dt $ 得  $ F(0) = F(1) = 0 \Rightarrow F'(0) = 0 $ (2)  $ \varphi'(x) = x f'(x) + 2 f(x) > 0 $

4.  $ \iint_{D}(x+|y|)dxdy $，D由星形线 $ x^{\frac{2}{3}}+y^{\frac{2}{3}}=a^{\frac{2}{3}} $围成

解： $ I=4\iint_{D}ydxdy=4\int_{0}^{a}dx\int_{0}^{y(x)}ydy=2\int_{0}^{a}y(x)dx $，令 $ \left\{\begin{array}{l}x=a\cos^{3}t\\y=a\sin^{3}t\end{array}\right. $， $ I=6a^{3}\int_{0}^{\frac{\pi}{2}}\sin^{2}t\cos^{2}dt=\frac{32a^{3}}{105} $

5.  $ \iint_{D}x^{2}d\sigma $，D由 $ r=2(1+\cos\theta) $ ( $ 0\leq\theta\leq\pi $)与极轴围成

解:  $ I=\int_{0}^{\pi}d\theta\int_{0}^{2(1+\cos\theta)}r^{3}\cos^{2}\theta dr=4\int_{0}^{\pi}\cos^{2}\theta(1+\cos\theta)^{4}d\theta\stackrel{t=\theta=\frac{\pi}{2}}{=}4\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\sin^{2}t(1-\sin t)^{4}dt=8\int_{0}^{\frac{\pi}{2}}\sin^{2}t+6\sin^{4}t+\sin^{6}dt=\frac{49\pi}{4} $

6.  $ P_{水}=1 $.  $ R_{球}=1 $,  $ P_{球}=0.1 $ 求球在水中的深度  $ h $ (2) 对球施压，把一半压入水中，求克服浮力所做功  $ W $

解: (1)  $ V = \pi r_{0}^{h} d x = \pi \int_{0}^{h} [1 - (x - y)^{2}] dx = \pi (h^{2} - \frac{1}{3} h^{3}) = 0.1 \times \frac{4}{3} \pi $, 故  $ 5h^{3} - 15h^{2} + 2 = 0 $

(2)  $ W = \pi g \int_{h}^{1} x^{2} - \frac{1}{3} x^{3} dx = \pi g \left( \frac{1}{4} - \frac{1}{3} h^{3} + \frac{1}{12} h^{4} \right) $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_0/imgs/img_in_image_box_929_981_1063_1076.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2Fd6173b6b4b338a08d4af38cb8ca8e8210cd3970c3d25ff2b1a2b36e83191afc1" alt="Image" width="11%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_0/imgs/img_in_image_box_929_981_1063_1076.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2Fd6173b6b4b338a08d4af38cb8ca8e8210cd3970c3d25ff2b1a2b36e83191afc1" alt="Image" width="11%" />

 $ 1.0h $

</div>


</div>


7. 均匀棒在X轴 $ [a,b] $上且 $ P=1 $，质点在Y轴 $ (0,h) $处且m、求棒对点的引力

解:  $ dF = k \frac{m}{h^2 + x^2} \quad dF_x = dF \cdot \cos\alpha = k \frac{m}{h^2 + x^2} \cdot \frac{x}{\sqrt{h^2 + x^2}} dx $,  $ F_x = \int_a^b \frac{kmx}{(h^2 + x^2)^2} dx = km (\sqrt{\frac{1}{a^2 + h^2}} - \sqrt{\frac{1}{b^2 + h^2}}) $

同理  $ F_y = \int_a^b \frac{-km}{h^2 + x^2} \cdot \frac{h}{\sqrt{h^2 + x^2}} dx = -\frac{km}{h} (\sqrt{\frac{b}{b^2 + h^2}} - \sqrt{\frac{a}{a^2 + h^2}}) $  $ \overrightarrow{F} = F_x \overrightarrow{z} + F_y \overrightarrow{z} $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_0/imgs/img_in_image_box_895_1138_1070_1253.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2Fd0e10d1fe4975e38349dc066eff77fd700ecbc89b4c2b97ca206edab728fb8be" alt="Image" width="14%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_0/imgs/img_in_image_box_895_1138_1070_1253.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A52Z%2F-1%2F%2Fd0e10d1fe4975e38349dc066eff77fd700ecbc89b4c2b97ca206edab728fb8be" alt="Image" width="14%" />

 $ \overrightarrow{dF_{x}} $
 $ \overrightarrow{dF_{y}} $

</div>


</div>


8.  $ \left\{\begin{array}{l} x=\cos^{2}t \\ y=\sin^{3}t \end{array}\right. $ 所圆平面绕  $ y=1 $ 旋转所得  $ V_{旋转体}= $

 $$ I=2\cdot2\pi\iint\limits_{D}[1-y]dy(取点(侧))=4\pi\int_{-1}^{1}1-y dy\int_{0}^{x(y)}dx=4\pi\int_{-1}^{1}(1-\sin^{3}t)\cos^{3}(3\sin^{2}t\cos t)dt=\frac{3}{4}\pi^{2} $$ 

9. 均匀  $ z=\sqrt{x^{2}-y^{2}}, x^{2}y^{2}=1, z=h(h>1) $ 围成，求 n 对原点处单位质点的引力

解: 由  $ F = G \frac{Mm}{\gamma^{2}} k_{0} dF = G \frac{m \rho dv}{\gamma^{2}} $ 而  $ \overrightarrow{n} = \frac{1}{\gamma}(x - x_{0}, y - y_{0}, z - z_{0}) $ 和  $ dF_{x} = G \frac{m \rho (x - x_{0})}{\gamma^{3}} dv $ (投影),  $ F_{x} = G m \iint_{D} \frac{\rho (x - x_{0})}{\gamma^{3}} dv $.

 $$ F_{2}=\iint\limits_{(x^{2}+y^{2}+z^{2})}^{}\frac{G z}{2}d v=\iint\limits_{(x^{2}+y^{2}+z^{2})}^{}d x d y\int\limits_{(x^{2}+y^{2}+z^{2})}^{h}\frac{G z d z}{(x^{2}+y^{2}+z^{2})}^{2}=\int\limits_{0}^{2\pi}d r\int\limits_{0}^{1}d r\int\limits_{r}^{h}\frac{G z r}{(r^{2}+z^{2})}\frac{1}{2}d z=2\pi G(\frac{1}{\sqrt{2}}+h-\sqrt{h^{2}+1}) $$ 

故  $ \overrightarrow{F} = (0, 0, 2\pi G(\frac{1}{\sqrt{2}} + h - \sqrt{h+1})) $

10. 求  $ \sqrt{x} + \sqrt{y} = 2 $ 的弧长 S

 $$ \{x(\theta)=4\cos^{4}\theta,y(\theta)=4\sin^{4}\theta,S=\int_{0}^{\frac{\pi}{2}}\sqrt{x^{2}+y^{2}}d\theta=16\int_{0}^{\frac{\pi}{2}}\sin\theta\cos\theta\sqrt{\cos^{4}\theta+\sin^{4}\theta}d\theta=8\int_{0}^{\frac{\pi}{2}}\sin2\theta\sqrt{1-\frac{1}{2}\sin^{2}2\theta}d\theta\xlongequal{t=\cos2\theta}2\sqrt{2}\int_{1}^{1}\sqrt{1+t^{2}}dt=4+2\sqrt{2}\ln(\sqrt{2}+1) $$ 

##### 多元微分

## 一、多元函数

1. 伞域  $ U(P_{0}, \delta) = \{P \mid |P P_{0}| < \delta\} $  $ \left\{(x, y) \mid \sqrt{(x-x_{0})^{2} + (y-y_{0})^{2}} < \delta\right\} $  $ \dot{U}(P_{0}, \delta) = \{P \mid 0 < |P P_{0}| < \delta\} $

2. 极限  $ \forall \varepsilon > 0, \exists \delta > 0 $ ，在  $ \mathring{U}(P_{0}, \delta) $ 内  $ \left|f(x, y) - A\right| < \varepsilon $ ，记作  $ \lim_{x \to y_{0}} f(x, y) = A \Leftrightarrow f(x, y) = A + a, \lim_{x \to y_{0}} d = 0 $

3. 连续  $ \lim_{{x \to y_0}} f(x, y) = f(x_0, y_0) $

4. 偏导数  $ \int_{x}^{1}(x_{0}, y_{0}) = \lim_{\Delta x \to 0} \frac{f(x_{0} + \Delta x, y_{0}) - f(x_{0}, y_{0})}{\Delta x} = \begin{cases} f_{x}^{\prime}(x, y_{0}) \mid_{x=x_{0}} \text{ 先求导再求导} \\ f_{x}^{\prime}(x, y) \mid_{x=y_{0}} \text{ 先求导再代值} \end{cases} $ 是  $ \left\{\begin{array}{l} z = f(x, y) \\ y = y_{0} \end{array}\right. $ 在  $ (x_{0}, y_{0}, z_{0}) $ 处的切线对 x 轴的斜率

5. 可微  $ \Delta\Sigma = f(x + \Delta x, y + \Delta y) - f(x, y) = A\Delta x + B\Delta y + O(p) $ 如  $ f(x, y) = f(0, 0) + (x - 0)f_{x}^{\prime} + (y - 0)f_{y}^{\prime} + O(\sqrt{x + y^{2}}) $

判别： $ \lim_{\Delta x \to 0} \frac{\Delta z - (\Delta z)}{\rho} = \lim_{\Delta y \to 0} \frac{f(x + \Delta x, y + \Delta y) - f(x, y) - \Delta z f'(x) \Delta x - f'(y)}{\sqrt{(\Delta x)^2 + (\Delta y)^2}} = 0 \Leftrightarrow (x_0, y_0) $处可微

6. 结论

 $ (1\lim_{(x,y)\to(0,0)}\frac{f(x,y)-\frac{f(0,0)}{\sqrt{x^{2}+y^{2}}}}=0 $ 是七在 $ (0,0) $可微的充分非必要条件)

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_2/imgs/img_in_image_box_164_548_392_669.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A54Z%2F-1%2F%2F8ae2b3a198253dee96299addcd23c8833e5666cb2afc49f185b7aa2719727a48" alt="Image" width="19%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_2/imgs/img_in_image_box_164_548_392_669.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A54Z%2F-1%2F%2F8ae2b3a198253dee96299addcd23c8833e5666cb2afc49f185b7aa2719727a48" alt="Image" width="19%" />

① 连续

可微  $ \uparrow $ 极限存在

可导  $ \rightarrow $ 一元

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_2/imgs/img_in_image_box_468_563_861_684.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A54Z%2F-1%2F%2Fae6ff5344b83078e23c2b5f1d4ef43035628225879a58c6575b5bc733297f7af" alt="Image" width="33%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_2/imgs/img_in_image_box_468_563_861_684.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A54Z%2F-1%2F%2Fae6ff5344b83078e23c2b5f1d4ef43035628225879a58c6575b5bc733297f7af" alt="Image" width="33%" />

偏导数连续  $ \rightarrow $ 可微  $ \rightarrow $ 连续  $ \rightarrow $ 极限存在  
偏导数存在 可偏导没有用 多元

</div>


</div>


②  $ \frac{\partial^{2}z}{\partial x\partial y} $ 与  $ \frac{\partial^{2}z}{\partial y\partial x} $ 连续  $ \Rightarrow \frac{\partial^{2}z}{\partial x\partial y} = \frac{\partial^{2}z}{\partial y\partial x} $

## 二、极值与最值

1.  $ f(x,y) $ 在  $ (x_{0},y_{0}) $ 取得极值  $ \Rightarrow f(x,y_{0}), f(x_{0},y) $ 分别在  $ x_{0},y_{0} $ 处取得极值 反例： $ f=x^{4}+y^{4}-(x+y)^{2} $ 在  $ (0,0) $ 处为整点

推论： $ t $ 有二阶连续偏导且在  $ (x_{0},y_{0}) $ 处取得极大值  $ \Rightarrow A=\frac{\partial^{2}f}{\partial x^{2}}\vert_{(x_{0},y_{0})}\leq0 $,  $ B=\frac{\partial^{2}f}{\partial y^{2}}\vert_{(x_{0},y_{0})} $

2. 无条件极值  $ \overrightarrow{grad f} = \overrightarrow{0} $

必要： $ f_{x}^{\prime}(x_{0},y_{0})=0 $ 且  $ f_{y}^{\prime}(x_{0},y_{0})=0 $ 或偏导不存在的点

充分:  $ \Delta=\left|\begin{matrix}A&B\\BC\end{matrix}\right| $. ①  $ \Delta>0 $  $ \left\{\begin{array}{l}A<0: 极大值\\A<0: 极小值\end{array}\right. $ ②  $ \Delta=0 $: 未知 ③  $ \Delta<0 $: 非极值

3. 有条件极值

边界约束：①将约束代入f ②拉格朗日乘数 不封闭曲线使用②时要比较端点处的f

闭区域约束：(1) 找D内的可疑点 (2) D上用边界约束

结论 $ ^{①} $光滑闭曲线L外一个点Q： $ P_{1}Q\perp P_{1} $的切线

②光滑闭曲线 $ L_{1,2} $不相交： $ P_{1}P_{2} $为 $ L_{1,2} $的公切线

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_2/imgs/img_in_image_box_617_1225_918_1368.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A54Z%2F-1%2F%2F87eea9ede1a97700c70b18e6e0a8779a7e14f6ef4203dcfee9b0f76bf6e88dae" alt="Image" width="25%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_2/imgs/img_in_image_box_617_1225_918_1368.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A54Z%2F-1%2F%2F87eea9ede1a97700c70b18e6e0a8779a7e14f6ef4203dcfee9b0f76bf6e88dae" alt="Image" width="25%" />

P_{1}(最远点) P_{2}(最远/近点)

① Q

</div>


</div>


## 三、其他

1. 为什么  $ F_{x}^{\prime} $ 与  $ \frac{2F}{x} $ 不同？如  $ z = z(x,y) $:  $ e^{x + 2 + 4 + 3z} + xy = z = 1 $，有  $ \frac{\partial F}{\partial x} = F_{x}^{\prime} \cdot 1 + F_{z}^{\prime} \cdot \frac{\partial z}{\partial x} = 0 $，而  $ F_{x}^{\prime} = e^{x + 2 + 4 + 3z} + y z $.

注意：这里  $ F_{x}^{\prime} $ 的 x 其实表示为第 1 个位置，此时 x, y, z 是独立的.

而  $ \frac{\partial F}{\partial x} $ 由  $ F_{z}^{\prime} $ 与链式法则，故为  $ \frac{\partial F}{\partial x} = F_{1}^{\prime} \cdot 1 + F_{3}^{\prime} \cdot \frac{\partial z}{\partial x} $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_3/imgs/img_in_image_box_808_339_1013_439.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A55Z%2F-1%2F%2Fdccfcf710d3811982889f16e40ef10f21f86a7bae7d48088c3bd181d968ebc2a" alt="Image" width="17%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_3/imgs/img_in_image_box_808_339_1013_439.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A55Z%2F-1%2F%2Fdccfcf710d3811982889f16e40ef10f21f86a7bae7d48088c3bd181d968ebc2a" alt="Image" width="17%" />

F  $ \angle x $ y  $ \angle x $ y 位于这一层
F_{x}位于这一层

</div>


</div>


### 2. 拉格朗日定理

①  $ f(x,y) $ 在 D 上连续，D 内连续偏导，则  $ \forall P_{0}(x_{0},y_{0}), P_{1}(x_{1},y_{1}), \exists S=(x_{3},y_{3}) $ 在  $ P_{0}P_{1} $ 上，使  $ f(x_{1},y_{1}) - f(x_{0},y_{0}) = f_{x}^{\prime}(3)(x_{1} - x_{0}) $

② 若  $ \frac{2t}{3x}=0, \frac{2t}{3y}=C $，则  $ f(x,y)= $ 常数  $ (x,y)\in D $ 。证：D为连通集，则  $ \forall P_{0}, P_{1} $，必有连续折线将  $ P_{0}, P_{1} $ 连起来。对任意折线，有  $ f(x_{i},y_{i})-f(x_{0},y_{0})=f_{x}^{1}(S)(x_{i}-x_{0})+f_{y}^{1}(S)(y_{i}-y_{0})=0 $

③ 若  $ \frac{2t}{2x}=0 $  $ \Rightarrow f(x,y)=g(y) $ （即：与x无关）反例： $ f(x,y)=\left\{\begin{array}{l}y(x>0,y>0)\\0\quad 其他\end{array}\right. $， $ \overrightarrow{D}=\left\{(x,y)\mid x=0,y\geq0\right\} $  $ f(1,1)=0 $  $ f(1,1)=1 $ 显然  $ \frac{2t}{2x}=0 $ 但  $ \{f(-1,1)\neq f(1,1)\} $ 因为不满足  $ \forall(x,y),(x-y),x_{1}<x,x_{2} $ 均有  $ \left\{(x,y)\mid x_{1}<x<x_{2}\right\}\in D $ 故此时不能用拉中  $ f(x,y)-f(x,y)=f_{x}^{1}(3)(x_{2}-x_{1})=0 $ 比如  $ (0,1) $ 就不在D内

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_3/imgs/img_in_image_box_898_650_1039_738.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A55Z%2F-1%2F%2F9119fa70e4df1edbebe45e6469e0f03b905e19dd3b2789613af5e65dd3b11ab6" alt="Image" width="11%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//c8586a9e-f5f5-488d-8a81-683c7af53b5b/markdown_3/imgs/img_in_image_box_898_650_1039_738.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A55Z%2F-1%2F%2F9119fa70e4df1edbebe45e6469e0f03b905e19dd3b2789613af5e65dd3b11ab6" alt="Image" width="11%" />

 $ f(1,1)=0 $  $ f(1,1)=1 $

</div>


</div>


3. 求解拉格朗日乘数法的方程时，考虑：①  $ F_{x}^{1}-F_{y}^{1}=0 $ 得 x=y ②  $ \left\{\begin{array}{l}F_{x}^{1}=A\left[y\right]=0 \\ F_{y}^{1}=B\left[y\right]=0\end{array}\right. $ 和  $ \left|\frac{A}{B}\right|=0 $ (若有非零解)

辛普森定理：若约束和目标在某种对称性变换下保持不变，则极值点上解也在该变换下保持不变)

4. 若  $ f(0,y)=f(x,0)=0 $，则  $ f(x,y)=xyf_{xy}^{n}(x,y) $ 左边  $ =f(x,y)-f(0,y)=xf_{x}^{1}(x,y)=xf[f_{x}^{1}(x,y)-f_{x}^{1}(x,0)]=xyf_{xy}^{n}(x,y) $

 $$ 5.f^{\prime}_{x y}(0,0)=\lim\limits_{y\rightarrow0}t^{\prime}_{x}(0,y)-t^{\prime}_{x}(0,0) $$ 

# 多元微分

1. 在 $ (0,0) $处， $ f=|x|+|y| $连续但不可导， $ f=\frac{xy}{x+y^{2}} $可导但不连续， $ f=\frac{xy}{\sqrt{x+y^{2}}} $可导但不可微， $ f=(x^{2}+y^{2})\sin\frac{1}{x^{2}+y^{2}} $可微但偏导不连续

2. 试举反例 满足  $ \lim_{x\to0}[f_{x}^{\prime}(x,0)-f_{x}^{\prime}(0,0)]=0 $ 且  $ \lim_{y\to0}[f_{y}^{\prime}(0,y)-f_{y}^{\prime}(0,0)]=0 $ 但不可微

解：取  $ f=\left\{\begin{array}{l}x, x \neq 0 \\ 1, x \neq 0\end{array}\right. $ 则  $ f(x,0)=1 \Rightarrow f'(x,0)=0 $ 但  $ f $ 不连续  $ \Rightarrow $ 不可微 （因为得不到  $ \lim\limits_{x \to 0} \frac{f'(x,y)}{f_x}(x,y)=f_x'(0,0) $）

注： $ \lim\limits_{x\to x_{0}}\frac{\partial f(x,y)}{\partial x}=\frac{\partial f(x,y)}{\partial x} $ 才叫  $ f'(x,y) $ 在  $ (x_{0},y) $ 处连续 补： $ \lim\limits_{x\to x_{0}}\frac{f(x,y)-f(0,0)}{\sqrt{x^{2}+y^{2}}}=0 $ 是  $ f $ 在  $ (0,0) $ 处可微的充分条件

3设 $ f_{x}(x_{0},y_{0}) $存在， $ f_{y}(x,y) $在 $ (x_{0},y_{0}) $处连续，证明： $ f(x,y) $在 $ (x_{0},y_{0}) $处可微

解：要证  $ \Delta Z = f_{x}^{\prime}(x_{0}, y_{0}) \Delta x + f_{y}^{\prime}(x_{0}, y_{0}) \Delta y + O(P) $，由  $ \Delta Z = f(x_{0} + \Delta x, y_{0} + \Delta y) - f(x, y_{0}) = f(x_{0} + \Delta x, y_{0} + \Delta y) $

 $ -f(x_{0} + \Delta x, y_{0}) + f(x_{0} + \Delta x, y_{0}) - f(x_{0}, y_{0}) = f_{x}^{\prime}(x_{0} + \Delta x, y_{0} + \Delta y) \Delta y + f_{x}^{\prime}(x_{0}, y_{0}) \Delta x + \Delta x \Delta x = L \frac{f_{y}^{\prime}(x_{0}, y_{0}) + \Delta x \Delta x}{\sqrt{f_{x}^{\prime}(x_{0}, y_{0}) + \Delta x \Delta x}} \Delta x $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

 $ \Delta y = \Delta y \Delta y $

 $ \Delta x = \Delta x \Delta x $

4. 若  $ f(x,y) $ 可微，证明： $ \forall t>0 $ 有  $ f(tx,ty)=t^{n}f(x,y) $ （n 次充次函数）  $ \Leftrightarrow x\frac{\partial f}{\partial x}+y\frac{\partial f}{\partial y}=nf(x,y) $

解：必要：对七导： $ \left\{f_{1}^{1}(tx,ty)+y_{1}^{1}(tx,ty)=nt^{m}f(x,y)\right\} $， $ \Delta t=1 $ 得  $ xf_{1}^{1}+y_{1}^{1}=f $

充分：令  $ F=f(tx,ty) $， $ \frac{\partial F}{\partial t}=xf_{1}^{1}(tx,ty)+yf_{2}^{1}(tx,ty) $，则  $ t\frac{df}{dt}=x+f_{1}^{1}(tx,ty)+yf_{2}^{1}(tx,ty)=nf(tx,ty)=nf(t) $

故  $ F(t)=Ct^{n} $ 由  $ F(1)=C=f(x,y) $ 知  $ F(t)=t^{n}f(x,y) $  $ \frac{\partial\left(f(x,y)\right)}{\partial x}=tf_{1}^{1} $

5.  $ f(x,y)= $ 阶偏导连续且  $ f_{y}^{\prime}\neq0 $. 证明:  $ \forall C,f(x,y)=C $ 为一条直线  $ \Leftrightarrow f_{2}^{\prime2}f_{11}^{\prime\prime}-2f_{1}^{\prime}f_{2}^{\prime}f_{12}^{\prime\prime}+f_{1}^{\prime2}f_{22}^{\prime\prime}=0 $

解：由题可知  $ f(x,y)=C $ 可确定隐函数  $ y=y(x) $，故  $ f(x,y)=C $ 为直线  $ \Leftrightarrow y=y(x) $ 是线性函数  $ \Leftrightarrow y''=0 $

对  $ f(x,y)=C $ 导： $ f_{1}^{1}+f_{2}^{1}\frac{dy}{dx}=0\Rightarrow\frac{dy}{dx}=-\frac{d}{dx}\left(\frac{f_{1}^{1}}{f_{2}^{1}}\right)=-\frac{\left(f_{1}^{n}+f_{2}^{n}\frac{dy}{dx}\right)f_{1}^{1}-\left(f_{2}^{n}+f_{2}^{n}\frac{dy}{dx}\right)f_{2}^{1}}{f_{2}^{1,2}}=-\frac{f_{1}^{2}f_{2}^{n}-2f_{1}^{1}f_{2}^{1}f_{2}^{n}+f_{2}^{1,2}f_{2}^{n}}{f_{2}^{1,3}} $

必要：由  $ y^{n}=0 $ 知  $ \frac{f_{1}^{2}f_{2}^{n}-2f_{1}^{1}f_{2}^{1}f_{2}^{n}+f_{1}^{1}f_{2}^{n}}{f_{2}^{1,2}}=0 $ 充分：由  $ \cdots=0 $ 知  $ y^{n}=0 $

6.  $ f(x,y) $ 在  $ (0,0) $ 某邻域内连续且  $ \lim\limits_{x\to0}\frac{f(x,y)-xy}{(x+y)^{2}}=1 $，证明  $ (0,0) $ 不是  $ f(x,y) $ 的极值点 (03. 一改)

解：由  $ \frac{f(x,y)-xy}{(x+y)^{2}}=1+d $  $ \left(\lim\limits_{x\to0}d=0\right) $  $ f(x,y)=xy+(H+d)(x^{2}+y^{2}) $. 令  $ y=x $,  $ f=x^{2}+4(1+d)x^{4}=x^{2}+o(x^{2})>0 $, 同理  $ \exists y=-x $ 得  $ f=-x^{2}+o(x^{2})>0 $, 即可正负. 注：① 不可得出  $ f(x,y) $ 由 xy 所确定，这是认为  $ (x^{2}+y)^{2} $ 是 xy 的高阶无穷小，但  $ \lim\limits_{x\to0}\frac{(x^{2}+y)^{2}}{xy} $ 不存在，因为  $ \lim\limits_{y=x^{2}+y^{2}}\frac{(x^{2}+y)^{2}}{xy}=\lim\limits_{x\to0}\frac{x^{4}+2x^{10}+x^{16}}{x^{5}}=\infty $

取 $ y=x^{n} $则 $ \frac{(x^{2}+x^{2})^{2}}{x^{n+1}}=\frac{x^{4}}{x^{n+1}} $，当 $ n+1>4 $时就不存在

7 设  $ f(x,y) $ 在全平面上可微且  $ \lim_{x\to+\infty}(x\frac{\partial f}{\partial x}+y\frac{\partial f}{\partial y})=\alpha>0 $， $ \beta=\sqrt{x^{2}+y^{2}} $， $ d $ 为常数。证明： $ f(x,y) $ 在全平面上有最小值。

证：由保号性， $ \exists R>0 $，当 $ y\geq R $时 $ X\frac{\partial F}{\partial x}+Y\frac{\partial F}{\partial y}>0 $，故 $ \frac{x}{Y} $较 $ y\frac{\partial F}{\partial y}>0 $。对于 $ \sqrt{x^{2}+y^{2}} $，则 $ \frac{\partial f}{\partial x^{2}}=\frac{x}{y}\frac{\partial f}{\partial x}+\frac{y}{y}\frac{\partial f}{\partial y}>0 $

即 $ f $在 $ x^{2}+y^{2}\geq R^{2} $上任一极径方向导数大于0（为增函数） $ ^{①} $由连续知 $ f $在 $ x^{2}+y^{2}\leq R^{2} $内有 $ \min $，又由 $ ^{①} $知为全局 $ \min $

注：极径 $ \frac{x}{y}=(x,y) $， $ \overrightarrow{n}=\frac{(x,y)}{|\overrightarrow{n}|} $， $ \frac{\partial f}{\partial y}=\frac{x}{|\overrightarrow{n}|}\frac{\partial f}{\partial x}+\frac{y}{|\overrightarrow{n}|}\frac{\partial f}{\partial y} $

### 8. 证明偏导连续  $ \Rightarrow $ 可微

 $$  f ( x , y ) - f ( x_{0} , y_{0}) = f ( x , y ) - f ( x_{0} , y ) + f ( x_{0} , y ) - f ( x_{0} , y_{0}) = ( x - x_{0} ) f _ { x } ^ { \prime } ( x , y ) + ( y - y_{0} ) f _ { y } ^ { \prime } ( x _ { 0 } , y ) $$ 

 $$ =(x-x_{0})\left[f_{x}^{1}(x_{0},y_{0})+0(1)\right]+(y-y_{0})\left[f_{y}^{1}(x_{0},y_{0})+0(1)\right]=\quad f_{x}^{1}(x_{0},y_{0})(x-x_{0})+f_{y}^{1}(x_{0},y_{0})(y-y_{0})+\left[0(x-x_{0})+0(y-y_{0})\right] $$ 

 $$ \lim\limits_{x\rightarrow x_{0}}\frac{0(x-x_{0})+0(x-x_{0})}{\sqrt{(x-x_{0})^{2}+(y-y_{0})^{2}}}=\lim\limits_{\sqrt{(x)^{2}+(y)^{2}}}-\frac{0(x-x_{0})}{\sqrt{(x)^{2}+(y)^{2}}}+\frac{0(y-y_{0})}{\sqrt{(y)^{2}+(x)^{2}}}\leq\lim\limits_{|x\rightarrow x_{0}|}\frac{0(x-x_{0})}{|x-x_{0}|}+\frac{0(y-y_{0})}{|y-y_{0}|}=0.故\Delta f=d f+O(P) $$ 

注：偏导本身R涉及x, y两个方向，故不可微。偏导连续是二元极限存在的问题，而二元极限所定义的邻域是四面八方，因此保证了任意路径

# 多元微分-A

1. 设  $ F(x,y,u,v) $,  $ G(x,y,u,v) $ 在点  $ M_{0}(x_{0},y_{0},u_{0},v_{0}) $ 某邻域内连续可偏导，且  $ F(x_{0},y_{0},u_{0},v_{0})=0 $,  $ G(x_{0},y_{0},u_{0},v_{0})=0 $, 且  $ \left.\sum_{i=0}^{2}\frac{\partial F_{i}}{\partial u_{i}}\right|_{M_{0}}=\left|\frac{\partial F}{\partial u}\frac{\partial F}{\partial v}\right|_{M_{0}}\neq0 $, 则  $ M_{0} $ 邻域内由 F=0, G=0 能唯一确定连续可偏导的  $ u=u(x,y) $,  $ v=v(x,y) $, 且有  $ \frac{\partial u}{\partial x}=-\frac{1}{5}\frac{\partial(F(x))}{\partial(x,v)} $,  $ \frac{\partial u}{\partial y}=-\frac{1}{5}\frac{\partial(F,w)}{\partial(y,v)} $,  $ \frac{\partial v}{\partial x}=-\frac{1}{5}\frac{\partial(F,w)}{\partial(u,x)} $,  $ \frac{\partial v}{\partial y}=-\frac{1}{5}\frac{\partial(F,w)}{\partial(u,y)} $

证：由$\left\{\begin{array}{l}\frac{\partial F}{\partial x}+\frac{\partial F}{\partial u}\frac{\partial u}{\partial x}+\frac{\partial F}{\partial v}\frac{\partial v}{\partial x}=0\\\frac{\partial F}{\partial x}+\frac{\partial F}{\partial u}\frac{\partial u}{\partial x}+\frac{\partial F}{\partial v}\frac{\partial v}{\partial x}=0\end{array}\right.$ 得$\left[\begin{array}{l}\frac{\partial F}{\partial u}\frac{\partial F}{\partial v}\\\frac{\partial F}{\partial u}\frac{\partial G}{\partial v}\end{array}\right]\left[\begin{array}{l}\frac{\partial u}{\partial x}\\\frac{\partial v}{\partial x}\end{array}\right]=\left[\begin{array}{l}-\frac{\partial F}{\partial x}\\-\frac{\partial F}{\partial x}\end{array}\right]$ 则$\left.\frac{\partial u}{\partial x}=\frac{1}{f}\right|-\left.\frac{2F}{2x}\frac{\partial F}{\partial v}\right|=-\frac{1}{f}\frac{\partial(F\psi)}{\partial(x,v)},\quad$ 其余同理

### 2. 三种变换求偏导，将 $ z=f(x,y) $与 $ z=g(u,v) $互换

(1)  $ \left\{\begin{array}{l} u=u(x,y) \\ v=v(x,y) \end{array}\right. $ 若  $ \left\{\begin{array}{l} u=ax+by \\ v=cx+dy \end{array}\right. $，求  $ \frac{\partial^{2}z}{\partial x^{2}} $， $ \frac{\partial^{2}z}{\partial y^{2}} $， $ \frac{\partial^{2}z}{\partial x\partial y} $

(2)  $ \left\{\begin{array}{l} W=W(x,y,3) \\ u=u(x,y) \\ v=v(x,y) \end{array}\right. $ 设  $ z=z(x,y) $ 满足  $ \frac{\partial z}{\partial x}-\frac{\partial z}{\partial y}=x+y $,  $ W=z-\ln(x+y) $,  $ \left\{\begin{array}{l} u=x+y \\ v=y \end{array}\right. $，将①转为W关于u,v的方程

(3)  $ \left\{\begin{array}{l} x=x(u,v) \\ y=y(u,v) \end{array}\right. $  $ f(x,y) $ 满足  $ \left(\frac{\partial x}{\partial x}\right)^{2}+\left(\frac{\partial y}{\partial y}\right)^{2}=4 $， $ \left\{\begin{array}{l} x=u v \\ y=\frac{u^{2}-v^{2}}{2} \end{array}\right. $ 将  $ f(x,y) $ 转为  $ g(u,v) $ 且满足  $ a\left(\frac{\partial y}{\partial u}\right)^{2}-b\left(\frac{\partial y}{\partial v}\right)^{2}=u^{2}+v^{2} $，求 a,b.

解: (1)  $ \frac{\partial^{2}z}{\partial x^{2}}=a^{2}+2ac+c^{2}=(a+c)^{2} $  $ \frac{\partial^{2}z}{\partial y^{2}}=b^{2}+2bd+d^{2}=(bd)^{2} $  $ \frac{\partial^{2}z}{\partial x\partial y}=ab+(ad+bc)+cd=(a+c)(bd+d) $

依次为 $ \frac{\partial^{2}z}{\partial u^{2}} $， $ \frac{\partial^{2}z}{\partial u\partial v} $， $ \frac{\partial^{2}z}{\partial v^{2}} $的系数

(2)  $ \left\{\begin{array}{l}\frac{\partial W}{\partial x}=\frac{\partial B}{\partial x}-\frac{1}{x+y}\\ \frac{\partial W}{\partial y}=\frac{\partial B}{\partial y}-\frac{1}{x+y}\end{array}\right. $，代入①有  $ \frac{\partial W}{\partial x}-\frac{\partial W}{\partial y}=x+y $，即  $ \left(\frac{\partial W}{\partial u}\right)-\left(\frac{\partial W}{\partial u}+\frac{\partial W}{\partial v}\right)=U $，即  $ -\frac{\partial W}{\partial V}=U $

思路：①对W偏导，将 $ \frac{\partial w}{\partial x} $，翻转为 $ \frac{\partial w}{\partial x} $， $ \frac{\partial w}{\partial y} $ ②同(1)将 $ \frac{\partial w}{\partial x} $， $ \frac{\partial w}{\partial y} $转为 $ \frac{\partial w}{\partial u} $， $ \frac{\partial w}{\partial v} $

(3)  $  f(x, y) = f(uv, \frac{u^{2} - v^{2}}{2}) = g(u, v)  $，则  $ \frac{\partial g}{\partial u} = \frac{\partial f}{\partial u} = vt_{1}^{1} + af_{2}^{1}, \frac{\partial g}{\partial v} = af_{1}^{1} - vf_{2}^{1} $，代入得  $ (av^{2} - bu)^{2} + f_{1}^{2} + (2a + 2b) $

 $ uv f_{1}^{1} f_{2}^{1} + (au^{2} - bv)^{2} f_{2}^{2} = u^{2} + v^{2} $，故  $ \left\{\begin{array}{l} a = -b \\ 2a + 2b = 0 \end{array}\right. $ 即  $ a = \frac{1}{4}, b = -\frac{1}{4} $

思路：①将 $ \left\{\begin{array}{l}x=x(u,v)\\y=y(u,v)\end{array}\right. $代入到f中得 $ g(u,v) $ ②对 $ g(u,v) $偏导

注： $ n $个变量， $ r $个等式约束  $ \Rightarrow $  $ n-r $个自变量， $ r $个函数

3.(1)  $ \lim_{x \to 0} \frac{x^2 + y^2}{(x+1)(1-x)} $ (2)  $ \lim_{x \to 0} \frac{(x-y)}{\sqrt{x^2+y^2}} $ (3)  $ f(x,y) $，其中  $ (0,0)=0 $ 且  $ (x,y) $ 在  $ (0,0) $ 某邻域内连续 (3)  $ \lim_{(x,y)\to(0,0)}\frac{x^3y^4}{x^2+y} $

解：(1)  $ 0 \leq L \leq \frac{x^2}{|x| + |y|} + \frac{y^2}{|x| + |y|} \leq \frac{x^2}{|x|} + \frac{y^2}{|x|} \rightarrow 0 $ (2)  $ \frac{|x-y|}{\sqrt{x^2+y^2}} \leq \frac{|x|}{\sqrt{x^2+y^2}} + \frac{|y|}{\sqrt{x^2+y^2}} \leq 2 $ 有界，故  $ L = 0 $

(3) 令  $ y = -x^{2} + x^{n} $，则  $ I = \lim_{x^{n}} \frac{x^{3} (-x^{2} + x^{n})^{2}}{x^{n}} = \lim_{x^{n}} x^{3} \frac{(x^{8} + \cdots + x^{4n})}{x^{n}} $ 则取  $ n \geq 1 $ 即可证  $ \lim_{x \to +\infty} $ 不存在

4. 设 $ (y,0) $为极坐标， $ u=u(x,0) $有二阶连续偏导且 $ \frac{\partial u}{\partial\theta}=0 $且 $ \frac{\partial^{2}u}{\partial x^{2}}+\frac{\partial^{2}u}{\partial y^{2}}=0 $，求 $ u(x,\theta) $.

解由 $ \frac{\partial u}{\partial x}=0 $知 $ u $仅为 $ r $的函数，设 $ u=\varphi(x) $，其中 $ r=\sqrt{x+y^{2}} $得 $ \frac{\partial u}{\partial x}=\varphi^{0}(x)\frac{x^{2}}{y^{2}}+\varphi^{1}(x)\left(\frac{1}{y}-\frac{x^{2}}{y^{2}}\right) $，代入得 $ \varphi^{0}(x)+\varphi^{1}(x)\frac{1}{x}=0 $即 $ \left[y\varphi(x)\right]^{2}=0\Rightarrow y\varphi'(x)=G\Rightarrow u=G\ln r+G $

5. 周长为2P的三角形，求使它绕自己的一边旋转时所构成旋转体体积最大的三角形

解  $  S = \frac{1}{2} y h = \sqrt{P(P-x)(P-y)(P-z)}  $,  $  V = \frac{\pi}{3} h^2 = \frac{\pi}{3} \cdot \frac{4S^2}{y} = \frac{4\pi}{3} P(P-x)(P-y)(P-z)/y  $, 不妨令

 $  F = \ln(P-x) + \ln(P-y) + \ln(P-z) - \ln y + \lambda (x+y+z-2p)  $，得  $  x = z = \frac{3P}{4}  $,  $  y = \frac{P}{2}  $,  $  V_{\max} = \frac{\pi}{12} p^3  $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//aab7b832-02c0-46bf-8d06-03533a7e99ad/markdown_2/imgs/img_in_image_box_928_409_1023_520.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A42Z%2F-1%2F%2Ffdf06d2be9273af82f3ab15e381f1a7147d67d277c224164e1167b2b07748d27" alt="Image" width="7%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//aab7b832-02c0-46bf-8d06-03533a7e99ad/markdown_2/imgs/img_in_image_box_928_409_1023_520.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A42Z%2F-1%2F%2Ffdf06d2be9273af82f3ab15e381f1a7147d67d277c224164e1167b2b07748d27" alt="Image" width="7%" />

 $ x $

 $ y $

 $ h $

 $ z $

</div>


</div>


6. 证明：\forall a,b,c>0, 有 abc^{3}\leq\frac{27}{5^{5}}(a+b+c)^{5}

解：①证： $ x+y+z=k $ 时  $ xyz^{3}\leq\frac{27}{5^{5}}k $，由条件极值方法知  $ x=y=\frac{k}{5} $， $ z=\frac{3k}{5} $ 时  $ (xyz^{3})_{\max}=\frac{27}{5^{5}}k^{5} $

②  $ xyz^{3}=3^{3}xy\frac{2}{3}\frac{b}{3}\frac{2}{3} $，又  $ x+y+\frac{3}{3}+\frac{3}{3}+\frac{3}{3}=k $，则  $ x=y=\frac{2}{3} $ 时  $ xyz^{3} $ 取得  $ \max $.

7. 求原点到  $ x^{2}-4xy+5y^{2}=1 $ 的距离的min, max

解:  $ F = x^{2} + y^{2} + \lambda(x^{2} - 4xy + 5y^{2} - 1) $  $ \left\{\begin{array}{l} F_{x}^{2} = 2x + 2\lambda x - 4xy = 0 \\ F_{y}^{2} = 2y - 4\lambda x + 10xy = 0 \end{array}\right. $ 由①  $ \frac{x}{2} + ② \cdot \frac{y}{2} $ 得  $ x^{2} + y^{2} + \lambda(x^{2} - 4xy + 5y^{2}) = 0 $ , 于是  $ x^{2} + y^{2} = -\lambda $. 又由有非零解  $ \left\{\begin{array}{l} |x - \lambda - 2| \\ |x + \lambda + 2| \end{array}\right. $  $ \left\{\begin{array}{l} x^{2} = x^{2} - 4xy + 5y^{2} = 0 \\ x + 6 + 1 = 0 \end{array}\right. $  $ \lambda = -3 \pm 2\sqrt{2} $,  $ d = \sqrt{2} - \lambda = \sqrt{2} \pm 1 $  $ \sqrt{2} - 1, \sqrt{2} + 1 $

另解(原创):  $ A = \begin{pmatrix} 1 & -2 \\ -2 & 5 \end{pmatrix} $,  $ \lambda = 3 \pm 2\sqrt{2} $ 在  $ x^{T} A x = 1 $ 下,  $ x^{T} x \in \left[\frac{1}{\lambda_{\max}}, \frac{1}{\lambda_{\min}}\right] $ 是  $ d = \sqrt{2} x \in [\sqrt{2} + \sqrt{2} + 1] $

其中①是常用结论的逆向，显然令 $ y=Q^{T}x $时， $ y^{T}\Lambda y=\lambda_{1}^{2}y^{2}+\lambda_{2}^{2}y^{2}=1 $， $ y^{T}y=x^{T}x=y_{1}^{2}+y_{2}^{2}\in\left[\frac{1}{\lambda_{\max}},\frac{1}{\lambda_{\min}}\right] $，即椭圆轴长 $ \frac{1}{\sqrt{2}} $， $ \frac{1}{\sqrt{2}} $

注：同理， $ f(x) $ 在球面  $ x^{T}x = k^{2} $ 上的  $ N_{max} = \lambda_{max} k^{2} $， $ \min = \lambda_{\min} k^{2} $

8. 说明  $ f(x, y) = \begin{cases}(y-e^{-\frac{x}{2}})(y-3e^{-\frac{x}{2}}) & x \neq 0 \\ y^2 & x = 0\end{cases} $ 在  $ (0, 0) $ 处取极值

解:  $ x=0 $ 时,  $ f(x,y)=y^{2}\geq0 $,  $ x\neq0 $ 时, 令  $ t=e^{-\frac{x}{2}} $, 则  $ f=(y-t)(y-3t)=y^{2}-4ty+3t^{2} $, 故取  $ y=2t=2e^{-\frac{x}{2}} $,  $ f=-t^{2}<0 $

7.  $ B = f(x, y) $ 连续  $ \lim_{(x, y) \to (0, 0)} \frac{f(x, y) + x^2 + x - 2y - 2}{x^2 - 2x + 2y^2 + 1} = 1 $，则  $ d\beta|_{(1,0)} = $ ___.

解：由连续， $ f(1, 0) = 0 $，而  $ \lim_{\sqrt{(x-1)^2 + y^2} \to 0} \frac{f(x, y) + x^2 + x - 2y - 2}{\sqrt{(x-1)^2 + y^2}} = \lim_{\sqrt{(x-1)^2 + y^2} \to 0} \frac{(x-1)^2 + 2y^2}{\sqrt{(x-1)^2 + y^2}} \leq 2\sqrt{(x-1)^2 + y^2} \to 0 $

又由  $ \lim_{x \to 0} \frac{f(x, y) + (x-1)^2 + 3(x-1) - 2y}{\sqrt{(x-1)^2 + y^2}} = 0 $

与  $ \lim_{(x, y) \to (1, 0)} \frac{(x-1)^2}{\sqrt{(x-1)^2 + y^2}} = \sqrt{(x-1)^2 + y^2} \to 0 $

知  $ \lim_{x \to 0} \frac{f(x, y) + 3(x-1) - 2y}{\sqrt{(x-1)^2 + y^2}} = 0 $

于是  $ d\beta = -3dx + 2dy $

# 重积分

## 一、二重积分

1. 根无念  $ \iint_{D} f(x,y) d\sigma = \lim_{\lambda \to 0} \sum_{i=1}^{n} f(s_{i}, \eta_{i}) \Delta \sigma_{i} $ ( $ \lambda $ 为各小闭区域直径的最大值)

### 2. 性质

(1) 可积必有界 (三重、曲线、曲面同理)

(2) 中值定理 设  $ f(x, y) $ 在有界闭区域 D 上连续，则  $ \exists(\xi, \eta) \in D $，使  $ \iint_{D} f(x, y) \, dG = f(\xi, \eta) S_{D} $

(3) 对称性 若 D 关于 y = x 对称，则  $ \iint_{D} f(x, y) d\delta = \iint_{D} f(x, x) d\delta = \frac{1}{2} \iint_{D} [f(x, y) + f(x, x)] dx dy $

若 D 关于 y = x 对称，则  $ \iint_{D} f(x, y) d\delta = \begin{cases} 2 \iint_{D} f(x, y) d\delta & (x, y) = f(x, x) \\ 0 & f(x, y) = -f(x, x) \end{cases} \rightarrow f(x, y) = f(\text{对称点坐标}) $ 相当于“偶倍”

## 3. 计算

(1) 先  $ y \in x $  $ \iint_{D} f(x,y) d\sigma = \int_{a}^{b} dx \int_{400}^{840} f(x,y) dy $ 适用于：易对 y 积分或 D 是 x 型区域

(2) 极坐标  $ \iint_{D} f(x,y) d\sigma = \int_{d}^{B} d\theta \int_{r_{1}(\theta)}^{r_{2}(\theta)} f(r\cos\theta, r\sin\theta) r dr $ 适用于:  $ f(x^{2} + y^{2}), f(x) $，圆，可先轮换再极坐标)

(3)换元法  $ \frac{\partial(x,y)}{\partial u,v}=\left|\frac{\partial x}{\partial u}\frac{\partial x}{\partial v}\right|\neq0 $ 则  $ dxdy\rightarrow\left|\frac{\partial(x,y)}{\partial u,v}\right| $ dudv 如:  $ dx dy\rightarrow\left\|\cos\theta\cdot r\sin\theta\right\|\sin\theta\ r\cos\theta\parallel dr d\theta=r d r d\theta $

## 二、三重积分

1. 根无念  $ \iiint_{D}f(x,y,z)dv=\lim_{\Delta\rightarrow0}\sum_{i=1}^{n}f(s_{i},\eta_{i},\zeta_{i})\Delta v_{i} $ (入为各小闭区域直径的最大值)

### 2. 性质

(1) 中值定理 设  $ f(x, y, z) $ 在有界闭区域  $ n $ 上连续，则  $ \exists\xi, \eta, \zeta) $ 使  $ \iint_{D} f(x, y, z) \, dV = f(\xi, \eta, \zeta) V $

(2) 对称性 若几关于x_{0}z对称，则 $ \{f(x,y,z)=f(x,y,z)\} $  $ \rightarrow x_{1} $不动，关于x_{0}z的函数

## 3. 计算

(1) 先已知  $  f(x) = \int_{0}^{x} f(t) \, dt = \int_{0}^{x} d\theta \int_{0}^{2\pi} (x, y) \, dz  $ 适用于：无侧面或侧面为柱面注： $ \iint_{D} d\theta $ 可用极坐标求解

(2) 先  $ xy $ 后  $ z $  $ \iiint\limits_{D} f\,dv = \int_{a}^{b} dz \, d\sigma \quad \iint\limits_{D_2} f\,d\sigma \rightarrow D_x = D(z) $ 好求 适用于: 凡是旋转体 注:  $ \iint\limits_{D_y} f\,d\sigma $ 可用极坐标求解

(3) 球面坐标系  $ \left\{\begin{array}{l} x=y\sin\varphi\cos\theta \\ y=y\sin\varphi\sin\theta \\ x=x\cos\varphi\end{array}\right. $,  $ dv = r^{2}\sin\varphi $  $ drd\varphi d\theta $ 注： $ \theta\in[0,2\pi] $,  $ \varphi\in[0,\pi] $, 图见右下

(4)换元法  $ \frac{\partial(x,y,z)}{\partial(u,v,w)}=\begin{vmatrix}\frac{\partial x}{\partial u}&\frac{\partial x}{\partial v}&\frac{\partial x}{\partial w}\\ \frac{\partial y}{\partial u}&\frac{\partial y}{\partial v}&\frac{\partial y}{\partial w}\end{vmatrix}\neq0 $，则  $ dx dy dz\rightarrow\left|\frac{\partial(x,y,z)}{\partial(u,v,w)}\right|du dv dw $ 如： $ \begin{vmatrix}\sin\varphi\cos\theta&-r\sin\varphi\sin\theta&r\cos\varphi\cos\theta\\ \sin\varphi\sin\theta&r\sin\varphi\cos\theta&r\cos\varphi\sin\theta\\ \cos\varphi&0&-r\sin\varphi\end{vmatrix}=\frac{r}{2}\sin\varphi $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//aab7b832-02c0-46bf-8d06-03533a7e99ad/markdown_3/imgs/img_in_image_box_915_1238_1056_1403.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A42Z%2F-1%2F%2F81b92d04bc11f1d704cc697069d70280f3f657bf2c1918f9267e786af7f44833" alt="Image" width="11%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//aab7b832-02c0-46bf-8d06-03533a7e99ad/markdown_3/imgs/img_in_image_box_915_1238_1056_1403.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A42Z%2F-1%2F%2F81b92d04bc11f1d704cc697069d70280f3f657bf2c1918f9267e786af7f44833" alt="Image" width="11%" />

Z↑
KOKUYO

</div>


</div>


### 三应用

### 1. 三重积分

质量  $ M = \iiint_{D} P(x, y, z) dv $ 重心/质心  $ (\overline{x}, \overline{y}, \overline{z}) $:  $ \overline{x} = \frac{\iiint_{D} P(x, y, z) dv}{\iiint_{D} P(x, y, z) dv} $ P为常数时为形心

转动惯量  $ I_{x}=\frac{\iint\limits_{D}(y^{2}+z^{2})P(x,y,z)dv}{dz} $ 引力  $ F_{x}=Gm\iint\limits_{D}\frac{P(x,y,z)(x-x_{0})}{d^{3}}dv $,  $ d=\sqrt{(x-x_{0})^{2}+(y-y_{0})^{2}+(z-z_{0})^{2}} $

### 2. 二重积分

空间曲面  $ S=\frac{\iint\limits_{D}H-2x^{2}+2y^{2}}{x}dx dy $ 质心  $ \overline{x}=\frac{\iint\limits_{D}P(x,y)dx dy}{\iint\limits_{D}P(x,y)dx dy} $

转动惯量  $ I_{x}=\int_{0}^{1}y^{2}P(x,y)dx dy $

### 重积分

1. 如何理解  $ dx\,dy = rdr\,d\theta $

解：①首先  $ d \times dy $ 不是乘积（不然代入  $ \left\{ \begin{array}{l} dx = \cos\theta \\ dy = \sin\theta \end{array} \right.  $  $ dr + r\cos\theta d\theta $ 是错的），可用雅克比矩阵的行列式证明.

②前置知识：外积 $ \overrightarrow{a} $表示平面区域，叉乘 $ \overrightarrow{a}\times\overrightarrow{b} $与平面垂直。外积满足反对称性： $ \overrightarrow{e_{3}}\wedge\overrightarrow{e_{3}}=-\overrightarrow{e_{3}}\wedge\overrightarrow{e_{3}} $那么 $ dx\wedge dy=(\cos\theta dr-\sin\theta d\theta)\wedge(\sin\theta dr+\cos\theta d\theta)=\cos\theta\sin\theta dr\wedge dr+\cos^{2}\theta dr\wedge d\theta-\sin^{2}\theta d\theta\wedge dr $

 $ -r^{2}\sin\theta\cos\theta d\theta\wedge d\theta=0+r\cos^{2}\theta dr\wedge d\theta+r\sin^{2}\theta dr\wedge d\theta-0=r dr\wedge d\theta $

 $$ d_{x}\wedge d_{y}=(\frac{\partial x}{\partial u}d u+\frac{\partial x}{\partial v}d v)\wedge(\frac{\partial y}{\partial u}d u+\frac{\partial y}{\partial v}d v)=\frac{\partial x}{\partial u}\frac{\partial y}{\partial v}d u\wedge d v-\frac{\partial x}{\partial v}\frac{\partial y}{\partial u}d u\wedge d v=\left|\frac{\partial x}{\partial u}\frac{\partial x}{\partial v}\right|d u\wedge d v $$ 

### 重积分-A

 $ f(1)\int_{0}^{+\infty}e^{x}dx $ (2)  $ \iint_{D}max\{x,y\}e^{-\frac{x^{2}}{2}}dxdy $,  $ D=\{x,y\vert x\geq0,y\geq0\} $

解考虑  $ D_{1}:\int_{0}^{+\infty}x^{2}+y^{2}\geq R^{2} $  $ D_{2}:\int_{x\geq0,y\geq0}^{x^{2}+y^{2}+2R^{2}}d\sigma\leq\iint_{D_{1}}e^{-x^{2}-y^{2}}d\sigma $

即  $ \int_{0}^{\frac{\pi}{2}}d\theta\int_{0}^{R}r\tau^{2}dr\leq(\int_{0}^{R}e^{-x^{2}}dx)^{2}\leq\int_{0}^{\frac{\pi}{2}}d\theta\int_{0}^{\sqrt{2}R}r\tau^{2}dr $，即  $ \frac{\pi}{4}(1-e^{-R^{2}})\leq\frac{1}{4}\pi(1-e^{-2R^{2}}) $，当  $ R\rightarrow+\infty $ 时  $ I=\frac{\sqrt{2}\pi}{2} $

(2)  $ \int_{0}^{\frac{\pi}{2}}I=f_{1}^{\prime}x e^{-x^{2}}dx $  $ dx dy+f_{2}^{\prime}y e^{-x^{2}}dx dy=\int_{0}^{\frac{\pi}{4}}d\theta\int_{0}^{+\infty}r^{2}cos\theta e^{-r^{2}}dr+\int_{\frac{\pi}{4}}^{\frac{\pi}{2}}d\theta\int_{0}^{+\infty}r^{2}sin\theta e^{-r^{2}}dr=\sqrt{2}\int_{0}^{+\infty}r^{2}e^{-r^{2}}dr $

 $ \frac{r^{2}}{2}=\frac{\sqrt{2}}{2}\int_{0}^{+\infty}t^{\frac{1}{2}}e^{-t}dt=\frac{\sqrt{2}}{2}\cdot\frac{1}{2}\sqrt{2}\pi=\frac{\sqrt{2}}{4} $

 $ 2(1+f(x)=0,f'(x)=1) $, D:  $ \left\{\begin{array}{l}x^{2}+y^{2}\leq2tx \\ y\geq0\end{array}\right. $，求  $ \lim\limits_{t\rightarrow0}\frac{\iint\limits_{D}yf(x+t)dxdy}{t^{4}} $

(2) 求  $ \lim\limits_{x\rightarrow0}\frac{\iint\limits_{D}e^{x^{2}-2y^{2}}\cos(2x+y)dxdy}{\pi r^{2}} $, D:  $ x^{2}+y^{2}\leq r^{2} $

解: I:  $ \int_{0}^{\frac{\pi}{2}} d\theta\int_{0}^{2t\cos\theta}r^{2}\sin\theta f(r)dr=\int_{0}^{2t}r^{2}f(r)dr\int_{0}^{arccos\frac{r}{2t}}\sin\theta d\theta=\int_{0}^{2t}r^{2}f(r)(1-\frac{r}{2t})dr $，则原式 =

 $ \lim\limits_{t\rightarrow0^{+}}t\int_{0}^{2t}f^{2}(t)dr-\frac{1}{2}\int_{0}^{2t}r^{2}(t)dr=\lim\limits_{t\rightarrow0^{+}}t\int_{0}^{2t}r^{2}f(t)dr=\lim\limits_{t\rightarrow0^{+}}t\frac{8t^{2}+f(x)}{20t^{3}}=\frac{4}{5}+f'(0)=\frac{4}{5} $  $ (f'(0)=\lim\limits_{t\rightarrow0}f(2t)-f(0) $

(4)积分中值， $ I = \lim_{r \to 0^{+}} \frac{1}{\pi r^{2}} \cdot \left( e^{\frac{5}{2} - 2r^{2}} \cos(2\xi + \eta) \right) \pi r^{2} = e^{\theta} \cos \theta = 1 $

 $$ D:1\leq x^{2}+y^{2}\leq4 $$ 

 $$ \int\limits_{0}^{4}d z\iint\limits_{D}\frac{\sin(2\sqrt{x^{2}+y^{2}})}{\sqrt{x^{2}+y^{2}}}d x d y $$ 

解:  $ I=\frac{1}{2}\int_{0}^{2\pi}d\theta\int_{1}^{2}dr\int_{2}^{4}\frac{\sin2r}{r}\cdot r d\theta=\lim_{u\to\infty}\int_{1}^{2}d\theta\int_{0}^{4}\sin2r d\theta=\lim_{u\to\infty}\int_{1}^{2}\frac{1-cosuv}{r}dr=\ln2 $，其中 $ \int_{1}^{2}\frac{cosuv}{r}dr=\int_{0}^{2u}\frac{cost}{t}dt\rightarrow0 $，因为 $ \lim_{u\to\infty}\int_{u}^{2u}\frac{cost}{t}dt=\frac{\sin t}{t}\int_{u}^{2u}+\int_{u}^{2u}\frac{\sin t}{t^{2}}dt\leq0+\int_{u}^{2u}\frac{1}{t^{2}}dt=0 $

# 微分方程

## 一、根无念

1. 微分方程 ①方程 ②含未知函数的导数

阶 最高阶导数的阶数

常微分方程未知函数是一元函数

n阶线性微分方程  $ a_{n}(x)y^{(n)}+\cdots+a_{1}(x)y^{1}+a_{0}(x)y=f(x) $  $ (a_{n}(x)\neq0) $

 $ a_{i}(k) $均为常数时称为常系数.

 $ f(x)=0 $ 称为齐次.

2. 通解 解中独立常数的个数 = 阶数

独立：经任何恒等变形都不能使常数个数减少

特解 不含任意常数 初始条件还可确定解的符号，如  $ y^{2}=x\xrightarrow{110}y=\sqrt{x} $

积分曲线 解对应的曲线

非线性方程：全部解 = 通解 + 奇解

线性方程：全部解 = 通解

如  $ y' = H \sin y $ 中  $ y = 2k\pi - \frac{\pi}{2} (\sin y = -1) $ 为奇解

## 二、求解 注意分母=0的奇解

1. 微分方程任意阶可导 光滑曲线⇒导数连续

2. 可分离变量  $ \int\frac{dy}{g(x)} = \int\frac{dx}{f(x)} $

换元：如  $ \frac{dy}{dx} = f(ax + by + c) $，令  $ u = ax + by + c $，则  $ \frac{du}{dx} = a + b\frac{dy}{dx} $。对换： $ (2y - x)y' = 2y \Rightarrow x' = \frac{2y - x}{2y} = 1 - \frac{1}{2y}x $

3. 齐次型  $ \frac{dy}{dx}=\varphi\left(\frac{y}{x}\right) $

令 $ u=\frac{y}{x} $，则 $ \frac{dx}{dx}=u+x\frac{du}{dx} $

如： $ y'=f(\frac{ax+by+k}{cx+dy+2}) $，令 $ \left\{\begin{array}{l}ax_{0}+by_{0}+k=0\\cx_{0}+dy_{0}+2=0\end{array}\right. $， $ \left\{\begin{array}{l}x=x-x_{0}\\y=y-y_{0}\end{array}\right. $得 $ \frac{dy}{dx}=f(\frac{ax+by}{cx+dy})=f(\frac{a+b\frac{y}{x}}{c+d\frac{y}{x}}) $

4. 一阶线性  $ y' + p(x)y = q(x) $

 $$ y=\left[\int q(x)\cdot e^{\int p(x)d x}d x+c\right]e^{-\int p(x)d x} $$ 

5. 伯努利  $ y' + p(x)y = q(x)y^{n}(n \neq 0,1) $

①同除 $ y^{-n} $:  $ y^{-n}y^{1}+p(x)y^{1-n}=q(x) $ ②令 $ z=y^{1-n} $:  $ \frac{1}{1-n}z_{x}^{1}+p(x)z=q(x) $

6. 二阶可降阶 是y的函数

①不含x：令 $ \frac{dy}{dx}=P $，则 $ y''=\frac{dp}{dy}\cdot P $，求得 $ P=\varphi(y,c) $，用分离变量

②不含 $ y $：令 $ \frac{dy}{dx}=p $，则 $ y''=\frac{dp}{dx} $，求得 $ P=\varphi(x,c) $，用直接积分.

7. 全微分方程  $ P(x,y)dx + Q(x,y)dy = 0 $

若 $ \frac{\partial Q}{\partial x}=\frac{\partial P}{\partial y} $，则 $ du=Pdx+Qdy $，通解为 $ u(x,y)=C $

8. 二阶常系数齐次线性  $ y'' + py' + qy = 0 $  $ \Delta = p^{2} - 4q $

①  $ \Delta > 0 $  $ \Delta_{1,2} $  $ y = C_{1}e^{\lambda_{1}x} + C_{2}e^{\lambda_{2}x} $

②  $ \Delta = 0 $  $ \lambda, \lambda $  $ y = (G + G_{2}x)e^{\lambda x} $

③  $ \Delta < 0 $  $ \alpha \pm \beta i $  $ y = e^{\alpha x} (C_{1}\cos\beta x + C_{2}\sin\beta x) $

9.  $ n(n>2) $ 阶常系数齐次线性

①单实根  $ \lambda $  $ y = ce^{2x} $

② k重实根  $ \lambda \cdots \lambda $  $  y = (G + G x + \cdots + G x)^{k-1} e^{\lambda x}  $

③单复根  $ \alpha \pm \beta i $  $ y = e^{\alpha x}(C_{1}\cos\beta x + G\sin\beta x) $

④二重复根  $ a \pm \beta i, a \pm \beta i $  $ y = e^{ax} (G \cos \beta x + Q \sin \beta x + Q_3 x \cos \beta x + Q_4 x \sin \beta x) $

10. 二阶常系数非齐次线性  $ y'' + py' + qy = f(x) $

①  $ f(x) = P_{n}(x)e^{dx} $  $ y^{*} = x^{k}Q_{n}(x)e^{dx} $， $ \alpha $ 是 K 重特征根。不同的两个 Y 次多项式

②  $ f(x) = e^{\alpha x}\left[P_{m}(x)\cos\beta x + P_{n}(x)\sin\beta x\right] $  $ y^{*} = e^{\alpha x}\left[Q_{r}(x)\cos\beta x + R_{r}(x)\sin\beta x\right]x^{k} $,  $ r = \max\{m, n\} $

③系数 $ \Sigma k=0 $为齐次之解， $ \Sigma k=1 $为非齐次之解

 $ b_{001} \leftarrow k = \{0, \alpha\beta\} $ 是特征根

11. 欧拉方程  $ x^{n}y^{(n)} + P_{1}x^{n-1}y^{(n-1)} + \cdots + P_{n-1}xy^{1} + P_{n}y = f(x) $

令  $ x = e^{t} (x > 0) $，有  $ x^{k} y^{(k)} = D(D-1) \cdots (D-k+1) y $

## 三、反求微分方程

n阶齐次，找出n个特征根即可.

2. 有  $ x^{k+1}e^{rx} \Rightarrow r $ 至少 k 重（特别地， $ e^{rx} \Rightarrow r $ 至少 1 重）

3.  $ y^{(n)} + a_{1}(x)y^{(n-1)} + \cdots + a_{n}(x)y = 0 $ 的通解满足：①  $ n \uparrow $ ②  $ \varphi_{1}(x), \ldots, \varphi_{n}(x) $ 线性无关 （通解： $ k\varphi_{1}(x) + \ldots + k_{n}\varphi_{n}(x) $）

4、①若解无界，则 $ x-+\infty\Rightarrow\gamma>0\quad x\to-\infty\Rightarrow\gamma<0 $

②若解有周期性，则 $ x=0 $，且此时解还有界

1. 推导  $ y' + p(x)y = q(x) $ 的通解

解：同乘  $ e^{Spwdx} $，有  $ e^{Spwdx}y' + e^{Spwdx}p(x)y = e^{Spwdx}q(x) $，即  $ [e^{Spwdx}y'] = e^{Spwdx}q(x) $，积分得： $ e^{Spwdx} \cdot y = \int e^{Spwdx}q(x)dx + c $，即  $ y = [\int e^{Spwdx}q(x)dx + c]e^{-Spwdx} $

注：① 如果  $ \int p(x)dx = |m|e(x)| $，有  $ e^{Spwdx} = |\varphi(x)| = \pm\varphi(x) $，代入公式有  $ y = [\int \pm \varphi(x)q(x)dx + c](\pm\frac{1}{\varphi(x)}) $

 $ = [\int \varphi(x)q(x)dx \pm c] \cdot \frac{1}{\varphi(x)} $，此时  $ \pm c $ 仍为任意常数，故  $ e^{Spwdx} = |\varphi(x)| $ 可不加绝对值

②该通解中的 $ \int $应理解为某一不含任意常数的原函数，则通解可写为： $ y=\left[\int_{x_{0}}^{x} q(t) e^{\int_{x_{0}}^{t} p(t) dt} dt + c\right] e^{-\int_{x_{0}}^{t} p(t) dt} $，特别地， $ y=\left[\int_{0}^{x} q(t) e^{\int_{0}^{t} p(t) dt} dt\right] e^{-\int_{x_{0}}^{x} p(t) dt} $

2.(原创)推导 $ y^{x}+py^{2}+ey=f $特解所满足的式子(1)记 $ y^{x}=x^{k}Q_{n}(x)e^{ax}=A(x)e^{ax} $ (2)记 $ y^{x}=e^{ax} $ [ $ A\times\cos\beta x+B\times\sin\beta x $]

解：(1)由 $ y=Ae^{ax},y=e^{ax} $  $ [\alpha A+A^{\prime}],y=e^{ax} $  $ [\alpha^{2}A+2\alpha A^{\prime}+A^{\prime\prime}] $，显然 $ A^{\prime\prime}+(2\alpha+p)A^{\prime}+(\alpha^{2}+p\alpha+q)A=P_{n}(x) $ 若α为1重特征根，则 $ \alpha^{2}+pa+q=0 $；若α为2重特征值，则 $ 2\alpha=-p $

这里记 $ x^{k}Q_{n}(x)=A(x) $ 是为了不与 $ Q_{n}(x) $ 混淆，(2)中一样令 $ x^{k}Q_{n}(x)=A(x) $， $ x^{k}R_{n}(x)=B(x) $

(2)不难算出 $ y=e^{ax} $  $ [A\cos\beta x+B\sin\beta x] $， $ y^{\prime}=e^{ax} $  $ [(1+\beta B+A\alpha)\cos\beta x+(B^{\prime}-A\beta+B\alpha)\sin\beta x] $

 $ y^{\prime\prime}=e^{ax} $  $ [(A^{\prime\prime}+2\alpha A^{\prime}+(\alpha^{2}-\beta^{2})A+2\beta B^{\prime}+2\alpha\beta B)\cos\beta x+(B^{\prime\prime}+2\alpha B^{\prime}+(\alpha^{2}-\beta^{2})B-2\beta A^{\prime}-2\alpha\beta A)\sin\beta x] $

显然有 $ \left\{\begin{aligned}&A^{\prime\prime}+(2\alpha+p)A^{\prime}+(\alpha^{2}-\beta^{2}+p\alpha+q)A+2\beta B^{\prime}+(2\alpha\beta+p\beta)B=P_{m}(x)\\&B^{\prime\prime}+(2\alpha+p)B^{\prime}+(\alpha^{2}-\beta^{2}+p\alpha+q)B-2\beta A^{\prime}-(2\alpha\beta+p\beta)A=P_{n}(x)\end{aligned}\right. $ 看似复杂，但注意到当 $ \alpha\neq\beta $ 为特征根时，有 $ \left\{\begin{aligned}&P=-2\alpha\\&q=\alpha^{2}+\beta^{2}\end{aligned}\right. $ 代入得 $ \left\{\begin{aligned}&A^{\prime\prime}+2\beta B^{\prime}=P_{m}(x)\\&B^{\prime\prime}-2\beta Q^{\prime}=P_{n}(x)\end{aligned}\right. $ 不含 $ e^{ax} $ 不含 $ e^{ax} $ 与 $ \cos\beta x\sin\beta x $

结论：为便于记忆，还是记 $ Q=X^{k}Q_{n}(x) $， $ Q=X^{k}Q_{r}(x) $， $ R=X^{k}R_{r}(x) $。有：

 $ \left\{\begin{array}{l}Q^{''}+(2\alpha+p)Q^{1}+(\alpha^{2}+p\alpha+q)A=P_{n}(x)\quad(\alpha\text{为}0\text{重特征根})\\Q^{''}+(2\alpha+p)Q^{1}=P_{n}(x)\quad(\alpha\text{为}1\text{重})\\Q^{''}=P_{n}(x)\quad(\alpha\text{为}2\text{重})\end{array}\right. $

不必记忆  $ (d\pm\beta) $ 不是特征根

 $ \left\{\begin{array}{l}Q^{''}+2\beta R^{1}=P_{m}(x)\\R^{''}-2\beta Q^{1}=P_{n}(x)\end{array}\right. $

 $ d\pm\beta $ 是特征根

注：同时注意到 $ \alpha $为 $ \vert $重时 $ \alpha^{2}+pd+q=0 $，由 $ Q^{1}(x) $为n次多项式，故取 $ Q(x)=xQ_{n}(x) $

 $ \alpha $为2重时 $ \alpha^{2}+pd+q=0 $， $ 2\alpha+p=0 $，由 $ Q^{1}(x) $为n次多项式，故取 $ Q(x)=x^{2}Q_{n}(x) $

## 3. 如何理解微分方程：函数映射函数

解：显然微分算子满足  $ D(x)=\lambda Dx $ (数乘)， $ \lambda_{1}D+\lambda_{2}D=(\lambda_{1}+\lambda_{2})D $ (可加)，因此微分算子就是线性变换。因此  $ y''+py'+qy=0 $  $ \Rightarrow(D^2+PD+qI)y=0 $ 由于  $ D(e^{yx})=ye^{yx} $，这相当于  $ A\overrightarrow{z}=\lambda\overrightarrow{z} $，因此  $ e^{yx} $ 为 D 对应  $ \lambda=\nu $ 的特征向量，因此令  $ y=e^{yx} $，有  $ (y^2+px+q)e^{yx}=0 $。以  $ \Delta>0 $ 为例， $ D^2+PD+qI $ 有  $ r_1\neq r_2 $，解空间是二维  $ (e^{yx}, e^{yx}) $，可由 Wronski 行列式  $ \left|\begin{array}{c}x_1 y_1 \\ x_2 y_2\end{array}\right|\neq0 $ 判断两个解线性无关。或者，由  $ (D-x_1)(D-x_2)y=0 $，令  $ (q-x_2)y=x_1y_1 $ 有  $ (D-x_1)x_1=0 $ 即  $ \frac{dx_1}{dx}-x_1y_1=0 $，故  $ y_1=Ce^{yx} $，故  $ \frac{dy_1}{dx}-x_2y_2=C_1e^{yx} $，显然  $ y=\frac{c_1}{r_1-r_2}e^{yx}+c_2e^{yx} $。若  $ r_1=r_2 $，显然积 D 后有  $ xe^{yx} $ 这一项。并且，这与广义特征向量  $ (A-\lambda E)\overrightarrow{z}=\overrightarrow{z} $， $ (A-\lambda E)\overrightarrow{z}=\overrightarrow{z} $ 形式上一致。而  $ y^2+py^2+q=f(x) $ 的特解可表为  $ y^*=\frac{1}{F(D)}e^{kx}P_n(x)=e^{kx}\frac{1}{F(D+k)}P_n(x) $，其中  $ f(x)=e^{kx}P_n(x) $  $ F(0)=D^2+PD+q $，令  $ y^*=e^{kx}u(x) $，有  $ D[e^{kx}u(x)]=e^{kx}u(x)+ke^{kx}u(x)=e^{kx}(D+k)u(x) $，即  $ F(D)=F(D+k)u(x) $，那么对于  $ F(D)y=e^{kx}P_n(x) $，有  $ F(D)[e^{kx}u(x)]=e^{kx}F(D+k)u(x)=e^{kx}P_n(x) $，因此  $ F(D+k)u(x)=P_n(x) $， $ u(x)=\frac{1}{F(D+k)}P_n(x) $，故  $ y=e^{kx}u(x)=e^{kx}F(D+k)P_n(x) $。或者说，将该式变形为  $ e^{-kx}F(D)e^{kx}P_n(x)=F(D+k)P_n(x) $，其实就是  $ e^{-kx}[D(e^{kx}+f)=(D+k)f $ 对  $ \forall f $ 恒成立，又由于  $ (D+k)e^{-kx}=r e^{(x-k)x} $，故相似变换  $ e^{-kx}pe^{kx} $ 使特征值  $ \frac{e^{-kx}}{p-k}[e^{kx}(f^1+kf)]=f^1+kf $

4. 说明  $ f(x)dx=\frac{dy}{g(x)} $ 为什么左边对x积分，右边对y积分等式仍成立

解 设解存在，记为  $ y=\varphi(x) $，则  $ f(x)dx=\frac{1}{g[\varphi(x)]}\varphi(x)dx $ 故  $ \int f(x)dx=\int\frac{\varphi(x)dx}{g[\varphi(x)]} $ 换元  $ \int\frac{dy}{g(x)} $

# 非常规的通解求法

1.  $ y' + \sin y + x \cos y + x = 0 $

解：注意到  $ 1 + \cos y = 2 \cos^{2}\frac{y}{2} $，则  $ \frac{1}{2\cos^{2}\frac{y}{2}} \frac{dy}{dx} + \tan\frac{y}{2} + x = 0 $，令  $ u = \tan\frac{y}{2} $，有  $ \frac{du}{dx} + u = -x $，即  $ \tan\frac{y}{2} = ce^{-x} + 1 - x $

# 微分方程

1.  $ y_{1}=x-\sqrt{1+x^{2}}, y_{2}=x+\sqrt{1+x^{2}} $ 为  $ y^{2}+p(x)y=Q(x) $ 的两个解，求  $ p(x), Q(x) $

解:  $ y_{2}-y_{1}=2\sqrt{4x^{2}} $ 为  $ y^{1}+p(x)y=0 $ 的解, 代入得  $ P(x)=-\frac{x}{1+x^{2}} $.  $ \frac{y_{1}+y_{2}}{2}=x $ 为  $ y^{1}-\frac{x}{1+x^{2}}y=Q(x) $ 的解, 代入得  $ Q(x)=\frac{1}{4x^{2}} $

2.  $ x=3, x=34x^{2}, y_{3}=3+e^{x} $ 是某一所线性非齐次方程的三个特解，求该微分方程

解：显然通解为  $ y = C_{1}x^{2} + C_{2}e^{x} + 3 $ 为消去  $ C_{1}, C_{2} $，由  $ \left\{\begin{array}{l} y^{2} = 2C_{1}x + C_{2}e^{x} \\ y^{2} = 2C_{1} + C_{2}e^{x} \end{array}\right. $ 得  $ \left\{\begin{array}{l} \textcircled{3} - \textcircled{2} : y = -y^{1} = 2C_{1}(1-x) \\ \textcircled{1} - \textcircled{2} : y = -y^{1} = C_{1}(x^{2} - 2x) + 3 \end{array}\right. $

④ $ x(2x-x^{2})+\textcircled{5}x(2(1-x)) $ 得  $ (2x-x^{2})y^{2}+(x^{2}-2)y^{2}+2(1-x)y=6(1-x) $

3  $ u(x,y)=f(x)+g(x) $ 有二阶连续偏导且  $ \left[H\left(\frac{\partial u}{\partial x}\right)\right]^{\frac{2}{2\alpha^{2}}}-2\frac{\partial u}{\partial x}\frac{\partial u}{\partial y}\frac{\partial u}{\partial x\partial y}+\left[H\left(\frac{\partial u}{\partial x}\right)^{2}\right]\frac{\partial u}{\partial y}=0 $ 且  $ f(x)\neq0, f(x,y) $

解：代入偏导有  $ \left[+g^{\prime}(x)\right]^{\prime}+(x+1)+f(x)g^{\prime}(x)=0 $ ，于是  $ \frac{f^{\prime}(x)}{1+x^{2}(x)}=-\frac{g^{\prime}(x)}{1+g^{\prime}(x)}=C_{1}\neq0 $ （因 x,y 任意性，故只能等于某常数）

不难得出  $ \lim_{x\to\infty}x\tan(c_{1}x+c_{2}) $，即  $ f(x)=-\frac{1}{c_{1}}\ln\left|\cos(c_{1}x+c_{2})\right|+C_{3} $，同理  $ g(x)=\frac{1}{c_{1}}\ln\left|\cos(c_{1}x+c_{2})\right|+C_{5} $，于是  $ u=\frac{1}{c_{1}}\ln\left|\frac{\cos(c_{1}x+c_{2})}{\cos(c_{1}x+c_{2})}\right|+C $

# 无穷级数

## 一、根无念与性质

1. 常数项级数  $ \sum_{n=1}^{\infty} u_{n} = u_{1} + u_{2} + \cdots + u_{n} + \cdots $ (u_{n} 为常数)  $ u_{n} $ 称为通项， $ u_{n} = S_{n} - S_{n-1} $  $ S_{n} = u_{1} + u_{2} + \cdots + u_{n} $ 称为部分和。若  $ \lim_{n \to \infty} S_{n} =  $ 有限数，则称  $ \sum_{n=1}^{\infty} u_{n} $ 收敛

2. 基本的敛散性质

①收敛的必要条件  $ \lim\limits_{n\rightarrow\infty}u_{n}=0 $

②敛土敛=敛 敛土散=散 散土散=不一定

③ 改变任意有限项不改变敛散性 敛散性取决于 $ n\rightarrow\infty $时的情况

3. 正项级数  $ U_{n} \geq 0 $ 收敛数列  $ \{u_{n}\} $ 收敛例： $ U_{n} \equiv 1 $

① 正项级数收敛  $ \Leftrightarrow $  $ \{S_{n}\} $ 有界. 由于  $ \{S_{n}\} $ 单调不减，则  $ \lim_{n\to\infty}S_{n}= $ 有限正数或  $ +\infty $.

②比较判别若 $ U_{n}\leq V_{n} $，则 $ U_{n} $更易敛例：正项级数 $ \frac{\infty}{n}a_{n} $收敛 $ \Rightarrow\frac{\infty}{n}a_{n}^{2} $收敛

③比值  $ \lim_{n\to\infty}\frac{U_{n+1}}{U_n}=P\left\{\begin{array}{l} <1 \\ >1 \end{array}\right. $ 收敛 根值  $ \lim_{n\to\infty}\sqrt[n]{U_n}=P\left\{\begin{array}{l} <1 \\ >1 \end{array}\right. $ 收敛 注：若  $ U_n>0 $ 且  $ \lim_{n\to\infty}\frac{U_{n+1}}{U_n}=P $ 存在，则  $ \lim_{n\to\infty}\sqrt[n]{U_n} $ 存在 = P

④无穷小比阶  $ \lim_{n\to\infty}\frac{U_{n}}{V_{n}}=A $  $ \left\{\begin{array}{l} =0  U_{n} 更危险  \\ (0,+\infty)  同致敬  \\ +\infty  U_{n} 更易散 \end{array}\right. $ 只有正项级数才能用等价无穷小判敛散（否则可以牵勒展开）

⑤积分判别 若非负连续  $ f(x) $ 单减且  $ u_{n}=f(n) $，则  $ \sum_{n=1}^{\infty} u_{n} $ 与  $ \int_{1}^{+\infty} f(x) dx $ 敛散性相同

⑥  $ n \rightarrow \infty $ 时， $ n! \sim \sqrt{2\pi n}\left(\frac{n}{e}\right)^{n} $

## 4. 交错级数  $ \frac{\infty}{n-1}(-1)^{n-1}U_{n}, U_{n}>0 $

①充分条件  $ \{u_{n}\} $ 单调不增且  $ \lim_{h\to\infty}u_{n}=0 $ ①  $ u_{n+1}-u_{n} $? O ②  $ \frac{U_{n+1}}{U_{n}} $? I ③  $ u_{n}=f(n), f'(x) $? O

②收敛和 $ S \leq u $

5. 任意项级数

① 绝对收敛： $ \lim_{n\to\infty}|u_n| $收敛 条件收敛： $ \lim_{n\to\infty}u_n $收敛但 $ \lim_{n\to\infty}|u_n| $发散

② 绝土绝 = 绝  $ \xrightarrow{反证法} $ 绝土条 = 条

条土条 = 绝/条

例1:  $ u_{n} = \frac{(V)^{n}}{n} $,  $ V_{n} = \frac{1}{n^{2}} - \frac{(V)^{n}}{n} $,  $ u_{n} + V_{n} $ 绝

例2:  $ u_{n} = \frac{(V)^{n}}{n} $,  $ V_{n} = \frac{(V)^{n}}{\sqrt{n}} $,  $ u_{n} + V_{n} $ 杂

证： $ 0 \leq |U_{n} \pm V_{n}| \leq |U_{n}| + |V_{n}| $

③条件收敛级的正项发散，负项发散。证：系=正+负，若正收敛，则负收敛，则系=|正+负|≤|正|+负收敛，矛盾。

## 二、敛散性大观

### 1. 判别结论

①设 $ \frac{\infty}{n-1}U_{n} $收敛，则：

收敛： $ \sum_{n=1}^{\infty}(u_{2n-1}+u_{2n}) $

 $$ \sum\limits_{n=1}^{\infty}(u_{n}+u_{n+1}),\sum\limits_{n=1}^{\infty}(u_{n}-u_{n+1}) $$ 

加括号更易敛，反例： $ (-1)^{m}a(a\neq0) $发散  $ \sum a_{n}=0 $ 与  $ \sum a_{n+1} $ 均收敛

不定： $ \frac{\infty}{n-1}U_{n}^{2} $  $ \star\frac{\infty}{n-1}\frac{(-1)^{n}U_{n}}{n} $

 $ \frac{\infty}{2-1}(U_{2n-1}-U_{2n}) $

 $$ \sum\limits_{n=1}^{\infty}u_{n}u_{n+1} $$ 

反例： $ \frac{\infty}{n-1}\frac{(-1)^{n}}{n}\quad\frac{\infty}{n-2}\frac{(-1)^{n}}{(n-1)n}\quad\frac{\infty}{n-1}\frac{(-1)^{n}}{n} $ 注意下标为2  $ \frac{\infty}{n-1}\frac{(-1)^{n}}{n} $

②设 $ U_{n}^{2} $收敛，则 $ \frac{U_{n}}{n} $绝对收敛.证 $ \vert\frac{U_{n}}{n}\vert\leq\frac{1}{2}(U_{n}^{2}+\frac{1}{n^{2}}) $

③ 设  $ \frac{\alpha}{n} \in (1, +\infty) $， $ \frac{\alpha}{n+1} \in (1, +\infty) $， $ \frac{2}{n+1} \in (1, +\infty) $， $ \frac{2}{n+2} \in (1, +\infty) $， $ \frac{2}{n+3} \in (1, +\infty) $， $ \frac{2}{n+4} \in (1, +\infty) $， $ \frac{2}{n+5} \in (1, +\infty) $， $ \frac{2}{n+6} \in (1, +\infty) $， $ \frac{2}{n+7} \in (1, +\infty) $， $ \frac{2}{n+8} \in (1, +\infty) $， $ \frac{2}{n+9} \in (1, +\infty) $， $ \frac{2}{n+10} \in (1, +\infty) $， $ \frac{2}{n+11} \in (1, +\infty) $， $ \frac{2}{n+12} \in (1, +\infty) $， $ \frac{2}{n+13} \in (1, +\infty) $， $ \frac{2}{n+14} \in (1, +\infty) $， $ \frac{2}{n+15} \in (1, +\infty) $， $ \frac{2}{n+16} \in (1, +\infty) $， $ \frac{2}{n+17} \in (1, +\infty) $， $ \frac{2}{n+18} \in (1, +\infty) $， $ \frac{2}{n+19} \in (1, +\infty) $， $ \frac{2}{n+20} \in (1, +\infty) $， $ \frac{2}{n+21} \in (1, +\infty) $， $ \frac{2}{n+22} \in (1, +\infty) $， $ \frac{2}{n+23} \in (1, +\infty) $， $ \frac{2}{n+24} \in (1, +\infty) $， $ \frac{2}{n+25} \in (1, +\infty) $， $ \frac{2}{n+26} \in (1, +\infty) $， $ \frac{2}{n+27} \in (1, +\infty) $， $ \frac{2}{n+28} \in (1, +\infty) $， $ \frac{2}{n+29} \in (1, +\infty) $， $ \frac{2}{n+30} \in (1, +\infty) $， $ \frac{2}{n+31} \in (1, +\infty) $， $ \frac{2}{n+32} \in (1, +\infty) $， $ \frac{2}{n+33} \in (1, +\infty) $， $ \frac{2}{n+34} \in (1, +\infty) $， $ \frac{2}{n+35} \in (1, +\infty) $， $ \frac{2}{n+36} \in (1, +\infty) $， $ \frac{2}{n+37} \in (1, +\infty) $， $ \frac{2}{n+38} \in (1, +\infty) $， $ \frac{2}{n+39} \in (1, +\infty) $， $ \frac{2}{n+40} \in (1, +\infty) $， $ \frac{2}{n+41} \in (1, +\infty) $， $ \frac{2}{n+42} \in (1, +\infty) $， $ \frac{2}{n+43} \in (1, +\infty) $， $ \frac{2}{n+44} \in (1, +\infty) $， $ \frac{2}{n+45} \in (1, +\infty) $， $ \frac{2}{n+46} \in (1, +\infty) $， $ \frac{2}{n+47} \in (1, +\infty) $， $ \frac{2}{n+48} \in (1, +\infty) $， $ \frac{2}{n+49} \in (1, +\infty) $， $ \frac{2}{n+50} \in (1, +\infty) $， $ \frac{2}{n+51} \in (1, +\infty) $， $ \frac{2}{n+52} \in (1, +\infty) $， $ \frac{2}{n+53} \in (1, +\infty) $， $ \frac{2}{n+54} \in (1, +\infty) $， $ \frac{2}{n+55} \in (1, +\infty) $， $ \frac{2}{n+56} \in (1, +\infty) $， $ \frac{2}{n+57} \in (1, +\infty) $， $ \frac{2}{n+58} \in (1, +\infty) $， $ \frac{2}{n+59} \in (1, +\infty) $， $ \frac{2}{n+60} \in (1, +\infty) $， $ \frac{2}{n+61} \in (1, +\infty) $， $ \frac{2}{n+62} \in (1, +\infty) $， $ \frac{2}{n+63} \in (1, +\infty) $， $ \frac{2}{n+64} \in (1, +\infty) $， $ \frac{2}{n+65} \in (1, +\infty) $， $ \frac{2}{n+66} \in (1, +\infty) $， $ \frac{2}{n+67} \in (1, +\infty) $， $ \frac{2}{n+68} \in (1, +\infty) $， $ \frac{2}{n+69} \in (1, +\infty) $， $ \frac{2}{n+70} \in (1, +\infty) $， $ \frac{2}{n+71} \in (1, +\infty) $， $ \frac{2}{n+72} \in (1, +\infty) $， $ \frac{2}{n+73} \in (1, +\infty) $， $ \frac{2}{n+74} \in (1, +\infty) $， $ \frac{2}{n+75} \in (1, +\infty) $， $ \frac{2}{n+76} \in (1, +\infty) $， $ \frac{2}{n+77} \in (1, +\infty) $， $ \frac{2}{n+78} \in (1, +\infty) $， $ \frac{2}{n+79} \in (1, +\infty) $， $ \frac{2}{n+80} \in (1, +\infty) $， $ \frac{2}{n+81} \in (1, +\infty) $， $ \frac{2}{n+82} \in (1, +\infty) $， $ \frac{2}{n+83} \in (1, +\infty) $， $ \frac{2}{n+84} \in (1, +\infty) $， $ \frac{2}{n+85} \in (1, +\infty) $， $ \frac{2}{n+86} \in (1, +\infty) $， $ \frac{2}{n+87} \in (1, +\infty) $， $ \frac{2}{n+88} \in (1, +\infty) $， $ \frac{2}{n+89} \in (1, +\infty) $， $ \frac{2}{n+90} \in (1, +\infty) $， $ \frac{2}{n+91} \in (1, +\infty) $， $ \frac{2}{n+92} \in (1, +\infty) $， $ \frac{2}{n+93} \in (1, +\infty) $， $ \frac{2}{n+94} \in (1, +\infty) $， $ \frac{2}{n+95} \in (1, +\infty) $， $ \frac{2}{n+96} \in (1, +\infty) $， $ \frac{2}{n+97} \in (1, +\infty) $， $ \frac{2}{n+98} \in (1, +\infty) $， $ \frac{2}{n+99} \in (1, +\infty) $， $ \frac{2}{n+100} \in (1, +\infty) $， $ \frac{2}{n+101} \in (1, +\infty) $， $ \frac{2}{n+102} \in (1, +\infty) $， $ \frac{2}{n+103} \in (1, +\infty) $， $ \frac{2}{n+104} \in (1, +\infty) $， $ \frac{2}{n+105} \in (1, +\infty) $， $ \frac{2}{n+106} \in (1, +\infty) $， $ \frac{2}{n+107} \in (1, +\infty) $， $ \frac{2}{n+108} \in (1, +\infty) $， $ \frac{2}{n+109} \in (1, +\infty) $， $ \frac{2}{n+110} \in (1, +\infty) $， $ \frac{2}{n+111} \in (1, +\infty) $， $ \frac{2}{n+112} \in (1, +\infty) $， $ \frac{2}{n+113} \in (1, +\infty) $， $ \frac{2}{n+114} \in (1, +\infty) $， $ \frac{2}{n+115} \in (1, +\infty) $， $ \frac{2}{n+116} \in (1, +\infty) $， $ \frac{2}{n+117} \in (1, +\infty) $， $ \frac{2}{n+118} \in (1, +\infty) $， $ \frac{2}{n+119} \in (1, +\infty) $， $ \frac{2}{n+120} \in (1, +\infty) $， $ \frac{2}{n+121} \in (1, +\infty) $， $ \frac{2}{n+122} \in (1, +\infty) $， $ \frac{2}{n+123} \in (1, +\infty) $， $ \frac{2}{n+124} \in (1, +\infty) $， $ \frac{2}{n+125} \in (1, +\infty) $， $ \frac{2}{n+126} \in (1, +\infty) $， $ \frac{2}{n+127} \in (1, +\infty) $， $ \frac{2}{n+128} \in (1, +\infty) $， $ \frac{2}{n+130} \in (1, +\infty) $， $ \frac{2}{n+131} \in (1, +\infty) $， $ \frac{2}{n+132} \in (1, +\infty) $， $ \frac{2}{n+133} \in (1, +\infty) $， $ \frac{2}{n+134} \in (1, +\infty) $， $ \frac{2}{n+135} \in (1, +\infty) $， $ \frac{2}{n+136} \in (1, +\infty) $， $ \frac{2}{n+137} \in (1, +\infty) $， $ \frac{2}{n+138} \in (1, +\infty) $， $ \frac{2}{n+140} \in (1, +\infty) $， $ \frac{2}{n+141} \in (1, +\infty) $， $ \frac{2}{n+142} \in (1, +\infty) $， $ \frac{2}{n+143} \in (1, +\infty) $， $ \frac{2}{n+144} \in (1, +\infty) $， $ \frac{2}{n+145} \in (1, +\infty) $， $ \frac{2}{n+146} \in (1, +\infty) $， $ \frac{2}{n+147} \in (1, +\infty) $， $ \frac{2}{n+148} \in (1, +\infty) $， $ \frac{2}{n+149} \in (1, +\infty) $， $ \frac{2}{n+150} \in (1, +\infty) $， $ \frac{2}{n+151} \in (1, +\infty) $， $ \frac{2}{n+152} \in (1, +\infty) $， $ \frac{2}{n+153} \in (1, +\infty) $， $ \frac{2}{n+154} \in (1, +\infty) $， $ \frac{2}{n+155} \in (1, +\infty) $， $ \frac{2}{n+156} \in (1, +\infty) $， $ \frac{2}{n+157} \in (1, +\infty) $， $ \frac{2}{n+158} \in (1, +\infty) $， $ \frac{2}{n+160} \in (1, +\infty) $， $ \frac{2}{n+161} \in (1, +\infty) $， $ \frac{2}{n+162} \in (1, +\infty) $， $ \frac{2}{n+163} \in (1, +\infty) $， $ \frac{2}{n+164} \in (1, +\infty) $， $ \frac{2}{n+165} \in (1, +\infty) $， $ \frac{2}{n+166} \in (1, +\infty) $， $ \frac{2}{n+167} \in (1, +\infty) $， $ \frac{2}{n+168} \in (1, +\infty) $， $ \frac{2}{n+169} \in (1, +\infty) $， $ \frac{2}{n+170} \in (1, +\infty) $， $ \frac{2}{n+171} \in (1, +\infty) $， $ \frac{2}{n+172} \in (1, +\infty) $， $ \frac{2}{n+173} \in (1, +\infty) $， $ \frac{2}{n+174} \in (1, +\infty) $， $ \frac{2}{n+175} \in (1, +\infty) $， $ \frac{2}{n+176} \in (1, +\infty) $， $ \frac{2}{n+177} \in (1, +\infty) $， $ \frac{2}{n+178} \in (1, +\infty) $， $ \frac{2}{n+179} \in (1, +\infty) $， $ \frac{2}{n+180} \in (1, +\infty) $， $ \frac{2}{n+181} \in (1, +\infty) $， $ \frac{2}{n+182} \in (1, +\infty) $， $ \frac{2}{n+183} \in (1, +\infty) $， $ \frac{2}{n+184} \in (1, +\infty) $， $ \frac{2}{n+185} \in (1, +\infty) $， $ \frac{2}{n+186} \in (1, +\infty) $， $ \frac{2}{n+187} \in (1, +\infty) $， $ \frac{2}{n+188} \in (1, +\infty) $， $ \frac{2}{n+189} \in (1, +\infty) $， $ \frac{2}{n+190} \in (1, +\infty) $， $ \frac{2}{n+191} \in (1, +\infty) $， $ \frac{2}{n+192} \in (1, +\infty) $， $ \frac{2}{n+193} \in (1, +\infty) $， $ \frac{2}{n+194} \in (1, +\infty) $， $ \frac{2}{n+195} \in (1, +\infty) $， $ \frac{2}{n+196} \in (1, +\infty) $， $ \frac{2}{n+197} \in (1, +\infty) $， $ \frac{2}{n+198} \in (1, +\infty) $， $ \frac{2}{n+199} \in (1, +\infty) $， $ \frac{2}{n+200} \in (1, +\infty) $， $ \frac{2}{n+201} \in (1, +\infty) $， $ \frac{2}{n+

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//07da9d60-fdd1-4654-8488-d4a959d34e03/markdown_4/imgs/img_in_image_box_133_782_745_1020.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A54Z%2F-1%2F%2Fe9515121d843972f9942671e972e0d6141f85a2846715e2200c6b95183910568" alt="Image" width="51%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//07da9d60-fdd1-4654-8488-d4a959d34e03/markdown_4/imgs/img_in_image_box_133_782_745_1020.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A54Z%2F-1%2F%2Fe9515121d843972f9942671e972e0d6141f85a2846715e2200c6b95183910568" alt="Image" width="51%" />

2. 欲散结论 q=0时称为反错P级数  $ \Rightarrow $ q=0时称为P级数

①  $ \sum_{n=2}^{\infty} \frac{(-1)^{n}}{p^{n} \ln q^{n}} $  $ \Rightarrow $ 绝：p=1, q>1

②  $ \sum_{n=2}^{\infty} \frac{1}{n^{p} \ln q^{n}} $  $ \Rightarrow $ 欲：p=1, q>1

③  $ \sum_{n=2}^{\infty} \frac{1}{n^{p} \ln q^{n}} $  $ \Rightarrow $ 绝：p=1, q≤1

④  $ \sum_{n=2}^{\infty} \frac{1}{n^{p} \ln q^{n}} $  $ \Rightarrow $ 欲：p=1, q≤1

⑤  $ \sum_{n=2}^{\infty} \frac{1}{n^{p} \ln q^{n}} $  $ \Rightarrow $ 欲：p=1, q≤1

⑥  $ \sum_{n=2}^{\infty} \frac{1}{n^{p} \ln q^{n}} $  $ \Rightarrow $ 欲：p=1, q≤1

</div>


</div>


②  $ \sum_{n=0}^{\infty}a^{q^{n}}(a\neq0) $  $ \left\{\begin{array}{l} 敛: |q|<1 \\  散: |q|\geq1 \end{array}\right. $ 注: |q|<1 时  $ \lim_{n\to\infty}S_{n}=\lim_{n\to\infty}a\frac{1-q^{n}}{1-q}=\frac{a}{1-q} $

### 3. 常用反例

负项无法抵消正项

 $ a_{n}=\left\{\frac{1}{2^{n}}\right\}^{n}, n $ 奇 数量级不同，可证  $ 0 \leq a_{n} < \frac{1}{n} $ 但  $ \sum_{n=1}^{\infty}(-1)^{n}a_{n} $ 发散

 $$ a_{n}=\left\{\begin{array}{l}0,n=2k\\1,n=2k-1\end{array}\right. $$ 

 $ a_{n}=-\frac{1}{n} $ (单增且有界)

## 三、幂级数

 $ (x^{n}) $ 可以视为一个基

1. 一般形式为  $ \sum_{n=0}^{\infty}U_{n}(x)=\sum_{n=0}^{\infty}a_{n}(x-x_{0})^{n}=a_{0}+a_{1}(x-x_{0})+\cdots+a_{n}(x-x_{0})^{n}+\cdots $，其中  $ a_{n}=\frac{f^{(n)}(x_{0})}{n!} $

### 2. 收敛域

①对  $ \sum_{n=0}^{\infty} a_{n} x^{n} $，若  $ \lim_{n \to \infty} \left| \frac{a_{n}}{a_{n}} \right| = \rho $ 或  $ \lim_{n \to \infty} \sqrt[n]{|a_{n}|} = \rho $，则  $ R = \frac{1}{\rho} $ 拒绝、散场注：若  $ \lim_{n \to \infty} \left| \frac{|a_{n}|}{|a_{n}|} \right| = \rho > 0 $，则  $ \lim_{n \to \infty} \sqrt[n]{|a|} = \rho $，即：能比一定能根②对  $ \sum_{n=0}^{\infty} a_{n}(x - x_{0})^{n} $，若在  $ x $ 处条件收敛，则  $ R = |x_{1} - x_{0}| $

③对  $ \Sigma u_{n}(x) $，令  $ \lim_{n\to\infty}\left|\frac{u_{n+1}(x)}{u_n(x)}\right|<1 $ 或  $ \lim_{n\to\infty}\sqrt[n]{|u_n|}<1 $，求出收敛区间  $ (a,b) $，再讨论  $ x=a,b $ 以确定收敛域

④ 提出或乘以因式  $ (x-x_{0})^{k} $ 或平移，收敛半径不变.

逐项求导收敛域可能缩小，逐项积分收敛域可能扩大，二者收敛半径不变。导小积大

### 3.幂级数 $ \rightarrow $和函数 分母除 $ x $就要讨论 $ x=0 $ 只要导积就要重新看收敛区间端点

①运算法则

 $ \sum_{n=0}^{\infty}a_{n}x^{n}+\sum_{n=0}^{\infty}b_{n}x^{n}=\sum_{n=0}^{\infty}(a_{n}\pm b_{n})x^{n} $  $ R^{n}=\min\{R_{a},R_{b}\}(R_{a}\neq R_{b}) $  $ R^{n}=\min\{R_{a},R_{b}\}(R_{a}=R_{b}) $

 $ R_{a}=R_{b} $ 时  $ R $ 可能变大，如  $ a_{n}(1+2^{n}),b_{n}(1-2^{n}) $ 有  $ R_{a}=\frac{1}{2}=R_{b}<R=1 $

 $ \sum_{n=0}^{\infty}\sum_{k=0}^{n}a_{k}b_{n}=\sum_{k=0}^{\infty}\sum_{n=k}^{+\infty}a_{k}b_{n} $ （发散+发散可能收敛）

 $ \sum_{n=0}^{\infty}a_{n}x^{n}\sum_{n=0}^{\infty}b_{n}x^{n}=\sum_{n=0}^{\infty}\left(\sum_{i=0}^{n}a_{i}b_{n-i}\right)x^{n},R=\min\{R_{a},R_{b}\} $

 $ =a_{0}b_{0}x^{0}+(a_{0}b_{1}+a_{1}b_{0})x^{1}+\cdots $ 其和为n，a的下标0~n

### ②恒等变形

例： $ \sum_{n=0}^{\infty}a_{n}x^{2n}+\sum_{n=0}^{\infty}b_{n+1}x^{2n+2}=a_{0}x^{0}+\sum_{n=1}^{\infty}a_{n}x^{2n}+\sum_{n=1}^{\infty}b_{n}x^{2n}=a_{0}+\sum_{n=1}^{\infty}(a_{n}+b_{n})x^{2n} $

只变下标：把前几项写出来 通项与下标一起变：一个+,一个-

如果只变通项：提出 $ x^{k} $

③导与积

24软先导后积  $ S(x)=\int_{a}^{x}S(t)dt+S(a) $  $ S(a)=S(x_{0})=\frac{\sqrt{2}}{2}a_{n}(x-x_{0})^{n}\bigg|_{x=x_{0}}=a_{0} $

注： $ \int_{a}^{x}S(t)dt=S(t)\bigg|_{a}^{x}=S(x)-S(a) $

先积后导  $ \left[\int S(x)dx\right]^{\prime}=S(x) $

④ 性质

幂级数的和函数在收敛域上连续

## 4. 和函数→幂级数 可能已知(1×)收敛但不在f(x)定义域内 (应取交集)

若端点处级数收敛且被展开的函数在该端点单侧连续，则此展开式在端点处也成立.

 $$ a_{n}=\frac{f^{\prime\prime}(x_{0})}{n!} $$ 

思路如下：

母为 $ \frac{1}{2n} $，则为 $ \frac{1}{2}\ln(1+x) $

 $ \ln(1+x) $族

看分母

 $$ \frac{1}{n} \rightarrow \ln(1+x) = \frac{\infty}{n-1}(-1)^{n-1} \frac{x^n}{n}, (1,1) \text{ 或 } \frac{1}{1+x} = \frac{\infty}{n-1}(-1)^{n-1} x^n \text{ 或 } \frac{1}{1-x} = \frac{\infty}{n-1} x^n (1,1) \rightarrow \arctan x = \underbrace{\frac{\infty}{n-1}}(-1)^{n-1} \cdot \frac{x^{2n+1}}{2n+1}, \left[1,1\right] \rightarrow \text{因为} (\arctan x)^{\prime} = \frac{\frac{1}{1-x^2}}{n=0}(-1)^{n-1} x^{2n+1} $$ 

 $$ (-1)^{n}\rightarrow\sin x=\frac{00}{24}(-1)^{n}\cdot\frac{x^{2n+1}}{(2n+1)!} $$ 

 $$ \cos x=\frac{\frac{a_{0}}{2^{n}}}{n=0}(-1)^{n}\frac{x^{2n}}{(2n)!} $$ 

由 $ e^{ix}=\cos x+i\sin x $得

 $$ \sin x=\frac{e^{2x}-e^{-2x}}{2i},\cos x=\frac{e^{2x}+e^{-2x}}{2} $$ 

 $$ \frac{e^{x}+e^{x}}{2}=\frac{\frac{100}{21}}{n=0}\frac{x^{2n}}{(2n)!} $$ 

省结论  $ \frac{80}{23}\frac{x^{n}}{n}=-\ln(1-x) $  $ H\leq x<1 $

## 四、傅里叶级数

1. 展开 对 T=2L 的 f(x)，若在  $ [-2, 2] $ 上可积，则

 $$ a_{n}=\frac{1}{2}\int\limits_{-1}^{2}f(x)\cos\frac{n\pi x}{2}d x,b_{n}=\frac{1}{2}\int\limits_{-1}^{2}f(x)\sin\frac{n\pi x}{2}d x,f(x)\sim\frac{a_{0}}{2}+\frac{\frac{\pi}{2}}{\pi-1}\left(a_{n}\cos\frac{n\pi x}{2}+b_{n}\sin\frac{n\pi x}{2}\right)=S(x) $$ 

①  $ i = \pi $ ② 奇延拓  $ a_{n} = 0, b_{n} = \frac{2}{2} \int_{0}^{2} f(x) \sin \frac{n \pi x}{2} dx $ ③ 偶延拓  $ a_{n} = \frac{2}{2} \int_{0}^{2} f(x) \cos \frac{n \pi x}{2} dx, b_{n} = 0 $

其中 $ \frac{a_{0}}{2}=\frac{1}{2\pi}\int_{-\pi}^{\pi}f(x)dx $为 $ \overline{f(x)} $ (直流分量)

(无第二类)

2. 欲利克雷收敛定理 对1中的 $ f(x) $，若还满足：①连续或只有有限个第一类间断点 ②至多有有限个极值点.

则 $ S(x) $处处收敛，且  $ S(x)=\left\{\begin{aligned}&\frac{f(x)}{2}+f(x)(x为连续点)\\&\frac{f(-x)}{2}+f(-x)(x为间断点)\end{aligned}\right. $ =该点的 $ \frac{左极限+右极限}{2} $

傅里叶级数的和函数  $ (x=\pm x) $

### 3、正交性 两个函数在某种度量下是相互独立的 $ \langle f,g\rangle=0 $则称k.g正交

不同频率的正弦和余弦函数在积分意义上是彼此独立的

由此证明 $ a_{n} $为什么满足

 $$ \begin{cases} \int_{-\pi}^{\pi}\cos m x\sin n x d x=0 \\ \int_{\pi}^{\pi}\cos m x\cos n x d x=\begin{cases} 2\pi & (m=n \text{或} n \text{)} \\ 0 & (m \neq n \text{或有} n \text{)} \\ \pi & (m=n \text{为自数) } \end{cases} \end{cases} $$ 

因此  $ \int_{\pi}^{\pi} f(x) \cos n x dx = \int_{\pi}^{\pi} \frac{a_{0}}{2} + \sum_{k=1}^{n} (a_{k} \cos k x + b_{k} \sin k x) \cos n x dx = \int_{\pi}^{\pi} a_{n} \cos n x \cos n x dx = a_{n} \cdot \pi $

正交性允许将任意  $ f(x) $ 投影到三角函数基上，傅里叶系数本质是投影长度： $ a_{n} = \frac{\langle f, \cos n x \rangle}{\langle \cos n x, \cos n x \rangle} $

# 无穷级数

1. 设  $ \frac{\infty}{n-1}U_{n} $ 发散，则  $ \frac{\infty}{n-1}|U_{n}| $ 发散.

证: 由  $ 2|u_{n}| \geq |u_{n} + |u_{n}| \geq 0 $. 设  $ \{u_{n}\} $ 收敛, 则  $ \lim_{n \to \infty} u_{n} $ 收敛, 矛盾.  $ ②|u_{n}| $ 收敛  $ \Rightarrow $  $ u_{n} $ 收敛的逆否命题.

注:  $ |u_{n}| \geq |u_{n}| \Rightarrow $ 发散是错的, 因为  $ u_{n} $ 不一定为正项级数, 只有正项才能比较判敛.

2. 设  $ a_{n} \leq b_{n} \leq c_{n} $ 且  $ \frac{\infty}{n-1}a_{n}, \frac{\infty}{n-1}c_{n} $ 收敛，证明： $ \sum_{n=1}^{\infty} b_{n} $ 收敛.

证： $ 0 \leq b_n - a_n \leq c_n - a_n $ 知  $ \sum_{n=1}^{\infty}(b_n - a_n) $ 收敛，故  $ \sum_{n=1}^{\infty} b_n $ 收敛

注：可证 $ \vert\Phi\vert $。由 $ -\vert u_{m}\vert\leq u_{n}\leq\vert u_{n}\vert $知 $ u_{n} $收

3. 设  $ \frac{a_{n+1}}{a_n} \leq \frac{b_{n+1}}{b_n} $ (n=1,2,\ldots, a_n > 0, b_n > 0), 证明：(1) 若  $ \sum_{n=1}^{\infty} b_n $ 收敛，则  $ \sum_{n=1}^{\infty} a_n $ 收敛 (2) 若  $ \sum_{n=1}^{\infty} a_n $ 发散，则  $ \sum_{n=1}^{\infty} b_n $ 发散

证：由  $ \frac{a_{n+1}}{b_{n+1}} \leq \frac{a_n}{b_n} $ 知  $ \left\{\frac{a_n}{b_n}\right\} \downarrow $，又  $ \frac{a_n}{b_n} \geq 0 $，故  $ \lim_{n \to \infty} \frac{a_n}{b_n} $ 存在 (记为 A) ① A > 0，显然 (1)(2) 成立 ② A = 0，则  $ \exists N > 0 $ 使  $ n > N $ 时  $ \frac{a_n}{b_n} < 1 $，即  $ 0 < a_n < b_n $，显然 (1)(2) 成立

4. 证明调和级数发散

证：反证. 设  $ n = \lim_{n \to \infty} S_n = S $. 由  $ S_{2n} - S_n = \frac{1}{n + 1} + \cdots + \frac{1}{2n} > n \cdot \frac{1}{2n} = \frac{1}{2} $ 与  $ \lim_{n \to \infty} S_{2n} - S_n = 0 $ 矛盾

### 5. 证明正项级数 $ \frac{1}{n^{p}} $在P>1时收敛

证：对  $ 0 < x \leq n $ 有  $ \frac{1}{n^{p}} \leq \frac{1}{x^{p}} $，则  $ \int_{n+1}^{n} \frac{1}{n^{p}} dx \leq \int_{n+1}^{n} \frac{1}{x^{p}} dx $，于是  $ S_{n} = 1 + \frac{1}{2^{p}} + \cdots + \frac{1}{n^{p}} \leq 1 + \int_{1}^{n} \frac{1}{x^{p}} dx = 1 + \frac{1}{p-1} - \frac{1}{(p-1)n^{p-1}} < 1 + \frac{1}{p-1} $ 即  $ \{S_{n}\} $ 有果  $ \Rightarrow $ 正项级数收敛

6.  $ a_{n}<b_{n}(n=1,2,\ldots) $， $ \sum_{n=1}^{\infty}a_{n} $ 与  $ \sum_{n=1}^{\infty}b_{n} $ 均收敛，证： $ \sum_{n=1}^{\infty}a_{n} $ 绝对收敛  $ \Leftrightarrow $  $ \sum_{n=1}^{\infty}b_{n} $ 绝对收敛

证：①由 $ b_{n}>a_{n} $知 $ c(b_{n}-a_{n}) $绝欧 $ \Rightarrow|b_{n}|=|b_{n}-a_{n}+a_{n}|\leq|b_{n}-a_{n}|+|a_{n}| $收 $ \Leftrightarrow|a_{n}|=|a_{n}-b_{n}+b_{n}|\leq|a_{n}-b_{n}|+|b_{n}| $

② $ \Rightarrow(i)a_{n}<b_{n}<0 $ 有 $ \vert a_{n}\vert=-a_{n}>-b_{n}=\frac{\vert b_{n}\vert-b_{n}}{2}>0 $ (ii) $ \vert b_{n}\vert>0 $ 有 $ \vert a_{n}\vert\geq0=\frac{\vert b_{n}\vert-b_{n}}{2} $，于是 $ \vert a_{n}\vert\geq\frac{\vert b_{n}\vert-b_{n}}{2}\geq0 $ 和  $ \frac{\vert b_{n}\vert-b_{n}}{2} $ 知 $ \vert a_{n}\vert $ 收敛  $ \Leftrightarrow-b_{n}\leq-a_{n} $ 同理

### 7. 证明交错级数中的莱布尼茨判别定理

证： $ S_{2n}=(u_{1}-u_{2})+\cdots+(u_{2n-1}-u_{2n})\Rightarrow S_{2n} $ 单增， $ S_{2n}=u_{1}-(u_{2}-u_{1})-\cdots-(u_{2n-2}-u_{2n-1})-u_{2n}\leq u_{1}=S_{2n} $ 有上界

于是  $ \lim_{n\to\infty}S_{2n}=S $ 由  $ S_{2n+1}=S_{2n}+u_{2n+1} $ 与  $ \lim_{n\to\infty}u_{2n+1}=0 $ 知  $ \lim_{n\to\infty}S_{2n+1}=S $

8. 若  $ a_{n}x^{n} $ 与  $ \frac{a_{n}}{n+1}x^{n} $ 的收敛半径分别为  $ \frac{\sqrt{5}}{3}, \frac{1}{3} $，则  $ \frac{a_{n}}{n+1}x^{n} $ 的收敛半径不一定为 5

证: 取  $ a_{n}=\left\{\frac{1}{3}, n=2k-1, n=2k, b_{n}=\left\{\begin{matrix}1, & n=2k-1 \\ 3, & n=2k\end{matrix}\right.\right. $

于是  $ R_{a}=\min\{1, \frac{\sqrt{5}}{3}\}=\frac{\sqrt{5}}{3}, R_{b}=\min\{1, \frac{1}{3}\}=\frac{1}{3} $，由  $ C_{n}=\left\{\frac{1}{(5)^{2k}}, n=2k\right. $

于是  $ R_{c}=\min\{1,5\}=1 $

注: 这说明 02 数三是错题

9. 证明： $ f(x)=\left\{\begin{aligned}&e^{-\frac{x^{2}}{2}},&x\neq0\\ &0,&x=0\end{aligned}\right. $ 的泰勒级数并不收敛于该函数本身

证: 由  $ f^{(n)}(0)=e^{-\frac{1}{x^{2}}}P_{n}(\frac{1}{x})=0 $ 知  $ S(x)=0+0x+\cdots+\frac{0}{n!}x^{n}+\cdots\rightarrow0 $ 当  $ x\neq0 $ 时  $ S(x)\neq f(x) $

注意阶导数，则  $ f(x) $ 在  $ (x_{0}-r, x_{0}+r) $ 上  $ S(x) $ 收敛于  $ f(x) \Leftrightarrow \forall x \in (x_{0}-r, x_{0}+r) $，有  $ \lim_{n \to \infty} P_{n}(x) = 0 $

#### 抽象型级数敛散性证明

1. 设  $ a_{n} = \int_{0}^{\frac{\pi}{4}} \tan^{n} x \, dx $ (1) 求  $ \sum_{n=1}^{\infty} \frac{1}{n} (a_{n} + a_{n+2}) $ (2) 证明：对  $ \forall \lambda > 0, \sum_{n=1}^{\infty} \frac{a_{n}}{n^x} $ 收敛 (1999.一)

解(1)  $ d\tan x = 1 + \tan^{2}x dx $  $ a_{n} + a_{n+1} = \int_{0}^{\frac{\pi}{4}} \tan^{n} x + \tan^{m} x dx = \int_{0}^{\frac{\pi}{4}} \tan^{n} x dt \tan x = \frac{1}{n+1}, S(n) = \frac{2}{n+1} \frac{1}{n(n+1)} = 1 - \frac{1}{n+1} = 1 $

(2)  $ 0 \leq a_{n} \frac{6a_{n}x = t}{} \int_{0}^{1} \frac{t^{n}}{1 + t^{2}} dt \leq \int_{0}^{1} t^{n} dt = \frac{1}{n+1} \leq \frac{1}{n} $ (由)亦可证出)，则  $ 0 \leq \frac{a_{n}}{n^{2}} \leq \frac{1}{n^{2m}} (\lambda > 0) $ 收敛.

2. 设  $ a_{1}=2 $,  $ a_{m+1}=\frac{1}{2}(a_{m}+\frac{1}{an}) $, 证明: (1)  $ \lim_{n\to\infty}a_n $ 存在 (2)  $ \sum_{n=1}^{\infty}\left(\frac{a_n}{a_{m+1}}-1\right) $ 收敛 (1997.)

解: (1)  $ a_{n+1} \geq 1 $ 且  $ a_{n+1} - a_n = \frac{1 - a_n^2}{2a_n} \leq 0 $ (2)  $ 0 \leq \frac{a_n - a_{n+1}}{a_{n+1}} \leq a_n - a_{n+1} $，又  $ \sum_{n=1}^{\infty}(a_n - a_{n+1}) = a_1 - a_{n+1} $，故收敛

3.  $ \sum_{n=0}^{\infty}a_{n}x^{n} $ 的收敛域为  $ (-∞,+∞) $，和函数  $ y(x) $ 满足  $ y^{n}-2xy^{1}-4y=0 $,  $ y(0)=0 $,  $ y^{1}(0)=1 $，求  $ a_{n} $,  $ y(x) $.

解: 显然  $ \left\{\begin{array}{l} a_{0}=0 \\ a_{1}=1 \end{array}\right. $  $ y'(x)=\sum_{n=1}^{\infty}n a_{n}x^{n-1}=\sum_{n=0}^{\infty}(n+1)a_{n+1}x^{n} $  $ y'(x)=\sum_{n=2}^{\infty}n(n+1)a_{n}x^{n-2}=\sum_{n=0}^{\infty}(n+1)(n+2)a_{n+2}x^{n} $

考虑到  $ -2xy^{1}=2\sum_{n=0}^{\infty}(n+1)a_{n+1}x^{n+1}=-2\sum_{n=1}^{\infty}n a_{n}x^{n} $，则  $ y^{n} $ 与 -4y 也应从  $ n=1 $ 开始。由  $ y^{n}=2a_{2}+\sum_{n=1}^{\infty}(n+1)(n+2)a_{n+2}x^{n} $ 与  $ y=\sum_{n=1}^{\infty}a_{n}x^{n} $ 得  $ 2a_{2}+\sum_{n=1}^{\infty}\left[(n+1)(n+2)a_{n+2}-2(n+3)a_{n}\right]x^{n}=0 $，故  $ a_{2}=0 $， $ a_{n+2}=\frac{2}{n+1}a_{n} $，则  $ a_{n}=0(n-2-k) $， $ a_{2k+1}=\frac{a_{2k+1}}{k}=\frac{a_{2k+3}}{k(k-1)}=\cdots=\frac{1}{k!}(n=2k+1) $。则  $ y(x)=\sum_{n=0}^{\infty}\frac{x^{2n+1}}{n!}=x e^{x^{2}} $

4. 设  $ a_{1}=a_{2}=1 $,  $ a_{n+1}=a_{n}+a_{n-1}(n\geq2,3,\ldots) $, 证明: 当  $ |x|<\frac{1}{2} $ 时,  $ \sum_{n=1}^{\infty}a_{n}x^{n+1} $ 收敛, 并求其和函数

解:  $ a_{n}>0 $,  $ a_{n+1} \geq a_{n} $ 由  $ \left|\frac{a_{n+1}x^{n}}{a_{n}x^{n+1}}\right| = \frac{a_{n} + a_{n+1}}{a_{n}} |x| \leq 2 |x| < 1 $ 知收敛。由  $ S(x) = 1 + x + \sum_{n=3}^{\infty} a_{n} x^{n+1} = 1 + x + \sum_{n=3}^{\infty} a_{n-2} x^{n+1} + \sum_{n=3}^{\infty} a_{n-1} x^{n+1} = 1 + x + x^{2} S(x) + \left[x(S(x-1)) \right] \Rightarrow S(x) = \frac{1}{1-x-x^{2}} $

5.  $ f(x) $ 可导， $ f(0)=1 $， $ 0 < f'(x) < \frac{1}{2} $。设数列  $ \{x_n\} $ 满足  $ x_{n+1} = f(x_n) $ ( $ n=1,2,\ldots $)。证明：(1) 级数  $ \sum_{n=1}^{\infty}(x_{n}-x_n) $ 绝对收敛  $ \sum_{n=0}^{\infty}(x_n|_{x_n+1})x_n $ 存在且  $ 0 < \lim_{x_n \to +\infty} x_n < 2 $

证: (1)  $ \left|x_{n+1}-x_n\right|\leq\frac{1}{2^{n+1}}\left|x_2-x_1\right| $ (2)  $ \lim_{n\to\infty}x_{n+1}-x_1=S $ 存在  $ \Rightarrow\lim_{n\to\infty}x_n $ 存在 ① 设  $ g(x)=x-f(x) $，由  $ g(0)=-1, g(2)=2-f(2) $

 $ =1-\left[f(2)-f(0)\right]=1-2f'(1)>0 $ 且  $ g'(x)=-f'(x)>0 $ 知  $ \exists x_0\in(0,2) $ 为唯一零点 ②  $ \lim_{n\to\infty}x_n=-1=\lim_{n\to\infty}\left[-f(x_{n+1})-f(0)\right] $

 $ \lim_{n\to\infty}x_{n+1}-f(3) $ 故  $ 0<\lim_{n\to\infty}x_n-1<\frac{1}{2}\lim_{n\to\infty}x_{n-1} $

设  $ a_{1}=a_{2}=1 $,  $ a_{n+1}=a_{n}+a_{n-1}(n=3,5) $，证明： $ \sum_{n=1}^{\infty}anx^{n+1} $ 在  $ (x)<\frac{1}{2} $ 处收敛，并求其和函数

设  $ a_{0}=1, a_{1}=0, a_{n+1}=\frac{1}{n+1}(na_{n}+a_{n-1})(n=1,3,5) $ 证明： $ \sum_{n=2}^{\infty}anx^{n} $ 的收敛半径不小于

证：(1) $ a_{n}\uparrow $，故 $ a_{n+1}<2a_{n}<\cdots<2^{n-1}a_{2}=2^{n-1} $，故 $ \left|a_{n}x^{n-1}\right|<2^{n-2}\left|x^{n-1}\right|=\frac{1}{2}\left(2x\right)^{n-1} $，而 $ \frac{a_{n}}{a_{n-1}}(2x)^{n-1} $在 $ [2x�] $绝对收敛， $ S(x)=\frac{1}{1-x^{2}} $， $ |x|<\frac{1}{2} $

(2) 数知知  $ 0\leq a_{n}\leq1 $，故  $ \frac{a_{n}}{a_{n-1}}|x^{n}|\leq\sum_{n=1}^{\infty}|x^{n}| $  $ \Rightarrow $  $ R<1 $

 $ S(x)=\frac{e^{-x}}{1-x} $， $ |x|<1 $

7.  $ f''(x) > 0 $，令  $ x_{n} = f(n) $ ( $ n = 1, 2, \ldots $)， $ x_{1} < x_{2} $，证明  $ \{x_{n}\} $ 必发散

证： $ x_{n+1}-x_n=f(n+1)-f(n)=f^{\prime}(x_n)>f(x_{n-1})>\cdots>f(x_n) $，则 $ x_{n+1}=x_n+\sum_{k=1}^{n}(x_{k+1}-x_k)>x_1+n+f(x_1)=x_1+n(x_2-x_1)\rightarrow+\infty $

②  $ f(k+1) > f(k) + f'(k) $ 知  $ f(n+1) > f(2) + \sum_{k=2}^{120} f'(k) > f(2) + (n-2)f'(2) $，又  $ f(1) > f(2) + f'(2)(1-2) + 0 + f(2) > f(2) - f'(2) = x_2 - x_1 > 0 $

8.  $ 0 \leq a_{n+1} \leq a_n + b_n $ ( $ n \in \mathbb{N}_+ $)，证明： $ \sum_{n=1}^{\infty} b_n $ 收敛  $ \Rightarrow \{a_n\} $ 收敛

证：记  $ S = \sum_{k=1}^{n} b_k $，则  $ b_n = S_n - S_{n-1}(n \geq 2) $。 $ a_{n+1} - S_n \leq a_n - S_{n-1} $ 即  $ \{a_n - S_{n-1}\} \downarrow $ 并且  $ a_n \geq 0 $， $ S_{n-1} $ 有界  $ \Rightarrow \{a_n - S_{n-1}\} $ 有下界  $ \Rightarrow $ 收敛

于是  $ \lim_{n \to \infty} a_n = \lim_{n \to \infty} [(a_n - S_{n-1}) + S_{n-1}] $ 存在  $ \Rightarrow \{a_n\} $ 收敛

注：反之不成立，如  $ a_n = \frac{1}{n} $， $ b_n = 1 $ （对  $ b_n $ 上界未作限制）

## 9.(19.数三) $ \sum_{n=1}^{100}n\ln n $ 绝敛， $ \sum_{n=1}^{100}\frac{V_{n}}{n} $ 条敛．讨论 $ \sum_{n=1}^{100}(U_{n}+V_{n}) $， $ \sum_{n=1}^{100}U_{n}V_{n} $ 的敛散性

解: (1) 取  $ U_{n} = \frac{1}{n^{3}} $,  $ V_{n} = (-1)^{n} $ 知  $ U_{n} + V_{n}) $ 散. 取  $ U_{n} = \frac{1}{n^{3}} $,  $ V_{n} = \frac{(-1)^{n}}{n^{2}n} $ 知  $ U(u_{n} + v_{n}) $ 收敛. 故不能确定

②对 $ \frac{t_{0}}{n+1}U_{n}x^{n} $导，得 $ \frac{t_{0}}{n+1}U_{n}x_{n}^{n-1} $，在 $ x=1 $收敛，由导小积大，故 $ \frac{t_{0}}{n+1}U_{n}x^{n} $在 $ x=1 $处必收敛。同理对 $ \frac{t_{0}}{n+1}V_{n}x^{n+1} $积，得 $ \sum_{n=1}^{+\infty}\frac{V_{n}}{n}x^{n} $，同理知 $ x=1 $不一定在收敛域内(条纹或发散)。于是 $ C(u_{n}+1,u_{n}) $条纹或发散

(2) 由  $ \lim \frac{V_{n}}{n}=0 $ 知  $ n>NB $ 时  $ \left|\frac{V_{n}}{n}\right|<1 $，即  $ \left|u_{n}V_{n}\right|=\left|n u_{n}\cdot\frac{V_{n}}{n}\right|<\left|n u_{n}\right| $ 绝敛

#### 注： $ \sum_{k=1}^{+\infty}a_{n} $ 欲  $ \Rightarrow $  $ \sum_{n=1}^{+\infty}\frac{a_{n}}{n} $ 敛.  $ \sum_{n=1}^{+\infty}a_{n} $ 散  $ \Rightarrow $  $ \sum_{n=1}^{+\infty}na_{n} $ 散

10.(02数一改)设 $ u_{n}\neq0 $ (1) $ \lim_{n\to\infty}\frac{n}{u_{n}}=1 $，判断 $ \sum_{n=1}^{\infty}(-1)^{n-1}\left(\frac{1}{u_{n}}+\frac{1}{u_{n+1}}\right) $， $ \sum_{n=1}^{\infty}\frac{(-1)^{n}}{u_{n}} $的敛散性 (2) $ \lim_{n\to\infty}\frac{u}{u_{n}}=0 $，判断 $ \sum_{n=1}^{\infty}\frac{(-1)^{n}}{u_{n}} $的敛散性

解：(1)(i) 由  $ \left|a_{n}\right|=\left|\frac{1}{a_{n}}+\frac{1}{a_{n+1}}\right|\geq\frac{1}{a_{n}} $ 且  $ \frac{1}{a_{n}}\sim\frac{1}{n} $ 知发散. 又  $ S_{n}=\frac{1}{u_{1}}+(-1)^{\frac{n+1}{u_{n+1}}}=\frac{1}{u_{1}} $ 知条件收

(ii) 取  $ U_{n}=n $ 时收敛. 取  $ U_{n}=n\left[1+\frac{(-1)^{n}}{\ln n}\right] $ 时  $ a_{n}=\frac{(-1)^{n}}{n}\frac{1}{1+\frac{(-1)^{n}}{n}}=\frac{(-1)^{n}}{n}\left[1-\frac{(-1)^{n}}{\ln n}+O\left(\frac{1}{n^{2}}\right)^{2}\right]=\frac{(-1)^{n}}{n}-\frac{1}{n\ln n}+O\left(\frac{1}{n\ln^{2}n}\right) $ 发散，故不能判定

(2) 取  $ u_{n}=n\ln n $ 时收敛. 取  $ u_{n}=n\sqrt{\ln n}\left[1+\frac{(-1)^{n}}{\sqrt{\ln n}}\right] $ 时,  $ a_{n}=\frac{(-1)^{n}}{n\sqrt{\ln n}}\left[1-\frac{(-1)^{n}}{\sqrt{\ln n}}+O\left(\frac{1}{\ln n}\right)\right]=\frac{(-1)^{n}}{n\sqrt{\ln n}}-\frac{1}{n\ln n}+O\left(\frac{1}{n\ln^{2}n}\right) $ 发散, 故不能判定

11.(91·数三)  $ 0 \leq a_{n} < \frac{1}{n} (n=1,2,\ldots) $，则肯定收敛的是() A. $ \sum_{n=1}^{+\infty}a_{n} $ B. $ \sum_{n=1}^{+\infty}(-1)^{n}a_{n} $ C. $ \sum_{n=1}^{+\infty}\sqrt{a_{n}} $ D. $ \sum_{n=1}^{+\infty}(-1)^{n}a_{n}^{2} $

解. 取  $ a_{n}=\frac{1}{2n} $ 则 A、C 错. 取  $ a_{n}=\left\{\frac{0}{n},\frac{n^{2}}{n^{2}+1}\right\} $ 知 B 错. 由  $ \vert4n\vert=a_{n}^{2}<\frac{1}{n^{2}} $ 和 D 绝

12.(20.数一)R是 $ a_{n}x^{n} $的收敛半径，当 $ \frac{a_{n}}{n+1}a_{2n}x^{2n} $发散时，证明： $ \vert\sqrt{2}\vert\geq R $

证： $ |x|<R $ 时  $ a_{n}x^{n} $ 绝敛  $ \Rightarrow a_{2n}x^{2n} $ 敛，逆命题： $ a_{2n}x^{n} $ 散  $ \Rightarrow |x| \geq R $

注 $ ^{8} $  $ a_{2n}x^{2n} $ 收敛半径  $ R_{1} $ 满足  $ R_{1} \geq R $

# 无穷级数

1. (1991.一) 将  $ f(x)=2+|x| $ ( $ 1 \leq x \leq 1 $) 展开成以2为周期的傅里叶级数，并由此求  $ \frac{\infty}{n+1} \frac{1}{n^2} $.

解:  $ Q_{0}=5, Q_{n}=2\int_{0}^{1}(24x)\cos n\pi x dx=\frac{2}{n^{2}\pi^{2}}\left[(-1)^{n}-1\right], $ 则  $ f(x)=\frac{5}{2}-\frac{4}{n^{2}}\cdot\frac{\infty}{\pi^{2}}\cdot\frac{\cos(2n+1)x}{(2n+1)^{2}} $，令 x=0 得  $ \frac{\frac{\infty}{23}}{n=0}\cdot\frac{1}{(2n+1)^{2}}=\frac{\pi^{2}}{8} $

注意到： $ \frac{\Delta x}{n-1}\frac{1}{n^{2}}=\frac{\Delta x}{n-1}\frac{1}{(2n+1)^{2}}+\frac{\Delta x}{n-1}\frac{1}{(2n)^{2}}=\frac{\Delta x}{n-1}\frac{1}{(2n+1)^{2}}+\frac{1}{4}\frac{\Delta x}{n-1}\frac{1}{n^{2}} $，故 $ S=\frac{4}{3}\cdot\frac{\pi^{2}}{8}=\frac{\pi^{2}}{6} $

2. 判断软散性 (1)  $ \sum_{n=1}^{\infty}\frac{1}{n^{1+\frac{1}{n}}} $ (2)  $ \sum_{n=1}^{\infty}\int_{n\pi}^{(m+1)\pi}\frac{\sin x}{\sqrt{x}}dx $ (3)  $ \sum_{n=2}^{\infty}\frac{1}{n^{1+\frac{1}{\sqrt{n+n}}}} $ (4) (22-数-改) $ \frac{n!}{n^n}e^n $

解(1)  $ \lim_{n\to\infty}\frac{n^{k+1}}{n}=\lim_{n\to\infty}n^{\frac{1}{k}}=1 $，由奇函数发散

(2)  $ \left\{\begin{array}{l} u_{n}>0 \\ u_{n}<0 \end{array}\right. $ (有) 故为交错. ①  $ 0 \leq |u_{n}| \leq \int_{n\pi}^{a+y\pi} \frac{dx}{\sqrt{x}} = 2\left[\sqrt{(n+y)\pi} - \sqrt{n\pi}\right] \rightarrow 0 $ ②  $ |u_{n}| > \int_{n\pi}^{a+y\pi} \frac{\sin x}{\sqrt{x+\pi}} dx = \int_{(n+y)\pi}^{a+y\pi} \frac{|\sin t|}{\sqrt{t}} dt = |u_{n+1}| $ 知收

(3)  $ U_{n} = \frac{1}{ne^{\sqrt{2n}}} \sim \frac{1}{xe^{\sqrt{2k}}} = f(x) $ (f(x)  $ \geq 0 $,  $ \downarrow $), 而  $ \int_{2}^{+\infty} \frac{1}{x e^{\sqrt{2k}}} dx = \int_{\sqrt{m2}}^{+\infty} \frac{2t dt}{e^{t}} = 2 (\sqrt{m2} + ye^{-\sqrt{m2}}) $ 知收敛

(4) 设  $ e_{n} = (1 + \frac{1}{n})^{n} $， $ \lim_{n \to \infty} e_{n} = e $ 且  $ e_{n} $ 故  $ e_{n} < e $。则  $ \frac{U_{m}}{U_{n}} = \frac{e}{e_{n}} > 1 $ 故  $ u_{n}\uparrow $， $ \lim_{n \to \infty} u_{n} \neq 0 $ 或由  $ n! \sim \sqrt{2\pi n} $ ( $ \frac{n}{e} $) 知发散

## 3. 求和函数 (1)  $ \sum_{n=1}^{\infty} n^{2}x^{n} $

解：(1)①直接展  $ S(x)=x\left(\sum_{n=1}^{\infty}n x^{n}\right)=x\left[x\left(\sum_{n=1}^{\infty}x^{n}\right)^{1}\right]^{\prime}=x\left[x\left(\frac{1}{1-x}-1\right)^{\prime}\right]^{\prime}=\frac{x(x+1)}{(1-x)^{3}} $

 $$ n^{2}=n(n-1)+n S(x)=\sum_{n=2}^{10}n(n-1)x^{n}+\sum_{n=1}^{\infty}n x^{n}=x^{2}(\frac{1}{1-x}-1-x^{1})+x(\frac{1}{1-x}-1)=\frac{x+x^{2}}{(1-x)^{3}} $$ 

③正推考虑基本形式： $ \sum_{n=0}^{\infty}x^{n}=\frac{1}{1-x} $，导： $ \sum_{n=1}^{\infty}nx^{n+1}=\frac{1}{(1+x)^{2}} $，即 $ \sum_{n=1}^{\infty}nx^{n}=\frac{x}{(1+x)^{2}} $，导： $ \sum_{n=1}^{\infty}n^{2}x^{n+1}=\frac{1+x}{(1+x)^{2}} $，即 $ S(x)=\frac{x(1+x)}{(1+x)^{3}} $

4. 将  $  f(x) = \frac{\sum_{n=0}^{\infty} (-1)^{n} x^{2n+1}}{4^{2n}(2n+1)!}  $ 展开成  $  x-1  $ 的幂级数 (2) 将  $  f(x) = \arctan \frac{1}{x}  $ 展开为  $  x  $ 的幂级数

解：收敛域  $  (-\infty, +\infty)  $， $  f(x) = 4 \cdot \sum_{n=0}^{\infty} (-1)^{n} \frac{\left(\frac{1}{4}\right)^{2n+1}}{(2n+1)!} = 4 \sin \frac{1}{4} = 4 \sin \frac{1}{4} \cos \frac{1}{4} + 4 \cos \frac{1}{4} \sin \frac{1}{4} = 4 \sin \frac{1}{4} + \sum_{n=0}^{\infty} (-1)^{n} (x-1)^{2n+1}  $

(2)  $  f(x) = \frac{1}{x^{2n}}  $， $  f(x) = \frac{\pi}{4} + \sum_{n=0}^{\infty} \frac{(-1)^{n} x^{2n+1}}{2n+1}  $， $  x \in [-1,1)  $  $  x = -1  $ 都收敛，但  $  x = 1  $ 不在定义域内

5 偶函数  $ f(x)=\left\{\begin{array}{l}x,0\leq x\leq\frac{1}{2}\\2-2x,\frac{1}{2}<x\leq1\end{array}\right. $, T=2.  $ x\in[-3,-\frac{5}{2}] $ 时  $ S(x)= $

解： $ x\in(-3,-\frac{8}{2}) $时， $ \frac{1}{2}\leq-x-2\leq1 $， $ S(x)=S(-x-2)=f(-x-2)=2x+6 $，再考虑端点， $ S(-3)=f(1)=0 $， $ S(-\frac{5}{2})=f(\frac{1}{2})=\frac{\frac{1}{2}+1}{2}=\frac{3}{4} $， $ \frac{2x+6}{3} $， $ -3\leq x<-\frac{2}{2} $

6.  $ \sum_{n=1}^{\infty} u_{n}(x) $ 的部分和为  $ S_{n}(x)=\left\{\begin{array}{l}n, \quad 0 < x < \frac{1}{n} \\ 0, \quad \text{其他}\end{array}\right. $，记  $ a=\int_{0}^{1} \sum_{n=1}^{\infty} u_{n}(x) dx $， $ b=\sum_{n=1}^{\infty} \int_{0}^{1} u_{n}(x) dx $，求  $ a, b $

解:  $ S(x)=\lim_{n\to\infty}\frac{S(x)}{n}\equiv0 $, 则  $ a=\int_{0}^{1}S(x)dx=0 $,  $ b=\lim_{n\to\infty}\left(\sum_{k=1}^{n}\int_{0}^{1}U_{k}(x)dx\right)=\lim_{n\to\infty}\left(\int_{0}^{1}\sum_{k=1}^{n}(u_{k}(x))dx\right)=\lim_{n\to\infty}\int_{0}^{\frac{1}{n}}n dx=1 $

7. 当  $ |x| < 1 $ 时， $ \sum_{n=1}^{\infty}\left(1+\frac{1}{2!}+\frac{1}{3!}+\cdots+\frac{1}{n!}\right)x^{n}= $ ___

解： $  S(x) = x + \left(1 + \frac{1}{2}\right)x^{2} + \left(1 + \frac{1}{2!} + \frac{1}{3!}\right)x^{3} + \cdots = (e^{x})_{n} + \sum_{n=2}^{\infty} \frac{x^{n}}{(n-1)!} + \sum_{n=3}^{\infty} \frac{x^{n}}{(n-1)!} = (e^{x}-1) + x(e^{x}-1) + x^{2}(e^{x}-1) = (e^{x}-1)(1 + x + x^{2}) = \frac{e^{x}-1}{1-x}  $

注：注意到每项都必有 $ (x+\frac{1}{21})x^{2}+\frac{1}{31}x^{3}+\cdots $可分解 $ S(x)=(x+\frac{1}{21})x^{2}+\frac{1}{31}x^{3}+\cdots $  $ (1+x+x^{2}+\cdots) $

8.  $ (-1)^{n} $ (1)  $ \sum_{n=2}^{+\infty}\frac{(-1)^{n}}{n+(-1)^{n}} $ 收敛性 (2) (2000. 数一)  $ \sum_{n=1}^{+\infty}\frac{1}{3^{n}+(-2)^{n}}\cdot\frac{x^{n}}{n} $ 收敛域 (3)  $ \sum_{n=1}^{+\infty}\frac{(3+(-1)^{n})^{n}}{n}x^{n} $ 的收敛半径

解：(1)①  $ S_{2n} = \sum_{k=1}^{+\infty} \left( \frac{(-1)^{2k}}{2k+(-1)^{2k}} + \frac{(-1)^{2k+1}}{2k+1+(-1)^{2k+1}} \right) = \sum_{k=1}^{+\infty} \left( \frac{1}{(2k+1)} - \frac{1}{2k} \right) $ 收敛，又由  $ \lim_{n \to \infty} U_{2n+1} = 0 $ 和  $ S_{2n+1} $ 收敛，故收敛

②  $ U_{n} = \frac{(-1)^{n}}{n \left[1 + \frac{(-1)^{n}}{n}\right]} = \frac{(-1)^{n}}{n} \left[1 - \frac{(-1)^{n}}{n} + O\left(\frac{1}{n^{2}}\right)\right] = \frac{(-1)^{n}}{n} - \frac{1}{n^{2}} + O\left(\frac{1}{n^{2}}\right) $ 收敛

(2)  $ P = \lim_{n \to \infty} \frac{n}{n+1} \cdot \frac{3^n + (-2)^n}{2^{n+1} + (-2)^{n+1}} = \frac{1}{3} \Rightarrow R = 3 $.  $ x = 3 $ 时， $ U_n = \frac{1}{n} \cdot \frac{1}{1 + \left(\frac{2}{3}\right)^n} \sim \frac{1}{n} $ 发散.  $ x = -3 $ 时， $ U_n = \frac{(-3)^n}{3^n + (-2)^n} \cdot \frac{1}{n} $

 $ = \frac{(-3)^{n}+2^{n}-2^{n}}{3^{n}+(-2)^{n}} \cdot \frac{1}{n} = \frac{(-1)^{n}}{n} - \frac{2^{n}}{3^{n}+(-2)^{n}} \cdot \frac{1}{n} = \frac{(-1)^{n}}{n} - \frac{1}{1+(-\frac{2}{3})^{n}} \cdot \frac{1}{n} \cdot (\frac{2}{3})^{n} $ 而  $ \frac{1}{n} \cdot (\frac{2}{3})^{n} $ 收敛，故收敛域  $ [-3, 3) $

(3) 偶项:  $ \frac{4^{2n} \times 2^{2n}}{2n} $，奇项:  $ \frac{2^{2n+1}}{2n-1} \times 2^{n+1} $，则  $ R_{1} = \frac{1}{4} $， $ R_{2} = \frac{1}{2} $，故  $ R = \min\{R_{1}, R_{2}\} = \frac{1}{4} $

9. (4数一) 若  $ \int_{0}^{\pi}(x-a\cos x-b\sin x)^{2}dx=\min_{a,b\in\mathbb{R}}\left\{\int_{\pi}^{\pi}(x-a\cos x-b\sin x)^{2}dx\right\} $，则  $ a,\cos x+b,\sin x= $

① 当  $ a_{k}=\frac{1}{\pi}\int_{k}^{\pi}(x)\cos xdx, b_{k}=\frac{1}{\pi}\int_{\pi}^{\pi}(x)\sin xdx $ 时 (为傅里叶系数)， $ \ln=\left[\int_{k}^{\pi}\left(\frac{1}{x}-S_{n}(x)\right)^{2}dx\right] $ 最小， $ \sin_{n}=\frac{a_{n}}{2}+a_{n}\cos x+b_{n}\sin x $

②  $ I=\frac{2\pi^{3}}{3}+\pi(a^{2}+b^{2}-4b) $，故  $ \left\{\frac{a=0}{b=2}\right. $

③  $ \frac{\partial f(a,b)}{\partial a}=\int_{\pi}^{\pi}\left[-2(x-a\cos x-b\sin x)\right]\cos xdx=2a\pi $

 $ \frac{\partial f(a,b)}{\partial b}=2b\pi-4\pi $

10.  $ \sum_{n=1}^{\infty}a_{n}x^{n} $ 在 x=-2 处条件收敛，求  $ \sum_{n=1}^{\infty}a_{2n}x^{n} $ 的收敛半径

解：考虑  $ \frac{5}{n+1}a_{n}x^{2n} $ 有  $ R_{1} \geq R = 2 $ 于是  $ R_{2} = R_{1}^{2} \geq 4 $ 即  $ [4, +\infty) $

# 空间几何

#### 一向量

1. 数量积  $ \overrightarrow{a} \cdot \overrightarrow{b} = |\overrightarrow{a}| |\overrightarrow{b}| \cos\theta = a_{1}b_{1} + a_{2}b_{2} + a_{3}b_{3} $  $ \overrightarrow{a} \perp \overrightarrow{b} \Leftrightarrow \theta = \frac{\pi}{2} \Leftrightarrow \overrightarrow{a} \cdot \overrightarrow{b} = 0 $

2. 投影  $ P_{r_i} \over \overrightarrow{a} = \frac{\overrightarrow{a} \cdot \overrightarrow{b}}{|\overrightarrow{b}|} $ 称为  $ \overrightarrow{a} $ 在  $ \overrightarrow{b} $ 上的投影  $ \rightarrow |a| \cos \theta $

3. 向量积  $ \overrightarrow{a} \times \overrightarrow{b} = |\overrightarrow{a}_{1} \overrightarrow{b}_{2}| \overrightarrow{a}_{3}|\overrightarrow{a}_{4} $ 口的面积

 $ \overrightarrow{a} // \overrightarrow{b} \Leftrightarrow \theta = 0 $ 或  $ \pi \Leftrightarrow \frac{a_{1}}{b_{1}} = \frac{a_{2}}{b_{2}} > \frac{a_{3}}{b_{3}} $  $ \Leftrightarrow \overrightarrow{a} \times \overrightarrow{b} = \overrightarrow{0} $

4. 混合积  $ [\overrightarrow{a} \overrightarrow{b} \overrightarrow{c}] = (\overrightarrow{a} \times \overrightarrow{b}) \cdot \overrightarrow{c} = \begin{vmatrix} a_{1} & a_{2} & a_{3} \\ a_{1} & a_{2} & b_{1} \\ c_{1} & c_{2} & c_{3} \end{vmatrix} \rightarrow $ 的积

三向量共面  $ \Leftrightarrow (\overrightarrow{a} \times \overrightarrow{b}) \cdot \overrightarrow{c} = 0 $ (线性相关)  $ \Leftrightarrow $ 不异面

5. 单位向量  $ \overrightarrow{a}^{0} = \frac{\overrightarrow{a}}{|\overrightarrow{a}|} = (\cos\alpha, \cos\beta, \cos\gamma) $  $ \cos\alpha = \frac{x}{\sqrt{x^{2}+y^{2}+z^{2}}} $,  $ \cos\beta = \frac{y}{\sqrt{x^{2}+y^{2}+z^{2}}} $,  $ \cos\gamma = \frac{z}{\sqrt{x^{2}+y^{2}+z^{2}}} $.  $ \cos^{2}\alpha + \cos^{2}\beta + \cos^{2}\gamma = 1 $

6. 两直线相交共面 三直线相交共面 若  $ \angle A, \angle B $ 相交，则  $ [\overrightarrow{e}_{A}, \overrightarrow{e}_{B}, \overrightarrow{M N}] = 0 $ (M, N 为  $ \angle A, \angle B $ 上两点)

## 二、直线与平面

1. 直线

定直线的二要素：方向向量 $ ^{2} $，点 $ P_{0} $

①一般式  $ \left\{\begin{array}{l} A x+B y+C z+D_{1}=0 \\ A_{2}x+B_{2}y+C_{2}z+D_{2}=0 \end{array}\right. $

 $$ \overrightarrow{e}=\overrightarrow{n_{1}}\times\overrightarrow{n_{2}} $$ 

② 点向式  $ \frac{x-x_{0}}{2}=\frac{y-y_{0}}{m}=\frac{z-z_{0}}{n} $  $ \overrightarrow{t}=(2,m,n) $

③参数式  $ \left\{\begin{array}{l} x=x_{0}+2t \\ y=y_{0}+mt \\ z=z_{0}+nt \end{array}\right. $

④两点式  $ \frac{x-x_{1}}{x_{2}-x_{1}}=\frac{y-y_{1}}{y_{2}-y_{1}}=\frac{z-z_{1}}{z_{2}-z_{1}} $

2. 平面

定平面的二要素：法向量 $ \overrightarrow{n} $，点P

①一般式  $ Ax + By + Cz + D = 0 $  $ \overrightarrow{n} = (A, B, C) $

②点法式  $ A(x-x_{0})+B(y-y_{0})+C(z-z_{0})=0 $  $ \overrightarrow{n}=(A,B,C) $

③ 三点式  $ \begin{cases} x-x_{1} & y-y_{1} & z-z_{1} \\ x-x_{2} & y-y_{2} & z-z_{2} \\ x-x_{3} & y-y_{3} & z-z_{3} \end{cases} = 0 $ (混合积)

④截矩式  $ \frac{x}{a} + \frac{y}{b} + \frac{z}{c} = 1 $

⑤平面束方程  $ A_{1}x + B_{1}y + C_{1}z + D_{1} + \lambda (A_{2}x + B_{2}y + C_{2}z + D_{2}) = 0 $ (不含  $ \pi_{2} $) 表示过交线的平面

### 3. 夹角  $ [0,\frac{\pi}{2}] $

算 $ \frac{|\overrightarrow{n_{1}}\cdot\overrightarrow{n_{2}}|}{|\overrightarrow{n_{1}}||\overrightarrow{n_{2}}|} $，同类为 $ \cos\theta $，异类为 $ \sin\theta $

### 4. 平行与垂直

 $ \frac{A_{1}}{A_{2}}=\frac{B_{1}}{B_{2}}=\frac{C_{1}}{C_{2}}\Leftrightarrow $ 同类平行，异类垂直  $ A_{1}A_{2}+B_{1}B_{2}+C_{1}C_{2}=0\Leftrightarrow $ 同类垂直，异类平行

5. 距离

①三维点线  $ d=\frac{|\overrightarrow{c}\times\overrightarrow{M_{1}M_{0}}|}{|\overrightarrow{c}|}=\frac{\left|\frac{2}{2}\overrightarrow{c}\cdot\overrightarrow{M_{1}M_{0}}\right|}{\sqrt{2^{2}+m^{2}+m^{2}}} $  $ M(x_{1},y_{1},z_{1}) $ 到  $ L:\frac{x-x_{0}}{2}=\frac{y-y_{0}}{m}=\frac{z-z_{0}}{n} $ 注： $ S_{\square}=|\overrightarrow{c}\times\overrightarrow{M_{1}M_{0}}|=|\overrightarrow{c}|\cdot d $

②二维点线  $ d=\frac{|Ax_{0}+By_{0}+C|}{\sqrt{A^{2}+B^{2}}} $  $ P(x_{0},y_{0}) $ 到  $ L:Ax+By+C=0 $

③ 点面  $ d=\frac{(A X_{0}+B Y_{0}+C Z_{0}+D)}{\sqrt{A^{2}+B^{2}+C^{2}}} $  $ P(X_{0},Y_{0},Z_{0}) $ 到  $ \Pi: A X+B Y+C Z+D=0 $ 注： $ d=\frac{\sqrt{P_{0}^{2}-n^{2}}}{1-1}=\frac{(A(x-x_{0})+B(y-y_{0})+C(z-z_{0}))}{\sqrt{A^{2}+B^{2}+C^{2}}} $

④异面直线 $ d=\frac{|\overrightarrow{e_{1}}\times\overrightarrow{e_{2}}|\cdot\overrightarrow{M_{1}M_{2}}|}{|\overrightarrow{e_{1}}\times\overrightarrow{e_{2}}|} $ 注： $ (\overrightarrow{e_{1}}\times\overrightarrow{e_{2}})\cdot\overrightarrow{M_{1}M_{2}}=0 $ 时 $ L_{1},L_{2} $ 共面

①③不同是因为①:  $ \vert\overrightarrow{P_{1}P_{0}}\vert\sin\langle\overrightarrow{P_{1}P_{0}},\overrightarrow{e}\rangle=\frac{\vert\overrightarrow{P_{1}P_{0}}\times\overrightarrow{S}\vert}{\vert\overrightarrow{S}\vert} $ ③:  $ \vert\overrightarrow{P_{1}P_{0}}\vert\sin\langle\overrightarrow{P_{1}P_{0}},\overrightarrow{T}\rangle=\vert\overrightarrow{P_{1}P_{0}}\vert\vert\cos\langle\overrightarrow{P_{1}P_{0}},\overrightarrow{x}\rangle=\vert\overrightarrow{P_{1}P_{0}}\vert\vert\frac{\overrightarrow{P_{1}P_{0}}\cdot\overrightarrow{x}}{\vert\overrightarrow{P_{1}P_{0}}\vert\vert\overrightarrow{P_{1}}\vert} $ KOKUYO

## 三、曲线与曲面

### 1. 二次曲面

椭圆球面 $ \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}+\frac{z^{2}}{c^{2}}=1 $

都有圆抛物面 $ \frac{x^{2}}{2p}+\frac{y^{2}}{2q}=z $

都有圆锥面 $ \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=\frac{z^{2}}{c^{2}} $

单叶双曲面  $ \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}-\frac{z^{2}}{c^{2}}=1 $

双叶双曲面  $ \frac{x^{2}}{a^{2}} - \frac{y^{2}}{b^{2}} - \frac{z^{2}}{c^{2}} = 1 $

双曲抛物面  $ -\frac{x^{2}}{2p}+\frac{y^{2}}{2q}=z $;  $ z=xy $

2. 柱面 → 母线平行于轴时，联立  $ \left\{\begin{array}{l} F(x, y, z) = 0 \\ G(x, y, z) = 0 \end{array}\right. $ 消正负为柱面  $ H(x, y) = 0 $

椭圆柱面 $ \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 $

双曲柱面 $ \frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1 $

抛物柱面  $ y=ax^{2} $

### 3. 投影

 $ F(x,y,z)=0 $ 向 $ x_{0}y $投影：消得 $ \varphi(x,y)=0 $，即 $ \left\{\begin{array}{l}\varphi(x,y)=0 \\ z=0\end{array}\right. $ (的子集).

如： $ \left\{\begin{array}{l}x^{2}+y^{2}=a \\ x^{2}+y^{2}=ax\end{array}\right. $ (a20)在xO₂投影为 $ \left\{\begin{array}{l}z^{2}+ax=a \\ y=0\end{array}\right. $ (0≤x≤a)

### 4. 旋转

 $ \Gamma:\left\{\begin{array}{l}F(x,y,z)=0\\G(x,y,z)=0\end{array}\right. $ 绕  $ L:\frac{x-x_{0}}{2}=\frac{y-y_{0}}{m}=\frac{z-z_{0}}{n} $ 旋转一周，有  $ \overrightarrow{M_{1}P}\perp\overrightarrow{C} $， $ \left|\overrightarrow{M_{0}P}\right|=\left|\overrightarrow{M_{0}M_{1}}\right| $

即： $ \left\{\begin{array}{l}2(x-x_{1})+m(y-y_{1})+n(z-z_{1})=0\ $ x-x_{0})^{2}+(y-y_{0})^{2}+(z-z_{0})^{2}=(x_{1}-x_{0})^{2}+(y_{1}-y_{0})^{2}+(z_{1}-z_{0})^{2}\end{array}\right. $，联立 $ \left\{\begin{array}{l}F(x_{1},y_{1},z_{1})=0\\G(x_{1},y_{1},z_{1})=0\end{array}\right. $消去 $ x_{1},y_{1},z_{1} $即可

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_0/imgs/img_in_image_box_824_629_950_747.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A40Z%2F-1%2F%2F96f04243184baa30668b57af121347e7f57b7f3c45146373b59fcbcf70bc21b2" alt="Image" width="10%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_0/imgs/img_in_image_box_824_629_950_747.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A40Z%2F-1%2F%2F96f04243184baa30668b57af121347e7f57b7f3c45146373b59fcbcf70bc21b2" alt="Image" width="10%" />

M₁ L
I
P

</div>


</div>


特别地，当L为Z轴，由 $ \vert\overrightarrow{OP}\vert=\vert\overrightarrow{OM}\vert $与 $ z=z_{1} $，则 $ x^{2}+y^{2}=x_{1}^{2}+y_{1}^{2} $，则 $ \left\{\begin{array}{l}f(x_{1},y_{1},z_{1})=0\\g(x_{1},y_{1},z_{1})=0\\x^{2}+y^{2}=x_{1}^{2}+y_{1}^{2}\end{array}\right. $消去 $ x_{1},y_{1} $即可.

更特别地，若工中可解出  $ \left\{\begin{array}{l} x-1(z) \\ y=f_{2}(z) \end{array}\right. $，则  $ x^{2}+y^{2}=f_{1}(z)+f_{2}(z) $

若  $ \left\{\begin{array}{l} f(y,z)=0 \\ x=0 \end{array}\right. $，则绕 y 轴转： $ f(y,\pm\sqrt{x^{2}+z^{2}})=0 $，绕区轴转： $ f(\pm\sqrt{x^{2}+y^{2}},z)=0 $

### 5. 切线与切平面

曲线的切向量 ①  $ \left\{\begin{array}{l} x=x_{1}t \\ y=y_{1}t \\ z=z_{1}t \end{array}\right. $  $ \overrightarrow{t}=\left(x_{t}^{1}, y_{t}^{1}, z_{t}^{1}\right) $ ②  $ \left\{\begin{array}{l} F(x, y, z)=0 \\ G(x, y, z)=0 \end{array}\right. $  $ \overrightarrow{t}=\left|\begin{array}{l} \overrightarrow{f_{x}} \\ \overrightarrow{f_{x}}, \overrightarrow{f_{y}}, \overrightarrow{f_{z}} \end{array}\right|=\overrightarrow{n_{F}}\times\overrightarrow{n_{G}} $ 切线、法平面

曲面的法向量 ①  $ F(x,y,z)=0 $  $ \overrightarrow{n}=(\overrightarrow{F_{x}}^{-1},F_{y}^{-1},F_{z}^{-1}) $ ②  $ z=f(x,y) $,  $ \overrightarrow{n}=(\overrightarrow{f_{x}}^{-1},f_{y}^{-1},-1) $ 法线、切平面

③  $ \left\{\begin{array}{l} x=x(u,v) \\ y=y(u,v) \\ z=z(u,v) \end{array}\right. $  $ \overrightarrow{n}=\left(\left|\frac{\partial y}{\partial u}\frac{\partial y}{\partial v}\right|,\left|\frac{\partial z}{\partial u}\frac{\partial z}{\partial v}\right|,\left|\frac{\partial x}{\partial u}\frac{\partial x}{\partial v}\right|\right) $

## 四.场论

### 1. 场

数量场  $ n $ 上每一点  $ M(x, y, z) $ 对应一个数量  $ u $，则确定了一个数量函数  $ u = u(x, y, z) $

向量场

向量 $ \overrightarrow{F} $

向量函数 $ F(x,y,z)=P(x,y,z)\overrightarrow{i}+Q(x,y,z)\overrightarrow{j}+R(x,y,z)\overrightarrow{k} $

2. 方向与数

 $ \left.\frac{\partial u}{\partial t}\right|_{0} = \lim_{t \to 0^{+}} \frac{u(x_0 + t \cos \theta, y_0 + t \cos \theta, z_0 + t \cos \theta) - u(x_0, y_0, z_0)}{t} = \lim_{t \to 0^{+}} \frac{u(x_0 + t \cos \theta, y_0 + t \cos \theta, z_0 + t \cos \theta) - u(x_0, y_0, z_0)}{t} = \sqrt{g(x_0 + t \cos \theta)}

若u在P处可微，则 $ \forall \varepsilon, \frac{\partial u}{\partial \varepsilon}, \frac{\partial u}{\partial \varepsilon} = g(x_0, y_0, z_0) = g(x_0, y_0, z_0) = g(x_0, y_0, z_0) = g(x_0, y_0, z_0) = g(x_0, y_0, z_0) $

证：由可微，则 $ \frac{\partial u}{\partial \varepsilon}|_{0} = \lim_{t \to 0^{+}} \frac{u(x_0 + t \cos \theta, y_0 + t \cos \theta, z_0 + t \cos \theta) - u(x_0, y_0, z_0)}{t} = \lim_{t \to 0^{+}} \frac{u_x^2 \Delta x + u_y^2 \Delta y + u_z^2 \Delta z + o(t)}{\sqrt{(x_0 + x_0)^2 + (x_0 + z_0)^2}} = \frac{\Delta x}{\sqrt{(x_0 + x_0)^2 + (x_0 + z_0)^2}} = \frac{\Delta x}{\sqrt{(x_0 + x_0)^2 + (x_0 + z_0)^2}} $

例： $ f(x, y) = \begin{cases} 1, & y > x, x \neq 0 \\ 0, & else \end{cases} $

在 $ (0, 0) $处 $ \frac{\partial t}{\partial \varepsilon} = \lim_{t \to 0^{+}} \frac{f(t \cos \theta, t \cos \theta) - f(t, \theta)}{\frac{\partial t}{\partial \varepsilon} - \frac{\partial t}{\partial x}} = \lim_{t \to 0^{+}} \frac{0 - \theta}{\frac{\partial t}{\partial \varepsilon} - \frac{\partial t}{\partial x}} = 0 $存在，但显然不连续 $ \lim_{t \to 0} f(t) = 0 $存在，但显然不连续 $ \lim_{t \to 0} f(t) = 0 $存在，但显然不连续

### 3. 梯度 不可微时用方向导数定义

 $ \nabla u = \overrightarrow{grad} u|_{p_0} = (u_x^1, u_y^1, u_z^1) $，其公式类似导数，如  $ \overrightarrow{grad}(u) = v \frac{\overrightarrow{grad} u - u \overrightarrow{grad} v}{v^2} (v \neq 0) $

 $ \cos\theta = | $时方向导数取得最大值  $ |\overrightarrow{grad} u| = \sqrt{(u_x^1)^2 + (u_y^1)^2 + (u_z^1)^2} $;  $ \cos\theta = 0 $ 时  $ \frac{\partial u}{\partial \vec{z}} = 0 $

### 4. 散度

对 $ \overrightarrow{A}=P\overrightarrow{i}+Q\overrightarrow{j}+R\overrightarrow{k} $，有 $ \operatorname{div}\overrightarrow{A}=P_{x}^{1}+Q_{y}^{1}+R_{z}^{1} $

### 5、旋度

 $ \overrightarrow{r o t}\overrightarrow{A}=\left|\frac{\overrightarrow{i}}{3x}\frac{\overrightarrow{j}}{3y}\frac{\overrightarrow{k}}{3z}\right| $，结果写成 $ C_{1}\overrightarrow{i}+C_{2}\overrightarrow{j}+C_{3}\overrightarrow{k} $的形式

 $ \overrightarrow{g r a d}(\overrightarrow{r o t}\overrightarrow{F})=0 $

### 6. 二次泰勒多项式

 $$ f(x,y)=f(x_{0},y_{0})+(f_{x}^{\prime},f_{y}^{\prime})_{0x y}^{\Delta x})+\frac{1}{2!}(0x,0y)\binom{f_{x x}^{\prime\prime}}{f_{x y}^{\prime\prime}}-\frac{f_{y y}^{\prime\prime}}{f_{y y}^{\prime\prime}}\binom{\Delta x}{\Delta y} $$ 

 $$ f(\overrightarrow{x})=f(\overrightarrow{x_{0}})+\left(\nabla f(\overrightarrow{x_{0}})\right)^{\mathrm{T}}(\overrightarrow{x}-\overrightarrow{x_{0}})+\frac{1}{2!}(\overrightarrow{x}-\overrightarrow{x_{0}})^{\mathrm{T}}\mathrm{H}(\overrightarrow{x}-\overrightarrow{x_{0}})^{\mathrm{T}} $$ 

## 五、常见S、V

球  $ S = 4\pi R^{2} $,  $ V = \frac{4}{3}\pi R^{3} $

概有球  $ V=\frac{4}{3}\pi a^{2}bc $

圆柱  $ S = 2\pi R(R+h) $  $ V = \pi R^{2}h $

圆锥  $ S=\pi R(R+2) $  $ V=\frac{\pi}{3}R^{2}h $ （斜高  $ l=\sqrt{R^{2}h^{2}} $） $ (S_{侧}=\pi R2) $

正四面体  $ S=\sqrt{3}a^{2} $  $ V=\frac{\sqrt{2}}{12}a^{3} $

正八面体  $ S=2\sqrt{3}a^{2} $  $ V=\frac{\sqrt{2}}{3}a^{3} $

球冠  $ S = 2\pi Rh $  $ V = \frac{\pi h^{2}}{3}(3R - h) $  $ y = \sqrt{R^{2} - x^{2}} $,  $ S = \int 2\pi y ds = \int_{R-h}^{R} 2\pi y \cdot \frac{R}{y} dx $  $ V = \int_{R-h}^{R} \pi (R^{2} - 2^{2}) dz $

球台  $ S = 2\pi Rh $  $ V = \frac{\pi h}{6}(3r_{1}^{2} + 3r_{2}^{2} + h^{2}) $  $ S = \int_{k}^{k+h} 2\pi y \cdot \frac{R}{y} dx $  $ V = \int_{k}^{k+h} \pi (R^{2} - 2^{2}) dz $ 且  $ \left\{\begin{array}{l} r_{1}^{2} = R^{2} - k^{2} \\ r_{2}^{2} = R^{2} - (k + h)^{2} \end{array}\right. $

## 六、常见形心

三角形： $ \left(\frac{x_{1}+x_{2}+x_{3}}{3},\frac{y_{1}+y_{2}+x_{3}}{3}\right) $

立体dv

正四面体:  $ (0,0,\frac{h}{4}) $

半圆：离圆心  $ \frac{4k}{3\pi} $

半圆弧 $ (0,\frac{2R}{\pi}) $

半球： $ (0,0,\frac{3k}{8}) $ 半球面： $ (0,0,\frac{k}{2}) $

扇形：离圆心  $ \frac{2R\sin\theta}{3\theta} $ (2θ为圆心角)

圆锥： $ (0,0,\frac{h}{4}) $ 圆锥侧面： $ (0,0,\frac{h}{3}) $

##### 拓展

考试大纲要求了解下列九种常用二次曲面的标准方程及其图形。读者可结合这些二次曲面的构造过程来记忆。

（1）椭圆锥面 $ \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=z^{2} $（如图①）

将 xOz 平面上的直线 x = az 绕 z 轴旋转得到圆锥面  $ \frac{x^{2} + y^{2}}{a^{2}} = z^{2} $，再将此旋转曲面沿 y 轴方向伸缩  $ \frac{b}{a} $ 倍，便得到椭圆锥面  $ \frac{x^{2}}{a^{2}} + \frac{y^{2}}{b^{2}} = z^{2} $.

(2) 椭球面  $ \frac{x^{2}}{a^{2}} + \frac{y^{2}}{b^{2}} + \frac{z^{2}}{c^{2}} = 1 $ (如图②)

将 xOz 平面上的椭圆  $ \frac{x^{2}}{a^{2}}+\frac{z^{2}}{c^{2}}=1 $ 绕 z 轴旋转得到旋转椭球面  $ \frac{x^{2}+y^{2}}{a^{2}}+\frac{z^{2}}{c^{2}}=1 $，再将此旋转曲面沿 y 轴方向伸缩  $ \frac{b}{a} $ 倍，便得到椭球面  $ \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}+\frac{z^{2}}{c^{2}}=1 $.

（3）单叶双曲面 $ \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}-\frac{z^{2}}{c^{2}}=1 $（如图③）

将 xOz 平面上的双曲线  $ \frac{x^{2}}{a^{2}} - \frac{z^{2}}{c^{2}} = 1 $ 绕 z 轴旋转得到旋转单叶双曲面  $ \frac{x^{2} + y^{2}}{a^{2}} - \frac{z^{2}}{c^{2}} = 1 $，再将此旋转曲面沿 y 轴方向伸缩  $ \frac{b}{a} $ 倍，便得到单叶双曲面  $ \frac{x^{2}}{a^{2}} + \frac{y^{2}}{b^{2}} - \frac{z^{2}}{c^{2}} = 1 $.

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_3/imgs/img_in_image_box_261_770_402_990.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A43Z%2F-1%2F%2F6b4c8e1ee57082415ee4fcdfd0de55a0089382fe54dbe84c1680f0338d150194" alt="Image" width="11%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_3/imgs/img_in_image_box_261_770_402_990.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A43Z%2F-1%2F%2F6b4c8e1ee57082415ee4fcdfd0de55a0089382fe54dbe84c1680f0338d150194" alt="Image" width="11%" />

z
O
x

</div>


</div>


<div style="text-align: center;"><div style="text-align: center;">①</div> </div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_3/imgs/img_in_image_box_486_806_687_1001.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A43Z%2F-1%2F%2F1b3606e5292056e1035782911d1fe1b59f21d51c3cb2bcb7bfe24e1d80011a7e" alt="Image" width="16%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_3/imgs/img_in_image_box_486_806_687_1001.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A43Z%2F-1%2F%2F1b3606e5292056e1035782911d1fe1b59f21d51c3cb2bcb7bfe24e1d80011a7e" alt="Image" width="16%" />

Z
y
O
x

</div>


</div>


<div style="text-align: center;"><div style="text-align: center;">②</div> </div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_3/imgs/img_in_image_box_770_771_931_992.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A43Z%2F-1%2F%2Fbdd85e6c27c0ee7f9deb70cdd6e6827164e69f4639dbb2ae652ca26993945d46" alt="Image" width="13%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_3/imgs/img_in_image_box_770_771_931_992.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A43Z%2F-1%2F%2Fbdd85e6c27c0ee7f9deb70cdd6e6827164e69f4639dbb2ae652ca26993945d46" alt="Image" width="13%" />

z
y
x

</div>


</div>


<div style="text-align: center;"><div style="text-align: center;">③</div> </div>


（4）双叶双曲面 $ \frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}-\frac{z^{2}}{c^{2}}=1 $（如图④）

将 xOz 平面上的双曲线  $ \frac{x^{2}}{a^{2}} - \frac{z^{2}}{c^{2}} = 1 $ 绕 x 轴旋转得到旋转双叶双曲面  $ \frac{x^{2}}{a^{2}} - \frac{y^{2} + z^{2}}{c^{2}} = 1 $，再将此旋转曲面沿 y 轴方向伸缩  $ \frac{b}{c} $ 倍，便得到双叶双曲面  $ \frac{x^{2}}{a^{2}} - \frac{y^{2}}{b^{2}} - \frac{z^{2}}{c^{2}} = 1 $.

(5) 椭圆抛物面  $ \frac{x^{2}}{a^{2}} + \frac{y^{2}}{b^{2}} = z $ (如图⑤)

将 xOz 平面上的抛物线  $ \frac{x^{2}}{a^{2}} = z $ 绕 z 轴旋转得到旋转抛物面  $ \frac{x^{2} + y^{2}}{a^{2}} = z $，再将此旋转曲面沿

y 轴方向伸缩  $ \frac{b}{a} $ 倍，便得到椭圆抛物面  $ \frac{x^{2}}{a^{2}} + \frac{y^{2}}{b^{2}} = z $.

(6) 双曲抛物面（马鞍面） $ \frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=z $（如图⑥）

若用平面 x = t 来截双曲抛物面，所得截痕为平面 x = t 上的抛物线  $ \frac{y^{2}}{b^{2}} = -z + \frac{t^{2}}{a^{2}} $，其开口朝下。若用平面 y = t 来截双曲抛物面，所得截痕为平面 y = t 上的抛物线  $ \frac{x^{2}}{a^{2}} = z + \frac{t^{2}}{b^{2}} $，其开口朝上。

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_265_556_490_734.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2Fb62b31ee323ee12a10aa307d438b0cc1b567161e321addfcbbe0d9de5676fef2" alt="Image" width="18%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_265_556_490_734.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2Fb62b31ee323ee12a10aa307d438b0cc1b567161e321addfcbbe0d9de5676fef2" alt="Image" width="18%" />

 $ \overrightarrow{z} $

 $ \overrightarrow{O} $

</div>


</div>


<div style="text-align: center;"><div style="text-align: center;">④</div> </div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_537_557_706_739.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2Fd4785f02c944c9c662e0928382cbd4850efcb9c2196f7d95fce0426c9869e528" alt="Image" width="14%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_537_557_706_739.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2Fd4785f02c944c9c662e0928382cbd4850efcb9c2196f7d95fce0426c9869e528" alt="Image" width="14%" />

Z
O
x

</div>


</div>


<div style="text-align: center;"><div style="text-align: center;">⑤</div> </div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_752_550_927_738.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2F808a48121c116b4b08a05c780887f07cc5ba3dc34ec7209b38ae02ca820feaf9" alt="Image" width="14%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_752_550_927_738.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2F808a48121c116b4b08a05c780887f07cc5ba3dc34ec7209b38ae02ca820feaf9" alt="Image" width="14%" />

z
x
y

</div>


</div>


<div style="text-align: center;"><div style="text-align: center;">⑥</div> </div>


（7）椭圆柱面 $ \frac{x^{2}}{a^{2}}+\frac{y^{2}}{b^{2}}=1 $（如图⑦）

（8）双曲柱面 $ \frac{x^{2}}{a^{2}}-\frac{y^{2}}{b^{2}}=1 $（如图⑧）

（9）抛物柱面  $ y^{2}=ax $ (如图⑨)

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_273_926_458_1159.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2F941372ba7446202ac32cef222cf6774992a26683827d31c19d7f240651802dba" alt="Image" width="15%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_273_926_458_1159.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2F941372ba7446202ac32cef222cf6774992a26683827d31c19d7f240651802dba" alt="Image" width="15%" />

Z
O
x

</div>


</div>


<div style="text-align: center;"><div style="text-align: center;">⑦</div> </div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_476_927_734_1167.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2F0c338f682123c9c23a465a1024fab1e9827c7de83a5770207a43a1e70128e008" alt="Image" width="21%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_476_927_734_1167.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2F0c338f682123c9c23a465a1024fab1e9827c7de83a5770207a43a1e70128e008" alt="Image" width="21%" />

Z
y
x

</div>


</div>


<div style="text-align: center;"><div style="text-align: center;">⑧</div> </div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_750_923_918_1164.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2F154f739b9ce40ca9d06d8788da91a4d6b0bb1d4819371d2b2d7ef86702ddd191" alt="Image" width="14%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//edb95279-b130-4575-8787-cd49b90f95ae/markdown_4/imgs/img_in_image_box_750_923_918_1164.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A44Z%2F-1%2F%2F154f739b9ce40ca9d06d8788da91a4d6b0bb1d4819371d2b2d7ef86702ddd191" alt="Image" width="14%" />

z
O  $ \rightarrow $ x

</div>


</div>


<div style="text-align: center;"><div style="text-align: center;">⑨</div> </div>


# 空间几何

过 $ \left\{\begin{array}{l}10x+2y-2z=27\\x+y-z=0\end{array}\right. $作 $ 3x^{2}+y^{2}-z^{2}=27 $的切平面，求切平面方程

解：平面束 $ (0+\lambda)x+(2+\lambda)y-(2+\lambda)z=27 $，则有 $ \left\{\begin{array}{l}  切：\frac{(0+\lambda)}{6x_{0}}=\frac{2+\lambda}{2x_{0}}=\frac{(2+\lambda)}{-2x_{0}} \\  面：3x_{0}^{2}+y_{0}^{2}-z_{0}^{2}=27 \\  切平面：\left(6+\lambda\right)x_{0}+(2+\lambda)y_{0}-(2+\lambda)z=27 \end{array}\right. $ ① 由①： $ y=2 $，代入②： $ x=\pm3 $，代入③：

 $ \lambda=-1 $或-19，代入①： $ y=2=1 $或-17

② 9x+y-2-27=0或 $ 9x+17y-17z+27=0 $

2.  $ 4z = x + y^{2} $ 上一点 M 的切平面为  $ \pi $，若过  $ \pi $ 的  $ \Gamma $:  $ \left\{\begin{array}{l} x = t \\ z = 3(t-1) \end{array}\right. $ 在  $ t=1 $ 的切线为 L 且  $ \angle C\pi $，求  $ \pi $ 的方程

解：切线  $ L = \frac{x+1}{2} = \frac{y+1}{2} = \frac{z}{3} $， $ \pi: x x_{0} + y y_{0} - 2z = 2z_{0} (\overrightarrow{n}^{2} + \frac{x_{0}}{2}, \frac{y_{0}}{2}, -1) $，由  $ (1,1,0) $， $ (3,2,3) \in \angle C\pi $ 知  $ \left\{\begin{array}{l} x_{0} + y_{0} = 2z \\ 3x_{0} + 2y_{0} - 6 = 2z_{0} \\ x_{0}^{2} + y_{0}^{2} = 4z_{0} \end{array}\right. $

则  $ M: (\frac{12}{5}, \frac{6}{5}, \frac{9}{5}) $ 或  $ (2, 2, 2) $

 $ 6x + 3y - 5z = 9 $ 或  $ x + y - z = 2 $

3.(1) $ \overrightarrow{a}=(2,4,-4) $， $ \overrightarrow{b}=(-1,2,-2) $，求与角平分线向量 $ \overrightarrow{c} $且 $ |\overrightarrow{c}|=\sqrt{32} $

(2) 设点  $ E $ 为点 A、B、C 的矢径向量. 试证: A, B, C 三点共线  $ \Leftrightarrow \overrightarrow{r_{1}} \times \overrightarrow{r_{2}} + \overrightarrow{r_{2}} \times \overrightarrow{r_{3}} + \overrightarrow{r_{3}} \times \overrightarrow{r_{1}} = \overrightarrow{0} $

解: (1)  $ \overrightarrow{C}=\lambda\left(\frac{\overrightarrow{a}}{|\overrightarrow{a}|}+\frac{\overrightarrow{b}}{|\overrightarrow{b}|}\right)=\lambda(0,\frac{4}{3},-\frac{4}{3})=(0,\pm4,F4) $ 归一化为单位向量后再相加

方向 (2) A, B, C共线  $ \Leftrightarrow \overrightarrow{AB} \times \overrightarrow{AC} = \overrightarrow{0} \Leftrightarrow (\overrightarrow{r_{2}} - \overrightarrow{r_{1}}) \times (\overrightarrow{r_{3}} - \overrightarrow{r_{1}}) = \overrightarrow{0} \Leftrightarrow \overrightarrow{r_{2}} \times \overrightarrow{r_{3}} - \overrightarrow{r_{2}} \times \overrightarrow{r_{1}} - \overrightarrow{r_{1}} \times \overrightarrow{r_{3}} + \overrightarrow{0} = \overrightarrow{0} $

途径向量：空间中某点相对于原点位置的向量，如 $ (x,y,z) $对应 $ \overrightarrow{v}=x\overrightarrow{i}+y\overrightarrow{j}+z\overrightarrow{k} $，因此 $ \overrightarrow{AB}=\overrightarrow{v}_{2}-\overrightarrow{v}_{1} $ (也叫位置向量)

4. 求过  $ (-1,0,4) $ 且平行  $ 3x-4y+2=10 $ 且与  $ x+1=y-3=\frac{2}{2} $ 相交的直线方程

解: ①  $ L = \begin{cases} x = -1 + a t, & t > 0 \\ y = 4 t, & t \leq 0 \end{cases} $

联立①②且  $ \alpha = 1 $ 得  $ \frac{1}{2} = (1, \frac{19}{16}, \frac{7}{4}) $

故  $ \left\{ \begin{array}{l} x = -1 + 16 t \\ y = 19 t \\ z = 4 + 28 t \end{array} \right. $

② 过  $ (1, 0, 4) $ 且平行  $ 3x - 4y + z = 0 $ 的平面为  $ 3x - 4y + z = 0 $

 $ \left\{ \begin{array}{l} x + 4y + z = 1 \\ x + 1 = y - 3 = \frac{5}{2}, \text{得 } \frac{1 - 19}{2} = 3, \text{L过}(-1, 0, 4) $ 与  $ (15, 19, 32) $

 $ \frac{x + 1}{16} = \frac{y}{19} = \frac{z - 4}{28} $

③  $ x + 1 = y - 3 = \frac{3}{2} $ 的平面求方程为  $ x - y + 4 + \lambda(y - \frac{3}{2} - 3) = 0 $ 过  $ (1, 0, 4) $ 得  $ \lambda = \frac{3}{5} $，即  $ \left\{ \begin{array}{l} x - 4y - 3 = -22, \\ x + 1 = y - 3 = -22 \end{array} \right. $

5.  $ L_{1} $:  $ \frac{x+2}{1} = \frac{y-3}{-1} = \frac{2+1}{1} $,  $ L_{2} $:  $ \frac{x+4}{2} = \frac{y}{1} = \frac{2-4}{3} $，求与  $ L_{1}, L_{2} $ 都垂直且相交的直线方程

解  $ \overrightarrow{c}=\overrightarrow{c_{1}}\times\overrightarrow{c_{2}}=(4,-1,3) $，过  $ L $ 且平行它的平面， $ \left\{\begin{array}{l}x+2y-3\\3x-9y+2+8=0\end{array}\right. $  $ \left\{\begin{array}{l}2x+7y+5z-12=0\\3x-9y+2+8=0\end{array}\right. $  $ \left\{\begin{array}{l}0, 即  $ 2x+7y+5z-12=0 $，同理，过  $ L $ 且平行它的平面\end{array}\right. $

6. 求以  $ P: \begin{cases} x^{2} + y^{2} + z = 1 \\ x + y + z = 0 \end{cases} $ 为准线，母线平行于  $ x = y = z $ 的柱面方程

解：① 圆柱面上  $ \forall (x,y,z) $ 到 x=y=z 距离为  $ | \Rightarrow \frac{|(x,y,z) \times (1,1)|}{\sqrt{3}} = 1  $  $ (x-y)^{2} + (y-z)^{2} + (z-x)^{2} = 3 $

② 设工上 $ (x_{0}, y_{0}, z_{0}) $ 所对应母线为

 $ x-x_{0}=y-y_{0}=z-z_{0} $ (因为平行  $ x=y=z $)，在  $ \left\{\begin{array}{l} x_{0}^{2}+y_{0}^{2}+z_{0}^{2}=1 \\ x_{0}+y_{0}+z_{0}=0 \end{array}\right. $

中消去 $ x_{0}, y_{0}, z_{0} $得 $ (2x - y - z)^{2} + (2y - x - z)^{2} + (2z - x - y)^{2} = 0 $，化简即可

7.  $ f(x,y) $ 在  $ (0,0) $ 附近有定义， $ f_{x}^{\prime}(0,0)=3 $， $ f_{y}^{\prime}(0,0)=1 $，求  $ \left\{\begin{array}{l} z=f(x,y) \\ y=0 \end{array}\right. $ 在  $ (0,0, f(0,0)) $ 的切向量

解：由  $ \frac{1}{x}(0,0)\neq0 $ 知  $ \exists y=y(x) $，该曲线可改写为  $ \left\{\begin{array}{l}x=x\\y=0\end{array}\right. $，则  $ \frac{x^{2}}{2}+(x-1)(x+1) $，则  $ \frac{1}{x^{2}}=f_{x}^{1}+f_{y}^{1}\cdot y(0)=3 $， $ \overrightarrow{e}=(1,0,3) $

注：仅知 $ t_{x}^{1}, t_{y}^{1} $不能推出连续、 $ \frac{\partial f}{\partial\pi}(t_{0})=3\cos\alpha+\cos\beta $等，R能推出沿x轴负方向的方向与数为 $ \lim_{t\to+\infty}\frac{f(-t,0)-f(t,0)}{t}=-f_{x}^{1}=-3 $这样的结论

8.  $ z=f(x,y) $可微与xoy交线为 $ \left\{\begin{array}{l}y=\int_{0}^{x}e^{-t^{2}}+\sin t^{2}dt\\z=0\end{array}\right. $， $ t_{x}^{1}(0,0)=1 $，则 $ \left|\frac{dz}{100}\right| $

解：由  $ f(x, \int_{0}^{x} e^{-\frac{t^{2}}{2}} dt) = 0 $ 对 x 导，有  $ f_{1}^{\prime} + (e^{-\frac{x^{2}}{2}} \sin x)^{\prime} f_{2}^{\prime} = 0 $，故  $ f_{2}^{\prime} = -1 $ (梯度与等值线切向量垂直)  $ dx - dy $

类似于等值线  $ f(x, t), y(t) = k $，则  $ f_{x}^{\prime} \cdot x_{t}^{\prime} + f_{y}^{\prime} \cdot y_{t}^{\prime} = 0 $，即  $ (f_{x}^{\prime}, f_{y}^{\prime}) \cdot (x_{t}^{\prime}, y_{t}^{\prime}) = 0 $

9.  $ f(u) \neq 0 $,  $ x_{0}^{2} + x_{0}^{2} = 0 $.  $ z = f(\sqrt{x_{0}^{2}}) $ 上点  $ M_{0}(x_{0}, x_{0}, z_{0}) $ 处法线与 Z 轴的位置关系是？

解： $ \overrightarrow{n}=(\frac{x_{0}}{x_{0}}f^{\prime}(x_{0}),\frac{x_{0}}{x_{0}}f^{\prime}(x_{0}),-1) $ 不平行于  $ \overrightarrow{k}=(0,0,1) $ 且不垂直于  $ \overrightarrow{k} $. 又由  $ \overrightarrow{k}\cdot(\overrightarrow{0}\overrightarrow{m}\times\overrightarrow{n})=\frac{\left|\overrightarrow{x_{0}}\times\overrightarrow{0}\right|\cdot\overrightarrow{2_{0}}}{\left|\overrightarrow{x_{0}}\times\overrightarrow{0}\right|\times\overrightarrow{f(x_{0})}}=0 $ 故共通相交 相交但不垂直

10.(1) 顶点  $ (0,1,1) $，准线  $ \left\{\begin{array}{l} x^{2}+y^{2}=1 \\ z=0 \end{array}\right. $ 的锥面方程 (2) 求  $ \left\{\begin{array}{l} x-y+2z-1=0 \\ x-3y-2z+1=0 \end{array}\right. $ 绕 y 轴旋转一周的曲面

解：(1) 由  $ \frac{x-0}{x_{1}-0}=\frac{y-1}{y_{1}-1}=\frac{2-1}{-1} $ 与  $ x_{1}^{2}+x_{1}^{2}=1 $ 知  $ x^{2}+(y-2)^{2}=(1-2)^{2} $

(2)  $ \left\{\begin{array}{l}x=2y\\z=-\frac{y-1}{2}\end{array}\right. $ 设  $ (x_{1},y_{1},z_{1})\in L $

则  $ \left\{\begin{array}{l}y=y_{0}\\x^{2}+z^{2}=x_{0}^{2}+2z^{2}\end{array}\right. $ 代入  $ \left\{\begin{array}{l}x_{0}=2x_{0}\\z_{0}=-\frac{x-1}{2}\end{array}\right. $ 得  $ 4x^{2}+17y^{2}+4z^{2} $

# 曲线曲面积分

## 一、第一型曲线积分

 $ \int_{L}f(x,y)ds=\lim_{\lambda\to0}\frac{\frac{n}{2\lambda}}{i=1}f(\xi_{i},\eta_{i})\Delta S_{i} $ 入为各小弧段长度的最大值

保号性总结: 定积分  $ f(x) \geq g(x) \Rightarrow \int_{a}^{b} f(x) dx \geq \int_{a}^{b} g(x)  $ 的前提是 b > a, 这是因为  $ \left\{\begin{array}{l} a < b \Rightarrow dx > 0 \\ a > b \Rightarrow dx < 0 \end{array}\right. $

而二重积分 $ d\delta>0 $，三重 $ dv>0 $，一型曲线 $ ds>0 $，一型曲面 $ dS>0 $

1. 计算

一、二型曲线、面均可

① 将曲线方程 L 代入被积函数  $  f(x, y)  $

② 利用  $ ds = \sqrt{(dx)^{2} + (dy)^{2}} \rightarrow \begin{cases} dx \\ dy \end{cases} $ (弧长计算公式) 例： $ \int_{L} f(x,y) ds = \int_{a}^{b} f(x,y,x) \sqrt{1 + [y + x]^{2}} dx $ ( $ a \leq x \leq b $)

### 2、应用

空间曲线弧长  $  l = \int_{x}^{b} \sqrt{x_{t}^{2} + y_{t}^{2} + z_{t}^{2}} \, dt  $ 重心  $  \overline{x} = \frac{\int_{L} x p \, ds}{\int_{L} p \, ds}  $ 逆用:  $  \int_{L} x \, ds = \overline{x} \cdot l  $ 转动惯量  $  I_{x} = \int_{L} (y + z) \, p \, ds  $

## 二、第二型曲线积分

变力 $ \overrightarrow{F}=P\overrightarrow{t}+Q\overrightarrow{v} $沿L，做功 $ W=\int_{L}dW=\int_{L}\overrightarrow{F}\cdot d\overrightarrow{S}=\int_{L}(P,Q)\cdot(dx,dy)=\int_{L}Pdx+Qdy $ 有向性

1. 计算

计算

①对称性 定方向(符号)看数量大小(正负) 例： $ \frac{A}{B} $ 在A处 $ \overrightarrow{d_{x}} $ 即 $ (-x)^{2}y(-d_{y}) $，在B处 $ \overrightarrow{d_{x}} $，即 $ x^{2}yd_{y} $

②代入化为定积分  $ \int_{L}P(x,y)dx=\int_{d}^{B}P[x(t),y(t)]x_{t}^{2}dt $  $ \int_{L}Pdx+Qdy=\int_{a}^{b}Pdx+Qy(x)dx $ a,d为起点，不一定小于b,β

③格林 有界闭区域，P、Q—阶偏导连续，取正向，则  $ \oint_{L} Pdx + q dy = \int_{D} Qx - Py d\sigma $

若有奇点，换含奇点的闭曲线  $ L_{1} $ 且方向一致，则  $ \oint_{L} \varphi = \oint_{L_{1}} \varphi $ 或换路径  $ L_{2} $ 且起终点一致且  $ L_{1} $、 $ L_{2} $ 围成区域不含奇点

对单连域，P、Q—阶偏导连续，有  $ Q_{x}^{\prime} = P_{y}^{\prime} $ 闭曲线  $ \oint_{L} Pdx + q dy = 0 $

其中  $ u(x,y) = \int_{x_{0}}^{x} p(x,y) dx + \int_{y_{0}}^{y} q(x,y) dy $ 证： $ \int_{x_{0},y_{0}}^{x_{0}} du = \int_{x_{0},y_{0}}^{x_{0}} pdx + qdy $

 $ du = Pdx + q dy $ （若不单连通（有同），则个）不能推出其他结论）

 $ P(x,y) = P_{0} + P_{1} + P_{2} + \cdots + P_{n} $

取折线  $ (x_{0}, y_{0}) \rightarrow (x_{0}, y_{0}) $

 $$ \text{证}:I=\iint\limits_{\Sigma}(\Delta x \cdot \Delta y \cdot \Delta z)dS=\frac{\partial\rho}{\partial x}dS-\frac{\partial\rho}{\partial y}dS-\frac{\partial\rho}{\partial z}dS=\iint\limits_{\Sigma}\Delta x\cdot\Delta y\cdot\Delta z dV-\iint\limits_{\Sigma}(\Delta x \cdot \Delta y\cdot \Delta z)dV=\frac{1}{2}\rho\Delta x\cdot\Delta y\cdot\Delta z dS=0-\frac{1}{2}\rho\Delta x\cdot\Delta y\cdot\Delta z dS $$ 

④斯托克斯 乙为分光光滑曲面片，工为乙边界，方向与乙的或右手系P、Q、R+阶偏导连续，则  $ = \iint_{D} (D \times F) \cdot \overrightarrow{AD} ds $

 $ \oint Pdx + Qdy + RdZ = \iint_{D} \left| \frac{\partial x}{\partial P} \cdot \frac{\partial y}{\partial Q} \right| = \iint_{D} \left| \frac{\partial x}{\partial P} \cdot \frac{\partial y}{\partial Q} \right| dS $ 与乙无关（即  $ \iint_{D} \left| \frac{\partial x}{\partial P} \cdot \frac{\partial y}{\partial Q} \right| dS = \iint_{D} \left| \frac{\partial x}{\partial P} \cdot \frac{\partial y}{\partial Q} \right| dS $）

⑤ 联系  $ \oint_{L}Pdx+Qdy=\oint_{L}(P\cos\alpha+Q\cos\beta)ds $ 证： $ ds=\sqrt{\frac{4x^{2}+(4y)^{2}}{4x^{2}+(4x)^{2}}}dt $，对  $ L:(x(t),y(t)) $，切向量  $ \overrightarrow{t}=(\frac{dx}{dt},\frac{dy}{dt}) $

因此  $ \cos\alpha=\frac{\frac{dx}{dt}}{\sqrt{\frac{dx}{dt}}+\left(\frac{dy}{dt}\right)}=\frac{\frac{dx}{dt}}{\frac{dx}{dt}}=\frac{dx}{ds} $，同理有  $ \cos\beta=\frac{dy}{ds} $

⑥原点为奇点 正向L绕原点一周，当 $ a_{2}=-b_{1} $， $ a_{1}C_{2}=C_{1}b_{2} $时  $ \oint_{L}\frac{(a_{1}x+a_{2}y)dx+(b_{1}x+b_{2}y)dy}{c_{1}x^{2}+c_{2}y^{2}} $ ( $ c_{1}>0,c_{2}>0 $) =  $ \frac{-2a_{2}\pi}{\sqrt{c_{1}c_{2}}} $

## 三、第一型曲面积分

 $ \iint_{D}f(x,y,z)dS=\lim_{x\to0}\frac{n}{24}f(x_{1},\eta_{1},\zeta_{1})\Delta S_{1} $，入为各小块曲面直径的最大值

## 人计算

投数点不能重合否则转投另一平面或分成若干曲面

①投影化为二重 对单值函数 $ z=x(x,y) $，有 $ dS=\sqrt{1+x^{2}+z^{2}}dxdy $ (没有±)

柱面 $ x^{2}+y^{2}=R^{2} $，有 $ ds=\frac{R}{\sqrt{R^{2}-x^{2}}}dx dz $ 球面 $ x^{2}+y^{2}+z^{2}=R^{2} $， $ ds=\frac{R}{\sqrt{R^{2}-x^{2}}}dx dy $ 锥面 $ z=\sqrt{x+y^{2}} $， $ ds=\sqrt{2}dx dy $

### 2应用

曲面面积  $ S = \iint_{D_y} \sqrt{H^2 x^2 + 2y^2} \, dx \, dy $ 重心  $ \overline{x} = \frac{\iint_{D_y} x p \, dS}{\frac{1}{2} \iint_{D_y} p \, dS} $ 逆用： $ \iint_{D_y} x \, ds = \overline{x} \cdot S $ 转动惯量  $ I_x = \frac{1}{2} (y^2 + z^2) \, p \, ds $

四、第二型曲面积分

 $ \overrightarrow{n}^{2}=(\cos\alpha_{1}\cos\beta_{1}\cos\gamma) $

 $ \overrightarrow{dS}=(\alpha_{1}d\alpha_{2}d\beta_{2}d\gamma) $

通过记的通量  $ \overrightarrow{F}\cdot d\overrightarrow{s}=\overrightarrow{F}\cdot d\overrightarrow{s}=\overrightarrow{F}\cdot\overrightarrow{n}^{2}dS=\frac{1}{2}(p_{1}d\alpha_{2}d\beta_{2}+q_{1}d\alpha_{2}d\beta_{2}+q_{2}d\alpha_{2}d\beta_{2}+d\alpha_{2}d\gamma) $

1. 计算

①对称性例：乙关于 $ x_{02} $对称，则 $ \frac{5}{2}x^{2}\geq d\geq d x=0 $，因为A处为 $ x(-x)^{2}\geq(-d\geq d x) $，或者用通量理解

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//e37b5176-5247-43fa-abe2-d88a7ce76b84/markdown_3/imgs/img_in_image_box_898_707_1056_864.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A43Z%2F-1%2F%2Fe0df58bd29f61eb6064ca837b18d02301a7f1deac16c5b0ca57f9704d77e7c78" alt="Image" width="13%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//e37b5176-5247-43fa-abe2-d88a7ce76b84/markdown_3/imgs/img_in_image_box_898_707_1056_864.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A43Z%2F-1%2F%2Fe0df58bd29f61eb6064ca837b18d02301a7f1deac16c5b0ca57f9704d77e7c78" alt="Image" width="13%" />

(d在x上投影为负)

 $ \overrightarrow{dS} $

 $ \overrightarrow{A_{1}B} $ 通量

流入为负

流出为正

</div>


</div>


②分别投影  $ \frac{\sqrt{2}}{2}R(x,y,z)dx dy=\pm\frac{\sqrt{2}}{2}R[x,y,z(x,y)]dx dy $，向上、前、右时取正.

为单值函数(投影点不重合)

③转换投影  $ \frac{\iint p d y d z + q d z d x + R d x d y}{} $ =  $ \pm\frac{\iint(-p z x^{2}-q z y^{2}+R)d x d y}{} $，其中  $ \vec{r} = \pm\frac{(-z x^{2},-z y,1)}{\sqrt{1+z x^{2}+z y^{2}}} $ 上、前、右取证

证： $ I = \iint_{D} F \cdot \vec{n} d S = \iint_{D} (P, Q, R) \cdot \left[\pm\frac{(z x_{1}, z y_{1},1)}{\sqrt{1+z x_{1}^{2}+z y_{1}^{2}}}\right] \cdot d S = \pm\iint_{D}(P, Q, R) \cdot (-z x_{1},-z y,1)d x d y $

④高斯有界闭区域，P、Q、R一阶偏导连续，取外侧，则 $ P d y d z + Q d z d x + R d x d y = \iint_{D}(P_{x}^{\prime}+Q_{y}^{\prime}+R_{z}^{\prime})d V $ 若除奇点外 $ \overrightarrow{F}=0 $，则换奇点的面取同侧，有 $ \iint_{D}=\frac{5}{22} $

⑤ 联系  $ \frac{\iint\limits_{D}(cos\alpha+cos\beta+R\cos\gamma)ds}{2\pi}\cdot dS=\iint\limits_{D}pdxdz+qdzdx+Rdxdy=\iint\limits_{D}\vec{r}\cdot\vec{n}ds=\pm\iint\limits_{D}\vec{r}\cdot\frac{\Delta F}{\sqrt{2}}\cdot\frac{\Delta F}{\sqrt{2}}\cdot dxdy $

其中  $ \cos\alpha\cos\beta\cos\gamma=\frac{(-t_{x}^{1},-t_{y}^{1},1)}{\sqrt{1+\frac{t_{x}^{2}+t_{y}^{2}}{2}}} $ (取上(则))  $ ds=\frac{dx dy}{\cos\gamma}=\frac{d\pi d x}{\cos\beta}=\frac{d\pi d y}{\cos\sqrt{1+\frac{t_{x}^{2}+t_{y}^{2}}{2}}} $

## 五、总结

格林  $ \oint_{\partial D} \overrightarrow{F} \cdot d\overrightarrow{r} = \iint_{D} (\overrightarrow{OXF}) \cdot \overrightarrow{F} d\sigma $ 斯托克斯  $ \oint_{\partial D} \overrightarrow{F} \cdot d\overrightarrow{r} = \iint_{D} (\overrightarrow{OXF}) \cdot \overrightarrow{n} dS $

高斯  $ \oint_{\partial D} \overrightarrow{F} \cdot \overrightarrow{n} dS = \iint_{D} \overrightarrow{O} \cdot \overrightarrow{F} dV $ 转换投影  $ \iint_{D} \overrightarrow{F} \cdot d\overrightarrow{s} = \iint_{D} \overrightarrow{F} \cdot \overrightarrow{n} dS $

#### 曲线曲面积分-A

1.  $ \oint_{S}y^{2}dx+\frac{1}{2}dy+x^{2}dz $,  $ I:x^{2}+y^{2}+z^{2}=1 $ 与  $ x^{2}=x(z>0) $ 的交线，从 x 轴正向着 I 的方向为逆时针.

解：记它为  $ z=\sqrt{x^{2}+y^{2}}=x $ 所截的曲面， $ I=-2\iint\left(\cos\alpha+x\cos\beta+y\cos\gamma\right)ds $，其中， $ \left(\cos\alpha,\cos\beta,\cos\gamma\right)=\frac{(x,y,z)}{\sqrt{x^{2}+y^{2}}} $，故  $ z=-2\iint\frac{x^{2}+y^{2}+z^{2}}{\sqrt{x^{2}+y^{2}+z^{2}}}ds=-2\iint\left(x\cdot\sqrt{x^{2}+y^{2}}\cdot\frac{1}{\sqrt{x^{2}+y^{2}}}dx dy=-\frac{\pi}{4}\right) $

或自 $ I=\sqrt{-2zdy d\theta-2\sqrt{2}dz dx} $， $ -2ydxdy $与 $ \overrightarrow{n}=(\frac{x}{2},\frac{y}{2},1) $转为 $ I=\iint_{M}(-2dx dy) $

2. 质点在力  $ F = \{ x, 2x, xy \}  $ 下沿直线从原点运动到  $ \frac{x^{2}}{a^{2}} + \frac{y^{2}}{b^{2}} + \frac{z^{2}}{c^{2}} $ 第 I 工厂限的点 M( $ x_{1}, y_{1} $, S). 当 S ∩ N 时，F ∩ N 做功 W 最大

解：设  $ \left\{\begin{array}{l} x=5t \\ y=n t \\ z=5t \end{array}\right. $ (0≤t≤1)，则  $ W=\int_{0}^{1} yz dx+2xy dy+xy dz=\xi_{1}S $ 当  $ (\xi, \eta, \zeta)=\frac{1}{\sqrt{3}}(a, b, c) $ 时  $ W_{max}=\frac{a b c}{3\sqrt{3}} $.

3. L为 $ x^{2}+y^{2}+z^{2}=1 $与 $ x+y+z=0 $的交线，则 $ \oint_{L}xyds= $

解① $ (x+y+2)^{2}-(x^{2}+y^{2}+2) $得 $ xy+yz+2x=-\frac{1}{2} $，则 $ I=-\frac{1}{6}\oint_{L}ds=-\frac{1}{6}\cdot2\pi\cdot1=-\frac{\pi}{3} $

②消得 $ x^{2}+xy+y^{2}=\frac{1}{2} $，即 $ \frac{3}{4}x^{2}+(y+\frac{x}{2})^{2}=\frac{1}{2} $令 $ \left\{\begin{array}{l}x=\sqrt{\frac{2}{3}}\cos t\\y=\frac{\sqrt{2}}{2}\sin t-\frac{1}{16}\cos t\end{array}\right. $则 $ z=-\frac{1}{\sqrt{2}}\sin t-\frac{1}{16}\cos t $， $ I=\int_{0}^{2\pi}(\frac{\sin t\cos t}{\sqrt{3}}-\frac{\cos^{2}t}{3})dt=-\frac{\pi}{3} $

4.(1) 已知  $ z = \sqrt{x^2 + y^2} (z \leq z \leq 2) $ 下侧， $ f(x) $ 连续，求  $ I = \int_{0}^{x} [x(xy) + 2x - y] \, dy \, dz + [y(xy) + 2y + x] \, dz \, dx + [z(xy) + 2] \, dx \, dy $

(2) 已知  $ z = |x^2 - 2y|^2 $ (230) 上侧， $ f(x) $ 连续，求  $ I = \int_{0}^{x} 2y^2 f(x + y) \, dy \, dz + xy \left[ \frac{1}{4} - f(x - y) \right] \, dz \, dx + (z - xy^2) \, dx \, dy $

解：(1)  $ \frac{x^2 + y^2 - 2z = 0}{2} = 0 $,  $ \overrightarrow{n} = (x, y, -2) $,  $ (\cos\alpha, \cos\beta, \cos2) = \frac{(x, y, -2)}{\sqrt{x^2 + y^2 + z^2}} $,  $ I = \int_{0}^{2} \frac{(x^2 + y^2 - 2z^2 - f(x + y) + 2x^2 + y^2 - 2)}{x^2 + y^2 + z^2} \, ds = \frac{1}{\sqrt{2}} \iint_{D} \sqrt{x^2 + y^2} \, ds $.

 $ \iint_{D} \sqrt{x^2 + y^2} \, dx \, dy = \int_{0}^{2\pi} d\theta \int_{0}^{2} r^2 \, dY = \frac{14}{3}\pi $

(2)  $ \cos\alpha, \cos\beta, \cos\gamma = \frac{(2x, 4y, -1)}{4(x^2 + (y^2 + 1) + 1)} $,  $ \cos\beta = 2x $,  $ \cos\gamma = 4y $,  $ I = \iint_{D} \left[ 2y^2 f(x + y) \cos\alpha + x y \left[ \frac{1}{4} - f(x - y) \right] \cos\beta + x y \left[ \frac{1}{4} - f(x - y) \right] \cos\gamma \right] $

 $ + z - xy^2 \int_{0}^{1} dx dy = \iint_{D} 4xy^2 \left[ f(x + y) - f(x - y) \right] + (1 - x^2 - 2y^2) dx dy = \iint_{D} 1 - x^2 - 2y^2 dx dy = \frac{1}{2} \iint_{D} \frac{1}{2} dx dy = \int_{0}^{1} r^3 dx = \frac{\pi}{4} = \frac{\sqrt{2}}{4} $

关于奇函数

### 5. 求  $ x^{2} + y^{2} = a^{2} $ 夹在 x - z = 0 与 z = 0 之间的面积

解: ①  $ S_{1}=\int_{4}^{2}ds=\int_{4}^{2}x^{2}\cosxdx=a^{2}\Rightarrow S=4S_{1}=4a^{2} $

②  $ x^{2}+y^{2}=a^{2} $ 得  $ dS=\frac{a}{\sqrt{a^{2}-x^{2}}}d_{2}dx $,  $ S=4S_{1}=4\int_{0}^{a}dx\int_{0}^{x}\frac{a}{\sqrt{a^{2}-x^{2}}}dz=4a^{2} $

注：母线平行于z轴，准线在Oxy面上的柱面被曲面 $ z=f(x,y)\geq0 $所截，部分面积为 $ S=\int_{L}f(x,y)ds $

6. 点 $ A(0,1) $对点M的引力大小为 $ \frac{k}{r}(k>0,y=1AM) $，M沿 $ y=\sqrt{2x^{2}} $自 $ B(2,0) $运动到 $ O(0,0) $，求A对M的引力所做的功

解  $ \overrightarrow{F}=\frac{k}{r^{2}}\frac{\sqrt{M+1}}{|M+1|}=k\frac{-x^{2}+(-1-y)^{2}}{[x^{2}+(-1-y)^{2}]^{2}} $， $ W=-k\int_{\theta_{0}}^{\frac{1}{2}}\frac{x dx-(1-y)dy}{[x^{2}+(1+y)^{2}]^{2}}=k\left(1-\frac{1}{\sqrt{5}}\right) $

 $ =k\int_{0}^{2}\frac{x dx}{(x+1)^{2}}\cdot\frac{2x}{2x}=\frac{2x}{3} $ 换线为 $ \overrightarrow{BO} $

7. 络原点闭曲线  $ L $， $ \oint_{L} \frac{(ax)dx + 2xy dy}{2x^{2} + y^{4}} = C $。证明：右半平面任意闭曲线  $ L_{1} $ 有  $ \oint_{L_{1}} \frac{\varphi(y)dx + 2xy dy}{2x^{2} + y^{4}} = 0 $

证: 在  $ L_{1} $ 上取 M, N, 则  $ \oint_{L_{1}} = \oint_{L_{2}} + \int_{L_{3}} + \int_{L} = 0 $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_0/imgs/img_in_image_box_880_203_1037_318.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A40Z%2F-1%2F%2Fa0940c14ac8121d27d4836becda95254f000bc8ad81ed4984dff7e9059c625f5" alt="Image" width="13%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_0/imgs/img_in_image_box_880_203_1037_318.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A40Z%2F-1%2F%2Fa0940c14ac8121d27d4836becda95254f000bc8ad81ed4984dff7e9059c625f5" alt="Image" width="13%" />

 $ L_{1} $

 $ L_{3} $

 $ L_{2} $

</div>


</div>


8. 求  $ \iint_{D} \frac{ds}{x^2 + y^2} = 2 \cdot x^2 + y^2 = R^2 $ (2:  $ 0 \leq x \leq h $ 2=h>0 之间的圆柱面)

解 设  $ y O_z $,  $ D_{yz} = \sqrt{R^2 + y^2} \leq R $, 则  $ \frac{N}{2} = \frac{N}{4} + \frac{N}{2} = 2 \cdot \frac{N}{D_{yz}} \cdot \frac{1}{R^2 + z^2} \cdot \frac{R}{\sqrt{R^2 + y^2}} \cdot dydz = 2R \int_{R \sqrt{R^2 + y^2}}^{R} \frac{dy}{R^2 + z^2} = 2 \pi \arctan \frac{h}{R} $

9. 已知  $ z = 2 - x^2 - y^2 (x, y \geq 0) $ 被  $ x^2 + y^2 = 1 $ 所截上侧， $ I = \iint_{D} y z dx dy + 2x dy dz + xy dz dx $

解  $ I = \iint_{D} y z + 2x - 2x + xy - 2y dx dy = \iint_{D} 2x^2 (2 - x^2 - y^2) dx dy + \iint_{D} (2y - x^2 - y^2 + 2xy^2) dx dy = I_1 + I_2 $, 而  $ I_1 = 2 \iint_{D} x^2 + y^2 dx dy - \iint_{D} (x + y)^2 dx dy = \frac{\pi}{4} - \frac{\pi}{12} = \frac{\pi}{6} $.  $ I_2 = \iint_{D} (2y - y^2 + x^2) dx dy = \int_0^{\frac{\pi}{2}} d\theta \int_0^1 2y^2 \sin\theta - y^4 \sin^3\theta + y^4 \sin^2\theta \cos\theta d\theta = \frac{3}{5} $, 故  $ I = \frac{\pi}{6} + \frac{3}{5} $

10.  $ P: \begin{cases} x^{2} + y^{2} = 2a^{2} \\ y = x \tan \theta \end{cases} (a > 0, -\frac{\pi}{2} < \theta < \frac{\pi}{2} \text{ 且 } \theta \neq 0)  $，从  $ x $ 轴正向看工顺时针，求  $ I(\theta) = \frac{\phi}{2}(y - 2)dx + (z - x)dy + (x - y)dz $ 的最大值

解：①  $ x^{2} = \tan \theta $，故  $ \theta > 0 $ 时， $ \overrightarrow{r} = (-\sin \theta, \cos \theta, 0) $， $ \theta < 0 $ 时  $ \overrightarrow{r} = (\sin \theta, -\cos \theta, 0) $，①  $ I = \frac{\sqrt{3}}{2} \times \frac{\cos \theta}{2} = \frac{0}{2} d s = 2 \sqrt{(\sin \theta - \cos \theta) d s} $

其中平面  $ S $ 面积为  $ \pi r^{2} = \pi a^{2} $（由  $ k = a, d = 0 $ 和  $ r = a $）故  $ I = 2\pi a^{2}(\sin \theta - \cos \theta) $， $ I(\theta) < I(\frac{\pi}{2}) = 2\pi a^{2} $ ②  $ I = \frac{1}{2} \left| \frac{\sin \theta - \cos \theta}{2} \right| d s = 2\pi a^{2}(\cos \theta - \sin \theta) $， $ I(\theta)_{\max} = I(-\frac{\pi}{4}) = 2\sqrt{2}\pi a^{2} $

② 可令  $ \left\{\begin{array}{l} x = a \cos \alpha \cos \theta \\ y = a \cos d \sin \theta \\ z = a \sin \alpha \end{array}\right. $ ①  $ \frac{\pi}{2} < \theta < 0 $， $ a: 0 \to 2\pi $ ②  $ 0 < \theta < \frac{\pi}{2} $， $ a: 2\pi \to 0 $

11. 锥曲己的顶点为原点，准线为曲线  $ I: \left\{ \begin{array}{l} z = y^{2} \\ x = 1 \end{array} \right. $ ( $ M \leq 1 $) (1) 求  $ I: (2) I = \frac{1}{2} 2x^{2} dy dz + xy dz dx + (z+1) dx dy $ (已取上侧)

解：(1) 设  $  l(x, y, z)  $，则  $  L: \frac{x}{x} = \frac{y}{y} = \frac{z}{z}  $ 与正交点为  $ (1, \frac{y}{x}, \frac{z}{x}) $ 满足  $  z = y^{2}  $，即  $ \frac{z}{x} = \frac{y^{2}}{x} $，故  $  y^{2} = xz  $ （ $  |y| \leq 1  $， $  0 \leq x \leq 1  $， $  0 \leq z \leq x  $）

(2)①向xOy投影为三角形，则 $ I=\frac{\int_{0}^{1}2x^{2}\cdot\frac{y^{2}}{x^{2}}+xy\left(-\frac{2y}{x}\right)+\frac{y^{2}}{x}+1\ dx dy=\int_{0}^{1}dx\int_{x}^{2}\frac{y^{2}}{x}+1\ dy=\frac{11}{9} $

②向yOZ投影，则 $ I=\frac{\int_{0}^{1}2x^{2}+xy\left(-\frac{2y}{x}\right)+(2+\frac{y}{x})^{2}\ dy}{2} $

注：由(0,0,0)到 $ (1,t,t^{2}) $的直线可参数化为 $ (x,y,z)=(1,\lambda,t,\lambda t^{2}) $ ( $ 0\leq\lambda\leq1,|t|\leq1 $)，于是，

向yO投影时由 $ x=\lambda=\frac{y^{2}}{2}\leq1 $知 $ z\geq y^{2} $，由 $ |t|=\left|\frac{2}{y}\right|\leq|x|0 $知 $ z\leq|y| $，加上 $ |t|\leq1 $和 $ D_{2} $： $ \left\{\begin{aligned}&|y|\leq1\\ &y\leq z\leq|y|\end{aligned}\right. $

向xOy投影时，由 $ x=\lambda $知 $ 0\leq x\leq1 $，由 $ |y|=|\lambda t|=|x|t\leq x $知 $ -x\leq y\leq x $，故 $ D_{xy}=\begin{cases}0\leq x\leq1\\x\leq y\leq x\end{cases} $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_0/imgs/img_in_image_box_914_1019_1043_1150.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A40Z%2F-1%2F%2F4ff0afa5a1db7b7b057b57ea8937568484da68f4c1987385e7e4ad0d8d992557" alt="Image" width="10%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_0/imgs/img_in_image_box_914_1019_1043_1150.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A40Z%2F-1%2F%2F4ff0afa5a1db7b7b057b57ea8937568484da68f4c1987385e7e4ad0d8d992557" alt="Image" width="10%" />

 $ z $

 $ \rightarrow y $

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_0/imgs/img_in_image_box_887_1148_1048_1247.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A40Z%2F-1%2F%2F2ddc5a9c1171598ffe14e10b577c9142b1410dd32bbeae2489d468cceaa1494b" alt="Image" width="13%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_0/imgs/img_in_image_box_887_1148_1048_1247.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A40Z%2F-1%2F%2F2ddc5a9c1171598ffe14e10b577c9142b1410dd32bbeae2489d468cceaa1494b" alt="Image" width="13%" />

 $ y \leftarrow \overrightarrow{0} $

</div>


</div>


12. 乙为柱面  $ x^{2}+z^{2}=4 $ 被锥面  $ z=\sqrt{x^{2}+y^{2}} $ 所截部分，求  $ I=\frac{1}{2}(x^{3}+\sqrt{3-2})ds $

解：已知于 $ x>0 $， $ y=2 $对称知 $ \iint\limits_{D}xy^{3}ds=0 $， $ \iint\limits_{D}\sqrt{2-2}ds=4\iint\limits_{D}\sqrt{2-2}ds $（记为已第一封限）由 $ 2z^{2}-y^{2}=4z $与 $ x\geq0,y\geq0,0\leq z\leq4 $知 $ Dy_{3}=\begin{cases}0\leq y\leq\sqrt{2-2^{2}-48}\\2\leq z\leq4\end{cases} $，又由 $ x=\sqrt{4-2^{2}-2^{2}} $知 $ dS=\frac{2}{\sqrt{4-2^{2}}}dydS $于是 $ I=4\int_{2}^{4}\frac{2\sqrt{2-2^{2}}}{(\sqrt{4-2^{2}})^{2}}dxdy=8\sqrt{2}\int_{2}^{4}\frac{8-2}{\sqrt{4-2^{2}}}d\varepsilon=16\sqrt{2}\int_{2}^{2}2t^{2}dt=\frac{128}{3} $

13. (23. 三、改)  $ d f(x, y) = \frac{x dy - y dx}{x^{2} + y^{2}} $,  $ f(1, 1) = \frac{\pi}{4} $, 则  $ f(-1, -1) =  $

解：无论取  $ f = a r \arctan \frac{x}{2} $ 或  $ \frac{\pi}{2} - a r \arctan \frac{x}{2} $ 都必跨过 x，y 轴而不连续，于是考虑取途径点 C.

设  $ BC $ 上  $ f_1 = -\arctan\frac{x}{y} + c_1 $,  $ AC $ 上  $ f_2 = \arctan\frac{x}{x} + c_2 $, 由 (1) 处连续知  $ \left\{\begin{array}{l} c_1 + \frac{x}{4} = c_2 - \frac{x}{4} \\ c_2 = 0 \end{array}\right. $ 于是  $ c_1 = -\frac{\pi}{2} $,  $ f(-1, -1) = -\frac{3}{4}\pi $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_950_407_1049_500.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F1404371c539fdfd1fd2070f0ec2d53941b8c0907ab9adf00a6bcedc4b17914c8" alt="Image" width="8%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_950_407_1049_500.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F1404371c539fdfd1fd2070f0ec2d53941b8c0907ab9adf00a6bcedc4b17914c8" alt="Image" width="8%" />

 $ y \uparrow A(1,1) $
 $ B(-1,1) $  $ C(1,-1) $

</div>


</div>


14. 求  $ 2x + 2y + z - 1 = 0 $ 被柱面  $ x^{2} + y^{2} = 1 (0 \leq z \leq 1) $ 所截面积

解交线受柱面所限，故平面高度亦受此限制，故  $ z=1-2x-2y \in [0,1] $，其投影为  $ D_{1}: O \leq x+y \leq \frac{1}{2} $，圆柱  $ D_{2}: x^{2}+y^{2} \leq 1 $，于是

截面投影为交集  $ D = D_{1} \cap D_{2} $ 显然  $ S = \int_{0}^{1} \sqrt{48r^{2} + \frac{1}{2}r^{2}} = 3S_{D} $，而 D 可分为半圆一弓形 = 半圆一（扇 AOB -  $ \Delta AOB $），由  $ OP = \frac{1}{2\sqrt{2}} $ 知  $ AB = \frac{\sqrt{14}}{2} $

 $ \angle AOP = \arcsin\frac{\sqrt{14}}{4}, \angle AOB = 2\arcsin\frac{\sqrt{14}}{4} $，于是  $ S = 3S_{0} = 3\left(\frac{\pi}{2} - \left(\frac{2\arcsin\frac{\sqrt{14}}{4}}{2}\right)^{2} - \frac{1}{2}\cdot\frac{\sqrt{2}}{4}\cdot\frac{\sqrt{14}}{2}\right) $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_713_635_849_775.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F336a445042ba622d8edf7039bee0a811ac8de21127dad0d054cff1b6a42bf63e" alt="Image" width="11%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_713_635_849_775.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F336a445042ba622d8edf7039bee0a811ac8de21127dad0d054cff1b6a42bf63e" alt="Image" width="11%" />

3

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_868_635_1020_762.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F826e6625b6088e54a49e8287fd3424a0f68143e052e4970e9672d88bdfaed760" alt="Image" width="12%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_868_635_1020_762.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F826e6625b6088e54a49e8287fd3424a0f68143e052e4970e9672d88bdfaed760" alt="Image" width="12%" />

A
P
D
B

</div>


</div>


 $$ =3(\frac{\pi}{2}+\frac{\sqrt{7}}{8}-\arcsin\frac{\sqrt{14}}{4}) $$ 

注：还有一种情况的投影：与侧、底面相交

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_511_777_734_871.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F68f09d487a2e1254a54017bb5a1e430339b5f6a46102d97d9f43d8c1ac7063a5" alt="Image" width="18%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_511_777_734_871.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F68f09d487a2e1254a54017bb5a1e430339b5f6a46102d97d9f43d8c1ac7063a5" alt="Image" width="18%" />

 $ B $  $ \uparrow $

</div>


</div>


<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_905_802_957_870.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2Fa73cbdfdfa78c5d5c5478ff4a8b304601714d89ba249f074179eb467639a917e" alt="Image" width="4%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_905_802_957_870.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2Fa73cbdfdfa78c5d5c5478ff4a8b304601714d89ba249f074179eb467639a917e" alt="Image" width="4%" />

 $ C_{2}H_{5}OH $

</div>


</div>


(最简单的是仅与侧面交，则根有圆短轴=圆柱直径，长轴= $ \frac{\text{直径}}{\sin\theta}=\frac{\frac{\text{直径}}{\cos d}}{} $，其中θ为平面与圆柱轴线夹角，α为平面倾角)

结论：曲面 $ E_{1}=(x,y)\in D $，柱面 $ E_{2}=(x,y)\in D_{2} $，则 $ D=D_{1}\cap D_{2} $为已被 $ E_{2} $所截部分的投影区域

15. 证明：简单曲面  $  C: F(x, y, z) = 0  $，已在某一坐标面的投影为 D 且 D 的单位法向量为  $ \overrightarrow{p} $ 且  $ \overrightarrow{vF} - \overrightarrow{p} \neq 0 $，则

 $$ S=\iint\limits_{D}\frac{1}{\vert\Delta F-\overrightarrow{P}\vert}\cdot d\sigma $$ 

证：由二面角公式： $ \vert\cos\theta\vert=\frac{S_{\triangle ABCD}}{S_{\triangle COD}}=\frac{\vert\overrightarrow{P}\cdot\overrightarrow{n}\vert}{\vert\overrightarrow{P}\cdot\overrightarrow{n}\vert}=\vert\overrightarrow{P}\cdot\overrightarrow{n}\vert $ 知  $ S=\frac{S_{AB}}{\vert\cos\theta\vert}=\frac{1}{\vert\overrightarrow{n}\cdot\overrightarrow{P}\vert} $

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_870_1047_959_1125.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F0202ca65d5e6579731fdd12a5e82fbf84214a203f755057d9596ad62e6bc5de8" alt="Image" width="7%" />

<div style="text-align: center;"><img src="https://pplines-online.bj.bcebos.com/deploy/official/paddleocr/pp-ocr-vl-16-online//82b40a10-77d4-47f3-b0a0-41f2a5ba729b/markdown_1/imgs/img_in_image_box_870_1047_959_1125.jpg?authorization=bce-auth-v1%2FALTAKDN8mY5KlNI7zaRpLmOqrw%2F2026-06-22T15%3A12%3A41Z%2F-1%2F%2F0202ca65d5e6579731fdd12a5e82fbf84214a203f755057d9596ad62e6bc5de8" alt="Image" width="7%" />

 $ \overrightarrow{P} $

</div>


</div>


对于显式方程  $ z = z(x, y) $，有  $ \overrightarrow{n} = \frac{(-z_{x}^{1}, -z_{y}^{1}, 1)}{\sqrt{1 + z_{x}^{12} + z_{y}^{12}}} $， $ \overrightarrow{p} = (0, 0, 1) $，于是  $ S = \iint_{\Omega} \frac{1}{\vert\overrightarrow{n} \cdot \overrightarrow{p}\vert} d\sigma = \iint_{\Omega} \sqrt{1 + z_{x}^{12} + z_{y}^{12}} \, dx dy $

对于隐式方程  $ F(x, y, z) $，有  $ \overrightarrow{n} = \frac{\Delta F}{|OF|} $，于是  $ S = \frac{\iint\limits_{D} \frac{1}{\left|\frac{\Delta F}{10F}\right|} d\sigma}{|\frac{\Delta F}{10F}| \cdot \overrightarrow{p}|} d\sigma = \iint\limits_{D} \frac{10F|}{|OF| \cdot \overrightarrow{p}|} d\sigma $

对于非简单曲面，应分片考虑.

对于  $ F(x,y,z)=0 $,  $ G(x,y,z)=0 $, 消 2 得  $ H(x,y)=0 $, 即为二曲面围成区域的截面投影.

注： $ \frac{f}{d}f dS=\iint_{D}\frac{f}{\left|\overrightarrow{r}-\overrightarrow{p}\right|}d\sigma=\iint_{D}f\cdot\frac{|\overrightarrow{r}||D|}{\left|\overrightarrow{r}-\overrightarrow{p}\right|}d\sigma $  $ \iint_{D}f\cdot dS=\iint_{D}\overrightarrow{f}\cdot\overrightarrow{d}dS=\iint_{D}\overrightarrow{f}\cdot\frac{\overrightarrow{DF}}{|\overrightarrow{DF}-\overrightarrow{p}|}\cdot\frac{|\overrightarrow{DF}|}{|\overrightarrow{DF}-\overrightarrow{p}|}d\sigma=\iint_{D}f\cdot\frac{\overrightarrow{DF}}{|\overrightarrow{DF}-\overrightarrow{p}|}d\sigma $ 注意正的负值

16. 曲线工为  $ z=\sqrt{4-x^{2}-8y^{2}} $ 与 z=y 交线上从  $ (2,0,0) $ 到  $ (1,\frac{\sqrt{3}}{3},\frac{\sqrt{3}}{3}) $ 的一段弧， $ f(u) $ 连续.

(1) 求工在  $ (x, y, z) $ 处单位切向量

(2) 计算  $ I = \int_{S} \frac{1}{\sqrt{2}x^{2} + 9y^{2}} \left\{ \left[ \frac{x}{2} (1xy) + 3y \right] (-3y) + \left[ 3y f(x,y) + x^{2} + \frac{3}{2} z \ln x \right] \right\} \frac{x}{3} $

解: (1) ① 由  $ \overrightarrow{n_{1}} = \left( \frac{x}{8}, \frac{8y}{2}, 1 \right) $ 与  $ \overrightarrow{n_{2}} = (0, -1, 1) $ 相交  $ \left( -8y - 2, x, x \right) \Rightarrow \left( \frac{-9y}{2}x, x, x \right) $

②  $ \left\{ \begin{array}{l} x = 2 \cos \theta \\ y = 2 \cdot \frac{3}{2} \sin \theta, \quad \overrightarrow{c} = (-2 \sin \theta, \frac{2}{3} \cos \theta, \frac{2}{3} \cos \theta) \end{array} \right. $

 $ = \overrightarrow{t_{0}} = \left( \frac{-3y, \frac{x}{3}, \frac{2}{3} \sqrt{3}}{-\frac{3}{2}x^{2} + 4y^{2}} \right) $

(2)  $ I = \int_{S} \left[ \frac{x}{2} f(x,y) + 3y \right] dx + \left[ 3y f(x,y) + x^{2} + \frac{3}{2} z f(x,y) \right] dy = \int_{0}^{\frac{\pi}{3}} -4\sin^{2} \theta + \frac{8}{3}\cos^{3} \theta d\theta = \frac{3\sqrt{3}}{2} - \frac{2\pi}{3} $

注:  $ \int_{S} \overrightarrow{r} - d\overrightarrow{r} = \int_{L} (P\cos x + Q\cos y + R\cos x) ds $

若 L 满足  $ y = z $，则  $ dy = dz $， $ \int_{S} pdx + qdy + kdz = \int_{L} pdx + (Q + p)dy $

