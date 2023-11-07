## FontBakery report

fontbakery version: 0.10.1

<details><summary><b>[20] SankofaDisplay-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 sankofa display (https://github.com/batsimadz/sankofa-display)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2023 Sankofa Display (https://github.com/batsimadz/Sankofa-Display)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1081, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 316, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.1, while a newer 0.10.3 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Glyph "Abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EAE" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EB6" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EB2" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EB4" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EB4" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EAA" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E1C" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EC4" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EBC" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E1A" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Itilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E2C" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni2C62" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1ED6" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EE0" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni01EA" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni01EC" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E4C" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E4E" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni022C" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EEE" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Utilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E78" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E74" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E7C" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EF8" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EAF" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EB7" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EB3" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EB5" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EB5" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EAB" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E1D" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EC5" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EBD" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E1B" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "dotlessi_ogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "itilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E2D" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni026B" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1ED7" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EE1" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni01EB" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni01ED" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E4D" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E4F" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni022D" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EEF" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "utilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E79" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E75" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1E7D" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EF9" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03060301" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03060309" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03060303" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03060303" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03020303" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030B" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0306" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "tildecomb" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0328" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0330" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0334" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0310

	- uni0311

	- uni0312

	- uni031B

	- uni0325

	- uni0326

	- uni0327

	- uni0328

	- uni032D

	- uni032F

	- uni0330

	- uni0331

	- uni0332

	- uni0334

	- uni0335

	- uni1DC4

	- uni1DC5

	- uni1DC6

	- uni1DC7

	- uni1DCA [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x207F (SUPERSCRIPT LATIN SMALL LETTER N)


	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x032E (COMBINING BREVE BELOW)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, old-permic, canadian-aboriginal, tai-le, tifinagh, math, coptic, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, cherokee, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, gothic, caucasian-albanian, cherokee, syriac
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
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
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+215B VULGAR FRACTION ONE EIGHTH: not included in any glyphset definition
 * U+215C VULGAR FRACTION THREE EIGHTHS: not included in any glyphset definition
 * U+215D VULGAR FRACTION FIVE EIGHTHS: not included in any glyphset definition
 * U+215E VULGAR FRACTION SEVEN EIGHTHS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
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
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CC DOTTED CIRCLE: try adding one of: soyombo, gujarati, modi, nko, tagalog, adlam, osage, lao, cham, tagbanwa, mahajani, zanabazar-square, oriya, sogdian, math, malayalam, buginese, music, wancho, manichaean, myanmar, sharada, khudawadi, kaithi, grantha, ahom, marchen, symbols, bassa-vah, hanunoo, psalter-pahlavi, bengali, tirhuta, buhid, gunjala-gondi, duployan, devanagari, rejang, kayah-li, pahawh-hmong, bhaiksuki, mende-kikakui, coptic, kannada, sundanese, meetei-mayek, siddham, telugu, chakma, tamil, mongolian, tai-viet, hebrew, kharoshthi, khojki, khmer, new-tai-lue, limbu, elbasan, syriac, brahmi, takri, yi, newa, gurmukhi, tai-le, balinese, thaana, tibetan, tifinagh, hanifi-rohingya, miao, caucasian-albanian, lepcha, old-permic, thai, masaram-gondi, javanese, batak, phags-pa, dogra, mandaic, sinhala, syloti-nagri
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- f.alt

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- i.loclTRK

	- j.alt

	- l.alt

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- q.alt

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.dnom

	- six.numr

	- six.tf

	- t.alt

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni004A0301

	- uni006A0301

	- uni013B.loclMAH

	- uni013C.loclMAH

	- uni0145.loclMAH

	- uni0146.loclMAH

	- uni03000304

	- uni03010304

	- uni03020300

	- uni03020301

	- uni03020303

	- uni03020309

	- uni03040300

	- uni03040301

	- uni03060300

	- uni03060301

	- uni03060303

	- uni03060309

	- uni0326.loclMAH

	- y.alt

	- z.alt

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: exclam	Contours detected: 4	Expected: 2

	- Glyph name: numbersign	Contours detected: 4	Expected: 2

	- Glyph name: ampersand	Contours detected: 6	Expected: 1, 2 or 3

	- Glyph name: zero	Contours detected: 4	Expected: 2 or 3

	- Glyph name: one	Contours detected: 3	Expected: 1

	- Glyph name: two	Contours detected: 3	Expected: 1

	- Glyph name: three	Contours detected: 3	Expected: 1

	- Glyph name: four	Contours detected: 4	Expected: 1 or 2

	- Glyph name: five	Contours detected: 4	Expected: 1

	- Glyph name: six	Contours detected: 4	Expected: 1 or 2

	- Glyph name: seven	Contours detected: 3	Expected: 1

	- Glyph name: eight	Contours detected: 7	Expected: 3

	- Glyph name: nine	Contours detected: 4	Expected: 1 or 2

	- Glyph name: colon	Contours detected: 4	Expected: 2

	- Glyph name: semicolon	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 4	Expected: 2

	- Glyph name: at	Contours detected: 4	Expected: 2

	- Glyph name: A	Contours detected: 5	Expected: 2

	- Glyph name: B	Contours detected: 7	Expected: 2 or 3

	- Glyph name: C	Contours detected: 3	Expected: 1

	- Glyph name: D	Contours detected: 4	Expected: 2

	- Glyph name: E	Contours detected: 3	Expected: 1

	- Glyph name: F	Contours detected: 4	Expected: 1

	- Glyph name: G	Contours detected: 4	Expected: 1

	- Glyph name: H	Contours detected: 5	Expected: 1

	- Glyph name: J	Contours detected: 4	Expected: 1

	- Glyph name: K	Contours detected: 4	Expected: 1 or 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 4	Expected: 1

	- Glyph name: O	Contours detected: 4	Expected: 2

	- Glyph name: P	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 5	Expected: 2

	- Glyph name: R	Contours detected: 4	Expected: 1 or 2

	- Glyph name: S	Contours detected: 3	Expected: 1

	- Glyph name: U	Contours detected: 6	Expected: 1

	- Glyph name: V	Contours detected: 4	Expected: 1

	- Glyph name: W	Contours detected: 4	Expected: 1 or 2

	- Glyph name: X	Contours detected: 5	Expected: 1

	- Glyph name: Y	Contours detected: 3	Expected: 1

	- Glyph name: Z	Contours detected: 3	Expected: 1

	- Glyph name: a	Contours detected: 4	Expected: 2

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: c	Contours detected: 3	Expected: 1

	- Glyph name: d	Contours detected: 4	Expected: 2

	- Glyph name: e	Contours detected: 4	Expected: 2

	- Glyph name: g	Contours detected: 4	Expected: 2 or 3

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: o	Contours detected: 4	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: u	Contours detected: 3	Expected: 1

	- Glyph name: v	Contours detected: 4	Expected: 1

	- Glyph name: w	Contours detected: 4	Expected: 1

	- Glyph name: x	Contours detected: 3	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: exclamdown	Contours detected: 4	Expected: 2

	- Glyph name: copyright	Contours detected: 4	Expected: 3

	- Glyph name: paragraph	Contours detected: 5	Expected: 1, 2 or 3

	- Glyph name: questiondown	Contours detected: 4	Expected: 2

	- Glyph name: Agrave	Contours detected: 6	Expected: 3

	- Glyph name: Aacute	Contours detected: 6	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 6	Expected: 3

	- Glyph name: Atilde	Contours detected: 6	Expected: 3

	- Glyph name: Adieresis	Contours detected: 7	Expected: 4

	- Glyph name: Aring	Contours detected: 7	Expected: 3 or 4

	- Glyph name: AE	Contours detected: 5	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Egrave	Contours detected: 4	Expected: 2

	- Glyph name: Eacute	Contours detected: 4	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Edieresis	Contours detected: 5	Expected: 3

	- Glyph name: Ograve	Contours detected: 5	Expected: 3

	- Glyph name: Oacute	Contours detected: 5	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 5	Expected: 3

	- Glyph name: Otilde	Contours detected: 5	Expected: 3

	- Glyph name: Odieresis	Contours detected: 6	Expected: 4

	- Glyph name: Ugrave	Contours detected: 7	Expected: 2

	- Glyph name: Uacute	Contours detected: 7	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 7	Expected: 2

	- Glyph name: Udieresis	Contours detected: 8	Expected: 3

	- Glyph name: Yacute	Contours detected: 4	Expected: 2

	- Glyph name: agrave	Contours detected: 5	Expected: 3

	- Glyph name: aacute	Contours detected: 5	Expected: 3

	- Glyph name: acircumflex	Contours detected: 5	Expected: 3

	- Glyph name: atilde	Contours detected: 5	Expected: 3

	- Glyph name: adieresis	Contours detected: 6	Expected: 4

	- Glyph name: aring	Contours detected: 6	Expected: 4

	- Glyph name: ae	Contours detected: 5	Expected: 3

	- Glyph name: ccedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: egrave	Contours detected: 5	Expected: 3

	- Glyph name: eacute	Contours detected: 5	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 5	Expected: 3

	- Glyph name: edieresis	Contours detected: 6	Expected: 4

	- Glyph name: eth	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ograve	Contours detected: 5	Expected: 3

	- Glyph name: oacute	Contours detected: 5	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 5	Expected: 3

	- Glyph name: otilde	Contours detected: 5	Expected: 3

	- Glyph name: odieresis	Contours detected: 6	Expected: 4

	- Glyph name: divide	Contours detected: 5	Expected: 3

	- Glyph name: ugrave	Contours detected: 4	Expected: 2

	- Glyph name: uacute	Contours detected: 4	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 4	Expected: 2

	- Glyph name: udieresis	Contours detected: 5	Expected: 3

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 6	Expected: 3

	- Glyph name: amacron	Contours detected: 5	Expected: 3

	- Glyph name: Abreve	Contours detected: 6	Expected: 3

	- Glyph name: abreve	Contours detected: 5	Expected: 3

	- Glyph name: Aogonek	Contours detected: 6	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 5	Expected: 2

	- Glyph name: Cacute	Contours detected: 4	Expected: 2

	- Glyph name: cacute	Contours detected: 4	Expected: 2

	- Glyph name: Ccircumflex	Contours detected: 4	Expected: 2

	- Glyph name: ccircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: cdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: Ccaron	Contours detected: 4	Expected: 2

	- Glyph name: ccaron	Contours detected: 4	Expected: 2

	- Glyph name: Dcaron	Contours detected: 5	Expected: 3

	- Glyph name: dcaron	Contours detected: 5	Expected: 3

	- Glyph name: dcroat	Contours detected: 4	Expected: 2

	- Glyph name: Emacron	Contours detected: 4	Expected: 2

	- Glyph name: emacron	Contours detected: 5	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 4	Expected: 2

	- Glyph name: edotaccent	Contours detected: 5	Expected: 3

	- Glyph name: Eogonek	Contours detected: 4	Expected: 1 or 2

	- Glyph name: eogonek	Contours detected: 5	Expected: 2

	- Glyph name: Ecaron	Contours detected: 4	Expected: 2

	- Glyph name: ecaron	Contours detected: 5	Expected: 3

	- Glyph name: Gcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: gcircumflex	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Gbreve	Contours detected: 5	Expected: 2

	- Glyph name: gbreve	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Gdotaccent	Contours detected: 5	Expected: 2

	- Glyph name: gdotaccent	Contours detected: 5	Expected: 3 or 4

	- Glyph name: uni0122	Contours detected: 5	Expected: 2

	- Glyph name: uni0123	Contours detected: 6	Expected: 3 or 4

	- Glyph name: Hcircumflex	Contours detected: 6	Expected: 2

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 3	Expected: 1

	- Glyph name: IJ	Contours detected: 5	Expected: 1 or 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Jcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: uni0136	Contours detected: 5	Expected: 2 or 3

	- Glyph name: kgreenlandic	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: eng	Contours detected: 3	Expected: 1

	- Glyph name: Omacron	Contours detected: 5	Expected: 3

	- Glyph name: omacron	Contours detected: 5	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 6	Expected: 4

	- Glyph name: ohungarumlaut	Contours detected: 6	Expected: 4

	- Glyph name: OE	Contours detected: 6	Expected: 2

	- Glyph name: oe	Contours detected: 8	Expected: 3

	- Glyph name: Racute	Contours detected: 5	Expected: 3

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 5	Expected: 3

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: Rcaron	Contours detected: 5	Expected: 3

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Scedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: Utilde	Contours detected: 7	Expected: 2

	- Glyph name: utilde	Contours detected: 4	Expected: 2

	- Glyph name: Umacron	Contours detected: 7	Expected: 2

	- Glyph name: umacron	Contours detected: 4	Expected: 2

	- Glyph name: Ubreve	Contours detected: 7	Expected: 2

	- Glyph name: ubreve	Contours detected: 4	Expected: 2

	- Glyph name: Uring	Contours detected: 8	Expected: 3

	- Glyph name: uring	Contours detected: 5	Expected: 3

	- Glyph name: Uhungarumlaut	Contours detected: 8	Expected: 3

	- Glyph name: uhungarumlaut	Contours detected: 5	Expected: 3

	- Glyph name: Uogonek	Contours detected: 7	Expected: 1

	- Glyph name: uogonek	Contours detected: 4	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 5	Expected: 3

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: uni0186	Contours detected: 3	Expected: 1

	- Glyph name: uni018F	Contours detected: 4	Expected: 2

	- Glyph name: Gammalatin	Contours detected: 4	Expected: 2

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: Ohorn	Contours detected: 5	Expected: 2 or 3

	- Glyph name: ohorn	Contours detected: 5	Expected: 2

	- Glyph name: Uhorn	Contours detected: 7	Expected: 1

	- Glyph name: uhorn	Contours detected: 4	Expected: 1

	- Glyph name: Upsilonlatin	Contours detected: 3	Expected: 1

	- Glyph name: uni01B7	Contours detected: 3	Expected: 1

	- Glyph name: uni01C3	Contours detected: 4	Expected: 2

	- Glyph name: uni01CD	Contours detected: 6	Expected: 3

	- Glyph name: uni01CE	Contours detected: 5	Expected: 3

	- Glyph name: uni01D1	Contours detected: 5	Expected: 3

	- Glyph name: uni01D2	Contours detected: 5	Expected: 3

	- Glyph name: uni01D3	Contours detected: 7	Expected: 2

	- Glyph name: uni01D4	Contours detected: 4	Expected: 2

	- Glyph name: uni01D5	Contours detected: 9	Expected: 4

	- Glyph name: uni01D6	Contours detected: 6	Expected: 4

	- Glyph name: uni01D7	Contours detected: 9	Expected: 4

	- Glyph name: uni01D8	Contours detected: 6	Expected: 4

	- Glyph name: uni01D9	Contours detected: 9	Expected: 4

	- Glyph name: uni01DA	Contours detected: 6	Expected: 4

	- Glyph name: uni01DB	Contours detected: 9	Expected: 4

	- Glyph name: uni01DC	Contours detected: 6	Expected: 4

	- Glyph name: uni01DE	Contours detected: 8	Expected: 5

	- Glyph name: uni01DF	Contours detected: 7	Expected: 5

	- Glyph name: uni01E0	Contours detected: 7	Expected: 4

	- Glyph name: uni01E1	Contours detected: 6	Expected: 4

	- Glyph name: uni01E2	Contours detected: 6	Expected: 3

	- Glyph name: uni01E3	Contours detected: 6	Expected: 4

	- Glyph name: uni01E4	Contours detected: 5	Expected: 1

	- Glyph name: uni01E5	Contours detected: 5	Expected: 2

	- Glyph name: Gcaron	Contours detected: 5	Expected: 2

	- Glyph name: gcaron	Contours detected: 5	Expected: 3 or 4

	- Glyph name: uni01E8	Contours detected: 5	Expected: 2

	- Glyph name: uni01E9	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 5	Expected: 2

	- Glyph name: uni01EB	Contours detected: 5	Expected: 2

	- Glyph name: uni01EC	Contours detected: 6	Expected: 3

	- Glyph name: uni01ED	Contours detected: 6	Expected: 3

	- Glyph name: uni01EE	Contours detected: 4	Expected: 2

	- Glyph name: uni01EF	Contours detected: 4	Expected: 2

	- Glyph name: uni01F0	Contours detected: 3	Expected: 2

	- Glyph name: uni01F4	Contours detected: 5	Expected: 2

	- Glyph name: uni01F5	Contours detected: 5	Expected: 3

	- Glyph name: uni01F9	Contours detected: 3	Expected: 2

	- Glyph name: uni0200	Contours detected: 7	Expected: 4

	- Glyph name: uni0201	Contours detected: 6	Expected: 4

	- Glyph name: uni0202	Contours detected: 6	Expected: 3

	- Glyph name: uni0203	Contours detected: 5	Expected: 3

	- Glyph name: uni0204	Contours detected: 5	Expected: 3

	- Glyph name: uni0205	Contours detected: 6	Expected: 4

	- Glyph name: uni0206	Contours detected: 4	Expected: 2

	- Glyph name: uni0207	Contours detected: 5	Expected: 3

	- Glyph name: uni020C	Contours detected: 6	Expected: 4

	- Glyph name: uni020D	Contours detected: 6	Expected: 4

	- Glyph name: uni020E	Contours detected: 5	Expected: 3

	- Glyph name: uni020F	Contours detected: 5	Expected: 3

	- Glyph name: uni0210	Contours detected: 6	Expected: 4

	- Glyph name: uni0211	Contours detected: 4	Expected: 3

	- Glyph name: uni0212	Contours detected: 5	Expected: 3

	- Glyph name: uni0213	Contours detected: 3	Expected: 2

	- Glyph name: uni0214	Contours detected: 8	Expected: 3

	- Glyph name: uni0215	Contours detected: 5	Expected: 3

	- Glyph name: uni0216	Contours detected: 7	Expected: 2

	- Glyph name: uni0217	Contours detected: 4	Expected: 2

	- Glyph name: uni0218	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni021E	Contours detected: 6	Expected: 2

	- Glyph name: uni021F	Contours detected: 3	Expected: 2

	- Glyph name: uni0226	Contours detected: 6	Expected: 3

	- Glyph name: uni0227	Contours detected: 5	Expected: 3

	- Glyph name: uni0228	Contours detected: 4	Expected: 1

	- Glyph name: uni0229	Contours detected: 5	Expected: 2

	- Glyph name: uni022A	Contours detected: 7	Expected: 5

	- Glyph name: uni022B	Contours detected: 7	Expected: 5

	- Glyph name: uni022C	Contours detected: 6	Expected: 4

	- Glyph name: uni022D	Contours detected: 6	Expected: 4

	- Glyph name: uni022E	Contours detected: 5	Expected: 3

	- Glyph name: uni022F	Contours detected: 5	Expected: 3

	- Glyph name: uni0230	Contours detected: 6	Expected: 4

	- Glyph name: uni0231	Contours detected: 6	Expected: 4

	- Glyph name: uni0232	Contours detected: 4	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni023A	Contours detected: 5	Expected: 3

	- Glyph name: uni023D	Contours detected: 3	Expected: 1

	- Glyph name: uni023E	Contours detected: 3	Expected: 2

	- Glyph name: uni0241	Contours detected: 2	Expected: 1

	- Glyph name: uni0247	Contours detected: 6	Expected: 4

	- Glyph name: uni0259	Contours detected: 4	Expected: 2

	- Glyph name: uni0292	Contours detected: 3	Expected: 1

	- Glyph name: uni02B7	Contours detected: 4	Expected: 1

	- Glyph name: uni02B8	Contours detected: 2	Expected: 1

	- Glyph name: uni0312	Contours detected: 2	Expected: 1

	- Glyph name: uni1E00	Contours detected: 7	Expected: 4

	- Glyph name: uni1E01	Contours detected: 6	Expected: 4

	- Glyph name: uni1E02	Contours detected: 8	Expected: 4

	- Glyph name: uni1E03	Contours detected: 5	Expected: 3

	- Glyph name: uni1E08	Contours detected: 5	Expected: 2

	- Glyph name: uni1E09	Contours detected: 5	Expected: 2

	- Glyph name: uni1E0A	Contours detected: 5	Expected: 3

	- Glyph name: uni1E0B	Contours detected: 5	Expected: 3

	- Glyph name: uni1E0C	Contours detected: 5	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 5	Expected: 3

	- Glyph name: Dmacronbelow	Contours detected: 5	Expected: 3

	- Glyph name: dmacronbelow	Contours detected: 5	Expected: 3

	- Glyph name: uni1E14	Contours detected: 5	Expected: 3

	- Glyph name: uni1E15	Contours detected: 6	Expected: 4

	- Glyph name: uni1E16	Contours detected: 5	Expected: 3

	- Glyph name: uni1E17	Contours detected: 6	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 5	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 6	Expected: 3

	- Glyph name: uni1E1E	Contours detected: 5	Expected: 2

	- Glyph name: uni1E20	Contours detected: 5	Expected: 2

	- Glyph name: uni1E21	Contours detected: 5	Expected: 3 or 4

	- Glyph name: uni1E24	Contours detected: 6	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 6	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E38	Contours detected: 4	Expected: 3

	- Glyph name: Lmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E3E	Contours detected: 5	Expected: 2

	- Glyph name: uni1E3F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E40	Contours detected: 5	Expected: 2

	- Glyph name: uni1E41	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 5	Expected: 2

	- Glyph name: uni1E43	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 6	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 6	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 7	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 7	Expected: 5

	- Glyph name: uni1E50	Contours detected: 6	Expected: 4

	- Glyph name: uni1E51	Contours detected: 6	Expected: 4

	- Glyph name: uni1E52	Contours detected: 6	Expected: 4

	- Glyph name: uni1E53	Contours detected: 6	Expected: 4

	- Glyph name: uni1E56	Contours detected: 5	Expected: 3

	- Glyph name: uni1E5A	Contours detected: 5	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5C	Contours detected: 6	Expected: 4

	- Glyph name: uni1E5D	Contours detected: 4	Expected: 3

	- Glyph name: Rmacronbelow	Contours detected: 5	Expected: 3

	- Glyph name: rmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E60	Contours detected: 4	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 4	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 5	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 5	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E78	Contours detected: 8	Expected: 3

	- Glyph name: uni1E79	Contours detected: 5	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 9	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 6	Expected: 4

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: wgrave	Contours detected: 5	Expected: 2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: uni1E8E	Contours detected: 4	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 4	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 6	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 5	Expected: 3

	- Glyph name: uni1EA2	Contours detected: 6	Expected: 3

	- Glyph name: uni1EA3	Contours detected: 5	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 7	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 6	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 7	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 6	Expected: 4

	- Glyph name: uni1EA8	Contours detected: 7	Expected: 4

	- Glyph name: uni1EA9	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 7	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAC	Contours detected: 7	Expected: 4

	- Glyph name: uni1EAD	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 7	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 7	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB2	Contours detected: 7	Expected: 4

	- Glyph name: uni1EB3	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 7	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB6	Contours detected: 7	Expected: 4

	- Glyph name: uni1EB7	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EB9	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBA	Contours detected: 4	Expected: 2

	- Glyph name: uni1EBB	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

	- Glyph name: uni1EBD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBE	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 6	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 6	Expected: 4

	- Glyph name: uni1EC2	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC3	Contours detected: 6	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 6	Expected: 4

	- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC7	Contours detected: 6	Expected: 4

	- Glyph name: uni1ECC	Contours detected: 5	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 5	Expected: 3

	- Glyph name: uni1ECE	Contours detected: 5	Expected: 3

	- Glyph name: uni1ECF	Contours detected: 5	Expected: 3

	- Glyph name: uni1ED0	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED4	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED5	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED8	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED9	Contours detected: 6	Expected: 4

	- Glyph name: uni1EDA	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EDB	Contours detected: 6	Expected: 3

	- Glyph name: uni1EDC	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EDD	Contours detected: 6	Expected: 3

	- Glyph name: uni1EDE	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EDF	Contours detected: 6	Expected: 3

	- Glyph name: uni1EE0	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EE1	Contours detected: 6	Expected: 3

	- Glyph name: uni1EE2	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EE3	Contours detected: 6	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 7	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 4	Expected: 2

	- Glyph name: uni1EE6	Contours detected: 7	Expected: 2

	- Glyph name: uni1EE7	Contours detected: 4	Expected: 2

	- Glyph name: uni1EE8	Contours detected: 8	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 5	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 8	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 5	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 8	Expected: 2

	- Glyph name: uni1EED	Contours detected: 5	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 8	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 5	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 8	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 5	Expected: 2

	- Glyph name: Ygrave	Contours detected: 4	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF4	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF6	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni2126	Contours detected: 3	Expected: 1

	- Glyph name: uni2153	Contours detected: 7	Expected: 3

	- Glyph name: uni2154	Contours detected: 7	Expected: 1 or 3

	- Glyph name: arrowboth	Contours detected: 2	Expected: 1

	- Glyph name: A	Contours detected: 5	Expected: 2

	- Glyph name: AE	Contours detected: 5	Expected: 2

	- Glyph name: Aacute	Contours detected: 6	Expected: 3

	- Glyph name: Abreve	Contours detected: 6	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 6	Expected: 3

	- Glyph name: Adieresis	Contours detected: 7	Expected: 4

	- Glyph name: Agrave	Contours detected: 6	Expected: 3

	- Glyph name: Amacron	Contours detected: 6	Expected: 3

	- Glyph name: Aogonek	Contours detected: 6	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 7	Expected: 3 or 4

	- Glyph name: Atilde	Contours detected: 6	Expected: 3

	- Glyph name: B	Contours detected: 7	Expected: 2 or 3

	- Glyph name: C	Contours detected: 3	Expected: 1

	- Glyph name: Cacute	Contours detected: 4	Expected: 2

	- Glyph name: Ccaron	Contours detected: 4	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Ccircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Cdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: D	Contours detected: 4	Expected: 2

	- Glyph name: Dcaron	Contours detected: 5	Expected: 3

	- Glyph name: E	Contours detected: 3	Expected: 1

	- Glyph name: Eacute	Contours detected: 4	Expected: 2

	- Glyph name: Ecaron	Contours detected: 4	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Edieresis	Contours detected: 5	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 4	Expected: 2

	- Glyph name: Egrave	Contours detected: 4	Expected: 2

	- Glyph name: Emacron	Contours detected: 4	Expected: 2

	- Glyph name: Eogonek	Contours detected: 4	Expected: 1 or 2

	- Glyph name: F	Contours detected: 4	Expected: 1

	- Glyph name: G	Contours detected: 4	Expected: 1

	- Glyph name: Gbreve	Contours detected: 5	Expected: 2

	- Glyph name: Gcaron	Contours detected: 5	Expected: 2

	- Glyph name: Gcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Gdotaccent	Contours detected: 5	Expected: 2

	- Glyph name: H	Contours detected: 5	Expected: 1

	- Glyph name: Hcircumflex	Contours detected: 6	Expected: 2

	- Glyph name: IJ	Contours detected: 5	Expected: 1 or 2

	- Glyph name: J	Contours detected: 4	Expected: 1

	- Glyph name: Jcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: K	Contours detected: 4	Expected: 1 or 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 4	Expected: 1

	- Glyph name: O	Contours detected: 4	Expected: 2

	- Glyph name: OE	Contours detected: 6	Expected: 2

	- Glyph name: Oacute	Contours detected: 5	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 5	Expected: 3

	- Glyph name: Odieresis	Contours detected: 6	Expected: 4

	- Glyph name: Ograve	Contours detected: 5	Expected: 3

	- Glyph name: Ohorn	Contours detected: 5	Expected: 2 or 3

	- Glyph name: Ohungarumlaut	Contours detected: 6	Expected: 4

	- Glyph name: Omacron	Contours detected: 5	Expected: 3

	- Glyph name: Otilde	Contours detected: 5	Expected: 3

	- Glyph name: P	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Q	Contours detected: 5	Expected: 2

	- Glyph name: R	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Racute	Contours detected: 5	Expected: 3

	- Glyph name: Rcaron	Contours detected: 5	Expected: 3

	- Glyph name: S	Contours detected: 3	Expected: 1

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: Scircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: U	Contours detected: 6	Expected: 1

	- Glyph name: Uacute	Contours detected: 7	Expected: 2

	- Glyph name: Ubreve	Contours detected: 7	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 7	Expected: 2

	- Glyph name: Udieresis	Contours detected: 8	Expected: 3

	- Glyph name: Ugrave	Contours detected: 7	Expected: 2

	- Glyph name: Uhorn	Contours detected: 7	Expected: 1

	- Glyph name: Uhungarumlaut	Contours detected: 8	Expected: 3

	- Glyph name: Umacron	Contours detected: 7	Expected: 2

	- Glyph name: Uogonek	Contours detected: 7	Expected: 1

	- Glyph name: Uring	Contours detected: 8	Expected: 3

	- Glyph name: Utilde	Contours detected: 7	Expected: 2

	- Glyph name: V	Contours detected: 4	Expected: 1

	- Glyph name: W	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: X	Contours detected: 5	Expected: 1

	- Glyph name: Y	Contours detected: 3	Expected: 1

	- Glyph name: Yacute	Contours detected: 4	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 5	Expected: 3

	- Glyph name: Ygrave	Contours detected: 4	Expected: 2

	- Glyph name: Z	Contours detected: 3	Expected: 1

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: a	Contours detected: 4	Expected: 2

	- Glyph name: aacute	Contours detected: 5	Expected: 3

	- Glyph name: abreve	Contours detected: 5	Expected: 3

	- Glyph name: acircumflex	Contours detected: 5	Expected: 3

	- Glyph name: adieresis	Contours detected: 6	Expected: 4

	- Glyph name: ae	Contours detected: 5	Expected: 3

	- Glyph name: agrave	Contours detected: 5	Expected: 3

	- Glyph name: amacron	Contours detected: 5	Expected: 3

	- Glyph name: ampersand	Contours detected: 6	Expected: 1, 2 or 3

	- Glyph name: aogonek	Contours detected: 5	Expected: 2

	- Glyph name: aring	Contours detected: 6	Expected: 4

	- Glyph name: arrowboth	Contours detected: 2	Expected: 1

	- Glyph name: at	Contours detected: 4	Expected: 2

	- Glyph name: atilde	Contours detected: 5	Expected: 3

	- Glyph name: b	Contours detected: 4	Expected: 2

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: c	Contours detected: 3	Expected: 1

	- Glyph name: cacute	Contours detected: 4	Expected: 2

	- Glyph name: ccaron	Contours detected: 4	Expected: 2

	- Glyph name: ccedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: ccircumflex	Contours detected: 4	Expected: 2

	- Glyph name: cdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: colon	Contours detected: 4	Expected: 2

	- Glyph name: copyright	Contours detected: 4	Expected: 3

	- Glyph name: d	Contours detected: 4	Expected: 2

	- Glyph name: dcaron	Contours detected: 5	Expected: 3

	- Glyph name: dcroat	Contours detected: 4	Expected: 2

	- Glyph name: divide	Contours detected: 5	Expected: 3

	- Glyph name: e	Contours detected: 4	Expected: 2

	- Glyph name: eacute	Contours detected: 5	Expected: 3

	- Glyph name: ecaron	Contours detected: 5	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 5	Expected: 3

	- Glyph name: edieresis	Contours detected: 6	Expected: 4

	- Glyph name: edotaccent	Contours detected: 5	Expected: 3

	- Glyph name: egrave	Contours detected: 5	Expected: 3

	- Glyph name: eight	Contours detected: 7	Expected: 3

	- Glyph name: emacron	Contours detected: 5	Expected: 3

	- Glyph name: eng	Contours detected: 3	Expected: 1

	- Glyph name: eogonek	Contours detected: 5	Expected: 2

	- Glyph name: eth	Contours detected: 3	Expected: 2

	- Glyph name: exclam	Contours detected: 4	Expected: 2

	- Glyph name: exclamdown	Contours detected: 4	Expected: 2

	- Glyph name: five	Contours detected: 4	Expected: 1

	- Glyph name: four	Contours detected: 4	Expected: 1 or 2

	- Glyph name: g	Contours detected: 4	Expected: 2 or 3

	- Glyph name: gbreve	Contours detected: 5	Expected: 3 or 4

	- Glyph name: gcaron	Contours detected: 5	Expected: 3 or 4

	- Glyph name: gcircumflex	Contours detected: 5	Expected: 3 or 4

	- Glyph name: gdotaccent	Contours detected: 5	Expected: 3 or 4

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: hbar	Contours detected: 3	Expected: 1

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: kgreenlandic	Contours detected: 4	Expected: 1 or 2

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: nine	Contours detected: 4	Expected: 1 or 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: numbersign	Contours detected: 4	Expected: 2

	- Glyph name: o	Contours detected: 4	Expected: 2

	- Glyph name: oacute	Contours detected: 5	Expected: 3

	- Glyph name: ocircumflex	Contours detected: 5	Expected: 3

	- Glyph name: odieresis	Contours detected: 6	Expected: 4

	- Glyph name: oe	Contours detected: 8	Expected: 3

	- Glyph name: ograve	Contours detected: 5	Expected: 3

	- Glyph name: ohorn	Contours detected: 5	Expected: 2

	- Glyph name: ohungarumlaut	Contours detected: 6	Expected: 4

	- Glyph name: omacron	Contours detected: 5	Expected: 3

	- Glyph name: one	Contours detected: 3	Expected: 1

	- Glyph name: otilde	Contours detected: 5	Expected: 3

	- Glyph name: paragraph	Contours detected: 5	Expected: 1, 2 or 3

	- Glyph name: question	Contours detected: 4	Expected: 2

	- Glyph name: questiondown	Contours detected: 4	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: scircumflex	Contours detected: 3	Expected: 2

	- Glyph name: semicolon	Contours detected: 3	Expected: 2

	- Glyph name: seven	Contours detected: 3	Expected: 1

	- Glyph name: six	Contours detected: 4	Expected: 1 or 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: three	Contours detected: 3	Expected: 1

	- Glyph name: two	Contours detected: 3	Expected: 1

	- Glyph name: u	Contours detected: 3	Expected: 1

	- Glyph name: uacute	Contours detected: 4	Expected: 2

	- Glyph name: ubreve	Contours detected: 4	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 4	Expected: 2

	- Glyph name: udieresis	Contours detected: 5	Expected: 3

	- Glyph name: ugrave	Contours detected: 4	Expected: 2

	- Glyph name: uhorn	Contours detected: 4	Expected: 1

	- Glyph name: uhungarumlaut	Contours detected: 5	Expected: 3

	- Glyph name: umacron	Contours detected: 4	Expected: 2

	- Glyph name: uni0122	Contours detected: 5	Expected: 2

	- Glyph name: uni0123	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni0136	Contours detected: 5	Expected: 2 or 3

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 5	Expected: 3

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0186	Contours detected: 3	Expected: 1

	- Glyph name: uni018F	Contours detected: 4	Expected: 2

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni01B7	Contours detected: 3	Expected: 1

	- Glyph name: uni01C3	Contours detected: 4	Expected: 2

	- Glyph name: uni01CD	Contours detected: 6	Expected: 3

	- Glyph name: uni01CE	Contours detected: 5	Expected: 3

	- Glyph name: uni01D1	Contours detected: 5	Expected: 3

	- Glyph name: uni01D2	Contours detected: 5	Expected: 3

	- Glyph name: uni01D3	Contours detected: 7	Expected: 2

	- Glyph name: uni01D4	Contours detected: 4	Expected: 2

	- Glyph name: uni01D5	Contours detected: 9	Expected: 4

	- Glyph name: uni01D6	Contours detected: 6	Expected: 4

	- Glyph name: uni01D7	Contours detected: 9	Expected: 4

	- Glyph name: uni01D8	Contours detected: 6	Expected: 4

	- Glyph name: uni01D9	Contours detected: 9	Expected: 4

	- Glyph name: uni01DA	Contours detected: 6	Expected: 4

	- Glyph name: uni01DB	Contours detected: 9	Expected: 4

	- Glyph name: uni01DC	Contours detected: 6	Expected: 4

	- Glyph name: uni01DE	Contours detected: 8	Expected: 5

	- Glyph name: uni01DF	Contours detected: 7	Expected: 5

	- Glyph name: uni01E0	Contours detected: 7	Expected: 4

	- Glyph name: uni01E1	Contours detected: 6	Expected: 4

	- Glyph name: uni01E2	Contours detected: 6	Expected: 3

	- Glyph name: uni01E3	Contours detected: 6	Expected: 4

	- Glyph name: uni01E4	Contours detected: 5	Expected: 1

	- Glyph name: uni01E5	Contours detected: 5	Expected: 2

	- Glyph name: uni01E8	Contours detected: 5	Expected: 2

	- Glyph name: uni01E9	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 6	Expected: 3

	- Glyph name: uni01ED	Contours detected: 6	Expected: 3

	- Glyph name: uni01EE	Contours detected: 4	Expected: 2

	- Glyph name: uni01EF	Contours detected: 4	Expected: 2

	- Glyph name: uni01F0	Contours detected: 3	Expected: 2

	- Glyph name: uni01F9	Contours detected: 3	Expected: 2

	- Glyph name: uni0218	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni021E	Contours detected: 6	Expected: 2

	- Glyph name: uni021F	Contours detected: 3	Expected: 2

	- Glyph name: uni0226	Contours detected: 6	Expected: 3

	- Glyph name: uni0227	Contours detected: 5	Expected: 3

	- Glyph name: uni0228	Contours detected: 4	Expected: 1

	- Glyph name: uni0229	Contours detected: 5	Expected: 2

	- Glyph name: uni022A	Contours detected: 7	Expected: 5

	- Glyph name: uni022B	Contours detected: 7	Expected: 5

	- Glyph name: uni022C	Contours detected: 6	Expected: 4

	- Glyph name: uni022D	Contours detected: 6	Expected: 4

	- Glyph name: uni022E	Contours detected: 5	Expected: 3

	- Glyph name: uni022F	Contours detected: 5	Expected: 3

	- Glyph name: uni0230	Contours detected: 6	Expected: 4

	- Glyph name: uni0231	Contours detected: 6	Expected: 4

	- Glyph name: uni0232	Contours detected: 4	Expected: 2

	- Glyph name: uni0233	Contours detected: 3	Expected: 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni023A	Contours detected: 5	Expected: 3

	- Glyph name: uni023D	Contours detected: 3	Expected: 1

	- Glyph name: uni023E	Contours detected: 3	Expected: 2

	- Glyph name: uni0241	Contours detected: 2	Expected: 1

	- Glyph name: uni0247	Contours detected: 6	Expected: 4

	- Glyph name: uni0259	Contours detected: 4	Expected: 2

	- Glyph name: uni0292	Contours detected: 3	Expected: 1

	- Glyph name: uni0312	Contours detected: 2	Expected: 1

	- Glyph name: uni1E00	Contours detected: 7	Expected: 4

	- Glyph name: uni1E01	Contours detected: 6	Expected: 4

	- Glyph name: uni1E02	Contours detected: 8	Expected: 4

	- Glyph name: uni1E03	Contours detected: 5	Expected: 3

	- Glyph name: uni1E08	Contours detected: 5	Expected: 2

	- Glyph name: uni1E09	Contours detected: 5	Expected: 2

	- Glyph name: uni1E0A	Contours detected: 5	Expected: 3

	- Glyph name: uni1E0B	Contours detected: 5	Expected: 3

	- Glyph name: uni1E0C	Contours detected: 5	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E14	Contours detected: 5	Expected: 3

	- Glyph name: uni1E15	Contours detected: 6	Expected: 4

	- Glyph name: uni1E16	Contours detected: 5	Expected: 3

	- Glyph name: uni1E17	Contours detected: 6	Expected: 4

	- Glyph name: uni1E1C	Contours detected: 5	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 6	Expected: 3

	- Glyph name: uni1E1E	Contours detected: 5	Expected: 2

	- Glyph name: uni1E20	Contours detected: 5	Expected: 2

	- Glyph name: uni1E21	Contours detected: 5	Expected: 3 or 4

	- Glyph name: uni1E24	Contours detected: 6	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E2A	Contours detected: 6	Expected: 2

	- Glyph name: uni1E2B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E36	Contours detected: 3	Expected: 2

	- Glyph name: uni1E38	Contours detected: 4	Expected: 3

	- Glyph name: uni1E3E	Contours detected: 5	Expected: 2

	- Glyph name: uni1E3F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E40	Contours detected: 5	Expected: 2

	- Glyph name: uni1E41	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 5	Expected: 2

	- Glyph name: uni1E43	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E4C	Contours detected: 6	Expected: 4

	- Glyph name: uni1E4D	Contours detected: 6	Expected: 4

	- Glyph name: uni1E4E	Contours detected: 7	Expected: 5

	- Glyph name: uni1E4F	Contours detected: 7	Expected: 5

	- Glyph name: uni1E50	Contours detected: 6	Expected: 4

	- Glyph name: uni1E51	Contours detected: 6	Expected: 4

	- Glyph name: uni1E52	Contours detected: 6	Expected: 4

	- Glyph name: uni1E53	Contours detected: 6	Expected: 4

	- Glyph name: uni1E56	Contours detected: 5	Expected: 3

	- Glyph name: uni1E5A	Contours detected: 5	Expected: 3

	- Glyph name: uni1E5B	Contours detected: 3	Expected: 2

	- Glyph name: uni1E5C	Contours detected: 6	Expected: 4

	- Glyph name: uni1E5D	Contours detected: 4	Expected: 3

	- Glyph name: uni1E60	Contours detected: 4	Expected: 2

	- Glyph name: uni1E61	Contours detected: 3	Expected: 2

	- Glyph name: uni1E62	Contours detected: 4	Expected: 2

	- Glyph name: uni1E63	Contours detected: 3	Expected: 2

	- Glyph name: uni1E64	Contours detected: 5	Expected: 3

	- Glyph name: uni1E65	Contours detected: 4	Expected: 3

	- Glyph name: uni1E66	Contours detected: 5	Expected: 3

	- Glyph name: uni1E67	Contours detected: 4	Expected: 3

	- Glyph name: uni1E68	Contours detected: 5	Expected: 3

	- Glyph name: uni1E69	Contours detected: 4	Expected: 3

	- Glyph name: uni1E78	Contours detected: 8	Expected: 3

	- Glyph name: uni1E79	Contours detected: 5	Expected: 3

	- Glyph name: uni1E7A	Contours detected: 9	Expected: 4

	- Glyph name: uni1E7B	Contours detected: 6	Expected: 4

	- Glyph name: uni1E8E	Contours detected: 4	Expected: 2

	- Glyph name: uni1E8F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E92	Contours detected: 4	Expected: 2

	- Glyph name: uni1EA0	Contours detected: 6	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 5	Expected: 3

	- Glyph name: uni1EA2	Contours detected: 6	Expected: 3

	- Glyph name: uni1EA3	Contours detected: 5	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 7	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 6	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 7	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 6	Expected: 4

	- Glyph name: uni1EA8	Contours detected: 7	Expected: 4

	- Glyph name: uni1EA9	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 7	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAC	Contours detected: 7	Expected: 4

	- Glyph name: uni1EAD	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 7	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 7	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB2	Contours detected: 7	Expected: 4

	- Glyph name: uni1EB3	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 7	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB6	Contours detected: 7	Expected: 4

	- Glyph name: uni1EB7	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EB9	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBA	Contours detected: 4	Expected: 2

	- Glyph name: uni1EBB	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

	- Glyph name: uni1EBD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBE	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 6	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 6	Expected: 4

	- Glyph name: uni1EC2	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC3	Contours detected: 6	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 6	Expected: 4

	- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC7	Contours detected: 6	Expected: 4

	- Glyph name: uni1ECC	Contours detected: 5	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 5	Expected: 3

	- Glyph name: uni1ECE	Contours detected: 5	Expected: 3

	- Glyph name: uni1ECF	Contours detected: 5	Expected: 3

	- Glyph name: uni1ED0	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED4	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED5	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED8	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED9	Contours detected: 6	Expected: 4

	- Glyph name: uni1EDA	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EDB	Contours detected: 6	Expected: 3

	- Glyph name: uni1EDC	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EDD	Contours detected: 6	Expected: 3

	- Glyph name: uni1EDE	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EDF	Contours detected: 6	Expected: 3

	- Glyph name: uni1EE0	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EE1	Contours detected: 6	Expected: 3

	- Glyph name: uni1EE2	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni1EE3	Contours detected: 6	Expected: 3

	- Glyph name: uni1EE4	Contours detected: 7	Expected: 2

	- Glyph name: uni1EE5	Contours detected: 4	Expected: 2

	- Glyph name: uni1EE6	Contours detected: 7	Expected: 2

	- Glyph name: uni1EE7	Contours detected: 4	Expected: 2

	- Glyph name: uni1EE8	Contours detected: 8	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 5	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 8	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 5	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 8	Expected: 2

	- Glyph name: uni1EED	Contours detected: 5	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 8	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 5	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 8	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 5	Expected: 2

	- Glyph name: uni1EF4	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF5	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF6	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF7	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

	- Glyph name: uni2126	Contours detected: 3	Expected: 1

	- Glyph name: uogonek	Contours detected: 4	Expected: 1

	- Glyph name: uring	Contours detected: 5	Expected: 3

	- Glyph name: utilde	Contours detected: 4	Expected: 2

	- Glyph name: v	Contours detected: 4	Expected: 1

	- Glyph name: w	Contours detected: 4	Expected: 1

	- Glyph name: wacute	Contours detected: 5	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: wgrave	Contours detected: 5	Expected: 2

	- Glyph name: x	Contours detected: 3	Expected: 1

	- Glyph name: y	Contours detected: 2	Expected: 1

	- Glyph name: yacute	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: zero	Contours detected: 4	Expected: 2 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 499 among a set of 2 math glyphs.
The following math glyphs have a different width, though:

Width = 572:
equal

Width = 486:
greater

Width = 413:
logicalnot

Width = 586:
plusminus

Width = 460:
multiply

Width = 555:
divide

Width = 600:
greaterequal, minus

Width = 477:
approxequal

Width = 545:
notequal

Width = 577:
lessequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Euro (U+20AC): L<<232.0,311.0>--<274.0,310.0>> -> L<<274.0,310.0>--<289.0,310.0>>

	* Euro (U+20AC): L<<77.0,371.0>--<64.0,371.0>> -> L<<64.0,371.0>--<1.0,372.0>>

	* Euro (U+20AC): L<<9.0,312.0>--<38.0,311.0>> -> L<<38.0,311.0>--<78.0,311.0>>

	* M (U+004D): L<<603.0,303.0>--<604.0,315.0>> -> L<<604.0,315.0>--<604.0,616.0>>

	* Oslash (U+00D8): L<<437.0,663.0>--<431.0,663.0>> -> L<<431.0,663.0>--<119.0,663.0>>

	* Oslashacute (U+01FE): L<<437.0,663.0>--<431.0,663.0>> -> L<<431.0,663.0>--<119.0,663.0>>

	* dagger (U+2020): L<<178.0,581.0>--<178.0,494.0>> -> L<<178.0,494.0>--<179.0,372.0>>

	* degree (U+00B0): L<<41.0,428.0>--<44.0,583.0>> -> L<<44.0,583.0>--<40.0,646.0>>

	* eth (U+00F0): L<<253.0,464.0>--<223.0,464.0>> -> L<<223.0,464.0>--<126.0,472.0>>

	* notequal (U+2260): L<<79.0,393.0>--<108.0,392.0>> -> L<<108.0,392.0>--<137.0,392.0>>

	* ordmasculine (U+00BA): L<<31.0,476.0>--<34.0,523.0>> -> L<<34.0,523.0>--<30.0,686.0>>

	* p (U+0070): L<<40.0,122.0>--<42.0,419.0>> -> L<<42.0,419.0>--<42.0,446.0>>

	* percent (U+0025): L<<31.0,478.0>--<34.0,583.0>> -> L<<34.0,583.0>--<30.0,646.0>>

	* perthousand (U+2030): L<<561.0,190.0>--<558.0,85.0>> -> L<<558.0,85.0>--<562.0,22.0>>

	* perthousand (U+2030): L<<823.0,188.0>--<820.0,83.0>> -> L<<820.0,83.0>--<824.0,20.0>>

	* s (U+0073): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* sacute (U+015B): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* scaron (U+0161): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* scedilla (U+015F): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* scircumflex (U+015D): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* three (U+0033): L<<279.0,0.0>--<268.0,0.0>> -> L<<268.0,0.0>--<82.0,3.0>>

	* uni018F (U+018F): L<<112.0,40.0>--<122.0,40.0>> -> L<<122.0,40.0>--<451.0,34.0>>

	* uni018F (U+018F): L<<200.0,697.0>--<396.0,700.0>> -> L<<396.0,700.0>--<407.0,700.0>>

	* uni018F (U+018F): L<<465.0,330.0>--<451.0,330.0>> -> L<<451.0,330.0>--<126.0,336.0>>

	* uni01C2 (U+01C2): L<<62.0,509.0>--<81.0,508.0>> -> L<<81.0,508.0>--<100.0,508.0>>

	* uni0219 (U+0219): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* uni02D7 (U+02D7): L<<321.0,435.0>--<82.0,437.0>> -> L<<82.0,437.0>--<67.0,437.0>>

	* uni1DBF (U+1DBF): L<<31.0,478.0>--<34.0,583.0>> -> L<<34.0,583.0>--<33.0,620.0>>

	* uni1DBF (U+1DBF): L<<34.0,583.0>--<33.0,620.0>> -> L<<33.0,620.0>--<30.0,746.0>>

	* uni1E3E (U+1E3E): L<<603.0,303.0>--<604.0,315.0>> -> L<<604.0,315.0>--<604.0,616.0>>

	* uni1E40 (U+1E40): L<<603.0,303.0>--<604.0,315.0>> -> L<<604.0,315.0>--<604.0,616.0>>

	* uni1E42 (U+1E42): L<<603.0,303.0>--<604.0,315.0>> -> L<<604.0,315.0>--<604.0,616.0>>

	* uni1E55 (U+1E55): L<<40.0,122.0>--<42.0,419.0>> -> L<<42.0,419.0>--<42.0,446.0>>

	* uni1E57 (U+1E57): L<<40.0,122.0>--<42.0,419.0>> -> L<<42.0,419.0>--<42.0,446.0>>

	* uni1E61 (U+1E61): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* uni1E63 (U+1E63): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* uni1E65 (U+1E65): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* uni1E67 (U+1E67): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* uni1E69 (U+1E69): L<<372.0,228.0>--<374.0,217.0>> -> L<<374.0,217.0>--<376.0,201.0>>

	* uni2070 (U+2070): L<<31.0,467.0>--<34.0,672.0>> -> L<<34.0,672.0>--<30.0,735.0>>

	* uni2080 (U+2080): L<<31.0,-134.0>--<34.0,71.0>> -> L<<34.0,71.0>--<30.0,134.0>>

	* uni2153 (U+2153): L<<1190.0,0.0>--<1179.0,0.0>> -> L<<1179.0,0.0>--<993.0,3.0>>

	* uni2154 (U+2154): L<<1208.0,0.0>--<1197.0,0.0>> -> L<<1197.0,0.0>--<1011.0,3.0>>

	* uniA7A8 (U+A7A8): L<<396.0,333.0>--<312.0,334.0>> -> L<<312.0,334.0>--<310.0,334.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* copyright (U+00A9): B<<213.5,395.5>-<213.0,388.0>-<212.0,394.0>>/B<<212.0,394.0>-<212.0,387.0>-<217.0,376.5>> = 9.462322208025613

	* copyright (U+00A9): B<<294.0,214.0>-<309.0,212.0>-<338.0,205.0>>/B<<338.0,205.0>-<335.0,206.0>-<342.0,206.5>> = 4.864514437760454

	* copyright (U+00A9): B<<344.0,204.0>-<345.0,204.0>-<340.0,205.0>>/L<<340.0,205.0>--<344.0,204.0>> = 2.726310993906212

	* notequal (U+2260): L<<172.0,184.0>--<192.0,210.0>>/B<<192.0,210.0>-<186.0,203.0>-<196.5,216.5>> = 3.032702616176968 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<391.0,180.0>--<392.0,304.0>>

	* D (U+0044): L<<76.0,308.0>--<75.0,60.0>>

	* Dcaron (U+010E): L<<76.0,308.0>--<75.0,60.0>>

	* Dcroat (U+0110): L<<105.0,323.0>--<104.0,94.0>>

	* Dmacronbelow (U+1E0E): L<<76.0,308.0>--<75.0,60.0>>

	* Eth (U+00D0): L<<125.0,329.0>--<124.0,94.0>>

	* G (U+0047): L<<368.0,0.0>--<152.0,-1.0>>

	* Gbreve (U+011E): L<<368.0,0.0>--<152.0,-1.0>>

	* Gcaron (U+01E6): L<<368.0,0.0>--<152.0,-1.0>>

	* Gcircumflex (U+011C): L<<368.0,0.0>--<152.0,-1.0>>

	* Gdotaccent (U+0120): L<<368.0,0.0>--<152.0,-1.0>>

	* R (U+0052): L<<49.0,337.0>--<50.0,654.0>>

	* R (U+0052): L<<84.0,650.0>--<82.0,384.0>>

	* Racute (U+0154): L<<49.0,337.0>--<50.0,654.0>>

	* Racute (U+0154): L<<84.0,650.0>--<82.0,384.0>>

	* Rcaron (U+0158): L<<49.0,337.0>--<50.0,654.0>>

	* Rcaron (U+0158): L<<84.0,650.0>--<82.0,384.0>>

	* Rmacronbelow (U+1E5E): L<<49.0,337.0>--<50.0,654.0>>

	* Rmacronbelow (U+1E5E): L<<84.0,650.0>--<82.0,384.0>>

	* Upsilonlatin (U+01B1): L<<124.0,41.0>--<356.0,42.0>>

	* b (U+0062): L<<45.0,26.0>--<40.0,665.0>>

	* b (U+0062): L<<94.0,451.0>--<422.0,450.0>>

	* bmacronbelow (U+1E07): L<<45.0,26.0>--<40.0,665.0>>

	* bmacronbelow (U+1E07): L<<94.0,451.0>--<422.0,450.0>>

	* d (U+0064): L<<109.0,33.0>--<348.0,34.0>>

	* d (U+0064): L<<317.0,1.0>--<78.0,0.0>>

	* d (U+0064): L<<399.0,496.0>--<398.0,654.0>>

	* d (U+0064): L<<429.0,665.0>--<432.0,27.0>>

	* d (U+0064): L<<65.0,450.0>--<383.0,451.0>>

	* dagger (U+2020): L<<178.0,494.0>--<179.0,372.0>>

	* dcaron (U+010F): L<<109.0,33.0>--<348.0,34.0>>

	* dcaron (U+010F): L<<317.0,1.0>--<78.0,0.0>>

	* dcaron (U+010F): L<<399.0,496.0>--<398.0,654.0>>

	* dcaron (U+010F): L<<429.0,665.0>--<432.0,27.0>>

	* dcaron (U+010F): L<<65.0,450.0>--<383.0,451.0>>

	* dcroat (U+0111): L<<109.0,33.0>--<348.0,34.0>>

	* dcroat (U+0111): L<<317.0,1.0>--<78.0,0.0>>

	* dcroat (U+0111): L<<429.0,587.0>--<432.0,27.0>>

	* dcroat (U+0111): L<<65.0,450.0>--<383.0,451.0>>

	* dmacronbelow (U+1E0F): L<<109.0,33.0>--<348.0,34.0>>

	* dmacronbelow (U+1E0F): L<<317.0,1.0>--<78.0,0.0>>

	* dmacronbelow (U+1E0F): L<<399.0,496.0>--<398.0,654.0>>

	* dmacronbelow (U+1E0F): L<<429.0,665.0>--<432.0,27.0>>

	* dmacronbelow (U+1E0F): L<<65.0,450.0>--<383.0,451.0>>

	* dollar (U+0024): L<<256.0,338.0>--<255.0,202.0>>

	* five (U+0035): L<<410.0,432.0>--<409.0,50.0>>

	* four (U+0034): L<<46.0,51.0>--<276.0,50.0>>

	* h (U+0068): L<<425.0,20.0>--<422.0,393.0>>

	* hbar (U+0127): L<<425.0,20.0>--<422.0,393.0>>

	* hcircumflex (U+0125): L<<425.0,20.0>--<422.0,393.0>>

	* infinity (U+221E): L<<37.0,381.0>--<38.0,519.0>>

	* ordfeminine (U+00AA): L<<42.0,617.0>--<182.0,616.0>>

	* p (U+0070): L<<40.0,122.0>--<42.0,419.0>>

	* p (U+0070): L<<76.0,213.0>--<75.0,-54.0>>

	* two (U+0032): L<<46.0,50.0>--<45.0,362.0>>

	* uni0122 (U+0122): L<<368.0,0.0>--<152.0,-1.0>>

	* uni0156 (U+0156): L<<49.0,337.0>--<50.0,654.0>>

	* uni0156 (U+0156): L<<84.0,650.0>--<82.0,384.0>>

	* uni0190 (U+0190): L<<338.0,666.0>--<106.0,665.0>>

	* uni01E2 (U+01E2): L<<391.0,180.0>--<392.0,304.0>>

	* uni01E4 (U+01E4): L<<368.0,0.0>--<152.0,-1.0>>

	* uni01F4 (U+01F4): L<<368.0,0.0>--<152.0,-1.0>>

	* uni0210 (U+0210): L<<49.0,337.0>--<50.0,654.0>>

	* uni0210 (U+0210): L<<84.0,650.0>--<82.0,384.0>>

	* uni0212 (U+0212): L<<49.0,337.0>--<50.0,654.0>>

	* uni0212 (U+0212): L<<84.0,650.0>--<82.0,384.0>>

	* uni021F (U+021F): L<<425.0,20.0>--<422.0,393.0>>

	* uni023A (U+023A): L<<110.0,304.0>--<111.0,180.0>>

	* uni02D7 (U+02D7): L<<321.0,435.0>--<82.0,437.0>>

	* uni1E03 (U+1E03): L<<45.0,26.0>--<40.0,665.0>>

	* uni1E03 (U+1E03): L<<94.0,451.0>--<422.0,450.0>>

	* uni1E05 (U+1E05): L<<45.0,26.0>--<40.0,665.0>>

	* uni1E05 (U+1E05): L<<94.0,451.0>--<422.0,450.0>>

	* uni1E0A (U+1E0A): L<<76.0,308.0>--<75.0,60.0>>

	* uni1E0B (U+1E0B): L<<109.0,33.0>--<348.0,34.0>>

	* uni1E0B (U+1E0B): L<<317.0,1.0>--<78.0,0.0>>

	* uni1E0B (U+1E0B): L<<399.0,496.0>--<398.0,654.0>>

	* uni1E0B (U+1E0B): L<<429.0,665.0>--<432.0,27.0>>

	* uni1E0B (U+1E0B): L<<65.0,450.0>--<383.0,451.0>>

	* uni1E0C (U+1E0C): L<<76.0,308.0>--<75.0,60.0>>

	* uni1E0D (U+1E0D): L<<109.0,33.0>--<348.0,34.0>>

	* uni1E0D (U+1E0D): L<<317.0,1.0>--<78.0,0.0>>

	* uni1E0D (U+1E0D): L<<399.0,496.0>--<398.0,654.0>>

	* uni1E0D (U+1E0D): L<<429.0,665.0>--<432.0,27.0>>

	* uni1E0D (U+1E0D): L<<65.0,450.0>--<383.0,451.0>>

	* uni1E10 (U+1E10): L<<76.0,308.0>--<75.0,60.0>>

	* uni1E11 (U+1E11): L<<109.0,33.0>--<348.0,34.0>>

	* uni1E11 (U+1E11): L<<317.0,1.0>--<78.0,0.0>>

	* uni1E11 (U+1E11): L<<399.0,496.0>--<398.0,654.0>>

	* uni1E11 (U+1E11): L<<429.0,665.0>--<432.0,27.0>>

	* uni1E11 (U+1E11): L<<65.0,450.0>--<383.0,451.0>>

	* uni1E12 (U+1E12): L<<76.0,308.0>--<75.0,60.0>>

	* uni1E13 (U+1E13): L<<109.0,33.0>--<348.0,34.0>>

	* uni1E13 (U+1E13): L<<317.0,1.0>--<78.0,0.0>>

	* uni1E13 (U+1E13): L<<399.0,496.0>--<398.0,654.0>>

	* uni1E13 (U+1E13): L<<429.0,665.0>--<432.0,27.0>>

	* uni1E13 (U+1E13): L<<65.0,450.0>--<383.0,451.0>>

	* uni1E20 (U+1E20): L<<368.0,0.0>--<152.0,-1.0>>

	* uni1E23 (U+1E23): L<<425.0,20.0>--<422.0,393.0>>

	* uni1E25 (U+1E25): L<<425.0,20.0>--<422.0,393.0>>

	* uni1E27 (U+1E27): L<<425.0,20.0>--<422.0,393.0>>

	* uni1E29 (U+1E29): L<<425.0,20.0>--<422.0,393.0>>

	* uni1E2B (U+1E2B): L<<425.0,20.0>--<422.0,393.0>>

	* uni1E55 (U+1E55): L<<40.0,122.0>--<42.0,419.0>>

	* uni1E55 (U+1E55): L<<76.0,213.0>--<75.0,-54.0>>

	* uni1E57 (U+1E57): L<<40.0,122.0>--<42.0,419.0>>

	* uni1E57 (U+1E57): L<<76.0,213.0>--<75.0,-54.0>>

	* uni1E58 (U+1E58): L<<49.0,337.0>--<50.0,654.0>>

	* uni1E58 (U+1E58): L<<84.0,650.0>--<82.0,384.0>>

	* uni1E5A (U+1E5A): L<<49.0,337.0>--<50.0,654.0>>

	* uni1E5A (U+1E5A): L<<84.0,650.0>--<82.0,384.0>>

	* uni1E5C (U+1E5C): L<<49.0,337.0>--<50.0,654.0>>

	* uni1E5C (U+1E5C): L<<84.0,650.0>--<82.0,384.0>>

	* uni2076 (U+2076): L<<69.0,612.0>--<184.0,613.0>>

	* uni2079 (U+2079): L<<162.0,596.0>--<42.0,595.0>>

	* uni2086 (U+2086): L<<69.0,11.0>--<184.0,12.0>>

	* uni2089 (U+2089): L<<162.0,2.0>--<42.0,1.0>>

	* uni2126 (U+2126): L<<328.0,713.0>--<565.0,712.0>>

	* uni2154 (U+2154): L<<46.0,50.0>--<45.0,362.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i̊ i̋ i̍ i̐ i̓ i᷆ i᷇ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: ĭ i̇ i̒ i᷄ i᷅ ĭ̛ i̛̇ i̛̊ i̛̋ i̛̍ i̛̐ i̛̒ i̛̓ i̛᷄ i̛᷅ i̛᷆ i̛᷇ ĭ̥ i̥̇ i̥̊

Your font does *not* cover the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Navajo (Latn, 166,319 speakers), Avokaya (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Basaa (Latn, 332,940 speakers), Dutch (Latn, 31,709,104 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ejagham (Latn, 120,000 speakers), Kom (Latn, 360,685 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 8 | 12 | 123 | 7 | 102 | 0 |
| 0% | 3% | 5% | 49% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
