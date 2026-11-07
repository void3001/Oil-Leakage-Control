---
name: Industrial Cybernetic Telemetry
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#bcc9cd'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#869397'
  outline-variant: '#3d494c'
  surface-tint: '#4cd7f6'
  primary: '#4cd7f6'
  on-primary: '#003640'
  primary-container: '#06b6d4'
  on-primary-container: '#00424f'
  inverse-primary: '#00687a'
  secondary: '#ffb95f'
  on-secondary: '#472a00'
  secondary-container: '#ee9800'
  on-secondary-container: '#5b3800'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#1bbd85'
  on-tertiary-container: '#00452e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#acedff'
  primary-fixed-dim: '#4cd7f6'
  on-primary-fixed: '#001f26'
  on-primary-fixed-variant: '#004e5c'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
  data-metric:
    fontFamily: JetBrains Mono
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

The design system establishes a high-precision, mission-critical supervisory control interface for autonomous industrial computer vision and hydraulic spill detection. It serves reliability engineers, plant operations directors, and automation safety teams who oversee heavy manufacturing, hydraulic press lines, and mission-critical shop floors. 

The aesthetic fuses **Tactile Technical Glassmorphism** with **High-Contrast SCADA Precision**. It rejects decorative consumer noise in favor of hyper-legible telemetry, optical sensor states, and instant spatial awareness. Interfaces deliver military-grade situational readiness: resting telemetry appears composed, low-friction, and deep-toned, while hydraulic anomalies puncture the dark field with luminescent amber and laser-focused warning states.

Key aesthetic tenants:
- **Low-Luminance Substrates:** Deep zinc and obsidian backplates isolate human focus on high-priority alerts and machine feeds.
- **Luminescent Telemetry:** State signaling relies on neon optical indicators, subtle backplate glows, and phosphor-trace line metrics rather than flat fills.
- **Structural Precision:** Surfaces feel like machined avionics instrumentation panels—crisp hairline edge lighting, layered acrylic glass, and monospaced diagnostic readouts.

## Colors

The palette balances ultra-dark background containment with high-chroma photon accents to maintain optical ergonomic stability during 24/7 industrial command center shifts.

### Surface Hierarchy & Canvas
- **Canvas Base:** `#0B0F17` (Deep Obsidian Zinc) — Absolute screen grounding.
- **Surface Elevation 1 (Cards & Modules):** `#111827` (Charcoal Substrate) with 60% opacity backdrop-filter blur.
- **Surface Elevation 2 (Instrument Panels & Overlays):** `#1E293B` (Milled Slate).
- **Hairline Borders & Structural Grids:** `#1E293B` to `#334155` at 40-70% alpha.

### Functional & Signal Tokens
- **Primary / Telemetry Link (`#06B6D4` - Electric Cyan):** Active computer vision focus vectors, node ping responses, ESP32-C3 mesh connectivity, telemetry graphs, and active navigational pivots.
- **Secondary / Warning (`#F59E0B` - Cyber Industrial Amber):** Stage-1 hydraulic sheen detection, micro-droplet alerts, mechanical vibration warnings, unconfirmed optical inferences.
- **Danger / Critical Breach (`#EF4444` - Emergency Crimson):** Stage-2 pooling containment failure, optical CV confidence threshold breach (>90%), automatic shutoff actuation triggers.
- **Tertiary / Nominal State (`#10B981` - Kinetic Emerald):** Heartbeat indicators, healthy pressure levels, dry floor zones, operational hydraulic seals.
- **Auxiliary Acoustic / Optical Fusion (`#8B5CF6` - Spectral Violet):** Auxiliary pressure transducers and acoustic frequency cross-correlation diagnostics.

### Luminance Behavior
Warning and error tokens must always incorporate a companion ambient glow (`box-shadow: 0 0 16px rgba(x, y, z, 0.35)`) against `#0B0F17` backgrounds to instantly capture peripheral vision during plant disruptions.

## Typography

Typography reflects dual functional duties: high-level tactical legibility and dense tabular/telemetric scanning.

