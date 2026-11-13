## Olá, eu sou o Leandro Franco 👋

**Desenvolvedor back-end** — Java · Spring Boot · TypeScript · PostgreSQL\
Estudante de Análise e Desenvolvimento de Sistemas (Facint) · freelancer · Brasil

Gosto de pegar um problema real e levar até produção. Começo pelos requisitos,
testo contra banco de verdade e deixo cada decisão registrada junto do código,
para quem vier depois entender o porquê — e não só o quê.

📫 [LinkedIn](https://www.linkedin.com/in/leandrofigueiredofranco) · aberto a oportunidades em back-end ou full stack

---

### Projetos em destaque

#### [Kamile — agenda de bolso](https://github.com/Leandro-Franco/kamile-agenda)
API de uma agenda pessoal mobile-first: compromissos com recorrência real, tarefas,
checklists e avisos por Web Push.
- Monólito modular em 7 módulos que só conversam por SPI e eventos de domínio
- 640+ testes contra PostgreSQL real (Testcontainers), incluindo testes de concorrência
- Auditoria OWASP Top 10 com cada correção provada por teste; 34 requisitos documentados

`Java 21` `Spring Boot 3` `Spring Security` `PostgreSQL` `Flyway` `Testcontainers` `Docker` `GitHub Actions`

#### [Salvadores Nacionais — site do evento](https://github.com/Leandro-Franco/salvadores-nacionais-site) · [no ar](https://salvadores-nacionais.vercel.app)
Site de um evento beneficente de rap, com inscrições e venda de merch.
- Mercado Pago Checkout Pro pela API Orders, sem SDK, com webhook HMAC idempotente
- Privacidade por padrão (LGPD): e-mail e IP só como HMAC, Supabase com RLS fechado
- CI com typecheck, lint, testes com Postgres, build, audit de dependências e gitleaks

`Next.js 16` `React 19` `TypeScript` `PostgreSQL` `Drizzle` `Zod` `Vitest` `Vercel`

#### [The Sir Vault — loja com vitrine 3D](https://github.com/Leandro-Franco/thesirvault-portfolio) · [no ar](https://thesirvault.com.br)
Loja de um pacote digital para produtores musicais: o visitante explora um estúdio em 3D,
compra pelo Mercado Pago e recebe por e-mail um link pessoal para baixar os arquivos.
- Vitrine 3D em three.js sem framework, com gestos de toque e versão em lista para aparelhos sem 3D
- Backend serverless em Cloudflare Worker, em camadas (rotas, casos de uso, repositórios, serviços)
- Webhook do Mercado Pago com HMAC, links de download assinados e bucket privado; 123 testes no CI

`JavaScript` `three.js` `Vite` `Cloudflare Workers` `D1` `R2` `Mercado Pago` `node:test` `GitHub Actions`

#### [um - AU — extensão para clínica veterinária](https://github.com/Leandro-Franco/um-au-extensao)
Extensão de navegador que lê o atendimento aberto no sistema da clínica e envia para
uma planilha via n8n, acabando com a digitação dupla.
- Humano no controle: revisar e enviar são cliques separados, nada sai sozinho
- Máquina de estados, observação de navegação SPA e rascunho que sobrevive ao recarregar

`JavaScript` `WebExtensions (MV3)` `n8n` `Google Sheets`

#### Armazzem — monitoramento de mercados autônomos *(cliente; código privado)*
Ferramentas para a operação de uma rede de mercados autônomos 24h.
- Diário de revisão das câmeras: app web local em Node.js, usado pelo celular na mesma
  rede, que gera a planilha de controle por loja a cada mudança
- Automação da planilha de ocorrências em Google Apps Script, com fluxo de status,
  histórico, trava de concorrência, testes e plano de rollback
- Arquitetura proposta para monitoramento com visão computacional na borda (mini-PC)

`Node.js` `Google Apps Script` `ExcelJS`

---

### Como eu trabalho

- **Requisito antes do código** — nenhuma função principal entra sem requisito aprovado
- **Teste que prova** — banco real nos testes, CI em todo pull request
- **Segurança desde o início** — OWASP Top 10, CSP, RLS, falha fechada
- **Decisões registradas** — ADRs com data e motivo, inclusive do que deu errado
- **Histórico legível** — uma branch por funcionalidade, PR com CI verde e Conventional Commits

### Stack

**Back-end:** Java 21, Spring Boot 3, Spring Security, JPA/Hibernate, Flyway\
**Web:** TypeScript, Next.js, React, Node.js, Tailwind CSS, three.js\
**Dados:** PostgreSQL, Supabase, Drizzle ORM\
**Qualidade e entrega:** JUnit 5, Testcontainers, Vitest, GitHub Actions, Docker, Vercel, Cloudflare Workers\
**Automação:** n8n, Google Apps Script, extensões de navegador

---

<details>
<summary><b>In English</b></summary>

Hi, I'm **Leandro Franco**, a back-end developer from Brazil (Java · Spring Boot ·
TypeScript · PostgreSQL), studying Systems Analysis and Development and working as a
freelancer. I like taking a real problem all the way to production: requirements
first, tests against a real database, and every decision written down next to the code.

- **[Kamile](https://github.com/Leandro-Franco/kamile-agenda)** — Spring Boot API for a
  mobile-first personal planner: modular monolith, 640+ tests on real Postgres,
  OWASP Top 10 audit.
- **[Salvadores Nacionais](https://github.com/Leandro-Franco/salvadores-nacionais-site)** —
  Next.js site for a charity rap event, with Mercado Pago payments, privacy by default
  and a full CI pipeline.
- **[The Sir Vault](https://github.com/Leandro-Franco/thesirvault-portfolio)** — online
  store with an interactive 3D showroom (three.js), Mercado Pago checkout and automatic
  delivery through a serverless Cloudflare Worker.
- **[um - AU](https://github.com/Leandro-Franco/um-au-extensao)** — browser extension
  that sends vet clinic appointments to Google Sheets through n8n, with a human in the loop.
- **Armazzem** *(client, private)* — tooling for a chain of 24/7 self-service stores.

</details>
