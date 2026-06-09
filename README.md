# recipes.willjackson.uk

A simple Astro recipe blog for **Approved by Georgie**: a personal collection of tested, mostly approved recipes.

## Tech stack

* Astro
* MDX
* TypeScript
* CSS

## Getting started

```bash
npm install
npm run dev
```

Build for production:

```bash
npm run build
```

## Recipes

Recipe files live in:

```text
src/content/recipes/
```

Each recipe is written in MDX and uses frontmatter:

```yaml
---
title: Recipe Title
pubDate: 'YYYY-MM-DD'
tags: ['tag1', 'tag2']
draft: false
description: A short description of the recipe.
---
```

Set `draft: true` to hide a recipe from the live site.

## Project structure

```text
public/              Static assets
src/content/recipes/ Recipe MDX files
src/layouts/         Page and recipe layouts
src/pages/           Site routes
src/styles/          Global styles
```

## Credit

Based on the Astro Starter Kit: Blog.
