---
title: Reference Hyperlinks
layout: default
navigation_weight: 9
---
# Reference Hyperlinks

Place the introducing line of text ie.) the 'tagline' here ...

## Table O Contents

- TOC
{:toc}

## Reference Style Hyperlinks In Markdown

More to come ...

### Reference Style Hyperlink, Stage One

The first stage of a **Reference Style Hyperlink** consists of ...

- An external url referenced from an inline bracketed clickable text ie.) `[MMINAIL]`,

- Followed by a bracketed index number ie.) `[1]`.

#### The Code: Reference Style Hyperlink, Stage One

```liquid
{% raw %}
The [MMINAIL][1] link in this paragraph ...
{% endraw %}
```

#### Live Example: Reference Style Hyperlink, Stage One

**Por ejemplo en vivo**. The [MMINAIL][1] link in this paragraph is anchored by a citation in the `nofooter` below.

### Reference Style Hyperlink, Stage Two

The citation below is comprised of the aforementioned bracketed index number `[1]` followed by a colon `:` followed by the url of the targeted destination.

#### Live Example: Reference Style Hyperlink, Stage Two

**Note**. The citation actually sits below this line of text, hidden in the `nofooter` of this live example.

##### nofooter

***

[1]:https://mminail.github.io

***

But, can now become manifest via a **Raw Code** liquid statement, as next illustrated ...

#### The Code: Reference Style Hyperlink, Stage Two

```liquid
{% raw %}
[1]:https://mminail.github.io
{% endraw %}
```

**Note**. No bare Urls allowed in Markdown

## Raw Code

```liquid
{% raw %}
`...`
{% endraw %}
```

***

**Source**: [Instructional Jekyll Tips n Vids by Cloud Cannon](https://learn.cloudcannon.com/){:target="_blank"}. Published by © 2017 [Cloudcannon.com](https://www.cloudcannon.com){:target="_blank"}.