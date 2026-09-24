---
name: Monochrome Craft Engine
colors:
  surface: '#121318'
  surface-dim: '#121318'
  surface-bright: '#38393f'
  surface-container-lowest: '#0d0e13'
  surface-container-low: '#1a1b21'
  surface-container: '#1e1f25'
  surface-container-high: '#292a2f'
  surface-container-highest: '#34343a'
  on-surface: '#e3e1e9'
  on-surface-variant: '#c4c7c9'
  inverse-surface: '#e3e1e9'
  inverse-on-surface: '#2f3036'
  outline: '#8e9193'
  outline-variant: '#444749'
  surface-tint: '#c4c7c9'
  primary: '#ffffff'
  on-primary: '#2d3133'
  primary-container: '#e0e3e5'
  on-primary-container: '#626567'
  inverse-primary: '#5c5f61'
  secondary: '#b9c8de'
  on-secondary: '#233143'
  secondary-container: '#39485a'
  on-secondary-container: '#a7b6cc'
  tertiary: '#ffffff'
  on-tertiary: '#00354a'
  tertiary-container: '#c4e7ff'
  on-tertiary-container: '#006c93'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e0e3e5'
  primary-fixed-dim: '#c4c7c9'
  on-primary-fixed: '#191c1e'
  on-primary-fixed-variant: '#444749'
  secondary-fixed: '#d4e4fa'
  secondary-fixed-dim: '#b9c8de'
  on-secondary-fixed: '#0d1c2d'
  on-secondary-fixed-variant: '#39485a'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#121318'
  on-background: '#e3e1e9'
  surface-variant: '#34343a'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 42px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style
The design system embodies the disciplined precision of a senior systems architect combined with the typographic refinement of high-end editorial publishing. The interface conveys uncompromising technical mastery, deliberate restraint, and artisanal digital craft.

Targeted at engineering leaders, founders, and discerning design engineers, the visual environment avoids gratuitous ornament or saturated decorative accents. It relies on architectural spacing, stark tonal contrast, hairline dividers, and meticulous typographic hierarchy to create a calm, hyper-focused atmosphere of competence and clarity.

The visual aesthetic synthesizes **Technical Minimalism** with **Swiss Editorial Precision**:
- Absolute adherence to pure pitch-black surfaces balanced against stark crisp whites and subtle graphite mid-tones.
- Deliberate use of monospaced typography for metadata, telemetry, commit hashes, and technology stacks, counterbalanced by structured grotesque sans-serifs for commanding titles.
- Thin hairline grid alignments reminiscent of technical blueprints and architectural manifests.

## Colors
The color foundation is built on an ultra-dark monochrome spectrum, calibrated to eliminate ocular fatigue while maximizing structural legibility.

- **Primary (`#F8FAFC`)**: Crisp, luminescent off-white used for primary headlines, active interactive labels, and focal indicators.
- **Secondary (`#94A3B8`)**: Cool zinc-slate midtone for secondary body prose, passive metadata, and structural outlines.
- **Tertiary (`#38BDF8`)**: Restrained cyan spark, applied with extreme parsimony strictly for live system indicators, git diff additions, or terminal highlights.
- **Neutral (`#090A0F`)**: Deepest void black, providing the infinite canvas backdrop upon which micro-borders establish containment.

### Functional Tones
- **Canvas Base**: `#090A0F`
- **Surface Elevation 1 (Card/Panel)**: `#0F1117`
- **Surface Elevation 2 (Popover/Hover State)**: `#181B22`
- **Hairline Border Subdued**: `rgba(248, 250, 252, 0.08)`
- **Hairline Border High-Contrast**: `rgba(248, 250, 252, 0.18)`
- **Text Muted**: `#64748B`

## Typography
Typography is treated as the primary graphical medium. The tension between the geometric grotesque neutrality of Geist and the surgical utility of JetBrains Mono creates visual cadence.

- **Headings (`Geist`)**: Tight letter spacing with strict vertical rhythm. Never bold beyond weight `600`; titles rely on scale, negative space, and stark lightness rather than brute weight.
- **Body Prose (`Inter`)**: Set with generous line heights to preserve long-form readability across dense technical architectural write-ups.
- **Metadata & Data Accents (`JetBrains Mono`)**: Always used for technical attributes, repository tags, commits, statistics, project durations, and numerical indexes. Applied in uppercase for category dividers (`label-caps`).

## Layout & Spacing
The layout follows a 12-column fixed-max modular grid anchored to a standard width of `1200px` for editorial balance, or fluidly stretching on dashboard viewports with hard perimeter margins.

