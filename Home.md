<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="./ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-Home--eaq-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 


# <!--       🟥H1🟥-->GitHub Wiki &mdash; Design and Implementation 

These Wiki pages are designed to be a full guide to developing and implementing a GitHub Wiki documentation project.

It originally started as a template that stored a set of GitHub Wiki page examples that I could quickly access and copy to the other Wiki pages in a repository.

In doing so, I realised that there are various techniques *(some might call them hacks)* to get around the limitations of GitHub Flavoured Markdown (GFM), I also realised that while many features of Wikis are documented by GitHub<a name="rn-01" href="#fn-01"><!-- FOOTNOTE LINK--><sup>💠1</sup></a>, the explanations in the GitHub documentation don’t always cover everything (or at least the explanations can be hard to find) and you end up looking around all sorts of websites to find the information.

The upshot of all this is that what started as a simple template page has become a bit of a guide for producing GitHub Wiki files. I hope you find it useful.

There is also a pdf version of the Wiki that you can download and use. It’s available here for free:

<p align="center"><a href="https://github.com/practicalseries/GitHub-Wiki-Design-and-Implementation/wiki/00-0000/04-data/github-wiki-design.pdf" download><img height="30" src="https://img.shields.io/badge/Download_the_pdf_version_of_this_Wiki-1F883D"></a></p>


**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

# <!--       🟥H1🟥-->What does this guide cover?

This guide covers pretty much everything you need to know about creating and manag-ing a GitHub Wiki for a repository.

It goes from the very basics of creating a page from scratch to the more complicated arrangement of a folder structure, independent sidebars and footers for each page and on to the vagaries of Git Flavoured Markdown, the use of HTML and the various techniques and workarounds that are required to make Wiki pages look good and respond properly.
It covers the following topics:

