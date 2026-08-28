---
name: Bianca Atti Portfolio — Comprovante
description: Portfólio de conversão para desenvolvedora de soluções digitais e agentes de IA
colors:
  paper: "#f6f1e4"
  paper-deep: "#ece1c4"
  paper-bright: "#fffdf6"
  paper-line: "#d9caa0"
  ink: "#201b14"
  ink-soft: "#5b5344"
  ink-faint: "#948a6d"
  carbon: "#37307e"
  carbon-deep: "#241f57"
  carbon-bright: "#4a41a8"
  carbon-tint: "#e7e4f5"
  stamp-green: "#2e7a50"
  stamp-green-tint: "#dcede1"
  stamp-red: "#a8462f"
  stamp-red-tint: "#f3e2dc"
  wa-green: "#25d366"
typography:
  display:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: "55px"
    fontWeight: 700
    lineHeight: 1.04
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: "39px"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.015em"
  title:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: "19px"
    fontWeight: 600
    lineHeight: 1.3
  body:
    fontFamily: "IBM Plex Sans, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "IBM Plex Mono, ui-monospace, monospace"
    fontSize: "12.5px"
    fontWeight: 600
    letterSpacing: "0.06em"
rounded:
  ticket: "14px"
  button: "10px"
  pill: "999px"
  small: "8px"
  avatar: "50%"
spacing:
  xs: "8px"
  sm: "14px"
  md: "22px"
  lg: "32px"
  xl: "52px"
  section: "88px"
components:
  button-primary:
    backgroundColor: "{colors.carbon}"
    textColor: "{colors.paper-bright}"
    rounded: "{rounded.button}"
    padding: "15px 24px"
  button-primary-hover:
    backgroundColor: "{colors.carbon-deep}"
  button-ghost:
    backgroundColor: "{colors.paper-bright}"
    textColor: "{colors.ink}"
    rounded: "{rounded.button}"
    padding: "15px 24px"
  button-ghost-hover:
    borderColor: "{colors.carbon}"
    textColor: "{colors.carbon}"
  ticket-card:
    backgroundColor: "{colors.paper-bright}"
    rounded: "{rounded.ticket}"
    padding: "22px"
  proj-tag:
    backgroundColor: "{colors.carbon-tint}"
    textColor: "{colors.carbon}"
    rounded: "{rounded.pill}"
    padding: "4px 10px"
---

# Design System: Bianca Atti Portfolio — "Comprovante"

## Overview

**Creative North Star: "O Comprovante Digital"**

O sistema traduz a promessa da Bianca — transformar o caos manual (caderno,
grupos de WhatsApp, planilhas soltas) numa operação organizada e confirmada —
para o vocabulário visual do universo dela e dos clientes dela: nota de
serviço, recibo, via duplicada, carimbo de confirmado. Não é fintech nem
"startup verde"; é papel, carbono e tinta de carimbo — o objeto físico que
todo pequeno negócio brasileiro já segurou na mão.

A cor de marca deixa de ser o esmeralda genérico de SaaS e passa a ser um
índigo-violeta profundo (`#37307e`), a cor da tinta de carbono das vias
duplicadas antigas — confiável, oficial, mas quente por estar sobre papel
kraft, nunca sobre preto. A tipografia mistura o geométrico contemporâneo do
Space Grotesk nos títulos com o humanista do IBM Plex Sans no corpo, e usa o
IBM Plex Mono como "tinta de carimbo" — números de item, timestamps, códigos
e selos.

**Key Characteristics:**
- Papel kraft como fundo dominante — nunca preto ou near-black em seção alguma
- Índigo-carbono como cor de confiança/ação, não esmeralda nem terracota
- Mono (IBM Plex Mono) só em rótulos, timestamps e selos — nunca em parágrafos
- Bordas denteadas/picotadas (perfuração) e cantos cortados só nos 2 ou 3
  pontos que representam fisicamente "papel" (recibo do hero, via de footer)
