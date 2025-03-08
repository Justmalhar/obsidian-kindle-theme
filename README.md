# Kindle Theme for Obsidian

A theme that transforms your Obsidian experience into a Kindle-like reading environment, optimized for comfortable long-form reading and note-taking.

## Demo

![Dark Theme](/demo/Kindle%20Theme%20Dark.png)

![Light Theme](/demo/Kindle%20Theme%20Light.png)

## Features

- **Kindle-inspired Typography**: Uses Bookerly font (with fallbacks to similar serif fonts) for a comfortable reading experience
- **Optimized Reading Width**: Carefully calibrated text width similar to Kindle devices
- **Paper-like Appearance**: Clean, distraction-free interface with subtle paper textures
- **First-letter Drop Caps**: Beautiful drop caps for the first letter of paragraphs after headings
- **Proper Paragraph Spacing**: Improved paragraph spacing and indentation for better readability
- **Elegant Blockquotes**: Styled with subtle quotation marks and indentation
- **Responsive Images**: Images scale appropriately and have subtle borders
- **Dark & Light Modes**: Both modes are carefully designed to reduce eye strain
- **Minimal UI**: Reduced interface elements to keep focus on your content

## Installation

### From Obsidian Community Themes

1. Open Obsidian Settings
2. Navigate to Appearance → Themes
3. Click "Manage" button
4. Search for "Kindle Theme" and click "Install"
5. Click the toggle button to activate the theme

### Manual Installation

1. Download the `theme.css` file from this repository
2. In your Obsidian vault, create a folder called `.obsidian/themes/Kindle Theme/`
3. Place the downloaded `theme.css` file into that folder
4. Open Obsidian Settings → Appearance → Themes and select "Kindle Theme"

## Recommended Settings

For the best Kindle-like experience, we recommend:

- Enable "Reading view" for your notes
- Set line width to "Readable" in Settings → Editor
- Consider using the [Longform](https://github.com/kevboh/longform) plugin for writing longer documents

## Customization

The theme uses CSS variables that you can override in your own snippets. Some key variables:

```css
body {
  --font-text-theme: "Your preferred font", serif;
  --font-size-base: 20px;
  --line-height-base: 1.618;
  --max-width: 38em;
}
```

## Credits

- Inspired by the reading experience of Amazon Kindle devices
- Font recommendations include Bookerly, Crimson Pro, and other serif fonts optimized for screen reading

## License

MIT License

## Support

If you encounter any issues or have suggestions for improvements, please open an issue on GitHub.

---

Enjoy your distraction-free reading and writing experience!
