<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="./ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-0700--eaE-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 

# 7<!--         🟥H1🟥--><img width="101" height="1" src="https://psop.uk/wi-s" alt="Spacer">Special characters and escaping characters

GitHub uses the Segoe UI font *(pronounced seg-o-ee)* as standard across all its Wiki pages (at least it does on Windows based browsers). Segoe is a large font with a very great number of characters all of which can be accessed by using escape codes.

*“Escaping”* a character is a term that applies to special characters that would otherwise be used to format the text in some way *(asterisks for example)*, it allows the character to be displayed as a character rather than being interpreted as a formatting instruction.

This *“escaping”* process takes different forms for different languages (Markdown, HTML &c.), but always results in the true character being rendered.

This escaping process allows the full range of the Segoe UI font characters to be accessed (not just the ones that can be entered from a keyboard). Thing like this:

&emsp;&emsp;&emsp;▛ ▜ ♑ ♞ ♬

There is a spreadsheet with the full Segoe UI character set <a href="https://github.com/practicalseries/GitHub-Wiki-Design-and-Implementation/wiki/C-0000/04-data/segou_full_character_set.xlsx" title="Use ctrl+click to open file in new tab">here</a>:

It’s a big list, there are 40,000 characters in it (not all of which render on GitHub, *but 26,684 of them do)*.

These are also listed in <a href="../C-0000/App%20C%20Segoe%20Character%20Set.md">Appendix&nbsp;C</a> of this Wiki.

## 7.1<!--      🟥H2🟥--><img width="091" height="1" src="https://psop.uk/wi-s" alt="Spacer">Escape characters and character codes

Markdown has a mechanism for displaying characters that would otherwise be use to format text *(asterisks for example)*, this mechanism is called *“escaping the character”*. It is also possible to use a Unicode value to display a specific character (in either decimal or hexadecimal format), plus all the HTML symbol codes (the ones that begin with an ampersand) are also supported.

### 7.1.1<!--   🟥H3🟥--><img width="083" height="1" src="https://psop.uk/wi-s" alt="Spacer">Markdown escape sequences

With Markdown, to display a literal character (i.e. to make the character appear in the text rather than format the text), precede it with a backslash character `\`.

For example if the following Markdown text were used:

<table name="t-07-00a" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
* Without a backslash this is rendered as a list.
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

* Without a backslash this is rendered as a list.

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

<a href="../08-0000/08%20Block%20quotes,%20lists%20and%20alerts.md">Section&nbsp;8</a> explains about lists. The point here is that if we wish to display the asterisk as an asterisk, we need to escape it *(by adding a backslash)*:

<table name="t-07-00b" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->     <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
\* With a backslash it renders as an asterisk.
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left" valign="top"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

\* With a backslash it renders as an asterisk.

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

The following characters can all be *“escaped”* by placing a backslash before the character:

<table name="t-07-01" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row -->     <tr>
                            <th width="100" align="center">Character</th>
                            <th width="400" align="left">Name</th>
                            <th width="150" align="center">Escape symbol</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>\</p></td>
                            <td align="left"><p>Backslash</p></td>
                            <td align="center"><p><code>\\</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>`</p></td>
                            <td align="left"><p>Backtick</p></td>
                            <td align="center"><p><code>\`</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>*</p></td>
                            <td align="left"><p>Asterisk</p></td>
                            <td align="center"><p><code>\*</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>_</p></td>
                            <td align="left"><p>Underscore</p></td>
                            <td align="center"><p><code>\_</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>{&emsp;}</p></td>
                            <td align="left"><p>Braces</p></td>
                            <td align="center"><p><code>\{</code>&emsp;<code>\}</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>[&emsp;]</p></td>
                            <td align="left"><p>Brackets</p></td>
                            <td align="center"><p><code>\[</code>&emsp;<code>\]</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>&lt;&emsp;&gt;</p></td>
                            <td align="left"><p>Angle brackets</p></td>
                            <td align="center"><p><code>\&lt;</code>&emsp;<code>\&gt;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>(&emsp;)</p></td>
                            <td align="left"><p>Parentheses</p></td>
                            <td align="center"><p><code>\(</code>&emsp;<code>\)</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>#</p></td>
                            <td align="left"><p>Hash sign</p></td>
                            <td align="center"><p><code>\#</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>+</p></td>
                            <td align="left"><p>Plus sign</p></td>
                            <td align="center"><p><code>\+</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>-</p></td>
                            <td align="left"><p>Minus sign (hyphen)</p></td>
                            <td align="center"><p><code>\-</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>.</p></td>
                            <td align="left"><p>Full stop</p></td>
                            <td align="center"><p><code>\.</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>!</p></td>
                            <td align="left"><p>Exclamation mark</p></td>
                            <td align="center"><p><code>\!</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>|</p></td>
                            <td align="left"><p>Pipe</p></td>
                            <td align="center"><p><code>\|</code></p></td>
                        </tr>
<!-- CAPTION -->    <tr><th colspan="3" align="left"><sup>
<!-- CAPTION TEXT -->Table 7.1 &mdash; Markdown escapable characters 
                     </sup></th></tr>
</table>                             <!-- TABLE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 7.1.2<!--   🟥H3🟥--><img width="080" height="1" src="https://psop.uk/wi-s" alt="Spacer">HTML escape sequences

Like Markdown, HTML has reserved characters, mostly the less than `<` and greater than signs `>`. These can also be escaped in HTML by using escape sequences.

There are several of these reserved characters in HTML:

<table name="t-07-02" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
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
<!-- CAPTION TEXT -->Table 7.2 &mdash; HTML reserved characters and escape sequences 
                     </sup></th></tr>
</table>                             <!-- TABLE END  🔼🔼(BLANK LINE BELOW) -->

HTML provides a series of escape sequences *(sometimes called symbol codes)* that start with an ampersand `&` followed by a meaningful group of characters *(well, meaningful in a way, some require a degree of interpretation)* and ending with a semicolon `;`. For example, the escape sequence for a less than symbol `<` is `&lt;`. 

Escape sequences always start with the ampersand character `&` and end with a semicolon `;`.

Basically, HTML escape sequences are a group of characters that are translated by the browser into a specific symbol.

Whenever the browser comes across the sequence of characters `&lt;`, it will display a less than sign `<`.

There are many other HTML escape sequences for characters not accessible via the key board `&mu;` for example displays the Greek Mu character µ. <a href="../A-0000/App%20A%20HTML%20escape%20characters.md">Appendix&nbsp;A</a> contains a full list of all HTML escape sequences.

**All of these HTML escape sequences work in Markdown, just put them in the text and GitHub will display them correctly.**

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 7.1.3<!--   🟥H3🟥--><img width="080" height="1" src="https://psop.uk/wi-s" alt="Spacer">HTML decimal and hexadecimal escape codes

The escape sequences of the previous section are one way of displaying reserved and non-keyboard characters. These escape sequences are intended to be intuitive mnemonics for the symbols they represent *(that said, I usually have to look them up)*. The problem is that not every character has one.

It is possible to use the Unicode value of the character as an *“escape code”* (as opposed to an escape sequence).

Every character that can be displayed has a Unicode value (a number), specifically a value given using the Unicode transformation format-8 (UTF-8<a name="rn-01" href="#fn-01"><!-- 🟨FOOTNOTE LINK🟨--><sup>💠1</sup></a>). For example, the letter “A” has a Unicode value of `65`, “B” `66` &c., there is a full list on Wikipedia: https://en.wikipedia.org/wiki/List_of_Unicode_characters. 

<a href="../C-0000/App%20C%20Segoe%20Character%20Set.md">Appendix&nbsp;C</a> contains a spreadsheet with the full character set.

In HTML and GitHub Flavoured Markdown, any character can be entered by using its Unicode value as an escape code. HTML escape codes are preceded by the ampersand and hash characters `&#` and finished with a semicolon `;`.

