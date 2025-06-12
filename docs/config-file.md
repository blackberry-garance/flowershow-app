---
title: "`config.json` file"
---
## What is `config.json` file

`config.json` file is the configuration file for your Flowershow site complementary to site settings in your dashboard. It allows you to customize various aspects of your site, from analytics and comments to navigation and layout options.

> [!info]
> This is just a reference page documenting the correct file structure, fields and value types. To see all the site configuration options we advise you to visit [[site-settings|Site settings]] instead.

## File location

Place the `config.json` file in the root directory of your site's content. For most users, this means placing it in the root of your repository. However, if you publish only a specific folder of your vault/repository, you should place this file within that folder.

## Available options

Here is an overview of all the site-wide configuration options that you can set through `config.json` file.

```json
{
  "title": "Your Site Title",
  "description": "Your site description",
  "favicon": "/path/to/favicon.png",
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
  "analytics": "G-XXXXXXXXXX",
  "showComments": false,           // Disable comments site-wide (if you want to enable them only on specific pages)
  "showSidebar": true,             // Show site map on the left,
  "contentInclude": ["/blog", "README.md"],
  "contentExclude": ["/blog/_archive"]
}
```
