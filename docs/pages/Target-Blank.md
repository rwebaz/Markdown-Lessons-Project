---
title: Target Blank
layout: default
navigation_weight: 9
---
# Issue: Target Blank

## How To Force a New Target Blank When Clicking A GFM Hyperlink

## Solution

To route an external link to a new tabbed page within your browser ...

From your GitHub Flavored Markdown, or **GFM** `(.md)` page ...

Append your `(.md)` external link with the `{:target="_blank"}` kramdown statement, as follows:

## The Code

```liquid
{% raw %}
[temporarily disable liquid tag processing](https://shopify.github.io/liquid/tags/raw/){:target="_blank"}
{% endraw %}
```

## Summation

The components of a successful external link in markdown are, as follows:

- First, clickable text enveloped in a single set of bracket characters `[...]`
- Followed by, the complete URI for the targeted destination enveloped in a single set of parenthesis characters `(...)`, and
- Thirdly, the given kramdown statement

## Live

[temporarily disable liquid tag processing](https://shopify.github.io/liquid/tags/raw/){:target="_blank"}