## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[23] LibertineSuper-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Libertine Super Bold | Libertine Super |
| Subfamily Name | Regular | Bold |
| Full Name | Libertine Super Bold | Libertine Super Bold |
| Poscript Name | LibertineSuper-Bold | LibertineSuper-Bold |
| Typographic Family Name | Libertine Super | N/A |
| Typographic Subfamily Name | Bold | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1327, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 354, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoLineGap (200) and hhea lineGap (0) must be equal. [code: lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be unset. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection BOLD bit should be set. [code: bad-BOLD]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- logo_full

	- logo_ls

	- uni00690307
 [code: unreachable-glyphs]
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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 605 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 665:
less, greater

Width = 612:
plusminus, notequal

Width = 598:
multiply

Width = 611:
approxequal

Width = 652:
lessequal

Width = 645:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Aacute (U+00C1): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Abreve (U+0102): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Acircumflex (U+00C2): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Adieresis (U+00C4): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Agrave (U+00C0): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Amacron (U+0100): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Aogonek (U+0104): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Aring (U+00C5): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Aringacute (U+01FA): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Atilde (U+00C3): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* Eng (U+014A): L<<173.0,716.0>--<173.0,716.0>> -> L<<173.0,716.0>--<173.0,716.0>>

	* IJ (U+0132): L<<424.0,103.0>--<438.0,103.0>> -> L<<438.0,103.0>--<440.0,103.0>>

	* J (U+004A): L<<222.0,103.0>--<236.0,103.0>> -> L<<236.0,103.0>--<238.0,103.0>>

	* Jcircumflex (U+0134): L<<222.0,103.0>--<236.0,103.0>> -> L<<236.0,103.0>--<238.0,103.0>>

	* N (U+004E): L<<173.0,716.0>--<173.0,716.0>> -> L<<173.0,716.0>--<173.0,716.0>>

	* Nacute (U+0143): L<<173.0,716.0>--<173.0,716.0>> -> L<<173.0,716.0>--<173.0,716.0>>

	* Ncaron (U+0147): L<<173.0,716.0>--<173.0,716.0>> -> L<<173.0,716.0>--<173.0,716.0>>

	* Nmacronbelow (U+1E48): L<<173.0,716.0>--<173.0,716.0>> -> L<<173.0,716.0>--<173.0,716.0>>

	* Ntilde (U+00D1): L<<173.0,716.0>--<173.0,716.0>> -> L<<173.0,716.0>--<173.0,716.0>>

	* Y (U+0059): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<38.0,664.0>>

	* Y (U+0059): L<<527.0,664.0>--<347.0,374.0>> -> L<<347.0,374.0>--<335.0,355.0>>

	* Yacute (U+00DD): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<38.0,664.0>>

	* Yacute (U+00DD): L<<527.0,664.0>--<347.0,374.0>> -> L<<347.0,374.0>--<335.0,355.0>>

	* Ycircumflex (U+0176): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<38.0,664.0>>

	* Ycircumflex (U+0176): L<<527.0,664.0>--<347.0,374.0>> -> L<<347.0,374.0>--<335.0,355.0>>

	* Ydieresis (U+0178): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<38.0,664.0>>

	* Ydieresis (U+0178): L<<527.0,664.0>--<347.0,374.0>> -> L<<347.0,374.0>--<335.0,355.0>>

	* Ygrave (U+1EF2): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<38.0,664.0>>

	* Ygrave (U+1EF2): L<<527.0,664.0>--<347.0,374.0>> -> L<<347.0,374.0>--<335.0,355.0>>

	* comma (U+002C): L<<187.0,63.0>--<187.0,63.0>> -> L<<187.0,63.0>--<187.0,63.0>>

	* eng (U+014B): L<<421.0,-144.0>--<421.0,62.0>> -> L<<421.0,62.0>--<421.0,278.0>>

	* eng (U+014B): L<<528.0,401.0>--<529.0,70.0>> -> L<<529.0,70.0>--<529.0,69.0>>

	* eng (U+014B): L<<529.0,53.0>--<529.0,52.0>> -> L<<529.0,52.0>--<529.0,-144.0>>

	* eng (U+014B): L<<529.0,62.0>--<529.0,53.0>> -> L<<529.0,53.0>--<529.0,52.0>>

	* eng (U+014B): L<<529.0,69.0>--<529.0,62.0>> -> L<<529.0,62.0>--<529.0,53.0>>

	* eng (U+014B): L<<529.0,70.0>--<529.0,69.0>> -> L<<529.0,69.0>--<529.0,62.0>>

	* k (U+006B): L<<168.0,589.0>--<367.0,589.0>> -> L<<367.0,589.0>--<368.0,589.0>>

	* k (U+006B): L<<367.0,589.0>--<368.0,589.0>> -> L<<368.0,589.0>--<368.0,589.0>>

	* semicolon (U+003B): L<<187.0,63.0>--<187.0,63.0>> -> L<<187.0,63.0>--<187.0,63.0>>

	* trademark (U+2122): L<<678.0,759.0>--<678.0,759.0>> -> L<<678.0,759.0>--<678.0,759.0>>

	* uni00B5 (U+00B5): L<<60.0,-126.0>--<60.0,187.0>> -> L<<60.0,187.0>--<59.0,535.0>>

	* uni0137 (U+0137): L<<168.0,589.0>--<367.0,589.0>> -> L<<367.0,589.0>--<368.0,589.0>>

	* uni0137 (U+0137): L<<367.0,589.0>--<368.0,589.0>> -> L<<368.0,589.0>--<368.0,589.0>>

	* uni0145 (U+0145): L<<173.0,716.0>--<173.0,716.0>> -> L<<173.0,716.0>--<173.0,716.0>>

	* uni019D (U+019D): L<<212.0,716.0>--<212.0,716.0>> -> L<<212.0,716.0>--<212.0,716.0>>

	* uni0232 (U+0232): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<38.0,664.0>>

	* uni0232 (U+0232): L<<527.0,664.0>--<347.0,374.0>> -> L<<347.0,374.0>--<335.0,355.0>>

	* uni0272 (U+0272): L<<168.0,278.0>--<168.0,53.0>> -> L<<168.0,53.0>--<168.0,51.0>>

	* uni0272 (U+0272): L<<168.0,53.0>--<168.0,51.0>> -> L<<168.0,51.0>--<168.0,-144.0>>

	* uni0272 (U+0272): L<<60.0,-144.0>--<60.0,56.0>> -> L<<60.0,56.0>--<60.0,58.0>>

	* uni0272 (U+0272): L<<60.0,56.0>--<60.0,58.0>> -> L<<60.0,58.0>--<60.0,535.0>>

	* uni03BC (U+03BC): L<<100.0,-126.0>--<100.0,187.0>> -> L<<100.0,187.0>--<99.0,535.0>>

	* uni1E44 (U+1E44): L<<173.0,716.0>--<173.0,716.0>> -> L<<173.0,716.0>--<173.0,716.0>>

	* uni1E46 (U+1E46): L<<173.0,716.0>--<173.0,716.0>> -> L<<173.0,716.0>--<173.0,716.0>>

	* uni1E8E (U+1E8E): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<38.0,664.0>>

	* uni1E8E (U+1E8E): L<<527.0,664.0>--<347.0,374.0>> -> L<<347.0,374.0>--<335.0,355.0>>

	* uni1EA0 (U+1EA0): L<<281.0,751.0>--<281.0,751.0>> -> L<<281.0,751.0>--<281.0,751.0>>

	* uni1EF8 (U+1EF8): L<<227.0,359.0>--<218.0,374.0>> -> L<<218.0,374.0>--<38.0,664.0>>

	* uni1EF8 (U+1EF8): L<<527.0,664.0>--<347.0,374.0>> -> L<<347.0,374.0>--<335.0,355.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<528.0,401.0>--<529.0,70.0>>

	* h (U+0068): L<<421.0,52.0>--<420.0,401.0>>

	* h (U+0068): L<<528.0,401.0>--<529.0,52.0>>

	* hbar (U+0127): L<<465.0,52.0>--<464.0,401.0>>

	* hbar (U+0127): L<<572.0,401.0>--<573.0,52.0>>

	* hcircumflex (U+0125): L<<421.0,52.0>--<420.0,401.0>>

	* hcircumflex (U+0125): L<<528.0,401.0>--<529.0,52.0>>

	* m (U+006D): L<<406.0,53.0>--<405.0,278.0>>

	* m (U+006D): L<<752.0,53.0>--<751.0,278.0>>

	* m (U+006D): L<<859.0,401.0>--<860.0,53.0>>

	* n (U+006E): L<<422.0,53.0>--<421.0,278.0>>

	* n (U+006E): L<<528.0,401.0>--<529.0,53.0>>

	* nacute (U+0144): L<<422.0,53.0>--<421.0,278.0>>

	* nacute (U+0144): L<<528.0,401.0>--<529.0,53.0>>

	* napostrophe (U+0149): L<<642.0,53.0>--<641.0,278.0>>

	* napostrophe (U+0149): L<<748.0,401.0>--<749.0,53.0>>

	* ncaron (U+0148): L<<422.0,53.0>--<421.0,278.0>>

	* ncaron (U+0148): L<<528.0,401.0>--<529.0,53.0>>

	* nmacronbelow (U+1E49): L<<422.0,53.0>--<421.0,278.0>>

	* nmacronbelow (U+1E49): L<<528.0,401.0>--<529.0,53.0>>

	* ntilde (U+00F1): L<<422.0,53.0>--<421.0,278.0>>

	* ntilde (U+00F1): L<<528.0,401.0>--<529.0,53.0>>

	* t (U+0074): L<<235.0,312.0>--<234.0,167.0>>

	* tcaron (U+0165): L<<235.0,312.0>--<234.0,167.0>>

	* tmacronbelow (U+1E6F): L<<235.0,312.0>--<234.0,167.0>>

	* u (U+0075): L<<168.0,535.0>--<169.0,269.0>>

	* u (U+0075): L<<61.0,187.0>--<60.0,535.0>>

	* uacute (U+00FA): L<<168.0,535.0>--<169.0,269.0>>

	* uacute (U+00FA): L<<61.0,187.0>--<60.0,535.0>>

	* ubreve (U+016D): L<<168.0,535.0>--<169.0,269.0>>

	* ubreve (U+016D): L<<61.0,187.0>--<60.0,535.0>>

	* ucircumflex (U+00FB): L<<168.0,535.0>--<169.0,269.0>>

	* ucircumflex (U+00FB): L<<61.0,187.0>--<60.0,535.0>>

	* udieresis (U+00FC): L<<168.0,535.0>--<169.0,269.0>>

	* udieresis (U+00FC): L<<61.0,187.0>--<60.0,535.0>>

	* ugrave (U+00F9): L<<168.0,535.0>--<169.0,269.0>>

	* ugrave (U+00F9): L<<61.0,187.0>--<60.0,535.0>>

	* uhungarumlaut (U+0171): L<<168.0,535.0>--<169.0,269.0>>

	* uhungarumlaut (U+0171): L<<61.0,187.0>--<60.0,535.0>>

	* umacron (U+016B): L<<168.0,535.0>--<169.0,269.0>>

	* umacron (U+016B): L<<61.0,187.0>--<60.0,535.0>>

	* uni00B5 (U+00B5): L<<167.0,535.0>--<168.0,187.0>>

	* uni00B5 (U+00B5): L<<60.0,187.0>--<59.0,535.0>>

	* uni0146 (U+0146): L<<422.0,53.0>--<421.0,278.0>>

	* uni0146 (U+0146): L<<528.0,401.0>--<529.0,53.0>>

	* uni0163 (U+0163): L<<235.0,312.0>--<234.0,167.0>>

	* uni021B (U+021B): L<<235.0,312.0>--<234.0,167.0>>

	* uni0233 (U+0233): L<<168.0,535.0>--<169.0,187.0>>

	* uni0233 (U+0233): L<<61.0,187.0>--<60.0,535.0>>

	* uni0272 (U+0272): L<<422.0,53.0>--<421.0,278.0>>

	* uni0272 (U+0272): L<<528.0,401.0>--<529.0,53.0>>

	* uni03BC (U+03BC): L<<100.0,187.0>--<99.0,535.0>>

	* uni03BC (U+03BC): L<<207.0,535.0>--<208.0,187.0>>

	* uni1E25 (U+1E25): L<<421.0,52.0>--<420.0,401.0>>

	* uni1E25 (U+1E25): L<<528.0,401.0>--<529.0,52.0>>

	* uni1E2B (U+1E2B): L<<421.0,52.0>--<420.0,401.0>>

	* uni1E2B (U+1E2B): L<<528.0,401.0>--<529.0,52.0>>

	* uni1E43 (U+1E43): L<<406.0,53.0>--<405.0,278.0>>

	* uni1E43 (U+1E43): L<<752.0,53.0>--<751.0,278.0>>

	* uni1E43 (U+1E43): L<<859.0,401.0>--<860.0,53.0>>

	* uni1E45 (U+1E45): L<<422.0,53.0>--<421.0,278.0>>

	* uni1E45 (U+1E45): L<<528.0,401.0>--<529.0,53.0>>

	* uni1E47 (U+1E47): L<<422.0,53.0>--<421.0,278.0>>

	* uni1E47 (U+1E47): L<<528.0,401.0>--<529.0,53.0>>

	* uni1E6D (U+1E6D): L<<235.0,312.0>--<234.0,167.0>>

	* uni1E79 (U+1E79): L<<168.0,535.0>--<169.0,269.0>>

	* uni1E79 (U+1E79): L<<61.0,187.0>--<60.0,535.0>>

	* uni1E7B (U+1E7B): L<<168.0,535.0>--<169.0,269.0>>

	* uni1E7B (U+1E7B): L<<61.0,187.0>--<60.0,535.0>>

	* uni1E8F (U+1E8F): L<<168.0,535.0>--<169.0,187.0>>

	* uni1E8F (U+1E8F): L<<61.0,187.0>--<60.0,535.0>>

	* uni1E97 (U+1E97): L<<235.0,312.0>--<234.0,167.0>>

	* uni1E9E (U+1E9E): L<<179.0,639.0>--<178.0,54.0>>

	* uni1E9E (U+1E9E): L<<70.0,54.0>--<71.0,693.0>>

	* uni1EE5 (U+1EE5): L<<168.0,535.0>--<169.0,269.0>>

	* uni1EE5 (U+1EE5): L<<61.0,187.0>--<60.0,535.0>>

	* uni1EF9 (U+1EF9): L<<168.0,535.0>--<169.0,187.0>>

	* uni1EF9 (U+1EF9): L<<61.0,187.0>--<60.0,535.0>>

	* uogonek (U+0173): L<<168.0,535.0>--<169.0,269.0>>

	* uogonek (U+0173): L<<61.0,187.0>--<60.0,535.0>>

	* uring (U+016F): L<<168.0,535.0>--<169.0,269.0>>

	* uring (U+016F): L<<61.0,187.0>--<60.0,535.0>>

	* utilde (U+0169): L<<168.0,535.0>--<169.0,269.0>>

	* utilde (U+0169): L<<61.0,187.0>--<60.0,535.0>>

	* y (U+0079): L<<168.0,535.0>--<169.0,187.0>>

	* y (U+0079): L<<61.0,187.0>--<60.0,535.0>>

	* yacute (U+00FD): L<<168.0,535.0>--<169.0,187.0>>

	* yacute (U+00FD): L<<61.0,187.0>--<60.0,535.0>>

	* ycircumflex (U+0177): L<<168.0,535.0>--<169.0,187.0>>

	* ycircumflex (U+0177): L<<61.0,187.0>--<60.0,535.0>>

	* ydieresis (U+00FF): L<<168.0,535.0>--<169.0,187.0>>

	* ydieresis (U+00FF): L<<61.0,187.0>--<60.0,535.0>>

	* ygrave (U+1EF3): L<<168.0,535.0>--<169.0,187.0>>

	* ygrave (U+1EF3): L<<61.0,187.0>--<60.0,535.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[21] LibertineSuper-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1327, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 354, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoLineGap (200) and hhea lineGap (0) must be equal. [code: lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libertine Super Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- logo_full

	- logo_ls

	- uni00690307
 [code: unreachable-glyphs]
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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 620 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 688:
less, greater

Width = 627:
plusminus, notequal

Width = 612:
multiply

Width = 626:
approxequal

Width = 673:
lessequal

Width = 666:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Y (U+0059): L<<229.0,358.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Y (U+0059): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<349.0,353.0>>

	* Yacute (U+00DD): L<<229.0,358.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Yacute (U+00DD): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<349.0,353.0>>

	* Ycircumflex (U+0176): L<<229.0,358.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Ycircumflex (U+0176): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<349.0,353.0>>

	* Ydieresis (U+0178): L<<229.0,358.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Ydieresis (U+0178): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<349.0,353.0>>

	* Ygrave (U+1EF2): L<<229.0,358.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* Ygrave (U+1EF2): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<349.0,353.0>>

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

	* uni00B5 (U+00B5): L<<60.0,-117.0>--<60.0,190.0>> -> L<<60.0,190.0>--<59.0,532.0>>

	* uni0137 (U+0137): L<<180.0,592.0>--<375.0,592.0>> -> L<<375.0,592.0>--<376.0,592.0>>

	* uni0137 (U+0137): L<<375.0,592.0>--<376.0,592.0>> -> L<<376.0,592.0>--<376.0,592.0>>

	* uni0232 (U+0232): L<<229.0,358.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* uni0232 (U+0232): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<349.0,353.0>>

	* uni0272 (U+0272): L<<180.0,267.0>--<180.0,59.0>> -> L<<180.0,59.0>--<180.0,56.0>>

	* uni0272 (U+0272): L<<180.0,59.0>--<180.0,56.0>> -> L<<180.0,56.0>--<180.0,-144.0>>

	* uni0272 (U+0272): L<<60.0,-144.0>--<60.0,61.0>> -> L<<60.0,61.0>--<60.0,64.0>>

	* uni0272 (U+0272): L<<60.0,61.0>--<60.0,64.0>> -> L<<60.0,64.0>--<60.0,532.0>>

	* uni03BC (U+03BC): L<<105.0,-117.0>--<105.0,190.0>> -> L<<105.0,190.0>--<104.0,532.0>>

	* uni1E8E (U+1E8E): L<<229.0,358.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* uni1E8E (U+1E8E): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<349.0,353.0>>

	* uni1EF8 (U+1EF8): L<<229.0,358.0>--<219.0,374.0>> -> L<<219.0,374.0>--<39.0,655.0>>

	* uni1EF8 (U+1EF8): L<<541.0,655.0>--<361.0,374.0>> -> L<<361.0,374.0>--<349.0,353.0>>

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

	* uni00B5 (U+00B5): L<<179.0,532.0>--<180.0,190.0>>

	* uni00B5 (U+00B5): L<<60.0,190.0>--<59.0,532.0>>

	* uni0146 (U+0146): L<<424.0,59.0>--<423.0,267.0>>

	* uni0146 (U+0146): L<<543.0,400.0>--<544.0,59.0>>

	* uni0233 (U+0233): L<<180.0,532.0>--<181.0,190.0>>

	* uni0233 (U+0233): L<<61.0,190.0>--<60.0,532.0>>

	* uni0272 (U+0272): L<<424.0,59.0>--<423.0,267.0>>

	* uni0272 (U+0272): L<<543.0,400.0>--<544.0,59.0>>

	* uni03BC (U+03BC): L<<105.0,190.0>--<104.0,532.0>>

	* uni03BC (U+03BC): L<<224.0,532.0>--<225.0,190.0>>

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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[21] LibertineSuper-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1327, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 354, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoLineGap (200) and hhea lineGap (0) must be equal. [code: lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libertine Super Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- logo_full

	- logo_ls

	- uni00690307
 [code: unreachable-glyphs]
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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 584 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 632:
less, greater

Width = 591:
plusminus, notequal

Width = 578:
multiply

Width = 590:
approxequal

Width = 624:
lessequal

Width = 617:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* A (U+0041): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Aacute (U+00C1): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Aacute (U+00C1): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Abreve (U+0102): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Abreve (U+0102): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Acircumflex (U+00C2): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Acircumflex (U+00C2): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Adieresis (U+00C4): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Adieresis (U+00C4): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Agrave (U+00C0): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Agrave (U+00C0): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Amacron (U+0100): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Amacron (U+0100): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Aogonek (U+0104): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Aogonek (U+0104): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Aring (U+00C5): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Aring (U+00C5): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Aringacute (U+01FA): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Aringacute (U+01FA): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* Atilde (U+00C3): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* Atilde (U+00C3): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* R (U+0052): L<<324.0,192.0>--<320.0,192.0>> -> L<<320.0,192.0>--<161.0,192.0>>

	* Racute (U+0154): L<<324.0,192.0>--<320.0,192.0>> -> L<<320.0,192.0>--<161.0,192.0>>

	* Rcaron (U+0158): L<<324.0,192.0>--<320.0,192.0>> -> L<<320.0,192.0>--<161.0,192.0>>

	* Rmacronbelow (U+1E5E): L<<324.0,192.0>--<320.0,192.0>> -> L<<320.0,192.0>--<161.0,192.0>>

	* Y (U+0059): L<<226.0,362.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,677.0>>

	* Y (U+0059): L<<508.0,677.0>--<327.0,374.0>> -> L<<327.0,374.0>--<317.0,358.0>>

	* Yacute (U+00DD): L<<226.0,362.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,677.0>>

	* Yacute (U+00DD): L<<508.0,677.0>--<327.0,374.0>> -> L<<327.0,374.0>--<317.0,358.0>>

	* Ycircumflex (U+0176): L<<226.0,362.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,677.0>>

	* Ycircumflex (U+0176): L<<508.0,677.0>--<327.0,374.0>> -> L<<327.0,374.0>--<317.0,358.0>>

	* Ydieresis (U+0178): L<<226.0,362.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,677.0>>

	* Ydieresis (U+0178): L<<508.0,677.0>--<327.0,374.0>> -> L<<327.0,374.0>--<317.0,358.0>>

	* Ygrave (U+1EF2): L<<226.0,362.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,677.0>>

	* Ygrave (U+1EF2): L<<508.0,677.0>--<327.0,374.0>> -> L<<327.0,374.0>--<317.0,358.0>>

	* comma (U+002C): L<<171.0,55.0>--<171.0,55.0>> -> L<<171.0,55.0>--<171.0,55.0>>

	* eng (U+014B): L<<417.0,-144.0>--<418.0,53.0>> -> L<<418.0,53.0>--<417.0,294.0>>

	* eng (U+014B): L<<508.0,402.0>--<509.0,60.0>> -> L<<509.0,60.0>--<509.0,59.0>>

	* eng (U+014B): L<<509.0,45.0>--<509.0,43.0>> -> L<<509.0,43.0>--<508.0,-144.0>>

	* eng (U+014B): L<<509.0,53.0>--<509.0,45.0>> -> L<<509.0,45.0>--<509.0,43.0>>

	* eng (U+014B): L<<509.0,59.0>--<509.0,53.0>> -> L<<509.0,53.0>--<509.0,45.0>>

	* eng (U+014B): L<<509.0,60.0>--<509.0,59.0>> -> L<<509.0,59.0>--<509.0,53.0>>

	* k (U+006B): L<<151.0,585.0>--<356.0,585.0>> -> L<<356.0,585.0>--<357.0,585.0>>

	* k (U+006B): L<<356.0,585.0>--<357.0,585.0>> -> L<<357.0,585.0>--<357.0,585.0>>

	* semicolon (U+003B): L<<171.0,55.0>--<171.0,55.0>> -> L<<171.0,55.0>--<171.0,55.0>>

	* trademark (U+2122): L<<647.0,760.0>--<647.0,760.0>> -> L<<647.0,760.0>--<647.0,760.0>>

	* uni00B5 (U+00B5): L<<60.0,-138.0>--<60.0,182.0>> -> L<<60.0,182.0>--<59.0,539.0>>

	* uni0137 (U+0137): L<<151.0,585.0>--<356.0,585.0>> -> L<<356.0,585.0>--<357.0,585.0>>

	* uni0137 (U+0137): L<<356.0,585.0>--<357.0,585.0>> -> L<<357.0,585.0>--<357.0,585.0>>

	* uni0156 (U+0156): L<<324.0,192.0>--<320.0,192.0>> -> L<<320.0,192.0>--<161.0,192.0>>

	* uni0232 (U+0232): L<<226.0,362.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,677.0>>

	* uni0232 (U+0232): L<<508.0,677.0>--<327.0,374.0>> -> L<<327.0,374.0>--<317.0,358.0>>

	* uni0272 (U+0272): L<<151.0,294.0>--<151.0,45.0>> -> L<<151.0,45.0>--<151.0,42.0>>

	* uni0272 (U+0272): L<<151.0,45.0>--<151.0,42.0>> -> L<<151.0,42.0>--<151.0,-144.0>>

	* uni0272 (U+0272): L<<60.0,-144.0>--<60.0,48.0>> -> L<<60.0,48.0>--<60.0,51.0>>

	* uni0272 (U+0272): L<<60.0,48.0>--<60.0,51.0>> -> L<<60.0,51.0>--<60.0,539.0>>

	* uni03BC (U+03BC): L<<92.0,-138.0>--<92.0,182.0>> -> L<<92.0,182.0>--<91.0,539.0>>

	* uni1E5A (U+1E5A): L<<324.0,192.0>--<320.0,192.0>> -> L<<320.0,192.0>--<161.0,192.0>>

	* uni1E8E (U+1E8E): L<<226.0,362.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,677.0>>

	* uni1E8E (U+1E8E): L<<508.0,677.0>--<327.0,374.0>> -> L<<327.0,374.0>--<317.0,358.0>>

	* uni1EA0 (U+1EA0): L<<270.0,751.0>--<270.0,751.0>> -> L<<270.0,751.0>--<271.0,751.0>>

	* uni1EA0 (U+1EA0): L<<270.0,751.0>--<271.0,751.0>> -> L<<271.0,751.0>--<271.0,751.0>>

	* uni1EF8 (U+1EF8): L<<226.0,362.0>--<218.0,374.0>> -> L<<218.0,374.0>--<37.0,677.0>>

	* uni1EF8 (U+1EF8): L<<508.0,677.0>--<327.0,374.0>> -> L<<327.0,374.0>--<317.0,358.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<417.0,-144.0>--<418.0,53.0>>

	* eng (U+014B): L<<418.0,53.0>--<417.0,294.0>>

	* eng (U+014B): L<<508.0,402.0>--<509.0,60.0>>

	* eng (U+014B): L<<509.0,43.0>--<508.0,-144.0>>

	* h (U+0068): L<<418.0,44.0>--<417.0,402.0>>

	* h (U+0068): L<<508.0,402.0>--<509.0,44.0>>

	* hbar (U+0127): L<<453.0,44.0>--<452.0,402.0>>

	* hbar (U+0127): L<<544.0,402.0>--<545.0,44.0>>

	* hcircumflex (U+0125): L<<418.0,44.0>--<417.0,402.0>>

	* hcircumflex (U+0125): L<<508.0,402.0>--<509.0,44.0>>

	* m (U+006D): L<<835.0,402.0>--<836.0,45.0>>

	* n (U+006E): L<<418.0,45.0>--<417.0,294.0>>

	* n (U+006E): L<<508.0,402.0>--<509.0,45.0>>

	* nacute (U+0144): L<<418.0,45.0>--<417.0,294.0>>

	* nacute (U+0144): L<<508.0,402.0>--<509.0,45.0>>

	* napostrophe (U+0149): L<<621.0,45.0>--<620.0,294.0>>

	* napostrophe (U+0149): L<<711.0,402.0>--<712.0,45.0>>

	* ncaron (U+0148): L<<418.0,45.0>--<417.0,294.0>>

	* ncaron (U+0148): L<<508.0,402.0>--<509.0,45.0>>

	* nmacronbelow (U+1E49): L<<418.0,45.0>--<417.0,294.0>>

	* nmacronbelow (U+1E49): L<<508.0,402.0>--<509.0,45.0>>

	* ntilde (U+00F1): L<<418.0,45.0>--<417.0,294.0>>

	* ntilde (U+00F1): L<<508.0,402.0>--<509.0,45.0>>

	* t (U+0074): L<<217.0,335.0>--<216.0,159.0>>

	* tcaron (U+0165): L<<217.0,335.0>--<216.0,159.0>>

	* tmacronbelow (U+1E6F): L<<217.0,335.0>--<216.0,159.0>>

	* u (U+0075): L<<151.0,539.0>--<152.0,257.0>>

	* u (U+0075): L<<61.0,182.0>--<60.0,539.0>>

	* uacute (U+00FA): L<<151.0,539.0>--<152.0,257.0>>

	* uacute (U+00FA): L<<61.0,182.0>--<60.0,539.0>>

	* ubreve (U+016D): L<<151.0,539.0>--<152.0,257.0>>

	* ubreve (U+016D): L<<61.0,182.0>--<60.0,539.0>>

	* ucircumflex (U+00FB): L<<151.0,539.0>--<152.0,257.0>>

	* ucircumflex (U+00FB): L<<61.0,182.0>--<60.0,539.0>>

	* udieresis (U+00FC): L<<151.0,539.0>--<152.0,257.0>>

	* udieresis (U+00FC): L<<61.0,182.0>--<60.0,539.0>>

	* ugrave (U+00F9): L<<151.0,539.0>--<152.0,257.0>>

	* ugrave (U+00F9): L<<61.0,182.0>--<60.0,539.0>>

	* uhungarumlaut (U+0171): L<<151.0,539.0>--<152.0,257.0>>

	* uhungarumlaut (U+0171): L<<61.0,182.0>--<60.0,539.0>>

	* umacron (U+016B): L<<151.0,539.0>--<152.0,257.0>>

	* umacron (U+016B): L<<61.0,182.0>--<60.0,539.0>>

	* uni00B5 (U+00B5): L<<150.0,539.0>--<151.0,182.0>>

	* uni00B5 (U+00B5): L<<60.0,182.0>--<59.0,539.0>>

	* uni0146 (U+0146): L<<418.0,45.0>--<417.0,294.0>>

	* uni0146 (U+0146): L<<508.0,402.0>--<509.0,45.0>>

	* uni0163 (U+0163): L<<217.0,335.0>--<216.0,159.0>>

	* uni021B (U+021B): L<<217.0,335.0>--<216.0,159.0>>

	* uni0233 (U+0233): L<<151.0,539.0>--<152.0,182.0>>

	* uni0233 (U+0233): L<<61.0,182.0>--<60.0,539.0>>

	* uni0272 (U+0272): L<<418.0,45.0>--<417.0,294.0>>

	* uni0272 (U+0272): L<<508.0,402.0>--<509.0,45.0>>

	* uni03BC (U+03BC): L<<182.0,539.0>--<183.0,182.0>>

	* uni03BC (U+03BC): L<<92.0,182.0>--<91.0,539.0>>

	* uni1E25 (U+1E25): L<<418.0,44.0>--<417.0,402.0>>

	* uni1E25 (U+1E25): L<<508.0,402.0>--<509.0,44.0>>

	* uni1E2B (U+1E2B): L<<418.0,44.0>--<417.0,402.0>>

	* uni1E2B (U+1E2B): L<<508.0,402.0>--<509.0,44.0>>

	* uni1E43 (U+1E43): L<<835.0,402.0>--<836.0,45.0>>

	* uni1E45 (U+1E45): L<<418.0,45.0>--<417.0,294.0>>

	* uni1E45 (U+1E45): L<<508.0,402.0>--<509.0,45.0>>

	* uni1E47 (U+1E47): L<<418.0,45.0>--<417.0,294.0>>

	* uni1E47 (U+1E47): L<<508.0,402.0>--<509.0,45.0>>

	* uni1E6D (U+1E6D): L<<217.0,335.0>--<216.0,159.0>>

	* uni1E79 (U+1E79): L<<151.0,539.0>--<152.0,257.0>>

	* uni1E79 (U+1E79): L<<61.0,182.0>--<60.0,539.0>>

	* uni1E7B (U+1E7B): L<<151.0,539.0>--<152.0,257.0>>

	* uni1E7B (U+1E7B): L<<61.0,182.0>--<60.0,539.0>>

	* uni1E8F (U+1E8F): L<<151.0,539.0>--<152.0,182.0>>

	* uni1E8F (U+1E8F): L<<61.0,182.0>--<60.0,539.0>>

	* uni1E97 (U+1E97): L<<217.0,335.0>--<216.0,159.0>>

	* uni1E9E (U+1E9E): L<<162.0,656.0>--<161.0,46.0>>

	* uni1E9E (U+1E9E): L<<70.0,46.0>--<71.0,701.0>>

	* uni1EE5 (U+1EE5): L<<151.0,539.0>--<152.0,257.0>>

	* uni1EE5 (U+1EE5): L<<61.0,182.0>--<60.0,539.0>>

	* uni1EF9 (U+1EF9): L<<151.0,539.0>--<152.0,182.0>>

	* uni1EF9 (U+1EF9): L<<61.0,182.0>--<60.0,539.0>>

	* uogonek (U+0173): L<<151.0,539.0>--<152.0,257.0>>

	* uogonek (U+0173): L<<61.0,182.0>--<60.0,539.0>>

	* uring (U+016F): L<<151.0,539.0>--<152.0,257.0>>

	* uring (U+016F): L<<61.0,182.0>--<60.0,539.0>>

	* utilde (U+0169): L<<151.0,539.0>--<152.0,257.0>>

	* utilde (U+0169): L<<61.0,182.0>--<60.0,539.0>>

	* y (U+0079): L<<151.0,539.0>--<152.0,182.0>>

	* y (U+0079): L<<61.0,182.0>--<60.0,539.0>>

	* yacute (U+00FD): L<<151.0,539.0>--<152.0,182.0>>

	* yacute (U+00FD): L<<61.0,182.0>--<60.0,539.0>>

	* ycircumflex (U+0177): L<<151.0,539.0>--<152.0,182.0>>

	* ycircumflex (U+0177): L<<61.0,182.0>--<60.0,539.0>>

	* ydieresis (U+00FF): L<<151.0,539.0>--<152.0,182.0>>

	* ydieresis (U+00FF): L<<61.0,182.0>--<60.0,539.0>>

	* ygrave (U+1EF3): L<<151.0,539.0>--<152.0,182.0>>

	* ygrave (U+1EF3): L<<61.0,182.0>--<60.0,539.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[21] LibertineSuper-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1327, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 354, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoLineGap (200) and hhea lineGap (0) must be equal. [code: lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libertine Super ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- logo_full

	- logo_ls

	- uni00690307
 [code: unreachable-glyphs]
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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 520 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 535:
less, greater

Width = 527:
plusminus, approxequal, notequal

Width = 519:
multiply

Width = 537:
lessequal

Width = 530:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* AE (U+00C6): L<<415.0,300.0>--<222.0,300.0>> -> L<<222.0,300.0>--<221.0,300.0>>

	* AE (U+00C6): L<<422.0,747.0>--<442.0,747.0>> -> L<<442.0,747.0>--<442.0,747.0>>

	* AE (U+00C6): L<<442.0,747.0>--<442.0,747.0>> -> L<<442.0,747.0>--<443.0,747.0>>

	* AE (U+00C6): L<<442.0,747.0>--<443.0,747.0>> -> L<<443.0,747.0>--<728.0,747.0>>

	* AEacute (U+01FC): L<<415.0,300.0>--<222.0,300.0>> -> L<<222.0,300.0>--<221.0,300.0>>

	* AEacute (U+01FC): L<<422.0,747.0>--<442.0,747.0>> -> L<<442.0,747.0>--<442.0,747.0>>

	* AEacute (U+01FC): L<<442.0,747.0>--<442.0,747.0>> -> L<<442.0,747.0>--<443.0,747.0>>

	* AEacute (U+01FC): L<<442.0,747.0>--<443.0,747.0>> -> L<<443.0,747.0>--<728.0,747.0>>

	* Aacute (U+00C1): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Abreve (U+0102): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Acircumflex (U+00C2): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Adieresis (U+00C4): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Agrave (U+00C0): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Amacron (U+0100): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Aogonek (U+0104): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Aring (U+00C5): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Aringacute (U+01FA): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Atilde (U+00C3): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* Y (U+0059): L<<220.0,369.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,716.0>>

	* Y (U+0059): L<<450.0,716.0>--<266.0,374.0>> -> L<<266.0,374.0>--<262.0,367.0>>

	* Yacute (U+00DD): L<<220.0,369.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,716.0>>

	* Yacute (U+00DD): L<<450.0,716.0>--<266.0,374.0>> -> L<<266.0,374.0>--<262.0,367.0>>

	* Ycircumflex (U+0176): L<<220.0,369.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,716.0>>

	* Ycircumflex (U+0176): L<<450.0,716.0>--<266.0,374.0>> -> L<<266.0,374.0>--<262.0,367.0>>

	* Ydieresis (U+0178): L<<220.0,369.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,716.0>>

	* Ydieresis (U+0178): L<<450.0,716.0>--<266.0,374.0>> -> L<<266.0,374.0>--<262.0,367.0>>

	* Ygrave (U+1EF2): L<<220.0,369.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,716.0>>

	* Ygrave (U+1EF2): L<<450.0,716.0>--<266.0,374.0>> -> L<<266.0,374.0>--<262.0,367.0>>

	* comma (U+002C): L<<120.0,30.0>--<120.0,30.0>> -> L<<120.0,30.0>--<120.0,30.0>>

	* eng (U+014B): L<<407.0,-144.0>--<407.0,23.0>> -> L<<407.0,23.0>--<407.0,342.0>>

	* eng (U+014B): L<<448.0,29.0>--<448.0,23.0>> -> L<<448.0,23.0>--<448.0,21.0>>

	* k (U+006B): L<<101.0,573.0>--<324.0,573.0>> -> L<<324.0,573.0>--<325.0,573.0>>

	* k (U+006B): L<<324.0,573.0>--<325.0,573.0>> -> L<<325.0,573.0>--<325.0,573.0>>

	* semicolon (U+003B): L<<120.0,30.0>--<120.0,30.0>> -> L<<120.0,30.0>--<120.0,30.0>>

	* trademark (U+2122): L<<555.0,761.0>--<555.0,761.0>> -> L<<555.0,761.0>--<555.0,761.0>>

	* uni00B5 (U+00B5): L<<60.0,-176.0>--<60.0,168.0>> -> L<<60.0,168.0>--<59.0,552.0>>

	* uni0137 (U+0137): L<<101.0,573.0>--<324.0,573.0>> -> L<<324.0,573.0>--<325.0,573.0>>

	* uni0137 (U+0137): L<<324.0,573.0>--<325.0,573.0>> -> L<<325.0,573.0>--<325.0,573.0>>

	* uni0232 (U+0232): L<<220.0,369.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,716.0>>

	* uni0232 (U+0232): L<<450.0,716.0>--<266.0,374.0>> -> L<<266.0,374.0>--<262.0,367.0>>

	* uni03BC (U+03BC): L<<70.0,-176.0>--<70.0,168.0>> -> L<<70.0,168.0>--<69.0,552.0>>

	* uni1E8E (U+1E8E): L<<220.0,369.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,716.0>>

	* uni1E8E (U+1E8E): L<<450.0,716.0>--<266.0,374.0>> -> L<<266.0,374.0>--<262.0,367.0>>

	* uni1EA0 (U+1EA0): L<<239.0,752.0>--<240.0,752.0>> -> L<<240.0,752.0>--<240.0,752.0>>

	* uni1EF8 (U+1EF8): L<<220.0,369.0>--<217.0,374.0>> -> L<<217.0,374.0>--<33.0,716.0>>

	* uni1EF8 (U+1EF8): L<<450.0,716.0>--<266.0,374.0>> -> L<<266.0,374.0>--<262.0,367.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<447.0,405.0>--<448.0,29.0>>

	* h (U+0068): L<<407.0,20.0>--<406.0,405.0>>

	* h (U+0068): L<<446.0,405.0>--<447.0,20.0>>

	* hbar (U+0127): L<<417.0,20.0>--<416.0,405.0>>

	* hbar (U+0127): L<<457.0,405.0>--<458.0,20.0>>

	* hcircumflex (U+0125): L<<407.0,20.0>--<406.0,405.0>>

	* hcircumflex (U+0125): L<<446.0,405.0>--<447.0,20.0>>

	* m (U+006D): L<<392.0,21.0>--<391.0,342.0>>

	* m (U+006D): L<<725.0,21.0>--<724.0,342.0>>

	* m (U+006D): L<<764.0,405.0>--<765.0,21.0>>

	* n (U+006E): L<<408.0,21.0>--<407.0,342.0>>

	* n (U+006E): L<<447.0,405.0>--<448.0,21.0>>

	* nacute (U+0144): L<<408.0,21.0>--<407.0,342.0>>

	* nacute (U+0144): L<<447.0,405.0>--<448.0,21.0>>

	* napostrophe (U+0149): L<<561.0,21.0>--<560.0,342.0>>

	* napostrophe (U+0149): L<<600.0,405.0>--<601.0,21.0>>

	* ncaron (U+0148): L<<408.0,21.0>--<407.0,342.0>>

	* ncaron (U+0148): L<<447.0,405.0>--<448.0,21.0>>

	* nmacronbelow (U+1E49): L<<408.0,21.0>--<407.0,342.0>>

	* nmacronbelow (U+1E49): L<<447.0,405.0>--<448.0,21.0>>

	* ntilde (U+00F1): L<<408.0,21.0>--<407.0,342.0>>

	* ntilde (U+00F1): L<<447.0,405.0>--<448.0,21.0>>

	* t (U+0074): L<<122.0,573.0>--<123.0,726.0>>

	* tbar (U+0167): L<<122.0,573.0>--<123.0,726.0>>

	* tcaron (U+0165): L<<122.0,573.0>--<123.0,726.0>>

	* tmacronbelow (U+1E6F): L<<122.0,573.0>--<123.0,726.0>>

	* u (U+0075): L<<101.0,552.0>--<102.0,220.0>>

	* u (U+0075): L<<61.0,168.0>--<60.0,552.0>>

	* uacute (U+00FA): L<<101.0,552.0>--<102.0,220.0>>

	* uacute (U+00FA): L<<61.0,168.0>--<60.0,552.0>>

	* ubreve (U+016D): L<<101.0,552.0>--<102.0,220.0>>

	* ubreve (U+016D): L<<61.0,168.0>--<60.0,552.0>>

	* ucircumflex (U+00FB): L<<101.0,552.0>--<102.0,220.0>>

	* ucircumflex (U+00FB): L<<61.0,168.0>--<60.0,552.0>>

	* udieresis (U+00FC): L<<101.0,552.0>--<102.0,220.0>>

	* udieresis (U+00FC): L<<61.0,168.0>--<60.0,552.0>>

	* ugrave (U+00F9): L<<101.0,552.0>--<102.0,220.0>>

	* ugrave (U+00F9): L<<61.0,168.0>--<60.0,552.0>>

	* uhungarumlaut (U+0171): L<<101.0,552.0>--<102.0,220.0>>

	* uhungarumlaut (U+0171): L<<61.0,168.0>--<60.0,552.0>>

	* umacron (U+016B): L<<101.0,552.0>--<102.0,220.0>>

	* umacron (U+016B): L<<61.0,168.0>--<60.0,552.0>>

	* uni00B5 (U+00B5): L<<100.0,552.0>--<101.0,168.0>>

	* uni00B5 (U+00B5): L<<60.0,168.0>--<59.0,552.0>>

	* uni0146 (U+0146): L<<408.0,21.0>--<407.0,342.0>>

	* uni0146 (U+0146): L<<447.0,405.0>--<448.0,21.0>>

	* uni0163 (U+0163): L<<122.0,573.0>--<123.0,726.0>>

	* uni021B (U+021B): L<<122.0,573.0>--<123.0,726.0>>

	* uni0233 (U+0233): L<<101.0,552.0>--<102.0,168.0>>

	* uni0233 (U+0233): L<<61.0,168.0>--<60.0,552.0>>

	* uni0272 (U+0272): L<<408.0,21.0>--<407.0,342.0>>

	* uni0272 (U+0272): L<<447.0,405.0>--<448.0,21.0>>

	* uni03BC (U+03BC): L<<110.0,552.0>--<111.0,168.0>>

	* uni03BC (U+03BC): L<<70.0,168.0>--<69.0,552.0>>

	* uni1E25 (U+1E25): L<<407.0,20.0>--<406.0,405.0>>

	* uni1E25 (U+1E25): L<<446.0,405.0>--<447.0,20.0>>

	* uni1E2B (U+1E2B): L<<407.0,20.0>--<406.0,405.0>>

	* uni1E2B (U+1E2B): L<<446.0,405.0>--<447.0,20.0>>

	* uni1E43 (U+1E43): L<<392.0,21.0>--<391.0,342.0>>

	* uni1E43 (U+1E43): L<<725.0,21.0>--<724.0,342.0>>

	* uni1E43 (U+1E43): L<<764.0,405.0>--<765.0,21.0>>

	* uni1E45 (U+1E45): L<<408.0,21.0>--<407.0,342.0>>

	* uni1E45 (U+1E45): L<<447.0,405.0>--<448.0,21.0>>

	* uni1E47 (U+1E47): L<<408.0,21.0>--<407.0,342.0>>

	* uni1E47 (U+1E47): L<<447.0,405.0>--<448.0,21.0>>

	* uni1E6D (U+1E6D): L<<122.0,573.0>--<123.0,726.0>>

	* uni1E79 (U+1E79): L<<101.0,552.0>--<102.0,220.0>>

	* uni1E79 (U+1E79): L<<61.0,168.0>--<60.0,552.0>>

	* uni1E7B (U+1E7B): L<<101.0,552.0>--<102.0,220.0>>

	* uni1E7B (U+1E7B): L<<61.0,168.0>--<60.0,552.0>>

	* uni1E8F (U+1E8F): L<<101.0,552.0>--<102.0,168.0>>

	* uni1E8F (U+1E8F): L<<61.0,168.0>--<60.0,552.0>>

	* uni1E97 (U+1E97): L<<122.0,573.0>--<123.0,726.0>>

	* uni1E9E (U+1E9E): L<<112.0,706.0>--<111.0,21.0>>

	* uni1E9E (U+1E9E): L<<70.0,21.0>--<71.0,726.0>>

	* uni1EE5 (U+1EE5): L<<101.0,552.0>--<102.0,220.0>>

	* uni1EE5 (U+1EE5): L<<61.0,168.0>--<60.0,552.0>>

	* uni1EF9 (U+1EF9): L<<101.0,552.0>--<102.0,168.0>>

	* uni1EF9 (U+1EF9): L<<61.0,168.0>--<60.0,552.0>>

	* uogonek (U+0173): L<<101.0,552.0>--<102.0,220.0>>

	* uogonek (U+0173): L<<61.0,168.0>--<60.0,552.0>>

	* uring (U+016F): L<<101.0,552.0>--<102.0,220.0>>

	* uring (U+016F): L<<61.0,168.0>--<60.0,552.0>>

	* utilde (U+0169): L<<101.0,552.0>--<102.0,220.0>>

	* utilde (U+0169): L<<61.0,168.0>--<60.0,552.0>>

	* y (U+0079): L<<101.0,552.0>--<102.0,168.0>>

	* y (U+0079): L<<61.0,168.0>--<60.0,552.0>>

	* yacute (U+00FD): L<<101.0,552.0>--<102.0,168.0>>

	* yacute (U+00FD): L<<61.0,168.0>--<60.0,552.0>>

	* ycircumflex (U+0177): L<<101.0,552.0>--<102.0,168.0>>

	* ycircumflex (U+0177): L<<61.0,168.0>--<60.0,552.0>>

	* ydieresis (U+00FF): L<<101.0,552.0>--<102.0,168.0>>

	* ydieresis (U+00FF): L<<61.0,168.0>--<60.0,552.0>>

	* ygrave (U+1EF3): L<<101.0,552.0>--<102.0,168.0>>

	* ygrave (U+1EF3): L<<61.0,168.0>--<60.0,552.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[21] LibertineSuper-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1327, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 354, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoLineGap (200) and hhea lineGap (0) must be equal. [code: lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Libertine Super Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- logo_full

	- logo_ls

	- uni00690307
 [code: unreachable-glyphs]
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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 541 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 567:
less, greater

Width = 548:
plusminus, approxequal, notequal

Width = 538:
multiply

Width = 566:
lessequal

Width = 559:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* AE (U+00C6): L<<421.0,747.0>--<450.0,747.0>> -> L<<450.0,747.0>--<450.0,747.0>>

	* AE (U+00C6): L<<450.0,747.0>--<450.0,747.0>> -> L<<450.0,747.0>--<454.0,747.0>>

	* AE (U+00C6): L<<450.0,747.0>--<454.0,747.0>> -> L<<454.0,747.0>--<743.0,747.0>>

	* AEacute (U+01FC): L<<421.0,747.0>--<450.0,747.0>> -> L<<450.0,747.0>--<450.0,747.0>>

	* AEacute (U+01FC): L<<450.0,747.0>--<450.0,747.0>> -> L<<450.0,747.0>--<454.0,747.0>>

	* AEacute (U+01FC): L<<450.0,747.0>--<454.0,747.0>> -> L<<454.0,747.0>--<743.0,747.0>>

	* Aacute (U+00C1): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Abreve (U+0102): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Acircumflex (U+00C2): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Adieresis (U+00C4): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Agrave (U+00C0): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Amacron (U+0100): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aogonek (U+0104): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aring (U+00C5): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Aringacute (U+01FA): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Atilde (U+00C3): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* Y (U+0059): L<<222.0,366.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Y (U+0059): L<<469.0,703.0>--<286.0,374.0>> -> L<<286.0,374.0>--<280.0,364.0>>

	* Yacute (U+00DD): L<<222.0,366.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Yacute (U+00DD): L<<469.0,703.0>--<286.0,374.0>> -> L<<286.0,374.0>--<280.0,364.0>>

	* Ycircumflex (U+0176): L<<222.0,366.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Ycircumflex (U+0176): L<<469.0,703.0>--<286.0,374.0>> -> L<<286.0,374.0>--<280.0,364.0>>

	* Ydieresis (U+0178): L<<222.0,366.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Ydieresis (U+0178): L<<469.0,703.0>--<286.0,374.0>> -> L<<286.0,374.0>--<280.0,364.0>>

	* Ygrave (U+1EF2): L<<222.0,366.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* Ygrave (U+1EF2): L<<469.0,703.0>--<286.0,374.0>> -> L<<286.0,374.0>--<280.0,364.0>>

	* comma (U+002C): L<<137.0,39.0>--<137.0,39.0>> -> L<<137.0,39.0>--<137.0,39.0>>

	* eng (U+014B): L<<411.0,-144.0>--<411.0,33.0>> -> L<<411.0,33.0>--<410.0,326.0>>

	* eng (U+014B): L<<468.0,29.0>--<468.0,28.0>> -> L<<468.0,28.0>--<468.0,-144.0>>

	* eng (U+014B): L<<468.0,33.0>--<468.0,29.0>> -> L<<468.0,29.0>--<468.0,28.0>>

	* eng (U+014B): L<<468.0,39.0>--<468.0,33.0>> -> L<<468.0,33.0>--<468.0,29.0>>

	* k (U+006B): L<<118.0,577.0>--<335.0,577.0>> -> L<<335.0,577.0>--<335.0,577.0>>

	* k (U+006B): L<<335.0,577.0>--<335.0,577.0>> -> L<<335.0,577.0>--<336.0,577.0>>

	* semicolon (U+003B): L<<137.0,39.0>--<137.0,39.0>> -> L<<137.0,39.0>--<137.0,39.0>>

	* thorn (U+00FE): L<<270.0,53.0>--<274.0,53.0>> -> L<<274.0,53.0>--<287.0,53.0>>

	* trademark (U+2122): L<<586.0,761.0>--<586.0,761.0>> -> L<<586.0,761.0>--<586.0,761.0>>

	* uni00B5 (U+00B5): L<<60.0,-163.0>--<60.0,173.0>> -> L<<60.0,173.0>--<59.0,548.0>>

	* uni0137 (U+0137): L<<118.0,577.0>--<335.0,577.0>> -> L<<335.0,577.0>--<335.0,577.0>>

	* uni0137 (U+0137): L<<335.0,577.0>--<335.0,577.0>> -> L<<335.0,577.0>--<336.0,577.0>>

	* uni0232 (U+0232): L<<222.0,366.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* uni0232 (U+0232): L<<469.0,703.0>--<286.0,374.0>> -> L<<286.0,374.0>--<280.0,364.0>>

	* uni0272 (U+0272): L<<118.0,29.0>--<118.0,28.0>> -> L<<118.0,28.0>--<118.0,-144.0>>

	* uni0272 (U+0272): L<<118.0,317.0>--<118.0,29.0>> -> L<<118.0,29.0>--<118.0,28.0>>

	* uni0272 (U+0272): L<<60.0,-144.0>--<60.0,33.0>> -> L<<60.0,33.0>--<60.0,34.0>>

	* uni0272 (U+0272): L<<60.0,33.0>--<60.0,34.0>> -> L<<60.0,34.0>--<60.0,548.0>>

	* uni03BC (U+03BC): L<<77.0,-163.0>--<77.0,173.0>> -> L<<77.0,173.0>--<76.0,548.0>>

	* uni1E8E (U+1E8E): L<<222.0,366.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* uni1E8E (U+1E8E): L<<469.0,703.0>--<286.0,374.0>> -> L<<286.0,374.0>--<280.0,364.0>>

	* uni1EA0 (U+1EA0): L<<250.0,752.0>--<250.0,752.0>> -> L<<250.0,752.0>--<250.0,752.0>>

	* uni1EF8 (U+1EF8): L<<222.0,366.0>--<218.0,374.0>> -> L<<218.0,374.0>--<34.0,703.0>>

	* uni1EF8 (U+1EF8): L<<469.0,703.0>--<286.0,374.0>> -> L<<286.0,374.0>--<280.0,364.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Acircumflex (U+00C2): B<<274.0,972.5>-<274.0,972.0>-<273.0,974.0>>/B<<273.0,974.0>-<275.0,971.0>-<277.0,967.0>> = 7.125016348901757

	* Ccaron (U+010C): B<<298.0,828.0>-<296.0,824.0>-<294.0,821.0>>/B<<294.0,821.0>-<295.0,823.0>-<294.5,822.5>> = 7.125016348901757

	* Ccircumflex (U+0108): B<<297.0,972.5>-<297.0,972.0>-<296.0,974.0>>/B<<296.0,974.0>-<298.0,971.0>-<300.0,967.0>> = 7.125016348901757

	* Dcaron (U+010E): B<<274.0,828.0>-<272.0,824.0>-<270.0,821.0>>/B<<270.0,821.0>-<271.0,823.0>-<270.5,822.5>> = 7.125016348901757

	* Ecircumflex (U+00CA): B<<265.0,972.5>-<265.0,972.0>-<264.0,974.0>>/B<<264.0,974.0>-<266.0,971.0>-<268.0,967.0>> = 7.125016348901757

	* Gcircumflex (U+011C): B<<310.0,972.5>-<310.0,972.0>-<309.0,974.0>>/B<<309.0,974.0>-<311.0,971.0>-<313.0,967.0>> = 7.125016348901757

	* Hcircumflex (U+0124): B<<279.0,972.5>-<279.0,972.0>-<278.0,974.0>>/B<<278.0,974.0>-<280.0,971.0>-<282.0,967.0>> = 7.125016348901757

	* Icircumflex (U+00CE): B<<123.0,972.5>-<123.0,972.0>-<122.0,974.0>>/B<<122.0,974.0>-<124.0,971.0>-<126.0,967.0>> = 7.125016348901757

	* Jcircumflex (U+0134): B<<278.0,972.5>-<278.0,972.0>-<277.0,974.0>>/B<<277.0,974.0>-<279.0,971.0>-<281.0,967.0>> = 7.125016348901757

	* Ocircumflex (U+00D4): B<<322.0,972.5>-<322.0,972.0>-<321.0,974.0>>/B<<321.0,974.0>-<323.0,971.0>-<325.0,967.0>> = 7.125016348901757

	* Scaron (U+0160): B<<271.0,828.0>-<269.0,824.0>-<267.0,821.0>>/B<<267.0,821.0>-<268.0,823.0>-<267.5,822.5>> = 7.125016348901757

	* Scircumflex (U+015C): B<<270.0,972.5>-<270.0,972.0>-<269.0,974.0>>/B<<269.0,974.0>-<271.0,971.0>-<273.0,967.0>> = 7.125016348901757

	* Tcaron (U+0164): B<<271.0,828.0>-<269.0,824.0>-<267.0,821.0>>/B<<267.0,821.0>-<268.0,823.0>-<268.0,822.5>> = 7.125016348901757

	* Ucircumflex (U+00DB): B<<317.0,972.5>-<317.0,972.0>-<316.0,974.0>>/B<<316.0,974.0>-<318.0,971.0>-<320.0,967.0>> = 7.125016348901757

	* Wcircumflex (U+0174): B<<311.0,972.5>-<311.0,972.0>-<310.0,974.0>>/B<<310.0,974.0>-<312.0,971.0>-<314.0,967.0>> = 7.125016348901757

	* Ycircumflex (U+0176): B<<270.0,972.5>-<270.0,972.0>-<269.0,974.0>>/B<<269.0,974.0>-<271.0,971.0>-<273.0,967.0>> = 7.125016348901757

	* acircumflex (U+00E2): B<<266.0,793.5>-<266.0,793.0>-<265.0,795.0>>/B<<265.0,795.0>-<267.0,792.0>-<269.0,788.0>> = 7.125016348901757

	* ccircumflex (U+0109): B<<271.0,793.5>-<271.0,793.0>-<270.0,795.0>>/B<<270.0,795.0>-<272.0,792.0>-<274.0,788.0>> = 7.125016348901757

	* circumflex (U+02C6): B<<374.0,731.5>-<374.0,731.0>-<373.0,733.0>>/B<<373.0,733.0>-<375.0,730.0>-<377.0,726.0>> = 7.125016348901757

	* ecircumflex (U+00EA): B<<289.0,793.5>-<289.0,793.0>-<288.0,795.0>>/B<<288.0,795.0>-<290.0,792.0>-<292.0,788.0>> = 7.125016348901757

	* gcircumflex (U+011D): B<<300.0,793.5>-<300.0,793.0>-<299.0,795.0>>/B<<299.0,795.0>-<301.0,792.0>-<303.0,788.0>> = 7.125016348901757

	* hcircumflex (U+0125): B<<283.0,1005.5>-<283.0,1005.0>-<282.0,1007.0>>/B<<282.0,1007.0>-<284.0,1004.0>-<286.0,1000.0>> = 7.125016348901757

	* icircumflex (U+00EE): B<<244.0,793.5>-<244.0,793.0>-<243.0,795.0>>/B<<243.0,795.0>-<245.0,792.0>-<247.0,788.0>> = 7.125016348901757

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* ncaron (U+0148): B<<290.0,649.0>-<288.0,645.0>-<286.0,642.0>>/B<<286.0,642.0>-<287.0,644.0>-<286.5,643.5>> = 7.125016348901757

	* ocircumflex (U+00F4): B<<295.0,793.5>-<295.0,793.0>-<294.0,795.0>>/B<<294.0,795.0>-<296.0,792.0>-<298.0,788.0>> = 7.125016348901757

	* rcaron (U+0159): B<<232.0,649.0>-<231.0,645.0>-<229.0,642.0>>/B<<229.0,642.0>-<230.0,644.0>-<229.5,643.5>> = 7.125016348901757

	* scaron (U+0161): B<<239.0,649.0>-<237.0,645.0>-<235.0,642.0>>/B<<235.0,642.0>-<236.0,644.0>-<235.5,643.5>> = 7.125016348901757

	* scircumflex (U+015D): B<<238.0,793.5>-<238.0,793.0>-<237.0,795.0>>/B<<237.0,795.0>-<239.0,792.0>-<241.0,788.0>> = 7.125016348901757

	* ucircumflex (U+00FB): B<<289.0,793.5>-<289.0,793.0>-<288.0,795.0>>/B<<288.0,795.0>-<290.0,792.0>-<292.0,788.0>> = 7.125016348901757

	* uni0302 (U+0302): B<<374.0,731.5>-<374.0,731.0>-<373.0,733.0>>/B<<373.0,733.0>-<375.0,730.0>-<377.0,726.0>> = 7.125016348901757

	* uni1E66 (U+1E66): B<<271.0,828.0>-<269.0,824.0>-<267.0,821.0>>/B<<267.0,821.0>-<268.0,823.0>-<267.5,822.5>> = 7.125016348901757

	* uni1E67 (U+1E67): B<<239.0,649.0>-<237.0,645.0>-<235.0,642.0>>/B<<235.0,642.0>-<236.0,644.0>-<235.5,643.5>> = 7.125016348901757

	* wcircumflex (U+0175): B<<374.0,793.5>-<374.0,793.0>-<373.0,795.0>>/B<<373.0,795.0>-<375.0,792.0>-<377.0,788.0>> = 7.125016348901757

	* ycircumflex (U+0177): B<<289.0,793.5>-<289.0,793.0>-<288.0,795.0>>/B<<288.0,795.0>-<290.0,792.0>-<292.0,788.0>> = 7.125016348901757

	* zcaron (U+017E): B<<271.0,649.0>-<270.0,645.0>-<268.0,642.0>>/B<<268.0,642.0>-<269.0,644.0>-<268.5,643.5>> = 7.125016348901757 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<411.0,33.0>--<410.0,326.0>>

	* eng (U+014B): L<<467.0,404.0>--<468.0,39.0>>

	* h (U+0068): L<<410.0,28.0>--<409.0,404.0>>

	* h (U+0068): L<<467.0,404.0>--<468.0,28.0>>

	* hbar (U+0127): L<<429.0,28.0>--<428.0,404.0>>

	* hbar (U+0127): L<<486.0,404.0>--<487.0,28.0>>

	* hcircumflex (U+0125): L<<410.0,28.0>--<409.0,404.0>>

	* hcircumflex (U+0125): L<<467.0,404.0>--<468.0,28.0>>

	* m (U+006D): L<<396.0,29.0>--<395.0,326.0>>

	* m (U+006D): L<<732.0,29.0>--<731.0,326.0>>

	* m (U+006D): L<<788.0,404.0>--<789.0,29.0>>

	* n (U+006E): L<<411.0,29.0>--<410.0,326.0>>

	* n (U+006E): L<<467.0,404.0>--<468.0,29.0>>

	* nacute (U+0144): L<<411.0,29.0>--<410.0,326.0>>

	* nacute (U+0144): L<<467.0,404.0>--<468.0,29.0>>

	* napostrophe (U+0149): L<<580.0,29.0>--<579.0,326.0>>

	* napostrophe (U+0149): L<<636.0,404.0>--<637.0,29.0>>

	* ncaron (U+0148): L<<411.0,29.0>--<410.0,326.0>>

	* ncaron (U+0148): L<<467.0,404.0>--<468.0,29.0>>

	* nmacronbelow (U+1E49): L<<411.0,29.0>--<410.0,326.0>>

	* nmacronbelow (U+1E49): L<<467.0,404.0>--<468.0,29.0>>

	* ntilde (U+00F1): L<<411.0,29.0>--<410.0,326.0>>

	* ntilde (U+00F1): L<<467.0,404.0>--<468.0,29.0>>

	* t (U+0074): L<<123.0,577.0>--<124.0,718.0>>

	* tbar (U+0167): L<<123.0,577.0>--<124.0,718.0>>

	* tcaron (U+0165): L<<123.0,577.0>--<124.0,718.0>>

	* tmacronbelow (U+1E6F): L<<123.0,577.0>--<124.0,718.0>>

	* u (U+0075): L<<118.0,548.0>--<119.0,232.0>>

	* u (U+0075): L<<61.0,173.0>--<60.0,548.0>>

	* uacute (U+00FA): L<<118.0,548.0>--<119.0,232.0>>

	* uacute (U+00FA): L<<61.0,173.0>--<60.0,548.0>>

	* ubreve (U+016D): L<<118.0,548.0>--<119.0,232.0>>

	* ubreve (U+016D): L<<61.0,173.0>--<60.0,548.0>>

	* ucircumflex (U+00FB): L<<118.0,548.0>--<119.0,232.0>>

	* ucircumflex (U+00FB): L<<61.0,173.0>--<60.0,548.0>>

	* udieresis (U+00FC): L<<118.0,548.0>--<119.0,232.0>>

	* udieresis (U+00FC): L<<61.0,173.0>--<60.0,548.0>>

	* ugrave (U+00F9): L<<118.0,548.0>--<119.0,232.0>>

	* ugrave (U+00F9): L<<61.0,173.0>--<60.0,548.0>>

	* uhungarumlaut (U+0171): L<<118.0,548.0>--<119.0,232.0>>

	* uhungarumlaut (U+0171): L<<61.0,173.0>--<60.0,548.0>>

	* umacron (U+016B): L<<118.0,548.0>--<119.0,232.0>>

	* umacron (U+016B): L<<61.0,173.0>--<60.0,548.0>>

	* uni00B5 (U+00B5): L<<117.0,548.0>--<118.0,173.0>>

	* uni00B5 (U+00B5): L<<60.0,173.0>--<59.0,548.0>>

	* uni0146 (U+0146): L<<411.0,29.0>--<410.0,326.0>>

	* uni0146 (U+0146): L<<467.0,404.0>--<468.0,29.0>>

	* uni0163 (U+0163): L<<123.0,577.0>--<124.0,718.0>>

	* uni021B (U+021B): L<<123.0,577.0>--<124.0,718.0>>

	* uni0233 (U+0233): L<<118.0,548.0>--<119.0,173.0>>

	* uni0233 (U+0233): L<<61.0,173.0>--<60.0,548.0>>

	* uni0272 (U+0272): L<<411.0,29.0>--<410.0,326.0>>

	* uni0272 (U+0272): L<<467.0,404.0>--<468.0,29.0>>

	* uni03BC (U+03BC): L<<134.0,548.0>--<135.0,173.0>>

	* uni03BC (U+03BC): L<<77.0,173.0>--<76.0,548.0>>

	* uni1E25 (U+1E25): L<<410.0,28.0>--<409.0,404.0>>

	* uni1E25 (U+1E25): L<<467.0,404.0>--<468.0,28.0>>

	* uni1E2B (U+1E2B): L<<410.0,28.0>--<409.0,404.0>>

	* uni1E2B (U+1E2B): L<<467.0,404.0>--<468.0,28.0>>

	* uni1E43 (U+1E43): L<<396.0,29.0>--<395.0,326.0>>

	* uni1E43 (U+1E43): L<<732.0,29.0>--<731.0,326.0>>

	* uni1E43 (U+1E43): L<<788.0,404.0>--<789.0,29.0>>

	* uni1E45 (U+1E45): L<<411.0,29.0>--<410.0,326.0>>

	* uni1E45 (U+1E45): L<<467.0,404.0>--<468.0,29.0>>

	* uni1E47 (U+1E47): L<<411.0,29.0>--<410.0,326.0>>

	* uni1E47 (U+1E47): L<<467.0,404.0>--<468.0,29.0>>

	* uni1E6D (U+1E6D): L<<123.0,577.0>--<124.0,718.0>>

	* uni1E79 (U+1E79): L<<118.0,548.0>--<119.0,232.0>>

	* uni1E79 (U+1E79): L<<61.0,173.0>--<60.0,548.0>>

	* uni1E7B (U+1E7B): L<<118.0,548.0>--<119.0,232.0>>

	* uni1E7B (U+1E7B): L<<61.0,173.0>--<60.0,548.0>>

	* uni1E8F (U+1E8F): L<<118.0,548.0>--<119.0,173.0>>

	* uni1E8F (U+1E8F): L<<61.0,173.0>--<60.0,548.0>>

	* uni1E97 (U+1E97): L<<123.0,577.0>--<124.0,718.0>>

	* uni1E9E (U+1E9E): L<<129.0,689.0>--<128.0,29.0>>

	* uni1E9E (U+1E9E): L<<70.0,29.0>--<71.0,718.0>>

	* uni1EE5 (U+1EE5): L<<118.0,548.0>--<119.0,232.0>>

	* uni1EE5 (U+1EE5): L<<61.0,173.0>--<60.0,548.0>>

	* uni1EF9 (U+1EF9): L<<118.0,548.0>--<119.0,173.0>>

	* uni1EF9 (U+1EF9): L<<61.0,173.0>--<60.0,548.0>>

	* uogonek (U+0173): L<<118.0,548.0>--<119.0,232.0>>

	* uogonek (U+0173): L<<61.0,173.0>--<60.0,548.0>>

	* uring (U+016F): L<<118.0,548.0>--<119.0,232.0>>

	* uring (U+016F): L<<61.0,173.0>--<60.0,548.0>>

	* utilde (U+0169): L<<118.0,548.0>--<119.0,232.0>>

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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[20] LibertineSuper-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1327, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 354, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoLineGap (200) and hhea lineGap (0) must be equal. [code: lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- logo_full

	- logo_ls

	- uni00690307
 [code: unreachable-glyphs]
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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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

	- Glyph name: perthousand	Contours detected: 9	Expected: 6or7

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

	- Glyph name: perthousand	Contours detected: 9	Expected: 6or7

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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 563 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 600:
less, greater

Width = 570:
plusminus, notequal

Width = 558:
multiply

Width = 569:
approxequal

Width = 595:
lessequal

Width = 588:
greaterequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* A (U+0041): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* AE (U+00C6): L<<421.0,747.0>--<458.0,747.0>> -> L<<458.0,747.0>--<458.0,747.0>>

	* AEacute (U+01FC): L<<421.0,747.0>--<458.0,747.0>> -> L<<458.0,747.0>--<458.0,747.0>>

	* Aacute (U+00C1): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* Abreve (U+0102): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* Acircumflex (U+00C2): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* Adieresis (U+00C4): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* Agrave (U+00C0): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* Amacron (U+0100): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* Aogonek (U+0104): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* Aring (U+00C5): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* Aringacute (U+01FA): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* Atilde (U+00C3): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* R (U+0052): L<<311.0,210.0>--<310.0,210.0>> -> L<<310.0,210.0>--<145.0,210.0>>

	* Racute (U+0154): L<<311.0,210.0>--<310.0,210.0>> -> L<<310.0,210.0>--<145.0,210.0>>

	* Rcaron (U+0158): L<<311.0,210.0>--<310.0,210.0>> -> L<<310.0,210.0>--<145.0,210.0>>

	* Rmacronbelow (U+1E5E): L<<311.0,210.0>--<310.0,210.0>> -> L<<310.0,210.0>--<145.0,210.0>>

	* Y (U+0059): L<<224.0,364.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,690.0>>

	* Y (U+0059): L<<489.0,690.0>--<306.0,374.0>> -> L<<306.0,374.0>--<299.0,361.0>>

	* Yacute (U+00DD): L<<224.0,364.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,690.0>>

	* Yacute (U+00DD): L<<489.0,690.0>--<306.0,374.0>> -> L<<306.0,374.0>--<299.0,361.0>>

	* Ycircumflex (U+0176): L<<224.0,364.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,690.0>>

	* Ycircumflex (U+0176): L<<489.0,690.0>--<306.0,374.0>> -> L<<306.0,374.0>--<299.0,361.0>>

	* Ydieresis (U+0178): L<<224.0,364.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,690.0>>

	* Ydieresis (U+0178): L<<489.0,690.0>--<306.0,374.0>> -> L<<306.0,374.0>--<299.0,361.0>>

	* Ygrave (U+1EF2): L<<224.0,364.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,690.0>>

	* Ygrave (U+1EF2): L<<489.0,690.0>--<306.0,374.0>> -> L<<306.0,374.0>--<299.0,361.0>>

	* comma (U+002C): L<<154.0,47.0>--<154.0,47.0>> -> L<<154.0,47.0>--<154.0,47.0>>

	* d (U+0064): L<<274.0,69.0>--<288.0,69.0>> -> L<<288.0,69.0>--<288.0,69.0>>

	* dcaron (U+010F): L<<274.0,69.0>--<288.0,69.0>> -> L<<288.0,69.0>--<288.0,69.0>>

	* dcroat (U+0111): L<<274.0,69.0>--<288.0,69.0>> -> L<<288.0,69.0>--<288.0,69.0>>

	* dmacronbelow (U+1E0F): L<<274.0,69.0>--<288.0,69.0>> -> L<<288.0,69.0>--<288.0,69.0>>

	* eng (U+014B): L<<414.0,-144.0>--<414.0,43.0>> -> L<<414.0,43.0>--<414.0,310.0>>

	* eng (U+014B): L<<489.0,49.0>--<489.0,43.0>> -> L<<489.0,43.0>--<489.0,37.0>>

	* g (U+0067): L<<274.0,-132.0>--<288.0,-132.0>> -> L<<288.0,-132.0>--<288.0,-132.0>>

	* gbreve (U+011F): L<<274.0,-132.0>--<288.0,-132.0>> -> L<<288.0,-132.0>--<288.0,-132.0>>

	* gcaron (U+01E7): L<<274.0,-132.0>--<288.0,-132.0>> -> L<<288.0,-132.0>--<288.0,-132.0>>

	* gcircumflex (U+011D): L<<274.0,-132.0>--<288.0,-132.0>> -> L<<288.0,-132.0>--<288.0,-132.0>>

	* gdotaccent (U+0121): L<<274.0,-132.0>--<288.0,-132.0>> -> L<<288.0,-132.0>--<288.0,-132.0>>

	* semicolon (U+003B): L<<154.0,47.0>--<154.0,47.0>> -> L<<154.0,47.0>--<154.0,47.0>>

	* trademark (U+2122): L<<616.0,760.0>--<616.0,760.0>> -> L<<616.0,760.0>--<617.0,760.0>>

	* trademark (U+2122): L<<616.0,760.0>--<617.0,760.0>> -> L<<617.0,760.0>--<617.0,760.0>>

	* trademark (U+2122): L<<617.0,760.0>--<617.0,760.0>> -> L<<617.0,760.0>--<617.0,760.0>>

	* uni00B5 (U+00B5): L<<60.0,-151.0>--<60.0,177.0>> -> L<<60.0,177.0>--<59.0,544.0>>

	* uni0123 (U+0123): L<<274.0,-132.0>--<288.0,-132.0>> -> L<<288.0,-132.0>--<288.0,-132.0>>

	* uni0156 (U+0156): L<<311.0,210.0>--<310.0,210.0>> -> L<<310.0,210.0>--<145.0,210.0>>

	* uni0232 (U+0232): L<<224.0,364.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,690.0>>

	* uni0232 (U+0232): L<<489.0,690.0>--<306.0,374.0>> -> L<<306.0,374.0>--<299.0,361.0>>

	* uni03BC (U+03BC): L<<85.0,-151.0>--<85.0,177.0>> -> L<<85.0,177.0>--<84.0,544.0>>

	* uni1E0D (U+1E0D): L<<274.0,69.0>--<288.0,69.0>> -> L<<288.0,69.0>--<288.0,69.0>>

	* uni1E21 (U+1E21): L<<274.0,-132.0>--<288.0,-132.0>> -> L<<288.0,-132.0>--<288.0,-132.0>>

	* uni1E5A (U+1E5A): L<<311.0,210.0>--<310.0,210.0>> -> L<<310.0,210.0>--<145.0,210.0>>

	* uni1E8E (U+1E8E): L<<224.0,364.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,690.0>>

	* uni1E8E (U+1E8E): L<<489.0,690.0>--<306.0,374.0>> -> L<<306.0,374.0>--<299.0,361.0>>

	* uni1EA0 (U+1EA0): L<<260.0,751.0>--<260.0,751.0>> -> L<<260.0,751.0>--<260.0,751.0>>

	* uni1EF8 (U+1EF8): L<<224.0,364.0>--<218.0,374.0>> -> L<<218.0,374.0>--<35.0,690.0>>

	* uni1EF8 (U+1EF8): L<<489.0,690.0>--<306.0,374.0>> -> L<<306.0,374.0>--<299.0,361.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eng (U+014B): B<<489.0,37.0>-<489.0,35.0>-<489.0,36.0>>/L<<489.0,36.0>--<488.0,-144.0>> = 0.3183066114507731

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

	* perthousand (U+2030): B<<186.0,267.0>-<190.0,295.0>-<200.0,319.0>>/L<<200.0,319.0>--<61.0,127.0>> = 13.283107126159278

	* perthousand (U+2030): B<<427.0,183.0>-<427.0,166.0>-<426.0,150.0>>/L<<426.0,150.0>--<485.0,354.0>> = 12.554364177115495 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* eng (U+014B): L<<488.0,403.0>--<489.0,49.0>>

	* eng (U+014B): L<<489.0,36.0>--<488.0,-144.0>>

	* h (U+0068): L<<414.0,36.0>--<413.0,403.0>>

	* h (U+0068): L<<487.0,403.0>--<488.0,36.0>>

	* hbar (U+0127): L<<441.0,36.0>--<440.0,403.0>>

	* hbar (U+0127): L<<515.0,403.0>--<516.0,36.0>>

	* hcircumflex (U+0125): L<<414.0,36.0>--<413.0,403.0>>

	* hcircumflex (U+0125): L<<487.0,403.0>--<488.0,36.0>>

	* m (U+006D): L<<399.0,37.0>--<398.0,310.0>>

	* m (U+006D): L<<812.0,403.0>--<813.0,37.0>>

	* n (U+006E): L<<415.0,37.0>--<414.0,310.0>>

	* n (U+006E): L<<488.0,403.0>--<489.0,37.0>>

	* nacute (U+0144): L<<415.0,37.0>--<414.0,310.0>>

	* nacute (U+0144): L<<488.0,403.0>--<489.0,37.0>>

	* napostrophe (U+0149): L<<601.0,37.0>--<600.0,310.0>>

	* napostrophe (U+0149): L<<674.0,403.0>--<675.0,37.0>>

	* ncaron (U+0148): L<<415.0,37.0>--<414.0,310.0>>

	* ncaron (U+0148): L<<488.0,403.0>--<489.0,37.0>>

	* nmacronbelow (U+1E49): L<<415.0,37.0>--<414.0,310.0>>

	* nmacronbelow (U+1E49): L<<488.0,403.0>--<489.0,37.0>>

	* ntilde (U+00F1): L<<415.0,37.0>--<414.0,310.0>>

	* ntilde (U+00F1): L<<488.0,403.0>--<489.0,37.0>>

	* t (U+0074): L<<200.0,710.0>--<199.0,581.0>>

	* tbar (U+0167): L<<200.0,710.0>--<199.0,581.0>>

	* tcaron (U+0165): L<<200.0,710.0>--<199.0,581.0>>

	* tmacronbelow (U+1E6F): L<<200.0,710.0>--<199.0,581.0>>

	* u (U+0075): L<<135.0,544.0>--<136.0,245.0>>

	* u (U+0075): L<<61.0,177.0>--<60.0,544.0>>

	* uacute (U+00FA): L<<135.0,544.0>--<136.0,245.0>>

	* uacute (U+00FA): L<<61.0,177.0>--<60.0,544.0>>

	* ubreve (U+016D): L<<135.0,544.0>--<136.0,245.0>>

	* ubreve (U+016D): L<<61.0,177.0>--<60.0,544.0>>

	* ucircumflex (U+00FB): L<<135.0,544.0>--<136.0,245.0>>

	* ucircumflex (U+00FB): L<<61.0,177.0>--<60.0,544.0>>

	* udieresis (U+00FC): L<<135.0,544.0>--<136.0,245.0>>

	* udieresis (U+00FC): L<<61.0,177.0>--<60.0,544.0>>

	* ugrave (U+00F9): L<<135.0,544.0>--<136.0,245.0>>

	* ugrave (U+00F9): L<<61.0,177.0>--<60.0,544.0>>

	* uhungarumlaut (U+0171): L<<135.0,544.0>--<136.0,245.0>>

	* uhungarumlaut (U+0171): L<<61.0,177.0>--<60.0,544.0>>

	* umacron (U+016B): L<<135.0,544.0>--<136.0,245.0>>

	* umacron (U+016B): L<<61.0,177.0>--<60.0,544.0>>

	* uni00B5 (U+00B5): L<<134.0,544.0>--<135.0,177.0>>

	* uni00B5 (U+00B5): L<<60.0,177.0>--<59.0,544.0>>

	* uni0146 (U+0146): L<<415.0,37.0>--<414.0,310.0>>

	* uni0146 (U+0146): L<<488.0,403.0>--<489.0,37.0>>

	* uni0163 (U+0163): L<<200.0,710.0>--<199.0,581.0>>

	* uni021B (U+021B): L<<200.0,710.0>--<199.0,581.0>>

	* uni0233 (U+0233): L<<135.0,544.0>--<136.0,177.0>>

	* uni0233 (U+0233): L<<61.0,177.0>--<60.0,544.0>>

	* uni0272 (U+0272): L<<415.0,37.0>--<414.0,310.0>>

	* uni0272 (U+0272): L<<488.0,403.0>--<489.0,37.0>>

	* uni03BC (U+03BC): L<<159.0,544.0>--<160.0,177.0>>

	* uni03BC (U+03BC): L<<85.0,177.0>--<84.0,544.0>>

	* uni1E25 (U+1E25): L<<414.0,36.0>--<413.0,403.0>>

	* uni1E25 (U+1E25): L<<487.0,403.0>--<488.0,36.0>>

	* uni1E2B (U+1E2B): L<<414.0,36.0>--<413.0,403.0>>

	* uni1E2B (U+1E2B): L<<487.0,403.0>--<488.0,36.0>>

	* uni1E43 (U+1E43): L<<399.0,37.0>--<398.0,310.0>>

	* uni1E43 (U+1E43): L<<812.0,403.0>--<813.0,37.0>>

	* uni1E45 (U+1E45): L<<415.0,37.0>--<414.0,310.0>>

	* uni1E45 (U+1E45): L<<488.0,403.0>--<489.0,37.0>>

	* uni1E47 (U+1E47): L<<415.0,37.0>--<414.0,310.0>>

	* uni1E47 (U+1E47): L<<488.0,403.0>--<489.0,37.0>>

	* uni1E6D (U+1E6D): L<<200.0,710.0>--<199.0,581.0>>

	* uni1E79 (U+1E79): L<<135.0,544.0>--<136.0,245.0>>

	* uni1E79 (U+1E79): L<<61.0,177.0>--<60.0,544.0>>

	* uni1E7B (U+1E7B): L<<135.0,544.0>--<136.0,245.0>>

	* uni1E7B (U+1E7B): L<<61.0,177.0>--<60.0,544.0>>

	* uni1E8F (U+1E8F): L<<135.0,544.0>--<136.0,177.0>>

	* uni1E8F (U+1E8F): L<<61.0,177.0>--<60.0,544.0>>

	* uni1E97 (U+1E97): L<<200.0,710.0>--<199.0,581.0>>

	* uni1E9E (U+1E9E): L<<146.0,672.0>--<145.0,37.0>>

	* uni1E9E (U+1E9E): L<<70.0,37.0>--<71.0,710.0>>

	* uni1EE5 (U+1EE5): L<<135.0,544.0>--<136.0,245.0>>

	* uni1EE5 (U+1EE5): L<<61.0,177.0>--<60.0,544.0>>

	* uni1EF9 (U+1EF9): L<<135.0,544.0>--<136.0,177.0>>

	* uni1EF9 (U+1EF9): L<<61.0,177.0>--<60.0,544.0>>

	* uogonek (U+0173): L<<135.0,544.0>--<136.0,245.0>>

	* uogonek (U+0173): L<<61.0,177.0>--<60.0,544.0>>

	* uring (U+016F): L<<135.0,544.0>--<136.0,245.0>>

	* uring (U+016F): L<<61.0,177.0>--<60.0,544.0>>

	* utilde (U+0169): L<<135.0,544.0>--<136.0,245.0>>

	* utilde (U+0169): L<<61.0,177.0>--<60.0,544.0>>

	* y (U+0079): L<<135.0,544.0>--<136.0,177.0>>

	* y (U+0079): L<<61.0,177.0>--<60.0,544.0>>

	* yacute (U+00FD): L<<135.0,544.0>--<136.0,177.0>>

	* yacute (U+00FD): L<<61.0,177.0>--<60.0,544.0>>

	* ycircumflex (U+0177): L<<135.0,544.0>--<136.0,177.0>>

	* ycircumflex (U+0177): L<<61.0,177.0>--<60.0,544.0>>

	* ydieresis (U+00FF): L<<135.0,544.0>--<136.0,177.0>>

	* ydieresis (U+00FF): L<<61.0,177.0>--<60.0,544.0>>

	* ygrave (U+1EF3): L<<135.0,544.0>--<136.0,177.0>>

	* ygrave (U+1EF3): L<<61.0,177.0>--<60.0,544.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details><details><summary><b>[20] LibertineSuper-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1327, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 354, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoLineGap (200) and hhea lineGap (0) must be equal. [code: lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJacute

	- logo_full

	- logo_ls

	- uni00690307
 [code: unreachable-glyphs]
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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 493 among a set of 9 math glyphs.
The following math glyphs have a different width, though:

Width = 500:
lessequal, plusminus, approxequal, notequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
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

	* Y (U+0059): L<<218.0,372.0>--<217.0,374.0>> -> L<<217.0,374.0>--<31.0,732.0>>

	* Y (U+0059): L<<425.0,732.0>--<240.0,374.0>> -> L<<240.0,374.0>--<238.0,370.0>>

	* Yacute (U+00DD): L<<218.0,372.0>--<217.0,374.0>> -> L<<217.0,374.0>--<31.0,732.0>>

	* Yacute (U+00DD): L<<425.0,732.0>--<240.0,374.0>> -> L<<240.0,374.0>--<238.0,370.0>>

	* Ycircumflex (U+0176): L<<218.0,372.0>--<217.0,374.0>> -> L<<217.0,374.0>--<31.0,732.0>>

	* Ycircumflex (U+0176): L<<425.0,732.0>--<240.0,374.0>> -> L<<240.0,374.0>--<238.0,370.0>>

	* Ydieresis (U+0178): L<<218.0,372.0>--<217.0,374.0>> -> L<<217.0,374.0>--<31.0,732.0>>

	* Ydieresis (U+0178): L<<425.0,732.0>--<240.0,374.0>> -> L<<240.0,374.0>--<238.0,370.0>>

	* Ygrave (U+1EF2): L<<218.0,372.0>--<217.0,374.0>> -> L<<217.0,374.0>--<31.0,732.0>>

	* Ygrave (U+1EF2): L<<425.0,732.0>--<240.0,374.0>> -> L<<240.0,374.0>--<238.0,370.0>>

	* comma (U+002C): L<<99.0,20.0>--<99.0,20.0>> -> L<<99.0,20.0>--<99.0,20.0>>

	* eng (U+014B): L<<403.0,-144.0>--<403.0,10.0>> -> L<<403.0,10.0>--<402.0,363.0>>

	* k (U+006B): L<<310.0,568.0>--<311.0,568.0>> -> L<<311.0,568.0>--<311.0,568.0>>

	* k (U+006B): L<<80.0,568.0>--<310.0,568.0>> -> L<<310.0,568.0>--<311.0,568.0>>

	* semicolon (U+003B): L<<99.0,20.0>--<99.0,20.0>> -> L<<99.0,20.0>--<99.0,20.0>>

	* uni00B5 (U+00B5): L<<60.0,-192.0>--<60.0,162.0>> -> L<<60.0,162.0>--<59.0,558.0>>

	* uni0137 (U+0137): L<<310.0,568.0>--<311.0,568.0>> -> L<<311.0,568.0>--<311.0,568.0>>

	* uni0137 (U+0137): L<<80.0,568.0>--<310.0,568.0>> -> L<<310.0,568.0>--<311.0,568.0>>

	* uni0232 (U+0232): L<<218.0,372.0>--<217.0,374.0>> -> L<<217.0,374.0>--<31.0,732.0>>

	* uni0232 (U+0232): L<<425.0,732.0>--<240.0,374.0>> -> L<<240.0,374.0>--<238.0,370.0>>

	* uni03BC (U+03BC): L<<60.0,-192.0>--<60.0,162.0>> -> L<<60.0,162.0>--<59.0,558.0>>

	* uni1E78 (U+1E78): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* uni1E7A (U+1E7A): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* uni1E8E (U+1E8E): L<<218.0,372.0>--<217.0,374.0>> -> L<<217.0,374.0>--<31.0,732.0>>

	* uni1E8E (U+1E8E): L<<425.0,732.0>--<240.0,374.0>> -> L<<240.0,374.0>--<238.0,370.0>>

	* uni1EA0 (U+1EA0): L<<226.0,752.0>--<227.0,752.0>> -> L<<227.0,752.0>--<227.0,752.0>>

	* uni1EE4 (U+1EE4): L<<70.0,187.0>--<70.0,192.0>> -> L<<70.0,192.0>--<70.0,737.0>>

	* uni1EF8 (U+1EF8): L<<218.0,372.0>--<217.0,374.0>> -> L<<217.0,374.0>--<31.0,732.0>>

	* uni1EF8 (U+1EF8): L<<425.0,732.0>--<240.0,374.0>> -> L<<240.0,374.0>--<238.0,370.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* logo (U+F0000): B<<1065.0,202.5>-<1062.0,185.0>-<1057.0,170.0>>/B<<1057.0,170.0>-<1083.0,213.0>-<1095.5,227.0>> = 12.724355685422335

	* logo (U+F0000): B<<1150.5,90.5>-<1165.0,144.0>-<1187.0,205.0>>/B<<1187.0,205.0>-<1173.0,183.0>-<1160.5,167.0>> = 12.639062440630111

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

	* uni00B5 (U+00B5): L<<60.0,162.0>--<59.0,558.0>>

	* uni00B5 (U+00B5): L<<79.0,558.0>--<80.0,162.0>>

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

	* uni03BC (U+03BC): L<<60.0,162.0>--<59.0,558.0>>

	* uni03BC (U+03BC): L<<79.0,558.0>--<80.0,162.0>>

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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 7 | 38 | 102 | 842 | 43 | 616 | 0 |
| 0% | 2% | 6% | 51% | 3% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
