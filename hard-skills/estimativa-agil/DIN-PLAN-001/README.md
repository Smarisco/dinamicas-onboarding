# DIN-PLAN-001 — Planning Poker

> **Grupo:** Hard Skills | **Temática:** Estimativa Ágil | **Momento:** Início de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-PLAN-001 |
| **Nome** | Planning Poker |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Hard Skills |
| **Subdomínio** | Estimativa Ágil |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Estimativa de Esforço` `Gestão de Backlog` `Story Points` `Negociação` `Scrum` `Onboarding`

---

## 2. Contexto

Técnica de estimativa relativa em que cada membro do time revela simultaneamente sua estimativa de esforço (em Story Points, escala Fibonacci) para uma User Story. A simultaneidade evita ancoragem cognitiva. Divergências disparam discussão técnica até consenso.

**Objetivo de aprendizagem:** Calibrar estimativas coletivas de esforço, promover alinhamento técnico entre membros do time e desenvolver habilidade de negociação orientada a dados. Fundamentado nos construtos E1.x (Aprendizado) e E2.x (Confiança), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Problem-Based Learning (§III-B3).

**Cenário de uso:** Reuniões de planejamento de sprint; workshops de estimativa para times novos; onboarding técnico de desenvolvedores.

**Problema endereçado:** Estimativas inconsistentes e falta de consenso na equipe. No onboarding: dificuldade em compreender o esforço relativo de tarefas técnicas (E1.x — ICSE 2021).

**Referências:** Grenning, J. (2002), *Planning Poker or How to Avoid Analysis Paralysis*; Pozenel, M. et al. (2024), *Agile Effort Estimation*.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-06A | Baralho Planning Poker | PDF | Entrada | DIN-PLAN-001/baralho_planning_poker.pdf |
| ART-06B | Guia do Facilitador | Markdown | Entrada | DIN-PLAN-001/guia_facilitador.md |
| ART-06C | Ficha KPI | XLSX | Saída | DIN-PLAN-001/registro_kpi.xlsx |
| ART-06D | Params | YAML | Metadados | DIN-PLAN-001/params.yaml |
| ART-06E | Relacionamentos | JSON | Metadados | DIN-PLAN-001/relationships.json |
| ART-06F | Profile Info | JSON | Metadados | DIN-PLAN-001/profile_info.json |

**Materiais físicos:** Baralho de Planning Poker por participante (cartas: 0, 1, 2, 3, 5, 8, 13, 21, ?, ∞, ☕); lista de User Stories para estimar; quadro branco.

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Conhecimento básico de Scrum e Story Points | Conceitual | Pré-requisito de conhecimento, não de ativo |

**Recomendado (não obrigatório):** DIN-AGIL-001 e DIN-AGIL-002 — consolidam cultura ágil antes de introduzir estimativa formal.

**Dependências externas:**
- Grenning, J. (2002). *Planning Poker or How to Avoid Analysis Paralysis while Release Planning*.
- Pozenel, M. et al. (2024). *Agile Effort Estimation*. arXiv:2401.16152.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala de reunião com mesa central; quadro branco
- **Participantes:** 3–9
- **Facilitador:** 1 (modera discussões e busca consenso)
- **Nível de experiência:** Conhecimento básico de Scrum
- **Time-box total:** ~60 minutos (5 rodadas de ~10 min)

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Setup e Briefing | 10 min | Distribuir baralhos; explicar regras e escala Fibonacci |
| Rodadas de Estimativa | 40 min | 5 rodadas: PO apresenta → votação → discussão → consenso |
| Retrospectiva da Estimativa | 10 min | "O que aprendemos sobre a complexidade das tarefas?" |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Product Owner | Apresenta a User Story e esclarece dúvidas de negócio |
| Time de Desenvolvimento | Estima esforço técnico com cartas |
| Facilitador / Scrum Master | Modera, garante simultaneidade da revelação e gerencia discussões |

### Passo a passo do facilitador

1. Distribuir baralhos (1 por participante). Explicar a escala Fibonacci e o significado de ?, ∞ e ☕.
2. PO apresenta a primeira User Story — sem revelar estimativa própria.
3. Todos escolhem carta em silêncio. Revelar simultaneamente ao sinal do facilitador.
4. Se convergência: registrar o valor e avançar.
5. Se divergência (outliers): quem estimou o menor e o maior valor explicam seu raciocínio.
6. Nova rodada de votação após discussão. Repetir até consenso (máx. 3 tentativas por story).
7. Registrar estimativas na Ficha KPI (ART-06C) — desvio padrão e tempo por story.
8. Retrospectiva: identificar padrões de divergência e o que revelaram sobre a story.

> **Instrução obrigatória para TEA:** Anunciar o valor consensual verbalmente E escrevê-lo no quadro simultaneamente. Garantir que a agenda de stories seja distribuída antes da reunião.

### Marco de Independência
Participante contribui com estimativa fundamentada e justifica tecnicamente sem auxílio do facilitador (ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Baralho T-Shirt (XS/S/M/L/XL) | Times novos em Scrum | Substituir Fibonacci por tamanhos de camiseta |
| Online (Miro/PlanITPoker) | Remote onboarding | Usar ferramentas digitais com revelar simultâneo |
| Cartas de café | Times com sessões longas | Incluir carta ☕ para pausas quando necessário |
| Estimativa de tarefas técnicas (não stories) | Times técnicos | Usar em reuniões de refinamento técnico |
| Escala linear (1–10) | Iniciantes absolutos em estimativa | Simplificar antes de introduzir Fibonacci |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| num_rodadas | 5 | 3 | 10 |
| duracao_rodada | 10 min | 5 | 20 |
| max_tentativas_consenso | 3 | 1 | 5 |
| baralho_custom | não | sim | sim |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-AGIL-001 | Jogo das Bolinhas | Similar | Estimativa e fluxo — DIN-AGIL-001 introduz conceito de velocity como base para estimativa |
| DIN-RETRO-001 | Retrospectiva Guiada | Similar / Complementar | Melhoria contínua do processo de estimativa — revisar acurácia nas retrospectivas |

**Progressão recomendada:**
`DIN-AGIL-001 → DIN-AGIL-002 → DIN-PLAN-001 → DIN-COM-001 → DIN-RETRO-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Em validação interna |
| Nível de Qualidade | Médio — baseado em Grenning (2002) e Pozenel et al. (2024) |
| Revisão | Equipe de Agilidade e facilitadores internos |

### Critérios de Aceitação
- Todos os participantes revelam cartas simultaneamente (sem ancoragem)
- Pelo menos 1 divergência significativa é discutida e explicada
- Estimativas finais registradas com desvio padrão calculado

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Desvio padrão das estimativas por rodada | Aprendizado (E1.x) | ART-06C — cálculo estatístico |
| KPI-2 | Tempo médio para consenso (min) | Confiança (E2.x) | ART-06C — cronômetro |

### Referências
- Grenning, J. (2002). *Planning Poker or How to Avoid Analysis Paralysis while Release Planning*.
- Pozenel, M. et al. (2024). *Agile Effort Estimation*. arXiv:2401.16152.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
