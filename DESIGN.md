---
version: alpha
name: Sistent
description: Open-source dashboard and component-system visual identity with a neutral application shell, teal brand actions, saffron CTAs, and a first-class dark mode.
target_framework: "@mui/material + React + TypeScript"
package_source_of_truth: package.json
colors:
  primary: '#00B39F'
  on-primary: '#FDFDFD'
  primary-hover: '#41CCB3'
  primary-pressed: '#93E6D1'
  secondary: '#3C494F'
  on-secondary: '#FDFDFD'
  accent: '#EBC017'
  on-accent: '#000D12'
  accent-hover: '#FFEB6B'
  navigation-light: '#252E31'
  on-navigation-light: '#FDFDFD'
  navigation-dark: '#000D12'
  on-navigation-dark: '#FDFDFD'
  surface-light-app: '#FDFDFD'
  surface-light-card: '#FFFFFF'
  surface-light-muted: '#F6F8F8'
  surface-light-tabs: '#F6F8F8'
  on-surface-light: '#000D12'
  surface-dark-app: '#000D12'
  surface-dark-card: '#212121'
  surface-dark-muted: '#15272F'
  surface-dark-tabs: '#1A1A1A'
  on-surface-dark: '#FDFDFD'
  on-ribbon: '#FDFDFD'
  ribbon-community: '#7A848E'
  ribbon-official: '#EBC017'
  ribbon-verified: '#00B39F'
typography:
  textH1Bold:
    fontFamily: 'Qanelas Soft Regular, Roboto, Helvetica, Arial, sans-serif'
    fontSize: 3.25rem
    fontWeight: 700
    lineHeight: 4rem
    letterSpacing: -0.02em
  textH2Medium:
    fontFamily: 'Qanelas Soft Regular, Roboto, Helvetica, Arial, sans-serif'
    fontSize: 2rem
    fontWeight: 500
    lineHeight: 2.5rem
  textH3Medium:
    fontFamily: 'Qanelas Soft Regular, Roboto, Helvetica, Arial, sans-serif'
    fontSize: 1.5rem
    fontWeight: 500
    lineHeight: 2.25rem
  textB1Regular:
    fontFamily: 'Qanelas Soft Regular, Open Sans, sans-serif'
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.75rem
  textB2SemiBold:
    fontFamily: 'Qanelas Soft Regular, Open Sans, sans-serif'
    fontSize: 1rem
    fontWeight: 600
    lineHeight: 1.75rem
  textB3Regular:
    fontFamily: 'Open Sans, sans-serif'
    fontSize: 0.875rem
    fontWeight: 400
    lineHeight: 1.5rem
  textL1Bold:
    fontFamily: 'Qanelas Soft Regular, Open Sans, sans-serif'
    fontSize: 0.75rem
    fontWeight: 700
    lineHeight: 1rem
    letterSpacing: 0.02em
  textL2Regular:
    fontFamily: 'Open Sans, sans-serif'
    fontSize: 0.75rem
    fontWeight: 400
    lineHeight: 1.5rem
  textC1Regular:
    fontFamily: 'Consolas, monospace'
    fontSize: 0.75rem
    fontWeight: 400
    lineHeight: 1.5rem
  textC2Regular:
    fontFamily: 'Consolas, monospace'
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.75rem
rounded:
  xs: 2px
  sm: 4px
  md: 5px
  lg: 8px
  xl: 15px
  xxl: 16px
  full: 9999px
spacing:
  base: 8px
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 20px
  xxl: 24px
  xxxl: 32px
strokes:
  light-default: '#EAEDEE'
  light-strong: '#28353A'
  light-normal: '#8C999E'
  dark-default: '#15272F'
  dark-strong: '#8D9FA7'
  dark-normal: '#3D4F57'
status-colors:
  info: '#2196F3'
  success: '#206D24'
  warning: '#F0A303'
  error: '#F91313'
icons:
  light-primary: '#15272F'
  dark-primary: '#D2D8DA'
motion:
  duration-fast: 150ms
  duration-short: 200ms
  duration-medium: 600ms
  duration-long: 800ms
  duration-xlong: 900ms
  easing-standard: ease-out
  easing-emphasized: cubic-bezier(0.2, 0.8, 0.2, 1)
