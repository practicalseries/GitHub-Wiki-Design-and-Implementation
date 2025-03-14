<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="./ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-0500--eaq-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 


# 5<!--         🟥H1🟥--><img width="100" height="1" src="https://psop.uk/wi-s" alt="Spacer">Markdown, GitHub Markdown and HTML

This section and those following cover the standard markdown and GitHub Flavoured Markdown (GFM) formatting techniques available within Wiki pages. It also covers the use of Hypertext Markup Language (HTML) within Wiki pages. 

HTML can be used within Wiki pages to a limited extent (GitHub restricts *“sanitises”* the range of HTML tags and attributes that can be used on its pages), but even this restricted form of HTML within Wiki pages is very useful and generally leads to better formatting on a Wiki page.

## 5.1<!--      🟥H2🟥--><img width="090" height="1" src="https://psop.uk/wi-s" alt="Spacer">Some useful Markdown sites

The following are some useful sites that cover both the basics and the more esoteric aspects of Markdown.

Firstly (for what it is worth), the official GitHub specification for GitHub flavoured markdown:

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡-->https://github.github.com/gfm/

This is the official specification for what is supported by GFM, it is to a large extent impenetrable and is difficult to understand. 

<a href="https://github.github.com/gfm/#html-blocks">Section&nbsp;4.6</a> for example, discusses the use of the HTML tag `<style>` (<a href="https://github.github.com/gfm/#example-114">example&nbsp;114</a>) and seems to imply it is supported by GFM. Similarly the `<script>` tag is used in <a href="https://github.github.com/gfm/#example-140">example&nbsp;140</a>; both however, are not supported by GFM. Again, the document is confusing — ***I may be missing something***.


As an aside, the GitHub documentation for Wikis itself is actually a repository in it's own right *(it can be useful to see how GitHub do things)*. You can find it here:

&emsp;&emsp;&emsp;<!--- ENTER URL -->https://github.com/github/docs/tree/main/content

Next is a much more useful site:

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡-->https://www.markdownguide.org/

This site is developed by Matt Cone and is a comprehensive list of what Markdown can do. The only slight problem is that is covers various different types of Markdown alternatives (GitHub Flavoured Markdown is only one of many) and the different variations all support different levels of complexity and function; they are all effectively different version of Markdown.

This site was my goto reference for Markdown and the use of HTML within GitHub flavoured markdown.
The following covers the features of Markdown in a concise form, it was written by John Gruber who, it so happens, invented Markdown:

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡-->https://daringfireball.net/projects/markdown/basics

There is one other site listed here that is a bit of an oddball, but I think it may turn out to be quite useful, it’s certainly clever:

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡-->https://pragmaticpineapple.com/adding-custom-html-and-css-to-github-readme/

GitHub Flavoured Markdown supports the use of SVG images. Now it turns out that you can do quite a lot with the SVG format (SVG is really just a container for code that usually renders a graphical image in a vector format). 

SVG supports the use of a `ForeignObject` element and this element can contain HTML and also inline CSS, it is a way around the HTML restrictions imposed by GitHub *(given their obsession with security, I’m surprised they allow it)*.

I haven’t used this yet, I don’t know enough about the SVG content language, but it is intriguing.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 5.2<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">An overview of Markdown

Markdown is a lightweight Markup language *(It’s a bit stupid I know, Markdown, Markup… I blame the Linux people.)*.

Markup languages are things like HTML, they use a lot of tags and a complex grouping of styles and elements to provide a very flexible arrangement for formatting text on web pages.

Markdown is a simpler version of Markup, it uses plain text with certain specific characters that in some way format the text *(i.e. make headings, tables, bold, italic &c.)*. Markdown is not as flexible as markup. Comparing Markdown with HTML, Markdown does not provide the intricate styling available to HTML, but it is much easier to read, understand and use.

Markdown is not a programming language (in the sense that HTML is) and it does not require the same level of understanding (Markup languages like HTML, due to their complex syntax and tags, require more time and effort to understand and to write and modify the content of a page or document).

