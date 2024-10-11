## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[9] KodeMono[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The OpenType spec recommends at <a href="https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table">https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table</a> that hhea.numberOfHMetrics be set to 3 but this font has 467 instead.
Please read <a href="https://github.com/fonttools/fonttools/issues/3014">https://github.com/fonttools/fonttools/issues/3014</a> to decide whether this makes sense for your font.</p>
 [code: bad-numberOfHMetrics]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- at.001

- nobreakspace
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: math, glagolitic, elbasan, gothic, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, hebrew, math, tai-le, syriac, malayalam, todhri, old-permic, tifinagh, coptic, duployan</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar</li>
<li>U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: try adding ethiopic</li>
<li>U+0310 COMBINING CANDRABINDU: try adding one of: sunuwar, math</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: todhri, old-permic</li>
<li>U+0314 COMBINING REVERSED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0316 COMBINING GRAVE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0317 COMBINING ACUTE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac, duployan</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, syriac, thai, sunuwar, gothic, tifinagh, caucasian-albanian</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math</li>
<li>U+2017 DOUBLE LOW LINE: try adding math</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+203E OVERLINE: not included in any glyphset definition</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+215F FRACTION NUMERATOR ONE: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols</li>
<li>U+2195 UP DOWN ARROW: try adding one of: math, symbols</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: math, symbols</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: math, symbols</li>
<li>U+2200 FOR ALL: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+24C0 CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+2500 BOX DRAWINGS LIGHT HORIZONTAL: try adding symbols2</li>
<li>U+2502 BOX DRAWINGS LIGHT VERTICAL: try adding symbols2</li>
<li>U+250C BOX DRAWINGS LIGHT DOWN AND RIGHT: try adding symbols2</li>
<li>U+2510 BOX DRAWINGS LIGHT DOWN AND LEFT: try adding symbols2</li>
<li>U+2514 BOX DRAWINGS LIGHT UP AND RIGHT: try adding symbols2</li>
<li>U+2518 BOX DRAWINGS LIGHT UP AND LEFT: try adding symbols2</li>
<li>U+251C BOX DRAWINGS LIGHT VERTICAL AND RIGHT: try adding symbols2</li>
<li>U+2524 BOX DRAWINGS LIGHT VERTICAL AND LEFT: try adding symbols2</li>
<li>U+252C BOX DRAWINGS LIGHT DOWN AND HORIZONTAL: try adding symbols2</li>
<li>U+2534 BOX DRAWINGS LIGHT UP AND HORIZONTAL: try adding symbols2</li>
<li>U+253C BOX DRAWINGS LIGHT VERTICAL AND HORIZONTAL: try adding symbols2</li>
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: psalter-pahlavi, music, thaana, tamil, caucasian-albanian, oriya, tai-tham, tagalog, symbols, elbasan, bassa-vah, armenian, kharoshthi, hanifi-rohingya, nko, hebrew, balinese, marchen, grantha, soyombo, zanabazar-square, kayah-li, masaram-gondi, duployan, math, tai-viet, malayalam, telugu, tagbanwa, wancho, mongolian, rejang, mandaic, tibetan, sundanese, yi, mende-kikakui, adlam, meetei-mayek, lao, tai-le, mahajani, takri, bhaiksuki, myanmar, old-permic, tifinagh, gujarati, kaithi, syriac, new-tai-lue, buhid, cham, warang-citi, chakma, phags-pa, siddham, sogdian, devanagari, bengali, osage, miao, canadian-aboriginal, thai, limbu, lepcha, kannada, gurmukhi, brahmi, manichaean, hanunoo, ahom, khojki, tirhuta, gunjala-gondi, batak, buginese, dogra, pahawh-hmong, khmer, khudawadi, sharada, sinhala, javanese, coptic, newa, saurashtra, modi, syloti-nagri</li>
<li>U+EE00 : not included in any glyphset definition</li>
<li>U+EE01 : not included in any glyphset definition</li>
<li>U+EE02 : not included in any glyphset definition</li>
<li>U+EE03 : not included in any glyphset definition</li>
<li>U+EE04 : not included in any glyphset definition</li>
<li>U+EE05 : not included in any glyphset definition</li>
<li>U+FFFFF : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Aogonek (U+0104): X=520.0,Y=1.0 (should be at baseline 0?)

* seveneighths (U+215E): X=300.0,Y=701.0 (should be at cap-height 700?)

