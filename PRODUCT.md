# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

- **Clientes Residenciais:** Proprietários e famílias que buscam projetos autorais, reformas completas e interiores com marcenaria sob medida e soluções personalizadas de iluminação e conforto.
- **Clientes Comerciais:** Empreendedores, lojistas e empresários buscando concepção de espaços comerciais funcionais (quiosques, cafeterias, áreas comuns, gourmet) com identidade de marca forte.
- **Parceiros e Clientes Técnicos:** Pessoas interessadas em detalhes executivos, pranchas, plantas e memoriais técnicos em PDF.

## Product Purpose

Apresentar o portfólio autoral e a trajetória de mais de duas décadas do arquiteto J. Meuren, equilibrando a elegância visual dos projetos executados com o rigor técnico de apresentação (pranchas, memoriais em PDF) e facilitando o contato direto e imediato via WhatsApp.

## Positioning

"Arquitetura é música edificada": equilíbrio entre rigor técnico, sensibilidade estética e soluções sob medida que transformam intenções em espaços acolhedores, funcionais e com identidade única. Trajetória com mais de 25 anos de experiência prática e parcerias consolidadas (Empório Hass, Sofisticatto, modelagens históricas e 3D).

## Operating Context

- Navegação web fluída (desktop e mobile).
- Carregamento de imagens de alta resolução dos projetos e pranchas em PDF.
- Acesso rápido a canal de comunicação em tempo real (WhatsApp) para início de atendimento.

## Capabilities and Constraints

- **Single Page Application:** Estrutura estática leve em HTML5, CSS e JS vanilla.
- **Gestão de Conteúdo (Decap CMS):** Painel `/admin` que grava atualizações de projetos e imagens diretamente em `data/projetos.json` e na pasta `Projetos/`.
- **Visualizador Duplo:** Overlay nativo para galeria de fotos de alta fidelidade e visualizador de plantas/documentos técnicos em PDF.
- **Animações Fluidas:** Uso de GSAP para entrada elegante e transições sutis.

## Brand Commitments

- **Nome da Marca:** JMeuren | Arquitetura • Interiores.
- **Paleta de Identidade:** Grafite (#1A1A1A), Terracota (#C94C35) e Off-white (#F9F8F6).
- **Tipografia:** Playfair Display (elegância e título autoral) e Inter/Montserrat (clareza e leitura moderna).
- **Voz e Tom:** Sofisticado, técnico, acolhedor e direto.

## Evidence on Hand

- Logotipos vetorizados e transparentes em `assets/LogoJmeuren-removebg.png` e `assets/LogoJmeuren.png`.
- Ilustração artística autoral em nanquim em `assets/ilustracao-nanquim.png`.
- Foto profissional e histórico do arquiteto em `assets/sobre.jpg`.
- Acervo fotográfico e pranchas reais em PDF organizados na pasta `Projetos/` (Apartamentos 314 Norte, 403 Norte, 410 Norte, Park Sul, Condomínio Riacho Fundo, Inova Café Park Shopping, Ponte Alta).

## Product Principles

1. **O Trabalho em Primeiro Lugar:** A fotografia arquitetônica e os detalhes espaciais devem brilhar; a interface serve como moldura refinada.
2. **Equilíbrio entre Arte e Rigor Técnico:** Valorizar tanto a estética das imagens quanto a precisão das pranchas e memoriais técnicos.
3. **Conversão Natural:** O caminho para iniciar uma conversa no WhatsApp deve ser evidente e convidativo, sem ser intrusivo.
4. **Performance e Fluidez:** Carregamento ágil, sem travamentos no carrossel ou na navegação móvel.

## Accessibility & Inclusion

- Contraste legível entre elementos de texto e fundos.
- Navegação acessível por teclado (setas e ESC em galerias e modais).
- Textos alternativos descritivos para fotos e pranchas.
