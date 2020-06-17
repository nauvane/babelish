---
title: "Types and usage"
linkTitle: "Types and usage"
date: 2020-03-04T11:55:11Z
weight: 2
description: >
  Fonts come in many forms and these forms can shape how we communicate in print
---

[Features of the Latin script](https://www.bl.uk/history-of-writing/articles/a-short-history-of-calligraphy-and-typography) that continue to shape how we communicate in print go back to the century that followed the invention of movable type in Europe and even further to ancient Rome.

### The profile of a font

One of these ancient features is the presence of **serifs**, or projections at the extremes of certain strokes, as in the upper case **e** and in **x** here.

{{< figure src="/images/guidelines_serifs.png" caption="Profile of a serif font (right click to view full size)" alt="Profile of a serif font" width="80%">}}

Each font has a number of distinctive elements, notably its **x-height**, or the height of lower-case characters, and its **capital height**. The full **point size** of a digital font is the distance between its **descender** and **ascender lines** (typography, needless to say, has [its own distinctive terminology](https://www.adobe.com/ie/products/type/adobe-type-references-tips/glossary.html)).

A font's x-height has an important bearing on its legibility.

{{< figure src="/images/xheights.png" caption="Contrasting x-heights" alt="Contrasting x-heights" width="80%">}}

Fonts of quite similar point size can have x-heights that differ quite sharply. The raised x-height of Noto Serif means that it is more legible at smaller point sizes, provided that [inter-line spacing](/docs/working-with-documents/word-processors#document-design-using-a-word-processor) is slightly increased.

### Serif and sans serif

Many [features of the design of serif fonts](https://www.bl.uk/history-of-writing/articles/a-short-history-of-calligraphy-and-typography) derive from calligraphy. **Sans serif** fonts, by contrast, are more geometric and less ornamental in character.

{{< figure src="/images/noto_serif_sans.png" caption="Serif and sans serif" alt="Serif and sans serif" width="80%">}}

Even so, some sans serif fonts retain the contrast between thinner and thicker elements of a character: compare the **shoulder** of the letter **h** in the two forms of the Noto font, or the **counter** of the sans serif **g**. Note also that in the serif and sans serif forms of Noto the x-height, capital height, ascender and descender lines are identical. Today, many fonts exist in the form of **font families** encompassing serif and sans serif forms with many variants of style and weight. Noto Sans is the font used in this site.

### Styles and weights

[Italic fonts](https://www.bl.uk/collection-items/first-book-in-italic-typeface) were first used in the sixteenth century to print material in Latin.

{{< figure src="/images/weights.png" caption="Styles and weights: roman, italic and bold" alt="Styles and weights: roman, italic and bold" width="80%">}}

Nowadays, they are used for more specialized purposes, e.g. to emphasize individual words (especially in serif fonts) and to denote the titles of books and other full-length works, e.g. *Le città invisibili*, *Le Mariage de Figaro*. Word-processors sometimes present block quotations by default in italics, but this is not a style that you should follow in your essays; likewise, italics should not be used for inline quotations. 

Bold fonts can also be used for emphasis and also to highlight the structural hierarchy of elements of a document, e.g. in headings. Note that here all three typefaces have the same point size, but differ in width. 

### OpenType fonts

**OpenType** is the most widely available font format available today. This is a file format that allows several different font variants to be combined in a single file — extending to features that we will now consider, including small capitals, ligatures and various forms of numerals. 

{{< figure src="/images/one.png" caption="Variations on the number 1" alt="Variations on the number 1" width="80%">}}

Here are the several forms of the number **1** in the font [Faustina](https://fonts.google.com/specimen/Faustina), including forms used in fractions, lining and non-lining versions with tabular and proportional variations. It is possible to activate any OpenType forms you wish to use in a document using controls in a word-processor. 

### Small capitals and structural divisions

Small capitals, which are characters that take the form of capitals but are proportional in height and weight to lower-case characters, emerged also in the sixteenth-century, typically to designate headings or other structural elements.

{{< figure src="/images/small_caps.png" caption="Small caps" alt="Small caps" width="80%">}}

As you can see here, they are marginally taller than the font's x-height. 

{{< figure src="/images/weights_sc.png" caption="Roman and small caps" alt="Roman and small caps" width="80%">}}

An unbroken series, as here, without any upper case characters is referred to as **even small capitals** and is a form often used in headings, and in [page headers and footers](/docs/working-with-documents/structured-documents). Note that this font also incorporates a form of the exclamation mark that is in proportion with the small capitals.

The legibility of small caps demands that what is termed the line's **tracking**, in other words, the space between characters, is increased: hence the greater width of the second line.  

### Kerning

Even where the tracking in a given font may have been varied, some upper-case characters call for further adjustments. This form of adjustment is called **kerning**.

{{< figure src="/images/kerning_noboxes.png" caption="Top line: no kerning" alt="Top line: no kerning" width="80%">}}

You can see here that the spacing between the first three characters in the top line looks out of proportion with the rest. 

{{< figure src="/images/kerning_boxes.png" caption="Kerning applied" alt="Kerning applied" width="80%">}}

Here is the second of the two lines with each character enclosed within a **bounding box**. Kerning is a special form of adjustment between specific upper case characters in particular. As you can see, when kerning is applied the **a** and the **v** all notably overlap, making the string as a whole appear more evenly spaced. 

{{< figure src="/images/kerningbis.png" caption="Variable kerning" alt="Variable kerning" width="80%">}}

In some cases, several characters in a row will require kerning, though to different degrees according to the specific combinations that may arise.

### Digraphs and ligatures

In some scripts, a single printed character can be composed of two components. This feature is termed a **[digraph](https://scriptsource.org/cms/scripts/page.php?item_id=glossary#multig)**: here is an example of a character that represents a discrete diphthong in Dutch  and belongs to the [Latin Extended-A block](https://unicode.org/charts/PDF/U0100.pdf) in Unicode.

{{< figure src="/images/ij.png" caption="IJ in Dutch: upper and lower case" alt="IJ in Dutch" width="80%">}}

In other words, this character is different from **i** and **j** printed side by side, which is why it has its own Unicode code point. 

{{< figure src="/images/ij_codepoint.png" caption="IJ: a composed character in Unicode" alt="IJ: a composed character in Unicode" width="80%">}}

Another example is the character **ǅ** and its lower-case equivalent **ǆ**, which are used in Croatian script. A further variant is the double capital form. 

{{< figure src="/images/dz_codepoint.png" caption="Latin capital DZ with caron" alt="Latin capital DZ with caron" width="80%">}}

All of these three characters form part of the Latin Extended-B block.

{{< figure src="/images/dz_block.png" caption="Latin Extended-B in Unicode" alt="Latin Extended-B in Unicode" width="80%">}}

See if you can identify them also in <a href="/documents/Noto_Serif_Unicode.pdf" target="_blank">the Noto Serif character set</a>.

A **[ligature](https://scriptsource.org/cms/scripts/page.php?item_id=glossary#ligature)** is another form of joined character, but with a different purpose.

{{< figure src="/images/ligatures.png" caption="Ligatures" alt="Ligatures" width="80%">}}

Today, what are termed **standard ligatures** are joined characters that avert otherwise awkward clashes, e.g. when an **i** or **l** follows an **f**. It is a good idea to activate these ligatures if you notice that clashes do arise in the font that you may be using. 

{{< figure src="/images/noto_liga.png" caption="Noto Serif: with and without ligatures" alt="Noto Serif: with and without ligatures" width="80%">}}

In the case of Noto Serif, **f** and **l** are liable to clash, as you can see in the top line. 

You can, however, opt for fonts which are designed in such a way as not to require ligatures, like [Liberation Serif](https://www.dafont.com/liberation-serif.font), which is the default open-source font in Libre Office.

{{< figure src="/images/liberation_nolig.png" caption="Liberation Serif" alt="Liberation Serif" width="80%">}}

OpenType fonts also often include historical or discretionary ligatures, which are mainly ornamental or antiquarian. These should be avoided in your essays: for the reader of today, they are something of a distraction. On the other hand, if you are reproducing the typography of an original source, you may wish to make use of them.

{{< figure src="/images/ws.png" caption="Shakespeare, Sonnet 130: historical st ligature" alt="Ligatures" width="80%">}}

### Numerals

OpenType fonts typically include numerals in different styles:

- old-style (or non-lining) proportional numerals
- old-style tabular numerals
- lining proportional numerals
- lining tabular numerals

{{< figure src="/images/numerals.png" caption="Varieties of numerals" alt="Varieties of numerals" width="80%">}}

Old-style numerals are appropriate to use in body text: they form an even line with alphabetical characters, so improving the legibility of your content. Tabular forms, whether lining or non-lining, are most useful in tables: columns of numbers then remain aligned from row to row. Lining numerals are as a rule slightly less than capital height. Where figures are to be combined with upper case characters, lining numerals are a better choice. 

### Accessing font features in word-processors

To access font controls in **Word**, select **Format** > **Fonts**, or use to keyboard to select **CTRL+D** (Windows) or **CMD+D** (macOS).

{{< figure src="/images/word_fonts.png" caption="Fonts in Word" alt="Fonts in Word" width="80%">}}

The basic controls are available in this interface. To access more specialized features, select **Advanced**.

{{< figure src="/images/fonts_advanced.png" caption="Advanced font options in Word" alt="Advanced font options in Word" width="80%">}}

Here, you can control kerning, where necessary. You can also access OpenType font features, including ligatures. 


{{< figure src="/images/nonlining.png" caption="Numerals in Word" alt="Numerals in Word" width="80%">}}

Here, proportional and non-lining or old-style numerals are selected.

The best option to control font features in **LibreOffice** is to use the **[Typography Toolbar](/docs/applications/#word-processors)**.

{{< figure src="/images/typography_toolbar.png" caption="The Typography Toolbar in LibreOffice" alt="The Typography Toolbar in LibreOffice" width="80%">}}

Highlight a segment of text, or press **CTRL+A** or **CMD+A** to select all of the text in a document, and select the feature that you wish to apply.

