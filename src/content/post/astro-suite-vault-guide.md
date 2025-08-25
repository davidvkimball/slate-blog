---
title: Astro Suite Vault Guide
description: Explanation of the Astro Suite Obsidian vault.
tags:
  - Meta
pubDate: 2025-08-23
draft: true
---
## Overview

All plugins, key bindings, and the theme can be customized to your liking, but this is what's on by default. Optimized for use with [Slate Astro theme](https://github.com/SlateDesign/slate-blog).

## Philosophy 

1. Plug-and-play Astro blogging experience.
2. Maintain vanilla Obsidian look and feel.
3. Emphasis on clarity and flexibility. 

## Plugins 

Disabled default core plugins: 
- Backlinks
- Canvas
- Daily notes
- Graph view
- Note composer
- Outgoing links
- Page preview
- Templates
- Sync

Community plugins enabled: 
- Astro Composer
- Custom save
- Default New Tab Page
- Homepage
- Image Inserter
- Paste image rename

### Astro Composer 

Handy for easily creating new notes as Astro blog posts. Just create a new note with `CTRL + N`, type in a title in Title case or with special characters, and the note or folder name generated is a kebab-case version of the title without special characters. This is ideal for automating post slugs. 

You can also define and set default properties that can be generated automatically or manually set for any open note as well.

Once you've used Wikilinks or markdown links, you can also convert those automatically to internal links for Astro with the "Convert internal links for Astro" command. 

### Custom save

This defines a set of commands to fire once `CTRL + S` is initiated. For convenience, both "Convert internal links for Astro" and "Standardize properties" commands from the Astro Composer plugin are included. You can add or remove any if you'd like - this is designed for posts to be "publish-ready" when manually saved.

### Homepage and Default New Tab Page

Both of these work together so you're default screen is a `.base` file that's a directory of all of your blog posts, listed in reverse-chronological order. You're able to customize the note properties in the views to your liking. 

### Paste Image Rename 

Quickly drag and drop image files or paste directly from your clipboard and give them kebab-case, SEO-friendly names. 

### BRAT (Temporary)

Only used temporarily to load Astro Composer and Disable Tabs plugins before they're available in the Obsidian plugin directory. Future versions will remove BRAT in favor of the official releases.