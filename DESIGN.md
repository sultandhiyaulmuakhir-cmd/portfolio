---
name: Sultan Dhiyaul Muakhir Portfolio
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e4e2e1'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e4e2e1'
  inverse-on-surface: '#303030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#0a0a0a'
  on-primary-container: '#7b7979'
  inverse-primary: '#5f5e5e'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#abd600'
  on-tertiary: '#283500'
  tertiary-container: '#070c00'
  on-tertiary-container: '#688300'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#c3f400'
  tertiary-fixed-dim: '#abd600'
  on-tertiary-fixed: '#161e00'
  on-tertiary-fixed-variant: '#3c4d00'
  background: '#131313'
  on-background: '#e4e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Syne
    fontSize: 80px
    fontWeight: '800'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style

The design system is built for a high-end UI/UX portfolio that embodies the concept of "antigravity"—visualized through weightless layouts, expansive negative space, and technical precision. The brand personality is professional, sophisticated, and forward-leaning, targeting premium tech firms and design-conscious studios.

The visual style is **Futuristic Minimalism** with a **Glassmorphic** layer. It leans into a "dark mode" default to create a sense of infinite depth, where content appears to float in a vacuum. Layouts are strictly grid-based but utilize unexpected vertical alignments to evoke a sense of zero-gravity. Interaction is signaled through high-frequency neon accents and precision-engineered transitions.

## Colors

The palette is rooted in a deep, obsidian base to provide maximum contrast for typography and media.

- **Primary (#0A0A0A):** The "Void." Used for the main background to eliminate visual noise.
- **Secondary (#FFFFFF):** The "Light." Used for primary headings and body text to ensure razor-sharp legibility.
- **Tertiary (#CCFF00):** The "Signal." A vibrant Electric Lime used sparingly for calls-to-action, active states, and critical highlights.
- **Neutral (#262626):** The "Structure." Used for subtle borders and secondary containers.
- **Silver (#A1A1AA):** The "Metadata." Used for labels, captions, and secondary information to create a clear hierarchy.

## Typography

This design system uses a high-contrast typographic pairing to balance expressive creativity with technical rigor.

- **Syne (Headings):** A wide, bold sans-serif that feels expansive and avant-garde. Used for large display titles to anchor the "gravity" of the page.
- **Geist (Body):** A modern, geometric sans-serif designed for readability and precision. It provides a clean, neutral balance to the expressive headlines.
- **JetBrains Mono (Labels/Metadata):** A monospaced font used for technical data, category labels, and micro-copy, reinforcing the "engineered" feel of the portfolio.

## Layout & Spacing

The layout follows a **Rigid Fluid Grid**. While the underlying structure is a 12-column grid, the visual implementation should feel airy and unconstrained.

- **The Void (Section Gaps):** Large vertical gaps (160px+) are used between sections to allow content to breathe and feel isolated in space.
- **Asymmetric Balance:** Elements should often be offset from the center or occupy specific grid tracks (e.g., columns 1-6 for text, columns 8-12 for imagery) to create a sense of floating.
- **Breakpoints:** 
  - **Desktop (1440px+):** 12 columns, 64px margins.
  - **Tablet (768px - 1439px):** 8 columns, 40px margins.
  - **Mobile (Up to 767px):** 4 columns, 24px margins. Section gaps reduce to 80px.

## Elevation & Depth

Depth is conveyed through transparency and light, rather than traditional shadows.

- **Glassmorphism:** Overlays (modals, navigation bars) use a `backdrop-filter: blur(20px)` with a highly transparent white fill (`rgba(255, 255, 255, 0.05)`).
- **Subtle Borders:** Instead of shadows, use 1px solid borders in `#262626` to define boundaries.
- **Z-Axis layering:** Interactive elements should appear to lift toward the user via scale transforms (`scale(1.02)`) and increased border brightness rather than drop shadows.
- **Active State:** The Electric Lime accent color acts as a "glow" source, highlighting specific interaction points.

## Shapes

The design system utilizes **Sharp (0px)** roundedness. Every element—buttons, cards, and input fields—features hard 90-degree angles. This architectural approach reinforces a sense of technical precision and structural integrity, contrasting with the "softness" of the background blurs and fluid transitions.

## Components

- **Buttons:** Rectangular with 1px white borders. Hover states trigger a fill of the Tertiary color (#CCFF00) and black text, creating a high-energy "active" signal.
- **Cards (Project Thumbs):** Full-width or half-width grid blocks. Images should have a subtle grayscale filter that transitions to full color on hover. Titles should use the `label-mono` style.
- **Navigation:** A fixed, glassmorphic top bar or a minimal corner-pinned menu. Use thin lines to separate navigation items.
- **Input Fields:** Bottom-border only (1px Silver). On focus, the border turns Electric Lime.
- **Chips/Tags:** Monospace text enclosed in a 1px Silver box. No background fill.
- **Lists:** Large, numbered list items using `headline-md`. On hover, the number translates horizontally to the right.
- **Gravity Elements:** Floating "floating action buttons" (FABs) or decorative elements that move slightly based on cursor proximity (parallax effect).