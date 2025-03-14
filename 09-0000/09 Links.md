<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="./ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-0900--ebC-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 

# 9<!--         🟥H1🟥--><img width="100" height="1" src="https://psop.uk/wi-s" alt="Spacer">Links

Links are used to jump to a particular page or heading within a Wiki, they can also be used to navigate to other websites or to download files *(just like links on any web page).*

Markdown links can be direct (normal type) links or can be reference-style links. Reference style links do exactly the same as direct links but make the Markdown easier to read (but in turn are more complicated to implement). 

This section concerns itself with direct links (these are by far the most widely used) <a href="09.05-links#97reference-style-links">section&nbsp;9.7</a> covers reference-style links.

Direct links can do the following:

<table name="l-09-01" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x25CF;</td>
    <td><!-- TEXT -->Link to an external web page (a web page that is not associated with a particular Wiki or repository)</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x25CF;</td>
    <td><!-- TEXT -->Link to another page in the same Wiki</td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x25CF;</td>
    <td><!-- TEXT -->Link to headings on the current Wiki page</td></tr>
<!-- LIST ROW 04  --><tr><td valign="top">&#x25CF;</td>
    <td><!-- TEXT -->Link to headings on a different Wiki page</td></tr>
<!-- LIST ROW 05  --><tr><td valign="top">&#x25CF;</td>
    <td><!-- TEXT -->Link to a named element on the same Wiki page</td></tr>
<!-- LIST ROW 06  --><tr><td valign="top">&#x25CF;</td>
    <td><!-- TEXT -->Link to a named element on a different Wiki page</td></tr>
<!-- LIST ROW 07  --><tr><td valign="top">&#x25CF;</td>
    <td><!-- TEXT -->Download a file</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="600"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 9.1 &mdash; Various types of links
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

All of these are covered in the next sections:

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 9.1<!--      🟥H2🟥--><img width="090" height="1" src="https://psop.uk/wi-s" alt="Spacer">Linking to an external web page

This is the easiest *(and probably most common)* type of link, there are different versions:

<table name="l-09-02" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2776;<!-- 1  --></td>
    <td><!-- TEXT -->A straight forward (direct) link to a URL: <a href="https://google.co.uk">https://google.co.uk</a></td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2777;<!-- 2  --></td>
    <td><!-- TEXT -->A link to a URL using substitute text e.g. <a href="https://google.co.uk">Google&nbsp;UK</a></td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x2778;<!-- 3  --></td>
    <td><!-- TEXT -->A link to a URL using substitute text and with a tooltip box that explains the link when the mouse hovers over it: e.g. <a href="https://google.co.uk" title="Link to Google UK">Google&nbsp;UK</a></td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="600"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 9.2 &mdash; Links to an external web page
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

Taking each in turn:

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 9.1.1<!--   🟥H3🟥--><img width="082" height="1" src="https://psop.uk/wi-s" alt="Spacer">A direct link to a URL

Let’s say we want to put a link to the Google UK website on a Wiki page, at its most basic it would look like this:

This is a link to https://google.co.uk.

The Markdown for this is very easy *(in fact there is no Markdown)*, GitHub automatically detects URLs and converts them to a web link: 

<table name="t-09-01" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th align="right" colspan="2"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="500">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                        <th align="left" width="350">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🔴HTML BELOW🔴 -->

```md
This is a link to https://google.co.uk.
```
<p> </p></td><!-- 🔴MARKDOWN END OF CELL🔴 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

This is a link to https://google.co.uk.

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🔴HTML BELOW🔴 -->

```md
This is a link to https://www.google.co.uk.
```
<p> </p></td><!-- 🔴MARKDOWN END OF CELL🔴 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

This is a link to https://www.google.co.uk.

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🔴HTML BELOW🔴 -->

```md
This is a link to www.google.co.uk.
```
<p> </p></td><!-- 🔴MARKDOWN END OF CELL🔴 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

