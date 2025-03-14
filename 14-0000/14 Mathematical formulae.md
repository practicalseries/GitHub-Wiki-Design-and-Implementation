<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="../ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-1400--ecg-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 

# 14<!--        🟥H1🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Mathematical formulae

GitHub flavoured Markdown supports the use of mathematical formulae (this was introduced in 2022). These are entered using the TeX and LaTeX<a name="rn-01" href="#fn-01"><!-- 🟨FOOTNOTE LINK🟨--><sup>💠1</sup></a> (more LaTeX than TeX).

LaTeX is a programming syntax used to encode a particular formula; it is a plain-text format. This is then interpreted by the JavaScript application MathJax which renders the formula in the correct, visually pleasing, form.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 14.1<!--     🟥H2🟥--><img width="080" height="1" src="https://psop.uk/wi-s" alt="Spacer">An overview of LaTex

The following is the LaTeX syntax for the common quadratic equation:

<table name="t-14-01" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
$x=\frac{-b\pm\sqrt{b^2—4ac}}{2a}$
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="middle" height="90"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

$\Large x=\frac{-b\pm\sqrt{b^2—4ac}}{2a}$

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 14.1 &mdash; GitHub Wiki rendering of a mathematical formulae
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

This rendering is carried out by the <a href="https://www.practicalseries.com/1001-webdevelopment/22-00-equations.html#js--000000">MathJax</a> application. It’s pretty good and does an excellent job of rendering equations.

I’ve used MathJax before, in fact I have a website about it <a href="https://www.mathjax.org/">here</a>.
The thing I liked about MathJax was that it could use AsciiMath<a name="rn-02" href="#fn-02"><!-- 🟨FOOTNOTE LINK🟨--><sup>💠2</sup></a>. 

AsciiMath is quite intuitive to use, this for example, is the quadratic formulae in AsciiMath form *(the one we all know from O levels)*: 

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡-->`x=(-b +- sqrt(b^2 — 4ac))/(2a)`

MathJax would render it as:

<p align="center">${\Large x=\frac{-b\pm\sqrt{b^2—4ac}}{2a}}$</p>

AsciiMath is a bit hard to explain, but at an intuitive level you can see exactly how it works. If you wanted to type that equation as a single line on a computer terminal, I bet you would come up with something similar to the above.

***When I found out the GitHub was using MathJax I had high hopes that it could use AsciiMath, but it can’t. It only uses the LaTeX syntax and this is harder to understand, see the next section.***

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 14.2<!--     🟥H2🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Inserting an inline formula

GitHub supports inline equations. Inline equations appear in the middle of a line or paragraph of text.

Inline equations are surrounded by an open dollar sign and left brace `${` and closed with a right brace and a dollar sign `}$`:


<table name="t-14-01" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
GitHub supports the use of inline formulae; they can be inserted directly into a paragraph of text
and the equation will be given the correct amount of spacing above and below. This is an inline 
formula ${x=\frac{-b\pm\sqrt{b^2—4ac}}{2a}}$, it sits in the middle of a line. The text 
surrounding the equation is normal body text, the equation itself uses a mathematical 
font that forms part of MathJax.
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

GitHub supports the use of inline formulae; they can be inserted directly into a paragraph of text
and the equation will be given the correct amount of spacing above and below. This is an inline 
formula ${x=\frac{-b\pm\sqrt{b^2—4ac}}{2a}}$, it sits in the middle of a line. The text 
surrounding the equation is normal body text, the equation itself uses a mathematical 
font that forms part of MathJax.

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 14.1 &mdash; Inline equation
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Generally, the use of inline equations should be restricted to single line type equations (${x=b+1}$ for example), these look better. Where more complex equations are used, the difference in line spacing gives an untidy appearance.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 14.2.1<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Alternative delimiter

