<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="./ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-1300--ecg-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 

# 13<!--        🟥H1🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Code fragments

GitHub, being a software development platform, needs some mechanism for allowing code to be displayed. Since code languages often include formatting characters within the various syntax arrangements, it is necessary that GitHub displays any code fragments exactly as they are entered without interpreting the various dashes, dots and backslashes as text formatting commands. 

I.e. it displays code fragments in the literal sense: exactly as they are entered. 

GitHub supports such code fragments, these can be displayed at a basic level (simply as code fragments without any coloration), they can also be displayed with syntax highlighting<a name="rn-01" href="#fn-01"><!-- 🟨FOOTNOTE LINK🟨--><sup>💠1</sup></a> (for known languages).

It also allows framed or fenced code highlights (these are large blocks of code that can cover several lines), again these can contain syntax highlighting.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 13.1<!--     🟥H2🟥--><img width="080" height="1" src="https://psop.uk/wi-s" alt="Spacer">Inline code

Inline code fragments can be inserted by surrounding the code with a single backtick character (\`). On a UK keyboard, the backtick is usually the key to the right of the number `1` key (immediately below the `esc` key).

The Markdown and HTML is as follows:

<table name="t-13-01" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr><!-- MARKDOWN HEADER 🔴🔴🔴 -->
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
The print command is `printf` in C.
```
<p> </p></td></tr><!-- MARKDOWN END OF ROW   🔴🔴🔴 -->
<!-- Header row --> <tr><!-- HTML HEADER     🟢🟢🟢 -->
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
The print command is <code>printf</code> in C
```
<p> </p></td></tr><!-- HTML END OF ROW       🟢🟢🟢 -->
<!-- Header row --> <tr><!-- GITHUB HEADER   🔵🔵🔵 -->
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

The print command is `printf` in C.

</td></tr><!-- 🔵GITHUB END (BLANK LINE ABOVE)🔵🔵🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 13.1 &mdash; An inline code fragment
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

The code is displayed in a monospaced font (in this case Consolas) in a grey rounded rectangle `rgb: (240,241,242) #F0F1F2`. The font colour is the same as body text: `rgb: (31,35,40) #1F2328`.

With the HTML, the `<code>` tag carries out the same function as the backtick character in Markdown.

The `<code>` tag is always used for HTML inline code fragments (it does not need the `<pre>` tag discussed in the following section).

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 13.2<!--     🟥H2🟥--><img width="077" height="1" src="https://psop.uk/wi-s" alt="Spacer">Code blocks

There are several ways to display code blocks in Markdown, some are more precise than others.

The simplest mechanism to display a block of code is to indent each line be at least four spaces *(depending on the text editor, this is sometimes done with the tab key)*:

<table name="t-13-02" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr><!-- MARKDOWN HEADER 🔴🔴🔴 -->
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
    #include <stdio.h>

    int main() {
        printf("Hello World");
        return 0;
    }
```
<p> </p></td></tr><!-- MARKDOWN END OF ROW   🔴🔴🔴 -->
<!-- Header row --> <tr><!-- HTML HEADER     🟢🟢🟢 -->
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<pre><code>#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
</code></pre>
```
<p> </p></td></tr><!-- HTML END OF ROW       🟢🟢🟢 -->
<!-- Header row --> <tr><!-- GITHUB HEADER   🔵🔵🔵 -->
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

    #include <stdio.h>

    int main() {
        printf("Hello World");
        return 0;
    }

</td></tr><!-- 🔵GITHUB END (BLANK LINE ABOVE)🔵🔵🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 13.2 &mdash; A simple code fragment
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

The code is again displayed in a monospaced font (in this case Consolas) in a grey rounded rectangle (see the previous section for colour details). 

The clipboard icon (highlighted) allows the code to be copied verbatim for pasting into some other editor.

With the HTML, the `<pre><code>` at the start informs the browser that what follows is to be rendered in a monospaced font and that spaces must be displayed (the `<pre>` tag does this) and that the content is a fragment of computer code (the `<code>` tag).

Technically, the `<code>` tag is for information only, the `<pre>` tag does everything we need; but syntactically `<pre><code>` is the correct format.

The `<pre><code>` is on the same line as the first line of the code, this stops additional line-breaks being inserted before the code fragment.

> [!IMPORTANT]<!-- IMPORTANT ALERT -->
> **GitHub will add a scrollbar to a code fragment if a line is too long to be displayed, there is nothing you can do about this *(no way to force it to wrap long lines)*, it is the way GitHub does it.**

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 13.2.1<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Preferred mechanism for code blocks

Although indenting code by four spaces forces GitHub to interpret the text as code, it is not the preferred mechanism for doing so. Using tabs and spaces can be a bit hit and miss.

The preferred mechanism for Markdown code fragments is to surround the block with three backtick characters (` ``` `). This is unambiguous and clearly marks the text as a code fragment. This is the preferred format for the previous example:

<table name="t-13-03" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

````md
```
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```
````
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

```
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 13.3 &mdash; Preferred Markdown for a code fragment
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

With this mechanism leading spaces are not required.

**Each set of backticks must be on its own blank line.**

> [!NOTE]<!-- NOTE ALERT -->
> *Using three backtick characters* (` ``` `) *works just like the single backtick* (<code>`</code>) *when used with inline code fragments.*

To escape the triple backticks discussed in the previous section, wrap then in quadruple backticks:

<table name="t-13-04" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

`````md
````
```
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```
````
`````
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

````
```
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```
````

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 13.4 &mdash; Escaping three backticks
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->


*How to escape four backticks? You guessed it, use five — **now it just gets silly.***

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 13.3<!--     🟥H2🟥--><img width="077" height="1" src="https://psop.uk/wi-s" alt="Spacer">Syntax highlighting

Syntax highlighting is used to colour certain aspects of the programming language to make the text more readable and easier to understand.

Syntax highlighting is only possible with GitHub Markdown (there is no HTML equivalent that works with GitHub).

The above code fragment looks like this with GitHub syntax highlighting (it is written in the C programming language):

<table name="t-13-05" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

````md
```c
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```
````

<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->


```c
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```
</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 13.5 &mdash; Syntax highlighting in Markdown
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

To activate syntax highlighting, simply follow the first three backticks with the lowercase code for the language being used, the  `c` in this case:

If the code were JavaScript, the three backticks would be followed by `java` for example (` ```java `).

There is no space between the backticks and the language code.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 13.3.1<!--  🟥H3🟥--><img width="071" height="1" src="https://psop.uk/wi-s" alt="Spacer">Supported languages

GitHub supports syntax highlighting for many programming languages, the following lists them all and the language code that must follow the three backticks:

| Language | Code | Language | Code | Language | Code |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <sup>1C</sup> | <sup>`1c`</sup> | <sup>Grammatical Framework</sup> | <sup>`gf`</sup> | <sup>PowerShell</sup> | <sup>`powershell, ps, ps1`</sup> |
| <sup>4D</sup> | <sup>`4d`</sup> | <sup>Golo</sup> | <sup>`golo, gololang`</sup> | <sup>Processing</sup> | <sup>`processing`</sup> |
| <sup>ABAP</sup> | <sup>`sap-abap, abap`</sup> | <sup>Gradle</sup> | <sup>`gradle`</sup> | <sup>Prolog</sup> | <sup>`prolog`</sup> |
| <sup>ABNF</sup> | <sup>`abnf`</sup> | <sup>GraphQL</sup> | <sup>`graphql, gql`</sup> | <sup>Properties</sup> | <sup>`properties`</sup> |
| <sup>Access logs</sup> | <sup>`accesslog`</sup> | <sup>Groovy</sup> | <sup>`groovy`</sup> | <sup>Protocol Buffers</sup> | <sup>`proto, protobuf`</sup> |
| <sup>Ada</sup> | <sup>`ada`</sup> | <sup>GSQL</sup> | <sup>`gsql`</sup> | <sup>Puppet</sup> | <sup>`puppet, pp`</sup> |
| <sup>Apex</sup> | <sup>`apex`</sup> | <sup>HTML, XML</sup> | <sup>`xml, html, xhtml, rss, a`</sup> | <sup>Python</sup> | <sup>`python, py, gyp`</sup> |
| <sup>Arduino</sup> | <sup>`arduino, ino`</sup> | <sup>HTTP</sup> | <sup>`http, https`</sup> | <sup>Python profiler results</sup> | <sup>`profile`</sup> |
| <sup>ARM assembler</sup> | <sup>`armasm, arm`</sup> | <sup>Haml</sup> | <sup>`haml`</sup> | <sup>Python REPL</sup> | <sup>`python-repl, pycon`</sup> |
| <sup>AVR assembler</sup> | <sup>`avrasm`</sup> | <sup>Handlebars</sup> | <sup>`handlebars, hbs, html.hb`</sup> | <sup>Q#</sup> | <sup>`qsharp`</sup> |
| <sup>ActionScript</sup> | <sup>`actionscript, as`</sup> | <sup>Haskell</sup> | <sup>`haskell, hs`</sup> | <sup>Q</sup> | <sup>`k, kdb`</sup> |
| <sup>Alan IF</sup> | <sup>`alan, i`</sup> | <sup>Haxe</sup> | <sup>`haxe, hx`</sup> | <sup>QML</sup> | <sup>`qml`</sup> |
| <sup>Alan</sup> | <sup>`ln`</sup> | <sup>High-level shader language</sup> | <sup>`hlsl`</sup> | <sup>R</sup> | <sup>`r`</sup> |
| <sup>AngelScript</sup> | <sup>`angelscript, asc`</sup> | <sup>Hy</sup> | <sup>`hy, hylang`</sup> | <sup>Raku</sup> | <sup>`raku, perl6, p6, pm6, ra`</sup> |
| <sup>Apache</sup> | <sup>`apache, apacheconf`</sup> | <sup>Ini, TOML</sup> | <sup>`ini, toml`</sup> | <sup>RakuDoc</sup> | <sup>`pod6, rakudoc`</sup> |
| <sup>AppleScript</sup> | <sup>`applescript, osascript`</sup> | <sup>Inform7</sup> | <sup>`inform7, i7`</sup> | <sup>RakuQuoting</sup> | <sup>`rakuquoting`</sup> |
| <sup>Arcade</sup> | <sup>`arcade`</sup> | <sup>IRPF90</sup> | <sup>`irpf90`</sup> | <sup>RakuRegexe</sup> | <sup>`rakuregexe`</sup> |
| <sup>AsciiDoc</sup> | <sup>`asciidoc, adoc`</sup> | <sup>Iptables</sup> | <sup>`iptables`</sup> | <sup>Razor CSHTML</sup> | <sup>`cshtml, razor, razor-csh`</sup> |
| <sup>AspectJ</sup> | <sup>`aspectj`</sup> | <sup>JSON</sup> | <sup>`json, jsonc`</sup> | <sup>ReasonML</sup> | <sup>`reasonml, re`</sup> |
| <sup>AutoHotkey</sup> | <sup>`autohotkey`</sup> | <sup>JSONata</sup> | <sup>`jsonata`</sup> | <sup>Rebol & Red</sup> | <sup>`redbol, rebol, red, red-`</sup> |
| <sup>AutoIt</sup> | <sup>`autoit`</sup> | <sup>Java</sup> | <sup>`java, jsp`</sup> | <sup>RenderMan RIB</sup> | <sup>`rib`</sup> |
| <sup>Awk</sup> | <sup>`awk, mawk, nawk, gawk`</sup> | <sup>JavaScript</sup> | <sup>`javascript, js, jsx`</sup> | <sup>RenderMan RSL</sup> | <sup>`rsl`</sup> |
| <sup>Ballerina</sup> | <sup>`ballerina, bal`</sup> | <sup>Jolie</sup> | <sup>`jolie, iol, ol`</sup> | <sup>ReScript</sup> | <sup>`rescript, res`</sup> |
| <sup>Bash</sup> | <sup>`bash, sh, zsh`</sup> | <sup>Julia</sup> | <sup>`julia, jl`</sup> | <sup>RiScript</sup> | <sup>`risc, riscript`</sup> |
| <sup>Basic</sup> | <sup>`basic`</sup> | <sup>Julia REPL</sup> | <sup>`julia-repl`</sup> | <sup>RISC-V Assembly</sup> | <sup>`riscv, riscvasm`</sup> |
| <sup>BBCode</sup> | <sup>`bbcode`</sup> | <sup>Kotlin</sup> | <sup>`kotlin, kt`</sup> | <sup>Roboconf</sup> | <sup>`graph, instances`</sup> |
| <sup>Blade (Laravel)</sup> | <sup>`blade`</sup> | <sup>Lang</sup> | <sup>`lang`</sup> | <sup>Robot Framework</sup> | <sup>`robot, rf`</sup> |
| <sup>BNF</sup> | <sup>`bnf`</sup> | <sup>LaTeX</sup> | <sup>`tex`</sup> | <sup>RPM spec files</sup> | <sup>`rpm-specfile, rpm, spec,`</sup> |
| <sup>BQN</sup> | <sup>`bqn`</sup> | <sup>Leaf</sup> | <sup>`leaf`</sup> | <sup>Ruby</sup> | <sup>`ruby, rb, gemspec, podsp`</sup> |
| <sup>Brainfuck</sup> | <sup>`brainfuck, bf`</sup> | <sup>Lean</sup> | <sup>`lean`</sup> | <sup>Rust</sup> | <sup>`rust, rs`</sup> |
| <sup>C#</sup> | <sup>`csharp, cs`</sup> | <sup>Lasso</sup> | <sup>`lasso, ls, lassoscript`</sup> | <sup>RVT Script</sup> | <sup>`rvt, rvt-script`</sup> |
| <sup>C</sup> | <sup>`c, h`</sup> | <sup>Less</sup> | <sup>`less`</sup> | <sup>SAS</sup> | <sup>`SAS, sas`</sup> |
| <sup>C++</sup> | <sup>`cpp, hpp, cc, hh, c++, h`</sup> | <sup>LDIF</sup> | <sup>`ldif`</sup> | <sup>SCSS</sup> | <sup>`scss`</sup> |
| <sup>C/AL</sup> | <sup>`cal`</sup> | <sup>Liquid</sup> | <sup>`liquid`</sup> | <sup>SQL</sup> | <sup>`sql`</sup> |
| <sup>C3</sup> | <sup>`c3`</sup> | <sup>Lisp</sup> | <sup>`lisp`</sup> | <sup>STEP Part 21</sup> | <sup>`p21, step, stp`</sup> |
| <sup>Cache Object Script</sup> | <sup>`cos, cls`</sup> | <sup>LiveCode Server</sup> | <sup>`livecodeserver`</sup> | <sup>Scala</sup> | <sup>`scala`</sup> |
| <sup>Candid</sup> | <sup>`candid, did`</sup> | <sup>LiveScript</sup> | <sup>`livescript, ls`</sup> | <sup>Scheme</sup> | <sup>`scheme`</sup> |
| <sup>CMake</sup> | <sup>`cmake, cmake.in`</sup> | <sup>LookML</sup> | <sup>`lookml`</sup> | <sup>Scilab</sup> | <sup>`scilab, sci`</sup> |
| <sup>COBOL</sup> | <sup>`cobol, standard-cobol`</sup> | <sup>Lua</sup> | <sup>`lua, pluto`</sup> | <sup>SFZ</sup> | <sup>`sfz`</sup> |
| <sup>CODEOWNERS</sup> | <sup>`codeowners`</sup> | <sup>Luau</sup> | <sup>`luau`</sup> | <sup>Shape Expressions</sup> | <sup>`shexc`</sup> |
| <sup>Coq</sup> | <sup>`coq`</sup> | <sup>Macaulay2</sup> | <sup>`macaulay2`</sup> | <sup>Shell</sup> | <sup>`shell, console`</sup> |
| <sup>CSP</sup> | <sup>`csp`</sup> | <sup>Makefile</sup> | <sup>`makefile, mk, mak, make`</sup> | <sup>Smali</sup> | <sup>`smali`</sup> |
| <sup>CSS</sup> | <sup>`css`</sup> | <sup>Markdown</sup> | <sup>`markdown, md, mkdown, mk`</sup> | <sup>Smalltalk</sup> | <sup>`smalltalk, st`</sup> |
| <sup>Cap’n Proto</sup> | <sup>`capnproto, capnp`</sup> | <sup>Mathematica</sup> | <sup>`mathematica, mma, wl`</sup> | <sup>SML</sup> | <sup>`sml, ml`</sup> |
| <sup>Chaos</sup> | <sup>`chaos, kaos`</sup> | <sup>Matl+C86:D134ab</sup> | <sup>`matlab`</sup> | <sup>Solidity</sup> | <sup>`solidity, sol`</sup> |
| <sup>Chapel</sup> | <sup>`chapel, chpl`</sup> | <sup>Maxima</sup> | <sup>`maxima`</sup> | <sup>Splunk SPL</sup> | <sup>`spl`</sup> |
| <sup>Cisco CLI</sup> | <sup>`cisco`</sup> | <sup>Maya Embedded Language</sup> | <sup>`mel`</sup> | <sup>Stan</sup> | <sup>`stan, stanfuncs`</sup> |
| <sup>Clojure</sup> | <sup>`clojure, clj`</sup> | <sup>Mercury</sup> | <sup>`mercury`</sup> | <sup>Stata</sup> | <sup>`stata`</sup> |
| <sup>CoffeeScript</sup> | <sup>`coffeescript, coffee, cs`</sup> | <sup>MetaPost</sup> | <sup>`metapost`</sup> | <sup>Structured Text</sup> | <sup>`iecst, scl, stl, structu`</sup> |
| <sup>CpcdosC+</sup> | <sup>`cpc`</sup> | <sup>MIPS Assembler</sup> | <sup>`mips, mipsasm`</sup> | <sup>Stylus</sup> | <sup>`stylus, styl`</sup> |
| <sup>Crmsh</sup> | <sup>`crmsh, crm, pcmk`</sup> | <sup>Mint</sup> | <sup>`mint`</sup> | <sup>SubUnit</sup> | <sup>`subunit`</sup> |
| <sup>Crystal</sup> | <sup>`crystal, cr`</sup> | <sup>Mirth</sup> | <sup>`mirth`</sup> | <sup>Supercollider</sup> | <sup>`supercollider, sc`</sup> |
| <sup>cURL</sup> | <sup>`curl`</sup> | <sup>mIRC Scripting Language</sup> | <sup>`mirc, mrc`</sup> | <sup>Svelte</sup> | <sup>`svelte`</sup> |
| <sup>Cypher (Neo4j)</sup> | <sup>`cypher`</sup> | <sup>Mizar</sup> | <sup>`mizar`</sup> | <sup>Swift</sup> | <sup>`swift`</sup> |
| <sup>D</sup> | <sup>`d`</sup> | <sup>MKB</sup> | <sup>`mkb`</sup> | <sup>Tcl</sup> | <sup>`tcl, tk`</sup> |
| <sup>Dafny</sup> | <sup>`dafny`</sup> | <sup>MLIR</sup> | <sup>`mlir`</sup> | <sup>Terraform (HCL)</sup> | <sup>`terraform, tf, hcl`</sup> |
| <sup>Dart</sup> | <sup>`dart`</sup> | <sup>Mojolicious</sup> | <sup>`mojolicious`</sup> | <sup>Test Anything Protocol</sup> | <sup>`tap`</sup> |
| <sup>Delphi</sup> | <sup>`dpr, dfm, pas, pascal`</sup> | <sup>Monkey</sup> | <sup>`monkey`</sup> | <sup>Thrift</sup> | <sup>`thrift`</sup> |
| <sup>Diff</sup> | <sup>`diff, patch`</sup> | <sup>Moonscript</sup> | <sup>`moonscript, moon`</sup> | <sup>Toit</sup> | <sup>`toit`</sup> |
| <sup>Django</sup> | <sup>`django, jinja`</sup> | <sup>Motoko</sup> | <sup>`motoko, mo`</sup> | <sup>TP</sup> | <sup>`tp`</sup> |
| <sup>DNS Zone file</sup> | <sup>`dns, zone, bind`</sup> | <sup>N1QL</sup> | <sup>`n1ql`</sup> | <sup>Transact-SQL</sup> | <sup>`tsql`</sup> |
| <sup>Dockerfile</sup> | <sup>`dockerfile, docker`</sup> | <sup>NSIS</sup> | <sup>`nsis`</sup> | <sup>TTCN-3</sup> | <sup>`ttcn, ttcnpp, ttcn3`</sup> |
| <sup>DOS</sup> | <sup>`dos, bat, cmd`</sup> | <sup>Never</sup> | <sup>`never`</sup> | <sup>Twig</sup> | <sup>`twig, craftcms`</sup> |
| <sup>dsconfig</sup> | <sup>`dsconfig`</sup> | <sup>Nginx</sup> | <sup>`nginx, nginxconf`</sup> | <sup>TypeScript</sup> | <sup>`typescript, ts, tsx, mts`</sup> |
| <sup>DTS (Device Tree)</sup> | <sup>`dts`</sup> | <sup>Nim</sup> | <sup>`nim, nimrod`</sup> | <sup>Unicorn Rails log</sup> | <sup>`unicorn-rails-log`</sup> |
| <sup>Dust</sup> | <sup>`dust, dst`</sup> | <sup>Nix</sup> | <sup>`nix`</sup> | <sup>Unison</sup> | <sup>`unison, u`</sup> |
| <sup>Dylan</sup> | <sup>`dylan`</sup> | <sup>Oak</sup> | <sup>`oak`</sup> | <sup>VB.Net</sup> | <sup>`vbnet, vb`</sup> |
| <sup>EBNF</sup> | <sup>`ebnf`</sup> | <sup>Object Constraint Language</sup> | <sup>`ocl`</sup> | <sup>VBA</sup> | <sup>`vba`</sup> |
| <sup>Elixir</sup> | <sup>`elixir`</sup> | <sup>OCaml</sup> | <sup>`ocaml, ml`</sup> | <sup>VBScript</sup> | <sup>`vbscript, vbs`</sup> |
| <sup>Elm</sup> | <sup>`elm`</sup> | <sup>Objective C</sup> | <sup>`objectivec, objc, ob`</sup> | <sup>VHDL</sup> | <sup>`vhdl`</sup> |
| <sup>Erlang</sup> | <sup>`erlang, erl`</sup> | <sup>Odin</sup> | <sup>`odin`</sup> | <sup>Vala</sup> | <sup>`vala`</sup> |
| <sup>Excel</sup> | <sup>`excel, xls, xlsx`</sup> | <sup>OpenGL Shading Language</sup> | <sup>`glsl`</sup> | <sup>Verilog</sup> | <sup>`verilog, v`</sup> |
| <sup>Extempore</sup> | <sup>`extempore, xtlang, xtm`</sup> | <sup>OpenSCAD</sup> | <sup>`openscad, scad`</sup> | <sup>Vim Script</sup> | <sup>`vim`</sup> |
| <sup>F#</sup> | <sup>`fsharp, fs, fsx, fsi, fs`</sup> | <sup>Oracle Rules Language</sup> | <sup>`ruleslanguage`</sup> | <sup>WGSL</sup> | <sup>`wgsl`</sup> |
| <sup>FIX</sup> | <sup>`fix`</sup> | <sup>Oxygene</sup> | <sup>`oxygene`</sup> | <sup>X#</sup> | <sup>`xsharp, xs, prg`</sup> |
| <sup>Flix</sup> | <sup>`flix`</sup> | <sup>PF</sup> | <sup>`pf, pf.conf`</sup> | <sup>X++</sup> | <sup>`axapta, x++`</sup> |
| <sup>Fortran</sup> | <sup>`fortran, f90, f95`</sup> | <sup>PHP</sup> | <sup>`php`</sup> | <sup>x86 Assembly</sup> | <sup>`x86asm`</sup> |
| <sup>FunC</sup> | <sup>`func`</sup> | <sup>Papyrus</sup> | <sup>`papyrus, psc`</sup> | <sup>x86 Assembly (AT&T)</sup> | <sup>`x86asmatt`</sup> |
| <sup>G-Code</sup> | <sup>`gcode, nc`</sup> | <sup>Parser3</sup> | <sup>`parser3`</sup> | <sup>XL</sup> | <sup>`xl, tao`</sup> |
| <sup>Gams</sup> | <sup>`gams, gms`</sup> | <sup>Perl</sup> | <sup>`perl, pl, pm`</sup> | <sup>XQuery</sup> | <sup>`xquery, xpath, xq, xqm`</sup> |
| <sup>GAUSS</sup> | <sup>`gauss, gss`</sup> | <sup>Phix</sup> | <sup>`phix`</sup> | <sup>YAML</sup> | <sup>`yml, yaml`</sup> |
| <sup>GDScript</sup> | <sup>`godot, gdscript`</sup> | <sup>Pine Script</sup> | <sup>`pine, pinescript`</sup> | <sup>ZenScript</sup> | <sup>`zenscript, zs`</sup> |
| <sup>Gherkin</sup> | <sup>`gherkin`</sup> | <sup>Plaintext</sup> | <sup>`plaintext, txt, text`</sup> | <sup>Zephir</sup> | <sup>`zephir, zep`</sup> |
| <sup>Glimmer and EmberJS</sup> | <sup>`hbs, glimmer, html.hbs,`</sup> | <sup>Pony</sup> | <sup>`pony`</sup> | <sup>Zig</sup> | <sup>`zig`</sup> |
| <sup>GN for Ninja</sup> | <sup>`gn, gni`</sup> | <sup>PostgreSQL & PL/pgSQL</sup> | <sup>`pgsql, postgre`</sup> | <sup></sup> | <sup></sup> |
| <sup>Go</sup> | <sup>`go, golang`</sup> | <sup>PowerOn</sup> | <sup>`poweron, po`</sup> | <sup></sup> | <sup></sup> |

*Yeah, I’ve no idea what most of them are either. Especially* `Brainfuck`.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 13.4<!--     🟥H2🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">HTML code fragments

Things can get a bit confusing when using HTML to display an HTML code fragment.

Let’s say for example that you wanted to use HTML to display the following as a code fragment:

```html
<table align="center">
<tr><td align="center"><img src="./01-0000/02-images/figm-01-01.png"></td></tr>
</table>
```

You would think we would simply wrap it in the `<pre><code>` tags as follows:


```html
<pre><code><table align="center">
<tr><td align="center"><img src="./01-0000/02-images/figm-01-01.png"></td></tr>
</table></code></pre>
```

What this give however is this:

<pre><code><table align="center">
<tr><td align="center"><img src="./01-0000/02-images/figm-01-01.png"></td></tr>
</table></code></pre>

It has got the grey background of a code fragment, but the HTML starting with `<table>` has simply rendered as HTML, we don’t see the code, but the code has been executed and displays the image.

> [!IMPORTANT]<!-- IMPORTANT ALERT -->
> **This doesn’t happen if we use Markdown with three backticks.**

The solution to this problem is that we must replace all the greater than and less than symbols with their HTML escape codes (these were first discussed in <a href="07-special-characters-and-escaping-characters#712html-escape-sequences">section&nbsp;7.1.2</a>), the table of which is reproduced below:


<table name="t-13-07" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Data row -->       <tr>
                            <td align="left"><p>Less than 	</p></td>
                            <td align="left"><p>&lt;</p></td>
                            <td align="left"><p>Replacement code:</p></td>
                            <td align="left"><p><code>&amp;lt;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="left"><p>Greater than </p></td>
                            <td align="left"><p>&gt;</p></td>
                            <td align="left"><p>Replacement code:</p></td>
                            <td align="left"><p><code>&amp;gt;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="left"><p>Ampersand </p></td>
                            <td align="left"><p>&amp;</p></td>
                            <td align="left"><p>Replacement code:</p></td>
                            <td align="left"><p><code>&amp;amp;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="left"><p>Double quotation mark</p></td>
                            <td align="left"><p>&quot;</p></td>
                            <td align="left"><p>Replacement code:</p></td>
                            <td align="left"><p><code>&amp;quot;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="left"><p>Single quotation mark</p></td>
                            <td align="left"><p>&apos;</p></td>
                            <td align="left"><p>Replacement code:</p></td>
                            <td align="left"><p><code>&amp;apos;</code></p></td>
                        </tr>
<!-- CAPTION -->    <tr><th colspan="4" align="left"><sup>
<!-- CAPTION TEXT -->Table 13.7 &mdash; HTML reserved characters and escape sequences 
                     </sup></th></tr>
</table>                             <!-- TABLE END  🔼🔼(BLANK LINE BELOW) -->

To make the HTML code fragment work, it must be re-written as:

<table name="t-13-08" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>HTML and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr><th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th></tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<pre><code>&lt;table align="center"&gt;
&lt;tr&gt;&lt;td align="center"&gt;&lt;img src="./01-0000/02-images/figm-01-01.png"&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;/table&gt;</code></pre>

```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr><th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th></tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<pre><code>&lt;table align="center"&gt;
&lt;tr&gt;&lt;td align="center"&gt;&lt;img src="./01-0000/02-images/figm-01-01.png"&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;/table&gt;</code></pre>

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 13.8 &mdash; Corrected HTML code fragment using HTML
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 13.4.1<!--  🟥H3🟥--><img width="070" height="1" src="https://psop.uk/wi-s" alt="Spacer">Converting HTML to code fragments

Converting all the reserved characters in a HTML code fragment into escape codes, is, to put it bluntly, *a pain in the arse*.

It’s something I’ve had to do a lot when producing the PracticalSeries website. In the end I used a Word document with embedded macros to do the conversion, it is available here for you to use:

&emsp;&emsp;&emsp;<!---🟡ENTER URL🟡--><a href="./13-0000/04-data/ps-html-converter.docm">ps-html-converter.docm</a>

To use this document: download the document, open it and enable the macros<a name="rn-02" href="#fn-02"><!-- 🟨FOOTNOTE LINK🟨--><sup>💠2</sup></a> (Word will try to stop you, especially since you downloaded it from the internet).

Copy the HTML you want to convert onto a blank page in the document (the one starting paste your stuff here will do), in this example I’m copying the HTML table example from the previous section, it looks like this in the document

<table name="f-13-01" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./13-0000/02-images/figm-13-01.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="850" src="./13-0000/02-images/figm-13-01.png" alt="HTML conversion">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 13.1 &mdash; HTML code copied into the conversion document
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

Now select the code to be converted:

<table name="f-13-02" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./13-0000/02-images/figm-13-02.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="850" src="./13-0000/02-images/figm-13-02.png" alt="HTML conversion">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 13.2 &mdash; Select the code fragment
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

Now press ctrl+alt+R to run the macro to convert the code. It does this:

<table name="f-13-03" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./13-0000/02-images/figm-13-03.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="850" src="./13-0000/02-images/figm-13-03.png" alt="HTML conversion">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 13.3 &mdash; Converted the code fragment
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

Cut and paste the converted code into the HTML code fragment:

<table name="t-13-09" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>HTML and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr><th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th></tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<pre><code>&lt;table align=&quot;center&quot;&gt;
&lt;tr&gt;&lt;td align=&quot;center&quot;&gt;&lt;img src=&quot;https://github.com/practicalseries/GitHub-Wiki-Design-and-Implementation/wiki/01-0000/02-images/fig-01-01.png&quot;&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;/table&gt;</code></pre>

```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr><th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th></tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

<pre><code>&lt;table align=&quot;center&quot;&gt;
&lt;tr&gt;&lt;td align=&quot;center&quot;&gt;&lt;img src=&quot;https://github.com/practicalseries/GitHub-Wiki-Design-and-Implementation/wiki/01-0000/02-images/fig-01-01.png&quot;&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;/table&gt;</code></pre>


</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 13.9 &mdash; Converted code fragment
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

*Hope this helps.*


**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->

<hr><!-- FOOTNOTE SEPARATOR 🟡🟡🟡🟡🟡 -->
<a name="idfn" href="#idfn">Footnotes:<!-- 🟡FOOTNOTE TITLE🟡 -->&emsp;&emsp;&emsp;&emsp;&emsp;</a>
<br><br><br>

> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-01" href="#rn-01"><sup>💠1</sup></a>&emsp;<!-- FOOTNOTE CONTENT TEXT -->Syntax highlighting is the colouring of various commands, attributes, variables &c. within a code fragment to highlight different components of the code. It is done to make the code more readable.<!--  CONTENT TEXT END --><a href="#rn-01">↩</a><!-- 🟡🟡🟡🟡🟡 FOOTNOTE END -->


> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-02" href="#rn-02"><sup>💠2</sup></a>&emsp;<!-- FOOTNOTE CONTENT TEXT -->To enable macros in Word, select the <u>File tab</u>, <u>options</u>, <u>trust centre</u>, <u>trust centre settings</u> (button on the right), this opens a new window. Select <u>macro settings</u> and click the <u>enable all macros</u> button and click <u>ok</u> to exit.
> 
>That’s the first part, now set the <u>trusted locations</u>, this is still in the <u>trust centre settings</u>, select <u>Trusted locations</u> and select <u>add new location</u>, navigate to wher-ever you have saved the document and select the folder containing it, select <u>include subfolders</u> if required.  
> 
> Now save, close and re-open the document.<!--  CONTENT TEXT END --><a href="#rn-02">↩</a><!-- 🟡🟡🟡🟡🟡 FOOTNOTE END -->









<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->