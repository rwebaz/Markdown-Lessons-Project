---
title: Markdown Tips
layout: default
navigation_weight: 9
---
# Markdown Tips

A bunch of Markdown - Kramdown - Liquid Short Lessons.

## GFG

GFM is an acronym for "Git Hub Flavor'd Markdown"

**Rule**. All markdown pages carry the suffix (.md)

***

## Creating Headers

When creating headers using GitHub Flavored Markdown (.md) ...

>Simply place one `#` = `<h1>`, two `##` = `<h2>`, or three `###` = `<h3>` sharp symbols in front of the text you wish to emphasize.

***

## Emphasizing Text

>When **emphasizing** text using GitHub Flavored Markdown (.md) ...

>Simply place two (**) asterisk symbols in front of, and in back of the text you wish to **emphasize**.

***

## Liquid Link Tags

The liquid `link` tag may be pre-pended by a **Liquid Variable Statement** commonly known as a *moustache*, as follows:

### The Code A

**Note**. The following three ellipsis inside the **Liquid Variable Statement** are shown as merely placeholders.

```liquid
{% raw %}
{{...}}
{% endraw %}
```

### The Code B

**Note**. Inside the pre-pending *moustache* or **Liquid Variable Statement**, the object `site` may be placed with a reference to the `site baseurl` property via dot notation, as follows:

```liquid
{% raw %}
{{ site.baseurl }}
{% endraw %}
```

### The Code C

**Note**. The `site baseurl` may be fixed by the user at the underscore config dot yml file, as follows:

```liquid
{% raw %}
baseurl: "/Liquid-Lessons-Project"
{% endraw %}
```

## The Link Tag

Next, the `link` tag is built within a separate liquid statement adjacent to and appending the liquid variable statement, as follows:

### The Code D

```liquid
{% raw %}
{% link pages/Target-Blank.md %}
{% endraw %}
```

Here, the `link` tag followed by a space points to the `pages` Subdirectory where the **GFM** file is housed.

Notice the extension, in this case `(.md)` must be included when declaring a liquid `link` tag.

Putting the two liquid statements together "live" we have the following "live" rendition complete with clickable text `[...]` pre-pending all ...

### The Code E

```liquid
{% raw %}
[Target Blank]{{ site.baseurl }}{% link pages/Target-Blank.md %}
{% endraw %}
```

### Live E

[Target Blank]{{ site.baseurl }}{% link pages/Target-Blank.md %}

***

## Inline Anchor Links

Inline anchor links that point internally to other pages within the repo require a separate bracketed `[page.name]` followed by a relative `/page.url` prepended by the `site.github.url` enveloped in a *moustache* or **Liquid Variable Statement** `{\{...}\}`, and enclosed in a single set of parenthesis `(...)`, as follows:

### The Code F

```liquid
{% raw %}
[Home Page]({{ site.github.url }}/index)
{% endraw %}
```

### Live F

**Por ejemplo en vivo**. Just typing along and here comes an inline anchor link! ... Click! ... [Home Page]({{ site.github.url }}/index).

**Note**. To effect an inline anchor link while served relatively at the remote GitHub-Jekyll web server farm, prepend the `/page.url` with the `site.github.url`, as follows:

### The Code G

```liquid
{% raw %}
[Target Blank]({{ site.github.url }}/pages/Target-Blank)
{% endraw %}
```

### Live G

**Por ejemplo en vivo**. Another inline anchor link ... [Target Blank]({{ site.github.url }}/pages/Target-Blank).

***

## Stand Alone External Hyperlinks

The sections of a **Stand Alone External Hyperlink** are, as follows:

1. Prepended and bracketed clickable text `[MMINAIL]`,

1. Followed by the url of the external website enclosed in a single set of parenthesis `(https://mminail.github.io)`,

1. Appended by a liquid target indicator `{:target="_blank"}`.

### Live Example: Stand Alone External Hyperlink

