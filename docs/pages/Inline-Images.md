---
title: Inline Images
layout: default
navigation_weight: 9
---
# Inline Images

Place the introducing line of text ie.) the 'tagline' here ...

## Table O Contents

- TOC
{:toc}

## Enabling Image URLs

When enabling Image URLs using GitHub Flavored Markdown (.md) ...

Simply place a "bracket" symbol in front of ( and, at the end of ) the 'Alt text' part of your Image URL.

Then, encircle the URL with "parenthesis", as follows:

### The Code N

```liquid
{% raw %}
[8 x 4 Solar Panel Array With Dual Axis Tracking](../assets/img/Canna-Solar-32-Panel-Array-8-x-4-w-dual-axis-tracking-640-x-480-px.png)
{% endraw %}
```

**Note**. Be sure to to place the 'images' subdirectory that holds the actual image file (.png) under the same subdirectory that houses your document file (.md) ie.) pages

Finally, to enable the fetching and rendering of your subject image, place an exclamation point '!' at the beginning of your image statement, as follows:

### The Code O

```liquid
{% raw %}
![8 x 4 Solar Panel Array With Dual Axis Tracking](../assets/img/Canna-Solar-32-Panel-Array-8-x-4-w-dual-axis-tracking-640-x-480-px.png)
{% endraw %}
```

## Subtitle

More to come ...

***

## Raw Code

```liquid
{% raw %}
`...`
{% endraw %}
```

***

**Source**: [Instructional Jekyll Tips n Vids by Cloud Cannon](https://learn.cloudcannon.com/){:target="_blank"}. Published by © 2017 [Cloudcannon.com](https://www.cloudcannon.com){:target="_blank"}.