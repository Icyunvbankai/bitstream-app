---
name: Obsidian Audio
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#3a393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#baccb0'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#85967c'
  outline-variant: '#3c4b35'
  surface-tint: '#2ae500'
  primary: '#efffe3'
  on-primary: '#053900'
  primary-container: '#39ff14'
  on-primary-container: '#107100'
  inverse-primary: '#106e00'
  secondary: '#c8c5cb'
  on-secondary: '#303034'
  secondary-container: '#47464b'
  on-secondary-container: '#b6b4b9'
  tertiary: '#fff8f7'
  on-tertiary: '#442927'
  tertiary-container: '#ffd3ce'
  on-tertiary-container: '#7a5955'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#79ff5b'
  primary-fixed-dim: '#2ae500'
  on-primary-fixed: '#022100'
  on-primary-fixed-variant: '#095300'
  secondary-fixed: '#e4e1e7'
  secondary-fixed-dim: '#c8c5cb'
  on-secondary-fixed: '#1b1b1f'
  on-secondary-fixed-variant: '#47464b'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#e7bdb8'
  on-tertiary-fixed: '#2c1513'
  on-tertiary-fixed-variant: '#5d3f3c'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: -0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: -0.01em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 12px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.25rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes an ultra-focused, high-fidelity listening environment tailored for technical operators, tech-savvy founders, and modern creators. Built on the ethos of "Zero Filler. All Value.", the aesthetic pairs the surgical precision of an audio workstation with the kinetic energy of contemporary electronic media.

The visual direction combines high-contrast dark mode with controlled neon luminescence. Dark obsidian layers recess non-essential chrome into the background, pushing dynamic waveforms and primary podcast artwork directly into focus. Electric neon accents guide real-time audio interaction (scrubbing, playback state, live badges), functioning like LED indicators on studio audio monitors. The interface evokes hyper-clarity, technical competence, and high-frequency utility.

## Colors

The palette is engineered around pure visual depth and precise light emission.

- **Primary (`#39FF14`):** Electric Neon Green. Reserved exclusively for playback states, active indicators, live status pills, scrub heads, and primary callouts. Use with a restrained touch to prevent visual exhaustion.
- **Secondary (`#1A1A1E`):** Raised Surface. Applied to elevated cards, control sheets, and floating audio drawers.
- **Surface Dark (`#141416`):** Base Surface. Used for list containers, persistent bars, and card containers sitting over the root canvas.
- **Neutral / Canvas (`#0A0A0B`):** Deep Obsidian Canvas. Zero-glare base layer designed to blend seamlessly with mobile OLED screens.
- **Typography & Details:**
  - Primary Content / Headings: Crisp White (`#FFFFFF`) at high contrast.
  - Secondary / Supporting: Slate Gray (`#A1A1AA`) for episode summaries, authors, and channel metadata.
  - Tertiary / Timestamps: Muted Metal (`#8E8E93`) for passive indicators, playback duration, and scrub rails.
  - Subtle Accent Stroke: Semi-translucent Neon (`rgba(57, 255, 20, 0.15)`) for active component boundaries and laser-cut borders.

## Typography

The type scale combines the high-efficiency neutral form of **Inter** for conversational reading with the calibrated cadence of **JetBrains Mono** for machine-level metadata.

- **Inter** handles all human narrative: show titles, episode titles, summaries, and menu hierarchies. Negative letter-spacing on headline styles creates a condensed, premium editorial impact.
- **JetBrains Mono** is deployed for operational audio metrics: playback timestamps (`02:44 / 48:12`), playback speeds (`1.5x`), scrubber positions, data badges, bitrate indicators, and section tracking tags. Monospaced figures prevent layout shifts during live streaming and playback scrubbing.

## Layout & Spacing

This design system uses an ergonomics-first, single-column fluid mobile layout contained inside a 390px-to-430px mobile canvas, with full support for safe area insets (notches, dynamic islands, home bars).

