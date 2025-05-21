---
title: Math equations
description: Write math equestions with LaTeX syntax.
---

## How to use

### Inline math

- Use between `$`

For example if your markdown file has the following

```markdown
$\sqrt{a^2 + b^2}$
```

will be rendered as

$\sqrt{a^2 + b^2}$

### Block math

- Use between double `$$`

For example if your markdown has the following

```markdown
$$
\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc
$$
```

will be rendered as

$$
\begin{vmatrix}a & b\\
c & d
\end{vmatrix}=ad-bc
$$

More documentation on math syntax usage can be found in [KaTeX docs](https://katex.org/docs/support_table.html).
