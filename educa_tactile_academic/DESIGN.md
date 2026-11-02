---
name: EDUCA Tactile Academic
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#4d4354'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#7e7386'
  outline-variant: '#cfc2d7'
  surface-tint: '#861fdd'
  primary: '#7800ce'
  on-primary: '#ffffff'
  primary-container: '#9333ea'
  on-primary-container: '#f6e6ff'
  inverse-primary: '#ddb8ff'
  secondary: '#b4136d'
  on-secondary: '#ffffff'
  secondary-container: '#fd56a7'
  on-secondary-container: '#600037'
  tertiary: '#3c3cca'
  on-tertiary: '#ffffff'
  tertiary-container: '#5658e3'
  on-tertiary-container: '#eceaff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#ddb8ff'
  on-primary-fixed: '#2c0051'
  on-primary-fixed-variant: '#6800b4'
  secondary-fixed: '#ffd9e4'
  secondary-fixed-dim: '#ffb0cd'
  on-secondary-fixed: '#3e0022'
  on-secondary-fixed-variant: '#8c0053'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 3rem
    fontWeight: '800'
    lineHeight: 3.5rem
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.625rem
    fontWeight: '700'
    lineHeight: 2.125rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '700'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: 1rem
    letterSpacing: 0.04em
  code-inline:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
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

This design system expresses a vibrant, motivating, and tactile academic workspace tailored specifically for SENA ADSO (Análisis y Desarrollo de Software) apprentices in Colombia. It balances disciplined institutional clarity with the energy of contemporary software development tools.

### Persona & Context
- **Audience:** SENA technical apprentices, instructors, and evaluators operating across desktop workstations and mobile devices.
- **Tone:** Energetic, rigorous, approachable, and tactile. The UI avoids sterile bureaucracy, feeling like a premium developer portal that rewards momentum and project milestone completions.
- **Design Style:** Modern Tactile. The interface uses crisp white elevated surfaces floating above an ultra-subtle cool slate canvas, softened by high-radius geometry (`rounded-2xl` to `rounded-3xl`), vivid chromatic violet-to-fuchsia linear transitions, tactile button depth with physical micro-feedback, and delicate ambient indigo light bleeds.

## Colors

The palette is engineered around high-energy purples and tech-focused accents balanced against high-contrast slate neutrals to maintain strict WCAG AA compliance across text and functional components.

### Palette Architecture
- **Primary (`#9333EA` - Vivid Violet):** Primary actions, focal states, active navigation tabs, and key brand moments.
- **Secondary (`#EC4899` - Vibrant Fuchsia):** Milestone achievements, gamification accents, progress milestones, and accent endpoints in tactical gradients.
- **Tertiary (`#6366F1` - Tech Indigo):** Technical metadata, code tags, repository references, and contextual deep-learning modules.
- **Neutral Dark (`#0F172A` - Deep Slate):** Primary reading typography and solid dark interactive icons (contrast ratio exceeds 12:1 against pure white).
- **Neutral Subtle (`#64748B` - Slate Muted):** Secondary text, timestamps (GMT-5 indicators), breadcrumbs, and structural dividers.
- **Surface Canvas (`#F8FAFC` - Light Slate Canvas):** Default body background, ensuring crisp contrast separation against pure white cards.
- **Surface Container (`#FFFFFF` - Pure White):** Workspaces, assessment containers, and code review cards.
- **Border Subtle (`#E2E8F0` - Soft Edge):** Perimeter hairline borders across elevated elements.

### Status Indicators (ADSO Academic States)
- **En Progreso (In Progress):** Background `#EFF6FF`, Border `#BFDBFE`, Text `#1D4ED8` with `#3B82F6` indicator dot.
- **Pendiente (Pending Submission):** Background `#FFFBEB`, Border `#FDE68A`, Text `#B45309` with `#F59E0B` indicator dot.
- **Calificado (Graded / Approved):** Background `#F0FDF4`, Border `#BBF7D0`, Text `#15803D` with `#22C55E` indicator dot.
- **Requiere Ajustes (Action Required):** Background `#FEF2F2`, Border `#FECACA`, Text `#B91C1C` with `#EF4444` indicator dot.

## Typography

The platform employs **Plus Jakarta Sans** across all text hierarchies for its balanced geometry, wide aperture, and modern technological cadence. 

- **Display & Headings:** Set with tight tracking (`-0.015em` to `-0.03em`) and heavy weights (700/800) to create clear course unit hierarchies and structural orientation.
- **Body:** Uses regular (400) and medium (500) weights with generous line heights (`1.5` to `1.6`) to minimize reading fatigue during multi-chapter software curriculum reviews.
- **Labels & Microcopy:** Badges, timestamps, and metric labels use uppercase or semibold small-scale tokens with boosted letter-spacing for scannability.
- **Code Metadata:** Inline code snippets, Git hashes, and terminal commands within the platform consume `JetBrains Mono` as a supplementary monospace family.

