# Earth Day Celebration Webpage

This project is dedicated to creating an interactive and visually appealing webpage to celebrate Earth Day. It aims to raise awareness of environmental issues through engaging content and interactive design using HTML, CSS, and SVG graphics.

## Features

- Responsively designed elements that work on various screen sizes.
- Custom animations for SVG graphics and emoji to create a dynamic user experience.
- Usage of environmentally-themed emojis to enhance visual storytelling.
- Integration of a modern, accessible font for better readability.
- No JavaScript used to keep the site lightweight and performant.

## Project Structure

- `index.html` - The main HTML document.
- `styles.css` - The stylesheet containing all the CSS for styling and animations.
- `assets/` - Directory containing any SVG files or additional resources used by the webpage.

## Usage

To use this webpage, simply clone the repository or download the `index.html` and `styles.css` files to the same directory on your web server.

### Adding Emojis

To insert emojis into your HTML content, use `<span>` tags with `aria-hidden="true"` to ensure they do not affect the accessibility of the site:

```html
<span aria-hidden="true">🌍</span> <!-- Earth Emoji -->
<span aria-hidden="true">🌳</span> <!-- Tree Emoji -->
<span aria-hidden="true">💧</span> <!-- Water Drop Emoji -->
