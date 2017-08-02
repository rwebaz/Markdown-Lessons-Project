---
title: E Books
layout: default
navigation_weight: 9
---
# Article Title ( From Front Matter Above )

Place the introducing line of text ie.) the 'tagline' here ...

## Table O Contents

- TOC
{:toc}

## Subtitle

More to come ...

***

**Source**: [Instructional Jekyll Tips n Vids by Cloud Cannon](https://learn.cloudcannon.com/){:target="_blank"}

***

## Navigating This Page ( Internal Anchor Links )

Also embed the introducing line of text ie.) the 'tagline' in the referring hyperlink that originates in the working repo nav, as follows:

### The Referring Hyperlink Code

```liquid
{% raw %}
<li><a href="https://rwebaz.github.io/Governance-Lessons-Project/pages/Stress-Uncertainty.html" title="Click to Visit the Stress Uncertainty Page at GitHub" target="_blank">Stress Uncertainty</a>: A deficiency of Brain Derived Neurotrophic Factors caused by the stresses of early childhood indirectly damages the adult prefrontal cortex, the hippocampus, as well as the adult hypothalamic adrenal system that is stimulated and regulated by the pituitary gland.</li>
{% endraw %}
```

**Note**. Unordered Lists (ul) should be surrounded by blank lines in GitHub Flavored Markdown (GFM), except in those instances where a Kramdown command is subsequently evoked on the very next line, as follows:

### Table O Contents Code

```liquid
{% raw %}
- TOC
{:toc}
{% endraw %}
```

## How To Include An 'include'

{% include firefox.htm %}

***

## Navigating This Page ( Internal Anchor Links )

Also embed the introducing line of text ie.) the 'tagline' in the referring hyperlink that originates in the working repo nav, as follows:

### The Referring Hyperlink Code

```liquid
{% raw %}
<li><a href="https://rwebaz.github.io/Governance-Lessons-Project/pages/Stress-Uncertainty.html" title="Click to Visit the Stress Uncertainty Page at GitHub" target="_blank">Stress Uncertainty</a>: A deficiency of Brain Derived Neurotrophic Factors caused by the stresses of early childhood indirectly damages the adult prefrontal cortex, the hippocampus, as well as the adult hypothalamic adrenal system that is stimulated and regulated by the pituitary gland.</li>
{% endraw %}
```

**Note**. Unordered Lists (ul) should be surrounded by blank lines in GitHub Flavored Markdown (GFM), except in those instances where a Kramdown command is subsequently evoked on the very next line, as follows:

### Table O Contents Code

```liquid
{% raw %}
- TOC
{:toc}
{% endraw %}
```

## How To Include An 'include'

{% include firefox.htm %}