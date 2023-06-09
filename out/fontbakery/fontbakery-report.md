## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[15] KodeMono-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ i̍ i̐ i̓ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̅ i̇ i̎ i̒ i̔ i̖̅ i̖̇ i̖̊ i̖̋ i̖̍ i̖̎ i̖̐ i̖̒ i̖̓ i̖̔ i̗̅ i̗̇ i̗̊ i̗̋ i̗̍ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'KDA ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.729x (3458) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
greater_greater_equal_middle.seq, greater_greater_hyphen_middle.seq, greater_greater_hyphen_start.seq and numbersign_underscore_parenleft.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- acute.case.loclPLK

	- at.spacer

	- braceright.spacer

	- commareversedbelowcomb.case

	- l.spacer

	- parenleft.spacer

	- strokelongoverlay 

	- strokeshortoverlay
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 3	Expected: 5

	- Glyph name: Q	Contours detected: 1	Expected: 2

	- Glyph name: yen	Contours detected: 3	Expected: 1 or 2

	- Glyph name: copyright	Contours detected: 2	Expected: 3

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

	- Glyph name: trademark	Contours detected: 1	Expected: 2

	- Glyph name: notalmostequal	Contours detected: 3	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: copyright	Contours detected: 2	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: percent	Contours detected: 3	Expected: 5

	- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: trademark	Contours detected: 1	Expected: 2

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1 

	- Glyph name: yen	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 acute (U+00B4), acute.case (unencoded), acutebelowcomb (U+0317), acutecomb (U+0301), breve (U+02D8), breve.case (unencoded), brevebelowcomb (U+032E), brevecomb (U+0306), breveinvertedbelowcomb (U+032F), breveinvertedcomb (U+0311), candraBinducomb (U+0310), caroncomb (U+030C), cedilla (U+00B8), cedilla.case (unencoded), cedillacomb (U+0327), circumflex (U+02C6), circumflexbelowcomb (U+032D), circumflexcomb (U+0302), commaabovecomb (U+0313), commaaboverightcomb (U+0315), commaaccentcomb (U+0326), commaaccentcomb.salt (unencoded), commabelowcomb.case (unencoded), commareversedabovecomb (U+0314), commareversedbelowcomb.case (unencoded), commaturnedabovecomb (U+0312), dblgravecomb (U+030F), dbllowlinecomb (U+0333), dblvlinecomb (U+030E), dieresis (U+00A8), dieresis.case (unencoded), dieresisbelowcomb (U+0324), dieresiscomb (U+0308), dotaccent (U+02D9), dotaccent.case (unencoded), dotaccentcomb (U+0307), dotbelowcomb (U+0323), grave.case (unencoded), gravebelowcomb (U+0316), gravecomb (U+0300), hookabovecomb (U+0309), hungarumlaut (U+02DD), hungarumlautcomb (U+030B), lowlinecomb (U+0332), macron (U+00AF), macron.case (unencoded), macronbelowcomb (U+0331), macroncomb (U+0304), ogonek (U+02DB), ogonekcomb (U+0328), overlinecomb (U+0305), period_equal.cv32 (unencoded), quoteleft (U+2018), ring (U+02DA), ring.case (unencoded), ringbelowcomb (U+0325), ringcomb (U+030A), tilde (U+02DC), tilde.case (unencoded), tildebelowcomb (U+0330), tildecomb (U+0303), tildeoverlaycomb (U+0334), vlinebelowcomb (U+0329) and vlinecomb (U+030D) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 strokelongcomb (U+0336) and strokeshortcomb (U+0335) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+00A8, U+00AF, U+00B4, U+00B8, U+02C6, U+02D8, U+02D9, U+02DA, U+02DB, U+02DC, U+02DD and U+2018 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* degree (U+00B0): X=709.0,Y=1398.0 (should be at cap-height 1400?)

	* Thorn (U+00DE): X=320.0,Y=-1.0 (should be at baseline 0?)

	* Thorn (U+00DE): X=160.0,Y=-1.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=720.0,Y=1398.0 (should be at cap-height 1400?)

	* edieresis (U+00EB): X=919.0,Y=1398.0 (should be at cap-height 1400?)

	* odieresis (U+00F6): X=720.0,Y=1398.0 (should be at cap-height 1400?)

	* odieresis (U+00F6): X=919.0,Y=1398.0 (should be at cap-height 1400?)

	* cdotaccent (U+010B): X=491.0,Y=1398.0 (should be at cap-height 1400?)

	* cdotaccent (U+010B): X=691.0,Y=1398.0 (should be at cap-height 1400?)

	* edotaccent (U+0117): X=500.0,Y=1398.0 (should be at cap-height 1400?)

	* edotaccent (U+0117): X=700.0,Y=1398.0 (should be at cap-height 1400?)

	* eogonek (U+0119): X=882.0,Y=1.0 (should be at baseline 0?)

	* Iogonek (U+012E): X=520.0,Y=1.0 (should be at baseline 0?)

	* Iogonek (U+012E): X=680.0,Y=1.0 (should be at baseline 0?)

	* utilde (U+0169): X=996.0,Y=1398.0 (should be at cap-height 1400?)

	* uring (U+016F): X=709.0,Y=1398.0 (should be at cap-height 1400?)

	* longs (U+017F): X=808.0,Y=1398.0 (should be at cap-height 1400?)

	* longs (U+017F): X=567.0,Y=1398.0 (should be at cap-height 1400?)

	* florin (U+0192): X=460.0,Y=1.0 (should be at baseline 0?)

	* florin (U+0192): X=459.0,Y=1.0 (should be at baseline 0?)

	* ring (U+02DA): X=711.0,Y=1398.0 (should be at cap-height 1400?)

	* tilde (U+02DC): X=999.0,Y=1398.0 (should be at cap-height 1400?)

	* tildecomb (U+0303): X=999.0,Y=1398.0 (should be at cap-height 1400?)

	* ringcomb (U+030A): X=711.0,Y=1398.0 (should be at cap-height 1400?) 

	* seven.inferior (U+2087): X=488.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* five (U+0035) contains a short segment L<<320.0,981.0>--<332.0,960.0>>

	* eight (U+0038) contains a short segment L<<344.0,671.0>--<323.0,671.0>>

	* M (U+004D) contains a short segment L<<510.0,795.0>--<510.0,799.0>>

	* W (U+0057) contains a short segment L<<335.0,144.0>--<384.0,144.0>>

	* W (U+0057) contains a short segment L<<817.0,144.0>--<865.0,144.0>>

	* Y (U+0059) contains a short segment L<<596.0,815.0>--<600.0,815.0>>

	* Z (U+005A) contains a short segment L<<845.0,815.0>--<880.0,815.0>>

	* w (U+0077) contains a short segment L<<375.0,145.0>--<384.0,145.0>>

	* w (U+0077) contains a short segment L<<816.0,145.0>--<822.0,145.0>>

	* x (U+0078) contains a short segment L<<356.0,480.0>--<356.0,483.0>>

	* z (U+007A) contains a short segment L<<880.0,889.0>--<880.0,912.0>>

	* yen (U+00A5) contains a short segment L<<596.0,815.0>--<600.0,815.0>>

	* mu (U+00B5) contains a short segment L<<362.0,0.0>--<344.0,26.0>>

	* Yacute (U+00DD) contains a short segment L<<596.0,815.0>--<600.0,815.0>>

	* ij (U+0133) contains a short segment L<<860.0,-56.0>--<860.0,-28.0>>

	* OE (U+0152) contains a short segment L<<760.0,166.0>--<739.0,144.0>>

	* Wcircumflex (U+0174) contains a short segment L<<335.0,144.0>--<384.0,144.0>>

	* Wcircumflex (U+0174) contains a short segment L<<817.0,144.0>--<865.0,144.0>>

	* wcircumflex (U+0175) contains a short segment L<<375.0,145.0>--<384.0,145.0>>

	* wcircumflex (U+0175) contains a short segment L<<816.0,145.0>--<822.0,145.0>>

	* Ycircumflex (U+0176) contains a short segment L<<596.0,815.0>--<600.0,815.0>>

	* Ydieresis (U+0178) contains a short segment L<<596.0,815.0>--<600.0,815.0>>

	* Zacute (U+0179) contains a short segment L<<845.0,815.0>--<880.0,815.0>>

	* zacute (U+017A) contains a short segment L<<880.0,889.0>--<880.0,912.0>>

	* Zdotaccent (U+017B) contains a short segment L<<845.0,815.0>--<880.0,815.0>>

	* zdotaccent (U+017C) contains a short segment L<<880.0,889.0>--<880.0,912.0>>

	* Zcaron (U+017D) contains a short segment L<<845.0,815.0>--<880.0,815.0>>

	* zcaron (U+017E) contains a short segment L<<880.0,889.0>--<880.0,912.0>>

	* florin (U+0192) contains a short segment L<<460.0,1.0>--<459.0,1.0>>

	* mu (U+03BC) contains a short segment L<<362.0,0.0>--<344.0,26.0>>

	* Wgrave (U+1E80) contains a short segment L<<335.0,144.0>--<384.0,144.0>>

	* Wgrave (U+1E80) contains a short segment L<<817.0,144.0>--<865.0,144.0>>

	* wgrave (U+1E81) contains a short segment L<<375.0,145.0>--<384.0,145.0>>

	* wgrave (U+1E81) contains a short segment L<<816.0,145.0>--<822.0,145.0>>

	* Wacute (U+1E82) contains a short segment L<<335.0,144.0>--<384.0,144.0>>

	* Wacute (U+1E82) contains a short segment L<<817.0,144.0>--<865.0,144.0>>

	* wacute (U+1E83) contains a short segment L<<375.0,145.0>--<384.0,145.0>>

	* wacute (U+1E83) contains a short segment L<<816.0,145.0>--<822.0,145.0>>

	* Wdieresis (U+1E84) contains a short segment L<<335.0,144.0>--<384.0,144.0>>

	* Wdieresis (U+1E84) contains a short segment L<<817.0,144.0>--<865.0,144.0>>

	* wdieresis (U+1E85) contains a short segment L<<375.0,145.0>--<384.0,145.0>>

	* wdieresis (U+1E85) contains a short segment L<<816.0,145.0>--<822.0,145.0>>

	* Ygrave (U+1EF2) contains a short segment L<<596.0,815.0>--<600.0,815.0>>

	* zero.superior (U+2070) contains a short segment L<<488.0,944.0>--<488.0,939.0>>

	* five.superior (U+2075) contains a short segment L<<488.0,1228.0>--<493.0,1219.0>>

	* eight.superior (U+2078) contains a short segment L<<498.0,1104.0>--<489.0,1104.0>>

	* zero.inferior (U+2080) contains a short segment L<<488.0,-131.0>--<488.0,-136.0>>

	* five.inferior (U+2085) contains a short segment L<<488.0,152.0>--<493.0,144.0>>

	* eight.inferior (U+2088) contains a short segment L<<498.0,28.0>--<489.0,28.0>>

	* trademark (U+2122) contains a short segment L<<784.0,939.0>--<784.0,942.0>>

	* lozenge (U+25CA) contains a short segment L<<604.0,1277.0>--<596.0,1277.0>> 

	* lozenge (U+25CA) contains a short segment L<<596.0,97.0>--<604.0,97.0>> [code: found-short-segments]