shadows:
  card-accent: '2px 2px 3px 0px #00B39F'
  hover-sm: '0 3px 10px 0px rgba(0, 0, 0, 0.08)'
  floating-panel-light: '0 4px 16px rgba(234, 237, 238, 0.5)'
  floating-panel-dark: '0 4px 16px rgba(0, 13, 18, 0.5)'
  tooltip-light: '0 10px 30px rgba(0, 0, 0, 0.12), 0 2px 8px rgba(0, 0, 0, 0.08)'
  tooltip-dark: '0 10px 30px rgba(0, 179, 159, 0.28), 0 2px 8px rgba(0, 179, 159, 0.20), 0 0 1px rgba(0, 179, 159, 0.32)'
elevation:
  flat: none
  raised-sm: '0 3px 10px 0px rgba(0, 0, 0, 0.08)'
  raised-accent: '2px 2px 3px 0px #00B39F'
  floating-panel-light: '0 4px 16px rgba(234, 237, 238, 0.5)'
  floating-panel-dark: '0 4px 16px rgba(0, 13, 18, 0.5)'
  tooltip-light: '0 10px 30px rgba(0, 0, 0, 0.12), 0 2px 8px rgba(0, 0, 0, 0.08)'
  tooltip-dark: '0 10px 30px rgba(0, 179, 159, 0.28), 0 2px 8px rgba(0, 179, 159, 0.20), 0 0 1px rgba(0, 179, 159, 0.32)'
gradients:
  tint-light: 'linear-gradient(90deg, #477E96 0%, #455A64 100%)'
  tint-dark: 'linear-gradient(90deg, #28353A 0%, #3D4F57 100%)'
  panel-header-light: 'linear-gradient(90deg, #3B687B 0%, #507D90 100%)'
  panel-header-dark: 'linear-gradient(90deg, #28353A 0%, #3D4F57 100%)'
effects:
  card-wash: 'radial-gradient(circle 3000px at 50% 50%, rgba(30, 33, 23, 0) 0%, rgba(30, 33, 23, 0.05) 10%, rgba(30, 33, 23, 0.1) 100%)'
  panel-blur-light: 'rgba(234, 237, 238, 0.5)'
  panel-blur-dark: 'rgba(0, 13, 18, 0.5)'
