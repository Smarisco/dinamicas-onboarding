# DIN-AGIL-001 — Jogo das Bolinhas

> **Grupo:** Hard Skills | **Temática:** Metodologias Ágeis | **Momento:** Início de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **ID** | DIN-AGIL-001 |
| **Nome** | Jogo das Bolinhas (Ballpoint Game) |
| **Versão** | 1.0.0 |
| **Status** | Aprovado |
| **Criação** | 2025-01-01 |
| **Última revisão** | 2026-04-28 |

**Descrição:** Simulação iterativa com bolinhas para demonstrar empiricamente a diferença entre fluxo e ocupação em times ágeis.

**Tags:** `Scrum` `Lean` `Velocity` `Melhoria Contínua` `Gamification` `Simulação`

---

## 2. Contexto

| Campo | Valor |
|-------|-------|
| **Domínio** | Engenharia de Software — Gestão Ágil, Scrum, Lean, Melhoria Contínua |
| **Público-alvo** | Facilitadores Scrum, Coaches Ágeis, Professores de ES, Times de Desenvolvimento (3–10 pessoas) |
| **Problema de negócio** | Times que confundem esforço individual com produtividade coletiva; ausência de cultura de melhoria contínua |
| **Cenário de uso** | Treinamento introdutório Scrum; onboarding; retrospectivas de times com baixa velocidade |

### Mapeamento de Habilidades

| Tipo | Habilidades |
|------|-------------|
| **Soft Skills** | Auto-organização; Segurança Psicológica; Comunicação Explícita |
| **Hard Skills** | Estimativa (Velocity); Pensamento Sistêmico |

---

## 3. Artefatos

| ID | Artefato | Tipo | Localização |
|----|----------|------|-------------|
| ART-01A | Guia do Facilitador | PDF | `DIN-AGIL-001/guia_facilitador.pdf` |
| ART-01B | Quadro de Pontuação | Modelo | `DIN-AGIL-001/quadro_pontuacao.md` |
| ART-01C | Checklist de Materiais | Markdown | `DIN-AGIL-001/checklist.md` |
| ART-01D | Customization Guide | Markdown | `DIN-AGIL-001/customization_guide.md` |
| ART-01E | Manifesto de Metadados | YAML | `DIN-AGIL-001/params.yaml` |
| ART-01F | Perfil de Extensão TEA | JSON | `DIN-AGIL-001/profile_info.json` |
| ART-01G | Relacionamentos | JSON | `DIN-AGIL-001/relationships.json` |

**Materiais físicos:** 50+ bolinhas de espuma; cronômetro; quadro branco.

---

## 4. Dependências

| Campo | Valor |
|-------|-------|
| **Ativos precedentes** | Nenhum |
| **Dependências externas** | Gloger (2008); Agile42 Ballpoint Game Guide |
| **Espaço físico** | Mínimo 20 m², sem mesas no centro |
| **Ferramentas** | 50+ bolinhas; cronômetro; quadro branco; 1 facilitador treinado |

---

## 5. Guia de Uso (Scaffolding)

### Regras — escrever no quadro antes de começar

1. Todos os participantes devem tocar na bola
2. A bola deve ter tempo de ar obrigatório entre toques
3. Começa e termina na mesma pessoa
4. Não pode passar para o vizinho imediato
5. Bola no chão = defeito (não conta)

### Ciclo Iterativo — 5 Sprints × 4 minutos

| Fase | Duração | O que acontece |
|------|---------|----------------|
| Planejamento | 1 min | Time define meta e estratégia |
| Execução (Sprint) | 2 min | Passagem das bolinhas |
| Review / Retrospectiva | 1 min | Contagem e reflexão |

### Evolução esperada

- **Sprint 1:** Caos — time não sabe como se organizar
- **Sprints 2–3:** Adaptação — surgem padrões e acordos
- **Sprints 4–5:** Otimização — fluxo emerge naturalmente

### Debriefing

> *"O que causou o maior salto de produtividade: trabalhar mais rápido ou mudar o processo?"*

**Lição central:** Processo > Esforço bruto.

---

## 6. Customização

| Variante | Descrição |
|----------|-----------|
| DIN-AGIL-001-VAR1 | Bolinhas com pesos diferentes — simula variabilidade de WIP |
| DIN-AGIL-001-VAR2 | Versão remota — objetos virtuais em quadro digital |
| DIN-AGIL-001-VAR3 | Com debriefing estendido — aprofundamento em métricas de fluxo |

