<a name="idtop"></a><!-- TOP OF PAGE IDENTIFIER -->

# GitHub Wiki — Design and Implementation

This repository is a result of creating various GitHub Wikis for the PracticalSeries repositories.

It originally started as a template repository that stored a set of GitHub page Wiki examples that I could quickly access and copy to the more relevant Wiki pages in this repository.

In doing so, I realised that there are various techniques (some might call them hacks) to get around the limitations of GitHub Flavoured Markdown (GFM), I also realised that while many features of Wikis are documented by GitHub[^1]:

The explanations in the GitHub documentation don’t always cover everything (or at least the explanations can be hard to find) and you end up looking around all sorts of websites to find the information.

The upshot of all this is that what started as a simple template page has become a bit of a guide for producing GitHub Wiki files. I hope you find it useful.

**The full guide can be found on the Wiki pages for this repository, click the Wiki tab at the top of this page. Alternatively, follow this link:**

**&emsp;&emsp;&emsp;https://github.com/practicalseries/GitHub-Wiki-Design-and-Implementation/wiki**

[^1]: The GitHub documentation is located here:

    &emsp;&emsp;&emsp;https://docs.github.com/en/enterprise-cloud@latest

    Select Get started and then Writing on GitHub.

    There is also a style guide for GitHub documents (this is GitHub’s own style guide for its own documentation), and it has some useful tips and conventions:

    &emsp;&emsp;&emsp;https://docs.github.com/en/contributing

**[:arrow_up: Top](#idtop)**<!-- Leave blank line above -->        <!-- LINK TO TOP START -->
<br><br>  
## What does this guide cover
This guide covers pretty much everything you need to know about creating and managing a GitHub Wiki for a repository. It goes from the very basics of creating a page from scratch to the more complicated arrangement of a folder structure, independent sidebars and footers for each page and on to the vagaries of Git Flavoured Markdown, the use of HTML and the various techniques and workarounds that are required to make Wiki pages look good and respond properly.

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
        <li>&emsp;Basic Markdown</li>
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
        <li>&emsp;Extended Markdown (Git Flavoured Markdown)</li>
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
        <li>&emsp;HTML within Markdown</li>
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
        <li>&emsp;Navigation bars</li>
      </ul>
    </td>
  </tr><!-- END OF SUBLIST -->
   
  <tr><!-- MAIN LIST (numbered) -->
    <td>&emsp;</td>
    <td colspan="2">
      <ol start="12"><!-- Main list (numbered) -->
        <li>&emsp;Differences between Wiki pages and standard GitHub Markdown pages</li>
        <li>&emsp;PracticalSeries conventions &mdash How to make the Wiki look good</li>
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
    <td><sup>&hairsp;</sup></td>
    <td><sup>&hairsp;</sup></td>
    <td><sup>&hairsp;</sup></td>
  </tr>
</table>

**The full guide can be found on the Wiki pages for this repository, click the Wiki tab at the top of this page. Alternatively, follow this link:**

**&emsp;&emsp;&emsp;https://github.com/practicalseries/GitHub-Wiki-Design-and-Implementation/wiki**

**[:arrow_up: Top](#idtop)**<!-- Leave blank line above -->        <!-- LINK TO TOP START -->
<br><br>

