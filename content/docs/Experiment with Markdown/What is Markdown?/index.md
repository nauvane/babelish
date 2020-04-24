---
title: "What is Markdown?"
linkTitle: "What is Markdown?"
date: 2020-03-04T12:19:41Z
weight: 2
description: >
  Markdown is a lightweight and flexible form of plain-text markup
---

As a first step in generating structured documents, you can experiment with **Markdown**, 'a plain text format for writing structured documents', as it is defined on the [CommonMark site](https://commonmark.org/).

{{< figure src="/images/commonmark.png" caption="Content in Markdown rendered for display" alt="Markdown" width="80%">}}

Next, take the [ten-minute CommonMark tutorial](https://commonmark.org/help/tutorial/). 

And then experiment in writing Markdown on the [pandoc site](https://pandoc.org/try/?text=&amp;from=commonmark&amp;to=), where you can experiment further by transforming one kind of markup into another.

### Markup and Markdown

Markdown is a format where text is encoded with minimal markup: hence **Mark*down***

Markdown is designed for writing structured documents and makes use of a distinct set of formatting conventions. A markup document is made up of "content" and of "markup", the latter consisting of simple tags and other identifiers that designate component parts of the content, for example, a heading, or a list. Markdown files are written in [UTF-8](https://www.w3.org/2001/06/utf-8-test/UTF-8-demo.html).

### Markup in practice

So, you use minimal code to designate a heading and other elements:

>     # This is a level-one heading
     
>     This is a paragraph with a *link* to [CommonMark](https://commonmark.org/)

Single asterisks denote italics; double italics denote bold.
     
Here is an unordered list: 
>     - markup
>     - markdown

And here is a block quotation: 

>  `> En 1815, M. Charles-François-Bienvenu Myriel était évêque de Digne. C'était un vieillard d'environ soixante-quinze ans; il occupait le siège  de Digne depuis 1806.`
     
A paragraph, by contrast, doesn't bear any specific code in Markdown, but is simply delimited by being followed by a blank line.

### Advantages of Markdown
     
This practice is different from how a word-processor is normally used, where one typically applies a format to a given element of a document, e.g. by applying bold to a heading for display, rather than designating its structural function. 

The advantage of a structured document, where, say, a heading or a list is designated as such, is that information about the **structure** can be re-used, just as much as the **content**: a single Markdown file can give rise to a PDF for printing, or to a webpage via an application like [Hugo](https://gohugo.io/), with the structure being displayed as appropriate in each case. 

This site is made up of Markdown files which are converted into webpages using Hugo.

{{< figure src="/images/markdown.png" caption="Developing web content in Markdown" alt="Developing web content in Markdown" width="80%">}}

By definition, then, Markdown is designed for writing structured documents and, like markup languages, makes use of a distinct set of formatting conventions. Because information on style is encoded, like content, in plain  text, content is not subordinated to presentation, meaning that Markdown files are smaller in size. 

Markdown files can incorporate also **metadata**, again in plain text. 

{{< figure src="/images/metadata.png" caption="File metadata in Markdown" alt="File metadata in Markdown" width="80%">}}

### A standard for Markdown

A variety of forms of Markdown exist, with work being undertaken at the moment to develop a common standard, namely [CommonMark](http://commonmark.org/). 

Markdown, like many of the tools you might use with it, is open source (subject to a [Creative Commons license](https://creativecommons.org/licenses/by-sa/4.0/)).