---
name: Lumière d'Or
colors:
  surface: '#16130b'
  surface-dim: '#16130b'
  surface-bright: '#3d392f'
  surface-container-lowest: '#110e07'
  surface-container-low: '#1f1b13'
  surface-container: '#231f17'
  surface-container-high: '#2d2a21'
  surface-container-highest: '#38342b'
  on-surface: '#eae2d4'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#eae2d4'
  inverse-on-surface: '#343027'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#e6c092'
  on-secondary: '#432c0a'
  secondary-container: '#5c421e'
  on-secondary-container: '#d4af82'
  tertiary: '#bfcdff'
  on-tertiary: '#082b72'
  tertiary-container: '#97b0ff'
  on-tertiary-container: '#254188'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffddb6'
  secondary-fixed-dim: '#e6c092'
  on-secondary-fixed: '#2a1800'
  on-secondary-fixed-variant: '#5c421e'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#27438a'
  background: '#16130b'
  on-background: '#eae2d4'
  surface-variant: '#38342b'
  midnight-void: '#0A0A0A'
  starlight-white: '#F8F5F0'
  french-gold: '#D4AF37'
  brushed-brass: '#BA976C'
  charcoal-surface: '#111111'
  gold-glow: rgba(212, 175, 55, 0.2)
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  margin-desktop: 64px
  margin-mobile: 16px
  gutter: 24px
  section-gap: 120px
  unit: 4px
---

## Brand & Style

Lumière d'Or is a luxury lighting design system that embodies "Cinematic Opulence." It targets high-net-worth individuals and interior designers looking for timeless elegance and artisanal craftsmanship. 

The aesthetic is a sophisticated blend of **Minimalism** and **Glassmorphism**, set against a deep, dramatic backdrop. It uses heavy whitespace (or "darkspace") to let product photography breathe, combined with high-contrast metallic accents. The visual narrative is one of warmth, exclusivity, and precision, evoking the feeling of a private gallery at midnight. Elements should feel etched, radiant, and substantial.

## Colors

The palette is anchored by **Midnight Void** (#0A0A0A) to provide an infinite depth that allows light-based products to "pop." 

- **Primary (French Gold):** The hero color. Used for key branding, primary actions, and decorative accents. It represents the physical material of the products.
- **Secondary (Brushed Brass):** A muted metallic used for supplementary information and hover states to provide tonal variety without competing with the primary gold.
- **Neutral/Surface:** A range of ultra-dark warm grays (Charcoal Surface) are used to create subtle container separation. 
- **Typography:** **Starlight White** (#F8F5F0) is used for high-readability headers, while primary gold and muted brass are used for labels and supporting text.

## Typography

The system utilizes a classic "Serif for Headlines, Sans for Utility" pairing.

- **Playfair Display** provides a literary, high-fashion feel. It is used for all major headings and display text. Use tighter letter-spacing for large display sizes to maintain a prestigious look.
- **Manrope** offers a clean, technical contrast. It is optimized for legibility in body copy and provides a structured, modern feel for technical specifications and labels.
- **Label Caps** are a critical stylistic element, always rendered in uppercase with generous tracking (0.1em+) to denote luxury "signage" within the UI.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain strict editorial control, transitioning to a fluid model for mobile devices.

- **Vertical Rhythm:** Sections are separated by a generous `120px` gap (Section-Gap) to emphasize exclusivity and prevent visual clutter.
- **Desktop Grid:** A 12-column grid with `24px` gutters. Content is typically centered or arranged in asymmetrical "Bento" style configurations.
- **Margins:** Large `64px` side margins on desktop create a frame-like effect for the content.
- **Hierarchy:** Use spacing to group related technical data, such as the 1:1 pairing of labels and values in specification lists.

## Elevation & Depth

Depth is primarily communicated through **Glassmorphism** and **Light Emission** rather than traditional shadows.

- **Tonal Layering:** The base is Midnight Void. Secondary surfaces (cards, info boxes) use **Charcoal Surface** (#111111).
- **Glassmorphism:** Elements like floating info cards or feature blocks use an 80% opacity fill with a `blur(12px)` backdrop to create a "frosted obsidian" look.
- **Glow Effects:** Interactive elements and hero components use "Bloom." Shadows are replaced with diffused gold-tinted glows (`rgba(212, 175, 55, 0.2)`) to simulate the product's light emission.
- **Etched Borders:** Instead of heavy shadows, use 1px borders in `french-gold/20` or `white/5` to define edges sharply.

## Shapes

The shape language is primarily **Sharp and Structural**. 

- **Primary Radius:** A subtle `0.25rem` (4px) radius is the standard for buttons and images, providing a hint of softness without losing the architectural precision.
- **Decorative Elements:** Use thin, horizontal gold lines (1px) as dividers or to lead the eye. 
- **Icons:** Use thin-stroke (weight 100-300) Material Symbols to match the refined weight of the typography.

## Components

- **Buttons:** 
    - *Primary:* Solid French Gold fill with Midnight Void text. No border. Subtle gold glow on hover.
    - *Secondary/Outline:* Transparent background, French Gold 1px border. Transitions to solid gold on hover.
- **Cards (Glass):** Dark semi-transparent background with backdrop blur. Borders should be a very faint gold or white.
- **Navigation:** Transparent backgrounds for top-level nav to allow hero imagery to bleed through. Active links are indicated by a 1px French Gold bottom border.
- **Specification Lists:** Minimalist rows with a 1px border-bottom (`white/10`). Labels in uppercase `label-caps`, values in `body-lg` bold.
- **Floating Badges:** Small, high-contrast labels used to call out specific features (e.g., "Premium Crystal"), often paired with a thin-line icon.