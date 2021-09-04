# Structured data, SEO and React

When you've built an amazing website, you likely want people to be able to find it when they use a search engine. This post is about how you can add structured data to a site which will help the likes of Google understand your content and get it in front of more eyeballs. We'll illustrate this by applying this to a simple React app.

## What is structured data?

Google, DuckDuckGo and others are proficient at understanding the content of websites. However, scraping HTML is not a highly reliable way to determine the categorisation of content. HTML is about presentation and it can have all manner of different structures. To make the life of search engines easier, there's a standardized format known as "structured data" which can be embedded within a page. That standardized format allows you to explicitly declare the type of content the page contains.

So let's say you've written an article, you can reliably state in a language that Google understands "this page is an article, it has this title, this description and image and was publised on this date". There are hundreds of types of structured data available, and you can read about all of them in depth at https://schema.org/ which is maintained by representatives of the search engine community.

It's worth knowing that whilst there are many types of structure data available to choose from, there are definitely more popular options and those that are more niche. So [Article](https://schema.org/Article) is likely to be used a great deal more than say [MolecularEntity](https://schema.org/MolecularEntity).

There's a variety of formats which can be used to provide structured data; these include [JSON-LD](http://json-ld.org/), [Microdata](https://www.w3.org/TR/microdata/) and [RDFa](https://rdfa.info/). Google explicitly prefer JSON-LD and so that's what we'll focus on.

## Adding structured data to a website

Google do a good job of demostrating 

https://developers.google.com/search/docs/advanced/structured-data/search-gallery

https://github.com/facebook/docusaurus/pull/5322

https://search.google.com/test/rich-results

Structured data is a standardized format for providing information about a page and classifying the page content; for example, on a recipe page, what are the ingredients, the cooking time and temperature, the calories, and so on.

A way to improve the discoverability of a website is through SEO (Search Engine Optimization). This post is about an aspect of that called structured


There's a particular  
a blog post on Structured Data, SEO and React
