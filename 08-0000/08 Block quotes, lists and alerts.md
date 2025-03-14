<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="./ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-0800--eba-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 

# 8<!--         🟥H1🟥--><img width="100" height="1" src="https://psop.uk/wi-s" alt="Spacer">Block quotes, lists and alerts

Markdown can produce its own numbered and unnumbered lists, these can be mixed and nested as required. These lists are quite basic and don’t look very good (lists within the PracticalSeries Wikis use tables to give better structure and formatting, see <a href="10-tables">section&nbsp;10</a> for details).

Block quotes and alerts are used to highlight particular text.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 8.1<!--      🟥H2🟥--><img width="090" height="1" src="https://psop.uk/wi-s" alt="Spacer">Block quotes


Block quotations are areas of text that are highlighted to make them distinct from the normal body text, they look like this:

> *This is an extract  from “Race to the Moon”: Cox, Catherine Bly & Charles Murray (1989). Published by Simon and Schuster. There is a Kindle version by the same authors, but it is just called [Apollo](https://www.amazon.co.uk/Apollo-Catherine-Bly-Cox-ebook/dp/B003KN3Z4M/).*

Block quotations are so called because they often contain quotes or references to other works. In practice, block quotations can be used for any purpose. 

GitHub displays block quotations with a 4 px wide grey bar on the left-hand side of the text area. The text is indented by 4.5 spaces and is in a grey colour: `#59636E` or `rgb(89,99,110)` that is lighter than the body text colour. Block quotation text is the same point size as body text.

Block quotations are created in Markdown by starting the line with a single greater than sign `>` followed by a space:

<table name="t-08-01" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
> First line
> 
> Second line
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<blockquote>
  <p>First line</p>
  <p>Second line</p>
</blockquote>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<blockquote>
  <p>First line</p>
  <p>Second line</p>
</blockquote>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.1 &mdash; Block quotes
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

A blank line with a leading greater than `>` can be used to separate paragraphs in a block quotation.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.1.1<!--   🟥H3🟥--><img width="082" height="1" src="https://psop.uk/wi-s" alt="Spacer">Nested block quotes

Block quotes can be nested by adding extra `>` at the start of the text:

<table name="t-08-02" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
> First level
>
>> Second level
>>
>>> Third level
>>>
>>>> Fourth level
>>>
>>> Third level
>>
>> Second level
>
> First level
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<blockquote>
  <p>First level</p>
  <blockquote>
    <p>Second level</p>
    <blockquote>
      <p>Third level</p>
      <blockquote>
        <p>Fourth level</p>
      </blockquote>
      <p>Third level</p>
    </blockquote>
    <p>Second level</p>
  </blockquote>
  <p>first level</p>
</blockquote>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<blockquote>
  <p>First level</p>
  <blockquote>
    <p>Second level</p>
    <blockquote>
      <p>Third level</p>
      <blockquote>
        <p>Fourth level</p>
      </blockquote>
      <p>Third level</p>
    </blockquote>
    <p>Second level</p>
  </blockquote>
  <p>first level</p>
</blockquote>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.2 &mdash; Nested block quotes
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.1.2<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">Other elements inside block quotes

Block quotes can contain other Markdown elements such as headings, emphasis (bold, italic, underline &c.), they can also contain lists (GitHub supports lists in block quotes). The lists can be ordered or unordered (see <a href="#83ordered-numbered-lists">section&nbsp;8.3</a> and <a href="#82unordered-unnumbered-lists">section&nbsp;8.2</a>). The following shows some examples:



<table name="t-08-03" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="200">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="280">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
> # Block Quotes
>
> With lists
>
> * List point 1
> * List point 2
>
> *Last **line***
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<blockquote>
  <h1> Block Quotes </h1>
  <p> With lists</p>
  <ul>
    <li> List point 1</li>
    <li> List point 2</li>
  </ul>
  <p><em>Last <strong>line</strong></em></p>
</blockquote>

```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<blockquote>
  <h1> Block Quotes </h1>
  <p> With lists</p>
  <ul>
    <li> List point 1</li>
    <li> List point 2</li>
  </ul>
  <p><em>Last <strong>line</strong></em></p>
</blockquote>


</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.3 &mdash; Markdown elements in block code
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.1.3<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">Markdown rules for block quotes

<table name="l-cc-nn" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2776;<!-- 1  --></td>
    <td><!-- TEXT -->Always leave a blank line before and after block quotes</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2777;<!-- 2  --></td>
    <td><!-- TEXT -->Separate paragraphs with a `>` on a blank line</td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x2778;<!-- 3  --></td>
    <td><!-- TEXT -->Block quotes can be nested without limit</td></tr>
<!-- LIST ROW 04  --><tr><td valign="top">&#x2779;<!-- 4  --></td>
    <td><!-- TEXT -->Block quotes are the same point size as body text</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="798"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 8.1 &mdash; Markdown rules for block quotes
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 8.2<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Unordered (unnumbered) lists

Unordered or unnumbered lists are the simplest form of list, they appear as indented lines with a point (•) at the start of the line:

* First point
* Second point
* Third point

Unordered lists are created in Markdown by starting the line with a single asterisk `*` followed by a space, a single dash `-` followed by a space or a single plus `+` followed by a space.

The following all work:

<table name="t-08-04" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
* First point
* Second point
* Third point
```
Or
```md
- First point
- Second point
- Third point
```
Or
```md
+ First point
+ Second point
+ Third point
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td valign="top" align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ul>
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td valign="top" align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ul>
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.4 &mdash; Unordered list
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

> [!TIP]<!-- TIP ALERT -->
> *Don’t mix and match the delimiters `*`, `+`, or `-`; if you do, GitHub will interpret it as the start of a new list and will change the line spacing, pick one and stick to it throughout the list.*

Whichever delimiter you use, it must be the first character on the line (spaces in front of it will be ignored), any non-space character that precedes it will cause the line to render as normal text.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.2.1<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">Nested unordered lists

It is possible to nest unordered lists:

* Level 1 point 1
* Level 1 point 2
    * Level 2 point 1
    * Level 2 point 2
        * Level 3 point 1
* Level 1 point 3
* Level 1 point 4

Unordered lists are nested by indenting each list by at least two spaces *(four is more conventional)* before the delimiter for each additional level. The above is generated as follows:

<table name="t-08-05" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
* Level 1 point 1
* Level 1 point 2
    * Level 2 point 1
    * Level 2 point 2
        * Level 3 point 1
* Level 1 point 3
* Level 1 point 4
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ul>
  <li>Level 1 point 1</li>
  <li>Level 1 point 2</li>
  <ul>
    <li>Level 2 point 1</li>
    <li>Level 2 point 2</li>
    <ul>
      <li>Level 3 point 1</li>
    </ul>
  </ul>
  <li>Level 1 point 3</li>
  <li>Level 1 point 4</li>
</ul>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ul>
  <li>Level 1 point 1</li>
  <li>Level 1 point 2</li>
  <ul>
    <li>Level 2 point 1</li>
    <li>Level 2 point 2</li>
    <ul>
      <li>Level 3 point 1</li>
    </ul>
  </ul>
  <li>Level 1 point 3</li>
  <li>Level 1 point 4</li>
</ul>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.5 &mdash; Nested unordered list
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Nesting uses different bullet marks for the first three levels: black circle: ${\color{#000000}\text{⏺}}$, open circle: ${\color{#000000}\text{⭘}}$ and black square: ${\color{#000000}\text{⯀}}$. All subsequent nesting levels just use the black square:

* Level 1
    * Level 2
         * Level 3
           * Level 4
             * Level 5 

Unordered lists can be indented as far as you like.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.2.2<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Type of bullet point

The type of bullet point used is fixed in Markdown: a black circle for the first level, open circle for the second and black square for all other layers.

HTML allows the type of bullet point to be selected (within limits) with the use of the type attribute. The `type` attribute can specify a `disk`, a `circle`, a `square`, or `none`.

<table name="t-08-06" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="2"><sup>HTML and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ul type = "disk">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ul type = "disk">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>


</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ul type = "circle">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ul type = "circle">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ul type = "square">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ul type = "square">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ul type = "none">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ul type = "none">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ul>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 8.6 &mdash; HTML bullet types
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->


**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.2.3<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Indents and spacing

In terms of spacing, the point mark (•) is indented three spaces from the left edge of the text area, the text following the point mark is indented a further two spaces.

If the line of text following the point wraps at the end of a line, the text will maintain the correct indentation as follows:

* Point 1
* Lorem ipsum dolor sit amet, consectetur adipiscing elit. In consectetur tortor a tortor ornare, non pretium diam faucibus. Morbi ut mollis dolor, nec pretium tellus. Suspendisse ornare neque placerat orci aliquam, eu sodales dui blandit. Maecenas nec risus vel magna blandit euismod. Suspendisse id finibus purus. Nam ultricies non sapien ac rutrum.
* Point 3

Here the second point wraps at the end of the line, but maintains the correct indentation.

Each nested level indents the list by a further seven spaces before the bullet point, the text following the bullet point is always indented two spaces.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.2.4<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Numbers in an unordered list

*A slightly misleading heading.*


If you start an unordered list with a number let’s say:



<table name="t-08-07" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="2"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```md
* 2004, Markdown invented
* 2008, GitHub adds Wiki support
```
<p> </p></td><!-- 🔴MARKDOWN END OF CELL🔴 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

* 2004, Markdown invented
* 2008, GitHub adds Wiki support

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 8.7 &mdash; Numbers at the start of an unordered list
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Then everything is fine, the list displays as you would expect: bullet point followed by the text.

If however, the number was followed by a full stop:

<table name="t-08-08" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="2"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```md
* 2004. Markdown invented
* 2008. GitHub adds Wiki support
```
<p> </p></td><!-- 🔴MARKDOWN END OF CELL🔴 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

* 2004. Markdown invented
* 2008. GitHub adds Wiki support

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 8.8 &mdash; Numbers with a full stop at the start of an unordered list
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

It converts the list to an ordered list (numbers followed by a full stop are interpreted as an ordered list, see <a href="#83ordered-numbered-lists">section&nbsp;8.3</a>) and displays the number in roman numerals (again see <a href="#83ordered-numbered-lists">section&nbsp;8.3</a> for details). This is GitHub trying to make sense of the conflicting information we have supplied it.

It’s the full stop after the number that cause the problem, GitHub thinks were trying to create an ordered list starting at 2004, it displays it as roman numerals because it is preceded by an asterisk (see <a href="#83ordered-numbered-lists">section&nbsp;8.3.3</a> for details).

To make the list display properly, we need to escape the full stop (see <a href="07-special-characters-and-escaping-characters#t-07-01">Table&nbsp;7.1</a>) by putting a backslash in front of it:

<table name="t-08-09" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="2"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```md
* 2004\. Markdown invented
* 2008\. GitHub adds Wiki support
```
<p> </p></td><!-- 🔴MARKDOWN END OF CELL🔴 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

* 2004\. Markdown invented
* 2008\. GitHub adds Wiki support

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 8.9 &mdash; Numbers with an escaped full stop at the start of an unordered list
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.2.5<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Adding paragraphs to an unordered list

It is possible to add an additional paragraph to an unordered list by indenting it by at least two spaces:

<table name="t-08-10" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
* First point

  Additional paragraph

* Second point
* Third point

```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ul>
  <li>First point</li>
  <p>Additional paragraph</p>
  <li>Second point</li>
  <li>Third point</li>
</ul>

```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

* First point

  Additional paragraph

* Second point
* Third point 

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.10 &mdash; Unordered list with an additional paragraph
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

The additional paragraph must have a blank line before and after.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.2.6<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Other elements inside an unordered list

Unordered lists can contain other Markdown elements such as headings, emphasis (bold, italic, underline &c.) and block quotes. The following shows some examples:

<table name="t-08-11" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
* ### First point

  > Block quote

* *Second point*
* Third point
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ul>
  <li><h3>First point</h3></li>
  <blockquote>
    Block quote
  </blockquote>
  <li><em>Second point</em></li>
  <li>Third point</li>
</ul>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

* ### First point

  > Block quote

* *Second point*
* Third point

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.11 &mdash; Unordered list with additional elements
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.2.7<!--   🟥H3🟥--><img width="077" height="1" src="https://psop.uk/wi-s" alt="Spacer">Markdown rules for unordered lists

<table name="l-08-02" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2776;<!-- 1  --></td>
    <td><!-- TEXT -->Always use the same delimiter in an unordered list, don’t mix the <code>*</code>, <code>-</code> or <code>+</code> in the same list.</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2777;<!-- 2  --></td>
    <td><!-- TEXT -->If starting with a number followed by a full stop, escape the full stop by using <code>\.</code></td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x2778;<!-- 3  --></td>
    <td><!-- TEXT -->Nest lists by indenting the levels by at least two additional spaces before the delimiter</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="798"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 8.2 &mdash; Markdown rules for unordered lists
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 8.3<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Ordered (numbered) lists

Ordered or numbered lists are lists that are automatically numbered when rendered by GitHub. They consist of a number followed by a full stop. The number increments for each new line in the list:

1. Point 1
2. Point 2
3. Point 3

Ordered lists are created in Markdown by entering a number followed by a full stop `1.` and a space.

Only the first number (top line of the list) matters, this will be the starting number of the list.

The following all work:

<table name="t-08-12" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
1. First point
2. Second point
3. Third point

```
Or
```md
1. First point
1. Second point
1. Third point

```
Or
```md
1. First point
4. Second point
6. Third point
```
Or
```md
1. First point
10. Second point
3. Third point
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td valign="top" align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol>
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td valign="top" align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

1. First point
10. Second point
3. Third point

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.12 &mdash; Ordered list
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

In the above table, all the Markdown options produce the same result (a list numbered `1`, `2` and `3`), this is because the first number in each list is the number `1`. The numbers for each subsequent point in a list are calculated automatically by GitHub when it renders the page, the actual numbers in the Markdown text are ignored.

Whichever number you use, it must be the first character on the line (spaces in front of it will be ignored), any non-space character that precedes it will cause the line to render as normal text.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.3.1<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">Starting at a different number




<table name="t-08-13" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
7. First point
8. Second point
9. Third point

```
Or
```md
7. First point
1. Second point
1. Third point

```
Or
```md
7. First point
4. Second point
6. Third point
```
Or
```md
7. First point
10. Second point
3. Third point
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td valign="top" align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol start="7">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td valign="top" align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

7. First point
10. Second point
3. Third point

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.13 &mdash; Ordered list starting at a specific number
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

> [!NOTE]<!-- NOTE ALERT -->
> *It is not possible to skip numbers in an ordered list.*

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.3.2<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Nested ordered lists

It is possible to nest ordered lists:

1. Level 1 point 1
1. Level 1 point 2
    *. Level 2 point 1
    1. Level 2 point 2
        1. Level 3 point 1
1. Level 1 point 3
1 Level 1 point 4

Ordered lists are nested by indenting each list by four spaces before the number for each additional level. The above is generated as follows:

<table name="t-08-14" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
1. Level 1 point 1
1. Level 1 point 2
    1.. Level 2 point 1
    1. Level 2 point 2
        1. Level 3 point 1
1. Level 1 point 3
1 Level 1 point 4
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol>
  <li>Level 1 point 1</li>
  <li>Level 1 point 2</li>
  <ol>
    <li>Level 2 point 1</li>
    <li>Level 2 point 2</li>
    <ol>
      <li>Level 3 point 1</li>
    </ol>
  </ol>
  <li>Level 1 point 3</li>
  <li>Level 1 point 4</li>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ol>
  <li>Level 1 point 1</li>
  <li>Level 1 point 2</li>
  <ol>
    <li>Level 2 point 1</li>
    <li>Level 2 point 2</li>
    <ol>
      <li>Level 3 point 1</li>
    </ol>
  </ol>
  <li>Level 1 point 3</li>
  <li>Level 1 point 4</li>
</ol>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.14 &mdash; Nested ordered list
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Nesting uses different numbering mechanisms for the first three levels: Arabic numerals (1, 2, 3…), lower case Roaman numerals (i, ii, iii…) and lowercase letters (a, b, c…). All subsequent nesting levels use the lowercase letters.

1. Level 1
    1. Level 2
        1. Level 3
            1. Level 4
                1. Level 5 

Ordered lists can be indented as far as you like.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.3.3<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Type of numbering

The type of numbering used in ordered lists is fixed in Markdown: Arabic numerals (1, 2, 3…), lower case Roaman numerals (i, ii, iii…) and lowercase letters (a, b, c…) for all other layers.

HTML allows the type of numbering to be selected *(within limits)* with the use of the `type` attribute. The type attribute can specify Arabic numerals `type = "1"`, lowercase alphabetically ordered `type = "a"`, uppercase alphabetically ordered `type = "A"`, lowercase Roman numerals `type = "i"` or uppercase Roman numerals `type = "I"`. 

<table name="t-08-15" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="2"><sup>HTML and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol type = "1">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ol type = "1">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>


</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol type = "a">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ol type = "a">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol type = "A">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ol type = "A">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol type = "i">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ol type = "i">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol type = "I">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ol type = "I">
  <li>First point</li>
  <li>Second point</li>
  <li>Third point</li>
</ol>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 8.15 &mdash; HTML ordered list numeral types
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

> [!TIP]<!-- TIP ALERT -->
> *There is no `none` option for the type attribute when used with ordered lists (unlike the unordered list, see <a href="#822type-of-bullet-point">section&nbsp;8.2.2</a>).*


**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.3.4<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Indents and spacing

In terms of spacing, the number mark is indented two normal spaces and a thin space (see <a href="07-special-characters-and-escaping-characters#72special-space-characters">section&nbsp;7.2</a>) from the left edge of the text area<a name="rn-01" href="#fn-01"><!-- 🟨FOOTNOTE LINK🟨--><sup>💠1</sup></a>, the text following the point mark is indented a further single space.

With nested levels, the text of each nested level is indented a further seven normal spaces.

If the line of text following the point wraps at the end of a line, the text will maintain the correct indentation as follows:

1. Point 1
1. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In consectetur tortor a tortor ornare, non pretium diam faucibus. Morbi ut mollis dolor, nec pretium tellus. Suspendisse ornare neque placerat orci aliquam, eu sodales dui blandit. Maecenas nec risus vel magna blandit euismod. Suspendisse id finibus purus. Nam ultricies non sapien ac rutrum.
1. Point 3

Here the second point wraps at the end of the line, but maintains the correct indentation.

The full stop following the number is always in the same position from the left-hand edge of the screen.

As more digits are added (going from point 9 to point 10 or from point 99 to point 100 &c.) the left indentation becomes less. This can be seen in the following lists:

<table name="f-08-01" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./08-0000/02-images/figm-08-01.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="187" src="./08-0000/02-images/figm-08-01.png" alt="Ordered list indentations ">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 8.1 &mdash; Ordered list indentations 
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

In the above diagram the blue dashes show the position of the full stop following the number (these always line up), the black squares start at the left edge of the page (where the body text starts), the orange line shows the left edge of the body text area.

It can be seen that one and two-digit numbers are indented from the left-hand side of the text area, three-digit numbers start at exactly the edge of the text area and any number with more than three digit expands beyond the left edge of the text area (into the margin area).

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.3.5<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Adding paragraphs to an ordered list

It is possible to add an additional paragraph to an ordered list by indenting it four spaces:

<table name="t-08-16" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
1. First point

    Additional paragraph

1. Second point
1. Third point

```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol>
  <li>First point</li>
  <p>Additional paragraph</p>
  <li>Second point</li>
  <li>Third point</li>
</ol>

```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

1. First point

    Additional paragraph

1. Second point
1. Third point

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.16 &mdash; Ordered list with an additional paragraph
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

The additional paragraph must have a blank line before and after.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.3.6<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Other elements inside an ordered list

Ordered lists can contain other Markdown elements such as headings, emphasis (bold, italic, underline &c.) and block quotes. The following shows some examples:

<table name="t-08-17" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
1. ### First point

    > Block quote

1. *Second point*
1. Third point
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol>
  <li><h3>First point</h3></li>
  <blockquote>
    Block quote
  </blockquote>
  <li><em>Second point</em></li>
  <li>Third point</li>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

1. ### First point

    > Block quote

1. *Second point*
1. Third point

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.17 &mdash; Ordered list with additional elements
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.3.7<!--   🟥H3🟥--><img width="077" height="1" src="https://psop.uk/wi-s" alt="Spacer">Markdown rules for ordered lists

<table name="l-08-02" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2776;<!-- 1  --></td>
    <td><!-- TEXT -->The first number on the first line of a list is the starting number for the list</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2777;<!-- 2  --></td>
    <td><!-- TEXT -->Nest lists by indenting the levels by four spaces before the number</td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x2778;<!-- 3  --></td>
    <td><!-- TEXT -->Lists are always Arabic numerals (1, 2, 3…), nested lists use lowercase Roman numerals (i, ii, iii…) followed by lowercase letters for all other nesting levels (a, b, c…).</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="798"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 8.2 &mdash; Markdown rules for unordered lists
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 8.4<!--      🟥H2🟥--><img width="086" height="1" src="https://psop.uk/wi-s" alt="Spacer">Mixing ordered and unordered lists

It is possible to nest together ordered and unordered lists. This usually involves having an unordered list within an ordered list:


<table name="t-08-18" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
1. General Points
    * Max page length
    * Comments
    * Keyboard shortcuts
1. Wiki structures
    * Folder structures
    * Conventions
1. Managing a Wiki
    * Revision control
    * Managing commits
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ol>
  <li>General Points</li>
  <ul>
    <li>Max page length</li>
    <li>Keyboard shortcuts</li>
  </ul>
  <li>Wiki structures</li>
  <ul>
    <li>Folder structures</li>
    <li>Conventions</li>
  </ul>
  <li>Managing a Wiki</li>
  <ul>
    <li>Revision control</li>
    <li>Managing commits</li>
  </ul>
</ol>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ol>
  <li>General Points</li>
  <ul>
    <li>Max page length</li>
    <li>Keyboard shortcuts</li>
  </ul>
  <li>Wiki structures</li>
  <ul>
    <li>Folder structures</li>
    <li>Conventions</li>
  </ul>
  <li>Managing a Wiki</li>
  <ul>
    <li>Revision control</li>
    <li>Managing commits</li>
  </ul>
</ol>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.18 &mdash; Ordered list with nested unordered lists
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

They can also be the other way round (unordered list with nested ordered list):

<table name="t-08-19" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="3"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- MD cell -->   <td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
* General Points
    1. Max page length
    1. Comments
    1. Keyboard shortcuts
* Wiki structures
    1. Folder structures
    1. Conventions
* Managing a Wiki
    1. Revision control
    1. Managing commits
```
<p> </p></td><!-- 🟢MARKDOWN END OF CELL🟢 -->
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<ul>
  <li> General Points </li>
  <ol>
    <li>Max page length</li>
    <li>Keyboard shortcuts</li>
  </ol>
  <li>Wiki structures </li>
  <ol>
    <li>Folder structures</li>
    <li>Conventions</li>
  </ol>
  <li>Managing a Wiki</li>
  <ol>
    <li>Revision control</li>
    <li>Managing commits</li>
  </ol>
</ul>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<ul>
  <li> General Points </li>
  <ol>
    <li>Max page length</li>
    <li>Keyboard shortcuts</li>
  </ol>
  <li>Wiki structures </li>
  <ol>
    <li>Folder structures</li>
    <li>Conventions</li>
  </ol>
  <li>Managing a Wiki</li>
  <ol>
    <li>Revision control</li>
    <li>Managing commits</li>
  </ol>
</ul>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="3"><sup>
<!-- CAPTION TEXT -->Table 8.19 &mdash; Unordered list with nested ordered lists
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

> [!NOTE]<!-- NOTE ALERT -->
> *In both cases, the nested list start with the numerical arrangement or point style for that level of indentation (circles for the unordered list in the first example, Roman numerals for the ordered list in the second example).*

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 8.5<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Task lists (check boxes)

Task lists are a special form of list with checkboxes:

- [ ] General Points
- [x] Wiki structures
- [X] Managing a Wik

Task lists are created in Markdown by starting the line with a single dash `-` followed by a space, followed by an open bracket `[` followed by a space followed by a close bracket `]` followed by a space: `- [ ] `.

If the checkbox is to be shown ticked, put an `x` between the brackets (the `x` can be lower or uppercase).

The above image is generated with the following Markdown:
<table name="t-08-20" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="2"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```md
- [ ] General Points
- [x] Wiki structures
- [X] Managing a Wik
```
<p> </p></td><!-- 🔴MARKDOWN END OF CELL🔴 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

- [ ] General Points
- [x] Wiki structures
- [X] Managing a Wik

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 8.20 &mdash; Task list Markdown
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->


> [!NOTE]<!-- NOTE ALERT -->
> *There is no HTML equivalent for task lists..*

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.5.1<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">Nested task lists

It is possible to nest task lists:

- [ ] General Points
    - [ ] Max page length
    - [x] Comments
    - [x] Keyboard shortcuts
- [ ] Wiki structures
    - [ ] Sidebars and Footnotes
    - [x] Folder structures
    - [ ] Conventions
        - [ ] PracticalSeries
        - [x] Standard
- [x] Managing a Wiki
    - [x] Revision control
    - [x] Managing commits

Task lists are nested by indenting each list by four spaces before the delimiter for each additional level. The above is generated as follows:

<table name="t-08-21" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right" colspan="2"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="240">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="240">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```md
- [ ] General Points
    - [ ] Max page length
    - [x] Comments
    - [x] Keyboard shortcuts
- [ ] Wiki structures
    - [ ] Sidebars and Footnotes
    - [x] Folder structures
    - [ ] Conventions
        - [ ] PracticalSeries
        - [x] Standard
- [x] Managing a Wiki
    - [x] Revision control
    - [x] Managing commits
```
<p> </p></td><!-- 🔴MARKDOWN END OF CELL🔴 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

- [ ] General Points
    - [ ] Max page length
    - [x] Comments
    - [x] Keyboard shortcuts
- [ ] Wiki structures
    - [ ] Sidebars and Footnotes
    - [x] Folder structures
    - [ ] Conventions
        - [ ] PracticalSeries
        - [x] Standard
- [x] Managing a Wiki
    - [x] Revision control
    - [x] Managing commits

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 8.21 &mdash; Nested task lists
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Task lists can be indented as far as you like.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 8.6<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Alerts

Alerts are similar to block quotes (see <a href="#81block-quotes">section&nbsp;8.1</a>) and are used to highlight specific information. GitHub supports five different types of alert:

> [!NOTE]<!-- NOTE ALERT -->
> Sidenotes and footnotes for reference

> [!TIP]<!-- TIP ALERT -->
> Advice or guidance for doing something

> [!IMPORTANT]<!-- IMPORTANT ALERT -->
> Essential information

> [!WARNING]<!-- WARNING ALERT -->
> Information for avoiding problems

> [!CAUTION]<!-- CAUTION ALERT -->
> Potential risks associated with specific actions

Alerts show a different coloured icon for each type and a similarly coloured 4 px wide bar at the left-hand edge of the text.

There is no HTML equivalent for alerts.

The Markdown for the above is:

<table name="t-08-22" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="480">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```md
> [!NOTE]
> Sidenotes and footnotes for reference

> [!TIP]
> Advice or guidance for doing something

> [!IMPORTANT]
> Essential information

> [!WARNING]
> Information for avoiding problems

> [!CAUTION]
> Potential risks associated with specific actions
```
<p> </p></td><!-- 🔴MARKDOWN END OF CELL🔴 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 8.22 &mdash; Alert Markdown
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

> [!NOTE]
> *Alerts cannot be used inside any form of HTML tag* `<p>`, `<table>` *&c.*


The Markdown is fairly self-explanatory and is very similar to block quotes. 

Alerts begin with a greater than sign followed by a space, an open bracket and an exclamation mark `> [!`. 

It then has one of five words (in either upper or lowercase, it doesn’t matter): `NOTE`, `TIP`, `IMPORTANT`, `WARNIN`G or `CAUTION` (any other word will render the line as a block quote). This is followed by a closing bracket `]`. There must be no further text on this line.

Subsequent lines in the alert begin with a greater than sign followed by a space `> `. If a blank line is needed in the alert, simply start it with a greater than sign `>` and leave the rest of the line blank.

Alerts use the following colours:

<table name="t-8-23" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- HEADER ROW --> <tr>
                        <th width="150" align="left">Alert</th>
                        <th width="300" align="left">Colour</th>
                    </tr>
<!-- DATA ROW -->   <tr>
                        <td align="left">${\large \color{#0969DA}\text{Note}}$</td>
                        <td align="left"><code>rgb(009, 105, 218)</code> or <code>#0969DA</code></td>
                    </tr>
<!-- DATA ROW -->   <tr>
                        <td align="left">${\large \color{#1A7F37}\text{Tip}}$</td>
                        <td align="left"><code>rgb(026, 127, 055)</code> or <code>#1A7F37</code></td>
                    </tr>
<!-- DATA ROW -->   <tr>
                        <td align="left">${\large \color{#8250DF}\text{Important}}$</td>
                        <td align="left"><code>rgb(130, 080, 223)</code> or <code>#8250DF</code></td>
                    </tr>
<!-- DATA ROW -->   <tr>
                        <td align="left">${\large \color{#9A6700}\text{Warning}}$</td>
                        <td align="left"><code>rgb(154, 103, 000)</code> or <code>#9A6700</code></td>
                    </tr>
<!-- DATA ROW -->   <tr>
                        <td align="left">${\large \color{#CF222E}\text{Caution}}$</td>
                        <td align="left"><code>rgb(207, 034, 046)</code> or <code>#CF222E</code></td>
                    </tr>
<!-- CAPTION -->    <tr><th colspan="2" align="left"><sup>
<!-- CAPTION TEXT -->Table 8.23 &mdash; Alert colours
                     </sup></th></tr>
</table>                             <!-- TABLE END  🔼🔼(BLANK LINE BELOW) -->

> [!NOTE]<!-- NOTE ALERT -->
> *Alerts cannot be nested.*

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 8.6.1<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">Markdown rules for alerts

<table name="l-08-06" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2776;<!-- 1  --></td>
    <td><!-- TEXT -->Always leave a blank line before and after alerts</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2777;<!-- 2  --></td>
    <td><!-- TEXT -->Alerts always have a header line: <code>[!type]</code>, where type is: <code>NOTE</code>, <code>TIP</code>, <code>IMPORTANT</code>, <code>WARNING</code> or <code>CAUTION</code></td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x2778;<!-- 3  --></td>
    <td><!-- TEXT -->Each line of text in an alert starts with <code>></code> followed by a space</td></tr>
<!-- LIST ROW 04  --><tr><td valign="top">&#x2779;<!-- 4  --></td>
    <td><!-- TEXT -->Separate paragraphs with a <code>></code> on a blank line</td></tr>
<!-- LIST ROW 05  --><tr><td valign="top">&#x277A;<!-- 5  --></td>
    <td><!-- TEXT -->Alerts <strong>cannot</strong> be nested</td></tr>
<!-- LIST ROW 06  --><tr><td valign="top">&#x277B;<!-- 6  --></td>
    <td><!-- TEXT -->Alerts are the same point size as body text</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="798"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 8.6 &mdash; Markdown rules for alerts
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->


<hr><!-- FOOTNOTE SEPARATOR 🟡🟡🟡🟡🟡 -->
<a name="idfn" href="#idfn">Footnotes:<!-- 🟡FOOTNOTE TITLE🟡 -->&emsp;&emsp;&emsp;&emsp;&emsp;</a>
<br><br><br>

> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-01" href="#rn-01"><sup>💠1</sup></a>&emsp;<!-- FOOTNOTE CONTENT TEXT -->For the unordered list, the bullet point was indented three spaces, the thin space instead of the last space in the ordered list allows for the additional full stop character (leaving the actual text for the list indented to the same point as for an unordered list, everything lines up).<!--  CONTENT TEXT END --><a href="#rn-01">↩</a><!-- 🟡🟡🟡🟡🟡 FOOTNOTE END -->
<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->