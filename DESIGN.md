# Design System: Bianca Atti Portfolio

## Core Architecture
- Single Page Application estática (HTML5 + Vanilla CSS + JS minimal).
- Zero dependências de build ou frameworks pesados.

## Palette & Color Strategy (Strategy: Committed Emerald)
- Brand Primary: `#0b6b5b` (Verde Esmeralda)
- Brand Primary Hover: `#073d34`
- Accent Light: `#e4f1ec`
- Dark Background (Theme): `#0d1b16`
- Dark Card Background: `#14261f`
- Dark Border: `#23372e`
- Light Background: `#ffffff` e `#f4f7f5`
- Text Ink: `#10201b` / `#0d1b16`
- Text Muted: `#45554f` / `#4c5c56`

## Typography System
- Display / Headings: `Bricolage Grotesque`, sans-serif (Weights: 600, 700, 800)
- Body / Microcopy: `Manrope`, sans-serif (Weights: 400, 500, 600, 700)
- Line-wrap strategy: `text-wrap: balance` em títulos, `text-wrap: pretty` em parágrafos.

## Motion & Interaction Tokens
- Easing Curve: `cubic-bezier(0.16, 1, 0.3, 1)`
- Micro-hover duration: `0.25s`
- Card Hover Lift: `translateY(-5px)` com sombra suave `rgba(11,107,91,.22)`
- Floating WhatsApp button: pulse sutil e elevação `:hover`