- **Primary Display & Titles (Space Grotesk):** Delivers a technical, sharp architectural presence for machine cells, zone classifications, and system headlines without decorative distraction.
- **System Interface & Narrative (Inter):** Applied across alerts, incident runbooks, operator actions, and documentation for maximum ocular clarity across low-light displays.
- **Hardware Telemetry, Coordinates & Logs (JetBrains Mono):** Reserved for raw device registers, MAC/IP identities, sensor voltages, auxiliary pressure metrics (PSI/bar), inference confidence ratings (`99.4%`), and timestamps. Monospaced tabular alignment guarantees numbers do not jitter during real-time streaming updates.

### Scaling & Readability Directives
All label-tier text rendered in JetBrains Mono must utilize uppercase transformations when denoting status tags (e.g., `OFFLINE`, `ACTIVE`, `CONTAINMENT_OK`). Metric typography always maintains fixed figures (`font-variant-numeric: tabular-nums`).

## Layout & Spacing

The dashboard employs a **12-column responsive fluid grid** with an edge-to-edge dark operational cockpit layout. 

### Screen Densities & Spatial Rhythms
- **Desktop (1440px+):** 12-column layout; gutter `1.5rem`; external margins `2rem`. Modular multi-panel split: Left navigation dock (compact 64px icon dock or 240px expanded tree), central visualizer (8 cols) housing the Zone Spatial Floorplan and Live Stream feeds, and right dock (4 cols) housing real-time telemetry graphs, alert feeds, and sensor-fusion streams.
- **Tablet (768px - 1439px):** 8-column layout; gutter `1rem`; margins `1.5rem`. Floorplan visualizer snaps to top 8 columns; telemetry and alert logs reflow below into paired 4-column cards.
- **Mobile Field Terminal (<768px):** 4-column layout; gutter `0.75rem`; margins `1rem`. UI prioritizes the single active critical alert banner, followed by a toggleable zone list and collapsible live stream cards.

### Spatial Discipline
Inner card paddings use `space-md` (`1rem`) to `space-lg` (`1.5rem`). Micro metrics (such as sensor tag arrays and pin indicators) bind tightly with `space-xs` (`0.25rem`) and `space-sm` (`0.5rem`) to maximize screen efficiency without visual clutter.

## Elevation & Depth

Visual hierarchy uses **Tactile Dark Glassmorphism and Luminescent Depth Layers** to delineate physical space on the plant floor.

### Elevation Levels
- **Level 0 (Base Floor):** `#0B0F17`. Deep non-reflective background texture, optionally overlaid with a subtle 24px isometric CAD grid pattern (`rgba(255, 255, 255, 0.02)`).
- **Level 1 (Monitoring Surfaces & Structural Pods):** Background `#111827` at 75% opacity, backdrop blur `12px`, hairline perimeter border `1px solid rgba(255, 255, 255, 0.06)`. Shadows: `0 4px 20px -2px rgba(0, 0, 0, 0.6)`.
- **Level 2 (Active Sub-Panels & Hover Targets):** Background `#1E293B` at 85% opacity, backdrop blur `16px`, border `1px solid rgba(6, 182, 212, 0.25)`.
- **Level 3 (Modal Alerts, Floating Incident Overlays, Floorplan Nodes):** Background `#0F172A` at 95% opacity, backdrop blur `24px`, border `1px solid rgba(245, 158, 11, 0.4)`. Casts an ambient colored shadow based on threat status:
  - Critical: `0 8px 32px 0 rgba(239, 68, 68, 0.35)`
  - Warning: `0 8px 32px 0 rgba(245, 158, 11, 0.25)`
  - Nominal: `0 8px 32px 0 rgba(6, 182, 212, 0.2)`

### Luminescent Glow Filters
Edge highlights must look like high-precision optical hardware. Selected nodes and critical pins utilize a dual-ring treatment: an inner concentrated border and an outer diffused radial aura (`box-shadow: 0 0 12px 2px currentColor`).

## Shapes

The design system maintains a **disciplined, semi-sharp mechanical geometry** (Level `1`). It communicates rigorous industrial hardware engineering rather than playful consumer softness.

