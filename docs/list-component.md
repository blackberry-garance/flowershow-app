---
title: "`List` component"
description: Create organized lists and content catalogs by automatically listing files in a specified directory.
---

## Basic example

```markdown
<List dir="/blog"/>
```

The `List` component will display all the markdown files in the specified directory, showing their titles and descriptions by default.

## Configuration

The `List` component accepts the following props:
- `dir` (required):
  - Absolute path to a directory (must start with '/')
  - Type: `string`
- `fields` (optional):
  - Array of metadata fields to display
  - Type: `Array<"title" | "description" | "authors" | "date" | "image">`
  - Default value: `["title", "description"]`
- `pageSize` (optional):
  - Number of items per page for pagination
  - Type: `number`
  - Default value: 10

For example:
```markdown
<List dir="/blog"/>
<List dir="/blog" fields={["title", "description", "date", "authors"]} pageSize={5}/>
```

## Behavior

The List component:
- Ignores `README.md` and `index.md` files
- Is recursive (includes files in subdirectories)
- Sorts by date if available, otherwise by title

> [!info]
> For a detailed guide including examples and step-by-step instructions, check out [[how-to-create-content-catalogs|this blog post]].