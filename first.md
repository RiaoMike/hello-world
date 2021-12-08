# 这个标题拥有 1 个 id {#my_id}
**这会是 粗体 的文字**
__这会是 粗体 的文字__
*这会是 斜体 的文字*
_这会是 斜体 的文字_
- Item 1
- Item 2
  - Item 2a
  - Item 2b
  - 正如 Kanye West 所说：

> We're living the future so
> the present is our past.
> ---

连字符print

---

星号

---

下划线
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
30^th^
Content [^1]

[^1]: Hi! This is a footnote
_[HTML]: Hyper Text Markup Language
_[W3C]: World Wide Web Consortium
The HTML specification
is maintained by the W3C.
$f(x)=sin(x)+12$
$$\sum_{n=1}^{100}sin(x)*cos(x)$$
因此你说这是不可能的 $x^2 + y^{12} = 1$
$\displaystyle \int_0^1x{\rm d}x \quad  \iint_{D_{xy}}$ 卧槽，我真的打出积分了
$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$
## This is an headline
**这是加粗** *这是斜体* ***这是斜体加粗***

---
*******
上面这些都是分割线  
要换行的话输入两个空格或者一个\\\
就行也可以用\<br/>,<br/>
你看现在就是另一行  
>This is quote  
>>and the quote can be 嵌套
你可以偷懒，只打一个\>符号

如果你要**退出**嵌套，多打一个空行就行  
+ 选项一
* 选项二（无序列表可以使用+，-，*）
- 选项三
1. 下面是有序列表
2. 有序列表则是用数字加上英文的句号

同理，要**退出**列表的话，多打一行空行就行  
*注意 列表标志符号与内容之间要有空格*  
1|2|3
---|:--:|---:
niaho|eerhj|sjid

$\longrightarrow \int_1^5{x^3}{\rm d}x$  
$sup_{x\in A}$

% 编号格式
\CTEXsetup[name={第,章}]{section}
% 把章节放在左侧，而不是居中
\CTEXsetup[format={\zihao{-3}\raggedright\bfseries}]{section}
\begin{document}
   \section{这是第一章节}
   Hello World
   \subsection{这是次级章节}
   Hello World
   \section{这是第二章节}
   Hello World
\end{document}
```
print('hello')
for i in [1,2,3,'rui']:
print i
```

$$ 
i \hbar \frac{\partial}{\partial t} \Psi(\boldsymbol{r}, t)=-\frac{\hbar^{2}}{2 m} \nabla^{2} \Psi(\boldsymbol{r}, t)+V(\boldsymbol{r}, t) \Psi(\boldsymbol{r}, t)
$$

I really like to go swimming

And ~~so~~ on.[^我也来写一个脚注]

[^我也来写一个脚注]：你好我们以后在一起！

  >python
  print('hello')

[nihao][1]

[1]:http://www.google.com/

$\displaystyle
\int_{\partial\Sigma}P{\rm d}x+Q{\rm d}y+R{\rm d}z=\iint_\Sigma 
\begin{vmatrix}
{\rm d}y{\rm d}z & {\rm d}z{\rm d}x & {\rm d}x{\rm d}y \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
P & Q & R\\
\end{vmatrix}
$  
下面列出Green,Gauss and Stokes定理
1. $\displaystyle\int_{\partial D}P{\rm d}x+Q{\rm d}y=\iint_D
\left(\frac{\partial Q}{\partial x}-\frac{\partial P}{\partial y}\right){\rm d}x{\rm d}y$
2. $\displaystyle\iiint_\Omega \left(\frac{\partial P}{\partial x}+\frac{\partial Q}{\partial y}+\frac{\partial R}{\partial z} \right){\rm d}x{\rm d}y{\rm d}z=\iint_{\partial\Omega}P{\rm d}y{\rm d}z+Q{\rm d}z{\rm d}x+R{\rm d}x{\rm d}y$

$$

在这里我做了一次修改
我做了第二次修改，notes