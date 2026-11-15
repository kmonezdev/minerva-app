---
name: Expreso Marvisur Mobile
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#5c403c'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#916f6a'
  outline-variant: '#e6bdb7'
  surface-tint: '#be0e0e'
  primary: '#b20007'
  on-primary: '#ffffff'
  primary-container: '#d7261e'
  on-primary-container: '#fff1ee'
  inverse-primary: '#ffb4a9'
  secondary: '#b4271d'
  on-secondary: '#ffffff'
  secondary-container: '#fe5c4b'
  on-secondary-container: '#610001'
  tertiary: '#575757'
  on-tertiary: '#ffffff'
  tertiary-container: '#706f6f'
  on-tertiary-container: '#f6f3f3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4a9'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930004'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4a9'
  on-secondary-fixed: '#410001'
  on-secondary-fixed-variant: '#910908'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474746'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '800'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-code:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  currency-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 22px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1rem
  margin-tablet: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system serves as an enterprise-grade, field-tested mobile operating environment for Peruvian ground freight, cargo dispatch, and parcel tracking. The visual character reflects precision, industrial dependability, and relentless transit efficiency across varied geographic terrain—from coastal ports to Andean distribution hubs.

The style unites **Modern Corporate Logistics** with a purposeful, high-contrast operational aesthetic:
- **Tone:** Authoritative, prompt, utilitarian, and reliable under intense field conditions (glare, motion, low-bandwidth).
- **Target Audience:** Commercial shippers, cargo dispatchers, branch agents across Peru, and everyday consumers tracking personal freight or parcel deliveries.
- **Visual Expression:** Dense data architecture arranged with generous touch targets (minimum 48px), ultra-crisp tabular readouts for volumetric weight and tracking numbers, and localized Peruvian identity touchpoints (Soles currency formatting `S/`, document inputs for DNI/CE/RUC, and departmental transit corridors).

## Colors
The palette is built around high-visibility logistics red paired with deep carbon neutrals to guarantee contrast under direct sunlight and high-glare environments.

### Primary & Brand Colors
- **Primary Brand Red (`#D7261E`):** Primary action buttons, active route milestones, high-priority cargo status bars, key waybill badges.
- **Deep Burgundy (`#9B130E`):** Pressed/active interaction states, header container accents, focused card frames.
- **Charcoal Dark Neutral (`#1A1A1A`):** Core typography, vector iconography, primary tabular values.
- **Deep Graphite (`#2A2A2A`):** Subdued headers, inactive bottom navigation items, secondary icons.

### Surface System
- **Canvas Base:** `#FFFFFF` (pure white for operational legibility).
- **Surface Level 1:** `#F8F9FA` (card fills, form backgrounds, module groupings).
- **Surface Level 2:** `#F1F3F5` (nested tables, disabled states, divider rails, barcode backdrop pads).
- **Border / Outline:** `#E5E7EB` (crisp 1px boundary lines).

### Semantic & Operational States
- **Success Emerald (`#198754`):** "Entregado" (Delivered), verified DNI/RUC validations, successful payment settlement.
- **Warning Amber (`#D97706`):** "En Tránsito" (In Transit), cargo re-route notices, dimension verification holds.
- **Error Crimson (`#DC2626`):** Failed delivery attempts, barcode mismatch, address/agency discrepancies.

## Typography
The system utilizes **Plus Jakarta Sans** for clear display branding, visual titles, and general interfaces, paired with **Inter** for dense transactional labels, alphanumeric tracking identifiers, and monetary tallies.

### Typographic Guidelines
- **Tabular Figures (`tnum`):** All weight values (`kg`, `m³`), billing summaries (`S/ 00.00`), guide numbers (Guía de Remisión), and tracking keys (`MVS-XXXX-XX`) must be rendered with monospaced numbers via `font-feature-settings: 'tnum' 1` in Inter.
- **Tracking Alphanumerics (`label-code`):** Uppercase, widened tracking (+0.08em) for immediate readability when verifying shipping labels against physical cartons.
- **Hierarchy Distinction:** Headings establish swift context; labels prioritize scan speed using medium-bold weights to reduce reading latency during counter operations.

## Layout & Spacing
A fluid 4-column layout model is calibrated for 360px–428px mobile viewports, shifting dynamically into an 8-column layout on tablets and dispatch terminal docks (>=600px).

