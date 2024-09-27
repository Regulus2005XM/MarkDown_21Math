# the运算符等

[【Tools】Markdown数学符号&amp;公式（史上最全公式表）_markdown求和符号-CSDN博客](https://blog.csdn.net/Darlingqiang/article/details/119620489)

若需要显示更大或更小的字符，在符号前插入 `\large`​ 或 `\small`​ 命令。

若找不到需要的符号，使用 [Detexify](http://detexify.kirelabs.org/classify.html) 来画出想要的符号。

* (1)．关系运算符

|输入|显示|输入|显示|输入|显示|输入|显示|
| --------------| ------| ----------------| ------| ---------------| ------| ----------------| -------|
|\\pm|±|\\times|×|\\div|÷|\\mid|∣|
|\\nmid|∤|\\cdot|⋅|\\circ|∘|\\ast|∗|
|\\bigodot|⨀|\\bigotimes|⨂|\\bigoplus|⨁|\\leq|≤|
|\\geq|≥|\\neq|≠|\\approx|≈|\\equiv|≡|
|\\sum|∑|\\prod|∏|\\coprod|∐|\\backslash|\\|

求和符号等在公式块中上下标正常显示，在行级公式中显示在右上角和右下角

注意使用\mid，而不是直接输入|

使用中文“丨gun”这样的东西有概率让你在debug时发疯:D

* (2)．集合运算符

|输入|显示|输入|显示|输入|显示|
| ---------------| ------| ---------------| ------| ---------------| ------|
|\\emptyset|∅|\\in|∈|\\notin|∉|
|\\subset|⊂|\\supset|⊃|\\subseteq|⊆|
|\\supseteq|⊇|\\bigcap|⋂|\\bigcup|⋃|
|\\bigvee|⋁|\\bigwedge|⋀|\\biguplus|⨄|

\\varnothing$\varnothing$  

\subsetneq$\subsetneq$ \supsetneq$\supsetneq$  

* (3)．对数运算符

|输入|显示|输入|显示|输入|显示|
| ----------| -------| ---------| ------| ---------| ------|
|\\log|log⁡|\\lg|lg⁡|\\ln|ln⁡|

* (4)．三角运算符

|输入|显示|输入|显示|输入|显示|
| ------------------| -------| ----------| -------| --------------| -------|
|30\^\\circ|30∘|\\bot|⊥|\\angle A|∠A|
|\\sin|⁡sin|\\cos|cos⁡|\\tan|tan⁡|
|\\csc|⁡csc|\\sec|sec⁡|\\cot|cot⁡|

\top

* (5)．微积分运算符

|输入|显示|输入|显示|输入|显示|
| --------------| -------| ------------| ------| ------------| ------|
|\\int|∫|\\iint|∬|\\iiint|∭|
|\\partial|∂|\\oint|∮|\\prime|′|
|\\lim|lim⁡|\\infty|∞|\\nabla|∇|

使用\iiint代替\int\int\int的写法

* (6)．逻辑运算符

|输入|显示|输入|显示|
| ---------------------| ------| ----------------| ------|
|\\because|∵|\\therefore|∴|
|\\forall|∀|\\exists|∃|
|\\not\\subset|<br />|\\not\<|<br />|
|\\not\>|<br />|\\not\=|<br />|

* (7)．戴帽符号

|输入|显示|输入|显示|
| ----------------| ------| ---------------------| ------|
|\\hat{xy}|<br />|\\widehat{xyz}|<br />|
|\\tilde{xy}|<br />|\\widetilde{xyz}|<br />|
|\\check{x}|<br />|\\breve{y}|<br />|
|\\grave{x}|<br />|\\acute{y}|<br />|

\dot ddot

### 未分类

{n \choose m\} ${n\choose m}$ 排列

\pmod $a\pmod b$  

\ldots \cdots $\ldots \cdots$  

\overline{} \underline{} $\overline{A} \underline{B}$  

\\star $\star$  

 \dot{} $\dot{x}$ \ddot $\ddot{x}$ \mid | $x\mid x\ and\ x|x$  

* (8)．连线符号

|输入|显示|
| --------------------------------------------------------------------| ------|
|\\fbox{a+b+c+d}||
|\\overleftarrow{a+b+c+d}||
|\\overrightarrow{a+b+c+d}||
|\\overleftrightarrow{a+b+c+d}||
|\\underleftarrow{a+b+c+d}||
|\\underrightarrow{a+b+c+d}||
|\\underleftrightarrow{a+b+c+d}||
|\\overline{a+b+c+d}||
|\\underline{a+b+c+d}||
|\\overbrace{a+b+c+d}\^{Sample}||
|\\underbrace{a+b+c+d}\_{Sample}||
|\\overbrace{a+\\underbrace{b+c}\_{1.0}+d}\^{2.0}||
|\\underbrace{a\\cdot a\\cdots a}\_{b\\text{ times}}|<br />|

* (9)．箭头符号

|输入|显示|输入|显示|
| ----------------------------| ------| --------------------------------------| ------|
|\\uparrow|↑|\\Uparrow|⇑|
|\\downarrow|↓|\\Downarrow|⇓|
|\\leftarrow|←|\\Leftarrow|⇐|
|\\rightarrow or \\to|→|\\Rightarrow|⇒|
|\\leftrightarrow|↔|\\Leftrightarrow|⇔|
|\\longleftarrow|⟵|\\Longleftarrow or \\impliedby|⟸|
|\\longrightarrow|⟶|\\Longrightarrow or \\implies|⟹|
|\\longleftrightarrow|⟷|\\Longleftrightarrow or \\iff|⟺|
|\\mapsto|↦|\\underrightarrow{1℃/min}|<br />|

\\upharpoonright $\upharpoonright$
