---
title: Page authors
description: Create dedicated profile pages for authors of your content and list them in page headers
---

The `authors` field in page frontmatter can be enhanced by creating regular markdown pages for your authors. When a page with the same name as an author exists, the author's name in page headers will automatically link to that page.

## Basic usage

Add authors to a page using the `authors` field in the frontmatter:

```yaml
---
title: My Amazing Post
authors:
  - jane-smith
  - john-doe
---
```

## Author pages

Author pages are just regular markdown pages. The only special aspect is the optional `avatar` field that enables displaying profile pictures next to author names in page headers.

Example author page:

```yaml
---
title: Jane Smith
description: Technical writer
avatar: /assets/jane-avatar.jpg  # Optional - enables profile picture in page headers
---

Regular markdown content about Jane...
```

The `avatar` field can be:
- A path to an image in your repository: `/assets/jane-avatar.jpg`
- An external URL: `https://example.com/jane-avatar.jpg`

That's it! Author pages work just like any other page in your site - you can use all standard frontmatter fields, apply custom styling, include any markdown content, and use all Flowershow features.

For a detailed guide with examples and screenshots, see [[how-to-create-author-pages|How to Create Author Pages]].