Continuing the previous example Unicode value for the letter “A” is `65` (decimal). To enter the letter “A” in HTML using an escape code, use the following:

&emsp;&emsp;&emsp;`&#65;`

**GitHub Markdown accepts the use of both HTML escape sequence and escape codes.**

The following tables gives a list of common escape sequence and escape codes <a href="../A-0000/App%20A%20HTML%20escape%20characters.md">Appendix&nbsp;A</a> has a complete list of all HTML escape sequences and codes (they mostly all work in GitHub Markdown, there are some exceptions though, these are listed in <a href="../07-0000/07%20Special%20characters%20and%20escaping%20characters.md#721escape-sequence-restrictions-in-github-html">section&nbsp;7.2.1</a>).

<table name="t-07-03" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row -->     <tr>
                            <th colspan="2">Mathematical</th>
                            <th>HTML</th>
                            <th>Code</th>
                            <th colspan="2">athematical</th>
                            <th>HTML</th>
                            <th>Code</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td width="75" align="center">&#0215;</td>
                            <td width="184" align="left">Multiplication sign</td>
                            <td width="102" align="center">&amp;times;</td>
                            <td width="87" align="center">&amp;#0215;</td>
                            <td width="75" align="center">&#8745;</td>
                            <td width="184" align="left">Intersection</td>
                            <td width="87" align="center">&amp;cap;</td>
                            <td width="75" align="center">&amp;#8745;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0247;</td>
                            <td align="left">Division sign</td>
                            <td align="center">&amp;divide;</td>
                            <td align="center">&amp;#0247;</td>
                            <td align="center">&#8747;</td>
                            <td align="left">Integral</td>
                            <td align="center">&amp;int;</td>
                            <td align="center">&amp;#8747;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8722;</td>
                            <td align="left">Minus sign</td>
                            <td align="center">&amp;minus;</td>
                            <td align="center">&amp;#8722;</td>
                            <td align="center">&#8776;</td>
                            <td align="left">Almost equal to</td>
                            <td align="center">&amp;asymp;</td>
                            <td align="center">&amp;#8776;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0177;</td>
                            <td align="left">Plus/minus sign</td>
                            <td align="center">&amp;plusmn;</td>
                            <td align="center">&amp;#0177;</td>
                            <td align="center">&#8800;</td>
                            <td align="left">Not equal to</td>
                            <td align="center">&amp;ne;</td>
                            <td align="center">&amp;#8800;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8260;</td>
                            <td align="left">Fraction slash</td>
                            <td align="center">&amp;frasl;</td>
                            <td align="center">&amp;#8260;</td>
                            <td align="center">&#8801;</td>
                            <td align="left">Identical to</td>
                            <td align="center">&amp;equiv;</td>
                            <td align="center">&amp;#8801;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8719;</td>
                            <td align="left">N-array product</td>
                            <td align="center">&amp;prod;</td>
                            <td align="center">&amp;#8719;</td>
                            <td align="center">&#0060;</td>
                            <td align="left">Less than </td>
                            <td align="center">&amp;lt;</td>
                            <td align="center">&amp;#0060;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8721;</td>
                            <td align="left">N-array summation</td>
                            <td align="center">&amp;sum;</td>
                            <td align="center">&amp;#8721;</td>
                            <td align="center">&#0062;</td>
                            <td align="left">Greater than</td>
                            <td align="center">&amp;gt;</td>
                            <td align="center">&amp;#0062;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8730;</td>
                            <td align="left">Square root</td>
                            <td align="center">&amp;radic;</td>
                            <td align="center">&amp;#8730;</td>
                            <td align="center">&#8804;</td>
                            <td align="left">Less than or equal to</td>
                            <td align="center">&amp;le;</td>
                            <td align="center">&amp;#8804;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8734;</td>
                            <td align="left">Infinity</td>
                            <td align="center">&amp;infin;</td>
                            <td align="center">&amp;#8734;</td>
                            <td align="center">&#8805;</td>
                            <td align="left">Greater than or equal to</td>
                            <td align="center">&amp;ge;</td>
                            <td align="center">&amp;#8805;</td>
                        </tr>
<!-- Header row -->     <tr valign="bottom">
                            <th colspan="2"><br><br><br>HTML reserved</th>
                            <th>HTML</th>
                            <th>Code</th>
                            <th colspan="2">HTML reserved</th>
                            <th>HTML</th>
                            <th>Code</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0060;</td>
                            <td align="left">Less than </td>
                            <td align="center">&amp;lt;</td>
                            <td align="center">&amp;#0060;</td>
                            <td align="center">&#0034;</td>
                            <td align="left">Quotation mark</td>
                            <td align="center">&amp;quot;</td>
                            <td align="center">&amp;#0034;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0062;</td>
                            <td align="left">Greater than</td>
                            <td align="center">&amp;gt;</td>
                            <td align="center">&amp;#0062;</td>
                            <td align="center">&#0039;</td>
                            <td align="left">Single quote</td>
                            <td align="center">&amp;apos;</td>
                            <td align="center">&amp;#0039;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0038;</td>
                            <td align="left">Ampersand</td>
                            <td align="center">&amp;amp;</td>
                            <td align="center">&amp;#0038;</td>
                            <td align="center"></td>
                            <td align="left"></td>
                            <td align="center"></td>
                            <td align="center"></td>
                        </tr>
<!-- Header row -->     <tr valign="bottom">
                            <th colspan="2"><br><br><br>Miscellaneous</th>
                            <th>HTML</th>
                            <th>Code</th>
                            <th colspan="2">Miscellaneous</th>
                            <th>HTML</th>
                            <th>Code</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8592;</td>
                            <td align="left">Leftwards arrow</td>
                            <td align="center">&amp;larr;</td>
                            <td align="center">&amp;#8592;</td>
                            <td align="center">&#0166;</td>
                            <td align="left">Broken vertical bar</td>
                            <td align="center">&amp;brvbar;</td>
                            <td align="center">&amp;#0166;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8593;</td>
                            <td align="left">Upwards arrow</td>
                            <td align="center">&amp;uarr;</td>
                            <td align="center">&amp;#8593;</td>
                            <td align="center">&#0176;</td>
                            <td align="left">Degree sign</td>
                            <td align="center">&amp;deg;</td>
                            <td align="center">&amp;#0176;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8594;</td>
                            <td align="left">Rightwards arrow</td>
                            <td align="center">&amp;rarr;</td>
                            <td align="center">&amp;#8594;</td>
                            <td align="center">&#0183;</td>
                            <td align="left">Middle dot</td>
                            <td align="center">&amp;middot;</td>
                            <td align="center">&amp;#0183;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8595;</td>
                            <td align="left">Downwards arrow</td>
                            <td align="center">&amp;darr;</td>
                            <td align="center">&amp;#8595;</td>
                            <td align="center">&#8226;</td>
                            <td align="left">Bullet</td>
                            <td align="center">&amp;bull;</td>
                            <td align="center">&amp;#8226;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8596;</td>
                            <td align="left">Left right arrow</td>
                            <td align="center">&amp;harr;</td>
                            <td align="center">&amp;#8596;</td>
                            <td align="center"></td>
                            <td align="left"></td>
                            <td align="center"></td>
                            <td align="center"></td>
                        </tr>
