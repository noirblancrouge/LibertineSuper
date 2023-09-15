## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[9] LibertineSuper-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "LibertineSuper" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'LibertineSuper Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.683x (1683) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

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

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1or2

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

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: perthousand	Contours detected: 10	Expected: 6or7

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: perthousand	Contours detected: 10	Expected: 6or7

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

	* AE (U+00C6): L<<421.0,747.0>--<456.0,747.0>> -> L<<456.0,747.0>--<456.0,747.0>>

	* AE (U+00C6): L<<456.0,747.0>--<456.0,747.0>> -> L<<456.0,747.0>--<462.0,747.0>>

	* AE (U+00C6): L<<456.0,747.0>--<462.0,747.0>> -> L<<462.0,747.0>--<754.0,747.0>>

	* AEacute (U+01FC): L<<421.0,747.0>--<456.0,747.0>> -> L<<456.0,747.0>--<456.0,747.0>>

	* AEacute (U+01FC): L<<456.0,747.0>--<456.0,747.0>> -> L<<456.0,747.0>--<462.0,747.0>>

	* AEacute (U+01FC): L<<456.0,747.0>--<462.0,747.0>> -> L<<462.0,747.0>--<754.0,747.0>>

	* Y (U+0059): L<<224.0,363.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,694.0>>

	* Y (U+0059): L<<483.0,694.0>--<301.0,374.0>> -> L<<301.0,374.0>--<294.0,363.0>>

	* Yacute (U+00DD): L<<224.0,363.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,694.0>>

	* Yacute (U+00DD): L<<483.0,694.0>--<301.0,374.0>> -> L<<301.0,374.0>--<294.0,363.0>>

	* Ycircumflex (U+0176): L<<224.0,363.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,694.0>>

	* Ycircumflex (U+0176): L<<483.0,694.0>--<301.0,374.0>> -> L<<301.0,374.0>--<294.0,363.0>>

	* Ydieresis (U+0178): L<<224.0,363.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,694.0>>

	* Ydieresis (U+0178): L<<483.0,694.0>--<301.0,374.0>> -> L<<301.0,374.0>--<294.0,363.0>>

	* Ygrave (U+1EF2): L<<224.0,363.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,694.0>>

	* Ygrave (U+1EF2): L<<483.0,694.0>--<301.0,374.0>> -> L<<301.0,374.0>--<294.0,363.0>>

	* eng (U+014B): L<<413.0,-144.0>--<413.0,40.0>> -> L<<413.0,40.0>--<413.0,315.0>>

	* eng (U+014B): L<<483.0,35.0>--<483.0,33.0>> -> L<<483.0,33.0>--<483.0,-144.0>>

	* eng (U+014B): L<<483.0,40.0>--<483.0,35.0>> -> L<<483.0,35.0>--<483.0,33.0>>

	* eng (U+014B): L<<483.0,46.0>--<483.0,40.0>> -> L<<483.0,40.0>--<483.0,35.0>>

	* g (U+0067): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* gbreve (U+011F): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* gcaron (U+01E7): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* gcircumflex (U+011D): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* gdotaccent (U+0121): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* k (U+006B): L<<130.0,580.0>--<343.0,580.0>> -> L<<343.0,580.0>--<343.0,580.0>>

	* k (U+006B): L<<343.0,580.0>--<343.0,580.0>> -> L<<343.0,580.0>--<344.0,580.0>>

	* p (U+0070): L<<280.0,65.0>--<282.0,65.0>> -> L<<282.0,65.0>--<295.0,65.0>>

	* q (U+0071): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* three (U+0033): L<<413.0,226.0>--<413.0,227.0>> -> L<<413.0,227.0>--<413.0,230.0>>

	* threequarters (U+00BE): L<<256.0,532.0>--<256.0,533.0>> -> L<<256.0,533.0>--<256.0,534.0>>

	* trademark (U+2122): L<<608.0,760.0>--<608.0,760.0>> -> L<<608.0,760.0>--<608.0,760.0>>

	* trademark (U+2122): L<<608.0,760.0>--<608.0,760.0>> -> L<<608.0,760.0>--<609.0,760.0>>

	* uni00B3 (U+00B3): L<<250.0,532.0>--<250.0,533.0>> -> L<<250.0,533.0>--<250.0,534.0>>

	* uni00B5 (U+00B5): L<<70.0,-154.0>--<70.0,176.0>> -> L<<70.0,176.0>--<69.0,545.0>>

	* uni0123 (U+0123): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* uni0137 (U+0137): L<<130.0,580.0>--<343.0,580.0>> -> L<<343.0,580.0>--<343.0,580.0>>

	* uni0137 (U+0137): L<<343.0,580.0>--<343.0,580.0>> -> L<<343.0,580.0>--<344.0,580.0>>

	* uni0232 (U+0232): L<<224.0,363.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,694.0>>

	* uni0232 (U+0232): L<<483.0,694.0>--<301.0,374.0>> -> L<<301.0,374.0>--<294.0,363.0>>

	* uni0272 (U+0272): L<<130.0,315.0>--<130.0,35.0>> -> L<<130.0,35.0>--<130.0,32.0>>

	* uni0272 (U+0272): L<<130.0,35.0>--<130.0,32.0>> -> L<<130.0,32.0>--<130.0,-144.0>>

	* uni03BC (U+03BC): L<<93.0,-154.0>--<93.0,176.0>> -> L<<93.0,176.0>--<92.0,545.0>>

	* uni1E21 (U+1E21): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* uni1E8E (U+1E8E): L<<224.0,363.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,694.0>>

	* uni1E8E (U+1E8E): L<<483.0,694.0>--<301.0,374.0>> -> L<<301.0,374.0>--<294.0,363.0>>

	* uni1EF8 (U+1EF8): L<<224.0,363.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,694.0>>

	* uni1EF8 (U+1EF8): L<<483.0,694.0>--<301.0,374.0>> -> L<<301.0,374.0>--<294.0,363.0>>

	* uni2083 (U+2083): L<<250.0,137.0>--<250.0,138.0>> -> L<<250.0,138.0>--<250.0,139.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* perthousand (U+2030): B<<182.0,276.0>-<188.0,308.0>-<201.0,334.0>>/L<<201.0,334.0>--<52.0,128.0>> = 9.313201082726328

	* perthousand (U+2030): B<<329.0,211.0>-<329.0,240.0>-<333.0,266.0>>/L<<333.0,266.0>--<268.0,41.0>> = 7.367255970534075

	* perthousand (U+2030): B<<419.0,183.0>-<419.0,173.0>-<418.0,164.0>>/L<<418.0,164.0>--<473.0,356.0>> = 9.644609774324655

	* perthousand (U+2030): L<<482.0,721.0>--<226.0,368.0>>/B<<226.0,368.0>-<239.0,381.0>-<257.0,388.5>> = 9.04990969669101 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<482.0,403.0>--<483.0,46.0>>

	* h (U+0068): L<<413.0,34.0>--<412.0,403.0>>

	* h (U+0068): L<<482.0,403.0>--<483.0,34.0>>

	* hbar (U+0127): L<<438.0,34.0>--<437.0,403.0>>

	* hbar (U+0127): L<<507.0,403.0>--<508.0,34.0>>

	* hcircumflex (U+0125): L<<413.0,34.0>--<412.0,403.0>>

	* hcircumflex (U+0125): L<<482.0,403.0>--<483.0,34.0>>

	* m (U+006D): L<<398.0,35.0>--<397.0,315.0>>

	* m (U+006D): L<<737.0,35.0>--<736.0,315.0>>

	* m (U+006D): L<<805.0,403.0>--<806.0,35.0>>

	* n (U+006E): L<<414.0,35.0>--<413.0,315.0>>

	* n (U+006E): L<<482.0,403.0>--<483.0,35.0>>

	* nacute (U+0144): L<<414.0,35.0>--<413.0,315.0>>

	* nacute (U+0144): L<<482.0,403.0>--<483.0,35.0>>

	* napostrophe (U+0149): L<<595.0,35.0>--<594.0,315.0>>

	* napostrophe (U+0149): L<<663.0,403.0>--<664.0,35.0>>

	* ncaron (U+0148): L<<414.0,35.0>--<413.0,315.0>>

	* ncaron (U+0148): L<<482.0,403.0>--<483.0,35.0>>

	* nmacronbelow (U+1E49): L<<414.0,35.0>--<413.0,315.0>>

	* nmacronbelow (U+1E49): L<<482.0,403.0>--<483.0,35.0>>

	* ntilde (U+00F1): L<<414.0,35.0>--<413.0,315.0>>

	* ntilde (U+00F1): L<<482.0,403.0>--<483.0,35.0>>

	* t (U+0074): L<<124.0,580.0>--<125.0,712.0>>

	* t (U+0074): L<<195.0,712.0>--<194.0,580.0>>

	* tbar (U+0167): L<<124.0,580.0>--<125.0,712.0>>

	* tbar (U+0167): L<<195.0,712.0>--<194.0,580.0>>

	* tcaron (U+0165): L<<124.0,580.0>--<125.0,712.0>>

	* tcaron (U+0165): L<<195.0,712.0>--<194.0,580.0>>

	* tmacronbelow (U+1E6F): L<<124.0,580.0>--<125.0,712.0>>

	* tmacronbelow (U+1E6F): L<<195.0,712.0>--<194.0,580.0>>

	* u (U+0075): L<<130.0,545.0>--<131.0,241.0>>

	* u (U+0075): L<<61.0,176.0>--<60.0,545.0>>

	* uacute (U+00FA): L<<130.0,545.0>--<131.0,241.0>>

	* uacute (U+00FA): L<<61.0,176.0>--<60.0,545.0>>

	* ubreve (U+016D): L<<130.0,545.0>--<131.0,241.0>>

	* ubreve (U+016D): L<<61.0,176.0>--<60.0,545.0>>

	* ucircumflex (U+00FB): L<<130.0,545.0>--<131.0,241.0>>

	* ucircumflex (U+00FB): L<<61.0,176.0>--<60.0,545.0>>

	* udieresis (U+00FC): L<<130.0,545.0>--<131.0,241.0>>

	* udieresis (U+00FC): L<<61.0,176.0>--<60.0,545.0>>

	* ugrave (U+00F9): L<<130.0,545.0>--<131.0,241.0>>

	* ugrave (U+00F9): L<<61.0,176.0>--<60.0,545.0>>

	* uhungarumlaut (U+0171): L<<130.0,545.0>--<131.0,241.0>>

	* uhungarumlaut (U+0171): L<<61.0,176.0>--<60.0,545.0>>

	* umacron (U+016B): L<<130.0,545.0>--<131.0,241.0>>

	* umacron (U+016B): L<<61.0,176.0>--<60.0,545.0>>

	* uni00B5 (U+00B5): L<<139.0,545.0>--<140.0,176.0>>

	* uni00B5 (U+00B5): L<<70.0,176.0>--<69.0,545.0>>

	* uni0146 (U+0146): L<<414.0,35.0>--<413.0,315.0>>

	* uni0146 (U+0146): L<<482.0,403.0>--<483.0,35.0>>

	* uni0163 (U+0163): L<<124.0,580.0>--<125.0,712.0>>

	* uni0163 (U+0163): L<<195.0,712.0>--<194.0,580.0>>

	* uni019D (U+019D): L<<92.0,-144.0>--<91.0,46.0>>

	* uni021B (U+021B): L<<124.0,580.0>--<125.0,712.0>>

	* uni021B (U+021B): L<<195.0,712.0>--<194.0,580.0>>

	* uni0233 (U+0233): L<<130.0,545.0>--<131.0,176.0>>

	* uni0233 (U+0233): L<<61.0,176.0>--<60.0,545.0>>

	* uni0272 (U+0272): L<<414.0,35.0>--<413.0,315.0>>

	* uni0272 (U+0272): L<<482.0,403.0>--<483.0,35.0>>

	* uni03BC (U+03BC): L<<162.0,545.0>--<163.0,176.0>>

	* uni03BC (U+03BC): L<<93.0,176.0>--<92.0,545.0>>

	* uni1E25 (U+1E25): L<<413.0,34.0>--<412.0,403.0>>

	* uni1E25 (U+1E25): L<<482.0,403.0>--<483.0,34.0>>

	* uni1E2B (U+1E2B): L<<413.0,34.0>--<412.0,403.0>>

	* uni1E2B (U+1E2B): L<<482.0,403.0>--<483.0,34.0>>

	* uni1E43 (U+1E43): L<<398.0,35.0>--<397.0,315.0>>

	* uni1E43 (U+1E43): L<<737.0,35.0>--<736.0,315.0>>

	* uni1E43 (U+1E43): L<<805.0,403.0>--<806.0,35.0>>

	* uni1E45 (U+1E45): L<<414.0,35.0>--<413.0,315.0>>

	* uni1E45 (U+1E45): L<<482.0,403.0>--<483.0,35.0>>

	* uni1E47 (U+1E47): L<<414.0,35.0>--<413.0,315.0>>

	* uni1E47 (U+1E47): L<<482.0,403.0>--<483.0,35.0>>

	* uni1E6D (U+1E6D): L<<124.0,580.0>--<125.0,712.0>>

	* uni1E6D (U+1E6D): L<<195.0,712.0>--<194.0,580.0>>

	* uni1E79 (U+1E79): L<<130.0,545.0>--<131.0,241.0>>

	* uni1E79 (U+1E79): L<<61.0,176.0>--<60.0,545.0>>

	* uni1E7B (U+1E7B): L<<130.0,545.0>--<131.0,241.0>>

	* uni1E7B (U+1E7B): L<<61.0,176.0>--<60.0,545.0>>

	* uni1E8F (U+1E8F): L<<130.0,545.0>--<131.0,176.0>>

	* uni1E8F (U+1E8F): L<<61.0,176.0>--<60.0,545.0>>

	* uni1E97 (U+1E97): L<<124.0,580.0>--<125.0,712.0>>

	* uni1E97 (U+1E97): L<<195.0,712.0>--<194.0,580.0>>

	* uni1E9E (U+1E9E): L<<141.0,677.0>--<140.0,35.0>>

	* uni1E9E (U+1E9E): L<<70.0,35.0>--<71.0,712.0>>

	* uni1EE5 (U+1EE5): L<<130.0,545.0>--<131.0,241.0>>

	* uni1EE5 (U+1EE5): L<<61.0,176.0>--<60.0,545.0>>

	* uni1EF9 (U+1EF9): L<<130.0,545.0>--<131.0,176.0>>

	* uni1EF9 (U+1EF9): L<<61.0,176.0>--<60.0,545.0>>

	* uogonek (U+0173): L<<130.0,545.0>--<131.0,241.0>>

	* uogonek (U+0173): L<<61.0,176.0>--<60.0,545.0>>

	* uring (U+016F): L<<130.0,545.0>--<131.0,241.0>>

	* uring (U+016F): L<<61.0,176.0>--<60.0,545.0>>

	* utilde (U+0169): L<<130.0,545.0>--<131.0,241.0>>

	* utilde (U+0169): L<<61.0,176.0>--<60.0,545.0>>

	* x (U+0078): L<<453.0,-1.0>--<65.0,-2.0>>

	* y (U+0079): L<<130.0,545.0>--<131.0,176.0>>

	* y (U+0079): L<<61.0,176.0>--<60.0,545.0>>

	* yacute (U+00FD): L<<130.0,545.0>--<131.0,176.0>>

	* yacute (U+00FD): L<<61.0,176.0>--<60.0,545.0>>

	* ycircumflex (U+0177): L<<130.0,545.0>--<131.0,176.0>>

	* ycircumflex (U+0177): L<<61.0,176.0>--<60.0,545.0>>

	* ydieresis (U+00FF): L<<130.0,545.0>--<131.0,176.0>>

	* ydieresis (U+00FF): L<<61.0,176.0>--<60.0,545.0>>

	* ygrave (U+1EF3): L<<130.0,545.0>--<131.0,176.0>>

	* ygrave (U+1EF3): L<<61.0,176.0>--<60.0,545.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] LibertineSuper-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "LibertineSuper" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.683x (1683) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

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

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1or2

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

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: perthousand	Contours detected: 12	Expected: 6or7

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: perthousand	Contours detected: 12	Expected: 6or7

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

	* A (U+0041): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Aacute (U+00C1): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Abreve (U+0102): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Acircumflex (U+00C2): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Adieresis (U+00C4): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Agrave (U+00C0): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Amacron (U+0100): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Aogonek (U+0104): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Aring (U+00C5): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Aringacute (U+01FA): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* Atilde (U+00C3): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* U (U+0055): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Uacute (U+00DA): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Ubreve (U+016C): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Ucircumflex (U+00DB): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Udieresis (U+00DC): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Ugrave (U+00D9): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Uhungarumlaut (U+0170): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Umacron (U+016A): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Uogonek (U+0172): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Uring (U+016E): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* Utilde (U+0168): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* comma (U+002C): L<<99.0,20.0>--<99.0,20.0>> -> L<<99.0,20.0>--<99.0,20.0>>

	* eng (U+014B): L<<403.0,-144.0>--<403.0,10.0>> -> L<<403.0,10.0>--<402.0,363.0>>

	* k (U+006B): L<<310.0,568.0>--<311.0,568.0>> -> L<<311.0,568.0>--<311.0,568.0>>

	* k (U+006B): L<<80.0,568.0>--<310.0,568.0>> -> L<<310.0,568.0>--<311.0,568.0>>

	* semicolon (U+003B): L<<99.0,20.0>--<99.0,20.0>> -> L<<99.0,20.0>--<99.0,20.0>>

	* uni00B5 (U+00B5): L<<70.0,-192.0>--<70.0,162.0>> -> L<<70.0,162.0>--<69.0,558.0>>

	* uni0137 (U+0137): L<<310.0,568.0>--<311.0,568.0>> -> L<<311.0,568.0>--<311.0,568.0>>

	* uni0137 (U+0137): L<<80.0,568.0>--<310.0,568.0>> -> L<<310.0,568.0>--<311.0,568.0>>

	* uni03BC (U+03BC): L<<70.0,-192.0>--<70.0,162.0>> -> L<<70.0,162.0>--<69.0,558.0>>

	* uni1E78 (U+1E78): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* uni1E7A (U+1E7A): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* uni1EA0 (U+1EA0): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* uni1EE4 (U+1EE4): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* o (U+006F): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* o (U+006F): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* oacute (U+00F3): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* oacute (U+00F3): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* obreve (U+014F): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* obreve (U+014F): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* ocircumflex (U+00F4): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* ocircumflex (U+00F4): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* odieresis (U+00F6): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* odieresis (U+00F6): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* oe (U+0153): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* oe (U+0153): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* ograve (U+00F2): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* ograve (U+00F2): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* ohungarumlaut (U+0151): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* ohungarumlaut (U+0151): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* omacron (U+014D): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* omacron (U+014D): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* ordmasculine (U+00BA): B<<199.5,694.5>-<179.0,733.0>-<140.0,739.0>>/L<<140.0,739.0>--<140.0,739.0>> = 8.746162262555211

	* otilde (U+00F5): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* otilde (U+00F5): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* uni01EB (U+01EB): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* uni01EB (U+01EB): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* uni1E4D (U+1E4D): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* uni1E4D (U+1E4D): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* uni1E4F (U+1E4F): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* uni1E4F (U+1E4F): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* uni1E51 (U+1E51): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* uni1E51 (U+1E51): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* uni1E53 (U+1E53): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* uni1E53 (U+1E53): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595

	* uni1ECD (U+1ECD): B<<299.5,474.0>-<265.0,538.0>-<200.0,548.0>>/L<<200.0,548.0>--<200.0,548.0>> = 8.746162262555211

	* uni1ECD (U+1ECD): L<<200.0,548.0>--<200.0,548.0>>/B<<200.0,548.0>-<137.0,532.0>-<103.5,470.0>> = 14.250032697803595 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<403.0,10.0>--<402.0,363.0>>

	* eng (U+014B): L<<421.0,406.0>--<422.0,16.0>>

	* h (U+0068): L<<402.0,9.0>--<401.0,406.0>>

	* h (U+0068): L<<420.0,406.0>--<421.0,9.0>>

	* hbar (U+0127): L<<402.0,9.0>--<401.0,406.0>>

	* hbar (U+0127): L<<420.0,406.0>--<421.0,9.0>>

	* hcircumflex (U+0125): L<<402.0,9.0>--<401.0,406.0>>

	* hcircumflex (U+0125): L<<420.0,406.0>--<421.0,9.0>>

	* m (U+006D): L<<388.0,10.0>--<387.0,363.0>>

	* m (U+006D): L<<716.0,10.0>--<715.0,363.0>>

	* m (U+006D): L<<734.0,406.0>--<735.0,10.0>>

	* n (U+006E): L<<403.0,10.0>--<402.0,363.0>>

	* n (U+006E): L<<421.0,406.0>--<422.0,10.0>>

	* nacute (U+0144): L<<403.0,10.0>--<402.0,363.0>>

	* nacute (U+0144): L<<421.0,406.0>--<422.0,10.0>>

	* napostrophe (U+0149): L<<534.0,10.0>--<533.0,363.0>>

	* napostrophe (U+0149): L<<552.0,406.0>--<553.0,10.0>>

	* ncaron (U+0148): L<<403.0,10.0>--<402.0,363.0>>

	* ncaron (U+0148): L<<421.0,406.0>--<422.0,10.0>>

	* nmacronbelow (U+1E49): L<<403.0,10.0>--<402.0,363.0>>

	* nmacronbelow (U+1E49): L<<421.0,406.0>--<422.0,10.0>>

	* ntilde (U+00F1): L<<403.0,10.0>--<402.0,363.0>>

	* ntilde (U+00F1): L<<421.0,406.0>--<422.0,10.0>>

	* t (U+0074): L<<120.0,121.0>--<121.0,431.0>>

	* t (U+0074): L<<141.0,431.0>--<140.0,121.0>>

	* tbar (U+0167): L<<120.0,285.0>--<121.0,431.0>>

	* tbar (U+0167): L<<141.0,431.0>--<140.0,285.0>>

	* tcaron (U+0165): L<<120.0,121.0>--<121.0,431.0>>

	* tcaron (U+0165): L<<141.0,431.0>--<140.0,121.0>>

	* tmacronbelow (U+1E6F): L<<120.0,121.0>--<121.0,431.0>>

	* tmacronbelow (U+1E6F): L<<141.0,431.0>--<140.0,121.0>>

	* u (U+0075): L<<61.0,162.0>--<60.0,558.0>>

	* u (U+0075): L<<80.0,558.0>--<81.0,204.0>>

	* uacute (U+00FA): L<<61.0,162.0>--<60.0,558.0>>

	* uacute (U+00FA): L<<80.0,558.0>--<81.0,204.0>>

	* ubreve (U+016D): L<<61.0,162.0>--<60.0,558.0>>

	* ubreve (U+016D): L<<80.0,558.0>--<81.0,204.0>>

	* ucircumflex (U+00FB): L<<61.0,162.0>--<60.0,558.0>>

	* ucircumflex (U+00FB): L<<80.0,558.0>--<81.0,204.0>>

	* udieresis (U+00FC): L<<61.0,162.0>--<60.0,558.0>>

	* udieresis (U+00FC): L<<80.0,558.0>--<81.0,204.0>>

	* ugrave (U+00F9): L<<61.0,162.0>--<60.0,558.0>>

	* ugrave (U+00F9): L<<80.0,558.0>--<81.0,204.0>>

	* uhungarumlaut (U+0171): L<<61.0,162.0>--<60.0,558.0>>

	* uhungarumlaut (U+0171): L<<80.0,558.0>--<81.0,204.0>>

	* umacron (U+016B): L<<61.0,162.0>--<60.0,558.0>>

	* umacron (U+016B): L<<80.0,558.0>--<81.0,204.0>>

	* uni00B5 (U+00B5): L<<70.0,162.0>--<69.0,558.0>>

	* uni00B5 (U+00B5): L<<89.0,558.0>--<90.0,162.0>>

	* uni0146 (U+0146): L<<403.0,10.0>--<402.0,363.0>>

	* uni0146 (U+0146): L<<421.0,406.0>--<422.0,10.0>>

	* uni0163 (U+0163): L<<120.0,121.0>--<121.0,431.0>>

	* uni0163 (U+0163): L<<141.0,431.0>--<140.0,121.0>>

	* uni021B (U+021B): L<<120.0,121.0>--<121.0,431.0>>

	* uni021B (U+021B): L<<141.0,431.0>--<140.0,121.0>>

	* uni0233 (U+0233): L<<61.0,162.0>--<60.0,558.0>>

	* uni0233 (U+0233): L<<80.0,558.0>--<81.0,162.0>>

	* uni0272 (U+0272): L<<403.0,10.0>--<402.0,363.0>>

	* uni0272 (U+0272): L<<421.0,406.0>--<422.0,10.0>>

	* uni03BC (U+03BC): L<<70.0,162.0>--<69.0,558.0>>

	* uni03BC (U+03BC): L<<89.0,558.0>--<90.0,162.0>>

	* uni1E25 (U+1E25): L<<402.0,9.0>--<401.0,406.0>>

	* uni1E25 (U+1E25): L<<420.0,406.0>--<421.0,9.0>>

	* uni1E2B (U+1E2B): L<<402.0,9.0>--<401.0,406.0>>

	* uni1E2B (U+1E2B): L<<420.0,406.0>--<421.0,9.0>>

	* uni1E43 (U+1E43): L<<388.0,10.0>--<387.0,363.0>>

	* uni1E43 (U+1E43): L<<716.0,10.0>--<715.0,363.0>>

	* uni1E43 (U+1E43): L<<734.0,406.0>--<735.0,10.0>>

	* uni1E45 (U+1E45): L<<403.0,10.0>--<402.0,363.0>>

	* uni1E45 (U+1E45): L<<421.0,406.0>--<422.0,10.0>>

	* uni1E47 (U+1E47): L<<403.0,10.0>--<402.0,363.0>>

	* uni1E47 (U+1E47): L<<421.0,406.0>--<422.0,10.0>>

	* uni1E6D (U+1E6D): L<<120.0,121.0>--<121.0,431.0>>

	* uni1E6D (U+1E6D): L<<141.0,431.0>--<140.0,121.0>>

	* uni1E79 (U+1E79): L<<61.0,162.0>--<60.0,558.0>>

	* uni1E79 (U+1E79): L<<80.0,558.0>--<81.0,204.0>>

	* uni1E7B (U+1E7B): L<<61.0,162.0>--<60.0,558.0>>

	* uni1E7B (U+1E7B): L<<80.0,558.0>--<81.0,204.0>>

	* uni1E8F (U+1E8F): L<<61.0,162.0>--<60.0,558.0>>

	* uni1E8F (U+1E8F): L<<80.0,558.0>--<81.0,162.0>>

	* uni1E97 (U+1E97): L<<120.0,121.0>--<121.0,431.0>>

	* uni1E97 (U+1E97): L<<141.0,431.0>--<140.0,121.0>>

	* uni1E9E (U+1E9E): L<<70.0,10.0>--<71.0,737.0>>

	* uni1E9E (U+1E9E): L<<91.0,727.0>--<90.0,10.0>>

	* uni1EE5 (U+1EE5): L<<61.0,162.0>--<60.0,558.0>>

	* uni1EE5 (U+1EE5): L<<80.0,558.0>--<81.0,204.0>>

	* uni1EF9 (U+1EF9): L<<61.0,162.0>--<60.0,558.0>>

	* uni1EF9 (U+1EF9): L<<80.0,558.0>--<81.0,162.0>>

	* uogonek (U+0173): L<<61.0,162.0>--<60.0,558.0>>

	* uogonek (U+0173): L<<80.0,558.0>--<81.0,204.0>>

	* uring (U+016F): L<<61.0,162.0>--<60.0,558.0>>

	* uring (U+016F): L<<80.0,558.0>--<81.0,204.0>>

	* utilde (U+0169): L<<61.0,162.0>--<60.0,558.0>>

	* utilde (U+0169): L<<80.0,558.0>--<81.0,204.0>>

	* y (U+0079): L<<61.0,162.0>--<60.0,558.0>>

	* y (U+0079): L<<80.0,558.0>--<81.0,162.0>>

	* yacute (U+00FD): L<<61.0,162.0>--<60.0,558.0>>

	* yacute (U+00FD): L<<80.0,558.0>--<81.0,162.0>>

	* ycircumflex (U+0177): L<<61.0,162.0>--<60.0,558.0>>

	* ycircumflex (U+0177): L<<80.0,558.0>--<81.0,162.0>>

	* ydieresis (U+00FF): L<<61.0,162.0>--<60.0,558.0>>

	* ydieresis (U+00FF): L<<80.0,558.0>--<81.0,162.0>>

	* ygrave (U+1EF3): L<<61.0,162.0>--<60.0,558.0>>

	* ygrave (U+1EF3): L<<80.0,558.0>--<81.0,162.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] LibertineSuper-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "LibertineSuper" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.683x (1683) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

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

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1or2

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

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: perthousand	Contours detected: 10	Expected: 6or7

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: perthousand	Contours detected: 10	Expected: 6or7

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

	* A (U+0041): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* AE (U+00C6): L<<415.0,299.0>--<224.0,299.0>> -> L<<224.0,299.0>--<223.0,299.0>>

	* AE (U+00C6): L<<418.0,196.0>--<414.0,196.0>> -> L<<414.0,196.0>--<169.0,196.0>>

	* AE (U+00C6): L<<418.0,299.0>--<415.0,299.0>> -> L<<415.0,299.0>--<224.0,299.0>>

	* AE (U+00C6): L<<422.0,747.0>--<444.0,747.0>> -> L<<444.0,747.0>--<444.0,747.0>>

	* AE (U+00C6): L<<444.0,747.0>--<444.0,747.0>> -> L<<444.0,747.0>--<446.0,747.0>>

	* AE (U+00C6): L<<444.0,747.0>--<446.0,747.0>> -> L<<446.0,747.0>--<731.0,747.0>>

	* AEacute (U+01FC): L<<415.0,299.0>--<224.0,299.0>> -> L<<224.0,299.0>--<223.0,299.0>>

	* AEacute (U+01FC): L<<418.0,196.0>--<414.0,196.0>> -> L<<414.0,196.0>--<169.0,196.0>>

	* AEacute (U+01FC): L<<418.0,299.0>--<415.0,299.0>> -> L<<415.0,299.0>--<224.0,299.0>>

	* AEacute (U+01FC): L<<422.0,747.0>--<444.0,747.0>> -> L<<444.0,747.0>--<444.0,747.0>>

	* AEacute (U+01FC): L<<444.0,747.0>--<444.0,747.0>> -> L<<444.0,747.0>--<446.0,747.0>>

	* AEacute (U+01FC): L<<444.0,747.0>--<446.0,747.0>> -> L<<446.0,747.0>--<731.0,747.0>>

	* Aacute (U+00C1): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Abreve (U+0102): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Acircumflex (U+00C2): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Adieresis (U+00C4): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Agrave (U+00C0): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Amacron (U+0100): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Aogonek (U+0104): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Aring (U+00C5): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Aringacute (U+01FA): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Atilde (U+00C3): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* Y (U+0059): L<<221.0,367.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,713.0>>

	* Y (U+0059): L<<454.0,713.0>--<270.0,374.0>> -> L<<270.0,374.0>--<266.0,367.0>>

	* Yacute (U+00DD): L<<221.0,367.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,713.0>>

	* Yacute (U+00DD): L<<454.0,713.0>--<270.0,374.0>> -> L<<270.0,374.0>--<266.0,367.0>>

	* Ycircumflex (U+0176): L<<221.0,367.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,713.0>>

	* Ycircumflex (U+0176): L<<454.0,713.0>--<270.0,374.0>> -> L<<270.0,374.0>--<266.0,367.0>>

	* Ydieresis (U+0178): L<<221.0,367.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,713.0>>

	* Ydieresis (U+0178): L<<454.0,713.0>--<270.0,374.0>> -> L<<270.0,374.0>--<266.0,367.0>>

	* Ygrave (U+1EF2): L<<221.0,367.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,713.0>>

	* Ygrave (U+1EF2): L<<454.0,713.0>--<270.0,374.0>> -> L<<270.0,374.0>--<266.0,367.0>>

	* ae (U+00E6): L<<584.0,534.0>--<580.0,534.0>> -> L<<580.0,534.0>--<570.0,534.0>>

	* aeacute (U+01FD): L<<584.0,534.0>--<580.0,534.0>> -> L<<580.0,534.0>--<570.0,534.0>>

	* comma (U+002C): L<<124.0,32.0>--<124.0,32.0>> -> L<<124.0,32.0>--<124.0,32.0>>

	* e (U+0065): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* eacute (U+00E9): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* ebreve (U+0115): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* ecaron (U+011B): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* ecircumflex (U+00EA): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* edieresis (U+00EB): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* edotaccent (U+0117): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* egrave (U+00E8): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* emacron (U+0113): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* eng (U+014B): L<<408.0,-144.0>--<408.0,25.0>> -> L<<408.0,25.0>--<407.0,339.0>>

	* eogonek (U+0119): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* k (U+006B): L<<105.0,574.0>--<326.0,574.0>> -> L<<326.0,574.0>--<327.0,574.0>>

	* k (U+006B): L<<326.0,574.0>--<327.0,574.0>> -> L<<327.0,574.0>--<327.0,574.0>>

	* oe (U+0153): L<<652.0,534.0>--<648.0,534.0>> -> L<<648.0,534.0>--<638.0,534.0>>

	* semicolon (U+003B): L<<124.0,32.0>--<124.0,32.0>> -> L<<124.0,32.0>--<124.0,32.0>>

	* trademark (U+2122): L<<561.0,761.0>--<562.0,761.0>> -> L<<562.0,761.0>--<562.0,761.0>>

	* trademark (U+2122): L<<562.0,761.0>--<562.0,761.0>> -> L<<562.0,761.0>--<562.0,761.0>>

	* uni00B5 (U+00B5): L<<70.0,-173.0>--<70.0,169.0>> -> L<<70.0,169.0>--<69.0,552.0>>

	* uni0137 (U+0137): L<<105.0,574.0>--<326.0,574.0>> -> L<<326.0,574.0>--<327.0,574.0>>

	* uni0137 (U+0137): L<<326.0,574.0>--<327.0,574.0>> -> L<<327.0,574.0>--<327.0,574.0>>

	* uni0232 (U+0232): L<<221.0,367.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,713.0>>

	* uni0232 (U+0232): L<<454.0,713.0>--<270.0,374.0>> -> L<<270.0,374.0>--<266.0,367.0>>

	* uni0259 (U+0259): L<<228.0,36.0>--<231.0,36.0>> -> L<<231.0,36.0>--<242.0,36.0>>

	* uni0272 (U+0272): L<<60.0,-144.0>--<60.0,27.0>> -> L<<60.0,27.0>--<60.0,28.0>>

	* uni0272 (U+0272): L<<60.0,27.0>--<60.0,28.0>> -> L<<60.0,28.0>--<60.0,552.0>>

	* uni03BC (U+03BC): L<<81.0,-173.0>--<81.0,169.0>> -> L<<81.0,169.0>--<80.0,552.0>>

	* uni1E15 (U+1E15): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* uni1E17 (U+1E17): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* uni1E1D (U+1E1D): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* uni1E8E (U+1E8E): L<<221.0,367.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,713.0>>

	* uni1E8E (U+1E8E): L<<454.0,713.0>--<270.0,374.0>> -> L<<270.0,374.0>--<266.0,367.0>>

	* uni1E9E (U+1E9E): L<<220.0,411.0>--<222.0,414.0>> -> L<<222.0,414.0>--<450.0,702.0>>

	* uni1EA0 (U+1EA0): L<<242.0,752.0>--<242.0,752.0>> -> L<<242.0,752.0>--<242.0,752.0>>

	* uni1EB9 (U+1EB9): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* uni1EBD (U+1EBD): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* uni1EF8 (U+1EF8): L<<221.0,367.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,713.0>>

	* uni1EF8 (U+1EF8): L<<454.0,713.0>--<270.0,374.0>> -> L<<270.0,374.0>--<266.0,367.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<408.0,25.0>--<407.0,339.0>>

	* h (U+0068): L<<408.0,21.0>--<407.0,405.0>>

	* h (U+0068): L<<451.0,405.0>--<452.0,21.0>>

	* hbar (U+0127): L<<420.0,21.0>--<419.0,405.0>>

	* hbar (U+0127): L<<463.0,405.0>--<464.0,21.0>>

	* hcircumflex (U+0125): L<<408.0,21.0>--<407.0,405.0>>

	* hcircumflex (U+0125): L<<451.0,405.0>--<452.0,21.0>>

	* m (U+006D): L<<393.0,22.0>--<392.0,339.0>>

	* m (U+006D): L<<726.0,22.0>--<725.0,339.0>>

	* m (U+006D): L<<770.0,405.0>--<771.0,22.0>>

	* n (U+006E): L<<408.0,22.0>--<407.0,339.0>>

	* n (U+006E): L<<452.0,405.0>--<453.0,22.0>>

	* nacute (U+0144): L<<408.0,22.0>--<407.0,339.0>>

	* nacute (U+0144): L<<452.0,405.0>--<453.0,22.0>>

	* napostrophe (U+0149): L<<564.0,22.0>--<563.0,339.0>>

	* napostrophe (U+0149): L<<608.0,405.0>--<609.0,22.0>>

	* ncaron (U+0148): L<<408.0,22.0>--<407.0,339.0>>

	* ncaron (U+0148): L<<452.0,405.0>--<453.0,22.0>>

	* nmacronbelow (U+1E49): L<<408.0,22.0>--<407.0,339.0>>

	* nmacronbelow (U+1E49): L<<452.0,405.0>--<453.0,22.0>>

	* ntilde (U+00F1): L<<408.0,22.0>--<407.0,339.0>>

	* ntilde (U+00F1): L<<452.0,405.0>--<453.0,22.0>>

	* t (U+0074): L<<122.0,574.0>--<123.0,725.0>>

	* t (U+0074): L<<168.0,725.0>--<167.0,574.0>>

	* tbar (U+0167): L<<122.0,574.0>--<123.0,725.0>>

	* tbar (U+0167): L<<168.0,725.0>--<167.0,574.0>>

	* tcaron (U+0165): L<<122.0,574.0>--<123.0,725.0>>

	* tcaron (U+0165): L<<168.0,725.0>--<167.0,574.0>>

	* tmacronbelow (U+1E6F): L<<122.0,574.0>--<123.0,725.0>>

	* tmacronbelow (U+1E6F): L<<168.0,725.0>--<167.0,574.0>>

	* u (U+0075): L<<105.0,552.0>--<106.0,223.0>>

	* u (U+0075): L<<61.0,169.0>--<60.0,552.0>>

	* uacute (U+00FA): L<<105.0,552.0>--<106.0,223.0>>

	* uacute (U+00FA): L<<61.0,169.0>--<60.0,552.0>>

	* ubreve (U+016D): L<<105.0,552.0>--<106.0,223.0>>

	* ubreve (U+016D): L<<61.0,169.0>--<60.0,552.0>>

	* ucircumflex (U+00FB): L<<105.0,552.0>--<106.0,223.0>>

	* ucircumflex (U+00FB): L<<61.0,169.0>--<60.0,552.0>>

	* udieresis (U+00FC): L<<105.0,552.0>--<106.0,223.0>>

	* udieresis (U+00FC): L<<61.0,169.0>--<60.0,552.0>>

	* ugrave (U+00F9): L<<105.0,552.0>--<106.0,223.0>>

	* ugrave (U+00F9): L<<61.0,169.0>--<60.0,552.0>>

	* uhungarumlaut (U+0171): L<<105.0,552.0>--<106.0,223.0>>

	* uhungarumlaut (U+0171): L<<61.0,169.0>--<60.0,552.0>>

	* umacron (U+016B): L<<105.0,552.0>--<106.0,223.0>>

	* umacron (U+016B): L<<61.0,169.0>--<60.0,552.0>>

	* uni00B5 (U+00B5): L<<114.0,552.0>--<115.0,169.0>>

	* uni00B5 (U+00B5): L<<70.0,169.0>--<69.0,552.0>>

	* uni0146 (U+0146): L<<408.0,22.0>--<407.0,339.0>>

	* uni0146 (U+0146): L<<452.0,405.0>--<453.0,22.0>>

	* uni0163 (U+0163): L<<122.0,574.0>--<123.0,725.0>>

	* uni0163 (U+0163): L<<168.0,725.0>--<167.0,574.0>>

	* uni021B (U+021B): L<<122.0,574.0>--<123.0,725.0>>

	* uni021B (U+021B): L<<168.0,725.0>--<167.0,574.0>>

	* uni0233 (U+0233): L<<105.0,552.0>--<106.0,169.0>>

	* uni0233 (U+0233): L<<61.0,169.0>--<60.0,552.0>>

	* uni0272 (U+0272): L<<408.0,22.0>--<407.0,339.0>>

	* uni0272 (U+0272): L<<452.0,405.0>--<453.0,22.0>>

	* uni03BC (U+03BC): L<<125.0,552.0>--<126.0,169.0>>

	* uni03BC (U+03BC): L<<81.0,169.0>--<80.0,552.0>>

	* uni1E25 (U+1E25): L<<408.0,21.0>--<407.0,405.0>>

	* uni1E25 (U+1E25): L<<451.0,405.0>--<452.0,21.0>>

	* uni1E2B (U+1E2B): L<<408.0,21.0>--<407.0,405.0>>

	* uni1E2B (U+1E2B): L<<451.0,405.0>--<452.0,21.0>>

	* uni1E43 (U+1E43): L<<393.0,22.0>--<392.0,339.0>>

	* uni1E43 (U+1E43): L<<726.0,22.0>--<725.0,339.0>>

	* uni1E43 (U+1E43): L<<770.0,405.0>--<771.0,22.0>>

	* uni1E45 (U+1E45): L<<408.0,22.0>--<407.0,339.0>>

	* uni1E45 (U+1E45): L<<452.0,405.0>--<453.0,22.0>>

	* uni1E47 (U+1E47): L<<408.0,22.0>--<407.0,339.0>>

	* uni1E47 (U+1E47): L<<452.0,405.0>--<453.0,22.0>>

	* uni1E6D (U+1E6D): L<<122.0,574.0>--<123.0,725.0>>

	* uni1E6D (U+1E6D): L<<168.0,725.0>--<167.0,574.0>>

	* uni1E79 (U+1E79): L<<105.0,552.0>--<106.0,223.0>>

	* uni1E79 (U+1E79): L<<61.0,169.0>--<60.0,552.0>>

	* uni1E7B (U+1E7B): L<<105.0,552.0>--<106.0,223.0>>

	* uni1E7B (U+1E7B): L<<61.0,169.0>--<60.0,552.0>>

	* uni1E8F (U+1E8F): L<<105.0,552.0>--<106.0,169.0>>

	* uni1E8F (U+1E8F): L<<61.0,169.0>--<60.0,552.0>>

	* uni1E97 (U+1E97): L<<122.0,574.0>--<123.0,725.0>>

	* uni1E97 (U+1E97): L<<168.0,725.0>--<167.0,574.0>>

	* uni1E9E (U+1E9E): L<<116.0,702.0>--<115.0,23.0>>

	* uni1E9E (U+1E9E): L<<70.0,23.0>--<71.0,725.0>>

	* uni1EE5 (U+1EE5): L<<105.0,552.0>--<106.0,223.0>>

	* uni1EE5 (U+1EE5): L<<61.0,169.0>--<60.0,552.0>>

	* uni1EF9 (U+1EF9): L<<105.0,552.0>--<106.0,169.0>>

	* uni1EF9 (U+1EF9): L<<61.0,169.0>--<60.0,552.0>>

	* uogonek (U+0173): L<<105.0,552.0>--<106.0,223.0>>

	* uogonek (U+0173): L<<61.0,169.0>--<60.0,552.0>>

	* uring (U+016F): L<<105.0,552.0>--<106.0,223.0>>

	* uring (U+016F): L<<61.0,169.0>--<60.0,552.0>>

	* utilde (U+0169): L<<105.0,552.0>--<106.0,223.0>>

	* utilde (U+0169): L<<61.0,169.0>--<60.0,552.0>>

	* y (U+0079): L<<105.0,552.0>--<106.0,169.0>>

	* y (U+0079): L<<61.0,169.0>--<60.0,552.0>>

	* yacute (U+00FD): L<<105.0,552.0>--<106.0,169.0>>

	* yacute (U+00FD): L<<61.0,169.0>--<60.0,552.0>>

	* ycircumflex (U+0177): L<<105.0,552.0>--<106.0,169.0>>

	* ycircumflex (U+0177): L<<61.0,169.0>--<60.0,552.0>>

	* ydieresis (U+00FF): L<<105.0,552.0>--<106.0,169.0>>

	* ydieresis (U+00FF): L<<61.0,169.0>--<60.0,552.0>>

	* ygrave (U+1EF3): L<<105.0,552.0>--<106.0,169.0>>

	* ygrave (U+1EF3): L<<61.0,169.0>--<60.0,552.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] LibertineSuper-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "LibertineSuper" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.683x (1683) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

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

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1or2

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

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	* Y (U+0059): L<<230.0,356.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Y (U+0059): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<350.0,356.0>>

	* Yacute (U+00DD): L<<230.0,356.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Yacute (U+00DD): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<350.0,356.0>>

	* Ycircumflex (U+0176): L<<230.0,356.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Ycircumflex (U+0176): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<350.0,356.0>>

	* Ydieresis (U+0178): L<<230.0,356.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Ydieresis (U+0178): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<350.0,356.0>>

	* Ygrave (U+1EF2): L<<230.0,356.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Ygrave (U+1EF2): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<350.0,356.0>>

	* eng (U+014B): L<<423.0,-144.0>--<424.0,69.0>> -> L<<424.0,69.0>--<423.0,267.0>>

	* eng (U+014B): L<<543.0,400.0>--<544.0,77.0>> -> L<<544.0,77.0>--<544.0,76.0>>

	* eng (U+014B): L<<544.0,59.0>--<544.0,56.0>> -> L<<544.0,56.0>--<543.0,-144.0>>

	* eng (U+014B): L<<544.0,69.0>--<544.0,59.0>> -> L<<544.0,59.0>--<544.0,56.0>>

	* eng (U+014B): L<<544.0,76.0>--<544.0,69.0>> -> L<<544.0,69.0>--<544.0,59.0>>

	* eng (U+014B): L<<544.0,77.0>--<544.0,76.0>> -> L<<544.0,76.0>--<544.0,69.0>>

	* k (U+006B): L<<180.0,592.0>--<375.0,592.0>> -> L<<375.0,592.0>--<376.0,592.0>>

	* k (U+006B): L<<375.0,592.0>--<376.0,592.0>> -> L<<376.0,592.0>--<376.0,592.0>>

	* trademark (U+2122): L<<700.0,759.0>--<700.0,759.0>> -> L<<700.0,759.0>--<700.0,759.0>>

	* trademark (U+2122): L<<700.0,759.0>--<700.0,759.0>> -> L<<700.0,759.0>--<701.0,759.0>>

	* uni00B5 (U+00B5): L<<69.0,-117.0>--<69.0,190.0>> -> L<<69.0,190.0>--<68.0,532.0>>

	* uni0137 (U+0137): L<<180.0,592.0>--<375.0,592.0>> -> L<<375.0,592.0>--<376.0,592.0>>

	* uni0137 (U+0137): L<<375.0,592.0>--<376.0,592.0>> -> L<<376.0,592.0>--<376.0,592.0>>

	* uni0232 (U+0232): L<<230.0,356.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* uni0232 (U+0232): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<350.0,356.0>>

	* uni0272 (U+0272): L<<180.0,267.0>--<180.0,59.0>> -> L<<180.0,59.0>--<180.0,56.0>>

	* uni0272 (U+0272): L<<180.0,59.0>--<180.0,56.0>> -> L<<180.0,56.0>--<180.0,-144.0>>

	* uni0272 (U+0272): L<<60.0,-144.0>--<60.0,61.0>> -> L<<60.0,61.0>--<60.0,64.0>>

	* uni0272 (U+0272): L<<60.0,61.0>--<60.0,64.0>> -> L<<60.0,64.0>--<60.0,532.0>>

	* uni03BC (U+03BC): L<<114.0,-117.0>--<114.0,190.0>> -> L<<114.0,190.0>--<113.0,532.0>>

	* uni1E8E (U+1E8E): L<<230.0,356.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* uni1E8E (U+1E8E): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<350.0,356.0>>

	* uni1EF8 (U+1EF8): L<<230.0,356.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* uni1EF8 (U+1EF8): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<350.0,356.0>>

	* w (U+0077): L<<226.0,40.0>--<25.0,508.0>> -> L<<25.0,508.0>--<24.0,510.0>>

	* wacute (U+1E83): L<<226.0,40.0>--<25.0,508.0>> -> L<<25.0,508.0>--<24.0,510.0>>

	* wcircumflex (U+0175): L<<226.0,40.0>--<25.0,508.0>> -> L<<25.0,508.0>--<24.0,510.0>>

	* wdieresis (U+1E85): L<<226.0,40.0>--<25.0,508.0>> -> L<<25.0,508.0>--<24.0,510.0>>

	* wgrave (U+1E81): L<<226.0,40.0>--<25.0,508.0>> -> L<<25.0,508.0>--<24.0,510.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* comma (U+002C): B<<199.0,69.0>-<199.0,67.0>-<199.0,68.0>>/L<<199.0,68.0>--<198.0,24.0>> = 1.3019526725787232

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* semicolon (U+003B): B<<199.0,69.0>-<199.0,67.0>-<199.0,68.0>>/L<<199.0,68.0>--<198.0,24.0>> = 1.3019526725787232 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<423.0,-144.0>--<424.0,69.0>>

	* eng (U+014B): L<<424.0,69.0>--<423.0,267.0>>

	* eng (U+014B): L<<543.0,400.0>--<544.0,77.0>>

	* eng (U+014B): L<<544.0,56.0>--<543.0,-144.0>>

	* h (U+0068): L<<424.0,58.0>--<423.0,400.0>>

	* h (U+0068): L<<543.0,400.0>--<544.0,58.0>>

	* hbar (U+0127): L<<474.0,58.0>--<473.0,400.0>>

	* hbar (U+0127): L<<593.0,400.0>--<594.0,58.0>>

	* hcircumflex (U+0125): L<<424.0,58.0>--<423.0,400.0>>

	* hcircumflex (U+0125): L<<543.0,400.0>--<544.0,58.0>>

	* m (U+006D): L<<408.0,59.0>--<407.0,267.0>>

	* m (U+006D): L<<757.0,59.0>--<756.0,267.0>>

	* m (U+006D): L<<876.0,400.0>--<877.0,59.0>>

	* n (U+006E): L<<424.0,59.0>--<423.0,267.0>>

	* n (U+006E): L<<543.0,400.0>--<544.0,59.0>>

	* nacute (U+0144): L<<424.0,59.0>--<423.0,267.0>>

	* nacute (U+0144): L<<543.0,400.0>--<544.0,59.0>>

	* napostrophe (U+0149): L<<656.0,59.0>--<655.0,267.0>>

	* napostrophe (U+0149): L<<775.0,400.0>--<776.0,59.0>>

	* ncaron (U+0148): L<<424.0,59.0>--<423.0,267.0>>

	* ncaron (U+0148): L<<543.0,400.0>--<544.0,59.0>>

	* nmacronbelow (U+1E49): L<<424.0,59.0>--<423.0,267.0>>

	* nmacronbelow (U+1E49): L<<543.0,400.0>--<544.0,59.0>>

	* ntilde (U+00F1): L<<424.0,59.0>--<423.0,267.0>>

	* ntilde (U+00F1): L<<543.0,400.0>--<544.0,59.0>>

	* u (U+0075): L<<180.0,532.0>--<181.0,278.0>>

	* u (U+0075): L<<61.0,190.0>--<60.0,532.0>>

	* uacute (U+00FA): L<<180.0,532.0>--<181.0,278.0>>

	* uacute (U+00FA): L<<61.0,190.0>--<60.0,532.0>>

	* ubreve (U+016D): L<<180.0,532.0>--<181.0,278.0>>

	* ubreve (U+016D): L<<61.0,190.0>--<60.0,532.0>>

	* ucircumflex (U+00FB): L<<180.0,532.0>--<181.0,278.0>>

	* ucircumflex (U+00FB): L<<61.0,190.0>--<60.0,532.0>>

	* udieresis (U+00FC): L<<180.0,532.0>--<181.0,278.0>>

	* udieresis (U+00FC): L<<61.0,190.0>--<60.0,532.0>>

	* ugrave (U+00F9): L<<180.0,532.0>--<181.0,278.0>>

	* ugrave (U+00F9): L<<61.0,190.0>--<60.0,532.0>>

	* uhungarumlaut (U+0171): L<<180.0,532.0>--<181.0,278.0>>

	* uhungarumlaut (U+0171): L<<61.0,190.0>--<60.0,532.0>>

	* umacron (U+016B): L<<180.0,532.0>--<181.0,278.0>>

	* umacron (U+016B): L<<61.0,190.0>--<60.0,532.0>>

	* uni00B5 (U+00B5): L<<188.0,532.0>--<189.0,190.0>>

	* uni00B5 (U+00B5): L<<69.0,190.0>--<68.0,532.0>>

	* uni0146 (U+0146): L<<424.0,59.0>--<423.0,267.0>>

	* uni0146 (U+0146): L<<543.0,400.0>--<544.0,59.0>>

	* uni0233 (U+0233): L<<180.0,532.0>--<181.0,190.0>>

	* uni0233 (U+0233): L<<61.0,190.0>--<60.0,532.0>>

	* uni0272 (U+0272): L<<424.0,59.0>--<423.0,267.0>>

	* uni0272 (U+0272): L<<543.0,400.0>--<544.0,59.0>>

	* uni03BC (U+03BC): L<<114.0,190.0>--<113.0,532.0>>

	* uni03BC (U+03BC): L<<233.0,532.0>--<234.0,190.0>>

	* uni1E25 (U+1E25): L<<424.0,58.0>--<423.0,400.0>>

	* uni1E25 (U+1E25): L<<543.0,400.0>--<544.0,58.0>>

	* uni1E2B (U+1E2B): L<<424.0,58.0>--<423.0,400.0>>

	* uni1E2B (U+1E2B): L<<543.0,400.0>--<544.0,58.0>>

	* uni1E43 (U+1E43): L<<408.0,59.0>--<407.0,267.0>>

	* uni1E43 (U+1E43): L<<757.0,59.0>--<756.0,267.0>>

	* uni1E43 (U+1E43): L<<876.0,400.0>--<877.0,59.0>>

	* uni1E45 (U+1E45): L<<424.0,59.0>--<423.0,267.0>>

	* uni1E45 (U+1E45): L<<543.0,400.0>--<544.0,59.0>>

	* uni1E47 (U+1E47): L<<424.0,59.0>--<423.0,267.0>>

	* uni1E47 (U+1E47): L<<543.0,400.0>--<544.0,59.0>>

	* uni1E79 (U+1E79): L<<180.0,532.0>--<181.0,278.0>>

	* uni1E79 (U+1E79): L<<61.0,190.0>--<60.0,532.0>>

	* uni1E7B (U+1E7B): L<<180.0,532.0>--<181.0,278.0>>

	* uni1E7B (U+1E7B): L<<61.0,190.0>--<60.0,532.0>>

	* uni1E8F (U+1E8F): L<<180.0,532.0>--<181.0,190.0>>

	* uni1E8F (U+1E8F): L<<61.0,190.0>--<60.0,532.0>>

	* uni1E9E (U+1E9E): L<<191.0,627.0>--<190.0,60.0>>

	* uni1E9E (U+1E9E): L<<70.0,60.0>--<71.0,687.0>>

	* uni1EE5 (U+1EE5): L<<180.0,532.0>--<181.0,278.0>>

	* uni1EE5 (U+1EE5): L<<61.0,190.0>--<60.0,532.0>>

	* uni1EF9 (U+1EF9): L<<180.0,532.0>--<181.0,190.0>>

	* uni1EF9 (U+1EF9): L<<61.0,190.0>--<60.0,532.0>>

	* uogonek (U+0173): L<<180.0,532.0>--<181.0,278.0>>

	* uogonek (U+0173): L<<61.0,190.0>--<60.0,532.0>>

	* uring (U+016F): L<<180.0,532.0>--<181.0,278.0>>

	* uring (U+016F): L<<61.0,190.0>--<60.0,532.0>>

	* utilde (U+0169): L<<180.0,532.0>--<181.0,278.0>>

	* utilde (U+0169): L<<61.0,190.0>--<60.0,532.0>>

	* y (U+0079): L<<180.0,532.0>--<181.0,190.0>>

	* y (U+0079): L<<61.0,190.0>--<60.0,532.0>>

	* yacute (U+00FD): L<<180.0,532.0>--<181.0,190.0>>

	* yacute (U+00FD): L<<61.0,190.0>--<60.0,532.0>>

	* ycircumflex (U+0177): L<<180.0,532.0>--<181.0,190.0>>

	* ycircumflex (U+0177): L<<61.0,190.0>--<60.0,532.0>>

	* ydieresis (U+00FF): L<<180.0,532.0>--<181.0,190.0>>

	* ydieresis (U+00FF): L<<61.0,190.0>--<60.0,532.0>>

	* ygrave (U+1EF3): L<<180.0,532.0>--<181.0,190.0>>

	* ygrave (U+1EF3): L<<61.0,190.0>--<60.0,532.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] LibertineSuper-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "LibertineSuper" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.683x (1683) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

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

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1or2

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

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: perthousand	Contours detected: 10	Expected: 6or7

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: AEacute	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: perthousand	Contours detected: 10	Expected: 6or7

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

	* A (U+0041): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* A (U+0041): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* AE (U+00C6): L<<450.0,747.0>--<454.0,747.0>> -> L<<454.0,747.0>--<743.0,747.0>>

	* AEacute (U+01FC): L<<450.0,747.0>--<454.0,747.0>> -> L<<454.0,747.0>--<743.0,747.0>>

	* Aacute (U+00C1): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aacute (U+00C1): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Abreve (U+0102): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Abreve (U+0102): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Acircumflex (U+00C2): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Acircumflex (U+00C2): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Adieresis (U+00C4): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Adieresis (U+00C4): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Agrave (U+00C0): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Agrave (U+00C0): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Amacron (U+0100): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Amacron (U+0100): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aogonek (U+0104): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aogonek (U+0104): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aring (U+00C5): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aring (U+00C5): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aringacute (U+01FA): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aringacute (U+01FA): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Atilde (U+00C3): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Atilde (U+00C3): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Y (U+0059): L<<223.0,365.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Y (U+0059): L<<469.0,703.0>--<285.0,374.0>> -> L<<285.0,374.0>--<280.0,365.0>>

	* Yacute (U+00DD): L<<223.0,365.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Yacute (U+00DD): L<<469.0,703.0>--<285.0,374.0>> -> L<<285.0,374.0>--<280.0,365.0>>

	* Ycircumflex (U+0176): L<<223.0,365.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Ycircumflex (U+0176): L<<469.0,703.0>--<285.0,374.0>> -> L<<285.0,374.0>--<280.0,365.0>>

	* Ydieresis (U+0178): L<<223.0,365.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Ydieresis (U+0178): L<<469.0,703.0>--<285.0,374.0>> -> L<<285.0,374.0>--<280.0,365.0>>

	* Ygrave (U+1EF2): L<<223.0,365.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Ygrave (U+1EF2): L<<469.0,703.0>--<285.0,374.0>> -> L<<285.0,374.0>--<280.0,365.0>>

	* comma (U+002C): L<<137.0,38.0>--<137.0,38.0>> -> L<<137.0,38.0>--<137.0,38.0>>

	* eng (U+014B): L<<411.0,-144.0>--<411.0,33.0>> -> L<<411.0,33.0>--<410.0,327.0>>

	* eng (U+014B): L<<468.0,39.0>--<468.0,33.0>> -> L<<468.0,33.0>--<468.0,28.0>>

	* k (U+006B): L<<118.0,577.0>--<334.0,577.0>> -> L<<334.0,577.0>--<335.0,577.0>>

	* k (U+006B): L<<334.0,577.0>--<335.0,577.0>> -> L<<335.0,577.0>--<335.0,577.0>>

	* s (U+0073): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* sacute (U+015B): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* scaron (U+0161): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* scedilla (U+015F): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* scircumflex (U+015D): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* semicolon (U+003B): L<<137.0,38.0>--<137.0,38.0>> -> L<<137.0,38.0>--<137.0,38.0>>

	* thorn (U+00FE): L<<269.0,52.0>--<274.0,52.0>> -> L<<274.0,52.0>--<287.0,52.0>>

	* trademark (U+2122): L<<585.0,761.0>--<585.0,761.0>> -> L<<585.0,761.0>--<585.0,761.0>>

	* uni00B5 (U+00B5): L<<70.0,-164.0>--<70.0,173.0>> -> L<<70.0,173.0>--<69.0,548.0>>

	* uni0137 (U+0137): L<<118.0,577.0>--<334.0,577.0>> -> L<<334.0,577.0>--<335.0,577.0>>

	* uni0137 (U+0137): L<<334.0,577.0>--<335.0,577.0>> -> L<<335.0,577.0>--<335.0,577.0>>

	* uni0219 (U+0219): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* uni0232 (U+0232): L<<223.0,365.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* uni0232 (U+0232): L<<469.0,703.0>--<285.0,374.0>> -> L<<285.0,374.0>--<280.0,365.0>>

	* uni0272 (U+0272): L<<60.0,-144.0>--<60.0,33.0>> -> L<<60.0,33.0>--<60.0,34.0>>

	* uni0272 (U+0272): L<<60.0,33.0>--<60.0,34.0>> -> L<<60.0,34.0>--<60.0,548.0>>

	* uni03A9 (U+03A9): L<<293.0,-5.0>--<292.0,-5.0>> -> L<<292.0,-5.0>--<291.0,-5.0>>

	* uni03BC (U+03BC): L<<87.0,-164.0>--<87.0,173.0>> -> L<<87.0,173.0>--<86.0,548.0>>

	* uni1E61 (U+1E61): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* uni1E63 (U+1E63): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* uni1E65 (U+1E65): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* uni1E67 (U+1E67): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* uni1E69 (U+1E69): L<<373.0,479.0>--<370.0,475.0>> -> L<<370.0,475.0>--<254.0,311.0>>

	* uni1E8E (U+1E8E): L<<223.0,365.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* uni1E8E (U+1E8E): L<<469.0,703.0>--<285.0,374.0>> -> L<<285.0,374.0>--<280.0,365.0>>

	* uni1EA0 (U+1EA0): L<<249.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* uni1EA0 (U+1EA0): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* uni1EF8 (U+1EF8): L<<223.0,365.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* uni1EF8 (U+1EF8): L<<469.0,703.0>--<285.0,374.0>> -> L<<285.0,374.0>--<280.0,365.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Ccaron (U+010C): B<<297.0,828.0>-<295.0,824.0>-<293.0,821.0>>/B<<293.0,821.0>-<294.0,823.0>-<294.0,822.5>> = 7.125016348901757

	* Ecaron (U+011A): B<<265.0,828.0>-<263.0,824.0>-<261.0,821.0>>/B<<261.0,821.0>-<262.0,823.0>-<261.5,822.5>> = 7.125016348901757

	* Gcaron (U+01E6): B<<309.0,828.0>-<308.0,824.0>-<306.0,821.0>>/B<<306.0,821.0>-<307.0,823.0>-<306.5,822.5>> = 7.125016348901757

	* Ncaron (U+0147): B<<271.0,828.0>-<270.0,824.0>-<268.0,821.0>>/B<<268.0,821.0>-<269.0,823.0>-<268.5,822.5>> = 7.125016348901757

	* Rcaron (U+0158): B<<271.0,828.0>-<269.0,824.0>-<267.0,821.0>>/B<<267.0,821.0>-<268.0,823.0>-<267.5,822.5>> = 7.125016348901757

	* Zcaron (U+017D): B<<282.0,828.0>-<281.0,824.0>-<279.0,821.0>>/B<<279.0,821.0>-<280.0,823.0>-<279.5,822.5>> = 7.125016348901757

	* caron (U+02C7): B<<356.0,594.0>-<354.0,591.0>-<352.0,588.0>>/B<<352.0,588.0>-<353.0,590.0>-<352.5,589.0>> = 7.125016348901757

	* ccaron (U+010D): B<<271.0,649.0>-<270.0,645.0>-<268.0,642.0>>/B<<268.0,642.0>-<269.0,644.0>-<268.5,643.5>> = 7.125016348901757

	* ecaron (U+011B): B<<289.0,649.0>-<287.0,645.0>-<285.0,642.0>>/B<<285.0,642.0>-<286.0,644.0>-<285.5,643.5>> = 7.125016348901757

	* gcaron (U+01E7): B<<300.0,649.0>-<299.0,645.0>-<297.0,642.0>>/B<<297.0,642.0>-<298.0,644.0>-<297.5,643.5>> = 7.125016348901757

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* ncaron (U+0148): B<<289.0,649.0>-<287.0,645.0>-<285.0,642.0>>/B<<285.0,642.0>-<286.0,644.0>-<286.0,643.5>> = 7.125016348901757

	* perthousand (U+2030): B<<316.0,212.0>-<316.0,217.0>-<317.0,223.0>>/L<<317.0,223.0>--<264.0,36.0>> = 6.361598723995848

	* rcaron (U+0159): B<<232.0,649.0>-<230.0,645.0>-<228.0,642.0>>/B<<228.0,642.0>-<229.0,644.0>-<229.0,643.5>> = 7.125016348901757

	* uni030C (U+030C): B<<356.0,594.0>-<354.0,591.0>-<352.0,588.0>>/B<<352.0,588.0>-<353.0,590.0>-<352.5,589.0>> = 7.125016348901757

	* zcaron (U+017E): B<<271.0,649.0>-<269.0,645.0>-<267.0,642.0>>/B<<267.0,642.0>-<268.0,644.0>-<267.5,643.5>> = 7.125016348901757 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* O (U+004F): L<<118.0,473.0>--<117.0,273.0>>

	* OE (U+0152): L<<118.0,473.0>--<117.0,273.0>>

	* Oacute (U+00D3): L<<118.0,473.0>--<117.0,273.0>>

	* Obreve (U+014E): L<<118.0,473.0>--<117.0,273.0>>

	* Ocircumflex (U+00D4): L<<118.0,473.0>--<117.0,273.0>>

	* Odieresis (U+00D6): L<<118.0,473.0>--<117.0,273.0>>

	* Ograve (U+00D2): L<<118.0,473.0>--<117.0,273.0>>

	* Ohungarumlaut (U+0150): L<<118.0,473.0>--<117.0,273.0>>

	* Omacron (U+014C): L<<118.0,473.0>--<117.0,273.0>>

	* Otilde (U+00D5): L<<118.0,473.0>--<117.0,273.0>>

	* Q (U+0051): L<<118.0,473.0>--<117.0,273.0>>

	* b (U+0062): L<<118.0,316.0>--<117.0,111.0>>

	* eng (U+014B): L<<411.0,33.0>--<410.0,327.0>>

	* eng (U+014B): L<<467.0,404.0>--<468.0,39.0>>

	* eng (U+014B): L<<468.0,28.0>--<467.0,-144.0>>

	* h (U+0068): L<<410.0,27.0>--<409.0,404.0>>

	* h (U+0068): L<<466.0,404.0>--<467.0,27.0>>

	* hbar (U+0127): L<<429.0,27.0>--<428.0,404.0>>

	* hbar (U+0127): L<<485.0,404.0>--<486.0,27.0>>

	* hcircumflex (U+0125): L<<410.0,27.0>--<409.0,404.0>>

	* hcircumflex (U+0125): L<<466.0,404.0>--<467.0,27.0>>

	* m (U+006D): L<<396.0,28.0>--<395.0,327.0>>

	* m (U+006D): L<<787.0,404.0>--<788.0,28.0>>

	* n (U+006E): L<<411.0,28.0>--<410.0,327.0>>

	* n (U+006E): L<<467.0,404.0>--<468.0,28.0>>

	* nacute (U+0144): L<<411.0,28.0>--<410.0,327.0>>

	* nacute (U+0144): L<<467.0,404.0>--<468.0,28.0>>

	* napostrophe (U+0149): L<<580.0,28.0>--<579.0,327.0>>

	* napostrophe (U+0149): L<<636.0,404.0>--<637.0,28.0>>

	* ncaron (U+0148): L<<411.0,28.0>--<410.0,327.0>>

	* ncaron (U+0148): L<<467.0,404.0>--<468.0,28.0>>

	* nmacronbelow (U+1E49): L<<411.0,28.0>--<410.0,327.0>>

	* nmacronbelow (U+1E49): L<<467.0,404.0>--<468.0,28.0>>

	* ntilde (U+00F1): L<<411.0,28.0>--<410.0,327.0>>

	* ntilde (U+00F1): L<<467.0,404.0>--<468.0,28.0>>

	* t (U+0074): L<<123.0,577.0>--<124.0,718.0>>

	* t (U+0074): L<<181.0,380.0>--<180.0,141.0>>

	* tbar (U+0167): L<<123.0,577.0>--<124.0,718.0>>

	* tcaron (U+0165): L<<123.0,577.0>--<124.0,718.0>>

	* tcaron (U+0165): L<<181.0,380.0>--<180.0,141.0>>

	* tmacronbelow (U+1E6F): L<<123.0,577.0>--<124.0,718.0>>

	* tmacronbelow (U+1E6F): L<<181.0,380.0>--<180.0,141.0>>

	* u (U+0075): L<<61.0,173.0>--<60.0,548.0>>

	* uacute (U+00FA): L<<61.0,173.0>--<60.0,548.0>>

	* ubreve (U+016D): L<<61.0,173.0>--<60.0,548.0>>

	* ucircumflex (U+00FB): L<<61.0,173.0>--<60.0,548.0>>

	* udieresis (U+00FC): L<<61.0,173.0>--<60.0,548.0>>

	* ugrave (U+00F9): L<<61.0,173.0>--<60.0,548.0>>

	* uhungarumlaut (U+0171): L<<61.0,173.0>--<60.0,548.0>>

	* umacron (U+016B): L<<61.0,173.0>--<60.0,548.0>>

	* uni00B5 (U+00B5): L<<126.0,548.0>--<127.0,173.0>>

	* uni00B5 (U+00B5): L<<70.0,173.0>--<69.0,548.0>>

	* uni0146 (U+0146): L<<411.0,28.0>--<410.0,327.0>>

	* uni0146 (U+0146): L<<467.0,404.0>--<468.0,28.0>>

	* uni0163 (U+0163): L<<123.0,577.0>--<124.0,718.0>>

	* uni0163 (U+0163): L<<181.0,380.0>--<180.0,141.0>>

	* uni01EA (U+01EA): L<<118.0,473.0>--<117.0,273.0>>

	* uni021B (U+021B): L<<123.0,577.0>--<124.0,718.0>>

	* uni021B (U+021B): L<<181.0,380.0>--<180.0,141.0>>

	* uni0233 (U+0233): L<<118.0,548.0>--<119.0,173.0>>

	* uni0233 (U+0233): L<<61.0,173.0>--<60.0,548.0>>

	* uni0272 (U+0272): L<<411.0,28.0>--<410.0,327.0>>

	* uni0272 (U+0272): L<<467.0,404.0>--<468.0,28.0>>

	* uni03BC (U+03BC): L<<143.0,548.0>--<144.0,173.0>>

	* uni03BC (U+03BC): L<<87.0,173.0>--<86.0,548.0>>

	* uni1E25 (U+1E25): L<<410.0,27.0>--<409.0,404.0>>

	* uni1E25 (U+1E25): L<<466.0,404.0>--<467.0,27.0>>

	* uni1E2B (U+1E2B): L<<410.0,27.0>--<409.0,404.0>>

	* uni1E2B (U+1E2B): L<<466.0,404.0>--<467.0,27.0>>

	* uni1E43 (U+1E43): L<<396.0,28.0>--<395.0,327.0>>

	* uni1E43 (U+1E43): L<<787.0,404.0>--<788.0,28.0>>

	* uni1E45 (U+1E45): L<<411.0,28.0>--<410.0,327.0>>

	* uni1E45 (U+1E45): L<<467.0,404.0>--<468.0,28.0>>

	* uni1E47 (U+1E47): L<<411.0,28.0>--<410.0,327.0>>

	* uni1E47 (U+1E47): L<<467.0,404.0>--<468.0,28.0>>

	* uni1E4C (U+1E4C): L<<118.0,473.0>--<117.0,273.0>>

	* uni1E4E (U+1E4E): L<<118.0,473.0>--<117.0,273.0>>

	* uni1E50 (U+1E50): L<<118.0,473.0>--<117.0,273.0>>

	* uni1E52 (U+1E52): L<<118.0,473.0>--<117.0,273.0>>

	* uni1E6D (U+1E6D): L<<123.0,577.0>--<124.0,718.0>>

	* uni1E6D (U+1E6D): L<<181.0,380.0>--<180.0,141.0>>

	* uni1E79 (U+1E79): L<<61.0,173.0>--<60.0,548.0>>

	* uni1E7B (U+1E7B): L<<61.0,173.0>--<60.0,548.0>>

	* uni1E8F (U+1E8F): L<<118.0,548.0>--<119.0,173.0>>

	* uni1E8F (U+1E8F): L<<61.0,173.0>--<60.0,548.0>>

	* uni1E97 (U+1E97): L<<123.0,577.0>--<124.0,718.0>>

	* uni1E97 (U+1E97): L<<181.0,380.0>--<180.0,141.0>>

	* uni1E9E (U+1E9E): L<<70.0,29.0>--<71.0,718.0>>

	* uni1ECC (U+1ECC): L<<118.0,473.0>--<117.0,273.0>>

	* uni1EE5 (U+1EE5): L<<61.0,173.0>--<60.0,548.0>>

	* uni1EF9 (U+1EF9): L<<118.0,548.0>--<119.0,173.0>>

	* uni1EF9 (U+1EF9): L<<61.0,173.0>--<60.0,548.0>>

	* uogonek (U+0173): L<<61.0,173.0>--<60.0,548.0>>

	* uring (U+016F): L<<61.0,173.0>--<60.0,548.0>>

	* utilde (U+0169): L<<61.0,173.0>--<60.0,548.0>>

	* y (U+0079): L<<118.0,548.0>--<119.0,173.0>>

	* y (U+0079): L<<61.0,173.0>--<60.0,548.0>>

	* yacute (U+00FD): L<<118.0,548.0>--<119.0,173.0>>

	* yacute (U+00FD): L<<61.0,173.0>--<60.0,548.0>>

	* ycircumflex (U+0177): L<<118.0,548.0>--<119.0,173.0>>

	* ycircumflex (U+0177): L<<61.0,173.0>--<60.0,548.0>>

	* ydieresis (U+00FF): L<<118.0,548.0>--<119.0,173.0>>

	* ydieresis (U+00FF): L<<61.0,173.0>--<60.0,548.0>>

	* ygrave (U+1EF3): L<<118.0,548.0>--<119.0,173.0>>

	* ygrave (U+1EF3): L<<61.0,173.0>--<60.0,548.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] LibertineSuper-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check family name for GF Guide compliance. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_name_compliance">com.google.fonts/check/name/family_name_compliance</a>)</summary><div>


