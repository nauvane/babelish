---
title: "What is Markdown?"
linkTitle: "What is Markdown?"
date: 2020-03-04T12:19:41Z
weight: 2
description: >
  Markdown is a lightweight and flexible form of plain-text markup
---

As a first step in generating structured documents, you should experiment with Markdown, 'a plain text format for writing structured documents', as it is defined on the [CommonMark site](https://commonmark.org/).

{{< figure src="/images/commonmark.png" caption="Markdown" alt="Markdown" width="80%">}}


To begin with, take the [ten-minute CommonMark tutorial](https://commonmark.org/help/tutorial/). Then experiment in writing Markdown on the [pandoc site](https://pandoc.org/try/?text=&amp;from=commonmark&amp;to=).

Markdown was originally developed by John Gruber and its rationale was to simplify as far as possible the process of formatting a computer file for display, as Gruber says:

>    The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions.

One of the advantages of Markdown is that it is designed to produce **structured documents**, in which the function of distinct elements is clearly encoded in the file. Thus, a document is made up of 'content' and of 'markup', the latter consisting of tags and other identifiers that designate component parts of the content. A structured document is in plain text where the content and markup alike are human-readable and are composed using [a pre-determined set of characters](https://www.w3.org/2001/06/utf-8-test/UTF-8-demo.html).

So, you use minimal code to designate a heading and other elements:

     # This is a level-one heading
     
     This is a paragraph with a *link* to [Hugo](http://gohugo.io)
     
     Here is an unordered list: 
     
     - Hugo 
     - Jekyll

     And here is a block quotation: 

    >En 1815, M. Charles-François-Bienvenu Myriel était évêque de Digne. 
    >C'était un vieillard d'environ soixante-quinze ans; il occupait le siège
    >de Digne depuis 1806.
     
A paragraph, by contrast, doesn't bear any specific code in Markdown, but is simply delimited by being followed by a blank line.
     
This practice is different from how a word-processor is normally used, where one typically applies a format to a given element of a document, e.g. by applying bold to a heading for display, rather than designating its structural function. The advantage of a structured document, where, say, a heading or a list is designated as such, is that information about the structure can be re-used, just as much as the content: a single Markdown file can give rise to a PDF for printing, or to a webpage via Hugo, with the structure being displayed as appropriate in each case.

#### Non-textual elements

Because Markdown is a plain-text format, it doesn't directly include or represent binary sources, like an image file in ``jpeg`` format, the contents of which are not human-readable; a file in a word-processor, which is itself in binary format, will directly display the image. Rather, Markdown, [when used with Hugo](http://gohugo.io/content-management/shortcodes/#use-hugo-s-built-in-shortcodes), can instruct the program to retrieve these from source:

{{< figure src="/images/brackets.png" caption="Markdown in Brackets" alt="Markdown in Brackets" width="80%">}}

Again we see that instructions to the computer in a plain-text file are contained in human-readable text throughout, just like content and markup. Webpages, which are written in HTML, are also plain-text, and contain instructions for the retrieval of image files, for instance, in exactly the same way. This means that you can draw on image files, or movie files, or sound files as you write your content and then rely on a program like Hugo to ensure that instructions for the correct retrieval and display of these are duly incorporated into your webpage. An editor like Brackets can equally incorporate an image file into a format for printing, alongside your structured plain text, as you can see in the screenshot above: note that in the Markdown file itself, the image is not displayed.

By definition, Markdown is designed for writing structured documents and, like markup languages, makes use of a distinct set of formatting conventions. Because information on style is encoded, like content, in plain  text, content is not subordinated to presentation, meaning inter alia that Markdown files are smaller in size. Markdown files can incorporate *metadata*, again in plain text. A variety of forms of Markdown exist, with work being undertaken at the moment to develop a common standard, namely [CommonMark](http://commonmark.org/). Markdown is both a plain text format and a format that can readily be converted to other formats, including binary ones. These factors testify to the *accessibility* and to the *flexibility* of Markdown.