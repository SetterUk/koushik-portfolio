---
name: Editorial Engineer
colors:
  surface: '#faf9fd'
  surface-dim: '#dbd9dd'
  surface-bright: '#faf9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f7'
  surface-container: '#efedf1'
  surface-container-high: '#e9e7eb'
  surface-container-highest: '#e3e2e6'
  on-surface: '#1a1b1e'
  on-surface-variant: '#43474f'
  inverse-surface: '#2f3033'
  inverse-on-surface: '#f1f0f4'
  outline: '#747780'
  outline-variant: '#c4c6d1'
  surface-tint: '#415e93'
  primary: '#103366'
  on-primary: '#ffffff'
  primary-container: '#2c4a7e'
  on-primary-container: '#9ebbf6'
  inverse-primary: '#acc7ff'
  secondary: '#476553'
  on-secondary: '#ffffff'
  secondary-container: '#c7e8d1'
  on-secondary-container: '#4c6957'
  tertiary: '#611d04'
  on-tertiary: '#ffffff'
  tertiary-container: '#7f3318'
  on-tertiary-container: '#ffa486'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#acc7ff'
  on-primary-fixed: '#001a40'
  on-primary-fixed-variant: '#28467a'
  secondary-fixed: '#c9ead3'
  secondary-fixed-dim: '#aeceb8'
  on-secondary-fixed: '#032012'
  on-secondary-fixed-variant: '#304d3c'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59e'
  on-tertiary-fixed: '#390b00'
  on-tertiary-fixed-variant: '#7a2f15'
  background: '#faf9fd'
  on-background: '#1a1b1e'
  surface-variant: '#e3e2e6'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-sm:
    fontFamily: Bricolage Grotesque
    fontSize: 44px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.02em
  display-sm-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
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
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses the balance between technical rigor and thoughtful human craftsmanship. Built for an AI/ML engineer and systems builder, it deliberately rejects the tropes of modern artificial intelligence interfaces: there are no glowing cyan gradients, dark glassmorphic overlays, or speculative cyberpunk motifs. Instead, it draws from high-end technical monographs, architecture portfolios, and mid-century editorial design.

The personality is intellectual, grounded, articulate, and tactile. It treats complex machine learning concepts, models, and codebases as tangible engineering artifacts worth curating with care. The aesthetic embraces an archival, print-inspired restraint—celebrating structured grids, generous negative space, purposeful line work, and physical paper-like warmth.

## Colors

The palette is rooted in tactile physical materials: unbleached cotton paper, printer’s ink, bookbinding linen, and mineral pigments.

- **Canvas & Surfaces:** The foundational ground is an ivory/cream base (`#F7F3EA`), paired with slightly stepped tonal layers: `#EFE9DC` for secondary surfaces and structural containers, and `#E4DDCF` for hairline rules and subtle divisions.
- **Ink & Typography:** Pure black is avoided. Primary text uses deep charcoal (`#202124`), providing decisive contrast while maintaining warmth. Muted text steps down to `#5A5A58`, and subtle metadata sits at `#787774`.
- **Primary Accent (Muted Cobalt - `#2c4a7e`):** Serves as the authoritative engineering anchor, used for key interactive triggers, links, and system highlights.
- **Secondary Accent (Sage Green - `#5a7865`):** Denotes stable system states, model convergence, organic research milestones, and verified production status.
- **Tertiary Accent (Terracotta / Peach - `#d97757`):** Adds warmth, used for active benchmarks, in-progress experimental tags, and contextual warnings.
- **Auxiliary Editorial Accents:** Muted lavender (`#8e82a6`), soft sky blue (`#89a8c4`), and pale ochre (`#dfb15b`) are reserved for data visualization categories, taxonomy tags, and multi-class distribution graphs.

## Typography

Typography establishes an intentional dialogue between expressive editorial display and technical instrument precision.

- **Headlines & Display:** **Bricolage Grotesque** introduces warmth, subtle historic quirks, and authoritative structure. It anchors project titles, section headings, and hero narratives with human personality.
- **Body & Longform:** **Hanken Grotesk** handles project descriptions, case studies, and essays with neutral, high-legibility clarity. It keeps long prose natural and unobtrusive.
- **Technical & Data Elements:** **JetBrains Mono** is employed for metadata, code snippets, mathematical symbols, performance metrics (latency, parameter sizes, throughput), and taxonomy labels. It keeps technical attributes distinct from editorial prose.

