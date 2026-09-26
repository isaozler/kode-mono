## FontSpector report

fontspector version: 1.8.0






## Check results




<details><summary>[14] fonts/variable/KodeMono[ROND,wdth,wght].ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. (opentype/monospace)</summary>
    <div>








- ⚠️ **WARN** The OpenType spec recommends at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 467 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check base characters have non-zero advance width. (base_has_width)</summary>
    <div>








- ⚠️ **WARN** U+FEFF ZERO WIDTH NO-BREAK SPACE has non-zero advance width: 600 [code: non-zero-advance]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* slash_equal.liga (unencoded): found 5, expected one of: [1, 3]
* ampersand_ampersand.liga (unencoded): found 5, expected one of: [4, 6]
* plus_plus.liga (unencoded): found 2, expected one of: [1, 3, 4] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. (interpolation_issues)</summary>
    <div>








- ⚠️ **WARN** Interpolation issue in Thorn: Kink in contour 0 at node 37 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in W: Kink in contour 0 at node 13 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in a: Kink in contour 0 at node 37 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in thorn: Kink in contour 0 at node 37 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in u: Kink in contour 0 at node 38 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in w: Kink in contour 0 at node 63 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni2081: Kink in contour 0 at node 2 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni2081: Kink in contour 0 at node 2 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni2083: Kink in contour 0 at node 78 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni2083: Kink in contour 0 at node 78 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni00B9: Kink in contour 0 at node 2 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni00B9: Kink in contour 0 at node 2 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni00B3: Kink in contour 0 at node 78 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni00B3: Kink in contour 0 at node 78 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0306: Kink in contour 0 at node 31 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0306: Kink in contour 0 at node 6 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0306: Kink in contour 0 at node 31 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0310: Kink in contour 0 at node 6 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni0310: Kink in contour 0 at node 31 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni032E: Kink in contour 0 at node 31 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni032E: Kink in contour 0 at node 6 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni032E: Kink in contour 0 at node 31 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in breve: Kink in contour 0 at node 31 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in breve: Kink in contour 0 at node 6 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in breve: Kink in contour 0 at node 31 [code: interpolation-issue]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. (mandatory_avar_table)</summary>
    <div>








