---
title: Spanish Tables
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

### How to form a table using Kramdown in Markdown

More to come ...

#### Source Code

From the Terminal prompt or your user root directory of your development machine, type the following command:

```liquid
{% raw %}
npm install -g how-to-markdown
{% endraw %}
```

## Table (Mesa) O Fruits (de Frutas)

|---------+---------+---------|
|English - Fruits|Photo|Spanish - Frutas|
|---------|:---------:|---------:|
Blackberries|![Zarzamoras](../assets/img/png/raspberry-frambuesa-32-x-32.png)|Zarzamoras|
Raspberries|![Frambuesas](../assets/img/png/raspberry-frambuesa-32-x-32.png)|Frambuesas|

**Rule**. Columns by default are left-aligned `---------` in Kramdown tables.

Follow this series of three introducing table frames to understand the difference between the respective left-alignment, centered, and right-alignment Kramdown table columns.

### Left Align Your Columns

```liquid
{% raw %}
|---------+---------+---------|
|English - Fruits|Photo|Spanish - Frutas|
|---------|---------|---------|
{% endraw %}
```

As the rule states above, columns are left-aligned `---------` as designated by the introducing frame `|---------|---------|---------|` following the header row of the table by default in Kramdown tables.

However, to center a column in a Kramdown table, simply apply a set of colons `:---------:` to the introducing frame ( following the header row of the table ), as follows:

### Center Align Your Colons

```liquid
{% raw %}
|---------+---------+---------|
|English - Fruits|Photo|Spanish - Frutas|
|---------|:---------:|---------|
{% endraw %}
```

You may also right-align the far right column ( in a table of three (3) columns ) by adding a single colon `---------:` to the introducing frame, as well:

### Right Align Your Colon

```liquid
{% raw %}
|---------+---------+---------|
|English - Fruits|Photo|Spanish - Frutas|
|---------|:---------:|---------:|
{% endraw %}
```

## Table (Mesa) O Vegetables (de Verdaduras)

|---------+---------+---------|
|English - Vegetables|Photo|Spanish - Verdaduras|
|---------|---------|---------|
Asparagus|![Page Banner](../assets/img/png/raspberry-frambuesa-32-x-32.png)|Espárragos|
Raspberries|![Page Banner](../assets/img/png/raspberry-frambuesa-32-x-32.png)|Frambuesas|

## Table (Mesa) O Meats (de Carnes)

English - Meats|Photo|Spanish - Carnes|
---------|---------|---------|
Chicken Breasts|![Page Banner](../assets/img/png/raspberry-frambuesa-32-x-32.png)|Pechugas de Pollo|
sin Hueso|![Page Banner](../assets/img/png/raspberry-frambuesa-32-x-32.png)|without Bone|

## Table (Mesa) O Hybrid Include #1

{% include include-a-table.htm %}

## Table (Mesa) O Hybrid Include #2

{% include get-data.htm %}

## Table (Mesa) O Hybrid Include #3

{% include ping-back.htm %}

**Note**. Unordered Lists (ul) should be surrounded by blank lines in GitHub Flavored Markdown (GFM), except in those instances where a Kramdown command is subsequently evoked on the very next line, as follows:

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Blank Author [[1](#BLANKAUTHOR){:.red}].

1. {:#BLANKAUTHOR}[A Narrative of Psychology by Blank Author, Jan #1999](http://cowles.yale.edu/sites/default/files/files/pub/d20/d2069.pdf){:target="_blank"}

***

{% include patreon-link.md %}
