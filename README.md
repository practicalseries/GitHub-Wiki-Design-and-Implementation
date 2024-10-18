<a name="idtop"></a><!-- TOP OF PAGE IDENTIFIER -->

<!-- PAL LOGO AND WEB ID START-->
<img width="896px" src="https://github.com/practicalseries/GitHub-Wiki-Design-and-Implementation/blob/master/ps-logo-github-wiki.svg?bxno=1436" alt="PAL Logo showing Wiki Documentation heading">
<p align="right"><img height="18px" src="https://img.shields.io/badge/Web_ID-README.md--djr-blue.svg"></p>
<!-- PAL LOGO AND WEB ID END-->

# GitHub Wiki — Design and Implementation

This repository is a result of creating various GitHub Wikis for the PracticalSeries repositories.

It originally started as a template repository that stored a set of GitHub Wiki page examples that I could quickly access and copy to the more relevant Wiki pages in this repository.

In doing so, I realised that there are various techniques *(some might call them hacks)* to get around the limitations of GitHub Flavoured Markdown (GFM), I also realised that while many features of Wikis are documented by GitHub[^1], the explanations in the GitHub documentation don’t always cover everything (or at least the explanations can be hard to find) and you end up looking around all sorts of websites to find the information.

The upshot of all this is that what started as a simple template page has become a bit of a guide for producing GitHub Wiki files. I hope you find it useful.

**The full guide can be found on the Wiki pages for this repository, click the Wiki tab at the top of this page. Alternatively, follow this link:**

**&emsp;&emsp;&emsp;https://github.com/practicalseries/GitHub-Wiki-Design-and-Implementation/wiki**

[^*1]: The GitHub documentation is located here:

    &emsp;&emsp;&emsp;https://docs.github.com/en/enterprise-cloud@latest

    Select `Get started` and then `Writing on GitHub`.

    There is also a style guide for GitHub documents (this is GitHub’s own style guide for its own documentation), and it has some useful tips and conventions:

    &emsp;&emsp;&emsp;https://docs.github.com/en/contributing
        <hr>