- O recibo impresso da conversa de WhatsApp no hero é o elemento assinatura —
  substitui qualquer mockup de celular genérico
- Numeração (1/2/3) usada só na seção "Como funciona", porque ali é uma
  sequência real de etapas — não decoração

## Colors

O índigo-carbono é a tinta que confirma. O resto é papel e selo.

### Primary
- **Carbono** (`#37307e`): Cor da marca. Botões primários, links, ícones de
  check funcional, número de logo. Nunca usado como textura decorativa.
- **Carbono Profundo** (`#241f57`): Hover de todos os elementos primários.
- **Carbono Vivo** (`#4a41a8`): Glow do recibo no hero, variações de gradiente
  nos thumbnails de projeto.
- **Carbono Tinta Suave** (`#e7e4f5`): Fundo de chips/tags. Nunca superfície de
  card inteiro.

### Selos (uso funcional, não decorativo)
- **Verde Confirmado** (`#2e7a50`): Selo "confirmado", marcas ✓ da via
  "Depois". Só aparece como confirmação de algo que deu certo.
- **Vermelho Carimbo** (`#a8462f`): Marcas ✕ da via "Antes". Só aparece como
  sinalização de problema. Nunca em botões nem títulos.

### Papel e Tinta
- **Papel** (`#f6f1e4`): Fundo padrão do body.
- **Papel Profundo** (`#ece1c4`): Seções alternadas (Serviços, Como Funciona)
  e a via "Antes".
- **Papel Vívido** (`#fffdf6`): Superfície de cards e do recibo — mais claro
  que o fundo pra parecer "papel novo saindo da impressora".
- **Linha de Papel** (`#d9caa0`): Bordas tracejadas, divisórias picotadas.
- **Tinta** (`#201b14`): Texto base e headings.
- **Tinta Suave** (`#5b5344`): Parágrafos secundários.
- **Tinta Fraca** (`#948a6d`): Timestamps, legendas, texto quase apagado.

**The Single Ink Rule.** Carbono aparece em botões, links e destaques — nunca
como fundo de seção inteira fora do bloco de CTA final e do header do modal.
Quando em dúvida, usar `carbon-tint` em vez de `carbon` sólido.

## Typography

**Display Font:** Space Grotesk (500, 600, 700)
**Body Font:** IBM Plex Sans (400, 500, 600, 700)
**Utility Font:** IBM Plex Mono (500, 600, 700) — rótulos, timestamps, selos,
números de item, letreiro do footer.

**Character:** Space Grotesk tem cantos levemente quadrados que lembram
carimbo de borracha sem virar tipografia fria. IBM Plex Sans é neutro e
extremamente legível — a voz "sem termo técnico" da Bianca. IBM Plex Mono
carrega o peso semântico de "isso é um dado/registro", igual a uma máquina de
recibo.

### Hierarchy
- **Display** (700, 55px, lh 1.04): H1 do hero. Escala para 40px em tablet,
  33px em mobile.
- **Headline** (700, 39px, lh 1.1): Títulos de seção. Escala para 31px
  tablet, 26px mobile.
- **Title** (600, 19–20px): Títulos de card.
- **Body** (400–600, 15–18px, lh 1.55–1.65): Parágrafos. `text-wrap: pretty`.
- **Label/Mono** (600–700, 11–13px, ls 0.05–0.08em, uppercase): Kickers,
  tags, selos, timestamps do recibo. Sempre IBM Plex Mono.

**The Balance Rule.** `h1`/`h2`/`h3` usam `text-wrap: balance`.

## Layout

Container 1180px, padding 28px (24px mobile via clip nas seções). Grid
contextual: hero 1.05fr/0.95fr, vias 1fr/16px/1fr (com perfuração central),
serviços 1.15fr/1fr/1fr, projetos 3 colunas, quem-sou 0.78fr/1.22fr. Tudo
colapsa pra 1 coluna ≤900px.

Seções alternam entre `paper` (`#f6f1e4`) e `paper-deep` (`#ece1c4`) — nunca
para preto. Padding vertical de seção: 88px desktop / 64px mobile.

