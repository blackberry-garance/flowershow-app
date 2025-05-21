---
title: "`config.json` file"
---
## What is `config.json` file

`config.json` file is the central configuration file for your Flowershow site. It allows you to customize various aspects of your site, from analytics and comments to navigation and layout options.

## File location

Place the `config.json` file in the root directory of your site's content. For most users, this means placing it in the root of your repository. However, if you publish only a specific folder of your vault/repository, you should place this file within that folder.

## Available options

Here is an overview of all the site-wide configuration options that you can set through `config.json` file.

```json
{
  "analytics": "G-XXXXXXXXXX",
  "nav": {
    "logo": "logo.jpeg",           // Path to your logo file or external URL
    "title": "My Digital Garden",  // Site title displayed next to the logo
    "links": [                     // Navigation links
      {
        "href": "/blog",
        "name": "Blog"
      }
    ],
    "social": [                    // Social media links
      {
        "label": "github",
        "name": "GitHub Profile",
        "href": "https://github.com/yourusername"
      }
    ]
  },
  "showComments": false,           // Disable comments site-wide (if you want to enable them only on specific pages)
  "showSidebar": true,             // Show site map on the left
}
```
