---
name: Enchanted Celebration
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#4d4635'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#7f7663'
  outline-variant: '#d0c5af'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#e9c349'
  secondary: '#795465'
  on-secondary: '#ffffff'
  secondary-container: '#fdcde1'
  on-secondary-container: '#795465'
  tertiary: '#b52045'
  on-tertiary: '#ffffff'
  tertiary-container: '#ff94a1'
  on-tertiary-container: '#8e002f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffd8e7'
  secondary-fixed-dim: '#e9bacd'
  on-secondary-fixed: '#2e1221'
  on-secondary-fixed-variant: '#5f3c4d'
  tertiary-fixed: '#ffd9dc'
  tertiary-fixed-dim: '#ffb2ba'
  on-tertiary-fixed: '#400010'
  on-tertiary-fixed-variant: '#910030'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system is built on the narrative of "The Bespoke Gala"—a digital environment that feels as curated and intentional as a luxury event. The brand personality is sophisticated yet vibrant, targeting high-end clientele who seek both professionalism and creative flair.

The design style merges **Minimalism** with **Glassmorphism**. We utilize heavy whitespace and a strict grid to maintain an air of high-fashion editorial, while using translucent "frosted" layers to mimic the airy quality of balloons and champagne bubbles. The emotional response should be one of "effortless enchantment": organized, premium, and celebratory.

## Colors
The palette is anchored by **Celebration Gold (#D4AF37)**, used sparingly for primary actions and signature accents to maintain a sense of luxury. **Soft Petal Pink (#F8C8DC)** serves as a gentle background or secondary element, while **Vibrant Berry (#990033)** provides a high-contrast focal point for deep emotional resonance.

**Sky Blue (#87CEEB)** is utilized specifically for playful accents, navigation highlights, or "joyful" micro-interactions. The background architecture relies on a **Warm White (#F9F7F2)** base, ensuring that photography—the true star of the design—appears vibrant and integrated rather than isolated.

## Typography
The typography strategy creates a high-contrast hierarchy between the "Bespoke" (Playfair Display) and the "Functional" (Montserrat). 

**Playfair Display** is used for all headlines and display text, evoking a literary, editorial feel. **Montserrat** is the workhorse for body copy and UI labels, providing a clean, geometric counterpoint that ensures the platform remains modern and readable. For mobile, display sizes scale down aggressively to maintain the "Enchanted" look without sacrificing the layout's structural integrity.

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous outside margins to simulate the feeling of a wide-format lifestyle magazine. On desktop, we utilize a 12-column grid with 24px gutters; on mobile, this collapses to a 4-column grid with 16px gutters.

The spacing rhythm is intentional and "airy." We use larger vertical padding (64px+) between sections to allow floral imagery and content blocks to "breathe." Content should rarely feel packed; instead, it should feel like a sequence of curated moments.

## Elevation & Depth
Depth in this design system is achieved through **Ambient Shadows** and **Glassmorphism**. Instead of harsh, black shadows, we use "Berry-tinted" or "Gold-tinted" soft shadows with high diffusion (e.g., 20px - 40px blur) at low opacity (8-12%). 

Surface tiers are created using Backdrop Blurs (15px - 25px) on semi-transparent white containers. This creates a "frosted champagne" effect that allows the vibrant colors of event photography to peek through the UI without compromising text legibility.

## Shapes
The shape language is defined by a **2xl roundedness** (1.5rem for standard cards). This softens the high-contrast typography and reinforces the "balloon" and "floral" theme. Interactive elements like buttons and chips should feel organic and approachable. Sharp corners are strictly avoided to maintain the "Enchanted" aesthetic.

## Components

### Buttons
Primary buttons use a **Celebration Gold** fill with white Montserrat Medium text. Secondary buttons utilize a **Soft Petal Pink** fill or a ghost style with a 1px Gold border. All buttons feature high-roundedness (1.5rem+) to appear soft and inviting.

### Cards
Cards are the primary container for portfolio items. They must feature a subtle 1px border in a slightly darker neutral tint and a soft ambient shadow. Imagery within cards should have a subtle zoom-in hover effect to create a feeling of immersion.

### Inputs & Selection
Input fields use the **Warm White** background with a subtle **Soft Petal Pink** focus ring. Checkboxes and Radios are styled as "circular bubbles" using the **Sky Blue** accent to reflect the balloon motif.

### Additional Components
- **The "Curtain" Loader:** A custom transition using a sheer, Berry-colored overlay that slides like a stage curtain between pages.
- **Image Carousels:** Large, edge-to-edge carousels with "floating" navigation arrows housed in glassmorphic circles.