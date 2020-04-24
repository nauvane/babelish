--- 
title: "What is Unicode?"
linkTitle: "What is Unicode?"
date: 2020-03-04T11:47:29Z
weight: 3
description: >
  With the development of Unicode, there is a unique code for each character in each language
---

Unicode is a computer standard that provides a single code for each character in each language . To quote [the Unicode site](https://home.unicode.org/basic-info/overview/), "Unicode provides a unique number for every character, no matter what the platform, program, or language is". 

### Encoding scripts: UTF-8

All of the data associated with a given script are contained in [character code charts](https://www.unicode.org/charts/) maintained by the Unicode Consortium. These charts, then, represent the **character set** of the script in question. 

When you are working in a given application and select a character on a keyboard, you need to be sure that it will then appear on screen: you depend on a **character encoding** for this to happen. 

The most common encoding used today is **UTF-8**. It is the standard encoding for the internet and is also the default in word-processing applications. 

Here are the characters contained in **Basic Latin**, which is the first block of the Latin script in Unicode, in the UTF-8 encoding.

{{< figure src="/images/unicode_basiclatin.png" caption="Basic Latin block in UTF-8" alt="Basic Latin block in Unicode" width="80%">}}

This block contains the familar basic alphabet, and some punctuation and other characters. Note that this chart denotes each character's code point in UTF-8 in **hexadecimal** form, a number system in base 16: `0–9, A–E`. 

Basic Latin begins at `U+0020`, which represents a space, and extends to `U+007E`, which is the tilde character. 

UTF-8 can represent any character in Unicode, which means that you can expect to be able to input any character in any script in the course of your work. The existence of a single standard and a universal encoding like UTF-8 therefore greatly simplifies your work.
 
### How is Unicode organized?

Unicode is made up of sixteen **planes**, with no characters assigned as of yet to planes 4 to 13.

{{< figure src="/images/bmp.png" caption="Unicode planes in UnicodeChecker" alt="Unicode planes in UnicodeChecker" width="80%">}}

The **Basic Multilingual Plane** contains almost all modern languages and a large number of symbols. The **Supplementary Multilingual Plane** contains historical scripts, for example, Egyptian hieroglypics.

{{< figure src="/images/hieroglyph.png" caption="Egyptian hieroglyphic block in UTF-8" alt="Egyptian hieroglyphic block in Unicode" width="80%">}}

The **Supplementary Ideographic Plane** includes CJK ideographs that have been added to more recent versions of Unicode.

{{< figure src="/images/suppplane.png" caption="Supplementary Ideographic Plane in UTF-8" alt="Supplementary Ideographic Plane" width="80%">}}

### Unicode blocks in Latin script

Each plane in Unicode is made up of a number of **blocks**. Latin script, for instance, is made up of a total of 1286 characters in the Basic Multilingual Plane, divided into twelve blocks. 

| Block      | UniView| Unicode |
| ----------- | ----------- | ----------- |
| Basic Latin                      | [Character data](https://r12a.github.io/uniview/?block=basic_latin)                      | [Character chart](http://www.unicode.org/charts/PDF/U0000.pdf) |
| Latin-1 Supplement               | [Character data](https://r12a.github.io/uniview/?block=latin-1_supplement)               | [Character chart](http://www.unicode.org/charts/PDF/U0080.pdf) |
| Latin Extended-A                 | [Character data](https://r12a.github.io/uniview/?block=latin_extended-a)                 | [Character chart](http://www.unicode.org/charts/PDF/U0100.pdf) |
| Latin Extended-B                 | [Character data](https://r12a.github.io/uniview/?block=latin_extended-b)                 | [Character chart](http://www.unicode.org/charts/PDF/U0180.pdf) |
| Latin Extended-C                 | [Character data](https://r12a.github.io/uniview/?block=latin_extended-c)                 | [Character chart](http://www.unicode.org/charts/PDF/U2C60.pdf) |
| Latin Extended-D                 | [Character data](https://r12a.github.io/uniview/?block=latin_extended-d)                 | [Character chart](http://www.unicode.org/charts/PDF/UA720.pdf) |
| Latin Extended-E                 | [Character data](https://r12a.github.io/uniview/?block=latin_extended-e)                 | [Character chart](http://www.unicode.org/charts/PDF/UAB30.pdf) |
| Latin Extended Additional        | [Character data](https://r12a.github.io/uniview/?block=latin_extended_additional)        | [Character chart](http://www.unicode.org/charts/PDF/U1E00.pdf) |
| Halfwidth and Fullwidth Forms    | [Character data](https://r12a.github.io/uniview/?block=halfwidth_and_fullwidth_forms)    | [Character chart](http://www.unicode.org/charts/PDF/UFF00.pdf) |
| IPA Extensions                   | [Character data](https://r12a.github.io/uniview/?block=ipa_extensions)                   | [Character chart](http://www.unicode.org/charts/PDF/U0250.pdf) |
| Phonetic Extensions              | [Character data](https://r12a.github.io/uniview/?block=phonetic_extensions)              | [Character chart](http://www.unicode.org/charts/PDF/U1D00.pdf) |
| Phonetic Extensions Supplement   | [Character data](https://r12a.github.io/uniview/?block=phonetic_extensions_supplement)   | [Character chart](http://www.unicode.org/charts/PDF/U1D80.pdf) |

<figcaption>Unicode blocks in Latin script</figcaption>

&nbsp;

Here are the characters that make up the second of these blocks, **Latin-1 Supplement**.

{{< figure src="/images/latin1supp.png" caption="Latin-1 Supplement in UTF-8" alt="Latin-1 Supplement in UTF-8" width="80%">}}