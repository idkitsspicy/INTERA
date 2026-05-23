---
name: Aurelian Industrial
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c8c6c5'
  on-secondary: '#303030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#d0cdcd'
  on-tertiary: '#303030'
  tertiary-container: '#b4b2b2'
  on-tertiary-container: '#454545'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474746'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  label-md:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
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
  margin-tablet: 32px
  margin-mobile: 20px
---

## Brand & Style

This design system embodies "Industrial Luxury"—a synthesis of raw, matte textures and refined metallic precision. It is designed for high-end automotive, luxury horology, or premium fintech platforms where authority and exclusivity are paramount. 

The aesthetic leverages **Minimalism** with a **Tactile** edge. It utilizes expansive dark surfaces to create a sense of infinite depth, punctuated by sharp, gold-accented focal points. The interface should feel heavy, permanent, and meticulously engineered. High-contrast interactions and metallic light-sculpting effects replace traditional colorful UI patterns to maintain a sophisticated, commanding presence.

## Colors

The palette is anchored by **Matte Black (#121212)**, providing a non-reflective, deep foundation that absorbs light. **Luxurious Gold (#D4AF37)** is used sparingly as a high-intent accent for primary actions, critical data, and decorative branding elements.

- **Surface Layers:** Use Charcoal (#1E1E1E) for secondary containers and Deep Gray (#2A2A2A) for tertiary elements like hover states or inset fields.
- **Typography & Icons:** Off-White (#F5F5F5) serves as the primary ink color to ensure legibility without the harshness of pure white. 
- **Accents:** Use a linear gradient for gold elements to simulate a metallic sheen: `linear-gradient(135deg, #D4AF37 0%, #C5A028 50%, #B8860B 100%)`.

## Typography

**Montserrat** is utilized across all levels to reinforce the architectural, geometric nature of the brand. 

- **Headlines:** Set in Bold or Semi-Bold. Use Gold for H1 and H2 levels when they represent "Hero" content. For standard page headers, use Off-White.
- **Body Text:** Always use Off-White (#F5F5F5) at 85-90% opacity to reduce eye strain against the matte black background.
- **Labels:** Labels and small captions should use "Gold" or "Off-White" with increased letter spacing and uppercase styling to evoke luxury watch face aesthetics.
- **Legibility:** Maintain a minimum contrast ratio of 7:1 for all functional text.

## Layout & Spacing

This design system follows a **Fixed Grid** philosophy on desktop to maintain a cinematic, curated feel. Content is centered within a 12-column grid with generous 64px outer margins to allow the matte black background to frame the UI.

- **Rhythm:** An 8px linear scale governs all spacing. 
- **Negative Space:** Use aggressive whitespace (64px+) between major sections to emphasize the premium nature of the content.
- **Adaptation:** On mobile, the grid collapses to 4 columns. Margins tighten to 20px, and vertical spacing is reduced by one step in the 8px scale to maintain density.

## Elevation & Depth

Depth is conveyed through **Tonal Layers** and **Low-Contrast Outlines** rather than traditional shadows. 

- **Surface tiers:** The base is #121212. Elevated cards sit at #1E1E1E. 
- **Outlines:** Instead of drop shadows, use 1px solid borders. For inactive states, use #2A2A2A. For active or hovered states, transition the border to the Gold (#D4AF37) palette.
- **Inner Glow:** For high-end "Gold" buttons or active cards, a very subtle, low-opacity (10%) gold inner glow can be used to simulate light reflecting off a metallic edge.

## Shapes

The shape language is **Soft (0.25rem)**, leaning toward the "Industrial" side of the narrative. Rectilinear forms with minimal rounding suggest precision-cut materials like carbon fiber or brushed steel. 

- **Standard Elements:** 4px radius for buttons, inputs, and small cards.
- **Large Containers:** 8px radius for main content areas or modal overlays.
- **Pill elements:** Only used for status indicators (e.g., "Active," "Live") to provide a distinct visual contrast from functional UI.

## Components

### Expanding Cards (Signature Component)
Cards feature a horizontal expansion behavior. In their default state, they show a vertical title in gold. On hover/active, they expand horizontally with a 300ms ease-in-out transition, revealing the content. The border transitions from Charcoal (#2A2A2A) to a 1px Gold (#D4AF37) stroke.

### Buttons
- **Primary:** Solid Gold background with Black (#121212) text. No border.
- **Secondary:** Transparent background with a 1px Gold border and Gold text.
- **States:** On hover, primary buttons should slightly brighten; secondary buttons should take on a 10% gold background tint.

### Input Fields
Inputs are "Flush" style: matte black background, 1px charcoal bottom border. On focus, the bottom border animates to Gold and the label (floating) shifts to Gold.

### Lists & Navigation
Navigation links use uppercase labels with 0.1em letter spacing. The active state is indicated by a 2px gold underline or a gold dot icon. List items are separated by subtle charcoal dividers (#2A2A2A).

### Selection Controls
Checkboxes and Radios are custom-styled. When checked, they feature a solid Gold fill with a Black checkmark/dot. The unselected state is a simple charcoal outline.