* 🔥 **FAIL** "LibertineSuper" is a CamelCased name. To solve this, simply use spaces instead in the font name. [code: camelcase]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.683x (1683) [code: bad-hhea-range]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: percent	Contours detected: 7	Expected: 5

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: J	Contours detected: 2	Expected: 1

	- Glyph name: O	Contours detected: 3	Expected: 2

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

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

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: Scedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: scedilla	Contours detected: 4	Expected: 1or2

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

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2or3

	- Glyph name: Aring	Contours detected: 5	Expected: 3or4

	- Glyph name: Aringacute	Contours detected: 6	Expected: 3, 4or5

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 4	Expected: 2or3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1or2

	- Glyph name: Ccircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: H	Contours detected: 2	Expected: 1

	- Glyph name: Hbar	Contours detected: 3	Expected: 2

	- Glyph name: Hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: IJ	Contours detected: 3	Expected: 1or2

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

	- Glyph name: P	Contours detected: 3	Expected: 1or2

	- Glyph name: Q	Contours detected: 3	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1or2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 2	Expected: 1

	- Glyph name: Sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scaron	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Thorn	Contours detected: 3	Expected: 1or2

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

	- Glyph name: W	Contours detected: 3	Expected: 1or2

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

	- Glyph name: ampersand	Contours detected: 4	Expected: 1, 2or3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: aringacute	Contours detected: 6	Expected: 4or5

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

	* A (U+0041): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Aacute (U+00C1): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Abreve (U+0102): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Acircumflex (U+00C2): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Adieresis (U+00C4): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Agrave (U+00C0): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Amacron (U+0100): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Aogonek (U+0104): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Aring (U+00C5): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Aringacute (U+01FA): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* Atilde (U+00C3): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* C (U+0043): L<<309.0,90.0>--<314.0,90.0>> -> L<<314.0,90.0>--<328.0,90.0>>

	* C (U+0043): L<<328.0,657.0>--<314.0,657.0>> -> L<<314.0,657.0>--<309.0,657.0>>

	* Cacute (U+0106): L<<309.0,90.0>--<314.0,90.0>> -> L<<314.0,90.0>--<328.0,90.0>>

	* Cacute (U+0106): L<<328.0,657.0>--<314.0,657.0>> -> L<<314.0,657.0>--<309.0,657.0>>

	* Ccaron (U+010C): L<<309.0,90.0>--<314.0,90.0>> -> L<<314.0,90.0>--<328.0,90.0>>

	* Ccaron (U+010C): L<<328.0,657.0>--<314.0,657.0>> -> L<<314.0,657.0>--<309.0,657.0>>

	* Ccedilla (U+00C7): L<<309.0,90.0>--<314.0,90.0>> -> L<<314.0,90.0>--<328.0,90.0>>

	* Ccedilla (U+00C7): L<<328.0,657.0>--<314.0,657.0>> -> L<<314.0,657.0>--<309.0,657.0>>

	* Ccircumflex (U+0108): L<<309.0,90.0>--<314.0,90.0>> -> L<<314.0,90.0>--<328.0,90.0>>

	* Ccircumflex (U+0108): L<<328.0,657.0>--<314.0,657.0>> -> L<<314.0,657.0>--<309.0,657.0>>

	* Cdotaccent (U+010A): L<<309.0,90.0>--<314.0,90.0>> -> L<<314.0,90.0>--<328.0,90.0>>

	* Cdotaccent (U+010A): L<<328.0,657.0>--<314.0,657.0>> -> L<<314.0,657.0>--<309.0,657.0>>

	* R (U+0052): L<<327.0,188.0>--<322.0,188.0>> -> L<<322.0,188.0>--<165.0,188.0>>

	* Racute (U+0154): L<<327.0,188.0>--<322.0,188.0>> -> L<<322.0,188.0>--<165.0,188.0>>

	* Rcaron (U+0158): L<<327.0,188.0>--<322.0,188.0>> -> L<<322.0,188.0>--<165.0,188.0>>

	* Rmacronbelow (U+1E5E): L<<327.0,188.0>--<322.0,188.0>> -> L<<322.0,188.0>--<165.0,188.0>>

	* Y (U+0059): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,674.0>>

	* Y (U+0059): L<<512.0,674.0>--<331.0,374.0>> -> L<<331.0,374.0>--<322.0,359.0>>

	* Yacute (U+00DD): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,674.0>>

	* Yacute (U+00DD): L<<512.0,674.0>--<331.0,374.0>> -> L<<331.0,374.0>--<322.0,359.0>>

	* Ycircumflex (U+0176): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,674.0>>

	* Ycircumflex (U+0176): L<<512.0,674.0>--<331.0,374.0>> -> L<<331.0,374.0>--<322.0,359.0>>

	* Ydieresis (U+0178): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,674.0>>

	* Ydieresis (U+0178): L<<512.0,674.0>--<331.0,374.0>> -> L<<331.0,374.0>--<322.0,359.0>>

	* Ygrave (U+1EF2): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,674.0>>

	* Ygrave (U+1EF2): L<<512.0,674.0>--<331.0,374.0>> -> L<<331.0,374.0>--<322.0,359.0>>

	* comma (U+002C): L<<174.0,57.0>--<174.0,57.0>> -> L<<174.0,57.0>--<174.0,57.0>>

	* eng (U+014B): L<<418.0,-144.0>--<419.0,55.0>> -> L<<419.0,55.0>--<418.0,291.0>>

	* semicolon (U+003B): L<<174.0,57.0>--<174.0,57.0>> -> L<<174.0,57.0>--<174.0,57.0>>

	* trademark (U+2122): L<<654.0,760.0>--<654.0,760.0>> -> L<<654.0,760.0>--<654.0,760.0>>

	* u (U+0075): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uacute (U+00FA): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* ubreve (U+016D): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* ucircumflex (U+00FB): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* udieresis (U+00FC): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* ugrave (U+00F9): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uhungarumlaut (U+0171): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* umacron (U+016B): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uni00B5 (U+00B5): L<<69.0,-136.0>--<69.0,183.0>> -> L<<69.0,183.0>--<68.0,539.0>>

	* uni0156 (U+0156): L<<327.0,188.0>--<322.0,188.0>> -> L<<322.0,188.0>--<165.0,188.0>>

	* uni0232 (U+0232): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,674.0>>

	* uni0232 (U+0232): L<<512.0,674.0>--<331.0,374.0>> -> L<<331.0,374.0>--<322.0,359.0>>

	* uni03BC (U+03BC): L<<103.0,-136.0>--<103.0,183.0>> -> L<<103.0,183.0>--<102.0,539.0>>

	* uni1E08 (U+1E08): L<<309.0,90.0>--<314.0,90.0>> -> L<<314.0,90.0>--<328.0,90.0>>

	* uni1E08 (U+1E08): L<<328.0,657.0>--<314.0,657.0>> -> L<<314.0,657.0>--<309.0,657.0>>

	* uni1E5A (U+1E5A): L<<327.0,188.0>--<322.0,188.0>> -> L<<322.0,188.0>--<165.0,188.0>>

	* uni1E79 (U+1E79): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uni1E7B (U+1E7B): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uni1E8E (U+1E8E): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,674.0>>

	* uni1E8E (U+1E8E): L<<512.0,674.0>--<331.0,374.0>> -> L<<331.0,374.0>--<322.0,359.0>>

	* uni1EA0 (U+1EA0): L<<273.0,751.0>--<273.0,751.0>> -> L<<273.0,751.0>--<273.0,751.0>>

	* uni1EE5 (U+1EE5): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uni1EF8 (U+1EF8): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,674.0>>

	* uni1EF8 (U+1EF8): L<<512.0,674.0>--<331.0,374.0>> -> L<<331.0,374.0>--<322.0,359.0>>

	* uogonek (U+0173): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uring (U+016F): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* utilde (U+0169): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<223.5,29.0>-<223.0,30.0>-<224.0,28.0>>/B<<224.0,28.0>-<222.0,31.0>-<222.0,34.0>> = 7.125016348901757

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* w (U+0077): B<<63.0,585.5>-<64.0,586.0>-<62.0,585.0>>/B<<62.0,585.0>-<65.0,586.0>-<68.0,586.0>> = 8.13010235415587

	* wacute (U+1E83): B<<63.0,585.5>-<64.0,586.0>-<62.0,585.0>>/B<<62.0,585.0>-<65.0,586.0>-<68.0,586.0>> = 8.13010235415587

	* wcircumflex (U+0175): B<<63.0,585.5>-<64.0,586.0>-<62.0,585.0>>/B<<62.0,585.0>-<65.0,586.0>-<68.0,586.0>> = 8.13010235415587

	* wdieresis (U+1E85): B<<63.0,585.5>-<64.0,586.0>-<62.0,585.0>>/B<<62.0,585.0>-<65.0,586.0>-<68.0,586.0>> = 8.13010235415587

	* wgrave (U+1E81): B<<63.0,585.5>-<64.0,586.0>-<62.0,585.0>>/B<<62.0,585.0>-<65.0,586.0>-<68.0,586.0>> = 8.13010235415587 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<418.0,-144.0>--<419.0,55.0>>

	* eng (U+014B): L<<419.0,55.0>--<418.0,291.0>>

	* h (U+0068): L<<419.0,46.0>--<418.0,402.0>>

	* h (U+0068): L<<512.0,402.0>--<513.0,46.0>>

	* hbar (U+0127): L<<456.0,46.0>--<455.0,402.0>>

	* hbar (U+0127): L<<550.0,402.0>--<551.0,46.0>>

	* hcircumflex (U+0125): L<<419.0,46.0>--<418.0,402.0>>

	* hcircumflex (U+0125): L<<512.0,402.0>--<513.0,46.0>>

	* m (U+006D): L<<403.0,47.0>--<402.0,291.0>>

	* m (U+006D): L<<747.0,47.0>--<746.0,291.0>>

	* m (U+006D): L<<841.0,402.0>--<842.0,47.0>>

	* n (U+006E): L<<419.0,47.0>--<418.0,291.0>>

	* n (U+006E): L<<513.0,402.0>--<514.0,47.0>>

	* nacute (U+0144): L<<419.0,47.0>--<418.0,291.0>>

	* nacute (U+0144): L<<513.0,402.0>--<514.0,47.0>>

	* napostrophe (U+0149): L<<626.0,47.0>--<625.0,291.0>>

	* napostrophe (U+0149): L<<720.0,402.0>--<721.0,47.0>>

	* ncaron (U+0148): L<<419.0,47.0>--<418.0,291.0>>

	* ncaron (U+0148): L<<513.0,402.0>--<514.0,47.0>>

	* nmacronbelow (U+1E49): L<<419.0,47.0>--<418.0,291.0>>

	* nmacronbelow (U+1E49): L<<513.0,402.0>--<514.0,47.0>>

	* ntilde (U+00F1): L<<419.0,47.0>--<418.0,291.0>>

	* ntilde (U+00F1): L<<513.0,402.0>--<514.0,47.0>>

	* t (U+0074): L<<125.0,147.0>--<126.0,330.0>>

	* t (U+0074): L<<221.0,330.0>--<220.0,161.0>>

	* tcaron (U+0165): L<<125.0,147.0>--<126.0,330.0>>

	* tcaron (U+0165): L<<221.0,330.0>--<220.0,161.0>>

	* tmacronbelow (U+1E6F): L<<125.0,147.0>--<126.0,330.0>>

	* tmacronbelow (U+1E6F): L<<221.0,330.0>--<220.0,161.0>>

	* u (U+0075): L<<155.0,539.0>--<156.0,260.0>>

	* u (U+0075): L<<61.0,183.0>--<60.0,539.0>>

	* uacute (U+00FA): L<<155.0,539.0>--<156.0,260.0>>

	* uacute (U+00FA): L<<61.0,183.0>--<60.0,539.0>>

	* ubreve (U+016D): L<<155.0,539.0>--<156.0,260.0>>

	* ubreve (U+016D): L<<61.0,183.0>--<60.0,539.0>>

	* ucircumflex (U+00FB): L<<155.0,539.0>--<156.0,260.0>>

	* ucircumflex (U+00FB): L<<61.0,183.0>--<60.0,539.0>>

	* udieresis (U+00FC): L<<155.0,539.0>--<156.0,260.0>>

	* udieresis (U+00FC): L<<61.0,183.0>--<60.0,539.0>>

	* ugrave (U+00F9): L<<155.0,539.0>--<156.0,260.0>>

	* ugrave (U+00F9): L<<61.0,183.0>--<60.0,539.0>>

	* uhungarumlaut (U+0171): L<<155.0,539.0>--<156.0,260.0>>

	* uhungarumlaut (U+0171): L<<61.0,183.0>--<60.0,539.0>>

	* umacron (U+016B): L<<155.0,539.0>--<156.0,260.0>>

	* umacron (U+016B): L<<61.0,183.0>--<60.0,539.0>>

	* uni00B5 (U+00B5): L<<163.0,539.0>--<164.0,183.0>>

	* uni00B5 (U+00B5): L<<69.0,183.0>--<68.0,539.0>>

	* uni0146 (U+0146): L<<419.0,47.0>--<418.0,291.0>>

	* uni0146 (U+0146): L<<513.0,402.0>--<514.0,47.0>>

	* uni0163 (U+0163): L<<125.0,147.0>--<126.0,330.0>>

	* uni0163 (U+0163): L<<221.0,330.0>--<220.0,161.0>>

	* uni021B (U+021B): L<<125.0,147.0>--<126.0,330.0>>

	* uni021B (U+021B): L<<221.0,330.0>--<220.0,161.0>>

	* uni0233 (U+0233): L<<155.0,539.0>--<156.0,183.0>>

	* uni0233 (U+0233): L<<61.0,183.0>--<60.0,539.0>>

	* uni0272 (U+0272): L<<419.0,47.0>--<418.0,291.0>>

	* uni0272 (U+0272): L<<513.0,402.0>--<514.0,47.0>>

	* uni03BC (U+03BC): L<<103.0,183.0>--<102.0,539.0>>

	* uni03BC (U+03BC): L<<197.0,539.0>--<198.0,183.0>>

	* uni1E25 (U+1E25): L<<419.0,46.0>--<418.0,402.0>>

	* uni1E25 (U+1E25): L<<512.0,402.0>--<513.0,46.0>>

	* uni1E2B (U+1E2B): L<<419.0,46.0>--<418.0,402.0>>

	* uni1E2B (U+1E2B): L<<512.0,402.0>--<513.0,46.0>>

	* uni1E43 (U+1E43): L<<403.0,47.0>--<402.0,291.0>>

	* uni1E43 (U+1E43): L<<747.0,47.0>--<746.0,291.0>>

	* uni1E43 (U+1E43): L<<841.0,402.0>--<842.0,47.0>>

	* uni1E45 (U+1E45): L<<419.0,47.0>--<418.0,291.0>>

	* uni1E45 (U+1E45): L<<513.0,402.0>--<514.0,47.0>>

	* uni1E47 (U+1E47): L<<419.0,47.0>--<418.0,291.0>>

	* uni1E47 (U+1E47): L<<513.0,402.0>--<514.0,47.0>>

	* uni1E6D (U+1E6D): L<<125.0,147.0>--<126.0,330.0>>

	* uni1E6D (U+1E6D): L<<221.0,330.0>--<220.0,161.0>>

	* uni1E79 (U+1E79): L<<155.0,539.0>--<156.0,260.0>>

	* uni1E79 (U+1E79): L<<61.0,183.0>--<60.0,539.0>>

	* uni1E7B (U+1E7B): L<<155.0,539.0>--<156.0,260.0>>

	* uni1E7B (U+1E7B): L<<61.0,183.0>--<60.0,539.0>>

	* uni1E8F (U+1E8F): L<<155.0,539.0>--<156.0,183.0>>

	* uni1E8F (U+1E8F): L<<61.0,183.0>--<60.0,539.0>>

	* uni1E97 (U+1E97): L<<125.0,147.0>--<126.0,330.0>>

	* uni1E97 (U+1E97): L<<221.0,330.0>--<220.0,161.0>>

	* uni1E9E (U+1E9E): L<<166.0,652.0>--<165.0,48.0>>

	* uni1E9E (U+1E9E): L<<70.0,48.0>--<71.0,700.0>>

	* uni1EE5 (U+1EE5): L<<155.0,539.0>--<156.0,260.0>>

	* uni1EE5 (U+1EE5): L<<61.0,183.0>--<60.0,539.0>>

	* uni1EF9 (U+1EF9): L<<155.0,539.0>--<156.0,183.0>>

	* uni1EF9 (U+1EF9): L<<61.0,183.0>--<60.0,539.0>>

	* uogonek (U+0173): L<<155.0,539.0>--<156.0,260.0>>

	* uogonek (U+0173): L<<61.0,183.0>--<60.0,539.0>>

	* uring (U+016F): L<<155.0,539.0>--<156.0,260.0>>

	* uring (U+016F): L<<61.0,183.0>--<60.0,539.0>>

	* utilde (U+0169): L<<155.0,539.0>--<156.0,260.0>>

	* utilde (U+0169): L<<61.0,183.0>--<60.0,539.0>>

	* y (U+0079): L<<155.0,539.0>--<156.0,183.0>>

	* y (U+0079): L<<61.0,183.0>--<60.0,539.0>>

	* yacute (U+00FD): L<<155.0,539.0>--<156.0,183.0>>

	* yacute (U+00FD): L<<61.0,183.0>--<60.0,539.0>>

	* ycircumflex (U+0177): L<<155.0,539.0>--<156.0,183.0>>

	* ycircumflex (U+0177): L<<61.0,183.0>--<60.0,539.0>>

	* ydieresis (U+00FF): L<<155.0,539.0>--<156.0,183.0>>

	* ydieresis (U+00FF): L<<61.0,183.0>--<60.0,539.0>>

	* ygrave (U+1EF3): L<<155.0,539.0>--<156.0,183.0>>

	* ygrave (U+1EF3): L<<61.0,183.0>--<60.0,539.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 43 | 716 | 43 | 607 | 0 |
| 0% | 0% | 3% | 51% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
