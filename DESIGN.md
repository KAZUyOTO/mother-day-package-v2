---
name: Parisian Excellence
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#4e4639'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#7f7667'
  outline-variant: '#d1c5b4'
  surface-tint: '#775a19'
  primary: '#775a19'
  on-primary: '#ffffff'
  primary-container: '#c5a059'
  on-primary-container: '#4e3700'
  inverse-primary: '#e9c176'
  secondary: '#5f5e5a'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2dc'
  on-secondary-container: '#656460'
  tertiary: '#5f5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#a7a5a5'
  on-tertiary-container: '#3b3b3b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4201'
  secondary-fixed: '#e5e2dc'
  secondary-fixed-dim: '#c9c6c1'
  on-secondary-fixed: '#1c1c18'
  on-secondary-fixed-variant: '#474743'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-xl:
    fontFamily: Noto Serif
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.15em
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The brand personality is rooted in the "Parisian Chic" aesthetic: effortless, sophisticated, and authoritative. It targets a high-end clientele who values craftsmanship, heritage, and personalized luxury. The UI must evoke a sense of calm confidence and exclusivity.

The design style is **Minimalism** with an editorial focus. This is achieved through generous whitespace (le vide), a restrained color palette, and high-quality photography that captures the movement and texture of hair. Every interaction should feel deliberate and smooth, mirroring the seamless experience of a luxury salon visit. The layout relies on structural balance rather than decorative elements, allowing the imagery of the "Franck Provost woman" to remain the focal point.

## Colors

The palette is inspired by the interior of a flagship Parisian studio.
- **Sophisticated Gold (Primary):** A muted, metallic champagne gold used for accents, primary calls to action, and highlighting the brand's premium status.
- **Cream (Secondary/Surface):** A warm, off-white "Crème" used as the primary background color. It provides a softer, more luxurious feel than pure white, reducing eye strain and evoking high-quality stationery.
- **Deep Charcoal (Tertiary/Text):** A near-black "Anthracite" used for primary typography and structural elements to provide sharp contrast without the harshness of pure black.
- **Neutral (Muted):** A sophisticated grey for secondary text and subtle borders, ensuring the hierarchy remains clear.

## Typography

This design system utilizes a classic editorial pairing to establish hierarchy and prestige.

**Noto Serif** is used for all headlines. Its timeless proportions and elegant serifs reflect the "Paris" heritage of the brand. For large display titles, a slight negative letter spacing is applied to mimic high-fashion mastheads.

**Manrope** serves as the functional workhorse for body copy and UI labels. Its modern, geometric construction provides a clean counterpoint to the serif headers, ensuring legibility on digital screens. 

Use **Label-caps** (uppercase Manrope with generous tracking) for small eyebrow headers, navigation items, and button text to instill a sense of curated order.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model on desktop, centered to create a focused, boutique feeling. A 12-column grid is used with wide margins to emphasize the "Minimalist" style.

The spacing rhythm is intentional and expansive. Large "section-gaps" (120px+) are used to separate different service categories or narrative sections, preventing the interface from feeling cluttered. Elements within a group follow an 8px base unit, but the overall composition favors asymmetrical arrangements and "white space as a luxury" to guide the user's eye toward call-to-action points.

## Elevation & Depth

To maintain a clean, modernist aesthetic, this design system avoids heavy drop shadows. Instead, it utilizes **Tonal Layers** and **Low-contrast Outlines**.

Depth is communicated through:
- **Surface Transitions:** Using subtle shifts between the Cream background and slightly lighter or darker containers to distinguish sections.
- **Refined Outlines:** Input fields and cards use 1px borders in a muted gold or soft charcoal with low opacity (10-15%).
- **Interactive Depth:** Only the primary "Book an Appointment" elements may use an "Ambient Shadow"—an extremely diffused, large-radius shadow with a hint of gold tint (#C5A059) to simulate a soft glow rather than a physical lift.

## Shapes

The shape language is **Sharp (0)**. 

True to Parisian high-fashion standards, the system utilizes 90-degree angles for all primary containers, buttons, and imagery. Sharp corners convey precision, discipline, and architectural elegance. This uncompromising geometry distinguishes the brand from more "mass-market" friendly salons that use rounded shapes. Rectangular image masks should favor vertical (portrait) orientations, reminiscent of fashion magazine layouts.

## Components

### Buttons
Primary buttons are solid Deep Charcoal with Cream text, or Gold with Deep Charcoal text for high-priority actions. They are rectangular (0px radius) and use "Label-caps" typography. Secondary buttons use a "Ghost" style: a 1px border with no fill, utilizing a subtle hover state where the background fills slightly.

### Input Fields
Fields are minimalist, consisting of a single bottom border or a very light 1px outline. Labels use "Label-caps" and sit above the field. Focus states are indicated by the border transitioning to the Primary Gold color.

### Cards
Service and Stylist cards are borderless, relying on high-quality photography and "Headline-md" typography. Content is often center-aligned within the card to reinforce the boutique aesthetic.

### Additional Components
- **The "Service Drawer":** A full-height side panel for selecting hair treatments, using a "Glassmorphism" effect with a cream-tinted backdrop blur to keep the salon imagery visible in the background.
- **Date Picker:** A highly custom, minimalist calendar using Noto Serif for the month/year and Manrope for dates, emphasizing a "Personal Concierge" feel.
- **Image Carousels:** Featuring a thin, gold progress bar at the bottom instead of traditional dots.