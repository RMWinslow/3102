---
title: Plan for site structure.
has_children: true
description: A plan for what the site looks like in terms of sidebar organization.
nav_exclude: true
---

# Site plan

## Goal

- High-quality
- concise
- intuitive
- examplanations of macro concepts.

I want a resource that can be used as the basis for my lecture plans, while also being useful for grad intro macro.
Start with the undergrad version, and then only do the grad notes after proof of concept.

Take advantage of html as a portable notes format with better navigability than pdf.


## Page formatting tricks.
Use detail-summary boxes like this one at the top of a page for a table of contents

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

    <details open markdown="block">
    <summary>
        Table of contents
    </summary>
    {: .text-delta }
    1. TOC
    {:toc}
    </details>

And use more general details boxes like this one for hiding algebric details and the like:

<details open markdown="block">
  <summary>
    The title of the section goes here. Something like "Click to see the algebra"
  </summary>
Type the contents of the box in markdown format here.
Make sure not to indent this section, or Kramdown will interpret it as code.
</details>

Footnotes can be done using kramdowns footnote syntax

This is a text with a
footnote[^1].

[^1]: And here is the definition.

    This is a text with a
    footnote[^1].

    [^1]: And here is the definition.

And sidenotes can be done using the aside tag.

<aside markdown="block">
Again, remembder to not indent this section.
Or Kramdown will treat it as code.
</aside>


Topics have a super concise summary page.

Maybe: Have a button that expands details and summary elemenst?
Maybe start discussion of each model


<aside markdown="block">
If printed, it would be nice for a topic to fit on one page.
Some testing reveals that 
- 12pt MSWord can fit 
    - and with 2-column
- default JtD print settings 
- lyx can fit 
</aside>



## Navigation Structure



### Top level Titles




### Bulletted page todo list

- [ ] Top level 1
