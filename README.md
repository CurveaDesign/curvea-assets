# Curvea Assets

Official brand and design assets used across the Curvea ecosystem.

This repository acts as the **single source of truth** for shared Curvea visual assets and is intended for use across Curvea products, websites, social media, and design workflows.

---

## Current Brand Assets

### Symbol

The standalone Curvea symbol is available in color, dark, and light variants.

**SVG**
- `logos/svg/curvea-symbol-color.svg`
- `logos/svg/curvea-symbol-dark.svg`
- `logos/svg/curvea-symbol-light.svg`

**PNG**
- `logos/png/curvea-symbol-color.png`
- `logos/png/curvea-symbol-dark.png`
- `logos/png/curvea-symbol-light.png`

Use the color symbol as the primary branded standalone mark. Use the dark or light version when a monochrome treatment is more appropriate.

### Wordmark

The Curvea wordmark is intentionally monochrome.

**SVG**
- `wordmarks/svg/curvea-wordmark-dark.svg`
- `wordmarks/svg/curvea-wordmark-light.svg`

**PNG**
- `wordmarks/png/curvea-wordmark-dark.png`
- `wordmarks/png/curvea-wordmark-light.png`

Use the dark wordmark on light backgrounds and the light wordmark on dark backgrounds.

### Favicons and App Icons

Current favicon and application icon assets are stored in `favicons/`:

- `favicon.ico`
- `favicon-16x16.png`
- `favicon-32x32.png`
- `favicon-48x48.png`
- `apple-touch-icon.png`
- `icon-192.png`
- `icon-512.png`
- `curvea-icon-1024.png`

---

## Asset Formats

- **SVG** is the preferred format for websites, interfaces, and scalable production use.
- **PNG** is provided for raster workflows, social media, presentations, and AI/image-generation reference workflows where an image asset is required.
- **ICO and favicon PNGs** are intended for browser, PWA, and application icon use.

Do not redraw, approximate, or reconstruct the Curvea symbol or wordmark when an official asset from this repository can be used.

---

## Production Migration

Legacy Curvea assets currently remain at their existing root paths inside `logos/`, `wordmarks/`, and `favicons/` so existing websites and products are not broken during the brand migration.

New projects and migrated projects should use the current assets listed above. Legacy files can be removed after all Curvea properties have been migrated to the new identity.

---

## Purpose

- Centralize Curvea brand assets in one place
- Ensure visual consistency across all Curvea products
- Avoid asset duplication between projects
- Provide stable, reusable asset URLs for production use
- Provide canonical source assets for design and AI-assisted workflows

---

## Usage

Assets can be referenced directly in projects using their raw GitHub URLs.

### Example: color symbol

```html
<img
  src="https://raw.githubusercontent.com/CurveaDesign/curvea-assets/main/logos/svg/curvea-symbol-color.svg"
  alt="Curvea"
/>
```

### Example: dark wordmark

```html
<img
  src="https://raw.githubusercontent.com/CurveaDesign/curvea-assets/main/wordmarks/svg/curvea-wordmark-dark.svg"
  alt="Curvea"
/>
```

---

## License

All assets in this repository are proprietary and owned by Curvea Design.  
Unauthorized use, redistribution, or modification is not permitted.
