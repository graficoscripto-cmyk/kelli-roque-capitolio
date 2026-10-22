# Kit Google SEO + GEO (IAs) — Passeios de Lancha Kelli Roque (Capitólio - MG)

Este documento reúne tudo o que já foi configurado no código do site e o passo a passo rápido para quando o domínio próprio for conectado.

## 1. O que já está 100% pronto e ativo no site
- **Schema `@graph` JSON-LD Completo (`index.html`):**
  - `WebSite` + `WebPage` + `BreadcrumbList`
  - `LocalBusiness` + `TravelAgency` + `BoatTourAgency` com NAP oficial (`Passeios de lancha Kelli Roque`, `Rodovia MG-050, KM 306 — Ponte do Rio Turvo, Capitólio - MG, 37930-000`, `+55-35-99823-5432`)
  - Coordenadas exatas (`-20.6428, -46.2755`), `hasMap` apontando para o Place ID oficial (`ChIJnaD4ukF5eAwRujDiKt4jXFk`)
  - `AggregateRating` (`5.0` estrelas com `174` avaliações reais) + `Review` estruturados
  - `OfferCatalog` com os passeios oficiais (**Cânions de Capitólio**, **Lagoa Azul** e **Vale dos Tucanos** — sem Cascata)
  - `FAQPage` com 6 perguntas e respostas ricas para aparecer nos resultados expandidos do Google e nas respostas do ChatGPT / Perplexity / Gemini
- **Arquivos Técnicos de Indexação:**
  - `/robots.txt` liberando Googlebot e todos os crawlers de IA (`GPTBot`, `OAI-SearchBot`, `ClaudeBot`, `PerplexityBot`, `Google-Extended`)
  - `/sitemap.xml` com sitemap de imagens 4K e fotos reais dos Cânions, Lagoa Azul e Vale dos Tucanos
  - `/llms.txt` estruturado para leitura direta por LLMs (ChatGPT, Claude, Perplexity, Gemini)
  - Kit completo de Favicons (`favicon.ico`, `favicon.svg`, `favicon-16x16.png` até `512x512.png`, `apple-touch-icon.png`, `site.webmanifest`)

## 2. Texto pronto para colar no Google Meu Negócio (Perfil da Empresa)
- **Nome da empresa:** Passeios de lancha Kelli Roque
- **Categoria principal:** Agência de passeios de barco
- **Categorias adicionais:** Atração turística, Agência de turismo, Serviço de aluguel de barcos
- **Descrição sugerida (740 caracteres):**
  > Viva o melhor do Mar de Minas com a Passeios de Lancha Kelli Roque em Capitólio - MG! Com saída oficial na Ponte do Rio Turvo (MG-050, KM 306), realizamos passeios de lancha privativos e compartilhados pelo Lago de Furnas. Nosso roteiro visita os imponentes Cânions de Capitólio, as águas cristalinas e o bar flutuante da Lagoa Azul e a enseada tranquila do Vale dos Tucanos. Lanchas modernas, higienizadas e equipadas com som Bluetooth, cooler térmico, coletes salva-vidas homologados e macarrões flutuantes. Atendimento 5 estrelas com a piloto Kelli Roque e reservas ágeis pelo WhatsApp com a Dara. Ideal para famílias com crianças, casais, grupos de amigos e pets! Chame no WhatsApp (35) 99823-5432.
- **Website para colocar no perfil:** `https://kelli-roque-capitolio.vercel.app/` (e substituir pelo domínio `.com.br` assim que registrar)
