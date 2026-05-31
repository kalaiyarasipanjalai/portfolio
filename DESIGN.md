---
name: Kinetic Engineering
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#909097'
  outline-variant: '#45464d'
  surface-tint: '#bec6e0'
  primary: '#bec6e0'
  on-primary: '#283044'
  primary-container: '#0f172a'
  on-primary-container: '#798098'
  inverse-primary: '#565e74'
  secondary: '#c3c0ff'
  on-secondary: '#1d00a5'
  secondary-container: '#3626ce'
  on-secondary-container: '#b3b1ff'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#001c10'
  on-tertiary-container: '#009365'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#e2dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#0f0069'
  on-secondary-fixed-variant: '#3323cc'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  code:
    fontFamily: monospace
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 0.5rem
  sm: 1rem
  md: 1.5rem
  lg: 3rem
  xl: 6rem
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: auto
  max-width: 1200px
---

## Brand & Style

The design system is engineered for high-performance software engineering portfolios, prioritizing rapid scannability and technical authority. The brand personality is precise, reliable, and modern, targeting technical recruiters and engineering managers who need to extract core competencies within seconds.

The visual style blends **Corporate Modern** with **Minimalist** efficiency. It utilizes a deep monochromatic base to provide a high-contrast backdrop for code and content, punctuated by vibrant functional accents. The interface should feel like a high-end IDE—focused, utilitarian, yet aesthetically polished. Emphasize heavy whitespace to prevent cognitive overload and use subtle kinetic feedback to signal interactivity.

## Colors

The palette is anchored by a **Deep Navy (#0F172A)** foundation to establish a professional, "night-mode" environment preferred by the developer community.

- **Primary:** The core background and deep surface color.
- **Secondary (Indigo-600):** Used for primary actions, focus states, and signifying technical depth.
- **Tertiary (Emerald-500):** Reserved for "success" indicators, live project links, and deployment status.
- **Surface Tiers:** Use Slate-900 for secondary containers and Slate-800 for interactive cards/hover states to create subtle depth without breaking the dark aesthetic.
- **Typography:** Pure White (#FFFFFF) for headers and high-emphasis content; Slate-400 (#94A3B8) for secondary body text to maintain a clear visual hierarchy.

## Typography

This design system utilizes **Plus Jakarta Sans** for headlines to provide a modern, slightly geometric character that feels approachable yet professional. **Inter** is used for all body and UI text due to its exceptional legibility at small sizes and neutral, systematic tone.

Text hierarchy is strictly enforced:
- **Display and Large Headlines:** High weight and tight tracking to create impact.
- **Body Text:** Generous line heights (1.6) to ensure long-form project descriptions remain readable.
- **Labels:** Uppercase with increased letter spacing for categorization and "Tech Stack" tags.
- **Code:** Fallback to a clean monospaced font for code snippets or terminal-style outputs to reinforce the engineering theme.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain a controlled, editorial feel, transitioning to a fluid model for mobile devices.

- **Desktop (1200px+):** A 12-column grid with a 1200px max-width, centered in the viewport.
- **Tablet (768px - 1199px):** 8-column fluid grid with 40px side margins.
- **Mobile (< 767px):** 4-column fluid grid with 20px side margins.

The spacing rhythm is based on a 4px baseline, but predominantly uses large steps (lg/xl) between sections to provide the "high-contrast padding" requested. This ensures that the recruiter’s eye can easily distinguish between the "About," "Experience," and "Projects" sections without visual noise.

## Elevation & Depth

To maintain the sleek, technical aesthetic, this design system avoids heavy shadows, instead using **Tonal Layers** and **Low-Contrast Outlines**.

- **Level 0 (Background):** #0F172A.
- **Level 1 (Cards/Sections):** Slate-900 with a 1px solid border of Slate-800.
- **Level 2 (Hover States):** Surface color shifts to Slate-800 with a subtle Indigo-600 glow (0px 4px 20px rgba(79, 70, 229, 0.15)).
- **Interactive Depth:** Elements should not feel "squishy"; they should feel responsive. Use 200ms ease-in-out transitions for all color and border shifts.

## Shapes

The design system utilizes **Soft (0.25rem)** roundedness to maintain a crisp, professional edge. This "near-sharp" approach communicates precision and technical rigor.

- **Standard Elements:** 4px (0.25rem) radius for buttons, input fields, and small cards.
- **Containers:** 8px (0.5rem) radius for large project cards and modals.
- **Interactive Pills:** Use 1rem (rounded-xl) specifically for "Tech Stack" tags to differentiate them from functional buttons.

## Components

### Buttons
- **Primary:** Solid Indigo-600 background, white text. Hover state: Lighten background by 10%.
- **Secondary:** Transparent background with 1px Slate-700 border. Hover state: Slate-800 background.
- **Tertiary (Action):** Emerald-500 text with a leading icon; no border.

### Project Cards
- Use Slate-900 background.
- Include a subtle 1px border.
- On hover: Scale image by 2%, change border color to Indigo-600.

### Tech Stack Chips
- Small, uppercase label text.
- Slate-800 background with no border.
- Indigo-600 left-accent border (2px) for "Expert" skills.

### Inputs
- Background: #0F172A (Inset look).
- Border: Slate-800.
- Focus State: Border color moves to Indigo-600 with a 2px outer ring of Indigo-600 at 20% opacity.

### Navigation
- Sticky header with a backdrop blur (12px) and 80% opacity on the primary background color.
- Active links marked with a 2px Emerald-500 underline.