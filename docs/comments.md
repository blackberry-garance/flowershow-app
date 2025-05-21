---
title: Page comments
description: Enable comments on yout site's pages. Powered by Giscus and GitHub Discussions.
---

## Requirements

1. GitHub Discussions enabled in your repository
2. [Giscus](https://github.com/apps/giscus) GitHub App installed on your repository
3. Repository ID and Category ID from giscus.app

## Getting Configuration IDs

Visit [giscus.app](https://giscus.app):
1. Enter your repository name
2. Select your preferred discussion category
3. Find the Repository ID (R_...) and Category ID (DIC_...) in the configuration section

## Configuration

In your site's dashboard settings:
1. Navigate to the Comments section
2. Toggle comments on
3. Enter your Repository ID and Category ID

For a detailed guide including examples and step-by-step instructions, check out our [[how-to-enable-page-comments|this blog post]].

## Default Behavior and Customization

By default, comments will be enabled on all pages once you've configured comments in your site settings. You have two ways to customize this behavior:

### Hiding Comments on Specific Pages

To hide comments on specific pages, add `showComments: false` to the page's frontmatter:

```yaml
---
title: My Page
showComments: false
---
```

### Granular Control Across Your Site

If you prefer to enable comments only on specific pages, you can:

1. Set `showComments: false` in your site's `config.json` to disable comments site-wide
2. Enable comments on specific pages by setting `showComments: true` in their frontmatter:

```yaml
---
title: My Page
showComments: true
---
```