* hyphen_greater.liga: X=52.0,Y=-2.0 (should be at baseline 0?)

* ampersand_ampersand.liga: X=-309.0,Y=701.0 (should be at cap-height 700?)

* ampersand_ampersand.liga: X=301.0,Y=701.0 (should be at cap-height 700?)

* ampersand_ampersand.liga: X=82.0,Y=701.0 (should be at cap-height 700?)

* ampersand_ampersand.liga: X=-89.0,Y=701.0 (should be at cap-height 700?)

* equal_greater.liga: X=82.0,Y=-1.0 (should be at baseline 0?)

* equal_greater_equal.liga: X=-369.0,Y=-1.0 (should be at baseline 0?)

* equal_less_equal.liga: X=-231.0,Y=-1.0 (should be at baseline 0?)

* less_hyphen.liga: X=-52.0,Y=-2.0 (should be at baseline 0?)

* less_equal.liga: X=-82.0,Y=-1.0 (should be at baseline 0?)

* uni25CC (U+25CC): X=532.0,Y=701.0 (should be at cap-height 700?)

* uni25CC (U+25CC): X=68.0,Y=1.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* .notdef has a counter-clockwise outer contour

* .notdef has a counter-clockwise outer contour

* .notdef has a counter-clockwise outer contour

* .notdef has a counter-clockwise outer contour

* .notdef has a counter-clockwise outer contour

* .notdef has a counter-clockwise outer contour

* .notdef has a counter-clockwise outer contour

* .notdef has a counter-clockwise outer contour

* A (U+0041) has a counter-clockwise outer contour

* AE (U+00C6) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Aacute (U+00C1) has a counter-clockwise outer contour

* Abreve (U+0102) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Acircumflex (U+00C2) has a counter-clockwise outer contour

* Adieresis (U+00C4) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Agrave (U+00C0) has a counter-clockwise outer contour

* Amacron (U+0100) has a counter-clockwise outer contour

* Aogonek (U+0104) has a counter-clockwise outer contour

* Aogonek (U+0104) has a counter-clockwise outer contour

* Aring (U+00C5) has a counter-clockwise outer contour

* Aring (U+00C5) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* Atilde (U+00C3) has a counter-clockwise outer contour

* B (U+0042) has a counter-clockwise outer contour

* Cacute (U+0106) has a counter-clockwise outer contour

* Ccaron (U+010C) has a counter-clockwise outer contour

* Dcaron (U+010E) has a counter-clockwise outer contour

* E (U+0045) has a counter-clockwise outer contour

* Eacute (U+00C9) has a counter-clockwise outer contour

* Eacute (U+00C9) has a counter-clockwise outer contour

* Ecaron (U+011A) has a counter-clockwise outer contour

* Ecaron (U+011A) has a counter-clockwise outer contour

* Ecircumflex (U+00CA) has a counter-clockwise outer contour

* Ecircumflex (U+00CA) has a counter-clockwise outer contour

* Edieresis (U+00CB) has a counter-clockwise outer contour

* Edotaccent (U+0116) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Egrave (U+00C8) has a counter-clockwise outer contour

* Emacron (U+0112) has a counter-clockwise outer contour

* Eogonek (U+0118) has a counter-clockwise outer contour

* Eogonek (U+0118) has a counter-clockwise outer contour

* Euro (U+20AC) has a counter-clockwise outer contour

* F (U+0046) has a counter-clockwise outer contour

* G (U+0047) has a counter-clockwise outer contour

* Gbreve (U+011E) has a counter-clockwise outer contour

* Gdotaccent (U+0120) has a counter-clockwise outer contour

* I (U+0049) has a counter-clockwise outer contour

* IJ (U+0132) has a counter-clockwise outer contour

* Iacute (U+00CD) has a counter-clockwise outer contour

* Iacute (U+00CD) has a counter-clockwise outer contour

* Icircumflex (U+00CE) has a counter-clockwise outer contour

* Icircumflex (U+00CE) has a counter-clockwise outer contour

* Idieresis (U+00CF) has a counter-clockwise outer contour

* Idotaccent (U+0130) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* Igrave (U+00CC) has a counter-clockwise outer contour

* Imacron (U+012A) has a counter-clockwise outer contour

* Iogonek (U+012E) has a counter-clockwise outer contour

* Iogonek (U+012E) has a counter-clockwise outer contour

* J (U+004A) has a counter-clockwise outer contour

