---
name: Bianca Atti Portfolio
description: Portfólio de conversão para desenvolvedora de soluções digitais e agentes de IA
colors:
  primary: "#0b6b5b"
  primary-hover: "#073d34"
  primary-glow: "#127c68"
  accent-light: "#e4f1ec"
  accent-mint: "#b8efd6"
  success-green: "#16b56a"
  dark-bg: "#0d1b16"
  dark-card: "#14261f"
  dark-border: "#23372e"
  light-bg: "#ffffff"
  light-surface: "#f4f7f5"
  text-ink: "#10201b"
  text-heading: "#0d1b16"
  text-body: "#45554f"
  text-muted: "#4c5c56"
  text-nav: "#43524d"
  text-dark-muted: "#a9bab3"
typography:
  display:
    fontFamily: "Bricolage Grotesque, sans-serif"
    fontSize: "56px"
    fontWeight: 800
    lineHeight: 1.03
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Bricolage Grotesque, sans-serif"
    fontSize: "40px"
    fontWeight: 800
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Bricolage Grotesque, sans-serif"
    fontSize: "20px"
    fontWeight: 700
    lineHeight: 1.3
  body:
    fontFamily: "Manrope, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Manrope, system-ui, sans-serif"
    fontSize: "13px"
    fontWeight: 700
    letterSpacing: "0.06em"
rounded:
  pill: "999px"
  card: "20px"
  button: "12px"
  chip: "999px"
  avatar: "50%"
  badge: "8px"
spacing:
  xs: "8px"
  sm: "14px"
  md: "22px"
  lg: "32px"
  xl: "52px"
  section: "88px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.light-bg}"
    rounded: "{rounded.button}"
    padding: "16px 26px"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
  button-ghost:
    backgroundColor: "{colors.light-bg}"
    textColor: "{colors.text-ink}"
    rounded: "{rounded.button}"
    padding: "16px 24px"
  button-ghost-hover:
    backgroundColor: "#f4fbf8"
    textColor: "{colors.primary}"
  button-wa-pill:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.light-bg}"
    rounded: "{rounded.pill}"
    padding: "11px 20px"
  card-project:
    backgroundColor: "{colors.light-bg}"
    rounded: "{rounded.card}"
    padding: "22px"
  chip-label:
    backgroundColor: "{colors.accent-light}"
    textColor: "{colors.primary}"
    rounded: "{rounded.chip}"
    padding: "4px 10px"
---

# Design System: Bianca Atti Portfolio

## Overview

**Creative North Star: "A Consultora de Confiança"**

O sistema é construído sobre uma tensão deliberada: é ao mesmo tempo caloroso e preciso. O verde esmeralda profundo (`#0b6b5b`) funciona como a cor de uma pessoa confiável — não de uma startup de tecnologia. A tipografia combina a força expressiva do Bricolage Grotesque nos títulos com a clareza humanista do Manrope no corpo, criando uma página que se sente escrita por uma pessoa real, não por um template.

A densidade é média: espaço generoso entre seções (88px), mas grupos internos coesos. A página não respira ansiosa nem é austera — é organizada como uma boa conversa. O WhatsApp é o ponto de chegada de cada seção, posicionado sem ser agressivo.

O dark mode existe apenas na seção "Antes × Depois" (`#0d1b16`), como um contraste dramático e intencional que separa o problema da solução. Não é um modo alternativo — é um dispositivo narrativo.

**Key Characteristics:**
- Verde esmeralda como cor de confiança, não de tecnologia
- Tipografia em dois registros: display expressivo + corpo legível
- Fundo claro dominante com dark strip narrativo pontual
- WhatsApp como CTA universal, sempre acessível
- Micro-animações de floating e bubbleIn apenas no hero — não espalhadas

## Colors

O verde esmeralda é a cor da promessa cumprida. Tudo o mais serve de suporte.

### Primary
- **Esmeralda Profundo** (`#0b6b5b`): Cor da marca. Usada em botões primários, links ativos, ícones de check, badges inline e o avatar do header. Seu rarity é relativa — está presente mas nunca decora.
- **Esmeralda Noturna** (`#073d34`): Estado hover de todos os elementos primários. Escurece o esmeralda sem mudar o tom.
- **Esmeralda Viva** (`#127c68`): Borda do card "Depois, comigo" e gradientes de projetos. Mais saturada que o primary para contraste em fundo escuro.

### Secondary
- **Verde Menta Suave** (`#e4f1ec`): Fundo de chips e badges de status. Nunca como superfície de card.
- **Verde Seleção** (`#b8efd6`): `::selection` highlight. Um detalhe que só quem seleciona texto vê.
- **Verde Sucesso** (`#16b56a`): O ponto de status "online agora" no hero. Não reutilizado em nenhum outro lugar.