## Layout & Spacing

EDUCA operates on an 8pt modular grid standard paired with a 12-column responsive fluid grid.

### Grid Anatomy
- **Desktop (≥ 1280px):** 12-column fluid grid, max container width `1440px`, `2rem` outer margins, `1.5rem` gutters.
- **Tablet (768px – 1279px):** 8-column layout, `1.5rem` margins, `1.25rem` gutters.
- **Mobile (≤ 767px):** 4-column layout, `1rem` margins, `1rem` gutters.

### Component Spacing Rationale
- `space-xs` (4px): Micro-gaps between status dots and text labels.
- `space-sm` (8px): Icon-to-text spacing in buttons, badge interior padding.
- `space-md` (16px): Internal element spacing within cards and input fields.
- `space-lg` (24px): Padding inside primary modules, metric cards, and dashboard panels.
- `space-xl` (40px): Vertical sectional separation between module blocks and unit headers.

## Elevation & Depth

To achieve a tactile, hyper-modern aesthetic without visual clutter, depth is structured across layered planar tiers using colored ambient drop-shadows combined with 1px border bounding.

### Elevation Hierarchy
1. **Base Flat (Level 0):** Canvas `#F8FAFC`. No shadow.
2. **Elevated Card (Level 1):** `#FFFFFF` surfaces. 
   - `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 4px 12px 0 rgba(15, 23, 42, 0.03);`
   - Bounded by `1px solid #E2E8F0`.
3. **Interactive Floating (Level 2 - Hover / Dropdowns):**
   - `box-shadow: 0 10px 25px -5px rgba(147, 51, 234, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04);`
   - Gives a light purple ambient lift under interactive modules.
4. **Primary Tactile Button (Resting):**
   - Background gradient: `linear-gradient(135deg, #9333EA 0%, #EC4899 100%)`.
   - Subtle bottom bevel: `box-shadow: 0 4px 14px 0 rgba(147, 51, 234, 0.39), inset 0 1px 0 0 rgba(255, 255, 255, 0.25);`
5. **Tactile Active (Pressed State):**
   - Translate `1px` downward, shadow reduces to `0 2px 6px 0 rgba(147, 51, 234, 0.3)`.

## Shapes

The interface embraces a hyper-rounded, approachable silhouette system that feels friendly yet technical.

- **Pills (`rounded-full`):** Reserved for interactive buttons, progress badges, status chips, and avatar containers.
- **Large Modular Containers (`1rem` / `rounded-2xl`):** Input containers, nested assignments, code blocks, and assessment feedback panels.
- **Section & Primary Cards (`1.5rem` / `rounded-3xl`):** Course summary cards, dashboard metrics panels, and floating modal sheets.

## Components

### Buttons
- **Primary Tactile Pill:** Pill-shaped (`rounded-full`), `px-6 py-3`, text `label-lg` in white. Background gradient (`#9333EA` to `#EC4899`). Features top inset reflection and ambient glow shadow. Active state depresses 1px.
- **Secondary Neutral Pill:** Pure white background, `1px solid #E2E8F0`, deep slate text. On hover: border tints to `#6366F1` with an ultra-light tint fill `#F8FAFC`.
- **Tertiary Ghost:** Pure text with an indigo hover background at 8% opacity.

### Status Badges & Chips
- **Geometry:** Height 28px, full pill curve (`rounded-full`), `px-3`, text `label-md`.
- **Anatomy:** Contains a 6px circular indicator dot on the leading edge, followed by uppercase or title-case text (e.g., `● Pendiente`, `● Calificado`, `● En progreso`).
- **Surface:** Soft-tinted pastel background with a matching 1px semi-transparent border to ensure contrast against white cards.

### Cards & Workspaces
- **Course & Lesson Cards:** Bounded by `rounded-3xl`, white background, `1px solid #E2E8F0`, padding `1.5rem`.
- **Hover Behavior:** Translates `-2px` on the Y-axis and shifts the shadow to violet-tinted elevation level 2.

### Form Inputs & Selectors
- **Input Fields:** Height 48px, `rounded-xl`, background `#FFFFFF`, border `1.5px solid #E2E8F0`, text `body-md` in `#0F172A`.
- **Focus State:** Border shifts to `#9333EA` with a concentric focus ring: `box-shadow: 0 0 0 3px rgba(147, 51, 234, 0.15)`.
- **Labels:** Positioned outside the field, formatted with `label-lg` in `#0F172A` with an optional secondary hint in `#64748B`.

### Academic Progress Bar
- **Track:** Height 8px, `rounded-full`, filled with `#E2E8F0`.
- **Indicator:** Animated gradient fill (`#9333EA` to `#EC4899`) with rounded ends, expressing real-time percentage completion of the ADSO competency.