- **Grid & Columns:** Standard 4-column layout on mobile devices with `0.75rem` (`12px`) inner gutters and `1rem` (`16px`) outer margins. For larger viewports or mini-tablets, expand to a 6-column grid with `1.25rem` gutters.
- **Thumb-Zone Optimization:** The primary interactive zone is anchored to the bottom 45% of the viewport. The persistent Mini-Player floats directly above the Bottom Navigation Bar, remaining reachable by one-handed gesture controls.
- **Rhythm & Stacking:** Vertical stacks maintain consistent `1rem` separation between track entries and `1.5rem` between curated modules (e.g., "Top Clips", "Network Shows").

## Elevation & Depth

Visual depth is achieved through structural tonal layering and selective neon edge-glows rather than traditional diffuse drop shadows.

- **Base Canvas (Level 0):** Deep Black (`#0A0A0B`), solid and unblurred.
- **Cards & Surface Containers (Level 1):** `#141416` with a delicate, crisp border stroke of `rgba(255, 255, 255, 0.06)`.
- **Raised Interactive Modules (Level 2):** `#1A1A1E` with subtle ambient blur (`backdrop-filter: blur(16px)` on floating navigation panels) and a top hair-line border of `rgba(255, 255, 255, 0.12)`.
- **Active State Illumination:** Selected elements or currently playing tracks display a perimeter border of `rgba(57, 255, 20, 0.35)` accompanied by a focused, low-spread ambient glow: `0 0 16px rgba(57, 255, 20, 0.18)`.

## Shapes

The geometry balances modern softened corners with architectural stability.

- **Cards & Containers (`rounded-lg` / 16px):** Standardizes show cards, full episode banners, and clip reels with balanced curvature that does not clip complex audio wave graphics.
- **Interactive Controls (`rounded` / 8px):** Applied to standard control buttons, input wrappers, modal sheets, and thumbnail media artwork.
- **Pills (`rounded-full`):** Reserved for badges (e.g., "LIVE", "DEMO", "CLIPS"), audio scrub heads, category filters, and pill action buttons.

## Components

### Buttons
- **Primary Action (Play / Subscribe):** Neon green (`#39FF14`) solid background, pure black text (`#0A0A0B`) in `Inter SemiBold`. On hover/tap, trigger an internal glow with no change to core text contrast.
- **Secondary Action (Queue / Download):** Surface dark (`#1A1A1E`) with crisp hairline border (`rgba(255, 255, 255, 0.12)`) and pure white text.
- **Icon Buttons (Shuffle / Skip / Heart):** Fully transparent background with muted gray icon (`#A1A1AA`), switching to `#39FF14` with a gentle radial pulse when toggled active.

### Chips & Badges
- **Status Pills (DEMO / EXCLUSIVE / LIVE):** Pill-shaped with dark glass fill (`rgba(57, 255, 20, 0.08)`), vibrant neon green border (`rgba(57, 255, 20, 0.4)`), and text in `JetBrains Mono` (`label-sm`, uppercase).
- **Filter Tags:** Dark secondary surface (`#141416`), `body-sm` font, transitioning to solid neon green outline when selected.

### Lists & Track Items
- **Episode Rows:** Flush card surfaces (`#141416`) with a 48x48px album thumbnail, bold episode title in `headline-sm`, metadata (release date + duration) in `JetBrains Mono` (`label-md`, `#8E8E93`).
- **Active Episode Item:** Left-side 2px neon green active border indicator accompanied by an animated 3-bar green waveform equalizer indicator.

### Waveform Visualizer & Scrubber
- Consists of vertical audio bar segments spaced 2px apart.
- Unplayed segments render at `#1A1A1E` or `rgba(255, 255, 255, 0.2)`. Played segments light up in `#39FF14`.
- The scrub head is a luminous neon pill displaying current playback position in `label-sm`.

### Form Fields & Search
- Solid `#141416` fill, `0.5rem` border radius, with `1px` stroke in `rgba(255, 255, 255, 0.08)`.
- Active focus state: Stroke switches to `#39FF14` accompanied by a localized neon outline glow (`0 0 8px rgba(57, 255, 20, 0.2)`).

### Bottom Navigation Bar
- Fixed at the screen base with integrated safe-area padding.
- Semi-transparent obsidian layer (`#0A0A0B` with 85% opacity, `backdrop-filter: blur(20px)`).
- Five icons: **Home**, **Discover**, **Clips**, **Library**, **Shop**.
- Inactive icons: `#8E8E93`. Active icon: `#39FF14` paired with an electric micro-dot indicator below.