* K (U+004B) has a counter-clockwise outer contour

* L (U+004C) has a counter-clockwise outer contour

* Lacute (U+0139) has a counter-clockwise outer contour

* Lacute (U+0139) has a counter-clockwise outer contour

* Lcaron (U+013D) has a counter-clockwise outer contour

* Lslash (U+0141) has a counter-clockwise outer contour

* Lslash (U+0141) has a counter-clockwise outer contour

* M (U+004D) has a counter-clockwise outer contour

* N (U+004E) has a counter-clockwise outer contour

* Nacute (U+0143) has a counter-clockwise outer contour

* Nacute (U+0143) has a counter-clockwise outer contour

* Ncaron (U+0147) has a counter-clockwise outer contour

* Ncaron (U+0147) has a counter-clockwise outer contour

* Ntilde (U+00D1) has a counter-clockwise outer contour

* Ntilde (U+00D1) has a counter-clockwise outer contour

* OE (U+0152) has a counter-clockwise outer contour

* Oacute (U+00D3) has a counter-clockwise outer contour

* Ocircumflex (U+00D4) has a counter-clockwise outer contour

* Ograve (U+00D2) has a counter-clockwise outer contour

* Ohungarumlaut (U+0150) has a counter-clockwise outer contour

* Ohungarumlaut (U+0150) has a counter-clockwise outer contour

* Otilde (U+00D5) has a counter-clockwise outer contour

* P (U+0050) has a counter-clockwise outer contour

* Q (U+0051) has a counter-clockwise outer contour

* R (U+0052) has a counter-clockwise outer contour

* Racute (U+0154) has a counter-clockwise outer contour

* Racute (U+0154) has a counter-clockwise outer contour

* Rcaron (U+0158) has a counter-clockwise outer contour

* Rcaron (U+0158) has a counter-clockwise outer contour

* Sacute (U+015A) has a counter-clockwise outer contour

* Scaron (U+0160) has a counter-clockwise outer contour

* Tcaron (U+0164) has a counter-clockwise outer contour

* Thorn (U+00DE) has a counter-clockwise outer contour

* U (U+0055) has a counter-clockwise outer contour

* Uacute (U+00DA) has a counter-clockwise outer contour

* Uacute (U+00DA) has a counter-clockwise outer contour

* Ucircumflex (U+00DB) has a counter-clockwise outer contour

* Ucircumflex (U+00DB) has a counter-clockwise outer contour

* Udieresis (U+00DC) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* Ugrave (U+00D9) has a counter-clockwise outer contour

* Uhungarumlaut (U+0170) has a counter-clockwise outer contour

* Uhungarumlaut (U+0170) has a counter-clockwise outer contour

* Uhungarumlaut (U+0170) has a counter-clockwise outer contour

* Umacron (U+016A) has a counter-clockwise outer contour

* Uogonek (U+0172) has a counter-clockwise outer contour

* Uogonek (U+0172) has a counter-clockwise outer contour

* Uring (U+016E) has a counter-clockwise outer contour

* Uring (U+016E) has a counter-clockwise outer contour

* V (U+0056) has a counter-clockwise outer contour

* W (U+0057) has a counter-clockwise outer contour

* Wacute (U+1E82) has a counter-clockwise outer contour

* Wacute (U+1E82) has a counter-clockwise outer contour

* Wcircumflex (U+0174) has a counter-clockwise outer contour

* Wcircumflex (U+0174) has a counter-clockwise outer contour

* Wdieresis (U+1E84) has a counter-clockwise outer contour

* Wgrave (U+1E80) has a counter-clockwise outer contour

* Wgrave (U+1E80) has a counter-clockwise outer contour

* X (U+0058) has a counter-clockwise outer contour

* Yacute (U+00DD) has a counter-clockwise outer contour

* Ycircumflex (U+0176) has a counter-clockwise outer contour

* Ygrave (U+1EF2) has a counter-clockwise outer contour

* Z (U+005A) has a counter-clockwise outer contour

* Zacute (U+0179) has a counter-clockwise outer contour

* Zacute (U+0179) has a counter-clockwise outer contour

* Zcaron (U+017D) has a counter-clockwise outer contour

* Zcaron (U+017D) has a counter-clockwise outer contour

* Zdotaccent (U+017B) has a counter-clockwise outer contour

* a (U+0061) has a counter-clockwise outer contour

