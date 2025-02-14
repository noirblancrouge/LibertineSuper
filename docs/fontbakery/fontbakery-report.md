## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[18] Libertine-Super[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Validates subfamilyNameID and postScriptNameID for the default instance record <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-valid-default-instance-nameids">opentype/varfont/valid_default_instance_nameids</a></summary>
    <div>







* 🔥 **FAIL** <p>'Thin' instance has the same coordinates as the default instance; its postscript name should be 'LibertineSuper-VF', instead of 'LibertineSuper-Thin'.</p>
 [code: invalid-default-instance-postscript-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking if OS/2 usWeightClass matches fvar. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-weight-class-fvar">opentype/weight_class_fvar</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 usWeightClass is '400', but should match fvar default value '100.0'.</p>
 [code: bad-weight-class]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɛ, Ɛ, ɔ, Ɔ</td>
<td align="left">bm_Latn (Bambara) and tw_akuapem_Latn (Akuapem Twi)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɛ, Ɔ, ɔ, Ɛ</td>
<td align="left">dyu_Latn (Dyula)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɔ, Ɛ, ɛ, ɔ</td>
<td align="left">fat_Latn (Fanti)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ƴ, ɓ, Ɓ, ɗ, Ɗ, Ƴ</td>
<td align="left">ff_Latn (Fulah)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɓ, ƴ, Ƴ, ɗ, Ɗ, ƙ, Ƙ, ɓ</td>
<td align="left">ha_Latn (Hausa)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɛ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɛ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɵ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɵ</td>
<td align="left">ig_Latn (Igbo)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* 🔥 **FAIL** <p>Expected &quot;LibertineSuper[wght].ttf. Got Libertine-Super[wght].ttf.</p>
 [code: bad-filename]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Libertine Super Thin</td>
<td align="left">Libertine Super Thin</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Libertine Super Thin</td>
<td align="left">Libertine Super Thin</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left"><strong>LibertineSuper-VF</strong></td>
<td align="left"><strong>LibertineSuper-Thin</strong></td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left">Libertine Super</td>
<td align="left">Libertine Super</td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left">Thin</td>
<td align="left">Thin</td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-weightclass">googlefonts/weightclass</a></summary>
    <div>







* 🔥 **FAIL** <p>Best SubFamily name is 'Thin'. Expected OS/2 usWeightClass is 100, got 400.</p>
 [code: bad-value]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 11 in glyph 'n.blackCircled' has a kink between location wght=100 and location wght=900

- Contour 0 point 11 in glyph 'r.blackCircled.ss01' has a kink between location wght=100 and location wght=900

- Contour 0 point 31 in glyph 'u.blackCircled' has a kink between location wght=100 and location wght=900

- Contour 0 point 30 in glyph 'd.blackCircled.ss01' has a kink between location wght=100 and location wght=900

- Contour 0 point 11 in glyph 'p.blackCircled.ss01' has a kink between location wght=100 and location wght=900

- Contour 0 point 50 in glyph 'a.blackCircled.ss01' has a kink between location wght=100 and location wght=900

- Contour 0 point 44 in glyph 'a.blackCircled' has a kink between location wght=100 and location wght=900

- Contour 0 point 11 in glyph 'm.blackCircled' has a kink between location wght=100 and location wght=900
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- f_f</p>
<pre><code>- f_i
</code></pre>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* .notdef: B&lt;&lt;565.0,88.0&gt;-&lt;567.0,88.0&gt;-&lt;568.5,86.5&gt;&gt; has the same coordinates as a previous segment.

* .notdef: B&lt;&lt;568.5,86.5&gt;-&lt;570.0,85.0&gt;-&lt;570.0,83.0&gt;&gt; has the same coordinates as a previous segment.

* .notdef: B&lt;&lt;207.0,-64.0&gt;-&lt;205.0,-64.0&gt;-&lt;204.0,-63.0&gt;&gt; has the same coordinates as a previous segment.

* .notdef: B&lt;&lt;204.0,-63.0&gt;-&lt;203.0,-62.0&gt;-&lt;203.0,-59.0&gt;&gt; has the same coordinates as a previous segment.

* .notdef: L&lt;&lt;378.0,186.0&gt;--&lt;368.0,186.0&gt;&gt; has the same coordinates as a previous segment.

* B (U+0042): L&lt;&lt;71.0,343.0&gt;--&lt;71.0,361.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E04 (U+1E04): L&lt;&lt;71.0,343.0&gt;--&lt;71.0,361.0&gt;&gt; has the same coordinates as a previous segment.

* uni01C5 (U+01C5): B&lt;&lt;806.0,501.0&gt;-&lt;810.0,501.0&gt;-&lt;812.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* uni01C5 (U+01C5): B&lt;&lt;812.5,498.5&gt;-&lt;815.0,496.0&gt;-&lt;815.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* N (U+004E): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* N (U+004E): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* N (U+004E): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* N (U+004E): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni01CA (U+01CA): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni01CA (U+01CA): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni01CA (U+01CA): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni01CA (U+01CA): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Nacute (U+0143): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* Nacute (U+0143): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* Nacute (U+0143): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Nacute (U+0143): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Ncaron (U+0147): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* Ncaron (U+0147): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* Ncaron (U+0147): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Ncaron (U+0147): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni0145 (U+0145): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni0145 (U+0145): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni0145 (U+0145): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni0145 (U+0145): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E44 (U+1E44): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E44 (U+1E44): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E44 (U+1E44): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E44 (U+1E44): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E46 (U+1E46): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E46 (U+1E46): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E46 (U+1E46): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E46 (U+1E46): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni019D (U+019D): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni019D (U+019D): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni019D (U+019D): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni019D (U+019D): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni01CB (U+01CB): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni01CB (U+01CB): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni01CB (U+01CB): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni01CB (U+01CB): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E48 (U+1E48): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E48 (U+1E48): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E48 (U+1E48): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E48 (U+1E48): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Ntilde (U+00D1): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* Ntilde (U+00D1): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* Ntilde (U+00D1): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Ntilde (U+00D1): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Eng (U+014A): B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* Eng (U+014A): B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* Eng (U+014A): B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Eng (U+014A): B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E9E (U+1E9E): B&lt;&lt;197.0,343.0&gt;-&lt;194.0,343.0&gt;-&lt;191.5,345.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E9E (U+1E9E): B&lt;&lt;191.5,345.5&gt;-&lt;189.0,348.0&gt;-&lt;189.0,352.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E9E (U+1E9E): B&lt;&lt;63.0,651.0&gt;-&lt;63.0,654.0&gt;-&lt;65.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E9E (U+1E9E): B&lt;&lt;65.5,656.5&gt;-&lt;68.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* X (U+0058): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* X (U+0058): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Y (U+0059): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Y (U+0059): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Yacute (U+00DD): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Yacute (U+00DD): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Ycircumflex (U+0176): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Ycircumflex (U+0176): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Ydieresis (U+0178): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Ydieresis (U+0178): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E8E (U+1E8E): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E8E (U+1E8E): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EF4 (U+1EF4): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EF4 (U+1EF4): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Ygrave (U+1EF2): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Ygrave (U+1EF2): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EF6 (U+1EF6): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EF6 (U+1EF6): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni0232 (U+0232): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni0232 (U+0232): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1EF8 (U+1EF8): B&lt;&lt;26.0,651.0&gt;-&lt;26.0,654.0&gt;-&lt;28.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1EF8 (U+1EF8): B&lt;&lt;28.5,656.5&gt;-&lt;31.0,659.0&gt;-&lt;35.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni0145.loclMAH: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni0145.loclMAH: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni0145.loclMAH: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni0145.loclMAH: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* B.ss01: L&lt;&lt;71.0,343.0&gt;--&lt;71.0,361.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E04.ss01: L&lt;&lt;71.0,343.0&gt;--&lt;71.0,361.0&gt;&gt; has the same coordinates as a previous segment.

* uni01C5.ss01: B&lt;&lt;806.0,501.0&gt;-&lt;810.0,501.0&gt;-&lt;812.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* uni01C5.ss01: B&lt;&lt;812.5,498.5&gt;-&lt;815.0,496.0&gt;-&lt;815.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* N.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* N.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* N.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* N.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni01CA.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni01CA.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni01CA.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni01CA.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Nacute.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* Nacute.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* Nacute.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Nacute.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Ncaron.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* Ncaron.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* Ncaron.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Ncaron.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni0145.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni0145.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni0145.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni0145.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E44.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E44.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E44.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E44.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E46.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E46.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E46.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E46.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni019D.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni019D.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni019D.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni019D.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni01CB.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni01CB.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni01CB.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni01CB.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E48.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E48.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E48.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E48.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Ntilde.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* Ntilde.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* Ntilde.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Ntilde.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* Eng.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* Eng.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* Eng.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* Eng.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E9E.ss01: B&lt;&lt;197.0,343.0&gt;-&lt;194.0,343.0&gt;-&lt;191.5,345.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E9E.ss01: B&lt;&lt;191.5,345.5&gt;-&lt;189.0,348.0&gt;-&lt;189.0,352.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E9E.ss01: B&lt;&lt;63.0,651.0&gt;-&lt;63.0,654.0&gt;-&lt;65.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E9E.ss01: B&lt;&lt;65.5,656.5&gt;-&lt;68.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni0145.loclMAH.ss01: B&lt;&lt;335.0,9.0&gt;-&lt;335.0,5.0&gt;-&lt;332.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni0145.loclMAH.ss01: B&lt;&lt;332.5,2.5&gt;-&lt;330.0,0.0&gt;-&lt;326.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni0145.loclMAH.ss01: B&lt;&lt;62.0,651.0&gt;-&lt;62.0,654.0&gt;-&lt;64.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni0145.loclMAH.ss01: B&lt;&lt;64.5,656.5&gt;-&lt;67.0,659.0&gt;-&lt;71.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uni01C6 (U+01C6): B&lt;&lt;797.0,501.0&gt;-&lt;801.0,501.0&gt;-&lt;803.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* uni01C6 (U+01C6): B&lt;&lt;803.5,498.5&gt;-&lt;806.0,496.0&gt;-&lt;806.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* oe (U+0153): L&lt;&lt;392.0,278.0&gt;--&lt;392.0,224.0&gt;&gt; has the same coordinates as a previous segment.

* oe (U+0153): L&lt;&lt;374.0,224.0&gt;--&lt;374.0,278.0&gt;&gt; has the same coordinates as a previous segment.

* germandbls (U+00DF): B&lt;&lt;122.0,343.0&gt;-&lt;118.0,343.0&gt;-&lt;115.5,345.5&gt;&gt; has the same coordinates as a previous segment.

* germandbls (U+00DF): B&lt;&lt;115.5,345.5&gt;-&lt;113.0,348.0&gt;-&lt;113.0,352.0&gt;&gt; has the same coordinates as a previous segment.

* germandbls (U+00DF): B&lt;&lt;113.0,352.0&gt;-&lt;113.0,356.0&gt;-&lt;115.5,358.5&gt;&gt; has the same coordinates as a previous segment.

* germandbls (U+00DF): B&lt;&lt;115.5,358.5&gt;-&lt;118.0,361.0&gt;-&lt;122.0,361.0&gt;&gt; has the same coordinates as a previous segment.

* z (U+007A): B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* z (U+007A): B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* zacute (U+017A): B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* zacute (U+017A): B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* zcaron (U+017E): B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* zcaron (U+017E): B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* zdotaccent (U+017C): B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* zdotaccent (U+017C): B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E93 (U+1E93): B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E93 (U+1E93): B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* uni01C6.ss01: B&lt;&lt;797.0,501.0&gt;-&lt;801.0,501.0&gt;-&lt;803.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* uni01C6.ss01: B&lt;&lt;803.5,498.5&gt;-&lt;806.0,496.0&gt;-&lt;806.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* oe.ss01: L&lt;&lt;392.0,278.0&gt;--&lt;392.0,224.0&gt;&gt; has the same coordinates as a previous segment.

* oe.ss01: L&lt;&lt;374.0,224.0&gt;--&lt;374.0,278.0&gt;&gt; has the same coordinates as a previous segment.

* germandbls.ss01: B&lt;&lt;122.0,343.0&gt;-&lt;118.0,343.0&gt;-&lt;115.5,345.5&gt;&gt; has the same coordinates as a previous segment.

* germandbls.ss01: B&lt;&lt;115.5,345.5&gt;-&lt;113.0,348.0&gt;-&lt;113.0,352.0&gt;&gt; has the same coordinates as a previous segment.

* germandbls.ss01: B&lt;&lt;113.0,352.0&gt;-&lt;113.0,356.0&gt;-&lt;115.5,358.5&gt;&gt; has the same coordinates as a previous segment.

* germandbls.ss01: B&lt;&lt;115.5,358.5&gt;-&lt;118.0,361.0&gt;-&lt;122.0,361.0&gt;&gt; has the same coordinates as a previous segment.

* z.ss01: B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* z.ss01: B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* zacute.ss01: B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* zacute.ss01: B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* zcaron.ss01: B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* zcaron.ss01: B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* zdotaccent.ss01: B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* zdotaccent.ss01: B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* uni1E93.ss01: B&lt;&lt;353.0,501.0&gt;-&lt;357.0,501.0&gt;-&lt;359.5,498.5&gt;&gt; has the same coordinates as a previous segment.

* uni1E93.ss01: B&lt;&lt;359.5,498.5&gt;-&lt;362.0,496.0&gt;-&lt;362.0,493.0&gt;&gt; has the same coordinates as a previous segment.

* s_t (U+FB06): B&lt;&lt;31.0,67.0&gt;-&lt;31.0,70.0&gt;-&lt;33.0,73.0&gt;&gt; has the same coordinates as a previous segment.

* uni2463 (U+2463): B&lt;&lt;379.0,238.0&gt;-&lt;374.0,238.0&gt;-&lt;371.0,241.0&gt;&gt; has the same coordinates as a previous segment.

* uni2463 (U+2463): B&lt;&lt;371.0,241.0&gt;-&lt;368.0,244.0&gt;-&lt;368.0,249.0&gt;&gt; has the same coordinates as a previous segment.

* uni2463.ss01: B&lt;&lt;379.0,238.0&gt;-&lt;374.0,238.0&gt;-&lt;371.0,241.0&gt;&gt; has the same coordinates as a previous segment.

* uni2463.ss01: B&lt;&lt;371.0,241.0&gt;-&lt;368.0,244.0&gt;-&lt;368.0,249.0&gt;&gt; has the same coordinates as a previous segment.

* braceleft (U+007B): L&lt;&lt;59.0,297.0&gt;--&lt;52.0,297.0&gt;&gt; has the same coordinates as a previous segment.

* braceleft (U+007B): B&lt;&lt;52.0,297.0&gt;-&lt;48.0,297.0&gt;-&lt;45.5,299.5&gt;&gt; has the same coordinates as a previous segment.

* braceleft (U+007B): B&lt;&lt;45.5,299.5&gt;-&lt;43.0,302.0&gt;-&lt;43.0,305.0&gt;&gt; has the same coordinates as a previous segment.

* braceleft (U+007B): B&lt;&lt;43.0,305.0&gt;-&lt;43.0,309.0&gt;-&lt;45.5,311.5&gt;&gt; has the same coordinates as a previous segment.

* braceleft (U+007B): B&lt;&lt;45.5,311.5&gt;-&lt;48.0,314.0&gt;-&lt;52.0,314.0&gt;&gt; has the same coordinates as a previous segment.

* braceleft (U+007B): L&lt;&lt;52.0,314.0&gt;--&lt;59.0,314.0&gt;&gt; has the same coordinates as a previous segment.

* braceright (U+007D): L&lt;&lt;184.0,314.0&gt;--&lt;191.0,314.0&gt;&gt; has the same coordinates as a previous segment.

* braceright (U+007D): B&lt;&lt;191.0,314.0&gt;-&lt;195.0,314.0&gt;-&lt;197.0,311.5&gt;&gt; has the same coordinates as a previous segment.

* braceright (U+007D): B&lt;&lt;197.0,311.5&gt;-&lt;199.0,309.0&gt;-&lt;199.0,305.0&gt;&gt; has the same coordinates as a previous segment.

* braceright (U+007D): B&lt;&lt;199.0,305.0&gt;-&lt;199.0,302.0&gt;-&lt;197.0,299.5&gt;&gt; has the same coordinates as a previous segment.

* braceright (U+007D): B&lt;&lt;197.0,299.5&gt;-&lt;195.0,297.0&gt;-&lt;191.0,297.0&gt;&gt; has the same coordinates as a previous segment.

* braceright (U+007D): L&lt;&lt;191.0,297.0&gt;--&lt;184.0,297.0&gt;&gt; has the same coordinates as a previous segment.

* uni0E3F (U+0E3F): L&lt;&lt;71.0,343.0&gt;--&lt;71.0,361.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;397.0,353.0&gt;-&lt;340.0,373.0&gt;-&lt;293.0,373.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;293.0,373.0&gt;-&lt;272.0,373.0&gt;-&lt;248.5,372.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;248.5,372.5&gt;-&lt;225.0,372.0&gt;-&lt;207.0,372.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): L&lt;&lt;207.0,372.0&gt;--&lt;179.0,372.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;179.0,372.0&gt;-&lt;169.0,372.0&gt;-&lt;144.0,374.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;144.0,374.0&gt;-&lt;119.0,376.0&gt;-&lt;99.0,378.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;99.0,378.0&gt;-&lt;57.0,383.0&gt;-&lt;51.0,401.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;51.0,401.0&gt;-&lt;37.0,402.0&gt;-&lt;30.5,403.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;30.5,403.0&gt;-&lt;24.0,404.0&gt;-&lt;20.0,406.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;20.0,406.0&gt;-&lt;20.0,411.0&gt;-&lt;20.5,415.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;20.5,415.0&gt;-&lt;21.0,419.0&gt;-&lt;23.0,422.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;23.0,422.0&gt;-&lt;29.0,431.0&gt;-&lt;44.5,433.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;44.5,433.0&gt;-&lt;60.0,435.0&gt;-&lt;76.5,434.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;76.5,434.0&gt;-&lt;93.0,433.0&gt;-&lt;102.0,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;102.0,432.0&gt;-&lt;108.0,432.0&gt;-&lt;108.0,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;108.0,432.0&gt;-&lt;110.0,432.0&gt;-&lt;121.5,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;121.5,432.0&gt;-&lt;133.0,432.0&gt;-&lt;147.0,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): L&lt;&lt;147.0,432.0&gt;--&lt;172.0,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): L&lt;&lt;172.0,432.0&gt;--&lt;251.0,441.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;251.0,441.0&gt;-&lt;266.0,443.0&gt;-&lt;285.0,443.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;285.0,443.5&gt;-&lt;304.0,444.0&gt;-&lt;320.0,443.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;320.0,443.5&gt;-&lt;336.0,443.0&gt;-&lt;339.0,443.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;339.0,443.0&gt;-&lt;341.0,443.0&gt;-&lt;364.0,446.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;364.0,446.0&gt;-&lt;385.0,449.0&gt;-&lt;414.5,452.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;414.5,452.5&gt;-&lt;444.0,456.0&gt;-&lt;466.0,456.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;466.0,456.0&gt;-&lt;475.0,456.0&gt;-&lt;498.5,449.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;498.5,449.0&gt;-&lt;522.0,442.0&gt;-&lt;552.5,431.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;552.5,431.0&gt;-&lt;583.0,420.0&gt;-&lt;613.5,408.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;613.5,408.0&gt;-&lt;644.0,396.0&gt;-&lt;667.0,386.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;667.0,386.0&gt;-&lt;713.0,366.0&gt;-&lt;737.0,360.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;737.0,360.0&gt;-&lt;761.0,354.0&gt;-&lt;772.0,352.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;772.0,352.0&gt;-&lt;778.0,352.0&gt;-&lt;802.0,353.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;802.0,353.5&gt;-&lt;826.0,355.0&gt;-&lt;857.0,357.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;857.0,357.5&gt;-&lt;888.0,360.0&gt;-&lt;915.0,363.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;915.0,363.0&gt;-&lt;942.0,366.0&gt;-&lt;953.0,368.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;953.0,368.0&gt;-&lt;965.0,370.0&gt;-&lt;975.0,351.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;975.0,351.0&gt;-&lt;985.0,332.0&gt;-&lt;990.0,304.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;990.0,304.0&gt;-&lt;995.0,276.0&gt;-&lt;993.5,247.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;993.5,247.0&gt;-&lt;992.0,218.0&gt;-&lt;982.5,198.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;982.5,198.5&gt;-&lt;973.0,179.0&gt;-&lt;953.0,179.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;953.0,179.0&gt;-&lt;942.0,179.0&gt;-&lt;920.0,178.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;920.0,178.5&gt;-&lt;898.0,178.0&gt;-&lt;876.5,177.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;876.5,177.0&gt;-&lt;855.0,176.0&gt;-&lt;844.0,173.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;844.0,173.0&gt;-&lt;837.0,172.0&gt;-&lt;830.0,168.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;830.0,168.5&gt;-&lt;823.0,165.0&gt;-&lt;815.0,160.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;815.0,160.0&gt;-&lt;806.0,156.0&gt;-&lt;797.0,151.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;797.0,151.0&gt;-&lt;788.0,146.0&gt;-&lt;776.0,143.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;776.0,143.0&gt;-&lt;765.0,140.0&gt;-&lt;743.5,141.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;743.5,141.5&gt;-&lt;722.0,143.0&gt;-&lt;698.0,146.5&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;698.0,146.5&gt;-&lt;674.0,150.0&gt;-&lt;656.0,153.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;656.0,153.0&gt;-&lt;638.0,141.0&gt;-&lt;629.0,139.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;629.0,139.0&gt;-&lt;626.0,133.0&gt;-&lt;617.0,123.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;617.0,123.0&gt;-&lt;608.0,113.0&gt;-&lt;598.0,105.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;598.0,105.0&gt;-&lt;588.0,97.0&gt;-&lt;583.0,97.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;583.0,97.0&gt;-&lt;581.0,95.0&gt;-&lt;577.0,92.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;577.0,92.0&gt;-&lt;573.0,89.0&gt;-&lt;571.0,88.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;571.0,88.0&gt;-&lt;567.0,87.0&gt;-&lt;555.5,85.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;555.5,85.0&gt;-&lt;544.0,83.0&gt;-&lt;531.0,82.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;531.0,82.0&gt;-&lt;519.0,80.0&gt;-&lt;508.5,78.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;508.5,78.0&gt;-&lt;498.0,76.0&gt;-&lt;495.0,75.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;495.0,75.0&gt;-&lt;491.0,74.0&gt;-&lt;478.0,74.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;478.0,74.0&gt;-&lt;465.0,74.0&gt;-&lt;455.0,74.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;447.0,74.0&gt;-&lt;435.0,74.0&gt;-&lt;434.0,86.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;434.0,86.0&gt;-&lt;433.0,98.0&gt;-&lt;434.0,104.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): L&lt;&lt;434.0,104.0&gt;--&lt;434.0,113.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): L&lt;&lt;434.0,113.0&gt;--&lt;399.0,114.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;399.0,114.0&gt;-&lt;391.0,115.0&gt;-&lt;379.5,121.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;379.5,121.0&gt;-&lt;368.0,127.0&gt;-&lt;366.0,137.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;366.0,137.0&gt;-&lt;366.0,143.0&gt;-&lt;368.0,154.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;368.0,154.0&gt;-&lt;350.0,164.0&gt;-&lt;348.5,176.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;348.5,176.0&gt;-&lt;347.0,188.0&gt;-&lt;348.0,196.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;348.0,196.0&gt;-&lt;349.0,201.0&gt;-&lt;349.0,202.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;349.0,202.0&gt;-&lt;349.0,206.0&gt;-&lt;357.0,232.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;357.0,232.0&gt;-&lt;365.0,258.0&gt;-&lt;376.5,292.0&gt;&gt; has the same coordinates as a previous segment.

