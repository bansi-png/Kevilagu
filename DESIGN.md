---
name: Artisanal Elegance
colors:
  surface: '#fff8f4'
  surface-dim: '#e0d9d4'
  surface-bright: '#fff8f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf2ed'
  surface-container: '#f4ece7'
  surface-container-high: '#eee7e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#594045'
  inverse-surface: '#33302d'
  inverse-on-surface: '#f7efea'
  outline: '#8d6f75'
  outline-variant: '#e1bec4'
  surface-tint: '#b90c55'
  primary: '#9b0044'
  on-primary: '#ffffff'
  primary-container: '#c2185b'
  on-primary-container: '#ffd9df'
  inverse-primary: '#ffb1c2'
  secondary: '#ab2c5d'
  on-secondary: '#ffffff'
  secondary-container: '#fd6c9c'
  on-secondary-container: '#6e0034'
  tertiary: '#6c3f50'
  on-tertiary: '#ffffff'
  tertiary-container: '#875668'
  on-tertiary-container: '#ffd8e4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9df'
  primary-fixed-dim: '#ffb1c2'
  on-primary-fixed: '#3f0018'
  on-primary-fixed-variant: '#8f003f'
  secondary-fixed: '#ffd9e1'
  secondary-fixed-dim: '#ffb1c5'
  on-secondary-fixed: '#3f001b'
  on-secondary-fixed-variant: '#8b0e45'
  tertiary-fixed: '#ffd9e4'
  tertiary-fixed-dim: '#f2b6cb'
  on-tertiary-fixed: '#330f1f'
  on-tertiary-fixed-variant: '#65394b'
  background: '#fff8f4'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
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
  margin-desktop: 64px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
  section-gap: 80px
---

## Brand & Style

This design system is crafted for an audience that values heritage, craftsmanship, and sophisticated luxury. The brand personality is poised and maternal yet vibrantly artistic, reflecting the intricate handiwork of Gujarati embroidery. 

The visual style leans into **Minimalism** with a **Tactile** edge. We prioritize generous whitespace to allow product photography to breathe, ensuring the interface never feels cluttered. The "flawless" aesthetic is achieved through high-fidelity rendering of textures and subtle nods to physical embroidery through soft shadows and layered surfaces. Accessibility is the core pillar, ensuring that the interface remains effortless to navigate for a demographic that prioritizes clarity and high visual contrast.

## Colors

The palette is rooted in warm, earthen neutrals and rich berry tones. 

- **Primary (Deep Raspberry):** Reserved for primary calls to action and critical brand markers. It provides a high-contrast anchor against the light backgrounds.
- **Secondary & Tertiary (Soft Pink & Blush):** Used for decorative accents, secondary buttons, and subtle container backgrounds to create a soft, feminine hierarchy.
- **Background (Warm Cream):** Replaces harsh whites to provide a more premium, "paper-like" feel that reduces eye strain.
- **Typography & Contrast (Deep Plum):** Used for all body text and iconography to ensure WCAG AAA compliance against the cream background. This plum tone is warmer and more sophisticated than pure black or grey.

## Typography

This design system employs a high-contrast typographic pairing to balance tradition with extreme legibility.

- **Headings:** We use **Playfair Display**, a sophisticated serif with high stroke contrast. This evokes the feeling of high-end fashion editorials and traditional luxury. 
- **Body & UI:** We use **Atkinson Hyperlegible Next**, specifically chosen to support women 45+. Its distinctive character shapes prevent common letter-form confusion, ensuring maximum readability even at smaller sizes or lower light levels.
- **Sizing Strategy:** Base body text is set to a generous 18px-20px to accommodate varying visual needs without requiring the user to zoom.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop to maintain a curated, boutique-like presentation. 

- **Grid:** A 12-column system with wide gutters (24px) creates an airy feel. 
- **Rhythm:** We utilize a 8px linear scale. For a "premium" feel, we lean towards the higher end of the scale (using 48px and 80px gaps) to prevent the UI from feeling crowded.
- **Negative Space:** Generous margins (64px) on desktop frame the content like a piece of jewelry in a display case. Vertical stacking is intentional and rhythmic, guiding the eye slowly through the artisanal story.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and tonal layering. 

- **Shadow Character:** Shadows are extremely soft, using the Deep Plum (#7A3B5A) as a shadow tint rather than pure black. This maintains warmth. Shadows should have a large blur radius (20px+) and very low opacity (5-8%).
- **Tonal Layers:** The primary background is Warm Cream. Interactive cards and modals use the Blush or pure white tones to "lift" off the surface.
- **Mirror-work Accents:** Depth is further suggested by subtle SVG patterns of Gujarati mirror-work (Abhala Bharat). These patterns should be placed in the background of sections with a 3-5% opacity, creating a "watermark" effect that feels woven into the digital fabric.

## Shapes

The shape language is organic and approachable, mirroring the softness of fabric and thread.

- **Corner Radius:** We utilize the `Rounded` (Value 2) setting. The 0.5rem (8px) base radius ensures that even functional elements like input fields feel soft to the touch. 
- **Circular Accents:** Buttons and "mirror" elements may use full pill-shaping or circles to echo the traditional mirror-work patterns common in Gujarati jewelry.
- **Borders:** When used, borders are thin (1px) and set in Deep Plum at 10% opacity, providing structure without creating visual noise.

## Components

- **Buttons:** Primary buttons use the Deep Raspberry background with white text for maximum contrast. They feature a subtle hover state that increases the shadow spread.
- **Input Fields:** Large tap targets (minimum 48px height) with 18px text. Borders are only used for focus states; otherwise, fields use a slightly darker neutral tint (#F8BBD0 at 20% opacity).
- **Cards:** Product cards utilize the Blush color for a very thin border and a soft ambient shadow. Typography within cards is strictly aligned to a baseline grid for a clean look.
- **Chips & Tags:** Small, rounded elements using the Deep Plum text on a Blush background, used for "New" or "Handmade" labels.
- **Pattern Accents:** Use a specific "Mirror" component—a small circle with a high-gloss gradient or reflective tint—to act as a bullet point or decorative divider, reinforcing the brand's jewelry roots.
- **Lists:** High-contrast list items with 24px vertical padding to ensure ease of interaction for older users.