## FontSpector report

fontspector version: 1.8.0






## Check results




<details><summary>[13] fonts/variable/KodeMono[ROND,wdth,wght].ttf</summary>
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








- ⚠️ **WARN** Interpolation issue in q: Kink in contour 0 at node 2 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni2081: Kink in contour 0 at node 6 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni2081: Kink in contour 0 at node 6 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni2083: Kink in contour 0 at node 2 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni2083: Kink in contour 0 at node 2 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni00B9: Kink in contour 0 at node 6 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni00B9: Kink in contour 0 at node 6 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni00B3: Kink in contour 0 at node 2 [code: interpolation-issue]
  
  


- ⚠️ **WARN** Interpolation issue in uni00B3: Kink in contour 0 at node 2 [code: interpolation-issue]
  
  


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
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ǎ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ǎ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
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
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * lv_Latn (Latvian)          |
|   The following auxiliary characters are missing from the font: Ō |                              |
|   The following auxiliary characters are missing from the font: Ŗ |                              |
|   The following auxiliary characters are missing from the font: ō |                              |
|   The following auxiliary characters are missing from the font: ŗ |                              |
| Auxiliary orthography codepoints:                                 | * ro_Latn (Romanian)         |
|   The following auxiliary characters are missing from the font: Ţ |                              |
|   The following auxiliary characters are missing from the font: ţ |                              |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)           |
|   The following auxiliary characters are missing from the font: Ǿ |                              |
|   The following auxiliary characters are missing from the font: ǿ |                              |
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
|   The following auxiliary characters are missing from the font: ʻ |                              | [code: warning-language-shaping]
  
  

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
* plus_plus.liga: Line(Line { p0: (0.0, 266.0), p1: (0.0, 334.0) }) has the same coordinates as a previous segment.
* plus_plus_plus.liga: Line(Line { p0: (-493.0, 334.0), p1: (-493.0, 266.0) }) has the same coordinates as a previous segment.
* plus_plus_plus.liga: Line(Line { p0: (-107.0, 266.0), p1: (-107.0, 334.0) }) has the same coordinates as a previous segment.
* equal_equal.liga: Line(Line { p0: (0.0, 353.0), p1: (0.0, 421.0) }) has the same coordinates as a previous segment.
* equal_equal.liga: Line(Line { p0: (0.0, 178.0), p1: (0.0, 246.0) }) has the same coordinates as a previous segment.
* trademark (U+2122): Quad(QuadBez { p0: (393.0, 423.0), p1: (393.0, 423.0), p2: (393.0, 423.0) }) has the same coordinates as a previous segment.
* yen (U+00A5): Quad(QuadBez { p0: (299.0, 410.0), p1: (299.0, 410.0), p2: (299.0, 410.0) }) has the same coordinates as a previous segment.
* lozenge (U+25CA): Quad(QuadBez { p0: (300.0, 642.0), p1: (300.0, 642.0), p2: (300.0, 642.0) }) has the same coordinates as a previous segment.
* lozenge (U+25CA): Quad(QuadBez { p0: (300.0, 49.0), p1: (300.0, 49.0), p2: (300.0, 49.0) }) has the same coordinates as a previous segment.
* www.liga: Quad(QuadBez { p0: (-899.0, 73.0), p1: (-899.0, 73.0), p2: (-899.0, 73.0) }) has the same coordinates as a previous segment.
* www.liga: Quad(QuadBez { p0: (-356.0, 73.0), p1: (-356.0, 73.0), p2: (-356.0, 73.0) }) has the same coordinates as a previous segment.
* www.liga: Quad(QuadBez { p0: (189.0, 73.0), p1: (189.0, 73.0), p2: (189.0, 73.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

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

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
* U+0305 COMBINING OVERLINE: try adding one of: elbasan, gothic, math, glagolitic, coptic
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, duployan, tifinagh, old-permic, math, coptic, syriac, tai-le, todhri, hebrew, canadian-aboriginal
* U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: tai-le, cherokee
* U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
* U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: try adding ethiopic
* U+0310 COMBINING CANDRABINDU: try adding one of: math, sunuwar
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0313 COMBINING COMMA ABOVE: try adding one of: todhri, old-permic
* U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee, duployan
* U+0325 COMBINING RING BELOW: try adding syriac
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: syriac, sunuwar
* U+032E COMBINING BREVE BELOW: try adding syriac
* U+0331 COMBINING MACRON BELOW: try adding one of: gothic, thai, caucasian-albanian, syriac, cherokee, sunuwar, tifinagh
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: math, elbasan, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: math, greek
* U+03C0 GREEK SMALL LETTER PI: try adding one of: math, yi, greek
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
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
* U+2195 UP DOWN ARROW: try adding one of: math, symbols
* U+2196 NORTH WEST ARROW: try adding one of: math, symbols
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
* U+25CA LOZENGE: try adding one of: math, symbols
* U+25CC DOTTED CIRCLE: try adding one of: tamil, sogdian, cham, tirhuta, balinese, gujarati, mende-kikakui, telugu, duployan, newa, canadian-aboriginal, psalter-pahlavi, thaana, buginese, bhaiksuki, buhid, dogra, miao, javanese, music, batak, hanifi-rohingya, gunjala-gondi, devanagari, new-tai-lue, warang-citi, tibetan, bengali, manichaean, ahom, sundanese, limbu, khojki, hanunoo, soyombo, zanabazar-square, malayalam, lao, old-permic, syriac, lepcha, tagalog, nko, pahawh-hmong, kharoshthi, syloti-nagri, gurmukhi, chakma, tai-le, caucasian-albanian, rejang, thai, mahajani, phags-pa, mongolian, kannada, tifinagh, yi, elbasan, math, marchen, oriya, sinhala, takri, kaithi, brahmi, symbols, wancho, armenian, coptic, siddham, tai-tham, tai-viet, saurashtra, bassa-vah, hebrew, kayah-li, modi, khudawadi, mandaic, adlam, khmer, grantha, masaram-gondi, meetei-mayek, myanmar, osage, sharada, tagbanwa

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 34 | 8 | 123 | 58 | 
| 15% | 4% | 55% | 26% | 