* uni261C (U+261C): B&lt;&lt;376.5,292.0&gt;-&lt;388.0,326.0&gt;-&lt;397.0,353.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;153.0,512.0&gt;-&lt;180.0,521.0&gt;-&lt;213.5,532.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;213.5,532.5&gt;-&lt;247.0,544.0&gt;-&lt;273.0,552.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;273.0,552.5&gt;-&lt;299.0,561.0&gt;-&lt;303.0,561.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;303.0,561.0&gt;-&lt;305.0,561.0&gt;-&lt;309.0,561.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;309.0,561.0&gt;-&lt;317.0,563.0&gt;-&lt;329.0,561.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;329.0,561.5&gt;-&lt;341.0,560.0&gt;-&lt;352.0,542.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;352.0,542.0&gt;-&lt;363.0,543.0&gt;-&lt;368.0,543.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;368.0,543.0&gt;-&lt;379.0,541.0&gt;-&lt;385.0,529.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;385.0,529.5&gt;-&lt;391.0,518.0&gt;-&lt;391.0,510.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): L&lt;&lt;391.0,510.0&gt;--&lt;393.0,475.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): L&lt;&lt;393.0,475.0&gt;--&lt;402.0,475.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;402.0,475.0&gt;-&lt;408.0,476.0&gt;-&lt;420.0,475.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;420.0,475.0&gt;-&lt;432.0,474.0&gt;-&lt;432.0,462.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;432.0,454.0&gt;-&lt;432.0,444.0&gt;-&lt;432.0,431.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;432.0,431.0&gt;-&lt;432.0,418.0&gt;-&lt;430.0,414.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;430.0,414.0&gt;-&lt;429.0,412.0&gt;-&lt;427.5,401.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;427.5,401.0&gt;-&lt;426.0,390.0&gt;-&lt;424.0,378.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;424.0,378.0&gt;-&lt;422.0,365.0&gt;-&lt;420.0,353.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;420.0,353.5&gt;-&lt;418.0,342.0&gt;-&lt;417.0,338.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;417.0,338.0&gt;-&lt;417.0,336.0&gt;-&lt;413.0,332.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;413.0,332.0&gt;-&lt;410.0,328.0&gt;-&lt;409.0,326.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;409.0,326.0&gt;-&lt;408.0,321.0&gt;-&lt;400.5,311.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;400.5,311.0&gt;-&lt;393.0,301.0&gt;-&lt;383.0,292.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;383.0,292.0&gt;-&lt;373.0,283.0&gt;-&lt;367.0,280.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;367.0,280.0&gt;-&lt;364.0,271.0&gt;-&lt;352.0,253.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;352.0,253.0&gt;-&lt;356.0,235.0&gt;-&lt;359.5,211.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;359.5,211.0&gt;-&lt;363.0,187.0&gt;-&lt;364.5,165.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;364.5,165.5&gt;-&lt;366.0,144.0&gt;-&lt;362.0,133.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;362.0,133.0&gt;-&lt;359.0,122.0&gt;-&lt;354.5,112.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;354.5,112.5&gt;-&lt;350.0,103.0&gt;-&lt;345.0,94.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;345.0,94.0&gt;-&lt;341.0,87.0&gt;-&lt;337.5,79.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;337.5,79.5&gt;-&lt;334.0,72.0&gt;-&lt;332.0,65.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;332.0,65.0&gt;-&lt;330.0,54.0&gt;-&lt;329.0,32.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;329.0,32.5&gt;-&lt;328.0,11.0&gt;-&lt;327.5,-10.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;327.5,-10.5&gt;-&lt;327.0,-32.0&gt;-&lt;327.0,-44.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;327.0,-44.0&gt;-&lt;327.0,-64.0&gt;-&lt;307.5,-73.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;307.5,-73.5&gt;-&lt;288.0,-83.0&gt;-&lt;259.0,-84.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;259.0,-84.5&gt;-&lt;230.0,-86.0&gt;-&lt;201.5,-81.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;201.5,-81.0&gt;-&lt;173.0,-76.0&gt;-&lt;154.5,-66.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;154.5,-66.0&gt;-&lt;136.0,-56.0&gt;-&lt;138.0,-44.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;138.0,-44.0&gt;-&lt;140.0,-33.0&gt;-&lt;142.5,-6.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;142.5,-6.0&gt;-&lt;145.0,21.0&gt;-&lt;148.0,52.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;148.0,52.0&gt;-&lt;151.0,83.0&gt;-&lt;152.5,107.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;152.5,107.0&gt;-&lt;154.0,131.0&gt;-&lt;153.0,137.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;153.0,137.0&gt;-&lt;152.0,148.0&gt;-&lt;146.0,172.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;146.0,172.0&gt;-&lt;140.0,196.0&gt;-&lt;120.0,242.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;120.0,242.0&gt;-&lt;109.0,266.0&gt;-&lt;97.0,296.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;97.0,296.5&gt;-&lt;85.0,327.0&gt;-&lt;74.5,357.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;74.5,357.0&gt;-&lt;64.0,387.0&gt;-&lt;57.0,410.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;57.0,410.5&gt;-&lt;50.0,434.0&gt;-&lt;50.0,443.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;50.0,443.0&gt;-&lt;50.0,466.0&gt;-&lt;53.5,495.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;53.5,495.0&gt;-&lt;57.0,524.0&gt;-&lt;59.0,545.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;59.0,545.0&gt;-&lt;63.0,568.0&gt;-&lt;62.0,570.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;62.0,570.0&gt;-&lt;62.0,574.0&gt;-&lt;62.0,589.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;62.0,589.5&gt;-&lt;62.0,605.0&gt;-&lt;62.5,624.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;62.5,624.0&gt;-&lt;63.0,643.0&gt;-&lt;64.0,658.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): L&lt;&lt;64.0,658.0&gt;--&lt;74.0,737.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): L&lt;&lt;74.0,737.0&gt;--&lt;74.0,762.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;74.0,762.0&gt;-&lt;74.0,776.0&gt;-&lt;74.0,787.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;74.0,787.5&gt;-&lt;74.0,799.0&gt;-&lt;74.0,801.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;74.0,801.0&gt;-&lt;74.0,801.0&gt;-&lt;73.0,807.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;73.0,807.0&gt;-&lt;72.0,816.0&gt;-&lt;71.5,832.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;71.5,832.5&gt;-&lt;71.0,849.0&gt;-&lt;73.0,864.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;73.0,864.5&gt;-&lt;75.0,880.0&gt;-&lt;84.0,886.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;84.0,886.0&gt;-&lt;87.0,888.0&gt;-&lt;91.0,888.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;91.0,888.5&gt;-&lt;95.0,889.0&gt;-&lt;99.0,889.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;99.0,889.0&gt;-&lt;101.0,885.0&gt;-&lt;102.0,879.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;102.0,879.0&gt;-&lt;103.0,873.0&gt;-&lt;104.0,858.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;104.0,858.0&gt;-&lt;123.0,852.0&gt;-&lt;128.0,811.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;128.0,811.0&gt;-&lt;130.0,790.0&gt;-&lt;132.0,765.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;132.0,765.0&gt;-&lt;134.0,740.0&gt;-&lt;134.0,730.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): L&lt;&lt;134.0,730.0&gt;--&lt;134.0,702.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;134.0,702.0&gt;-&lt;133.0,684.0&gt;-&lt;133.0,660.5&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;133.0,660.5&gt;-&lt;133.0,637.0&gt;-&lt;133.0,616.0&gt;&gt; has the same coordinates as a previous segment.