<!-- Header row -->     <tr valign="bottom">
                            <th>&emsp;&emsp;&emsp;</th>
                            <th><br><br><br>Spacing</th>
                            <th>HTML</th>
                            <th>Code</th>
                            <th>&emsp;&emsp;&emsp;</th>
                            <th>Spacing</th>
                            <th>HTML</th>
                            <th>Code</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">█&emsp;█</td>
                            <td align="left">Em space</td>
                            <td align="center">&amp;emsp;</td>
                            <td align="center">&amp;#8195;</td>
                            <td align="center">█ █</td>
                            <td align="left">Space</td>
                            <td align="center"> </td>
                            <td align="center">&amp;#0032;</td>
                        </tr>
<!-- Data row -->       <tr>                            
                            <td align="center">█&#8199;█</td>
                            <td align="left">Number space</td>
                            <td align="center">&amp;numsp;</td>
                            <td align="center">&amp;#8199;</td>
                            <td align="center">█&#8197;█</td>
                            <td align="left">Em/4 space</td>
                            <td align="center">&amp;emsp14;</td>
                            <td align="center">&amp;#8197;</td>
                        </tr>
<!-- Data row -->       <tr>                            
                            <td align="center">█&#8194;█</td>
                            <td align="left">En space</td>
                            <td align="center">&amp;ensp;</td>
                            <td align="center">&amp;#8194;</td>
                            <td align="center">█&#8200;█</td>
                            <td align="left">Punctuation space</td>
                            <td align="center">&amp;puncsp;</td>
                            <td align="center">&amp;#8200;</td>
                        </tr>
<!-- Data row -->       <tr>                            
                            <td align="center">█&#8196;█</td>
                            <td align="left">Em/3 space</td>
                            <td align="center">&amp;emsp13;</td>
                            <td align="center">&amp;#8196;</td>
                            <td align="center">█&#8201;█</td>
                            <td align="left">Thin space</td>
                            <td align="center">&amp;thinsp;</td>
                            <td align="center">&amp;#8201;</td>
                        </tr>
<!-- Data row -->       <tr>                            
                            <td align="center">█&#0160;█</td>
                            <td align="left">Non-breaking space</td>
                            <td align="center">&amp;nbsp;</td>
                            <td align="center">&amp;#0160;</td>
                            <td align="center">█&#8202;█</td>
                            <td align="left">Hair space</td>
                            <td align="center">&amp;hairsp;</td>
                            <td align="center">&amp;#8202;</td>
                        </tr>
<!-- Header row -->     <tr valign="bottom">
                            <th colspan="2"><br><br><br>Currency</th>
                            <th>HTML</th>
                            <th>Code</th>
                            <th colspan="2">Currency</th>
                            <th>HTML</th>
                            <th>Code</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0036;</td>
                            <td align="left">Dollar</td>
                            <td align="center">&amp;dollar;</td>
                            <td align="center">&amp;#0036;</td>
                            <td align="center">&#0162;</td>
                            <td align="left">Cent sign</td>
                            <td align="center">&amp;cent;</td>
                            <td align="center">&amp;#0162;</td>
                        </tr>
<!-- Data row -->       <tr>
                           <td align="center">&#0163;</td>
                            <td align="left">Pound sign</td>
                            <td align="center">&amp;pound;</td>
                            <td align="center">&amp;#0163;</td>
                            <td align="center">&yen;</td>
                            <td align="left">Yen</td>
                            <td align="center">&amp;yen;</td>
                            <td align="center">&amp;#0165;</td>
                         </tr>
<!-- Data row -->       <tr>
                            <td align="center">&euro;</td>
                            <td align="left">Euro sign</td>
                            <td align="center">&amp;euro;</td>
                            <td align="center">&amp;#0128;</td>
                            <td align="center">&curren;</td>
                            <td align="left">Curren</td>
                            <td align="center">&amp;curren;</td>
                            <td align="center">&amp;#0164;</td>
                        </tr>
<!-- Header row -->     <tr valign="bottom">
                            <th colspan="2"><br><br><br>Numbers</th>
                            <th>HTML</th>
                            <th>Code</th>
                            <th colspan="2">Numbers</th>
                            <th>HTML</th>
                            <th>Code</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0185;</td>
                            <td align="left">Superscript one</td>
                            <td align="center">&amp;sup1;</td>
                            <td align="center">&amp;#0185;</td>
                            <td align="center">&#0189;</td>
                            <td align="left">Fraction one half</td>
                            <td align="center">&amp;frac12;</td>
                            <td align="center">&amp;#0189;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0178;</td>
                            <td align="left">Superscript two</td>
                            <td align="center">&amp;sup2;</td>
                            <td align="center">&amp;#0178;</td>
                            <td align="center">&#0188;</td>
                            <td align="left">Fraction one quarter</td>
                            <td align="center">&amp;frac14</td>
                            <td align="center">&amp;#0188;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0179;</td>
                            <td align="left">Superscript three</td>
                            <td align="center">&amp;sup3;</td>
                            <td align="center">&amp;#0179;</td>
                            <td align="center">&#0190;</td>
                            <td align="left">Fraction three quarters</td>
                            <td align="center">&amp;frac34</td>
                            <td align="center">&amp;#0190;</td>
                        </tr>