* aacute (U+00E1) has a counter-clockwise outer contour

* aacute (U+00E1) has a counter-clockwise outer contour

* abreve (U+0103) has a counter-clockwise outer contour

* acircumflex (U+00E2) has a counter-clockwise outer contour

* acircumflex (U+00E2) has a counter-clockwise outer contour

* acute (U+00B4) has a counter-clockwise outer contour

* acutecomb (U+0301) has a counter-clockwise outer contour

* adieresis (U+00E4) has a counter-clockwise outer contour

* ae (U+00E6) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* agrave (U+00E0) has a counter-clockwise outer contour

* amacron (U+0101) has a counter-clockwise outer contour

* ampersand (U+0026) has a counter-clockwise outer contour

* ampersand_ampersand.liga has a counter-clockwise outer contour

* aogonek (U+0105) has a counter-clockwise outer contour

* aogonek (U+0105) has a counter-clockwise outer contour

* aring (U+00E5) has a counter-clockwise outer contour

* aring (U+00E5) has a counter-clockwise outer contour

* asciicircum (U+005E) has a counter-clockwise outer contour

* asciitilde (U+007E) has a counter-clockwise outer contour

* asterisk (U+002A) has a counter-clockwise outer contour

* asterisk_asterisk.liga has a counter-clockwise outer contour

* asterisk_asterisk.liga has a counter-clockwise outer contour

* asterisk_slash.liga has a counter-clockwise outer contour

* at (U+0040) has a counter-clockwise outer contour

* at.001 has a counter-clockwise outer contour

* atilde (U+00E3) has a counter-clockwise outer contour

* atilde (U+00E3) has a counter-clockwise outer contour

* b (U+0062) has a counter-clockwise outer contour

* braceleft (U+007B) has a counter-clockwise outer contour

* braceright (U+007D) has a counter-clockwise outer contour

* bracketleft (U+005B) has a counter-clockwise outer contour

* bracketright (U+005D) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* brokenbar (U+00A6) has a counter-clockwise outer contour

* bullet (U+2022) has a counter-clockwise outer contour

* cacute (U+0107) has a counter-clockwise outer contour

* caron (U+02C7) has a counter-clockwise outer contour

* ccaron (U+010D) has a counter-clockwise outer contour

* cent (U+00A2) has a counter-clockwise outer contour

* circumflex (U+02C6) has a counter-clockwise outer contour

* comma (U+002C) has a counter-clockwise outer contour

* copyright (U+00A9) has a counter-clockwise outer contour

* currency (U+00A4) has a counter-clockwise outer contour

* degree (U+00B0) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* divide (U+00F7) has a counter-clockwise outer contour

* dollar (U+0024) has a counter-clockwise outer contour

* dollar_greater.liga has a counter-clockwise outer contour

* dotlessi (U+0131) has a counter-clockwise outer contour

* e (U+0065) has a counter-clockwise outer contour

* eacute (U+00E9) has a counter-clockwise outer contour

* eacute (U+00E9) has a counter-clockwise outer contour

* ecaron (U+011B) has a counter-clockwise outer contour

* ecaron (U+011B) has a counter-clockwise outer contour

* ecircumflex (U+00EA) has a counter-clockwise outer contour

* ecircumflex (U+00EA) has a counter-clockwise outer contour

* edieresis (U+00EB) has a counter-clockwise outer contour

* edotaccent (U+0117) has a counter-clockwise outer contour

* egrave (U+00E8) has a counter-clockwise outer contour

* egrave (U+00E8) has a counter-clockwise outer contour

* eight (U+0038) has a counter-clockwise outer contour

* eight.dnom has a counter-clockwise outer contour

* eight.numr has a counter-clockwise outer contour

* emacron (U+0113) has a counter-clockwise outer contour

* eogonek (U+0119) has a counter-clockwise outer contour

* eogonek (U+0119) has a counter-clockwise outer contour

* eth (U+00F0) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* f (U+0066) has a counter-clockwise outer contour

* five (U+0035) has a counter-clockwise outer contour

* five.dnom has a counter-clockwise outer contour

* five.numr has a counter-clockwise outer contour

* fiveeighths (U+215D) has a counter-clockwise outer contour

* fiveeighths (U+215D) has a counter-clockwise outer contour

* fiveeighths (U+215D) has a counter-clockwise outer contour

* four (U+0034) has a counter-clockwise outer contour

* four.dnom has a counter-clockwise outer contour