* uni261D (U+261D): B&lt;&lt;133.0,616.0&gt;-&lt;133.0,569.0&gt;-&lt;153.0,512.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;617.0,353.0&gt;-&lt;626.0,326.0&gt;-&lt;637.5,292.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;637.5,292.0&gt;-&lt;649.0,258.0&gt;-&lt;657.5,232.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;657.5,232.0&gt;-&lt;666.0,206.0&gt;-&lt;666.0,202.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;666.0,202.0&gt;-&lt;666.0,201.0&gt;-&lt;666.0,196.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;666.0,196.0&gt;-&lt;668.0,188.0&gt;-&lt;666.5,176.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;666.5,176.0&gt;-&lt;665.0,164.0&gt;-&lt;647.0,154.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;647.0,154.0&gt;-&lt;648.0,143.0&gt;-&lt;648.0,137.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;648.0,137.0&gt;-&lt;646.0,127.0&gt;-&lt;634.5,121.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;634.5,121.0&gt;-&lt;623.0,115.0&gt;-&lt;615.0,114.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): L&lt;&lt;615.0,114.0&gt;--&lt;580.0,113.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): L&lt;&lt;580.0,113.0&gt;--&lt;580.0,104.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;580.0,104.0&gt;-&lt;581.0,98.0&gt;-&lt;580.0,86.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;580.0,86.0&gt;-&lt;579.0,74.0&gt;-&lt;567.0,74.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;559.0,74.0&gt;-&lt;549.0,74.0&gt;-&lt;536.0,74.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;536.0,74.0&gt;-&lt;523.0,74.0&gt;-&lt;519.0,75.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;519.0,75.0&gt;-&lt;517.0,76.0&gt;-&lt;506.0,78.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;506.0,78.0&gt;-&lt;495.0,80.0&gt;-&lt;483.0,82.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;483.0,82.0&gt;-&lt;470.0,83.0&gt;-&lt;458.5,85.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;458.5,85.0&gt;-&lt;447.0,87.0&gt;-&lt;443.0,88.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;443.0,88.0&gt;-&lt;441.0,89.0&gt;-&lt;437.0,92.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;437.0,92.0&gt;-&lt;433.0,95.0&gt;-&lt;431.0,97.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;431.0,97.0&gt;-&lt;426.0,97.0&gt;-&lt;416.0,105.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;416.0,105.0&gt;-&lt;406.0,113.0&gt;-&lt;397.0,123.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;397.0,123.0&gt;-&lt;388.0,133.0&gt;-&lt;385.0,139.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;385.0,139.0&gt;-&lt;376.0,141.0&gt;-&lt;358.0,153.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;358.0,153.0&gt;-&lt;340.0,150.0&gt;-&lt;316.0,146.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;316.0,146.5&gt;-&lt;292.0,143.0&gt;-&lt;270.5,141.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;270.5,141.5&gt;-&lt;249.0,140.0&gt;-&lt;238.0,143.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;238.0,143.0&gt;-&lt;227.0,146.0&gt;-&lt;217.5,151.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;217.5,151.0&gt;-&lt;208.0,156.0&gt;-&lt;199.0,160.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;199.0,160.0&gt;-&lt;192.0,165.0&gt;-&lt;184.5,168.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;184.5,168.5&gt;-&lt;177.0,172.0&gt;-&lt;170.0,173.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;170.0,173.0&gt;-&lt;159.0,176.0&gt;-&lt;137.5,177.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;137.5,177.0&gt;-&lt;116.0,178.0&gt;-&lt;94.5,178.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;94.5,178.5&gt;-&lt;73.0,179.0&gt;-&lt;61.0,179.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;61.0,179.0&gt;-&lt;41.0,179.0&gt;-&lt;31.5,198.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;31.5,198.5&gt;-&lt;22.0,218.0&gt;-&lt;20.5,247.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;20.5,247.0&gt;-&lt;19.0,276.0&gt;-&lt;24.0,304.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;24.0,304.0&gt;-&lt;29.0,332.0&gt;-&lt;39.0,351.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;39.0,351.0&gt;-&lt;49.0,370.0&gt;-&lt;61.0,368.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;61.0,368.0&gt;-&lt;72.0,366.0&gt;-&lt;99.0,363.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;99.0,363.0&gt;-&lt;126.0,360.0&gt;-&lt;157.0,357.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;157.0,357.5&gt;-&lt;188.0,355.0&gt;-&lt;212.0,353.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;212.0,353.5&gt;-&lt;236.0,352.0&gt;-&lt;242.0,352.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;242.0,352.0&gt;-&lt;253.0,354.0&gt;-&lt;277.0,360.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;277.0,360.0&gt;-&lt;301.0,366.0&gt;-&lt;347.0,386.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;347.0,386.0&gt;-&lt;371.0,396.0&gt;-&lt;401.5,408.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;401.5,408.0&gt;-&lt;432.0,420.0&gt;-&lt;462.0,431.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;462.0,431.0&gt;-&lt;492.0,442.0&gt;-&lt;515.5,449.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;515.5,449.0&gt;-&lt;539.0,456.0&gt;-&lt;548.0,456.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;548.0,456.0&gt;-&lt;571.0,456.0&gt;-&lt;600.0,452.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;600.0,452.5&gt;-&lt;629.0,449.0&gt;-&lt;650.0,446.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;650.0,446.0&gt;-&lt;673.0,443.0&gt;-&lt;675.0,443.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;675.0,443.0&gt;-&lt;679.0,443.0&gt;-&lt;694.5,443.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;694.5,443.5&gt;-&lt;710.0,444.0&gt;-&lt;729.0,443.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;729.0,443.5&gt;-&lt;748.0,443.0&gt;-&lt;763.0,441.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): L&lt;&lt;763.0,441.0&gt;--&lt;842.0,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): L&lt;&lt;842.0,432.0&gt;--&lt;867.0,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;867.0,432.0&gt;-&lt;881.0,432.0&gt;-&lt;892.5,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;892.5,432.0&gt;-&lt;904.0,432.0&gt;-&lt;906.0,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;906.0,432.0&gt;-&lt;906.0,432.0&gt;-&lt;912.0,432.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;912.0,432.0&gt;-&lt;921.0,433.0&gt;-&lt;937.5,434.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;937.5,434.0&gt;-&lt;954.0,435.0&gt;-&lt;969.5,433.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;969.5,433.0&gt;-&lt;985.0,431.0&gt;-&lt;991.0,422.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;991.0,422.0&gt;-&lt;993.0,419.0&gt;-&lt;993.5,415.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;993.5,415.0&gt;-&lt;994.0,411.0&gt;-&lt;994.0,406.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;994.0,406.0&gt;-&lt;990.0,404.0&gt;-&lt;984.0,403.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;984.0,403.0&gt;-&lt;978.0,402.0&gt;-&lt;963.0,401.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;963.0,401.0&gt;-&lt;957.0,383.0&gt;-&lt;916.0,378.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;916.0,378.0&gt;-&lt;895.0,376.0&gt;-&lt;870.0,374.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;870.0,374.0&gt;-&lt;845.0,372.0&gt;-&lt;835.0,372.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): L&lt;&lt;835.0,372.0&gt;--&lt;807.0,372.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;807.0,372.0&gt;-&lt;789.0,372.0&gt;-&lt;765.5,372.5&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;765.5,372.5&gt;-&lt;742.0,373.0&gt;-&lt;721.0,373.0&gt;&gt; has the same coordinates as a previous segment.