<!-- Header row -->     <tr valign="bottom">
                            <th colspan="2"><br><br><br>Punctuation</th>
                            <th>HTML</th>
                            <th>Code</th>
                            <th colspan="2">Punctuation</th>
                            <th>HTML</th>
                            <th>Code</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0161;</td>
                            <td align="left">Inverted exclamation mark</td>
                            <td align="center">&amp;iexcl;</td>
                            <td align="center">&amp;#0161;</td>
                            <td align="center">&#8230;</td>
                            <td align="left">Horizontal ellipsis</td>
                            <td align="center">&amp;hellip;</td>
                            <td align="center">&amp;#8230;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0191;</td>
                            <td align="left">Inverted question mark</td>
                            <td align="center">&amp;iquest;</td>
                            <td align="center">&amp;#0191;</td>
                            <td align="center">&#8254;</td>
                            <td align="left">Overline</td>
                            <td align="center">&amp;oline;</td>
                            <td align="center">&amp;#8254;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8220;</td>
                            <td align="left">Left double quote</td>
                            <td align="center">&amp;ldquo;</td>
                            <td align="center">&amp;#8220;</td>
                            <td align="center">&#0167;</td>
                            <td align="left">Section sign</td>
                            <td align="center">&amp;sect;</td>
                            <td align="center">&amp;#0167;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8221;</td>
                            <td align="left">Right double quote</td>
                            <td align="center">&amp;rdquo;</td>
                            <td align="center">&amp;#8221;</td>
                            <td align="center">&#0182;</td>
                            <td align="left">Paragraph sign</td>
                            <td align="center">&amp;para;</td>
                            <td align="center">&amp;#0182;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8222;</td>
                            <td align="left">Double low-9 quote</td>
                            <td align="center">&amp;bdquo;</td>
                            <td align="center">&amp;#8222;</td>
                            <td align="center">&#0169;</td>
                            <td align="left">Copyright sign</td>
                            <td align="center">&amp;copy;</td>
                            <td align="center">&amp;#0169;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8216;</td>
                            <td align="left">Left single quote</td>
                            <td align="center">&amp;lsquo;</td>
                            <td align="center">&amp;#8216;</td>
                            <td align="center">&#0174;</td>
                            <td align="left">Registered trademark sign</td>
                            <td align="center">&amp;reg;</td>
                            <td align="center">&amp;#0174;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8217;</td>
                            <td align="left">Right single quote</td>
                            <td align="center">&amp; rsquo;</td>
                            <td align="center">&amp;#8217;</td>
                            <td align="center">&#8482;</td>
                            <td align="left">Trademark sign</td>
                            <td align="center">&amp;trade;</td>
                            <td align="center">&amp;#8482;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8218;</td>
                            <td align="left">Single low-9 quote</td>
                            <td align="center">&amp;sbquo;</td>
                            <td align="center">&amp;#8218;</td>
                            <td align="center">&#0172;</td>
                            <td align="left">Not sign</td>
                            <td align="center">&amp;not;</td>
                            <td align="center">&amp;#0172;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#9674;</td>
                            <td align="left">Lozenge</td>
                            <td align="center">&amp;loz;</td>
                            <td align="center">&amp;#9674;</td>
                            <td align="center">&#0181;</td>
                            <td align="left">Micro sign</td>
                            <td align="center">&amp;micro;</td>
                            <td align="center">&amp;#0181;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0171;</td>
                            <td align="left">Left double angle quote</td>
                            <td align="center">&amp;laquo;</td>
                            <td align="center">&amp;#0171;</td>
                            <td align="center">&#8240;</td>
                            <td align="left">Per mille sign</td>
                            <td align="center">&amp;permil;</td>
                            <td align="center">&amp;#8240;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0187;</td>
                            <td align="left">Right double angle quote</td>
                            <td align="center">&amp;raquo;</td>
                            <td align="center">&amp;#0187;</td>
                            <td align="center">&#8242;</td>
                            <td align="left">Prime (straight quote)</td>
                            <td align="center">&amp;prime;</td>
                            <td align="center">&amp;#8242;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8249;</td>
                            <td align="left">Single left angle quote</td>
                            <td align="center">&amp;lsaquo;</td>
                            <td align="center">&amp;#8249;</td>
                            <td align="center">&#8243;</td>
                            <td align="left">Double prime (straight quote)</td>
                            <td align="center">&amp;Prime;</td>
                            <td align="center">&amp;#8243;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8250;</td>
                            <td align="left">Single right angle quote</td>
                            <td align="center">&amp;rsaquo;</td>
                            <td align="center">&amp;#8250;</td>
                            <td align="center">&#8224;</td>
                            <td align="left">Dagger</td>
                            <td align="center">&amp;dagger;</td>
                            <td align="center">&amp;#8224;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8211;</td>
                            <td align="left">En dash</td>
                            <td align="center">&amp;ndash;</td>
                            <td align="center">&amp;#8211;</td>
                            <td align="center">&#8225;</td>
                            <td align="left">Double dagger</td>
                            <td align="center">&amp;Dagger;</td>
                            <td align="center">&amp;#8225;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#8212;</td>
                            <td align="left">Em dash</td>
                            <td align="center">&amp;mdash;</td>
                            <td align="center">&amp;#8212;</td>
                            <td align="center"></td>
                            <td align="left"></td>
                            <td align="center"></td>
                            <td align="center"></td>
                        </tr>
