# DIN-PSAF-001 — Termômetro Psicológico

> **Grupo:** Soft Skills | **Temática:** Segurança Psicológica | **Momento:** Fim de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-PSAF-001 |
| **Nome** | Termômetro Psicológico (Psychological Thermometer) |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Soft Skills |
| **Subdomínio** | Segurança Psicológica |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Segurança Psicológica` `Vulnerabilidade Profissional` `Autorregulação` `Comunicação Social` `Ansiedade Social` `Previsibilidade` `Onboarding`

---

## 2. Contexto

Dinâmica de autoavaliação coletiva que utiliza uma escala visual de termômetro (1–5) para medir e promover a segurança psicológica da equipe. Cada participante marca anonimamente seu nível de conforto para expressar opiniões, errar e pedir ajuda. Os resultados são discutidos em grupo para identificar barreiras e construir acordos de convivência.

**Objetivo de aprendizagem:** Medir o nível de segurança psicológica da equipe e promover cultura de vulnerabilidade profissional segura. Fundamentado nos construtos E2.x (Confiança) e E3.x (Socialização), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Experiential Learning (§III-B2).

**Cenário de uso:** Reuniões de equipe; check-ins periódicos; workshops de segurança psicológica; momento de consolidação ao final do onboarding.

**Problema endereçado:** Medo de expressar opiniões; falta de confiança para errar ou pedir ajuda. No onboarding: dificuldade em se sentir seguro para contribuir ativamente (E2.x — ICSE 2021).

**Referências:** Edmondson, A. (1999), *Psychological Safety and Learning Behavior in Work Teams*; Tkalich, A. et al. (2024), *The Role of Psychological Safety in Promoting Software Quality in Agile Teams*.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-12A | Quadro de Termômetro Visual | PDF | Entrada | DIN-PSAF-001/termometro_visual.pdf |
| ART-12B | Fichas Anônimas | PDF | Entrada | DIN-PSAF-001/fichas_anonimas.pdf |
| ART-12C | Guia do Facilitador | Markdown | Entrada | DIN-PSAF-001/guia_facilitador.md |
| ART-12D | Ficha KPI | XLSX | Saída | DIN-PSAF-001/registro_kpi.xlsx |
| ART-12E | Params | YAML | Metadados | DIN-PSAF-001/params.yaml |
| ART-12F | Relacionamentos | JSON | Metadados | DIN-PSAF-001/relationships.json |
| ART-12G | Profile Info | JSON | Metadados | DIN-PSAF-001/profile_info.json |

**Materiais físicos:** Sala de reunião com quadro branco; fichas anônimas (papel); marcadores; quadro de termômetro impresso ou desenhado (escala 1–5).

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Nenhuma experiência prévia necessária | Conceitual | Pré-requisito de conhecimento, não de ativo |

**Recomendado (não obrigatório):** DIN-FEED-001 — pratica feedback estruturado antes de medir segurança psicológica; DIN-RETRO-001 — retrospectivas constroem a base de confiança necessária para a dinâmica.

**Dependências externas:**
- Edmondson, A. (1999). *Psychological Safety and Learning Behavior in Work Teams*. Administrative Science Quarterly.
- Tkalich, A. et al. (2024). *The Role of Psychological Safety in Promoting Software Quality in Agile Teams*. Empirical Software Engineering.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala de reunião com quadro branco
- **Participantes:** 3–10
- **Facilitador:** 1 (criador de ambiente seguro; não avalia ou julga respostas individuais)
- **Nível de experiência:** Nenhuma experiência prévia necessária
- **Time-box total:** ~40 minutos

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Briefing e contexto | 10 min | Explicar segurança psicológica; mostrar termômetro; garantir anonimato |
| Marcação anônima | 5 min | Cada participante marca sua posição no termômetro via ficha anônima |
| Consolidação visual | 5 min | Facilitador coleta fichas e marca os pontos no quadro (sem identificar) |
| Discussão coletiva | 15 min | "O que nos impede de chegar ao 5?" — identificar barreiras e acordos |
| Encerramento | 5 min | Definir 1–2 acordos de convivência; próximo check-in agendado |

### Escala do Termômetro

| Nível | Significado |
|-------|------------|
| 1 | Não me sinto seguro para expressar opiniões ou errar |
| 2 | Me sinto seguro apenas em situações muito específicas |
| 3 | Me sinto parcialmente seguro — depende do contexto |
| 4 | Me sinto seguro na maioria das situações |
| 5 | Me sinto totalmente seguro para contribuir, errar e pedir ajuda |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Facilitador | Garante anonimato; conduz discussão sem apontar indivíduos; registra acordos |
| Participantes | Marcam honestamente; contribuem para identificar barreiras coletivas |

### Passo a passo do facilitador

1. Desenhar ou projetar o termômetro visual no quadro (escala 1–5 com descrições).
2. Explicar o conceito de segurança psicológica com exemplos concretos (ex.: "você pergunta quando não entende? você admite erro em reunião?").
3. Distribuir fichas anônimas — cada participante escreve apenas o número.
4. Recolher fichas e marcar pontos no termômetro sem identificar autores.
5. **Discussão coletiva (15 min):** "O que nos impede de chegar ao 5? O que pode mudar?"
6. Facilitador registra barreiras e propostas sem atribuir a pessoas.
7. Definir 1–2 acordos concretos de convivência: o que a equipe se compromete a fazer diferente.
8. Agendar próximo check-in de termômetro para medir evolução (ART-12D).

> **Instrução obrigatória para TEA:** Fichas anônimas são obrigatórias — ninguém precisa verbalizar seu número. A escala é visual e literal (1 a 5 com descrição por escrito de cada nível). Opção de não falar durante a discussão — participante pode escrever sua barreira em post-it e o facilitador lê.

### Marco de Independência
Participante expressa seu nível de segurança psicológica honestamente e propõe ao menos uma barreira ou acordo de convivência (ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Termômetro de humor | Check-ins diários | Escala de humor/energia (1–5) em vez de segurança psicológica |
| Termômetro de energia | Sprints longos | Medir carga de trabalho percebida; identificar esgotamento precoce |
| Online (Mentimeter) | Times remotos | Votação anônima digital com histograma em tempo real |
| Multi-dimensão | Times maduros | 3 termômetros: segurança para errar / pedir ajuda / discordar |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| escala_termometro | 1–5 | 1–3 | 1–10 |
| duracao_dinamica | 40 min | 20 | 60 |
| anonimato | sim | não | sim |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-FEED-001 | Feedback em 4 Passos | Similar / Complementar | Feedback estruturado é instrumento que demonstra e fortalece segurança psicológica |
| DIN-RETRO-001 | Retrospectiva Guiada | Similar / Complementar | Retrospectivas constroem a base de confiança medida pelo termômetro |

**Progressão recomendada:**
`DIN-FEED-001 → DIN-PSAF-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Em validação interna |
| Nível de Qualidade | Médio — baseado em Edmondson (1999) e Tkalich et al. (2024) |
| Revisão | Equipe de RH e facilitadores internos |

### Critérios de Aceitação
- Todos os participantes marcam o termômetro (fichas anônimas recolhidas)
- Pelo menos 2 barreiras identificadas coletivamente
- Pelo menos 1 acordo de convivência definido e registrado

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Média do nível de segurança psicológica | Confiança (E2.x) | ART-12D — cálculo da média das fichas |
| KPI-2 | Variação do nível de segurança psicológica | Confiança (E2.x) | ART-12D — desvio padrão entre sessões |

### Referências
- Edmondson, A. (1999). *Psychological Safety and Learning Behavior in Work Teams*. Administrative Science Quarterly.
- Tkalich, A. et al. (2024). *The Role of Psychological Safety in Promoting Software Quality in Agile Teams*. Empirical Software Engineering.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
