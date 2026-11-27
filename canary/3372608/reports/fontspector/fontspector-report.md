## FontSpector report

fontspector version: 1.9.0



## Checks with FATAL results

These must be addressed first.


<details><summary>[1] fonts/ttf/ThunaCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>💥 <b>ERROR</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- 💥 **ERROR** Error: Error reading font file: the GPOS table is missing 
  
  

</div>
</details>


</div>
</details>







## All other checks




<details><summary>[1] fonts/ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>


</div>
</details>


<details><summary>[15] fonts/ttf/ThunaCANARY-Regular.ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (opentype/glyf_non_transformed_duplicate_components)</summary>
    <div>








- 🔥 **FAIL** ellipsis: duplicate component period at 0,0. Duplicate components may cause rendering issues. [code: found-duplicates]
  
  


- 🔥 **FAIL** ellipsis: duplicate component period at 0,0. Duplicate components may cause rendering issues. [code: found-duplicates]
  
  


- 🔥 **FAIL** quotedblbase: duplicate component comma at 0,0. Duplicate components may cause rendering issues. [code: found-duplicates]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? (whitespace_glyphs)</summary>
    <div>








- 🔥 **FAIL** Whitespace glyph missing for codepoint 0x00A0 [code: missing-whitespace-glyph-0x00A0]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check that format 12 cmap subtables are correctly constituted. (cmap/format_12)</summary>
    <div>








- ⚠️ **WARN** The format 12 subtable did not contain all codepoints from the format 4 subtable:

* U+FFFF [code: missing-format-4]
  
  


- ⚠️ **WARN** The format 12 subtable did not contain all codepoints from the format 4 subtable:

