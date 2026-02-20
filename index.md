---
layout: default
---

# Features

*   **Fast & Lightweight** No fancy stuff, only the essential to get the work done.
*   **Simple to adapt** Edit the config file, add the description in the index.md and a screenshot That's all!
*   **Elegant and minimal** Give your project the landing page it deserves!
*   **Open Source** Can simply be adapted to your specific needs.

# Usage

## In Github pages

Create a repo or a website folder in your project.

Add a `_config.yml` file with the following content

```yaml
title: "Complete each line"
subtitle: "with the relevant content"
description: "..."
header_image: 
download_url: 
download_text: 
footer_text: 
markdown: kramdown
plugins:
  - jekyll-remote-theme
remote_theme: username/kinapp-theme
```

Now all you need to add is an image presenting the project and an `index.md` file with the project description.

## On your server

Clone the repository, edit the `_config.yml` file and the `index.md`; add the header image in `assets/images` and build the site using `jekyll build`.

# Changelog

Version 1: Februrary 2026
 - First release
