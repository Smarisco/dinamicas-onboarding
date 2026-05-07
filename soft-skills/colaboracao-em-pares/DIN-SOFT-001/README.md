# DIN-SOFT-001 — A Moeda de Duas Faces

> **Grupo:** Soft Skills | **Temática:** Colaboração em Pares | **Momento:** Fim de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-SOFT-001 |
| **Nome** | A Moeda de Duas Faces (The Two-Sided Coin) |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Soft Skills |
| **Subdomínio** | Colaboração em Pares |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Role-Playing` `Empatia` `QA` `MoSCoW` `Debate` `Onboarding`

---

## 2. Contexto

Debate estruturado com inversão de papéis: metade do grupo defende "Lançar Agora" (perspectiva Dev) e a outra defende "Atrasar e Testar" (perspectiva QA). Após o debate, os papéis são invertidos. A dinâmica força cada participante a construir argumentos técnicos e de negócio para a posição oposta à sua.

**Objetivo de aprendizagem:** Desenvolver empatia cognitiva entre perfis Dev e QA; compreender trade-offs de velocidade vs. qualidade em decisões go/no-go. Fundamentado nos construtos E3.1 (Socialização — Integração Social) e E1.4 (Aprendizado — Big Picture), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Exploration-Based (§III-B3, p.620).

**Cenário de uso:** Retrospectivas de incidentes de produção; treinamentos de gestão de produto; formação de times Dev+QA.

**Problema endereçado:** Conflito Dev vs. QA sem base técnica; falta de compreensão do papel do outro no processo. No onboarding: visão limitada ao próprio papel (E3.3, p.618 — ICSE 2021).

**Referências:** Spolin, V. (1963), *Improvisation for the Theater*; Robbins & Judge (2003), *Organizational Behavior*.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-04A | Cartões de Cenário de Conflito | PDF | Entrada | DIN-SOFT-001/cenarios_conflito.pdf |
| ART-04B | Roteiro do Facilitador | PDF | Entrada | DIN-SOFT-001/roteiro_facilitador.pdf |
| ART-04C | Matriz de Argumentos | XLSX | Saída | DIN-SOFT-001/matriz_argumentos.xlsx |
| ART-04D | Bastão da Fala (protocolo) | Markdown | Entrada | DIN-SOFT-001/bastao_fala.md |
| ART-04E | Customization Guide | Markdown | Entrada | DIN-SOFT-001/customization_guide.md |
| ART-04F | Ficha KPI | XLSX | Saída | DIN-SOFT-001/registro_kpi.xlsx |
| ART-04G | Diagrama de Debate | PDF | Referência | DIN-SOFT-001/models/fluxo_debate.pdf |
| ART-04H | Params | YAML | Metadados | DIN-SOFT-001/params.yaml |
| ART-04I | Relacionamentos | JSON | Metadados | DIN-SOFT-001/relationships.json |
| ART-04J | Profile Info | JSON | Metadados | DIN-SOFT-001/profile_info.json |

**Materiais físicos:** Cartões de cenário impressos; bastão da fala (objeto físico); post-its e canetas; quadro branco; cronômetro.

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Nenhum pré-requisito obrigatório | — | — |

**Recomendado (não obrigatório):** DIN-COM-001 — consolida comunicação precisa antes de escalonar para debate argumentativo com inversão de papéis.

**Dependências externas:**
- Spolin, V. (1963). *Improvisation for the Theater*. Northwestern University Press.
- Robbins, S.P.; Judge, T.A. (2003). *Organizational Behavior*, 10ª ed. Pearson.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala com dois grupos separados (mesas frente a frente ou lados opostos)
- **Participantes:** 6–20
- **Facilitador:** 1 (suporte ativo — media conflitos e mantém papéis)
- **Nível de experiência:** Nenhuma experiência prévia
- **Time-box total:** ~45 minutos

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Setup e Atribuição de Papéis | 5 min | Dividir grupos A e B; distribuir cartões de cenário |
| Preparação dos Argumentos | 10 min | Cada grupo prepara 3 argumentos técnicos + 3 de negócio |
| Exposição inicial | 4 min | A expõe (2 min) → B expõe (2 min) |
| Debate — Réplica/Tréplica | 15 min | Rodadas alternadas com bastão da fala |
| Inversão de Papéis | 2 min | Grupos trocam de posição sem novo cartão |
| Reflexão e Debriefing | 10 min | "Qual argumento do outro lado foi mais difícil de refutar?" |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Grupo A — "Lançar Agora" | Defende velocidade de entrega e impacto de negócio |
| Grupo B — "Atrasar e Testar" | Defende qualidade, risco e débito técnico |
| Facilitador | Media, cronometra, garante alternância com bastão da fala |

### Passo a passo do facilitador

1. Dividir sala em grupos A e B (frente a frente ou lados opostos).
2. Distribuir Cartões de Cenário (ART-04A) — mesmo cenário para ambos.
3. Explicar conceito de "advogado do diabo": defender posição atribuída, não a pessoal.
4. Preparação (10 min): cada grupo registra argumentos em post-its no quadro.
5. Exposição inicial com bastão da fala: A (2 min) → B (2 min).
6. Debate livre com bastão (15 min): réplica → tréplica → réplica...
7. Inversão: grupos trocam de posição e repetem exposição (opcional, +10 min).
8. Reflexão: "Qual foi o argumento mais difícil de refutar? Por quê?"

> **Instrução obrigatória para TEA:** Explicar "advogado do diabo" com exemplo concreto antes de começar. Reforçar: "Você defende a posição do cartão, não a sua opinião pessoal."

### Marco de Independência
Participante articula argumentos técnicos válidos para a posição oposta à sua sem auxílio do facilitador (ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Silenciosa (post-its) | TEA / ansiedade social alta | Todos os argumentos em post-its no quadro; sem exposição oral |
| GDPR/LGPD | Contexto de privacidade | Cenário: "Coletar mais dados" vs. "Conformidade legal" |
| Dívida técnica | Times sênior | Cenário: "Refatorar agora" vs. "Feature nova primeiro" |
| Sem inversão de papéis | Time com conflito real agudo | Mantém papéis fixos para evitar acirramento |
| Matriz MoSCoW | Treinamento de PO/Scrum | Adicionar priorização formal com Must/Should/Could/Won't |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| num_participantes | 6–20 | 6 | 30 |
| num_argumentos | 3+3 | 2+2 | 5+5 |
| dur_preparacao | 10 min | 5 | 20 |
| dur_exposicao | 2 min | 1 | 5 |
| num_rodadas_debate | 2 | 1 | 4 |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-COM-001 | O Campo Minado | Similar / Precedente | Consolida comunicação bilateral antes de debate argumentativo |
| DIN-AGIL-001 | Jogo das Bolinhas | Similar | Processo vs. prioridades — perspectivas complementares |

**Progressão recomendada:**
`DIN-AGIL-001 → DIN-AGIL-002 → DIN-COM-001 → DIN-SOFT-001 → DIN-MAND-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Validado em treinamentos corporativos Dev+QA |
| Nível de Qualidade | Alto — role-playing consagrada (Spolin, 1963) |
| Revisão | Facilitadores corporativos e coaches; v1.3.0 auditada 2026-04-28 |

### Critérios de Aceitação
- Todos os participantes conseguem nomear pelo menos 1 argumento técnico válido da posição oposta
- Taxa de mudança de opinião mensurável (pré/pós votação anônima)
- Debate mantém tom técnico sem conflito interpessoal

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Qualidade dos argumentos opostos (1–5) | Aprendizado (E1.4) | ART-04F — rubrica |
| KPI-2 | Taxa de mudança de opinião (%) | Socialização (E3.1) | ART-04F — votação pré/pós |
| KPI-3 | Argumentos técnicos válidos por grupo | Aprendizado (E1.1) | ART-04F — contagem |
| KPI-4 | Taxa de mudança de perspectiva | Socialização (E3.3) | ART-04F — autoavaliação |

### Referências
- Spolin, V. (1963). *Improvisation for the Theater*. Northwestern University Press.
- Robbins, S.P.; Judge, T.A. (2003). *Organizational Behavior*, 10ª ed. Pearson.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
- Object Management Group. *Reusable Asset Specification v2.2*. OMG, 2005.
