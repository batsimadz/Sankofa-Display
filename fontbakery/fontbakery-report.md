## FontBakery report

fontbakery version: 0.10.1

<details><summary><b>[19] SankofaDisplay-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00A0 (NO-BREAK SPACE)


	- 0x007C (VERTICAL LINE)


	- 0x002B (PLUS SIGN)


	- 0x00D7 (MULTIPLICATION SIGN)


	- 0x00F7 (DIVISION SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003C (LESS-THAN SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x00B0 (DEGREE SIGN)


	- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


	- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


	- 0x014B (LATIN SMALL LETTER ENG)


	- 0x00AA (FEMININE ORDINAL INDICATOR)


	- 0x00BA (MASCULINE ORDINAL INDICATOR)


	- 0x0040 (COMMERCIAL AT)


	- 0x0026 (AMPERSAND)


	- 0x00B6 (PILCROW SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x20AC (EURO SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x2212 (MINUS SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


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


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1027, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 213, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.1, while a newer 0.10.2 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains glyphs for whitespace characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphs">com.google.fonts/check/whitespace_glyphs</a>)</summary><div>


* 🔥 **FAIL** Whitespace glyph missing for codepoint 0x00A0. [code: missing-whitespace-glyph-0x00A0]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Glyph "Abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EBC" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Itilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni01EA" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni01EC" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Utilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EF8" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni1EBD" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "itilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni01EB" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni01ED" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "utilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, syriac, canadian-aboriginal, tai-le, tifinagh, math, malayalam, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, syriac, caucasian-albanian, tifinagh, gothic
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese
 * U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
 * U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
 * U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
 * U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese
 * U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese
 * U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- f.alt

	- i.loclTRK

	- j.alt

	- l.alt

	- q.alt

	- t.alt

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
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: exclam	Contours detected: 4	Expected: 2

	- Glyph name: numbersign	Contours detected: 4	Expected: 2

	- Glyph name: zero	Contours detected: 4	Expected: 2 or 3

	- Glyph name: two	Contours detected: 3	Expected: 1

	- Glyph name: four	Contours detected: 4	Expected: 1 or 2

	- Glyph name: five	Contours detected: 3	Expected: 1

	- Glyph name: seven	Contours detected: 3	Expected: 1

	- Glyph name: eight	Contours detected: 7	Expected: 3

	- Glyph name: nine	Contours detected: 4	Expected: 1 or 2

	- Glyph name: colon	Contours detected: 4	Expected: 2

	- Glyph name: semicolon	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 4	Expected: 2

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

	- Glyph name: z	Contours detected: 3	Expected: 1

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: exclamdown	Contours detected: 4	Expected: 2

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

	- Glyph name: IJ	Contours detected: 5	Expected: 1 or 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Jcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: uni0136	Contours detected: 5	Expected: 2 or 3

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: Omacron	Contours detected: 5	Expected: 3

	- Glyph name: omacron	Contours detected: 5	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 6	Expected: 4

	- Glyph name: ohungarumlaut	Contours detected: 6	Expected: 4

	- Glyph name: OE	Contours detected: 5	Expected: 2

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

	- Glyph name: zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 4	Expected: 2

	- Glyph name: Uhorn	Contours detected: 7	Expected: 1

	- Glyph name: uni01CD	Contours detected: 6	Expected: 3

	- Glyph name: uni01CE	Contours detected: 5	Expected: 3

	- Glyph name: uni01D1	Contours detected: 5	Expected: 3

	- Glyph name: uni01D2	Contours detected: 5	Expected: 3

	- Glyph name: uni01D3	Contours detected: 7	Expected: 2

	- Glyph name: uni01D4	Contours detected: 4	Expected: 2

	- Glyph name: uni01DE	Contours detected: 8	Expected: 5

	- Glyph name: uni01DF	Contours detected: 7	Expected: 5

	- Glyph name: Gcaron	Contours detected: 5	Expected: 2

	- Glyph name: gcaron	Contours detected: 5	Expected: 3 or 4

	- Glyph name: uni01E8	Contours detected: 5	Expected: 2

	- Glyph name: uni01E9	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 5	Expected: 2

	- Glyph name: uni01EB	Contours detected: 5	Expected: 2

	- Glyph name: uni01EC	Contours detected: 6	Expected: 3

	- Glyph name: uni01ED	Contours detected: 6	Expected: 3

	- Glyph name: uni0218	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0228	Contours detected: 4	Expected: 1

	- Glyph name: uni0229	Contours detected: 5	Expected: 2

	- Glyph name: uni022A	Contours detected: 7	Expected: 5

	- Glyph name: uni022B	Contours detected: 7	Expected: 5

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0312	Contours detected: 2	Expected: 1

	- Glyph name: uni1E0C	Contours detected: 5	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 5	Expected: 3

	- Glyph name: Dmacronbelow	Contours detected: 5	Expected: 3

	- Glyph name: dmacronbelow	Contours detected: 5	Expected: 3

	- Glyph name: uni1E14	Contours detected: 5	Expected: 3

	- Glyph name: uni1E15	Contours detected: 6	Expected: 4

	- Glyph name: uni1E16	Contours detected: 5	Expected: 3

	- Glyph name: uni1E17	Contours detected: 6	Expected: 4

	- Glyph name: uni1E20	Contours detected: 5	Expected: 2

	- Glyph name: uni1E21	Contours detected: 5	Expected: 3 or 4

	- Glyph name: uni1E24	Contours detected: 6	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E3E	Contours detected: 5	Expected: 2

	- Glyph name: uni1E3F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 5	Expected: 2

	- Glyph name: uni1E43	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: nmacronbelow	Contours detected: 3	Expected: 2

	- Glyph name: uni1E50	Contours detected: 6	Expected: 4

	- Glyph name: uni1E51	Contours detected: 6	Expected: 4

	- Glyph name: uni1E52	Contours detected: 6	Expected: 4

	- Glyph name: uni1E53	Contours detected: 6	Expected: 4

	- Glyph name: uni1E62	Contours detected: 4	Expected: 2

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: wgrave	Contours detected: 5	Expected: 2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: uni1EA1	Contours detected: 5	Expected: 3

	- Glyph name: uni1EAC	Contours detected: 7	Expected: 4

	- Glyph name: uni1EAD	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EB9	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

	- Glyph name: uni1EBD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC7	Contours detected: 6	Expected: 4

	- Glyph name: uni1ECC	Contours detected: 5	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 5	Expected: 3

	- Glyph name: uni1ED8	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED9	Contours detected: 6	Expected: 4

	- Glyph name: Ygrave	Contours detected: 4	Expected: 2

	- Glyph name: ygrave	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

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

	- Glyph name: OE	Contours detected: 5	Expected: 2

	- Glyph name: Oacute	Contours detected: 5	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 5	Expected: 3

	- Glyph name: Odieresis	Contours detected: 6	Expected: 4

	- Glyph name: Ograve	Contours detected: 5	Expected: 3

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

	- Glyph name: aogonek	Contours detected: 5	Expected: 2

	- Glyph name: aring	Contours detected: 6	Expected: 4

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

	- Glyph name: d	Contours detected: 4	Expected: 2

	- Glyph name: dcaron	Contours detected: 5	Expected: 3

	- Glyph name: dcroat	Contours detected: 4	Expected: 2

	- Glyph name: e	Contours detected: 4	Expected: 2

	- Glyph name: eacute	Contours detected: 5	Expected: 3

	- Glyph name: ecaron	Contours detected: 5	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 5	Expected: 3

	- Glyph name: edieresis	Contours detected: 6	Expected: 4

	- Glyph name: edotaccent	Contours detected: 5	Expected: 3

	- Glyph name: egrave	Contours detected: 5	Expected: 3

	- Glyph name: eight	Contours detected: 7	Expected: 3

	- Glyph name: emacron	Contours detected: 5	Expected: 3

	- Glyph name: eogonek	Contours detected: 5	Expected: 2

	- Glyph name: eth	Contours detected: 3	Expected: 2

	- Glyph name: exclam	Contours detected: 4	Expected: 2

	- Glyph name: exclamdown	Contours detected: 4	Expected: 2

	- Glyph name: five	Contours detected: 3	Expected: 1

	- Glyph name: four	Contours detected: 4	Expected: 1 or 2

	- Glyph name: g	Contours detected: 4	Expected: 2 or 3

	- Glyph name: gbreve	Contours detected: 5	Expected: 3 or 4

	- Glyph name: gcaron	Contours detected: 5	Expected: 3 or 4

	- Glyph name: gcircumflex	Contours detected: 5	Expected: 3 or 4

	- Glyph name: gdotaccent	Contours detected: 5	Expected: 3 or 4

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: hcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: jcircumflex	Contours detected: 3	Expected: 2

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

	- Glyph name: ohungarumlaut	Contours detected: 6	Expected: 4

	- Glyph name: omacron	Contours detected: 5	Expected: 3

	- Glyph name: otilde	Contours detected: 5	Expected: 3

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

	- Glyph name: two	Contours detected: 3	Expected: 1

	- Glyph name: u	Contours detected: 3	Expected: 1

	- Glyph name: uacute	Contours detected: 4	Expected: 2

	- Glyph name: ubreve	Contours detected: 4	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 4	Expected: 2

	- Glyph name: udieresis	Contours detected: 5	Expected: 3

	- Glyph name: ugrave	Contours detected: 4	Expected: 2

	- Glyph name: uhungarumlaut	Contours detected: 5	Expected: 3

	- Glyph name: umacron	Contours detected: 4	Expected: 2

	- Glyph name: uni0122	Contours detected: 5	Expected: 2

	- Glyph name: uni0123	Contours detected: 6	Expected: 3 or 4

	- Glyph name: uni0136	Contours detected: 5	Expected: 2 or 3

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 5	Expected: 3

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni01CD	Contours detected: 6	Expected: 3

	- Glyph name: uni01CE	Contours detected: 5	Expected: 3

	- Glyph name: uni01D1	Contours detected: 5	Expected: 3

	- Glyph name: uni01D2	Contours detected: 5	Expected: 3

	- Glyph name: uni01D3	Contours detected: 7	Expected: 2

	- Glyph name: uni01D4	Contours detected: 4	Expected: 2

	- Glyph name: uni01DE	Contours detected: 8	Expected: 5

	- Glyph name: uni01DF	Contours detected: 7	Expected: 5

	- Glyph name: uni01E8	Contours detected: 5	Expected: 2

	- Glyph name: uni01E9	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 6	Expected: 3

	- Glyph name: uni01ED	Contours detected: 6	Expected: 3

	- Glyph name: uni0218	Contours detected: 4	Expected: 2

	- Glyph name: uni0219	Contours detected: 3	Expected: 2

	- Glyph name: uni0228	Contours detected: 4	Expected: 1

	- Glyph name: uni0229	Contours detected: 5	Expected: 2

	- Glyph name: uni022A	Contours detected: 7	Expected: 5

	- Glyph name: uni022B	Contours detected: 7	Expected: 5

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0312	Contours detected: 2	Expected: 1

	- Glyph name: uni1E0C	Contours detected: 5	Expected: 3

	- Glyph name: uni1E0D	Contours detected: 5	Expected: 3

	- Glyph name: uni1E14	Contours detected: 5	Expected: 3

	- Glyph name: uni1E15	Contours detected: 6	Expected: 4

	- Glyph name: uni1E16	Contours detected: 5	Expected: 3

	- Glyph name: uni1E17	Contours detected: 6	Expected: 4

	- Glyph name: uni1E20	Contours detected: 5	Expected: 2

	- Glyph name: uni1E21	Contours detected: 5	Expected: 3 or 4

	- Glyph name: uni1E24	Contours detected: 6	Expected: 2

	- Glyph name: uni1E25	Contours detected: 3	Expected: 2

	- Glyph name: uni1E3E	Contours detected: 5	Expected: 2

	- Glyph name: uni1E3F	Contours detected: 3	Expected: 2

	- Glyph name: uni1E42	Contours detected: 5	Expected: 2

	- Glyph name: uni1E43	Contours detected: 3	Expected: 2

	- Glyph name: uni1E45	Contours detected: 3	Expected: 2

	- Glyph name: uni1E47	Contours detected: 3	Expected: 2

	- Glyph name: uni1E50	Contours detected: 6	Expected: 4

	- Glyph name: uni1E51	Contours detected: 6	Expected: 4

	- Glyph name: uni1E52	Contours detected: 6	Expected: 4

	- Glyph name: uni1E53	Contours detected: 6	Expected: 4

	- Glyph name: uni1E62	Contours detected: 4	Expected: 2

	- Glyph name: uni1EA1	Contours detected: 5	Expected: 3

	- Glyph name: uni1EAC	Contours detected: 7	Expected: 4

	- Glyph name: uni1EAD	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EB9	Contours detected: 5	Expected: 3

	- Glyph name: uni1EBC	Contours detected: 4	Expected: 2

	- Glyph name: uni1EBD	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC6	Contours detected: 5	Expected: 3

	- Glyph name: uni1EC7	Contours detected: 6	Expected: 4

	- Glyph name: uni1ECC	Contours detected: 5	Expected: 3

	- Glyph name: uni1ECD	Contours detected: 5	Expected: 3

	- Glyph name: uni1ED8	Contours detected: 6	Expected: 4

	- Glyph name: uni1ED9	Contours detected: 6	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 4	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 3	Expected: 2

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

	- Glyph name: z	Contours detected: 3	Expected: 1

	- Glyph name: zacute	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: zero	Contours detected: 4	Expected: 2 or 3
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* M (U+004D): L<<633.0,303.0>--<634.0,315.0>> -> L<<634.0,315.0>--<634.0,616.0>>

	* Oslash (U+00D8): L<<437.0,663.0>--<431.0,663.0>> -> L<<431.0,663.0>--<119.0,663.0>>

	* eth (U+00F0): L<<253.0,464.0>--<223.0,464.0>> -> L<<223.0,464.0>--<126.0,472.0>>

	* s (U+0073): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>>

	* sacute (U+015B): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>>

	* scaron (U+0161): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>>

	* scedilla (U+015F): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>>

	* scircumflex (U+015D): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>>

	* three (U+0033): L<<300.0,0.0>--<289.0,0.0>> -> L<<289.0,0.0>--<103.0,3.0>>

	* uni0219 (U+0219): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>>

	* uni1E3E (U+1E3E): L<<633.0,303.0>--<634.0,315.0>> -> L<<634.0,315.0>--<634.0,616.0>>

	* uni1E42 (U+1E42): L<<633.0,303.0>--<634.0,315.0>> -> L<<634.0,315.0>--<634.0,616.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<391.0,180.0>--<392.0,304.0>>

	* D (U+0044): L<<106.0,308.0>--<105.0,60.0>>

	* Dcaron (U+010E): L<<106.0,308.0>--<105.0,60.0>>

	* Dcroat (U+0110): L<<105.0,329.0>--<104.0,94.0>>

	* Dmacronbelow (U+1E0E): L<<106.0,308.0>--<105.0,60.0>>

	* Eth (U+00D0): L<<125.0,329.0>--<124.0,94.0>>

	* G (U+0047): L<<398.0,0.0>--<182.0,-1.0>>

	* Gbreve (U+011E): L<<398.0,0.0>--<182.0,-1.0>>

	* Gcaron (U+01E6): L<<398.0,0.0>--<182.0,-1.0>>

	* Gcircumflex (U+011C): L<<398.0,0.0>--<182.0,-1.0>>

	* Gdotaccent (U+0120): L<<398.0,0.0>--<182.0,-1.0>>

	* R (U+0052): L<<114.0,650.0>--<112.0,384.0>>

	* R (U+0052): L<<79.0,337.0>--<80.0,654.0>>

	* Racute (U+0154): L<<114.0,650.0>--<112.0,384.0>>

	* Racute (U+0154): L<<79.0,337.0>--<80.0,654.0>>

	* Rcaron (U+0158): L<<114.0,650.0>--<112.0,384.0>>

	* Rcaron (U+0158): L<<79.0,337.0>--<80.0,654.0>>

	* b (U+0062): L<<124.0,451.0>--<452.0,450.0>>

	* b (U+0062): L<<75.0,26.0>--<70.0,665.0>>

	* d (U+0064): L<<139.0,33.0>--<378.0,34.0>>

	* d (U+0064): L<<347.0,1.0>--<108.0,0.0>>

	* d (U+0064): L<<429.0,496.0>--<428.0,654.0>>

	* d (U+0064): L<<459.0,665.0>--<462.0,27.0>>

	* d (U+0064): L<<95.0,450.0>--<413.0,451.0>>

	* dcaron (U+010F): L<<139.0,33.0>--<378.0,34.0>>

	* dcaron (U+010F): L<<347.0,1.0>--<108.0,0.0>>

	* dcaron (U+010F): L<<429.0,496.0>--<428.0,654.0>>

	* dcaron (U+010F): L<<459.0,665.0>--<462.0,27.0>>

	* dcaron (U+010F): L<<95.0,450.0>--<413.0,451.0>>

	* dcroat (U+0111): L<<139.0,33.0>--<378.0,34.0>>

	* dcroat (U+0111): L<<347.0,1.0>--<108.0,0.0>>

	* dcroat (U+0111): L<<459.0,587.0>--<462.0,27.0>>

	* dcroat (U+0111): L<<95.0,450.0>--<413.0,451.0>>

	* dmacronbelow (U+1E0F): L<<139.0,33.0>--<378.0,34.0>>

	* dmacronbelow (U+1E0F): L<<347.0,1.0>--<108.0,0.0>>

	* dmacronbelow (U+1E0F): L<<429.0,496.0>--<428.0,654.0>>

	* dmacronbelow (U+1E0F): L<<459.0,665.0>--<462.0,27.0>>

	* dmacronbelow (U+1E0F): L<<95.0,450.0>--<413.0,451.0>>

	* five (U+0035): L<<96.0,607.0>--<97.0,382.0>>

	* four (U+0034): L<<46.0,51.0>--<276.0,50.0>>

	* h (U+0068): L<<455.0,20.0>--<452.0,393.0>>

	* hcircumflex (U+0125): L<<455.0,20.0>--<452.0,393.0>>

	* two (U+0032): L<<67.0,50.0>--<66.0,362.0>>

	* uni0122 (U+0122): L<<398.0,0.0>--<182.0,-1.0>>

	* uni0156 (U+0156): L<<114.0,650.0>--<112.0,384.0>>

	* uni0156 (U+0156): L<<79.0,337.0>--<80.0,654.0>>

	* uni1E05 (U+1E05): L<<124.0,451.0>--<452.0,450.0>>

	* uni1E05 (U+1E05): L<<75.0,26.0>--<70.0,665.0>>

	* uni1E0C (U+1E0C): L<<106.0,308.0>--<105.0,60.0>>

	* uni1E0D (U+1E0D): L<<139.0,33.0>--<378.0,34.0>>

	* uni1E0D (U+1E0D): L<<347.0,1.0>--<108.0,0.0>>

	* uni1E0D (U+1E0D): L<<429.0,496.0>--<428.0,654.0>>

	* uni1E0D (U+1E0D): L<<459.0,665.0>--<462.0,27.0>>

	* uni1E0D (U+1E0D): L<<95.0,450.0>--<413.0,451.0>>

	* uni1E20 (U+1E20): L<<398.0,0.0>--<182.0,-1.0>>

	* uni1E25 (U+1E25): L<<455.0,20.0>--<452.0,393.0>>

	* zero (U+0030): L<<58.0,32.0>--<207.0,33.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i̊ i̋ i̓ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĭ i̇ ỉ i̒ ĭ̛ i̛̇ ỉ̛ i̛̊ i̛̋ i̛̒ i̛̓ ị̆ ị̇ ị̉ ị̊ ị̋ ị̒ ị̓ ĭ̦ i̦̇

Your font does *not* cover the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Nateni (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Ejagham (Latn, 120,000 speakers), Dutch (Latn, 31,709,104 speakers), Igbo (Latn, 27,823,640 speakers), Lugbara (Latn, 2,200,000 speakers), Navajo (Latn, 166,319 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 9 | 10 | 125 | 7 | 101 | 0 |
| 0% | 4% | 4% | 50% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
