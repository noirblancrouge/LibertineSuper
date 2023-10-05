## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[6] LibertineSup-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
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

	* u (U+0075): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uacute (U+00FA): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* ubreve (U+016D): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* ucircumflex (U+00FB): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* udieresis (U+00FC): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* ugrave (U+00F9): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uhungarumlaut (U+0171): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* umacron (U+016B): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uni1E79 (U+1E79): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uni1E7B (U+1E7B): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uni1EE5 (U+1EE5): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uogonek (U+0173): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* uring (U+016F): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>>

	* utilde (U+0169): L<<419.0,260.0>--<419.0,265.0>> -> L<<419.0,265.0>--<419.0,539.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Oslash (U+00D8): L<<488.0,279.0>--<487.0,468.0>>

	* Oslashacute (U+01FE): L<<488.0,279.0>--<487.0,468.0>>

	* h (U+0068): L<<419.0,46.0>--<418.0,402.0>>

	* h (U+0068): L<<512.0,402.0>--<513.0,46.0>>

	* hbar (U+0127): L<<456.0,46.0>--<455.0,402.0>>

	* hbar (U+0127): L<<550.0,402.0>--<551.0,46.0>>

	* hcircumflex (U+0125): L<<419.0,46.0>--<418.0,402.0>>

	* hcircumflex (U+0125): L<<512.0,402.0>--<513.0,46.0>>

	* m (U+006D): L<<403.0,47.0>--<402.0,291.0>>

	* m (U+006D): L<<747.0,47.0>--<746.0,291.0>>

	* m (U+006D): L<<841.0,402.0>--<842.0,47.0>>

	* t (U+0074): L<<125.0,147.0>--<126.0,330.0>>

	* t (U+0074): L<<221.0,330.0>--<220.0,161.0>>

	* tcaron (U+0165): L<<125.0,147.0>--<126.0,330.0>>

	* tcaron (U+0165): L<<221.0,330.0>--<220.0,161.0>>

	* tmacronbelow (U+1E6F): L<<125.0,147.0>--<126.0,330.0>>

	* tmacronbelow (U+1E6F): L<<221.0,330.0>--<220.0,161.0>>

	* uni0163 (U+0163): L<<125.0,147.0>--<126.0,330.0>>

	* uni0163 (U+0163): L<<221.0,330.0>--<220.0,161.0>>

	* uni021B (U+021B): L<<125.0,147.0>--<126.0,330.0>>

	* uni021B (U+021B): L<<221.0,330.0>--<220.0,161.0>>

	* uni0233 (U+0233): L<<155.0,539.0>--<156.0,183.0>>

	* uni0233 (U+0233): L<<61.0,183.0>--<60.0,539.0>>

	* uni1E25 (U+1E25): L<<419.0,46.0>--<418.0,402.0>>

	* uni1E25 (U+1E25): L<<512.0,402.0>--<513.0,46.0>>

	* uni1E2B (U+1E2B): L<<419.0,46.0>--<418.0,402.0>>

	* uni1E2B (U+1E2B): L<<512.0,402.0>--<513.0,46.0>>

	* uni1E43 (U+1E43): L<<403.0,47.0>--<402.0,291.0>>

	* uni1E43 (U+1E43): L<<747.0,47.0>--<746.0,291.0>>

	* uni1E43 (U+1E43): L<<841.0,402.0>--<842.0,47.0>>

	* uni1E6D (U+1E6D): L<<125.0,147.0>--<126.0,330.0>>

	* uni1E6D (U+1E6D): L<<221.0,330.0>--<220.0,161.0>>

	* uni1E8F (U+1E8F): L<<155.0,539.0>--<156.0,183.0>>

	* uni1E8F (U+1E8F): L<<61.0,183.0>--<60.0,539.0>>

	* uni1E97 (U+1E97): L<<125.0,147.0>--<126.0,330.0>>

	* uni1E97 (U+1E97): L<<221.0,330.0>--<220.0,161.0>>

	* uni1E9E (U+1E9E): L<<166.0,652.0>--<165.0,48.0>>

	* uni1E9E (U+1E9E): L<<70.0,48.0>--<71.0,700.0>>

	* uni1EF9 (U+1EF9): L<<155.0,539.0>--<156.0,183.0>>

	* uni1EF9 (U+1EF9): L<<61.0,183.0>--<60.0,539.0>>

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
</div></details><br></div></details><details><summary><b>[5] LibertineSup-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
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
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<424.0,58.0>--<423.0,400.0>>

	* h (U+0068): L<<543.0,400.0>--<544.0,58.0>>

	* hbar (U+0127): L<<474.0,58.0>--<473.0,400.0>>

	* hbar (U+0127): L<<593.0,400.0>--<594.0,58.0>>

	* hcircumflex (U+0125): L<<424.0,58.0>--<423.0,400.0>>

	* hcircumflex (U+0125): L<<543.0,400.0>--<544.0,58.0>>

	* m (U+006D): L<<408.0,59.0>--<407.0,267.0>>

	* m (U+006D): L<<757.0,59.0>--<756.0,267.0>>

	* m (U+006D): L<<876.0,400.0>--<877.0,59.0>>

	* uni0233 (U+0233): L<<180.0,532.0>--<181.0,190.0>>

	* uni0233 (U+0233): L<<61.0,190.0>--<60.0,532.0>>

	* uni1E25 (U+1E25): L<<424.0,58.0>--<423.0,400.0>>

	* uni1E25 (U+1E25): L<<543.0,400.0>--<544.0,58.0>>

	* uni1E2B (U+1E2B): L<<424.0,58.0>--<423.0,400.0>>

	* uni1E2B (U+1E2B): L<<543.0,400.0>--<544.0,58.0>>

	* uni1E43 (U+1E43): L<<408.0,59.0>--<407.0,267.0>>

	* uni1E43 (U+1E43): L<<757.0,59.0>--<756.0,267.0>>

	* uni1E43 (U+1E43): L<<876.0,400.0>--<877.0,59.0>>

	* uni1E8F (U+1E8F): L<<180.0,532.0>--<181.0,190.0>>

	* uni1E8F (U+1E8F): L<<61.0,190.0>--<60.0,532.0>>

	* uni1E9E (U+1E9E): L<<191.0,627.0>--<190.0,60.0>>

	* uni1E9E (U+1E9E): L<<70.0,60.0>--<71.0,687.0>>

	* uni1EF9 (U+1EF9): L<<180.0,532.0>--<181.0,190.0>>

	* uni1EF9 (U+1EF9): L<<61.0,190.0>--<60.0,532.0>>

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
</div></details><br></div></details><details><summary><b>[6] LibertineSup-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
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

	* g (U+0067): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* gbreve (U+011F): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* gcaron (U+01E7): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* gcircumflex (U+011D): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* gdotaccent (U+0121): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* p (U+0070): L<<280.0,65.0>--<282.0,65.0>> -> L<<282.0,65.0>--<295.0,65.0>>

	* q (U+0071): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* s (U+0073): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* sacute (U+015B): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* scaron (U+0161): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* scedilla (U+015F): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* scircumflex (U+015D): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* three (U+0033): L<<413.0,226.0>--<413.0,227.0>> -> L<<413.0,227.0>--<413.0,230.0>>

	* threequarters (U+00BE): L<<255.0,532.0>--<255.0,533.0>> -> L<<255.0,533.0>--<255.0,534.0>>

	* uni00B3 (U+00B3): L<<250.0,532.0>--<250.0,533.0>> -> L<<250.0,533.0>--<250.0,534.0>>

	* uni0123 (U+0123): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* uni0219 (U+0219): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* uni1E21 (U+1E21): L<<290.0,-5.0>--<285.0,-5.0>> -> L<<285.0,-5.0>--<272.0,-5.0>>

	* uni1E61 (U+1E61): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* uni1E63 (U+1E63): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* uni1E65 (U+1E65): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* uni1E67 (U+1E67): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* uni1E69 (U+1E69): L<<35.0,96.0>--<35.0,96.0>> -> L<<35.0,96.0>--<35.0,96.0>>

	* uni2083 (U+2083): L<<250.0,137.0>--<250.0,138.0>> -> L<<250.0,138.0>--<250.0,139.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* perthousand (U+2030): B<<181.5,275.0>-<187.0,307.0>-<200.0,333.0>>/L<<200.0,333.0>--<52.0,128.0>> = 9.262395902795747

	* perthousand (U+2030): B<<329.0,211.0>-<329.0,239.0>-<333.0,265.0>>/L<<333.0,265.0>--<268.0,41.0>> = 7.435433982627346

	* perthousand (U+2030): L<<352.0,333.0>--<351.0,329.0>>/L<<351.0,329.0>--<353.0,333.0>> = 12.528807709151522

	* perthousand (U+2030): L<<482.0,721.0>--<226.0,369.0>>/B<<226.0,369.0>-<240.0,381.0>-<257.5,388.5>> = 13.371331969891953 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* O (U+004F): L<<482.0,275.0>--<481.0,472.0>>

	* OE (U+0152): L<<482.0,275.0>--<481.0,472.0>>

	* Oacute (U+00D3): L<<482.0,275.0>--<481.0,472.0>>

	* Obreve (U+014E): L<<482.0,275.0>--<481.0,472.0>>

	* Ocircumflex (U+00D4): L<<482.0,275.0>--<481.0,472.0>>

	* Odieresis (U+00D6): L<<482.0,275.0>--<481.0,472.0>>

	* Ograve (U+00D2): L<<482.0,275.0>--<481.0,472.0>>

	* Ohungarumlaut (U+0150): L<<482.0,275.0>--<481.0,472.0>>

	* Omacron (U+014C): L<<482.0,275.0>--<481.0,472.0>>

	* Otilde (U+00D5): L<<482.0,275.0>--<481.0,472.0>>

	* Q (U+0051): L<<482.0,275.0>--<481.0,472.0>>

	* h (U+0068): L<<413.0,34.0>--<412.0,403.0>>

	* h (U+0068): L<<482.0,403.0>--<483.0,34.0>>

	* hbar (U+0127): L<<438.0,34.0>--<437.0,403.0>>

	* hbar (U+0127): L<<507.0,403.0>--<508.0,34.0>>

	* hcircumflex (U+0125): L<<413.0,34.0>--<412.0,403.0>>

	* hcircumflex (U+0125): L<<482.0,403.0>--<483.0,34.0>>

	* m (U+006D): L<<398.0,35.0>--<397.0,315.0>>

	* m (U+006D): L<<737.0,35.0>--<736.0,315.0>>

	* m (U+006D): L<<805.0,403.0>--<806.0,35.0>>

	* t (U+0074): L<<124.0,580.0>--<125.0,712.0>>

	* t (U+0074): L<<195.0,712.0>--<194.0,580.0>>

	* tbar (U+0167): L<<124.0,580.0>--<125.0,712.0>>

	* tbar (U+0167): L<<195.0,712.0>--<194.0,580.0>>

	* tcaron (U+0165): L<<124.0,580.0>--<125.0,712.0>>

	* tcaron (U+0165): L<<195.0,712.0>--<194.0,580.0>>

	* tmacronbelow (U+1E6F): L<<124.0,580.0>--<125.0,712.0>>

	* tmacronbelow (U+1E6F): L<<195.0,712.0>--<194.0,580.0>>

	* uni0163 (U+0163): L<<124.0,580.0>--<125.0,712.0>>

	* uni0163 (U+0163): L<<195.0,712.0>--<194.0,580.0>>

	* uni01EA (U+01EA): L<<482.0,275.0>--<481.0,472.0>>

	* uni021B (U+021B): L<<124.0,580.0>--<125.0,712.0>>

	* uni021B (U+021B): L<<195.0,712.0>--<194.0,580.0>>

	* uni0233 (U+0233): L<<130.0,545.0>--<131.0,176.0>>

	* uni0233 (U+0233): L<<61.0,176.0>--<60.0,545.0>>

	* uni1E25 (U+1E25): L<<413.0,34.0>--<412.0,403.0>>

	* uni1E25 (U+1E25): L<<482.0,403.0>--<483.0,34.0>>

	* uni1E2B (U+1E2B): L<<413.0,34.0>--<412.0,403.0>>

	* uni1E2B (U+1E2B): L<<482.0,403.0>--<483.0,34.0>>

	* uni1E43 (U+1E43): L<<398.0,35.0>--<397.0,315.0>>

	* uni1E43 (U+1E43): L<<737.0,35.0>--<736.0,315.0>>

	* uni1E43 (U+1E43): L<<805.0,403.0>--<806.0,35.0>>

	* uni1E4C (U+1E4C): L<<482.0,275.0>--<481.0,472.0>>

	* uni1E4E (U+1E4E): L<<482.0,275.0>--<481.0,472.0>>

	* uni1E50 (U+1E50): L<<482.0,275.0>--<481.0,472.0>>

	* uni1E52 (U+1E52): L<<482.0,275.0>--<481.0,472.0>>

	* uni1E6D (U+1E6D): L<<124.0,580.0>--<125.0,712.0>>

	* uni1E6D (U+1E6D): L<<195.0,712.0>--<194.0,580.0>>

	* uni1E8F (U+1E8F): L<<130.0,545.0>--<131.0,176.0>>

	* uni1E8F (U+1E8F): L<<61.0,176.0>--<60.0,545.0>>

	* uni1E97 (U+1E97): L<<124.0,580.0>--<125.0,712.0>>

	* uni1E97 (U+1E97): L<<195.0,712.0>--<194.0,580.0>>

	* uni1E9E (U+1E9E): L<<141.0,677.0>--<140.0,35.0>>

	* uni1E9E (U+1E9E): L<<70.0,35.0>--<71.0,712.0>>

	* uni1ECC (U+1ECC): L<<482.0,275.0>--<481.0,472.0>>

	* uni1EF9 (U+1EF9): L<<130.0,545.0>--<131.0,176.0>>

	* uni1EF9 (U+1EF9): L<<61.0,176.0>--<60.0,545.0>>

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
</div></details><br></div></details><details><summary><b>[6] LibertineSup-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
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

	* s (U+0073): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* sacute (U+015B): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* scaron (U+0161): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* scedilla (U+015F): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* scircumflex (U+015D): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* thorn (U+00FE): L<<269.0,52.0>--<274.0,52.0>> -> L<<274.0,52.0>--<287.0,52.0>>

	* uni0219 (U+0219): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* uni03A9 (U+03A9): L<<293.0,-5.0>--<292.0,-5.0>> -> L<<292.0,-5.0>--<291.0,-5.0>>

	* uni1E61 (U+1E61): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* uni1E63 (U+1E63): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* uni1E65 (U+1E65): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* uni1E67 (U+1E67): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>>

	* uni1E69 (U+1E69): L<<35.0,91.0>--<35.0,91.0>> -> L<<35.0,91.0>--<35.0,91.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111 [code: found-jaggy-segments]
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

	* h (U+0068): L<<410.0,27.0>--<409.0,404.0>>

	* h (U+0068): L<<466.0,404.0>--<467.0,27.0>>

	* hbar (U+0127): L<<429.0,27.0>--<428.0,404.0>>

	* hbar (U+0127): L<<485.0,404.0>--<486.0,27.0>>

	* hcircumflex (U+0125): L<<410.0,27.0>--<409.0,404.0>>

	* hcircumflex (U+0125): L<<466.0,404.0>--<467.0,27.0>>

	* m (U+006D): L<<396.0,28.0>--<395.0,327.0>>

	* m (U+006D): L<<787.0,404.0>--<788.0,28.0>>

	* t (U+0074): L<<123.0,577.0>--<124.0,718.0>>

	* t (U+0074): L<<181.0,380.0>--<180.0,141.0>>

	* tbar (U+0167): L<<123.0,577.0>--<124.0,718.0>>

	* tcaron (U+0165): L<<123.0,577.0>--<124.0,718.0>>

	* tcaron (U+0165): L<<181.0,380.0>--<180.0,141.0>>

	* tmacronbelow (U+1E6F): L<<123.0,577.0>--<124.0,718.0>>

	* tmacronbelow (U+1E6F): L<<181.0,380.0>--<180.0,141.0>>

	* uni0163 (U+0163): L<<123.0,577.0>--<124.0,718.0>>

	* uni0163 (U+0163): L<<181.0,380.0>--<180.0,141.0>>

	* uni01EA (U+01EA): L<<118.0,473.0>--<117.0,273.0>>

	* uni021B (U+021B): L<<123.0,577.0>--<124.0,718.0>>

	* uni021B (U+021B): L<<181.0,380.0>--<180.0,141.0>>

	* uni0233 (U+0233): L<<118.0,548.0>--<119.0,173.0>>

	* uni0233 (U+0233): L<<61.0,173.0>--<60.0,548.0>>

	* uni1E25 (U+1E25): L<<410.0,27.0>--<409.0,404.0>>

	* uni1E25 (U+1E25): L<<466.0,404.0>--<467.0,27.0>>

	* uni1E2B (U+1E2B): L<<410.0,27.0>--<409.0,404.0>>

	* uni1E2B (U+1E2B): L<<466.0,404.0>--<467.0,27.0>>

	* uni1E43 (U+1E43): L<<396.0,28.0>--<395.0,327.0>>

	* uni1E43 (U+1E43): L<<787.0,404.0>--<788.0,28.0>>

	* uni1E4C (U+1E4C): L<<118.0,473.0>--<117.0,273.0>>

	* uni1E4E (U+1E4E): L<<118.0,473.0>--<117.0,273.0>>

	* uni1E50 (U+1E50): L<<118.0,473.0>--<117.0,273.0>>

	* uni1E52 (U+1E52): L<<118.0,473.0>--<117.0,273.0>>

	* uni1E6D (U+1E6D): L<<123.0,577.0>--<124.0,718.0>>

	* uni1E6D (U+1E6D): L<<181.0,380.0>--<180.0,141.0>>

	* uni1E8F (U+1E8F): L<<118.0,548.0>--<119.0,173.0>>

	* uni1E8F (U+1E8F): L<<61.0,173.0>--<60.0,548.0>>

	* uni1E97 (U+1E97): L<<123.0,577.0>--<124.0,718.0>>

	* uni1E97 (U+1E97): L<<181.0,380.0>--<180.0,141.0>>

	* uni1E9E (U+1E9E): L<<70.0,29.0>--<71.0,718.0>>

	* uni1ECC (U+1ECC): L<<118.0,473.0>--<117.0,273.0>>

	* uni1EF9 (U+1EF9): L<<118.0,548.0>--<119.0,173.0>>

	* uni1EF9 (U+1EF9): L<<61.0,173.0>--<60.0,548.0>>

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
</div></details><br></div></details><details><summary><b>[6] LibertineSup-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
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

	* AE (U+00C6): L<<418.0,299.0>--<227.0,299.0>> -> L<<227.0,299.0>--<223.0,299.0>>

	* AEacute (U+01FC): L<<418.0,299.0>--<227.0,299.0>> -> L<<227.0,299.0>--<223.0,299.0>>

	* ae (U+00E6): L<<590.0,534.0>--<586.0,534.0>> -> L<<586.0,534.0>--<576.0,534.0>>

	* aeacute (U+01FD): L<<590.0,534.0>--<586.0,534.0>> -> L<<586.0,534.0>--<576.0,534.0>>

	* e (U+0065): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* eacute (U+00E9): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* ebreve (U+0115): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* ecaron (U+011B): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* ecircumflex (U+00EA): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* edieresis (U+00EB): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* edotaccent (U+0117): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* egrave (U+00E8): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* emacron (U+0113): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* eogonek (U+0119): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* oe (U+0153): L<<652.0,534.0>--<648.0,534.0>> -> L<<648.0,534.0>--<638.0,534.0>>

	* s (U+0073): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* sacute (U+015B): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* scaron (U+0161): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* scedilla (U+015F): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* scircumflex (U+015D): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* uni0219 (U+0219): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* uni0259 (U+0259): L<<228.0,36.0>--<231.0,36.0>> -> L<<231.0,36.0>--<242.0,36.0>>

	* uni1E15 (U+1E15): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* uni1E17 (U+1E17): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* uni1E1D (U+1E1D): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* uni1E61 (U+1E61): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* uni1E63 (U+1E63): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* uni1E65 (U+1E65): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* uni1E67 (U+1E67): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* uni1E69 (U+1E69): L<<35.0,86.0>--<35.0,86.0>> -> L<<35.0,86.0>--<35.0,86.0>>

	* uni1EB9 (U+1EB9): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>>

	* uni1EBD (U+1EBD): L<<272.0,534.0>--<268.0,534.0>> -> L<<268.0,534.0>--<258.0,534.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* logo_full (U+F0001): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo_full (U+F0001): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* O (U+004F): L<<409.0,475.0>--<408.0,272.0>>

	* OE (U+0152): L<<409.0,475.0>--<408.0,272.0>>

	* Oacute (U+00D3): L<<409.0,475.0>--<408.0,272.0>>

	* Obreve (U+014E): L<<409.0,475.0>--<408.0,272.0>>

	* Ocircumflex (U+00D4): L<<409.0,475.0>--<408.0,272.0>>

	* Odieresis (U+00D6): L<<409.0,475.0>--<408.0,272.0>>

	* Ograve (U+00D2): L<<409.0,475.0>--<408.0,272.0>>

	* Ohungarumlaut (U+0150): L<<409.0,475.0>--<408.0,272.0>>

	* Omacron (U+014C): L<<409.0,475.0>--<408.0,272.0>>

	* Oslash (U+00D8): L<<475.0,272.0>--<474.0,475.0>>

	* Oslashacute (U+01FE): L<<475.0,272.0>--<474.0,475.0>>

	* Otilde (U+00D5): L<<409.0,475.0>--<408.0,272.0>>

	* h (U+0068): L<<408.0,21.0>--<407.0,405.0>>

	* h (U+0068): L<<451.0,405.0>--<452.0,21.0>>

	* hbar (U+0127): L<<420.0,21.0>--<419.0,405.0>>

	* hbar (U+0127): L<<463.0,405.0>--<464.0,21.0>>

	* hcircumflex (U+0125): L<<408.0,21.0>--<407.0,405.0>>

	* hcircumflex (U+0125): L<<451.0,405.0>--<452.0,21.0>>

	* m (U+006D): L<<393.0,22.0>--<392.0,339.0>>

	* m (U+006D): L<<726.0,22.0>--<725.0,339.0>>

	* m (U+006D): L<<770.0,405.0>--<771.0,22.0>>

	* t (U+0074): L<<122.0,574.0>--<123.0,725.0>>

	* t (U+0074): L<<168.0,725.0>--<167.0,574.0>>

	* tbar (U+0167): L<<122.0,574.0>--<123.0,725.0>>

	* tbar (U+0167): L<<168.0,725.0>--<167.0,574.0>>

	* tcaron (U+0165): L<<122.0,574.0>--<123.0,725.0>>

	* tcaron (U+0165): L<<168.0,725.0>--<167.0,574.0>>

	* tmacronbelow (U+1E6F): L<<122.0,574.0>--<123.0,725.0>>

	* tmacronbelow (U+1E6F): L<<168.0,725.0>--<167.0,574.0>>

	* uni0163 (U+0163): L<<122.0,574.0>--<123.0,725.0>>

	* uni0163 (U+0163): L<<168.0,725.0>--<167.0,574.0>>

	* uni01EA (U+01EA): L<<409.0,475.0>--<408.0,272.0>>

	* uni021B (U+021B): L<<122.0,574.0>--<123.0,725.0>>

	* uni021B (U+021B): L<<168.0,725.0>--<167.0,574.0>>

	* uni0233 (U+0233): L<<105.0,552.0>--<106.0,169.0>>

	* uni0233 (U+0233): L<<61.0,169.0>--<60.0,552.0>>

	* uni1E25 (U+1E25): L<<408.0,21.0>--<407.0,405.0>>

	* uni1E25 (U+1E25): L<<451.0,405.0>--<452.0,21.0>>

	* uni1E2B (U+1E2B): L<<408.0,21.0>--<407.0,405.0>>

	* uni1E2B (U+1E2B): L<<451.0,405.0>--<452.0,21.0>>

	* uni1E43 (U+1E43): L<<393.0,22.0>--<392.0,339.0>>

	* uni1E43 (U+1E43): L<<726.0,22.0>--<725.0,339.0>>

	* uni1E43 (U+1E43): L<<770.0,405.0>--<771.0,22.0>>

	* uni1E4C (U+1E4C): L<<409.0,475.0>--<408.0,272.0>>

	* uni1E4E (U+1E4E): L<<409.0,475.0>--<408.0,272.0>>

	* uni1E50 (U+1E50): L<<409.0,475.0>--<408.0,272.0>>

	* uni1E52 (U+1E52): L<<409.0,475.0>--<408.0,272.0>>

	* uni1E6D (U+1E6D): L<<122.0,574.0>--<123.0,725.0>>

	* uni1E6D (U+1E6D): L<<168.0,725.0>--<167.0,574.0>>

	* uni1E8F (U+1E8F): L<<105.0,552.0>--<106.0,169.0>>

	* uni1E8F (U+1E8F): L<<61.0,169.0>--<60.0,552.0>>

	* uni1E97 (U+1E97): L<<122.0,574.0>--<123.0,725.0>>

	* uni1E97 (U+1E97): L<<168.0,725.0>--<167.0,574.0>>

	* uni1E9E (U+1E9E): L<<116.0,702.0>--<115.0,23.0>>

	* uni1E9E (U+1E9E): L<<70.0,23.0>--<71.0,725.0>>

	* uni1ECC (U+1ECC): L<<409.0,475.0>--<408.0,272.0>>

	* uni1EF9 (U+1EF9): L<<105.0,552.0>--<106.0,169.0>>

	* uni1EF9 (U+1EF9): L<<61.0,169.0>--<60.0,552.0>>

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
</div></details><br></div></details><details><summary><b>[6] LibertineSup-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.0, while a newer 0.9.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
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

	* s (U+0073): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* sacute (U+015B): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* scaron (U+0161): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* scedilla (U+015F): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* scircumflex (U+015D): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* uni0219 (U+0219): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* uni1E61 (U+1E61): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* uni1E63 (U+1E63): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* uni1E65 (U+1E65): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* uni1E67 (U+1E67): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>>

	* uni1E69 (U+1E69): L<<35.0,76.0>--<35.0,76.0>> -> L<<35.0,76.0>--<35.0,76.0>> [code: found-colinear-vectors]
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

	* h (U+0068): L<<402.0,9.0>--<401.0,406.0>>

	* h (U+0068): L<<420.0,406.0>--<421.0,9.0>>

	* hbar (U+0127): L<<402.0,9.0>--<401.0,406.0>>

	* hbar (U+0127): L<<420.0,406.0>--<421.0,9.0>>

	* hcircumflex (U+0125): L<<402.0,9.0>--<401.0,406.0>>

	* hcircumflex (U+0125): L<<420.0,406.0>--<421.0,9.0>>

	* m (U+006D): L<<388.0,10.0>--<387.0,363.0>>

	* m (U+006D): L<<716.0,10.0>--<715.0,363.0>>

	* m (U+006D): L<<734.0,406.0>--<735.0,10.0>>

	* t (U+0074): L<<120.0,121.0>--<121.0,431.0>>

	* t (U+0074): L<<141.0,431.0>--<140.0,121.0>>

	* tbar (U+0167): L<<120.0,285.0>--<121.0,431.0>>

	* tbar (U+0167): L<<141.0,431.0>--<140.0,285.0>>

	* tcaron (U+0165): L<<120.0,121.0>--<121.0,431.0>>

	* tcaron (U+0165): L<<141.0,431.0>--<140.0,121.0>>

	* tmacronbelow (U+1E6F): L<<120.0,121.0>--<121.0,431.0>>

	* tmacronbelow (U+1E6F): L<<141.0,431.0>--<140.0,121.0>>

	* uni0163 (U+0163): L<<120.0,121.0>--<121.0,431.0>>

	* uni0163 (U+0163): L<<141.0,431.0>--<140.0,121.0>>

	* uni021B (U+021B): L<<120.0,121.0>--<121.0,431.0>>

	* uni021B (U+021B): L<<141.0,431.0>--<140.0,121.0>>

	* uni0233 (U+0233): L<<61.0,162.0>--<60.0,558.0>>

	* uni0233 (U+0233): L<<80.0,558.0>--<81.0,162.0>>

	* uni1E25 (U+1E25): L<<402.0,9.0>--<401.0,406.0>>

	* uni1E25 (U+1E25): L<<420.0,406.0>--<421.0,9.0>>

	* uni1E2B (U+1E2B): L<<402.0,9.0>--<401.0,406.0>>

	* uni1E2B (U+1E2B): L<<420.0,406.0>--<421.0,9.0>>

	* uni1E43 (U+1E43): L<<388.0,10.0>--<387.0,363.0>>

	* uni1E43 (U+1E43): L<<716.0,10.0>--<715.0,363.0>>

	* uni1E43 (U+1E43): L<<734.0,406.0>--<735.0,10.0>>

	* uni1E6D (U+1E6D): L<<120.0,121.0>--<121.0,431.0>>

	* uni1E6D (U+1E6D): L<<141.0,431.0>--<140.0,121.0>>

	* uni1E8F (U+1E8F): L<<61.0,162.0>--<60.0,558.0>>

	* uni1E8F (U+1E8F): L<<80.0,558.0>--<81.0,162.0>>

	* uni1E97 (U+1E97): L<<120.0,121.0>--<121.0,431.0>>

	* uni1E97 (U+1E97): L<<141.0,431.0>--<140.0,121.0>>

	* uni1E9E (U+1E9E): L<<70.0,10.0>--<71.0,737.0>>

	* uni1E9E (U+1E9E): L<<91.0,727.0>--<90.0,10.0>>

	* uni1EF9 (U+1EF9): L<<61.0,162.0>--<60.0,558.0>>

	* uni1EF9 (U+1EF9): L<<80.0,558.0>--<81.0,162.0>>

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
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 29 | 716 | 43 | 621 | 0 |
| 0% | 0% | 2% | 51% | 3% | 44% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