### Spacing Principles
- **Base Grid:** 4px incremental scale (`0.25rem`). Component paddings adhere strictly to `space-xs` through `space-xl`.
- **Canvas Margins:** Mobile screens maintain a strict `1rem` (16px) lateral margin to maximize screen real estate for deep tracking timelines and complex cargo manifest tables.
- **Safe Tap Targets:** All actionable elements maintain a minimum touch bounding box of 48×48px, even when the inner visual badge or pill is smaller.
- **Data Rhythm:** In manifests, inputs and specs sit on concise vertical steps (`space-sm` for related micro-labels, `space-md` for distinct form controls).

## Elevation & Depth
To preserve maximum contrast and avoid muddy screens under outdoor sunlight, elevation relies primarily on tonal separation and razor-thin boundary lines over heavy shadows.

### Surface Tiers & Depth Strategy
- **Layer 0 (Canvas):** `#FFFFFF` background.
- **Layer 1 (Card & Module Deck):** `#F8F9FA` fill bound by a 1px solid outline `#E5E7EB`.
- **Layer 2 (Floating Action Bars & Tracking Sliders):** `#FFFFFF` fill with an ultra-subtle tinted ambient shadow: `box-shadow: 0px 4px 16px rgba(26, 26, 26, 0.06), 0px 1px 3px rgba(26, 26, 26, 0.04)`.
- **Layer 3 (Modals & Sheet Drawers):** High-level overlay backed by a 40% `#1A1A1A` backdrop scrim, framed with a 1px top border.
- **Pressed Elevation:** Buttons and cards drop inward with zero shadow and a darkened border or tonal shift (`#9B130E` or `#F1F3F5`) to signal tactical tactile confirmation.

## Shapes
The system applies a disciplined **Soft** shape language (`roundedness: 1`). Logistics environments demand structure, geometric clarity, and space efficiency.

- **Base Radius (0.25rem / 4px):** Form fields, quantity steppers, data tables, barcode framing boxes, and agency route cards.
- **Medium Radius (0.5rem / 8px):** Primary shipment summary cards, modal sheets, and quick-filter button surfaces.
- **Pill Exceptions (Full Radius / 9999px):** Tracking code identifiers, live status indicators ("En Almacén", "En Ruta"), and urgent tag badges. These remain pill-shaped to stand out distinctly against standard rectangular card modules.

## Components

### 1. Tracking Badges & Route Step Indicators
- **Waybill / Tracking Pill:** Displayed with `label-code` in an Inter monospace style. Outlined with 1px border `#E5E7EB`, background `#F8F9FA`, featuring a copy-to-clipboard shortcut.
- **Agency Transit Timeline:** Vertical stepper with a 2px continuous spine line (`#E5E7EB`). Completed stops display a solid emerald `#198754` node with a checkmark; active segments pulse with primary red `#D7261E`; future stops show an open ring `#2A2A2A` with a `#F8F9FA` center. Department and agency names (e.g., "Agencia Arequipa - Terminal") render in `headline-sm`.

### 2. Buttons & Actions
- **Primary Operational Button:** `#D7261E` solid fill, white text, 48px height, 4px border radius. Hover/active state `#9B130E`.
- **Secondary Action Button:** `#FFFFFF` fill with a 1.5px `#1A1A1A` border and `#1A1A1A` text.
- **Destructive/Cancel Button:** Flat surface with `#DC2626` text, no heavy red background to avoid confusion with the brand primary color.

### 3. Inputs & Peruvian Localization Controls
- **Document Type Selector:** Segmented toggle for DNI (8 digits), RUC (11 digits), and CE. Numerical keyboard automatically triggers based on document selection with instant checksum validation.
- **Cargo Dimension Inputs:** Three-segment grouped input (Largo × Ancho × Alto in cm) plus total weight (kg) with a dynamic volumetric calculation badge (`(L × W × H) / 5000 = kg vol`).
- **Currency Readout:** Displays Peruvian Soles explicitly with non-breaking formatting: `S/ 120.50` using `currency-md` tabular figures.

### 4. Barcode & QR Manifest Card
- Center-aligned barcode container on a `#FFFFFF` backdrop protected by a high-contrast 1px border (`#1A1A1A`). Includes the alphanumeric manifest string underneath, readable by handheld industrial laser scanners and mobile phone cameras without glare reflection.

### 5. Freight Summary Cards
- Stacked summary card with a `#F8F9FA` container, 8px outer corner radius, displaying sender/receiver metadata, insured value, payment modality (Pago en Destino / Contado), and delivery route summary (e.g., "Lima ➔ Cusco").