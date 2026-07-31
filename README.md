# Unraid Dark Theme

A custom dark theme for the Unraid web interface, with blue and orange accents,
animated ambient gradients, moving background specks, and subtle dithering to
reduce color banding.

## Features

- Dark, translucent interface surfaces
- Blue accent color with orange status highlights
- Animated gradient and speck background
- Reduced-motion support
- Styling for common Unraid tables, forms, dialogs, navigation, and plugins
- Self-contained assets embedded directly in the stylesheet

## Installation

1. Open [`theme.css`](theme.css) and copy its contents.
2. Paste the CSS into the custom CSS field provided by your Unraid theming or
   custom styling plugin.
3. Save the changes and refresh the Unraid web interface.

Keep a copy of your previous CSS before replacing it. Unraid or plugin updates
can change selectors, so some rules may occasionally need adjustment.

## Customization

The main accent color is defined near the top of `theme.css`:

```css
--theme-accent: #5b8bd9;
```

Near the end of the file, the **Speck Controls** section contains variables for
background brightness and animation speed. The **Gradient Anti-Banding /
Dither** section contains `--dither-opacity` for tuning the noise overlay.

## Compatibility

The theme targets the Unraid web interface and includes rules for several
commonly used interface components and plugins. Exact results can vary between
Unraid and plugin versions.

## License

No license has been granted yet. Add a license before redistributing or
accepting contributions.
