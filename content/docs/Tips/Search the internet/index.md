---
title: "Search the internet"
linkTitle: "Search the internet"
date: 2020-03-03T14:11:32Z
weight: 9
description: 
  How do you locate the information you seek on the internet?
---

The most common kind of search is via a search engine querying the public internet. **[Google](https://www.google.com/)** is the most commonly used search engine. **[DuckDuckGo](https://duckduckgo.com/)** is an instance of a search engine that allows greater scope for privacy, in that it does not track users and does not store personal information. 

### Search tips

- to search a specific site, use the following method: `CJK site:unicode.org` (note that you do not need to specify the protocol (`https`) nor include the `www` prefix)
- to search for exact matches of a specific phrase, use quotation marks: `"detective fiction"`, or `"Victor Hugo" drawings`
- you can use wildcards to extend the scope of a search: `i think therefore *`
- wildcards can also be used with search terms: `gramm*` will return results with "grammar", "grammatical", "grammaticalization", and so on
- a wildcard will also return terms with variant spellings: `characteri?ation` will return "characterization" and "characterisation"
- to limit your search to resources with a specific page title, use this method: `character intitle:unicode`
- to find out which pages link to a site you are interested in, use the following method: `link:europeana.eu` (in this case, you can locate versions of the site in question in different European languages)
- you can limit your search by specifying a file type: `"Victor Hugo" drawings filetype:jpg`
- you can search social media by using the relevant prefix as follows: `@twitter unicode`

You can also use what are termed Boolean operators in your searches:

- `novel AND fiction`: search for material where **both** terms occur
- `novel OR fiction`: search for material which contains **either or both** of the terms (thus, wider in scope that a search with AND)
- `novel NOT fiction`: search for material that contains the first term but does **not** contain the second

You can also exclude a term by using a hyphen: `Celtic -football`

These operators can also be combined: `"Victor Hugo" AND (novel OR poetry)`

### Searching repositories

Major data collections or repositories have their own dedicated search facilities. 

Take the example of **[data.bnf.fr](https://data.bnf.fr/)**, a public database provided by the [Bibliothèque nationale de France](https://www.bnf.fr/).

{{< figure src="/images/databnf.png" caption="data.bnf.fr: a web interface to BNF data" alt="data.bnf.fr: a web interface to BNF data" width="80%" >}}

As you can see, this site provides its own search engine, through which you can apply several of the search techniques described above.

Because this database has its own public domain name, you can also search its contents using a search engine, again using the techniques described above and some further search options:

- to locate items connected to a given keyword, e.g. "roman", meaning "novel" in French, you can  search with wildcards: `roman* site:data.bnf.fr`

This search will produce a set of terms connected to "roman", e.g. "roman d'aventures", "roman grec", "roman à clefs".

[Repositories that you access through the Library](https://libguides.ucc.ie/az.php) will also have their own search engines. Note also that you can search across these from the Library homepage.

{{< figure src="/images/onesearch.png" caption="OneSearch: applying search techniques in the Library homepage" alt="OneSearch: applying search techniques in the Library homepage" width="80%" >}}

### Searching the Creative Commons

You may on occasion wish to use relevant illustrations in your work.

{{< figure src="/images/ccsearch.png" caption="Image search in the Creative Commons" alt="Image search in the Creative Commons" width="80%" >}}

The **[Creative Commons](https://creativecommons.org/)** is a major open-access resource with its own [dedicated search engine](https://ccsearch.creativecommons.org/) — note too its guidance on its own specialized [search query syntax](https://search.creativecommons.org/search-help). Make sure to [document your use of such sources](https://creativecommons.org/use-remix/attribution/) by including captions with the relevant copyright information.
