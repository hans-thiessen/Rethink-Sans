## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Rethink Sans Medium: 992
Rethink Sans ExtraBold: 991
Rethink Sans Bold: 992
Rethink Sans Regular: 992 [code: sTypoAscender-mismatch]
* 🔥 **FAIL** sTypoDescender is not the same across the family:
Rethink Sans Medium: -310
Rethink Sans ExtraBold: -309
Rethink Sans Bold: -310
Rethink Sans Regular: -310 [code: sTypoDescender-mismatch]
* 🔥 **FAIL** usWinAscent is not the same across the family:
Rethink Sans Medium: 992
Rethink Sans ExtraBold: 991
Rethink Sans Bold: 992
Rethink Sans Regular: 992 [code: usWinAscent-mismatch]
* 🔥 **FAIL** usWinDescent is not the same across the family:
Rethink Sans Medium: 310
Rethink Sans ExtraBold: 309
Rethink Sans Bold: 310
Rethink Sans Regular: 310 [code: usWinDescent-mismatch]
* 🔥 **FAIL** ascent is not the same across the family:
Rethink Sans Medium: 992
Rethink Sans ExtraBold: 991
Rethink Sans Bold: 992
Rethink Sans Regular: 992 [code: ascent-mismatch]
* 🔥 **FAIL** descent is not the same across the family:
Rethink Sans Medium: -310
Rethink Sans ExtraBold: -309
Rethink Sans Bold: -310
Rethink Sans Regular: -310 [code: descent-mismatch]
</div></details><br></div></details><details><summary><b>[19] RethinkSans-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2014-2017 indian type foundry with reserved font name 'poppins'."

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2014-2017 Indian Type Foundry with Reserved Font Name 'Poppins'. Copyright 2019 Google LLC with Reserved Name 'DM Sans'. Copyright 2022 Rethink Communications LLP with Reserved Name 'Rethink Sans'." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/RethinkSans-Medium.ttf', 'fonts/ttf/RethinkSans-ExtraBold.ttf', 'fonts/ttf/RethinkSans-Bold.ttf', 'fonts/ttf/RethinkSans-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1006, but got 992 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- E + less

	- R + E

	- less + greater

	- greater + less

	- f + i

	- i + l

	- hyphen + hyphen

	- hyphen + greater

	- greater + hyphen

	- parenleft + R

	- R + parenright

	- parenright + eight

	- eight + parenright

	- parenright + five

	- five + parenright

	- parenright + four

	- four + parenright

	- parenright + nine

	- nine + parenright

	- parenright + one

	- one + parenright

	- parenright + seven

	- seven + parenright

	- parenright + six

	- six + parenright

	- parenright + three

	- three + parenright

	- parenright + two

	- two + parenright

	- parenright + zero

	- zero + parenright

	- braceleft + eight

	- eight + braceright

	- braceright + five

	- five + braceright

	- braceright + four

	- four + braceright

	- braceright + nine

	- nine + braceright

	- braceright + one

	- one + braceright

	- braceright + seven

	- seven + braceright

	- braceright + six

	- six + braceright

	- braceright + three

	- three + braceright

	- braceright + two

	- two + braceright

	- braceright + zero

	- zero + braceright

	- registered + plus 

	- And less + hyphen [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ('Poppins'. Copyright 2019 Google LLC with Reserved Name 'DM Sans'. Copyright 2022 Rethink Communications LLP with Reserved Name 'Rethink Sans') that differs from the currently used family name (RethinkSans), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- gravecomb.cap

	- tildecomb.cap

	- uni0302.cap

	- uni0304.cap

	- uni0306.cap

	- uni0307.cap

	- uni0308.cap

	- uni030A.cap

	- uni030B.cap

	- uni030C.alt

	- uni0327.cap 

	- And uni0328.cap
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: quotedbl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0308	Contours detected: 1	Expected: 2

	- Glyph name: quotedblright	Contours detected: 1	Expected: 2

	- Glyph name: perthousand	Contours detected: 5	Expected: 6 or 7

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: uni2783	Contours detected: 3	Expected: 4

	- Glyph name: perthousand	Contours detected: 5	Expected: 6 or 7

	- Glyph name: quotedbl	Contours detected: 1	Expected: 2

	- Glyph name: quotedblright	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0308	Contours detected: 1	Expected: 2

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- And Glyph name: uni2783	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=172.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=304.0,Y=701.0 (should be at cap-height 700?)

	* at (U+0040): X=772.0,Y=-1.0 (should be at baseline 0?)

	* m (U+006D): X=857.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=595.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=483.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=269.0,Y=1.0 (should be at baseline 0?)

	* x (U+0078): X=477.0,Y=1.0 (should be at baseline 0?)

	* adieresis (U+00E4): X=173.0,Y=701.0 (should be at cap-height 700?)

	* adieresis (U+00E4): X=366.0,Y=701.0 (should be at cap-height 700?)

	* aring (U+00E5): X=307.5,Y=700.5 (should be at cap-height 700?)

	* aring (U+00E5): X=230.0,Y=700.5 (should be at cap-height 700?)

	* edieresis (U+00EB): X=191.0,Y=701.0 (should be at cap-height 700?)

	* edieresis (U+00EB): X=384.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=14.0,Y=701.0 (should be at cap-height 700?)

	* idieresis (U+00EF): X=207.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=199.0,Y=701.0 (should be at cap-height 700?)

	* odieresis (U+00F6): X=392.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=182.0,Y=701.0 (should be at cap-height 700?)

	* udieresis (U+00FC): X=373.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=175.0,Y=701.0 (should be at cap-height 700?)

	* ydieresis (U+00FF): X=366.0,Y=701.0 (should be at cap-height 700?)

	* eogonek (U+0119): X=362.0,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=310.0,Y=698.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=258.0,Y=698.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=370.0,Y=701.0 (should be at cap-height 700?)

	* uring (U+016F): X=314.5,Y=700.5 (should be at cap-height 700?)

	* uring (U+016F): X=237.0,Y=700.5 (should be at cap-height 700?)

	* wcircumflex (U+0175): X=595.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=483.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=269.0,Y=1.0 (should be at baseline 0?)

	* ring (U+02DA): X=165.5,Y=700.5 (should be at cap-height 700?)

	* ring (U+02DA): X=88.0,Y=700.5 (should be at cap-height 700?)

	* uni030A (U+030A): X=148.5,Y=700.5 (should be at cap-height 700?)

	* uni030A (U+030A): X=71.0,Y=700.5 (should be at cap-height 700?)

	* wgrave (U+1E81): X=595.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=483.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=269.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=595.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=483.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=269.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=283.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=474.0,Y=701.0 (should be at cap-height 700?)

	* wdieresis (U+1E85): X=595.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=483.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=269.0,Y=1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=172.0,Y=701.0 (should be at cap-height 700?) 

	* And quotedblright (U+201D): X=304.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment L<<255.0,320.0>--<237.0,326.0>>

	* ampersand (U+0026) contains a short segment L<<156.0,388.0>--<149.0,398.0>>

	* ampersand (U+0026) contains a short segment L<<463.0,82.0>--<456.0,73.0>>

	* parenleft (U+0028) contains a short segment L<<351.0,811.0>--<351.0,801.0>>

	* parenright (U+0029) contains a short segment L<<35.0,-145.0>--<35.0,-135.0>>

	* paragraph (U+00B6) contains a short segment L<<284.0,289.0>--<270.0,289.0>>

	* germandbls (U+00DF) contains a short segment B<<335.0,454.0>-<345.0,461.0>-<355.0,467.5>>

	* germandbls (U+00DF) contains a short segment B<<355.0,467.5>-<365.0,474.0>-<375.0,481.0>>

	* ae (U+00E6) contains a short segment B<<875.0,271.0>-<875.0,261.0>-<874.0,249.5>>

	* uni0162 (U+0162) contains a short segment L<<339.0,0.0>--<322.0,0.0>>

	* aeacute (U+01FD) contains a short segment B<<875.0,271.0>-<875.0,261.0>-<874.0,249.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<335.0,454.0>-<345.0,461.0>-<355.0,467.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<355.0,467.5>-<365.0,474.0>-<375.0,481.0>>

	* perthousand (U+2030) contains a short segment B<<393.0,444.0>-<393.0,444.0>-<393.0,443.5>>

	* perthousand (U+2030) contains a short segment B<<393.0,443.5>-<393.0,443.0>-<393.0,443.0>>

	* perthousand (U+2030) contains a short segment L<<430.0,257.0>--<430.0,257.0>>

	* Euro (U+20AC) contains a short segment B<<102.0,309.0>-<101.0,319.0>-<100.5,329.0>>

	* Euro (U+20AC) contains a short segment B<<100.5,329.0>-<100.0,339.0>-<100.0,350.0>>

	* Euro (U+20AC) contains a short segment B<<100.0,350.0>-<100.0,360.0>-<100.5,370.5>> 

	* And Euro (U+20AC) contains a short segment B<<100.5,370.5>-<101.0,381.0>-<102.0,391.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* arrowdown (U+2193): L<<300.0,152.0>--<339.0,197.0>> -> L<<339.0,197.0>--<421.0,280.0>>

	* arrowdown (U+2193): L<<88.0,280.0>--<170.0,197.0>> -> L<<170.0,197.0>--<209.0,152.0>>

	* arrowleft (U+2190): L<<208.0,305.0>--<253.0,266.0>> -> L<<253.0,266.0>--<336.0,184.0>>

	* arrowleft (U+2190): L<<336.0,517.0>--<253.0,435.0>> -> L<<253.0,435.0>--<208.0,396.0>>

	* arrowright (U+2192): L<<485.0,184.0>--<569.0,266.0>> -> L<<569.0,266.0>--<614.0,305.0>>

	* arrowright (U+2192): L<<614.0,396.0>--<569.0,435.0>> -> L<<569.0,435.0>--<485.0,517.0>>

	* arrowup (U+2191): L<<209.0,549.0>--<171.0,504.0>> -> L<<171.0,504.0>--<88.0,420.0>> 

	* And arrowup (U+2191): L<<422.0,420.0>--<339.0,504.0>> -> L<<339.0,504.0>--<301.0,549.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Iogonek (U+012E): L<<175.0,700.0>--<174.0,0.0>>

	* summation (U+2211): L<<42.0,-49.0>--<43.0,73.0>>

	* trademark (U+2122): L<<624.0,349.0>--<623.0,579.0>>

	* x (U+0078): L<<477.0,1.0>--<361.0,0.0>>

	* yen (U+00A5): L<<228.0,316.0>--<58.0,317.0>> 

	* And yen (U+00A5): L<<564.0,317.0>--<395.0,316.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] RethinkSans-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWeightClass. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** OS/2 usWeightClass is '900' when it should be '800'. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2014-2017 indian type foundry with reserved font name 'poppins'."

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2014-2017 Indian Type Foundry with Reserved Font Name 'Poppins'. Copyright 2019 Google LLC with Reserved Name 'DM Sans'. Copyright 2022 Rethink Communications LLP with Reserved Name 'Rethink Sans'." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/RethinkSans-Medium.ttf', 'fonts/ttf/RethinkSans-ExtraBold.ttf', 'fonts/ttf/RethinkSans-Bold.ttf', 'fonts/ttf/RethinkSans-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1006, but got 991 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- E + less

	- R + E

	- less + greater

	- greater + less

	- f + i

	- i + l

	- hyphen + hyphen

	- hyphen + greater

	- greater + hyphen

	- parenleft + R

	- R + parenright

	- parenright + eight

	- eight + parenright

	- parenright + five

	- five + parenright

	- parenright + four

	- four + parenright

	- parenright + nine

	- nine + parenright

	- parenright + one

	- one + parenright

	- parenright + seven

	- seven + parenright

	- parenright + six

	- six + parenright

	- parenright + three

	- three + parenright

	- parenright + two

	- two + parenright

	- parenright + zero

	- zero + parenright

	- braceleft + eight

	- eight + braceright

	- braceright + five

	- five + braceright

	- braceright + four

	- four + braceright

	- braceright + nine

	- nine + braceright

	- braceright + one

	- one + braceright

	- braceright + seven

	- seven + braceright

	- braceright + six

	- six + braceright

	- braceright + three

	- three + braceright

	- braceright + two

	- two + braceright

	- braceright + zero

	- zero + braceright

	- registered + plus 

	- And less + hyphen [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Rethink Sans ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ('Poppins'. Copyright 2019 Google LLC with Reserved Name 'DM Sans'. Copyright 2022 Rethink Communications LLP with Reserved Name 'Rethink Sans') that differs from the currently used family name (RethinkSans), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- gravecomb.cap

	- tildecomb.cap

	- uni0302.cap

	- uni0304.cap

	- uni0306.cap

	- uni0307.cap

	- uni0308.cap

	- uni030A.cap

	- uni030B.cap

	- uni030C.alt

	- uni0327.cap 

	- And uni0328.cap
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: uni2783	Contours detected: 3	Expected: 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- And Glyph name: uni2783	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=260.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=99.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=477.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=315.0,Y=701.0 (should be at cap-height 700?)

	* ampersand (U+0026): X=202.0,Y=2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=374.0,Y=-1.0 (should be at baseline 0?)

	* six (U+0036): X=217.0,Y=700.5 (should be at cap-height 700?)

	* eight (U+0038): X=372.5,Y=1.0 (should be at baseline 0?)

	* nine (U+0039): X=342.0,Y=-0.5 (should be at baseline 0?)

	* i (U+0069): X=43.0,Y=702.0 (should be at cap-height 700?)

	* i (U+0069): X=178.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=43.5,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=178.0,Y=702.0 (should be at cap-height 700?)

	* sterling (U+00A3): X=581.0,Y=1.0 (should be at baseline 0?)

	* dieresis (U+00A8): X=277.0,Y=699.0 (should be at cap-height 700?)

	* dieresis (U+00A8): X=83.0,Y=699.0 (should be at cap-height 700?)

	* questiondown (U+00BF): X=211.0,Y=1.0 (should be at baseline 0?)

	* questiondown (U+00BF): X=334.5,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=275.5,Y=1.5 (should be at baseline 0?)

	* eogonek (U+0119): X=351.0,Y=-1.0 (should be at baseline 0?)

	* iogonek (U+012F): X=43.0,Y=702.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=178.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=43.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=178.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=262.5,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=397.0,Y=702.0 (should be at cap-height 700?)

	* dotaccent (U+02D9): X=82.0,Y=699.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=70.0,Y=699.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=263.0,Y=699.0 (should be at cap-height 700?)

	* uni0308 (U+0308): X=69.0,Y=699.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=260.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=99.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=477.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=315.0,Y=701.0 (should be at cap-height 700?)

	* uni2077 (U+2077): X=27.0,Y=698.0 (should be at cap-height 700?)

	* uni2077 (U+2077): X=291.0,Y=698.0 (should be at cap-height 700?)

	* uni2087 (U+2087): X=65.0,Y=-2.0 (should be at baseline 0?)

	* uni2087 (U+2087): X=155.0,Y=-2.0 (should be at baseline 0?)

	* uni20BD (U+20BD): X=114.0,Y=701.0 (should be at cap-height 700?)

	* uni20BD (U+20BD): X=399.0,Y=701.0 (should be at cap-height 700?)

	* oneeighth (U+215B): X=70.0,Y=-2.0 (should be at baseline 0?)

	* oneeighth (U+215B): X=590.0,Y=698.0 (should be at cap-height 700?)

	* oneeighth (U+215B): X=706.0,Y=698.0 (should be at cap-height 700?)

	* oneeighth (U+215B): X=186.0,Y=-2.0 (should be at baseline 0?)

	* threeeighths (U+215C): X=66.0,Y=-2.0 (should be at baseline 0?)

	* threeeighths (U+215C): X=587.0,Y=698.0 (should be at cap-height 700?)

	* threeeighths (U+215C): X=703.0,Y=698.0 (should be at cap-height 700?)

	* threeeighths (U+215C): X=183.0,Y=-2.0 (should be at baseline 0?)

	* fiveeighths (U+215D): X=63.0,Y=-2.0 (should be at baseline 0?)

	* fiveeighths (U+215D): X=583.0,Y=698.0 (should be at cap-height 700?)

	* fiveeighths (U+215D): X=701.0,Y=698.0 (should be at cap-height 700?)

	* fiveeighths (U+215D): X=181.0,Y=-2.0 (should be at baseline 0?)

	* seveneighths (U+215E): X=35.0,Y=-2.0 (should be at baseline 0?)

	* seveneighths (U+215E): X=555.0,Y=698.0 (should be at cap-height 700?)

	* seveneighths (U+215E): X=673.0,Y=698.0 (should be at cap-height 700?)

	* seveneighths (U+215E): X=153.0,Y=-2.0 (should be at baseline 0?)

	* seveneighths (U+215E): X=46.0,Y=698.0 (should be at cap-height 700?)

	* seveneighths (U+215E): X=310.0,Y=698.0 (should be at cap-height 700?)

	* arrowup (U+2191): X=193.0,Y=1.0 (should be at baseline 0?)

	* arrowup (U+2191): X=316.0,Y=1.0 (should be at baseline 0?)

	* fi (U+FB01): X=366.0,Y=702.0 (should be at cap-height 700?) 

	* And fi (U+FB01): X=501.0,Y=702.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment L<<250.0,288.0>--<244.0,290.0>>

	* ampersand (U+0026) contains a short segment L<<130.0,390.0>--<119.0,407.0>>

	* ampersand (U+0026) contains a short segment L<<465.0,50.0>--<452.0,39.0>>

	* at (U+0040) contains a short segment B<<734.0,152.0>-<734.0,126.0>-<744.0,116.0>>

	* at (U+0040) contains a short segment B<<744.0,116.0>-<754.0,106.0>-<773.0,106.0>>

	* sterling (U+00A3) contains a short segment B<<148.0,278.0>-<148.0,279.0>-<149.0,283.5>>

	* sterling (U+00A3) contains a short segment B<<149.0,283.5>-<150.0,288.0>-<151.0,290.0>>

	* sterling (U+00A3) contains a short segment B<<299.0,290.0>-<298.0,289.0>-<297.5,283.0>>

	* sterling (U+00A3) contains a short segment B<<297.5,283.0>-<297.0,277.0>-<297.0,277.0>>

	* uni00B5 (U+00B5) contains a short segment B<<238.0,-11.0>-<228.0,-10.0>-<220.0,-7.0>>

	* paragraph (U+00B6) contains a short segment L<<287.0,275.0>--<265.0,275.0>>

	* germandbls (U+00DF) contains a short segment B<<319.0,444.0>-<328.0,451.0>-<336.5,457.0>>

	* germandbls (U+00DF) contains a short segment B<<336.5,457.0>-<345.0,463.0>-<353.0,470.0>>

	* uni03BC (U+03BC) contains a short segment B<<238.0,-11.0>-<228.0,-10.0>-<220.0,-7.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<319.0,444.0>-<328.0,451.0>-<336.5,457.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<336.5,457.0>-<345.0,463.0>-<353.0,470.0>>

	* Euro (U+20AC) contains a short segment B<<96.0,318.0>-<95.0,326.0>-<94.5,333.5>>

	* Euro (U+20AC) contains a short segment B<<94.5,333.5>-<94.0,341.0>-<94.0,348.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,348.0>-<94.0,357.0>-<94.5,364.5>>

	* Euro (U+20AC) contains a short segment B<<94.5,364.5>-<95.0,372.0>-<96.0,379.0>>

	* Euro (U+20AC) contains a short segment B<<255.0,379.0>-<254.0,372.0>-<254.5,364.0>>

	* Euro (U+20AC) contains a short segment B<<254.5,364.0>-<255.0,356.0>-<255.0,348.0>>

	* Euro (U+20AC) contains a short segment B<<255.0,348.0>-<255.0,340.0>-<254.5,332.5>> 

	* And Euro (U+20AC) contains a short segment B<<254.5,332.5>-<254.0,325.0>-<255.0,318.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* arrowdown (U+2193): L<<107.0,299.0>--<156.0,251.0>> -> L<<156.0,251.0>--<193.0,209.0>>

	* arrowdown (U+2193): L<<316.0,209.0>--<354.0,251.0>> -> L<<354.0,251.0>--<402.0,299.0>>

	* arrowleft (U+2190): L<<265.0,289.0>--<307.0,250.0>> -> L<<307.0,250.0>--<355.0,203.0>>

	* arrowleft (U+2190): L<<355.0,498.0>--<307.0,450.0>> -> L<<307.0,450.0>--<265.0,412.0>>

	* arrowright (U+2192): L<<466.0,203.0>--<514.0,250.0>> -> L<<514.0,250.0>--<556.0,289.0>>

	* arrowright (U+2192): L<<556.0,412.0>--<514.0,450.0>> -> L<<514.0,450.0>--<466.0,498.0>>

	* arrowup (U+2191): L<<193.0,491.0>--<155.0,449.0>> -> L<<155.0,449.0>--<107.0,401.0>> 

	* And arrowup (U+2191): L<<402.0,401.0>--<353.0,449.0>> -> L<<353.0,449.0>--<316.0,491.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Iogonek (U+012E): L<<205.0,700.0>--<206.0,0.0>>

	* sterling (U+00A3): L<<581.0,1.0>--<69.0,0.0>>

	* trademark (U+2122): L<<131.0,350.0>--<130.0,625.0>>

	* trademark (U+2122): L<<214.0,625.0>--<213.0,350.0>> 

	* And yen (U+00A5): L<<613.0,311.0>--<452.0,310.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] RethinkSans-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2014-2017 indian type foundry with reserved font name 'poppins'."

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2014-2017 Indian Type Foundry with Reserved Font Name 'Poppins'. Copyright 2019 Google LLC with Reserved Name 'DM Sans'. Copyright 2022 Rethink Communications LLP with Reserved Name 'Rethink Sans'." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/RethinkSans-Medium.ttf', 'fonts/ttf/RethinkSans-ExtraBold.ttf', 'fonts/ttf/RethinkSans-Bold.ttf', 'fonts/ttf/RethinkSans-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1006, but got 992 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- E + less

	- R + E

	- less + greater

	- greater + less

	- f + i

	- i + l

	- hyphen + hyphen

	- hyphen + greater

	- greater + hyphen

	- parenleft + R

	- R + parenright

	- parenright + eight

	- eight + parenright

	- parenright + five

	- five + parenright

	- parenright + four

	- four + parenright

	- parenright + nine

	- nine + parenright

	- parenright + one

	- one + parenright

	- parenright + seven

	- seven + parenright

	- parenright + six

	- six + parenright

	- parenright + three

	- three + parenright

	- parenright + two

	- two + parenright

	- parenright + zero

	- zero + parenright

	- braceleft + eight

	- eight + braceright

	- braceright + five

	- five + braceright

	- braceright + four

	- four + braceright

	- braceright + nine

	- nine + braceright

	- braceright + one

	- one + braceright

	- braceright + seven

	- seven + braceright

	- braceright + six

	- six + braceright

	- braceright + three

	- three + braceright

	- braceright + two

	- two + braceright

	- braceright + zero

	- zero + braceright

	- registered + plus 

	- And less + hyphen [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ('Poppins'. Copyright 2019 Google LLC with Reserved Name 'DM Sans'. Copyright 2022 Rethink Communications LLP with Reserved Name 'Rethink Sans') that differs from the currently used family name (RethinkSans), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- gravecomb.cap

	- tildecomb.cap

	- uni0302.cap

	- uni0304.cap

	- uni0306.cap

	- uni0307.cap

	- uni0308.cap

	- uni030A.cap

	- uni030B.cap

	- uni030C.alt

	- uni0327.cap 

	- And uni0328.cap
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: uni2783	Contours detected: 3	Expected: 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- And Glyph name: uni2783	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=288.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=423.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=96.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=231.0,Y=701.0 (should be at cap-height 700?)

	* g (U+0067): X=255.0,Y=-1.0 (should be at baseline 0?)

	* i (U+0069): X=55.5,Y=702.0 (should be at cap-height 700?)

	* i (U+0069): X=173.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=57.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=175.0,Y=702.0 (should be at cap-height 700?)

	* m (U+006D): X=877.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=604.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=467.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=283.0,Y=1.0 (should be at baseline 0?)

	* x (U+0078): X=475.0,Y=1.0 (should be at baseline 0?)

	* aring (U+00E5): X=302.5,Y=698.5 (should be at cap-height 700?)

	* aring (U+00E5): X=228.5,Y=698.5 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=221.5,Y=702.0 (should be at cap-height 700?)

	* cdotaccent (U+010B): X=339.0,Y=702.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=222.5,Y=702.0 (should be at cap-height 700?)

	* edotaccent (U+0117): X=339.5,Y=702.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=255.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=202.0,Y=702.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=320.0,Y=702.0 (should be at cap-height 700?)

	* gdotaccent (U+0121): X=255.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=194.0,Y=701.0 (should be at cap-height 700?)

	* uni0123 (U+0123): X=255.0,Y=-1.0 (should be at baseline 0?)

	* ij (U+0133): X=55.5,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=173.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=284.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=402.0,Y=702.0 (should be at cap-height 700?)

	* uring (U+016F): X=311.0,Y=698.5 (should be at cap-height 700?)

	* uring (U+016F): X=237.0,Y=698.5 (should be at cap-height 700?)

	* wcircumflex (U+0175): X=604.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=467.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=283.0,Y=1.0 (should be at baseline 0?)

	* zdotaccent (U+017C): X=141.0,Y=702.0 (should be at cap-height 700?)

	* zdotaccent (U+017C): X=259.0,Y=702.0 (should be at cap-height 700?)

	* ring (U+02DA): X=165.5,Y=698.5 (should be at cap-height 700?)

	* ring (U+02DA): X=91.5,Y=698.5 (should be at cap-height 700?)

	* uni030A (U+030A): X=151.0,Y=698.5 (should be at cap-height 700?)

	* uni030A (U+030A): X=77.0,Y=698.5 (should be at cap-height 700?)

	* wgrave (U+1E81): X=604.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=467.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=283.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=604.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=467.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=283.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=604.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=467.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=283.0,Y=1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=288.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=423.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=96.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=231.0,Y=701.0 (should be at cap-height 700?)

	* uni2077 (U+2077): X=28.0,Y=699.0 (should be at cap-height 700?)

	* uni2077 (U+2077): X=290.0,Y=699.0 (should be at cap-height 700?)

	* uni2087 (U+2087): X=71.0,Y=-1.0 (should be at baseline 0?)

	* uni2087 (U+2087): X=152.0,Y=-1.0 (should be at baseline 0?)

	* oneeighth (U+215B): X=81.0,Y=-1.0 (should be at baseline 0?)

	* oneeighth (U+215B): X=601.0,Y=699.0 (should be at cap-height 700?)

	* oneeighth (U+215B): X=699.0,Y=699.0 (should be at cap-height 700?)

	* oneeighth (U+215B): X=179.0,Y=-1.0 (should be at baseline 0?)

	* threeeighths (U+215C): X=79.0,Y=-1.0 (should be at baseline 0?)

	* threeeighths (U+215C): X=599.0,Y=699.0 (should be at cap-height 700?)

	* threeeighths (U+215C): X=697.0,Y=699.0 (should be at cap-height 700?)

	* threeeighths (U+215C): X=177.0,Y=-1.0 (should be at baseline 0?)

	* fiveeighths (U+215D): X=82.0,Y=-1.0 (should be at baseline 0?)

	* fiveeighths (U+215D): X=602.0,Y=699.0 (should be at cap-height 700?)

	* fiveeighths (U+215D): X=701.0,Y=699.0 (should be at cap-height 700?)

	* fiveeighths (U+215D): X=181.0,Y=-1.0 (should be at baseline 0?)

	* seveneighths (U+215E): X=50.0,Y=-1.0 (should be at baseline 0?)

	* seveneighths (U+215E): X=570.0,Y=699.0 (should be at cap-height 700?)

	* seveneighths (U+215E): X=669.0,Y=699.0 (should be at cap-height 700?)

	* seveneighths (U+215E): X=149.0,Y=-1.0 (should be at baseline 0?)

	* seveneighths (U+215E): X=51.0,Y=699.0 (should be at cap-height 700?)

	* seveneighths (U+215E): X=313.0,Y=699.0 (should be at cap-height 700?)

	* fi (U+FB01): X=361.5,Y=702.0 (should be at cap-height 700?) 

	* And fi (U+FB01): X=479.0,Y=702.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment L<<256.0,307.0>--<247.0,310.0>>

	* ampersand (U+0026) contains a short segment L<<145.0,389.0>--<136.0,402.0>>

	* ampersand (U+0026) contains a short segment L<<464.0,68.0>--<454.0,58.0>>

	* parenleft (U+0028) contains a short segment L<<367.0,811.0>--<367.0,799.0>>

	* parenright (U+0029) contains a short segment L<<32.0,-145.0>--<32.0,-133.0>>

	* yen (U+00A5) contains a short segment L<<257.0,238.0>--<257.0,249.0>>

	* yen (U+00A5) contains a short segment L<<385.0,249.0>--<385.0,238.0>>

	* paragraph (U+00B6) contains a short segment L<<285.0,283.0>--<268.0,283.0>>

	* germandbls (U+00DF) contains a short segment B<<329.0,450.0>-<339.0,457.0>-<348.0,463.0>>

	* germandbls (U+00DF) contains a short segment B<<348.0,463.0>-<357.0,469.0>-<367.0,476.0>>

	* ae (U+00E6) contains a short segment B<<878.0,264.0>-<878.0,254.0>-<877.5,242.0>>

	* Eng (U+014A) contains a short segment L<<433.0,-111.0>--<460.0,-111.0>>

	* aeacute (U+01FD) contains a short segment B<<878.0,264.0>-<878.0,254.0>-<877.5,242.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<329.0,450.0>-<339.0,457.0>-<348.0,463.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<348.0,463.0>-<357.0,469.0>-<367.0,476.0>>

	* Euro (U+20AC) contains a short segment B<<99.0,313.0>-<98.0,322.0>-<97.5,331.0>>

	* Euro (U+20AC) contains a short segment B<<97.5,331.0>-<97.0,340.0>-<97.0,349.0>>

	* Euro (U+20AC) contains a short segment B<<97.0,349.0>-<97.0,359.0>-<97.5,368.0>>

	* Euro (U+20AC) contains a short segment B<<97.5,368.0>-<98.0,377.0>-<99.0,386.0>>

	* Euro (U+20AC) contains a short segment B<<229.0,386.0>-<228.0,377.0>-<228.0,368.0>>

	* Euro (U+20AC) contains a short segment B<<228.0,368.0>-<228.0,359.0>-<228.0,349.0>>

	* Euro (U+20AC) contains a short segment B<<228.0,349.0>-<228.0,339.0>-<228.0,330.0>> 

	* And Euro (U+20AC) contains a short segment B<<228.0,330.0>-<228.0,321.0>-<229.0,313.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* arrowdown (U+2193): L<<307.0,176.0>--<345.0,220.0>> -> L<<345.0,220.0>--<413.0,288.0>>

	* arrowdown (U+2193): L<<96.0,288.0>--<164.0,220.0>> -> L<<164.0,220.0>--<202.0,176.0>>

	* arrowleft (U+2190): L<<232.0,298.0>--<276.0,259.0>> -> L<<276.0,259.0>--<344.0,192.0>>

	* arrowleft (U+2190): L<<344.0,509.0>--<276.0,441.0>> -> L<<276.0,441.0>--<232.0,403.0>>

	* arrowright (U+2192): L<<477.0,192.0>--<545.0,259.0>> -> L<<545.0,259.0>--<589.0,298.0>>

	* arrowright (U+2192): L<<589.0,403.0>--<545.0,441.0>> -> L<<545.0,441.0>--<477.0,509.0>>

	* arrowup (U+2191): L<<202.0,524.0>--<164.0,480.0>> -> L<<164.0,480.0>--<96.0,412.0>> 

	* And arrowup (U+2191): L<<413.0,412.0>--<345.0,480.0>> -> L<<345.0,480.0>--<307.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* k (U+006B): L<<172.0,700.0>--<173.0,286.0>>

	* m (U+006D): L<<877.0,1.0>--<750.0,0.0>>

	* r (U+0072): L<<172.0,248.0>--<173.0,0.0>>

	* racute (U+0155): L<<172.0,248.0>--<173.0,0.0>>

	* rcaron (U+0159): L<<172.0,248.0>--<173.0,0.0>>

	* summation (U+2211): L<<43.0,-50.0>--<44.0,99.0>>

	* summation (U+2211): L<<44.0,552.0>--<45.0,700.0>>

	* uni0137 (U+0137): L<<172.0,700.0>--<173.0,286.0>>

	* uni0157 (U+0157): L<<172.0,248.0>--<173.0,0.0>>

	* w (U+0077): L<<283.0,1.0>--<145.0,0.0>>

	* wacute (U+1E83): L<<283.0,1.0>--<145.0,0.0>>

	* wcircumflex (U+0175): L<<283.0,1.0>--<145.0,0.0>>

	* wdieresis (U+1E85): L<<283.0,1.0>--<145.0,0.0>>

	* wgrave (U+1E81): L<<283.0,1.0>--<145.0,0.0>>

	* x (U+0078): L<<475.0,1.0>--<332.0,0.0>> 

	* And yen (U+00A5): L<<585.0,314.0>--<419.0,313.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[20] RethinkSans-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2014-2017 indian type foundry with reserved font name 'poppins'."

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2014-2017 Indian Type Foundry with Reserved Font Name 'Poppins'. Copyright 2019 Google LLC with Reserved Name 'DM Sans'. Copyright 2022 Rethink Communications LLP with Reserved Name 'Rethink Sans'." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/RethinkSans-Medium.ttf', 'fonts/ttf/RethinkSans-ExtraBold.ttf', 'fonts/ttf/RethinkSans-Bold.ttf', 'fonts/ttf/RethinkSans-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1006, but got 992 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- E + less

	- R + E

	- less + greater

	- greater + less

	- f + i

	- i + l

	- hyphen + hyphen

	- hyphen + greater

	- greater + hyphen

	- parenleft + R

	- R + parenright

	- parenright + eight

	- eight + parenright

	- parenright + five

	- five + parenright

	- parenright + four

	- four + parenright

	- parenright + nine

	- nine + parenright

	- parenright + one

	- one + parenright

	- parenright + seven

	- seven + parenright

	- parenright + six

	- six + parenright

	- parenright + three

	- three + parenright

	- parenright + two

	- two + parenright

	- parenright + zero

	- zero + parenright

	- braceleft + eight

	- eight + braceright

	- braceright + five

	- five + braceright

	- braceright + four

	- four + braceright

	- braceright + nine

	- nine + braceright

	- braceright + one

	- one + braceright

	- braceright + seven

	- seven + braceright

	- braceright + six

	- six + braceright

	- braceright + three

	- three + braceright

	- braceright + two

	- two + braceright

	- braceright + zero

	- zero + braceright

	- registered + plus 

	- And less + hyphen [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Name table strings must not contain the string 'Reserved Font Name'. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/rfn">com.google.fonts/check/name/rfn</a>)</summary><div>


* ⚠ **WARN** Name table entry contains "Reserved Font Name" for a family name ('Poppins'. Copyright 2019 Google LLC with Reserved Name 'DM Sans'. Copyright 2022 Rethink Communications LLP with Reserved Name 'Rethink Sans') that differs from the currently used family name (RethinkSans), which is fine. [code: legacy-familyname]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- CR

	- gravecomb.cap

	- tildecomb.cap

	- uni0302.cap

	- uni0304.cap

	- uni0306.cap

	- uni0307.cap

	- uni0308.cap

	- uni030A.cap

	- uni030B.cap

	- uni030C.alt

	- uni0327.cap 

	- And uni0328.cap
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2

	- Glyph name: uni2783	Contours detected: 3	Expected: 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni2113	Contours detected: 1	Expected: 2 

	- And Glyph name: uni2783	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=777.0,Y=2.0 (should be at baseline 0?)

	* braceleft (U+007B): X=168.0,Y=-2.0 (should be at baseline 0?)

	* braceright (U+007D): X=257.0,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=541.0,Y=-1.0 (should be at baseline 0?)

	* acircumflex (U+00E2): X=272.0,Y=698.0 (should be at cap-height 700?)

	* ecircumflex (U+00EA): X=291.0,Y=698.0 (should be at cap-height 700?)

	* icircumflex (U+00EE): X=111.0,Y=698.0 (should be at cap-height 700?)

	* ocircumflex (U+00F4): X=302.0,Y=698.0 (should be at cap-height 700?)

	* ucircumflex (U+00FB): X=277.0,Y=698.0 (should be at cap-height 700?)

	* ccaron (U+010D): X=160.0,Y=698.0 (should be at cap-height 700?)

	* ccaron (U+010D): X=434.0,Y=698.0 (should be at cap-height 700?)

	* eogonek (U+0119): X=369.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=262.0,Y=702.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=258.0,Y=698.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=331.0,Y=698.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=410.0,Y=698.0 (should be at cap-height 700?)

	* ohungarumlaut (U+0151): X=483.0,Y=698.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=232.0,Y=698.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=305.0,Y=698.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=384.0,Y=698.0 (should be at cap-height 700?)

	* uhungarumlaut (U+0171): X=457.0,Y=698.0 (should be at cap-height 700?)

	* Uogonek (U+0172): X=421.5,Y=2.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=377.0,Y=698.0 (should be at cap-height 700?)

	* ycircumflex (U+0177): X=276.0,Y=698.0 (should be at cap-height 700?)

	* circumflex (U+02C6): X=159.0,Y=698.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=240.0,Y=698.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=313.0,Y=698.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=88.0,Y=698.0 (should be at cap-height 700?)

	* hungarumlaut (U+02DD): X=161.0,Y=698.0 (should be at cap-height 700?)

	* uni0302 (U+0302): X=137.0,Y=698.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=218.0,Y=698.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=291.0,Y=698.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=66.0,Y=698.0 (should be at cap-height 700?)

	* uni030B (U+030B): X=139.0,Y=698.0 (should be at cap-height 700?)

	* uni20BD (U+20BD): X=127.0,Y=699.0 (should be at cap-height 700?)

	* uni20BD (U+20BD): X=347.0,Y=699.0 (should be at cap-height 700?)

	* arrowup (U+2191): X=216.0,Y=-1.0 (should be at baseline 0?) 

	* And arrowup (U+2191): X=294.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment L<<323.0,395.0>--<329.0,393.0>>

	* ampersand (U+0026) contains a short segment L<<167.0,387.0>--<161.0,394.0>>

	* ampersand (U+0026) contains a short segment L<<462.0,95.0>--<457.0,87.0>>

	* parenleft (U+0028) contains a short segment L<<334.0,811.0>--<334.0,803.0>>

	* parenright (U+0029) contains a short segment L<<38.0,-145.0>--<38.0,-137.0>>

	* ordfeminine (U+00AA) contains a short segment L<<378.0,354.0>--<371.0,354.0>>

	* paragraph (U+00B6) contains a short segment L<<282.0,295.0>--<272.0,295.0>>

	* germandbls (U+00DF) contains a short segment B<<340.0,458.0>-<351.0,465.0>-<361.5,472.0>>

	* germandbls (U+00DF) contains a short segment B<<361.5,472.0>-<372.0,479.0>-<383.0,486.0>>

	* ae (U+00E6) contains a short segment B<<871.0,278.0>-<871.0,268.0>-<870.5,257.0>>

	* uni0162 (U+0162) contains a short segment L<<254.0,0.0>--<238.0,0.0>>

	* uni0162 (U+0162) contains a short segment L<<322.0,0.0>--<310.0,0.0>>

	* aeacute (U+01FD) contains a short segment B<<871.0,278.0>-<871.0,268.0>-<870.5,257.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<340.0,458.0>-<351.0,465.0>-<361.5,472.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<361.5,472.0>-<372.0,479.0>-<383.0,486.0>>

	* Euro (U+20AC) contains a short segment B<<104.0,305.0>-<103.0,316.0>-<102.5,327.5>>

	* Euro (U+20AC) contains a short segment B<<102.5,327.5>-<102.0,339.0>-<102.0,350.0>>

	* Euro (U+20AC) contains a short segment B<<102.0,350.0>-<102.0,361.0>-<102.5,373.0>>

	* Euro (U+20AC) contains a short segment B<<102.5,373.0>-<103.0,385.0>-<104.0,396.0>>

	* Euro (U+20AC) contains a short segment B<<190.0,396.0>-<189.0,385.0>-<188.5,373.5>>

	* Euro (U+20AC) contains a short segment B<<188.5,373.5>-<188.0,362.0>-<188.0,350.0>>

	* Euro (U+20AC) contains a short segment B<<188.0,350.0>-<188.0,338.0>-<188.5,327.0>> 

	* And Euro (U+20AC) contains a short segment B<<188.5,327.0>-<189.0,316.0>-<190.0,305.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* arrowdown (U+2193): L<<293.0,127.0>--<332.0,173.0>> -> L<<332.0,173.0>--<429.0,272.0>>

	* arrowdown (U+2193): L<<79.0,272.0>--<176.0,173.0>> -> L<<176.0,173.0>--<215.0,127.0>>

	* arrowleft (U+2190): L<<183.0,311.0>--<229.0,272.0>> -> L<<229.0,272.0>--<328.0,175.0>>

	* arrowleft (U+2190): L<<328.0,525.0>--<229.0,428.0>> -> L<<229.0,428.0>--<183.0,389.0>>

	* arrowright (U+2192): L<<493.0,175.0>--<592.0,272.0>> -> L<<592.0,272.0>--<638.0,311.0>>

	* arrowright (U+2192): L<<638.0,389.0>--<592.0,428.0>> -> L<<592.0,428.0>--<493.0,525.0>>

	* arrowup (U+2191): L<<216.0,573.0>--<177.0,527.0>> -> L<<177.0,527.0>--<80.0,428.0>> 

	* And arrowup (U+2191): L<<430.0,428.0>--<333.0,527.0>> -> L<<333.0,527.0>--<294.0,573.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* partialdiff (U+2202): B<<390.5,533.0>-<428.0,509.0>-<444.0,444.0>>/B<<444.0,444.0>-<442.0,514.0>-<426.5,569.0>> = 12.19207393066342 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Iogonek (U+012E): L<<158.0,700.0>--<156.0,0.0>>

	* sterling (U+00A3): L<<541.0,-1.0>--<87.0,0.0>>

	* trademark (U+2122): L<<116.0,348.0>--<117.0,647.0>>

	* trademark (U+2122): L<<182.0,647.0>--<183.0,348.0>>

	* trademark (U+2122): L<<620.0,348.0>--<619.0,606.0>>

	* yen (U+00A5): L<<232.0,318.0>--<59.0,319.0>> 

	* And yen (U+00A5): L<<543.0,319.0>--<370.0,318.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 30 | 50 | 442 | 25 | 316 | 0 |
| 0% | 3% | 6% | 51% | 3% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
