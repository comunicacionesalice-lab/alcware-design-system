---
version: alpha
name: "ALCWARE"
description: "Cross-product business software design system. Professional, compact, structured and data-oriented. Teal is the interaction color; Neutral is structural; semantic colors are reserved for meaning."
category: "Business Software & SaaS"
surface: web
colors:
  primary: "#00909E"
  on-primary: "#FFFFFF"
  primary-hover: "#007C88"
  primary-active: "#006B76"
  primary-deep: "#004F58"
  primary-medium: "#1EA4B0"
  primary-light: "#74D5DA"
  primary-border: "#BFECEF"
  primary-soft: "#E6F7F9"
  primary-subtle: "#F3FBFC"
  canvas: "#F4F8F9"
  surface: "#FFFFFF"
  surface-soft: "#FAFCFC"
  ink-strong: "#0B181B"
  ink: "#102124"
  ink-soft: "#2D3A3D"
  muted: "#5D7074"
  contextual: "#7C8D91"
  meta: "#91A4A8"
  border-strong: "#DDECEE"
  border: "#EAF3F4"
  success: "#43B76C"
  success-soft: "#DDF5E6"
  success-text: "#2F7F4E"
  warning: "#D9A441"
  warning-soft: "#FAF4E6"
  warning-text: "#8A6A2F"
  danger: "#E76F61"
  danger-soft: "#FFF0EE"
  danger-text: "#C9574B"
  orange: "#F28C45"
  blue: "#4F9BD3"
  cyan: "#58BFD0"
  violet: "#BFA6E8"
  pink: "#E5A5C2"
typography:
  kpi:
    fontFamily: "DM Sans"
    fontSize: 31px
    fontWeight: 800
    lineHeight: 1
    letterSpacing: -0.045em
  title:
    fontFamily: "DM Sans"
    fontSize: 20px
    fontWeight: 800
    lineHeight: 1.15
    letterSpacing: -0.02em
  section:
    fontFamily: "DM Sans"
    fontSize: 16px
    fontWeight: 800
    lineHeight: 1.2
  context:
    fontFamily: "DM Sans"
    fontSize: 14px
    fontWeight: 800
    lineHeight: 1.25
  body:
    fontFamily: "DM Sans"
    fontSize: 13px
    fontWeight: 600
    lineHeight: 1.5
  table:
    fontFamily: "DM Sans"
    fontSize: 11.5px
    fontWeight: 500
    lineHeight: 1.4
  metadata:
    fontFamily: "DM Sans"
    fontSize: 10.5px
    fontWeight: 500
    lineHeight: 1.4
  label:
    fontFamily: "DM Sans"
    fontSize: 9px
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: 0.055em
    textTransform: uppercase
rounded:
  table-action: 10px
  control: 12px
  card: 20px
  pill: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 20px
  2xl: 24px
  3xl: 32px
  4xl: 48px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: 38px
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.muted}"
    borderColor: "{colors.border-strong}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: 38px
  button-danger:
    backgroundColor: "{colors.danger-soft}"
    textColor: "{colors.danger-text}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: 38px
  input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    borderColor: "{colors.border-strong}"
    typography: "{typography.body}"
    rounded: "{rounded.control}"
    height: 40px
  table-action:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.muted}"
    borderColor: "{colors.border-strong}"
    rounded: "{rounded.table-action}"
    height: 36px
    width: 36px
---

# ALCWARE Design System

> Category: Business Software & SaaS
>
> Surface: web

ALCWARE is a cross-product design system for operational business software. It is shared across ALCWARE products and is not specific to CRM Seguros.

## Visual theme

Professional, clear, reliable, modern, structured and efficient. Interfaces are working tools first. Data, actions and hierarchy take priority over decoration. Keep screens compact and easy to scan without feeling cramped.

Do not replace this visual language with a generic SaaS kit. The component fixture in `components.html` is the visual reference for controls and patterns.

## Color architecture