<table name="l-00-01" align="center">  <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- MAIN LIST - START --><tr><td></td><!-- first cell is empty (spacer) -->
<!-- MAIN LIST - NUMBER --> <td colspan="2"><ol start="1">
<li>&emsp;&emsp;<!-- TEXT -->Creating a Wiki for a repository</li>
<li>&emsp;&emsp;<!-- TEXT -->Cloning a Wiki to a local machine</li>
<li>&emsp;&emsp;<!-- TEXT -->Understanding how Wiki pages are stored and structured</li>
<li>&emsp;&emsp;<!-- TEXT -->Basic concepts of a Wiki page</li>
<li>&emsp;&emsp;<!-- TEXT -->Sidebars and footers</li>
<li>&emsp;&emsp;<!-- TEXT -->Imposing a folder structure on a Wiki</li>
<li>&emsp;&emsp;<!-- TEXT -->Creating different sidebars and footers for individual pages</li>
<li>&emsp;&emsp;<!-- TEXT -->Understanding Markdown, Git Flavoured Markdown and HTML for Wiki pages</li>
<li>&emsp;&emsp;<!-- TEXT -->Basic Markdown:</li>
<!-- END OF MAIN LIST --> </ol></td></tr>
<!-- SUB LIST - START --> <tr><td colspan="2"></td><td><ul><!-- Entry in third column -->
<li>&emsp;&emsp;<!-- TEXT -->Body text</li>
<li>&emsp;&emsp;<!-- TEXT -->Paragraphs</li>
<li>&emsp;&emsp;<!-- TEXT -->Line breaks</li>
<li>&emsp;&emsp;<!-- TEXT -->Horizontal lines</li>
<li>&emsp;&emsp;<!-- TEXT -->Emphasis (bold, italic, underline, strikethrough)</li>
<li>&emsp;&emsp;<!-- TEXT -->Lists (numbered, unnumbered, nested and combinations)</li>
<li>&emsp;&emsp;<!-- TEXT -->Block quotes</li>
<li>&emsp;&emsp;<!-- TEXT -->Headings</li>
<li>&emsp;&emsp;<!-- TEXT -->Links</li>
<li>&emsp;&emsp;<!-- TEXT -->Images</li>
<li>&emsp;&emsp;<!-- TEXT -->Escape characters</li>
<li>&emsp;&emsp;<!-- TEXT -->Using special space characters</li>
<!-- END OF SUB LIST -->  </ul></td></tr>
<!-- MAIN LIST - START --><tr><td></td> <!-- first cell is empty (spacer) -->
<!-- MAIN LIST - NUMBER --> <td colspan="2"><ol start="10">
<li>&emsp;&emsp;<!-- TEXT -->Extended Markdown (Git Flavoured Markdown):</li>
<!-- END OF MAIN LIST --> </ol></td></tr>
<!-- SUB LIST - START --> <tr><td colspan="2"></td><td><ul><!-- Entry in third column -->
<li>&emsp;&emsp;<!-- TEXT -->Footnotes and alerts</li>
<li>&emsp;&emsp;<!-- TEXT -->Links to headings</li>
<li>&emsp;&emsp;<!-- TEXT -->Task lists</li>
<li>&emsp;&emsp;<!-- TEXT -->Tables of contents</li>
<li>&emsp;&emsp;<!-- TEXT -->Tables (Markdown)</li>
<li>&emsp;&emsp;<!-- TEXT -->Code fragments (with syntax highlighting)</li>
<li>&emsp;&emsp;<!-- TEXT -->Formulae and LaTeX</li>
<li>&emsp;&emsp;<!-- TEXT -->Built in diagrams (Mermaid) and interactive maps</li>
<li>&emsp;&emsp;<!-- TEXT -->Links by reference </li>
<li>&emsp;&emsp;<!-- TEXT -->Emojis</li>
<!-- END OF SUB LIST -->  </ul></td></tr>
<!-- MAIN LIST - START --><tr><td></td> <!-- first cell is empty (spacer) -->
<!-- MAIN LIST - NUMBER --> <td colspan="2"><ol start="11">
<li>&emsp;&emsp;<!-- TEXT -->HTML within Markdown:</li>
<!-- END OF MAIN LIST --> </ol></td></tr>
<!-- SUB LIST - START --> <tr><td colspan="2"></td><td><ul><!-- Entry in third column -->
<li>&emsp;&emsp;<!-- TEXT -->Names and anchor points</li>
<li>&emsp;&emsp;<!-- TEXT -->Tables (HTML)</li>
<li>&emsp;&emsp;<!-- TEXT -->Tables vertical alignment</li>
<li>&emsp;&emsp;<!-- TEXT -->Collapsable content</li>
<li>&emsp;&emsp;<!-- TEXT -->Links with HTML</li>
<li>&emsp;&emsp;<!-- TEXT -->Images with HTML</li>
<li>&emsp;&emsp;<!-- TEXT -->Buttons</li>
<li>&emsp;&emsp;<!-- TEXT -->Navigation bars</li>
<!-- END OF SUB LIST -->  </ul></td></tr>
<!-- MAIN LIST - START --><tr><td></td> <!-- first cell is empty (spacer) -->
<!-- MAIN LIST - NUMBER --> <td colspan="2"><ol start="12">
<li>&emsp;&emsp;<!-- TEXT -->Differences between Wiki pages and standard GitHub Markdown pages</li>
<li>&emsp;&emsp;<!-- TEXT -->PracticalSeries conventions &mdash; How to make the Wiki look good:</li>
<!-- END OF MAIN LIST --> </ol></td></tr>
<!-- SUB LIST - START --> <tr><td colspan="2"></td><td><ul><!-- Entry in third column -->
<li>&emsp;&emsp;<!-- TEXT -->Sidebars and footers, best practice</li>
<li>&emsp;&emsp;<!-- TEXT -->IO Badges</li>
<li>&emsp;&emsp;<!-- TEXT -->Conventions for folders, image storage and data storage</li>
<li>&emsp;&emsp;<!-- TEXT -->Links to top, bottom and other points on a page</li>
<li>&emsp;&emsp;<!-- TEXT -->Making footnotes work on Wiki pages</li>
<!-- END OF SUB LIST -->  </ul></td></tr>
<!-- MAIN LIST - START --><tr><td></td> <!-- first cell is empty (spacer) -->
<!-- MAIN LIST - NUMBER --> <td colspan="2"><ol start="13">
<li>&emsp;&emsp;<!-- TEXT -->Wiki revision control, commits and rebasing</li>
<li>&emsp;&emsp;<!-- TEXT -->Examples, templates and good working practices</li>
<li>&emsp;&emsp;<!-- TEXT -->Appendices of HTML escape codes, emojis and character</li>
<!-- END OF MAIN LIST --> </ol></td></tr>
<!-- CAPTION -->          <tr><th width="50"></th><th width="52"></th><!-- SPACERS -->
<!-- LIST WIDTH -->         <th align="left" width="600"><sup>
<!-- CAPTION TEXT -->&emsp;<!-- TEXT -->List 1 &mdash; Scope of this Wiki
                          </sup></th></tr>
