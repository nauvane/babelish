---
title: "What is a script?"
linkTitle: "What is a script?"
date: 2020-03-14T21:06:05Z
weight: 2
description: >
  A script is the medium of writing in a given language — or languages
---

Unicode supports 154 scripts, through which the writing systems of the world are mediated. With the publication of **[Unicode 13.0.0](http://www.unicode.org/versions/Unicode13.0.0/)** on 10 March 2020, the standard now supports [154 scripts](https://www.unicode.org/standard/supported.html). The written word is pervasive and scripts are the basis on which we communicate in writing.

This is how Unicode defines a script: "A collection of letters and other written signs used to represent textual information in one or more writing systems. For example, Russian is written with a subset of the Cyrillic script; Ukranian is written with a different subset. The Japanese writing system uses several scripts" (<a href="https://www.unicode.org/glossary/#script">Glossary of Unicode terms</a>). Within this framework, the different scripts in the world, historical and contemporary, present [wide variations](https://scriptsource.org/cms/scripts/page.php?item_id=entry_detail&uid=cq3q4pwuah).

### Latin script

This is the script that you are likely to use most often: it is the one in which English and many European languages are written, and is the most widely script used today (in addtion, about two-thirds of the writing systems in the world today use alphabetical scripts).

{{< figure src="/images/word_boundaries.png" caption="Latin script features" alt="Latin script features" width="80%">}}

Scripts can be defined according to a number of characteristics, using [Unicode](https://www.unicode.org/glossary/) or [typographical](https://www.adobe.com/ie/products/type/adobe-type-references-tips/glossary.html) terminology. Here are a number of these characteristics in the case of Latin script:

- Latin script is **bicameral**, meaning that it has upper-case and lower-case characters, and is **case-sensitive** — so, we recognize **Brown** as a proper noun and **brown** as an adjective
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
- it is a **cursive** script; in other words, the characters "join up"
- the shape of cursive characters can be determined by the characters to which they are joined; characters can also overlap
- the script directly represents only consonants and long vowel sounds, with short vowel sounds and other phonetic information being denoted by **diacritics**
- unlike Latin script, it is not case-sensitive
- like Latin script, it has native digits
- spaces are used as word-separators

### CJK scripts

**CJK scripts** refer to Chinese, or Han, ideographs used in the writing systems of Chinese and Japanese, and to a more limited extent in Korean. Unicode supports more than eighty thousand Han characters.

{{< figure src="/images/boundaries_han.png" caption="CJK: alignment and boundaries" alt="CJK: alignment and boundaries" width="80%">}}

- CJK scripts are **ideographic**, with characters usually representing a spoken syllable
- CJK scripts are left-to-right and can also be written vertically
- they are not case-sensitive
- CJK scripts do not use spaces as word-separators, though the **justification** of lines leads to adjustments in the placement of characters within their frames
- a CJK character can be thought of as contained a uniform square frame (here, the characters are displayed in visible **bounding boxes** to illustrate features like case and word separation)
