# DIN-FEED-001 — Feedback em 4 Passos

> **Grupo:** Soft Skills | **Temática:** Feedback | **Momento:** Fim de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-FEED-001 |
| **Nome** | Feedback em 4 Passos (Four-Step Feedback) |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Soft Skills |
| **Subdomínio** | Feedback |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Feedback Estruturado` `Comunicação Não-Violenta` `Escuta Empática` `Modelo Pendleton` `Onboarding`

---

## 2. Contexto

Dinâmica para praticar feedback estruturado e comunicação não-violenta seguindo o Modelo Pendleton (4 passos): O que foi bem? → O que poderia ser melhor? → O que você faria diferente? → Como posso apoiar? A estrutura sequencial garante que o feedback seja construtivo, seguro e orientado à ação.

**Objetivo de aprendizagem:** Desenvolver habilidade de dar e receber feedback de forma construtiva, empática e eficaz. Fundamentado nos construtos E3.x (Socialização) e E2.x (Confiança), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Practice-Based Learning (§III-B3).

**Cenário de uso:** Workshops de comunicação profissional; treinamentos de liderança; onboarding de times com desafios de comunicação e feedback.

**Problema endereçado:** Feedback ineficaz, agressivo ou passivo; dificuldade em se adaptar à cultura de feedback durante o onboarding (E3.x — ICSE 2021).

**Referências:** Pendleton, D. et al. (1984), *The Consultation: An Approach to Learning and Teaching*; Huang, V.W. et al. (2024), *Improving SE Teamwork with Structured Feedback*.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-11A | Cartões com Modelo Pendleton | PDF | Entrada | DIN-FEED-001/modelo_pendleton.pdf |
| ART-11B | Cenários de Feedback | Markdown | Entrada | DIN-FEED-001/cenarios_feedback.md |
| ART-11C | Guia do Facilitador | Markdown | Entrada | DIN-FEED-001/guia_facilitador.md |
| ART-11D | Ficha KPI | XLSX | Saída | DIN-FEED-001/registro_kpi.xlsx |
| ART-11E | Params | YAML | Metadados | DIN-FEED-001/params.yaml |
| ART-11F | Relacionamentos | JSON | Metadados | DIN-FEED-001/relationships.json |
| ART-11G | Profile Info | JSON | Metadados | DIN-FEED-001/profile_info.json |

**Materiais físicos:** Sala com espaço para duplas/trios; cartões impressos com Modelo Pendleton; cenários de feedback impressos; quadro branco.

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Nenhuma experiência prévia necessária | Conceitual | Pré-requisito de conhecimento, não de ativo |

**Recomendado (não obrigatório):** DIN-MAND-001 — consolida comunicação assertiva antes de praticar feedback estruturado; DIN-RETRO-001 — as ações da retrospectiva podem ser comunicadas via Modelo Pendleton.

**Dependências externas:**
- Pendleton, D. et al. (1984). *The Consultation: An Approach to Learning and Teaching*. Oxford University Press.
- Huang, V.W. et al. (2024). *Improving SE Teamwork with Structured Feedback*. SIGCSE.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala com espaço para duplas/trios
- **Participantes:** 4–12 (em duplas ou trios)
- **Facilitador:** 1 (treinado em feedback estruturado e escuta ativa)
- **Nível de experiência:** Nenhuma experiência prévia necessária
- **Time-box total:** ~45 minutos

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Briefing e distribuição | 10 min | Explicar Modelo Pendleton; distribuir cartões e cenários |
| Prática em duplas/trios | 20 min | Participantes praticam dar e receber feedback nos cenários |
| Inversão de papéis | 10 min | Quem deu feedback agora recebe; quem recebeu agora dá |
| Reflexão coletiva | 5 min | "Como o feedback estruturado pode melhorar nossas relações?" |

### O Modelo Pendleton — 4 Passos

| Passo | Pergunta | Quem responde primeiro |
|-------|----------|----------------------|
| 1 | O que foi bem? | Quem recebeu o feedback |
| 2 | O que poderia ter sido melhor? | Quem recebeu o feedback |
| 3 | O que você faria diferente? | Quem deu o feedback (complementa) |
| 4 | Como posso apoiar? | Quem deu o feedback |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Facilitador | Apresenta o modelo; distribui cenários; observa as duplas; conduz reflexão coletiva |
| Quem dá feedback | Segue o roteiro Pendleton; escuta sem interromper nas perguntas 1 e 2 |
| Quem recebe feedback | Responde primeiro às perguntas 1 e 2 antes de ouvir a perspectiva do parceiro |

### Passo a passo do facilitador

1. Distribuir cartões com o Modelo Pendleton — 1 por participante.
2. Explicar os 4 passos com exemplo concreto no quadro.
3. Distribuir cenários de feedback — 1 por dupla/trio.
4. Duplas praticam por 20 min: quem dá feedback guia pelas 4 perguntas em ordem.
5. **Regra crítica:** Passo 1 e 2 são respondidos por quem recebeu — quem dá ouve e anota.
6. Inversão de papéis (10 min): mesmo cenário ou cenário alternativo.
7. Reflexão coletiva: "Qual passo foi mais difícil? Por quê?"
8. Registrar aprendizados e dificuldades na Ficha KPI (ART-11D).

> **Instrução obrigatória para TEA:** Cartões com 4 passos numerados permanecem visíveis durante toda a prática — participante não precisa memorizar o roteiro. Cenários escritos com linguagem direta e sem ambiguidade. Opção de escrever respostas antes de falar.

### Marco de Independência
Participante conduz feedback estruturado completo (4 passos, ordem correta, sem pular etapas) sem auxílio do facilitador (ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Cenários da empresa | Equipes reais | Substituir cenários genéricos por situações reais do contexto da empresa |
| Foco em feedback positivo | Times novos | Praticar apenas passo 1 nas primeiras sessões; introduzir passos 2-4 gradualmente |
| Inversão de papéis | Líderes | Gestores praticam receber feedback de seus liderados |
| Online (Miro/Mentimeter) | Times remotos | Cenários em cards digitais; feedback digitado antes de verbalizado |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| num_cenarios | 3 | 1 | 5 |
| duracao_pratica | 45 min | 20 | 60 |
| feedback_pares | sim | não | sim |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-MAND-001 | Peço, Logo Recebo | Similar / Precedente | Autoadvocacia e comunicação assertiva são base para dar e receber feedback construtivo |
| DIN-RETRO-001 | Retrospectiva Guiada | Similar / Complementar | Feedback estruturado é ferramenta natural para comunicar ações da retrospectiva |

**Progressão recomendada:**
`DIN-RETRO-001 → DIN-FEED-001 → DIN-PSAF-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Em validação interna |
| Nível de Qualidade | Médio — baseado em Pendleton et al. (1984) e Huang et al. (2024) |
| Revisão | Equipe de RH e facilitadores internos |

### Critérios de Aceitação
- Cada participante pratica dar feedback completo (4 passos, sem pular)
- Inversão de papéis realizada em todas as duplas
- Reflexão coletiva conduzida ao final com pelo menos 1 aprendizado por pessoa

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Qualidade do feedback dado (1–5) | Aprendizado (E1.x) | ART-11D — avaliação do facilitador |
| KPI-2 | Capacidade de receber feedback (1–5) | Confiança (E2.x) | ART-11D — autoavaliação |

### Referências
- Pendleton, D. et al. (1984). *The Consultation: An Approach to Learning and Teaching*. Oxford University Press.
- Huang, V.W. et al. (2024). *Improving SE Teamwork with Structured Feedback*. SIGCSE.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
