# Prompts do projeto — Sensei Zanella JJ

> Fluxo por etapas (skill `/passo-a-passo`). Cada etapa só é executada após confirmação do usuário.

---

## PROMPT MASTER

Criar uma landing page profissional pra Rodrigo Zanella — faixa preta de Jiu-Jitsu,
professor na Academia CT Caveira, Licenciado e Bacharel em Educação Física, campeão
mundial de Jiu-Jitsu pela SJJIF (Japão). O projeto é um presente (sem cobrança).

**Objetivo:** divulgar a trajetória e as conquistas do atleta e captar patrocinadores.

**Tom:** sério, de alto rendimento, sem infantilização — a página precisa transmitir
autoridade técnica (faixa preta, formação acadêmica em Ed. Física) e resultado
(campeão mundial). Nada de clichê de "guru" ou linguagem genérica de marketing esportivo.

**Público-alvo:** patrocinadores em potencial — marcas de equipamento esportivo,
suplementação, academias parceiras, empresas locais.

**Identidade visual:** preto (`#0A0A0A`) + vermelho (`#C81E2C`) + branco + dourado
(`#C9A227`) como acento de conquista. Tipografia condensada/impactante nos títulos
(Bebas Neue) + Inter no corpo. Ver `identidade/design-guide.md`.

**Estrutura da página:**
1. Hero — foto de impacto, nome, título ("Faixa Preta · Campeão Mundial SJJIF"), CTA
2. Sobre — trajetória, formação (Lic. e Bacharel em Ed. Física), papel na CT Caveira
3. Conquistas — títulos e resultados, com destaque pro Mundial no Japão
4. Galeria — fotos de treino, competição e graduação
5. Patrocínio — proposta de valor pra quem patrocinar + contato

**Referências visuais:** Instagram @zanellajj (bloqueia scraping de imagem — fotos
precisam ser enviadas manualmente pelo usuário).

---

## ETAPA 1 — Coleta de referências e identidade visual

Analisar/receber as fotos do atleta, selecionar as melhores (competição, treino,
graduação, mídia). Paleta e tipografia já fechadas (ver Prompt Master) — ajustar só
se as fotos reais pedirem.

**Status:** paleta e tipografia definidas. Aguardando fotos.

---

## ETAPA 2 — Copywriting

Escrever todos os textos da página: headline do hero, bio/trajetória, lista de
conquistas (com datas e resultados reais), texto da seção de patrocínio, CTA final.

---

## ETAPA 3 — Estrutura e wireframe

Hierarquia de seções e comportamento responsivo (mobile primeiro).

---

## ETAPA 4 — Design e desenvolvimento (HTML/CSS)

Construir `index.html` **na raiz do repositório do projeto** (Regra de Ouro —
nunca em subpasta `site/`), usando a identidade e os textos definidos.

---

## ETAPA 5 — Galeria e conquistas (conteúdo real)

Popular a galeria e a seção de conquistas com fotos e informações reais.

---

## ETAPA 6 — Seção de contato/patrocínio

Proposta de valor + forma de contato real (WhatsApp, email).

---

## ETAPA 7 — Deploy

Seguir o checklist da skill `/passo-a-passo` (`checklist-deploy.txt`):
git init próprio → `.gitignore` do MazyOS → `vercel.json` (`framework: null`) →
repo no GitHub → push → import na Vercel.

---

### Status

- [x] Etapa 0 — pasta do projeto criada
- [~] Etapa 1 — paleta/tipografia definidas; aguardando fotos
- [ ] Etapa 2
- [ ] Etapa 3
- [ ] Etapa 4
- [ ] Etapa 5
- [ ] Etapa 6
- [ ] Etapa 7
