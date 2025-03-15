<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="./ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-A02--eaq-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 

## A.2<!--      🟥H2🟥--><img width="087" height="1" src="https://psop.uk/wi-s" alt="Spacer">Non-functional escape sequences

For reasons that are not clear, some HTML escape sequences do not work with HTML tags in GitHub Wiki Markdown. This is a Wiki problem only; the same escape sequenc-es work perfectly well with HTML tags in repository Markdown files.

This is a list of all affected escape sequences *(the replacement codes always work)*:

|Unicode&nbsp;(dec)<br>Unicode (hex)|Symbol| ${\large \color{#B00000}\text{NON-FUNCTIONAL}}$ <br> ${\large \color{#B00000}\text{HTML\ CODE}}$ |Escape&nbsp;(dec)<br>Escape (hex)|Description|
|:---|:---|:---|:---|:---|
|0009<br>U+0009|Tab|`&Tab;`|`&#0009;`<br>`&#x0009;`|Tab|
|0010<br>U+000A|New Line|`&NewLine;`|`&#0010;`<br>`&#x000A;`|New Line|
|0256<br>U+0100|█ █|`&Amacr;`|`&#0256;`<br>`&#x0100;`|Latin capital letter a with macron|
|0257<br>U+0101|!|`&amacr;`|`&#0257;`<br>`&#x0101;`|Latin small letter a with macron|
|0258<br>U+0102|“|`&Abreve;`|`&#0258;`<br>`&#x0102;`|Latin capital letter a with breve|
|0259<br>U+0103|#|`&abreve;`|`&#0259;`<br>`&#x0103;`|Latin small letter a with breve|
|0260<br>U+0104|$|`&Aogon;`|`&#0260;`<br>`&#x0104;`|Latin capital letter a with ogonek|
|0261<br>U+0105|%|`&aogon;`|`&#0261;`<br>`&#x0105;`|Latin small letter a with ogonek|
|0262<br>U+0106|&|`&Cacute;`|`&#0262;`<br>`&#x0106;`|Latin capital letter c with acute|
|0263<br>U+0107|‘|`&cacute;`|`&#0263;`<br>`&#x0107;`|Latin small letter c with acute|
|0264<br>U+0108|(|`&Ccirc;`|`&#0264;`<br>`&#x0108;`|Latin capital letter c with circumflex|
|0265<br>U+0109|)|`&ccirc;`|`&#0265;`<br>`&#x0109;`|Latin small letter c with circumflex|
|0266<br>U+010A|*|`&Cdot;`|`&#0266;`<br>`&#x010A;`|Latin capital letter c with dot above|
|0267<br>U+010B|+|`&cdot;`|`&#0267;`<br>`&#x010B;`|Latin small letter c with dot above|
|0268<br>U+010C|,|`&Ccaron;`|`&#0268;`<br>`&#x010C;`|Latin capital letter c with caron|
|0269<br>U+010D|–|`&ccaron;`|`&#0269;`<br>`&#x010D;`|Latin small letter c with caron|
|0270<br>U+010E|.|`&Dcaron;`|`&#0270;`<br>`&#x010E;`|Latin capital letter d with caron|
|0271<br>U+010F|/|`&dcaron;`|`&#0271;`<br>`&#x010F;`|Latin small letter d with caron|
|0272<br>U+0110|0|`&Dstrok;`|`&#0272;`<br>`&#x0110;`|Latin capital letter d with stroke|
|0273<br>U+0111|1|`&dstrok;`|`&#0273;`<br>`&#x0111;`|Latin small letter d with stroke|
|0274<br>U+0112|2|`&Emacr;`|`&#0274;`<br>`&#x0112;`|Latin capital letter e with macron|
|0275<br>U+0113|3|`&emacr;`|`&#0275;`<br>`&#x0113;`|Latin small letter e with macron|
|0276<br>U+0114|4|`&Ebreve;`|`&#0276;`<br>`&#x0114;`|Latin capital letter e with breve|
|0277<br>U+0115|5|`&ebreve;`|`&#0277;`<br>`&#x0115;`|Latin small letter e with breve|
|0278<br>U+0116|6|`&Edot;`|`&#0278;`<br>`&#x0116;`|Latin capital letter e with dot above|
|0279<br>U+0117|7|`&edot;`|`&#0279;`<br>`&#x0117;`|Latin small letter e with dot above|
|0280<br>U+0118|8|`&Eogon;`|`&#0280;`<br>`&#x0118;`|Latin capital letter e with ogonek|
|0281<br>U+0119|9|`&eogon;`|`&#0281;`<br>`&#x0119;`|Latin small letter e with ogonek|
|0282<br>U+011A|:|`&Ecaron;`|`&#0282;`<br>`&#x011A;`|Latin capital letter e with caron|
|0283<br>U+011B|;|`&ecaron;`|`&#0283;`<br>`&#x011B;`|Latin small letter e with caron|
|0284<br>U+011C|<|`&Gcirc;`|`&#0284;`<br>`&#x011C;`|Latin capital letter g with circumflex|
|0285<br>U+011D|=|`&gcirc;`|`&#0285;`<br>`&#x011D;`|Latin small letter g with circumflex|
|0286<br>U+011E|>|`&Gbreve;`|`&#0286;`<br>`&#x011E;`|Latin capital letter g with breve|
|0287<br>U+011F|?|`&gbreve;`|`&#0287;`<br>`&#x011F;`|Latin small letter g with breve|
|0288<br>U+0120|@|`&Gdot;`|`&#0288;`<br>`&#x0120;`|Latin capital letter g with dot above|
|0289<br>U+0121|A|`&gdot;`|`&#0289;`<br>`&#x0121;`|Latin small letter g with dot above|
|0290<br>U+0122|B|`&Gcedil;`|`&#0290;`<br>`&#x0122;`|Latin capital letter g with cedilla|
|0291<br>U+0123|C|`&gcedil;`|`&#0291;`<br>`&#x0123;`|Latin small letter g with cedilla|
|0292<br>U+0124|D|`&Hcirc;`|`&#0292;`<br>`&#x0124;`|Latin capital letter h with circumflex|
|0293<br>U+0125|E|`&hcirc;`|`&#0293;`<br>`&#x0125;`|Latin small letter h with circumflex|
|0294<br>U+0126|F|`&Hstrok;`|`&#0294;`<br>`&#x0126;`|Latin capital letter h with stroke|
|0295<br>U+0127|G|`&hstrok;`|`&#0295;`<br>`&#x0127;`|Latin small letter h with stroke|
|0296<br>U+0128|H|`&Itilde;`|`&#0296;`<br>`&#x0128;`|Latin capital letter I with tilde|
|0297<br>U+0129|I|`&itilde;`|`&#0297;`<br>`&#x0129;`|Latin small letter I with tilde|
|0298<br>U+012A|J|`&Imacr;`|`&#0298;`<br>`&#x012A;`|Latin capital letter I with macron|
|0299<br>U+012B|K|`&imacr;`|`&#0299;`<br>`&#x012B;`|Latin small letter I with macron|
|0300<br>U+012C|L|`&Ibreve;`|`&#0300;`<br>`&#x012C;`|Latin capital letter I with breve|
|0301<br>U+012D|M|`&ibreve;`|`&#0301;`<br>`&#x012D;`|Latin small letter I with breve|
|0302<br>U+012E|N|`&Iogon;`|`&#0302;`<br>`&#x012E;`|Latin capital letter I with ogonek|
|0303<br>U+012F|O|`&iogon;`|`&#0303;`<br>`&#x012F;`|Latin small letter I with ogonek|
|0304<br>U+0130|P|`&Idot;`|`&#0304;`<br>`&#x0130;`|Latin capital letter I with dot above|
|0305<br>U+0131|Q|`&imath; &inodot;`|`&#0305;`<br>`&#x0131;`|Latin small letter dotless I|
|0306<br>U+0132|R|`&IJlig;`|`&#0306;`<br>`&#x0132;`|Latin capital ligature ij|
|0307<br>U+0133|S|`&ijlig;`|`&#0307;`<br>`&#x0133;`|Latin small ligature ij|
|0308<br>U+0134|T|`&Jcirc;`|`&#0308;`<br>`&#x0134;`|Latin capital letter j with circumflex|
|0309<br>U+0135|U|`&jcirc;`|`&#0309;`<br>`&#x0135;`|Latin small letter j with circumflex|
|0310<br>U+0136|V|`&Kcedil;`|`&#0310;`<br>`&#x0136;`|Latin capital letter k with cedilla|
|0311<br>U+0137|W|`&kcedil;`|`&#0311;`<br>`&#x0137;`|Latin small letter k with cedilla|
|0312<br>U+0138|X|`&kgreen;`|`&#0312;`<br>`&#x0138;`|Latin small letter kra|
|0313<br>U+0139|Y|`&Lacute;`|`&#0313;`<br>`&#x0139;`|Latin capital letter l with acute|
|0314<br>U+013A|Z|`&lacute;`|`&#0314;`<br>`&#x013A;`|Latin small letter l with acute|
|0315<br>U+013B|[|`&Lcedil;`|`&#0315;`<br>`&#x013B;`|Latin capital letter l with cedilla|
|0316<br>U+013C|&#0316;|`&lcedil;`|`&#0316;`<br>`&#x013C;`|Latin small letter l with cedilla|
|0317<br>U+013D|]|`&Lcaron;`|`&#0317;`<br>`&#x013D;`|Latin capital letter l with caron|
|0318<br>U+013E|^|`&lcaron;`|`&#0318;`<br>`&#x013E;`|Latin small letter l with caron|
|0319<br>U+013F|_|`&Lmidot;`|`&#0319;`<br>`&#x013F;`|Latin capital letter l with middle dot|
|0320<br>U+0140|`|`&lmidot;`|`&#0320;`<br>`&#x0140;`|Latin small letter l with middle dot|
|0321<br>U+0141|a|`&Lstrok;`|`&#0321;`<br>`&#x0141;`|Latin capital letter l with stroke|
|0322<br>U+0142|b|`&lstrok;`|`&#0322;`<br>`&#x0142;`|Latin small letter l with stroke|
|0323<br>U+0143|c|`&Nacute;`|`&#0323;`<br>`&#x0143;`|Latin capital letter n with acute|
|0324<br>U+0144|d|`&nacute;`|`&#0324;`<br>`&#x0144;`|Latin small letter n with acute|
|0325<br>U+0145|e|`&Ncedil;`|`&#0325;`<br>`&#x0145;`|Latin capital letter n with cedilla|
|0326<br>U+0146|f|`&ncedil;`|`&#0326;`<br>`&#x0146;`|Latin small letter n with cedilla|
|0327<br>U+0147|g|`&Ncaron;`|`&#0327;`<br>`&#x0147;`|Latin capital letter n with caron|
|0328<br>U+0148|h|`&ncaron;`|`&#0328;`<br>`&#x0148;`|Latin small letter n with caron|
|0329<br>U+0149|i|`&napos;`|`&#0329;`<br>`&#x0149;`|Latin small letter n preceded by apostrophe|
|0330<br>U+014A|j|`&ENG;`|`&#0330;`<br>`&#x014A;`|Latin capital letter eng|
|0331<br>U+014B|k|`&eng;`|`&#0331;`<br>`&#x014B;`|Latin small letter eng|
|0332<br>U+014C|l|`&Omacr;`|`&#0332;`<br>`&#x014C;`|Latin capital letter o with macron|
|0333<br>U+014D|m|`&omacr;`|`&#0333;`<br>`&#x014D;`|Latin small letter o with macron|
|0334<br>U+014E|n|`&Obreve;`|`&#0334;`<br>`&#x014E;`|Latin capital letter o with breve|
|0335<br>U+014F|o|`&obreve;`|`&#0335;`<br>`&#x014F;`|Latin small letter o with breve|
|0336<br>U+0150|p|`&Odblac;`|`&#0336;`<br>`&#x0150;`|Latin capital letter o with double acute|
|0337<br>U+0151|q|`&odblac;`|`&#0337;`<br>`&#x0151;`|Latin small letter o with double acute|
|0340<br>U+0154|r|`&Racute;`|`&#0340;`<br>`&#x0154;`|Latin capital letter r with acute|
|0341<br>U+0155|s|`&racute;`|`&#0341;`<br>`&#x0155;`|Latin small letter r with acute|
|0342<br>U+0156|t|`&Rcedil;`|`&#0342;`<br>`&#x0156;`|Latin capital letter r with cedilla|
|0343<br>U+0157|u|`&rcedil;`|`&#0343;`<br>`&#x0157;`|Latin small letter r with cedilla|
|0344<br>U+0158|v|`&Rcaron;`|`&#0344;`<br>`&#x0158;`|Latin capital letter r with caron|
|0345<br>U+0159|w|`&rcaron;`|`&#0345;`<br>`&#x0159;`|Latin small letter r with caron|
|0346<br>U+015A|x|`&Sacute;`|`&#0346;`<br>`&#x015A;`|Latin capital letter s with acute|
|0347<br>U+015B|y|`&sacute;`|`&#0347;`<br>`&#x015B;`|Latin small letter s with acute|
|0348<br>U+015C|z|`&Scirc;`|`&#0348;`<br>`&#x015C;`|Latin capital letter s with circumflex|
|0349<br>U+015D|{|`&scirc;`|`&#0349;`<br>`&#x015D;`|Latin small letter s with circumflex|
|0350<br>U+015E|&#0350;|`&Scedil;`|`&#0350;`<br>`&#x015E;`|Latin capital letter s with cedilla|
|0351<br>U+015F|}|`&scedil;`|`&#0351;`<br>`&#x015F;`|Latin small letter s with cedilla|
|0354<br>U+0162|~|`&Tcedil;`|`&#0354;`<br>`&#x0162;`|Latin capital letter t with cedilla|
|0355<br>U+0163|€|`&tcedil;`|`&#0355;`<br>`&#x0163;`|Latin small letter t with cedilla|
|0356<br>U+0164|‚|`&Tcaron;`|`&#0356;`<br>`&#x0164;`|Latin capital letter t with caron|
|0357<br>U+0165|ƒ|`&tcaron;`|`&#0357;`<br>`&#x0165;`|Latin small letter t with caron|
|0358<br>U+0166|„|`&Tstrok;`|`&#0358;`<br>`&#x0166;`|Latin capital letter t with stroke|
|0359<br>U+0167|…|`&tstrok;`|`&#0359;`<br>`&#x0167;`|Latin small letter t with stroke|
|0360<br>U+0168|†|`&Utilde;`|`&#0360;`<br>`&#x0168;`|Latin capital letter u with tilde|
|0361<br>U+0169|‡|`&utilde;`|`&#0361;`<br>`&#x0169;`|Latin small letter u with tilde|
|0362<br>U+016A|ˆ|`&Umacr;`|`&#0362;`<br>`&#x016A;`|Latin capital letter u with macron|
|0363<br>U+016B|‰|`&umacr;`|`&#0363;`<br>`&#x016B;`|Latin small letter u with macron|
|0364<br>U+016C|Š|`&Ubreve;`|`&#0364;`<br>`&#x016C;`|Latin capital letter u with breve|
|0365<br>U+016D|‹|`&ubreve;`|`&#0365;`<br>`&#x016D;`|Latin small letter u with breve|
|0366<br>U+016E|Œ|`&Uring;`|`&#0366;`<br>`&#x016E;`|Latin capital letter u with ring above|
|0367<br>U+016F|Ž|`&uring;`|`&#0367;`<br>`&#x016F;`|Latin small letter u with ring above|
|0368<br>U+0170|‘|`&Udblac;`|`&#0368;`<br>`&#x0170;`|Latin capital letter u with double acute|
|0369<br>U+0171|’|`&udblac;`|`&#0369;`<br>`&#x0171;`|Latin small letter u with double acute|
|0370<br>U+0172|“|`&Uogon;`|`&#0370;`<br>`&#x0172;`|Latin capital letter u with ogonek|
|0371<br>U+0173|”|`&uogon;`|`&#0371;`<br>`&#x0173;`|Latin small letter u with ogonek|
|0372<br>U+0174|•|`&Wcirc;`|`&#0372;`<br>`&#x0174;`|Latin capital letter w with circumflex|
|0373<br>U+0175|–|`&wcirc;`|`&#0373;`<br>`&#x0175;`|Latin small letter w with circumflex|
|0374<br>U+0176|—|`&Ycirc;`|`&#0374;`<br>`&#x0176;`|Latin capital letter y with circumflex|
|0375<br>U+0177|˜|`&ycirc;`|`&#0375;`<br>`&#x0177;`|Latin small letter y with circumflex|
|8196<br>U+2004|™|`&emsp13;`|`&#8196;`<br>`&#x2004;`|1/3 of an em space (between blocks)|
|8197<br>U+2005|š|`&emsp14;`|`&#8197;`<br>`&#x2005;`|1/4 of an em space (between blocks)|
|8199<br>U+2007|›|`&numsp;`|`&#8199;`<br>`&#x2007;`|Number space (between blocks)|
|8200<br>U+2008|œ|`&puncsp;`|`&#8200;`<br>`&#x2008;`|Punctuation space (between blocks)|
|8202<br>U+200A|ž|`&hairsp;`|`&#8202;`<br>`&#x200A;`|Hair space (between blocks)|
|8208<br>U+2010|Ÿ|`&dash;`|`&#8208;`<br>`&#x2010;`|Hyphen (true graphic)|
|8213<br>U+2015|█ █|`&horbar;`|`&#8213;`<br>`&#x2015;`|Horizontal bar|
|8214<br>U+2016|¡|`&verbar;`|`&#8214;`<br>`&#x2016;`|Double vertical bar|
|8229<br>U+2025|¢|`&nldr;`|`&#8229;`<br>`&#x2025;`|Double baseline dot|
|8244<br>U+2034|£|`&tprime;`|`&#8244;`<br>`&#x2034;`|Triple prime|
|8245<br>U+2035|¤|`&bprime;`|`&#8245;`<br>`&#x2035;`|Backprime|
|8257<br>U+2041|¥|`&caret;`|`&#8257;`<br>`&#x2041;`|Caret (insertion mark)|
|8259<br>U+2043|¦|`&hybull;`|`&#8259;`<br>`&#x2043;`|Filled rectangle|
|8411<br>U+20DB|§|`&tdot;`|`&#8411;`<br>`&#x20DB;`|Three dots above|
|8412<br>U+20DC|¨|`&DotDot;`|`&#8412;`<br>`&#x20DC;`|Four dots above|
|8453<br>U+2105|©|`&incare;`|`&#8453;`<br>`&#x2105;`|In-care-of symbol|
|8459<br>U+210B|ª|`&hamilt;`|`&#8459;`<br>`&#x210B;`|Script capital H|
|8463<br>U+210F|«|`&planck;`|`&#8463;`<br>`&#x210F;`|Planck's over 2pi|
|8466<br>U+2112|¬|`&lagran;`|`&#8466;`<br>`&#x2112;`|Script capital L|
|8467<br>U+2113|¬Soft hyphen|`&ell;`|`&#8467;`<br>`&#x2113;`|Cursive small l|
|8470<br>U+2116|®|`&numero;`|`&#8470;`<br>`&#x2116;`|Numero sign|
|8471<br>U+2117|¯|`&copysr;`|`&#8471;`<br>`&#x2117;`|Sound recording copyright|
|8486<br>U+2126|°|`&ohm;`|`&#8486;`<br>`&#x2126;`|Ohm sign|
|8491<br>U+212B|±|`&angst;`|`&#8491;`<br>`&#x212B;`|Angstrom|
|8492<br>U+212C|²|`&bernou;`|`&#8492;`<br>`&#x212C;`|Script capital B|
|8499<br>U+2133|³|`&phmmat;`|`&#8499;`<br>`&#x2133;`|Script capital M|
|8500<br>U+2134|´|`&order;`|`&#8500;`<br>`&#x2134;`|Script small o|
|8501<br>U+2135|µ|`&aleph;`|`&#8501;`<br>`&#x2135;`|Aleph, Hebrew|
|8502<br>U+2136|¶|`&beth;`|`&#8502;`<br>`&#x2136;`|Beth, Hebrew|
|8503<br>U+2137|·|`&gimel;`|`&#8503;`<br>`&#x2137;`|Gimel, Hebrew|
|8504<br>U+2138|¸|`&daleth;`|`&#8504;`<br>`&#x2138;`|Daleth, Hebrew|
|8531<br>U+2153|¹|`&frac13;`|`&#8531;`<br>`&#x2153;`|Fraction one-third|
|8532<br>U+2154|º|`&frac23;`|`&#8532;`<br>`&#x2154;`|Fraction two-thirds|
|8533<br>U+2155|»|`&frac15;`|`&#8533;`<br>`&#x2155;`|Fraction one-fifth|
|8534<br>U+2156|¼|`&frac25;`|`&#8534;`<br>`&#x2156;`|Fraction two-fifths|
|8535<br>U+2157|½|`&frac35;`|`&#8535;`<br>`&#x2157;`|Fraction three-fifths|
|8536<br>U+2158|¾|`&frac45;`|`&#8536;`<br>`&#x2158;`|Fraction four-fifths|
|8537<br>U+2159|¿|`&frac16;`|`&#8537;`<br>`&#x2159;`|Fraction one-sixth|
|8538<br>U+215A|À|`&frac56;`|`&#8538;`<br>`&#x215A;`|Fraction five-sixths|
|8539<br>U+215B|Á|`&frac18;`|`&#8539;`<br>`&#x215B;`|Fraction one-eighth|
|8540<br>U+215C|Â|`&frac38;`|`&#8540;`<br>`&#x215C;`|Fraction three-eighths|
|8541<br>U+215D|Ã|`&frac58;`|`&#8541;`<br>`&#x215D;`|Fraction five-eighths|
|8542<br>U+215E|Ä|`&frac78;`|`&#8542;`<br>`&#x215E;`|Fraction seven-eighths|
|8597<br>U+2195|Å|`&varr;`|`&#8597;`<br>`&#x2195;`|Up & down arrow|
|8598<br>U+2196|Æ|`&nwarr;`|`&#8598;`<br>`&#x2196;`|NW pointing arrow|
|8599<br>U+2197|Ç|`&nearr;`|`&#8599;`<br>`&#x2197;`|NE pointing arrow|
|8600<br>U+2198|È|`&searr;`|`&#8600;`<br>`&#x2198;`|SE pointing arrow|
|8601<br>U+2199|É|`&swarr;`|`&#8601;`<br>`&#x2199;`|SW pointing arrow|
|8602<br>U+219A|Ê|`&nlarr;`|`&#8602;`<br>`&#x219A;`|Not left arrow|
|8603<br>U+219B|Ë|`&nrarr;`|`&#8603;`<br>`&#x219B;`|Not right arrow|
|0009<br>U+0009|Ì|`&Tab;`|`&#0009;`<br>`&#x0009;`|Tab|
|0010<br>U+000A|Í|`&NewLine;`|`&#0010;`<br>`&#x000A;`|New Line|
|0256<br>U+0100|Î|`&Amacr;`|`&#0256;`<br>`&#x0100;`|Latin capital letter a with macron|
|0257<br>U+0101|Ï|`&amacr;`|`&#0257;`<br>`&#x0101;`|Latin small letter a with macron|
|0258<br>U+0102|Ð|`&Abreve;`|`&#0258;`<br>`&#x0102;`|Latin capital letter a with breve|
|0259<br>U+0103|Ñ|`&abreve;`|`&#0259;`<br>`&#x0103;`|Latin small letter a with breve|
|0260<br>U+0104|Ò|`&Aogon;`|`&#0260;`<br>`&#x0104;`|Latin capital letter a with ogonek|
|0261<br>U+0105|Ó|`&aogon;`|`&#0261;`<br>`&#x0105;`|Latin small letter a with ogonek|
|0262<br>U+0106|Ô|`&Cacute;`|`&#0262;`<br>`&#x0106;`|Latin capital letter c with acute|
|0263<br>U+0107|Õ|`&cacute;`|`&#0263;`<br>`&#x0107;`|Latin small letter c with acute|
|0264<br>U+0108|Ö|`&Ccirc;`|`&#0264;`<br>`&#x0108;`|Latin capital letter c with circumflex|
|0265<br>U+0109|×|`&ccirc;`|`&#0265;`<br>`&#x0109;`|Latin small letter c with circumflex|



<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->
