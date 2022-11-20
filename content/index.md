---
title: 'Title of the page'
description: 'meta description of the page'
---

<!-- Content of the page -->
# Hello Content

::the-title
A [rich text](/) will be **rendered** by the component.
::

::card
The content of the card
::

::hero 
 Default slot text
#description
 This will be rendered inside the `description` slot.
::

::hero
  :::card
    A nested card
    ::card
      A super nested card
    ::
  :::
::

# Title
:banner

::alert{type="warning"}
The **alert** component.
::

::icon-card
---
icon: IconNuxt
description: Harness the full power of Nuxt and the Nuxt ecosystem.
title: Nuxt Architecture.
---
::

Hello [World]{.bg-blue-500}!

Hello [World]{.text-primary-500}!

Attributes works on:
- ![](/icon.png){.inline.w-5.h-5.bg-primary-500} image,
- [link](#attributes){.bg-primary-400}, `code`{.text-red-500},
- _italic_{.bg-primary-500} and **bold**{.bg-primary-500} texts.

