---
name: Hyper-Minimalist Portfolio
colors:
  surface: '#fcf8f8'
  surface-dim: '#ddd9d9'
  surface-bright: '#fcf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c8'
  surface-tint: '#5d5f5f'
  primary: '#5d5f5f'
  on-primary: '#ffffff'
  primary-container: '#ffffff'
  on-primary-container: '#747676'
  inverse-primary: '#c6c6c7'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dcdddd'
  on-secondary-container: '#5f6161'
  tertiary: '#5d5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffffff'
  on-tertiary-container: '#757676'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-xl:
    fontFamily: Hanken Grotesk
    fontSize: 80px
    fontWeight: '300'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '300'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.2em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style
The design system is rooted in the philosophy of "Less is More," drawing heavily from high-end editorial design and Swiss International Style. It is designed to act as a silent frame for creative work, emphasizing precision, intentionality, and breathing room. 

The aesthetic is ultra-modern and hyper-minimalist. By removing all non-essential decorative elements, the design system directs absolute focus toward content and typography. It prioritizes clarity over ornamentation, using purposeful layout structures and hairline dividers to create a sense of architectural order. The intended emotional response is one of calm authority, sophistication, and meticulous attention to detail.

## Colors
The palette is monochromatic and restrained, utilizing subtle tonal shifts to define hierarchy. 

- **Primary:** Pure white (#FFFFFF) serves as the expansive base for the layout, providing the "infinite" canvas required for high-end editorial aesthetics.
- **Secondary:** A soft gray (#F5F5F5) is used for subtle container backgrounds or large-scale section differentiation without breaking the minimalist flow.
- **Tertiary:** A slightly deeper gray (#E5E5E5) is reserved exclusively for functional hairlines and structural borders.
- **Typography:** Deep charcoal (#1A1A1A) provides high-contrast legibility while appearing softer and more sophisticated than pure black.

## Typography
Typography is the primary visual driver of this design system. It utilizes Hanken Grotesk to achieve a sharp, contemporary look. 

The system relies on extreme weight contrasts—pairing light, oversized display type with bold, compact labels. Generous letter spacing is applied to uppercase labels to evoke a luxury, gallery-like feel. Line heights are kept airy to ensure the "breathing room" mentioned in the layout philosophy is maintained within the text blocks themselves. Use `display-xl` sparingly for maximum impact.

## Layout & Spacing
The layout follows a fixed-grid model centered on a 12-column system for desktop. However, the defining characteristic is the extreme use of whitespace. Margins are significantly larger than standard web practices to force focus onto the center-aligned or offset content.

Section transitions should be marked by wide vertical gaps (`section-gap`) rather than background color changes. Thin, 1px hairlines (#E5E5E5) should be used horizontally to separate content groups or vertically to define edge boundaries in a way that feels like a printed architectural plan. Elements should never feel "crowded"; if in doubt, increase padding.

## Elevation & Depth
This design system rejects shadows and traditional 3D depth. Elevation is communicated solely through tonal layering and flat, low-contrast outlines.

The hierarchy of surfaces is as follows:
- **Level 0 (Base):** #FFFFFF.
- **Level 1 (Subtle Insets/Cards):** #F5F5F5 background with no border.
- **Level 2 (Active/Interactive):** #FFFFFF background with a 1px #E5E5E5 hairline border.

Depth is implied by the overlap of content and the use of the "thin hairline" which acts as a structural ghost border. There is no use of blurs or skeuomorphism.

## Shapes
The shape language is strictly geometric and sharp. All containers, buttons, and image masks use 0px border-radius. This reinforces the "precision" and "architectural" themes of the design system, creating a rigid, high-end editorial look that contrasts with the soft grays of the palette.

## Components
- **Buttons:** Primary buttons are solid #1A1A1A with #FFFFFF text, sharp corners, and `label-caps` typography. Secondary buttons are transparent with a 1px #E5E5E5 border. Hover states should involve a simple opacity shift or a fill-color swap—no movement or shadow.
- **Input Fields:** Minimalist under-lines only (1px hairline) rather than full boxes. The label sits above in `label-caps`.
- **Chips/Labels:** Small, sharp-edged rectangles with #F5F5F5 backgrounds and `label-caps` typography.
- **Cards:** Defined not by shadows, but by 1px hairlines or simple shifts to #F5F5F5 backgrounds. Images within cards must always be full-bleed to the sharp container edges.
- **Lists:** Separated by horizontal 1px hairlines that span the full width of the container. 
- **Pagination/Nav:** Use numerical indicators and `label-caps`. Navigation items should have generous horizontal padding to maintain the "editorial" rhythm.