</div></details><br></div></details><details><summary><b>[16] KodeMono-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ i̍ i̐ i̓ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̅ i̇ i̎ i̒ i̔ i̖̅ i̖̇ i̖̊ i̖̋ i̖̍ i̖̎ i̖̐ i̖̒ i̖̓ i̖̔ i̗̅ i̗̇ i̗̊ i̗̋ i̗̍ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'KDA ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.729x (3458) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
greater_greater_equal_middle.seq, greater_greater_hyphen_middle.seq, greater_greater_hyphen_start.seq and numbersign_underscore_parenleft.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- acute.case.loclPLK

	- at.spacer

	- braceright.spacer

	- commareversedbelowcomb.case

	- l.spacer

	- parenleft.spacer

	- strokelongoverlay 

	- strokeshortoverlay
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 3	Expected: 5

	- Glyph name: Q	Contours detected: 1	Expected: 2

	- Glyph name: yen	Contours detected: 3	Expected: 1 or 2

	- Glyph name: copyright	Contours detected: 2	Expected: 3

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

	- Glyph name: trademark	Contours detected: 1	Expected: 2

	- Glyph name: notalmostequal	Contours detected: 3	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: copyright	Contours detected: 2	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: percent	Contours detected: 3	Expected: 5

	- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: trademark	Contours detected: 1	Expected: 2

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1 

	- Glyph name: yen	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 acute (U+00B4), acute.case (unencoded), acutebelowcomb (U+0317), acutecomb (U+0301), breve (U+02D8), breve.case (unencoded), brevebelowcomb (U+032E), brevecomb (U+0306), breveinvertedbelowcomb (U+032F), breveinvertedcomb (U+0311), candraBinducomb (U+0310), caroncomb (U+030C), cedilla (U+00B8), cedilla.case (unencoded), cedillacomb (U+0327), circumflex (U+02C6), circumflexbelowcomb (U+032D), circumflexcomb (U+0302), commaabovecomb (U+0313), commaaboverightcomb (U+0315), commaaccentcomb (U+0326), commaaccentcomb.salt (unencoded), commabelowcomb.case (unencoded), commareversedabovecomb (U+0314), commareversedbelowcomb.case (unencoded), commaturnedabovecomb (U+0312), dblgravecomb (U+030F), dbllowlinecomb (U+0333), dblvlinecomb (U+030E), dieresis (U+00A8), dieresis.case (unencoded), dieresisbelowcomb (U+0324), dieresiscomb (U+0308), dotaccent (U+02D9), dotaccent.case (unencoded), dotaccentcomb (U+0307), dotbelowcomb (U+0323), grave.case (unencoded), gravebelowcomb (U+0316), gravecomb (U+0300), hookabovecomb (U+0309), hungarumlaut (U+02DD), hungarumlautcomb (U+030B), lowlinecomb (U+0332), macron (U+00AF), macron.case (unencoded), macronbelowcomb (U+0331), macroncomb (U+0304), ogonek (U+02DB), ogonekcomb (U+0328), overlinecomb (U+0305), period_equal.cv32 (unencoded), quoteleft (U+2018), ring (U+02DA), ring.case (unencoded), ringbelowcomb (U+0325), ringcomb (U+030A), tilde (U+02DC), tilde.case (unencoded), tildebelowcomb (U+0330), tildecomb (U+0303), tildeoverlaycomb (U+0334), vlinebelowcomb (U+0329) and vlinecomb (U+030D) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 strokelongcomb (U+0336) and strokeshortcomb (U+0335) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+00A8, U+00AF, U+00B4, U+00B8, U+02C6, U+02D8, U+02D9, U+02DA, U+02DB, U+02DC, U+02DD and U+2018 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* g (U+0067): X=391.0,Y=1.0 (should be at baseline 0?)

	* j (U+006A): X=703.0,Y=-2.0 (should be at baseline 0?)

	* gcircumflex (U+011D): X=391.0,Y=1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=391.0,Y=1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=391.0,Y=1.0 (should be at baseline 0?)

	* gcommaaccent (U+0123): X=391.0,Y=1.0 (should be at baseline 0?)

	* jcircumflex (U+0135): X=703.0,Y=-2.0 (should be at baseline 0?)

	* jcircumflex (U+0135): X=581.0,Y=1435.0 (should be at cap-height 1433?)

	* obreve (U+014F): X=227.0,Y=1434.0 (should be at cap-height 1433?)

	* obreve (U+014F): X=973.0,Y=1434.0 (should be at cap-height 1433?)

	* umacron (U+016B): X=313.0,Y=1435.0 (should be at cap-height 1433?)

	* umacron (U+016B): X=887.0,Y=1435.0 (should be at cap-height 1433?)

	* uni01F0 (U+01F0): X=768.0,Y=-2.0 (should be at baseline 0?)

	* dotlessj (U+0237): X=768.0,Y=-2.0 (should be at baseline 0?) 

	* uni0249 (U+0249): X=703.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment L<<822.0,197.0>--<853.0,224.0>>

	* two (U+0032) contains a short segment L<<347.0,224.0>--<347.0,197.0>>

	* five (U+0035) contains a short segment L<<347.0,1007.0>--<357.0,987.0>>

	* eight (U+0038) contains a short segment L<<308.0,680.0>--<293.0,680.0>>

	* M (U+004D) contains a short segment L<<347.0,1392.0>--<347.0,1359.0>>

	* M (U+004D) contains a short segment L<<510.0,769.0>--<510.0,792.0>>

	* N (U+004E) contains a short segment L<<383.0,1168.0>--<347.0,1168.0>>

	* S (U+0053) contains a short segment L<<822.0,197.0>--<853.0,224.0>>

	* W (U+0057) contains a short segment L<<388.0,236.0>--<411.0,236.0>>

	* W (U+0057) contains a short segment L<<798.0,235.0>--<819.0,235.0>>

	* Y (U+0059) contains a short segment L<<599.0,830.0>--<603.0,830.0>>

	* Z (U+005A) contains a short segment L<<908.0,842.0>--<934.0,842.0>>

	* a (U+0061) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* w (U+0077) contains a short segment L<<402.0,232.0>--<411.0,232.0>>

	* w (U+0077) contains a short segment L<<789.0,238.0>--<795.0,238.0>>

	* x (U+0078) contains a short segment L<<318.0,493.0>--<318.0,496.0>>

	* y (U+0079) contains a short segment L<<853.0,-19.0>--<853.0,3.0>>

	* z (U+007A) contains a short segment L<<800.0,873.0>--<800.0,885.0>>

	* yen (U+00A5) contains a short segment L<<599.0,830.0>--<603.0,830.0>>

	* section (U+00A7) contains a short segment L<<763.0,197.0>--<790.0,227.0>>

	* ordfeminine (U+00AA) contains a short segment L<<374.0,870.0>--<374.0,864.0>>

	* twosuperior (U+00B2) contains a short segment L<<499.0,941.0>--<499.0,930.0>>

	* mu (U+00B5) contains a short segment L<<387.0,0.0>--<372.0,26.0>>

	* Ntilde (U+00D1) contains a short segment L<<383.0,1168.0>--<347.0,1168.0>>

	* Yacute (U+00DD) contains a short segment L<<599.0,830.0>--<603.0,830.0>>

	* agrave (U+00E0) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* aacute (U+00E1) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* acircumflex (U+00E2) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* atilde (U+00E3) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* adieresis (U+00E4) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* aring (U+00E5) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* yacute (U+00FD) contains a short segment L<<853.0,-19.0>--<853.0,3.0>>

	* ydieresis (U+00FF) contains a short segment L<<853.0,-19.0>--<853.0,3.0>>

	* amacron (U+0101) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* abreve (U+0103) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* aogonek (U+0105) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* ij (U+0133) contains a short segment L<<826.0,-41.0>--<826.0,-17.0>>

	* Nacute (U+0143) contains a short segment L<<383.0,1168.0>--<347.0,1168.0>>

	* Ncommaaccent (U+0145) contains a short segment L<<383.0,1168.0>--<347.0,1168.0>>

	* Ncaron (U+0147) contains a short segment L<<383.0,1168.0>--<347.0,1168.0>>

	* Eng (U+014A) contains a short segment L<<383.0,1168.0>--<347.0,1168.0>>

	* Sacute (U+015A) contains a short segment L<<822.0,197.0>--<853.0,224.0>>

	* Scircumflex (U+015C) contains a short segment L<<822.0,197.0>--<853.0,224.0>>

	* Scedilla (U+015E) contains a short segment L<<822.0,197.0>--<853.0,224.0>>

	* Scaron (U+0160) contains a short segment L<<822.0,197.0>--<853.0,224.0>>

	* Wcircumflex (U+0174) contains a short segment L<<388.0,236.0>--<411.0,236.0>>

	* Wcircumflex (U+0174) contains a short segment L<<798.0,235.0>--<819.0,235.0>>

	* wcircumflex (U+0175) contains a short segment L<<402.0,232.0>--<411.0,232.0>>

	* wcircumflex (U+0175) contains a short segment L<<789.0,238.0>--<795.0,238.0>>

	* Ycircumflex (U+0176) contains a short segment L<<599.0,830.0>--<603.0,830.0>>

	* ycircumflex (U+0177) contains a short segment L<<853.0,-19.0>--<853.0,3.0>>

	* Ydieresis (U+0178) contains a short segment L<<599.0,830.0>--<603.0,830.0>>

	* Zacute (U+0179) contains a short segment L<<908.0,842.0>--<934.0,842.0>>

	* zacute (U+017A) contains a short segment L<<800.0,873.0>--<800.0,885.0>>

	* Zdotaccent (U+017B) contains a short segment L<<908.0,842.0>--<934.0,842.0>>

	* zdotaccent (U+017C) contains a short segment L<<800.0,873.0>--<800.0,885.0>>

	* Zcaron (U+017D) contains a short segment L<<908.0,842.0>--<934.0,842.0>>

	* zcaron (U+017E) contains a short segment L<<800.0,873.0>--<800.0,885.0>>

	* florin (U+0192) contains a short segment L<<487.0,0.0>--<485.0,0.0>>

	* Scommaaccent (U+0218) contains a short segment L<<822.0,197.0>--<853.0,224.0>>

	* mu (U+03BC) contains a short segment L<<387.0,0.0>--<372.0,26.0>>

	* uni1E01 (U+1E01) contains a short segment L<<339.0,301.0>--<339.0,293.0>>

	* Wgrave (U+1E80) contains a short segment L<<388.0,236.0>--<411.0,236.0>>

	* Wgrave (U+1E80) contains a short segment L<<798.0,235.0>--<819.0,235.0>>

	* wgrave (U+1E81) contains a short segment L<<402.0,232.0>--<411.0,232.0>>

	* wgrave (U+1E81) contains a short segment L<<789.0,238.0>--<795.0,238.0>>

	* Wacute (U+1E82) contains a short segment L<<388.0,236.0>--<411.0,236.0>>

	* Wacute (U+1E82) contains a short segment L<<798.0,235.0>--<819.0,235.0>>

	* wacute (U+1E83) contains a short segment L<<402.0,232.0>--<411.0,232.0>>

	* wacute (U+1E83) contains a short segment L<<789.0,238.0>--<795.0,238.0>>

	* Wdieresis (U+1E84) contains a short segment L<<388.0,236.0>--<411.0,236.0>>

	* Wdieresis (U+1E84) contains a short segment L<<798.0,235.0>--<819.0,235.0>>

	* wdieresis (U+1E85) contains a short segment L<<402.0,232.0>--<411.0,232.0>>

	* wdieresis (U+1E85) contains a short segment L<<789.0,238.0>--<795.0,238.0>>

	* Ygrave (U+1EF2) contains a short segment L<<599.0,830.0>--<603.0,830.0>>

	* ygrave (U+1EF3) contains a short segment L<<853.0,-19.0>--<853.0,3.0>>

	* five.superior (U+2075) contains a short segment L<<499.0,1254.0>--<503.0,1246.0>>

	* eight.superior (U+2078) contains a short segment L<<483.0,1123.0>--<477.0,1123.0>>

	* two.inferior (U+2082) contains a short segment L<<499.0,-150.0>--<499.0,-161.0>>

	* five.inferior (U+2085) contains a short segment L<<499.0,163.0>--<503.0,155.0>>

	* eight.inferior (U+2088) contains a short segment L<<483.0,32.0>--<477.0,32.0>>

	* trademark (U+2122) contains a short segment L<<784.0,939.0>--<784.0,942.0>>

	* lozenge (U+25CA) contains a short segment L<<604.0,1212.0>--<596.0,1212.0>> 

	* lozenge (U+25CA) contains a short segment L<<596.0,157.0>--<604.0,157.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Lcaron (U+013D): L<<842.0,854.0>--<866.0,1121.0>> -> L<<866.0,1121.0>--<866.0,1388.0>>

	* dcaron (U+010F): L<<887.0,980.0>--<912.0,1247.0>> -> L<<912.0,1247.0>--<912.0,1515.0>>

	* lcaron (U+013E): L<<648.0,954.0>--<672.0,1221.0>> -> L<<672.0,1221.0>--<672.0,1488.0>> 

	* tcaron (U+0165): L<<782.0,954.0>--<807.0,1221.0>> -> L<<807.0,1221.0>--<807.0,1488.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[16] KodeMono-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ i̍ i̐ i̓ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̅ i̇ i̎ i̒ i̔ i̖̅ i̖̇ i̖̊ i̖̋ i̖̍ i̖̎ i̖̐ i̖̒ i̖̓ i̖̔ i̗̅ i̗̇ i̗̊ i̗̋ i̗̍ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'KDA ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.729x (3458) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