Markdown is designed to be easy to learn and accessible for beginners, but is also limited in what can be achieved. It is not a replacement for Word processors or HTML.

Markdown was created by [John Gruber](https://en.wikipedia.org/wiki/John_Gruber) in 2004 and is the default mechanism for documenting repositories in GitHub (any file on GitHub that ends with the `.md` extension is a Markdown file). The following sections explain in some detail how Markdown and the GitHub version of Markdown (called *“GitHub Flavoured Markdown”* or GFM) work.

Markdown is not generally application specific; it is designed to be platform independent. In our case though, we are using Markdown because that is what GitHub requires us to do for its Wiki pages *(yes, there are other languages: AcsiiDoc, Creole, MediaWiki &c. but they are not widely used. Everybody uses Markdown)*.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 5.3<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">How Markdown works

Markdown is written in a plain text file with the extension .md. Markdown files are normally created in a text editor (in my case this is Microsoft’s Visual Studio Code or more commonly just VS Code). The following is an extract of the Markdown file for this page:

<table name="f-05-01" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./05-0000/02-images/figm-05-01.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="806" src="./05-0000/02-images/figm-05-01.png" alt="A Markdown file">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 5.1 &mdash; A Markdown file
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

*It may be fair to say that my Markdown files might be considered, er... different. They don't look like everybody else’s. Don't worry, you'll get used to them.

Markdown files are not *“what you see is what you get”* (WYSIWIG) files like Word files, it is encoded plain text.

*So what happens once you have written a Markdown file?* Well, in the case of GitHub Wikis, GitHub uses a Markdown processor (sometimes called a *parser*) which converts the plain text in the .md into HTML. This HTML is then made available via the GitHub website to any web browser, as shown:

<table name="f-05-02" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./05-0000/02-images/figm-05-02.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="786" src="./05-0000/02-images/figm-05-02.png" alt="Markdown process">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 5.2 &mdash; A visual representation of the Markdown process
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

For the purposes of producing a GitHub Wiki, all that is needed is the first part — it is necessary to write the Wiki content. GitHub does the rest.

GitHub helps the writing process (on its website), by allowing the written `.md` file to be previewed. Within VS Code, the extension: [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)  does the same thing.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 5.4<!--      🟥H2🟥--><img width="086" height="1" src="https://psop.uk/wi-s" alt="Spacer">Markdown flavours

Virtually every implementation of Markdown uses a slightly different version, each with its own features and variations. These are referred to as *“flavours”* of Markdown *(I know, the terminology is awful)*.

In the case of GitHub, the only thing we need to know about is GitHub Flavoured Markdown (GFM).

### 5.4.1<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">GitHub Flavoured Markdown (GFM)

There is a common set of rules for basic Markdown, these include adding headings, images, links, emphasis &c. This is called **basic Markdown syntax**.

GitHub needed a bit more than this; they want to include tables, code fragments, flow charts, task lists and links to GitHub elements. These additions are referred to as **GitHub Flavoured Markdown** or **GFM**. 

Finally, there is the extended Markdown syntax, this allows the use of certain HTML tags directly within the Markdown file.

The following sections give full explanations of how each of these things work and the syntax and mechanisms involved.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 5.5<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">HTML and Markdown

The fact the Markdown is rendered into HTML, and the fact that Markdown by itself is lacking in certain areas, probably explains why most Markdown processors allow *certain* elements of HTML to be used directly in the Markdown text.

GitHub is no exception and it supports a wide range of HTML tags and attributes. In most cases, everything that can be done with Markdown can be replicated using HTML tags and attributes.

This guide is not intended to be an instruction manual for HTML (although I do have one here: https://www.practicalseries.com/1001-webdevelopment/index.html), but wherever I give an example of how to do something with Markdown, I also include the HTML equivalent.

In many cases (tables for example), HTML is much easier and more flexible than Markdown.

The PracticalSeries Wikis use HTML a lot, particularly where tables are concerned (see <a href="10-tables">section&nbsp;10</a>).

*It seems to me that using HTML in Markdown is frowned upon; I see the point: Markdown is supposed to be easy to read and adding HTML makes it harder. It’s a fair point; the trouble is HTML is needed to make Markdown do what you want it to do. It isn’t the 1990s anymore and online documentation has come a long way. Markdown needs to be more sophisticated in what it will allow* ${\large\color{#C00000}\text{(changing\ the\ font\ colour\ doesn’t\ seem\ too\ outrageous\ to\ me)}}$ *. Until Markdown is better, people will find ways around the restrictions.*

**GitHub needs to either bite the bullet and embrace HTML or make its version of Markdown better**

${\large\color{#C00000}\text{p.s.\ If\ you\ want\ to\ know\ how\ I\ got\ the\ red\ text\ in\ there,\ see}}$ <a href="14-mathematical-formulae#146abusing-latex">section&nbsp;14.6</a>.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 5.5.1<!--   🟥H3🟥--><img width="079" height="1" src="https://psop.uk/wi-s" alt="Spacer">HTML with GitHub Flavoured Markdown

GitHub tolerates HTML in its Wiki pages *(I think reluctantly)*. It is however, quite strict about what it will allow. It does not, for example *(and much to many people’s annoyance)*, allow the `<style>` tag, it thinks it is dangerous: *“not allowed for security reasons”*. It’s annoying because the style tag give access to a lot of useful things like text alignment. It also means it’s practically impossible to change the font colour.

> [!TIP]<!-- TIP ALERT -->
> *Although GitHub doesn’t allow the style tag or the use of CSS on its Wiki pages, it does allow the use of SVG images. I hadn’t realised before I started this that SVG files can actually contain HTML and CSS code that is executed when the image is loaded. This gives a workaround (albeit a very awkward one) to having CSS on a Wiki page. It is also a glaring hole in GitHub’s security. There are several articles on the subject, this is one: https://pragmaticpineapple.com.*

When GitHub detects HTML tags in a Markdown page, it *“sanitises”* the HTML by stripping out anything it doesn’t like. Effectively there is a white list for tags that GitHub will allow. Similarly, it also removes certain attributes it doesn’t like if it finds them attached to a tag.

In addition, there are some tags and attributes which, while not officially whitelisted by GitHub, work perfectly well. There is a useful page https://github.com/bryanbraun/github-wiki-html-test/wiki that runs through all the main HTML tags and tries them on a GitHub wiki page.

The following tables summarise my findings:

<br><br>
#### <!--       🟥H4🟥--><u>GFM blacklisted HTML tags&emsp;&emsp;&emsp;&emsp;&emsp;</u>

The tags that GitHub specifically does not allow (**BLACKLIST**) are:

<table name="t-05-01" align="center"><tr>
<td valign="top" width="200">
    &lt;audio&gt;<br>
    &lt;font&gt;<br>
    &lt;form&gt;<br>
    &lt;iframe&gt;<br>
</td><td valign="top" width="200">
    &lt;input&gt;<br>
    &lt;noembed&gt;<br>
    &lt;noframes&gt;<br>
    &lt;output&gt;<br>
</td><td valign="top" width="200">
    &lt;plaintext&gt;<br>
    &lt;script&gt;<br>
    &lt;select&gt;<br>
    &lt;style&gt;<br>
</td><td valign="top" width="200">
    &lt;textarea&gt;<br>
    &lt;title&gt;<br>
    &lt;video&gt;<br>
    &lt;xmp&gt;<br>
</td>
</tr>
<!-- CAPTION -->   <tr>
<!-- LIST WIDTH -->  <th align="left" colspan="4""><sup>
<!-- CAPTION TEXT -->Table 5.1 &mdash; GitHub Markdown BLACKLISTED HTML tags
                     </sup></th></tr>
</table>                             <!-- TABLE END  🔼🔼(BLANK LINE BELOW) -->

<br><br>
#### <!--       🟥H4🟥--><u>GFM whitelisted HTML tags&emsp;&emsp;&emsp;&emsp;&emsp;</u>

The tags that GitHub specifically supports (**WHITELIST**) are (by tag type):

<table name="t-05-02" align="center">
<tr><th valign="top">Anchor:</th><td valign="top">&lt;a&gt;</td></tr>
<tr><th valign="top">Breaks:</th><td valign="top">&lt;br&gt;&ensp;&lt;hr&gt;</td></tr>
<tr><th valign="top">Headings:</th><td valign="top">&lt;h1&gt;&ensp;&lt;h2&gt;&ensp;&lt;h3&gt;&ensp;&lt;h4&gt;&ensp;&lt;h5&gt;&ensp;&lt;h6&gt;</td></tr>
<tr><th valign="top">Images:</td><td valign="top">&lt;img&gt;</td></tr>
<tr><th valign="top">Lists:</th><td valign="top">&lt;ol&gt;&ensp;&lt;ul&gt;&ensp;&lt;li&gt;&ensp;&lt;dl&gt;&ensp;&lt;dt&gt;&ensp;&lt;dd&gt;</td></tr>
<tr><th valign="top">Tables:</th><td valign="top">&lt;table&gt;&ensp;&lt;thead&gt;&ensp;&lt;tbody&gt;&ensp;&lt;tfoot&gt;&ensp;&lt;tr&gt;&ensp;&lt;td&gt;&ensp;&lt;th&gt;</td></tr>
<tr><th valign="top">Text (block):</th><td valign="top">&lt;p&gt;&ensp;&lt;div&gt;&ensp;&lt;blockquote&gt;&ensp;&lt;details&gt;&ensp;&lt;summary&gt;&ensp;&lt;pre&gt;</td></tr>
<tr><th valign="top">Text (inline):</th><td valign="top">&lt;b&gt;&ensp;&lt;i&gt;&ensp;&lt;strong&gt;&ensp;&lt;em&gt;&ensp;&lt;code&gt;&ensp;&lt;ins&gt;&ensp;&lt;u&gt;&ensp;&lt;del&gt;&ensp;&lt;s&gt;&ensp;&lt;sup&gt;&ensp;&lt;sub&gt;&ensp;&lt;samp&gt;&ensp;&lt;q&gt;&ensp;&lt;var&gt;</td></tr>
<!-- CAPTION -->   <tr>
<!-- LIST WIDTH -->  <th align="left" colspan="2""><sup>
<!-- CAPTION TEXT -->Table 5.2 &mdash; GitHub Markdown WHITELISTED HTML tags
                     </sup></th></tr>
</table>                             <!-- TABLE END  🔼🔼(BLANK LINE BELOW) -->

<br><br>
#### <!--       🟥H4🟥--><u>GFM HTML tags &mdash; the grey area&emsp;&emsp;&emsp;&emsp;&emsp;</u>

Tags that are not in either the blacklist or the whitelist are a grey area. Things like `<section>` work, things like `<option>` don't.

A rough rule of thumb is that harmless or informative static tags like `<section>` and `<figure>` work, tags that have some form of live data or have an interaction or excesive influence like `<time>` and `<option>` do not work.

<br><br>
#### <!--       🟥H4🟥--><u>GFM whitelisted HTML attributes&emsp;&emsp;&emsp;&emsp;&emsp;</u>

In terms of HTML attributes, the following are WHITELISTED:

<table name="t-05-03" align="center"><tr>
    <td valign="top" width="200">
        abbr<br>
        accept<br>
        accept-charset<br>
        accesskey<br>
        action<br>
        align<br>
        alt<br>
        axis<br>
        border<br>
        cellpadding<br>
        cellspacing<br>
        char<br>
        charoff<br>
        charset<br>
        checked<br>
        cite<br>
        clear<br>
        cols<br>
    </td><td valign="top" width="200">
        colspan<br>
        color<br>
        compact<br>
        coords<br>
        datetime<br>
        dir<br>
        disabled<br>
        enctype<br>
        for<br>
        frame<br>
        headers<br>
        height<br>
        href<br>
        hreflang<br>
        hspace<br>
        ismap<br>
        itemprop<br>
        itemscope<br>
    </td><td valign="top" width="200">
        itemtype<br>
        label<br>
        lang<br>
        longdesc<br>
        maxlength<br>
        media<br>
        method<br>
        multiple<br>
        name<br>
        nohref<br>
        noshade<br>
        nowrap<br>
        prompt<br>
        readonly<br>
        rel<br>
        rev<br>
        rows<br>
        rowspan<br>
    </td><td valign="top" width="200">
        rules<br>
        scope<br>
        selected<br>
        shape<br>
        size<br>
        span<br>
        src<br>
        start<br>
        summary<br>
        tabindex<br>
        target<br>
        title<br>
        type<br>
        usemap<br>
        valign<br>
        value<br>
        vspace<br>
        width<br>
    </td>
<!-- CAPTION -->   <tr>
<!-- LIST WIDTH -->  <th align="left" colspan="4""><sup>
<!-- CAPTION TEXT -->Table 5.3 &mdash; GitHub Markdown WHITELISTED HTML attributes
                     </sup></th></tr>
</table>                             <!-- TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 5.5.2<!--   🟥H3🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">PracticalSeries and Markdown

I haven’t invented my own Markdown *“flavour”*, but I have discovered various workarounds and techniques that give consistency and a visual style to the PracticalSeries Wiki pages, things like the link to the top of the page that appears at the end of each section:

<p align="center"><a href="#idtop"><strong>⬆ Top</strong></a><!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) --></p>
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

It explains things like the collapsible content tables in the sidebar, badges and buttons, navigation bars a consistent approach to images, tables and captions &c.

I cover all of these *“conventions”* in <a href="16-practicalseries-wiki-conventions">section&nbsp;16</a>.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 5.6<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Markdown difference between files

Surprisingly, there are difference between Markdown files used in a GitHub Wiki and that used in repository Markdown files (such as `README.md`).

I don’t really have an explanation why this should be the case; to my mind, I would have thought they used the same Markdown engine.

Anyway, here are the differences I’ve found

<table name="l-05-01" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW     --><tr><td valign="top">&#x2776;<!-- 1  --></td>
<td align="left"><!-- TEXT -->Footnotes, these work in repositories, but not in Wiki markdown, see <a href="12-Contents,-collapsible-content-and-footnotes#126footnotes">section&nbsp;12.6</a></td></tr>
<!-- LIST ROW     --><tr><td valign="top">&#x2777;<!-- 2  --></td>
<td align="left"><!-- TEXT -->Repository Markdown does not support the <code>&lt;u&gt;</code> tag for underlining text (you have to use the <code>&lt;ins&gt;</code> tag instead) see <a href="06.07-basic-markdown-and-text-formatting#67emphasis-with-underlining">section&nbsp;6.7</a></td></tr>
<!-- LIST ROW     --><tr><td valign="top">&#x2778;<!-- 2  --></td>
<td align="left"><!-- TEXT -->HTML in GitHub Markdown does not support the <code>&numsp;</code>, <code>&emsp13;</code>, <code>&emsp14;</code>, <code>&puncsp;</code> or <code>&hairsp;</code> <em>(and other)</em> escape sequences. Repostitory HTML has no problems <a href="07-special-characters-and-escaping-characters#721escape-sequence-restrictions-in-github-html">section&nbsp;7.2.1</a></td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="700"><sup>
<!-- CAPTION TEXT -->List 5.1 &mdash; List of Markdown differences
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

*That’s it, that’s all I’ve found.*

If I find any others, I’ll add them to this list.
<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->