**[:arrow_up: Top](#idtop)**<!-- Leave blank line above -->        <!-- LINK TO TOP START -->
<br><br>  
## What does this guide cover?
This guide covers pretty much everything you need to know about creating and managing a GitHub Wiki for a repository. 

It goes from the very basics of creating a page from scratch to the more complicated arrangement of a folder structure, independent sidebars and footers for each page and on to the vagaries of Git Flavoured Markdown, the use of HTML and the various techniques and workarounds that are required to make Wiki pages look good and respond properly.

It covers the following topics:

<table>
  <tr><!-- MAIN LIST (numbered) -->
    <td>&emsp;</td>
    <td colspan="2">
      <ol>
        <li>&emsp;Creating a Wiki for a repository</li>
        <li>&emsp;Cloning a Wiki to a local machine</li>
        <li>&emsp;Understanding how Wiki pages are stored and structured</li>
        <li>&emsp;Basic concepts of a Wiki page</li>
        <li>&emsp;Sidebars and footers</li>
        <li>&emsp;Imposing a folder structure on a Wiki</li>
        <li>&emsp;Creating different sidebars and footers for individual pages</li>
        <li>&emsp;Understanding Markdown, Git Flavoured Markdown and HTML for Wiki pages</li>
        <li>&emsp;Basic Markdown:</li>
      </ol>
    </td>
  </tr><!-- END OF MAIN LIST -->
  <tr><!-- SUBLIST -->
    <td colspan="2">&emsp;&emsp;&emsp;&numsp;&nbsp;</td>
    <td>
      <ul>
        <li>&emsp;Body text</li>
        <li>&emsp;Paragraph</li>
        <li>&emsp;Line breaks</li>
        <li>&emsp;Horizontal lines</li>
        <li>&emsp;Emphasis (bold, italic, underline, strikethrough)</li>
        <li>&emsp;Lists (numbered, unnumbered, nested and combinations)</li>
        <li>&emsp;Block quotes</li>
        <li>&emsp;Headings</li>
        <li>&emsp;Images</li>
        <li>&emsp;Links</li>
        <li>&emsp;Escape characters</li>
        <li>&emsp;Using special space characters</li>
      </ul>
    </td>
  </tr><!-- END OF SUBLIST -->
  
  <tr><!-- MAIN LIST (numbered) -->
    <td>&emsp;</td>
    <td colspan="2">
      <ol start="10"><!-- Main list (numbered) -->
        <li>&emsp;Extended Markdown (Git Flavoured Markdown):</li>
      </ol>
    </td>
  </tr><!-- END OF MAIN LIST -->
  <tr><!-- SUBLIST -->
    <td colspan="2">&emsp;&emsp;&emsp;&numsp;&nbsp;</td>
    <td>
      <ul>
        <li>&emsp;Emojis</li>
        <li>&emsp;Footnotes and alerts</li>
        <li>&emsp;Link to headings</li>
        <li>&emsp;Task lists</li>
        <li>&emsp;Contents</li>
        <li>&emsp;Tables (Markdown)</li>
        <li>&emsp;Code fragments</li>
        <li>&emsp;Code fragments with syntax highlights</li>
        <li>&emsp;Built in diagrams (Mermaid)</li>
        <li>&emsp;Link by reference</li>
      </ul>
    </td>
  </tr><!-- END OF SUBLIST -->
   
  <tr><!-- MAIN LIST (numbered) -->
    <td>&emsp;</td>
    <td colspan="2">
      <ol start="11"><!-- Main list (numbered) -->
        <li>&emsp;HTML within Markdown:</li>
      </ol>
    </td>
  </tr><!-- END OF MAIN LIST -->
  <tr><!-- SUBLIST -->
    <td colspan="2">&emsp;&emsp;&emsp;&numsp;&nbsp;</td>
    <td>
      <ul>
        <li>&emsp;Names and IDs</li>
        <li>&emsp;Tables (HTML)</li>
        <li>&emsp;Tables vertical alignment</li>
        <li>&emsp;Collapsable content</li>
        <li>&emsp;Links with HTML</li>
        <li>&emsp;Images with HTML</li>
        <li>&emsp;Buttons</li>
       <li>&emsp;Navigation bars</li>
      </ul>
    </td>
  </tr><!-- END OF SUBLIST -->
   
  <tr><!-- MAIN LIST (numbered) -->
    <td>&emsp;</td>
    <td colspan="2">
      <ol start="12"><!-- Main list (numbered) -->
        <li>&emsp;Differences between Wiki pages and standard GitHub Markdown pages</li>
        <li>&emsp;PracticalSeries conventions &mdash; How to make the Wiki look good:</li>
      </ol>
    </td>
  </tr><!-- END OF MAIN LIST -->
  <tr><!-- SUBLIST -->
    <td colspan="2">&emsp;&emsp;&emsp;&numsp;&nbsp;</td>
    <td>
      <ul>
        <li>&emsp;Individual Sidebars and footers for each page</li>
        <li>&emsp;IO Badges</li>
        <li>&emsp;Conventions for folders, image storage and data storage</li>
        <li>&emsp;Links to top, bottom and other points on a page</li>
        <li>&emsp;Making footnotes work on Wiki pages</li>
      </ul>
    </td>
  </tr><!-- END OF SUBLIST -->
   
  <tr><!-- MAIN LIST (numbered) -->
    <td>&emsp;</td>
    <td colspan="2">
      <ol start="14"><!-- Main list (numbered) -->
        <li>&emsp;Wiki revision control, commits and rebasing </li>
        <li>&emsp;Examples, templates and good working practices</li>
        <li>&emsp;Appendices of HTML escape codes, emojis and cheat sheets</li>
      </ol>
    </td>
  </tr><!-- END OF MAIN LIST -->
    
  <tr>
    <th><sup>&hairsp;</sup></th>
    <th><sup>&hairsp;</sup></th>
    <th align="left"><sup>Table 1 &mdash; Scope of this repository</sup></th>
  </tr>
</table>

**The full guide can be found on the Wiki pages for this repository, click the Wiki tab at the top of this page. Alternatively, follow this link:**

**&emsp;&emsp;&emsp;https://github.com/practicalseries/GitHub-Wiki-Design-and-Implementation/wiki**

**[:arrow_up: Top](#idtop)**<!-- Leave blank line above -->        <!-- LINK TO TOP START -->
<br><br>



## A note by the Author

GitHub Wiki pages are generally written in Markdown (like this readme file). 

I’ll say right from the start that I’m not the biggest fan of Markdown. I understand the idea, it’s designed to be an easy way to format plain text and make it into a more readable document. It’s easier to understand than the HTML (hyper-text markup language) and CSS (cascading style sheets) used to create web pages, but has roughly the same purpose.

The reason I’m not the biggest fan is that Markdown itself isn’t good enough for today’s documentation requirements. We’re all used to responsive websites with distinct fonts and clever images and animations. Markdown feels a bit like turn of the century websites and is very restrictive in terms of what you can do.

This may be done on purpose, GitHub in particular *(I think)* wants repository documentation to conform to certain styles and have a common appearance (and I have some sympathy for this approach, after all it’s their website and they can impose whatever restrictions they want).

The problem is that basic Markdown doesn’t support all the things that are needed to format a document properly for software documentation. This means that things get added and we have GitHub Flavoured Markdown which supports things such as code fragments, task lists &c. This in itself is also not sufficient and now GitHub Markdown supports certain HTML tags to allow better formatting.

The whole thing is a bit of a mess and is actually quite badly documented. It’s pretty difficult to find out which HTML tags are allowed or not allowed by GitHub. You will spend a lot of time doing Google searches, looking around on the Stack Overflow (https://stackoverflow.com/) website and coming across phrases like *“syntactic sugar*[^2]*”*.

**To overcome some of these problems, I’ve put together descriptions of the things that I’ve discovered and the various work arounds I've found, I’ve also listed some of the more useful sites that I’ve come across in my research[^3] *(clearly, I’m not the only one who found the lack of documentation frustrating)*.**

In a later section I’ve put together a series of conventions, examples and templates that I use on the PracticalSeries Wikis these conventions cover most of the things you will want to do within Wiki pages.

Michael Gledhill<br>Chester &mdash; October 2024

**[:arrow_up: Top](#idtop)**<!-- Leave blank line above -->        <!-- LINK TO TOP START -->
<br><br>  


[^2]: *Syntactic sugar:* a horrible expression that refers to features of a programming language that makes the code easier to read. I suppose along the lines of *“It sweetens the deal”*.
    <hr>


[^3]: The following are some useful sites that cover both the basics and the more esoteric aspects of Markdown.

    Firstly (for what it is worth), the official GitHub specification for GitHub flavoured markdown (GFM):

    &emsp;&emsp;&emsp;https://github.github.com/gfm/

    This is the official specification for what is supported by GFM, it is to a large extent impenetrable and is difficult to understand. Section 4.6 for example, discusses the use of the HTML tag ```<style>``` (example 114) and seems to imply it is supported by GFM. Similarly the ```<script>``` tag is used in example 140; both however, are not supported by GFM. Again, the document is confusing — I may be missing something.

    Next is a much more useful site:

    &emsp;&emsp;&emsp;https://www.markdownguide.org/

    This site is developed by Matt Cone and is a comprehensive list of what Markdown can do. The only slight problem is that is covers various different types of Markdown alternatives (GitHub Flavoured Markdown is only one of many) and the different variations all support different levels of complexity and function, they are all effectively different version of Markdown.

    This site was my goto reference for Markdown and the use of HTML within GitHub flavoured markdown.

    The following covers the features of Markdown in a concise form, it was written by John Gruber who, it so happens, invented Markdown:

    &emsp;&emsp;&emsp;https://daringfireball.net/projects/markdown/basics

    There is one other site listed here that is a bit of an oddball, but I think it may turnout to be quite useful, it’s certainly clever:

    &emsp;&emsp;&emsp;https://pragmaticpineapple.com/adding-custom-html-and-css-to-github-readme/

    GitHub Flavoured Markdown supports the use of SVG images. Now it turns out that you can do quite a lot with the SVG format (SVG is really just a container for code that usually renders a graphical image in a vector format). SVG supports the use of a ```ForeignObject``` element and this element can contain HTML and also inline CSS, it is a way around the HTML restrictions imposed by GitHub *(given their obsession with security, I’m surprised they allow it)*.
 





