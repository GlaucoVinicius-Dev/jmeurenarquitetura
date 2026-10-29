# Sistema de Design • J.Meuren | Arquitetura • Interiores

Documento de governança e design para o portfólio **J.Meuren | Arquitetura • Interiores**, redesenhado com referências de estúdios contemporâneos do Mobbin (*A24*, *YLLW*, *Vucko*, *Unseen Studio*, *MOUTHWASH Studio*, *Freshman*).

---

## 1. Princípios & Fundamentos

1. **Rigor com os Textos Originais**:
   Preservação integral dos textos do arquiteto, bio autoral, links legítimos e todas as 8 etapas históricas da formação e trajetória profissional (1993 a 2025).
2. **Hero com Palco Vivo (Inspiração: *A24* & *YLLW*)**:
   Em vez de elementos estáticos, o Hero atua como um palco de galeria com transição de fotos dos projetos em tamanho generoso, índice numerado interativo e barra de progresso viva.
3. **Faixa Técnica Mineral (Inspiração: *Raw Materials* & *Unseen Studio*)**:
   Transição em terracota profunda (`#A9412D`) com letreiro contínuo original (*residencial • comercial • interiores*) e a ilustração em nanquim apresentada como prancha técnica com marcas de corte e selo de prancha.
4. **Portfólio com Dinamismo e Controle (Inspiração: *MOUTHWASH Studio* & *Freshman*)**:
   - Alternância entre **Grade Editorial Assimétrica** e **Modo Lista Tipográfico**.
   - **Hover Cycling**: Ao passar o cursor sobre qualquer cartão na grade, barras de progresso (estilo *stories*) alternam automaticamente entre as fotos do projeto.
   - **Cursor Magnético & Preview Flutuante**: No modo lista, o cursor acompanha o movimento exibindo a prévia da foto em tempo real.

---

## 2. Paleta Cromática

| Token CSS | Valor | Aplicação |
| :--- | :--- | :--- |
| `--paper` | `#F4EFE7` | Fundo principal da página (linho quente de prancha) |
| `--paper-2` | `#ECE5D9` | Superfície secundária sutil |
| `--paper-3` | `#E2D9CA` | Fundo neutro para molduras e placeholders |
| `--ink` | `#1A1714` | Títulos principais e botões primários (grafite mineral carvão) |
| `--ink-3` | `#3A332C` | Texto de leitura com contraste ideal |
| `--graphite` | `#5A5249` | Metadados, categorias e legendas técnicas |
| `--terra` | `#C24A33` | Terracota da marca (destaques, cursores e acentos) |
| `--terra-ink`| `#A63F2B` | Terracota adaptada para textos pequenos (WCAG AA > 5:1) |
| `--band` | `#A9412D` | Fundo da faixa monumental e seção de contato |
| `--clay` | `#E59A82` | Terracota clara para fundos escuros (Currículo) |

---

## 3. Tipografia Editorial

- **Monumental & Títulos**: `Instrument Serif` (serifa clássica, proporções monumentais e itálicos elegantes).
- **Interface & Leitura**: `Hanken Grotesk` (sans-serif contemporânea de alta legibilidade).
- **Metadados & Índices Técnicos**: `IBM Plex Mono` (monospace para numeração `01`, `02`, categorias e tags).

---

## 4. Estrutura de Seções

1. **Header Fixo**: Monograma da marca com rotação suave ao hover, links de âncora com traço ativo dinâmico e botão direto de WhatsApp.
2. **Hero Split**:
   - *Coluna Esquerda*: Título autoral "Arquitetura • Interiores", efeito de máquina de escrever com as 4 frases originais, botões de ação e lista dos projetos com numeração técnica.
   - *Coluna Direita*: Palco com transição suave das fotos reais dos projetos de [data/projetos.json](file:///c:/Users/glauc/Downloads/jmeurenarquitetura-main/data/projetos.json), barra de progresso, contador `01 / 07` e setas de navegação.
3. **Faixa Terracota**: Letreiro em duas direções com prancha em nanquim emoldurada com marcas de registro e selo técnico.
4. **Sobre**: Fotografia em proporção áurea com efeito sutil de paralaxe, biografia original e citação com revelação progressiva ao scroll.
5. **Currículo Completo (8 Marcos)**:
   - 01: Atualmente Autônomo
   - 02: Arquiteto e sócio na Empório Hass (2010/2025)
   - 03: Arquiteto na Sofisticatto Interiores (2009/2010)
   - 04: Especialista em Maquetes Eletrônicas (2000/2009) — 3dsMax - Vray
   - 05: Projetista (Brasília-DF) (1996/2000) — Progeto Interiores e Elementos Interiores
   - 06: Equipe Leonardo Caravana Guelman (2006) — Projeto Aurora Luminosa (Av. Central RJ 100 anos OSN)
   - 07: Colaboração CD-ROM Universo Gentileza (1999) — Arq. Leonardo Caravana Guelman
   - 08: Recuperação da Candelária - RJ (1993) — Arq. Leonardo Caravana Guelman
6. **Projetos**:
   - Filtros por categoria com contadores vivos (`Todos`, `Residencial`, `Comercial`).
   - Alternância Grade / Lista.
   - Hover interativo com passagem de fotos.
   - Modais integrados para Lightbox com miniaturas e Visualizador de Pranchas Técnicas em PDF.
7. **Contato & Rodapé**: Acesso direto por WhatsApp, e-mail e Instagram, com botão de retorno suave ao topo.
