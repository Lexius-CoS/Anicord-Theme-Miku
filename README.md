# Anicord Miku Edition

A customized version of the [Anicord Theme](https://github.com/sang765/Anicord-Theme) for Discord, featuring Miku's teal accent color and forest green panels.

## Features

- **Miku Teal Accent**: Buttons, links, and highlights use Miku's signature teal color (`#7AD1D1`)
- **Forest Green Panels**: Sidebar, chat, and member list have a dark forest green tint
- **Reduced Blur**: Blur effect reduced from 5px to 2px for better performance
- **Custom Wallpaper**: Features the Miku meadow wallpaper as the background

## Installation

### Vencord
1. Go to **Settings** → **Themes** → **Online Themes**
2. Paste this URL:
   ```
   https://raw.githubusercontent.com/Lexius-CoS/Anicord-Theme-Miku/main/Anicord.theme.css
   ```
3. Click **Save**

### BetterDiscord
1. Download the `Anicord.theme.css` file
2. Place it in your BetterDiscord themes folder
3. Enable the theme in **Settings** → **Themes**

## Customization

You can modify the theme by editing the CSS variables in the `:root` selector:

```css
:root {
    /* Background */
    --app-bg: url(your-image-url);
    --app-blur: 2px; /* Adjust blur intensity */
    
    /* Accent Color (HSL) */
    --accent-hue: 180; /* Teal */
    --accent-saturation: 49%;
    --accent-lightness: 65%;
    
    /* Panel Colors */
    --sidebar-color: rgba(15, 30, 15, 0.85);
    --main-content-color: rgba(15, 30, 15, 0.65);
}
```

## Credits

- **Original Theme**: [Anicord](https://github.com/sang765/Anicord-Theme) by sangsdayy
- **Base Theme**: [Translucence](https://capnkitten.github.io/BetterDiscord/Themes/Translucence/) by CapnKitten
- **Miku Edition Customization**: Lexius-CoS

## License

This customization follows the same license as the original Anicord theme.
