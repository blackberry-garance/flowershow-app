---
title: How to Create Blogs and Listing Pages with Flowershow
description: Flowershow's new listing features make it super easy to create blog index pages and other kind of listing pages for tutorials, recipes, and more.
date: 2025-03-25
modified: 2025-06-03
authors:
  - olayway
image: /assets/Pasted%20image%2020250325124121.png
---

Whether you're managing a blog, documentation, recipes, or any other collection of markdown files, the List component makes it easy to display them in a clean, organized way.

## Quick Start (2-Minute Setup)

1. Create a new markdown file (or pick one you already have)
2. Add this single line:
```jsx
<List dir="/blog"/> // replace `/blog` with path to your folder 
```

That's it! You now have a beautifully formatted list of all the markdown files within the specified directory. Read on to learn how to customize it further.

## Using the List Component

The `List` component is a simple way to automatically list all markdown files in any directory in your site. Here's how to use it:

```markdown
<List dir="/blog"/>
```

That's it! This single line will create an elegantly formatted list of all markdown files in your `/blog` directory, displaying each file's:
- Title
- Description

## Configuration Options

The List component supports several configuration options:

```markdown
<List 
  dir="/blog"
  fields={["title", "description", "date", "authors", "image"]}
  pageSize={5}
/>
```

### Fields

The `fields` prop lets you specify which metadata to display for each item:
- `title`: The page title
- `description`: The page description
- `authors`: Author information
- `date`: Publication date
- `image`: Featured image

By default, only `title` and `description` are shown.

### Pagination

The `pageSize` prop controls how many items are displayed per page. The default is 10 items per page.

## Example Usage

```markdown
---
title: Welcome to My Blog
description: Welcome to my collection of thoughts and ideas
---

Here are all my blog posts:

<List 
  dir="/blog"
  fields={["title", "description", "date", "authors"]}
  pageSize={5}
/>
```

## Important Notes

- The `dir` prop must be an absolute path
- The component won't list home (aka index) pages (`README.md` or `index.md` files)
- Files are sorted by date (newest first) if dates are provided in frontmatter, otherwise they are sorted by title
- The component is recursive - it will show files in subdirectories

By using the List component effectively, you can create organized, easy-to-navigate content collections that your readers will love. It's a simple yet powerful way to showcase your markdown content in a professional and user-friendly manner.
