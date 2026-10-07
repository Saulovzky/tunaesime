---
name: Prestigio Politécnico
colors:
  surface: '#111412'
  surface-dim: '#111412'
  surface-bright: '#373a37'
  surface-container-lowest: '#0c0f0d'
  surface-container-low: '#191c1a'
  surface-container: '#1d201e'
  surface-container-high: '#282b28'
  surface-container-highest: '#323533'
  on-surface: '#e1e3df'
  on-surface-variant: '#bfc9bd'
  inverse-surface: '#e1e3df'
  inverse-on-surface: '#2e312f'
  outline: '#899388'
  outline-variant: '#404940'
  surface-tint: '#8ad89b'
  primary: '#8ad89b'
  on-primary: '#003919'
  primary-container: '#005a2b'
  on-primary-container: '#83d094'
  inverse-primary: '#1e6c3b'
  secondary: '#7dda8f'
  on-secondary: '#003916'
  secondary-container: '#007032'
  on-secondary-container: '#93f1a4'
  tertiary: '#bdc8d3'
  on-tertiary: '#28313b'
  tertiary-container: '#454f59'
  on-tertiary-container: '#b6c0cc'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#a6f4b6'
  primary-fixed-dim: '#8ad89b'
  on-primary-fixed: '#00210c'
  on-primary-fixed-variant: '#005227'
  secondary-fixed: '#99f7a9'
  secondary-fixed-dim: '#7dda8f'
  on-secondary-fixed: '#00210a'
  on-secondary-fixed-variant: '#005323'
  tertiary-fixed: '#dae3f0'
  tertiary-fixed-dim: '#bdc8d3'
  on-tertiary-fixed: '#131d25'
  on-tertiary-fixed-variant: '#3e4852'
  background: '#111412'
  on-background: '#e1e3df'
  surface-variant: '#323533'
typography:
  display-xl:
    fontFamily: Bodoni Moda
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 88px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Bodoni Moda
    fontSize: 44px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 38px
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: Bodoni Moda
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Metrophobic
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Metrophobic
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Metrophobic
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.14em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.18em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 9px
    fontWeight: '400'
    lineHeight: 12px
    letterSpacing: 0.22em
spacing:
  gutter: 2rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-mobile: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

The design system embodies the rare convergence of centuries-old university musical tradition and haute-editorial luxury. Tailored for Tuna de la Escuela Superior de Ingeniería Mecánica y Eléctrica (ESIME) Zacatenco, the aesthetic balances historic collegiate dignity with avant-garde artistic poise.

The emotional tone evokes academic reverence, virtuosic musicianship, and aristocratic heritage without appearing antique or nostalgic. It treats collegiate musical traditions as living cultural art pieces. The style fuses **High-Contrast Editorial Typography** and **Refined Architectural Layouts**—characterized by crisp hairline rules, measured asymmetrical white space, micro-scale typography paired with monumental display titles, and tactile mineral finishes.

Key style guidelines:
- **Haute Editorial Rigor**: Compositions echo archival exhibition catalogues and classical music monographs.
- **Asymmetrical Tension**: Reject template-driven centered layouts. Use intentional offsets, left-anchored heavy typography balanced against delicate media framing.
- **Micro-Detailing**: Hairline dividers, subtle roman numerals, precise catalog labeling (`OPUS`, `ACTO`, `ARCHIVUM`), and subtle silver edge reflections.

## Colors

The palette draws strictly from historic IPN (Instituto Politécnico Nacional) academic iconography, transmuted into luxury finishes. 

- **Obsidian Dark Canvas (`#0A0D0B`)**: An ultra-deep chromatic black tinted with the faintest verdant undertone, serving as the dominant background.
- **Verde Bandera Imperial (`#005A2B`, `#007032`)**: The definitive Mexican university flag green. Used with surgical restraint for focal accents, audio playheads, key status indicators, and selected luxury focal points. Never oversaturated across wide containers.
- **Mineral Silver & Platinum (`#CBD5E1`, `#94A3B8`, `#334155`)**: Architectural structural colors. Used for hairlines, metadata, borders, and subheadings to maintain high elegance without visual clutter.
- **Crisp Archival White (`#F8FAFC`)**: Reserved for primary display text, high-priority numerals, and key actions to command immediate authority.

Surface hierarchies are defined through tonal layering rather than standard dropshadows:
- `surface-base`: `#0A0D0B`
- `surface-elevated`: `#111613`
- `surface-interactive`: `#17201B`
- `border-hairline`: `rgba(203, 213, 225, 0.14)`
- `border-active`: `rgba(0, 112, 50, 0.45)`

## Typography

The typographical pair establishes high-contrast hierarchy:
- **Bodoni Moda** provides the dramatic, razor-sharp serif serifs characteristic of luxury editorial editions and academic ceremony. It must be rendered with optical sizing enabled where available.
- **Metrophobic** provides the structural, calm geometric counterweight. Its understated mid-century modern lines ensure performance annotations, historical essays, and technical tour data remain readable.
- **JetBrains Mono** acts as the archival numbering and indexing layer. It renders catalogue registers, timecodes, instrumentation rosters, and performance metadata in a precise monospaced cadence.

