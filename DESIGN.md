---
name: Architectural Monochrome
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c8'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c7'
  primary: '#ffffff'
  on-primary: '#2f3131'
  primary-container: '#e2e2e2'
  on-primary-container: '#636565'
  inverse-primary: '#5d5f5f'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#ffffff'
  on-tertiary: '#313030'
  tertiary-container: '#e5e2e1'
  on-tertiary-container: '#656464'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
typography:
  headline-display:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 24px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style

This design system embodies a rigorous, high-end architectural aesthetic. It is defined by a strict monochromatic palette that rejects all warmth in favor of structural purity and stark contrast. The brand personality is authoritative, sophisticated, and uncompromising, targeting a high-end audience that values precision and minimal luxury.

The design style is a hybrid of **Minimalism** and **High-Contrast**, utilizing massive whitespace to frame content like a gallery. By removing all color, the focus shifts entirely to form, typography, and the rhythm of the grid. The emotional response should be one of "expensive silence"—calm, professional, and intellectually sharp.

## Colors

The palette is strictly achromatic. The primary color is a pure white, used for high-impact typography and essential actions. The foundation is built upon deep obsidian and pure black to create a sense of infinite depth.

- **Primary:** #ffffff — Used for primary text, active states, and focus elements.
- **Secondary:** #f5f5f5 — Used for subtle secondary text and high-contrast accents against dark backgrounds.
- **Surface (Deep Obsidian):** #131313 — Used for container backgrounds and section dividers.
- **Background (Pure Black):** #000000 — The root background color for all screens.
- **Accents:** Only varying shades of gray are permitted. No warm tones, golds, or yellows are allowed under any circumstances.

## Typography

The typographic system relies on the interplay between the editorial elegance of **Playfair Display** and the geometric precision of **Montserrat**. 

- **Display & Headlines:** Use Playfair Display. Large headings should use tight letter-spacing to feel like a high-end masthead.
- **Body & Interface:** Use Montserrat. Body text should be spaced generously to ensure readability against dark backgrounds.
- **Labels:** Use Montserrat in all-caps with increased letter-spacing for a technical, architectural feel on buttons and metadata.
- **Contrast:** Maintain high contrast by using pure white (#ffffff) for headlines and light gray (#f5f5f5) for body text to reduce eye strain.

## Layout & Spacing

The layout is built on a rigid 12-column grid. The philosophy is "Negative Space as a Feature," where large gaps between sections (stack-lg) are used to emphasize the importance of the content.

- **Desktop:** 12 columns with 24px gutters and wide 64px outer margins to create a "letterboxed" feel.
- **Tablet:** 8 columns with 24px gutters.
- **Mobile:** 4 columns with 16px gutters and 24px margins. Content should reflow vertically with significant padding between elements to maintain the premium aesthetic.
- **Alignment:** Use strict horizontal rules (1px lines in #131313) to separate sections rather than soft shadows.

## Elevation & Depth

In this monochromatic system, depth is achieved through **Tonal Layering** and **Crisp Outlines** rather than traditional shadows.

- **Surface Levels:** The base is #000000. Elements that sit "above" the base use #131313. 
- **Borders:** Use 1px solid borders in #f5f5f5 at low opacity (10-20%) to define shapes without breaking the dark aesthetic.
- **Z-Index:** High-elevation components (like modals) use a solid #131313 background with a 1px white border to pop against the black background.
- **Interaction:** Hover states are indicated by shifting from an outline to a solid white fill, creating a binary "on/off" feel.

## Shapes

The shape language is **Strictly Sharp (0)**. There are no rounded corners in the design system. This reinforces the architectural and structural theme.

- **Buttons & Inputs:** Hard 90-degree angles only.
- **Cards:** Defined by 1px borders or subtle tonal shifts with sharp corners.
- **Imagery:** All images should be cropped to sharp rectangles. Bounding boxes for icons must also follow the sharp-edge rule.

## Components

Components follow a "Binary" logic: they are either empty outlines or solid blocks of contrast.

- **Buttons:** 
  - *Primary:* Solid white background with black Montserrat Bold text (All-caps).
  - *Secondary:* 1px white border with white text, no background.
- **Inputs:** A single 1px white bottom-border or a full sharp rectangle outline. Placeholders should be in a mid-gray to distinguish from active input.
- **Lists:** Separated by 1px horizontal lines in #131313. No chevrons or arrows unless strictly necessary; use typographic weight to imply hierarchy.
- **Cards:** No shadows. Use #131313 as a background color to separate the card from the #000000 page background.
- **Chips:** Small, sharp-edged boxes with 1px borders and high-tracking uppercase labels.
- **Checkboxes/Radios:** Pure geometric squares (even for radios) to maintain the sharp-edged architectural theme. When selected, they fill solid white.