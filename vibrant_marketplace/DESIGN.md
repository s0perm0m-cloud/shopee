---
name: Vibrant Marketplace
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#5b403b'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#8f7069'
  outline-variant: '#e3beb6'
  surface-tint: '#b62506'
  primary: '#b22204'
  on-primary: '#ffffff'
  primary-container: '#d63c1e'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a4'
  secondary: '#7b5800'
  on-secondary: '#ffffff'
  secondary-container: '#f9b500'
  on-secondary-container: '#684a00'
  tertiary: '#00685c'
  on-tertiary: '#ffffff'
  tertiary-container: '#008375'
  on-tertiary-container: '#f4fffb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad3'
  primary-fixed-dim: '#ffb4a4'
  on-primary-fixed: '#3e0500'
  on-primary-fixed-variant: '#8d1600'
  secondary-fixed: '#ffdea6'
  secondary-fixed-dim: '#ffbb0c'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5d4200'
  tertiary-fixed: '#81f6e3'
  tertiary-fixed-dim: '#63dac7'
  on-tertiary-fixed: '#00201c'
  on-tertiary-fixed-variant: '#005047'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  h1:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  h2:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
  h3:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 22px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  price-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: -0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '400'
    lineHeight: 12px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  gutter: 10px
  margin-mobile: 12px
---

## Brand & Style

This design system is engineered for a high-velocity mobile commerce environment. The brand personality is energetic, accessible, and retail-focused, designed to evoke a sense of urgency and excitement while maintaining a bedrock of reliability. 

The aesthetic follows a **Corporate / Modern** style with a heavy emphasis on mobile-first ergonomics. It prioritizes clarity over decorative elements, utilizing a "Content-First" approach where white space acts as a structural component to prevent cognitive overload in a data-dense marketplace. The visual language is approachable and optimized for quick scanning and seamless conversion.

## Colors

The palette is anchored by a vibrant, high-visibility orange that serves as the primary driver for action and brand recognition. 

*   **Primary (Orange):** Used for key calls-to-action, active states, and brand-critical elements.
*   **Secondary (Gold):** Reserved for loyalty programs, star ratings, and "Flash Sale" urgency.
*   **Tertiary (Teal):** Utilized for trust signals, such as "Shopee Guarantee" or verified badges.
*   **Neutral & Backgrounds:** The design system utilizes a pure white (#FFFFFF) for page surfaces to maximize contrast. Borders and dividers use a light gray (#E8E8E8) to provide structure without adding visual weight.

## Typography

This design system employs **Plus Jakarta Sans** for its friendly yet functional geometric proportions. The typography is scaled for mobile readability, with a clear hierarchy that distinguishes between product discovery and transactional data. 

Price points are given specific typographic treatment with tighter letter spacing and heavier weights to ensure they are the most prominent element in any product card. Body text remains neutral to allow the vibrant primary colors of the UI to lead the user's eye.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** model optimized for a 4px baseline rhythm. For mobile views, the design system utilizes a standard 2-column grid for product feeds to maximize screen real estate while maintaining image clarity.

*   **Margins:** A standard 12px horizontal margin is applied to the main container for mobile devices.
*   **Gutter:** A 10px gutter separates product cards in a grid to provide a "breathable" but dense shopping experience.
*   **Section Spacing:** Major vertical sections are separated by 8px gray "dividing blocks" (F5F5F5) to create a clear visual break in the infinite scroll.

## Elevation & Depth

Visual hierarchy is established primarily through **Tonal Layers** and **Low-Contrast Outlines**. 

*   **Surfaces:** The primary background is white. Secondary areas (like the "tray" behind a product list) use a very light gray.
*   **Depth:** Shadows are used sparingly and are exclusively "Ambient Shadows"—soft, blurred, and low opacity (4-8%). This gives elements like the bottom navigation bar or floating "Back to Top" buttons a subtle lift without feeling heavy.
*   **Borders:** 1px solid lines in light gray (#E8E8E8) are the primary tool for defining component boundaries, ensuring the UI feels crisp and structured.

## Shapes

The design system uses a **Soft** shape language. This creates an approachable and modern feel while remaining space-efficient for retail layouts.

*   **Small Elements:** Checkboxes, tags, and small badges use a 2px radius.
*   **Medium Elements:** Product cards and input fields use a 4px to 8px radius.
*   **Large Elements:** Bottom sheets and prominent "Buy Now" buttons use a 12px radius or full pill-shape to draw maximum attention.

## Components

### Search Bar
The search bar is the primary entry point. It features a subtle light gray background (#F0F0F0) with a 2px radius. It must contain a persistent magnifying glass icon on the left and a camera icon (for image search) on the right.

### Product Cards
Cards are the core of the experience. They use a white background with no border but a subtle shadow or a 1px light gray outline. 
- **Image:** 1:1 aspect ratio.
- **Content:** Title (max 2 lines), Price (Primary Orange), Rating (Gold Star + numerical value), and Sales Volume (Caption text).

### Buttons
- **Primary Button:** Solid #EE4D2D background with white text. High-contrast, bold weight.
- **Secondary Button:** White background with #EE4D2D border and text.
- **Ghost Button:** Clear background with gray text for low-priority actions.

### Category Grids
Icons in the category grid should be "flat-color" or "skeuomorphic-lite," featuring simple shapes with vibrant accents. They are arranged in a 4 or 5-column layout with center-aligned labels below.

### Selection Controls
Checkboxes and radio buttons use the Primary Orange for the active state. When inactive, they maintain a 1px gray border to remain unobtrusive.