* four.numr has a counter-clockwise outer contour

* fraction (U+2044) has a counter-clockwise outer contour

* g (U+0067) has a counter-clockwise outer contour

* gbreve (U+011F) has a counter-clockwise outer contour

* gdotaccent (U+0121) has a counter-clockwise outer contour

* germandbls (U+00DF) has a counter-clockwise outer contour

* grave (U+0060) has a counter-clockwise outer contour

* gravecomb (U+0300) has a counter-clockwise outer contour

* greaterequal (U+2265) has a counter-clockwise outer contour

* greaterequal (U+2265) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guilsinglleft (U+2039) has a counter-clockwise outer contour

* guilsinglright (U+203A) has a counter-clockwise outer contour

* hungarumlaut (U+02DD) has a counter-clockwise outer contour

* hungarumlaut (U+02DD) has a counter-clockwise outer contour

* i (U+0069) has a counter-clockwise outer contour

* i.loclTRK has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* iacute (U+00ED) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* icircumflex (U+00EE) has a counter-clockwise outer contour

* idieresis (U+00EF) has a counter-clockwise outer contour

* idotlessogonek has a counter-clockwise outer contour

* idotlessogonek has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* igrave (U+00EC) has a counter-clockwise outer contour

* ij (U+0133) has a counter-clockwise outer contour

* ij (U+0133) has a counter-clockwise outer contour

* ij (U+0133) has a counter-clockwise outer contour

* imacron (U+012B) has a counter-clockwise outer contour

* infinity (U+221E) has a counter-clockwise outer contour

* iogonek (U+012F) has a counter-clockwise outer contour

* iogonek (U+012F) has a counter-clockwise outer contour

* k (U+006B) has a counter-clockwise outer contour

* l (U+006C) has a counter-clockwise outer contour

* lacute (U+013A) has a counter-clockwise outer contour

* lacute (U+013A) has a counter-clockwise outer contour

* lcaron (U+013E) has a counter-clockwise outer contour

* less_asterisk_greater.liga has a counter-clockwise outer contour

* less_dollar.liga has a counter-clockwise outer contour

* less_dollar_greater.liga has a counter-clockwise outer contour

* lessequal (U+2264) has a counter-clockwise outer contour

* lessequal (U+2264) has a counter-clockwise outer contour

* logicalnot (U+00AC) has a counter-clockwise outer contour

* lozenge (U+25CA) has a counter-clockwise outer contour

* lslash (U+0142) has a counter-clockwise outer contour

* lslash (U+0142) has a counter-clockwise outer contour

* m (U+006D) has a counter-clockwise outer contour

* minus (U+2212) has a counter-clockwise outer contour

* multiply (U+00D7) has a counter-clockwise outer contour

* n (U+006E) has a counter-clockwise outer contour

* nacute (U+0144) has a counter-clockwise outer contour

* nacute (U+0144) has a counter-clockwise outer contour

* ncaron (U+0148) has a counter-clockwise outer contour

* ncaron (U+0148) has a counter-clockwise outer contour

* nine (U+0039) has a counter-clockwise outer contour

* nine.dnom has a counter-clockwise outer contour

* nine.numr has a counter-clockwise outer contour

* ntilde (U+00F1) has a counter-clockwise outer contour

* ntilde (U+00F1) has a counter-clockwise outer contour

* numbersign (U+0023) has a counter-clockwise outer contour

* o (U+006F) has a counter-clockwise outer contour

* oacute (U+00F3) has a counter-clockwise outer contour

* oacute (U+00F3) has a counter-clockwise outer contour

* ocircumflex (U+00F4) has a counter-clockwise outer contour

* ocircumflex (U+00F4) has a counter-clockwise outer contour

* odieresis (U+00F6) has a counter-clockwise outer contour

* oe (U+0153) has a counter-clockwise outer contour

* ogonek (U+02DB) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* ograve (U+00F2) has a counter-clockwise outer contour

* ohungarumlaut (U+0151) has a counter-clockwise outer contour

* ohungarumlaut (U+0151) has a counter-clockwise outer contour

* ohungarumlaut (U+0151) has a counter-clockwise outer contour

* one (U+0031) has a counter-clockwise outer contour

* one.dnom has a counter-clockwise outer contour

* one.numr has a counter-clockwise outer contour

* oneeighth (U+215B) has a counter-clockwise outer contour

* oneeighth (U+215B) has a counter-clockwise outer contour