components:
  app-shell-light:
    backgroundColor: '{colors.surface-light-app}'
    textColor: '{colors.on-surface-light}'
    typography: '{typography.textB1Regular}'
    padding: '{spacing.xxl}'
  app-shell-dark:
    backgroundColor: '{colors.surface-dark-app}'
    textColor: '{colors.on-surface-dark}'
    typography: '{typography.textB1Regular}'
    padding: '{spacing.xxl}'
  navigation-bar-light:
    backgroundColor: '{colors.navigation-light}'
    textColor: '{colors.on-navigation-light}'
    typography: '{typography.textB2SemiBold}'
    padding: '{spacing.lg}'
  navigation-bar-dark:
    backgroundColor: '{colors.navigation-dark}'
    textColor: '{colors.on-navigation-dark}'
    typography: '{typography.textB2SemiBold}'
    padding: '{spacing.lg}'
  button-primary:
    backgroundColor: '{colors.primary}'
    textColor: '{colors.on-primary}'
    typography: '{typography.textB2SemiBold}'
    rounded: '{rounded.sm}'
    padding: 6px 16px
  button-primary-hover:
    backgroundColor: '{colors.primary-hover}'
    textColor: '{colors.on-primary}'
    typography: '{typography.textB2SemiBold}'
    rounded: '{rounded.sm}'
    padding: 6px 16px
  button-primary-pressed:
    backgroundColor: '{colors.primary-pressed}'
    textColor: '{colors.on-surface-light}'
    typography: '{typography.textB2SemiBold}'
    rounded: '{rounded.sm}'
    padding: 6px 16px
  button-secondary:
    backgroundColor: '{colors.secondary}'
    textColor: '{colors.on-secondary}'
    typography: '{typography.textB2SemiBold}'
    rounded: '{rounded.sm}'
    padding: 6px 16px
  button-cta:
    backgroundColor: '{colors.accent}'
    textColor: '{colors.on-accent}'
    typography: '{typography.textB2SemiBold}'
    rounded: '{rounded.sm}'
    padding: 6px 16px
  button-cta-hover:
    backgroundColor: '{colors.accent-hover}'
    textColor: '{colors.on-accent}'
    typography: '{typography.textB2SemiBold}'
    rounded: '{rounded.sm}'
    padding: 6px 16px
  card-standard-light:
    backgroundColor: '{colors.surface-light-card}'
    textColor: '{colors.on-surface-light}'
    rounded: '{rounded.sm}'
    padding: '{spacing.lg}'
  card-standard-dark:
    backgroundColor: '{colors.surface-dark-card}'
    textColor: '{colors.on-surface-dark}'
    rounded: '{rounded.sm}'
    padding: '{spacing.lg}'
  tab-selected-light:
    backgroundColor: '{colors.surface-light-tabs}'
    textColor: '{colors.on-surface-light}'
    typography: '{typography.textB2SemiBold}'
    rounded: '{rounded.sm}'
    padding: 12px 16px
  tab-selected-dark:
    backgroundColor: '{colors.surface-dark-tabs}'
    textColor: '{colors.on-surface-dark}'
    typography: '{typography.textB2SemiBold}'
    rounded: '{rounded.sm}'
    padding: 12px 16px
  input-field-light:
    backgroundColor: transparent
    textColor: '{colors.on-surface-light}'
    typography: '{typography.textB1Regular}'
    rounded: '{rounded.sm}'
    padding: 16px 14px
  input-field-dark:
    backgroundColor: transparent
    textColor: '{colors.on-surface-dark}'
    typography: '{typography.textB1Regular}'
    rounded: '{rounded.sm}'
    padding: 16px 14px
  checkbox:
    backgroundColor: transparent
    textColor: '{colors.on-surface-light}'
    rounded: '{rounded.xs}'
    size: 20px
  modal-header-light:
    backgroundColor: 'linear-gradient(90deg, #477E96 0%, #455A64 100%)'
    textColor: '{colors.on-primary}'
    typography: '{typography.textB1Regular}'
    rounded: '{rounded.md}'
    height: 52px
    padding: 11px 16px
  modal-header-dark:
    backgroundColor: 'linear-gradient(90deg, #28353A 0%, #3D4F57 100%)'
    textColor: '{colors.on-surface-dark}'
    typography: '{typography.textB1Regular}'
    rounded: '{rounded.md}'
    height: 52px
    padding: 11px 16px
  panel-floating-light:
    backgroundColor: 'rgba(234, 237, 238, 0.5)'
    textColor: '{colors.on-surface-light}'
    rounded: '{rounded.lg}'
    padding: '{spacing.xl}'
  panel-floating-dark:
    backgroundColor: 'rgba(0, 13, 18, 0.5)'
    textColor: '{colors.on-surface-dark}'
    rounded: '{rounded.lg}'
    padding: '{spacing.xl}'
  table-header-light:
    backgroundColor: '{colors.surface-light-muted}'
    textColor: '{colors.on-surface-light}'
    typography: '{typography.textB2SemiBold}'
    padding: '{spacing.lg}'
  table-header-dark:
    backgroundColor: '{colors.surface-dark-muted}'
    textColor: '{colors.on-surface-dark}'
    typography: '{typography.textB2SemiBold}'
    padding: '{spacing.lg}'
  badge-community:
    backgroundColor: '{colors.ribbon-community}'
    textColor: '{colors.on-ribbon}'
    typography: '{typography.textL1Bold}'
    rounded: '{rounded.full}'
    padding: 4px 8px
  badge-official:
    backgroundColor: '{colors.ribbon-official}'
    textColor: '{colors.on-accent}'
    typography: '{typography.textL1Bold}'
    rounded: '{rounded.full}'
    padding: 4px 8px
  badge-verified:
    backgroundColor: '{colors.ribbon-verified}'
    textColor: '{colors.on-ribbon}'
    typography: '{typography.textL1Bold}'
    rounded: '{rounded.full}'
    padding: 4px 8px
---

## 1. Overview & Architectural Boundaries

Sistent is the design system and UI component library for Layer5 products and open-source applications (such as Meshery). It provides a calm, technical visual identity built around:
- A cool, restrained neutral application shell.
- Vivid brand teal (`#00B39F`) for primary actions, navigation indicators, and active cues.
- Saffron (`#EBC017`) as an intentional CTA and badge accent.
- A first-class dark mode treated as a peer surface system rather than a naive color inversion.

### Document Scope & Separation of Concerns

To avoid contradictory guidance across the repository, documentation responsibilities are strictly separated:

* **`DESIGN.md` (UI & Design Contract)**:
  * **Owns**: Visual philosophy, semantic design tokens (frontmatter), verified token-to-code bridges, component conventions, interaction states, responsive layouts, evidence-backed accessibility guidance, and UI-specific AI guardrails.
  * **Strict Non-Goals**: Build tooling, rollup/dts configurations, npm releases, package dependency categorization, multi-repo schema definitions, and git commit signing (DCO).