* uni261E (U+261E): B&lt;&lt;721.0,373.0&gt;-&lt;674.0,373.0&gt;-&lt;617.0,353.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;329.0,221.0&gt;-&lt;302.0,212.0&gt;-&lt;268.5,200.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;268.5,200.5&gt;-&lt;235.0,189.0&gt;-&lt;209.0,180.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;209.0,180.5&gt;-&lt;183.0,172.0&gt;-&lt;179.0,172.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;179.0,172.0&gt;-&lt;177.0,172.0&gt;-&lt;173.0,172.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;173.0,172.0&gt;-&lt;164.0,170.0&gt;-&lt;152.5,171.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;152.5,171.5&gt;-&lt;141.0,173.0&gt;-&lt;130.0,191.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;130.0,191.0&gt;-&lt;119.0,190.0&gt;-&lt;114.0,190.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;114.0,190.0&gt;-&lt;103.0,192.0&gt;-&lt;97.0,203.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;97.0,203.5&gt;-&lt;91.0,215.0&gt;-&lt;91.0,223.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): L&lt;&lt;91.0,223.0&gt;--&lt;89.0,258.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): L&lt;&lt;89.0,258.0&gt;--&lt;80.0,258.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;80.0,258.0&gt;-&lt;74.0,257.0&gt;-&lt;62.0,258.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;62.0,258.0&gt;-&lt;50.0,259.0&gt;-&lt;50.0,271.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;50.0,279.0&gt;-&lt;50.0,289.0&gt;-&lt;50.0,302.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;50.0,302.0&gt;-&lt;50.0,315.0&gt;-&lt;52.0,319.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;52.0,319.0&gt;-&lt;52.0,321.0&gt;-&lt;54.0,332.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;54.0,332.0&gt;-&lt;56.0,343.0&gt;-&lt;58.0,355.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;58.0,355.0&gt;-&lt;60.0,368.0&gt;-&lt;61.5,379.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;61.5,379.5&gt;-&lt;63.0,391.0&gt;-&lt;64.0,395.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;64.0,395.0&gt;-&lt;65.0,397.0&gt;-&lt;69.0,401.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;69.0,401.0&gt;-&lt;72.0,405.0&gt;-&lt;73.0,407.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;73.0,407.0&gt;-&lt;74.0,412.0&gt;-&lt;81.5,422.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;81.5,422.0&gt;-&lt;89.0,432.0&gt;-&lt;99.0,441.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;99.0,441.0&gt;-&lt;109.0,450.0&gt;-&lt;115.0,453.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;115.0,453.0&gt;-&lt;118.0,462.0&gt;-&lt;129.0,480.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;129.0,480.0&gt;-&lt;126.0,498.0&gt;-&lt;122.5,522.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;122.5,522.0&gt;-&lt;119.0,546.0&gt;-&lt;117.5,567.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;117.5,567.5&gt;-&lt;116.0,589.0&gt;-&lt;119.0,600.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;119.0,600.0&gt;-&lt;123.0,611.0&gt;-&lt;127.5,620.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;127.5,620.5&gt;-&lt;132.0,630.0&gt;-&lt;137.0,639.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;137.0,639.0&gt;-&lt;141.0,646.0&gt;-&lt;144.5,653.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;144.5,653.5&gt;-&lt;148.0,661.0&gt;-&lt;150.0,668.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;150.0,668.0&gt;-&lt;152.0,679.0&gt;-&lt;153.0,700.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;153.0,700.5&gt;-&lt;154.0,722.0&gt;-&lt;154.5,743.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;154.5,743.5&gt;-&lt;155.0,765.0&gt;-&lt;155.0,777.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;155.0,777.0&gt;-&lt;155.0,797.0&gt;-&lt;174.5,806.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;174.5,806.5&gt;-&lt;194.0,816.0&gt;-&lt;223.0,817.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;223.0,817.5&gt;-&lt;252.0,819.0&gt;-&lt;280.5,814.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;280.5,814.0&gt;-&lt;309.0,809.0&gt;-&lt;327.5,799.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;327.5,799.0&gt;-&lt;346.0,789.0&gt;-&lt;344.0,777.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;344.0,777.0&gt;-&lt;342.0,766.0&gt;-&lt;339.5,739.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;339.5,739.0&gt;-&lt;337.0,712.0&gt;-&lt;334.0,681.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;334.0,681.0&gt;-&lt;331.0,650.0&gt;-&lt;329.5,626.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;329.5,626.0&gt;-&lt;328.0,602.0&gt;-&lt;329.0,596.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;329.0,596.0&gt;-&lt;330.0,585.0&gt;-&lt;336.0,561.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;336.0,561.0&gt;-&lt;342.0,537.0&gt;-&lt;362.0,491.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;362.0,491.0&gt;-&lt;372.0,467.0&gt;-&lt;384.0,436.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;384.0,436.5&gt;-&lt;396.0,406.0&gt;-&lt;407.0,376.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;407.0,376.0&gt;-&lt;418.0,346.0&gt;-&lt;425.0,322.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;425.0,322.5&gt;-&lt;432.0,299.0&gt;-&lt;432.0,290.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;432.0,290.0&gt;-&lt;432.0,267.0&gt;-&lt;428.5,238.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;428.5,238.0&gt;-&lt;425.0,209.0&gt;-&lt;422.0,188.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;422.0,188.0&gt;-&lt;419.0,165.0&gt;-&lt;420.0,163.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;420.0,163.0&gt;-&lt;420.0,159.0&gt;-&lt;420.0,143.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;420.0,143.5&gt;-&lt;420.0,128.0&gt;-&lt;419.5,109.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;419.5,109.0&gt;-&lt;419.0,90.0&gt;-&lt;418.0,75.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): L&lt;&lt;418.0,75.0&gt;--&lt;408.0,-4.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): L&lt;&lt;408.0,-4.0&gt;--&lt;408.0,-29.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;408.0,-29.0&gt;-&lt;408.0,-43.0&gt;-&lt;408.0,-54.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;408.0,-54.5&gt;-&lt;408.0,-66.0&gt;-&lt;408.0,-68.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;408.0,-68.0&gt;-&lt;408.0,-68.0&gt;-&lt;409.0,-74.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;409.0,-74.0&gt;-&lt;409.0,-83.0&gt;-&lt;410.0,-99.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;410.0,-99.5&gt;-&lt;411.0,-116.0&gt;-&lt;409.0,-131.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;409.0,-131.5&gt;-&lt;407.0,-147.0&gt;-&lt;398.0,-153.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;398.0,-153.0&gt;-&lt;395.0,-155.0&gt;-&lt;391.0,-155.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;391.0,-155.5&gt;-&lt;387.0,-156.0&gt;-&lt;383.0,-156.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;383.0,-156.0&gt;-&lt;381.0,-152.0&gt;-&lt;379.5,-146.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;379.5,-146.0&gt;-&lt;378.0,-140.0&gt;-&lt;377.0,-125.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;377.0,-125.0&gt;-&lt;359.0,-119.0&gt;-&lt;354.0,-78.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;354.0,-78.0&gt;-&lt;352.0,-57.0&gt;-&lt;350.0,-32.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;350.0,-32.0&gt;-&lt;348.0,-7.0&gt;-&lt;348.0,3.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): L&lt;&lt;348.0,3.0&gt;--&lt;348.0,31.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;348.0,31.0&gt;-&lt;348.0,49.0&gt;-&lt;348.5,72.5&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;348.5,72.5&gt;-&lt;349.0,96.0&gt;-&lt;349.0,117.0&gt;&gt; has the same coordinates as a previous segment.