</table>                               <!-- LIST END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

# <!--       🟥H1🟥-->A note by the Author

GitHub Wiki pages are generally written in Markdown (like repository `README.md` files).

I’ll say right from the start that I’m not the biggest fan of Markdown. I understand the idea, it’s designed to be an easy way to format plain text and make it into a more readable document. It’s easier to understand than the HTML (hyper-text markup language) and CSS (cascading style sheets) used to create web pages, but has roughly the same purpose.

The reason I’m not the biggest fan is that Markdown itself isn’t good enough for today’s documentation requirements. We’re all used to responsive websites with distinct fonts and clever images and animations. Markdown feels a bit like turn of the century websites and is very restrictive in terms of what you can do.

This may be done on purpose, GitHub in particular (I think) wants repository documentation to conform to certain styles and have a common appearance (and I have some sympathy for this approach, after all it’s their website and they can impose whatever restrictions they want).

The problem is that basic Markdown doesn’t support all the things that are needed to format a document properly for software documentation. This means that things get added and we have GitHub Flavoured Markdown which supports things such as code fragments, task lists &c. This in itself is also not sufficient and now GitHub Markdown supports certain HTML tags to allow better formatting.

The whole thing is a bit of a mess and is actually quite badly documented. It’s pretty difficult to find out which HTML tags are allowed or not allowed by GitHub. You will spend a lot of time doing Google searches, looking around on the Stack Overflow (https://stackoverflow.com/) website and coming across phrases like “syntactic sugar<a name="rn-02" href="#fn-02"><!-- FOOTNOTE LINK--><sup>💠2</sup></a>”.

**To overcome some of these problems, I’ve put together descriptions of the things that I’ve discovered and the various work arounds I've found, I’ve also listed some of the more useful sites that I’ve come across in my research** *(clearly, I’m not the only one who found the lack of documentation frustrating)*.

In a later section I’ve put together a series of conventions, examples and templates that I use on the PracticalSeries Wikis these conventions cover most of the things you will want to do within Wiki pages.

Michael Gledhill
Chester &mdash; January 2025

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->


<a name="idfn" href="#idfn">Footnotes:<!-- 🟡FOOTNOTE TITLE🟡 -->&emsp;&emsp;&emsp;&emsp;&emsp;</a>

> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-01" href="#rn-01"><sup>💠1</sup></a>&emsp;The GitHub documentation is located here:
> 
> &emsp;&emsp;&emsp;<!--- ENTER URL -->https://docs.github.com/en/enterprise-cloud@latest
> 
> Select [Get started](https://docs.github.com/en/enterprise-cloud@latest/get-started) and then [Writing on GitHub](https://docs.github.com/en/enterprise-cloud@latest/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github).
> 
> There is also a style guide for GitHub documents (this is GitHub’s own style guide for its own documentation), and it has some useful tips and conventions:
>
> &emsp;&emsp;&emsp;<!--- ENTER URL -->https://docs.github.com/en/contributing
>
> As an aside, the GitHub documentation is actually a repository in it's own right (it can be useful to see how GitHub do things). You can find it here:
> 
>&emsp;&emsp;&emsp;<!--- ENTER URL -->https://github.com/github/docs/tree/main/content
> <a href="#rn-01">↩</a>

<br><br>

> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-02" href="#rn-02"><sup>💠2</sup></a>&emsp;**Syntactic sugar**: a horrible expression that refers to features of a programming language that makes the code easier to read. I suppose along the lines of *“It sweetens the deal”*.<a href="#rn-02">↩</a>
<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->