* oneeighth (U+215B) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onehalf (U+00BD) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* onequarter (U+00BC) has a counter-clockwise outer contour

* ordfeminine (U+00AA) has a counter-clockwise outer contour

* ordmasculine (U+00BA) has a counter-clockwise outer contour

* oslash (U+00F8) has a counter-clockwise outer contour

* oslash (U+00F8) has a counter-clockwise outer contour

* otilde (U+00F5) has a counter-clockwise outer contour

* otilde (U+00F5) has a counter-clockwise outer contour

* p (U+0070) has a counter-clockwise outer contour

* paragraph (U+00B6) has a counter-clockwise outer contour

* parenleft (U+0028) has a counter-clockwise outer contour

* parenright (U+0029) has a counter-clockwise outer contour

* partialdiff (U+2202) has a counter-clockwise outer contour

* percent (U+0025) has a counter-clockwise outer contour

* perthousand (U+2030) has a counter-clockwise outer contour

* perthousand (U+2030) has a counter-clockwise outer contour

* perthousand (U+2030) has a counter-clockwise outer contour

* perthousand (U+2030) has a counter-clockwise outer contour

* pi (U+03C0) has a counter-clockwise outer contour

* plus (U+002B) has a counter-clockwise outer contour

* plus_plus.liga has a counter-clockwise outer contour

* plus_plus.liga has a counter-clockwise outer contour

* plus_plus_plus.liga has a counter-clockwise outer contour

* plus_plus_plus.liga has a counter-clockwise outer contour

* plus_plus_plus.liga has a counter-clockwise outer contour

* plusminus (U+00B1) has a counter-clockwise outer contour

* plusminus (U+00B1) has a counter-clockwise outer contour

* product (U+220F) has a counter-clockwise outer contour

* q (U+0071) has a counter-clockwise outer contour

* question (U+003F) has a counter-clockwise outer contour

* question (U+003F) has a counter-clockwise outer contour

* question_period.liga has a counter-clockwise outer contour

* question_period.liga has a counter-clockwise outer contour

* questiondown (U+00BF) has a counter-clockwise outer contour

* questiondown (U+00BF) has a counter-clockwise outer contour

* quotedbl (U+0022) has a counter-clockwise outer contour

* quotedbl (U+0022) has a counter-clockwise outer contour

* quotedblbase (U+201E) has a counter-clockwise outer contour

* quotedblbase (U+201E) has a counter-clockwise outer contour

* quotedblleft (U+201C) has a counter-clockwise outer contour

* quotedblleft (U+201C) has a counter-clockwise outer contour

* quotedblright (U+201D) has a counter-clockwise outer contour

* quotedblright (U+201D) has a counter-clockwise outer contour

* quoteleft (U+2018) has a counter-clockwise outer contour

* quoteright (U+2019) has a counter-clockwise outer contour

* quotesinglbase (U+201A) has a counter-clockwise outer contour

* quotesingle (U+0027) has a counter-clockwise outer contour

* r (U+0072) has a counter-clockwise outer contour

* racute (U+0155) has a counter-clockwise outer contour

* racute (U+0155) has a counter-clockwise outer contour

* rcaron (U+0159) has a counter-clockwise outer contour

* rcaron (U+0159) has a counter-clockwise outer contour

* registered (U+00AE) has a counter-clockwise outer contour

* ring (U+02DA) has a counter-clockwise outer contour

* sacute (U+015B) has a counter-clockwise outer contour

* scaron (U+0161) has a counter-clockwise outer contour

* section (U+00A7) has a counter-clockwise outer contour

* semicolon (U+003B) has a counter-clockwise outer contour

* seven (U+0037) has a counter-clockwise outer contour

* seven.dnom has a counter-clockwise outer contour

* seven.numr has a counter-clockwise outer contour

* seveneighths (U+215E) has a counter-clockwise outer contour

* seveneighths (U+215E) has a counter-clockwise outer contour

* seveneighths (U+215E) has a counter-clockwise outer contour

* six (U+0036) has a counter-clockwise outer contour

* six.dnom has a counter-clockwise outer contour

* six.numr has a counter-clockwise outer contour

* slash_asterisk.liga has a counter-clockwise outer contour

* sterling (U+00A3) has a counter-clockwise outer contour

* summation (U+2211) has a counter-clockwise outer contour

* thorn (U+00FE) has a counter-clockwise outer contour

