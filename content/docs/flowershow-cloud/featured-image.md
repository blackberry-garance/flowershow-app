---
title: Add Featured Images
tags:
  - flowershow-cloud
---

You can add featured images to your pages in Flowershow Cloud by setting the `image` frontmatter field. This image will also be used for social media cards.

## Image Sources

You can specify your featured image in two ways:

1. **Repository Path**: Use a relative or absolute path to an image in your repository
2. **External URL**: Link to an image hosted elsewhere on the web

## Adding a Featured Image

Add the `image` field to your page's frontmatter:

```yaml
---
title: My Page
image: content/assets/my-image.jpg  # relative path
---
```

Or use an absolute path from your repository root:

```yaml
---
title: My Page
image: /content/assets/my-image.jpg  # absolute path
---
```

You can also use external URLs:

```yaml
---
title: My Page
image: https://example.com/my-image.jpg  # external URL
---
```

## Best Practices

- Use high-quality images that represent your content well
- Recommended image dimensions: 1200x630 pixels for optimal social media sharing
- Keep file sizes reasonable (under 1MB) for better performance