ALCWARE uses separate color families with separate jobs. Never merge them.

**Primary / Teal = brand and interaction.** The main interactive accent is `#00909E` (Primary 600), not Primary 900. `#004F58` is a deep brand shade, not the default CTA.

**Neutral = structure.** Text, backgrounds, borders, metadata and quiet controls use Neutral colors.

**White / Surface = structural surface.** `#FFFFFF` is not Primary.

**Semantic = meaning only.** Success, Warning and Danger communicate status and feedback.

**Auxiliary = categories/data.** Orange, Blue, Cyan, Violet and Pink differentiate phases, categories and chart series. They do not replace the Primary action color.

### Primary / Teal scale

| Token | Hex | Role |
| --- | --- | --- |
| Primary 900 | `#004F58` | deepest brand emphasis |
| Primary 800 | `#006B76` | strong interactive text and icons |
| Primary 700 | `#007C88` | hover/active navigation |
| Primary 600 | `#00909E` | **default primary CTA and accent** |
| Primary 500 | `#1EA4B0` | accent and charts |
| Primary 300 | `#74D5DA` | focus/supporting accent |
| Primary 200 | `#BFECEF` | selected borders |
| Primary 100 | `#E6F7F9` | soft selected backgrounds |
| Primary 50 | `#F3FBFC` | subtle hover/highlight backgrounds |

### Neutral scale

| Token | Hex | Role |
| --- | --- | --- |
| Neutral 950 | `#0B181B` | strongest entity text |
| Neutral 900 | `#102124` | default foreground/headings |
| Neutral 800 | `#2D3A3D` | table/supporting strong text |
| Neutral 700 | `#5D7074` | secondary text |
| Neutral 600 | `#7C8D91` | contextual text |
| Neutral 500 | `#91A4A8` | metadata/placeholders |
| Neutral 400 | `#C2D2D6` | disabled/subtle boundaries |
| Neutral 300 | `#DDECEE` | strong borders |
| Neutral 200 | `#EAF3F4` | default borders/dividers |
| Neutral 100 | `#F4F8F9` | application canvas |
| Neutral 50 | `#FAFCFC` | soft surface/table header/neutral hover |

### Surface roles

| Role | Value |
| --- | --- |
| Page background | `#F4F8F9` |
| Surface | `#FFFFFF` |
| Surface soft | `#FAFCFC` |
| Border | `#EAF3F4` |
| Border strong | `#DDECEE` |
| Foreground | `#102124` |
| Strong entity text | `#0B181B` |
| Muted text | `#5D7074` |
| Metadata | `#91A4A8` |

### Semantic families

Semantic recipe: **100 = soft background · 500 = accent/dot/chart · 700 = text/icon**.

- Success: `#DDF5E6` / `#43B76C` / `#2F7F4E`; border `#BFE6CA`.
- Warning: `#FAF4E6` / `#D9A441` / `#8A6A2F`; border `#EAD9B0`.
- Danger: `#FFF0EE` / `#E76F61` / `#C9574B`; border `#F1B7B0`.

Auxiliary families use the same 100/500/700 recipe:
- Orange `#FFF3E8` / `#F28C45` / `#C96A28`.
- Blue `#EAF4FD` / `#4F9BD3` / `#356F9E`.
- Cyan `#E8F7F9` / `#58BFD0` / `#2E8790`.
- Violet `#F1EBFB` / `#BFA6E8` / `#7255A5`.
- Pink `#FBEAF1` / `#E5A5C2` / `#9B5574`.

## Typography

**DM Sans is mandatory for the UI.** Do not substitute Inter as the intended brand font. If DM Sans is not locally available, the renderer may temporarily show a fallback, but the design token must remain `DM Sans`.

| Role | Size | Weight | Use |
| --- | ---: | ---: | --- |
| KPI | 31px | 800 | primary metrics |
| Detail title | 20px | 800 | detail headers |
| Section title | 16px | 800 | card/section headings |
| Context/module | 14px | 800 | contextual module title |
| Body | 13px | 600 | operational copy/buttons |
| Table | 11.5px | 500 | row data |
| Metadata | 10.5px | 500 | secondary information |
| Label | 9px | 800 | labels/captions, uppercase when appropriate |

