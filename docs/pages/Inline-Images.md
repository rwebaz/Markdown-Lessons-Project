---
title: Inline Images
layout: default
navigation_weight: 9
---
# Inline Images In Markdown

**Inline Images** may be displayed in markdown using the exclamation point `!` followed by a bracketed `[Alt Text]` followed by a relative `URL` enclosed in a single set of parenthesis `(...)`.

![MMI™ Flammarion Logo Badge](../assets/ico/ms-icon-70x70.png)

## Table O Contents

- TOC
{:toc}

## Enabling Image URLs

When enabling Image URLs using GitHub Flavored Markdown (.md) ...

> Simply place a "bracket" symbol in front of and at the end of the 'Alt text' part of your Image URL, as follows:

```liquid
{% raw %}
[MMI™ Flammarion Logo Badge]
{% endraw %}
```

> Next, append and encircle the URL with "parenthesis" ...

```liquid
{% raw %}
[MMI™ Flammarion Logo Badge](../assets/ico/ms-icon-70x70.png)
{% endraw %}
```

**Note**. Be sure to to place the 'images' subdirectory that holds the actual image file (.png) under the docs folder.

***

**Tip**. The docs folder also houses your (.md) document files via the subdirectory named 'pages'.

> Finally, to enable the fetching and rendering of your subject image, place an exclamation point '!' at the beginning of your image statement, as follows:

```liquid
{% raw %}
![MMI™ Flammarion Logo Badge](../assets/ico/ms-icon-70x70.png)
{% endraw %}
```

## Live Example

Inline images may be displayed using the exclamation point `!` followed by a bracketed `[Alt Text]` followed by a relative `URL` enclosed in a single set of parenthesis `(...)`, as follows:

![MMI™ Flammarion Logo Badge](../assets/ico/ms-icon-70x70.png)

## Raw Code

More to come ...

```liquid
{% raw %}
`...`
{% endraw %}
```

***

**Source**: [Instructional Jekyll Tips n Vids by Cloud Cannon](https://learn.cloudcannon.com/){:target="_blank"}. Published by © 2017 [Cloud Cannon dot com](https://www.cloudcannon.com/){:target="_blank"}.