---

## 7. Relacionamentos

| Ativo | Tipo | Justificativa |
|-------|------|---------------|
| DIN-AGIL-002 — Construção com Blocos | Similar | Mesmo domínio ágil; aprofunda integração modular |
| DIN-COM-001 — O Campo Minado | Similar | Complementa comunicação explícita e auto-organização |

**Progressão recomendada:** DIN-AGIL-001 → DIN-AGIL-002 → DIN-COM-001 → DIN-SOFT-001

---

## 8. Avaliação e Qualidade

| Campo | Valor |
|-------|-------|
| **Status de validação** | Validado em múltiplas turmas de pós-graduação |
| **Nível de qualidade** | Alto — dinâmica canônica da literatura Scrum |
| **Revisão** | Facilitadores certificados CSM/PSM |

### KPIs de eficácia

| KPI | Como medir |
|-----|-----------|
| Aumento do Throughput por Sprint | Contagem de bolinhas registrada no quadro por sprint |
| Redução da variância Estimativa vs. Realizado | Comparação entre meta planejada e resultado obtido |

---

## 9. Profile Specification — Onboarding-Accessibility Profile (OAP-1.0)

### 9.1 Identificação do Profile

| Campo | Valor |
|-------|-------|
| **Profile Name** | Onboarding-Accessibility Profile |
| **Profile Version** | OAP-1.0 |
| **Asset Profile ID** | OAP-DIN-AGIL-001-v1 |
| **Data de Aderência** | 2026-04-28 |
| **Conformidade RAS Core** | Classification ✅ \| Solution ✅ \| Usage ✅ \| RelatedAssets ✅ |

### 9.2 Dimensão 1 — Pedagogia de Onboarding

| Metadado | Valor | Fundamentação |
|----------|-------|---------------|
| **Construto Pedagógico Primário** | E2.1 — Confiança (Frequência de Entrega) | ICSE 2021 Tabela III |
| **Estratégia de Onboarding** | Simple-Complex | ICSE 2021 §III-B1 p.619 |
| **Abordagem Metodológica** | Aprendizagem Experiencial + Gamificação | RAS 3.0 — Modeling approach |
| **Complexidade da Tarefa** | Baixa | Regras simples (5), ciclos rápidos (2 min), feedback imediato |
| **Marco de Independência** | Participante estima velocidade e sugere melhorias sem auxílio | ICSE 2021 §III-A p.617 |
| **Nível de Suporte Facilitador** | Mínimo — observa, não intervém | ICSE 2021 §III-A1 p.617 |

### 9.3 Dimensão 2 — Acessibilidade Neurodiversa (TEA)

| Aspecto | Estratégia | Implementação |
|---------|-----------|---------------|
| **Auditivo** | Sem dependência exclusiva de fala | Bolas de espuma + sinal visual para "pare" |
| **Visual** | Regras visíveis + previsibilidade | Quadro branco com 5 regras escritas durante toda a dinâmica |
| **Tátil/Motor** | Feedback tátil importante | Bolinhas de espuma (suaves); movimento livre |
| **Variabilidade de Entrada** | Múltiplas formas de participação | Contagem manual, registro escrito ou participação corporal |
| **Pontos de Atenção Sensorial** | Ruído e multidão | Espuma abafa ruído; grupos pequenos de 6–8 pessoas |
| **Literalidade** | Instruções literais | "Bola no chão = defeito" é literal, não metáfora |
| **Previsibilidade** | Estrutura clara e repetível | 5 sprints = padrão fixo; Setup → Sprint → Retro → Debriefing sempre igual |

### 9.4 Dimensão 3 — Rastreabilidade RAS 3.0

| Metadado | Valor |
|----------|-------|
| **Tipo de Ativo** | dinâmica_presencial |
| **Parent Asset ID** | Nenhum — ativo raiz |
| **Tipo de Linhagem** | raiz (root) |
| **Variantes documentadas** | DIN-AGIL-001-VAR1, DIN-AGIL-001-VAR2, DIN-AGIL-001-VAR3 |

---

## Referências

- Gloger, B. (2008). *Ballpoint Game*
- Agile42. *Ballpoint Game Guide*
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021
- Object Management Group. *Reusable Asset Specification v2.2*. OMG, 2005
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE 2025