Primary entities in tables use stronger weight than metadata. Dates and supporting context remain visually quieter.

## Layout and spacing

Use an 8px baseline rhythm with 4px half-step when needed. Common spaces: 4, 8, 12, 16, 20, 24, 32 and 48px.

Application surfaces use `#F4F8F9` canvas and white cards/panels. Borders are preferred over heavy shadows. Shadows remain subtle and functional.

Radii: 10px table actions; 12px controls; 20px cards/panels; 9999px pill actions/chips.

## Buttons and actions

ALCWARE buttons are compact and intentional. Primary, Secondary, Neutral and Danger are the core variants.

**Primary:** 38px height, pill radius, `#00909E` background, white text. Hover `#007C88`. Use one clear primary action per local action group.

**Secondary:** white surface, 1px `#DDECEE` border, Neutral 700 text. Hover uses soft neutral/teal feedback; it must not visually compete with Primary.

**Neutral:** quiet low-priority action using neutral surface/border/text.

**Danger:** soft coral default (`#FFF0EE` with `#C9574B` text); destructive hover may become filled `#E76F61` with white text.

**Icon action:** 40×40px for general actions. **Table icon action:** 36×36px with 10px radius. Use Tabler icons. Common actions: eye = view, edit = edit, trash = delete, dots = more.

Do not replace ALCWARE buttons with generic rectangular SaaS buttons, dashed buttons or text-only link families unless a specific pattern calls for them.

## Navigation and interaction

Top navigation uses compact pill tabs. Selected tab: Primary 50 background, Primary 200 border, Primary 800 text. Hover is softer than selected.

`Volver` is text + left arrow only: no filled background and no visible border. Default Primary 800; hover Primary 700 and underline text only; focus uses a visible teal outline.

Selected controls use Primary 50/100 backgrounds with Primary 200 borders. Focus uses `0 0 0 3px rgba(0,144,158,.16)`.

## Forms, tables and overlays

Inputs are 40px high, 12px radius, white background and Neutral 300 border. Focus uses Primary 500 plus focus ring. Error uses Danger 500.

Tables are compact. The primary entity is the visual anchor. Context fields are regular/medium weight. Dates and metadata are quieter. Actions are last. Header background is Neutral 50 with strong teal/neutral labeling.

Modals use white surface, soft overlay, clear header and right-aligned footer actions. Destructive confirmation keeps Danger semantic treatment.

Dropdowns/popovers are compact, icon + text, with destructive actions separated visually.

## Cards, badges and feedback

Cards use white surface, Neutral 200 border, 20px radius and restrained shadow. KPI cards establish clear hierarchy between label, value and context.

Chips are interactive filters/selections. Badges are non-interactive statuses. Tags classify phases/categories. Do not use semantic colors merely for decoration.

Inline alerts and toasts use semantic families consistently. Empty states should be useful and quiet, not marketing illustrations by default.

## Motion and accessibility

Interaction transitions should be short: around 150–200ms. Avoid exaggerated scaling. Respect reduced motion.

All interactive controls need visible keyboard focus. Normal text should reach 4.5:1 contrast and large text 3:1 against the actual paired background.

## Do and avoid

**Do:** preserve DM Sans; use Primary 600 as the main CTA; keep Primary/Neutral/Semantic families distinct; use compact tables; make entity names stronger than metadata; keep secondary actions quieter; use Tabler icons; preserve the approved component geometry in `components.html`.

**Avoid:** using Primary 900 as the default button; treating White/Neutral as Primary; substituting Inter as the intended font; generic dashed button families; oversized marketing UI inside operational screens; decorative gradients; heavy shadows; arbitrary colors; product-specific visual languages that diverge from ALCWARE core.
