---
title: "What is a script?"
linkTitle: "What is a script?"
date: 2020-03-14T21:06:05Z
weight: 2
description: >
  A script is the medium of writing in a given language — or languages
---

The written word is pervasive and scripts are the basis on which we communicate in writing. With the publication of **[Unicode 14.0.0](http://www.unicode.org/versions/Unicode14.0.0/)** on 14 September 2021, the standard now supports [159 scripts](https://www.unicode.org/standard/supported.html). 

This is how Unicode defines a script: "A collection of letters and other written signs used to represent textual information in one or more writing systems. For example, Russian is written with a subset of the Cyrillic script; Ukrainian is written with a different subset. The Japanese writing system uses several scripts" (<a href="https://www.unicode.org/glossary/#script">Glossary of Unicode terms</a>). Within this framework, the different scripts in the world, historical and contemporary, present [wide variations](https://scriptsource.org/cms/scripts/page.php?item_id=entry_detail&uid=cq3q4pwuah). 

About two-thirds of the writing systems in the world today use [alphabetical scripts](https://scriptsource.org/cms/scripts/page.php?item_id=glossary#alph)

### Latin script

This is the script that you are likely to use most often: it is the one in which English and many European languages are written, and is the most widely script used today.

{{< figure src="/images/word_boundaries.png" caption="Latin script features" alt="Latin script features" width="80%">}}

Scripts can be defined according to a number of characteristics, using [Unicode](https://www.unicode.org/glossary/) or [typographical](https://www.adobe.com/ie/products/type/adobe-type-references-tips/glossary.html) terminology. Here are a number of these characteristics in the case of Latin script:

- Latin script is **alphabetical**
- it is **bicameral**, meaning that it has upper-case and lower-case characters, and is **case-sensitive** — so, we recognize **brown** to be an adjective and **Brown** to be a proper noun
- it is a **left-to-right** script
- it uses spaces as **word-separators**
- Latin script uses **hyphenation**
- Latin script uses what is termed a **mid-baseline**, with some characters having elements that **descend** below the base
- Latin script has what are termed its own **native digits**, or numerals

You can see in the example above that the character **d** is used it its upper case form. The bounding boxes allow us to see that words are separated by spaces and that some characters, for example, **d**, **h**, **k**, **b** and **f**, have **ascenders**, or parts of the character that extend about what is termed the script's **x-height**. Likewise, **j**, **p**, **y** and **g** have **descenders**. Note too that the interrogation mark extends about x-height. 

### Arabic script

{{< figure src="/images/arabic.png" caption="Arabic script" alt="Arabic script" width="80%">}}

[Arabic scripts](https://r12a.github.io/scripts/arabic/index) present several more distinguishing features than Latin script. After the Latin alphabet, it is the second most widely used script in the world.

- Arabic is a **right-to-left** mid-baseline script
- the script directly represents only consonants and long vowel sounds; in other words, it is an **[abjad](https://scriptsource.org/cms/scripts/page.php?item_id=glossary#abjad)**
- short vowel sounds and other phonetic information are denoted by **[diacritics](https://scriptsource.org/cms/scripts/page.php?item_id=glossary#diacritic)**
- it is a **cursive** script; in other words, the characters "join up"
- the shape of cursive characters can be determined by the characters to which they are joined
- characters can also overlap
- unlike Latin script, it is not case-sensitive
- like Latin script, it has native digits
- spaces are used as word-separators

{{< figure src="/images/arabic_keyboard.png" caption="An Arabic keyboard" alt="An Arabic keyboard" width="80%">}}

Note the Arabic numerals on the second row from the top of this lower case keyboard.

### CJK scripts

**CJK scripts** refer to Chinese, or [Han](https://scriptsource.org/cms/scripts/page.php?item_id=script_detail&key=Hans), ideographs used in the writing systems of Chinese and [Japanese](https://scriptsource.org/cms/scripts/page.php?item_id=script_detail&key=Jpan), and to a more limited extent in [Korean](https://scriptsource.org/cms/scripts/page.php?item_id=script_detail&key=Kore). Unicode supports more than eighty thousand Han characters.

Here is an example of a sentence using [the Simplified Chinese script](https://r12a.github.io/scripts/chinese/).

{{< figure src="/images/han.png" caption="CJK: Simplified Chinese" alt="CJK: Simplified Chinese" width="80%">}}

Can you identify the use of Traditional Chinese quotation marks here, as well as the European comma and full point?

- Han scripts are **ideographic**, with characters usually representing a spoken syllable
- for this reason, Han script is also referred to as a **[logosyllabary](https://scriptsource.org/cms/scripts/page.php?item_id=glossary#logosyl)**
- Japanese script features both syllabic and ideographic-syllabic text, with word-spacing being used with the former
- CJK scripts generally are left-to-right and can also be written vertically
- they are not case-sensitive
- Han does not use spaces as word-separators, though the **justification** of lines leads to adjustments in the placement of characters within their frames
- Korean, by contrast, does feature spacing between words
- both Han and Japanese script uses [a centred baseline](https://scriptsource.org/cms/scripts/page.php?item_id=glossary#baseline), whereas in Korean a bottom baseline is used

{{< figure src="/images/boundaries_han.png" caption="Han: case and boundaries" alt="Han: case and boundaries" width="80%">}}

A Han ideogram can be thought of as contained a uniform square frame: here, the characters are displayed in visible **bounding boxes** to illustrate the absence of features like case and word separation. Note that punctuation marks imported from European scripts are **[full-width](https://unicode.org/glossary/#fullwidth)** rather than **[half-width](https://unicode.org/glossary/#halfwidth)**, and therefore do not require additional spacing. 

### A historical script: Ogham

Unicode extends also to historical scripts that are no longer current, one example being the medieval script of [Ogham](https://scriptsource.org/scr/Ogam), which was widely used for inscriptions in Ireland, and also in parts of Britain. Here is [an example](https://www.ucl.ac.uk/archaeology/cisp/database/stone/incha_1.html) of an Ogham inscription.

{{< figure src="/images/ogham.png" caption="An inscription in Ogham" alt="An inscription in Ogham" width="10%">}}

- Ogham is [an alphabetical script](https://www.omniglot.com/writing/ogham.htm), with incisions corresponding to characters in the Latin alphabet
- it is a left-to-right script, with a mid-baseline
- many original Ogham inscriptions are vertical, reading from bottom to top, as in this example
- Ogham inscriptions did not make use of word-spacing
- Ogham forms a [block](https://www.unicode.org/charts/PDF/U1680.pdf) in the **[Basic Multilingual Plane](/docs/scripts-and-unicode/what-is-unicode/#how-is-unicode-organized)** in Unicode
- the **[Noto Project](/docs/fonts/installing-fonts/#unicode-fonts)** includes [a font for Ogham](https://noto-website-2.storage.googleapis.com/pkgs/NotoSansOgham-unhinted.zip)

{{< figure src="/images/ogham_sail.png" caption="Inserting an Ogham character in LibreOffice" alt="Inserting an Ogham character in LibreOffice" width="80%">}}
