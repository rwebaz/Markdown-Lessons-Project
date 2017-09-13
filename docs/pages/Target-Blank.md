---
title: Target Blank
layout: default
navigation_weight: 8
---
# Target Blank

How To Force a New Target Blank When Clicking A **GFM** Hyperlink.

{% include toc-flammarion.md %}

## Solution

More to come ...

## The Code

More to come ...

### Break It Down

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

{% include sources-and-uses.md %}

### External Sources

- The [Project Source Links](https://mminail.github.io/Markdown/Source-Markdown-Links.htm){:title="Click to Visit the Source Links page of the Markdown Lessons Project at GitHub pages"}{:target="_blank"} page of the Markdown Lessons Project. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.