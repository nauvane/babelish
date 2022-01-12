---
title: "Using the International Phonetic Alphabet"
linkTitle: "Using the International Phonetic Alphabet"
date: 2020-06-17T17:38:28+01:00
weight: 5
description: >
  Learn how to carry out phonetic transcriptions
---

The [International Phonetic Alphabet](https://www.internationalphoneticassociation.org/content/full-ipa-chart) is an alphabetical system of phonetic notation. It is based on [Latin script](/docs/scripts-and-unicode/what-is-a-script). 

{{< figure src="/images/ipachart.png" caption="The IPA chart (source: [r12a](https://r12a.github.io/pickers/ipa/))" alt="The IPA chart (source: r12a)" width="80%">}}

One convenient way to generate a phonetic transcription using the IPA is via [an IPA picker](https://r12a.github.io/pickers/ipa/): you select the relevant symbols as they appear in the IPA chart and they then appear in a box at the top of the screen. Here is a transcription of the German word **_für_**.
You can then, for example, copy and paste a transcription into a word-processing document. 

{{% alert title="Tip" color="primary" %}}
Remember the keyboard shortcuts that you can use for copying and pasting: to copy, CTRL+C (Windows) or CMD+C (macOS); and to paste, CTRL+V (Windows) or CMD+C (macOS).
{{% /alert %}}

When you do so, it's important you ensure that the word-processor is equipped with a [font](/docs/fonts/installing-fonts) that supports the IPA.

{{< figure src="/images/ipafonts.png" caption="IPA-compatible fonts (source: r12a)" alt="IPA-compatible fonts (source: r12a)" width="80%">}}

It is also possible to enter phonetic symbols directly in a word-processing application, again provided that a suitable font has been selected. 

{{< figure src="/images/ipaeg.png" caption="Phonetic transcriptions in Libre Office" alt="Phonetic transcriptions in Libre Office" width="80%">}}

[Libre Office](https://www.libreoffice.org/) lends itself particularly well to this task. You can see that the transcription of the German word "für" includes two symbols, the triangular colon and the small turned **a** character, that do not form part of the Basic Latin script. The IPA is, however, included in [Unicode](/docs/scripts-and-unicode/what-is-unicode) and when you need to input a symbol that is not to be found in the Basic Latin block, you can click on the omega icon in Libre Office in order to select the relevant character.

{{< figure src="/images/turneda.png" caption="Selecting an IPA symbol in Libre Office" alt="Selecting an IPA symbol in Libre Office" width="80%">}}

A panel will then open below the menu bar. Select the relevant Unicode block: in this case, **IPA Extensions**, and then you can insert the required symbol.
