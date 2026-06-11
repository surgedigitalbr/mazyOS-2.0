---
name: ajuda
description: >
  Mostra o que o MazyOS sabe fazer — lista as skills agrupadas, explica o loop de trabalho
  (memória, /atualizar, /salvar) e como o sistema decide o que usar. Use quando o usuário disser
  "ajuda", "/ajuda", "o que você faz", "o que o mazyos faz", "quais skills tem", "o que é cada
  coisa", "help", ou estiver perdido sobre o que pedir.
---

# /ajuda — O que o MazyOS faz

Lembrete rápido: **você não precisa decorar comando.** Só conversa — descreve o que quer fazer e o sistema aciona o que precisa. Esta lista é só pra referência.

## Como o MazyOS trabalha

Você dirige, a IA é o braço direito: vocês conversam, ela dá ideia, monta o projeto do cliente. Ela lê a memória do negócio antes de cada resposta, aplica a marca, e usa o conhecimento certo pela intenção da sua fala. Tudo organizado em pastas, versionado no seu GitHub.

**Loop do dia a dia:** trabalha conversando → `/atualizar` quando o chat encher (grava onde paramos) → `/compact` ou `/clear` (nativos) → janela nova retoma pela memória. `/salvar` manda pro repo do cliente.

## O que ela resolve (skills disponíveis)

**Operação & memória**
- `/abrir` — abre a sessão e diz onde paramos
- `/atualizar` — grava tudo na memória (inclusive o estado atual do trabalho)
- `/salvar` — commit + push no repo do cliente (no seu GitHub)
- `/novo-projeto` — cria pasta isolada de cliente/projeto
- `/briefing-cliente` — lê a transcrição da call e monta o perfil do cliente
- `/mapear-rotinas` — transforma o que você repete em skill nova

**Construção**
- `/design` — site, SaaS, micro-SaaS, dashboard, mobile — premium, sem cara de IA
- `/copy` — texto que vende (site, SaaS, ads, social), com a estrutura certa
- `/gerar-imagem` — foto, criativo, logo (SVG), banner — melhor modelo por caso
- `/deploy` — sobe o projeto na Vercel + domínio

**Marketing & conteúdo**
- `/carrossel` — carrossel/post pro Instagram com a marca
- `/reels` — roteiro + vídeo curto + legenda
- `/publicar-tema` — vira um tema em blog + carrossel + legendas
- `/seo` — SEO + GEO + Google Ads completo (8 passos)
- `/anuncio-google` — campanha em CSV pro Google Ads Editor
- `/aprovar-post` — publica blog + Instagram + Facebook
- `/responder-avaliacoes` — respostas pras reviews do Google

**Comercial**
- `/proposta` — proposta/orçamento premium com a marca da Surge

**Análise**
- `/analisar-dados` — resumo executivo de CSV/XLSX/PDF
- `/relatorio-ads` — relatório semanal de Google + Meta Ads
- `/email-profissional` — rascunho de email

## E por baixo: um arsenal que as skills puxam sozinhas

Além dessas, o MazyOS vem com um **arsenal de craft** (dezenas de skills) que as de cima **acionam automaticamente** conforme a tarefa pede — você nunca precisa chamar. São 81 skills no total. O que ele cobre por baixo:

- **Design premium** — `impeccable`, `taste`, `soft`, `gpt-taste` e cia. (o `/design` orquestra)
- **Produto/backend** — `supabase` (login, banco), `stripe` (pagamento), performance React/Next, QA com Playwright (pra SaaS/loja)
- **Conversão & growth** — `cro`, `pricing`, `paywalls`, `onboarding`, `analytics`, A/B test… (o site já nasce pensado pra converter)
- **Aquisição & vendas** — `cold-email`, `prospecting`, `lead-magnets`, `sales-enablement`, `competitors`
- **Estratégia & lançamento** — `content-strategy`, `customer-research`, `marketing-plan`, `launch`, `public-relations`
- **Documentos** — `pdf`, `docx`, `pptx` (proposta, contrato, ebook, slides)

Regra de ouro: essas nunca decidem marca/cor (isso é sempre do cliente) e nunca substituem as skills MazyOS de frente — só dão profundidade por baixo.

## Como usar de verdade

Não chame os comandos um a um. Fala natural: "vamos montar o site do cliente X", "agora o SEO", "monta uma imagem pra essa seção", "faz a proposta" — a IA reconhece e aciona o que precisa, às vezes várias skills juntas.

Mostrar essa lista enxuta no chat (não o arquivo inteiro). Se o usuário perguntar de uma skill específica, explicar só ela.
