---
name: Premium Peruvian Security
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e7bdb9'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ad8884'
  outline-variant: '#5d3f3c'
  surface-tint: '#ffb3ad'
  primary: '#ffb3ad'
  on-primary: '#680009'
  primary-container: '#d91023'
  on-primary-container: '#ffecea'
  inverse-primary: '#c0001a'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#92ccff'
  on-tertiary: '#003351'
  tertiary-container: '#0073ae'
  on-tertiary-container: '#e7f2ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#930011'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#92ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Montserrat
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
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style
The design system embodies a professional, high-trust identity rooted in national prestige and modern security. It targets a sophisticated audience that values reliability, speed, and safety. 

The aesthetic is **Corporate / Modern** with a focus on dark-mode prestige. It utilizes deep charcoal foundations contrasted against a vibrant, authoritative red to evoke a sense of urgency tempered by institutional stability. The interface should feel premium and expansive, using generous whitespace (even in dark mode) and precise alignment to signal meticulous attention to detail.

## Colors
The palette is centered on the Peruvian national colors, reimagined for a digital-first security context.

- **Primary (Red):** A rich, high-trust red used for primary actions, critical status indicators, and branding elements. It must be vibrant enough to pass accessibility standards against dark backgrounds without appearing aggressive.
- **Secondary (White):** Pure white is reserved for high-contrast typography, iconography, and subtle accent borders to provide clarity and a "premium" polish.
- **Neutral (Dark):** The foundation is built on deep grays and near-blacks (#121212). Avoid pure #000000 to maintain depth and reduce eye strain.
- **Functional:** Success states should use a muted emerald, while warnings remain secondary to the primary brand red.

## Typography
Montserrat is the exclusive typeface for this design system, chosen for its geometric precision and modern architectural feel. 

Headlines should utilize the **Bold (700)** weight to project authority. For body text, the **Regular (400)** weight ensures readability against dark backgrounds. Tracking (letter spacing) should be tightened slightly for large display titles and opened slightly for small labels to maintain legibility. All typography should default to White or High-Emphasis Gray to ensure a premium, high-contrast look.

## Layout & Spacing
The design system employs a **fixed grid** approach for desktop to maintain a controlled, high-end editorial feel, transitioning to a fluid model for mobile devices.

- **Grid:** A 12-column grid is used for desktop (1280px max width).
- **Rhythm:** An 8px linear scale governs all padding and margin decisions. 
- **Mobile:** Margins shrink to 16px, and the 12-column grid collapses to a single column or 2-column pattern for cards.
- **Density:** Favor "High-Room" layouts. Use generous vertical padding (64px+) between major sections to emphasize a premium, uncluttered experience.

## Elevation & Depth
Depth is created through **Tonal Layers** rather than heavy shadows. In this dark mode environment, higher elevation is signaled by lighter surface colors.

1.  **Level 0 (Base):** The darkest neutral (#121212).
2.  **Level 1 (Cards/Surface):** A slightly lighter gray (#1E1E1E).
3.  **Level 2 (Overlays/Menus):** A mid-gray (#2C2C2C).

Where shadows are necessary for focus (e.g., Modals), use a large, soft ambient shadow with a subtle Red tint (#D91023 at 10% opacity) to reinforce the brand color in the Z-axis.

## Shapes
This design system utilizes **Soft** geometry. Corners are rounded just enough to feel modern and accessible without losing the professional "sharpness" required of a security-focused product.

Standard components use a 0.25rem (4px) radius. Larger containers like cards or feature blocks may scale up to 0.5rem (8px). Avoid fully rounded "pill" shapes for buttons to maintain a more structured, corporate aesthetic; instead, stick to the defined soft-cornered rectangles.

## Components
- **Buttons:** Primary buttons are solid Red (#D91023) with Bold White text. Secondary buttons use a White ghost outline. Active states should involve a slight darkening of the red.
- **Inputs:** Text fields feature a dark background (#1E1E1E) with a 1px White border at 20% opacity. Upon focus, the border becomes solid Red.
- **Cards:** Use "Level 1" tonal layers with no border. On hover, apply a subtle 1px Red top-border to indicate interactivity.
- **Chips/Status:** Use the Primary Red for high-priority alerts. For neutral metadata, use White text on a transparent background with a thin White stroke.
- **Lists:** Items should be separated by thin, low-opacity lines (White at 10%) to maintain a clean, organized hierarchy without visual clutter.
- **Data Visualizations:** Use Red as the primary data point, with White and Light Gray for secondary metrics.