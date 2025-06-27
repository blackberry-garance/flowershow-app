---
title: How to Set Custom Fonts Using Google Fonts
description: Learn how to enhance your site's typography by using custom fonts from Google Fonts
date: 2025-06-27
publish: false
authors:
  - olayway
---

This guide will show you how to use custom fonts from Google Fonts to enhance your site's typography. You'll learn how to select fonts, import them using CSS, and apply them to different elements of your site.

Here's what we'll transform:

![[Pasted image 20250627144126.png]]

Into this:



## What You'll Need

Before you begin, make sure you have:
- A Flowershow Cloud site set up
- A `custom.css` file in your site's root directory
- Basic knowledge of CSS

## Step 1: Choose Your Fonts

1. Visit [Google Fonts](https://fonts.google.com)
2. Browse and select the fonts you want to use:
   - Click on a font family you like (e.g., "Playfair Display")
   - Click the "Get font" button
   - Repeat for additional fonts (e.g., "Source Sans 3")
   - Click the "View selected families" button in the top right corner 
3. In the selected families panel:
   - Click "Get embeded code"
   - Review all your chosen fonts and make sure to select the styles and weights you need
   - Find your import code in the "Web" tab on the right
   - Choose "@import" to get the CSS import code

> [!tip]
> When selecting fonts, consider:
> - Readability at different sizes
> - Loading time (more fonts/weights = slower load times)
> - How fonts complement each other (e.g., serif headings with sans-serif body text)

## Step 2: Import the Fonts

1. Open your `custom.css` file
2. At the very top of the file, add the `@import` code from Google Fonts. For example:

```css
/* Import fonts from Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Source+Sans+Pro:wght@400;600&display=swap');
```

This code imports:
- Playfair Display (regular 400 and bold 700 weights)
- Source Sans Pro (regular 400 and semibold 600 weights)

## Step 3: Apply the Fonts

Now add CSS rules to apply your fonts to different elements. Here's an example:

```css
/* Apply fonts to all headings */
h1, h2, h3, h4, h5, h6 {
    font-family: 'Playfair Display', serif !important;
}

/* Apply font to body text */
body {
    font-family: 'Source Sans 3', sans-serif !important;
}

/* Style specific heading levels */
h1 {
    font-weight: 700 !important; /* Bold weight */
    font-size: 2.5rem !important;
}

h2 {
    font-weight: 400 !important; /* Regular weight */
    font-size: 2rem !important;
}

/* Style paragraphs */
p {
    font-weight: 400 !important; /* Regular weight */
    line-height: 1.6 !important;
}

/* Style strong/bold text */
strong {
    font-weight: 600 !important; /* Semibold weight */
}
```

> [!note]
> We use `!important` to ensure our custom styles override the default theme styles.

## Having Problems?

If your fonts aren't loading:

1. Check your internet connection (Google Fonts requires internet access)
2. Verify the `@import` URL is correct
3. Make sure the font names in your CSS exactly match the Google Fonts names
4. Clear your browser cache and reload the page
5. Check the browser's developer tools console for any errors

> [!tip]
> For better performance, consider:
> - Loading only the font weights you actually use
> - Using system fonts as fallbacks
> - Preloading critical fonts using `<link rel="preload">` in your HTML

## Best Practices

1. **Don't use too many fonts**: Stick to 2-3 fonts maximum for better consistency and performance
2. **Choose readable fonts**: Ensure your body text font is highly readable
3. **Test different sizes**: What looks good on your screen might be too small/large on others
4. **Consider fallbacks**: Always include fallback fonts in case Google Fonts is unavailable:
```css
body {
    font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif !important;
}
```

By following these steps, you'll have a professionally styled site with custom typography that enhances your content's readability and visual appeal.