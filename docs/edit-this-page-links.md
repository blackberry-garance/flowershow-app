---
title: '"Edit this page" links'
description: Display an “Edit this page” link at the bottom of each page that takes users directly to the file in your GitHub repo, ready for editing.
---

## Requirements

1. Public GitHub repository containing your content
2. `editLinkRoot` configured in your `config.mjs` file

## Configuration

### Setting up the Edit Link Root

In your `config.mjs` file, set the `editLinkRoot` to point to your repository's edit URL:

```js
{
  editLinkRoot: "https://github.com/flowershow/flowershow/edit/main/site/content"; //example
}
```

## Default Behavior and Customization

By default, the "Edit this page" button is disabled on all pages. You have two ways to customize this behavior:

### Enabling Site-wide

To enable the button on all pages, set `showEditLink: true` in your `config.mjs` file:

```js
{
  showEditLink: true
}
```

### Per-page Control

You can override the default setting on specific pages by adding `showEditLink` to the page's frontmatter:

```yaml
---
title: My Page
showEditLink: true  # Enable on this page
---
```

Or to hide the button on a specific page when it's enabled site-wide:

```yaml
---
title: My Page
showEditLink: false  # Disable on this page
---
```

For a detailed guide including examples and step-by-step instructions, check out our [[how-to-add-edit-this-page-button|this blog post]].