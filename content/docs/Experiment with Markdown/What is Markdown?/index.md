---
title: "What is Markdown?"
linkTitle: "What is Markdown?"
date: 2020-03-04T12:19:41Z
weight: 2
description: >
  Markdown is a lightweight and flexible form of plain-text markup
---

Markup is a means of denoting the structure of a document. Any markup document is made up of "content" and of "markup", the latter consisting of simple tags and other identifiers that designate component parts of the content, for example, a heading, or a list. 

### Markup in web pages

A commonplace example is the use of markup to denote the structure of webpages. 

> `<!DOCTYPE html>`  
> `<html>`  
> `<head> `  
> `<title>This is an HTML document</title>`  
> ` </head>`  
> `<body>`  
> `<h1>This is a heading</h1>`  
> `<p>This is a paragraph.</p>`  
> `</body>`  
> `</html> `

Today, the form of markup used for writing structured documents for the web is **Hypertext Markup Language** and the current standard is **[HTML5](https://www.w3schools.com/html/default.asp)**. 

This markup language is made up of a series of **[tags](https://www.w3schools.com/tags/default.asp)**. An HTML document is composed by default up of two main components, a `<head>`, which contains information about the document, including its `<title>`, and a `<body>`, which is made up of the content, for instance, headings and paragraphs, as shown above. 
  
HTML5 also contains tags for all of the other expected elements of structured documents, such as [ordered](https://www.w3schools.com/tags/tag_ol.asp) and [unordered](https://www.w3schools.com/tags/tag_ul.asp) lists, [inline](https://www.w3schools.com/tags/tag_q.asp) and [block](https://www.w3schools.com/tags/tag_blockquote.asp) quotations, [tables](https://www.w3schools.com/tags/tag_table.asp), and [links](https://www.w3schools.com/tags/tag_a.asp). It also contains tags like `<img>` and `<video>` to display audio-visual material, as well as markup for inline components, such as `<em>` or `<strong>`. 
    
Note also that in HTML an opening tag is as a rule matched by a closing tag:

> `this word is <em>emphasized</em>`

### Markup and Markdown

Markdown is a format where text is encoded with minimal markup: hence **Mark*down***

Markdown is designed for writing structured documents and makes use of a distinct but simple set of formatting conventions. 

Markdown files are written in [UTF-8](https://www.w3.org/2001/06/utf-8-test/UTF-8-demo.html).

### Simple structured documents in Markdown

As a first step in generating structured documents, you can experiment with **Markdown**, 'a plain text format for writing structured documents', as it is defined on the [CommonMark site](https://commonmark.org/).

{{< figure src="/images/commonmark.png" caption="Content in Markdown rendered for display" alt="Markdown" width="80%">}}

Next, take the [ten-minute CommonMark tutorial](https://commonmark.org/help/tutorial/). 

And then experiment in writing Markdown on the [pandoc site](https://pandoc.org/try/?text=&amp;from=commonmark&amp;to=), where you can experiment further by transforming one kind of markup into another.

### Markdown in practice

So, you use minimal code to designate a heading and other elements:

>     # This is a level-one heading
     
>     This is a paragraph with a *link* to [CommonMark](https://commonmark.org/)

A paragraph, by contrast with a heading, doesn't bear any specific code in Markdown, but is simply delimited by being followed by a blank line.

Single asterisks denote emphasis, or italics; double asterisks denote strong emphasis, or bold type.
     
Here is an unordered list: 
>     - markup
>     - markdown

And here is a block quotation: 

>  `> En 1815, M. Charles-François-Bienvenu Myriel était évêque de Digne. C'était un vieillard d'environ soixante-quinze ans; il occupait le siège  de Digne depuis 1806.`
     
### Advantages of Markdown
     
This practice is different from how a word-processor is normally used, where one typically applies a format to a given element of a document, e.g. by applying bold to a heading for display, rather than designating its structural function. 

The advantage of a structured document, where, say, a heading or a list is designated as such, is that information about the **structure** can be re-used, just as much as the **content**: a single Markdown file can give rise to a PDF for printing, or to a webpage via an application like [Hugo](https://gohugo.io/), with the structure being displayed as appropriate in each case. 

This site is made up of Markdown files which are converted into webpages using Hugo.

{{< figure src="/images/markdown.png" caption="Developing web content in Markdown" alt="Developing web content in Markdown" width="80%">}}

By definition, then, Markdown is designed for writing structured documents and, like markup languages, makes use of a distinct set of formatting conventions. Because information on style is encoded, like content, in plain  text, content is not subordinated to presentation, meaning that Markdown files are smaller in size. 

Markdown files can incorporate also **metadata**, again in plain text. 

{{< figure src="/images/metadata.png" caption="File metadata in Markdown" alt="File metadata in Markdown" width="80%">}}

The four elements of metadata included here are the document's title, its author, a set of tags to denote its content, and an abstract, or summary.

### A standard for Markdown

A variety of forms of Markdown exist, with work being undertaken at the moment to develop a common standard, namely [CommonMark](http://commonmark.org/). 

Markdown, like many of the tools you might use with it, is open source (subject to a [Creative Commons license](https://creativecommons.org/licenses/by-sa/4.0/)).

### Why markup matters

Markup matters because it is widely used to store structured data, including a wide range of data used in [language databases](https://ec.europa.eu/jrc/en/language-technologies) and in [corpora](https://www.clarin.eu/resource-families). 

{{< figure src="/images/hr.png" caption="EU legislation: a structured document in Croatian" alt="EU legislation: a structured document in Croatian" width="80%">}}

In EU translation databases, texts like legal documents are **encoded** using [XML markup](https://www.w3schools.com/xml/xml_whatis.asp), consisting of specialized tags, e.g. `<p>` for **paragraph**, or `<head>` for a **heading** that contains information about a document. 
  
  Collections of electronic texts are a further example of the use of markup. A local example is [CELT](https://celt.ucc.ie/about.html), which is a collection of materials relating to Irish literary and historical culture in the languages represented on the island, including Irish, Latin, Anglo-Norman French and English. CELT makes use of [specialized markup](https://celt.ucc.ie//links.html#sgmltei) designed for use with just these kinds of sources.
  
  As you work with specialized collections like these in the course of your studies, you will learn more about the different kinds of markup that allow large collections of linguistic data to be used in flexible ways. Experimenting with Markdown is a way of beginning to understand other forms of markup.