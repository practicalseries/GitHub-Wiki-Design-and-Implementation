<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="./ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-C00--eaq-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 

# C.<!--         🟥H1🟥--><img width="097" height="1" src="https://psop.uk/wi-s" alt="Spacer">Segoe UI &mdash; Full Unicode character set

The following is a full character set for the Segoe UI font. All characters are renderable on GitHub (with the exception of certain control characters, these function as control characters but have no renderable appearance, these are labelled N/A).

The character set is very large (approximately 26,700 characters in total) and has been split across several pages (GitHub limits a Wiki page to a maximum of 484,000 characters). 

The character set is split as follows:

&emsp;&emsp;&emsp;[C.2.&emsp;Characters U+00000 to U+00FFF](App-C.02-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.3.&emsp;Characters U+01000 to U+01FFF](App-C.03-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.4.&emsp;Characters U+02000 to U+02FFF](App-C.04-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.5.&emsp;Characters U+03000 to U+09FFF](App-C.05-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.6.&emsp;Characters U+0A000 to U+0AFFF](App-C.06-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.7.&emsp;Characters U+0B000 to U+0FFFF](App-C.07-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.8.&emsp;Characters U+10000 to U+10FFF](App-C.08-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.9.&emsp;Characters U+11000 to U+11FFF](App-C.09-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.10.&ensp;Characters U+12000 to U+12FFF](App-C.10-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.11.&ensp;Characters U+13000 to U+15FFF](App-C.11-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.12.&ensp;Characters U+16000 to U+1CFFF](App-C.12-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.13.&ensp;Characters U+1D000 to U+1EFFF](App-C.13-Segoe-Character-Set)<br>
&emsp;&emsp;&emsp;[C.14.&ensp;Characters U+1F000 to U+3FFFF](App-C.14-Segoe-Character-Set)<br>

There is a spread sheet version of all this data here:


<p align="center"><a href="./C-0000/04-data/segou_full_character_set.xlsx"><img height="30" src="https://img.shields.io/badge/Download_the_full_Segoe_UI_character_spread_sheet-1F883D"></a></p>

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

#### <!--       🟥H4🟥--><u>A note by the Author<!-- Extended line -->&emsp;&emsp;&emsp;&emsp;&emsp;</u> 

You may be wondering why I’ve bothered to include these tables of Unicode character sets.

The answer is: “I already had them”. As part of the process of procuring the [PAL Software Library]( https://practicalseries.com/2001-pal/11-web/index.html), it was necessary to identify the characters that were in one of the distributed fonts needed to program the various devices. This font was called Siemens TIA Portal and I put together the whole spreadsheet of available characters for it.

It turns out that the Siemens TIA Portal font and Segoe UI have very similar character sets and, since the spreadsheet already existed, it was very easy to just change the font to Segoe UI and then check to see which characters no longer worked and edit them from the spreadsheet.

The second reason for doing this is that it is actually quite difficult to find a full list of Unicode characters all in one place with their descriptions. 

The closest I could get was a CSV file on the Unicode site that has all the descriptions, you can get it here:

&emsp;&emsp;&emsp;<!--- Enter URL -->http://unicode.org/Public/UCD/latest/ucd/UnicodeData.txt

It's a bit brutal, just plain CSV without column headings.

So here it all is, if you are looking for the full list, I suggest you use the downloadable spreadsheet, it just has all the information in one place.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## C.1<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Inserting Unicode characters in a Markdown file

Any character can be inserted into a Markdown file by incorporating its Unicode value (either decimal or hexadecimal) in an escape code.

For example, the “A” character can be inserted using the hexadecimal Unicode value:

&emsp;&emsp;&emsp;`&#x41;`

Within any Markdown file. Hexadecimal codes should be preceded by `&#x` and followed by a semicolon (`;`).
The decimal equivalent is:

&emsp;&emsp;&emsp;`&#65;`

Decimal codes should be preceded by `&#` and followed by a semicolon (`;`).

Although the tables show hexadecimal numbers with leading zeros, the leading zeros can be included or omitted in the escape code (it makes no difference).

<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->