The normal delimiter for an inline equation is `${...}$` . An alternative is to start the equation with a dollar, backtick (<code>$&#x0060;</code>) and end it with a backtick dollar (<code>&#x0060;$</code>).

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->


## 14.3<!--     🟥H2🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">A formula block

A formula block is an equation that appears outside any text and may span multiple lines:

<table name="t-14-02" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

````md
Lorem ipsum dolor sit amet, consectetur adipiscing elit.

```math
x=\frac{-b\pm\sqrt{b^2—4ad}}{2a}
```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. 

````
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 

${x=\frac{-b\pm\sqrt{b^2—4ad}}{2a}}$

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 14.2 &mdash; Block equation
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Alternatively, the equation can be surrounded by a double dollar sign (`$$`) or the dollar, braces arrangement (`${...}$`):


<table name="t-14-03" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
Lorem ipsum dolor sit amet, consectetur adipiscing elit.

$$x=\frac{-b\pm\sqrt{b^2—4ad}}{2a}$$

${x=\frac{-b\pm\sqrt{b^2—4ad}}{2a}}$

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
````
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

$$x=\frac{-b\pm\sqrt{b^2—4ad}}{2a}$$

${x=\frac{-b\pm\sqrt{b^2—4ad}}{2a}}$

Lorem ipsum dolor sit amet, consectetur adipiscing elit. 

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 14.3 &mdash; Block equation alternative
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Both do exactly the same thing.

> [!IMPORTANT]<!-- IMPORTANT ALERT -->
> ***Block equations must have a blank line above and below.***

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 14.4<!--     🟥H2🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Some example formulae

The following section gives some insights into the LaTeX equation syntax, this section has several examples of the types of equations that are possible:

<table name="t-e01" align="left"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row --> <tr>
                        <th width="567" align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
</table>
<br clear="all">

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e01" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
f(x)=(x+a)(x+b)
```
````
<p> </p></td></tr>
</table><br>

```math
f(x)=(x+a)(x+b)
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e02" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\cos(2\theta\phi) = \cos^2 \theta\phi - \sin^2 \theta\phi
```
````
<p> </p></td></tr>
</table><br>

```math
\cos(2\theta\phi) = \cos^2 \theta\phi - \sin^2 \theta\phi
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e03" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
(a+b)\left[1-\frac{b}{a+b}\right]=a
```
````
<p> </p></td></tr>
</table><br>

```math
(a+b)\left[1-\frac{b}{a+b}\right]=a
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e04" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\int_a^bu\frac{d^2v}{dx^2}\,dx
=\left.u\frac{dv}{dx}\right|_a^b
-\int_a^b\frac{du}{dx}\frac{dv}{dx}\,dx
```
````
<p> </p></td></tr>
</table><br>

```math
\int_a^bu\frac{d^2v}{dx^2}\,dx
=\left.u\frac{dv}{dx}\right|_a^b
-\int_a^b\frac{du}{dx}\frac{dv}{dx}\,dx
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e05" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\tilde f(\omega)=\frac{1}{2\pi}
\int_{-\infty}^\infty f(x)e^{-i\omega x}\,dx
```
````
<p> </p></td></tr>
</table><br>

```math
\tilde f(\omega)=\frac{1}{2\pi}
\int_{-\infty}^\infty f(x)e^{-i\omega x}\,dx
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e06" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}
```
````
<p> </p></td></tr>
</table><br>

```math
x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- EQU TABLE START -->
<table name="t-e07" align="left"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- MD row -->     <tr><td width="567"  align="left"><!-- 🔴MARKDOWN BELOW🔴 -->

````md
```math
x = a_0 + \frac{1}{\displaystyle a_1
+ \frac{1}{\displaystyle a_2
+ \fr
```
````
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
</table><br>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

```math
x = a_0 + \frac{1}{\displaystyle a_1
+ \frac{1}{\displaystyle a_2
+ \frac{1}{\displaystyle a_3 + a_4}}}
```
<br clear="all">
<!--- EQU TABLE END -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e08" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\begin{bmatrix}
1 & x & 0 \\
0 & 1 & -1
\end{bmatrix}\begin{bmatrix}
1 \\
y \\
1
\end{bmatrix}
=\begin{bmatrix}
1+xy \\
y-1
\end{bmatrix}
```
````
<p> </p></td></tr>
</table><br><br><br><br>

```math
\begin{bmatrix}
1 & x & 0 \\
0 & 1 & -1
\end{bmatrix}\begin{bmatrix}
1 \\
y \\
1
\end{bmatrix}
=\begin{bmatrix}
1+xy \\
y-1
\end{bmatrix}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e09" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\begin{pmatrix}
2 & 3 & 4\\
5 & 6 & 7\\
8 & 9 & 10 \end{pmatrix} v = 0
```
````
<p> </p></td></tr>
</table><br><br>

```math
\begin{pmatrix}
2 & 3 & 4\\
5 & 6 & 7\\
8 & 9 & 10 \end{pmatrix} v = 0

```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e10" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\begin{matrix}
-2 & 1 & 0 & 0 & \cdots & 0 \\
1 & -2 & 1 & 0 & \cdots & 0 \\
0 & 1 & -2 & 1 & \cdots & 0 \\
0 & 0 & 1 & -2 & \ddots & \vdots \\
\vdots & \vdots & \vdots & \ddots & \ddots & 1 \\
0 & 0 & 0 & \cdots & 1 & -2
\end{matrix}
```
````
<p> </p></td></tr>
</table><br><br>

```math
\begin{matrix}
-2 & 1 & 0 & 0 & \cdots & 0 \\
1 & -2 & 1 & 0 & \cdots & 0 \\
0 & 1 & -2 & 1 & \cdots & 0 \\
0 & 0 & 1 & -2 & \ddots & \vdots \\
\vdots & \vdots & \vdots & \ddots & \ddots & 1 \\
0 & 0 & 0 & \cdots & 1 & -2
\end{matrix}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e11" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
|x|=\begin{cases}
x, & \text{if }x\geq 0 \\
-x, & \text{if }x< 0
\end{cases}
```
````
<p> </p></td></tr>
</table><br><br>

```math
|x|=\begin{cases}
x, & \text{if }x\geq 0 \\
-x, & \text{if }x< 0
\end{cases}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e12" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
(1+x)^n = \sum_{i=0}^n {n \choose i} x^i
```
````
<p> </p></td></tr>
</table>

```math
(1+x)^n = \sum_{i=0}^n {n \choose i} x^i
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e13" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
e^x = 1 + x + \frac{x^2}{2} + \cdots = \sum_{n\geq 0} \frac{x^n}{n!}
```
````
<p> </p></td></tr>
</table><br>

```math
e^x = 1 + x + \frac{x^2}{2} + \cdots = \sum_{n\geq 0} \frac{x^n}{n!}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e14" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\frac{n!}{k!(n-k)!} = \binom{n}{k}
```
````
<p> </p></td></tr>
</table><br>

```math
\frac{n!}{k!(n-k)!} = \binom{n}{k}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table name="t-e13" align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
e^x = 1 + x + \frac{x^2}{2} + \cdots = \sum_{n\geq 0} \frac{x^n}{n!}
```
````
<p> </p></td></tr>
</table><br>

```math
e^x = 1 + x + \frac{x^2}{2} + \cdots = \sum_{n\geq 0} \frac{x^n}{n!}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="850"  align="left">
<sup>Table 14.4 &mdash; Example equations</sup>
<p> </p></td></tr>
</table>
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 14.5<!--     🟥H2🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">LaTeX syntax

LaTeX isn’t quite as intuitive as AsciiMath, but the more you use it, the more you begin to understand it.

LaTeX uses some mathematical operators: `+`, `-`, `=`, and brackets and parenthesis `[]`, `()` directly, just by typing them on a keyboard. Other things are entered as commands: `\sqrt` these always start with a backslash character.


Some commands have arguments, these are encompassed in braces `{}`. For example the fraction is in the form:

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\frac{a}{a+b}
```
````
<p> </p></td></tr>
</table><br>

```math
\frac{a}{a+b}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

Everything in the first pair of braces is numerator (top of the fraction) and everything in the second pair of braces is the denominator (bottom of the fraction).

Brackets and parenthesis do not by default expand vertically to encompass whatever is inside them:

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
x=(1-\frac{a}{b})
```
````
<p> </p></td></tr>
</table><br>

```math
x=(1-\frac{a}{b})
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

Here, the parentheses remain small and the fraction extends above and below it.

To make brackets and parenthesis resize, precede the left bracket/parenthesis with `\left` and the right bracket/parenthesis with `\right`:


<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
x=\left(1-\frac{a}{b}\right)
```
````
<p> </p></td></tr>
</table><br>

```math
x=\left(1-\frac{a}{b}\right)
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

To use braces (instead of brackets or parentheses), precede the brace with a backslash:

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
x=\{1-\frac{a}{b}\}
```
````
<p> </p></td></tr>
</table><br>

```math
x=\{1-\frac{a}{b}\}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

\left and \right: work in the same way as before:

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
x=\left\{1-\frac{a}{b}\right\}
```
````
<p> </p></td></tr>
</table><br>

```math
x=\left\{1-\frac{a}{b}\right\}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

Various characters (Greek characters, symbols &c.) have their own commands:


<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\tau\epsilon\chi
```
````
<p> </p></td></tr>
</table><br><br>

```math
\tau\epsilon\chi
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

Superscript characters are preceded with `^` and subscript with `_`. Thes can also be used for limits on operators:

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
a^b
```
````
<p> </p></td></tr>
</table><br><br>

```math
a^b
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
a_b
```
````
<p> </p></td></tr>
</table><br><br>

```math
a_b
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

With limits, it is like this:

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\sum_{n=1}^{\infty}
```
````
<p> </p></td></tr>
</table><br>

```math
\sum_{n=1}^{\infty}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->


<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="567"  align="left">

````md
```math
\int_{0}^{\infty}
```
````
<p> </p></td></tr>
</table><br>

```math
\int_{0}^{\infty}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

The braces are not always required, but where multiple limit (or super/subscript) terms are used, it is best to put the braces around everything that should be a limit or super/subscript.

The following tables summarise all the LaTeX commands:


### 14.5.1<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Greek lowercase

<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\alpha
```
</td>
<td><code>\alpha</code></td>
<td>

```math
\gamma
```
</td>
<td><code>\gamma</code></td>
<td>

```math
\omega
```
</td>
<td><code>\omega</code></td>
<td>

```math
\sigma
```
</td>
<td><code>\sigma</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\beta
```
</td>
<td><code>\beta</code></td>
<td>

```math
\iota
```
</td>
<td><code>\iota</code></td>
<td>

```math
\phi
```
</td>
<td><code>\phi</code></td>
<td>

```math
\tau
```
</td>
<td><code>\tau</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\chi
```
</td>
<td><code>\chi</code></td>
<td>

```math
\kappa
```
</td>
<td><code>\kappa</code></td>
<td>

```math
\varphi
```
</td>
<td><code>\varphi</code></td>
<td>

```math
\theta
```
</td>
<td><code>\theta</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\delta
```
</td>
<td><code>\delta</code></td>
<td>

```math
\lambda
```
</td>
<td><code>\lambda</code></td>
<td>

```math
\pi
```
</td>
<td><code>\pi</code></td>
<td>

```math
\upsilon
```
</td>
<td><code>\upsilon</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\epsilon
```
</td>
<td><code>\epsilon</code></td>
<td>

```math
\mu
```
</td>
<td><code>\mu</code></td>
<td>

```math
\psi
```
</td>
<td><code>\psi</code></td>
<td>

```math
\xi
```
</td>
<td><code>\xi</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\eta
```
</td>
<td><code>\eta</code></td>
<td>

```math
\nu
```
</td>
<td><code>\nu</code></td>
<td>

```math
\rho
```
</td>
<td><code>\rho</code></td>
<td>

```math
\zeta
```
</td>
<td><code>\zeta</code></td>
<!-- ROW END --></tr>
</table><br><br><br>

### 14.5.2<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Greek uppercase, variations and Hebrew

<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\Delta
```
</td>
<td><code>\Delta</code></td>
<td>

```math
\Psi
```
</td>
<td><code>\Psi</code></td>
<td>

```math
\varepsilon
```
</td>
<td><code>\varepsilon</code></td>
<td>

```math
\aleph
```
</td>
<td><code>\aleph</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Gamma
```
</td>
<td><code>\Gamma</code></td>
<td>

```math
\Sigma
```
</td>
<td><code>\Sigma</code></td>
<td>

```math
\varkappa
```
</td>
<td><code>\varkappa</code></td>
<td>

```math
\beth
```
</td>
<td><code>\beth</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Lambda
```
</td>
<td><code>\Lambda</code></td>
<td>

```math
\Theta
```
</td>
<td><code>\Theta</code></td>
<td>

```math
\Phi
```
</td>
<td><code>\Phi</code></td>
<td>

```math
\daleth
```
</td>
<td><code>\daleth</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Omega
```
</td>
<td><code>\Omega</code></td>
<td>

```math
\Upsilon
```
</td>
<td><code>\Upsilon</code></td>
<td>

```math
\Pi
```
</td>
<td><code>\Pi</code></td>
<td>

```math
\gimel
```
</td>
<td><code>\gimel</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Xi
```
</td>
<td><code>\Xi</code></td>
<td>

```math
\vartheta
```
</td>
<td><code>\vartheta</code></td>
<td>

```math
\varepsilon
```
</td>
<td><code>\varepsilon</code></td>
<td>

</td>
<td></td>
<!-- ROW END --></tr>
</table><br><br><br>

### 14.5.3<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Mathematical constructions

<table align="center">
<tr><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\frac{abc}{xyz}
```
</td>
<td><code>\frac{abc}{xyz}</code></td>
<td>

```math
\overline{abc}
```
</td>
<td><code>\overline{abc}</code></td>
<td>

```math
\overrightarrow{abc}
```
</td>
<td><code>\overrightarrow{abc}</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
f’
```
</td>
<td><code>f’</code></td>
<td>

```math
\underline{abc}
```
</td>
<td><code>\underline{abc}</code></td>
<td>

```math
\overleftarrow{abc}
```
</td>
<td><code>\overleftarrow{abc}</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\sqrt{abc}
```
</td>
<td><code>\sqrt{abc}</code></td>
<td>

```math
\widehat{abc}
```
</td>
<td><code>\widehat{abc}</code></td>
<td>

```math
\overbrace{abc}
```
</td>
<td><code>\overbrace{abc}</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\sqrt[n]{abc}
```
</td>
<td><code>\sqrt[n]{abc}</code></td>
<td>

```math
\widetilde{abc}
```
</td>
<td><code>\widetilde{abc}</code></td>
<td>

```math
\underbrace{abc}
```
</td>
<td><code>\underbrace{abc}</code></td>
<!-- ROW END --></tr>
</table><br><br><br>


### 14.5.4<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Variable sized delimiters

<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
|
```
</td>
<td><code>|</code></td>
<td>

```math
\{
```
</td>
<td><code>\{</code></td>
<td>

```math
\Uparrow
```
</td>
<td><code>\Uparrow</code></td>
<td>

```math
/
```
</td>
<td><code>/</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\vert
```
</td>
<td><code>\vert</code></td>
<td>

```math
\}
```
</td>
<td><code>\}</code></td>
<td>

```math
\uparrow
```
</td>
<td><code>\uparrow</code></td>
<td>

```math
\backslash
```
</td>
<td><code>\backslash</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Vert
```
</td>
<td><code>\Vert</code></td>
<td>

```math
\langle
```
</td>
<td><code>\langle</code></td>
<td>

```math
\Downarrow
```
</td>
<td><code>\Downarrow</code></td>
<td>

</td>
<td></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
(
```
</td>
<td><code>(</code></td>
<td>

```math
\rangle
```
</td>
<td><code>\rangle</code></td>
<td>

```math
\downarrow
```
</td>
<td><code>\downarrow</code></td>
<td>

</td>
<td></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
)
```
</td>
<td><code>)</code></td>
<td>

```math
\lfloor
```
</td>
<td><code>\lfloor</code></td>
<td>

```math
\llcorner
```
</td>
<td><code>\llcorner</code></td>
<td>

</td>
<td></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
[
```
</td>
<td><code>[</code></td>
<td>

```math
\rfloor
```
</td>
<td><code>\rfloor</code></td>
<td>

```math
\lrcorner
```
</td>
<td><code>\lrcorner</code></td>
<td>

</td>
<td></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
]
```
</td>
<td><code>]</code></td>
<td>

```math
\lceil
```
</td>
<td><code>\lceil</code></td>
<td>

```math
\llcorner
```
</td>
<td><code>\ulcorner</code></td>
<td>

</td>
<td></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

</td>
<td></td>
<td>

```math
\rceil
```
</td>
<td><code>\rceil</code></td>
<td>

```math
\urcorner
```
</td>
<td><code>\urcorner</code></td>
<td>

</td>
<td></td>
<!-- ROW END --></tr>
</table>

Precede the first delimiter with \left and last delimiter with \right to match the height of their content (note \left and \right must be paired). E.g.:


<table align="center">
<tr><td width="100" align="center">Sym</td><th width="328" align="left">Command</th><td width="100" align="center">Sym</td><th width="328" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\left(1-\frac{a}{b}\right)
```
</td>
<td><code>\left(1-\frac{a}{b}\right)</code></td>
<td>

```math
\left[1-\frac{a}{b}\right]
```
</td>
<td><code>\left[1-\frac{a}{b}\right]</code></td>
<!-- ROW END --></tr>
</table><br><br><br>


### 14.5.5<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Variable sized symbols

<table align="center">
<tr><td width="100" align="center">Sym</td><th width="328" align="left">Command</th><td width="100" align="center">Sym</td><th width="328" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\sum
```
</td>
<td><code>\sum</code></td>
<td>

```math
\biguplus
```
</td>
<td><code>\biguplus</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\prod
```
</td>
<td><code>\prod</code></td>
<td>

```math
\bigcap
```
</td>
<td><code>\bigcap</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\coprod
```
</td>
<td><code>\coprod</code></td>
<td>

```math
\bigcup
```
</td>
<td><code>\bigcup</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\int
```
</td>
<td><code>\int</code></td>
<td>

```math
\bigoplus
```
</td>
<td><code>\bigoplus</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\oint
```
</td>
<td><code>\oint</code></td>
<td>

```math
\bigotimes
```
</td>
<td><code>\bigotimes</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\iint
```
</td>
<td><code>\iint</code></td>
<td>

```math
\bigodot
```
</td>
<td><code>\bigodot</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\iiint
```
</td>
<td><code>\iiint</code></td>
<td>

```math
\bigvee
```
</td>
<td><code>\bigvee</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\lim
```
</td>
<td><code>\lim</code></td>
<td>

```math
\bigwedge
```
</td>
<td><code>\bigwedge</code></td>
<!-- ROW END --></tr>
</table><br><br><br>



### 14.5.6<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Variable sized symbols with limits

<table align="center">
<tr><td width="100" align="center">Sym</td><th width="328" align="left">Command</th><td width="100" align="center">Sym</td><th width="328" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\sum_{def}^{abc}x_y^z
```
</td>
<td><code>\sum_{def}^{abc}x_y^z</code></td>
<td>

```math
\biguplus_{n=1}^{10}A_n
```
</td>
<td><code>\biguplus_{n=1}^{10}A_n</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\prod_{def}^{abc} x_y^z
```
</td>
<td><code>\prod_{def}^{abc} x_y^z</code></td>
<td>

```math
\bigcap_{n=1}^{10}A_n
```
</td>
<td><code>\bigcap_{n=1}^{10}A_n</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\coprod_{n=1}^{\infty} x_y^z
```
</td>
<td><code>\coprod_{n=1}^{\infty} x_y^z</code></td>
<td>

```math
\bigcup_{n=1}^{10}A_n
```
</td>
<td><code>\bigcup_{n=1}^{10}A_n</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\int_{0}^{\infty} x^2 dx
```
</td>
<td><code>\int_{0}^{\infty} x^2 dx</code></td>
<td>

```math
\bigoplus_{b\epsilon B}R_b
```
</td>
<td><code>\bigoplus_{b\epsilon B}R_b</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\oint_{c_1} \frac{-y}{x^2 +y^2}dr
```
</td>
<td><code>\oint_{c_1} \frac{-y}{x^2 +y^2}dr</code></td>
<td>

```math
\bigotimes_{b\epsilon B}R_b
```
</td>
<td><code>\bigotimes_{b\epsilon B}R_b</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\iint_{w}^{k} dV
```
</td>
<td><code>\iint_{w}^{k} dV</code></td>
<td>

```math
\bigodot_{b\epsilon B}R_b
```
</td>
<td><code>\bigodot_{b\epsilon B}R_b</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\iiint_{w}^{k} dV
```
</td>
<td><code>\iiint_{w}^{k} dV</code></td>
<td>

```math
\bigvee_{n=1}^{10}A_n
```
</td>
<td><code>\bigvee_{n=1}^{10}A_n</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\lim_{x\to \infty} x^2
```
</td>
<td><code>\lim_{x\to \infty} x^2</code></td>
<td>

```math
\bigwedge_{n=1}^{10}A_n
```
</td>
<td><code>\bigwedge_{n=1}^{10}A_n</code></td>
<!-- ROW END --></tr>
</table><br><br><br>

### 14.5.7<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Standard functions

<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\arccos
```
</td>
<td><code>\arccos</code></td>
<td>

```math
\arcsin
```
</td>
<td><code>\arcsin</code></td>
<td>

```math
\arctan
```
</td>
<td><code>\arctan</code></td>
<td>

```math
\arg
```
</td>
<td><code>\arg</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\cos
```
</td>
<td><code>\cos</code></td>
<td>

```math
\cosh
```
</td>
<td><code>\cosh</code></td>
<td>

```math
\cot
```
</td>
<td><code>\cot</code></td>
<td>

```math
\coth
```
</td>
<td><code>\coth</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\csc
```
</td>
<td><code>\csc</code></td>
<td>

```math
\deg
```
</td>
<td><code>\deg</code></td>
<td>

```math
\det
```
</td>
<td><code>\det</code></td>
<td>

```math
\dim
```
</td>
<td><code>\dim</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\exp
```
</td>
<td><code>\exp</code></td>
<td>

```math
\gcd
```
</td>
<td><code>\gcd</code></td>
<td>

```math
\hom
```
</td>
<td><code>\hom</code></td>
<td>

```math
\inf
```
</td>
<td><code>\inf</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\ker
```
</td>
<td><code>\ker</code></td>
<td>

```math
\lg
```
</td>
<td><code>\lg</code></td>
<td>

```math
\lim
```
</td>
<td><code>\lim</code></td>
<td>

```math
\liminf
```
</td>
<td><code>liminf</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\limsup
```
</td>
<td><code>\limsup</code></td>
<td>

```math
\ln
```
</td>
<td><code>\ln</code></td>
<td>

```math
\log
```
</td>
<td><code>\log</code></td>
<td>

```math
\max
```
</td>
<td><code>\max</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\min
```
</td>
<td><code>\min</code></td>
<td>

```math
\Pr
```
</td>
<td><code>\Pr</code></td>
<td>

```math
\sec
```
</td>
<td><code>\sec</code></td>
<td>

```math
\sin
```
</td>
<td><code>\sin</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\sinh
```
</td>
<td><code>\sinh</code></td>
<td>

```math
\sup
```
</td>
<td><code>\sup</code></td>
<td>

```math
\tan
```
</td>
<td><code>\tan</code></td>
<td>

```math
\tanh
```
</td>
<td><code>\tanh</code></td>
<!-- ROW END --></tr>
</table>

Standard functions should appear as Roman regular characters, not italics.
<br><br><br>

### 14.5.8<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Operators and relational symbols


<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\ast
```
</td>
<td><code>\ast</code></td>
<td>

```math
\pm
```
</td>
<td><code>\pm</code></td>
<td>

```math
\cap
```
</td>
<td><code>\cap</code></td>
<td>

```math
\lhd
```
</td>
<td><code>\lhd</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\star
```
</td>
<td><code>\aaa</code></td>
<td>

```math
\mp
```
</td>
<td><code>\mp</code></td>
<td>

```math
\cup
```
</td>
<td><code>\cup</code></td>
<td>

```math
\rhd
```
</td>
<td><code>\rhd</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\cdot
```
</td>
<td><code>\cdot</code></td>
<td>

```math
\amalg
```
</td>
<td><code>\amalg</code></td>
<td>

```math
\uplus
```
</td>
<td><code>\uplus</code></td>
<td>

```math
\triangleleft
```
</td>
<td><code>\triangleleft</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\circ
```
</td>
<td><code>\circ</code></td>
<td>

```math
\odot
```
</td>
<td><code>\odot</code></td>
<td>

```math
\sqcap
```
</td>
<td><code>\sqcap</code></td>
<td>

```math
\triangleright
```
</td>
<td><code>\triangleright</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\bullet
```
</td>
<td><code>\bullet</code></td>
<td>

```math
\ominus
```
</td>
<td><code>\ominus</code></td>
<td>

```math
\sqcup
```
</td>
<td><code>\sqcup</code></td>
<td>

```math
\unlhd
```
</td>
<td><code>\unlhd</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\bigcirc
```
</td>
<td><code>\bigcirc</code></td>
<td>

```math
\oplus
```
</td>
<td><code>\oplus</code></td>
<td>

```math
\wedge
```
</td>
<td><code>\wedge</code></td>
<td>

```math
\unrhd
```
</td>
<td><code>\unrhd</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\diamond
```
</td>
<td><code>\diamond</code></td>
<td>

```math
\oslash
```
</td>
<td><code>\oslash</code></td>
<td>

```math
\vee
```
</td>
<td><code>\vee</code></td>
<td>

```math
\bigtriangledown
```
</td>
<td><code>\bigtriangledown</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\times
```
</td>
<td><code>\times</code></td>
<td>

```math
\otimes
```
</td>
<td><code>\otimes</code></td>
<td>

```math
\dagger
```
</td>
<td><code>\dagger</code></td>
<td>

```math
\bigtriangleup
```
</td>
<td><code>\bigtriangleup</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\div
```
</td>
<td><code>\div</code></td>
<td>

```math
\wr
```
</td>
<td><code>\wr</code></td>
<td>

```math
\ddagger
```
</td>
<td><code>\ddagger</code></td>
<td>

```math
\setminus
```
</td>
<td><code>\setminus</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\centerdot
```
</td>
<td><code>\centerdot</code></td>
<td>

```math
\Box
```
</td>
<td><code>\Box</code></td>
<td>

```math
\barwedge
```
</td>
<td><code>\barwedge</code></td>
<td>

```math
\veebar
```
</td>
<td><code>\veebar</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\circledast
```
</td>
<td><code>\circledast</code></td>
<td>

```math
\boxplus
```
</td>
<td><code>\boxplus</code></td>
<td>

```math
\curlywedge
```
</td>
<td><code>\curlywedge</code></td>
<td>

```math
\curlyvee
```
</td>
<td><code>\curlyvee</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\circledcirc
```
</td>
<td><code>\circledcirc</code></td>
<td>

```math
\boxminus
```
</td>
<td><code>\boxminus</code></td>
<td>

```math
\Cap
```
</td>
<td><code>\Cap</code></td>
<td>

```math
\Cup
```
</td>
<td><code>\Cup</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\circleddash
```
</td>
<td><code>\circleddash</code></td>
<td>

```math
\boxtimes
```
</td>
<td><code>\boxtimes</code></td>
<td>

```math
\bot
```
</td>
<td><code>\bot</code></td>
<td>

```math
\top
```
</td>
<td><code>\top</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\dotplus
```
</td>
<td><code>\dotplus</code></td>
<td>

```math
\boxdot
```
</td>
<td><code>\boxdot</code></td>
<td>

```math
\intercal
```
</td>
<td><code>\intercal</code></td>
<td>

```math
\rightthreetimes
```
</td>
<td><code>\rightthreetimes</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\divideontimes
```
</td>
<td><code>\divideontimes</code></td>
<td>

```math
\square
```
</td>
<td><code>\square</code></td>
<td>

```math
\doublebarwedge
```
</td>
<td><code>\doublebarwedge</code></td>
<td>

```math
\leftthreetimes
```
</td>
<td><code>\leftthreetimes</code></td>
<!-- ROW END --></tr>
</table><br><br><br>




<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\equiv
```
</td>
<td><code>\equiv</code></td>
<td>

```math
\leq
```
</td>
<td><code>\leq</code></td>
<td>

```math
\geq
```
</td>
<td><code>\geq</code></td>
<td>

```math
\perp
```
</td>
<td><code>\perp</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\cong
```
</td>
<td><code>\cong</code></td>
<td>

```math
\prec
```
</td>
<td><code>\prec</code></td>
<td>

```math
\succ
```
</td>
<td><code>\succ</code></td>
<td>

```math
\mid
```
</td>
<td><code>\mid</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\neq
```
</td>
<td><code>\neq</code></td>
<td>

```math
\preceq
```
</td>
<td><code>\preceq</code></td>
<td>

```math
\succeq
```
</td>
<td><code>\succeq</code></td>
<td>

```math
\parallel
```
</td>
<td><code>\parallel</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\sim
```
</td>
<td><code>\sim</code></td>
<td>

```math
\ll
```
</td>
<td><code>\ll</code></td>
<td>

```math
\gg
```
</td>
<td><code>\gg</code></td>
<td>

```math
\bowtie
```
</td>
<td><code>\bowtie</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\simeq
```
</td>
<td><code>\simeq</code></td>
<td>

```math
\subset
```
</td>
<td><code>\subset</code></td>
<td>

```math
\supset
```
</td>
<td><code>\supset</code></td>
<td>

```math
\Join
```
</td>
<td><code>\Join</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\approx
```
</td>
<td><code>\approx</code></td>
<td>

```math
\subseteq
```
</td>
<td><code>\subseteq</code></td>
<td>

```math
\supseteq
```
</td>
<td><code>\supseteq</code></td>
<td>

```math
\ltimes
```
</td>
<td><code>\ltimes</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\asymp
```
</td>
<td><code>\asymp</code></td>
<td>

```math
\sqsubset
```
</td>
<td><code>\sqsubset</code></td>
<td>

```math
\sqsupset
```
</td>
<td><code>\sqsupset</code></td>
<td>

```math
\rtimes
```
</td>
<td><code>\rtimes</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\doteq
```
</td>
<td><code>\doteq</code></td>
<td>

```math
\sqsubseteq
```
</td>
<td><code>\sqsubseteq</code></td>
<td>

```math
\sqsupseteq
```
</td>
<td><code>\sqsupseteq</code></td>
<td>

```math
\smile
```
</td>
<td><code>\smile</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\propto
```
</td>
<td><code>\propto</code></td>
<td>

```math
\dashv
```
</td>
<td><code>\dashv</code></td>
<td>

```math
\vdash
```
</td>
<td><code>\vdash</code></td>
<td>

```math
\frown
```
</td>
<td><code>\frown</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\models
```
</td>
<td><code>\models</code></td>
<td>

```math
\in
```
</td>
<td><code>\in</code></td>
<td>

```math
\ni
```
</td>
<td><code>\ni</code></td>
<td>

```math
\notin
```
</td>
<td><code>\notin</code></td>
<!-- ROW END --></tr>
</table><br><br><br>




<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\approxeq
```
</td>
<td><code>\approxeq</code></td>
<td>

```math
\leqq
```
</td>
<td><code>\leqq</code></td>
<td>

```math
\geqq
```
</td>
<td><code>\geqq</code></td>
<td>

```math
\lessgtr
```
</td>
<td><code>\lessgtr</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\thicksim
```
</td>
<td><code>\thicksim</code></td>
<td>

```math
\leqslant
```
</td>
<td><code>\leqslant</code></td>
<td>

```math
\geqslant
```
</td>
<td><code>\geqslantcc</code></td>
<td>

```math
\lesseqgtr
```
</td>
<td><code>\lesseqgtr</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\backsim
```
</td>
<td><code>\backsim</code></td>
<td>

```math
\lessapprox
```
</td>
<td><code>\lessapprox</code></td>
<td>

```math
\gtrapprox
```
</td>
<td><code>\gtrapprox</code></td>
<td>

```math
\lesseqqgtr
```
</td>
<td><code>\lesseqqgtr</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\backsimeq
```
</td>
<td><code>\backsimeq</code></td>
<td>

```math
\lll
```
</td>
<td><code>\lll</code></td>
<td>

```math
\ggg
```
</td>
<td><code>\ggg</code></td>
<td>

```math
\gtreqqless
```
</td>
<td><code>\gtreqqless</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\triangleq
```
</td>
<td><code>\triangleq</code></td>
<td>

```math
\lessdot
```
</td>
<td><code>\lessdot</code></td>
<td>

```math
\gtrdot
```
</td>
<td><code>\gtrdot</code></td>
<td>

```math
\gtreqless
```
</td>
<td><code>\gtreqless</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\circeq
```
</td>
<td><code>\circeq</code></td>
<td>

```math
\lesssim
```
</td>
<td><code>\lesssim</code></td>
<td>

```math
\gtrsim
```
</td>
<td><code>\gtrsim</code></td>
<td>

```math
\gtrless
```
</td>
<td><code>\gtrless</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\bumpeq
```
</td>
<td><code>\bumpeq</code></td>
<td>

```math
\eqslantless
```
</td>
<td><code>\eqslantless</code></td>
<td>

```math
\eqslantgtr
```
</td>
<td><code>\eqslantgtr</code></td>
<td>

```math
\backepsilon
```
</td>
<td><code>\backepsilon</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Bumpeq
```
</td>
<td><code>\Bumpeq</code></td>
<td>

```math
\precsim
```
</td>
<td><code>\precsim</code></td>
<td>

```math
\succsim
```
</td>
<td><code>\succsim</code></td>
<td>

```math
\between
```
</td>
<td><code>\between</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\doteqdot
```
</td>
<td><code>\doteqdot</code></td>
<td>

```math
\precapprox
```
</td>
<td><code>\precapprox</code></td>
<td>

```math
\succapprox
```
</td>
<td><code>\succapprox</code></td>
<td>

```math
\pitchfork
```
</td>
<td><code>\pitchfork</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\thickapprox
```
</td>
<td><code>\thickapprox</code></td>
<td>

```math
\Subset
```
</td>
<td><code>\Subset</code></td>
<td>

```math
\Supset
```
</td>
<td><code>\Supset</code></td>
<td>

```math
\shortmid
```
</td>
<td><code>\shortmid</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\fallingdotseq
```
</td>
<td><code>\fallingdotseq</code></td>
<td>

```math
\subseteqq
```
</td>
<td><code>\subseteqq</code></td>
<td>

```math
\supseteqq
```
</td>
<td><code>\csupseteqqcc</code></td>
<td>

```math
\smallfrown
```
</td>
<td><code>\smallfrown</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\risingdotseq
```
</td>
<td><code>\risingdotseq</code></td>
<td>

```math
\sqsubset
```
</td>
<td><code>\sqsubset</code></td>
<td>

```math
\sqsupset
```
</td>
<td><code>\sqsupset</code></td>
<td>

```math
\smallsmile
```
</td>
<td><code>\smallsmile</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\varpropto
```
</td>
<td><code>\varpropto</code></td>
<td>

```math
\preccurlyeq
```
</td>
<td><code>\preccurlyeq</code></td>
<td>

```math
\succcurlyeq
```
</td>
<td><code>\succcurlyeq</code></td>
<td>

```math
\Vdash
```
</td>
<td><code>\Vdash</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\therefore
```
</td>
<td><code>\therefore</code></td>
<td>

```math
\curlyeqprec
```
</td>
<td><code>\curlyeqprec</code></td>
<td>

```math
\curlyeqsucc
```
</td>
<td><code>\curlyeqsucc</code></td>
<td>

```math
\vDash
```
</td>
<td><code>\vDash</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\because
```
</td>
<td><code>\because</code></td>
<td>

```math
\blacktriangleleft
```
</td>
<td><code>\blacktriangleleft</code></td>
<td>

```math
\blacktriangleright
```
</td>
<td><code>\blacktriangleright</code></td>
<td>

```math
\Vvdash
```
</td>
<td><code>\Vvdash</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\eqcirc
```
</td>
<td><code>\eqcirc</code></td>
<td>

```math
\trianglelefteq
```
</td>
<td><code>\trianglelefteq</code></td>
<td>

```math
\trianglerighteq
```
</td>
<td><code>\trianglerighteq</code></td>
<td>

```math
\shortparallel
```
</td>
<td><code>\shortparallel</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\neq
```
</td>
<td><code>\neq</code></td>
<td>

```math
\vartriangleleft
```
</td>
<td><code>\vartriangleleft</code></td>
<td>

```math
\vartriangleright
```
</td>
<td><code>\vartriangleright</code></td>
<td>

```math
\nshortparallel
```
</td>
<td><code>\nshortparallel</code></td>
<!-- ROW END --></tr>
</table><br><br><br>




<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\ncong
```
</td>
<td><code>\ncong</code></td>
<td>

```math
\nleq
```
</td>
<td><code>\nleq</code></td>
<td>

```math
\ngeq
```
</td>
<td><code>\ngeq</code></td>
<td>

```math
\nsubseteq
```
</td>
<td><code>\nsubseteq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nmid
```
</td>
<td><code>\nmid</code></td>
<td>

```math
\nleqq
```
</td>
<td><code>\nleqq</code></td>
<td>

```math
\ngeqq
```
</td>
<td><code>\ngeqq</code></td>
<td>

```math
\nsupseteq
```
</td>
<td><code>\nsupseteq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nparallel
```
</td>
<td><code>\nparallel</code></td>
<td>

```math
\nleqslant
```
</td>
<td><code>\nleqslant</code></td>
<td>

```math
\ngeqslant
```
</td>
<td><code>\ngeqslant</code></td>
<td>

```math
\nsubseteqq
```
</td>
<td><code>\nsubseteqq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nshortmid
```
</td>
<td><code>\nshortmid</code></td>
<td>

```math
\nless
```
</td>
<td><code>\nless</code></td>
<td>

```math
\ngtr
```
</td>
<td><code>\ngtr</code></td>
<td>

```math
\nsupseteqq
```
</td>
<td><code>\nsupseteqq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nshortparallel
```
</td>
<td><code>\nshortparallel</code></td>
<td>

```math
\nprec
```
</td>
<td><code>\nprec</code></td>
<td>

```math
\nsucc
```
</td>
<td><code>\nsucc</code></td>
<td>

```math
\subsetneq
```
</td>
<td><code>\subsetneq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nsim
```
</td>
<td><code>\nsim</code></td>
<td>

```math
\npreceq
```
</td>
<td><code>\npreceq</code></td>
<td>

```math
\nsucceq
```
</td>
<td><code>\nsucceq</code></td>
<td>

```math
\supsetneq
```
</td>
<td><code>\supsetneq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nVDash
```
</td>
<td><code>\nVDash</code></td>
<td>

```math
\precnapprox
```
</td>
<td><code>\precnapprox</code></td>
<td>

```math
\succnapprox
```
</td>
<td><code>\succnapprox</code></td>
<td>

```math
\subsetneqq
```
</td>
<td><code>\subsetneqq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nvDash
```
</td>
<td><code>\nvDash</code></td>
<td>

```math
\precnsim
```
</td>
<td><code>\precnsim</code></td>
<td>

```math
\succnsim
```
</td>
<td><code>\succnsim</code></td>
<td>

```math
\supsetneqq
```
</td>
<td><code>\supsetneqq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nvdash
```
</td>
<td><code>\nvdash</code></td>
<td>

```math
\lnapprox
```
</td>
<td><code>\lnapprox</code></td>
<td>

```math
\gnapprox
```
</td>
<td><code>\gnapprox</code></td>
<td>

```math
\varsubsetneq
```
</td>
<td><code>\varsubsetneq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\ntriangleleft
```
</td>
<td><code>\ntriangleleft</code></td>
<td>

```math
\lneq
```
</td>
<td><code>\lneq</code></td>
<td>

```math
\gneq
```
</td>
<td><code>\gneq</code></td>
<td>

```math
\varsupsetneq
```
</td>
<td><code>\varsupsetneq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\ntrianglelefteq
```
</td>
<td><code>\ntrianglelefteq</code></td>
<td>

```math
\lneqq
```
</td>
<td><code>\lneqq</code></td>
<td>

```math
\gneqq
```
</td>
<td><code>\gneqq</code></td>
<td>

```math
\varsubsetneqq
```
</td>
<td><code>\varsubsetneqq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\ntriangleright
```
</td>
<td><code>\ntriangleright</code></td>
<td>

```math
\lnsim
```
</td>
<td><code>\lnsim</code></td>
<td>

```math
\gnsim
```
</td>
<td><code>\gnsim</code></td>
<td>

```math
\varsupsetneqq
```
</td>
<td><code>\varsupsetneqq</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\ntrianglerighteq
```
</td>
<td><code>\ntrianglerighteq</code></td>
<td>

```math
\lvertneqq
```
</td>
<td><code>\blvertneqqbb</code></td>
<td>

```math
\gvertneqq
```
</td>
<td><code>\gvertneqq</code></td>
<td>
</td>
<td></td>
<!-- ROW END --></tr>
</table><br><br><br>

### 14.5.9<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Arrows

<table align="center">
<tr><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\leftarrow
```
</td>
<td><code>\leftarrow</code></td>
<td>

```math
\longleftarrow
```
</td>
<td><code>\longleftarrow</code></td>
<td>

```math
\uparrow
```
</td>
<td><code>\uparrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Leftarrow
```
</td>
<td><code>\Leftarrow</code></td>
<td>

```math
\Longleftarrow
```
</td>
<td><code>\Longleftarrow</code></td>
<td>

```math
\Uparrow
```
</td>
<td><code>\Uparrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\rightarrow
```
</td>
<td><code>\rightarrow</code></td>
<td>

```math
\longrightarrow
```
</td>
<td><code>\longrightarrow</code></td>
<td>

```math
\downarrow
```
</td>
<td><code>\downarrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Rightarrow
```
</td>
<td><code>\Rightarrow</code></td>
<td>

```math
\Longrightarrow
```
</td>
<td><code>\Longrightarrow</code></td>
<td>

```math
\Downarrow
```
</td>
<td><code>\Downarrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\leftrightarrow
```
</td>
<td><code>\leftrightarrow</code></td>
<td>

```math
\longleftrightarrow
```
</td>
<td><code>\longleftrightarrow</code></td>
<td>

```math
\updownarrow
```
</td>
<td><code>\updownarrow</code></td>
<!-- ROW END --></tr>
</table><br><br><br>


<table align="center">
<tr><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\mapsto
```
</td>
<td><code>\mapsto</code></td>
<td>

```math
\longmapsto
```
</td>
<td><code>\longmapsto</code></td>
<td>

```math
\nearrow
```
</td>
<td><code>\nearrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\hookleftarrow
```
</td>
<td><code>\hookleftarrow</code></td>
<td>

```math
\hookrightarrow
```
</td>
<td><code>\hookrightarrow</code></td>
<td>

```math
\searrow
```
</td>
<td><code>\searrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\leftharpoonup
```
</td>
<td><code>\leftharpoonup</code></td>
<td>

```math
\rightharpoonup
```
</td>
<td><code>\rightharpoonup</code></td>
<td>

```math
\swarrow
```
</td>
<td><code>\swarrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\leftharpoondown
```
</td>
<td><code>\leftharpoondown</code></td>
<td>

```math
\rightharpoondown
```
</td>
<td><code>\rightharpoondown</code></td>
<td>

```math
\nwarrow
```
</td>
<td><code>\nwarrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\rightleftharpoons
```
</td>
<td><code>\rightleftharpoons</code></td>
<td>
</td>
<td></td>
<td>
</td>
<td></td>
<!-- ROW END --></tr>
</table><br><br><br>


<table align="center">
<tr><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\dashrightarrow
```
</td>
<td><code>\dashrightarrow</code></td>
<td>

```math
\dashleftarrow
```
</td>
<td><code>\dashleftarrow</code></td>
<td>

```math
\leftleftarrows
```
</td>
<td><code>\leftleftarrows</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\leftrightarrows
```
</td>
<td><code>\leftrightarrows</code></td>
<td>

```math
\Lleftarrow
```
</td>
<td><code>\Lleftarrow</code></td>
<td>

```math
\twoheadleftarrow
```
</td>
<td><code>\twoheadleftarrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\leftarrowtail
```
</td>
<td><code>\leftarrowtail</code></td>
<td>

```math
\looparrowleft
```
</td>
<td><code>\looparrowleft</code></td>
<td>

```math
\leftrightharpoons
```
</td>
<td><code>\leftrightharpoons</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\curvearrowleft
```
</td>
<td><code>\curvearrowleft</code></td>
<td>

```math
\circlearrowleft
```
</td>
<td><code>\circlearrowleft</code></td>
<td>

```math
\Lsh
```
</td>
<td><code>\Lsh</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\upuparrows
```
</td>
<td><code>\upuparrows</code></td>
<td>

```math
\upharpoonleft
```
</td>
<td><code>\upharpoonleft</code></td>
<td>

```math
\downharpoonleft
```
</td>
<td><code>\downharpoonleft</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\multimap
```
</td>
<td><code>\multimap</code></td>
<td>

```math
\leftrightsquigarrow
```
</td>
<td><code>\leftrightsquigarrow</code></td>
<td>

```math
\rightrightarrows
```
</td>
<td><code>\rightrightarrows</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\rightleftarrows
```
</td>
<td><code>\rightleftarrows</code></td>
<td>

```math
\rightrightarrows
```
</td>
<td><code>\rightrightarrows</code></td>
<td>

```math
\rightleftarrows
```
</td>
<td><code>\rightleftarrows</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\twoheadrightarrow
```
</td>
<td><code>\twoheadrightarrow</code></td>
<td>

```math
\rightarrowtail
```
</td>
<td><code>\rightarrowtail</code></td>
<td>

```math
\looparrowright
```
</td>
<td><code>\looparrowright</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\rightleftharpoons
```
</td>
<td><code>\rightleftharpoons</code></td>
<td>

```math
\curvearrowright
```
</td>
<td><code>\curvearrowright</code></td>
<td>

```math
\circlearrowright
```
</td>
<td><code>\circlearrowright</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Rsh
```
</td>
<td><code>\Rsh</code></td>
<td>

```math
\downdownarrows
```
</td>
<td><code>\downdownarrows</code></td>
<td>

```math
\upharpoonright
```
</td>
<td><code>\upharpoonright</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\downharpoonright
```
</td>
<td><code>\downharpoonright</code></td>
<td>

```math
\rightsquigarrow
```
</td>
<td><code>\rightsquigarrow</code></td>
<td>

</td>
<td></td>
<!-- ROW END --></tr>
</table><br><br><br>


<table align="center">
<tr><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th><td width="100" align="center">Sym</td><th width="184" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\nleftarrow
```
</td>
<td><code>\nleftarrow</code></td>
<td>

```math
\nrightarrow
```
</td>
<td><code>\nrightarrow</code></td>
<td>

```math
\nLeftarrow
```
</td>
<td><code>\nLeftarrow</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nRightarrow
```
</td>
<td><code>\nRightarrow</code></td>
<td>

```math
\nleftrightarrow
```
</td>
<td><code>\nleftrightarrow</code></td>
<td>

```math
\nLeftrightarrow
```
</td>
<td><code>\nLeftrightarrow</code></td>
<!-- ROW END --></tr>
</table><br><br><br>


### 14.5.10<!--  🟥H3🟥--><img width="060" height="1" src="https://psop.uk/wi-s" alt="Spacer">Other symbols

<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\infty
```
</td>
<td><code>\infty</code></td>
<td>

```math
\forall
```
</td>
<td><code>\forall</code></td>
<td>

```math
\Diamond
```
</td>
<td><code>\Diamond</code></td>
<td>

```math
\complement
```
</td>
<td><code>\complement</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\nabla
```
</td>
<td><code>\nabla</code></td>
<td>

```math
\exists
```
</td>
<td><code>\exists</code></td>
<td>

```math
\Finv
```
</td>
<td><code>\Finv</code></td>
<td>

```math
\triangledown
```
</td>
<td><code>\dtriangledowndd</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\partial
```
</td>
<td><code>\partial</code></td>
<td>

```math
\nexists
```
</td>
<td><code>\nexists</code></td>
<td>
</td>
<td></td>
<td>

```math
\triangle
```
</td>
<td><code>\triangle</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\eth
```
</td>
<td><code>\eth</code></td>
<td>

```math
\emptyset
```
</td>
<td><code>\emptyset</code></td>
<td>

```math
\hbar
```
</td>
<td><code>\hbar</code></td>
<td>

```math
\vartriangle
```
</td>
<td><code>\vartriangle</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\clubsuit
```
</td>
<td><code>\clubsuit</code></td>
<td>

```math
\varnothing
```
</td>
<td><code>\varnothing</code></td>
<td>

```math
\hslash
```
</td>
<td><code>\hslash</code></td>
<td>

```math
\blacklozenge
```
</td>
<td><code>\blacklozenge</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\diamondsuit
```
</td>
<td><code>\diamondsuit</code></td>
<td>

```math
\imath
```
</td>
<td><code>\imath</code></td>
<td>

```math
\lozenge
```
</td>
<td><code>\lozenge</code></td>
<td>

```math
\blacksquare
```
</td>
<td><code>\blacksquare</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\heartsuit
```
</td>
<td><code>\heartsuit</code></td>
<td>

```math
\jmath
```
</td>
<td><code>\jmath</code></td>
<td>

```math
\mho
```
</td>
<td><code>\mho</code></td>
<td>

```math
\blacktriangle
```
</td>
<td><code>\blacktriangle</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\spadesuit
```
</td>
<td><code>\spadesuit</code></td>
<td>

```math
\ell
```
</td>
<td><code>\ell</code></td>
<td>

```math
\prime
```
</td>
<td><code>\prime</code></td>
<td>
</td>
<td></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\cdots
```
</td>
<td><code>\cdots</code></td>
<td>

```math
\sharp
```
</td>
<td><code>\sharp</code></td>
<td>

```math
\square
```
</td>
<td><code>\square</code></td>
<td>

```math
\backprime
```
</td>
<td><code>\backprime</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\vdots
```
</td>
<td><code>\vdots</code></td>
<td>

```math
\flat
```
</td>
<td><code>\flat</code></td>
<td>

```math
\surd
```
</td>
<td><code>\surd</code></td>
<td>

```math
\circledS
```
</td>
<td><code>\circledS</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\ldots
```
</td>
<td><code>\ldots</code></td>
<td>

```math
\natural
```
</td>
<td><code>\natural</code></td>
<td>

```math
\wp
```
</td>
<td><code>\wp</code></td>
<td>

```math
\measuredangle
```
</td>
<td><code>\measuredangle</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\Im
```
</td>
<td><code>\Im</code></td>
<td>

```math
\Re
```
</td>
<td><code>\Re</code></td>
<td>

```math
\diagdown
```
</td>
<td><code>\diagdown</code></td>
<td>

```math
\diagup
```
</td>
<td><code>\diagup</code></td>
<!-- ROW END --></tr>
</table><br><br><br>

### 14.5.11<!--  🟥H3🟥--><img width="063" height="1" src="https://psop.uk/wi-s" alt="Spacer">Accents

<table align="center">
<tr><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th><td width="50" align="center">Sym</td><th width="163" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>

```math
\acute{a}
```
</td>
<td><code>\acute{a}</code></td>
<td>

```math
\bar{a}
```
</td>
<td><code>\bar{a}</code></td>
<td>

```math
\breve{a}
```
</td>
<td><code>\breve{a}</code></td>
<td>

```math
\check{a}
```
</td>
<td><code>\check{a}</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\ddot{a}
```
</td>
<td><code>\ddot{a}</code></td>
<td>

```math
\dot{a}
```
</td>
<td><code>\dot{a}</code></td>
<td>

```math
\grave{a}
```
</td>
<td><code>\grave{a}</code></td>
<td>

```math
\hat{a}
```
</td>
<td><code>\hat{a}</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>

```math
\tilde{a}
```
</td>
<td><code>\atilde{a}aa</code></td>
<td>

```math
\vec{a}
```
</td>
<td><code>\vec{a}</code></td>
<td>
</td>
<td></td>
<td>
</td>
<td></td>
<!-- ROW END --></tr>
</table><br><br><br>

### 14.5.12<!--  🟥H3🟥--><img width="060" height="1" src="https://psop.uk/wi-s" alt="Spacer">Matrices

Matrices can be generated using the `\begin{xmatrix}` command where `x` defines the type of delimiter used. 

Following the command, columns are separated by the `&` character and a new row follows a double backslash character `\\`. 

The following are some examples (in each case the `x` character preceding matrix changes):

<table align="left"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row --> <tr>
                        <th width="283" align="left">${\large \color{#00C050}\text{D\ E\ S\ C\ R\ I\ P\ T\ I\ O\ N}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
</table>
<br clear="all">

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center" >No delimiter</th>

<td width="284"  align="left">

````md
```math
\begin{matrix}
1 & 2 & 3\\
a & b & c
\end{matrix}
```
````
<p> </p></td></tr>
</table><br><br><br>

```math
\begin{matrix}
1 & 2 & 3\\
a & b & c
\end{matrix}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center">Parentheses</th>

<td width="284"  align="left">

````md
```math
\begin{pmatrix}
1 & 2 & 3\\
a & b & c
\end{pmatrix}
```
````
<p> </p></td></tr>
</table><br><br><br>

```math
\begin{pmatrix}
1 & 2 & 3\\
a & b & c
\end{pmatrix}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->


<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center">Brackets</th>

<td width="284"  align="left">

````md
```math
\begin{bmatrix}
1 & 2 & 3\\
a & b & c
\end{bmatrix}
```
````
<p> </p></td></tr>
</table><br><br><br>

```math
\begin{bmatrix}
1 & 2 & 3\\
a & b & c
\end{bmatrix}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center">Braces</th>

<td width="284"  align="left">

````md
```math
\begin{Bmatrix}
1 & 2 & 3\\
a & b & c
\end{Bmatrix}
```
````
<p> </p></td></tr>
</table><br><br><br>

```math
\begin{Bmatrix}
1 & 2 & 3\\
a & b & c
\end{Bmatrix}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center">Pipes</th>

<td width="284"  align="left">

````md
```math
\begin{vmatrix}
1 & 2 & 3\\
a & b & c
\end{vmatrix}
```
````
<p> </p></td></tr>
</table><br><br><br>

```math
\begin{vmatrix}
1 & 2 & 3\\
a & b & c
\end{vmatrix}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center">Double pipes</th>

<td width="284"  align="left">

````md
```math
\begin{Vmatrix}
1 & 2 & 3\\
a & b & c
\end{Vmatrix}
```
````
<p> </p></td></tr>
</table><br><br><br>

```math
\begin{Vmatrix}
1 & 2 & 3\\
a & b & c
\end{Vmatrix}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center">Left and right ceiling delimiters <br>(these use a plain matrix<br>inside the specified delimiter)
</th>

<td width="284"  align="left">

````md
```math
\left\lceil
\begin{matrix}
1 & 2 & 3\\
a & b & c
\end{matrix}
\right\rceil
```
````
<p> </p></td></tr>
</table><br><br><br>

```math
\left\lceil
\begin{matrix}
1 & 2 & 3\\
a & b & c
\end{matrix}
\right\rceil
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center">Different delimiters either side</th>

<td width="284"  align="left">

````md
```math
\left\langle
\begin{matrix}
1 & 2 & 3\\
a & b & c
\end{matrix}
\right\rangle
```
````
<p> </p></td></tr>
</table><br><br><br>

```math
\left\langle
\begin{matrix}
1 & 2 & 3\\
a & b & c
\end{matrix}
\right\rangle
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

Matrices automatically align the columns where the content is wider: 



<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center">Different column widths</th>

<td width="284"  align="left">

````md
```math
\begin{pmatrix}
111 & 2 & 3\\
a & b & ccc
\end{pmatrix}
```
````
<p> </p></td></tr>
</table><br><br><br>

```math
\begin{pmatrix}
111 & 2 & 3\\
a & b & ccc
\end{pmatrix}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->
<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="850"  align="left">
<sup>Table 14.5 &mdash; Matrices</sup>
<p> </p></td></tr>
</table>
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

<br><br><br>

### 14.5.13<!--  🟥H3🟥--><img width="060" height="1" src="https://psop.uk/wi-s" alt="Spacer">Cases

Cases are a variation of matrices; they are often referred to as a piecewise function and consist of a left brace containing the results that occur under specific conditions. Cases are generated using the `\begin{cases}` command. 

Following the command, columns are separated by the `&` character and a new row follows a double backslash character `\\`.




<table align="left"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row --> <tr>
                        <th width="283" align="left">${\large \color{#00C050}\text{D\ E\ S\ C\ R\ I\ P\ T\ I\ O\ N}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
</table>
<br clear="all">

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center" >Typical case</th>

<td width="284"  align="left">

````md
```math
x=\begin{cases}
x, & \text{if }x\geq 0 \\
0, & \text{if }x< 0
\end{cases}
```
````
<p> </p></td></tr>
</table><br><br>

```math
x=\begin{cases}
x, & \text{if }x\geq 0 \\
0, & \text{if }x< 0
\end{cases}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->
<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="850"  align="left">
<sup>Table 14.6 &mdash; Cases</sup>
<p> </p></td></tr>
</table>
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->

The `\text{}` command is used to render the text between the braces literally (see <a href="#the-text-command">Text formatting — the text command section</a> for details).

<br><br><br>


#### <!--       🟥H4🟥--><u>Aligning multiple equations<!-- Extended line -->&emsp;&emsp;&emsp;&emsp;&emsp;</u> 

The `\begin{align}` command will align multiple equations at the `&` sign, the `&` can be inserted anywhere in the equation (usually before the equals sign). 

The equations for each line are separated by the double backslash character `\\`.




<table align="left"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row --> <tr>
                        <th width="283" align="left">${\large \color{#00C050}\text{D\ E\ S\ C\ R\ I\ P\ T\ I\ O\ N}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
</table>
<br clear="all">

<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><th width="283" align="center" >Equation alignment</th>

<td width="284"  align="left">

````md
```math
\begin{align} 
x - 5y &= 8 \\ 
3x + 9y &= -12
\end{align}
```
````
<p> </p></td></tr>
</table><br><br>

```math
\begin{align} 
x - 5y &= 8 \\ 
3x + 9y &= -12
\end{align}
```
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->
<!--- 🔴EQU TABLE START🔴 -->
<table align="left">
<!-- MD row -->     <tr><td width="850"  align="left">
<sup>Table 14.7 &mdash; Aligning multiple equations</sup>
<p> </p></td></tr>
</table>
<br clear="all">
<!--- 🟥EQU TABLE END🟥 -->


<br><br><br>
### 14.5.14<!--  🟥H3🟥--><img width="059" height="1" src="https://psop.uk/wi-s" alt="Spacer">Text formatting

LaTeX is a typsetting language and supports various text formatting operations, these are discussed below:

#### <!--       🟥H4🟥--><u>Font size<!-- Extended line -->&emsp;&emsp;&emsp;&emsp;&emsp;</u> 

LaTeX supports different font sizes, some are general sizes (`large`, `tiny` &c.) and some are mathematical formula sizes (these all end with the word `style`). GitHub is a bit inconsistent in how these render (some are just duplicates of others).


To change the font size, use the command below, everything following the command will be at the size specified. The point sizes are those generated by GitHub in the main body text area:


<table name="t-14-08" align="left"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row --> <tr>
                        <th width="283" align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#00C050}\text{P\ O\ I\ N\ T}\space\ \space\text{S\ I\ Z\ E}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<tr>
<td><code>\scriptscriptstyle</code></td>
<th align="center">9.60</th>
<td>${\scriptscriptstyle \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\tiny </code></td>
<th align="center">11.31</th>
<td>${\tiny  \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\scriptsize</code></td>
<th align="center">11.31</th>
<td>${\scriptsize \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\scriptstyle</code></td>
<th align="center">11.68</th>
<td>${\scriptstyle \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\small</code></td>
<th align="center">13.60</th>
<td>${\small \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\normalsize </code></td>
<th align="center">16.00</th>
<td>${\normalsize  \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\textstyle </code></td>
<th align="center">16.00</th>
<td>${\textstyle  \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\displaystyle</code></td>
<th align="center">16.00</th>
<td>${\displaystyle \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\large</code></td>
<th align="center">19.20</th>
<td>${\large \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\Large</code></td>
<th align="center">23.04</th>
<td>${\Large \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\huge </code></td>
<th align="center">23.04</th>
<td>${\huge \text{Lorem\ ipsum}}$</td>
</tr>
<tr>
<td><code>\Huge </code></td>
<th align="center">23.04</th>
<td>${\Huge \text{Lorem\ ipsum}}$</td>
</tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 14.8 &mdash; LaTeX text formatting, point size
                    </sup></th></tr>
</table>
<br clear="all">

<br><br><br>

#### <!--       🟥H4🟥--><u>Font colour<!-- Extended line -->&emsp;&emsp;&emsp;&emsp;&emsp;</u> 

The `\color{}` command can be used to change the colour of any text that follows.

It is fairly flexible in its approach, it can use pre-named colours, RGB hex colours, RGB decimal colours, RGBA with transparency, HSL colours and HSLA with transparency.

Once invoked, everything that follows the closing brace will be in the specified colour:

<table name="t-14-09" align="center">
<tr><td width="130" align="center">Sym</td><th width="760" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td>
${\color{red}EXAMPLE}$
</td>
<td><code>\color{red}EXAMPLE</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>
${\color{blue}EXAMPLE}$
</td>
<td><code>\color{blue}EXAMPLE</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>
${\color{#446FBD}EXAMPLE}$
</td>
<td><code>\color{#446FBD}EXAMPLE</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>
${\color{rgb(255,0,0)}EXAMPLE}$
</td>
<td><code>\color{rgb(255,0,0)}EXAMPLE</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>
${\color{rgba(0,255,0, 0.5)}EXAMPLE}$
</td>
<td><code>\color{rgba(0,255,0, 0.5)}EXAMPLE</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>
${\color{hsl(100%,0,0)}EXAMPLE}$
</td>
<td><code>\color{hsl(100%,0,0)}EXAMPLE</code></td>
<!-- ROW END --></tr>
<!--DATA ROW --><tr>
<td>
${\color{hsla(120, 100%, 50%, 0.5)}EXAMPLE}$
</td>
<td><code>\color{hsla(120, 100%, 50%, 0.5)}EXAMPLE</code></td>
<!-- ROW END --></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 14.9 &mdash; LaTeX text formatting, colours
                    </sup></th></tr>
<table>

The predefined colours are:


<table name="t-14-10" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row --> <tr>
                        <th width="222" align="left">Colour</th>
                        <th width="222" align="left">Name</th>
                        <th width="224" align="left">RGB</th>
                        <th width="224" align="left">Hex</th>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{black}\text{EXAMPLE}}$</td>
                        <td align="left"><code>black</code></td>
                        <td align="left"><code>0,0,0</code></td>
                        <td align="left"><code>#000000</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{blue}\text{EXAMPLE}}$</td>
                        <td align="left"><code>blue</code></td>
                        <td align="left"><code>0,0,255</code></td>
                        <td align="left"><code>#0000FF</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{brown}\text{EXAMPLE}}$</td>
                        <td align="left"><code>brown</code></td>
                        <td align="left"><code>191,248,64</code></td>
                        <td align="left"><code>#BF8040</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{cyan}\text{EXAMPLE}}$</td>
                        <td align="left"><code>cyan</code></td>
                        <td align="left"><code>0,185,224</code></td>
                        <td align="left"><code>#00B9F2</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{darkgrey}\text{EXAMPLE}}$</td>
                        <td align="left"><code>darkgrey</code></td>
                        <td align="left"><code>64,64,64</code></td>
                        <td align="left"><code>#404040</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{gray}\text{EXAMPLE}}$</td>
                        <td align="left"><code>gray</code></td>
                        <td align="left"><code>156,156,156</code></td>
                        <td align="left"><code>#9C9C9C</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{green}\text{EXAMPLE}}$</td>
                        <td align="left"><code>green</code></td>
                        <td align="left"><code>0,255,0</code></td>
                        <td align="left"><code>#00FF00</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{lightgrey}\text{EXAMPLE}}$</td>
                        <td align="left"><code>lightgrey</code></td>
                        <td align="left"><code>191,191,191</code></td>
                        <td align="left"><code>#BFBFBF</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{lime}\text{EXAMPLE}}$</td>
                        <td align="left"><code>lime</code></td>
                        <td align="left"><code>191,255,0</code></td>
                        <td align="left"><code>#BFFF00</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{magenta}\text{EXAMPLE}}$</td>
                        <td align="left"><code>magenta</code></td>
                        <td align="left"><code>251,49,153</code></td>
                        <td align="left"><code>#FB3199</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{olive}\text{EXAMPLE}}$</td>
                        <td align="left"><code>olive</code></td>
                        <td align="left"><code>159,140,24</code></td>
                        <td align="left"><code>#9F8C18</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{orange}\text{EXAMPLE}}$</td>
                        <td align="left"><code>orange</code></td>
                        <td align="left"><code>255,128,0</code></td>
                        <td align="left"><code>#FF8000</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{pink}\text{EXAMPLE}}$</td>
                        <td align="left"><code>pink</code></td>
                        <td align="left"><code>255,191,191</code></td>
                        <td align="left"><code>#FFBFBF</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{purple}\text{EXAMPLE}}$</td>
                        <td align="left"><code>purple</code></td>
                        <td align="left"><code>191,0,64</code></td>
                        <td align="left"><code>#BF0040</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{red}\text{EXAMPLE}}$</td>
                        <td align="left"><code>red</code></td>
                        <td align="left"><code>255,0,0</code></td>
                        <td align="left"><code>#FF0000</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{teal}\text{EXAMPLE}}$</td>
                        <td align="left"><code>teal</code></td>
                        <td align="left"><code>0,128,128</code></td>
                        <td align="left"><code>#008080</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{violet}\text{EXAMPLE}}$</td>
                        <td align="left"><code>violet</code></td>
                        <td align="left"><code>128,0,128</code></td>
                        <td align="left"><code>#800080</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{yellow}\text{EXAMPLE}}$</td>
                        <td align="left"><code>yellow</code></td>
                        <td align="left"><code>255,235,61</code></td>
                        <td align="left"><code>#FFEB3D</code></td>
                    </tr>
<!-- Data row -->   <tr>
                        <td align="left">${\color{white}\text{EXAMPLE}}$</td>
                        <td align="left"><code>white</code></td>
                        <td align="left"><code>255,255,255</code></td>
                        <td align="left"><code>#FFFFFF</code></td>
                    </tr>
<!-- CAPTION -->    <tr><th colspan="4" align="left"><sup>
<!-- CAPTION TEXT -->   Table 14.10 &mdash; LaTeX predefined colours
                    </sup></th></tr>
</table>
<br clear="all">                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->


<br><br><br>

#### <!--       🟥H4🟥--><u>The text command<!-- Extended line -->&emsp;&emsp;&emsp;&emsp;&emsp;</u> 

Text can be entered directly into an equation by just typing it in:


<table align="center">
<tr><td width="200" align="center">Sym</td><th width="690" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td align="center">
${EXAMPLE}$
</td>
<td><code>EXAMPLE</code></td>
<!-- ROW END --></tr>
<table>

The problem with this is that text entered this way is always in italics and, depending on the context and position, some spaces can go missing.

To ensure that text is displayed correctly, use the `\text{}` command:

<table align="center">
<tr><td width="200" align="center">Sym</td><th width="690" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td align="center">
${\text{EXAMPLE}}$
</td>
<td><code>\text{EXAMPLE}</code></td>
<!-- ROW END --></tr>
<table>

The `\text{}` command can be a bit hit and miss with spaces, to make sure that a space is definitely shown, precede it with a backslash (`\ `). I.e. backslash space. 

<table align="center">
<tr><td width="200" align="center">Sym</td><th width="690" align="left">Command</th></tr>
<!--DATA ROW --><tr>
<td align="center">

${\text{EXAMPLE\ TEXT}}$
</td>
<td><code>\text{EXAMPLE\ TEXT}</code></td>
<!-- ROW END --></tr>
<table>

> [!IMPORTANT]<!-- IMPORTANT ALERT -->
> **The `\ ` backslash space also works in an equation outside of the `\text{}` command, as does the `\space` option (which does not work inside the`\text{}` command).**


<br><br><br>

#### <!--       🟥H4🟥--><u>Font restrictions<!-- Extended line -->&emsp;&emsp;&emsp;&emsp;&emsp;</u> 

LaTeX supports different fonts *(of course it does, it’s a typesetting language)*. It has all the following options available to it (and this is just for maths formulae).

It should work like this:




<table name="t-14-08" align="left"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row --> <tr>
                        <th width="283" align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th width="283" align="center">${\large \color{#00C050}\text{D\ E\ S\ C\ R\ I\ P\ T\ I\ O\ N}}$ 🔽</th>
                        <th width="283" align="left">${\large \color{#B00000}\text{E\ X\ P\ E\ C\ T\ E\ D}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<tr>
<td><code>\mathsf{ABCDEF}</code></td>
<th align="center">San-serif font</th>
<td><img height="20" src="../14-0000/02-images/figm-00-00a.png" alt="San-serif"></td>
</tr>
<tr>
<td><code>\mathbf{ABCDEF}</code></td>
<th align="center">Bold  font</th>
<td><img height="20" src="../14-0000/02-images/figm-00-00b.png" alt="Bold"></td>
</tr>
<tr>
<td><code>\mathcal{ABCDEF}</code></td>
<th align="center">Script  font</th>
<td><img height="20" src="../14-0000/02-images/figm-00-00c.png" alt="Script"></td>
</tr>
<tr>
<td><code>\mathbb{ABCDEF}</code></td>
<th align="center">Double struck font</th>
<td><img height="20" src="../14-0000/02-images/figm-00-00d.png" alt="Double struck"></td>
</tr>
<tr>
<td><code>\mathefrak{ABCDEF}</code></td>
<th align="center">Frakturs  font</th>
<td><img height="20" src="../14-0000/02-images/figm-00-00e.png" alt="Frakturs"></td>
</tr>
</table>
<br clear="all">

***This is good I thought, now I can play tunes with GitHub, but it wasn’t to be.***

<p align="center">${\Large \color{#C00000}\text{GitHub\ ignores\ all\ these\ commands.}}$</p>


GitHub ignores all commands that apply specific fonts. All LaTeX entries are always rendered in the standard GitHub Math font (a serif font).

***So there go my hopes for using a different font.***

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 14.6<!--     🟥H2🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Abusing LaTeX

*Er… I might need to rethink that title.*

GitHub doesn’t allow the font colour to be changed. It will change it itself for things like links, but as users, we can’t just change the font to green for example.

The following uses inline LaTeX formulas to add text in any colour to a GitHub page, it is a poor substitute, it is clumsy to enter and uses the standard LaTeX serif font, but it does work:

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 14.6.1<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Using LaTeX to change the font colour

The following is an extract from an earlier section of this document:

&emsp;&emsp;&nbsp;&nbsp; $$\large \color{#7030A0}\text{https:/}\text{/github.com}\color{#446FBD}\text{/}\color{#ED7D31}\text{[UserName]}\color{#446FBD}\text{/}\color{#00B050}\text{[RepositoryName]}\color{#446FBD}\text{/}\color{#c00000}\text{wiki}$$

The Markdown behind this is:

<table name="t-14-11" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
$$\large \color{#7030A0}\text{https:/}\text{/github.com}\color{#446FBD}\text{/}\color{#ED7D31}\text{[UserName]}\color{#446FBD}\text{/}\color{#00B050}\text{[RepositoryName]}\color{#446FBD}\text{/}\color{#c00000}\text{wiki}$$
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 14.11 &mdash; Coloured text example
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

It starts and ends with a double dollar sign (`$$`), this makes it a block equation (centres it on the page). It then uses a series of `\color{}` and `\text{}` commands to construct the visible text string and assign the different colours.

The only oddball thing here is the splitting of the `https://github.com` web address, it has become `\text{https:}\text{//github.com}`. I.e. it has been split into two parts, `https:` and `//github.com`. 

The reason for this is that GitHub doesn’t like links in LaTeX formula *(it won’t render the formula if there is a link in it)*, hence splitting it into two components that are not interpreted by GitHub as a link, but look like one when joined together.

Inline colour is perfectly possible too:

This line has inline ${\color{#C00000}\text{coloured}}$ ${\color{#00B050}\text{text}}$ information.

The Markdown being


<table name="t-14-12" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
This line has inline ${\color{#C00000}\text{coloured}}$ ${\color{#00B050}\text{text}}$ information.
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 14.12 &mdash; Inline colours
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

The principle is exactly the same, just encapsulate it between `${…}$` to signify an inline formula (see <a href="#142inserting-an-inline-formula">section&nbsp;14.2</a>)

<hr><!-- FOOTNOTE SEPARATOR 🟡🟡🟡🟡🟡 -->
<a name="idfn" href="#idfn">Footnotes:<!-- 🟡FOOTNOTE TITLE🟡 -->&emsp;&emsp;&emsp;&emsp;&emsp;</a>
<br><br><br>

> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-01" href="#rn-01"><sup>💠1</sup></a>&emsp;<!-- FOOTNOTE CONTENT TEXT -->TeX and LaTeX; TeX (pronounced *tech)* came first. It’s named after the Greek word τέχνη which means something between art and skill, the first three letters being tau, epsilon, and chi or TEX in the Roman alphabet (the chi character looks like an x, but is pronounced “k”, hence tech not tex).
> 
> TeX is a very low-level typesetting programming language (developed by Donald Knuth in 1978), it was intended as a mechanism for producing professional documents, in particular it is used for the publication of mathematical, engineering and physics documentation. It is a comprehensive set of extensions (sometimes *engines)* and macros that provide extensive type-setting functions, including the representation of mathematical formulae.
> 
> LaTeX (pronounced *Lay-tech)* is a version of TeX created by Leslie Lamport in 1984 (the La being the first two letters of his surname). It works at a (slightly) higher programming language level than TeX and provides various macros that move away from the elementary programming commands of Tex to a markup language format.
> 
> Generally, LaTeX is more widely used and it is this format that GitHub uses to display mathe-matical formulae<!--  CONTENT TEXT END --><a href="#rn-01">↩</a><!-- 🟡🟡🟡🟡🟡 FOOTNOTE END -->


> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-02" href="#rn-01"><sup>💠1</sup></a>&emsp;<!-- FOOTNOTE CONTENT TEXT -->AsciiMath itself is a plain-text form of notation for writing equations.<!--  CONTENT TEXT END --><a href="#rn-02">↩</a><!-- 🟡🟡🟡🟡🟡 FOOTNOTE END -->


<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->