---
name: Coastal Editorial
colors:
  surface: '#fff8f6'
  surface-dim: '#f0d4cf'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ee'
  surface-container: '#ffe9e5'
  surface-container-high: '#ffe2dd'
  surface-container-highest: '#f9dcd7'
  on-surface: '#271815'
  on-surface-variant: '#5b403c'
  inverse-surface: '#3e2c29'
  inverse-on-surface: '#ffedea'
  outline: '#8f706a'
  outline-variant: '#e4beb7'
  surface-tint: '#b82111'
  primary: '#b41e0e'
  on-primary: '#ffffff'
  primary-container: '#d83925'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a7'
  secondary: '#9d4132'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b77'
  on-secondary-container: '#752317'
  tertiary: '#00647e'
  on-tertiary: '#ffffff'
  tertiary-container: '#007f9e'
  on-tertiary-container: '#fafdff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a7'
  on-primary-fixed: '#400100'
  on-primary-fixed-variant: '#920700'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#ffb4a7'
  on-secondary-fixed: '#400200'
  on-secondary-fixed-variant: '#7e2a1d'
  tertiary-fixed: '#b9eaff'
  tertiary-fixed-dim: '#6cd3f9'
  on-tertiary-fixed: '#001f29'
  on-tertiary-fixed-variant: '#004d62'
  background: '#fff8f6'
  on-background: '#271815'
  surface-variant: '#f9dcd7'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 60px
  section-gap: 120px
---

## Brand & Style

This design system captures the essence of a premium beach-club retreat. The brand personality is "Sophisticated Relaxation"—a blend of high-end editorial aesthetics and the raw, organic warmth of the San Isidro riverside. It targets an upscale audience seeking an escape that feels both curated and effortless.

The UI style is a fusion of **Minimalism** and **Tactile Organicism**. It prioritizes high-quality, full-bleed imagery that evokes a sense of place. The interface utilizes generous whitespace to allow content to "breathe," mirroring the open horizons of a coastal setting. Elements are characterized by soft, sweeping curves and subtle textural cues, avoiding any rigid or "corporate" structures. The emotional response should be one of immediate decompression, warmth, and quiet luxury.

## Colors

The palette is rooted in the natural materials and vivid accents of the beach club environment.
- **Primary Vermillion (#DB3B27):** A more intense, sun-drenched red-orange used for high-priority calls to action and interactive highlights, echoing a vibrant sunset.
- **Earthy Rose (#BD5948) & Deep Atlantic (#008FB2):** These serve as secondary brand colors. The muted rose provides organic warmth, while the deep blue-teal grounds the design in the water.
- **Taupe Driftwood (#89726E):** The primary neutral, used for structural elements and text to provide a sophisticated, weathered organic feel.

This system is strictly Light Mode to maintain the airy, sun-drenched atmosphere.

## Typography

The typography strategy balances characterful expression with functional clarity. 

**Bricolage Grotesque** is selected for headlines. Its unique, slightly organic, and "crafted" letterforms provide an editorial, boutique feel that mirrors a custom-branded menu or magazine. It should be used with tight tracking in larger sizes to emphasize its personality.

**DM Sans** provides a clean, understated counterpoint for body text and navigation. Its geometric but low-contrast nature ensures readability against textured backgrounds. 

**Label-caps** should be used for small metadata, like "San Isidro, AR" or "Available Now," to add a layer of sophisticated organization.

## Layout & Spacing

The layout philosophy is **Fluid Editorial**. It uses a 12-column grid for desktop but encourages elements to break the grid or span full-bleed to create a dynamic, non-templated look.

- **Generous Gaps:** Section vertical spacing is intentionally large (120px+) to evoke the luxury of space.
- **Asymmetric Balance:** Combine full-bleed hero images with inset text containers to create visual interest.
- **Mobile Reflow:** On mobile, margins tighten to 20px, and large display type scales down aggressively to maintain the "beach-side reading" legibility. 
- **Safe Areas:** Ensure interactive elements are never cramped; buttons should have a minimum of 64px vertical breathing room from neighboring text blocks.

## Elevation & Depth

Depth in this design system is created through **Tonal Layering** and **Soft Ambient Shadows**. 

- **Surface Stacking:** Use soft tonal shifts between surfaces to create stacked depth. Lighter containers on slightly tinted backgrounds create a natural depth without needing heavy borders.
- **Shadows:** Shadows are highly diffused and tinted with the neutral **Taupe Driftwood** (#89726E) at 5-10% opacity. Avoid gray or black shadows; the goal is to make elements look like they are resting on a sunlit surface.
- **Glassmorphism (Subtle):** Use a high-radius backdrop blur (20px+) with a semi-transparent surface fill for navigation bars or overlay menus. This maintains the "airy" feel while ensuring text legibility over photography.

## Shapes

The shape language is dominated by **Extra-Large Roundedness**. 

- **Containers & Cards:** Use a standard `rounded-2xl` (1rem/16px) for cards, increasing to `rounded-3xl` (1.5rem/24px) for major section containers or image carousels.
- **Dividers:** Instead of standard 1px gray lines, use "Rattan Dividers"—thin, 1px lines using the neutral Taupe (#89726E) with a very subtle, repeating dashed pattern (e.g., 8px dash, 4px gap) to mimic natural fibers.
- **Interactive Elements:** Buttons and input fields follow the `rounded-lg` (1rem) pattern to feel soft to the touch.

## Components

### Buttons
- **Primary:** Background Vermillion (#DB3B27), text White. High-pill shape, bold weight.
- **Secondary:** Transparent background, 1.5px Taupe border, Taupe text.
- **Hover States:** Soft scale-up (1.02x) and a slight increase in shadow diffusion. No aggressive color shifts.

### Cards
- **Editorial Cards:** No borders. Backgrounds utilize soft tonal neutrals. Images should always have a top-rounded corner or a full-bleed aspect ratio within the card.

### Inputs & Selects
- Background should be a slightly tinted neutral or transparent with a bottom-only border (Taupe) to keep the UI "light."
- Focus states use the Deep Atlantic (#008FB2) for the border color.

### Lists
- Use the "Rattan Divider" between list items.
- Bullet points should be replaced with custom organic shapes (e.g., a small Atlantic blue leaf or a simple circle in Vermillion).

### Navigation
- A floating "Island" navigation bar at the top, utilizing backdrop blur and a `rounded-xl` shape, keeping the edges of the screen clear for the background imagery.