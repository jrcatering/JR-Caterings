# Design System: Heritage Gold
ID: asset-stub-assets_0329c00cfa4046be992afbe61945672e (assets/0329c00cfa4046be992afbe61945672e)

---
name: Heritage Gold
colors:
  surface: '#fbf9f3'
  surface-dim: '#dbdad4'
  surface-bright: '#fbf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee8'
  surface-container-high: '#eae8e2'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#4e4540'
  inverse-surface: '#30312d'
  inverse-on-surface: '#f2f1eb'
  outline: '#807570'
  outline-variant: '#d1c4be'
  surface-tint: '#6a5b54'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#241914'
  on-primary-container: '#918179'
  inverse-primary: '#d6c3ba'
  secondary: '#745b00'
  on-secondary: '#ffffff'
  secondary-container: '#fdd978'
  on-secondary-container: '#775e00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f0016'
  on-tertiary-container: '#d45b79'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f3dfd5'
  primary-fixed-dim: '#d6c3ba'
  on-primary-fixed: '#241914'
  on-primary-fixed-variant: '#51443d'
  secondary-fixed: '#ffe08c'
  secondary-fixed-dim: '#e5c364'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#ffd9de'
  tertiary-fixed-dim: '#ffb1c0'
  on-tertiary-fixed: '#3f0016'
  on-tertiary-fixed-variant: '#851e3e'
  background: '#fbf9f3'
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
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  title-lg:
    fontFamily: DM Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.02em
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: DM Sans
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style

This design system captures the legacy of JR Caterings (Since 1960) by blending high-end editorial aesthetics with traditional South Indian warmth. The visual direction is **Premium Modern-Traditional**, characterized by a sophisticated interplay of deep earth tones and metallic accents.

The system emphasizes:
- **Heritage Luxury:** Using high-contrast serif typography and a palette that evokes the richness of brass, coffee, and silk.
- **Editorial Precision:** Large margins, intentional whitespace, and sharp edges that mirror luxury lifestyle publications.
- **Trustworthy Elegance:** A disciplined layout that balances the "raw" feeling of tradition with the "refined" execution of professional catering services.

## Colors

The color strategy is anchored in a "70-20-10" distribution to maintain a light, airy, yet grounded feel.

- **Primary (Deep Espresso):** Used for primary navigation, bold headings, and heavy structural elements. It provides a modern, high-contrast anchor.
- **Secondary (Warm Gold):** Reserved for interactive elements, decorative accents, and calls to action. It evokes the quality of polished brass.
- **Background (Warm Ivory):** The primary canvas. It feels more organic and inviting than a clinical white.
- **Accent (Deep Maroon):** Used sparingly for highlighting key heritage details or status indicators.
- **Soft Cream:** Applied to section backgrounds or container fills to subtly differentiate content without adding visual weight.

## Typography

The typography system uses a classic pairing to signify authority and modern efficiency. 

- **Playfair Display** handles all major storytelling and editorial moments. Use high-contrast weights for displays to create a luxury feel.
- **DM Sans** provides a clean, geometric contrast for functional UI, long-form descriptions, and labels.
- **Editorial Hierarchy:** Ensure large headlines have ample breathing room. Labels should frequently use `label-caps` for a structured, professional appearance.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop to maintain editorial control, transitioning to a fluid model for mobile devices.

- **Grid:** A 12-column grid with generous 24px gutters.
- **Margins:** Desktop margins are intentionally wide (64px+) to create a "gallery" feel.
- **Rhythm:** Vertical spacing follows a 8px baseline. Use `stack-lg` between major sections to emphasize exclusivity and prevent visual clutter.
- **Mobile Reflow:** Content should stack vertically with `margin-mobile`. Image-heavy cards should span the full width to maximize detail.

## Elevation & Depth

To maintain a premium, grounded feel, this design system avoids heavy drop shadows. Depth is created through **Tonal Layering** and **Line Work**.

- **Layers:** Use the `Soft Cream` background to pull a container "forward" against the `Warm Ivory` base.
- **Outlines:** Use thin (1px) borders in `Warm Gold` or a low-opacity version of `Deep Espresso` to define containers.
- **Minimal Shadows:** When necessary for interactivity (e.g., a hovered card), use a very soft, diffused ambient shadow: `0 8px 24px rgba(22, 13, 8, 0.05)`.
- **Subtle Texture:** Apply a very light grain or a subtle Kolam pattern watermark (5% opacity) to background layers to add physical depth.

## Shapes

The shape language is **Structured and Sharp**. 

- **Corners:** Use a `Soft` (4px) radius for most UI components (buttons, input fields) to prevent them from feeling aggressive, but keep large image containers and sections at 0px (Sharp) for a more architectural, professional look.
- **Dividers:** Use thin, horizontal rules with a `Warm Gold` center-point or a small decorative Kolam motif to separate content sections.

## Components

- **Buttons:** Primary buttons use a `Deep Espresso` fill with `Warm Ivory` text. Secondary buttons use a `Warm Gold` border and text. Buttons are rectangular with a 4px radius.
- **Cards:** No heavy shadows. Use a 1px border in `#D9B85A` at 30% opacity or a simple tonal shift. Text within cards should be center-aligned for menu items to feel more "boutique."
- **Inputs:** Underlined or fully boxed with 1px `Charcoal` borders. Focus state shifts the border color to `Warm Gold`.
- **Chips/Labels:** Small, all-caps labels with `Warm Gold` background and `Deep Espresso` text, used to denote "Chef's Special" or "Heritage Recipe."
- **Lists:** Menu lists should use `Playfair Display` for the item name and `DM Sans` for the price and description. Use a dotted leader line for a classic menu feel.
- **Decorative Elements:** Include a "Kolam" pattern component that can be used as a corner frame for images or a subtle background watermark.
