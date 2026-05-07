# DIN-MAND-001 — Peço, Logo Recebo

> **Grupo:** Soft Skills | **Temática:** Autoadvocacia | **Momento:** Fim de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-MAND-001 |
| **Nome** | Peço, Logo Recebo (Ask and Receive) |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Soft Skills |
| **Subdomínio** | Autoadvocacia |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Autoadvocacia` `Comunicação Assertiva` `Autorrevelação Profissional` `Onboarding`

---

## 2. Contexto

Prática estruturada de comunicação assertiva em que os participantes exercitam formular pedidos claros — pedir ajuda, expressar necessidades, estabelecer limites — a partir de cartões de cenário do contexto de desenvolvimento de software. O facilitador oferece feedback sobre clareza e assertividade após cada prática.

**Objetivo de aprendizagem:** Capacitar profissionais em onboarding a expressar necessidades e limites de forma direta, eliminando passividade e dependência de inferência por parte dos colegas. Fundamentado nos construtos E3.x (Socialização) e E2.x (Confiança), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Role-Playing (§III-B2).

**Cenário de uso:** Treinamentos de comunicação para times com desafios de assertividade; onboarding de profissionais com alto perfil de ansiedade social; workshops de desenvolvimento pessoal.

**Problema endereçado:** Passividade e falta de proatividade em pedir ajuda ou expressar opiniões no onboarding. No contexto TEA: dificuldade em autoadvocacia é documentada como barreira significativa de integração profissional (de Marchena et al., 2025).

**Referências:** Skinner, B.F. (1957), *Verbal Behavior*; de Marchena, A. et al. (2025), *Communication in Autistic Adults*.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-05A | Cartões de Cenário | PDF | Entrada | DIN-MAND-001/cenarios_assertividade.pdf |
| ART-05B | Fichas de Recurso (scripts) | PDF | Entrada | DIN-MAND-001/fichas_recurso.pdf |
| ART-05C | Guia do Facilitador | Markdown | Entrada | DIN-MAND-001/guia_facilitador.md |
| ART-05D | Ficha KPI | XLSX | Saída | DIN-MAND-001/registro_kpi.xlsx |
| ART-05E | Params | YAML | Metadados | DIN-MAND-001/params.yaml |
| ART-05F | Relacionamentos | JSON | Metadados | DIN-MAND-001/relationships.json |
| ART-05G | Profile Info | JSON | Metadados | DIN-MAND-001/profile_info.json |

**Materiais físicos:** Cartões de cenário impressos; fichas de recurso com scripts de frase; quadro de registro; post-its.

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Nenhum pré-requisito obrigatório | — | — |

**Recomendado (não obrigatório):** DIN-SOFT-001 — consolida empatia cognitiva antes de escalar para autoexpressão assertiva individual.

**Dependências externas:**
- Skinner, B.F. (1957). *Verbal Behavior*. Appleton-Century-Crofts.
- de Marchena, A. et al. (2025). *Communication in Autistic Adults: An Action-Focused Review*. Current Psychiatry Reports.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala com espaço para movimentação; quadro branco
- **Participantes:** 4–12
- **Facilitador:** 1 (suporte ativo — oferece feedback sobre assertividade após cada prática)
- **Nível de experiência:** Nenhuma experiência prévia
- **Time-box total:** ~40 minutos

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Introdução | 5 min | Apresentar conceito de autoadvocacia; distribuir Fichas de Recurso |
| Apresentação de cenários | 5 min | Leitura e discussão dos Cartões de Cenário |
| Prática individual (rodada 1) | 10 min | Cada participante formula pedido para o cenário do cartão |
| Feedback coletivo | 5 min | Grupo e facilitador oferecem feedback sobre clareza e assertividade |
| Prática individual (rodada 2) | 10 min | Nova rodada com cenário diferente; incorporar feedback |
| Reflexão | 5 min | "Como posso aplicar isso no meu dia a dia no time?" |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Participante | Formula e pratica o pedido do cenário |
| Parceiro de prática | Recebe o pedido e dá feedback imediato |
| Facilitador | Oferece feedback sobre assertividade; registra na Ficha KPI |

### Passo a passo do facilitador

1. Distribuir Fichas de Recurso (ART-05B) — contêm modelos de frases assertivas.
2. Apresentar o conceito: "Autoadvocacia = dizer claramente o que você precisa, sem rodeios."
3. Ler um Cartão de Cenário em voz alta como exemplo. Demonstrar uma formulação passiva e uma assertiva.
4. Distribuir cartões individuais. Participantes praticam em duplas (rodada 1).
5. Registrar observações na Ficha KPI: frequência de pedidos, clareza (1–5).
6. Feedback coletivo: o que tornou o pedido claro? O que ainda estava ambíguo?
7. Rodada 2 com novo cartão, incorporando feedback recebido.
8. Reflexão final: situações reais do trabalho onde autoadvocacia seria útil.

> **Adaptação TEA obrigatória:** Disponibilizar Fichas de Recurso com scripts literais de frases antes da prática. Permitir ensaio escrito antes da fala oral. Não exigir contato visual durante a prática.

### Marco de Independência
Participante formula pedido claro e assertivo sem consultar Ficha de Recurso e sem auxílio do facilitador (de Marchena et al., 2025).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Cenários da empresa | Equipes específicas | Substituir cartões genéricos por cenários do dia a dia do time |
| Prática em trios | Times grandes | Adicionar papel de observador além do par |
| Inversão de papéis | Aprofundamento | Participante que recebeu o pedido pratica dar o pedido |
| Escrita antes da fala | TEA / ansiedade alta | Participante escreve o pedido antes de verbalizá-lo |
| Somente escrita | Ansiedade social severa | Toda a prática ocorre via troca de post-its |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| num_cenarios | 5 | 3 | 10 |
| duracao_pratica | 40 min | 20 | 60 |
| feedback_pares | sim | não | sim |
| uso_scripts | opcional | não | sim |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-FEED-001 | Feedback em 4 Passos | Similar / Complementar | Complementa habilidades de comunicação assertiva com estrutura de feedback estruturado |
| DIN-SOFT-001 | A Moeda de Duas Faces | Similar | Prática de argumentação e empatia — base para assertividade |

**Progressão recomendada:**
`DIN-COM-001 → DIN-SOFT-001 → DIN-MAND-001 → DIN-FEED-001 → DIN-PSAF-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Em validação interna |
| Nível de Qualidade | Médio — baseado em feedback de workshops e literatura TEA |
| Revisão | Equipe de RH e facilitadores internos |

### Critérios de Aceitação
- Participantes formulam pedidos com sujeito + verbo + necessidade específica (sem rodeios)
- Frequência de pedidos de ajuda no ambiente real aumenta após a dinâmica
- Participantes com TEA conseguem usar scripts como andaime para comunicação real

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Frequência de pedidos de ajuda/esclarecimento | Socialização (E3.x) | ART-05D — registro de observação |
| KPI-2 | Clareza e assertividade da comunicação (1–5) | Confiança (E2.x) | ART-05D — avaliação do facilitador |

### Referências
- Skinner, B.F. (1957). *Verbal Behavior*. Appleton-Century-Crofts.
- de Marchena, A. et al. (2025). *Communication in Autistic Adults*. Current Psychiatry Reports.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