<!-- Header row -->     <tr valign="bottom">
                            <th colspan="2"><br><br><br>Greek small letters</th>
                            <th>HTML</th>
                            <th>Code</th>
                            <th colspan="2">Greek capital letters</th>
                            <th>HTML</th>
                            <th>Code</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0945;</td>
                            <td align="left">Alpha</td>
                            <td align="center">&amp;alpha</td>
                            <td align="center">&amp;#0945;</td>
                            <td align="center">&#0913;</td>
                            <td align="left">Alpha</td>
                            <td align="center">&amp;Alpha</td>
                            <td align="center">&amp;#0913;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0946;</td>
                            <td align="left">Beta</td>
                            <td align="center">&amp;beta;</td>
                            <td align="center">&amp;#0946;</td>
                            <td align="center">&#0914;</td>
                            <td align="left">Beta</td>
                            <td align="center">&amp;Beta;</td>
                            <td align="center">&amp;#0914;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0947;</td>
                            <td align="left">Gamma</td>
                            <td align="center">&amp;gamma;</td>
                            <td align="center">&amp;#0947;</td>
                            <td align="center">&#0915;</td>
                            <td align="left">Gamma</td>
                            <td align="center">&amp;Gamma;</td>
                            <td align="center">&amp;#0915;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0948;</td>
                            <td align="left">Delta</td>
                            <td align="center">&amp;delta;</td>
                            <td align="center">&amp;#0948;</td>
                            <td align="center">&#0916;</td>
                            <td align="left">Delta</td>
                            <td align="center">&amp;Delta;</td>
                            <td align="center">&amp;#0916;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0949;</td>
                            <td align="left">Epsilon</td>
                            <td align="center">&amp;epsilon;</td>
                            <td align="center">&amp;#0949;</td>
                            <td align="center">&#0917;</td>
                            <td align="left">Epsilon</td>
                            <td align="center">&amp;Epsilon;</td>
                            <td align="center">&amp;#0917;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0950;</td>
                            <td align="left">Zeta</td>
                            <td align="center">&amp;zeta;</td>
                            <td align="center">&amp;#0950;</td>
                            <td align="center">&#0918;</td>
                            <td align="left">Zeta</td>
                            <td align="center">&amp;Zeta;</td>
                            <td align="center">&amp;#0918;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0951;</td>
                            <td align="left">Eta</td>
                            <td align="center">&amp;eta;</td>
                            <td align="center">&amp;#0951;</td>
                            <td align="center">&#0919;</td>
                            <td align="left">Eta</td>
                            <td align="center">&amp;Eta;</td>
                            <td align="center">&amp;#0919;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0952;</td>
                            <td align="left">Theta</td>
                            <td align="center">&amp;theta;</td>
                            <td align="center">&amp;#0952;</td>
                            <td align="center">&#0920;</td>
                            <td align="left">Theta</td>
                            <td align="center">&amp;Theta;</td>
                            <td align="center">&amp;#0920;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0953;</td>
                            <td align="left">Iota</td>
                            <td align="center">&amp;iota;</td>
                            <td align="center">&amp;#0953;</td>
                            <td align="center">&#0921;</td>
                            <td align="left">Iota</td>
                            <td align="center">&amp;Iota;</td>
                            <td align="center">&amp;#0921;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0954;</td>
                            <td align="left">Kappa</td>
                            <td align="center">&amp;kappa;</td>
                            <td align="center">&amp;#0954;</td>
                            <td align="center">&#0922;</td>
                            <td align="left">Kappa</td>
                            <td align="center">&amp;Kappa;</td>
                            <td align="center">&amp;#0922;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0955;</td>
                            <td align="left">Lambda</td>
                            <td align="center">&amp;lambda;</td>
                            <td align="center">&amp;#0955;</td>
                            <td align="center">&#0923;</td>
                            <td align="left">Lambda</td>
                            <td align="center">&amp;Lambda;</td>
                            <td align="center">&amp;#0923;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0956;</td>
                            <td align="left">Mu</td>
                            <td align="center">&amp;mu;</td>
                            <td align="center">&amp;#0956;</td>
                            <td align="center">&#0924;</td>
                            <td align="left">Mu</td>
                            <td align="center">&amp;Mu;</td>
                            <td align="center">&amp;#0924;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0957;</td>
                            <td align="left">Nu</td>
                            <td align="center">&amp;nu;</td>
                            <td align="center">&amp;#0957;</td>
                            <td align="center">&#0925;</td>
                            <td align="left">Nu</td>
                            <td align="center">&amp;Nu;</td>
                            <td align="center">&amp;#0925;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0958;</td>
                            <td align="left">Xi</td>
                            <td align="center">&amp;xi;</td>
                            <td align="center">&amp;#0958;</td>
                            <td align="center">&#0926;</td>
                            <td align="left">Xi</td>
                            <td align="center">&amp;Xi;</td>
                            <td align="center">&amp;#0926;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0959;</td>
                            <td align="left">Omicron</td>
                            <td align="center">&amp;omicron;</td>
                            <td align="center">&amp;#0959;</td>
                            <td align="center">&#0927;</td>
                            <td align="left">Omicron</td>
                            <td align="center">&amp;Omicron;</td>
                            <td align="center">&amp;#0927;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0960;</td>
                            <td align="left">Pi</td>
                            <td align="center">&amp;pi;</td>
                            <td align="center">&amp;#0960;</td>
                            <td align="center">&#0928;</td>
                            <td align="left">Pi</td>
                            <td align="center">&amp;Pi;</td>
                            <td align="center">&amp;#0928;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0961;</td>
                            <td align="left">Rho</td>
                            <td align="center">&amp;rho;</td>
                            <td align="center">&amp;#0961;</td>
                            <td align="center">&#0929;</td>
                            <td align="left">Rho</td>
                            <td align="center">&amp;Rho;</td>
                            <td align="center">&amp;#0929;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0962;</td>
                            <td align="left">Sigma 1</td>
                            <td align="center">&amp;sigmaf;</td>
                            <td align="center">&amp;#0962;</td>
                            <td align="center">&#0931;</td>
                            <td align="left">Sigma</td>
                            <td align="center">&amp;Sigma;</td>
                            <td align="center">&amp;#0931;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0963;</td>
                            <td align="left">Sigma 2</td>
                            <td align="center">&amp;sigma;</td>
                            <td align="center">&amp;#0963;</td>
                            <td align="center"></td>
                            <td align="left"></td>
                            <td align="center"></td>
                            <td align="center"></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0964;</td>
                            <td align="left">Tau</td>
                            <td align="center">&amp;tau;</td>
                            <td align="center">&amp;#0964;</td>
                            <td align="center">&#0932;</td>
                            <td align="left">Tau</td>
                            <td align="center">&amp;Tau;</td>
                            <td align="center">&amp;#0932;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0965;</td>
                            <td align="left">Upsilon</td>
                            <td align="center">&amp;upsilon;</td>
                            <td align="center">&amp;#0965;</td>
                            <td align="center">&#0933;</td>
                            <td align="left">Upsilon</td>
                            <td align="center">&amp;Upsilon;</td>
                            <td align="center">&amp;#0933;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0966;</td>
                            <td align="left">Phi</td>
                            <td align="center">&amp;phi;</td>
                            <td align="center">&amp;#0966;</td>
                            <td align="center">&#0934;</td>
                            <td align="left">Phi</td>
                            <td align="center">&amp;Phi;</td>
                            <td align="center">&amp;#0934;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0967;</td>
                            <td align="left">Chi</td>
                            <td align="center">&amp;chi;</td>
                            <td align="center">&amp;#0967;</td>
                            <td align="center">&#0935;</td>
                            <td align="left">Chi</td>
                            <td align="center">&amp;Chi;</td>
                            <td align="center">&amp;#0935;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0968;</td>
                            <td align="left">Psi</td>
                            <td align="center">&amp;psi;</td>
                            <td align="center">&amp;#0968;</td>
                            <td align="center">&#0936;</td>
                            <td align="left">Psi</td>
                            <td align="center">&amp;Psi;</td>
                            <td align="center">&amp;#0936;</td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center">&#0969;</td>
                            <td align="left">Omega</td>
                            <td align="center">&amp;omega;</td>
                            <td align="center">&amp;#0969;</td>
                            <td align="center">&#0937;</td>
                            <td align="left">Omega</td>
                            <td align="center">&amp;Omega;</td>
                            <td align="center">&amp;#0937;</td>
                        </tr>
<!-- CAPTION -->    <tr><th colspan="8" align="left"><sup>
<!-- CAPTION TEXT -->Table 7.3 &mdash; HTML common escape sequences and codes
                     </sup></th></tr>
</table>                             <!-- TABLE END  🔼🔼(BLANK LINE BELOW) -->

<br><br>
#### <!--       🟥H4🟥--><u>Hexadecimal escape codes<!-- Extended line -->&emsp;&emsp;&emsp;&emsp;&emsp;</u> 

The escape codes listed above use decimal numbers for the Unicode characters `&#65;` where `65` is the decimal value of the Unicode number for “A”. 

The escape codes can also be given in hexadecimal format and this will work within GitHub Markdown and Wiki pages. The hexadecimal equivalent of `65` is `41`. To use the hexadecimal number in an escape code, precede it with `&#x` and follow it with a semicolon `;`. Thus:

<!---🟡ENTER URL🟡-->https://docs.github.com/en/enterprise-cloud@latest
`&#65;` and `&#x41;` both display the “A” character.

> [!TIP]<!-- TIP ALERT -->
> *Being able to use hexadecimal notation is useful; simply because Unicode char-acters are generally given in hexadecimal format.* `U+0041` *is Unicode for* “A”.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 7.2<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Special space characters

Markdown (and GitHub Markdown) ignore multiple spaces. In the following example, the two words “TEST” are separated by five spaces:

<table name="t-07-04" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
TEST     TEST
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

TEST     TEST

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 7.4 &mdash; Markdown ignores multiple consecutive spaces
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Markdown simply ignores the multiple, consecutive spaces.

Markdown does not, however, ignore the non-breaking space character `&nbsp;,` this has exactly the same spacing as a normal space character, but will always be rendered by Markdown.

This is the same example with five non-breaking spaces between the two words “TEST”

<table name="t-07-05" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
TEST&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;TEST
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

TEST&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;TEST

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 7.4 &mdash; Markdown does not ignore multiple consecutive non-breaking spaces
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

Markdown supports several such space characters; this is a full list — the spaces are bounded by full blocks to give an idea of the width of each type of space, the second column shows four of each type of space to emphasize the different relative sizes:

<table name="t-07-06" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row -->     <tr>
                            <th width="120" align="center">Single Space</th>
                            <th width="130" align="center">Four Spaces</th>
                            <th width="180" align="center">Name</th>
                            <th width="180" align="center">Escape sequence</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>█&emsp;█</p></td>
                            <td align="center"><p>█&emsp;&emsp;&emsp;&emsp;█</p></td>
                            <td align="center"><p>Em space</p></td>
                            <td align="center"><p><code>&amp;emsp;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>█&#8199;█</p></td>
                            <td align="center"><p>█&#8199;&#8199;&#8199;&#8199;█</p></td>
                            <td align="center"><p>Number space</p></td>
                            <td align="center"><p><code>&amp;numsp;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>█&ensp;█</p></td>
                            <td align="center"><p>█&ensp;&ensp;&ensp;&ensp;█</p></td>
                            <td align="center"><p>En space</p></td>
                            <td align="center"><p><code>&amp;ensp;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>█&#8196;█</p></td>
                            <td align="center"><p>█&#8196;&#8196;&#8196;&#8196;█</p></td>
                            <td align="center"><p>Em/3 space</p></td>
                            <td align="center"><p><code>&amp;emsp13;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>█&nbsp;█</p></td>
                            <td align="center"><p>█&nbsp;&nbsp;&nbsp;&nbsp;█</p></td>
                            <td align="center"><p>Non-breaking space</p></td>
                            <td align="center"><p><code>&amp;nbsp;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>█&#8197;█</p></td>
                            <td align="center"><p>█&#8197;&#8197;&#8197;&#8197;█</p></td>
                            <td align="center"><p>Em/4 space</p></td>
                            <td align="center"><p><code>&amp;emsp14;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>█&#8200;█</p></td>
                            <td align="center"><p>█&#8200;&#8200;&#8200;&#8200;█</p></td>
                            <td align="center"><p>Punctuation space</p></td>
                            <td align="center"><p><code>&amp;puncsp;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>█&thinsp;█</p></td>
                            <td align="center"><p>█&thinsp;&thinsp;&thinsp;&thinsp;█</p></td>
                            <td align="center"><p>Thin space</p></td>
                            <td align="center"><p><code>&amp;thinsp;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>█&#8202;█</p></td>
                            <td align="center"><p>█&#8202;&#8202;&#8202;&#8202;█</p></td>
                            <td align="center"><p>Hair space</p></td>
                            <td align="center"><p><code>&amp;hairsp;</code></p></td>
                        </tr>
<!-- CAPTION -->    <tr><th colspan="4" align="left"><sup>
<!-- CAPTION TEXT -->   Table 7.6 &mdash; Different spaces and relative widths
                    </sup></th></tr>
</table>
<br clear="all">                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->

These different size spaces are used extensively in the PracticalSeries Wiki page headings and tables of contents to ensure that the gaps between the heading numbers and the heading text are consistent. 

The size of the gap between the heading number on the left and the heading text on the right, depends on how many numbers there are (**90.10.20** has six numbers, **1.2.4** only has three. Both are valid section numbers, but the first will have a smaller space between the last full stop and the heading text).

The width of each type of space depends where the space is used. The space in a heading (all headings are different) is generally larger than the same space used in body text. Similarly, if the text is in a sidebar or footer, the spacings are again different for headings and body text. 

The following tables give the width in pixels of each different type of space character for all headings and body text in both the main page area and sidebars/footers *(there is no difference between space sizes in sidebars and in footers, they are the same)*.


<table name="t-07-07" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row -->     <tr>
                            <th colspan="8" align="center">Space witdths in pixels for the main page</th>
                        </tr>
<!-- Data row -->       <tr>
                            <th width="174" align="center"><p></p></th>
                            <th width="97"  align="center"><p>H1</p></th>
                            <th width="97"  align="center"><p>H2</p></th>
                            <th width="97"  align="center"><p>H3</p></th>
                            <th width="97"  align="center"><p>H4</p></th>
                            <th width="97"  align="center"><p>H5</p></th>
                            <th width="97"  align="center"><p>H6</p></th>
                            <th width="97"  align="center"><p>Body text</p></th>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Em space</p></th>
                            <td align="center"><p>32.00</p></td>
                            <td align="center"><p>24.00</p></td>
                            <td align="center"><p>20.00</p></td>
                            <td align="center"><p>16.00</p></td>
                            <td align="center"><p>14.00</p></td>
                            <td align="center"><p>13.60</p></td>
                            <td align="center"><p>16.00</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Number space</p></th>
                            <td align="center"><p>17.77</p></td>
                            <td align="center"><p>13.33</p></td>
                            <td align="center"><p>11.10</p></td>
                            <td align="center"><p>8.87</p></td>
                            <td align="center"><p>7.77</p></td>
                            <td align="center"><p>7.53</p></td>
                            <td align="center"><p>8.63</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>En space</p></th>
                            <td align="center"><p>16.00</p></td>
                            <td align="center"><p>12.00</p></td>
                            <td align="center"><p>10.00</p></td>
                            <td align="center"><p>8.00</p></td>
                            <td align="center"><p>7.00</p></td>
                            <td align="center"><p>6.80</p></td>
                            <td align="center"><p>8.00</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Em/3 space</p></th>
                            <td align="center"><p>10.63</p></td>
                            <td align="center"><p>8.00</p></td>
                            <td align="center"><p>6.63</p></td>
                            <td align="center"><p>5.33</p></td>
                            <td align="center"><p>4.67</p></td>
                            <td align="center"><p>4.53</p></td>
                            <td align="center"><p>5.33</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Normal space</p></th>
                            <td align="center"><p>8.80</p></td>
                            <td align="center"><p>6.60</p></td>
                            <td align="center"><p>5.47</p></td>
                            <td align="center"><p>4.40</p></td>
                            <td align="center"><p>3.87</p></td>
                            <td align="center"><p>3.73</p></td>
                            <td align="center"><p>4.37</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Non-breaking space</p></th>
                            <td align="center"><p>8.80</p></td>
                            <td align="center"><p>6.60</p></td>
                            <td align="center"><p>5.47</p></td>
                            <td align="center"><p>4.40</p></td>
                            <td align="center"><p>3.87</p></td>
                            <td align="center"><p>3.73</p></td>
                            <td align="center"><p>4.37</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Em/4 space</p></th>
                            <td align="center"><p>8.00</p></td>
                            <td align="center"><p>6.00</p></td>
                            <td align="center"><p>5.00</p></td>
                            <td align="center"><p>4.00</p></td>
                            <td align="center"><p>3.50</p></td>
                            <td align="center"><p>3.40</p></td>
                            <td align="center"><p>4.00</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Punctuation space</p></th>
                            <td align="center"><p>7.70</p></td>
                            <td align="center"><p>5.80</p></td>
                            <td align="center"><p>4.80</p></td>
                            <td align="center"><p>3.87</p></td>
                            <td align="center"><p>3.37</p></td>
                            <td align="center"><p>3.27</p></td>
                            <td align="center"><p>3.47</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Thin space</p></th>
                            <td align="center"><p>6.40</p></td>
                            <td align="center"><p>4.83</p></td>
                            <td align="center"><p>4.00</p></td>
                            <td align="center"><p>3.20</p></td>
                            <td align="center"><p>2.80</p></td>
                            <td align="center"><p>2.70</p></td>
                            <td align="center"><p>3.20</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Hair space</p></th>
                            <td align="center"><p>4.00</p></td>
                            <td align="center"><p>3.00</p></td>
                            <td align="center"><p>2.50</p></td>
                            <td align="center"><p>2.00</p></td>
                            <td align="center"><p>1.77</p></td>
                            <td align="center"><p>1.70</p></td>
                            <td align="center"><p>2.00</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Two blocks ██</p></th>
                            <td align="center"><p>47.00</p></td>
                            <td align="center"><p>35.00</p></td>
                            <td align="center"><p>30.00</p></td>
                            <td align="center"><p>24.00</p></td>
                            <td align="center"><p>21.00</p></td>
                            <td align="center"><p>21.00</p></td>
                            <td align="center"><p>24.00</p></td>
                        </tr>