* uni261F (U+261F): B&lt;&lt;349.0,117.0&gt;-&lt;349.0,164.0&gt;-&lt;329.0,221.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;442.0,222.0&gt;--&lt;624.0,112.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;334.0,221.0&gt;--&lt;388.0,28.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;260.0,295.0&gt;--&lt;149.0,109.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;262.0,401.0&gt;--&lt;56.0,348.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;333.0,478.0&gt;--&lt;152.0,584.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;442.0,478.0&gt;--&lt;388.0,669.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;516.0,402.0&gt;--&lt;617.0,577.0&gt;&gt; has the same coordinates as a previous segment.

* uni2735 (U+2735): L&lt;&lt;517.0,296.0&gt;--&lt;720.0,348.0&gt;&gt; has the same coordinates as a previous segment.

* trademark (U+2122): B&lt;&lt;455.0,673.0&gt;-&lt;459.0,673.0&gt;-&lt;461.0,670.5&gt;&gt; has the same coordinates as a previous segment.

* trademark (U+2122): B&lt;&lt;461.0,670.5&gt;-&lt;463.0,668.0&gt;-&lt;463.0,664.0&gt;&gt; has the same coordinates as a previous segment.

* uni2116 (U+2116): B&lt;&lt;334.0,9.0&gt;-&lt;334.0,5.0&gt;-&lt;331.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni2116 (U+2116): B&lt;&lt;331.5,2.5&gt;-&lt;329.0,0.0&gt;-&lt;325.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni2116 (U+2116): B&lt;&lt;61.0,651.0&gt;-&lt;61.0,654.0&gt;-&lt;63.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni2116 (U+2116): B&lt;&lt;63.5,656.5&gt;-&lt;66.0,659.0&gt;-&lt;70.0,659.0&gt;&gt; has the same coordinates as a previous segment.

* uniFFFC (U+FFFC): L&lt;&lt;275.0,382.0&gt;--&lt;275.0,388.0&gt;&gt; has the same coordinates as a previous segment.

* uni24B7 (U+24B7): L&lt;&lt;385.0,333.0&gt;--&lt;385.0,356.0&gt;&gt; has the same coordinates as a previous segment.

* uni24C2 (U+24C2): B&lt;&lt;355.0,588.0&gt;-&lt;355.0,593.0&gt;-&lt;358.0,596.5&gt;&gt; has the same coordinates as a previous segment.

* uni24C2 (U+24C2): B&lt;&lt;358.0,596.5&gt;-&lt;361.0,600.0&gt;-&lt;366.0,600.0&gt;&gt; has the same coordinates as a previous segment.

* uni24CD (U+24CD): B&lt;&lt;352.0,588.0&gt;-&lt;352.0,593.0&gt;-&lt;355.5,596.5&gt;&gt; has the same coordinates as a previous segment.

* uni24CD (U+24CD): B&lt;&lt;355.5,596.5&gt;-&lt;359.0,600.0&gt;-&lt;364.0,600.0&gt;&gt; has the same coordinates as a previous segment.

* uni24CE (U+24CE): B&lt;&lt;353.0,588.0&gt;-&lt;353.0,593.0&gt;-&lt;356.5,596.5&gt;&gt; has the same coordinates as a previous segment.

* uni24CE (U+24CE): B&lt;&lt;356.5,596.5&gt;-&lt;360.0,600.0&gt;-&lt;364.0,600.0&gt;&gt; has the same coordinates as a previous segment.

* uni24DC (U+24DC): B&lt;&lt;511.0,127.0&gt;-&lt;511.0,122.0&gt;-&lt;508.0,119.0&gt;&gt; has the same coordinates as a previous segment.

* uni24DC (U+24DC): B&lt;&lt;508.0,119.0&gt;-&lt;505.0,116.0&gt;-&lt;500.0,116.0&gt;&gt; has the same coordinates as a previous segment.

* uni24DC (U+24DC): B&lt;&lt;500.0,116.0&gt;-&lt;495.0,116.0&gt;-&lt;492.0,119.0&gt;&gt; has the same coordinates as a previous segment.

* uni24DC (U+24DC): B&lt;&lt;492.0,119.0&gt;-&lt;489.0,122.0&gt;-&lt;489.0,127.0&gt;&gt; has the same coordinates as a previous segment.

* uni24E7 (U+24E7): B&lt;&lt;642.5,120.0&gt;-&lt;640.0,117.0&gt;-&lt;636.0,117.0&gt;&gt; has the same coordinates as a previous segment.

* uni24E9 (U+24E9): B&lt;&lt;628.0,535.0&gt;-&lt;632.0,535.0&gt;-&lt;635.5,532.0&gt;&gt; has the same coordinates as a previous segment.

* uni24E9 (U+24E9): B&lt;&lt;635.5,532.0&gt;-&lt;639.0,529.0&gt;-&lt;639.0,524.0&gt;&gt; has the same coordinates as a previous segment.

* uni24B7.ss01: L&lt;&lt;385.0,333.0&gt;--&lt;385.0,356.0&gt;&gt; has the same coordinates as a previous segment.

* uni24C2.ss01: B&lt;&lt;355.0,588.0&gt;-&lt;355.0,593.0&gt;-&lt;358.0,596.5&gt;&gt; has the same coordinates as a previous segment.