This is a link to www.google.co.uk.

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 9.1 &mdash; Markdown for a basic link
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

The equivalent HTML for the above is:

<table name="t-09-02" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th align="right" colspan="2"><sup>HTML and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left" width="500">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                        <th align="left" width="350">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
<!-- Header end --> </tr>
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
This is a link to <a href="https://google.co.uk">
https://google.co.uk</a>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

This is a link to <a href="https://google.co.uk">
https://google.co.uk</a>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
This is a link to <a href="https://www.google.co.uk">
https://www.google.co.uk</a>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

This is a link to <a href="https://www.google.co.uk">
https://www.google.co.uk</a>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row -->   <tr>
<!-- HTML cell --> <td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
This is a link to <a href="www.google.co.uk">
www.google.co.uk</a>
```
<p> </p></td><!-- 🟢HTML END OF CELL🟢 -->
<!-- GIT cell -->   <td align="left" height="80" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

This is a link to <a href="www.google.co.uk">
www.google.co.uk</a>

</td><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- Data row end--></tr>
<!-- CAPTION -->    <tr><th align="left" colspan="2"><sup>
<!-- CAPTION TEXT -->Table 9.2 &mdash; HTML for a basic link
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

GitHub will render anything that starts `https://`, `http://` or `www.` as a link.

> [!NOTE]<!-- NOTE ALERT -->
> *GitHub does not check the format of the link beyond the starting characters, it would think* www.google *was a perfectly good link (even though the domain suffix is missing), it would also think* https://🌳🌳🌳🌳 *is a link despite the fact the characters in it are not valid for URLs.*

Links are always displayed in blue `rgb(009,105,218) #0969DA` and underlined.

Links are always the same size as body text and can be emphasised with bold or italic by putting the appropriate number of asterisks before and after them (see **<a href="06.04-basic-markdown-and-text-formatting#64emphasis-with-bold">section&nbsp;6.4</a>** and *<a href="06.04-basic-markdown-and-text-formatting#65emphasis-with-italics">section&nbsp;6.5</a>)*. For example:

<table name="t-09-03" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
This is a link to **https://google.co.uk**.
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
This is a link to <strong><a href="https://www.google.co.uk">https://www.google.co.uk</a></strong>
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" height="80" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

This is a link to **https://google.co.uk**.

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 9.3 &mdash; A basic link in bold</sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 9.1.2<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">A link using substitute text