### Shape Attributes
- **Micro Radii (`rounded-sm` - 2px):** Badges, sensor indicator pills, monospaced register tags, and chart tooltips.
- **Base Components (`rounded` - 4px / 0.25rem):** Action buttons, input toggles, floorplan room nodes, telemetry bar graphs, and drop-down selectors.
- **Card Surfaces (`rounded-lg` - 8px / 0.5rem):** Glass panels, camera feed viewports, incident modals, and sensor matrix frames.
- **Floating Overlays & Video Nodes (`rounded-xl` - 12px / 0.75rem):** Floorplan pan-zoom controls, camera viewport overlays, floating HUD dials.

Circular geometry (`border-radius: 9999px`) is reserved exclusively for node heartbeat status dots, connection pulse rings, and circular gauge telemetry centers.

## Components

### 1. Buttons & Machine Action Triggers
- **Primary Cyber Trigger (Acknowledge / Actuate):** Background `rgba(6, 182, 212, 0.15)`, text `#06B6D4`, border `1px solid #06B6D4`, inner shadow `inset 0 0 12px rgba(6, 182, 212, 0.2)`. On hover: background `#06B6D4`, text `#0B0F17`, box-shadow `0 0 16px rgba(6, 182, 212, 0.5)`.
- **Emergency Spill Response Button:** Background `rgba(239, 68, 68, 0.2)`, text `#FCA5A5`, border `1px solid #EF4444`. On hover: solid `#EF4444`, text `#FFFFFF`, box-shadow `0 0 24px rgba(239, 68, 68, 0.65)`.
- **Secondary Ghost Controls:** Background `rgba(255, 255, 255, 0.03)`, text `#94A3B8`, border `1px solid rgba(255, 255, 255, 0.08)`.

### 2. Status Chips & Sensor Node Badges
- Constructed with `JetBrains Mono` label-sm text.
- Consists of a blinking animated radial anchor dot (`6px`) paired with uppercase alphanumeric status labels (`NODE-ESP32-OK`, `SPILL-ALERT-LVL2`).
- Integrated pill borders with 15% transparent tinted backgrounds matching the state color (Cyan, Amber, Crimson, Emerald).

### 3. Glassmorphic Industrial Cards & Feed Viewers
- Base: Charcoal-tinted frosted glass (`rgba(17, 24, 39, 0.7)`), 1px stroke border (`rgba(255, 255, 255, 0.07)`).
- Header bar: Features technical diagnostic subheads, monospaced zone index indicators (e.g., `ZN-04 // PRESS-LINE-HYD`), and status pulse signals.
- Camera Feed Windows: Bounded by thin cyan crosshair reticles at the four corners, live timestamp overlays in the upper right, and bounding-box overlay layers indicating AI confidence scores (`CONF: 98.7% [HYD_OIL]`).

### 4. Interactive Zone Floorplan Visualizer
- Visual vector blueprints mapped onto a dark CAD matrix.
- Non-affected machinery renders in low-opacity slate outlines (`#334155`).
- Active spill or anomaly zones illuminate with pulsing dynamic vector fills:
  - Amber wave propagation for micro-sheen detection.
  - Flashing Crimson polygons with hazard stripes for confirmed spill expansion.
- Node pins display live ESP32-C3 ping status with concentric pulsing wave ripples.

### 5. Sensor Fusion Telemetry Charts & Wave Indicators
- Real-time line and spline charts display triple-stream sensor data (Optical Specular Reflection, CV Spill Probability, and Transducer Pressure Drop).
- Rendered with glowing stroke lines (2px stroke with canvas shadow blur `8px`) without heavy opaque fills beneath, ensuring overlapping metrics remain distinguishable.

### 6. Incident Acknowledge & Quarantine Workflow Drawer
- Triggered by unresolved alerts. Slides in from screen right as a high-density Level 3 overlay.
- Houses a freeze-frame inference thumbnail, bounding box optical inspection toggle, secondary sensor cross-check confirmation list, and physical shutoff trigger with two-step slider verification.

### 7. Form Controls & Toggle Switches
- Checkboxes and radio toggles use sharp-cornered cyber styling (`rounded-sm`). Unchecked: dark slate backdrop with 1px border. Checked: electric cyan fill with a high-contrast black check mark.
- Digital toggles emulate military avionics rocker switches: recessed track in `#0B0F17` with glowing indicator bars when active.