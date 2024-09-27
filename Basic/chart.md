# the矩阵图表

用&表示需要对齐的内容

在\\\\\\\后使用[ex][2ex]等修改行高

```tex
$ \begin{matrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{matrix} $
$ \begin{pmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{pmatrix} $
$ \begin{bmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{bmatrix} $
$ \begin{Bmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{Bmatrix} $
$ \begin{vmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{vmatrix} $
$ \begin{Vmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{Vmatrix} $
```

$\begin{matrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{matrix}$​$\begin{pmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{pmatrix}$​$\begin{bmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{bmatrix}$​$\begin{Bmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{Bmatrix}$​$\begin{vmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{vmatrix}$​$\begin{Vmatrix} 1 & 2 \\\\ 3 & 4 \\\\ \end{Vmatrix}$  

```TeX
$$
        \begin{pmatrix}
        1 & a_1 & a_1^2 & \cdots & a_1^n \\\\
        1 & a_2 & a_2^2 & \cdots & a_2^n \\\\
        \vdots & \vdots & \vdots & \ddots & \vdots \\\\
        1 & a_m & a_m^2 & \cdots & a_m^n \\\\
        \end{pmatrix}
$$
```

$$
\begin{pmatrix}
        1 & a_1 & a_1^2 & \cdots & a_1^n \\\\
        1 & a_2 & a_2^2 & \cdots & a_2^n \\\\
        \vdots & \vdots & \vdots & \ddots & \vdots \\\\
        1 & a_m & a_m^2 & \cdots & a_m^n \\\\
        \end{pmatrix}
$$

```TeX
$$
        \left[
            \begin{array}{cc|c}
              1&2&3\\\\
              4&5&6
            \end{array}
        \right]
$$
```

其中 `cc|c`​ 代表在一个三列矩阵中的第二和第三列之间插入分割线。

$$
\left[
            \begin{array}{cc|c}
              1&2&3\\\\
              4&5&6
            \end{array}
        \right]
$$

```TeX
$$
\left\{ 
    \begin{array}{c}
        a_1x+b_1y+c_1z &=d_1 \\\\ 
        a_2x+b_2y+c_2z &=d_2 \\\\ 
        a_3x+b_3y+c_3z &=d_3 \\\\
    \end{array}
\right. 
$$
```

$$
\left\{ 
    \begin{array}{c}
        a_1x+b_1y+c_1z &=d_1 \\\\ 
        a_2x+b_2y+c_2z &=d_2 \\\\ 
        a_3x+b_3y+c_3z &=d_3 \\\\
    \end{array}
\right.
$$

```tex
$$
\begin{array}{c|lcr}
n & \text{左对齐} & \text{居中对齐} & \text{右对齐} \\\\
\hline
1 & 0.24 & 1 & 125 \\\\
2 & -1 & 189 & -8 \\\\
3 & -20 & 2000 & 1+10i
\end{array}
$$
```

$$
\begin{array}{c|lcr}
n & \text{左对齐} & \text{居中对齐} & \text{右对齐} \\\\
\hline
1 & 0.24 & 1 & 125 \\\\
2 & -1 & 189 & -8 \\\\
3 & -20 & 2000 & 1+10i
\end{array}
$$

使用一行 `\require{AMScd}`​ 语句来允许交换图表的显示。 声明交换图表后，语法与矩阵相似，在开头使用 `begin{CD}`​，在结尾使用 `end{CD}`​，在中间插入图表元素，每个元素之间插入 `&`​ ，并在每行结尾处使用`\\`​ 。

Copy

```tex
$$
\begin{CD}
    A  @>a>>  B \\\\
    @VbVV   @VVcV \\\\
    C  @>>d>  D
\end{CD}
$$
```

$$
\begin{CD}
    A  @>a>>  B \\\\
    @VbVV   @VVcV \\\\
    C  @>>d>  D
\end{CD}
$$

其中，`@>>>`​ 代表右箭头、`@<<<`​ 代表左箭头、`@VVV`​ 代表下箭头、`@AAA`​ 代表上箭头、`@=`​ 代表水平双实线、`@|`​ 代表竖直双实线、`@.`​代表没有箭头。 在 `@>>>`​ 的 `>>>`​ 之间任意插入文字即代表该箭头的注释文字。

Copy

```tex
$$
\begin{CD}
    A @>>> B @>{\text{very long label}}>> C \\\\
    @. @AAA @| \\\\
    D @= E @<<< F
\end{CD}
$$
```

$$
\begin{CD}
    A @>>> B @>{\text{very long label}}>> C \\\\
    @. @AAA @| \\\\
    D @= E @<<< F
\end{CD}
$$

在本例中， “very long label“自动延长了它所在箭头以及对应箭头的长度。

‍