* **`AGENTS.md` (Repository & Engineering Contract)**:
  * **Owns**: Contributor engineering runbooks, build/test gates, declaration bundling troubleshooting, optional peer rules, schema derivation contracts, and DCO requirements.
  * **Strict Non-Goals**: Visual styling choices, typography variants, component color palettes, and UI layout rules.
* **`package.json`**:
  * **Sole Authority** for installed framework and library versions (e.g. `@mui/material`, `react`, `typescript`).

---

## 2. The Two-Layer Model: Design Tokens vs Runtime MUI Theme

> ### Core Principle: DESIGN TOKENS ≠ MUI THEME API
> Sistent establishes an explicit two-layer design contract:
> 1. **Layer 1: Semantic Design Tokens**: Abstract design concepts defined in the YAML frontmatter (`colors.primary`, `spacing.lg`, `rounded.sm`). These define visual relationships, scales, and component compositions across design tools and specifications.
> 2. **Layer 2: Canonical Runtime Implementation**: How React and TypeScript code consumes those tokens via Material UI (`theme.palette.interactive.primary`, `theme.spacing(2)`, `theme.shape.borderRadius`).
>
> **AI Coding Rule**: Never write design tokens as literal runtime theme properties (e.g. do not write `theme.spacing.lg`, `theme.rounded.sm`, or `theme.shadows['card-accent']`). Instead, use the explicit mappings below to translate design tokens into their canonical runtime implementations.

---

## 3. Explicit Design-Token-to-Runtime-Implementation Mappings

Every documented implementation path below is verified against current repository source code or explicitly identified as a historical/compatibility reference.

### A. Colors & Surface Semantics

> **Surface Semantics Rule**: Do not assume `theme.palette.background.card` is the universal token for all surfaces. Sistent distinguishes between application canvases, cards, modal bodies, panels, and data surfaces based on their structural role.

| Design Token | Design Value (Light / Dark) | Semantic Role | Canonical Implementation Path | Classification | New Code Guidance |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `colors.primary` | `#00B39F` / `#00B39F` | Interactive Primary | `theme.palette.interactive.primary` | Canonical Semantic | **Use for all new interactive controls, icons, and active indicators.** |
| `colors.primary-hover` | `#41CCB3` / `#41CCB3` | Interactive Hover | `theme.palette.interactive.hover` | Canonical Semantic | **Use for hover states of primary interactive controls.** |
| `colors.primary-pressed`| `#93E6D1` / `#93E6D1` | Interactive Pressed | `theme.palette.interactive.pressed` | Canonical Semantic | **Use for active and pressed control states.** |
| `colors.secondary` | `#3C494F` / `#B1B9BC` | Secondary Text / Icon | `theme.palette.text.secondary` / `icon.secondary` | Canonical Semantic | **Use for captions, metadata, hints, and passive icons.** |
| `colors.accent` | `#EBC017` / `#EBC017` | CTA Accent (Saffron) | `theme.palette.background.cta?.default` | Active Component Binding | **Use for high-visibility Call-to-Action buttons.** |
| `colors.accent-hover` | `#FFEB6B` / `#FFEB6B` | CTA Hover | `theme.palette.background.cta?.hover` | Active Component Binding | **Use for hover states of CTA buttons.** |
| `colors.navigation-light / dark`| `#252E31` / `#000D12`| Navigation Bar | `theme.palette.navigation.primary` | Canonical Semantic | **Use for application shell navigation bars and side drawers.** |
| `colors.surface-light / dark-app`| `#FDFDFD` / `#000D12`| Surface Canvas (App) | `theme.palette.surface.primary` | Canonical Semantic | **Use for application screen canvases and modal body containers.** |
| `colors.surface-light / dark-card`| `#FFFFFF` / `#212121`| Card Container | `theme.palette.background.card` | Active Component Binding | Used for card surfaces and dark-mode table toolbars/headers. |
| `colors.surface-light / dark-muted`| `#F6F8F8` / `#15272F`| Panel / Data Surface | `theme.palette.background.surfaces` | Active Component Binding | Used for floating panel bodies, sidebars, and light-mode table headers. |
| `colors.surface-light / dark-tabs`| `#F6F8F8` / `#1A1A1A`| Tabs Background | `theme.palette.background.tabs` | Active Component Binding | Used for segmented tab container bars (`tab.modifier.ts`). |
| `strokes.light / dark-default`| `#EAEDEE` / `#15272F`| Border Default | `theme.palette.border.default` | Canonical Semantic | **Use for standard card outlines and container dividers.** |
| `strokes.light / dark-strong`| `#28353A` / `#8D9FA7`| Border Strong | `theme.palette.border.strong` | Canonical Semantic | **Use for emphasized borders and active boundaries.** |
| `strokes.light / dark-normal`| `#8C999E` / `#3D4F57`| Border Normal | `theme.palette.border.normal` | Canonical Semantic | **Use for intermediate divider contrast.** |
| `icons.light / dark-primary`| `#15272F` / `#D2D8DA`| Primary Icon Fill | `theme.palette.icon.default` | Canonical Semantic | **Use for standard icons.** |
| `status-colors.info` | `#2196F3` / `#2196F3` | System Info | `theme.palette.status.info` | Canonical Semantic | **Use for informative alerts and status badges.** |
| `status-colors.success`| `#206D24` / `#206D24` | System Success | `theme.palette.status.success` | Canonical Semantic | **Use for success states and confirmation badges.** |
| `status-colors.warning`| `#F0A303` / `#F0A303` | System Warning | `theme.palette.status.warning` | Canonical Semantic | **Use for warnings and caution alerts.** |
| `status-colors.error` | `#F91313` / `#F91313` | System Error | `theme.palette.status.error` | Canonical Semantic | **Use for errors, alert banners, and destructive actions.** |
| `gradients.tint-light / dark`| Gradient | Surface Header Tint | `theme.palette.surface.tint` | Canonical Semantic | **Use for modal, drawer, and panel header gradient banners.** |
| — | — | App Canvas (Legacy) | `theme.palette.background.default` | Legacy / Compatibility | Baseline MUI background; prefer `surface.primary` in new code. |
| — | — | MUI Primary Main | `theme.palette.primary.main` | Deprecated | Avoid direct theme path in new code; pass `color="primary"` to Sistent components. |
| — | — | Text Brand | `theme.palette.text.brand` | Deprecated | Avoid in new code; use `theme.palette.interactive.primary`. |

