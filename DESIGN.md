---
name: Neo-Sabor Brutalist
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#5a413a'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#8e7069'
  outline-variant: '#e2bfb6'
  surface-tint: '#b02e02'
  primary: '#831f00'
  on-primary: '#ffffff'
  primary-container: '#d83900'
  on-primary-container: '#ffc9ba'
  inverse-primary: '#ffb5a0'
  secondary: '#4b6700'
  on-secondary: '#ffffff'
  secondary-container: '#b6f300'
  on-secondary-container: '#4f6c06'
  tertiary: '#454544'
  on-tertiary: '#ffffff'
  tertiary-container: '#5d5c5b'
  on-tertiary-container: '#d7d5d3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a0'
  on-primary-fixed: '#3b0900'
  on-primary-fixed-variant: '#872000'
  secondary-fixed: '#b8f600'
  secondary-fixed-dim: '#b0d368'
  on-secondary-fixed: '#141f00'
  on-secondary-fixed-variant: '#384e00'
  tertiary-fixed: '#e5e2e0'
  tertiary-fixed-dim: '#c8c6c4'
  on-tertiary-fixed: '#1c1c1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
  dark-neutral: '#1a1a1a'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Archivo Narrow
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 16px
  label-sm:
    fontFamily: Archivo Narrow
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 40px
  container-max: 1280px
  section-padding: 80px
---

## Brand & Style
The brand personality is energetic, loud, and unapologetically bold, targeting a youthful audience that values high-impact street food and artisanal treats. It blends the raw structural intensity of **Neo-Brutalism** with a vibrant, high-contrast color palette. 

The emotional response should be one of "controlled chaos" and "appetite-inducing energy." The UI utilizes heavy black borders, hard drop shadows (no blur), and massive, uppercase typography to create a physical, tactile sense of space. It rejects traditional digital polish in favor of a "printed flyer" aesthetic that feels immediate and authentic.

## Colors
The palette is built on high-saturation "Fidelity" tones. 
- **Primary (#ad2c00):** A deep, cooked red used for the "Salado" (savory) side of the brand and primary calls to action.
- **Secondary (#4b6700):** A vibrant, zesty green representing "Guanahani" (sweet/natural) and artisanal freshness.
- **Backgrounds:** The design uses a tiered neutral system, starting with a clean off-white (#f8f9fa) and moving to darker, high-contrast surfaces (#1a1a1a) for footers to ground the experience.
- **Black Accents:** Pure black or near-black (#191c1d) is used for all structural borders and hard shadows to maintain the brutalist signature.

## Typography
The typographic system uses a three-font stack to differentiate brand hierarchy:
- **Display:** *Plus Jakarta Sans* in Extra Bold weights. It is frequently used in uppercase with tight letter-spacing for a "shouting" headline effect.
- **Body:** *Work Sans* provides a neutral, highly readable counterpoint to the aggressive headlines, maintaining clarity in descriptions.
- **Utility:** *Archivo Narrow* is used for labels, badges, and micro-copy, where horizontal space efficiency is required without sacrificing the bold brand voice.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop, centering content within a 1280px container, and transitions to a fluid model for mobile with 20px side margins.

Spacing is generous between sections (80px) to prevent the heavy borders from feeling cluttered. The "Split-Screen" pattern is a core layout device, used in the hero and major category headers to visually separate the "Salado" and "Dulce" offerings. 

Elements like cards and buttons use a consistent 8px base unit for internal padding and rhythm.

## Elevation & Depth
Depth is strictly non-mimetic. Instead of using light physics (soft shadows), this system uses **Structural Brutalism**:
- **Hard Shadows:** All interactive elements and containers use a 4px or 6px offset shadow with 100% opacity (#191c1d).
- **Hard Borders:** A consistent 2px black border defines all surface boundaries.
- **Interactive State:** Hovering over an element increases the shadow offset (e.g., 6px) and moves the element slightly (Translate-Y), while clicking "flattens" the element by removing the shadow and resetting the transform, mimicking a physical button press.

## Shapes
The shape language is primarily **Soft-Brutalist**. While the borders are heavy and the shadows are hard, most containers use a 0.25rem (4px) corner radius to prevent the UI from feeling dangerously sharp. Larger containers like the footer may use more pronounced rounding (top-xl / 12px) to introduce a modern, friendly touch amidst the raw styling.

## Components
- **Buttons:** Must have a 2px border and a 4px hard shadow. Use uppercase `label-bold` or `headline-md` typography. Primary buttons use the brand red; secondary use the brand green.
- **Cards:** White or tinted surfaces with 2px borders and hard shadows. Content should be padded with `base * 2` (16px).
- **Badges:** Use `Archivo Narrow` on high-contrast backgrounds (like `secondary-fixed`) with 2px borders.
- **Marquee:** A key component for urgency; uses `display-lg` typography on a high-visibility color strip (Green/Yellow).
- **Icons:** Use *Material Symbols Outlined* with a weight of 400. Icons are often enclosed in circular or square containers with 2px borders and hard shadows.
- **Input Fields:** Thick 2px borders, no soft shadows, and high-contrast focus states (background color change rather than subtle glow).