## Layout & Spacing

The layout is built upon an editorial broadsheet discipline using a fixed-fluid hybrid grid.

- **Desktop (>= 1200px):** 12-column grid with a maximum content container width of 1280px. Outer margins sit at `2.5rem` (40px) with `1.5rem` (24px) gutters. Asymmetrical splits (e.g., 4 columns for technical specifications/metadata vs. 8 columns for narrative documentation and interactive demos) create editorial pace.
- **Tablet (768px – 1199px):** 8-column layout with `2rem` (32px) margins and `1.25rem` (20px) gutters. Complex multi-column comparisons compress into balanced two-column modules.
- **Mobile (< 768px):** 4-column layout with `1.25rem` (20px) margins and `1rem` (16px) gutters. Layout collapses into a single vertical stream where horizontal hairline rules partition independent thoughts.

Spacing rhythm values strictly dictate element separation. Negative space is treated as an active framing device rather than passive void, reinforcing an unhurried, archival presence.

## Elevation & Depth

This design system abandons drop shadows in favor of editorial framing, tonal layering, and crisp architectural rules.

- **Surface Layers:** The background canvas rests on `#F7F3EA`. Elevated modules, code blocks, and card surfaces sit on `#EFE9DC` or `#FFFFFF` (pure stark paper contrast), maintaining a flat, book-like plane.
- **Hairline Boundaries:** Depth is defined through 1px solid borders (`#E4DDCF` for passive separation, `#202124` for focal structural framing). Elements do not float; they are set into dedicated grid cells.
- **Hover & Interaction Shift:** Instead of elevated vertical shadow lift, interactive states use physical tactile cues: a 1px solid hairline shift, background micro-tinting toward `#EFE9DC`, or an intentional ink-density change.

## Shapes

The geometric personality is architectural and precise. Standard components leverage a minimal 4px (`0.25rem`) corner radius, avoiding cold mechanical razor-edges while maintaining the structure of trimmed print plates. 

Larger containers (such as interactive visualizers and modal inspection drawers) scale to 8px (`0.5rem`). Circular or pill radii are strictly restricted to metric status indicators and numerical badges.

## Components

### Buttons
- **Primary:** Deep charcoal background (`#202124`), ivory text (`#F7F3EA`), 4px border radius. Hover introduces a transition to muted cobalt (`#2c4a7e`).
- **Secondary / Outline:** 1px border in `#202124` over a transparent base, charcoal text. Hover fills the background with `#EFE9DC`.
- **Text / Inline Action:** Deep charcoal text with a permanent 1px underline offset by 4px; transitions to muted cobalt on hover with a crisp 150ms ease.

### Chips & Badges
- **Architecture:** Rendered with `JetBrains Mono` at `label-sm`.
- **Appearance:** 1px border (`#E4DDCF`), cream ground (`#EFE9DC`), 4px radius. 
- **Variants:** Category chips take muted tonal fills (e.g., sage green tint `#5a786515` with text `#5a7865` for "NLP / Production"; terracotta tint `#d9775715` with text `#d97757` for "PyTorch / Research").

### Lists & Technical Indexes
- Ordered and unordered lists use hairline dividers (`1px solid #E4DDCF`) between rows.
- Index indicators (e.g., `01`, `02`, `[0x1]`) are aligned left using `JetBrains Mono` in `#787774`, separating metadata cleanly from title strings.

### Cards & Project Plates
- Constructed on a `#FFFFFF` or `#EFE9DC` ground framed with a 1px border (`#E4DDCF`).
- Content partitions within cards (header, interactive demo area, parameter table, footer links) are separated by internal 1px horizontal hairline rules.

### Input Fields & Terminal Controls
- Clean 1px border (`#202124` on focus, `#E4DDCF` at rest), background `#FFFFFF`, typography in `JetBrains Mono`.
- Clear, unadorned labels positioned strictly above the input field with accompanying variable types (e.g., `input_prompt: string`).

### Code Blocks & Model Spec Sheets
- Background is `#EAE4D7` with an embedded 1px border (`#DDD6C7`).
- Header bar includes filename, parameter count, and language badge separated by vertical rule dividers.
- Monospaced typography with syntax tokens rendered in desaturated editorial hues (cobalt, sage, ochre, terracotta).