### Grid & Breakpoints
- **Desktop (>= 1024px)**: 12-column grid, `gutter`: 1.5rem, `margin`: 3rem (or centered with auto margins).
- **Tablet (768px - 1023px)**: 8-column grid, `gutter`: 1rem, `margin`: 2rem.
- **Mobile (< 768px)**: 4-column grid, `gutter`: 1rem, `margin-mobile`: 1.25rem.

### Spacing Rhythm
Spacing is geometric and architectural. Sections are punctuated by generous vertical gutters (`space-xl` and above) contrasted with dense, tightly controlled clusters of information inside cards and navigation ribbons (`space-xs` and `space-sm`). Grid guides are frequently rendered as visible hairline rules that span edge-to-edge across the viewport.

## Elevation & Depth
Elevation in this system discards volumetric blur shadows entirely in favor of **Tonal Layers and Micro-Outlines (Ghost Borders)**. Depth is planar, discrete, and tactile.

- **Level 0 (Base Canvas)**: Absolute `#090A0F`.
- **Level 1 (Structural Cards & Sections)**: `#0F1117` encapsulated by a 1px solid border of `rgba(248, 250, 252, 0.08)`.
- **Level 2 (Dropdowns, Floating Palettes, Modals)**: `#181B22` with a 1px solid border of `rgba(248, 250, 252, 0.16)` and an ambient, non-colored proximity falloff (`0 16px 32px rgba(0, 0, 0, 0.6)`).
- **Interactive State Elevation**: Surfaces do not float up on hover via displacement; instead, their borders brighten from `0.08` to `0.24` opacity, accompanied by an instantaneous surface shift to a micro-highlight tone (`#141720`).

## Shapes
Geometry is disciplined, razor-sharp, and subtly restrained. A roundedness factor of `1` (Soft: 0.25rem / 4px base radius) is universally maintained.

- **Cards, Panels, Inputs, Code Blocks**: 4px radius (`rounded`). Never exceed 8px (`rounded-lg`) even on full-screen containers.
- **Pills & Status Indicators**: Status indicator pips remain pure circles (100% radius); technical metadata tags retain the strict 4px radius or absolute 0px sharp corners to maintain the aesthetic of an engineering schematic.

## Components

### Buttons
- **Primary**: Solid crisp off-white background (`#F8FAFC`), deep black text (`#090A0F`), font `Inter` or `Geist` weight 500, 4px border radius. No border. On hover, background shifts to pure `#FFFFFF` with high luminance.
- **Secondary / Ghost**: Background `transparent`, 1px border `rgba(248, 250, 252, 0.12)`, text `#F8FAFC`. On hover, border shifts to `rgba(248, 250, 252, 0.35)` and background to `rgba(248, 250, 252, 0.03)`.
- **Icon Actions**: Compact 32x32px square buttons framed with 1px hairline borders.

### Badges & Tech Chips
- Rendered using `label-mono` or `label-caps` in `JetBrains Mono`.
- Background: `rgba(248, 250, 252, 0.03)`.
- Border: 1px solid `rgba(248, 250, 252, 0.08)`.
- Padding: 2px 8px.
- Subtle status badges incorporate a 4x4px glowing dot indicator (e.g., `#38BDF8` for active status).

### Cards & Project Showcases
- Background: `#0F1117`.
- Border: 1px hairline `rgba(248, 250, 252, 0.08)`.
- Internal Padding: `space-lg` (28px).
- Internal layout cleanly isolates project titles, metric columns, and code snippets with delicate inner horizontal rules (`1px solid rgba(248, 250, 252, 0.05)`).

### Input Fields & Command Palettes
- Background: `#090A0F` or `#0F1117`.
- Border: 1px solid `rgba(248, 250, 252, 0.12)`.
- Typography: `Inter` for standard input, `JetBrains Mono` for command query inputs.
- Focus State: Border transitions immediately to `#F8FAFC`; zero ring outline glow.

### Lists & Activity Feeds
- Structured as continuous tables with hairline divider lines (`rgba(248, 250, 252, 0.06)`).
- Alternate row striping is avoided; differentiation is achieved solely through crisp tabular monospaced metadata columns (dates, hashes, scopes) alongside grotesque sans descriptions.

### Code Snippets & Terminal Modules
- Header bar with title, directory path in `JetBrains Mono`, and active branch/status tags.
- Background: `#07080B` with 1px border. Syntax highlighting constrained to high-contrast monochrome with targeted desaturated cyan (`#38BDF8`) for keywords.