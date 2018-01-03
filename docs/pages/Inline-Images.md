---
title: Inline Images
layout: default
navigation_weight: 8
---
# Inline Images

{{ site.tagline }}

{% include toc-flammarion.md %}

## Enabling Image URLs

In **Markdown** *Inline Images* may be displayed in using the exclamation point `!` followed by a bracketed `[Alt Text]` followed by a relative `URL` enclosed in a single set of parenthesis `(...)`, as follows:

```liquid
{% raw %}
![MMI™ Flammarion Logo Badge](../assets/img/png/MMI-Medmj-Org-Got-Tree-Flammarion-Person-Through-Celestial-Sphere-circle-100-x-100.png)
{% endraw %}
```

### Break It Down

Place a "bracket" symbol `[` in front of and at the end of `]` the **Alt Text** part of your **Image Url** when crafting Image Url using **GitHub Flavored Markdown**, as follows:

### Alt Text

Recall from **Html** how **Alt Text** is required just in case your image file does not render in the client browser window.

Especially for screen readers that do not rely on visual information, having an idea of what type of image you are attempting to render keeps the flow of information moving.

```liquid
{% raw %}
[MMI™ Flammarion Logo Badge]
{% endraw %}
```

Next, append and encircle the relative path to the image file with a single set of parenthesis as shown in the following code block ...

```liquid
{% raw %}
[MMI™ Flammarion Logo Badge](../assets/img/png/MMI-Medmj-Org-Got-Tree-Flammarion-Person-Through-Celestial-Sphere-circle-100-x-100.png)
{% endraw %}
```

### The Assets Subdirectory

The **Assets** sub-folder sits in the root of your docs folder.

Recall that all of your **Git Hub Pages** are served from the docs folder.

Specifically, from the pages subdirectory within the docs folder.

### The Assets Subfolder

The **Assets** sub-folder is further split into three more folders ...

1. **css**

1. **ico**, and

1. **img**

**Note**. The **css** folder holds the style sheet ( .scss ) for the repo, the **ico** folder holds images of less than 100 px in width, and the **img** folder holds image files of 100 px or more in width.

### The Exclamation Point

Finally, to enable the fetching and rendering of your subject image in **Markdown**, prepend the **Alt Text** of your image with an exclamation point `!` right before the first bracket `[` at the beginning of your image statement, as follows:

```liquid
{% raw %}
![MMI™ Flammarion Logo Badge](../assets/img/png/MMI-Medmj-Org-Got-Tree-Flammarion-Person-Through-Celestial-Sphere-circle-100-x-100.png)
{% endraw %}
```

## Going Live

### Da Rule

**Inline Images** may be displayed using the exclamation point `!` followed by a bracketed `[Alt Text]` followed by a relative pathway to the image file enclosed in a single set of parenthesis `(...)`.

### The Flammarion

![MMI™ Flammarion Logo Badge](../assets/img/png/MMI-Medmj-Org-Got-Tree-Flammarion-Person-Through-Celestial-Sphere-circle-100-x-100.png)

To activate a hyperlink to a new tab in your browser ...

- Append an appropriate title and target to a link, as follows:

```liquid
{% raw %}
[Project Source Links]
(https://mminail.github.io/Shell/Source-Shell-Links.htm)
{:title="Click to Visit the Source Links page of the Shell Lessons Project at GitHub pages"}{:target="_blank"}
{% endraw %}
```

Or,

To activate an hyperlink embedded in an image ...

- More to come

```liquid
{% raw %}
More to come ...
{% endraw %}
```
**Note**. Inline Images may be displayed in **Markdown** using the exclamation point `!` ...

- Followed by a bracketed `[Alt Text]` ... 

- Followed by a relative `URL` enclosed in a single set of parenthesis `(...)`.

- And, that includes SVG images, too!

### Dot ePub

When converting a **Kramdown** md file holding the suffix ( .html ), the ( .mobi ) engine **Dotepub** will return the message [Image in a non-supported format] even though clear as a bell your Chrome browser is rendering the ( .svg ) "No hay problema!"

#### Base Dimensions

Here, we are going to use an original `( .xcf )` file that has been exported from **GIMP** as a `( .psd )` of dimensions 725 px X 725 px X 96 dpi.

#### Import to AI

Next, the resultant `( .psd )` file is imported into **Adobe Illustrator**, or **AI** via simple 'File Open'.

Once inside **AI**, the `( .psd )` file is then "save as" an `( .svg )`.

Out comes a perfectly centered ... to the top horizontal and center vertical ... an `( .svg )` file of initial dimensions 543.75 px X 543.75 px, as follows:

```liquid
{% raw %}
![MMI™ Flammarion Logo Badge](../assets/img/svg/MMI-Medmj-Org-Got-Tree-Flammarion-Person-Through-Celestial-Sphere-circle-543-x-543.svg)
{% endraw %}
```

#### Responsive SVG

An **SVG** file can be both expandable and responsive.

To render a smaller version of the `( .svg )`, simply append an appropriate height and width, as follows:

```liquid
{% raw %}
{:height="120px" width="120px"}
{% endraw %}
```

#### Presentation Dimensions

The following **Live** rendition of the **MMI™ Flammarion Logo Badge** `( .svg )` image file is set to the dimensions of 500.00 px X 500.00 px, as shown in the following code block:

```liquid
{% raw %}
![MMI™ Flammarion Logo Badge](../assets/img/svg/MMI-Medmj-Org-Got-Tree-Flammarion-Person-Through-Celestial-Sphere-circle-543-x-543.svg){:height="500px" width="500px"}
{% endraw %}
```

##### Live Image: SVG In Markup

![MMI™ Flammarion Logo Badge](../assets/img/svg/MMI-Medmj-Org-Got-Tree-Flammarion-Person-Through-Celestial-Sphere-circle-543-x-543.svg){:height="500px" width="500px"}

{% include sources-and-uses.md %}

### External Sources

- The [Project Source Links](https://mminail.github.io/Markdown/Source-Markdown-Links.htm){:title="Click to Visit the Source Links page of the Markdown Lessons Project at GitHub pages"}{:target="_blank"} page of the Markdown Lessons Project. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

- [Instructional Jekyll Tips n Vids by Cloud Cannon](https://learn.cloudcannon.com/){:title="Click to Visit Instructional Jekyll Tips n Vids by Cloud Cannon"}{:target="_blank"}. Published by © 2017 [Cloudcannon.com](https://www.cloudcannon.com){:title="Click to Visit Cloud Cannon dot com"}{:target="_blank"}.

- [Inline Image Construction](https://rwebaz.github.io/Markdown-Lessons-Project/pages/Inline-Images.html){:title="Click to Visit the Inline Images Page at GitHub"}{:target="_blank"}. Inline images may be displayed in Markdown using the exclamation point `!` followed by a bracketed `[Alt Text]` followed by a relative `URL` enclosed in a single set of parenthesis `(...)`. Published by © 2017 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the current Home Page of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.