- ⚠️ **WARN** The font does not include an avar table.  If the progression rates of axes is linear and no user-mapping is expected, this is fine, and this check can be ignored or excluded. [code: missing-avar]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* at.001
* nobreakspace [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ō |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ō |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * en_Latn (English)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ō |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ō |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
|   The following auxiliary characters are missing from the font: ʻ |                              |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)           |
|   The following auxiliary characters are missing from the font: Ǔ |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ǔ |                              |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ǧ |                              |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ȟ |                              |
|   The following auxiliary characters are missing from the font: Ǩ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŝ |                              |
|   The following auxiliary characters are missing from the font: Ţ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ǧ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ȟ |                              |
|   The following auxiliary characters are missing from the font: ǩ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŝ |                              |
|   The following auxiliary characters are missing from the font: ţ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              |
| Auxiliary orthography codepoints:                                 | * cs_Latn (Czech)            |
|   The following auxiliary characters are missing from the font: Ĕ | * cy_Latn (Welsh)            |
|   The following auxiliary characters are missing from the font: Ĭ | * es_Latn (Spanish)          |
|   The following auxiliary characters are missing from the font: Ŏ | * hu_Latn (Hungarian)        |
|   The following auxiliary characters are missing from the font: Ō | * pt_Latn (Portuguese)       |
|   The following auxiliary characters are missing from the font: Ŭ | * sk_Latn (Slovak)           |
|   The following auxiliary characters are missing from the font: ĕ | * tr_Latn (Turkish)          |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ō |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * lt_Latn (Lithuanian)       |
|   The following auxiliary characters are missing from the font: Ẽ |                              |
|   The following auxiliary characters are missing from the font: Ĩ |                              |
|   The following auxiliary characters are missing from the font: Ũ |                              |
|   The following auxiliary characters are missing from the font: ẽ |                              |
|   The following auxiliary characters are missing from the font: ĩ |                              |
|   The following auxiliary characters are missing from the font: ũ |                              |
| Auxiliary orthography codepoints:                                 | * lv_Latn (Latvian)          |
|   The following auxiliary characters are missing from the font: Ō |                              |
|   The following auxiliary characters are missing from the font: Ŗ |                              |
|   The following auxiliary characters are missing from the font: ō |                              |
|   The following auxiliary characters are missing from the font: ŗ |                              |
| Auxiliary orthography codepoints:                                 | * ro_Latn (Romanian)         |
|   The following auxiliary characters are missing from the font: Ţ |                              |
|   The following auxiliary characters are missing from the font: ţ |                              |
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ǎ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ǎ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)           |
|   The following auxiliary characters are missing from the font: Ǿ |                              |
|   The following auxiliary characters are missing from the font: ǿ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ō |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ō |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* .notdef has a counter-clockwise outer contour
* .notdef has a counter-clockwise outer contour
* .notdef has a counter-clockwise outer contour
* .notdef has a counter-clockwise outer contour
* .notdef has a counter-clockwise outer contour
* .notdef has a counter-clockwise outer contour
* .notdef has a counter-clockwise outer contour
* .notdef has a counter-clockwise outer contour
* A (U+0041) has a counter-clockwise outer contour
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
* AE (U+00C6) has a counter-clockwise outer contour
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
* F (U+0046) has a counter-clockwise outer contour
* G (U+0047) has a counter-clockwise outer contour
* Gbreve (U+011E) has a counter-clockwise outer contour
* uni0122 (U+0122) has a counter-clockwise outer contour
* uni0122 (U+0122) has a counter-clockwise outer contour
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
* uni0136 (U+0136) has a counter-clockwise outer contour
* uni0136 (U+0136) has a counter-clockwise outer contour
* L (U+004C) has a counter-clockwise outer contour
* Lacute (U+0139) has a counter-clockwise outer contour
* Lacute (U+0139) has a counter-clockwise outer contour
* Lcaron (U+013D) has a counter-clockwise outer contour
* uni013B (U+013B) has a counter-clockwise outer contour
* uni013B (U+013B) has a counter-clockwise outer contour
* Lslash (U+0141) has a counter-clockwise outer contour
* Lslash (U+0141) has a counter-clockwise outer contour
* M (U+004D) has a counter-clockwise outer contour
* N (U+004E) has a counter-clockwise outer contour
* Nacute (U+0143) has a counter-clockwise outer contour
* Nacute (U+0143) has a counter-clockwise outer contour
* Ncaron (U+0147) has a counter-clockwise outer contour
* Ncaron (U+0147) has a counter-clockwise outer contour
* uni0145 (U+0145) has a counter-clockwise outer contour
* uni0145 (U+0145) has a counter-clockwise outer contour
* Ntilde (U+00D1) has a counter-clockwise outer contour
* Ntilde (U+00D1) has a counter-clockwise outer contour
* Oacute (U+00D3) has a counter-clockwise outer contour
* Ocircumflex (U+00D4) has a counter-clockwise outer contour
* Ograve (U+00D2) has a counter-clockwise outer contour
* Ohungarumlaut (U+0150) has a counter-clockwise outer contour
* Ohungarumlaut (U+0150) has a counter-clockwise outer contour
* Otilde (U+00D5) has a counter-clockwise outer contour
* OE (U+0152) has a counter-clockwise outer contour
* P (U+0050) has a counter-clockwise outer contour
* Thorn (U+00DE) has a counter-clockwise outer contour
* Q (U+0051) has a counter-clockwise outer contour
* R (U+0052) has a counter-clockwise outer contour
* Racute (U+0154) has a counter-clockwise outer contour
* Racute (U+0154) has a counter-clockwise outer contour
* Rcaron (U+0158) has a counter-clockwise outer contour
* Rcaron (U+0158) has a counter-clockwise outer contour
* Sacute (U+015A) has a counter-clockwise outer contour
* Scaron (U+0160) has a counter-clockwise outer contour
* uni0218 (U+0218) has a counter-clockwise outer contour
* uni1E9E (U+1E9E) has a counter-clockwise outer contour
* Tcaron (U+0164) has a counter-clockwise outer contour
* uni021A (U+021A) has a counter-clockwise outer contour
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
* adieresis (U+00E4) has a counter-clockwise outer contour
* agrave (U+00E0) has a counter-clockwise outer contour
* agrave (U+00E0) has a counter-clockwise outer contour
* amacron (U+0101) has a counter-clockwise outer contour
* aogonek (U+0105) has a counter-clockwise outer contour
* aogonek (U+0105) has a counter-clockwise outer contour
* aring (U+00E5) has a counter-clockwise outer contour
* aring (U+00E5) has a counter-clockwise outer contour
* atilde (U+00E3) has a counter-clockwise outer contour
* atilde (U+00E3) has a counter-clockwise outer contour
* ae (U+00E6) has a counter-clockwise outer contour
* b (U+0062) has a counter-clockwise outer contour
* cacute (U+0107) has a counter-clockwise outer contour
* ccaron (U+010D) has a counter-clockwise outer contour
* eth (U+00F0) has a counter-clockwise outer contour
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
* emacron (U+0113) has a counter-clockwise outer contour
* eogonek (U+0119) has a counter-clockwise outer contour
* eogonek (U+0119) has a counter-clockwise outer contour
* f (U+0066) has a counter-clockwise outer contour
* g (U+0067) has a counter-clockwise outer contour
* gbreve (U+011F) has a counter-clockwise outer contour
* uni0123 (U+0123) has a counter-clockwise outer contour
* uni0123 (U+0123) has a counter-clockwise outer contour
* gdotaccent (U+0121) has a counter-clockwise outer contour
* i (U+0069) has a counter-clockwise outer contour
* dotlessi (U+0131) has a counter-clockwise outer contour
* iacute (U+00ED) has a counter-clockwise outer contour
* iacute (U+00ED) has a counter-clockwise outer contour
* icircumflex (U+00EE) has a counter-clockwise outer contour
* icircumflex (U+00EE) has a counter-clockwise outer contour
* idieresis (U+00EF) has a counter-clockwise outer contour
* i.loclTRK has a counter-clockwise outer contour
* igrave (U+00EC) has a counter-clockwise outer contour
* igrave (U+00EC) has a counter-clockwise outer contour
* imacron (U+012B) has a counter-clockwise outer contour
* iogonek (U+012F) has a counter-clockwise outer contour
* iogonek (U+012F) has a counter-clockwise outer contour
* ij (U+0133) has a counter-clockwise outer contour
* ij (U+0133) has a counter-clockwise outer contour
* ij (U+0133) has a counter-clockwise outer contour
* k (U+006B) has a counter-clockwise outer contour
* uni0137 (U+0137) has a counter-clockwise outer contour
* uni0137 (U+0137) has a counter-clockwise outer contour
* l (U+006C) has a counter-clockwise outer contour
* lacute (U+013A) has a counter-clockwise outer contour
* lacute (U+013A) has a counter-clockwise outer contour
* lcaron (U+013E) has a counter-clockwise outer contour
* uni013C (U+013C) has a counter-clockwise outer contour
* uni013C (U+013C) has a counter-clockwise outer contour
* lslash (U+0142) has a counter-clockwise outer contour
* lslash (U+0142) has a counter-clockwise outer contour
* m (U+006D) has a counter-clockwise outer contour
* n (U+006E) has a counter-clockwise outer contour
* nacute (U+0144) has a counter-clockwise outer contour
* nacute (U+0144) has a counter-clockwise outer contour
* ncaron (U+0148) has a counter-clockwise outer contour
* ncaron (U+0148) has a counter-clockwise outer contour
* uni0146 (U+0146) has a counter-clockwise outer contour
* uni0146 (U+0146) has a counter-clockwise outer contour
* ntilde (U+00F1) has a counter-clockwise outer contour
* ntilde (U+00F1) has a counter-clockwise outer contour
* o (U+006F) has a counter-clockwise outer contour
* oacute (U+00F3) has a counter-clockwise outer contour
* oacute (U+00F3) has a counter-clockwise outer contour
* ocircumflex (U+00F4) has a counter-clockwise outer contour
* ocircumflex (U+00F4) has a counter-clockwise outer contour
* odieresis (U+00F6) has a counter-clockwise outer contour
* ograve (U+00F2) has a counter-clockwise outer contour
* ograve (U+00F2) has a counter-clockwise outer contour
* ohungarumlaut (U+0151) has a counter-clockwise outer contour
* ohungarumlaut (U+0151) has a counter-clockwise outer contour
* ohungarumlaut (U+0151) has a counter-clockwise outer contour
* oslash (U+00F8) has a counter-clockwise outer contour
* oslash (U+00F8) has a counter-clockwise outer contour
* otilde (U+00F5) has a counter-clockwise outer contour
* otilde (U+00F5) has a counter-clockwise outer contour
* oe (U+0153) has a counter-clockwise outer contour
* p (U+0070) has a counter-clockwise outer contour
* thorn (U+00FE) has a counter-clockwise outer contour
* q (U+0071) has a counter-clockwise outer contour
* r (U+0072) has a counter-clockwise outer contour
* racute (U+0155) has a counter-clockwise outer contour
* racute (U+0155) has a counter-clockwise outer contour
* rcaron (U+0159) has a counter-clockwise outer contour
* rcaron (U+0159) has a counter-clockwise outer contour
* sacute (U+015B) has a counter-clockwise outer contour
* scaron (U+0161) has a counter-clockwise outer contour
* uni0219 (U+0219) has a counter-clockwise outer contour
* germandbls (U+00DF) has a counter-clockwise outer contour
* uni021B (U+021B) has a counter-clockwise outer contour
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
* ordfeminine (U+00AA) has a counter-clockwise outer contour
* ordmasculine (U+00BA) has a counter-clockwise outer contour
* uni0394 (U+0394) has a counter-clockwise outer contour
* pi (U+03C0) has a counter-clockwise outer contour
* zero (U+0030) has a counter-clockwise outer contour
* one (U+0031) has a counter-clockwise outer contour
* two (U+0032) has a counter-clockwise outer contour
* three (U+0033) has a counter-clockwise outer contour
* four (U+0034) has a counter-clockwise outer contour
* five (U+0035) has a counter-clockwise outer contour
* six (U+0036) has a counter-clockwise outer contour
* seven (U+0037) has a counter-clockwise outer contour
* eight (U+0038) has a counter-clockwise outer contour
* nine (U+0039) has a counter-clockwise outer contour
* zero.dnom has a counter-clockwise outer contour
* one.dnom has a counter-clockwise outer contour
* two.dnom has a counter-clockwise outer contour
* three.dnom has a counter-clockwise outer contour
* four.dnom has a counter-clockwise outer contour
* five.dnom has a counter-clockwise outer contour
* six.dnom has a counter-clockwise outer contour
* seven.dnom has a counter-clockwise outer contour
* eight.dnom has a counter-clockwise outer contour
* nine.dnom has a counter-clockwise outer contour
* zero.numr has a counter-clockwise outer contour
* one.numr has a counter-clockwise outer contour
* two.numr has a counter-clockwise outer contour
* three.numr has a counter-clockwise outer contour
* four.numr has a counter-clockwise outer contour
* five.numr has a counter-clockwise outer contour
* six.numr has a counter-clockwise outer contour
* seven.numr has a counter-clockwise outer contour
* eight.numr has a counter-clockwise outer contour
* nine.numr has a counter-clockwise outer contour
* fraction (U+2044) has a counter-clockwise outer contour
* uni215F (U+215F) has a counter-clockwise outer contour
* uni215F (U+215F) has a counter-clockwise outer contour
* onehalf (U+00BD) has a counter-clockwise outer contour
* onehalf (U+00BD) has a counter-clockwise outer contour
* onehalf (U+00BD) has a counter-clockwise outer contour
* uni2153 (U+2153) has a counter-clockwise outer contour
* uni2153 (U+2153) has a counter-clockwise outer contour
* uni2153 (U+2153) has a counter-clockwise outer contour
* uni2154 (U+2154) has a counter-clockwise outer contour
* uni2154 (U+2154) has a counter-clockwise outer contour
* uni2154 (U+2154) has a counter-clockwise outer contour
* onequarter (U+00BC) has a counter-clockwise outer contour
* onequarter (U+00BC) has a counter-clockwise outer contour
* onequarter (U+00BC) has a counter-clockwise outer contour
* threequarters (U+00BE) has a counter-clockwise outer contour
* threequarters (U+00BE) has a counter-clockwise outer contour
* threequarters (U+00BE) has a counter-clockwise outer contour
* oneeighth (U+215B) has a counter-clockwise outer contour
* oneeighth (U+215B) has a counter-clockwise outer contour
* oneeighth (U+215B) has a counter-clockwise outer contour
* threeeighths (U+215C) has a counter-clockwise outer contour
* threeeighths (U+215C) has a counter-clockwise outer contour
* threeeighths (U+215C) has a counter-clockwise outer contour
* fiveeighths (U+215D) has a counter-clockwise outer contour
* fiveeighths (U+215D) has a counter-clockwise outer contour
* fiveeighths (U+215D) has a counter-clockwise outer contour
* seveneighths (U+215E) has a counter-clockwise outer contour
* seveneighths (U+215E) has a counter-clockwise outer contour
* seveneighths (U+215E) has a counter-clockwise outer contour
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
* uni2070 (U+2070) has a counter-clockwise outer contour
* uni00B9 (U+00B9) has a counter-clockwise outer contour
* uni00B2 (U+00B2) has a counter-clockwise outer contour
* uni00B3 (U+00B3) has a counter-clockwise outer contour
* uni2074 (U+2074) has a counter-clockwise outer contour
* uni2075 (U+2075) has a counter-clockwise outer contour
* uni2076 (U+2076) has a counter-clockwise outer contour
* uni2077 (U+2077) has a counter-clockwise outer contour
* uni2078 (U+2078) has a counter-clockwise outer contour
* uni2079 (U+2079) has a counter-clockwise outer contour
* question_period.liga has a counter-clockwise outer contour
* question_period.liga has a counter-clockwise outer contour
* asterisk_asterisk.liga has a counter-clockwise outer contour
* asterisk_asterisk.liga has a counter-clockwise outer contour
* asterisk_slash.liga has a counter-clockwise outer contour
* slash_asterisk.liga has a counter-clockwise outer contour
* comma (U+002C) has a counter-clockwise outer contour
* semicolon (U+003B) has a counter-clockwise outer contour
* exclam (U+0021) has a counter-clockwise outer contour
* exclam (U+0021) has a counter-clockwise outer contour
* exclamdown (U+00A1) has a counter-clockwise outer contour
* exclamdown (U+00A1) has a counter-clockwise outer contour
* question (U+003F) has a counter-clockwise outer contour
* question (U+003F) has a counter-clockwise outer contour
* questiondown (U+00BF) has a counter-clockwise outer contour
* questiondown (U+00BF) has a counter-clockwise outer contour
* bullet (U+2022) has a counter-clockwise outer contour
* asterisk (U+002A) has a counter-clockwise outer contour
* numbersign (U+0023) has a counter-clockwise outer contour
* parenleft (U+0028) has a counter-clockwise outer contour
* parenright (U+0029) has a counter-clockwise outer contour
* braceleft (U+007B) has a counter-clockwise outer contour
* braceright (U+007D) has a counter-clockwise outer contour
* bracketleft (U+005B) has a counter-clockwise outer contour
* bracketright (U+005D) has a counter-clockwise outer contour
* quotesinglbase (U+201A) has a counter-clockwise outer contour
* quotedblbase (U+201E) has a counter-clockwise outer contour
* quotedblbase (U+201E) has a counter-clockwise outer contour
* quotedblleft (U+201C) has a counter-clockwise outer contour
* quotedblleft (U+201C) has a counter-clockwise outer contour
* quotedblright (U+201D) has a counter-clockwise outer contour
* quotedblright (U+201D) has a counter-clockwise outer contour
* quoteleft (U+2018) has a counter-clockwise outer contour
* quoteright (U+2019) has a counter-clockwise outer contour
* guillemotleft (U+00AB) has a counter-clockwise outer contour
* guillemotleft (U+00AB) has a counter-clockwise outer contour
* guillemotright (U+00BB) has a counter-clockwise outer contour
* guillemotright (U+00BB) has a counter-clockwise outer contour
* guilsinglleft (U+2039) has a counter-clockwise outer contour
* guilsinglright (U+203A) has a counter-clockwise outer contour
* quotedbl (U+0022) has a counter-clockwise outer contour
* quotedbl (U+0022) has a counter-clockwise outer contour
* quotesingle (U+0027) has a counter-clockwise outer contour
* ampersand_ampersand.liga has a counter-clockwise outer contour
* dollar_greater.liga has a counter-clockwise outer contour
* plus_plus.liga has a counter-clockwise outer contour
* plus_plus.liga has a counter-clockwise outer contour
* plus_plus_plus.liga has a counter-clockwise outer contour
* plus_plus_plus.liga has a counter-clockwise outer contour
* plus_plus_plus.liga has a counter-clockwise outer contour
* greater_equal.liga has a counter-clockwise outer contour
* greater_equal.liga has a counter-clockwise outer contour
* less_asterisk_greater.liga has a counter-clockwise outer contour
* less_dollar.liga has a counter-clockwise outer contour
* less_dollar_greater.liga has a counter-clockwise outer contour
* less_equal.liga has a counter-clockwise outer contour
* less_equal.liga has a counter-clockwise outer contour
* at (U+0040) has a counter-clockwise outer contour
* ampersand (U+0026) has a counter-clockwise outer contour
* paragraph (U+00B6) has a counter-clockwise outer contour
* section (U+00A7) has a counter-clockwise outer contour
* copyright (U+00A9) has a counter-clockwise outer contour
* registered (U+00AE) has a counter-clockwise outer contour
* trademark (U+2122) has a counter-clockwise outer contour
* degree (U+00B0) has a counter-clockwise outer contour
* brokenbar (U+00A6) has a counter-clockwise outer contour
* brokenbar (U+00A6) has a counter-clockwise outer contour
* at.001 has a counter-clockwise outer contour
* uni20BF (U+20BF) has a counter-clockwise outer contour
* uni20BF (U+20BF) has a counter-clockwise outer contour
* uni20BF (U+20BF) has a counter-clockwise outer contour
* uni20BF (U+20BF) has a counter-clockwise outer contour
* uni20BF (U+20BF) has a counter-clockwise outer contour
* cent (U+00A2) has a counter-clockwise outer contour
* currency (U+00A4) has a counter-clockwise outer contour
* dollar (U+0024) has a counter-clockwise outer contour
* Euro (U+20AC) has a counter-clockwise outer contour
* sterling (U+00A3) has a counter-clockwise outer contour
* plus (U+002B) has a counter-clockwise outer contour
* minus (U+2212) has a counter-clockwise outer contour
* multiply (U+00D7) has a counter-clockwise outer contour
* divide (U+00F7) has a counter-clockwise outer contour
* divide (U+00F7) has a counter-clockwise outer contour
* divide (U+00F7) has a counter-clockwise outer contour
* greaterequal (U+2265) has a counter-clockwise outer contour
* greaterequal (U+2265) has a counter-clockwise outer contour
* lessequal (U+2264) has a counter-clockwise outer contour
* lessequal (U+2264) has a counter-clockwise outer contour
* plusminus (U+00B1) has a counter-clockwise outer contour
* plusminus (U+00B1) has a counter-clockwise outer contour
* asciitilde (U+007E) has a counter-clockwise outer contour
* logicalnot (U+00AC) has a counter-clockwise outer contour
* asciicircum (U+005E) has a counter-clockwise outer contour
* infinity (U+221E) has a counter-clockwise outer contour
* product (U+220F) has a counter-clockwise outer contour
* summation (U+2211) has a counter-clockwise outer contour
* partialdiff (U+2202) has a counter-clockwise outer contour
* percent (U+0025) has a counter-clockwise outer contour
* perthousand (U+2030) has a counter-clockwise outer contour
* perthousand (U+2030) has a counter-clockwise outer contour
* perthousand (U+2030) has a counter-clockwise outer contour
* perthousand (U+2030) has a counter-clockwise outer contour
* universal (U+2200) has a counter-clockwise outer contour
* arrowup (U+2191) has a counter-clockwise outer contour
* arrowup (U+2191) has a counter-clockwise outer contour
* uni2197 (U+2197) has a counter-clockwise outer contour
* uni2197 (U+2197) has a counter-clockwise outer contour
* uni2198 (U+2198) has a counter-clockwise outer contour
* uni2198 (U+2198) has a counter-clockwise outer contour
* arrowdown (U+2193) has a counter-clockwise outer contour
* arrowdown (U+2193) has a counter-clockwise outer contour
* uni2199 (U+2199) has a counter-clockwise outer contour
* uni2199 (U+2199) has a counter-clockwise outer contour
* uni2196 (U+2196) has a counter-clockwise outer contour
* uni2196 (U+2196) has a counter-clockwise outer contour
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
* lozenge (U+25CA) has a counter-clockwise outer contour
* gravecomb (U+0300) has a counter-clockwise outer contour
* acutecomb (U+0301) has a counter-clockwise outer contour
* uni030B (U+030B) has a counter-clockwise outer contour
* uni030B (U+030B) has a counter-clockwise outer contour
* uni0302 (U+0302) has a counter-clockwise outer contour
* uni030C (U+030C) has a counter-clockwise outer contour
* uni030A (U+030A) has a counter-clockwise outer contour
* tildecomb (U+0303) has a counter-clockwise outer contour
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
* grave (U+0060) has a counter-clockwise outer contour
* acute (U+00B4) has a counter-clockwise outer contour
* hungarumlaut (U+02DD) has a counter-clockwise outer contour
* hungarumlaut (U+02DD) has a counter-clockwise outer contour
* circumflex (U+02C6) has a counter-clockwise outer contour
* caron (U+02C7) has a counter-clockwise outer contour
* ring (U+02DA) has a counter-clockwise outer contour
* tilde (U+02DC) has a counter-clockwise outer contour
* ogonek (U+02DB) has a counter-clockwise outer contour
* uniEE00 (U+EE00) has a counter-clockwise outer contour
* uniEE01 (U+EE01) has a counter-clockwise outer contour
* uniEE01 (U+EE01) has a counter-clockwise outer contour
* uniEE02 (U+EE02) has a counter-clockwise outer contour
* uniEE03 (U+EE03) has a counter-clockwise outer contour
* uniEE04 (U+EE04) has a counter-clockwise outer contour
* uniEE04 (U+EE04) has a counter-clockwise outer contour
* uniEE04 (U+EE04) has a counter-clockwise outer contour
* uniEE05 (U+EE05) has a counter-clockwise outer contour
* idotlessogonek has a counter-clockwise outer contour
* idotlessogonek has a counter-clockwise outer contour
* www.liga has a counter-clockwise outer contour
* eight.ss01 has a counter-clockwise outer contour
* Q.ss01 has a counter-clockwise outer contour
* Dcaron.ss01 has a counter-clockwise outer contour
* uniE0A1 (U+E0A1) has a counter-clockwise outer contour
* uniE0A1 (U+E0A1) has a counter-clockwise outer contour [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* M (U+004D): Quad(QuadBez { p0: (255.0, 401.0), p1: (255.0, 401.0), p2: (255.0, 401.0) }) has the same coordinates as a previous segment.
* Y (U+0059): Quad(QuadBez { p0: (298.0, 410.0), p1: (298.0, 410.0), p2: (298.0, 410.0) }) has the same coordinates as a previous segment.
* Yacute (U+00DD): Quad(QuadBez { p0: (298.0, 410.0), p1: (298.0, 410.0), p2: (298.0, 410.0) }) has the same coordinates as a previous segment.
* Ycircumflex (U+0176): Quad(QuadBez { p0: (298.0, 410.0), p1: (298.0, 410.0), p2: (298.0, 410.0) }) has the same coordinates as a previous segment.
* Ydieresis (U+0178): Quad(QuadBez { p0: (298.0, 410.0), p1: (298.0, 410.0), p2: (298.0, 410.0) }) has the same coordinates as a previous segment.
* Ygrave (U+1EF2): Quad(QuadBez { p0: (298.0, 410.0), p1: (298.0, 410.0), p2: (298.0, 410.0) }) has the same coordinates as a previous segment.
* x (U+0078): Quad(QuadBez { p0: (177.0, 242.0), p1: (177.0, 242.0), p2: (177.0, 242.0) }) has the same coordinates as a previous segment.
* two.dnom: Quad(QuadBez { p0: (241.0, 58.0), p1: (241.0, 58.0), p2: (241.0, 58.0) }) has the same coordinates as a previous segment.
* seven.dnom: Quad(QuadBez { p0: (360.0, 302.0), p1: (360.0, 302.0), p2: (360.0, 302.0) }) has the same coordinates as a previous segment.
* two.numr: Quad(QuadBez { p0: (241.0, 418.0), p1: (241.0, 418.0), p2: (241.0, 418.0) }) has the same coordinates as a previous segment.
* seven.numr: Quad(QuadBez { p0: (360.0, 662.0), p1: (360.0, 662.0), p2: (360.0, 662.0) }) has the same coordinates as a previous segment.
* onehalf (U+00BD): Quad(QuadBez { p0: (321.0, -102.0), p1: (321.0, -102.0), p2: (321.0, -102.0) }) has the same coordinates as a previous segment.
* seveneighths (U+215E): Quad(QuadBez { p0: (240.0, 722.0), p1: (240.0, 722.0), p2: (240.0, 722.0) }) has the same coordinates as a previous segment.
* uni2082 (U+2082): Quad(QuadBez { p0: (241.0, 58.0), p1: (241.0, 58.0), p2: (241.0, 58.0) }) has the same coordinates as a previous segment.
* uni2087 (U+2087): Quad(QuadBez { p0: (360.0, 302.0), p1: (360.0, 302.0), p2: (360.0, 302.0) }) has the same coordinates as a previous segment.
* uni00B2 (U+00B2): Quad(QuadBez { p0: (241.0, 418.0), p1: (241.0, 418.0), p2: (241.0, 418.0) }) has the same coordinates as a previous segment.
* uni2077 (U+2077): Quad(QuadBez { p0: (360.0, 662.0), p1: (360.0, 662.0), p2: (360.0, 662.0) }) has the same coordinates as a previous segment.
* slash_equal.liga: Line(Line { p0: (0.0, 353.0), p1: (0.0, 421.0) }) has the same coordinates as a previous segment.
* slash_equal.liga: Line(Line { p0: (0.0, 178.0), p1: (0.0, 246.0) }) has the same coordinates as a previous segment.
* plus_plus.liga: Line(Line { p0: (0.0, 334.0), p1: (0.0, 266.0) }) has the same coordinates as a previous segment.
* plus_plus_plus.liga: Line(Line { p0: (-493.0, 266.0), p1: (-493.0, 334.0) }) has the same coordinates as a previous segment.
* plus_plus_plus.liga: Line(Line { p0: (-107.0, 334.0), p1: (-107.0, 266.0) }) has the same coordinates as a previous segment.
* equal_equal.liga: Line(Line { p0: (0.0, 353.0), p1: (0.0, 421.0) }) has the same coordinates as a previous segment.
* equal_equal.liga: Line(Line { p0: (0.0, 178.0), p1: (0.0, 246.0) }) has the same coordinates as a previous segment.
* trademark (U+2122): Quad(QuadBez { p0: (393.0, 423.0), p1: (393.0, 423.0), p2: (393.0, 423.0) }) has the same coordinates as a previous segment.
* yen (U+00A5): Quad(QuadBez { p0: (299.0, 410.0), p1: (299.0, 410.0), p2: (299.0, 410.0) }) has the same coordinates as a previous segment.
* lozenge (U+25CA): Quad(QuadBez { p0: (300.0, 642.0), p1: (300.0, 642.0), p2: (300.0, 642.0) }) has the same coordinates as a previous segment.
* lozenge (U+25CA): Quad(QuadBez { p0: (300.0, 49.0), p1: (300.0, 49.0), p2: (300.0, 49.0) }) has the same coordinates as a previous segment.
* www.liga: Quad(QuadBez { p0: (189.0, 73.0), p1: (189.0, 73.0), p2: (189.0, 73.0) }) has the same coordinates as a previous segment.
* www.liga: Quad(QuadBez { p0: (-356.0, 73.0), p1: (-356.0, 73.0), p2: (-356.0, 73.0) }) has the same coordinates as a previous segment.
* www.liga: Quad(QuadBez { p0: (-899.0, 73.0), p1: (-899.0, 73.0), p2: (-899.0, 73.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'NONE' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[1] fonts/variable</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** fonts/variable/KodeMono[ROND,wdth,wght].ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math
* U+0305 COMBINING OVERLINE: try adding one of: elbasan, gothic, glagolitic, math, coptic
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, canadian-aboriginal, syriac, tai-le, math, malayalam, old-permic, coptic, hebrew, todhri, duployan
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
* U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: try adding ethiopic
* U+0310 COMBINING CANDRABINDU: try adding one of: sunuwar, math
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0313 COMBINING COMMA ABOVE: try adding one of: old-permic, todhri
* U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac, duployan
* U+0325 COMBINING RING BELOW: try adding syriac
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac
* U+032E COMBINING BREVE BELOW: try adding syriac
* U+0331 COMBINING MACRON BELOW: try adding one of: syriac, thai, gothic, tifinagh, caucasian-albanian, cherokee, sunuwar
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math
* U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
* U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
* U+2017 DOUBLE LOW LINE: try adding math
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2070 SUPERSCRIPT ZERO: try adding math
* U+2074 SUPERSCRIPT FOUR: try adding math
* U+2075 SUPERSCRIPT FIVE: try adding math
* U+2076 SUPERSCRIPT SIX: try adding math
* U+2077 SUPERSCRIPT SEVEN: try adding math
* U+2078 SUPERSCRIPT EIGHT: try adding math
* U+2079 SUPERSCRIPT NINE: try adding math
* U+2080 SUBSCRIPT ZERO: try adding math
* U+2081 SUBSCRIPT ONE: try adding math
* U+2082 SUBSCRIPT TWO: try adding math
* U+2083 SUBSCRIPT THREE: try adding math
* U+2084 SUBSCRIPT FOUR: try adding math
* U+2085 SUBSCRIPT FIVE: try adding math
* U+2086 SUBSCRIPT SIX: try adding math
* U+2087 SUBSCRIPT SEVEN: try adding math
* U+2088 SUBSCRIPT EIGHT: try adding math
* U+2089 SUBSCRIPT NINE: try adding math
* U+2153 VULGAR FRACTION ONE THIRD: try adding symbols
* U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols
* U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols
* U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols
* U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols
* U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols
* U+215F FRACTION NUMERATOR ONE: try adding symbols
* U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: symbols, math
* U+2197 NORTH EAST ARROW: try adding one of: math, symbols
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
* U+2200 FOR ALL: try adding math
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+24C0 CIRCLED LATIN CAPITAL LETTER K: try adding symbols
* U+2500 BOX DRAWINGS LIGHT HORIZONTAL: try adding symbols2
* U+2502 BOX DRAWINGS LIGHT VERTICAL: try adding symbols2
* U+250C BOX DRAWINGS LIGHT DOWN AND RIGHT: try adding symbols2
* U+2510 BOX DRAWINGS LIGHT DOWN AND LEFT: try adding symbols2
* U+2514 BOX DRAWINGS LIGHT UP AND RIGHT: try adding symbols2
* U+2518 BOX DRAWINGS LIGHT UP AND LEFT: try adding symbols2
* U+251C BOX DRAWINGS LIGHT VERTICAL AND RIGHT: try adding symbols2
* U+2524 BOX DRAWINGS LIGHT VERTICAL AND LEFT: try adding symbols2
* U+252C BOX DRAWINGS LIGHT DOWN AND HORIZONTAL: try adding symbols2
* U+2534 BOX DRAWINGS LIGHT UP AND HORIZONTAL: try adding symbols2
* U+253C BOX DRAWINGS LIGHT VERTICAL AND HORIZONTAL: try adding symbols2
* U+25CA LOZENGE: try adding one of: symbols, math
* U+25CC DOTTED CIRCLE: try adding one of: grantha, hanunoo, meetei-mayek, tamil, lao, syloti-nagri, mahajani, zanabazar-square, bhaiksuki, khojki, sundanese, devanagari, javanese, modi, math, pahawh-hmong, phags-pa, tai-viet, osage, lepcha, buhid, hanifi-rohingya, duployan, myanmar, bengali, balinese, canadian-aboriginal, caucasian-albanian, marchen, coptic, oriya, mongolian, tagalog, telugu, masaram-gondi, symbols, mende-kikakui, thaana, sogdian, brahmi, newa, siddham, khudawadi, tirhuta, old-permic, syriac, nko, gujarati, batak, hebrew, miao, tai-tham, wancho, mandaic, thai, music, yi, tagbanwa, sinhala, bassa-vah, tai-le, warang-citi, chakma, adlam, kharoshthi, gunjala-gondi, malayalam, sharada, ahom, kayah-li, khmer, takri, buginese, new-tai-lue, armenian, cham, soyombo, kaithi, manichaean, kannada, rejang, gurmukhi, saurashtra, dogra, psalter-pahlavi, tibetan, limbu, tifinagh, elbasan

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 40 | 8 | 122 | 58 | 
| 18% | 4% | 54% | 25% | 



