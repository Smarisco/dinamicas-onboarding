# DIN-COM-001 — O Campo Minado

> **Grupo:** Soft Skills | **Temática:** Comunicação | **Momento:** Meio de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-COM-001 |
| **Nome** | O Campo Minado (The Minefield) |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Soft Skills |
| **Subdomínio** | Comunicação |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Pair Programming` `Comunicação` `Debugging` `Mentoria` `Onboarding`

---

## 2. Contexto

Simulação de navegação verbal em campo com objetos: um participante ("Sistema", vendado ou de óculos) atravessa o campo guiado exclusivamente pelas instruções verbais do parceiro ("Programador", fora do campo). A metáfora representa um dev júnior executando instruções ambíguas de um sênior durante o debugging.

**Objetivo de aprendizagem:** Desenvolver comunicação precisa, escuta ativa e confiança mútua entre pares Sênior/Júnior. Fundamentado nos construtos E3.1 (Socialização — Integração Social) e E2.5 (Confiança — Confiança Interpessoal), conforme Ju et al., ICSE 2021, Tabela III.

**Cenário de uso:** Onboarding de dev júnior; workshop de pair programming; treinamento de mentoria.

**Problema endereçado:** Instruções ambíguas em code review; dev júnior isolado sem pedir ajuda. No onboarding: dificuldade de integração social por comunicação indireta (E3.2, p.618 — ICSE 2021).

**Referências:** Newstrom & Scannell (1980), *Games Trainers Play*; Robbins & Judge (2003), *Organizational Behavior*, 10ª ed.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-03A | Roteiro do Facilitador | PDF | Entrada | DIN-COM-001/roteiro_facilitador.pdf |
| ART-03B | Mapa do Campo (Objetos) | PDF | Entrada | DIN-COM-001/mapa_campo.pdf |
| ART-03C | Ficha KPI | XLSX | Saída | DIN-COM-001/registro_kpi.xlsx |
| ART-03D | Cartão de Comandos Válidos | PDF | Entrada | DIN-COM-001/comandos_validos.pdf |
| ART-03E | Customization Guide | Markdown | Entrada | DIN-COM-001/customization_guide.md |
| ART-03F | Diagrama de Fluxo | PDF | Referência | DIN-COM-001/models/fluxo_navegacao.pdf |
| ART-03G | Params | YAML | Metadados | DIN-COM-001/params.yaml |
| ART-03H | Relacionamentos | JSON | Metadados | DIN-COM-001/relationships.json |
| ART-03I | Profile Info | JSON | Metadados | DIN-COM-001/profile_info.json |

**Materiais físicos:** 10–15 objetos leves (garrafas, cones, caixas); vendas ou óculos opacos (opcionais); fita adesiva para marcação de partida/chegada; cronômetro.

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Nenhum pré-requisito obrigatório | — | — |

**Recomendado (não obrigatório):** DIN-AGIL-001 e DIN-AGIL-002 — estabelecem base de auto-organização e comunicação em equipe antes de aprofundar comunicação bilateral 1:1.

**Dependências externas:**
- Newstrom, J.W.; Scannell, E.E. (1980). *Games Trainers Play*. McGraw-Hill.
- Robbins, S.P.; Judge, T.A. (2003). *Organizational Behavior*, 10ª ed. Pearson.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala 30 m², piso plano, sem mobiliário no centro
- **Participantes:** 4–6 duplas (8–12 total)
- **Facilitador:** 1 (suporte mentor — guia passo a passo quando necessário)
- **Nível de experiência:** Nenhuma experiência prévia
- **Time-box total:** ~40 minutos

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Setup | 5 min | Montar campo com objetos; marcar partida/chegada com fita |
| Briefing e distribuição | 5 min | Explicar papéis; distribuir Cartão de Comandos (ART-03D) |
| Travessia — Papel 1 | 10 min | "Sistema" (vendado/óculos) guiado pelo "Programador" |
| Inversão de papéis | 2 min | Trocar papéis sem reorganizar o campo |
| Travessia — Papel 2 | 10 min | Repetir com papéis invertidos |
| Debriefing | 10 min | "Quantas instruções foram ambíguas? Por quê?" |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Sistema (vendado) | Executa as instruções literalmente; não pode perguntar |
| Programador (guia) | Instrui verbalmente de fora do campo; não pode tocar |
| Facilitador | Cronometra; registra colisões; garante segurança |

### Passo a passo do facilitador

1. Montar campo: 10–15 objetos distribuídos aleatoriamente no espaço.
2. Marcar partida e chegada com fita adesiva colorida.
3. Distribuir Cartão de Comandos: "2 passos à frente", "90° à esquerda", etc.
4. "Sistema" entra vendado (ou com óculos opacos) no ponto de partida.
5. "Programador" guia verbalmente de fora do campo — sem tocar.
6. Registrar colisões (= bugs) na Ficha KPI (ART-03C).
7. Após 10 min: inversão de papéis sem reorganizar o campo.
8. Debriefing: comparar colisões Papel 1 vs. Papel 2; explorar causas.

> **Instrução literal obrigatória para TEA:** Reforçar antes de iniciar: "O Sistema executa exatamente o que ouve — 2 passos significa 2 passos, não 'vá em frente até o obstáculo'."

### Marco de Independência
Participante guia o parceiro com zero colisões sem intervenção do facilitador (ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Sem venda (escrita prévia) | TEA / ansiedade alta | Programador escreve instruções antes; Sistema segue lista escrita |
| Remota via chat | Remote onboarding | Instruções por Slack com delay de 5 s entre mensagens |
| Múltiplos Sistemas | Turmas grandes | 1 Programador guia 2–3 Sistemas simultâneos (simula 1:N) |
| Campo codificado | Perfil técnico avançado | Comandos em pseudocódigo ("move(2, NORTH)") |
| Sem objetos (grade desenhada) | Espaço limitado | Grade 5×5 desenhada no chão; objetos = células marcadas |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| num_duplas | 4–6 | 2 | 15 |
| num_objetos | 10–15 | 5 | 25 |
| duracao_travessia | 10 min | 5 | 20 |
| com_venda | opcional | não | sim |
| num_inversoes | 1 | 1 | 3 |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-AGIL-001 | Jogo das Bolinhas | Similar | Auto-organização compartilhada; recomendado como base antes de comunicação bilateral |
| DIN-SOFT-001 | A Moeda de Duas Faces | Similar / Complementar | Aprofunda empatia e inversão de perspectiva em contextos de conflito técnico |

**Progressão recomendada:**
`DIN-AGIL-001 → DIN-AGIL-002 → DIN-PLAN-001 → DIN-COM-001 → DIN-SOFT-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Validado em treinamentos de Pair Programming |
| Nível de Qualidade | Alto — dinâmica consagrada (Newstrom & Scannell, 1980) |
| Revisão | Facilitadores de grupo e coaching; v1.3.0 auditada 2026-04-28 |

### Critérios de Aceitação
- Pelo menos 1 dupla completa a travessia com zero colisões após a inversão de papéis
- Debriefing identifica pelo menos 2 instruções ambíguas concretas
- Participantes conseguem relacionar o aprendizado a situações reais de code review

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Colisões com objetos (bugs) | Aprendizado (E1.2) | ART-03C — contagem |
| KPI-2 | Tempo de travessia (s) | Confiança (E2.5) | ART-03C — cronômetro |
| KPI-3 | Delta colisões Papel 1 vs. Papel 2 | Aprendizado | ART-03C — comparação |
| KPI-4 | Tempo até 1ª execução sem hesitação | Socialização (E3.1) | ART-03C — cronômetro |

### Referências
- Newstrom, J.W.; Scannell, E.E. (1980). *Games Trainers Play*. McGraw-Hill.
- Robbins, S.P.; Judge, T.A. (2003). *Organizational Behavior*, 10ª ed. Pearson.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
- Object Management Group. *Reusable Asset Specification v2.2*. OMG, 2005.
