---
name: Field Ops Stamping HUD
colors:
  surface: '#0f131b'
  surface-dim: '#0f131b'
  surface-bright: '#353941'
  surface-container-lowest: '#0a0e15'
  surface-container-low: '#181c23'
  surface-container: '#1c2027'
  surface-container-high: '#262a32'
  surface-container-highest: '#31353d'
  on-surface: '#dfe2ed'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#dfe2ed'
  inverse-on-surface: '#2d3038'
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
  background: '#0f131b'
  on-background: '#dfe2ed'
  surface-variant: '#31353d'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  telemetry-lg:
    fontFamily: JetBrains Mono
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 24px
  telemetry-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  telemetry-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.25rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes an industrial cyber-telemetry interface engineered for mission-critical field operations, site verification, and evidentiary overtime documentation. The visual aesthetic fuses rugged field utility with high-precision aerospace instrumentation and HUD ergonomics.

### Personality & Tone
- **Instrumental & Exacting:** Surfaces function as optical tools rather than decorative canvases. Information is calibrated, verified, and telemetry-backed.
- **Rugged High-Tech:** Engineered for intense field conditions, direct sunlight, nocturnal pole climbs, and degraded network environments.
- **Decisive & Evidentiary:** Clean, unambiguous statuses that clearly signal tamper-evident integrity, millimeter-level GPS lock, and synchronous server time.

### Design Movement
**Industrial Cyber-Tech / Tactical HUD.** Characterized by deep obsidian surfaces, crisp 1px optical dividers, micro-corner ticks, technical coordinate readouts, and high-luminance indicator states. Glass surfaces use low-diffusion, high-legibility dark lenses with ultra-thin edge highlights to mirror field-grade optics and camera viewfinders.

## Colors

The palette is anchored in an ultra-deep optical cockpit black, paired with calibrated spectral accents engineered for swift comprehension in low-light and harsh outdoor environments.

### Core Swatches
- **Primary (`#38bdf8` / Sky Cyan & Deep `#0b7fa3`):** Primary reticle lines, active camera frame markers, selection borders, and authoritative telemetry labels.
- **Secondary (`#10b981` / Emerald Lock):** Cryptographic verification, RTK/differential GPS signal lock, altitude fix, and successful evidentiary stamp confirmation.
- **Tertiary (`#f59e0b` / Safety Amber):** Sensor drift warnings, weak satellite constellation, battery-saver constraints, and uncommitted field capture buffers.
- **Neutral (`#090d14` / Tactical Obsidian):** Base viewfinder canvas, optical mask backing, and contrast foundation.

### Functional Roles & Gradients
- **Surface Void (`#05080c`):** Viewfinder outer mask and canvas base.
- **Surface Layer 1 (`#0c131d`):** Primary telemetry drawers, card baselines, and bottom bar controls.
- **Surface Layer 2 (`#131e2e`):** Floating HUD HUD badges, compass azimuth dials, and camera setting triggers.
- **Border Tactical (`#1e3048`):** 1px structural guidelines, reticle boundaries, and frame brackets.
- **Text Primary (`#f8fafc`):** Crucial numerical readouts and status metrics.
- **Text Muted (`#64748b`):** Metric units, sensor labels, and metadata keys.

## Typography

Typography delivers immediate legibility under high-glare environments through distinct functional roles:

1. **Display & Operational Headlines (Space Grotesk):** Engineered structural geometry used for operational headers, shift task names, and system mode banners.
2. **Body & Descriptive Copy (Work Sans):** Highly legible, human-centric grotesque with open apertures for fast scanning of task descriptions, validation logs, and site notes.
3. **Data Telemetry & Coordinate Stamps (JetBrains Mono):** Fixed-width baseline for coordinate readouts (`DD°MM'SS.S"` or decimal degrees), UTC timestamps, compass degrees, network latency, and cryptographic hash manifests. Tabular alignment ensures that fluctuating digits never cause visual jitter in live HUD displays.

## Layout & Spacing

The interface applies a specialized viewport-dominant fluid grid designed around the central camera sensor aspect ratio (4:3 and 16:9) flanked by tactical instrumentation wings.

### Breakpoints & Adaptations
- **Mobile Handheld (< 640px):** Single-column HUD. 100vh dynamic camera viewport with an on-canvas floating top bar (satellites, battery, network, clock), bottom HUD strip (azimuth, coordinates, target cluster), and bottom-docked shutter trigger with thumb-reach mechanics.
- **Tablet Tactical (640px – 1024px):** Split-view HUD. Main optical viewfinder occupying 70% width, side telemetry drawer occupying 30% width featuring live geofence maps, task checklist, and real-time EXIF preview.
- **Desktop Command (> 1024px):** Dual-wing layout. Viewfinder pinned center with left instrumentation column (telemetry, hardware diagnostic, beam status) and right validation stack (overtime ticket metadata, server approval pipe, stamped ledger).