<!-- CAPTION -->    <tr><th colspan="8" align="left"><sup>
<!-- CAPTION TEXT -->   Table 7.7 &mdash; Space widths in the main page (in pixels)
                    </sup></th></tr>
</table>
<br clear="all">                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->


<table name="t-07-08" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row -->     <tr>
                            <th colspan="8" align="center">Space witdths in pixels for sidebars and footers</th>
                        </tr>
<!-- Data row -->       <tr>
                            <th width="174" align="center"><p></p></th>
                            <th width="97"  align="center"><p>H1</p></th>
                            <th width="97"  align="center"><p>H2</p></th>
                            <th width="97"  align="center"><p>H3</p></th>
                            <th width="97"  align="center"><p>H4</p></th>
                            <th width="97"  align="center"><p>H5</p></th>
                            <th width="97"  align="center"><p>H6</p></th>
                            <th width="97"  align="center"><p>Body text</p></th>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Em space</p></th>
                            <td align="center"><p>24.00</p></td>
                            <td align="center"><p>18.00</p></td>
                            <td align="center"><p>15.00</p></td>
                            <td align="center"><p>12.00</p></td>
                            <td align="center"><p>10.50</p></td>
                            <td align="center"><p>10.20</p></td>
                            <td align="center"><p>12.00</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Number space</p></th>
                            <td align="center"><p>13.33</p></td>
                            <td align="center"><p>10.00</p></td>
                            <td align="center"><p>8.30</p></td>
                            <td align="center"><p>6.67</p></td>
                            <td align="center"><p>5.83</p></td>
                            <td align="center"><p>5.63</p></td>
                            <td align="center"><p>6.47</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>En space</p></th>
                            <td align="center"><p>12.00</p></td>
                            <td align="center"><p>9.00</p></td>
                            <td align="center"><p>7.50</p></td>
                            <td align="center"><p>6.00</p></td>
                            <td align="center"><p>5.27</p></td>
                            <td align="center"><p>5.10</p></td>
                            <td align="center"><p>6.00</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Em/3 space</p></th>
                            <td align="center"><p>8.00</p></td>
                            <td align="center"><p>6.00</p></td>
                            <td align="center"><p>4.97</p></td>
                            <td align="center"><p>4.00</p></td>
                            <td align="center"><p>3.50</p></td>
                            <td align="center"><p>3.40</p></td>
                            <td align="center"><p>4.00</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Normal space</p></th>
                            <td align="center"><p>6.60</p></td>
                            <td align="center"><p>4.93</p></td>
                            <td align="center"><p>4.10</p></td>
                            <td align="center"><p>3.30</p></td>
                            <td align="center"><p>2.90</p></td>
                            <td align="center"><p>2.80</p></td>
                            <td align="center"><p>3.30</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Non-breaking space</p></th>
                            <td align="center"><p>6.60</p></td>
                            <td align="center"><p>4.93</p></td>
                            <td align="center"><p>4.10</p></td>
                            <td align="center"><p>3.30</p></td>
                            <td align="center"><p>2.90</p></td>
                            <td align="center"><p>2.80</p></td>
                            <td align="center"><p>3.30</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Em/4 space</p></th>
                            <td align="center"><p>6.00</p></td>
                            <td align="center"><p>4.50</p></td>
                            <td align="center"><p>3.73</p></td>
                            <td align="center"><p>3.00</p></td>
                            <td align="center"><p>2.63</p></td>
                            <td align="center"><p>2.53</p></td>
                            <td align="center"><p>3.00</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Punctuation space</p></th>
                            <td align="center"><p>5.80</p></td>
                            <td align="center"><p>4.33</p></td>
                            <td align="center"><p>3.60</p></td>
                            <td align="center"><p>2.90</p></td>
                            <td align="center"><p>2.53</p></td>
                            <td align="center"><p>2.43</p></td>
                            <td align="center"><p>2.60</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Thin space</p></th>
                            <td align="center"><p>4.83</p></td>
                            <td align="center"><p>3.60</p></td>
                            <td align="center"><p>3.00</p></td>
                            <td align="center"><p>2.40</p></td>
                            <td align="center"><p>2.10</p></td>
                            <td align="center"><p>2.03</p></td>
                            <td align="center"><p>2.40</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Hair space</p></th>
                            <td align="center"><p>3.00</p></td>
                            <td align="center"><p>2.23</p></td>
                            <td align="center"><p>1.87</p></td>
                            <td align="center"><p>1.47</p></td>
                            <td align="center"><p>1.33</p></td>
                            <td align="center"><p>1.27</p></td>
                            <td align="center"><p>1.50</p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <th align="right"><p>Two blocks ██</p></th>
                            <td align="center"><p>35.00</p></td>
                            <td align="center"><p>27.00</p></td>
                            <td align="center"><p>23.00</p></td>
                            <td align="center"><p>18.00</p></td>
                            <td align="center"><p>16.00</p></td>
                            <td align="center"><p>16.00</p></td>
                            <td align="center"><p>18.00</p></td>
                        </tr>
<!-- CAPTION -->    <tr><th colspan="8" align="left"><sup>
<!-- CAPTION TEXT -->   Table 7.8 &mdash; Space widths in sidebars and footers (in pixels)
                    </sup></th></tr>
</table>
<br clear="all">                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->

> [!NOTE]<!-- NOTE ALERT -->
> *All widths in the above tables are measured using the Edge browser with page magnification set to 100% on a monitor set to its native resolution (2560 × 1440 px).*

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 7.2.1<!--   🟥H3🟥--><img width="080" height="1" src="https://psop.uk/wi-s" alt="Spacer">Escape sequence restrictions in GitHub HTML

For some reason, some HTML escape sequences do not work in GitHub Wiki Markdown.

This is true only when the escape sequences are between HTML tags, i.e. in a table `<table>…</table>` or between `<p>…</p>` tags for example.

Mainly this affects some of the special space characters:

<table name="t-07-09" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Header row -->     <tr>
                            <th width="200" valign="bottom" align="center">Name</th>
                            <th width="200" align="center">Non-functional<br>Esc sequence
</th>
                            <th width="180" align="center">Replacement<br>Esc code (dec)
</th>
                            <th width="180" align="center">Replacement<br>Esc code (hex)</th>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>Number space</p></td>
                            <td align="center"><p><code>&amp;numsp;</code></p></td>
                            <td align="center"><p><code>&amp;#8199;</code></p></td>
                            <td align="center"><p><code>&amp;#x2007;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>Em/3 space</p></td>
                            <td align="center"><p><code>&amp;emsp13;</code></p></td>
                            <td align="center"><p><code>&amp;#8196;</code></p></td>
                            <td align="center"><p><code>&amp;#x2004;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>Em/4 space</p></td>
                            <td align="center"><p><code>&amp;emsp14;</code></p></td>
                            <td align="center"><p><code>&amp;#8197;</code></p></td>
                            <td align="center"><p><code>&amp;#x2005;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>Punctuation space</p></td>
                            <td align="center"><p><code>&amp;puncsp;</code></p></td>
                            <td align="center"><p><code>&amp;#8200;</code></p></td>
                            <td align="center"><p><code>&amp;#x2008;</code></p></td>
                        </tr>