It is possible to use substitute text which is displayed in place of the URL. Things like:

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡-->The PracticalSeries website can be accessed [here](https://practicalseries.com).

The word **here** is displayed in place of the full URL, but clicking the word navigates to the URL: https://practicalseries.com.

The Markdown for this is in the form:


<table name="t-09-03a" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<tr><td width="850" height="60" valign="middle">

&emsp;&emsp;&nbsp;&nbsp; ${\LARGE \color{#0050C0}\text{\[}\color{#C00000}\text{Substitute\ Text}\color{#0050C0}\text{\]\(}\color{#1F883D}\text{URL}\color{#0050C0}\text{\)}}$
</td></tr>
</table>                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->

The ${\large \color{#C00000}\text{Substitute\ Text}}$ can be anything at all (including spaces, emojis and any other character), the ${\large \color{#1F883D}\text{URL}}$ must be a proper URL. There is no space between the closing bracket and opening parenthesis: ${\large \color{#0050C0}\text{\]\(}}$.

The Markdown for the above is:

<table name="t-09-04" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
The PracticalSeries website can be accessed [here](https://practicalseries.com).
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
The PracticalSeries website can be accessed <a href="https://practicalseries.com">
here</a>
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" height="80" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

The PracticalSeries website can be accessed [here](https://practicalseries.com).

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 9.4 &mdash; A basic link with substitute text
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->


### 9.1.3<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">A link using substitute text with tooltip

A tooltip is a small box that opens up to display some information about the link whenever the mouse hovers over the link:

Try it by hovering the mouse over the link below:

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡-->Search engine [Google](https://Google.co.uk "Link to Google UK").

The following figure shows the effect:

<table name="f-09-02" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./09-0000/02-images/figm-09-01.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="385" src="./09-0000/02-images/figm-09-01.png" alt="Link with tooltip">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 9.2 &mdash; Link to a web page with substitute text and tooltip
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

The Markdown for this is in the form:

<table name="t-09-03a" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<tr><td width="850" height="60" valign="middle">

&emsp;&emsp;&nbsp;&nbsp; ${\LARGE \color{#0050C0}\text{\[}\color{#C00000}\text{Substitute\ Text}\color{#0050C0}\text{\]\(}\color{#1F883D}\text{URL}\color{#0050C0}\text{\ "}\color{#ED7D31}\text{Tooltip\ Text}\color{#0050C0}\text{"\)}}$
</td></tr>
</table>                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->

The ${\large \color{#C00000}\text{Substitute\ Text}}$ can be anything at all (including spaces, emojis and any other character), the ${\large \color{#1F883D}\text{URL}}$ must be a proper URL the ${\large \color{#ED7D31}\text{Tootltip\ Text}}$ can also be anything at all. There is no space between the closing bracket and opening parenthesis: ${\large \color{#0050C0}\text{\]\(}}$. There must be at least one space between the end of the URL and the first quotation mark.

The Markdown for the above figure is:

<table name="t-09-05" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
Search engine [Google](https://Google.co.uk "Link to Google UK").
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
Search engine <a href="https://google.co.uk" title="Link to Google UK">Google</a>.
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" height="80" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

Search engine [Google](https://Google.co.uk "Link to Google UK").

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 9.5 &mdash; A basic link with substitute text and tooltip
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 9.2<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Linking to another page in the same Wiki

Linking to pages in the same Wiki doesn’t require a full web address (URL), GitHub accepts relative addresses<a name="rn-01" href="#fn-01"><!-- 🟨FOOTNOTE LINK🟨--><sup>💠1</sup></a> (this is true for both Markdown and HTML).

Let’s say that a Wiki exists with three pages in a folder structure as follows:

<table name="f-09-01" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./09-0000/02-images/figm-09-02.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="345" src="./09-0000/02-images/figm-09-02.png" alt="Simple Wiki structure">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 9.1 &mdash; Simple Wiki structure
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

Here there are three pages: `Home.md` in the root directory, `Page01.md` in folder `01_Page1` and `Page02.md` in folder `02_Page2`. The `.md` files are shown in red in the above figure.

All Wiki pages are `.md` files and GitHub ignores the folder structure when navigating the Wiki folder structure for `.md` *(but only for* `.md` *files, all other files must include the correct path to the file).*

To link to any other page in the Wiki, all that is necessary is to include the filename, **but not the extension** in the link.

Thus if `Page02.md` required a link to `Page01.md` it would simply have the following Markdown:

<table name="t-09-06" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
[Link to page 1](page01)
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<a href="page01">Link to page 1</a>
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" height="80" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

[Link to page 1](page01)

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 9.6 &mdash; Relative link to a page within the same Wiki
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

> [!NOTE]<!-- NOTE ALERT -->
> *The important thing to remember is that the* `.md` *extension **must not be included** in the relative link. Only use the filename that precedes the extension (it is not case sensitive).*

All that is needed for a link to any other page in the Wiki is simply the filename of the page that is to be navigated to (**always without the file extension**<a name="rn-02" href="#fn-02"><!-- 🟨FOOTNOTE LINK🟨--><sup>💠2</sup></a>)

Links to other page in the Wiki can also have tooltips (in exactly the same way as links to an external page, see <a href="#913a-link-using-substitute-text-with-tooltip">section&nbsp;9.1.3</a> ), in this form:


<table name="t-09-06a" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<tr><td width="850" height="60" valign="middle">

&emsp;&emsp;&nbsp;&nbsp; ${\LARGE \color{#0050C0}\text{\[}\color{#C00000}\text{Substitute\ Text}\color{#0050C0}\text{\]\(}\color{#1F883D}\text{PageName}\color{#0050C0}\text{\ "}\color{#ED7D31}\text{Tooltip\ Text}\color{#0050C0}\text{"\)}}$
</td></tr>
</table>                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->

For example adding a tooltip to the previous example gives *(to see the effect, hover the mouse over the link at the bottom)*:

<table name="t-09-07" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
[Link to page 1](page01 "GO TO PAGE 1")
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<a href="page01" title="GO TO PAGE 1">Link to page 1</a>
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" height="80" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

[Link to page 1](page01 "GO TO PAGE 1")

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 9.7 &mdash; Relative link to a page within the same Wiki with tooltip
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 9.2.1<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">Rules for linking to a Wiki page

The Markdown and HTML forms for linking to a Wiki page are:

<table name="t-09-07a" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<tr><td width="850" height="60" valign="middle">

&emsp;&emsp;&nbsp;&nbsp; ${\LARGE \color{#0050C0}\text{\[}\color{#C00000}\text{Substitute\ Text}\color{#0050C0}\text{\]\(}\color{#1F883D}\text{PageName}\color{#0050C0}\text{\ "}\color{#ED7D31}\text{Tooltip\ Text}\color{#0050C0}\text{"\)}}$ <br><br>

&emsp;&emsp;&nbsp;&nbsp; ${\LARGE \color{#0050C0}\text{<a href="}\color{#1F883D}\text{PageName}\color{#0050C0}\text{" title="}\color{#0050C0}\text{\ "}\color{#ED7D31}\text{Tooltip\ Text}\color{#0050C0}\text{">)}\color{#C00000}\text{Substitute\ Text}\color{#0050C0}\text{</}\text{a>}}$ 
</td></tr>
</table>                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->

The ${\LARGE \color{#1F883D}\text{PageName}}$ in the both the Markdown link and the HTML link is the same as the name of the `.md` file with the following changes:

<table name="l-09-03" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2776;<!-- 1  --></td>
    <td><!-- TEXT -->Do not add the <code>.md</code> extension to the ${\LARGE \color{#1F883D}\text{PageName}}$</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2777;<!-- 2  --></td>
    <td><!-- TEXT -->Any spaces within the ${\LARGE \color{#1F883D}\text{PageName}}$ are replaced with a dash `-`</td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x2778;<!-- 3  --></td>
    <td><!-- TEXT -->All uppercase letters are made lowercase (optional)</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="798"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 9.3 &mdash; RRules for converting a page name to a link
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

For example, the page:

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡--> ${\LARGE \color{#446FBD}\text{08.02\ Block\ quotes,\ lists\ and\ alerts.md}}$

Would becomes the ${\LARGE \color{#1F883D}\text{PageName}}$:

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡--> ${\LARGE \color{#1F883D}\text{08.02-block-quotes,-lists-and-alerts}}$

Thus:

<table name="t-09-07b" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
[Section 8.2](08.02-block-quotes,-lists-and-alerts)
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<a href="08.02-block-quotes,-lists-and-alerts">Section 8.2</a>
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" height="80" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

[Section 8.2](08-block-quotes,-lists-and-alerts#82unordered-unnumbered-lists)

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

> [!NOTE]<!-- NOTE ALERT -->
> *While it is not necessary to change the name to all lowercase letters, it is best to do so, it gives consistency to the addressing.*

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 9.3<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Linking to headings on the current page

GitHub can link to any Markdown heading on a page *(the ones constructed with leading hashes, see <a href="06.10-basic-markdown-and-text-formatting#610headings">section&nbsp;6.10</a> )*. In fact, GitHub highlights the links and allows them to be copied, these highlights are the small chains that appear when the mouse hovers over the link:

<table name="f-09-03" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./09-0000/02-images/figm-09-03.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="850" src="./09-0000/02-images/figm-09-03.png" alt="Heading link icon">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 9.3 &mdash; Heading link icon (highlighted)
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

To copy the link, right click and select ${\large \color{#00B050}\langle\text{Copy\ link}\rangle}$ from the drop down *(note, this copies the full URL to the link)*. Left clicking the link will navigate to the heading (i.e. put the heading at the top of the browser page).

Clicking a link to a heading navigates up or down the page until the heading is at the top of the browser window.

Links to a heading on the same page are constructed in a similar way to the direct link using substitute text (see <a href="#912a-link-using-substitute-text">section&nbsp;9.1.2</a>) as follows:

<table name="t-09-07c" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<tr><td width="850" height="60" valign="middle">

&emsp;&emsp;&nbsp;&nbsp;&nbsp; <img width="328" src="./09-0000/02-images/figm-09-03a.png" alt="Heading link icon">
</td></tr>
</table>                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->

The ${\large \color{#C00000}\text{Substitute\ Text}}$ can be anything you like; this is what is displayed as the link text.

> [!NOTE]<!-- NOTE ALERT -->
> *Just inserting the hash and the #headingName directly in the Markdown (like the direct link of <a href="#911a-direct-link-to-a-url">section&nbsp;9.1.1</a>) will not work.*

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 9.3.1<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">Rules for converting a heading to a link

The ${\large \color{#00B050}\text{headingName}}$ is the same as the heading itself with the following changes:

<table name="l-09-04" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2776;<!-- 1  --></td>
    <td><!-- TEXT -->There is only one hash `#` before the ${\large \color{#00B050}\text{headingName}}$ irrespective of the heading level</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2777;<!-- 2  --></td>
    <td><!-- TEXT -->All text is converted to lowercase</td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x2778;<!-- 3  --></td>
    <td><!-- TEXT -->Spaces are converted to a single dash</td></tr>
<!-- LIST ROW 04  --><tr><td valign="top">&#x2779;<!-- 4  --></td>
    <td><!-- TEXT -->If multiple consecutive spaces are present, they are converted to a single dash</td></tr>
<!-- LIST ROW 05  --><tr><td valign="top">&#x277A;<!-- 5  --></td>
    <td><!-- TEXT -->Special space characters (see <a href="07-special-characters-and-escaping-characters#72special-space-characters">section&nbsp;7.2</a>) are ignored</td></tr>
<!-- LIST ROW 06  --><tr><td valign="top">&#x277B;<!-- 6  --></td>
    <td><!-- TEXT -->Any HTML tags are ignored (tags and attributes between `<>`)</td></tr>
<!-- LIST ROW 07  --><tr><td valign="top">&#x277C;<!-- 7  --></td>
    <td><!-- TEXT -->Any comments within the heading (text between `<!--  -->`) are ignored</td></tr>
<!-- LIST ROW 08  --><tr><td valign="top">&#x277D;<!-- 8  --></td>
    <td><!-- TEXT -->Numbers (0 to 9) are included</td></tr>
<!-- LIST ROW 09  --><tr><td valign="top">&#x277E;<!-- 9  --></td>
    <td><!-- TEXT -->All non-alphanumeric characters are ignored</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="798"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 9.4 &mdash; Rules for converting a heading
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 9.3.2<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">An example of a heading link

For example, on the Wiki page: [01 Introducing the GitHub Wiki](01-introducing-the-github-wiki) there is a heading: 
[1.1. What are GitHub Wiki pages?](01-introducing-the-github-wiki#11what-are-github-wiki-pages).

The Markdown for the heading is this:

<table name="t-09-07d" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
## 1.1&ensp;&emsp;&emsp;&ensp;&emsp13;&emsp13;&hairsp;<!-- H2 -->What are GitHub Wiki pages?
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

## 1.1&ensp;&emsp;&emsp;&ensp;&emsp13;&emsp13;&hairsp;<!-- H2 -->What are GitHub Wiki pages?

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Now, this heading is a bit more complicated than the headings in <a href="06.10-basic-markdown-and-text-formatting#610headings">section&nbsp;6.10</a>, but it works in the same way:

It starts as normal, with two hashes `##`, it is a level 2 heading. There is a chapter and section number separated by a full stop `1.1`.

Next, there are various special spacing characters: `&ensp;&emsp;&emsp;&ensp;&emsp13;&emsp13;&hairsp;`, these are used to space the title text from the heading number (see <a href="07-special-characters-and-escaping-characters#72special-space-characters">section&nbsp;7.2</a>). This is followed by a comment field `<!-- H2 -->` that identifies the heading as a level 2 heading.

Finally, there is a question mark `?` at the end.

The link to this heading (from within the same page), would be:

<table name="t-09-08" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
Link to [1.1 What are GitHub Wiki pages?](#11what-are-github-wiki-pages)
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
Link to <a href="#11what-are-github-wiki-pages">1.1 What are GitHub Wiki pages?</a>
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td width="850" height="60" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

Link to [1.1 What are GitHub Wiki pages?](01-introducing-the-github-wiki#11what-are-github-wiki-pages)

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 9.8 &mdash; A link to a heading on the same page
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Let’s examine what has happened to the heading link: ${\large \color{#1F883D}\text{11what-are-github-wiki-pages}}$ by applying the rules in the list in the previous section (<a href="#l-09-03">List&nbsp;9.3</a>):

It is preceded by a single hash `#`, links only use one hash irrespective of the heading level.

The numbers `11` are the numbers in the heading `1.1` without the full stop (all non-alphanumeric characters are ignored).

All the special space characters `&emsp;` &c. are ignored as is the comment field.

Thus, the numbers are immediately followed by the text of the heading in lowercase.

All the spaces between the words in the heading text are replaced with dashes `-`.

Finally, the question mark at the end is missing (all non-alphanumeric characters are ignored).

So the Markdown (or HTML `href` ) for the link to the heading becomes:

<table name="t-09-08a" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
#11what-are-github-wiki-pages
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

### 9.3.3<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Heading link with tooltips

Tooltips can also be applied to links to headings, this is exactly the same as shown in <a href="#913a-link-using-substitute-text-with-tooltip">section&nbsp;9.1.3</a> *(hover the mouse over the link at the bottom to see the tooltip)*:

<table name="t-09-09" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
Link to [1.1. What are GitHub Wiki pages?](#11what-are-github-wiki-pages "HEADING LINK")
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
Link to <a href="#11what-are-github-wiki-pages" title="HEADING LINK">1.1. What are GitHub Wiki pages?</a>
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td width="850" height="60" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

Link to [1.1. What are GitHub Wiki pages?](01-introducing-the-github-wiki#11what-are-github-wiki-pages "HEADING LINK")


</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 9.9 &mdash; A link to a heading on the same page with tooltips
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 9.4<!--      🟥H2🟥--><img width="086" height="1" src="https://psop.uk/wi-s" alt="Spacer">Linking to headings on a different page

It is possible to link to any heading on a page within the same Wiki by adding the page name to the Markdown link. Links to a Hheading links to a point on a different page are constructed in a similar way to the heading link on a same page (see <a href="#93linking-to-headings-on-the-current-page">section&nbsp;9.3</a>), but also include the page name:



<table name="t-09-03a" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<tr><td width="850" height="60" valign="middle">

&emsp;&emsp;&nbsp;&nbsp; ${\LARGE \color{#0050C0}\text{\[}\color{#C00000}\text{Substitute\ Text}\color{#0050C0}\text{\]\(}\color{#4B0082}\text{pageName\}}$<img width="15" src="./09-0000/02-images/figm-09-03b.png?bx=0911" alt="Hash">${\LARGE \color{#1F883D}\text{headingName}\color{#0050C0}\text{\)}}$
</td></tr>
</table>                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->

The ${\large \color{#C00000}\text{Substitute\ Text}}$ can be anything you like, this is displayed as the link text.

The rules for the ${\large \color{#4B0082}\text{pageName}}$ and ${\large \color{#1F883D}\text{headingName}}$ are given in <a href="#921rules-for-linking-to-a-wiki-page">section&nbsp;9.2.1</a> and <a href="#931rules-for-converting-a-heading-to-a-link">section&nbsp;9.3.1</a>.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 9.4.1<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">An example of a heading link

Using the same example of <a href="#932an-example-of-a-heading-link">section&nbsp;9.3.2</a> where:

The Wiki page: [01 Introducing the GitHub Wiki](01-introducing-the-github-wiki) has the heading: 
[1.1. What are GitHub Wiki pages?](01-introducing-the-github-wiki#11what-are-github-wiki-pages).

The Markdown for the heading is this:

<table name="t-09-09a" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
## 1.1&ensp;&emsp;&emsp;&ensp;&emsp13;&emsp13;&hairsp;<!-- H2 -->What are GitHub Wiki pages?
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

This is the same as the heading in <a href="#932an-example-of-a-heading-link">section&nbsp;9.3.2</a>.

The heading becomes the following when coverted to a link (again see <a href="#932an-example-of-a-heading-link">section&nbsp;9.3.2</a>), the ${\large \color{#1F883D}\text{headingName}}$:

<table name="t-09-09b" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
#11what-are-github-wiki-pages
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

The ${\large \color{#4B0082}\text{pageName}}$ (using the rules of <a href="#921rules-for-linking-to-a-wiki-page">section&nbsp;9.2.1</a>) becomes:


<table name="t-09-09c" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
01-introducing-the-github-wiki
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Thus the whole link become:


<table name="t-09-10" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
[1.1.What are GitHub Wiki pages?](01-introducing-the-github-wiki#11what-are-github-wiki-pages)
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<a href="01-introducing-the-github-wiki#11what-are-github-wiki-pages">1.1 What are GitHub Wiki pages?</a>
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td width="850" height="60" valign="middle"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

[1.1 What are GitHub Wiki pages?](01-introducing-the-github-wiki#11what-are-github-wiki-pages)

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 9.10 &mdash; A link to a heading on a different  page
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->


<hr><!-- FOOTNOTE SEPARATOR 🟡🟡🟡🟡🟡 -->
<a name="idfn" href="#idfn">Footnotes:<!-- 🟡FOOTNOTE TITLE🟡 -->&emsp;&emsp;&emsp;&emsp;&emsp;</a>
<br><br><br>

> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-01" href="#rn-01"><sup>💠1</sup></a>&emsp;<!-- FOOTNOTE CONTENT TEXT -->A relative address, or relative file path, identifies the location of a file *relative* to the location of the current page. It is common practice for websites to use relative addressing (see <a href="09.05-links#98relative-links">section&nbsp;9.8</a> for details).<!--  CONTENT TEXT END --><a href="#rn-01">↩</a><!-- 🟡🟡🟡🟡🟡 FOOTNOTE END -->

> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-02" href="#rn-02"><sup>💠2</sup></a>&emsp;<!-- FOOTNOTE CONTENT TEXT -->The relative link must not include the file extension, if the link in the example were `page01.md`, the link would not work, GitHub will not find the file (I think it adds `.md` to the filename and is now trying to find a file that ends `.md.md` and it can’t).<!--  CONTENT TEXT END --><a href="#rn-02">↩</a><!-- 🟡🟡🟡🟡🟡 FOOTNOTE END -->
<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->
