---
title: Site settings
description: Edit and manage settings for your entire published site
---

> [!info]
> Some features are only available on [premium sites](https://flowershow.app/pricing).

## Site name

Change your site name. If you don't have a custom domain set it will be used in the URL at which your site is published, i.e. `https://my.flowershow.app/@<your-username>/<site-name>`.

![[site-name-option.png]]

## Branch

Change the branch of the GitHub repository you're site is built from. Defaults to `main`.

![[branch-option.png]]

## Root directory

Set path to the folder in your GitHub repository that you want to publish. Leave this field empty if you want to publish the entire repository.

![[root-dir-option.png]]

For example, if you have a repository with your app's code and you wish to publish only it's documentation that you keep in `/docs`, you can use this field to do that.

## Auto-sync

Make your site content automatically publish after you commit any changes to your GitHub repository.

![[auto-sync-option.png]]

## Comments

Show comments section at the bottom of your pages.

![[comments-option.png]]

👉 See [[/docs/comments|Comments]] to learn more.

## Full-text search (⭐️ Premium feature)

Turn on content indexing and show search field in the nav bar to make finding relevant information easier for your visitors.

![[search-option.png]]

## Custom domain (⭐️ Premium feature)

Set custom domain for your site.

![[custom-domain-option.png]]

👉 See [[custom-domain|Custom domain]] to learn more.

## Analytics

Enable Google Analytics tracking with `analytics` field in your [[config-file|config file]].

```json
{
  "analytics": "G-XXXXXXXXXX" // Your GA4 Tracking ID
}
```

👉 See [[/docs/analytics|Analytics]] to learn more.

## Favicon (⭐️ Premium feature)

Set your site's favicon by specifying the path to your favicon file in the `favicon` field in your [[config-file|config file]]. You can also set it to an emoji using the same field.

```json
{
  "favicon": "/path/to/favicon.ico"
  // or "favicon": "🐶"
}
```

## Navigation bar

Customize your site's navigation bar. Set **logo**, **title**, **links** and **socials**.

```json
{
  "nav": {
    "logo": "/path/to/logo.png",
    ...
  }
}
```

👉 See [[navbar|Navigation bar]] to learn more.

## Sidebar

Show your site's sitemap in a sidebar on the left.

```json
{
  "showSidebar": true
}
```

👉 See [[sidebar|Sidebar]] to learn more.

## "Edit this page" links

> [!important] Works only for sites published from **public** GitHub repositories.

Show "Edit this page" links at the bottom of your site's pages to allow visitors to contribute to your content easily. Links will open the underlying files in edit mode in your GitHub repository.

```json
{
  "showEditLink": true
}
```

👉 See [[edit-this-page-links|"Edit this page" links]] to learn more.

## Excluding files from publishing

Control which files and directories get published.

```json
{
  "contentExclude": [
    "/private-folder",
    "/draft-file.md"
  ]
}
```

👉 See [[content-filtering|Content filtering]] to learn more.