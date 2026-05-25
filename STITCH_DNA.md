# Tatsyaa Stitch Design System DNA (STITCH_DNA.md)

This document contains the complete extracted design DNA from the Tatsyaa Home Page, detailing the color palette, typography rules, layout systems, component padding, and shapes.

---

## 🎨 1. Color Palette & Hex Codes

| Token Name | Hex Code | Purpose / Usage |
| :--- | :--- | :--- |
| `primary` | `#5a000c` | Deep burgundy brand mark, primary headings, key action underlines. |
| `primary-container` | `#7f0f1b` | Solid background for primary call-to-actions (CTAs) and active overlays. |
| `surface` | `#fbf8ff` | Primary theme background, evoking a premium, airy, lavender-tinted off-white feel. |
| `on-surface` | `#1a1b22` | Warm charcoal for primary body text, ensuring luxury editorial legibility. |
| `secondary` | `#5c5e68` | Muted charcoal for secondary text, labels, and icons. |
| `on-surface-variant` | `#584140` | Subtle text color for secondary descriptors. |
| `outline` | `#8b716f` | Micro-accent borders and standard divider lines. |
| `outline-variant` | `#dfbfbd` | Very low-contrast boundaries (used at 20-30% opacity). |
| `surface-container-low` | `#f4f2fd` | Foundational background block color for section containers. |
| `surface-container-high` | `#e8e7f1` | Subtle backgrounds for hover cards and search blocks. |
| `surface-container-highest` | `#e3e1ec` | Full-width high-contrast container panels (e.g. newsletter). |

---

## ✒️ 2. Typography Rules

The typography strategy leverages the literary authority of **Noto Serif** paired with the clean geometric precision of **Manrope**.

| Rule Name | Font Family | Size | Weight | Line Height | Tracking (Letter Spacing) | Usage |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `display-lg` | Noto Serif | `48px` | `400` | `1.2` | `-0.02em` | Main hero titles (EDITORIAL) |
| `headline-lg` | Noto Serif | `32px` | `400` | `1.3` | Default | Standard section headings |
| `headline-lg-mobile` | Noto Serif | `28px` | `400` | `1.3` | Default | Mobile section headings |
| `headline-md` | Noto Serif | `24px` | `500` | `1.4` | Default | Card titles & testimonials |
| `body-lg` | Manrope | `18px` | `400` | `1.6` | Default | Editorial story descriptions |
| `body-md` | Manrope | `16px` | `400` | `1.6` | Default | Standard paragraph text |
| `label-md` | Manrope | `14px` | `600` | `1.2` | `0.05em` | UPPERCASE tags, CTAs, navigation |

---

## 📏 3. Spacing, Layout & Element Padding

The spatial layout relies on an 8px modular spacing unit to ensure proportional vertical rhythm and a generous "luxury brand" white space.

### Core Spacing Tokens
* **Base Spacing Unit:** `8px`
* **Maximum Container Width:** `1280px`
* **Section Grid Gutters:** `24px`
* **Desktop Page Margin (Side Padding):** `64px`
* **Mobile Page Margin (Side Padding):** `20px`

### Component Padding Rules
* **Major Section Padding:** Minimum `80px` (or `py-24`) vertical padding to allow content categories to breathe.
* **CTAs / Primary Buttons:**
  * Vertical Padding: `16px` (`py-4`)
  * Horizontal Padding: `40px` (`px-10`)
  * Font Treatment: Uppercase `label-md`
* **Curated Search Bar:**
  * Horizontal Padding: `16px` (`px-4`)
  * Vertical Padding: `8px` (`py-2`)
* **Collection Cards & Product Grids:**
  * Gutter spacing: `24px` (`gap-gutter`)
  * Information center-aligned with no visible borders, utilizing blank spaces as separators.

---

## 📐 4. Shapes & Roundness
To maintain a precision, structured, and architectural aesthetic, shapes are kept **Soft (Level 1)**:
* `sm` (Small): `0.125rem` (2px)
* `DEFAULT` (Medium): `0.25rem` (4px)
* `md` (Card radius): `0.375rem` (6px)
* `lg` (Major elements): `0.5rem` (8px)
* `xl` (Large overlay): `0.75rem` (12px)
* `full` (Pills/Badges): `9999px`
