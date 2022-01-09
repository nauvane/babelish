--- 
title: "What is Unicode?"
linkTitle: "What is Unicode?"
date: 2020-03-04T11:47:29Z
weight: 3
description: >
  With the development of Unicode, there is a unique code for each character in each language — or script
---

Unicode is a computer standard that provides a single code for each character in each language, or each script, bearing in mind that a given script can be used by more than one language. To quote [the Unicode site](https://home.unicode.org/basic-info/overview/), "Unicode provides a unique number for every character, no matter what the platform, program, or language is". 

### Encoding scripts

All of the data associated with a given script are contained in [character code charts](https://www.unicode.org/charts/) maintained by the Unicode Consortium. These charts, then, represent the **character set** of the script in question. 

Here are the characters contained in **Basic Latin**, which is the first block of the Latin script in Unicode.

{{< figure src="/images/unicode_basiclatin.png" caption="Basic Latin block in Unicode" alt="Basic Latin block in Unicode" width="80%">}}

This block contains the familar basic alphabet, and some punctuation and other characters. Note that this chart denotes each character's code point in Unicode in **hexadecimal** form, a number system in base 16: `0–9, A–F`.

Basic Latin begins at `U+0020`, which represents a space, and extends to `U+007E`, which is the tilde character. 

Each and every character in Unicode has its unique hexadecimal reference in this form.
 
### How is Unicode organized?

Unicode is made up of sixteen **planes**, with no characters assigned as of yet to planes 4 to 13.

{{< figure src="/images/bmp.png" caption="Unicode planes in UnicodeChecker" alt="Unicode planes in UnicodeChecker" width="80%">}}

The **Basic Multilingual Plane** contains almost all modern languages, including those using the Latin, Arabic and CJK scripts, and also a large number of symbols. 

The **Supplementary Multilingual Plane** contains historical scripts, for example, Egyptian hieroglypics.

{{< figure src="/images/hieroglyph.png" caption="Egyptian hieroglyphic block in UnicodeChecker" alt="Egyptian hieroglyphic block in Unicode" width="80%">}}

The **Supplementary Ideographic Plane** includes CJK ideographs that have been added to more recent versions of Unicode.

{{< figure src="/images/suppplane.png" caption="Supplementary Ideographic Plane in UnicodeChecker" alt="Supplementary Ideographic Plane" width="80%">}}

### Unicode blocks: the case of Latin script

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

{{< figure src="/images/latin1supp.png" caption="Latin-1 Supplement in the Basic Multilingual Plane" alt="Latin-1 Supplement in the Basic Multilingual Plane" width="80%">}}

Unicode charts are now available in [French](https://www.unicode.org/charts/fr/) as well as English, with the added possibility of [searching for characters by name](https://www.unicode.org/charts/fr/charindex.html).

### How computers handle characters

When you are working in a given application and select a character on a keyboard, you need to be sure that it will then appear on screen: you depend on a **character encoding** for this to happen. 

The most common encoding used today is **UTF-8**. It is the standard encoding for the internet and is also the default in word-processing applications. When you enter a character in UTF-8, a computer will then transform that into binary code in **bits**, or minimal units of digital information (a **0** or a **1** in base 2 numbers). 

For example, the character **A** in UTF-8 has the following value in binary code: `01000001`.

{{< figure src="/images/unicode_utf.png" caption="Unicode and UTF code points in UnicodeChecker" alt="Unicode and UTF code points in UnicodeChecker" width="80%">}}

Here, you can see the familiar hexadecimal reference for upper-case **a** in Unicode. UTF-8 is one of three **transformation formats**, alongside **UTF-16** and **UTF-32**. They differ according to the number of **bytes**, or units of 8 bits, they use to encode a character. UTF-8 uses between one and four 8-bit bytes; UTF-16 uses two bytes (that is, 16 bits at a minimum) or four bytes; UTF-32 uses four bytes to encode each character (that is, 32 bits). 

{{< figure src="/images/a_length.png" caption="Code lengths in Unicode and in UTFs" alt="Code lengths in Unicode and in UTFs" width="80%">}}

Here again are some data for the upper-case character **a**. You can see that there is one codepoint or code unit in each case, but the number of bytes varies from one to four, with UTF-8 being the most economical format for simple characters in Latin script. This is one reason why today it is by far the most widely used encoding in the internet. 

{{< figure src="/images/ij_length.png" caption="IJ: code length" alt="IJ: code length" width="80%">}}

By contrast, the upper-case **[ij](/docs/fonts/types-and-usage/#digraphs-and-ligatures)** digraph as used in Dutch represents a single code point and requires two bytes in UTF-8. An **[em-dash](/docs/tips/smart-typography/#dashes)** requires three bytes.

{{< figure src="/images/emrule_length.png" caption="Em-dash: code length" alt="Em-dash: code length" width="80%">}}

CJK characters in UTF-8 are as a rule longer than those in Latin scripts. 

{{< figure src="/images/5929_length.png" caption="CJK character: code length" alt="CJK character: code length" width="80%">}}

What, then, is the purpose of any of these transformation formats? It is to connect a Unicode reference-point to the purely binary encoding through which a computer operates.

{{< figure src="/images/unicode_binary.png" caption="Translating code points between Unicode and binary" alt="Translating code points between Unicode and binary" width="80%">}}

It is in binary format that the characters you type are ultimately stored in a computer — in other words, in bits and in turn in bytes. This explains what the size of a file, and all of the data it may contain in the form of numbers, formulae or text, is likewise expressed in bytes (e.g. kilobytes, megabytes).

{{< figure src="/images/kb.png" caption="File size in kilobytes (k)" alt="File size in kilobytes (k)" width="80%">}}

Transformation formats such as UTF-8 can represent any character in Unicode, which means that you can expect to be able to input any character in any script in the course of your work. The existence of a single standard and a universal encoding like UTF-8 therefore greatly simplifies your work. UTF-8 values are also much easier to handle that plain binary code would be.
