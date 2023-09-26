## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[10] NotoSansTakri-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, canadian-aboriginal, syriac, tai-le, math, malayalam, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+116B9 TAKRI ABBREVIATION SIGN: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `takri` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
northIndicFractionThreeSixteenths [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+116B6 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

	* dollar (U+0024): X=113.5,Y=624.0 (should be at cap-height 625?)

	* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* three (U+0033): X=137.0,Y=-1.5 (should be at baseline 0?)

	* four (U+0034): X=368.0,Y=624.0 (should be at cap-height 625?)

	* four (U+0034): X=364.0,Y=624.0 (should be at cap-height 625?)

	* eight (U+0038): X=193.5,Y=626.5 (should be at cap-height 625?)

	* eight (U+0038): X=377.0,Y=626.5 (should be at cap-height 625?)

	* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

	* A (U+0041): X=318.0,Y=624.0 (should be at cap-height 625?)

	* G (U+0047): X=537.0,Y=-1.0 (should be at baseline 0?)

	* M (U+004D): X=177.0,Y=626.0 (should be at cap-height 625?)

	* M (U+004D): X=173.0,Y=626.0 (should be at cap-height 625?)

	* S (U+0053): X=136.0,Y=-1.0 (should be at baseline 0?)

	* asciicircum (U+005E): X=276.0,Y=626.0 (should be at cap-height 625?)

	* e (U+0065): X=408.0,Y=-1.5 (should be at baseline 0?)

	* s (U+0073): X=123.5,Y=-1.0 (should be at baseline 0?)

	* w (U+0077): X=258.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=158.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=626.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=523.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=217.0,Y=-2.0 (should be at baseline 0?)

	* braceleft (U+007B): X=150.0,Y=1.0 (should be at baseline 0?)

	* Agrave (U+00C0): X=318.0,Y=624.0 (should be at cap-height 625?)

	* Aacute (U+00C1): X=318.0,Y=624.0 (should be at cap-height 625?)

	* Acircumflex (U+00C2): X=318.0,Y=624.0 (should be at cap-height 625?)

	* Atilde (U+00C3): X=318.0,Y=624.0 (should be at cap-height 625?)

	* Adieresis (U+00C4): X=318.0,Y=624.0 (should be at cap-height 625?)

	* Aring (U+00C5): X=318.0,Y=624.0 (should be at cap-height 625?)

	* germandbls (U+00DF): X=317.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=710.5,Y=-1.5 (should be at baseline 0?)

	* egrave (U+00E8): X=408.0,Y=-1.5 (should be at baseline 0?)

	* eacute (U+00E9): X=408.0,Y=-1.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=408.0,Y=-1.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=408.0,Y=-1.5 (should be at baseline 0?)

	* yacute (U+00FD): X=217.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=217.0,Y=-2.0 (should be at baseline 0?)

	* Amacron (U+0100): X=318.0,Y=624.0 (should be at cap-height 625?)

	* Abreve (U+0102): X=318.0,Y=624.0 (should be at cap-height 625?)

	* Aogonek (U+0104): X=318.0,Y=624.0 (should be at cap-height 625?)

	* emacron (U+0113): X=408.0,Y=-1.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=408.0,Y=-1.5 (should be at baseline 0?)

	* ecaron (U+011B): X=408.0,Y=-1.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=537.0,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=537.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=537.0,Y=-1.0 (should be at baseline 0?)

	* oe (U+0153): X=791.0,Y=-1.5 (should be at baseline 0?)

	* Sacute (U+015A): X=136.0,Y=-1.0 (should be at baseline 0?)

	* sacute (U+015B): X=123.5,Y=-1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=136.0,Y=-1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=123.5,Y=-1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=136.0,Y=-1.0 (should be at baseline 0?)

	* scaron (U+0161): X=123.5,Y=-1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=447.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=258.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=158.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=626.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=523.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=217.0,Y=-2.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=136.0,Y=-1.0 (should be at baseline 0?)

	* uni0219 (U+0219): X=123.5,Y=-1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=258.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=158.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=626.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=523.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=258.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=158.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=626.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=523.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=258.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=158.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=626.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=523.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=326.5,Y=-1.5 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=448.0,Y=625.5 (should be at cap-height 625?)

	* ygrave (U+1EF3): X=217.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=177.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=90.0,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=439.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=352.0,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=700.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=613.0,Y=2.0 (should be at baseline 0?)

	* Euro (U+20AC): X=468.5,Y=-0.5 (should be at baseline 0?)

	* northIndicPlaceholderMark (U+A837): X=453.0,Y=623.0 (should be at cap-height 625?)

	* ngatakr (U+1168E): X=479.0,Y=624.0 (should be at cap-height 625?)

	* catakr (U+1168F): X=407.0,Y=-1.5 (should be at baseline 0?)

	* tthatakr (U+11695): X=148.5,Y=626.0 (should be at cap-height 625?)

	* ddhatakr (U+11697): X=418.0,Y=-2.0 (should be at baseline 0?)

	* datakr (U+1169B): X=417.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* a (U+0061) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* d (U+0064) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* m (U+006D) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* n (U+006E) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* p (U+0070) contains a short segment L<<169.0,463.0>--<173.0,463.0>>

	* r (U+0072) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* u (U+0075) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Ntilde (U+00D1) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ntilde (U+00D1) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* germandbls (U+00DF) contains a short segment B<<382.0,412.0>-<382.0,399.0>-<388.5,388.0>>

	* agrave (U+00E0) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aacute (U+00E1) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* acircumflex (U+00E2) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* atilde (U+00E3) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* adieresis (U+00E4) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aring (U+00E5) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* ntilde (U+00F1) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* ugrave (U+00F9) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uacute (U+00FA) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ucircumflex (U+00FB) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* udieresis (U+00FC) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* amacron (U+0101) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* abreve (U+0103) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aogonek (U+0105) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* dcaron (U+010F) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* dcroat (U+0111) contains a short segment L<<445.0,72.0>--<441.0,72.0>>

	* Nacute (U+0143) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Nacute (U+0143) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* nacute (U+0144) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* uni0145 (U+0145) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* uni0145 (U+0145) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* uni0146 (U+0146) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Ncaron (U+0147) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ncaron (U+0147) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* ncaron (U+0148) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Eng (U+014A) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Eng (U+014A) contains a short segment L<<582.0,142.0>--<586.0,142.0>>

	* eng (U+014B) contains a short segment L<<170.0,463.0>--<175.0,463.0>>

	* racute (U+0155) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* uni0157 (U+0157) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* rcaron (U+0159) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* umacron (U+016B) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ubreve (U+016D) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uring (U+016F) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Uogonek (U+0172) contains a short segment B<<539.5,-158.5>-<551.0,-156.0>-<559.0,-155.0>>

	* uogonek (U+0173) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Wcircumflex (U+0174) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wgrave (U+1E80) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wacute (U+1E82) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wdieresis (U+1E84) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Euro (U+20AC) contains a short segment B<<184.0,390.0>-<183.0,380.0>-<183.0,371.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,371.0>-<183.0,362.0>-<183.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,352.0>-<183.0,343.0>-<183.0,332.5>>

	* Euro (U+20AC) contains a short segment B<<183.0,332.5>-<183.0,322.0>-<184.0,311.0>>

	* Euro (U+20AC) contains a short segment B<<95.0,311.0>-<94.0,323.0>-<94.0,331.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,331.0>-<94.0,339.0>-<94.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,352.0>-<94.0,363.0>-<94.5,373.5>>

	* Euro (U+20AC) contains a short segment B<<94.5,373.5>-<95.0,384.0>-<95.0,390.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>>

	* atakr (U+11680) contains a short segment B<<242.0,550.0>-<247.0,540.0>-<250.0,525.0>>

	* aatakr (U+11681) contains a short segment B<<242.0,550.0>-<247.0,540.0>-<250.0,525.0>>

	* utakr (U+11684) contains a short segment L<<288.0,318.0>--<307.0,318.0>>

	* uutakr (U+11685) contains a short segment L<<288.0,318.0>--<307.0,318.0>>

	* otakr (U+11688) contains a short segment B<<242.0,550.0>-<247.0,540.0>-<250.0,525.0>>

	* autakr (U+11689) contains a short segment B<<242.0,550.0>-<247.0,540.0>-<250.0,525.0>>

	* ghatakr (U+1168D) contains a short segment B<<59.0,396.0>-<59.0,407.0>-<60.5,417.5>>

	* ghatakr (U+1168D) contains a short segment B<<60.5,417.5>-<62.0,428.0>-<63.0,437.0>>

	* ghatakr (U+1168D) contains a short segment B<<153.0,501.0>-<153.0,490.0>-<151.5,477.5>>

	* jatakr (U+11691) contains a short segment B<<361.0,395.0>-<373.0,396.0>-<381.0,396.0>>

	* nyatakr (U+11693) contains a short segment B<<216.0,431.0>-<220.0,432.0>-<223.5,432.0>>

	* nyatakr (U+11693) contains a short segment B<<223.5,432.0>-<227.0,432.0>-<231.0,432.0>>

	* natakr (U+1169D) contains a short segment B<<226.0,471.0>-<230.0,472.0>-<233.5,472.0>>

	* natakr (U+1169D) contains a short segment B<<233.5,472.0>-<237.0,472.0>-<241.0,472.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 9 | 119 | 7 | 113 | 0 |
| 0% | 0% | 4% | 48% | 3% | 45% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
