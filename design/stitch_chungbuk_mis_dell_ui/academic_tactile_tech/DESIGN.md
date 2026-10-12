---
name: Academic Tactile & Tech
colors:
  surface: '#f6fafe'
  surface-dim: '#d6dade'
  surface-bright: '#f6fafe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4f8'
  surface-container: '#eaeef2'
  surface-container-high: '#e4e9ed'
  surface-container-highest: '#dfe3e7'
  on-surface: '#171c1f'
  on-surface-variant: '#444651'
  inverse-surface: '#2c3134'
  inverse-on-surface: '#edf1f5'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#00312c'
  on-tertiary: '#ffffff'
  tertiary-container: '#004942'
  on-tertiary-container: '#4ebdb0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#f6fafe'
  on-background: '#171c1f'
  surface-variant: '#dfe3e7'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses the intersection of business strategy, data analytics, and computational technology for an institutional academic department. The aesthetic balances collegiate credibility with tactile digital craftsmanship.

### Core Philosophy
- **Tactile Academic Authority**: Moving away from sterile, flat institutional portals, surfaces use a calibrated Neumorphic (Soft UI) treatment. Extruded planes and recessed troughs feel physical yet precise, evoking high-end hardware consoles and modern analytical dashboards.
- **Academic Rigor & Innovation**: Grounded in classic collegiate navy, punctuated with electric cobalt for data streams and emerald teal for software engineering.
- **Clarity Over Gimmick**: Soft dual-shadow depth is tightly restrained to maintain crisp visual hierarchy, optimal accessibility, and high information density.

### Emotional Target
- **Prospective & Current Students**: Inspires confidence, technological curiosity, and clarity across academic roadmaps and course modules.
- **Faculty & Industry Partners**: Conveys institutional stability, research depth, and contemporary technical relevance.

## Colors

The palette operates strictly in light mode to provide the tonal contrast necessary for light and dark drop shadows to sculpt soft surfaces.

### Palette Architecture
- **Primary (`#1E3A8A`)**: Collegiate Royal Navy. Represents business governance, academic heritage, and structural integrity. Applied to key brand landmarks, major headings, and primary calls to action.
- **Secondary (`#3B82F6`)**: Electric Cobalt. Signals data pipelines, live computational metrics, active states, and interactive links.
- **Tertiary (`#0D9488`)**: Tech Emerald / Mint. Denotes software engineering tracks, code syntax success markers, and active research badges.
- **Neutral Canvas (`#F0F4F8`)**: Pale Slate Off-White. The foundational clay canvas tuned specifically to let pure white light highlights (`#FFFFFF`) pop on the top-left while casting cool tinted slate shadows (`rgba(166, 180, 200, 0.6)`) to the bottom-right.
- **High-Readability Ink (`#0F172A` & `#1E293B`)**: Ultra-deep slate neutrals ensure WCAG AAA compliance for body text, avoiding the low-contrast legibility pitfalls typical of unrefined Neumorphism.

## Typography

The typographic hierarchy pairs the friendly modern curves of `Plus Jakarta Sans` for editorial headings with the neutral, analytical clarity of `Inter` for body copy, tabular grids, and labels.

### Typographic Guidelines
- **Headings**: Set tight letter spacing (`-0.01em` to `-0.02em`) on display sizes to give titles a cohesive, authoritative weight against soft surfaces.
- **Code & Query Accents**: When displaying course identifiers (e.g., `MIS-301`), SQL statements, or algorithm snippets, apply system monospaced stacks (`ui-monospace`, `SFMono-Regular`, `Menlo`, `Consolas`) using `body-sm` proportions with slightly expanded line height.
- **Numeric & Metric Readouts**: Use tabular figures (`font-variant-numeric: tabular-nums`) on all analytical counters, GPA trackers, and curriculum credit matrices to maintain vertical alignment.

## Layout & Spacing

Layouts rely on a 12-column responsive fluid grid designed to host multi-panel administrative workflows, academic curriculum maps, and real-time announcement boards.

### Grid & Breakpoints
- **Desktop (≥ 1200px)**: 12 columns, `gutter: 1.5rem` (24px), outer canvas `margin: 2rem` (32px). Maximum container width is constrained to 1440px to prevent Neumorphic cards from stretching into low-density spans.
- **Tablet (768px – 1199px)**: 8 columns, `gutter: 1.25rem` (20px), outer canvas `margin: 1.5rem` (24px). Sidebar navigations collapse into floating soft-dock navigation bars.
- **Mobile (< 768px)**: 4 columns, `gutter: 1rem` (16px), outer canvas `margin: 1rem` (16px). Dual-shadow offsets scale down proportionally to maintain sharp contrast on smaller display densities.

