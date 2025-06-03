---
title: "`List` component"
description: Create organized lists and content catalogs by automatically listing files in a specified directory.
---

## Usage

Add the List component to your markdown file:

```markdown
<List dir="/blog"/>
```

The component will display:
- Title (from frontmatter or filename)
- Description (from frontmatter)
- Publication date (from frontmatter)

>[!note]
>Files are sorted by date (newest first) if dates are provided in frontmatter, otherwise they are sorted by title.

## Configuration

The List component accepts the following props:

```markdown
dir: string       # Absolute path to directory (must start with '/')
fields?: Array<"title" | "description" | "authors" | "date" | "image">  # Which metadata fields to display
pageSize?: number # Number of items per page for pagination
```

The default values are:
- `fields = ["title", "description"]`
- `pageSize = 10`

For example:
```markdown
<List dir="/blog"/>
<List dir="/blog" fields={["title", "description", "date", "authors"]} pageSize={5}/>
```

## Behavior

The List component:
- Lists markdown files from the specified directory
- Ignores `README.md` and `index.md` files
- Is recursive (includes files in subdirectories)
- Sorts by date if available, otherwise by title
- Displays selected metadata fields based on the fields prop
- Paginates results based on the pageSize prop
- Displays each file's metadata according to the specified fields

For a detailed guide including examples and step-by-step instructions, check out our [[how-to-create-content-catalogs|this blog post]].