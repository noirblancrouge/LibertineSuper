## FontBakery report

fontbakery version: 0.10.2

<details><summary><b>[8] LibertineSup-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 332, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, old-permic, canadian-aboriginal, math, tifinagh, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: math, syriac, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, syriac, gothic, tifinagh, cherokee
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: greek, elbasan, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, elbasan, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
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
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: psalter-pahlavi, batak, telugu, zanabazar-square, tagalog, tamil, gunjala-gondi, hanifi-rohingya, adlam, mahajani, syloti-nagri, takri, limbu, coptic, grantha, tai-viet, kharoshthi, new-tai-lue, siddham, marchen, gurmukhi, wancho, kannada, duployan, dogra, soyombo, khmer, tifinagh, tagbanwa, oriya, thaana, balinese, syriac, old-permic, meetei-mayek, music, yi, lao, tai-le, modi, malayalam, myanmar, osage, tirhuta, bengali, ahom, buginese, khojki, pahawh-hmong, hebrew, tibetan, sharada, sinhala, bassa-vah, javanese, hanunoo, chakma, manichaean, mongolian, mandaic, devanagari, kaithi, miao, symbols, caucasian-albanian, thai, khudawadi, bhaiksuki, kayah-li, elbasan, rejang, nko, sundanese, masaram-gondi, mende-kikakui, buhid, brahmi, phags-pa, sogdian, cham, gujarati, newa, lepcha, math
 * U+E133 : not included in any glyphset definition
 * U+E134 : not included in any glyphset definition
 * U+F0000 : not included in any glyphset definition
 * U+F0001 : not included in any glyphset definition
 * U+F0002 : not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: Obreve	Contours detected: 4	Expected: 3

	- Glyph name: obreve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: uni01EA	Contours detected: 4	Expected: 2

	- Glyph name: uni01EB	Contours detected: 4	Expected: 2

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni03A9	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: Dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni03A9	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* s (U+0073): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* sacute (U+015B): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* scaron (U+0161): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* scedilla (U+015F): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* scircumflex (U+015D): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* u (U+0075): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* uacute (U+00FA): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* ubreve (U+016D): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* ucircumflex (U+00FB): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* udieresis (U+00FC): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* ugrave (U+00F9): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* uhungarumlaut (U+0171): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* umacron (U+016B): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* uni0219 (U+0219): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* uni0233 (U+0233): L<<253.0,-5.0>--<248.0,-5.0>> -> L<<248.0,-5.0>--<235.0,-5.0>>

	* uni1E61 (U+1E61): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* uni1E63 (U+1E63): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* uni1E65 (U+1E65): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* uni1E67 (U+1E67): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* uni1E69 (U+1E69): L<<33.0,99.0>--<33.0,99.0>> -> L<<33.0,99.0>--<33.0,99.0>>

	* uni1E79 (U+1E79): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* uni1E7B (U+1E7B): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* uni1E8F (U+1E8F): L<<253.0,-5.0>--<248.0,-5.0>> -> L<<248.0,-5.0>--<235.0,-5.0>>

	* uni1EE5 (U+1EE5): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* uni1EF9 (U+1EF9): L<<253.0,-5.0>--<248.0,-5.0>> -> L<<248.0,-5.0>--<235.0,-5.0>>

	* uogonek (U+0173): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* uring (U+016F): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* utilde (U+0169): L<<392.0,243.0>--<392.0,249.0>> -> L<<392.0,249.0>--<392.0,505.0>>

	* y (U+0079): L<<253.0,-5.0>--<248.0,-5.0>> -> L<<248.0,-5.0>--<235.0,-5.0>>

	* yacute (U+00FD): L<<253.0,-5.0>--<248.0,-5.0>> -> L<<248.0,-5.0>--<235.0,-5.0>>

	* ycircumflex (U+0177): L<<253.0,-5.0>--<248.0,-5.0>> -> L<<248.0,-5.0>--<235.0,-5.0>>

	* ydieresis (U+00FF): L<<253.0,-5.0>--<248.0,-5.0>> -> L<<248.0,-5.0>--<235.0,-5.0>>

	* ygrave (U+1EF3): L<<253.0,-5.0>--<248.0,-5.0>> -> L<<248.0,-5.0>--<235.0,-5.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo (U+F0000): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* logo_full (U+F0001): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo_full (U+F0001): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* uni03A9 (U+03A9): B<<255.0,-5.0>-<254.0,-5.0>-<256.0,-5.0>>/B<<256.0,-5.0>-<252.0,-6.0>-<249.0,-6.0>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<392.0,43.0>--<391.0,376.0>>

	* h (U+0068): L<<480.0,376.0>--<481.0,43.0>>

	* hbar (U+0127): L<<427.0,43.0>--<426.0,376.0>>

	* hbar (U+0127): L<<515.0,376.0>--<516.0,43.0>>

	* hcircumflex (U+0125): L<<392.0,43.0>--<391.0,376.0>>

	* hcircumflex (U+0125): L<<480.0,376.0>--<481.0,43.0>>

	* m (U+006D): L<<378.0,44.0>--<377.0,273.0>>

	* m (U+006D): L<<700.0,44.0>--<699.0,273.0>>

	* t (U+0074): L<<117.0,137.0>--<118.0,309.0>>

	* t (U+0074): L<<207.0,309.0>--<206.0,151.0>>

	* tcaron (U+0165): L<<117.0,137.0>--<118.0,309.0>>

	* tcaron (U+0165): L<<207.0,309.0>--<206.0,151.0>>

	* tmacronbelow (U+1E6F): L<<117.0,137.0>--<118.0,309.0>>

	* tmacronbelow (U+1E6F): L<<207.0,309.0>--<206.0,151.0>>

	* uni0163 (U+0163): L<<117.0,137.0>--<118.0,309.0>>

	* uni0163 (U+0163): L<<207.0,309.0>--<206.0,151.0>>

	* uni021B (U+021B): L<<117.0,137.0>--<118.0,309.0>>

	* uni021B (U+021B): L<<207.0,309.0>--<206.0,151.0>>

	* uni0233 (U+0233): L<<145.0,505.0>--<146.0,171.0>>

	* uni0233 (U+0233): L<<57.0,171.0>--<56.0,505.0>>

	* uni1E25 (U+1E25): L<<392.0,43.0>--<391.0,376.0>>

	* uni1E25 (U+1E25): L<<480.0,376.0>--<481.0,43.0>>

	* uni1E2B (U+1E2B): L<<392.0,43.0>--<391.0,376.0>>

	* uni1E2B (U+1E2B): L<<480.0,376.0>--<481.0,43.0>>

	* uni1E43 (U+1E43): L<<378.0,44.0>--<377.0,273.0>>

	* uni1E43 (U+1E43): L<<700.0,44.0>--<699.0,273.0>>

	* uni1E6D (U+1E6D): L<<117.0,137.0>--<118.0,309.0>>

	* uni1E6D (U+1E6D): L<<207.0,309.0>--<206.0,151.0>>

	* uni1E8F (U+1E8F): L<<145.0,505.0>--<146.0,171.0>>

	* uni1E8F (U+1E8F): L<<57.0,171.0>--<56.0,505.0>>

	* uni1E97 (U+1E97): L<<117.0,137.0>--<118.0,309.0>>

	* uni1E97 (U+1E97): L<<207.0,309.0>--<206.0,151.0>>

	* uni1E9E (U+1E9E): L<<66.0,45.0>--<67.0,655.0>>

	* uni1EF9 (U+1EF9): L<<145.0,505.0>--<146.0,171.0>>

	* uni1EF9 (U+1EF9): L<<57.0,171.0>--<56.0,505.0>>

	* y (U+0079): L<<145.0,505.0>--<146.0,171.0>>

	* y (U+0079): L<<57.0,171.0>--<56.0,505.0>>

	* yacute (U+00FD): L<<145.0,505.0>--<146.0,171.0>>

	* yacute (U+00FD): L<<57.0,171.0>--<56.0,505.0>>

	* ycircumflex (U+0177): L<<145.0,505.0>--<146.0,171.0>>

	* ycircumflex (U+0177): L<<57.0,171.0>--<56.0,505.0>>

	* ydieresis (U+00FF): L<<145.0,505.0>--<146.0,171.0>>

	* ydieresis (U+00FF): L<<57.0,171.0>--<56.0,505.0>>

	* ygrave (U+1EF3): L<<145.0,505.0>--<146.0,171.0>>

	* ygrave (U+1EF3): L<<57.0,171.0>--<56.0,505.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] LibertineSup-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 332, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, old-permic, canadian-aboriginal, math, tifinagh, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: math, syriac, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, syriac, gothic, tifinagh, cherokee
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: greek, elbasan, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, elbasan, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
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
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: psalter-pahlavi, batak, telugu, zanabazar-square, tagalog, tamil, gunjala-gondi, hanifi-rohingya, adlam, mahajani, syloti-nagri, takri, limbu, coptic, grantha, tai-viet, kharoshthi, new-tai-lue, siddham, marchen, gurmukhi, wancho, kannada, duployan, dogra, soyombo, khmer, tifinagh, tagbanwa, oriya, thaana, balinese, syriac, old-permic, meetei-mayek, music, yi, lao, tai-le, modi, malayalam, myanmar, osage, tirhuta, bengali, ahom, buginese, khojki, pahawh-hmong, hebrew, tibetan, sharada, sinhala, bassa-vah, javanese, hanunoo, chakma, manichaean, mongolian, mandaic, devanagari, kaithi, miao, symbols, caucasian-albanian, thai, khudawadi, bhaiksuki, kayah-li, elbasan, rejang, nko, sundanese, masaram-gondi, mende-kikakui, buhid, brahmi, phags-pa, sogdian, cham, gujarati, newa, lepcha, math
 * U+E133 : not included in any glyphset definition
 * U+E134 : not included in any glyphset definition
 * U+F0000 : not included in any glyphset definition
 * U+F0001 : not included in any glyphset definition
 * U+F0002 : not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 5	Expected: 3

	- Glyph name: abreve	Contours detected: 5	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: ebreve	Contours detected: 5	Expected: 3

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: gbreve	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Ibreve	Contours detected: 3	Expected: 2

	- Glyph name: ibreve	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: Obreve	Contours detected: 5	Expected: 3

	- Glyph name: obreve	Contours detected: 5	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 4	Expected: 2

	- Glyph name: ubreve	Contours detected: 4	Expected: 2

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: uni01EA	Contours detected: 4	Expected: 2

	- Glyph name: uni01EB	Contours detected: 4	Expected: 2

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: breve	Contours detected: 2	Expected: 1

	- Glyph name: uni0306	Contours detected: 2	Expected: 1

	- Glyph name: uni032E	Contours detected: 2	Expected: 1

	- Glyph name: uni03A9	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: Dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 6	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 4	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 5	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Ebreve	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Ibreve	Contours detected: 3	Expected: 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 4	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 5	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: breve	Contours detected: 2	Expected: 1

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 5	Expected: 3

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: gbreve	Contours detected: 5	Expected: 3 or 4

	- Glyph name: ibreve	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 4	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni0306	Contours detected: 2	Expected: 1

	- Glyph name: uni032E	Contours detected: 2	Expected: 1

	- Glyph name: uni03A9	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 4	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 6	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 4	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo (U+F0000): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* logo_full (U+F0001): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo_full (U+F0001): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* uni03A9 (U+03A9): B<<270.5,-5.5>-<269.0,-6.0>-<271.0,-5.0>>/B<<271.0,-5.0>-<267.0,-6.0>-<262.0,-6.0>> = 12.528807709151492 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<397.0,54.0>--<396.0,375.0>>

	* h (U+0068): L<<509.0,375.0>--<510.0,54.0>>

	* hbar (U+0127): L<<444.0,54.0>--<443.0,375.0>>

	* hbar (U+0127): L<<556.0,375.0>--<557.0,54.0>>

	* hcircumflex (U+0125): L<<397.0,54.0>--<396.0,375.0>>

	* hcircumflex (U+0125): L<<509.0,375.0>--<510.0,54.0>>

	* m (U+006D): L<<821.0,375.0>--<822.0,55.0>>

	* uni0233 (U+0233): L<<169.0,498.0>--<170.0,178.0>>

	* uni0233 (U+0233): L<<57.0,178.0>--<56.0,498.0>>

	* uni1E25 (U+1E25): L<<397.0,54.0>--<396.0,375.0>>

	* uni1E25 (U+1E25): L<<509.0,375.0>--<510.0,54.0>>

	* uni1E2B (U+1E2B): L<<397.0,54.0>--<396.0,375.0>>

	* uni1E2B (U+1E2B): L<<509.0,375.0>--<510.0,54.0>>

	* uni1E43 (U+1E43): L<<821.0,375.0>--<822.0,55.0>>

	* uni1E8F (U+1E8F): L<<169.0,498.0>--<170.0,178.0>>

	* uni1E8F (U+1E8F): L<<57.0,178.0>--<56.0,498.0>>

	* uni1E9E (U+1E9E): L<<179.0,587.0>--<178.0,56.0>>

	* uni1E9E (U+1E9E): L<<66.0,56.0>--<67.0,644.0>>

	* uni1EF9 (U+1EF9): L<<169.0,498.0>--<170.0,178.0>>

	* uni1EF9 (U+1EF9): L<<57.0,178.0>--<56.0,498.0>>

	* y (U+0079): L<<169.0,498.0>--<170.0,178.0>>

	* y (U+0079): L<<57.0,178.0>--<56.0,498.0>>

	* yacute (U+00FD): L<<169.0,498.0>--<170.0,178.0>>

	* yacute (U+00FD): L<<57.0,178.0>--<56.0,498.0>>

	* ycircumflex (U+0177): L<<169.0,498.0>--<170.0,178.0>>

	* ycircumflex (U+0177): L<<57.0,178.0>--<56.0,498.0>>

	* ydieresis (U+00FF): L<<169.0,498.0>--<170.0,178.0>>

	* ydieresis (U+00FF): L<<57.0,178.0>--<56.0,498.0>>

	* ygrave (U+1EF3): L<<169.0,498.0>--<170.0,178.0>>

	* ygrave (U+1EF3): L<<57.0,178.0>--<56.0,498.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] LibertineSup-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 332, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, old-permic, canadian-aboriginal, math, tifinagh, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: math, syriac, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, syriac, gothic, tifinagh, cherokee
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: greek, elbasan, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, elbasan, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
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
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: psalter-pahlavi, batak, telugu, zanabazar-square, tagalog, tamil, gunjala-gondi, hanifi-rohingya, adlam, mahajani, syloti-nagri, takri, limbu, coptic, grantha, tai-viet, kharoshthi, new-tai-lue, siddham, marchen, gurmukhi, wancho, kannada, duployan, dogra, soyombo, khmer, tifinagh, tagbanwa, oriya, thaana, balinese, syriac, old-permic, meetei-mayek, music, yi, lao, tai-le, modi, malayalam, myanmar, osage, tirhuta, bengali, ahom, buginese, khojki, pahawh-hmong, hebrew, tibetan, sharada, sinhala, bassa-vah, javanese, hanunoo, chakma, manichaean, mongolian, mandaic, devanagari, kaithi, miao, symbols, caucasian-albanian, thai, khudawadi, bhaiksuki, kayah-li, elbasan, rejang, nko, sundanese, masaram-gondi, mende-kikakui, buhid, brahmi, phags-pa, sogdian, cham, gujarati, newa, lepcha, math
 * U+E133 : not included in any glyphset definition
 * U+E134 : not included in any glyphset definition
 * U+F0000 : not included in any glyphset definition
 * U+F0001 : not included in any glyphset definition
 * U+F0002 : not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: Obreve	Contours detected: 4	Expected: 3

	- Glyph name: obreve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: uni01EA	Contours detected: 4	Expected: 2

	- Glyph name: uni01EB	Contours detected: 4	Expected: 2

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni03A9	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: Dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 10	Expected: 6 or 7

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: perthousand	Contours detected: 10	Expected: 6 or 7

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni03A9	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<394.0,274.0>--<221.0,274.0>> -> L<<221.0,274.0>--<216.0,274.0>>

	* AEacute (U+01FC): L<<394.0,274.0>--<221.0,274.0>> -> L<<221.0,274.0>--<216.0,274.0>>

	* s (U+0073): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* sacute (U+015B): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* scaron (U+0161): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* scedilla (U+015F): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* scircumflex (U+015D): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* thorn (U+00FE): L<<252.0,49.0>--<257.0,49.0>> -> L<<257.0,49.0>--<269.0,49.0>>

	* thorn (U+00FE): L<<269.0,491.0>--<257.0,491.0>> -> L<<257.0,491.0>--<252.0,491.0>>

	* uni0219 (U+0219): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* uni1E61 (U+1E61): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* uni1E63 (U+1E63): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* uni1E65 (U+1E65): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* uni1E67 (U+1E67): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>>

	* uni1E69 (U+1E69): L<<33.0,85.0>--<33.0,85.0>> -> L<<33.0,85.0>--<33.0,85.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo (U+F0000): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* logo_full (U+F0001): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo_full (U+F0001): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* uni1E93 (U+1E93): B<<28.5,21.0>-<28.0,23.0>-<29.0,21.0>>/B<<29.0,21.0>-<28.0,24.0>-<28.0,27.0>> = 8.13010235415587

	* z (U+007A): B<<28.5,21.0>-<28.0,23.0>-<29.0,21.0>>/B<<29.0,21.0>-<28.0,24.0>-<28.0,27.0>> = 8.13010235415587

	* zacute (U+017A): B<<28.5,21.0>-<28.0,23.0>-<29.0,21.0>>/B<<29.0,21.0>-<28.0,24.0>-<28.0,27.0>> = 8.13010235415587

	* zcaron (U+017E): B<<28.5,21.0>-<28.0,23.0>-<29.0,21.0>>/B<<29.0,21.0>-<28.0,24.0>-<28.0,27.0>> = 8.13010235415587

	* zdotaccent (U+017C): B<<28.5,21.0>-<28.0,23.0>-<29.0,21.0>>/B<<29.0,21.0>-<28.0,24.0>-<28.0,27.0>> = 8.13010235415587 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<384.0,26.0>--<383.0,378.0>>

	* h (U+0068): L<<437.0,378.0>--<438.0,26.0>>

	* hbar (U+0127): L<<402.0,26.0>--<401.0,378.0>>

	* hbar (U+0127): L<<454.0,378.0>--<455.0,26.0>>

	* hcircumflex (U+0125): L<<384.0,26.0>--<383.0,378.0>>

	* hcircumflex (U+0125): L<<437.0,378.0>--<438.0,26.0>>

	* m (U+006D): L<<371.0,27.0>--<370.0,306.0>>

	* m (U+006D): L<<738.0,378.0>--<739.0,27.0>>

	* t (U+0074): L<<170.0,673.0>--<169.0,541.0>>

	* tbar (U+0167): L<<170.0,673.0>--<169.0,541.0>>

	* tcaron (U+0165): L<<170.0,673.0>--<169.0,541.0>>

	* tmacronbelow (U+1E6F): L<<170.0,673.0>--<169.0,541.0>>

	* uni0163 (U+0163): L<<170.0,673.0>--<169.0,541.0>>

	* uni021B (U+021B): L<<170.0,673.0>--<169.0,541.0>>

	* uni0233 (U+0233): L<<110.0,514.0>--<111.0,162.0>>

	* uni0233 (U+0233): L<<57.0,162.0>--<56.0,514.0>>

	* uni1E25 (U+1E25): L<<384.0,26.0>--<383.0,378.0>>

	* uni1E25 (U+1E25): L<<437.0,378.0>--<438.0,26.0>>

	* uni1E2B (U+1E2B): L<<384.0,26.0>--<383.0,378.0>>

	* uni1E2B (U+1E2B): L<<437.0,378.0>--<438.0,26.0>>

	* uni1E43 (U+1E43): L<<371.0,27.0>--<370.0,306.0>>

	* uni1E43 (U+1E43): L<<738.0,378.0>--<739.0,27.0>>

	* uni1E6D (U+1E6D): L<<170.0,673.0>--<169.0,541.0>>

	* uni1E8F (U+1E8F): L<<110.0,514.0>--<111.0,162.0>>

	* uni1E8F (U+1E8F): L<<57.0,162.0>--<56.0,514.0>>

	* uni1E97 (U+1E97): L<<170.0,673.0>--<169.0,541.0>>

	* uni1E9E (U+1E9E): L<<120.0,646.0>--<119.0,27.0>>

	* uni1E9E (U+1E9E): L<<66.0,27.0>--<67.0,673.0>>

	* uni1EF9 (U+1EF9): L<<110.0,514.0>--<111.0,162.0>>

	* uni1EF9 (U+1EF9): L<<57.0,162.0>--<56.0,514.0>>

	* y (U+0079): L<<110.0,514.0>--<111.0,162.0>>

	* y (U+0079): L<<57.0,162.0>--<56.0,514.0>>

	* yacute (U+00FD): L<<110.0,514.0>--<111.0,162.0>>

	* yacute (U+00FD): L<<57.0,162.0>--<56.0,514.0>>

	* ycircumflex (U+0177): L<<110.0,514.0>--<111.0,162.0>>

	* ycircumflex (U+0177): L<<57.0,162.0>--<56.0,514.0>>

	* ydieresis (U+00FF): L<<110.0,514.0>--<111.0,162.0>>

	* ydieresis (U+00FF): L<<57.0,162.0>--<56.0,514.0>>

	* ygrave (U+1EF3): L<<110.0,514.0>--<111.0,162.0>>

	* ygrave (U+1EF3): L<<57.0,162.0>--<56.0,514.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] LibertineSup-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 332, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, old-permic, canadian-aboriginal, math, tifinagh, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: math, syriac, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, syriac, gothic, tifinagh, cherokee
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: greek, elbasan, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, elbasan, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
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
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: psalter-pahlavi, batak, telugu, zanabazar-square, tagalog, tamil, gunjala-gondi, hanifi-rohingya, adlam, mahajani, syloti-nagri, takri, limbu, coptic, grantha, tai-viet, kharoshthi, new-tai-lue, siddham, marchen, gurmukhi, wancho, kannada, duployan, dogra, soyombo, khmer, tifinagh, tagbanwa, oriya, thaana, balinese, syriac, old-permic, meetei-mayek, music, yi, lao, tai-le, modi, malayalam, myanmar, osage, tirhuta, bengali, ahom, buginese, khojki, pahawh-hmong, hebrew, tibetan, sharada, sinhala, bassa-vah, javanese, hanunoo, chakma, manichaean, mongolian, mandaic, devanagari, kaithi, miao, symbols, caucasian-albanian, thai, khudawadi, bhaiksuki, kayah-li, elbasan, rejang, nko, sundanese, masaram-gondi, mende-kikakui, buhid, brahmi, phags-pa, sogdian, cham, gujarati, newa, lepcha, math
 * U+E133 : not included in any glyphset definition
 * U+E134 : not included in any glyphset definition
 * U+F0000 : not included in any glyphset definition
 * U+F0001 : not included in any glyphset definition
 * U+F0002 : not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: Obreve	Contours detected: 4	Expected: 3

	- Glyph name: obreve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: uni01EA	Contours detected: 4	Expected: 2

	- Glyph name: uni01EB	Contours detected: 4	Expected: 2

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni03A9	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: Dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 10	Expected: 6 or 7

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: perthousand	Contours detected: 10	Expected: 6 or 7

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni03A9	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* d (U+0064): L<<254.0,60.0>--<267.0,60.0>> -> L<<267.0,60.0>--<271.0,60.0>>

	* d (U+0064): L<<271.0,482.0>--<267.0,482.0>> -> L<<267.0,482.0>--<254.0,482.0>>

	* dcaron (U+010F): L<<254.0,60.0>--<267.0,60.0>> -> L<<267.0,60.0>--<271.0,60.0>>

	* dcaron (U+010F): L<<271.0,482.0>--<267.0,482.0>> -> L<<267.0,482.0>--<254.0,482.0>>

	* dcroat (U+0111): L<<254.0,60.0>--<267.0,60.0>> -> L<<267.0,60.0>--<271.0,60.0>>

	* dcroat (U+0111): L<<271.0,482.0>--<267.0,482.0>> -> L<<267.0,482.0>--<254.0,482.0>>

	* dmacronbelow (U+1E0F): L<<254.0,60.0>--<267.0,60.0>> -> L<<267.0,60.0>--<271.0,60.0>>

	* dmacronbelow (U+1E0F): L<<271.0,482.0>--<267.0,482.0>> -> L<<267.0,482.0>--<254.0,482.0>>

	* g (U+0067): L<<271.0,-5.0>--<267.0,-5.0>> -> L<<267.0,-5.0>--<254.0,-5.0>>

	* gbreve (U+011F): L<<271.0,-5.0>--<267.0,-5.0>> -> L<<267.0,-5.0>--<254.0,-5.0>>

	* gcaron (U+01E7): L<<271.0,-5.0>--<267.0,-5.0>> -> L<<267.0,-5.0>--<254.0,-5.0>>

	* gcircumflex (U+011D): L<<271.0,-5.0>--<267.0,-5.0>> -> L<<267.0,-5.0>--<254.0,-5.0>>

	* gdotaccent (U+0121): L<<271.0,-5.0>--<267.0,-5.0>> -> L<<267.0,-5.0>--<254.0,-5.0>>

	* p (U+0070): L<<262.0,60.0>--<264.0,60.0>> -> L<<264.0,60.0>--<276.0,60.0>>

	* p (U+0070): L<<276.0,482.0>--<264.0,482.0>> -> L<<264.0,482.0>--<262.0,482.0>>

	* q (U+0071): L<<271.0,-5.0>--<267.0,-5.0>> -> L<<267.0,-5.0>--<254.0,-5.0>>

	* s (U+0073): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* sacute (U+015B): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* scaron (U+0161): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* scedilla (U+015F): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* scircumflex (U+015D): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* uni0123 (U+0123): L<<271.0,-5.0>--<267.0,-5.0>> -> L<<267.0,-5.0>--<254.0,-5.0>>

	* uni0219 (U+0219): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* uni1E0D (U+1E0D): L<<254.0,60.0>--<267.0,60.0>> -> L<<267.0,60.0>--<271.0,60.0>>

	* uni1E0D (U+1E0D): L<<271.0,482.0>--<267.0,482.0>> -> L<<267.0,482.0>--<254.0,482.0>>

	* uni1E21 (U+1E21): L<<271.0,-5.0>--<267.0,-5.0>> -> L<<267.0,-5.0>--<254.0,-5.0>>

	* uni1E61 (U+1E61): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* uni1E63 (U+1E63): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* uni1E65 (U+1E65): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* uni1E67 (U+1E67): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>>

	* uni1E69 (U+1E69): L<<33.0,90.0>--<33.0,90.0>> -> L<<33.0,90.0>--<33.0,90.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo (U+F0000): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* logo_full (U+F0001): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo_full (U+F0001): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* perthousand (U+2030): B<<170.5,258.0>-<176.0,288.0>-<188.0,312.0>>/L<<188.0,312.0>--<49.0,120.0>> = 9.337920897121688

	* perthousand (U+2030): B<<308.0,198.0>-<308.0,224.0>-<312.0,248.0>>/L<<312.0,248.0>--<251.0,38.0>> = 6.735000748127188

	* perthousand (U+2030): L<<330.0,312.0>--<329.0,308.0>>/B<<329.0,308.0>-<330.0,310.0>-<331.0,312.0>> = 12.528807709151492

	* perthousand (U+2030): L<<451.0,676.0>--<212.0,346.0>>/B<<212.0,346.0>-<225.0,357.0>-<241.0,364.0>> = 13.84999128414955 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<387.0,31.0>--<386.0,378.0>>

	* h (U+0068): L<<451.0,378.0>--<452.0,31.0>>

	* hbar (U+0127): L<<410.0,31.0>--<409.0,378.0>>

	* hbar (U+0127): L<<475.0,378.0>--<476.0,31.0>>

	* hcircumflex (U+0125): L<<387.0,31.0>--<386.0,378.0>>

	* hcircumflex (U+0125): L<<451.0,378.0>--<452.0,31.0>>

	* m (U+006D): L<<373.0,32.0>--<372.0,295.0>>

	* m (U+006D): L<<690.0,32.0>--<689.0,295.0>>

	* m (U+006D): L<<754.0,378.0>--<755.0,32.0>>

	* t (U+0074): L<<116.0,543.0>--<117.0,667.0>>

	* t (U+0074): L<<182.0,341.0>--<181.0,138.0>>

	* tbar (U+0167): L<<116.0,543.0>--<117.0,667.0>>

	* tcaron (U+0165): L<<116.0,543.0>--<117.0,667.0>>

	* tcaron (U+0165): L<<182.0,341.0>--<181.0,138.0>>

	* tmacronbelow (U+1E6F): L<<116.0,543.0>--<117.0,667.0>>

	* tmacronbelow (U+1E6F): L<<182.0,341.0>--<181.0,138.0>>

	* uni0163 (U+0163): L<<116.0,543.0>--<117.0,667.0>>

	* uni0163 (U+0163): L<<182.0,341.0>--<181.0,138.0>>

	* uni021B (U+021B): L<<116.0,543.0>--<117.0,667.0>>

	* uni021B (U+021B): L<<182.0,341.0>--<181.0,138.0>>

	* uni0233 (U+0233): L<<122.0,511.0>--<123.0,165.0>>

	* uni0233 (U+0233): L<<57.0,165.0>--<56.0,511.0>>

	* uni1E25 (U+1E25): L<<387.0,31.0>--<386.0,378.0>>

	* uni1E25 (U+1E25): L<<451.0,378.0>--<452.0,31.0>>

	* uni1E2B (U+1E2B): L<<387.0,31.0>--<386.0,378.0>>

	* uni1E2B (U+1E2B): L<<451.0,378.0>--<452.0,31.0>>

	* uni1E43 (U+1E43): L<<373.0,32.0>--<372.0,295.0>>

	* uni1E43 (U+1E43): L<<690.0,32.0>--<689.0,295.0>>

	* uni1E43 (U+1E43): L<<754.0,378.0>--<755.0,32.0>>

	* uni1E6D (U+1E6D): L<<116.0,543.0>--<117.0,667.0>>

	* uni1E6D (U+1E6D): L<<182.0,341.0>--<181.0,138.0>>

	* uni1E8F (U+1E8F): L<<122.0,511.0>--<123.0,165.0>>

	* uni1E8F (U+1E8F): L<<57.0,165.0>--<56.0,511.0>>

	* uni1E97 (U+1E97): L<<116.0,543.0>--<117.0,667.0>>

	* uni1E97 (U+1E97): L<<182.0,341.0>--<181.0,138.0>>

	* uni1E9E (U+1E9E): L<<132.0,634.0>--<131.0,33.0>>

	* uni1E9E (U+1E9E): L<<66.0,33.0>--<67.0,667.0>>

	* uni1EF9 (U+1EF9): L<<122.0,511.0>--<123.0,165.0>>

	* uni1EF9 (U+1EF9): L<<57.0,165.0>--<56.0,511.0>>

	* y (U+0079): L<<122.0,511.0>--<123.0,165.0>>

	* y (U+0079): L<<57.0,165.0>--<56.0,511.0>>

	* yacute (U+00FD): L<<122.0,511.0>--<123.0,165.0>>

	* yacute (U+00FD): L<<57.0,165.0>--<56.0,511.0>>

	* ycircumflex (U+0177): L<<122.0,511.0>--<123.0,165.0>>

	* ycircumflex (U+0177): L<<57.0,165.0>--<56.0,511.0>>

	* ydieresis (U+00FF): L<<122.0,511.0>--<123.0,165.0>>

	* ydieresis (U+00FF): L<<57.0,165.0>--<56.0,511.0>>

	* ygrave (U+1EF3): L<<122.0,511.0>--<123.0,165.0>>

	* ygrave (U+1EF3): L<<57.0,165.0>--<56.0,511.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] LibertineSup-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 332, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, old-permic, canadian-aboriginal, math, tifinagh, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: math, syriac, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, syriac, gothic, tifinagh, cherokee
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: greek, elbasan, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, elbasan, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
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
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: psalter-pahlavi, batak, telugu, zanabazar-square, tagalog, tamil, gunjala-gondi, hanifi-rohingya, adlam, mahajani, syloti-nagri, takri, limbu, coptic, grantha, tai-viet, kharoshthi, new-tai-lue, siddham, marchen, gurmukhi, wancho, kannada, duployan, dogra, soyombo, khmer, tifinagh, tagbanwa, oriya, thaana, balinese, syriac, old-permic, meetei-mayek, music, yi, lao, tai-le, modi, malayalam, myanmar, osage, tirhuta, bengali, ahom, buginese, khojki, pahawh-hmong, hebrew, tibetan, sharada, sinhala, bassa-vah, javanese, hanunoo, chakma, manichaean, mongolian, mandaic, devanagari, kaithi, miao, symbols, caucasian-albanian, thai, khudawadi, bhaiksuki, kayah-li, elbasan, rejang, nko, sundanese, masaram-gondi, mende-kikakui, buhid, brahmi, phags-pa, sogdian, cham, gujarati, newa, lepcha, math
 * U+E133 : not included in any glyphset definition
 * U+E134 : not included in any glyphset definition
 * U+F0000 : not included in any glyphset definition
 * U+F0001 : not included in any glyphset definition
 * U+F0002 : not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: Obreve	Contours detected: 4	Expected: 3

	- Glyph name: obreve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: uni01EA	Contours detected: 4	Expected: 2

	- Glyph name: uni01EB	Contours detected: 4	Expected: 2

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: Dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 12	Expected: 6 or 7

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: perthousand	Contours detected: 12	Expected: 6 or 7

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* s (U+0073): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* sacute (U+015B): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* scaron (U+0161): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* scedilla (U+015F): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* scircumflex (U+015D): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* uni0219 (U+0219): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* uni1E61 (U+1E61): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* uni1E63 (U+1E63): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* uni1E65 (U+1E65): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* uni1E67 (U+1E67): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>>

	* uni1E69 (U+1E69): L<<33.0,71.0>--<33.0,71.0>> -> L<<33.0,71.0>--<33.0,71.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo (U+F0000): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* logo_full (U+F0001): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo_full (U+F0001): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* ordmasculine (U+00BA): B<<187.0,650.5>-<167.0,686.0>-<131.0,692.0>>/L<<131.0,692.0>--<131.0,692.0>> = 9.462322208025613

	* ordmasculine (U+00BA): L<<131.0,692.0>--<131.0,692.0>>/B<<131.0,692.0>-<96.0,684.0>-<77.0,648.5>> = 12.875001559612462 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<377.0,8.0>--<376.0,380.0>>

	* hbar (U+0127): L<<377.0,8.0>--<376.0,380.0>>

	* hcircumflex (U+0125): L<<377.0,8.0>--<376.0,380.0>>

	* m (U+006D): L<<364.0,9.0>--<363.0,340.0>>

	* m (U+006D): L<<671.0,9.0>--<670.0,340.0>>

	* m (U+006D): L<<688.0,380.0>--<689.0,9.0>>

	* t (U+0074): L<<112.0,113.0>--<113.0,404.0>>

	* t (U+0074): L<<132.0,404.0>--<131.0,113.0>>

	* tbar (U+0167): L<<112.0,113.0>--<113.0,248.0>>

	* tbar (U+0167): L<<132.0,404.0>--<131.0,267.0>>

	* tcaron (U+0165): L<<112.0,113.0>--<113.0,404.0>>

	* tcaron (U+0165): L<<132.0,404.0>--<131.0,113.0>>

	* tmacronbelow (U+1E6F): L<<112.0,113.0>--<113.0,404.0>>

	* tmacronbelow (U+1E6F): L<<132.0,404.0>--<131.0,113.0>>

	* uni0163 (U+0163): L<<112.0,113.0>--<113.0,404.0>>

	* uni0163 (U+0163): L<<132.0,404.0>--<131.0,113.0>>

	* uni021B (U+021B): L<<112.0,113.0>--<113.0,404.0>>

	* uni021B (U+021B): L<<132.0,404.0>--<131.0,113.0>>

	* uni0233 (U+0233): L<<57.0,152.0>--<56.0,523.0>>

	* uni0233 (U+0233): L<<75.0,523.0>--<76.0,152.0>>

	* uni1E25 (U+1E25): L<<377.0,8.0>--<376.0,380.0>>

	* uni1E2B (U+1E2B): L<<377.0,8.0>--<376.0,380.0>>

	* uni1E43 (U+1E43): L<<364.0,9.0>--<363.0,340.0>>

	* uni1E43 (U+1E43): L<<671.0,9.0>--<670.0,340.0>>

	* uni1E43 (U+1E43): L<<688.0,380.0>--<689.0,9.0>>

	* uni1E6D (U+1E6D): L<<112.0,113.0>--<113.0,404.0>>

	* uni1E6D (U+1E6D): L<<132.0,404.0>--<131.0,113.0>>

	* uni1E8F (U+1E8F): L<<57.0,152.0>--<56.0,523.0>>

	* uni1E8F (U+1E8F): L<<75.0,523.0>--<76.0,152.0>>

	* uni1E97 (U+1E97): L<<112.0,113.0>--<113.0,404.0>>

	* uni1E97 (U+1E97): L<<132.0,404.0>--<131.0,113.0>>

	* uni1E9E (U+1E9E): L<<66.0,9.0>--<67.0,691.0>>

	* uni1E9E (U+1E9E): L<<85.0,681.0>--<84.0,9.0>>

	* uni1EF9 (U+1EF9): L<<57.0,152.0>--<56.0,523.0>>

	* uni1EF9 (U+1EF9): L<<75.0,523.0>--<76.0,152.0>>

	* y (U+0079): L<<57.0,152.0>--<56.0,523.0>>

	* y (U+0079): L<<75.0,523.0>--<76.0,152.0>>

	* yacute (U+00FD): L<<57.0,152.0>--<56.0,523.0>>

	* yacute (U+00FD): L<<75.0,523.0>--<76.0,152.0>>

	* ycircumflex (U+0177): L<<57.0,152.0>--<56.0,523.0>>

	* ycircumflex (U+0177): L<<75.0,523.0>--<76.0,152.0>>

	* ydieresis (U+00FF): L<<57.0,152.0>--<56.0,523.0>>

	* ydieresis (U+00FF): L<<75.0,523.0>--<76.0,152.0>>

	* ygrave (U+1EF3): L<<57.0,152.0>--<56.0,523.0>>

	* ygrave (U+1EF3): L<<75.0,523.0>--<76.0,152.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] LibertineSup-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 332, but got 200 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, malayalam, syriac, old-permic, canadian-aboriginal, math, tifinagh, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032E COMBINING BREVE BELOW: try adding syriac
 * U+0330 COMBINING TILDE BELOW: try adding one of: math, syriac, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, syriac, gothic, tifinagh, cherokee
 * U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: greek, elbasan, math
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, elbasan, math
 * U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math
 * U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+2080 SUBSCRIPT ZERO: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2116 NUMERO SIGN: try adding cyrillic
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
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: psalter-pahlavi, batak, telugu, zanabazar-square, tagalog, tamil, gunjala-gondi, hanifi-rohingya, adlam, mahajani, syloti-nagri, takri, limbu, coptic, grantha, tai-viet, kharoshthi, new-tai-lue, siddham, marchen, gurmukhi, wancho, kannada, duployan, dogra, soyombo, khmer, tifinagh, tagbanwa, oriya, thaana, balinese, syriac, old-permic, meetei-mayek, music, yi, lao, tai-le, modi, malayalam, myanmar, osage, tirhuta, bengali, ahom, buginese, khojki, pahawh-hmong, hebrew, tibetan, sharada, sinhala, bassa-vah, javanese, hanunoo, chakma, manichaean, mongolian, mandaic, devanagari, kaithi, miao, symbols, caucasian-albanian, thai, khudawadi, bhaiksuki, kayah-li, elbasan, rejang, nko, sundanese, masaram-gondi, mende-kikakui, buhid, brahmi, phags-pa, sogdian, cham, gujarati, newa, lepcha, math
 * U+E133 : not included in any glyphset definition
 * U+E134 : not included in any glyphset definition
 * U+F0000 : not included in any glyphset definition
 * U+F0001 : not included in any glyphset definition
 * U+F0002 : not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: Obreve	Contours detected: 4	Expected: 3

	- Glyph name: obreve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: uni01EA	Contours detected: 4	Expected: 2

	- Glyph name: uni01EB	Contours detected: 4	Expected: 2

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: Dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: dmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: Rmacronbelow	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: perthousand	Contours detected: 10	Expected: 6 or 7

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4 or 5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1 or 2

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 4	Expected: 2

	- Glyph name: Oacute	Contours detected: 4	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Odieresis	Contours detected: 5	Expected: 4

	- Glyph name: Ograve	Contours detected: 4	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: Omacron	Contours detected: 4	Expected: 3

	- Glyph name: Otilde	Contours detected: 4	Expected: 3

	- Glyph name: P	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1 or 2

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: Uacute	Contours detected: 3	Expected: 2

	- Glyph name: Ubreve	Contours detected: 3	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Udieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ugrave	Contours detected: 3	Expected: 2

	- Glyph name: Uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Umacron	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Uring	Contours detected: 4	Expected: 3

	- Glyph name: Utilde	Contours detected: 3	Expected: 2

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 2	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 6	Expected: 3

	- Glyph name: aeacute	Contours detected: 7	Expected: 4

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4 or 5

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ebreve	Contours detected: 4	Expected: 3

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: eng	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 1	Expected: 2

	- Glyph name: m	Contours detected: 3	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: napostrophe	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: o	Contours detected: 3	Expected: 2

	- Glyph name: oacute	Contours detected: 4	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 4	Expected: 3

	- Glyph name: odieresis	Contours detected: 5	Expected: 4

	- Glyph name: oe	Contours detected: 6	Expected: 3

	- Glyph name: ograve	Contours detected: 4	Expected: 3

	- Glyph name: ohungarumlaut	Contours detected: 5	Expected: 4

	- Glyph name: omacron	Contours detected: 4	Expected: 3

	- Glyph name: otilde	Contours detected: 4	Expected: 3

	- Glyph name: p	Contours detected: 3	Expected: 2

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: perthousand	Contours detected: 10	Expected: 6 or 7

	- Glyph name: s	Contours detected: 3	Expected: 1

	- Glyph name: sacute	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: thorn	Contours detected: 3	Expected: 2

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ubreve	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0218	Contours detected: 3	Expected: 2

	- Glyph name: uni0219	Contours detected: 4	Expected: 2

	- Glyph name: uni0232	Contours detected: 3	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0259	Contours detected: 3	Expected: 2

	- Glyph name: uni0272	Contours detected: 2	Expected: 1

	- Glyph name: uni1E08	Contours detected: 4	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E0C	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E15	Contours detected: 5	Expected: 4

	- Glyph name: uni1E17	Contours detected: 5	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E24	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 3	Expected: 2

	- Glyph name: uni1E43	Contours detected: 4	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 5	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 6	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 6	Expected: 5

	- Glyph name: uni1E50	Contours detected: 5	Expected: 4

	- Glyph name: uni1E51	Contours detected: 5	Expected: 4

	- Glyph name: uni1E52	Contours detected: 5	Expected: 4

	- Glyph name: uni1E53	Contours detected: 5	Expected: 4

	- Glyph name: uni1E5A	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 3	Expected: 2

	- Glyph name: uni1E61	Contours detected: 4	Expected: 2

	- Glyph name: uni1E62	Contours detected: 3	Expected: 2

	- Glyph name: uni1E63	Contours detected: 4	Expected: 2

	- Glyph name: uni1E64	Contours detected: 4	Expected: 3

	- Glyph name: uni1E65	Contours detected: 5	Expected: 3

	- Glyph name: uni1E66	Contours detected: 4	Expected: 3

	- Glyph name: uni1E67	Contours detected: 5	Expected: 3

	- Glyph name: uni1E68	Contours detected: 4	Expected: 3

	- Glyph name: uni1E69	Contours detected: 5	Expected: 3

	- Glyph name: uni1E78	Contours detected: 4	Expected: 3

	- Glyph name: uni1E79	Contours detected: 4	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 5	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 5	Expected: 4

	- Glyph name: uni1E8E	Contours detected: 3	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EB9	Contours detected: 4	Expected: 3

	- Glyph name: uni1EBD	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECC	Contours detected: 4	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: utilde	Contours detected: 3	Expected: 2

	- Glyph name: w	Contours detected: 3	Expected: 1

	- Glyph name: wacute	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wgrave	Contours detected: 4	Expected: 2

	- Glyph name: x	Contours detected: 2	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* ae (U+00E6): L<<553.0,500.0>--<549.0,500.0>> -> L<<549.0,500.0>--<539.0,500.0>>

	* aeacute (U+01FD): L<<553.0,500.0>--<549.0,500.0>> -> L<<549.0,500.0>--<539.0,500.0>>

	* e (U+0065): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* eacute (U+00E9): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* ebreve (U+0115): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* ecaron (U+011B): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* ecircumflex (U+00EA): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* edieresis (U+00EB): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* edotaccent (U+0117): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* egrave (U+00E8): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* emacron (U+0113): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* eogonek (U+0119): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* oe (U+0153): L<<611.0,500.0>--<607.0,500.0>> -> L<<607.0,500.0>--<597.0,500.0>>

	* s (U+0073): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* sacute (U+015B): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* scaron (U+0161): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* scedilla (U+015F): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* scircumflex (U+015D): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* uni0219 (U+0219): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* uni0259 (U+0259): L<<214.0,43.0>--<217.0,43.0>> -> L<<217.0,43.0>--<227.0,43.0>>

	* uni1E15 (U+1E15): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* uni1E17 (U+1E17): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* uni1E1D (U+1E1D): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* uni1E61 (U+1E61): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* uni1E63 (U+1E63): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* uni1E65 (U+1E65): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* uni1E67 (U+1E67): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* uni1E69 (U+1E69): L<<33.0,81.0>--<33.0,81.0>> -> L<<33.0,81.0>--<33.0,81.0>>

	* uni1EB9 (U+1EB9): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>>

	* uni1EBD (U+1EBD): L<<255.0,500.0>--<251.0,500.0>> -> L<<251.0,500.0>--<241.0,500.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo (U+F0000): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* logo_full (U+F0001): B<<1078.5,85.0>-<1092.0,135.0>-<1112.0,192.0>>/B<<1112.0,192.0>-<1099.0,172.0>-<1087.5,156.5>> = 13.689059017970232

	* logo_full (U+F0001): B<<998.0,189.5>-<995.0,173.0>-<990.0,159.0>>/B<<990.0,159.0>-<1015.0,199.0>-<1026.5,212.5>> = 12.35155915003017

	* uni1E93 (U+1E93): B<<28.5,15.5>-<28.0,17.0>-<29.0,15.0>>/B<<29.0,15.0>-<28.0,18.0>-<28.0,21.0>> = 8.13010235415587

	* z (U+007A): B<<28.5,15.5>-<28.0,17.0>-<29.0,15.0>>/B<<29.0,15.0>-<28.0,18.0>-<28.0,21.0>> = 8.13010235415587

	* zacute (U+017A): B<<28.5,15.5>-<28.0,17.0>-<29.0,15.0>>/B<<29.0,15.0>-<28.0,18.0>-<28.0,21.0>> = 8.13010235415587

	* zcaron (U+017E): B<<28.5,15.5>-<28.0,17.0>-<29.0,15.0>>/B<<29.0,15.0>-<28.0,18.0>-<28.0,21.0>> = 8.13010235415587

	* zdotaccent (U+017C): B<<28.5,15.5>-<28.0,17.0>-<29.0,15.0>>/B<<29.0,15.0>-<28.0,18.0>-<28.0,21.0>> = 8.13010235415587 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<382.0,20.0>--<381.0,379.0>>

	* h (U+0068): L<<422.0,379.0>--<423.0,20.0>>

	* hbar (U+0127): L<<394.0,20.0>--<393.0,379.0>>

	* hbar (U+0127): L<<434.0,379.0>--<435.0,20.0>>

	* hcircumflex (U+0125): L<<382.0,20.0>--<381.0,379.0>>

	* hcircumflex (U+0125): L<<422.0,379.0>--<423.0,20.0>>

	* m (U+006D): L<<368.0,21.0>--<367.0,318.0>>

	* m (U+006D): L<<721.0,379.0>--<722.0,21.0>>

	* t (U+0074): L<<114.0,121.0>--<115.0,372.0>>

	* t (U+0074): L<<157.0,372.0>--<156.0,126.0>>

	* tcaron (U+0165): L<<114.0,121.0>--<115.0,372.0>>

	* tcaron (U+0165): L<<157.0,372.0>--<156.0,126.0>>

	* tmacronbelow (U+1E6F): L<<114.0,121.0>--<115.0,372.0>>

	* tmacronbelow (U+1E6F): L<<157.0,372.0>--<156.0,126.0>>

	* uni0163 (U+0163): L<<114.0,121.0>--<115.0,372.0>>

	* uni0163 (U+0163): L<<157.0,372.0>--<156.0,126.0>>

	* uni021B (U+021B): L<<114.0,121.0>--<115.0,372.0>>

	* uni021B (U+021B): L<<157.0,372.0>--<156.0,126.0>>

	* uni0233 (U+0233): L<<57.0,158.0>--<56.0,517.0>>

	* uni0233 (U+0233): L<<98.0,517.0>--<99.0,158.0>>

	* uni1E25 (U+1E25): L<<382.0,20.0>--<381.0,379.0>>

	* uni1E25 (U+1E25): L<<422.0,379.0>--<423.0,20.0>>

	* uni1E2B (U+1E2B): L<<382.0,20.0>--<381.0,379.0>>

	* uni1E2B (U+1E2B): L<<422.0,379.0>--<423.0,20.0>>

	* uni1E43 (U+1E43): L<<368.0,21.0>--<367.0,318.0>>

	* uni1E43 (U+1E43): L<<721.0,379.0>--<722.0,21.0>>

	* uni1E6D (U+1E6D): L<<114.0,121.0>--<115.0,372.0>>

	* uni1E6D (U+1E6D): L<<157.0,372.0>--<156.0,126.0>>

	* uni1E8F (U+1E8F): L<<57.0,158.0>--<56.0,517.0>>

	* uni1E8F (U+1E8F): L<<98.0,517.0>--<99.0,158.0>>

	* uni1E97 (U+1E97): L<<114.0,121.0>--<115.0,372.0>>

	* uni1E97 (U+1E97): L<<157.0,372.0>--<156.0,126.0>>

	* uni1E9E (U+1E9E): L<<109.0,658.0>--<108.0,21.0>>

	* uni1E9E (U+1E9E): L<<66.0,21.0>--<67.0,679.0>>

	* uni1EF9 (U+1EF9): L<<57.0,158.0>--<56.0,517.0>>

	* uni1EF9 (U+1EF9): L<<98.0,517.0>--<99.0,158.0>>

	* y (U+0079): L<<57.0,158.0>--<56.0,517.0>>

	* y (U+0079): L<<98.0,517.0>--<99.0,158.0>>

	* yacute (U+00FD): L<<57.0,158.0>--<56.0,517.0>>

	* yacute (U+00FD): L<<98.0,517.0>--<99.0,158.0>>

	* ycircumflex (U+0177): L<<57.0,158.0>--<56.0,517.0>>

	* ycircumflex (U+0177): L<<98.0,517.0>--<99.0,158.0>>

	* ydieresis (U+00FF): L<<57.0,158.0>--<56.0,517.0>>

	* ydieresis (U+00FF): L<<98.0,517.0>--<99.0,158.0>>

	* ygrave (U+1EF3): L<<57.0,158.0>--<56.0,517.0>>

	* ygrave (U+1EF3): L<<98.0,517.0>--<99.0,158.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 12 | 35 | 716 | 43 | 628 | 0 |
| 0% | 1% | 2% | 50% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