---

### B. Spacing: Semantic Tokens vs Functional Invocation

> **AI Rule**: `spacing.*` tokens define the design grid rhythm. At runtime, the MUI theme implements this via an invocable function `theme.spacing(factor)`. Never write `theme.spacing.base` or `theme.spacing.lg` in code.

| Design Token | Design Value | Canonical Runtime Implementation | Usage Context |
| :--- | :--- | :--- | :--- |
| `spacing.xxs` | `2px` | `theme.spacing(0.25)` or `2px` literal | Micro gaps, border adjustments |
| `spacing.xs` | `4px` | `theme.spacing(0.5)` | Micro gaps, tight chip padding |
| `spacing.sm` / `spacing.base` | `8px` | `theme.spacing(1)` | Base element separation |
| `spacing.md` | `12px` | `theme.spacing(1.5)` | Compact card gutters, internal control padding |
| `spacing.lg` | `16px` | `theme.spacing(2)` | Standard container padding, button horizontal padding |
| `spacing.xl` | `20px` | `theme.spacing(2.5)` | Modal and panel padding |
| `spacing.xxl` | `24px` | `theme.spacing(3)` | Section separation |
| `spacing.xxxl` | `32px` | `theme.spacing(4)` | Major layout gutters |

---

### C. Border Radii: Semantic Tokens vs Theme Shapes & Conventions

> **AI Rule**: Sistent defines a single formal theme token: `theme.shape.borderRadius` (`4px`). Other radii in the `rounded.*` token scale represent component-level CSS conventions. Sistent does not define a `theme.rounded` object.

| Design Token | Design Value | Canonical Implementation Mechanism | Component Conventions |
| :--- | :--- | :--- | :--- |
| `rounded.xs` | `2px` | CSS literal (`2px`) | Micro controls (checkboxes, inner tags) |
| `rounded.sm` | `4px` | `theme.shape.borderRadius` | Standard controls (Buttons, TextFields, base Cards) |
| `rounded.md` | `5px` | CSS literal (`5px` / `0.5rem`) | Modal dialog wrappers, header caps |
| `rounded.lg` | `8px` | CSS literal (`8px` / `0.5rem`) | Modal dialog containers, floating panels |
| `rounded.xl` | `15px` | CSS literal (`15px`) | Featured card variants |
| `rounded.xxl` | `16px` | CSS literal (`16px`) | Catalog showcase cards |
| `rounded.full` | `9999px` | CSS literal (`9999px`) | Badges, rounded pills, avatars |

---

### D. Typography System

All 10 custom variants are registered in `MuiTypography` via `src/theme/typography.ts`. Consumer code must use these named variants rather than declaring arbitrary font styles:

| Design Token | Typography Spec | Canonical Runtime Usage | Responsive Behavior (`down('sm')`) | Primary Role |
| :--- | :--- | :--- | :--- | :--- |
| `typography.textH1Bold` | `3.25rem` / `4rem`, 700 | `<Typography variant="textH1Bold">` | Scales to `2rem` / `2.5rem` | Top-level screen headers |
| `typography.textH2Medium` | `2rem` / `2.5rem`, 500 | `<Typography variant="textH2Medium">` | Scales to `1.5rem` / `2.25rem` | Primary section headers |
| `typography.textH3Medium` | `1.5rem` / `2.25rem`, 500 | `<Typography variant="textH3Medium">` | Scales to `1rem` / `1.75rem` (700) | Card & modal titles |
| `typography.textB1Regular` | `1rem` / `1.75rem`, 400 | `<Typography variant="textB1Regular">` | Preserves `1rem` / `1.75rem` | Primary UI & body copy |
| `typography.textB2SemiBold`| `1rem` / `1.75rem`, 600, `capitalize` | `<Typography variant="textB2SemiBold">` | Preserves `1rem` / `1.75rem` | Action labels, active tab titles |
| `typography.textB3Regular` | `0.875rem` / `1.5rem`, 400 | `<Typography variant="textB3Regular">` | Fixed | Supporting labels, hints |
| `typography.textL1Bold` | `0.75rem` / `1rem`, 700 | `<Typography variant="textL1Bold">` | Fixed | Ribbon badges, small chips |
| `typography.textL2Regular` | `0.75rem` / `1.5rem`, 400 | `<Typography variant="textL2Regular">` | Fixed | Secondary metadata, captions |
| `typography.textC1Regular` | `0.75rem` / `1.5rem`, 400 | `<Typography variant="textC1Regular">` | Fixed | Compact code blocks, UUIDs |
| `typography.textC2Regular` | `1rem` / `1.75rem`, 400 | `<Typography variant="textC2Regular">` | Fixed | Standard monospace text |

---

### E. Shadows, Elevation & Depth

* **Tooltip Elevation**: Encapsulated in `src/theme/components/tooltip.modifier.ts`. Automatically renders neutral shadow in light mode and a dual-tone teal luminescent glow in dark mode.
* **Card Surface Depth**: Encapsulated via the subtle radial wash in `src/theme/components/card.modifier.ts`.
* **Floating Panels**: Composed using backdrop blur: `boxShadow: 0 4px 16px ${theme.palette.background.blur?.light}` (`src/custom/Panel/style.tsx`).
* **Showcase Cards**: Accent shadow: `boxShadow: 2px 2px 3px 0px ${theme.palette.background.brand?.default}` (`src/custom/CatalogCard/style.tsx`).
* **Negative Constraint**: `theme.shadows` is a standard MUI 25-element tuple. Named keys like `theme.shadows['card-accent']` or `theme.elevation` do not exist.

---

## 4. Component Usage & Import Conventions

### Import Precedence Rule
> **"Prefer `@sistent/sistent` when a Sistent abstraction exists. Use `@mui/material` when no equivalent exists or when implementing Sistent itself."**

* **Base Controls**: Always import from `@sistent/sistent`:
  `Button`, `Card`, `Checkbox`, `Dialog`, `IconButton`, `Select`, `Tab`, `Tabs`, `TextField`, `Tooltip`, `Typography`.
* **Custom Components**: Always import from `@sistent/sistent`:
  `ActionButton`, `CustomTooltip`, `Modal`, `Panel`, `ResponsiveDataTable`, `SearchBar`, `UniversalFilter`.
* **MUI Fallbacks**: Permitted only when building internal Sistent primitives or when no Sistent wrapper exists.

---

## 5. Interaction States Matrix

Interaction states are derived from active Sistent component implementations and theme modifiers (`button.modifier.ts`, `tab.modifier.ts`, `input.modifier.ts`):