* three (U+0033) has a counter-clockwise outer contour

* three.dnom has a counter-clockwise outer contour

* three.numr has a counter-clockwise outer contour

* threeeighths (U+215C) has a counter-clockwise outer contour

* threeeighths (U+215C) has a counter-clockwise outer contour

* threeeighths (U+215C) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* threequarters (U+00BE) has a counter-clockwise outer contour

* tilde (U+02DC) has a counter-clockwise outer contour

* tildecomb (U+0303) has a counter-clockwise outer contour

* trademark (U+2122) has a counter-clockwise outer contour

* two (U+0032) has a counter-clockwise outer contour

* two.dnom has a counter-clockwise outer contour

* two.numr has a counter-clockwise outer contour

* u (U+0075) has a counter-clockwise outer contour

* uacute (U+00FA) has a counter-clockwise outer contour

* uacute (U+00FA) has a counter-clockwise outer contour

* ucircumflex (U+00FB) has a counter-clockwise outer contour

* ucircumflex (U+00FB) has a counter-clockwise outer contour

* udieresis (U+00FC) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* ugrave (U+00F9) has a counter-clockwise outer contour

* uhungarumlaut (U+0171) has a counter-clockwise outer contour

* uhungarumlaut (U+0171) has a counter-clockwise outer contour

* uhungarumlaut (U+0171) has a counter-clockwise outer contour

* umacron (U+016B) has a counter-clockwise outer contour

* uni00B2 (U+00B2) has a counter-clockwise outer contour

* uni00B3 (U+00B3) has a counter-clockwise outer contour

* uni00B9 (U+00B9) has a counter-clockwise outer contour

* uni0122 (U+0122) has a counter-clockwise outer contour

* uni0122 (U+0122) has a counter-clockwise outer contour

* uni0123 (U+0123) has a counter-clockwise outer contour

* uni0123 (U+0123) has a counter-clockwise outer contour

* uni0136 (U+0136) has a counter-clockwise outer contour

* uni0136 (U+0136) has a counter-clockwise outer contour

* uni0137 (U+0137) has a counter-clockwise outer contour

* uni0137 (U+0137) has a counter-clockwise outer contour

* uni013B (U+013B) has a counter-clockwise outer contour

* uni013B (U+013B) has a counter-clockwise outer contour

* uni013C (U+013C) has a counter-clockwise outer contour

* uni013C (U+013C) has a counter-clockwise outer contour

* uni0145 (U+0145) has a counter-clockwise outer contour

* uni0145 (U+0145) has a counter-clockwise outer contour

* uni0146 (U+0146) has a counter-clockwise outer contour

* uni0146 (U+0146) has a counter-clockwise outer contour

* uni0218 (U+0218) has a counter-clockwise outer contour

* uni0219 (U+0219) has a counter-clockwise outer contour

* uni021A (U+021A) has a counter-clockwise outer contour

* uni021B (U+021B) has a counter-clockwise outer contour

* uni0302 (U+0302) has a counter-clockwise outer contour

* uni030A (U+030A) has a counter-clockwise outer contour

* uni030B (U+030B) has a counter-clockwise outer contour

* uni030B (U+030B) has a counter-clockwise outer contour

* uni030C (U+030C) has a counter-clockwise outer contour

* uni0312 (U+0312) has a counter-clockwise outer contour

* uni0313 (U+0313) has a counter-clockwise outer contour

* uni0314 (U+0314) has a counter-clockwise outer contour

* uni0316 (U+0316) has a counter-clockwise outer contour

* uni0317 (U+0317) has a counter-clockwise outer contour

* uni0325 (U+0325) has a counter-clockwise outer contour

* uni0326 (U+0326) has a counter-clockwise outer contour

* uni0328 (U+0328) has a counter-clockwise outer contour

* uni032D (U+032D) has a counter-clockwise outer contour

* uni0337 (U+0337) has a counter-clockwise outer contour

* uni0394 (U+0394) has a counter-clockwise outer contour

* uni1E9E (U+1E9E) has a counter-clockwise outer contour

* uni2070 (U+2070) has a counter-clockwise outer contour

* uni2074 (U+2074) has a counter-clockwise outer contour

* uni2075 (U+2075) has a counter-clockwise outer contour

* uni2076 (U+2076) has a counter-clockwise outer contour

* uni2077 (U+2077) has a counter-clockwise outer contour

