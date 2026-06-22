---
name: RentFlow
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#0d1c2f'
  on-tertiary-container: '#76859b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#d5e3fd'
  tertiary-fixed-dim: '#b9c7e0'
  on-tertiary-fixed: '#0d1c2f'
  on-tertiary-fixed-variant: '#3a485c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  code-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  sidebar-width: 260px
  sidebar-collapsed: 72px
  container-max: 1440px
---

## Brand & Style
The design system is engineered for a high-trust, high-utility SaaS environment. It balances the rigor of financial management with the approachability of a modern service platform. The aesthetic is **Modern Corporate Minimalism**, prioritizing clarity, data density without clutter, and a calm, professional atmosphere.

The interface leverages ample whitespace and a structured information hierarchy to reduce cognitive load for property managers. By utilizing subtle depth and a refined color palette, the system evokes a sense of stability and institutional quality while remaining accessible to individual landlords.

## Colors
The palette is anchored in **Deep Ocean Blue** (#0F172A) to communicate authority and reliability. **Emerald Green** (#10B981) is used strategically as a "success" accent for financial growth, positive cash flow, and primary actions.

- **Primary:** Deep Blue for navigation, headings, and core structural elements.
- **Secondary:** Emerald Green for growth indicators, "Paid" statuses, and primary CTAs.
- **Neutrals:** A sophisticated range of cool grays (Slate) to define borders, secondary text, and background layers.
- **Semantic:** Error states use a muted Carmine; Warnings use a deep Amber.

Both Light and Dark modes utilize the same primary/secondary accents, but the background shifts from a clean "Salt" white to a deep "Midnight" navy to maintain contrast and reduce eye strain during long sessions.

## Typography
This design system uses **Inter** exclusively to ensure a systematic, utilitarian feel that excels in data-heavy environments. 

- **Weight Strategy:** Use *Semi-Bold (600)* for headers and *Medium (500)* for labels to create clear visual separation from *Regular (400)* body text.
- **Scaling:** On mobile devices, Large Headlines scale down by approximately 25% to ensure readability without excessive wrapping.
- **Readability:** Line heights are kept generous (1.5x for body) to ensure financial tables and lease agreements remain legible.

## Layout & Spacing
The system utilizes a **Fixed Grid** on desktop (12 columns, 24px gutters) and a **Fluid Layout** on mobile (4 columns, 16px gutters).

- **Sidebar:** A collapsible navigation rail is the primary anchor. It transitions from 260px to 72px.
- **Content Area:** Content is housed in a central container with a max-width of 1440px to prevent excessive line lengths on ultra-wide monitors.
- **Rhythm:** A 4px baseline grid governs all spacing. Vertical rhythm should primarily use 16px (md) and 24px (lg) increments for component separation.

## Elevation & Depth
Depth is conveyed through **Tonal Layering** and **Ambient Shadows**. 

- **Level 0 (Base):** The main background color.
- **Level 1 (Cards):** Surfaces use a white (or deep navy) fill with a subtle 1px border (#E2E8F0 in light mode) and a soft, low-opacity shadow (Y: 2px, Blur: 4px, Spread: 0, Opacity: 0.05).
- **Level 2 (Dropdowns/Modals):** Elements that sit above the UI use a more pronounced shadow (Y: 10px, Blur: 15px, Opacity: 0.1) to create a clear physical separation.
- **Transitions:** All elevation changes (e.g., hovering over a card) should use a subtle 200ms ease-in-out transition.

## Shapes
The shape language is defined by **Soft Geometric** forms. 

- **Cards & Modals:** Use a standard 12px (`rounded-lg`) corner radius to soften the professional aesthetic.
- **Buttons & Inputs:** Use an 8px (`rounded-md`) radius for a precise, clickable appearance.
- **Status Pills:** Use a fully rounded (`rounded-full`) radius to distinguish categorical metadata from interactive elements.

## Components

### Buttons
- **Primary:** Emerald Green background with white text. No shadow, 8px radius.
- **Secondary:** Transparent background with a 1px Slate border. 
- **Tertiary:** Ghost style; no border or background until hover.

### Cards
Cards are the primary container for data. They must include a 16px or 24px internal padding. Card headers should have a subtle bottom border to separate titles from content.

### Inputs & Selects
Fields use a 1px border and a subtle internal shadow to appear slightly inset. Focused states utilize a 2px Emerald Green ring with a 2px offset.

### Data Visualization
Charts should use a simplified color palette: Primary Blue for historical data, Emerald Green for forecasts, and Slate for benchmarks. Use 4px rounded corners on bar charts.

### Sidebar
The sidebar uses a dark theme even in "Light Mode" by default to anchor the UI. Active states are indicated by a 3px vertical Emerald Green bar on the left edge and a subtle high-contrast background shift.