| Interaction State | Primary Contained Control | Outlined Control | Surface / Container | Rule Status |
| :--- | :--- | :--- | :--- | :--- |
| **Default** | `theme.palette.interactive.primary` | Transparent background, `border.default` | Canonical surface token (`surface.primary`, `background.card`) | Canonical Design Rule |
| **Hover** | `theme.palette.interactive.hover` (`#41CCB3`) | `theme.palette.background.hover` | `theme.palette.background.hover` | Canonical Design Rule |
| **Pressed** | `theme.palette.interactive.pressed` (`#93E6D1`) | `theme.palette.interactive.pressed` tint | Stepped surface depth | Canonical Design Rule |
| **Focus-Visible** | Distinct focus outline: `theme.palette.border.brand` | Outline: `theme.palette.border.brand` | Outline: `theme.palette.border.brand` | Canonical Design Rule |
| **Disabled** | `theme.palette.interactive.disabled`, text `disabled` | Stroke `theme.palette.text.disabled` | N/A | Canonical Design Rule |
| **Loading** | Spinner / skeleton indicator; interactions inert | Inherits disabled state modifiers | Loading overlay / skeleton | Implementation-Specific |
| **Selected / Active** | Active tab indicator / contained toggle | `border.brand` with subtle background tint | Component-specific active fill | Implementation-Specific |
| **Error** | Background: `theme.palette.background.error?.default`, text via `getContrastText()` | Border: `theme.palette.status.error` | Border: `theme.palette.status.error` | Canonical Design Rule |
| **Success / Warning** | Component-specific status badge / icon | Border / text using status token | Background / border using status token | Implementation-Specific |

---

## 6. Authorization & Permissions

### Permission Rule
> **"When an action is authorization-controlled, use the existing Sistent permission mechanism and provide the appropriate `permissionKey`. Do not invent local permission logic."**

* Built-in native support exists on: `Button`, `IconButton`, `MenuItem`, `ListItem`, and `ListItemButton`.
* If unauthorized, the component automatically disables itself and shows a badge tooltip (`permissionAction="showShield"`, default) or renders nothing (`permissionAction="hide"`).
* **Applicability Scope**: Actions that are not authorization-controlled and standard informational triggers do **not** require `permissionKey`. The optional `permissionKey` prop is strictly for protected operations.
* Arbitrary custom triggers must be wrapped in `<PermissionShield permissionKey={key}>`.

---

## 7. Responsive Behavior & Accessibility (a11y) Guidance

* **Breakpoints**: Standard MUI breakpoints (`xs: 0`, `sm: 600px`, `md: 900px`, `lg: 1200px`, `xl: 1536px`).
* **Header Auto-Scaling**: `textH1Bold`, `textH2Medium`, and `textH3Medium` automatically scale down below the `sm` breakpoint via `src/theme/typography.ts`.
* **Dynamic Contrast & Readability**:
  * **Mechanism**: Use `readableTextColor(bg)` from `src/theme/theme.ts` when placing text over dynamic brand/custom background fills to automatically select high-contrast ink (`charcoal[10]` vs `charcoal[100]`).
  * **Design Guidance**: Aim for 4.5:1 contrast on standard text and 3:1 on large text/icons against their immediate surface.
  * **Enforcement Status**: Contrast is guided by theme tokens and helper utilities (`readableTextColor`), but is not enforced by a global automated linting/test suite across every component.
* **Label Capitalization**: Action labels use `textTransform: 'capitalize'` built into `textB2SemiBold`.
* **Semantic ARIA**: Icon-only buttons must supply descriptive `aria-label` and `Tooltip`.

---

## 8. Canonical Code Recipes

All code recipes below adhere strictly to Sistent component conventions, canonical semantic tokens, accessibility guidelines, and AI guardrails:

### Recipe 1: Container Surface with Light/Dark Support
```tsx
import React from 'react';
import { styled, Box, Typography } from '@sistent/sistent';

const CardContainer = styled(Box)(({ theme }) => ({
  backgroundColor: theme.palette.background.card,
  color: theme.palette.text.default,
  border: `1px solid ${theme.palette.border.default}`,
  borderRadius: theme.shape.borderRadius,
  padding: theme.spacing(2),
}));

export const CustomCard: React.FC<{ title: string; children: React.ReactNode }> = ({ title, children }) => (
  <CardContainer>
    <Typography variant="textH3Medium" component="h3">
      {title}
    </Typography>
    <Box sx={{ marginTop: (theme) => theme.spacing(1.5) }}>
      {children}
    </Box>
  </CardContainer>
);
```

### Recipe 2: Authorization-Controlled Action Button

> **Note**: This pattern applies strictly to actions that are actually authorization-controlled. The optional `permissionKey` must not be interpreted as a requirement for every button or action in the system; standard actions and informational triggers should omit `permissionKey`.

```tsx
import React from 'react';
import { Button } from '@sistent/sistent';
import type { Key } from '@meshery/schemas/permissions';

interface ActionProps {
  label: string;
  onClick: () => void;
  permissionKey?: Key;
}

export const ActionButton: React.FC<ActionProps> = ({ label, onClick, permissionKey }) => (
  <Button
    variant="contained"
    color="primary"
    onClick={onClick}
    permissionKey={permissionKey}
    permissionAction="showShield"
  >
    {label}
  </Button>
);
```

