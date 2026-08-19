---
name: Academic Excellence System
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
  on-surface-variant: '#44474e'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#465f88'
  primary: '#000a1e'
  on-primary: '#ffffff'
  primary-container: '#002147'
  on-primary-container: '#708ab5'
  inverse-primary: '#aec7f6'
  secondary: '#aa304f'
  on-secondary: '#ffffff'
  secondary-container: '#fd6f8c'
  on-secondary-container: '#6f0028'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca830'
  on-tertiary-container: '#4f3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#aec7f6'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#ffd9dd'
  secondary-fixed-dim: '#ffb2bd'
  on-secondary-fixed: '#400013'
  on-secondary-fixed-variant: '#8a1538'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Source Serif 4
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '600'
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
  label-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
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

The design system is engineered to evoke a sense of heritage, intellectual rigor, and institutional stability. It targets a sophisticated audience of prospective students, faculty, and global researchers who value tradition as a foundation for innovation. 

The visual style is **Corporate / Modern** with a strong **Minimalist** influence. It prioritizes clarity and whitespace to allow scholarly content to breathe, while using high-quality editorial touches to signal prestige. The emotional response should be one of quiet confidence and unshakeable trust. All UI elements should feel intentional, structured, and permanent.

## Colors

The palette is anchored by **Oxford Blue** (#002147), representing authority and history. **Heritage Burgundy** (#8A1538) is used as a secondary accent for call-to-actions and academic highlights, creating a warm, sophisticated contrast. **Scholar’s Gold** (#D4AF37) is reserved for high-prestige elements, such as honors, crests, or special recognitions.

Backgrounds primarily utilize **Pure White** for content areas and **Gallery Gray** (#F8F9FA) for structural sections to maintain a clean, organized appearance. Text should utilize a high-contrast off-black (#1A1A1A) to ensure maximum readability and a premium feel.

## Typography

This design system employs a pairing of **Source Serif 4** for headlines and **Work Sans** for functional text. This combination bridges the gap between traditional academic publishing and modern digital accessibility.

- **Headlines:** Use serif styles to emphasize authority. Large displays should use a slight negative letter-spacing to appear tighter and more "editorial."
- **Body:** Work Sans provides a neutral, highly legible foundation for long-form research papers and course descriptions.
- **Labels:** Small labels and navigational elements should use uppercase Work Sans with increased tracking to maintain clarity at small scales.

## Layout & Spacing

The design system utilizes a **12-column fixed grid** for desktop, ensuring content remains readable and centered on ultra-wide monitors. On mobile, it transitions to a fluid 4-column grid.

- **Rhythm:** All spacing is based on an 8px base unit. 
- **Margins:** Generous outer margins (64px on desktop) are critical to maintaining the "prestigious" feel, preventing the UI from appearing cluttered.
- **Hierarchy:** Use larger vertical gaps (80px+) between major sections to signal distinct topical shifts (e.g., from "Admissions" to "Global Research").

## Elevation & Depth

Elevation is conveyed through **Tonal Layers** and **Low-Contrast Outlines** rather than aggressive shadows. This keeps the interface feeling "flat" and architectural, like a printed academic journal.

- **Surface Tiers:** Use subtle background shifts (White to Light Gray) to separate content modules.
- **Borders:** Use 1px solid strokes in a light gray (#E0E0E0) for card containers and input fields.
- **Shadows:** When necessary for functional depth (e.g., dropdown menus), use a single, highly diffused "Ambient Shadow" (0px 4px 20px rgba(0, 0, 0, 0.05)) to avoid a heavy, "app-like" appearance.

## Shapes

The shape language is disciplined and conservative. A **Soft** roundedness (4px) is applied to buttons and form fields to provide just enough modernity without losing the professional, "squared-off" rigor associated with institutional architecture.

- **Hard Edges:** Large imagery and section containers should remain at 0px radius to maintain a formal, structural look.
- **Interactive Elements:** Buttons and tags use the `rounded-sm` (4px) or `rounded-md` (8px) tokens to distinguish them from static structural elements.

## Components

- **Buttons:** Primary buttons use the Oxford Blue background with white text. Secondary buttons use a Burgundy outline. Interaction states should be subtle (e.g., a slight darken of the background color).
- **Cards:** White backgrounds with a 1px border. Do not use shadows. Headlines within cards should be the Source Serif 4 "headline-sm."
- **Input Fields:** Squared corners (4px) with a subtle gray border. Focus states should use a 2px Oxford Blue bottom-border to mimic a formal signature line.
- **Chips/Tags:** Used for academic categories or departments. Small, uppercase Work Sans labels with a very light Oxford Blue tinted background.
- **Lists:** Bulleted lists should use custom square markers in Burgundy to match the institutional aesthetic.
- **Academic Stats:** A specialized component for displaying data (e.g., "98% Placement Rate") using large Source Serif 4 numbers in Burgundy.