* uni24C2.ss01: B&lt;&lt;358.0,596.5&gt;-&lt;361.0,600.0&gt;-&lt;366.0,600.0&gt;&gt; has the same coordinates as a previous segment.

* uni24DC.ss01: B&lt;&lt;510.0,127.0&gt;-&lt;510.0,122.0&gt;-&lt;507.0,119.0&gt;&gt; has the same coordinates as a previous segment.

* uni24DC.ss01: B&lt;&lt;507.0,119.0&gt;-&lt;504.0,116.0&gt;-&lt;499.0,116.0&gt;&gt; has the same coordinates as a previous segment.

* uni24DC.ss01: B&lt;&lt;499.0,116.0&gt;-&lt;494.0,116.0&gt;-&lt;491.0,119.0&gt;&gt; has the same coordinates as a previous segment.

* uni24DC.ss01: B&lt;&lt;491.0,119.0&gt;-&lt;488.0,122.0&gt;-&lt;488.0,127.0&gt;&gt; has the same coordinates as a previous segment.

* uni24E9.ss01: B&lt;&lt;628.0,535.0&gt;-&lt;632.0,535.0&gt;-&lt;635.5,532.0&gt;&gt; has the same coordinates as a previous segment.

* uni24E9.ss01: B&lt;&lt;635.5,532.0&gt;-&lt;639.0,529.0&gt;-&lt;639.0,524.0&gt;&gt; has the same coordinates as a previous segment.

* uni20BF (U+20BF): L&lt;&lt;71.0,343.0&gt;--&lt;71.0,361.0&gt;&gt; has the same coordinates as a previous segment.

* uni20A6 (U+20A6): B&lt;&lt;403.0,9.0&gt;-&lt;403.0,5.0&gt;-&lt;400.5,2.5&gt;&gt; has the same coordinates as a previous segment.

* uni20A6 (U+20A6): B&lt;&lt;400.5,2.5&gt;-&lt;398.0,0.0&gt;-&lt;394.0,0.0&gt;&gt; has the same coordinates as a previous segment.

* uni20A6 (U+20A6): B&lt;&lt;130.0,651.0&gt;-&lt;130.0,654.0&gt;-&lt;132.5,656.5&gt;&gt; has the same coordinates as a previous segment.

* uni20A6 (U+20A6): B&lt;&lt;132.5,656.5&gt;-&lt;135.0,659.0&gt;-&lt;139.0,659.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- _currency_part

- prime
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, syriac, malayalam, tai-le, tifinagh, hebrew, duployan, todhri, canadian-aboriginal, math, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: coptic, todhri</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee, duployan</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: syriac, cherokee, math</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, syriac, tifinagh, cherokee, gothic, sunuwar, thai</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: elbasan, greek, math</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, greek, math</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2010 HYPHEN: try adding one of: coptic, sundanese, yi, cham, arabic, sora-sompeng, hebrew, kaithi, syloti-nagri, kharoshthi, lisu, kayah-li, armenian</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+203D INTERROBANG: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+2048 QUESTION EXCLAMATION MARK: try adding mongolian</li>
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
<li>U+2105 CARE OF: try adding math</li>
<li>U+2106 CADA UNA: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+21BA ANTICLOCKWISE OPEN CIRCLE ARROW: try adding math</li>
<li>U+21BB CLOCKWISE OPEN CIRCLE ARROW: try adding math</li>
<li>U+21C4 RIGHTWARDS ARROW OVER LEFTWARDS ARROW: try adding math</li>
<li>U+21C5 UPWARDS ARROW LEFTWARDS OF DOWNWARDS ARROW: try adding math</li>
<li>U+21E7 UPWARDS WHITE ARROW: try adding symbols</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2205 EMPTY SET: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, yi, symbols, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2317 VIEWDATA SQUARE: try adding symbols</li>
<li>U+2318 PLACE OF INTEREST SIGN: try adding symbols</li>
<li>U+2325 OPTION KEY: try adding symbols</li>
<li>U+23CE RETURN SYMBOL: try adding symbols</li>
<li>U+23CF EJECT SYMBOL: try adding symbols</li>
<li>U+23E9 BLACK RIGHT-POINTING DOUBLE TRIANGLE: try adding symbols</li>
<li>U+23EA BLACK LEFT-POINTING DOUBLE TRIANGLE: try adding symbols</li>
<li>U+23ED BLACK RIGHT-POINTING DOUBLE TRIANGLE WITH VERTICAL BAR: try adding symbols</li>
<li>U+23EE BLACK LEFT-POINTING DOUBLE TRIANGLE WITH VERTICAL BAR: try adding symbols</li>
<li>U+23F5 BLACK MEDIUM RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+23F8 DOUBLE VERTICAL BAR: try adding symbols</li>
<li>U+23F9 BLACK SQUARE FOR STOP: try adding symbols</li>
<li>U+23FA BLACK CIRCLE FOR RECORD: try adding symbols</li>
<li>U+2460 CIRCLED DIGIT ONE: try adding one of: yi, mongolian, symbols</li>
<li>U+2461 CIRCLED DIGIT TWO: try adding one of: yi, mongolian, symbols</li>
<li>U+2462 CIRCLED DIGIT THREE: try adding one of: yi, mongolian, symbols</li>
<li>U+2463 CIRCLED DIGIT FOUR: try adding one of: yi, mongolian, symbols</li>
<li>U+2464 CIRCLED DIGIT FIVE: try adding one of: yi, mongolian, symbols</li>
<li>U+2465 CIRCLED DIGIT SIX: try adding one of: yi, mongolian, symbols</li>
<li>U+2466 CIRCLED DIGIT SEVEN: try adding one of: yi, mongolian, symbols</li>
<li>U+2467 CIRCLED DIGIT EIGHT: try adding one of: yi, mongolian, symbols</li>
<li>U+2468 CIRCLED DIGIT NINE: try adding one of: yi, mongolian, symbols</li>
<li>U+24B6 CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+24B7 CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+24B8 CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+24B9 CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+24BA CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+24BB CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+24BC CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+24BD CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+24BE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+24BF CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+24C0 CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+24C1 CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+24C2 CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+24C3 CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+24C4 CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+24C5 CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+24C6 CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+24C7 CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+24C8 CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+24C9 CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+24CA CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+24CB CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+24CC CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+24CD CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+24CE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+24CF CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+24D0 CIRCLED LATIN SMALL LETTER A: try adding symbols</li>
<li>U+24D1 CIRCLED LATIN SMALL LETTER B: try adding symbols</li>
<li>U+24D2 CIRCLED LATIN SMALL LETTER C: try adding symbols</li>
<li>U+24D3 CIRCLED LATIN SMALL LETTER D: try adding symbols</li>
<li>U+24D4 CIRCLED LATIN SMALL LETTER E: try adding symbols</li>
<li>U+24D5 CIRCLED LATIN SMALL LETTER F: try adding symbols</li>
<li>U+24D6 CIRCLED LATIN SMALL LETTER G: try adding symbols</li>
<li>U+24D7 CIRCLED LATIN SMALL LETTER H: try adding symbols</li>
<li>U+24D8 CIRCLED LATIN SMALL LETTER I: try adding symbols</li>
<li>U+24D9 CIRCLED LATIN SMALL LETTER J: try adding symbols</li>
<li>U+24DA CIRCLED LATIN SMALL LETTER K: try adding symbols</li>
<li>U+24DB CIRCLED LATIN SMALL LETTER L: try adding symbols</li>
<li>U+24DC CIRCLED LATIN SMALL LETTER M: try adding symbols</li>
<li>U+24DD CIRCLED LATIN SMALL LETTER N: try adding symbols</li>
<li>U+24DE CIRCLED LATIN SMALL LETTER O: try adding symbols</li>
<li>U+24DF CIRCLED LATIN SMALL LETTER P: try adding symbols</li>
<li>U+24E0 CIRCLED LATIN SMALL LETTER Q: try adding symbols</li>
<li>U+24E1 CIRCLED LATIN SMALL LETTER R: try adding symbols</li>
<li>U+24E2 CIRCLED LATIN SMALL LETTER S: try adding symbols</li>
<li>U+24E3 CIRCLED LATIN SMALL LETTER T: try adding symbols</li>
<li>U+24E4 CIRCLED LATIN SMALL LETTER U: try adding symbols</li>
<li>U+24E5 CIRCLED LATIN SMALL LETTER V: try adding symbols</li>
<li>U+24E6 CIRCLED LATIN SMALL LETTER W: try adding symbols</li>
<li>U+24E7 CIRCLED LATIN SMALL LETTER X: try adding symbols</li>
<li>U+24E8 CIRCLED LATIN SMALL LETTER Y: try adding symbols</li>
<li>U+24E9 CIRCLED LATIN SMALL LETTER Z: try adding symbols</li>
<li>U+24EA CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math</li>
<li>U+25C6 BLACK DIAMOND: try adding symbols</li>
<li>U+25C7 WHITE DIAMOND: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: syriac, mende-kikakui, mandaic, balinese, brahmi, tirhuta, music, caucasian-albanian, tai-le, gurmukhi, khmer, kharoshthi, bhaiksuki, javanese, siddham, malayalam, limbu, newa, lao, syloti-nagri, soyombo, telugu, coptic, hanifi-rohingya, masaram-gondi, oriya, warang-citi, gunjala-gondi, armenian, yi, marchen, tamil, meetei-mayek, phags-pa, gujarati, chakma, kannada, kayah-li, modi, thaana, wancho, sundanese, tifinagh, sogdian, new-tai-lue, adlam, ahom, tibetan, bassa-vah, khojki, canadian-aboriginal, thai, psalter-pahlavi, mongolian, cham, tagbanwa, hebrew, tagalog, devanagari, takri, mahajani, lepcha, manichaean, saurashtra, grantha, buginese, dogra, pahawh-hmong, buhid, batak, elbasan, kaithi, math, sinhala, old-permic, rejang, hanunoo, zanabazar-square, bengali, myanmar, tai-tham, duployan, miao, osage, sharada, khudawadi, nko, symbols, tai-viet</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+2606 WHITE STAR: try adding symbols</li>
<li>U+261A BLACK LEFT POINTING INDEX: try adding symbols</li>
<li>U+261B BLACK RIGHT POINTING INDEX: try adding symbols</li>
<li>U+261C WHITE LEFT POINTING INDEX: try adding symbols</li>
<li>U+261D WHITE UP POINTING INDEX: try adding symbols</li>
<li>U+261E WHITE RIGHT POINTING INDEX: try adding symbols</li>
<li>U+261F WHITE DOWN POINTING INDEX: try adding symbols</li>
<li>U+262F YIN YANG: try adding symbols</li>
<li>U+2639 WHITE FROWNING FACE: try adding symbols</li>
<li>U+263A WHITE SMILING FACE: try adding symbols</li>
<li>U+263B BLACK SMILING FACE: try adding symbols</li>
<li>U+2660 BLACK SPADE SUIT: try adding symbols</li>
<li>U+2663 BLACK CLUB SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+2666 BLACK DIAMOND SUIT: try adding symbols</li>
<li>U+2713 CHECK MARK: try adding symbols</li>
<li>U+272F PINWHEEL STAR: try adding symbols</li>
<li>U+2735 EIGHT POINTED PINWHEEL STAR: try adding symbols</li>
<li>U+273F BLACK FLORETTE: try adding symbols</li>
<li>U+2740 WHITE FLORETTE: try adding symbols</li>
<li>U+2766 FLORAL HEART: try adding symbols</li>
<li>U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols</li>
<li>U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols</li>
<li>U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols</li>
<li>U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols</li>
<li>U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols</li>
<li>U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols</li>
<li>U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols</li>
<li>U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols</li>
<li>U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols</li>
<li>U+2B1B BLACK LARGE SQUARE: try adding symbols</li>
<li>U+2B1C WHITE LARGE SQUARE: try adding symbols</li>
<li>U+2B98 THREE-D TOP-LIGHTED LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B99 THREE-D RIGHT-LIGHTED UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9A THREE-D TOP-LIGHTED RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9B THREE-D LEFT-LIGHTED DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9C BLACK LEFTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9D BLACK UPWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9E BLACK RIGHTWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+2B9F BLACK DOWNWARDS EQUILATERAL ARROWHEAD: try adding symbols</li>
<li>U+E133 : not included in any glyphset definition</li>
<li>U+E134 : not included in any glyphset definition</li>
<li>U+E135 : not included in any glyphset definition</li>
<li>U+FB00 LATIN SMALL LIGATURE FF: not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FB06 LATIN SMALL LIGATURE ST: not included in any glyphset definition</li>
<li>U+FFFC OBJECT REPLACEMENT CHARACTER: not included in any glyphset definition</li>
<li>U+1F150 NEGATIVE CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+1F151 NEGATIVE CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+1F152 NEGATIVE CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+1F153 NEGATIVE CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+1F154 NEGATIVE CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+1F155 NEGATIVE CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+1F156 NEGATIVE CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+1F157 NEGATIVE CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+1F158 NEGATIVE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+1F159 NEGATIVE CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+1F15A NEGATIVE CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+1F15B NEGATIVE CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+1F15C NEGATIVE CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+1F15D NEGATIVE CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+1F15E NEGATIVE CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+1F15F NEGATIVE CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+1F160 NEGATIVE CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+1F161 NEGATIVE CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+1F162 NEGATIVE CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+1F163 NEGATIVE CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+1F164 NEGATIVE CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+1F165 NEGATIVE CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+1F166 NEGATIVE CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+1F167 NEGATIVE CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+1F168 NEGATIVE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+1F169 NEGATIVE CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+1F500 TWISTED RIGHTWARDS ARROWS: not included in any glyphset definition</li>
<li>U+1F501 CLOCKWISE RIGHTWARDS AND LEFTWARDS OPEN CIRCLE ARROWS: not included in any glyphset definition</li>
<li>U+1F502 CLOCKWISE RIGHTWARDS AND LEFTWARDS OPEN CIRCLE ARROWS WITH CIRCLED ONE OVERLAY: not included in any glyphset definition</li>
<li>U+1F503 CLOCKWISE DOWNWARDS AND UPWARDS OPEN CIRCLE ARROWS: try adding symbols</li>
<li>U+1F504 ANTICLOCKWISE DOWNWARDS AND UPWARDS OPEN CIRCLE ARROWS: not included in any glyphset definition</li>
<li>U+1F5A2 BLACK UP POINTING BACKHAND INDEX: try adding symbols</li>
<li>U+1F5A3 BLACK DOWN POINTING BACKHAND INDEX: try adding symbols</li>
<li>U+1F7CF HEAVY EIGHT POINTED BLACK STAR: try adding symbols</li>
<li>U+1F7D3 HEAVY TWELVE POINTED BLACK STAR: try adding symbols</li>
<li>U+1F7D4 HEAVY TWELVE POINTED PINWHEEL STAR: try adding symbols</li>
<li>U+F0000 : not included in any glyphset definition</li>
<li>U+F0001 : not included in any glyphset definition</li>
<li>U+F0002 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: j̑</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: j̉ j̏ j̛̉ j̛̏ j̛̑ j̣̉ j̣̏ j̣̑ j̤̉ j̤̏ j̤̑ j̦̉ j̦̏ j̦̑ j̧̉ j̧̏ j̧̑ j̨̉ j̨̏ j̨̑</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* a.blackCircled has a counter-clockwise outer contour

