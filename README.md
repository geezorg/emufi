# EMUFI
**E**thiopic **M**anuscript **U**nicode **F**ont **I**nitiative
This is the public repository of the [EMUFI project](http://emufi.geezorg/).
Project documentation and work products will be found here.  The primary work product of the project at this time is the [“Geʾez Manuscript Zemen”](https://github.com/geezorg/emufi/releases/latest) font.

Please report defects and request additions using the repository [Issues](https://github.com/geezorg/emufi/issues) interface.

### Symbol Inventory
Extensions beyond the [Unicode](http://unicode.org/) standard are tabulated by category in the following:

| Symbol Type | Count |
|--------------|-------:|
 Numbers| 484 |
|Punctuation &amp; Marks | 78 |
|Ligatures|28|
|Variants|5|
|Qirts (ቅርጽ) Notes| 79|
|Bēt (ቤት) Markers|117|
|**Total** | **791** |

## FAQ on Project Fonts

***Why Not Use OpenType Character Variants or Stylistical Sets?***

Character Variants (CV) would be the ideal way to support the graphical variants in many of the symbols, such as numerals and punctuation. Unfortunately, the widely used Microsoft Office suite does not support Character Varaints (while LibreOffice does).  Stylistical Sets (SS) are another OpenType option that can be used to identify a set of symbols. However, while Stylistical Sets are supported by Microsoft Office products, using them has proven awkward and tedious in document production. 

The capability of storing a CV or SS attribute with character data is also an observed limitation with OCR software.  To work around these short comings, each symbol has been assigned its own Private Use Area (PUA) codepoint. 

***Is it Safe to Use the Project Fonts?***

While publishing software is still being updated to work with multi-colored fonts, the fonts are safe to use in those applications that can support color with the following constraints:

* When sending a document to another party, the font must be sent along as well if the other party does not already have it installed.
* Within a major version of a project font (e.g. 1.x , 2.x , 3.x) the symbols are "stable" and will not "disappear". Should symbols change location in a future version, or when adopted into Unicode, a document converter will be provided.

***What is the Relationship to Unicode?***

All extra symbols are ***not*** recognized in any published version of a Unicode standard.  The additional symbols are encoded in the *Private Use Area* of the Unicode standard and thus the font is compatible with Unicode compliant software. The Unicode Consortium is occassionally consulted regarding technical and encoding issues.  It has been established with the Consortium that the following categories are ***not*** subject to standardized encoding: Numerals, Ligatures, Variants, Bēt Markers, and some Punctuation.  Thus these symbols will necessarily reside permanently in the Private Use Area.
