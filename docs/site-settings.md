---
title: Site settings
description: Edit and manage settings for your entire published site
---

> [!info] Some features are only available on [premium sites](https://flowershow.app/pricing).

## Configuration File

The `config.json` file is the central configuration file for your Flowershow site. It allows you to customize various aspects of your site, from analytics and comments to navigation and layout options.

### File Location

Place the `config.json` file in the root directory of your site's content. For most users, this means placing it in the root of your repository. However, if you publish only a specific folder of your vault/repository, you should place this file within that folder.

### Configuration Options

Here's a comprehensive overview of all available configuration options:

#### Analytics

Enable Google Analytics 4 tracking:

```json
{
  "analytics": "G-XXXXXXXXXX"  // Your GA4 Measurement ID
}
```

[[/docs/analytics|Learn more]]

#### Comments

Control comment functionality across your site:

```json
{
  "showComments": false  // Disable comments site-wide (if you want to enable them only on specific pages)
}
```

[[/docs/comments|Learn more]]

#### Navigation Bar

Customize your site's navigation bar:

```json
{
  "nav": {
    "logo": "logo.jpeg",        // Path to your logo file or external URL
    "title": "My Digital Garden", // Site title displayed next to the logo
    "links": [                  // Navigation links
      {
        "href": "/blog",
        "name": "Blog"
      }
    ],
    "social": [                // Social media links
      {
        "label": "github",     // Platform identifier
        "name": "GitHub Profile",
        "href": "https://github.com/yourusername"
      }
    ]
  }
}
```

[[/blog/how-to-configure-navigation-bar|Learn more]]

#### Sidebar

Enable the sidebar navigation:

```json
{
  "showSidebar": true  // Enable sidebar navigation (with sitemap)
}
```

[[/docs/sidebar-configuration|Learn more]]

### Complete Example

Here's a comprehensive example showing all available options:

```json
{
  "analytics": "G-XXXXXXXXXX",
  "showComments": true,
  "showSidebar": true,
  "nav": {
    "logo": "logo.jpeg",
    "title": "My Digital Garden",
    "links": [
      {
        "href": "/blog",
        "name": "Blog"
      }
    ],
    "social": [
      {
        "label": "github",
        "name": "GitHub Profile",
        "href": "https://github.com/yourusername"
      }
    ]
  }
}
```