* a.blackCircled.ss01 has a counter-clockwise outer contour

* b.blackCircled has a counter-clockwise outer contour

* b.blackCircled.ss01 has a counter-clockwise outer contour

* c.blackCircled has a counter-clockwise outer contour

* c.blackCircled.ss01 has a counter-clockwise outer contour

* d.blackCircled has a counter-clockwise outer contour

* d.blackCircled.ss01 has a counter-clockwise outer contour

* e.blackCircled has a counter-clockwise outer contour

* e.blackCircled.ss01 has a counter-clockwise outer contour

* f.blackCircled has a counter-clockwise outer contour

* f.blackCircled.ss01 has a counter-clockwise outer contour

* g.blackCircled has a counter-clockwise outer contour

* g.blackCircled.ss01 has a counter-clockwise outer contour

* h.blackCircled has a counter-clockwise outer contour

* h.blackCircled.ss01 has a counter-clockwise outer contour

* i.blackCircled has a counter-clockwise outer contour

* i.blackCircled.ss01 has a counter-clockwise outer contour

* j.blackCircled has a counter-clockwise outer contour

* j.blackCircled.ss01 has a counter-clockwise outer contour

* k.blackCircled has a counter-clockwise outer contour

* k.blackCircled.ss01 has a counter-clockwise outer contour

* l.blackCircled has a counter-clockwise outer contour

* l.blackCircled.ss01 has a counter-clockwise outer contour

* m.blackCircled has a counter-clockwise outer contour

* m.blackCircled.ss01 has a counter-clockwise outer contour

* n.blackCircled has a counter-clockwise outer contour

* n.blackCircled.ss01 has a counter-clockwise outer contour

* o.blackCircled has a counter-clockwise outer contour

* o.blackCircled.ss01 has a counter-clockwise outer contour

* p.blackCircled has a counter-clockwise outer contour

* p.blackCircled.ss01 has a counter-clockwise outer contour

* q.blackCircled has a counter-clockwise outer contour

* q.blackCircled.ss01 has a counter-clockwise outer contour

* r.blackCircled has a counter-clockwise outer contour

* r.blackCircled.ss01 has a counter-clockwise outer contour

* s.blackCircled has a counter-clockwise outer contour

* s.blackCircled.ss01 has a counter-clockwise outer contour

* t.blackCircled has a counter-clockwise outer contour

* t.blackCircled.ss01 has a counter-clockwise outer contour

* u.blackCircled has a counter-clockwise outer contour

* u.blackCircled.ss01 has a counter-clockwise outer contour

* u1F150 (U+1F150) has a counter-clockwise outer contour

* u1F150.ss01 has a counter-clockwise outer contour

* u1F151 (U+1F151) has a counter-clockwise outer contour

* u1F151.ss01 has a counter-clockwise outer contour

* u1F152 (U+1F152) has a counter-clockwise outer contour

* u1F152.ss01 has a counter-clockwise outer contour

* u1F153 (U+1F153) has a counter-clockwise outer contour

* u1F153.ss01 has a counter-clockwise outer contour

* u1F154 (U+1F154) has a counter-clockwise outer contour

* u1F154.ss01 has a counter-clockwise outer contour

* u1F155 (U+1F155) has a counter-clockwise outer contour

* u1F155.ss01 has a counter-clockwise outer contour

* u1F156 (U+1F156) has a counter-clockwise outer contour

* u1F156.ss01 has a counter-clockwise outer contour

* u1F157 (U+1F157) has a counter-clockwise outer contour

* u1F157.ss01 has a counter-clockwise outer contour

* u1F158 (U+1F158) has a counter-clockwise outer contour

* u1F158.ss01 has a counter-clockwise outer contour

* u1F159 (U+1F159) has a counter-clockwise outer contour

* u1F159.ss01 has a counter-clockwise outer contour

* u1F15A (U+1F15A) has a counter-clockwise outer contour

* u1F15A.ss01 has a counter-clockwise outer contour

* u1F15B (U+1F15B) has a counter-clockwise outer contour

* u1F15B.ss01 has a counter-clockwise outer contour

* u1F15C (U+1F15C) has a counter-clockwise outer contour

* u1F15C.ss01 has a counter-clockwise outer contour

* u1F15D (U+1F15D) has a counter-clockwise outer contour

* u1F15D.ss01 has a counter-clockwise outer contour

* u1F15E (U+1F15E) has a counter-clockwise outer contour

* u1F15E.ss01 has a counter-clockwise outer contour

* u1F15F (U+1F15F) has a counter-clockwise outer contour

* u1F15F.ss01 has a counter-clockwise outer contour

* u1F160 (U+1F160) has a counter-clockwise outer contour

* u1F160.ss01 has a counter-clockwise outer contour

* u1F161 (U+1F161) has a counter-clockwise outer contour

* u1F161.ss01 has a counter-clockwise outer contour

* u1F162 (U+1F162) has a counter-clockwise outer contour

* u1F162.ss01 has a counter-clockwise outer contour

* u1F163 (U+1F163) has a counter-clockwise outer contour

* u1F163.ss01 has a counter-clockwise outer contour

* u1F164 (U+1F164) has a counter-clockwise outer contour

* u1F164.ss01 has a counter-clockwise outer contour

* u1F165 (U+1F165) has a counter-clockwise outer contour

* u1F165.ss01 has a counter-clockwise outer contour

* u1F166 (U+1F166) has a counter-clockwise outer contour

* u1F166.ss01 has a counter-clockwise outer contour

