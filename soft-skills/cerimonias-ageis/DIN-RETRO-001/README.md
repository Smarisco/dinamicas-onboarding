# DIN-RETRO-001 — Retrospectiva Guiada

> **Grupo:** Soft Skills | **Temática:** Cerimônias Ágeis | **Momento:** Fim de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-RETRO-001 |
| **Nome** | Retrospectiva Guiada (Guided Retrospective) |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Soft Skills |
| **Subdomínio** | Cerimônias Ágeis |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Retrospectiva` `Melhoria Contínua` `Reflexão de Time` `Métricas de Sprint` `Abertura a Feedback` `Onboarding`

---

## 2. Contexto

Facilitação estruturada de retrospectiva ágil seguindo o modelo de 5 atividades de Derby & Larsen: Set the Stage → Gather Data → Generate Insights → Decide What to Do → Close the Retrospective. A estrutura guiada transforma a retrospectiva de conversa informal em processo sistemático de melhoria.

**Objetivo de aprendizagem:** Desenvolver habilidade de reflexão crítica coletiva e cultura de melhoria contínua. Fundamentado nos construtos E3.x (Socialização) e E2.x (Confiança), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Experiential Learning (§III-B2).

**Cenário de uso:** Reuniões de retrospectiva ao final de sprints; workshops de agilidade; onboarding de times em processo de retrospectiva estruturada.

**Problema endereçado:** Retrospectivas ineficazes com falta de engajamento; times que não se integram ao processo de melhoria contínua no onboarding (E3.x — ICSE 2021).

**Referências:** Derby, E. & Larsen, D. (2006), *Agile Retrospectives*; Hundhausen, C. et al. (2024), *Sprint Retrospectives in Undergraduate Teams*.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-10A | Template de Retrospectiva | Markdown | Entrada | DIN-RETRO-001/template_retrospectiva.md |
| ART-10B | Guia do Facilitador | Markdown | Entrada | DIN-RETRO-001/guia_facilitador.md |
| ART-10C | Ficha KPI | XLSX | Saída | DIN-RETRO-001/registro_kpi.xlsx |
| ART-10D | Params | YAML | Metadados | DIN-RETRO-001/params.yaml |
| ART-10E | Relacionamentos | JSON | Metadados | DIN-RETRO-001/relationships.json |
| ART-10F | Profile Info | JSON | Metadados | DIN-RETRO-001/profile_info.json |

**Materiais físicos:** Quadro branco ou digital; post-its (3 cores diferentes); marcadores; timer visível.

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Conhecimento básico de Scrum e retrospectivas | Conceitual | Pré-requisito de conhecimento, não de ativo |

**Recomendado (não obrigatório):** DIN-PLAN-001 — consolida cultura de Sprint antes de revisar o processo via retrospectiva.

**Dependências externas:**
- Derby, E. & Larsen, D. (2006). *Agile Retrospectives: Making Good Teams Great*. Pragmatic Bookshelf.
- Hundhausen, C. et al. (2024). *Sprint Retrospectives in Undergraduate Teams*. ICSE SEET.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala de reunião com quadro branco ou digital; post-its
- **Participantes:** 3–10
- **Facilitador:** 1 (guia o time na identificação de problemas e soluções)
- **Nível de experiência:** Conhecimento básico de Scrum
- **Time-box total:** ~50 minutos

### Time-box por fase (Modelo Derby & Larsen)

| Fase | Duração | Descrição |
|------|---------|-----------|
| Set the Stage | 5 min | Check-in: palavra/emoji de como cada um está chegando |
| Gather Data | 10 min | Post-its: O que foi bem? O que pode melhorar? Métricas do sprint |
| Generate Insights | 15 min | Agrupar post-its; identificar padrões e causas-raiz |
| Decide What to Do | 15 min | Priorizar 1–3 ações de melhoria com dono e prazo |
| Close the Retrospective | 5 min | Votação: foi útil esta retro? Como melhorar a próxima? |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Facilitador / Scrum Master | Guia cada fase; garante participação de todos; registra ações |
| Time | Contribui com percepções honestas; compromete-se com ações |

### Passo a passo do facilitador

1. Preparar quadro com 3 colunas: "O que foi bem?", "O que pode melhorar?", "Ações".
2. Set the Stage (5 min): cada pessoa diz uma palavra sobre como está chegando.
3. Gather Data (10 min): silêncio — todos escrevem post-its e colam nas colunas.
4. Ler os post-its em voz alta (facilitador) sem julgamento.
5. Generate Insights (15 min): agrupar post-its similares; nomear cada cluster; votar nos clusters mais importantes.
6. Decide What to Do (15 min): top 1–3 clusters → ação concreta + dono + prazo.
7. Close (5 min): votação de utilidade da retro (polegar ou 1–5 dedos).
8. Registrar ações na Ficha KPI (ART-10C).

> **Instrução obrigatória para TEA:** Fase de escrita em silêncio é fundamental — elimina pressão de improviso oral. Tempo de cada fase exibido no quadro/timer visível. Estrutura das 5 fases anunciada antes de começar.

### Marco de Independência
Participante propõe ações de melhoria concretas (quem faz o quê até quando) sem auxílio do facilitador (ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Estrelas e Desejos | Times novos | Perguntas: "O que brilhou?" e "O que eu desejo para o próximo sprint?" |
| Barco e Âncoras | Visualização | Metáfora do barco: vento (impulso) vs. âncora (bloqueio) |
| Retro Técnica | Times de dev | Foco em práticas de engenharia: qualidade, débito técnico, deploys |
| Retro Interpessoal | Times com conflito | Foco em relações; facilitador com experiência em mediação |
| Online (Miro/Metroretro) | Remote teams | Ferramentas digitais com post-its virtuais |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| duracao_retro | 50 min | 30 | 90 |
| num_etapas | 5 | 3 | 7 |
| num_acoes_max | 3 | 1 | 5 |
| tema_retro | geral | tecnico | interpessoal |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-PLAN-001 | Planning Poker | Similar / Complementar | Retrospectiva permite revisar acurácia das estimativas do sprint |
| DIN-FEED-001 | Feedback em 4 Passos | Similar / Complementar | Feedback estruturado complementa a cultura de melhoria da retrospectiva |

**Progressão recomendada:**
`DIN-PLAN-001 → DIN-RETRO-001 → DIN-FEED-001 → DIN-PSAF-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Em validação interna |
| Nível de Qualidade | Médio — baseado em Derby & Larsen (2006) e Hundhausen et al. (2024) |
| Revisão | Equipe de Agilidade e facilitadores internos |

### Critérios de Aceitação
- Pelo menos 1 ação de melhoria com dono e prazo definidos
- Participação de todos (pelo menos 1 post-it por pessoa)
- Votação de utilidade da retro registrada

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Número de ações de melhoria propostas | Aprendizado (E1.x) | ART-10C — contagem |
| KPI-2 | Taxa de implementação das ações (%) | Confiança (E2.x) | ART-10C — acompanhamento no sprint seguinte |

### Referências
- Derby, E. & Larsen, D. (2006). *Agile Retrospectives: Making Good Teams Great*. Pragmatic Bookshelf.
- Hundhausen, C. et al. (2024). *Sprint Retrospectives in Undergraduate Teams*. ICSE SEET.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