### Neutral
- **Tinta Principal** (`#10201b`): Cor base do `body`. Quase-preto com matiz verde para não criar contraste clínico.
- **Tinta Título** (`#0d1b16`): Headings e textos de ênfase. Mais fundo que o body.
- **Cinza Verde Corpo** (`#45554f`): Parágrafos principais e descrições em fundo claro.
- **Cinza Verde Suave** (`#4c5c56`): Descrições secundárias em cards.
- **Cinza Navegação** (`#43524d`): Links do header no estado default.
- **Superfície Principal** (`#ffffff`): Fundo do body, cards de projeto.
- **Superfície Alternada** (`#f4f7f5`): Seções Serviços e Como Funciona. Alternância suave, não contraste.
- **Dark Strip** (`#0d1b16`): Fundo da seção "Antes × Depois". Modo escuro pontual e narrativo.
- **Dark Card** (`#14261f`): Superfície de card dentro do dark strip.
- **Dark Border** (`#23372e`): Bordas dentro do dark strip.
- **Muted Dark** (`#a9bab3`): Texto de suporte na seção dark.

**The Esmeralda Única Rule.** O esmeralda aparece em botões, ícones de check e destaques de texto — mas nunca como fundo de superfície grande nem como cor decorativa sem propósito funcional. Quando em dúvida, usar `#e4f1ec` (accent-light) em vez do primary.

## Typography

**Display Font:** Bricolage Grotesque (600, 700, 800 — optical size 12–96)
**Body Font:** Manrope (400, 500, 600, 700)

**Character:** O Bricolage Grotesque tem uma tensão entre o geométrico e o humanista que faz os títulos parecerem assertivos sem serem frios. O Manrope é o oposto do jargão técnico — leve, legível e caloroso. A combinação transmite "profissional que fala sua língua".

### Hierarchy
- **Display** (800, 56px, lh 1.03, ls -0.03em): Headline principal do hero. Uma instância na página. Escala para 40px em tablet, 33px em mobile.
- **Headline** (800, 40px, lh 1.08, ls -0.02em): Títulos de seção (Serviços, Projetos, Como Funciona). Escala para 32px em tablet, 27px em mobile.
- **Title** (700, 20px, lh 1.3): Títulos de card e subtítulos dentro de seções. Sempre Bricolage Grotesque.
- **Body** (400–600, 17–18.5px, lh 1.6): Parágrafos principais. `text-wrap: pretty`. Sem limite de linha explícito, mas containers limitam a ~60ch na prática.
- **Label** (700, 13px, ls 0.06em, uppercase): Badges e chips (ex: "Projeto de demonstração", "HOJE"). Sempre em caps, nunca em titulos.

**The Balance Rule.** Todos os `h1`, `h2`, `h3` usam `text-wrap: balance`. Nenhum heading termina com uma palavra sozinha na linha. Parágrafos usam `text-wrap: pretty`.

## Layout

Container máximo de 1180px, centralizado, com padding horizontal de 28px (reduzido a 24px em mobile). O grid é contextual: 2 colunas no hero (1.05fr + 0.95fr), 2 colunas no Antes/Depois, 3 colunas em Serviços/Projetos/Steps, 2 colunas em Quem Sou (0.8fr + 1.2fr). Em viewports ≤900px, todos os grids colapsam para 1 coluna.

Seções alternam entre `#ffffff` e `#f4f7f5` para separação sem usar divisores. O padding vertical de seção é 88px desktop / 64px mobile. O header é `position: sticky` com `backdrop-filter: blur(10px)` — a página rola por baixo sem perder o acesso ao CTA.

**The Section Rhythm Rule.** Nenhuma seção começa sem 88px de respiro vertical (64px mobile). O espaço acima de um heading é sempre maior que o abaixo.

## Elevation & Depth

O sistema usa sombras com offset e blur generosos, sempre no tom esmeralda, nunca cinza. Superfícies em repouso são planas; sombras aparecem como resposta ao estado (hover, featured).

### Shadow Vocabulary
- **Hero Float** (`0 40px 80px -30px rgba(7,61,52,.55)`): Sombra profunda sob o mockup de WhatsApp no hero. Singular.
- **Card Hover** (`0 20px 40px -20px rgba(11,107,91,.22)`): Surge ao hover em cards de projeto. `.hv-card` class.
- **Button Primary Hover** (`0 16px 36px -12px rgba(11,107,91,.9)`): Glow esmeralda sob botões primários ao hover.
- **Button WA Hover** (`0 10px 24px -8px rgba(11,107,91,.8)`): Variante mais suave para botão da header.
- **About Photo** (`0 20px 40px -20px rgba(11,107,91,.4)`): Sombra estática sob a foto da Bianca.
- **Featured Card** (`0 30px 60px -30px rgba(11,107,91,.9)`): Card "Depois, comigo" com sombra intensa por ser o estado desejado.
- **WA Button Float** (`0 6px 18px -8px rgba(11,107,91,.7)`): Header CTA pill.

**The Emerald Shadow Rule.** Nenhuma sombra usa `rgba(0,0,0,...)` exceto no mockup de WhatsApp (onde imita a sombra real de um celular). Todas as demais sombras são derivadas do esmeralda.

