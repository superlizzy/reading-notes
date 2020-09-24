# 04 - Structure web pages with HTML

### Plan

The first step in creating a web page does not involve any coding. Instead, it involves listening and researching. If you're designing a website for a client, it is often more helpful to ask them about their business, target customer, and goals rather than how they see the website looking.

Depending on the purpose and the audience of the web page, you can then sketch a "wire frame" version on paper, or digitally, that will show where content will be on the page. This wire frame won't have the distraction of colors, pictures, and actual content, so the client can focus on the order and placement of highlighted content.

---

### Structure

Structure is coded using HTML (hyper-text markup language), and stlyed with CSS (cascading stylesheets).

Here are the basics of creating an HTML page:

**Elements**

Ususally made up of two tags - an opening tag and a closing tag

```
<html>
   <head>
      <title>
   </head>
   <body>
   </body>
</html>
```

**Attributes**

Added in an element's opening tag to provide more information about the element. Comprised of an attribute `name` and an attribute `value`. These names and values come from a defined list that is allowed within HTML code.

**HTML5 Layout Elements**

Although new, using these tags to define common parts of your web page can help with search engine optimization (SEO) and help users utilizing screen readers to better access your page.

HTML5 Layout Element | What it is generally used for...
---------------------|--------------
`<header>` | Contain page headings and subheadings, often contains the `<nav>`. Used within an `<article>`, groups the articles heading information.
`<footer>` | Contains copyright information, a secondary navigation (some developers use the `<nav>` tag again in the footer), and other information.
`<nav>` | Signifying the page's main navigation menu.
`<article>` | Groups an article together. Articles can contain their own header, footer, aside, sections, etc.
`<aside>` | Signifying a group of content that applies to the entire page, or to the entire article if used within `<article>`
`<section>` | Sections of your page content that don't fit into an article or other layout element, but should be grouped together. Can be useful to break up long articles.
`<hgroup>` | Though not universally adopted, this groups text headings and subheadings together, even if the `<p>` tag is used, to help with SEO and readability.
`<figure>` | Images, videos, graphs, etc. Can also use `<figcaption>` to include a descriptive caption.
`<div>` | A container for the entire page, or other uses that are not better served with an HTML5 layout element. It will need to contain a `name` and often a `class` attribute.



---



[Back to Home](https://superlizzy.github.io/reading-notes/)