<!-- Data row -->       <tr>
                            <td align="center"><p>Hair space</p></td>
                            <td align="center"><p><code>&amp;hairsp;</code></p></td>
                            <td align="center"><p><code>&amp;#8202;</code></p></td>
                            <td align="center"><p><code>&amp;#x200A;</code></p></td>
                        </tr>
<!-- CAPTION -->    <tr><th colspan="4" align="left"><sup>
<!-- CAPTION TEXT -->   Table 7.9 &mdash; Escape sequences that do not work in GitHub Markdown HTML
                    </sup></th></tr>
</table>
<br clear="all">                     <!-- TABLE END🔼🔼(BLANK LINE BELOW) -->

> [!IMPORTANT]<!-- IMPORTANT ALERT -->
> **This is only a partial list of the most common escape sequences, a full list is available in <a href="../A-0200/App%20A.02%20HTML%20escape%20characters.md#heading">Appendix&nbsp;A.2</a>**



The alternate decimal and hexadecimal escape codes work everywhere.

> [!NOTE]<!-- NOTE ALERT -->
> *The above escape sequences work perfectly well with just Markdown, it is only when they are inside an HTML tag that problems occur.*
>
> *To complicate things, it is only Wiki Markdown that is affected, all the escape sequences work perfectly well in repository Markdown, see* <a href="../05-0000/05%20Markdown,%20GitHub%20Markdown%20and%20HTML.md#56markdown-difference-between-files">section 5.6</a>.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 7.3<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Emojis and emoticons

Emojis and emoticons are pictograms that can be embedded in text to convey some form of emotion, smiley face symbols, that sort of thing. They are popular with teenagers and the intellectually challenged.

GitHub supports a full set of Unicode emojis and these can be pasted directly into a Wiki or Markdown page, they can be entered using short name abbreviations or they can be entered as either decimal escape codes `&#…;` or hexadecimal escape codes `&#x…;`.

There is a standard version of the short names that can be used for emojis, these are managed by the Unicode CLDR (Common Locale Data Repository), available here: https://cldr.unicode.org/. 

The Unicode CLDR provides a full list of all emoji characters, their Unicode character (or string of characters) and the formal short form name, the list is available here: https://unicode.org/emoji/charts/full-emoji-list.html.

GitHub allows short names to be used, these are surrounded by a colon `:` before and after, thus, the crossed fingers emoji is displayed in Markdown with the short name:

&emsp;&emsp;&emsp;`:crossed_fingers:` it looks like this: 🤞

The problem with this approach is that GitHub, *in its wisdom,* decided not to use the standardised (Unicode CDLR) short names, it uses its own versions with slightly different names.

I thought at first this was so that GitHub could use shorter names than the standard CLDR, for example where the CLDR has the name `grinning face` (😀)and GitHub just has `:grinning:`. 

This argument falls down with the CLDR: `smiling face with hearts` and the GitHub `:smiling_face_with_three_hearts:` (🥰). So I’ve no idea why GitHub have differed.

<a href="../B-0000/App%20B%20Emoji%20list.md">Appendix&nbsp;B</a> contains a full list of all the emojis. For completeness, it shows both the GitHub short name and the standardised CDLR short name, the decimal escape code and the hexadecimal escape code.

<br><br>
#### <!--       🟥H4🟥--><u>A note by the Author about emojis<!-- Extended line -->&emsp;&emsp;&emsp;&emsp;&emsp;</u> 

<table name="f-07-00a" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr>
                        <td width="500" align="center">Well, I’m an engineer and engineers in particular are not at home to emojis <em>(we’re not generally tainted with emotion)</em>.<br><br>
                        <strong>Engineers have only one rule for using emojis:</strong><br><br>
                        ${\LARGE \color{#C00000}\text{DON'T\ EVER!}}$
                        </td>
                        <td>
<!-- LINK -->         <a href="./07-0000/02-images/sgsmiley.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="200" src="./07-0000/02-images/sgsmiley.png" alt="Smiley">
                        </a></td>
                    </tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 7.4<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Comments

It is possible to insert comments in Markdown text.

Comments are visible in Markdown, but are not displayed when the page is rendered (on a web browser).

Comments in Markdown are identical to those in HTML.

Any text between `<!--` and `-->` is a comment and will not be displayed:

<table name="t-07-10" align="center"><!-- 🔴🟢🔵TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- TOP & WIDTH --><tr><th width="850" align="right"><sup>Markdown, HTML equivalence and GitHub output
                    </sup></th></tr>
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#0050C0}\text{M\ A\ R\ K\ D\ O\ W\ N}}$ 🔽</th>
                    </tr>
<!-- MD row -->    <tr><td align="left"><br><!-- 🔴MARKDOWN BELOW🔴 -->

```md
Comments <!-- Like this --> are not displayed
```
<p> </p></td></tr><!-- 🔴MARKDOWN END OF ROW🔴 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#00C050}\text{H\ T\ M\ L}}$ 🔽</th>
                    </tr>
<!-- HTML row -->   <tr><td align="left"><br><!-- 🟢HTML BELOW🟢 -->

```html
<p>Comments <!-- Like this --> are not displayed</p>
```
<p> </p></td></tr><!-- 🟢HTML END OF ROW🟢 -->
<!-- Header row --> <tr>
                        <th align="left">${\large \color{#B00000}\text{G\ I\ T\ H\ U\ B}\space\ \space\text{O\ U\ T\ P\ U\ T}}$ 🔽</th>
                    </tr>
<!-- GIT row -->    <tr><td align="left"><!-- 🔵GITHUB OUTPUT BELOW (BLANK LINE BELOW)🔵 -->

Comments <!-- Like this --> are not displayed

</td></tr><!-- 🔵GITHUB OUTPUT END (BLANK LINE ABOVE)🔵 -->
<!-- CAPTION -->    <tr><th align="left"><sup>
<!-- CAPTION TEXT -->Table 7.10 &mdash; Body text examples
                    </sup></th></tr>
</table>                             <!-- 🟥🟩🟦TABLE END  🔼🔼(BLANK LINE BELOW) -->

*I think I’m one of the only people who bother putting comments in their Markdown.*


<hr><!-- FOOTNOTE SEPARATOR 🟡🟡🟡🟡🟡 -->
<a name="idfn" href="#idfn">Footnotes:<!-- 🟡FOOTNOTE TITLE🟡 -->&emsp;&emsp;&emsp;&emsp;&emsp;</a>
<br><br><br>

> [!NOTE]<!-- 🟡FOOTNOTE CONTENT -->
> <a name="fn-01" href="#rn-01"><sup>💠1</sup></a>&emsp;<!-- FOOTNOTE CONTENT TEXT -->UTF-8 is a Unicode character set that is backwards compatible with the old 7-bit ASCII char-acters that those of us of a certain age will remember. The 8 means it uses 8-bit blocks (bytes to most people, but octets in the Unicode standard) to represent characters, it can have up to 4 bytes and can represent all Unicode characters *(there is a lot of them, ‘bout a million)*.<!--  CONTENT TEXT END --><a href="#rn-01">↩</a>
>
> UTF-8 is the standard character set for web pages and E-mail.


<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->