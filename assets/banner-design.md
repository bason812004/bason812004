# Cyber-Glassmorphism Banner Specification

## Overview
This document specifies the technical design system and aesthetic rules for the header banner of **Nguyễn Bá Sơn**'s GitHub profile. The banner employs a modern **Cyber-Glassmorphism** theme built specifically for dark GitHub UI rendering (`#0D1117`).

---

## Design Principles

### 1. Modern Minimalist Cyber Aesthetics
- Clean dark background (`#0D1117`) eliminating visual noise.
- Translucent glass containers (`#161B22` at 60% opacity with backdrop blur filters).
- Subtle glow effects around text and container edges to project high technical polish.
- Strict avoidance of generic templates, gaming visuals, anime tropes, or hacker wallpapers.

### 2. Information Hierarchy
- **Primary Title:** `Nguyễn Bá Sơn` — Prominent, high contrast text in custom sans-serif font.
- **Secondary Title:** `Full Stack Developer` — Emerald green accent subhead (`#00D26A`).
- **Core Tech Line:** `React • Node.js • TypeScript • PostgreSQL` — Clear stack badges.
- **Tagline:** `Building Scalable Web Applications` — Recruiter-focused mission statement.

---

## Layout Architecture

```
+-------------------------------------------------------------------+
|  [Background: Grid Pattern & Subtle Neon Glow #00D26A / #58A6FF]   |
|                                                                   |
|  +-------------------------------------------------------------+  |
|  |  [Glassmorphism Container #161B22 @ 60% Opacity]            |  |
|  |                                                             |  |
|  |  Nguyễn Bá Sơn                                              |  |
|  |  Full Stack Developer                                       |  |
|  |                                                             |  |
|  |  React • Node.js • TypeScript • PostgreSQL                  |  |
|  |  Building Scalable Web Applications                         |  |
|  +-------------------------------------------------------------+  |
+-------------------------------------------------------------------+
```

---

## Dimensions & Aspect Ratio

- **Recommended Canvas Size:** 1200px × 400px (3:1 Aspect Ratio)
- **Safe Rendering Zone:** 1000px × 320px (Centers perfectly across desktop & mobile displays)
- **Export Format:** High-density WebP or PNG with maximum anti-aliasing.