* u1F167 (U+1F167) has a counter-clockwise outer contour

* u1F167.ss01 has a counter-clockwise outer contour

* u1F168 (U+1F168) has a counter-clockwise outer contour

* u1F168.ss01 has a counter-clockwise outer contour

* u1F169 (U+1F169) has a counter-clockwise outer contour

* u1F169.ss01 has a counter-clockwise outer contour

* uni2460 (U+2460) has a counter-clockwise outer contour

* uni2460.ss01 has a counter-clockwise outer contour

* uni2461 (U+2461) has a counter-clockwise outer contour

* uni2461.ss01 has a counter-clockwise outer contour

* uni2462 (U+2462) has a counter-clockwise outer contour

* uni2462.ss01 has a counter-clockwise outer contour

* uni2463 (U+2463) has a counter-clockwise outer contour

* uni2463.ss01 has a counter-clockwise outer contour

* uni2464 (U+2464) has a counter-clockwise outer contour

* uni2464.ss01 has a counter-clockwise outer contour

* uni2465 (U+2465) has a counter-clockwise outer contour

* uni2465.ss01 has a counter-clockwise outer contour

* uni2466 (U+2466) has a counter-clockwise outer contour

* uni2466.ss01 has a counter-clockwise outer contour

* uni2467 (U+2467) has a counter-clockwise outer contour

* uni2467.ss01 has a counter-clockwise outer contour

* uni2468 (U+2468) has a counter-clockwise outer contour

* uni2468.ss01 has a counter-clockwise outer contour

* uni24B6 (U+24B6) has a counter-clockwise outer contour

* uni24B6.ss01 has a counter-clockwise outer contour

* uni24B7 (U+24B7) has a counter-clockwise outer contour

* uni24B7.ss01 has a counter-clockwise outer contour

* uni24B8 (U+24B8) has a counter-clockwise outer contour

* uni24B8.ss01 has a counter-clockwise outer contour

* uni24B9 (U+24B9) has a counter-clockwise outer contour

* uni24B9.ss01 has a counter-clockwise outer contour

* uni24BA (U+24BA) has a counter-clockwise outer contour

* uni24BA.ss01 has a counter-clockwise outer contour

* uni24BB (U+24BB) has a counter-clockwise outer contour

* uni24BB.ss01 has a counter-clockwise outer contour

* uni24BC (U+24BC) has a counter-clockwise outer contour

* uni24BC.ss01 has a counter-clockwise outer contour

* uni24BD (U+24BD) has a counter-clockwise outer contour

* uni24BD.ss01 has a counter-clockwise outer contour

* uni24BE (U+24BE) has a counter-clockwise outer contour

* uni24BE.ss01 has a counter-clockwise outer contour

* uni24BF (U+24BF) has a counter-clockwise outer contour

* uni24BF.ss01 has a counter-clockwise outer contour

* uni24C0 (U+24C0) has a counter-clockwise outer contour

* uni24C0.ss01 has a counter-clockwise outer contour

* uni24C1 (U+24C1) has a counter-clockwise outer contour

* uni24C1.ss01 has a counter-clockwise outer contour

* uni24C2 (U+24C2) has a counter-clockwise outer contour

* uni24C2.ss01 has a counter-clockwise outer contour

* uni24C3 (U+24C3) has a counter-clockwise outer contour

* uni24C3.ss01 has a counter-clockwise outer contour

* uni24C4 (U+24C4) has a counter-clockwise outer contour

* uni24C4.ss01 has a counter-clockwise outer contour

* uni24C5 (U+24C5) has a counter-clockwise outer contour

* uni24C5.ss01 has a counter-clockwise outer contour

* uni24C6 (U+24C6) has a counter-clockwise outer contour

* uni24C6.ss01 has a counter-clockwise outer contour

* uni24C7 (U+24C7) has a counter-clockwise outer contour

* uni24C7.ss01 has a counter-clockwise outer contour

* uni24C8 (U+24C8) has a counter-clockwise outer contour

* uni24C8.ss01 has a counter-clockwise outer contour

* uni24C9 (U+24C9) has a counter-clockwise outer contour

* uni24C9.ss01 has a counter-clockwise outer contour

* uni24CA (U+24CA) has a counter-clockwise outer contour

* uni24CA.ss01 has a counter-clockwise outer contour

* uni24CB (U+24CB) has a counter-clockwise outer contour

* uni24CB.ss01 has a counter-clockwise outer contour

* uni24CC (U+24CC) has a counter-clockwise outer contour

* uni24CC.ss01 has a counter-clockwise outer contour

* uni24CD (U+24CD) has a counter-clockwise outer contour

* uni24CD.ss01 has a counter-clockwise outer contour

* uni24CE (U+24CE) has a counter-clockwise outer contour

* uni24CE.ss01 has a counter-clockwise outer contour

* uni24CF (U+24CF) has a counter-clockwise outer contour

* uni24CF.ss01 has a counter-clockwise outer contour

* uni24D0 (U+24D0) has a counter-clockwise outer contour

* uni24D0.ss01 has a counter-clockwise outer contour

* uni24D1 (U+24D1) has a counter-clockwise outer contour

* uni24D1.ss01 has a counter-clockwise outer contour

* uni24D2 (U+24D2) has a counter-clockwise outer contour

* uni24D2.ss01 has a counter-clockwise outer contour

* uni24D3 (U+24D3) has a counter-clockwise outer contour

* uni24D3.ss01 has a counter-clockwise outer contour

* uni24D4 (U+24D4) has a counter-clockwise outer contour

* uni24D4.ss01 has a counter-clockwise outer contour

* uni24D5 (U+24D5) has a counter-clockwise outer contour

* uni24D5.ss01 has a counter-clockwise outer contour

* uni24D6 (U+24D6) has a counter-clockwise outer contour

* uni24D6.ss01 has a counter-clockwise outer contour

* uni24D7 (U+24D7) has a counter-clockwise outer contour

* uni24D7.ss01 has a counter-clockwise outer contour

* uni24D8 (U+24D8) has a counter-clockwise outer contour

* uni24D8.ss01 has a counter-clockwise outer contour

* uni24D9 (U+24D9) has a counter-clockwise outer contour

* uni24D9.ss01 has a counter-clockwise outer contour

* uni24DA (U+24DA) has a counter-clockwise outer contour

* uni24DA.ss01 has a counter-clockwise outer contour

* uni24DB (U+24DB) has a counter-clockwise outer contour

* uni24DB.ss01 has a counter-clockwise outer contour

* uni24DC (U+24DC) has a counter-clockwise outer contour

* uni24DC.ss01 has a counter-clockwise outer contour

* uni24DD (U+24DD) has a counter-clockwise outer contour

* uni24DD.ss01 has a counter-clockwise outer contour

* uni24DE (U+24DE) has a counter-clockwise outer contour

* uni24DE.ss01 has a counter-clockwise outer contour

* uni24DF (U+24DF) has a counter-clockwise outer contour

* uni24DF.ss01 has a counter-clockwise outer contour

* uni24E0 (U+24E0) has a counter-clockwise outer contour

* uni24E0.ss01 has a counter-clockwise outer contour

* uni24E1 (U+24E1) has a counter-clockwise outer contour

* uni24E1.ss01 has a counter-clockwise outer contour

* uni24E2 (U+24E2) has a counter-clockwise outer contour

* uni24E2.ss01 has a counter-clockwise outer contour

* uni24E3 (U+24E3) has a counter-clockwise outer contour

* uni24E3.ss01 has a counter-clockwise outer contour

* uni24E4 (U+24E4) has a counter-clockwise outer contour

* uni24E4.ss01 has a counter-clockwise outer contour

* uni24E5 (U+24E5) has a counter-clockwise outer contour

* uni24E5.ss01 has a counter-clockwise outer contour

* uni24E6 (U+24E6) has a counter-clockwise outer contour

* uni24E6.ss01 has a counter-clockwise outer contour

* uni24E7 (U+24E7) has a counter-clockwise outer contour

* uni24E7.ss01 has a counter-clockwise outer contour

* uni24E8 (U+24E8) has a counter-clockwise outer contour

* uni24E8.ss01 has a counter-clockwise outer contour

* uni24E9 (U+24E9) has a counter-clockwise outer contour

* uni24E9.ss01 has a counter-clockwise outer contour

* uni24EA (U+24EA) has a counter-clockwise outer contour

* uni24EA.ss01 has a counter-clockwise outer contour

* uni24FF (U+24FF) has a counter-clockwise outer contour

* uni24FF.ss01 has a counter-clockwise outer contour

* uni2776 (U+2776) has a counter-clockwise outer contour

* uni2776.ss01 has a counter-clockwise outer contour

* uni2777 (U+2777) has a counter-clockwise outer contour

* uni2777.ss01 has a counter-clockwise outer contour

* uni2778 (U+2778) has a counter-clockwise outer contour

* uni2778.ss01 has a counter-clockwise outer contour

* uni2779 (U+2779) has a counter-clockwise outer contour

* uni2779.ss01 has a counter-clockwise outer contour

* uni277A (U+277A) has a counter-clockwise outer contour

* uni277A.ss01 has a counter-clockwise outer contour

* uni277B (U+277B) has a counter-clockwise outer contour

* uni277B.ss01 has a counter-clockwise outer contour

* uni277C (U+277C) has a counter-clockwise outer contour

* uni277C.ss01 has a counter-clockwise outer contour

* uni277D (U+277D) has a counter-clockwise outer contour

* uni277D.ss01 has a counter-clockwise outer contour

* uni277E (U+277E) has a counter-clockwise outer contour

* uni277E.ss01 has a counter-clockwise outer contour

* uniFFFD (U+FFFD) has a counter-clockwise outer contour

* v.blackCircled has a counter-clockwise outer contour

* v.blackCircled.ss01 has a counter-clockwise outer contour

* w.blackCircled has a counter-clockwise outer contour

* w.blackCircled.ss01 has a counter-clockwise outer contour

* x.blackCircled has a counter-clockwise outer contour

* x.blackCircled.ss01 has a counter-clockwise outer contour

* y.blackCircled has a counter-clockwise outer contour

* y.blackCircled.ss01 has a counter-clockwise outer contour

* z.blackCircled has a counter-clockwise outer contour

* z.blackCircled.ss01 has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 7 | 11 | 88 | 8 | 122 | 0 | 
| 0% | 0% | 3% | 5% | 37% | 3% | 52% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
