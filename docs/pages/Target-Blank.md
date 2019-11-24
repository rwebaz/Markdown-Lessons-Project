---
title: Target Blank
layout: default
excerpt: Place the introducing line of text ie.) the 'tagline' here ...
hint: Place the intro paragraph ie.) the 'hypothesis' here ...
repo: Markdown-Lessons-Project
ver_date: 11-20-19
navigation_weight: 8
categories: page
---
{% include toc.md %}

## First Subtitle

> **Hint**. {{ page.hint }}

More to come ...

### How To Force a New Target Blank When Clicking A GFM Hyperlink

More to come ...

#### Solution

More to come ...

#### The Code

More to come ...

#### Break It Down

To route to an external link, or to a new tabbed page within your browser, start with a clickable description of the link enveloped in a set of brackets `[...]`, as follows:

```liquid
{% raw %}
[temporarily disable liquid tag processing]
{% endraw %}
```

Next envelope the URL to the destination of your link in a set of parenthesis `(...)` and bunk the URL right next to the clickable description of the link.

**Note**. Place no spaces between the description brackets and the destination parenthesis.

```liquid
{% raw %}
[temporarily disable liquid tag processing](https://shopify.github.io/liquid/tags/raw/)
{% endraw %}
```

Finally, add the title and the target to the ensemble, as follows:

From your GitHub Flavored Markdown, or **GFM** `(.md)` page ...

Append your `(.md)` external link with the `{:title="Click to Visit ..."}` and `{:target="_blank"}` kramdown statements.

```liquid
{% raw %}
[temporarily disable liquid tag processing](https://shopify.github.io/liquid/tags/raw/){:title="Click to Visit the Raw page at Shopify"}{:target="_blank"}
{% endraw %}
```

**Note**. Again, place no spaces between the description brackets and the destination parenthesis, nor the title braces, nor the target braces.

## Summation

The components of a successful external link in markdown are, as follows:

- First, clickable text enveloped in a single set of bracket characters `[...]`,

- Followed by, the complete URI for the targeted destination enveloped in a single set of parenthesis characters `(...)`,

- Thirdly, add the title and the target to the ensemble

## Live

How to [temporarily disable liquid tag processing](https://shopify.github.io/liquid/tags/raw/){:title="Click to Visit the Raw page at Shopify"}{:target="_blank"} in **Markdown**.

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Blank Author [[1](#BLANKAUTHOR){:.red}].

1. {:#BLANKAUTHOR}[A Narrative of Psychology by Blank Author, Jan #1999](http://cowles.yale.edu/sites/default/files/files/pub/d20/d2069.pdf){:target="_blank"}

***

{% include patreon-link.md %}