**The No-Black-Section Rule.** Nenhuma seção usa fundo preto ou near-black —
inclusive o "antes" da comparação, que no sistema anterior era dark mode.
Aqui o contraste entre "antes" e "depois" vem da textura do papel (fosco vs.
crisp) e da borda (tracejada vs. sólida carbono), não de luz vs. escuridão —
evita o clichê de "hero claro + bloco quase-preto" que qualquer gerador de
design cai por padrão.

## Signature Component: O Recibo do Hero

Um recibo impresso simulando a conversa real de WhatsApp, com borda inferior
picotada (`clip-path` em zigue-zague — classe `.torn-bottom`), saindo de uma
"boca de impressora" (barra escura de 14px) no topo. Ao carregar a página, o
recibo desliza pra baixo (`print-out`) e cada linha da conversa aparece em
sequência (`bubble-in` com delay incremental), terminando com um selo
"CONFIRMADO ✓" que salta em rotação (`stamp-thud`). É o único momento de
animação orquestrada da página — tudo mais é reveal de scroll discreto.

## Perfuração (Perforation)

Dois usos, nunca mais que isso:
1. `.perf-h` — linha horizontal pontilhada por buracos (radial-gradient) entre
   o hero e a seção "Antes × Depois", e no topo do footer.
2. `.perf-v` — a mesma técnica na vertical, separando as duas "vias" (Antes /
   Depois) como se fossem uma nota rasgada ao meio.

**The Restraint Rule.** Perfuração/carimbo/via só nesses pontos. O resto da
página (serviços, projetos, como funciona, quem sou) usa a mesma paleta e
tipografia mas em cards simples — o "papel rasgado" não se repete em todo
elemento só porque é o tema.

## Shapes

Cards e recibo: raio 14px. Botões: 10px. Pills/badges: 999px. Selo do
"confirmado": pill com borda 1.5px sólida, sem preenchimento. Números de
etapa (Como Funciona): círculo com borda tracejada — não quadrado
preenchido, pra diferenciar de um badge comum e sugerir "carimbo em
trânsito".

## Components

### Buttons
- **Primary:** `#37307e`, texto branco, raio 10px, sombra índigo. Hover:
  `#241f57` + lift 2px.
- **Ghost:** Fundo `paper-bright`, borda `paper-line`, texto `ink`. Hover:
  borda e texto viram `carbon`.
- **WhatsApp flutuante:** único elemento que usa o verde real do WhatsApp
  (`#25d366`) — funciona como selo de plataforma, não como cor de marca.

### Tags / Selos
- **Proj Tag:** fundo `carbon-tint`, texto `carbon`, mono, pill.
- **Selo Confirmado:** borda sólida `stamp-green`, sem fundo, mono uppercase,
  usado só no recibo do hero e na via "Depois".

### Cards
- **Ticket/Service Card:** fundo `paper-bright`, borda `paper-line`, raio
  14px. Hover: lift 4px + borda `carbon`.
- **Via Card:** "Antes" = `paper-deep` + borda tracejada `ink-faint`.
  "Depois" = `paper-bright` + borda sólida `carbon` + selo "confirmado" no
  canto.

## Do's and Don'ts

### Do:
- **Do** usar `carbon` (`#37307e`) como cor de ação — botões, links, ícones
  funcionais.
- **Do** manter mono (IBM Plex Mono) só para dados/rótulos/selos.
- **Do** manter o CTA de WhatsApp acessível em toda seção.
- **Do** respeitar `prefers-reduced-motion`.

### Don't:
- **Don't** usar fundo preto/near-black em qualquer seção.
- **Don't** usar terracota como cor de destaque dominante (só o vermelho de
  selo, com uso mínimo e só na via "Antes").
- **Don't** usar serifada em título ou corpo.
- **Don't** repetir perfuração/carimbo fora dos pontos documentados acima.
- **Don't** usar números de seção (01/02/03) fora de "Como Funciona", onde a
  sequência é real.