**Por ejemplo en vivo**. A stand alone, clickable text, external hyperlink with target indicator blank ... [MMINAIL](https://mminail.github.io){:target="_blank"}.

### The Code: Stand Alone External Hyperlink

```liquid
{% raw %}
[MMINAIL](https://mminail.github.io){:target="_blank"}
{% endraw %}
```

## Auto External Hyperlinks

Stand alone "auto" URLs that point to external targets may be enclosed in angle brackets `<...>` and optionally prepended by a bracketed `[external.site.name]`, as follows:

### The Code I

```liquid
{% raw %}
[MMINAIL] <https://mminail.github.io>
{% endraw %}
```

### Live I

**Por ejemplo en vivo**. A list item hyperlink ...

- [MMINAIL] <https://mminail.github.io>

**Note**. All external "auto" URLs must start with `https`.

***

## Enabling Hyperlinks

>When enabling hyperlinks using GitHub Flavored Markdown (.md) ...

>Simply place a "bracket" symbol \[ label part ] in front of ( and, at the end of ) the label part of your hyperlink.

>Then, encircle the URL with "parenthesis", \( URL ) as follows:

## Example

### The Code L

```liquid
{% raw %}
Copyright ©2016 [The Medical Marijuana Initiative of North America - International Limited](https://cannabuds.us/). All rights reserved.
{% endraw %}
```

### Live L

**Por ejemplo en vivo**. Copyright ©2016 [The Medical Marijuana Initiative of North America - International Limited](https://cannabuds.us/). All rights reserved.

### The Code M

```liquid
{% raw %}
This Webpage is being hosted via [GitHub Pages](https://pages.github.com/).
{% endraw %}
```

### Live M

**Por ejemplo en vivo**. This Webpage is being hosted via [GitHub Pages](https://pages.github.com/).

***

## Stand Alone URLs

When enabling **Stand Alone URLs** using GitHub Flavored Markdown (.md) ...

Simply type the URL as a Stand Alone URL, as follows:

C=> https://medmj.us/SolarPowerYes

The Git Hub Markdown interpreter will automatically recognize a properly typed URL.

***

## Anchor Links w Site Base URL Using the Optional liquid link tag

Internal anchor links may be served locally or remotely using the optional liquid link tag.

Here, the bracketed clickable text `[Target Blank]` is followed by a single set of parenthesis `(...)`.

Inside the single set of parenthesis `(...)` is a double set of braces ie.) a *moustache* statement that references a liquid variable, as follows:

### The Code P

**Note**. The following three ellipsis inside the **Liquid Variable Statement** are shown as merely placeholders.

```liquid
{% raw %}
({{...}})
{% endraw %}
```

In this case ... the site base URL `site.baseurl` followed by another liquid `{\%...\%}` statement that houses the liquid `link` keyword plus a `space` followed by the relative `page` URL of the targeted page `pages/Target-Blank.md`.

Using a Triple-backtick highlighted code block with a language qualifier of liquid to illustrate ... all together now!

### The Code Q

```liquid
{% raw %}
[Target Blank]({{ site.baseurl }}{% link pages/Target-Blank.md %})
{% endraw %}
```

### Live Q

**Por ejemplo en vivo**. [Target Blank]({{ site.baseurl }}{% link pages/Target-Blank.md %})

***

## Single Backticks

**Rule**. A single set of Back-ticks \`  ` in GitHub Flavored Markdown, or **GFM** will create an inline code block, as follows:

### The Code R

```liquid
{% raw %}
`...`
{% endraw %}
```

### Live R

**Por ejemplo en vivo**. For example, the Visual Studio Code, or **VSC** default colors for a code block may be shown as rendered `<li>`, or line items in an unordered list, as follows:

- `gold colored text`

- `dark grey background`

**Note**. The way to render a `<li>` in a `(.md)` page is to use a hyphen symbol `-` as follows:

### The Code S

```liquid
{% raw %}
- `gold colored text`

- `dark grey background`
{% endraw %}
```

**Note**. Remember to append a language qualifier to the first set of Triple-backticks when rendering a highlighted code block in **GFM**.

Also, be sure to leave a blank line after the second set of Triple-backticks, as well.

## Triple Backticks

**Rule**. A double set of triple Back-ticks  in **GFM** will create an multi-line, or "Fenced" highlighted code block, as follows:

### The Code T

```liquid
{% raw %}
The code goes inside the fence ...
{% endraw %}
```

**Note**. Always remember to place a language qualifier after the first set of triple Back-ticks when highlighting a multi-line block of code in **GFM**.

Por ejemplo ( for example ), here is a block of `html` that has a double set of triple Back-ticks.

One set of triple Back-ticks is placed above the start of the highlighted code block, and one set of triple Back-ticks is placed below the highlighted code block.

Remember, similar to the **GFM** requirement that a blank line follow a Subtitle, the immediately 'below' set of triple Back-ticks requires a blank line following it, as well.

***

## Subtitles

Subtitles without an "auto" unstyled hard return below may be invoked in a `(.md)` page with a set of double hash `##` placed at the beginning of any line thus yielding the traditional Html `<h2>Title</h2>` header tag.

**Note**. A blank line following a Subtitle is required in **GFM**, or a declared unstyled hard return may be used, as well ( followed by the required blank line! )

## Snippet Insertion In Visual Studio Code

To insert a code snippet in Visual Studio Code, or **VSC** simply select and copy a batch of plain text to the clip board and open up the Command Palette in **VSC**, as follows:

```html
Shortcut to the Command Palette in **VSC**
```

Next, type `Insert Snippet`.

## Support for Emoji in VSC

Support for emoji in Visual Studio Code, or **VSC** when working on a `(.md)` page does not exist at this time ( May '17).

`@rwebaz:+1:`

Solution. Go to GitHub comments to render Emoji

Format ...

:musical_note:

## Italic Text

Text that you wish to be italicized go between ... *single asterisk*

## Bold Text

Text that you wish to look emboldened such as a **Note**. Prefix ... Go between a set of double asterisks `**`...`**`, as follows:

## Double Asterisks

## Inline Images

Inline images may be displayed using the exclamation point `!` followed by a bracketed `[Alt Text]` followed by a relative `URL` enclosed in a single set of parenthesis `(...)`, as follows:

![Logo Badge](../assets/ico/ms-icon-70x70.png)

## Referenced Images

Referenced images may be displayed using the exclamation point `!` followed by a bracketed `[Alt Text]` followed by a bracketed index number `[2]`, as follows:

![ePub Badge][2]

The bracketed index number represents a citation below embedded in the `nofooter` of this example.

The citation is the bracketed index number `[2]` followed by a colon `:` followed by the raw `URL` followed by the title to the photo.

Note. The title to the photo is enveloped in a set of double `"..."` quotes.

When the mouse is hovered over the photo the title given will appear.

**Warning**. The Reference-style method for serving links and images will not work on duplicate index numbers attempting to render multiple objects on the same page.

Therefore, always use a separate index number for each set of Reference-style links or images.

As above in the *Reference Style Hyperlink* section, the citation actually sits below this paragraph of text, hidden in the `nofooter` of this example.

[2]:
https://mminail.github.io/images/png/dot-epub-button-62-x-20.png
"The Official Logo Badge of ePub"

## Blockquote

A blockquote may be started with a single right angle bracket `>`, or greater than `&gt;` symbol &gt; :

>This is a blockquote with an Reference-style image below:

![CFFP Logo Banner][3]

As above in the *Reference Style Hyperlink* section, the citation actually sits below this paragraph of text, hidden in the `nofooter` of this example.

[2]:
https://rwebaz.github.io/carbon-free-footprint-project/docs/assets/img/svg/ghp-git-hub-pages-medmjorg-carbon-free-footprint-project-flammarion-got-tree-final-banner-1200-x-230.svg
"The Official CFFP Logo Banner"

## Unstyled Hard Returns

The Unstyled Hard Return counterpart in Html `<hr />` may be reproduced in a `(.md)` page using triple asterisks `***`, as follows:

***

But, not above or below Subtitles.

**Note**. By default, the single hash `#` placed at the beginning of a line in a `(.md)` page yields the traditional Html `<h1>Title</h1>` header tag with an automatically generated unstyled hard return placed below.

## Cross Out Text

How do you cross-out text in a `(.md)` page?

Simple ... Prepend ie.) place at the beginning and Append ie.) place at the end, a double set of enveloping tildes `~~...~~~` that surround the targeted text, as follows:

~~Cross Dis Sh't~~ ... out!

## Listing Image Assets

Listing the various image assets of your repo require a liquid tag statement placed within a `(.htm)` page, as follows:

```liquid
{% raw %}
{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}
{% endraw %}
```

**Note**. Remember to place a language qualifier `liquid` after the first set of triple backticks when highlighting a multi-line block of code in a `(.md)` page.

***

## Block Text

```liquid
{% raw %}
First Line of Text
>As you can see in the following live rendition, the usage of the "greater than" symbol `>` in this case yields an indented 2nd line of text with a corresponding "thick pipe" drawn preceding Line Number Two.
{% endraw %}
```

## More To Come

As more snippets are generated or found, expect this list to grow.

***

**Source**: [Instructional Jekyll Tips n Vids by Cloud Cannon](https://learn.cloudcannon.com/){:target="_blank"}
