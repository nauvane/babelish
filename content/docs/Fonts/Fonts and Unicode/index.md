---
title: "Fonts and Unicode"
linkTitle: "Fonts and Unicode"
date: 2020-03-04T11:56:09Z
weight: 5
description: >
  How typefaces allow you to access the resources of Unicode
---

### Fonts and scripts

Unicode has led to the development of a range of fonts that encompass not only the major scripts in use in the world today, but also historical and iconographic materials. 

### CJK fonts

Thus, [the Noto CJK Simplified Chinese font](https://noto-website-2.storage.googleapis.com/pkgs/NotoSerifCJKsc-hinted.zip) provides support for the following major contemporary scripts:

>Cyrillic, Han, Hangul, Hiragana, Katakana, Latin, Simplified Han, Traditional Han

This means in turn that it can encode content in the following languages:

> Afrikaans, Albanian, Asu, Basque, Bemba, Bena, Bulgarian, Cantonese, Catalan, Chiga, Chinese, Chinese (Simplified), Cornish, Danish, Embu, English, Faroese, Filipino, Friulian, Galician, German, Gusii, Icelandic, Indonesian, Irish, Italian, Japanese, Kabuverdianu, Kalaallisut, Kalenjin, Kamba, Kikuyu, Kinyarwanda, Korean, Low German, Luo, Luxembourgish, Luyia, Machame, Makhuwa-Meetto, Makonde, Malagasy, Malay, Manx, Meru, Morisyen, North Ndebele, Norwegian Bokmål, Norwegian Nynorsk, Nyankole, Oromo, Portuguese, Romansh, Rombo, Rundi, Russian, Rwa, Samburu, Sango, Sangu, Scottish Gaelic, Sena, Shambala, Shona, Soga, Somali, Spanish, Swahili, Swedish, Swiss German, Taita, Teso, Vietnamese, Vunjo, Zulu

The CJK fonts were developed jointly with Adobe and [the Source Han typefaces](https://source.typekit.com/source-han-serif/) are the equivalent of the Noto versions. Like European serif fonts in particular, the development of Source Han is rooted in calligraphic traditions.

<iframe width="80%" height="315" src="https://www.youtube.com/embed/yNfYdxgV1jA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<figcaption>Introducing Source Han Serif, Adobe's open source Pan-CJK typeface</figcaption>
&nbsp;

### European scripts, ancient and modern

[Clara](http://mirrors.ctan.org/fonts/clara.zip), by contrast, encompasses a range of European scripts, ancient and modern, including Latin and Cyrillic, as well as the medieval Irish script known as Ogham. It can therefore support the following languages:

>Afrikaans, Akan, Albanian, Asturian, Asu, Basque, Belarusian, Bemba, Bena, Bosnian, Breton, Bulgarian, Catalan, Central Atlas Tamazight, Chiga, Colognian, Cornish, Croatian, Czech, Danish, Duala, Dutch, Embu, English, Estonian, Ewe, Faroese, Filipino, Finnish, French, Friulian, Fulah, Galician, Ganda, German, Gusii, Hausa, Hawaiian, Hungarian, Icelandic, Inari Sami, Indonesian, Irish, Italian, Jola-Fonyi, Kabuverdianu, Kalaallisut, Kalenjin, Kamba, Kikuyu, Kinyarwanda, Lithuanian, Low German, Lower Sorbian, Luba-Katanga, Luo, Luxembourgish, Luyia, Macedonian, Machame, Makhuwa-Meetto, Makonde, Malagasy, Malay, Maltese, Manx, Meru, Morisyen, Nama, North Ndebele, Northern Sami, Norwegian Bokmål, Norwegian Nynorsk, Nuer, Nyankole, Oromo, Polish, Portuguese, Quechua, Romanian, Romansh, Rombo, Rundi, Russian, Rwa, Samburu, Sango, Sangu, Scottish Gaelic, Sena, Serbian, Shambala, Shona, Slovak, Slovenian, Soga, Somali, Spanish, Swahili, Swedish, Swiss German, Taita, Teso, Tongan, Turkish, Turkmen, Ukrainian, Upper Sorbian, Uzbek, Vunjo, Walser, Western Frisian, Wolof, Zulu

The scope of the font is considerably wider than many of the system fonts installed by default on computers. This makes it a useful choice for your work. 

### Phonetic transcription

A set of Unicode blocks that is fully supported in the Noto Sans and Serif fonts, [Charis SIL](https://software.sil.org/charis/) and Clara are among those which cover [the phonetic script](https://www.internationalphoneticassociation.org/sites/default/files/phonsymbol.pdf) of the [International Phonetic Association](https://www.internationalphoneticassociation.org/).

{{< figure src="/images/ipa_eg.png" caption="An IPA transcription" alt="An IPA transcription" width="80%">}}

You can use a dedicated keyboard where extended inputting in a specialized block is required. 

### Unicode block by block

Using LibreOffice, you can readily explore Unicode blocks contained in a given font. Consider first the case of Noto Serif. To view the characters encoded in a font, select the omega icon and the select **More Characters**.

{{< figure src="/images/omega.png" caption="Access to Unicode blocks in LibreOffice" alt="Access to Unicode blocks in LibreOffice" width="80%">}}

You can then access individual blocks using a drop-down menu.

{{< figure src="/images/blocks.png" caption="Unicode blocks in Noto Serif" alt="Unicode blocks in Noto Serif" width="80%">}}

You can then see the characters that are available in a specific block.

{{< figure src="/images/ipa.png" caption="IPA Extensions in Noto Serif" alt="IPA Extensions in Noto Serif" width="80%">}}

In LibreOffice, you can input characters using this interface, which is a convenient option in isolated cases. 

### Symbols

Unicode extends also to typographical and many other symbols. 

{{< figure src="/images/symbola.png" caption="Symbola: musical symbols in Unicode" alt="Symbola: musical symbols in Unicode" width="80%">}}

The font [Symbola](https://dn-works.com/ufas/) allows access to multilingual blocks and also to [a very wide range of Unicode symbols](https://dn-works.com/wp-content/uploads/2020/UFAS-Docs/Symbola.pdf). 

### Combining scripts

Dedicated Latin scripts were developed for use with Source Serif and Noto CJK fonts. This means that content in European and Asian languages can easily be combined using the same font.

{{< figure src="/images/noto_cjk_sc.png" caption="Noto Serif and Sans Serif CJK: Latin and Simplified Chinese" alt="Noto Serif and Sans Serif: Latin and CJK Simplified Chinese" width="80%">}}

Though Latin and CJK fonts use different baselines and other reference points, they are aligned in such a way as to ensure content in different scripts is integrated.

{{< figure src="/images/lodoccjk.png" caption="Latin and CJK scripts in Libre Office" alt="Latin and CJK scripts in Libre Office" width="80%">}}

LibreOffice, among other word-processors, now has good support for the display and printing of characters in markedly different scripts.

Similarly, the use of a font like Noto Serif of Charis SIL or Clara makes it possible to combine Latin and IPA scripts, as we can see in the example above.