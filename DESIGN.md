# Design

## Visual Theme

Forge Forward Engineering uses a restrained technical brand system: light, precise, laboratory-clean surfaces with dark graphite text, measured blue-green accents, hard-working grids, and subtle industrial cues. The physical scene is a quality or validation lead reviewing a consultant's site on a laptop between facility-readiness meetings, under bright office or lab-adjacent light, needing confidence quickly.

## Color Palette

- `--ink`: `oklch(22% 0.018 215)`, primary text.
- `--muted`: `oklch(44% 0.02 215)`, secondary text.
- `--paper`: `oklch(97% 0.008 205)`, page background.
- `--panel`: `oklch(94% 0.012 205)`, section tint.
- `--line`: `oklch(83% 0.018 205)`, borders and rules.
- `--forge`: `oklch(43% 0.085 203)`, primary action and section labels.
- `--oxide`: `oklch(57% 0.115 53)`, warm accent for forge-related emphasis.
- `--deep`: `oklch(28% 0.05 205)`, dark bands.

## Typography

Use a system stack to keep the site fast and dependable: `Aptos`, `Segoe UI`, `Arial`, sans-serif. Hierarchy comes from scale, weight, and spacing rather than decorative type. Headings use tight but non-negative letter spacing, body copy stays below 75ch.

## Components

- Header: compact sticky nav with text links and one clear contact action.
- Hero: split between oversized message, service proof points, and current industrial imagery.
- Service list: numbered consulting areas with varied row rhythm, not identical icon cards.
- About: founder-led section with current portrait and concise background copy.
- Contact: two-column inquiry form and direct contact details.
- Buttons: solid primary and quiet secondary variants with visible focus states.

## Layout

Use one long single page with anchored sections. Desktop layouts use asymmetric grids and large section spacing; mobile stacks content with stable form controls and generous touch targets. Cards are limited to repeated service/contact units only.

## Motion

Use a light initial reveal and hover/focus transitions only. Respect `prefers-reduced-motion`.
