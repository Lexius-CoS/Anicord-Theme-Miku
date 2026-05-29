# Miku Rose

A personalized Discord theme — soft pink accents, forest green translucent panels, zero glow lag.

Based on [Anicord](https://github.com/sang765/Anicord-Theme) → [Translucence](https://capnkitten.github.io/BetterDiscord/Themes/Translucence/).

## Features

- **Soft Pink Accent** (`HSL: 340, 60%, 65%`) — buttons, links, highlights, mentions
- **Forest Green Panels** — dark green tint, more transparent than stock Anicord
- **Miku Meadow Wallpaper** — custom background
- **Performance Optimized** — all glow effects, backdrop-filter blur, brightness filters, and heavy animations stripped

## Installation (Vencord)

1. **Settings** → **Themes** → **Online Themes**
2. Paste:
```
https://raw.githubusercontent.com/Lexius-CoS/Anicord-Theme-Miku/main/Anicord.theme.css
```
3. Save

## Customization

```css
:root {
    --app-bg: url(your-image-url);
    --accent-hue: 340;          /* Pink */
    --accent-saturation: 60%;
    --accent-lightness: 65%;
    --sidebar-color: rgba(12, 24, 12, 0.55);
    --main-content-color: rgba(12, 24, 12, 0.35);
}
```

## What was stripped for performance

| Effect | Location | Fix |
|--------|----------|-----|
| `backdrop-filter: blur(5px)` | Hardcoded on popouts, modals, sidebar, chat | `none !important` |
| Glow `box-shadow` | Guild icons, channels, members, avatars, badges | `none !important` |
| `text-shadow` glow | Username hover | `none !important` |
| `filter: brightness(2)` | Icons | `none !important` |
| Animated `box-shadow` transitions | `.3s`–`.5s` on multiple elements | Replaced with 150ms opacity/transform only |
| Version fade animation | `@keyframes version` | `none !important` |

## Credits

- **Base**: [Translucence](https://capnkitten.github.io/BetterDiscord/Themes/Translucence/) by CapnKitten
- **Original concept**: [Anicord](https://github.com/sang765/Anicord-Theme) by sangsdayy
- **Miku Rose**: Lexius-CoS
