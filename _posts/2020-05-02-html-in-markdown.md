---
layout: single
title: HTML in Markdown
date: '2020-05-02 19:53:27 -0500'
excerpt: This post should
header:
  overlay_image: /assets/images/site/earth_tile.jpg
  overlay_filter: 0.25
  caption: 'Photo credit: [**Unsplash**](https://unsplash.com)'
  actions:
    - label: More Info
      url: 'https://unsplash.com'
categories: jekyll html markdown
---

# Introduction

The markdown writer I use for creating blog posts is Atom's markdown writer. The package can be downloaded from [here](https://atom.io/packages/markdown-writer) and its background information states, "Works great with static blogging . . . ." Zhuochun is the author of markdown writer and maintains a [wiki](https://github.com/zhuochun/md-writer/wiki/Settings) on the package.  Three packages meet my needs so far:  `markdown-writer`, `language-markdown` and `markdown-preview-enhanced`.

# Keep the html

One of the challenges in the way that I put posts together is I like to be able to toggle back and forth between markdown and html.  For example in a markdown post, I might like to include a searchable table.

# Example 1

## Code

```htm
<div class="rob">
"hello world!"
</div>

```

## Output

<div class="rob">
"hello world!"
</div>

---

# Example 2

## Code

```html

<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

```

## Output

<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

---
# Example 3

## Code

```HTML
<!--https://www.w3schools.com/html/html_tables.asp-->
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

## Output

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