greater_greater_equal_middle.seq, greater_greater_hyphen_middle.seq, greater_greater_hyphen_start.seq and numbersign_underscore_parenleft.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- acute.case.loclPLK

	- at.spacer

	- braceright.spacer

	- commareversedbelowcomb.case

	- l.spacer

	- parenleft.spacer

	- strokelongoverlay 

	- strokeshortoverlay
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 3	Expected: 5

	- Glyph name: Q	Contours detected: 1	Expected: 2

	- Glyph name: yen	Contours detected: 3	Expected: 1 or 2

	- Glyph name: copyright	Contours detected: 2	Expected: 3

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

	- Glyph name: trademark	Contours detected: 1	Expected: 2

	- Glyph name: notalmostequal	Contours detected: 3	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: copyright	Contours detected: 2	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: percent	Contours detected: 3	Expected: 5

	- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: trademark	Contours detected: 1	Expected: 2

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1 

	- Glyph name: yen	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 acute (U+00B4), acute.case (unencoded), acutebelowcomb (U+0317), acutecomb (U+0301), breve (U+02D8), breve.case (unencoded), brevebelowcomb (U+032E), brevecomb (U+0306), breveinvertedbelowcomb (U+032F), breveinvertedcomb (U+0311), candraBinducomb (U+0310), caroncomb (U+030C), cedilla (U+00B8), cedilla.case (unencoded), cedillacomb (U+0327), circumflex (U+02C6), circumflexbelowcomb (U+032D), circumflexcomb (U+0302), commaabovecomb (U+0313), commaaboverightcomb (U+0315), commaaccentcomb (U+0326), commaaccentcomb.salt (unencoded), commabelowcomb.case (unencoded), commareversedabovecomb (U+0314), commareversedbelowcomb.case (unencoded), commaturnedabovecomb (U+0312), dblgravecomb (U+030F), dbllowlinecomb (U+0333), dblvlinecomb (U+030E), dieresis (U+00A8), dieresis.case (unencoded), dieresisbelowcomb (U+0324), dieresiscomb (U+0308), dotaccent (U+02D9), dotaccent.case (unencoded), dotaccentcomb (U+0307), dotbelowcomb (U+0323), grave.case (unencoded), gravebelowcomb (U+0316), gravecomb (U+0300), hookabovecomb (U+0309), hungarumlaut (U+02DD), hungarumlautcomb (U+030B), lowlinecomb (U+0332), macron (U+00AF), macron.case (unencoded), macronbelowcomb (U+0331), macroncomb (U+0304), ogonek (U+02DB), ogonekcomb (U+0328), overlinecomb (U+0305), period_equal.cv32 (unencoded), quoteleft (U+2018), ring (U+02DA), ring.case (unencoded), ringbelowcomb (U+0325), ringcomb (U+030A), tilde (U+02DC), tilde.case (unencoded), tildebelowcomb (U+0330), tildecomb (U+0303), tildeoverlaycomb (U+0334), vlinebelowcomb (U+0329) and vlinecomb (U+030D) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 strokelongcomb (U+0336) and strokeshortcomb (U+0335) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+00A8, U+00AF, U+00B4, U+00B8, U+02C6, U+02D8, U+02D9, U+02DA, U+02DB, U+02DC, U+02DD and U+2018 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* e (U+0065): X=329.0,Y=639.0 (should be at x-height 640?)

	* e (U+0065): X=644.0,Y=639.0 (should be at x-height 640?)

	* sterling (U+00A3): X=407.0,Y=1419.0 (should be at cap-height 1417?)

	* sterling (U+00A3): X=1038.0,Y=1419.0 (should be at cap-height 1417?)

	* Thorn (U+00DE): X=333.0,Y=-1.0 (should be at baseline 0?)

	* Thorn (U+00DE): X=147.0,Y=-1.0 (should be at baseline 0?)

	* eth (U+00F0): X=596.0,Y=1416.0 (should be at cap-height 1417?)

	* oslash (U+00F8): X=899.0,Y=1416.0 (should be at cap-height 1417?)

	* florin (U+0192): X=473.0,Y=1.0 (should be at baseline 0?)

	* florin (U+0192): X=472.0,Y=1.0 (should be at baseline 0?) 

	* oslashacute (U+01FF): X=899.0,Y=1416.0 (should be at cap-height 1417?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* zero (U+0030) contains a short segment L<<333.0,287.0>--<333.0,275.0>>

	* five (U+0035) contains a short segment L<<333.0,994.0>--<344.0,973.0>>

	* eight (U+0038) contains a short segment L<<326.0,675.0>--<308.0,675.0>>

	* M (U+004D) contains a short segment L<<333.0,1392.0>--<333.0,1348.0>>

	* M (U+004D) contains a short segment L<<510.0,782.0>--<510.0,795.0>>

	* W (U+0057) contains a short segment L<<362.0,190.0>--<397.0,190.0>>

	* W (U+0057) contains a short segment L<<807.0,190.0>--<842.0,190.0>>

	* Y (U+0059) contains a short segment L<<598.0,823.0>--<602.0,823.0>>

	* Z (U+005A) contains a short segment L<<877.0,828.0>--<907.0,828.0>>

	* w (U+0077) contains a short segment L<<388.0,188.0>--<397.0,188.0>>

	* w (U+0077) contains a short segment L<<803.0,192.0>--<809.0,192.0>>

	* x (U+0078) contains a short segment L<<337.0,487.0>--<337.0,490.0>>

	* y (U+0079) contains a short segment L<<867.0,-37.0>--<867.0,3.0>>

	* z (U+007A) contains a short segment L<<840.0,881.0>--<840.0,899.0>>

	* yen (U+00A5) contains a short segment L<<598.0,823.0>--<602.0,823.0>>

	* mu (U+00B5) contains a short segment L<<375.0,0.0>--<358.0,26.0>>

	* Yacute (U+00DD) contains a short segment L<<598.0,823.0>--<602.0,823.0>>

	* yacute (U+00FD) contains a short segment L<<867.0,-37.0>--<867.0,3.0>>

	* ydieresis (U+00FF) contains a short segment L<<867.0,-37.0>--<867.0,3.0>>

	* ij (U+0133) contains a short segment L<<843.0,-48.0>--<843.0,-23.0>>

	* eng (U+014B) contains a short segment L<<867.0,-5.0>--<867.0,0.0>>

	* eng (U+014B) contains a short segment L<<867.0,0.0>--<867.0,0.0>>

	* OE (U+0152) contains a short segment L<<773.0,197.0>--<749.0,171.0>>

	* Wcircumflex (U+0174) contains a short segment L<<362.0,190.0>--<397.0,190.0>>

	* Wcircumflex (U+0174) contains a short segment L<<807.0,190.0>--<842.0,190.0>>

	* wcircumflex (U+0175) contains a short segment L<<388.0,188.0>--<397.0,188.0>>

	* wcircumflex (U+0175) contains a short segment L<<803.0,192.0>--<809.0,192.0>>

	* Ycircumflex (U+0176) contains a short segment L<<598.0,823.0>--<602.0,823.0>>

	* ycircumflex (U+0177) contains a short segment L<<867.0,-37.0>--<867.0,3.0>>

	* Ydieresis (U+0178) contains a short segment L<<598.0,823.0>--<602.0,823.0>>

	* Zacute (U+0179) contains a short segment L<<877.0,828.0>--<907.0,828.0>>

	* zacute (U+017A) contains a short segment L<<840.0,881.0>--<840.0,899.0>>

	* Zdotaccent (U+017B) contains a short segment L<<877.0,828.0>--<907.0,828.0>>

	* zdotaccent (U+017C) contains a short segment L<<840.0,881.0>--<840.0,899.0>>

	* Zcaron (U+017D) contains a short segment L<<877.0,828.0>--<907.0,828.0>>

	* zcaron (U+017E) contains a short segment L<<840.0,881.0>--<840.0,899.0>>

	* florin (U+0192) contains a short segment L<<473.0,1.0>--<472.0,1.0>>

	* mu (U+03BC) contains a short segment L<<375.0,0.0>--<358.0,26.0>>

	* Wgrave (U+1E80) contains a short segment L<<362.0,190.0>--<397.0,190.0>>

	* Wgrave (U+1E80) contains a short segment L<<807.0,190.0>--<842.0,190.0>>

	* wgrave (U+1E81) contains a short segment L<<388.0,188.0>--<397.0,188.0>>

	* wgrave (U+1E81) contains a short segment L<<803.0,192.0>--<809.0,192.0>>

	* Wacute (U+1E82) contains a short segment L<<362.0,190.0>--<397.0,190.0>>

	* Wacute (U+1E82) contains a short segment L<<807.0,190.0>--<842.0,190.0>>

	* wacute (U+1E83) contains a short segment L<<388.0,188.0>--<397.0,188.0>>

	* wacute (U+1E83) contains a short segment L<<803.0,192.0>--<809.0,192.0>>

	* Wdieresis (U+1E84) contains a short segment L<<362.0,190.0>--<397.0,190.0>>

	* Wdieresis (U+1E84) contains a short segment L<<807.0,190.0>--<842.0,190.0>>

	* wdieresis (U+1E85) contains a short segment L<<388.0,188.0>--<397.0,188.0>>

	* wdieresis (U+1E85) contains a short segment L<<803.0,192.0>--<809.0,192.0>>

	* Ygrave (U+1EF2) contains a short segment L<<598.0,823.0>--<602.0,823.0>>

	* ygrave (U+1EF3) contains a short segment L<<867.0,-37.0>--<867.0,3.0>>

	* five.superior (U+2075) contains a short segment L<<493.0,1241.0>--<498.0,1233.0>>

	* eight.superior (U+2078) contains a short segment L<<490.0,1113.0>--<483.0,1113.0>>

	* five.inferior (U+2085) contains a short segment L<<493.0,158.0>--<498.0,149.0>>

	* eight.inferior (U+2088) contains a short segment L<<490.0,30.0>--<483.0,30.0>>

	* trademark (U+2122) contains a short segment L<<784.0,939.0>--<784.0,942.0>>

	* lozenge (U+25CA) contains a short segment L<<604.0,1245.0>--<596.0,1245.0>> 

	* lozenge (U+25CA) contains a short segment L<<596.0,127.0>--<604.0,127.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* longs (U+017F): L<<818.0,1542.0>--<819.0,1371.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] KodeMono-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ i̍ i̐ i̓ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: i̅ i̇ i̎ i̒ i̔ i̖̅ i̖̇ i̖̊ i̖̋ i̖̍ i̖̎ i̖̐ i̖̒ i̖̓ i̖̔ i̗̅ i̗̇ i̗̊ i̗̋ i̗̍ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 1 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'KDA ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.729x (3458) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss06 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss07 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss09 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss10 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-char length limit:
greater_greater_equal_middle.seq, greater_greater_hyphen_middle.seq, greater_greater_hyphen_start.seq and numbersign_underscore_parenleft.liga [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- acute.case.loclPLK

	- at.spacer

	- braceright.spacer

	- commareversedbelowcomb.case

	- l.spacer

	- parenleft.spacer

	- strokelongoverlay 

	- strokeshortoverlay
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 3	Expected: 5

	- Glyph name: Q	Contours detected: 1	Expected: 2

	- Glyph name: yen	Contours detected: 3	Expected: 1 or 2

	- Glyph name: copyright	Contours detected: 2	Expected: 3

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

	- Glyph name: trademark	Contours detected: 1	Expected: 2

	- Glyph name: notalmostequal	Contours detected: 3	Expected: 1

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Q	Contours detected: 1	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: copyright	Contours detected: 2	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: percent	Contours detected: 3	Expected: 5

	- Glyph name: perthousand	Contours detected: 4	Expected: 6 or 7

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: trademark	Contours detected: 1	Expected: 2

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1 

	- Glyph name: yen	Contours detected: 3	Expected: 1 or 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 acute (U+00B4), acute.case (unencoded), acutebelowcomb (U+0317), acutecomb (U+0301), breve (U+02D8), breve.case (unencoded), brevebelowcomb (U+032E), brevecomb (U+0306), breveinvertedbelowcomb (U+032F), breveinvertedcomb (U+0311), candraBinducomb (U+0310), caroncomb (U+030C), cedilla (U+00B8), cedilla.case (unencoded), cedillacomb (U+0327), circumflex (U+02C6), circumflexbelowcomb (U+032D), circumflexcomb (U+0302), commaabovecomb (U+0313), commaaboverightcomb (U+0315), commaaccentcomb (U+0326), commaaccentcomb.salt (unencoded), commabelowcomb.case (unencoded), commareversedabovecomb (U+0314), commareversedbelowcomb.case (unencoded), commaturnedabovecomb (U+0312), dblgravecomb (U+030F), dbllowlinecomb (U+0333), dblvlinecomb (U+030E), dieresis (U+00A8), dieresis.case (unencoded), dieresisbelowcomb (U+0324), dieresiscomb (U+0308), dotaccent (U+02D9), dotaccent.case (unencoded), dotaccentcomb (U+0307), dotbelowcomb (U+0323), grave.case (unencoded), gravebelowcomb (U+0316), gravecomb (U+0300), hookabovecomb (U+0309), hungarumlaut (U+02DD), hungarumlautcomb (U+030B), lowlinecomb (U+0332), macron (U+00AF), macron.case (unencoded), macronbelowcomb (U+0331), macroncomb (U+0304), ogonek (U+02DB), ogonekcomb (U+0328), overlinecomb (U+0305), period_equal.cv32 (unencoded), quoteleft (U+2018), ring (U+02DA), ring.case (unencoded), ringbelowcomb (U+0325), ringcomb (U+030A), tilde (U+02DC), tilde.case (unencoded), tildebelowcomb (U+0330), tildecomb (U+0303), tildeoverlaycomb (U+0334), vlinebelowcomb (U+0329) and vlinecomb (U+030D) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 strokelongcomb (U+0336) and strokeshortcomb (U+0335) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+00A8, U+00AF, U+00B4, U+00B8, U+02C6, U+02D8, U+02D9, U+02DA, U+02DB, U+02DC, U+02DD and U+2018 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* k (U+006B): X=528.0,Y=638.0 (should be at x-height 640?)

	* degree (U+00B0): X=833.0,Y=1448.0 (should be at cap-height 1450?)

	* degree (U+00B0): X=368.0,Y=1448.0 (should be at cap-height 1450?)

	* acircumflex (U+00E2): X=600.0,Y=1448.0 (should be at cap-height 1450?)

	* ebreve (U+0115): X=432.0,Y=1449.0 (should be at cap-height 1450?)

	* ebreve (U+0115): X=752.0,Y=1449.0 (should be at cap-height 1450?)

	* gbreve (U+011F): X=444.0,Y=1448.0 (should be at cap-height 1450?)

	* gbreve (U+011F): X=764.0,Y=1448.0 (should be at cap-height 1450?)

	* ncaron (U+0148): X=600.0,Y=1451.0 (should be at cap-height 1450?)

	* rcaron (U+0159): X=617.0,Y=1451.0 (should be at cap-height 1450?)

	* scaron (U+0161): X=585.0,Y=1451.0 (should be at cap-height 1450?)

	* zcaron (U+017E): X=600.0,Y=1451.0 (should be at cap-height 1450?)

	* ring (U+02DA): X=834.0,Y=1448.0 (should be at cap-height 1450?)

	* ring (U+02DA): X=369.0,Y=1448.0 (should be at cap-height 1450?)

	* ringcomb (U+030A): X=834.0,Y=1448.0 (should be at cap-height 1450?)

	* ringcomb (U+030A): X=369.0,Y=1448.0 (should be at cap-height 1450?)

	* perthousand (U+2030): X=719.0,Y=-1.0 (should be at baseline 0?) 

	* perthousand (U+2030): X=552.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Lcaron (U+013D): L<<840.0,825.0>--<860.0,1102.0>> -> L<<860.0,1102.0>--<860.0,1386.0>>

	* dcaron (U+010F): L<<883.0,967.0>--<903.0,1244.0>> -> L<<903.0,1244.0>--<903.0,1528.0>>

	* lcaron (U+013E): L<<663.0,927.0>--<683.0,1204.0>> -> L<<683.0,1204.0>--<683.0,1488.0>> 

	* tcaron (U+0165): L<<810.0,927.0>--<830.0,1204.0>> -> L<<830.0,1204.0>--<830.0,1488.0>> [code: found-colinear-vectors]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 8 | 54 | 482 | 25 | 364 | 0 |
| 0% | 1% | 6% | 52% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