Editorial Rules:
- Display headings should always favor sentence casing or strict small-caps tracking; avoid default capitalized title cases.
- Use `label-md` and `label-sm` strictly in full uppercase with wide tracking (`0.18em` to `0.22em`) for archival tags (`REGISTRO 04`, `SOLISTA`, `PASACALLES`).

## Layout & Spacing

The layout philosophy rejects symmetrical modularity in favor of an **Asymmetrical Editorial Grid**:
- **Desktop (1200px+)**: 12-column architectural grid with generous `4rem` lateral margins. Columns frequently pair in unexpected groupings: a 4-column informational sidebar running alongside an 8-column media showcase, offset vertically by `2rem`.
- **Tablet (768px - 1199px)**: 8-column grid with `2.5rem` margins and `1.5rem` gutters.
- **Mobile (< 768px)**: 4-column structured grid with `1.5rem` outer margins. Content reflows into vertical ledger lists rather than miniaturized cards.

Gridlines are frequently surfaced explicitly using `1px` hairlines (`border-hairline`) to evoke classical ledger plates and sheet music manuscripts. Elements must maintain intentional negative space: whitespace is considered an active luxury material.

## Elevation & Depth

This system rejects floating, bubble-like drop shadows. Depth is communicated strictly via **Subtle Mineral Contrast and Hairline Layering**:
- **Depth Tier 0 (Base)**: `#0A0D0B` canvas.
- **Depth Tier 1 (Plinths & Plates)**: `#111613` with a crisp `1px` border of `rgba(203, 213, 225, 0.12)`.
- **Depth Tier 2 (Overlays & Audio Consoles)**: Glass-sheen obsidian surface utilizing `rgba(10, 13, 11, 0.88)` with a background blur filter of `16px` and an upper hairline accent of `rgba(203, 213, 225, 0.25)`.
- **Active State Glow**: Hovered or active elements receive a controlled, low-spread ambient backlight: `0 0 24px rgba(0, 112, 50, 0.18)`.

## Shapes

The design system uses a strict **Sharp (`0`)** shape language. 

- All buttons, media viewports, badges, input fields, and audio visualizer frames feature `0px` border-radius.
- Precision 90-degree corners create an authoritative, academic aesthetic reminiscent of framed certificates, fine bookbinding, and architectural prints.
- Micro-notches (chamfered corners cut at 45 degrees, `4px`) are permitted exclusively for primary commemorative badges and archival index tabs.

## Components

### Buttons
- **Primary (Sovereign)**: Pure obsidian base `#0A0D0B` encased in a solid `1px` border of `#007032`. Text in `label-md` uppercase `#F8FAFC`. On hover, the background transitions to `#005A2B` with a subtle silver letter tint (`#CBD5E1`).
- **Secondary (Archival Line)**: Transparent background, `1px` hairline of `rgba(203, 213, 225, 0.3)`. Text in `#CBD5E1`. On hover, border shifts to `#F8FAFC` with an ambient glow.
- **Tertiary (Ghost Link)**: Text-only Bodoni italic or Metrophobic uppercase with a persistent horizontal `1px` underline offset by `6px`.

### Chips & Archival Badges
- Rigid `0px` rectangular containers.
- Padding: `4px 10px`.
- Background: `rgba(203, 213, 225, 0.04)`.
- Border: `1px solid rgba(203, 213, 225, 0.18)`.
- Typography: `label-sm` monospaced silver text (`#94A3B8`).

### Lists (Ledger Row Pattern)
- Traditional cards are superseded by editorial ledger rows.
- Each item is delimited by top and bottom `1px` hairlines (`rgba(203, 213, 225, 0.1)`).
- Structure: Monospaced catalog index (`01.`, `02.`) on the left, primary Bodoni title centered or left-aligned, followed by year, city, and audio duration on the far right.
- On hover, the row illuminates with a `#111613` background fill and displays an emerald cursor indicator.

### Input Fields
- Understated architectural underlines or sharp boundary boxes.
- Background: `#0D120F`.
- Border: `1px solid rgba(203, 213, 225, 0.2)`. Focus border: `1px solid #007032`.
- Text: Metrophobic `#F8FAFC`. Placeholder: `#94A3B8` in `body-sm`.
- Labels float above in `label-sm` uppercase.

### Bespoke Media Components
- **Acoustic Player Bar**: Fixed docked bar at canvas bottom. Pure obsidian glass blur, featuring an unrounded scrub bar in `#005A2B` with an active playhead highlighted in `#CBD5E1`. Monospaced track timing and Bodoni italic song titles.
- **Archival Repertoire Frame**: High-contrast image containment with a double hairline border (an outer `#334155` border separated by `4px` of black space from an inner `rgba(203, 213, 225, 0.1)` rule).