## Shapes

O sistema usa bordas arredondadas generosas. Cards têm 20px de raio — suficientemente suaves para parecerem amigáveis, sem serem infantis. Botões primários têm 12px. Pills (WhatsApp header, badges) usam `border-radius: 999px`. Avatares são círculos perfeitos (50%). O badge de status do hero tem 8px.

Bordas são usadas com moderação: `1px solid` em cards no tom da superfície (claro ou escuro), nunca decorativas ou espessas. O header usa `1px solid #eceeed` como separador do conteúdo que rola por baixo.

**The Soft Edge Rule.** Nenhum elemento interativo tem `border-radius: 0`. O sistema não tem arestas vivas — nem mesmo o avatar de letra no mockup de WhatsApp.

## Components

### Buttons

O comportamento dos botões é tátil: eles sobem 2px no hover e afundam levemente no active (`scale(0.98)`). O movimento vem da classe `.hv-primary` / `.hv-wa` / `.hv-ghost`.

- **Shape:** Raio de 12px (botões inline) ou 999px (pill do header)
- **Primary:** Fundo `#0b6b5b`, texto branco, padding 16px 26px, shadow esmeralda. Hover: fundo `#073d34` + glow `0 16px 36px -12px rgba(11,107,91,.9)` + lift 2px
- **Ghost:** Fundo `#fff`, borda `1.5px solid #d5ddd9`, texto `#0d1b16`. Hover: borda e texto mudam para `#0b6b5b`, fundo `#f4fbf8`
- **WA Pill (header):** Como Primary mas `border-radius: 999px`, padding 11px 20px

### Chips / Badges

- **Label Chip:** Fundo `#e4f1ec`, texto `#0b6b5b`, 700, 11.5px uppercase, raio 999px, padding 4px 10px. Usado em cards de projeto ("Projeto de demonstração")
- **Status Pill:** Fundo `#0b6b5b`, texto branco, 12px bold, raio 999px. Usado no hero e no mockup de WhatsApp

### Cards / Containers

- **Project Card:** Fundo branco, borda `1px solid #e6ebe8`, raio 20px, padding 22px. Hover: borda muda para `#0b6b5b`, lift `translateY(-5px)`, shadow card hover
- **Dark Card (Before/After):** Fundo `#14261f`, borda `1px solid #23372e`, raio 20px, padding 32px
- **Featured Card ("Depois"):** Gradiente `linear-gradient(160deg, #0b6b5b, #073d34)`, borda `1px solid #127c68`, raio 20px, sombra profunda

### Navigation

- **Header:** Sticky, `background: rgba(255,255,255,.86)`, `backdrop-filter: blur(10px)`, `border-bottom: 1px solid #eceeed`
- **Links:** Manrope 600, 15px, `#43524d`. Sem underline. Ocultos em mobile (≤640px)
- **Logo:** Bricolage Grotesque 800, 20px, `#10201b`, ls -0.02em

### WhatsApp Mockup (Signature Component)

O mockup de smartphone no hero é um componente assinatura: simula uma conversa real de atendimento com animações escalonadas (`bubbleIn` + delays). Representa o produto vendido (agente de WhatsApp) em vez de mostrar uma screenshot genérica. Fundo `#0b141a` (dark phone body), conversa em `#efe7dd` (WhatsApp beige), bolhas do cliente em branco, bolhas do agente em `#d9fdd3` (verde WhatsApp). Animação `floatY` de 6s no container.

## Do's and Don'ts

### Do:
- **Do** usar `#0b6b5b` como cor de ação e confiança — em botões, checks e ícones funcionais.
- **Do** manter `text-wrap: balance` em todos os headings e `text-wrap: pretty` em parágrafos.
- **Do** usar sombras derivadas do esmeralda (`rgba(11,107,91,...)`) para todos os glows e halos.
- **Do** adicionar `translateY(-2px)` + shadow no hover de botões e `translateY(-5px)` em cards.
- **Do** respeitar `prefers-reduced-motion`: desativar todas as animações e transições quando solicitado.
- **Do** manter o CTA de WhatsApp acessível em toda seção — no header (sticky), no hero, em Quem Sou, e no footer.

### Don't:
- **Don't** usar gradiente de texto. Ênfase vem de peso (800) ou cor sólida do primary.
- **Don't** usar sombras `rgba(0,0,0,...)` em elementos de UI (apenas no mockup de telefone do hero).
- **Don't** animar a imagem da foto da Bianca diretamente — apenas o container pode receber feedback.
- **Don't** usar o dark background (`#0d1b16`) fora da seção narrativa Antes/Depois e do footer — é um dispositivo dramático, não um tema alternativo.
- **Don't** criar seções com `border-left` colorido em cards ou listas — o sistema não usa esse padrão.
- **Don't** adicionar números de seção (01/02/03) — a hierarquia visual já organiza a sequência.
