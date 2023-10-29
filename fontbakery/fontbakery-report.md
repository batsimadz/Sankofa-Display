## FontBakery report

fontbakery version: 0.10.1

<details><summary><b>[20] Sankofa-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)


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


	- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


	- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


	- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


	- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


	- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


	- 0x014A (LATIN CAPITAL LETTER ENG)


	- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


	- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


	- 0x016C (LATIN CAPITAL LETTER U WITH BREVE)


	- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


	- 0x011F (LATIN SMALL LETTER G WITH BREVE)


	- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


	- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


	- 0x0131 (LATIN SMALL LETTER DOTLESS I)


	- 0x014B (LATIN SMALL LETTER ENG)


	- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


	- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


	- 0x016D (LATIN SMALL LETTER U WITH BREVE)


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
"Copyright 2023 Sankofa Display (https://github.com/batsimadz/Sankofa)" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1041, but got 1000 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 220, but got 200 instead [code: descent]
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
* 🔥 **FAIL** Glyph "Iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03060301" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03060309" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03060303" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03060303" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni03020303" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030B" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0306" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "tildecomb" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0328" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: germandbls	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: germandbls	Expected: 1

	- Glyph name: uni1E9E	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: exclam	Contours detected: 4	Expected: 2

	- Glyph name: numbersign	Contours detected: 3	Expected: 2

	- Glyph name: colon	Contours detected: 4	Expected: 2

	- Glyph name: semicolon	Contours detected: 3	Expected: 2

	- Glyph name: question	Contours detected: 4	Expected: 2

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: B	Contours detected: 5	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: F	Contours detected: 3	Expected: 1

	- Glyph name: G	Contours detected: 3	Expected: 1

	- Glyph name: H	Contours detected: 3	Expected: 1

	- Glyph name: I	Contours detected: 3	Expected: 1

	- Glyph name: J	Contours detected: 3	Expected: 1

	- Glyph name: K	Contours detected: 3	Expected: 1 or 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: S	Contours detected: 3	Expected: 1

	- Glyph name: T	Contours detected: 3	Expected: 1

	- Glyph name: U	Contours detected: 4	Expected: 1

	- Glyph name: V	Contours detected: 3	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: X	Contours detected: 3	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Z	Contours detected: 3	Expected: 1

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: c	Contours detected: 2	Expected: 1

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: k	Contours detected: 3	Expected: 1 or 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: q	Contours detected: 4	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: t	Contours detected: 2	Expected: 1

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: v	Contours detected: 3	Expected: 1

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: x	Contours detected: 3	Expected: 1

	- Glyph name: y	Contours detected: 3	Expected: 1

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: exclamdown	Contours detected: 4	Expected: 2

	- Glyph name: questiondown	Contours detected: 4	Expected: 2

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Igrave	Contours detected: 4	Expected: 2

	- Glyph name: Iacute	Contours detected: 4	Expected: 2

	- Glyph name: Icircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Idieresis	Contours detected: 5	Expected: 3

	- Glyph name: Ugrave	Contours detected: 5	Expected: 2

	- Glyph name: Uacute	Contours detected: 5	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Udieresis	Contours detected: 6	Expected: 3

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: eth	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: yacute	Contours detected: 4	Expected: 2

	- Glyph name: ydieresis	Contours detected: 5	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1 or 2

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: uni0122	Contours detected: 4	Expected: 2

	- Glyph name: uni0123	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Imacron	Contours detected: 4	Expected: 2

	- Glyph name: Iogonek	Contours detected: 4	Expected: 1 or 2

	- Glyph name: IJ	Contours detected: 6	Expected: 1 or 2

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

	- Glyph name: uni0137	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 5	Expected: 3

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: Scedilla	Contours detected: 4	Expected: 1 or 2

	- Glyph name: scedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: uni0162	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0163	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Tcaron	Contours detected: 4	Expected: 2

	- Glyph name: tcaron	Contours detected: 3	Expected: 2

	- Glyph name: Umacron	Contours detected: 5	Expected: 2

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: Uring	Contours detected: 6	Expected: 3

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: Uhungarumlaut	Contours detected: 6	Expected: 3

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 5	Expected: 1

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: zacute	Contours detected: 3	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: zcaron	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 5	Expected: 1

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0312	Contours detected: 2	Expected: 1

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: wgrave	Contours detected: 3	Expected: 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: ygrave	Contours detected: 4	Expected: 2

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: AE	Contours detected: 3	Expected: 2

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: B	Contours detected: 5	Expected: 2 or 3

	- Glyph name: C	Contours detected: 2	Expected: 1

	- Glyph name: Cacute	Contours detected: 3	Expected: 2

	- Glyph name: Ccaron	Contours detected: 3	Expected: 2

	- Glyph name: Ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: D	Contours detected: 3	Expected: 2

	- Glyph name: Dcaron	Contours detected: 4	Expected: 3

	- Glyph name: E	Contours detected: 2	Expected: 1

	- Glyph name: Eacute	Contours detected: 3	Expected: 2

	- Glyph name: Ecaron	Contours detected: 3	Expected: 2

	- Glyph name: Ecircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Edieresis	Contours detected: 4	Expected: 3

	- Glyph name: Edotaccent	Contours detected: 3	Expected: 2

	- Glyph name: Egrave	Contours detected: 3	Expected: 2

	- Glyph name: Emacron	Contours detected: 3	Expected: 2

	- Glyph name: Eogonek	Contours detected: 3	Expected: 1 or 2

	- Glyph name: F	Contours detected: 3	Expected: 1

	- Glyph name: G	Contours detected: 3	Expected: 1

	- Glyph name: H	Contours detected: 3	Expected: 1

	- Glyph name: I	Contours detected: 3	Expected: 1

	- Glyph name: IJ	Contours detected: 6	Expected: 1 or 2

	- Glyph name: Iacute	Contours detected: 4	Expected: 2

	- Glyph name: Icircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Idieresis	Contours detected: 5	Expected: 3

	- Glyph name: Igrave	Contours detected: 4	Expected: 2

	- Glyph name: Imacron	Contours detected: 4	Expected: 2

	- Glyph name: Iogonek	Contours detected: 4	Expected: 1 or 2

	- Glyph name: J	Contours detected: 3	Expected: 1

	- Glyph name: K	Contours detected: 3	Expected: 1 or 2

	- Glyph name: L	Contours detected: 2	Expected: 1

	- Glyph name: Lacute	Contours detected: 3	Expected: 2

	- Glyph name: Lcaron	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: M	Contours detected: 3	Expected: 1

	- Glyph name: OE	Contours detected: 3	Expected: 2

	- Glyph name: Q	Contours detected: 4	Expected: 2

	- Glyph name: R	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Racute	Contours detected: 4	Expected: 3

	- Glyph name: Rcaron	Contours detected: 4	Expected: 3

	- Glyph name: S	Contours detected: 3	Expected: 1

	- Glyph name: Sacute	Contours detected: 4	Expected: 2

	- Glyph name: Scaron	Contours detected: 4	Expected: 2

	- Glyph name: T	Contours detected: 3	Expected: 1

	- Glyph name: Tcaron	Contours detected: 4	Expected: 2

	- Glyph name: U	Contours detected: 4	Expected: 1

	- Glyph name: Uacute	Contours detected: 5	Expected: 2

	- Glyph name: Ucircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Udieresis	Contours detected: 6	Expected: 3

	- Glyph name: Ugrave	Contours detected: 5	Expected: 2

	- Glyph name: Uhorn	Contours detected: 5	Expected: 1

	- Glyph name: Uhungarumlaut	Contours detected: 6	Expected: 3

	- Glyph name: Umacron	Contours detected: 5	Expected: 2

	- Glyph name: Uogonek	Contours detected: 5	Expected: 1

	- Glyph name: Uring	Contours detected: 6	Expected: 3

	- Glyph name: V	Contours detected: 3	Expected: 1

	- Glyph name: W	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Wacute	Contours detected: 4	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 4	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 5	Expected: 3

	- Glyph name: Wgrave	Contours detected: 4	Expected: 2

	- Glyph name: X	Contours detected: 3	Expected: 1

	- Glyph name: Y	Contours detected: 2	Expected: 1

	- Glyph name: Yacute	Contours detected: 3	Expected: 2

	- Glyph name: Ycircumflex	Contours detected: 3	Expected: 2

	- Glyph name: Ydieresis	Contours detected: 4	Expected: 3

	- Glyph name: Ygrave	Contours detected: 3	Expected: 2

	- Glyph name: Z	Contours detected: 3	Expected: 1

	- Glyph name: Zacute	Contours detected: 4	Expected: 2

	- Glyph name: Zcaron	Contours detected: 4	Expected: 2

	- Glyph name: Zdotaccent	Contours detected: 4	Expected: 2

	- Glyph name: a	Contours detected: 3	Expected: 2

	- Glyph name: aacute	Contours detected: 4	Expected: 3

	- Glyph name: abreve	Contours detected: 4	Expected: 3

	- Glyph name: acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: adieresis	Contours detected: 5	Expected: 4

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: agrave	Contours detected: 4	Expected: 3

	- Glyph name: amacron	Contours detected: 4	Expected: 3

	- Glyph name: aogonek	Contours detected: 4	Expected: 2

	- Glyph name: aring	Contours detected: 5	Expected: 4

	- Glyph name: atilde	Contours detected: 4	Expected: 3

	- Glyph name: b	Contours detected: 3	Expected: 2

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: c	Contours detected: 2	Expected: 1

	- Glyph name: cacute	Contours detected: 3	Expected: 2

	- Glyph name: ccaron	Contours detected: 3	Expected: 2

	- Glyph name: ccedilla	Contours detected: 3	Expected: 1 or 2

	- Glyph name: colon	Contours detected: 4	Expected: 2

	- Glyph name: d	Contours detected: 3	Expected: 2

	- Glyph name: dcaron	Contours detected: 4	Expected: 3

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: e	Contours detected: 3	Expected: 2

	- Glyph name: eacute	Contours detected: 4	Expected: 3

	- Glyph name: ecaron	Contours detected: 4	Expected: 3

	- Glyph name: ecircumflex	Contours detected: 4	Expected: 3

	- Glyph name: edieresis	Contours detected: 5	Expected: 4

	- Glyph name: edotaccent	Contours detected: 4	Expected: 3

	- Glyph name: egrave	Contours detected: 4	Expected: 3

	- Glyph name: emacron	Contours detected: 4	Expected: 3

	- Glyph name: eogonek	Contours detected: 4	Expected: 2

	- Glyph name: eth	Contours detected: 3	Expected: 2

	- Glyph name: exclam	Contours detected: 4	Expected: 2

	- Glyph name: exclamdown	Contours detected: 4	Expected: 2

	- Glyph name: f	Contours detected: 2	Expected: 1

	- Glyph name: h	Contours detected: 2	Expected: 1

	- Glyph name: ij	Contours detected: 5	Expected: 3 or 4

	- Glyph name: j	Contours detected: 3	Expected: 2

	- Glyph name: k	Contours detected: 3	Expected: 1 or 2

	- Glyph name: l	Contours detected: 2	Expected: 1

	- Glyph name: lacute	Contours detected: 3	Expected: 2

	- Glyph name: lcaron	Contours detected: 3	Expected: 2

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: n	Contours detected: 2	Expected: 1

	- Glyph name: nacute	Contours detected: 3	Expected: 2

	- Glyph name: ncaron	Contours detected: 3	Expected: 2

	- Glyph name: ntilde	Contours detected: 3	Expected: 2

	- Glyph name: numbersign	Contours detected: 3	Expected: 2

	- Glyph name: oe	Contours detected: 5	Expected: 3

	- Glyph name: q	Contours detected: 4	Expected: 2

	- Glyph name: question	Contours detected: 4	Expected: 2

	- Glyph name: questiondown	Contours detected: 4	Expected: 2

	- Glyph name: r	Contours detected: 2	Expected: 1

	- Glyph name: racute	Contours detected: 3	Expected: 2

	- Glyph name: rcaron	Contours detected: 3	Expected: 2

	- Glyph name: s	Contours detected: 2	Expected: 1

	- Glyph name: sacute	Contours detected: 3	Expected: 2

	- Glyph name: scaron	Contours detected: 3	Expected: 2

	- Glyph name: semicolon	Contours detected: 3	Expected: 2

	- Glyph name: t	Contours detected: 2	Expected: 1

	- Glyph name: tcaron	Contours detected: 3	Expected: 2

	- Glyph name: u	Contours detected: 2	Expected: 1

	- Glyph name: uacute	Contours detected: 3	Expected: 2

	- Glyph name: ucircumflex	Contours detected: 3	Expected: 2

	- Glyph name: udieresis	Contours detected: 4	Expected: 3

	- Glyph name: ugrave	Contours detected: 3	Expected: 2

	- Glyph name: uhungarumlaut	Contours detected: 4	Expected: 3

	- Glyph name: umacron	Contours detected: 3	Expected: 2

	- Glyph name: uni0122	Contours detected: 4	Expected: 2

	- Glyph name: uni0123	Contours detected: 5	Expected: 3 or 4

	- Glyph name: uni0136	Contours detected: 4	Expected: 2 or 3

	- Glyph name: uni0137	Contours detected: 4	Expected: 2 or 3

	- Glyph name: uni013B	Contours detected: 3	Expected: 2

	- Glyph name: uni013C	Contours detected: 3	Expected: 2

	- Glyph name: uni0146	Contours detected: 3	Expected: 2

	- Glyph name: uni0156	Contours detected: 4	Expected: 3

	- Glyph name: uni0157	Contours detected: 3	Expected: 2

	- Glyph name: uni0162	Contours detected: 4	Expected: 1 or 2

	- Glyph name: uni0163	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni0237	Contours detected: 2	Expected: 1

	- Glyph name: uni0312	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 3	Expected: 1

	- Glyph name: uring	Contours detected: 4	Expected: 3

	- Glyph name: v	Contours detected: 3	Expected: 1

	- Glyph name: w	Contours detected: 2	Expected: 1

	- Glyph name: wacute	Contours detected: 3	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 3	Expected: 2

	- Glyph name: wdieresis	Contours detected: 4	Expected: 3

	- Glyph name: wgrave	Contours detected: 3	Expected: 2

	- Glyph name: x	Contours detected: 3	Expected: 1

	- Glyph name: y	Contours detected: 3	Expected: 1

	- Glyph name: yacute	Contours detected: 4	Expected: 2

	- Glyph name: ycircumflex	Contours detected: 4	Expected: 2

	- Glyph name: ydieresis	Contours detected: 5	Expected: 3

	- Glyph name: ygrave	Contours detected: 4	Expected: 2

	- Glyph name: z	Contours detected: 2	Expected: 1

	- Glyph name: zacute	Contours detected: 3	Expected: 2

	- Glyph name: zcaron	Contours detected: 3	Expected: 2

	- Glyph name: zdotaccent	Contours detected: 3	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, canadian-aboriginal, tai-le, coptic, math, syriac, malayalam, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni004A0301

	- uni006A0301

	- uni03020300

	- uni03020301

	- uni03020303

	- uni03020309

	- uni03060300

	- uni03060301

	- uni03060303

	- uni03060309
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* M (U+004D): L<<633.0,303.0>--<634.0,315.0>> -> L<<634.0,315.0>--<634.0,616.0>>

	* OE (U+0152): L<<446.0,3.0>--<444.0,3.0>> -> L<<444.0,3.0>--<412.0,3.0>>

	* Oslash (U+00D8): L<<437.0,663.0>--<431.0,663.0>> -> L<<431.0,663.0>--<119.0,663.0>>

	* eth (U+00F0): L<<253.0,464.0>--<223.0,464.0>> -> L<<223.0,464.0>--<126.0,472.0>>

	* s (U+0073): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>>

	* sacute (U+015B): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>>

	* scaron (U+0161): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>>

	* scedilla (U+015F): L<<402.0,228.0>--<404.0,217.0>> -> L<<404.0,217.0>--<406.0,201.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<391.0,180.0>--<392.0,304.0>>

	* D (U+0044): L<<105.0,329.0>--<104.0,94.0>>

	* Dcaron (U+010E): L<<105.0,329.0>--<104.0,94.0>>

	* Dcroat (U+0110): L<<105.0,329.0>--<104.0,94.0>>

	* Eth (U+00D0): L<<125.0,329.0>--<124.0,94.0>>

	* R (U+0052): L<<114.0,650.0>--<112.0,384.0>>

	* R (U+0052): L<<79.0,337.0>--<80.0,654.0>>

	* Racute (U+0154): L<<114.0,650.0>--<112.0,384.0>>

	* Racute (U+0154): L<<79.0,337.0>--<80.0,654.0>>

	* Rcaron (U+0158): L<<114.0,650.0>--<112.0,384.0>>

	* Rcaron (U+0158): L<<79.0,337.0>--<80.0,654.0>>

	* b (U+0062): L<<119.0,451.0>--<417.0,450.0>>

	* b (U+0062): L<<70.0,35.0>--<73.0,665.0>>

	* d (U+0064): L<<139.0,33.0>--<358.0,34.0>>

	* d (U+0064): L<<327.0,1.0>--<108.0,0.0>>

	* d (U+0064): L<<409.0,496.0>--<408.0,654.0>>

	* d (U+0064): L<<439.0,665.0>--<442.0,27.0>>

	* d (U+0064): L<<95.0,450.0>--<393.0,451.0>>

	* dcaron (U+010F): L<<139.0,33.0>--<358.0,34.0>>

	* dcaron (U+010F): L<<327.0,1.0>--<108.0,0.0>>

	* dcaron (U+010F): L<<409.0,496.0>--<408.0,654.0>>

	* dcaron (U+010F): L<<439.0,665.0>--<442.0,27.0>>

	* dcaron (U+010F): L<<95.0,450.0>--<393.0,451.0>>

	* dcroat (U+0111): L<<139.0,33.0>--<358.0,34.0>>

	* dcroat (U+0111): L<<327.0,1.0>--<108.0,0.0>>

	* dcroat (U+0111): L<<439.0,587.0>--<442.0,27.0>>

	* dcroat (U+0111): L<<95.0,450.0>--<393.0,451.0>>

	* e (U+0065): L<<104.0,450.0>--<470.0,448.0>>

	* eacute (U+00E9): L<<104.0,450.0>--<470.0,448.0>>

	* ecaron (U+011B): L<<104.0,450.0>--<470.0,448.0>>

	* ecircumflex (U+00EA): L<<104.0,450.0>--<470.0,448.0>>

	* edieresis (U+00EB): L<<104.0,450.0>--<470.0,448.0>>

	* edotaccent (U+0117): L<<104.0,450.0>--<470.0,448.0>>

	* egrave (U+00E8): L<<104.0,450.0>--<470.0,448.0>>

	* emacron (U+0113): L<<104.0,450.0>--<470.0,448.0>>

	* eogonek (U+0119): L<<104.0,450.0>--<470.0,448.0>>

	* h (U+0068): L<<455.0,20.0>--<452.0,393.0>>

	* oe (U+0153): L<<439.0,448.0>--<805.0,446.0>>

	* uni0156 (U+0156): L<<114.0,650.0>--<112.0,384.0>>

	* uni0156 (U+0156): L<<79.0,337.0>--<80.0,654.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: ĩ ĭ i̇ ỉ ǐ i̒ ĩ̛ ĭ̛ i̛̇ ỉ̛ i̛̊ i̛̋ ǐ̛ i̛̒ ị̃ ị̆ ị̇ ị̉ ị̊ ị̋

Your font fully covers the following languages that require the soft-dotted feature: Igbo (Latn, 27,823,640 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ma’di (Latn, 584,000 speakers), Basaa (Latn, 332,940 speakers), Dutch (Latn, 31,709,104 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Lithuanian (Latn, 2,357,094 speakers), Dan (Latn, 1,099,244 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 10 | 10 | 125 | 7 | 100 | 0 |
| 0% | 4% | 4% | 50% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