### Spacing Rhythm
Component layouts rely on a strict 4px sub-grid with base increments of `space-sm` (8px) and `space-md` (12px) to preserve density without sacrificing touch target reliability (minimum 48px hit areas for one-handed glove interaction).

## Elevation & Depth

Depth is established through low-opacity optical glassing, luminous rim lighting, and structural border framing rather than traditional drop shadows.

### Elevation Hierarchy
- **Level 0 (Viewfinder Feed):** Raw hardware camera canvas with edge vignetting.
- **Level 1 (Telemetry Overlay - HUD Ground):** `rgba(9, 13, 20, 0.72)` with `backdrop-filter: blur(12px)`. Outlined with `1px solid rgba(56, 189, 248, 0.15)`. Used for corner brackets, target crosshairs, and live coordinate stamps.
- **Level 2 (Interactive Floating Controls):** `rgba(12, 19, 29, 0.90)` with `backdrop-filter: blur(16px)` and `1px solid rgba(56, 189, 248, 0.35)`. Subtle directional edge glow: `0 0 12px rgba(56, 189, 248, 0.12)`.
- **Level 3 (Modal Alerts & Sensor Lock Banners):** Solid tactical surface (`#0f172a`) reinforced with high-luminance status halos (Emerald: `0 0 20px rgba(16, 185, 129, 0.25)` or Amber: `0 0 20px rgba(245, 158, 11, 0.25)`).

## Shapes

The interface embraces a mechanical, angular architectural silhouette with soft micro-radii (4px) to retain technical precision while softening edge glare.

### Architectural Corner Geometry
- All primary frames, badges, and card containers utilize `0.25rem` (`4px`) rounded corners.
- High-level telemetry pods and crosshairs utilize tactical cut-ins: corner-bracket graphics layered over the 4px rounded frames to reinforce an optical rangefinder feel.
- Shutter triggers and circular azimuth dials break geometry deliberately, using strict concentric circles with radial tick marks to delineate analogue precision within digital instrumentation.

## Components

### Buttons & Shutter Controls
- **Primary Tactical Action:** Solid fill with `#38bdf8`, text in `#05080c`, `font-family: JetBrains Mono`, uppercase, bold. `box-shadow: 0 0 16px rgba(56, 189, 248, 0.4)`.
- **Secondary Ghost Action:** Transparent background, `1px solid #1e3048`, text in `#38bdf8`. On hover/touch, background becomes `rgba(56, 189, 248, 0.08)`.
- **Shutter Mechanism:** Double-ring mechanical structure. Outer fixed bezel (`76px`) in `rgba(56, 189, 248, 0.3)` with 4 radial ticks; inner floating button (`60px`) in luminous `#f8fafc`. When GPS lock is incomplete, outer ring pulses Amber (`#f59e0b`); when locked, ring turns solid Emerald (`#10b981`).

### Telemetry Badges & Chips
- **Status Indicator Badges:** Minimalist capsules with a live beacon dot. `1px solid` border corresponding to status: Emerald for `GPS FIXED (RTK 0.02m)`, Amber for `ACQUIRING SATS [4/12]`, and Sky Cyan for `STAMP VERIFIED`.
- Monospace readout with uppercase labels positioned left-to-right (`LAT`, `LON`, `ALT`, `AZM`).

### Viewfinder HUD & Azimuth Bezel
- **Crosshair / Reticle:** Center screen target with 4-way micro tick lines (`12px` length, `1px` stroke, Sky Cyan). Center dot has an inner 3px clear aperture.
- **Top Horizon & Azimuth Ribbon:** Horizontal scroll ticker showing cardinal points (N, NE, E, SE, S, SW, W, NW) with active degree digits (e.g., `248° WSW`) framed in a primary cyan reticle box.
- **Stamp Watermark Overlay:** Pinned to bottom-left of capture: Biznet logo mark, ticket ID, field tech UID, GPS coordinates, accuracy radius, network timestamp, and cryptographic SHA-256 fingerprint preview.

### Cards & Telemetry Pods
- **Telemetry Card:** Dark optical glass background (`#0c131d` at 85%), 1px border (`#1e3048`), top-right corner chamfer accent. Header features micro-labeling in muted mono uppercase (`SYS.TEL // 01`).

### Form Inputs & Checkboxes
- **Input Fields:** Recessed cockpit styling. Fill `#060a10`, border `1px solid #1e3048`, text in JetBrains Mono `#f8fafc`. Active focus switches border to `#38bdf8` with a micro ambient glow.
- **Tactical Checkboxes:** Square (`18px`) with `2px` border in `#1e3048`. Checked state renders solid `#10b981` background with an inset obsidian checkmark.