### Recipe 3: Modal Dialog with Sistent Gradient Header
```tsx
import React from 'react';
import { styled, Dialog, DialogContent, Box, Typography } from '@sistent/sistent';

const ModalHeader = styled(Box)(({ theme }) => ({
  background: theme.palette.surface.tint,
  color: theme.palette.text.constant?.white,
  padding: theme.spacing(2),
  display: 'flex',
  justifyContent: 'space-between',
  alignItems: 'center',
}));

const ModalBody = styled(DialogContent)(({ theme }) => ({
  backgroundColor: theme.palette.surface.primary,
  padding: theme.spacing(2.5),
}));

export const SistentModal: React.FC<{
  open: boolean;
  title: string;
  onClose: () => void;
  children: React.ReactNode;
}> = ({ open, title, onClose, children }) => (
  <Dialog open={open} onClose={onClose} PaperProps={{ sx: { borderRadius: '8px', overflow: 'hidden' } }}>
    <ModalHeader>
      <Typography variant="textH3Medium">{title}</Typography>
    </ModalHeader>
    <ModalBody>
      {children}
    </ModalBody>
  </Dialog>
);
```

---

## 9. AI Coding Guardrails (UI & Styling Specific)

1. **Design Tokens ≠ Runtime Theme API**:
   > Translate semantic tokens into canonical runtime calls (`theme.spacing(2)`, `theme.shape.borderRadius`). Never write `theme.spacing.lg` or `theme.rounded.sm`.
2. **Color Literal Rule**:
   > Consumer/UI code must not introduce new raw color literals when an existing semantic Sistent token applies. Theme source and token definitions are exempt.
3. **Spacing & Shape Token Rule**:
   > Consumer/UI code must use `theme.spacing(n)` for element layout and gutters. Do not invent arbitrary inline pixel offsets when an 8px grid factor satisfies the requirement.
4. **Component Import Rule**:
   > Prefer `@sistent/sistent` when a Sistent abstraction exists. Use `@mui/material` when no equivalent exists or when implementing Sistent itself.
5. **Permission Rule**:
   > When an action is authorization-controlled, use the existing Sistent permission mechanism and provide the appropriate `permissionKey`. Do not invent local permission logic.
6. **No Manual Dark-Mode Forking**:
   > Avoid manual conditionals like `theme.palette.mode === 'dark' ? '#212121' : '#fff'`. Use semantic tokens (`theme.palette.background.card`, `theme.palette.surface.primary`, `theme.palette.text.default`) that resolve automatically.
7. **Preserve Typography Variants**:
   > Use `<Typography variant="textH1Bold">` through `<Typography variant="textC2Regular">` rather than ad-hoc inline font declarations.

---

## 10. Documentation / Implementation Drift Protocol

When `DESIGN.md` and repository source code disagree:
1. **Do not silently change the design contract.**
2. **Determine discrepancy classification**:
   * **Documentation Drift**: The source implementation was updated intentionally, but `DESIGN.md` was not updated to match (e.g. `surface-dark-card` frontmatter was `#121212` vs code `#212121`).
   * **Implementation Drift**: A component diverges from established design tokens due to an accidental or ad-hoc local override.
   * **Intentional Legacy / Compatibility Behavior**: An older token path maintained to avoid breaking consumer downstream imports (e.g. `background.default`).
   * **Intentional Exception**: A component has a specialized visual requirement that intentionally diverges from the standard token.
3. **Record the discrepancy in the audit log.**
4. **Only change the design contract when there is an explicit design-system decision to do so.**
5. **Do not make unrelated design changes during AI-context work.**

---

## 11. Do's and Don'ts

* **Do** keep teal (`#00B39F`) as the default primary interaction color.
* **Do** reserve gradients (`surface.tint`) for modal headers, drawer banners, and structural framing.
* **Do** prefer tonal layering, border contrast, and subtle surface depth before adding large shadows.
* **Do** treat dark mode as a fully supported surface system, not a simple color inversion.
* **Do** use `theme.spacing(factor)` for all layout margins and paddings.
* **Don't** flood content areas with saturated fills.
* **Don't** overuse large radii on utilitarian controls; reserve `16px` for showcase cards.
* **Don't** replace neutral text with accent colors unless the content is genuinely interactive or status-bearing.
* **Don't** write phantom theme paths like `theme.spacing.lg` or `theme.rounded.sm`.
