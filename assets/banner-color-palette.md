# Banner Color Palette & Theme Specification

## Core Color Palette

The banner and profile visuals adhere strictly to the dark GitHub modern cyber color system:

| Color Role | Hex Code | RGB | HSL | Usage & Description |
| :--- | :--- | :--- | :--- | :--- |
| **Dark Background** | `#0D1117` | `rgb(13, 17, 23)` | `hsl(216, 28%, 7%)` | Primary canvas canvas matching GitHub Dark Default theme. |
| **Container Surface** | `#161B22` | `rgb(22, 27, 34)` | `hsl(215, 21%, 11%)` | Frosted glass card fill and subtle elevated panels. |
| **Neon Emerald** | `#00D26A` | `rgb(0, 210, 106)` | `hsl(150, 100%, 41%)` | Primary accent color, highlights, success states, and badges. |
| **GitHub Tech Blue** | `#58A6FF` | `rgb(88, 166, 255)` | `hsl(212, 100%, 67%)` | Secondary accent, link indicators, and technical details. |
| **Primary Text** | `#FFFFFF` | `rgb(255, 255, 255)` | `hsl(0, 0%, 100%)` | Main headings and high-contrast title typography. |
| **Muted Text** | `#C9D1D9` | `rgb(201, 209, 217)` | `hsl(210, 25%, 82%)` | Body copy, secondary descriptors, and technical subtext. |
| **Border / Subtle** | `#30363D` | `rgb(48, 54, 61)` | `hsl(212, 12%, 21%)` | Card borders, dividers, and subtle structural outlines. |

---

## Accessibility & Contrast Ratios

- `#FFFFFF` on `#0D1117` — **17.9:1** (WCAG AAA compliant)
- `#00D26A` on `#0D1117` — **8.4:1** (WCAG AAA compliant)
- `#58A6FF` on `#0D1117` — **7.2:1** (WCAG AAA compliant)
- `#C9D1D9` on `#0D1117` — **13.5:1** (WCAG AAA compliant)

---

## Gradient Combinations

- **Emerald Glow Gradient:** `linear-gradient(135deg, rgba(0, 210, 106, 0.25) 0%, rgba(13, 17, 23, 0) 100%)`
- **Cyber Blue Glow Gradient:** `linear-gradient(135deg, rgba(88, 166, 255, 0.20) 0%, rgba(22, 27, 34, 0.8) 100%)`
- **Glass Border Overlay:** `linear-gradient(90deg, #00D26A 0%, #58A6FF 100%)`
