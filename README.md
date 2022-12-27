# Onge's Neocities Feed Enhancer

Enhance your Neocities feed with custom HTML tags. Add images, spoilers, line breaks, headings, and more. Color your text and make it bold with custom tags! Easily add these features to your Neocities feed with this userscript.

[Click here to install the script.](https://ongezell.com/userscripts/onges-neocities-feed-enhancer.user.js)


## How to use

1. Install a userscript manager like Tampermonkey.
2. Install the userscript from the URL of your repository.
3. Navigate to your Neocities feed.
4. Enjoy the enhanced features!

## What it does

- Replaces image links with actual images for easier viewing, no need for tags for image links.
- Adds a "Spoiler" button to hide and reveal spoiler text.
- Replaces custom tags with HTML elements for adding line breaks, headings, and more.
- Allows you to style your text with the `(style=...)` custom tag.

## Custom tags
- `(style=css_style)` : Let's you stylized any element in your post using inline css.
- `(br)`: Inserts a line break.
- `(p)`: Inserts a paragraph.
- `(h1)`: Inserts a heading.
- `(center)`: Centers the text.


Here are some examples of how to use the custom tags:

- `(style=font-family: Arial; color: red; font-weight: bold) Text or Content to be stylized (style_)`
- `(br)`: Inserts a line break.
- `(p)This text is in a paragraph.(p_)`
- `(h1)This text is a heading.(h1_)`
- `(center)This text is centered.(center_)`


Note: Make sure to include the closing tags if needed. (e.g. `(h1_)`, `(center_)`).

