---
name: Modern Heritage
colors:
  surface: '#fbf8ff'
  surface-dim: '#dad9e3'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f2fd'
  surface-container: '#eeedf7'
  surface-container-high: '#e8e7f1'
  surface-container-highest: '#e3e1ec'
  on-surface: '#1a1b22'
  on-surface-variant: '#584140'
  inverse-surface: '#2f3038'
  inverse-on-surface: '#f1effa'
  outline: '#8b716f'
  outline-variant: '#dfbfbd'
  surface-tint: '#ab3237'
  primary: '#5a000c'
  on-primary: '#ffffff'
  primary-container: '#7f0f1b'
  on-primary-container: '#ff8785'
  inverse-primary: '#ffb3b0'
  secondary: '#5c5e68'
  on-secondary: '#ffffff'
  secondary-container: '#e1e1ed'
  on-secondary-container: '#62646e'
  tertiary: '#292929'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f3f3f'
  on-tertiary-container: '#acaaaa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b0'
  on-primary-fixed: '#410006'
  on-primary-fixed-variant: '#8a1922'
  secondary-fixed: '#e1e1ed'
  secondary-fixed-dim: '#c5c6d1'
  on-secondary-fixed: '#191b24'
  on-secondary-fixed-variant: '#454650'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#fbf8ff'
  on-background: '#1a1b22'
  surface-variant: '#e3e1ec'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

This design system embodies "Modern Heritage"—a bridge between timeless Indian craftsmanship and contemporary luxury e-commerce. The brand personality is sophisticated, artisanal, and curated. It targets a discerning audience that values cultural roots but prefers a clean, editorial shopping experience.

The visual style is a blend of **Minimalism** and **Modern Corporate**, utilizing generous whitespace and precise typography to allow high-fidelity product photography to lead the narrative. Subtle textures, inspired by textile weaves, are used as low-opacity backgrounds to ground the digital experience in the tactile world of high-end fashion.

## Colors

The palette is anchored by a deep burgundy primary color, evoking luxury and traditional pigments. This is balanced by a soft, lavender-tinted off-white for surfaces, providing a more elegant and softer alternative to pure white.

- **Primary (#7F0F1B):** Used for key actions, brand marks, and high-impact accents.
- **Surface (#E8E8F4):** The foundational background color to evoke a premium, airy feel.
- **On-Surface (#2C2C2C):** A warm charcoal for primary text, ensuring readability without the harshness of pure black.
- **Muted (#71717A):** Used for secondary information and decorative borders.

## Typography

The pairing combines the literary authority of **Noto Serif** with the geometric precision of **Manrope**. 

Headlines utilize Noto Serif to mirror the logo’s elegance, featuring tight letter-spacing in display sizes for a high-fashion editorial look. Body text uses Manrope for its exceptional readability and modern, neutral character. Labels and navigation items are set in uppercase Manrope with increased letter spacing to create a sense of organized luxury.

## Layout & Spacing

This design system uses a **fixed grid** model for desktop to maintain editorial control over whitespace, and a **fluid grid** for mobile devices. 

- **Desktop:** 12-column grid with a 1280px max-width, 24px gutters, and 64px side margins. 
- **Mobile:** 4-column fluid grid with 16px gutters and 20px side margins.

The spacing rhythm is based on an 8px base unit. Generous vertical padding (minimum 80px between major sections) is essential to maintain the "Modern Heritage" aesthetic, preventing the UI from feeling cluttered or "discount."

## Elevation & Depth

Visual hierarchy is achieved through **tonal layers** and **low-contrast outlines** rather than heavy shadows. 

Surfaces should feel flat and structural. To indicate elevation for floating elements like dropdowns or cart drawers, use an extremely diffused, low-opacity shadow (#7F0F1B at 4% opacity) to provide a subtle "glow" that feels integrated with the brand color. Borders are kept thin (1px) and use a slightly darker tint of the background color to create definition without visual noise.

## Shapes

To maintain the "Modern" half of the heritage narrative, shapes are kept **Soft (Level 1)**. 

Rectilinear forms with very slight corner rounding (4px) communicate precision and structure. This applies to product cards, input fields, and buttons. Interactive elements like "Add to Cart" should maintain these crisp edges to feel more like high-end architectural elements than casual mobile app components.

## Components

- **Buttons:** Primary CTAs are solid Burgundy (#7F0F1B) with white Manrope text in uppercase. Secondary buttons use a 1px Burgundy border with a transparent background.
- **Input Fields:** Use a 1px border in #D1D1DF. Focus states should transition the border to Burgundy. Labels are placed above the field in uppercase Manrope (Label-md).
- **Product Cards:** Minimalist styling with no external border. Information is center-aligned below the image using Noto Serif for the product name and Manrope for the price.
- **Chips/Filters:** Rectangular with 2px rounded corners. Active states use a soft lavender fill (#D8D8E6) with burgundy text.
- **Lists:** Editorial style with thin horizontal dividers (1px #D1D1DF). High-contrast typography distinguishes list titles from descriptions.
- **Special Accents:** Use subtle, semi-transparent Indian geometric patterns as background watermarks in the footer or section headers to reinforce the "Heritage" aspect.
