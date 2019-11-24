---
title: Terminal Markdown
layout: default
excerpt: Markdown is a set of common rules that allow the enduser to easily write readable and formatted digitally text quickly ...
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

### How To Learn Markdown From The Terminal

"Knowledge of Markdown is an important skill for modern developers.~ [@wangding](https://www.github.com/wangding){:target="_blank"}

## Installation

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

### Set the session Ruby

```liquid
{% raw %}
rvm use 2.4.1
{% endraw %}
```

### Utilize npm

Use npm ( Node Package Manager ) to install the program, as follows:

```liquid
{% raw %}
npm install -g how-to-markdown
{% endraw %}
```

**Note**. Be sure to use the global `-g` switch when installing ie.) `npm i -g how-to-markdown`

### Confirm installation where

```liquid
{% raw %}
which how-to-markdown
{% endraw %}
```

Returns ...

```liquid
{% raw %}
/usr/local/bin/how-to-markdown
{% endraw %}
```

### Confirm version

```liquid
{% raw %}
how-to-markdown --version
{% endraw %}
```

Returns ...

```liquid
{% raw %}
how-to-markdown@1.5.2
{% endraw %}
```

## Execute the Program

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

```liquid
{% raw %}
how-to-markdown
{% endraw %}
```

Returns ...

```liquid
{% raw %}
Markdown is awesome!
   ─────────────────────────────────────────────────────────────────────────
   » HELLO WORLD
   » HEADINGS
   » EMPHASIS
   » LISTS
   » LINKS
   » IMAGES
   » BLOCKQUOTES
   » CODE
   » TABLES
   » HORIZONTAL RULES
   » HTML
   » GFM
   ─────────────────────────────────────────────────────────────────────────
   HELP
   CHOOSE LANGUAGE
   CREDITS
   CHECK FOR UPDATE
   EXIT
{% endraw %}
```

## Ping-backs

If you have enjoyed the usage of the program, please drop the creators a line.

Tell them their program is the greatest thing since "sliced bread", or something like that.

### Pre-text Template

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

From the base Terminal prompt ( your-machine-name:~ your-root-directory$ ) ...

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Aaron Swartz [[1](#AARONSWARTZ){:.red}] and John Gruber [[2](#JOHNGRUBER){:.red}].

1. {:#AARONSWARTZ}[Aaron Swartz, original Markdown creator, 2004](https://www.aaronsw.com/){:title="Click to Visit Aaron Sw dot com"}{:target="_blank"} Original Co-Creator of Markdown.

1. {:#JOHNGRUBER}[John Gruber, original Markdown creator, #2004](https://daringfireball.net/){:title="Click to Visit Daring Fireball dot net"}{:target="_blank"} Original Co-Creator of Markdown.

1. {:#WANGDING}[GitHub Username: @wangding](https://www.github.com/wangding){:title="Click to Visit the Git Hub profile of wang ding"}{:target="_blank"} Original Creator of How-To-Markdown.

***

{% include patreon-link.md %}