* U+FFFF [code: missing-format-4]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* uni0D92 (U+0D92): found 2, expected one of: [3, 4, 5]
* uni0D9B (U+0D9B): found 1, expected one of: [2, 3]
* uni0D9E (U+0D9E): found 1, expected one of: [2, 3, 4]
* uni0D9F (U+0D9F): found 2, expected one of: [1, 3, 5]
* uni0DA1 (U+0DA1): found 2, expected one of: [3, 4, 5]
* uni0DA3 (U+0DA3): found 2, expected one of: [3, 4]
* ellipsis (U+2026): found 5, expected one of: [3, 7] [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 462 among a set of 4  math glyphs.
The following math glyphs have a different width, though:
width=492: plus
width=530: equal [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. (Overriden: Sinhala fonts: U+20B9 is optional (Sri Lanka writes රු / Rs)) [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* isignsinh.alt
* iisignsinh.alt1
* usignsinh.alt1
* uusignsinh.alt
* rasignsinh.long
* rasignsinh.medium
* rasignsinh.short
* aasign_viramasinh
* .null
* nonmarkingreturn
* mooniak [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* quotedblbase (U+201E) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uni0D8A (U+0D8A): from (45.0, 289.0) to (51.0, 300.0) is colinear with segment from (51.0, 300.0) to (219.0, 600.0)
* uni0DF4 (U+0DF4): from (390.0, 80.0) to (390.0, 76.0) is colinear with segment from (390.0, 76.0) to (391.0, 55.0)
* uni0DF4 (U+0DF4): from (447.0, 214.0) to (447.0, 216.0) is colinear with segment from (447.0, 216.0) to (447.0, 221.0)
* uni0DBB (U+0DBB): from (99.0, 290.0) to (105.0, 300.0) is colinear with segment from (105.0, 300.0) to (273.0, 600.0)
* tThasinh: from (749.0, 27.0) to (762.0, 28.0) is colinear with segment from (762.0, 28.0) to (764.0, 28.0)
* nVasinh: from (664.0, 27.0) to (678.0, 28.0) is colinear with segment from (678.0, 28.0) to (679.0, 28.0)
* rsinh: from (104.0, 299.0) to (105.0, 301.0) is colinear with segment from (105.0, 301.0) to (273.0, 600.0)
* tVsinh: from (748.0, 27.0) to (762.0, 28.0) is colinear with segment from (762.0, 28.0) to (763.0, 28.0)
* tThsinh: from (749.0, 27.0) to (763.0, 28.0) is colinear with segment from (763.0, 28.0) to (764.0, 28.0)
* nVsinh: from (658.0, 27.0) to (671.0, 28.0) is colinear with segment from (671.0, 28.0) to (673.0, 28.0)
* rIsinh: from (109.0, 290.0) to (115.0, 301.0) is colinear with segment from (115.0, 301.0) to (283.0, 601.0)
* tThIsinh: from (749.0, 27.0) to (762.0, 28.0) is colinear with segment from (762.0, 28.0) to (764.0, 28.0)
* nVIsinh: from (684.0, 27.0) to (698.0, 28.0) is colinear with segment from (698.0, 28.0) to (699.0, 28.0)
* rIisinh: from (92.0, 289.0) to (98.0, 300.0) is colinear with segment from (98.0, 300.0) to (266.0, 600.0)
* tThIisinh: from (749.0, 27.0) to (762.0, 28.0) is colinear with segment from (762.0, 28.0) to (764.0, 28.0)
* nVIisinh: from (660.0, 27.0) to (674.0, 28.0) is colinear with segment from (674.0, 28.0) to (675.0, 28.0)
* nThIisinh: from (677.0, 27.0) to (690.0, 28.0) is colinear with segment from (690.0, 28.0) to (692.0, 28.0)
* nnUsinh: from (456.0, 128.0) to (455.0, 134.0) is colinear with segment from (455.0, 134.0) to (413.0, 430.0)
* rUsinh: from (62.0, 289.0) to (69.0, 300.0) is colinear with segment from (69.0, 300.0) to (236.0, 600.0)
* tVUsinh: from (749.0, 25.0) to (762.0, 26.0) is colinear with segment from (762.0, 26.0) to (764.0, 26.0)
* rUusinh: from (70.0, 290.0) to (76.0, 300.0) is colinear with segment from (76.0, 300.0) to (243.0, 600.0)
* kVUusinh: from (658.0, 26.0) to (671.0, 27.0) is colinear with segment from (671.0, 27.0) to (673.0, 27.0)
* tVUusinh: from (749.0, 26.0) to (762.0, 27.0) is colinear with segment from (762.0, 27.0) to (764.0, 27.0)
* nVUusinh: from (677.0, 27.0) to (690.0, 28.0) is colinear with segment from (690.0, 28.0) to (692.0, 28.0)
* rAesinh: from (58.0, 289.0) to (64.0, 300.0) is colinear with segment from (64.0, 300.0) to (231.0, 600.0)
* rAaesinh: from (72.0, 290.0) to (78.0, 300.0) is colinear with segment from (78.0, 300.0) to (245.0, 600.0)
* nyRsinh: from (528.0, 452.0) to (607.0, 453.0) is colinear with segment from (607.0, 453.0) to (878.0, 453.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (569.0, 32.0), p1: (558.0, 160.0), p2: (555.0, 217.0) })/Quad(QuadBez { p0: (555.0, 217.0), p1: (553.0, 200.0), p2: (541.0, 120.0) }) = 9.722624311940258 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (476.0, 4.0), p1: (457.0, 53.0), p2: (450.0, 164.0) })/Quad(QuadBez { p0: (450.0, 164.0), p1: (447.0, 141.0), p2: (441.0, 103.0) }) = 11.039876823738844 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (500.0, 131.0), p1: (502.0, 105.0), p2: (503.0, 86.0) })/Quad(QuadBez { p0: (503.0, 86.0), p1: (506.0, 106.0), p2: (518.0, 151.0) }) = 11.543553114131454 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (594.0, 329.0), p1: (583.0, 259.0), p2: (597.0, 78.0) })/Quad(QuadBez { p0: (597.0, 78.0), p1: (602.0, 127.0), p2: (625.0, 224.0) }) = 10.249253458106132 degrees
* uni0DF4 (U+0DF4): Quad(QuadBez { p0: (810.0, 339.0), p1: (795.0, 261.0), p2: (805.0, 109.0) })/Quad(QuadBez { p0: (805.0, 109.0), p1: (806.0, 124.0), p2: (828.0, 206.0) }) = 7.5781096991959975 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* nyRIsinh: Line(Line { p0: (923.0, 426.0), p1: (633.0, 425.0) }) (angle: -179.80 degrees, expected: -180.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* ellipsis (U+2026): Quad(QuadBez { p0: (500.0, 0.0), p1: (486.0, 0.0), p2: (486.0, 14.0) }) has the same coordinates as a previous segment.
* ellipsis (U+2026): Quad(QuadBez { p0: (486.0, 14.0), p1: (486.0, 28.0), p2: (500.0, 28.0) }) has the same coordinates as a previous segment.
* ellipsis (U+2026): Quad(QuadBez { p0: (500.0, 28.0), p1: (514.0, 28.0), p2: (514.0, 14.0) }) has the same coordinates as a previous segment.
* ellipsis (U+2026): Quad(QuadBez { p0: (514.0, 14.0), p1: (514.0, 0.0), p2: (500.0, 0.0) }) has the same coordinates as a previous segment.
* ellipsis (U+2026): Quad(QuadBez { p0: (500.0, 0.0), p1: (486.0, 0.0), p2: (486.0, 14.0) }) has the same coordinates as a previous segment.
* ellipsis (U+2026): Quad(QuadBez { p0: (486.0, 14.0), p1: (486.0, 28.0), p2: (500.0, 28.0) }) has the same coordinates as a previous segment.
* ellipsis (U+2026): Quad(QuadBez { p0: (500.0, 28.0), p1: (514.0, 28.0), p2: (514.0, 14.0) }) has the same coordinates as a previous segment.
* ellipsis (U+2026): Quad(QuadBez { p0: (514.0, 14.0), p1: (514.0, 0.0), p2: (500.0, 0.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Line(Line { p0: (513.0, 0.0), p1: (503.0, -65.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Line(Line { p0: (503.0, -65.0), p1: (487.0, -65.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Line(Line { p0: (487.0, -65.0), p1: (487.0, 0.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Line(Line { p0: (487.0, 0.0), p1: (513.0, 0.0) }) has the same coordinates as a previous segment. [code: overlapping-path-segments]
  
  

</div>
</details>


</div>
</details>






### Summary

| 💥 ERROR | 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|---|
| 1 | 4 | 15 | 12 | 77 | 51 | 
| 1% | 2% | 9% | 8% | 48% | 32% | 



