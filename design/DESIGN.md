---
name: Fig & Filter Narrative
colors:
  surface: '#fff8f8'
  surface-dim: '#e1d8d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f2'
  surface-container: '#f5eced'
  surface-container-high: '#efe6e7'
  surface-container-highest: '#e9e0e1'
  on-surface: '#1e1b1c'
  on-surface-variant: '#4d444b'
  inverse-surface: '#342f30'
  inverse-on-surface: '#f8eeef'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#755377'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#1b2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#303b0f'
  on-tertiary-container: '#98a66f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#dbe9ac'
  tertiary-fixed-dim: '#bfcd92'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1e'
  background: '#fff8f8'
  on-background: '#1e1b1c'
  surface-variant: '#e9e0e1'
  fig-deep: '#4A2C4D'
  amber-glow: '#D9A441'
  paper-white: '#FAF6F0'
  ink-black: '#221E1F'
typography:
  display-lg:
    fontFamily: Vollkorn
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Vollkorn
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Vollkorn
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Vollkorn
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
  label-caps:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  price-tag:
    fontFamily: Vollkorn
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1120px
  gutter: 24px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style

The design system is built to evoke the atmosphere of a warm, neighborhood sanctuary. It balances the artisanal craft of on-site roasting and baking with a "plainspoken" and "dry-humoured" personality. The aesthetic is **Modern Minimalist with Tactile warmth**, prioritizing clarity for the user while using rich, organic tones to create an inviting digital space.

The target audience ranges from the local commuter needing a quick menu check to the professional office manager organizing catering. To serve both, the system emphasizes high legibility, mobile-first utility, and a "less-is-more" approach to decoration. The interface should feel intentional, grounded, and slightly nostalgic—like a well-loved cookbook or a hand-stamped coffee bag.

## Colors

The palette is derived from the raw ingredients of the café: the deep skin of a ripe fig, the golden hue of honey or roasted beans, and the warmth of cream-toned parchment.

- **Primary (Fig):** Used for headings, primary buttons, and brand-defining architectural elements. It provides a sophisticated, weighty foundation.
- **Secondary (Amber):** Reserved strictly for accents. Use this for small icons, active states, or subtle highlights. It should never be used for long-form body text.
- **Background (Paper):** A warm off-white that reduces eye strain and reinforces the tactile, "printed" feel of the brand.
- **Text (Ink):** A near-black that ensures high contrast against the paper background while appearing softer and more organic than pure black.

## Typography

This design system uses a pairing of **Vollkorn** and **Work Sans**. 

**Vollkorn** is our "serif with character"—it is sturdy, literary, and warm, making it perfect for the café's storytelling and menu headings. **Work Sans** provides a clean, neutral balance for body copy, ensuring that price lists and catering details remain legible on small screens.

Use `label-caps` for secondary information like dietary markers (V, VG, GF) or the roasting schedule notes to provide a clear visual hierarchy without adding visual clutter.

## Layout & Spacing

The layout philosophy is **Mobile-First and Single-Column**. 

On mobile devices, content is stacked vertically with a 20px side margin to ensure focus and readability. On desktop, the layout expands to a maximum of 1120px, allowing for a two-column grid specifically for the Menu and Catering sections to aid "at-a-glance" comparisons.

A strict vertical rhythm is maintained using an 8px base unit. Vertical "stacks" should be generous (stack-lg) between major sections like "The Founding Story" and "Founder Profiles" to create a sense of pace and airiness.

## Elevation & Depth

To maintain the grounded, neighborhood feel, this design system avoids heavy shadows or futuristic blurs. Instead, depth is communicated through **Tonal Layering and Borders**.

1.  **The Base:** Everything sits on the `paper-white` background.
2.  **Containers:** Use subtle `fig-deep` hairline borders (0.5px or 1px) to group content like menu categories or catering packages. 
3.  **No Shadows:** Do not use drop shadows on buttons or cards. Instead, use a solid color fill for primary actions to create "pop" through contrast rather than artificial depth.
4.  **Photography:** Use full-width images or images with a slight "inset" to create visual breaks.

## Shapes

The shape language is **Soft (Level 1)**. 

While the brand is traditional, slight rounding (4px for standard elements) prevents the UI from feeling too sharp or aggressive. This applies to buttons, input fields for catering enquiries, and image containers. 

For a more organic touch, portrait photographs of Mara and Dev may use a slightly larger `rounded-lg` (8px) or a soft organic mask to distinguish people from more structural UI components.

## Components

### Buttons
- **Primary:** Solid `fig-deep` background with `paper-white` text. Rectangular with a 4px corner radius. High-impact, used exactly once per page.
- **Secondary/Text Link:** Simple `ink-black` text with a 1px underline. No background.

### Menu Lists
- Use a "dotted leader" (dots connecting the item name to the price) for a classic café aesthetic.
- Dietary markers (V, VG, GF) should be styled as small `label-caps` in `amber-glow` next to the item name.

### Catering Cards
- Defined by a thin `fig-deep` border.
- The price should be prominently displayed using the `price-tag` typography level.
- Inside the card, use a simple bulleted list for package inclusions.

### Input Fields (Catering Enquiry)
- Clean, 1px `ink-black` border on three sides (bottom, left, right) or a full border if preferred for accessibility. 
- Background should remain `paper-white` to feel like part of the page.

### Navigation & Footer
- **Navigation:** Horizontal on desktop, centered stack on mobile. Use `label-caps` for nav items.
- **Footer:** Separated by a horizontal rule. High-density information (hours, address, contact) should be organized in clear, legible blocks using `body-md`.