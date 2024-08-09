---
title: 'Styling in Astro'
pubDate: 2024-08-19
description: 'Learn how to style your Astro components using CSS and other styling techniques.'
author: 'Pieter Deane'
image:
    url: 'https://docs.astro.build/assets/styling.webp'
    alt: 'Styling in Astro illustration.'
tags: ["astro", "styling", "CSS"]
---

# Styling in Astro

*Published on: 2024-08-19*

In this post, we'll explore different ways to style your Astro components. Styling is an essential part of web development, and Astro provides several options to make your components look great.

## Using CSS

The simplest way to style your components is by using CSS. You can include CSS directly in your `.astro` files:

```astro
---
const message = "Styled with CSS!";
---
<style>
  .message {
    color: blue;
    font-size: 1.5em;
  }
</style>
<div class="message">
  <h1>{message}</h1>
</div>