* uni2078 (U+2078) has a counter-clockwise outer contour

* uni2079 (U+2079) has a counter-clockwise outer contour

* uni2080 (U+2080) has a counter-clockwise outer contour

* uni2081 (U+2081) has a counter-clockwise outer contour

* uni2082 (U+2082) has a counter-clockwise outer contour

* uni2083 (U+2083) has a counter-clockwise outer contour

* uni2084 (U+2084) has a counter-clockwise outer contour

* uni2085 (U+2085) has a counter-clockwise outer contour

* uni2086 (U+2086) has a counter-clockwise outer contour

* uni2087 (U+2087) has a counter-clockwise outer contour

* uni2088 (U+2088) has a counter-clockwise outer contour

* uni2089 (U+2089) has a counter-clockwise outer contour

* uni20BF (U+20BF) has a counter-clockwise outer contour

* uni20BF (U+20BF) has a counter-clockwise outer contour

* uni20BF (U+20BF) has a counter-clockwise outer contour

* uni20BF (U+20BF) has a counter-clockwise outer contour

* uni20BF (U+20BF) has a counter-clockwise outer contour

* uni2153 (U+2153) has a counter-clockwise outer contour

* uni2153 (U+2153) has a counter-clockwise outer contour

* uni2153 (U+2153) has a counter-clockwise outer contour

* uni2154 (U+2154) has a counter-clockwise outer contour

* uni2154 (U+2154) has a counter-clockwise outer contour

* uni2154 (U+2154) has a counter-clockwise outer contour

* uni215F (U+215F) has a counter-clockwise outer contour

* uni215F (U+215F) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uni25CC (U+25CC) has a counter-clockwise outer contour

* uniEE00 (U+EE00) has a counter-clockwise outer contour

* uniEE01 (U+EE01) has a counter-clockwise outer contour

* uniEE01 (U+EE01) has a counter-clockwise outer contour

* uniEE02 (U+EE02) has a counter-clockwise outer contour

* uniEE03 (U+EE03) has a counter-clockwise outer contour

* uniEE04 (U+EE04) has a counter-clockwise outer contour

* uniEE04 (U+EE04) has a counter-clockwise outer contour

* uniEE04 (U+EE04) has a counter-clockwise outer contour

* uniEE05 (U+EE05) has a counter-clockwise outer contour

* universal (U+2200) has a counter-clockwise outer contour

* uogonek (U+0173) has a counter-clockwise outer contour

* uogonek (U+0173) has a counter-clockwise outer contour

* uring (U+016F) has a counter-clockwise outer contour

* uring (U+016F) has a counter-clockwise outer contour

* v (U+0076) has a counter-clockwise outer contour

* w (U+0077) has a counter-clockwise outer contour

* wacute (U+1E83) has a counter-clockwise outer contour

* wacute (U+1E83) has a counter-clockwise outer contour

* wcircumflex (U+0175) has a counter-clockwise outer contour

* wcircumflex (U+0175) has a counter-clockwise outer contour

* wdieresis (U+1E85) has a counter-clockwise outer contour

* wgrave (U+1E81) has a counter-clockwise outer contour

* wgrave (U+1E81) has a counter-clockwise outer contour

* www.liga has a counter-clockwise outer contour

* x (U+0078) has a counter-clockwise outer contour

* y (U+0079) has a counter-clockwise outer contour

* yacute (U+00FD) has a counter-clockwise outer contour

* yacute (U+00FD) has a counter-clockwise outer contour

* ycircumflex (U+0177) has a counter-clockwise outer contour

* ycircumflex (U+0177) has a counter-clockwise outer contour

* ydieresis (U+00FF) has a counter-clockwise outer contour

* ygrave (U+1EF3) has a counter-clockwise outer contour

* ygrave (U+1EF3) has a counter-clockwise outer contour

* z (U+007A) has a counter-clockwise outer contour

* zacute (U+017A) has a counter-clockwise outer contour

* zacute (U+017A) has a counter-clockwise outer contour

* zcaron (U+017E) has a counter-clockwise outer contour

* zcaron (U+017E) has a counter-clockwise outer contour

* zdotaccent (U+017C) has a counter-clockwise outer contour

* zero (U+0030) has a counter-clockwise outer contour

* zero.dnom has a counter-clockwise outer contour

* zero.numr has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 9 | 97 | 8 | 137 | 0 | 
| 0% | 0% | 0% | 4% | 39% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