### Rhythmic Discipline
Neumorphic dual shadows extend 6px to 14px outward from container perimeters. Spacing tokens (`space-md`, `space-lg`, `space-xl`) must be strictly maintained between adjacent surfaces to guarantee that shadow radii never overlap into muddy, dark artifacts.

## Elevation & Depth

Depth is modeled as a physical plane sculpted from a single slab of matte material under directional light emanating from the top-left (135° illumination angle).

### Soft Elevation Scale
1. **Level 0 (Flat Canvas)**:
   - Background: `#F0F4F8`.
   - Used for the primary screen backdrop.

2. **Level 1 (Extruded Surface - Resting Cards & Panels)**:
   - Surface: `#F0F4F8` with smooth gradient fill (`linear-gradient(145deg, #ffffff, #e6ebf0)`).
   - Drop Shadow: `6px 6px 14px rgba(166, 180, 200, 0.6), -6px -6px 14px rgba(255, 255, 255, 0.9)`.
   - Used for curriculum cards, announcement list containers, and professor profile blocks.

3. **Level 2 (Extruded Floating - Hover & Modals)**:
   - Drop Shadow: `10px 10px 22px rgba(166, 180, 200, 0.7), -10px -10px 22px rgba(255, 255, 255, 1.0)`.
   - Applied during hover states on interactive cards, active popovers, and dialogs.

4. **Level -1 (Recessed / Inset Wells - Data & Input Containers)**:
   - Inset Shadow: `inset 4px 4px 8px rgba(166, 180, 200, 0.5), inset -4px -4px 8px rgba(255, 255, 255, 0.9)`.
   - Background: `#EBF0F5`.
   - Used for search inputs, terminal/code snippet blocks, data visualizer troughs, and checked/pressed toggle states.

## Shapes

With a roundedness index of `2`, the shape vocabulary prioritizes organic, machined contours that allow dual-source light gradients to wrap smoothly around container corners without visual pinching.

### Radii Application
- **Standard (`rounded`, 0.5rem / 8px)**: Segmented controls, input fields, code chips, and small table cells.
- **Large (`rounded-lg`, 1rem / 16px)**: Standard cards, data metric panels, notice boards, and dialog modals.
- **Extra Large (`rounded-xl`, 1.5rem / 24px)**: Hero feature panels, curriculum track containers, and prominent dashboard clusters.
- **Full Pill (`rounded-full`)**: Department status chips, live tech badges, and floating action button clusters.

## Components

### Buttons
- **Primary Action**: Extruded soft navy gradient (`linear-gradient(145deg, #2344a0, #1b347c)`), white label, with a deep navy shadow blend (`4px 4px 10px rgba(30, 58, 138, 0.35), -3px -3px 8px rgba(255, 255, 255, 0.8)`).
- **Secondary / Soft Button**: Canvas-matching background (`#F0F4F8`), standard Level 1 extruded shadow, primary navy label. On hover, shadows deepen slightly; on `:active`, shadows flip instantaneously to Level -1 inset, producing a tactile mechanical click sensation.

### Input Fields & Search Bars
- Recessed Level -1 inset well. `#0F172A` text entry with `#64748B` placeholder tone.
- **Focus State**: A subtle 1.5px outline in secondary cobalt (`#3B82F6`) with an internal light halo (`inset 2px 2px 4px rgba(59, 130, 246, 0.15)`).

### Chips & Badges
- **Academic Track Chips**: Pill-shaped recessed or low-extrusion tags.
  - *Management / Business*: Navy accent border with subtle blue tint.
  - *Data Analytics*: Secondary cobalt icon with semi-translucent pill container.
  - *Software Engineering*: Mint/Emerald tertiary dot badge (`#0D9488`) with monospace text.

### Cards & Dashboards
- Structural cards use Level 1 extruded depth with 16px internal padding. 
- Headers feature sharp ink typography (`#0F172A`) sitting directly on the matte surface.
- Sub-sections within cards (such as code preview snippets or data summary cards) nest smoothly into Level -1 inset wells to create natural, borderless visual hierarchy.

### Lists & Notice Boards
- Rows sit on a continuous flat canvas separated by soft indented divider channels or alternating low-depth extruded item strips on hover.
- Post dates and category prefixes use crisp label typography with monospace metadata tags.

### Checkboxes & Switches
- **Switch Track**: Recessed Level -1 pill groove.
- **Switch Thumb**: Extruded Level 1 circular nub that glides smoothly into an illuminated cobalt-tinted active state.