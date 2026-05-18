---
name: Artisanal Purity
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#524345'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#847374'
  outline-variant: '#d6c2c3'
  surface-tint: '#874e56'
  primary: '#874e56'
  on-primary: '#ffffff'
  primary-container: '#d18d96'
  on-primary-container: '#58272f'
  inverse-primary: '#fcb3bc'
  secondary: '#596245'
  on-secondary: '#ffffff'
  secondary-container: '#dde7c2'
  on-secondary-container: '#5f684b'
  tertiary: '#645e4b'
  on-tertiary: '#ffffff'
  tertiary-container: '#a79f89'
  on-tertiary-container: '#3b3625'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9dd'
  primary-fixed-dim: '#fcb3bc'
  on-primary-fixed: '#360c15'
  on-primary-fixed-variant: '#6b373f'
  secondary-fixed: '#dde7c2'
  secondary-fixed-dim: '#c1cba8'
  on-secondary-fixed: '#171e07'
  on-secondary-fixed-variant: '#424a2f'
  tertiary-fixed: '#ece2c9'
  tertiary-fixed-dim: '#cfc6ae'
  on-tertiary-fixed: '#201b0c'
  on-tertiary-fixed-variant: '#4c4634'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  title-md:
    fontFamily: Libre Caslon Text
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 28px
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
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style
The brand personality is rooted in the intersection of nature and self-care. It is gentle, transparent, and sophisticated, targeting a conscious consumer who values craftsmanship and organic wellness. The UI evokes a sense of calm, mimicking the tactile experience of a premium apothecary.

The design style is **Modern Minimalism with Tactile accents**. It leverages significant whitespace to emphasize the purity of the ingredients, while using soft, organic shapes and subtle depth to mirror the physical form of the heart-shaped soaps. The aesthetic is clean and premium, avoiding cluttered layouts in favor of an editorial, boutique-like presentation.

## Colors
The palette is a curated selection of botanical and earth tones that feel natural and inviting. 

- **Primary (Rose/Blush):** Derived from the central floral logo, used for key actions, highlights, and emotional connectivity.
- **Secondary (Sage/Olive):** Represents the organic, plant-based nature of the ingredients (Aloe, Calendula). Used for supportive elements and brand accents.
- **Tertiary (Cream/Sand):** A warm, soft base that provides a more tactile feel than pure white, used for container backgrounds and section dividers.
- **Neutral (Parchment):** An off-white used as the primary canvas color to reduce eye strain and enhance the premium feel.

Text should be rendered in a deep charcoal-olive rather than pure black to maintain the soft, organic visual harmony.

## Typography
The typography pairing balances traditional craftsmanship with modern readability. 

**Libre Caslon Text** is used for all headlines and display elements. Its classic serif proportions and elegant curves reflect the artisanal nature of the products and provide a literary, premium feel.

**Work Sans** serves as the functional workhorse for body copy and UI labels. It is clean, exceptionally legible at small sizes, and its slightly wider apertures provide a friendly, open feel that complements the more structured serif. Use increased line-height (1.5x - 1.6x) for body text to maintain the "airy" feel of the design system.

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous padding to ensure the UI never feels cramped. 

- **Desktop:** A 12-column grid with a 1200px max-width. Large 40px margins allow the content to "breathe" against the edges of the viewport.
- **Mobile:** A simple 2-column or 4-column grid with 16px margins. Content should reflow vertically, but product cards can be displayed in a side-by-side "masonry-lite" style to showcase more soap varieties.

Spacing follows an 8px base unit. Use larger spacing increments (e.g., 64px or 80px) between major sections to reinforce the sense of "luxury" and "calm."

## Elevation & Depth
Depth is created through **Tonal Layers** and **Ambient Shadows** rather than harsh outlines.

- **Surfaces:** Use the Tertiary (Cream) or Secondary (Sage) colors at very low opacities (5-10%) to create subtle background blocks for different content zones.
- **Shadows:** Shadows are extremely soft and diffused. Use a large blur radius (20px+) with low opacity (0.05) tinted with the Primary rose color to create a "glow" rather than a dark drop-shadow. This makes the heart-shaped soaps appear as if they are resting gently on a soft surface.
- **Interaction:** On hover, elements should lift slightly with a more pronounced ambient shadow to mimic the physical act of picking up a soap.

## Shapes
The shape language is organic and soft, directly inspired by the heart-shaped artisanal soaps. 

Standard components (buttons, input fields) use a 0.5rem (8px) radius. Larger containers, such as product image cards or promotional banners, use the `rounded-xl` (1.5rem / 24px) setting to emphasize the friendly and safe nature of the brand. Avoid sharp 90-degree corners entirely to maintain a "hand-crafted" aesthetic.

## Components

- **Buttons:** Primary buttons use a solid Blush fill with white or deep-olive text. Secondary buttons should be "ghost" style with a Sage border and text. All buttons feature high horizontal padding (at least 24px) for a balanced, spacious look.
- **Cards:** Product cards are the centerpiece. Use a very light Cream background, the `rounded-xl` shape, and a subtle ambient shadow. The product name should be in `title-md` (Serif).
- **Chips/Tags:** Used for ingredients (e.g., "Vitamin C", "Aloe Vera"). These should be small, pill-shaped, and use the Secondary Sage color at a low opacity with dark text.
- **Input Fields:** Minimalist design with a soft 1px border in a muted Sand color. Focus states transition the border to the Primary Blush color with a soft outer glow.
- **Lists:** Ingredient lists should use custom floral icons (derived from the logo) as bullets to reinforce the brand identity.
- **Specialty Component - Ingredient Story:** A dedicated card layout that pairs a high-resolution macro image of a raw ingredient (like oats or coconut) with a serif-based description.