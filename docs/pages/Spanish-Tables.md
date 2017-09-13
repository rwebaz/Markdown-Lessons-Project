---
title: Spanish Tables
layout: default
navigation_weight: 8
---
# Spanish Tables

How to form a table using Kramdown in Markdown.

{% include toc-flammarion.md %}

## Source Code

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

{% include sources-and-uses.md %}

**Note**. Unordered Lists (ul) should be surrounded by blank lines in GitHub Flavored Markdown (GFM), except in those instances where a Kramdown command is subsequently evoked on the very next line, as follows:

### External Sources

- The [Project Source Links](https://mminail.github.io/Markdown/Source-Markdown-Links.htm){:title="Click to Visit the Source Links page of the Markdown Lessons Project at GitHub pages"}{:target="_blank"} page of the Markdown Lessons Project. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.
