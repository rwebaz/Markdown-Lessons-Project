---
title: Spanish Tables
layout: default
navigation_weight: 9
---
# Spanish ( Kramdown ) Tables

## Navigating This Page ( Internal Anchor Links )

- TOC
{:toc}

**Note**. Unordered Lists (ul) should be surrounded by blank lines in GitHub Flavored Markdown (GFM), except in those instances where a Kramdown command is subsequently evoked on the very next line, as follows:

### Table O Contents

```liquid
{% raw %}
- TOC
{:toc}
{% endraw %}
```

## Table (Mesa) O Fruits (de Frutas)

|---------+---------+---------|
|English - Fruits|Photo|Spanish - Frutas|
|---------|:---------:|---------:|
Blackberries|![Zarzamoras](../assets/img/raspberry-frambuesa-32-x-32.png)|Zarzamoras|
Raspberries|![Frambuesas](../assets/img/raspberry-frambuesa-32-x-32.png)|Frambuesas|

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

**Source**: npm install -g how-to-markdown

***

## Table (Mesa) O Vegetables (de Verdaduras)

|---------+---------+---------|
|English - Vegetables|Photo|Spanish - Verdaduras|
|---------|---------|---------|
Asparagus|![Page Banner](../assets/img/raspberry-frambuesa-32-x-32.png)|Espárragos|
Raspberries|![Page Banner](../assets/img/raspberry-frambuesa-32-x-32.png)|Frambuesas|

***

## Table (Mesa) O Meats (de Carnes)

English - Meats|Photo|Spanish - Carnes|
---------|---------|---------|
Chicken Breasts|![Page Banner](../assets/img/raspberry-frambuesa-32-x-32.png)|Pechugas de Pollo|
sin Hueso|![Page Banner](../assets/img/raspberry-frambuesa-32-x-32.png)|without Bone|

***

## Table (Mesa) O Hybrid Include #1

{% include include-a-table.htm %}

***

## Table (Mesa) O Hybrid Include #2

{% include get-data.htm %}

***

## Table (Mesa) O Hybrid Include #3

{% include ping-back.htm %}

***

**Source**: [Instructional Jekyll Tips n Vids by Cloud Cannon](https://learn.cloudcannon.com/){:target="_blank"}