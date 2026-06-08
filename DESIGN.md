---
name: High-Velocity Sports Intelligence
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffc174'
  on-tertiary: '#472a00'
  tertiary-container: '#f59e0b'
  on-tertiary-container: '#613b00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  data-mono:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style
This design system is engineered for the high-stakes environment of live sports betting and predictive analytics. The brand personality is authoritative, precise, and technologically advanced, catering to users who demand real-time data clarity and professional-grade tools.

The visual style follows a **Modern / High-Tech** aesthetic. It utilizes a deep, dark canvas to reduce eye strain during extended night-time viewing and uses vibrant, neon-tinted accents to draw immediate attention to fluctuating odds and live match statuses. Elements of **Glassmorphism** are used sparingly to create a sense of depth and hierarchy without compromising the density of information required for sports statistics.

## Colors
The palette is built on a foundation of "True Dark" tones to ensure maximum contrast for data visualization.

- **Primary (Electric Blue):** Used for primary actions, active states, and selection highlights. It represents the "tech" core of the system.
- **Secondary (Emerald Green):** Dedicated to "Live" indicators, winning trends, and positive probability shifts.
- **Tertiary (Amber):** Reserved for cautionary data, pending bets, or half-time statuses.
- **Neutrals:** A scale of cool charcoals and slates provide the structural framework, ensuring that white text remains crisp and legible against dark backgrounds.

## Typography
The design system relies on **Inter** for its exceptional legibility in data-dense environments. 

- **Weight Strategy:** Headlines use Bold and ExtraBold weights to establish immediate hierarchy. Body copy stays at Regular, while tactical data (odds, scores) uses SemiBold or Bold to ensure they are the first things a user sees.
- **Data Mono:** While Inter is a sans-serif, we treat specific numeric labels with increased letter-spacing and uppercase styling to mimic the precision of a scoreboard.
- **Readability:** Line heights are kept tight for statistics to allow more data "above the fold," but generous for editorial content and news feeds.

## Layout & Spacing
The layout uses a **Fluid Grid** system based on an 8px rhythmic scale. 

- **Desktop:** 12-column grid with 24px gutters. This allows for a multi-pane view: navigation on the left, live markets in the center, and the bet slip/stats on the right.
- **Mobile:** 4-column grid with 16px margins. Content prioritizes vertical scrolling of match cards.
- **Density:** Information density is "High." Padding within cards is kept to 12px or 16px to maximize the number of betting markets visible on a single screen.

## Elevation & Depth
Depth is created through **Tonal Layers** rather than heavy shadows, maintaining a sleek, modern feel.

- **Level 0 (Base):** Deepest black (#0F172A). Used for the main application background.
- **Level 1 (Surface):** Charcoal (#1E293B). Used for match cards and container elements.
- **Level 2 (Overlay):** Lightened slate. Used for hover states and active selections.
- **Glow Effects:** High-importance elements (like a "Live" tag or a "Place Bet" button) utilize a subtle outer glow (0px 0px 12px) using the Primary or Secondary color at 30% opacity to simulate a digital screen effect.

## Shapes
This design system utilizes **Soft (Level 1)** roundedness. 

- **Standard Radius:** 4px (0.25rem) for small components like tags and buttons.
- **Large Radius:** 8px (0.5rem) for cards and containers.
This geometric approach maintains a professional, "engineered" look that feels more technical and precise than overly rounded or pill-shaped alternatives.

## Components
- **Match Cards:** High-contrast containers with a 1px border (#334155). Live matches should feature a pulsing Emerald Green dot.
- **Buttons:** Primary buttons are solid Electric Blue with white or dark navy text. Ghost buttons use the primary color for the border and text.
- **Win Probability Bars:** Sleek, low-profile horizontal bars. The "fill" should use a gradient from Primary to Secondary to show momentum.
- **Odds Chips:** Small, rectangular buttons with a dark background. Upon selection, they transition to a solid Primary color with a subtle inner glow.
- **Input Fields:** Minimalist design with a focus on the focus state; when active, the border glows Electric Blue.
- **Status Indicators:** Glowing, high-saturation icons. Green for "In-Play," Amber for "Reviewing," and Red for "Closed."
