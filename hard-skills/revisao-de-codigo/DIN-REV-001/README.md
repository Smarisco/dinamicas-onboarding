# DIN-REV-001 — CRSG (Code Review Simulation Game)

> **Grupo:** Hard Skills | **Temática:** Revisão de Código | **Momento:** Meio de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-REV-001 |
| **Nome** | CRSG — Code Review Simulation Game |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Hard Skills |
| **Subdomínio** | Revisão de Código |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Revisão de Código` `Detecção de Defeitos` `Refatoração` `Feedback Técnico` `Onboarding`

---

## 2. Contexto

Simulação de code review em que participantes recebem trechos de código com defeitos intencionais (bugs, code smells, problemas de segurança) e devem identificá-los usando checklists estruturados, além de redigir comentários de revisão construtivos.

**Objetivo de aprendizagem:** Desenvolver capacidade de identificar defeitos sistematicamente e fornecer feedback técnico construtivo em code reviews. Fundamentado nos construtos E1.x (Aprendizado) e E2.x (Confiança), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Problem-Based Learning (§III-B3).

**Cenário de uso:** Workshops de code review; onboarding técnico de desenvolvedores; treinamentos de qualidade de software.

**Problema endereçado:** Code reviews ineficazes com feedback pouco construtivo; dificuldade em entender a importância do code review no processo de qualidade (E2.x — ICSE 2021).

**Referência:** Ardic, T. et al. (2025). *CRSG — Code Review Simulation Game*.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-08A | Códigos-fonte com defeitos | TXT | Entrada | DIN-REV-001/codigos_defeitos.txt |
| ART-08B | Checklists de revisão | Markdown | Entrada | DIN-REV-001/checklists_revisao.md |
| ART-08C | Guia do Facilitador | Markdown | Entrada | DIN-REV-001/guia_facilitador.md |
| ART-08D | Ficha KPI | XLSX | Saída | DIN-REV-001/registro_kpi.xlsx |
| ART-08E | Params | YAML | Metadados | DIN-REV-001/params.yaml |
| ART-08F | Relacionamentos | JSON | Metadados | DIN-REV-001/relationships.json |
| ART-08G | Profile Info | JSON | Metadados | DIN-REV-001/profile_info.json |

**Materiais digitais:** Computadores com editor de texto ou IDE; projetor para revisão coletiva.

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Conhecimento básico de programação | Conceitual | Pré-requisito de conhecimento, não de ativo |

**Dependências externas:**
- Ardic, T. et al. (2025). *CRSG — Code Review Simulation Game*.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala com computadores ou projetor para revisão coletiva
- **Participantes:** 2–6
- **Facilitador:** 1 (suporte ativo — oferece exemplos e feedback)
- **Nível de experiência:** Conhecimento básico de programação
- **Time-box total:** ~55 minutos

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Setup e Briefing | 10 min | Distribuir código e checklists; explicar objetivo e critérios |
| Revisão Individual / Dupla | 20 min | Identificar defeitos e escrever comentários |
| Revisão Coletiva | 15 min | Comparar achados; projetar código e discutir cada defeito |
| Prática de Comentário | 5 min | Reformular comentários para feedback construtivo |
| Debriefing | 5 min | "Como melhorar nossos code reviews reais?" |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Revisor | Analisa código e identifica defeitos com checklist |
| Autor (facilitador simula) | Recebe comentários e reage (simula processo real) |
| Facilitador | Projeta código, media discussão, registra KPIs |

### Passo a passo do facilitador

1. Distribuir código-fonte (impresso ou digital). Distribuir checklist de revisão (ART-08B).
2. Explicar objetivo: "Encontrar os defeitos E escrever comentários que ajudem o autor a melhorar."
3. Revisão individual/dupla (20 min): marcar defeitos e escrever comentário para cada um.
4. Parar. Projetar código no quadro/TV. Percorrer linha a linha coletivamente.
5. Para cada defeito: "Quem encontrou? Qual é o problema? Como comentaria?"
6. Comparar versões do comentário: qual é mais construtiva?
7. Registrar na Ficha KPI: defeitos encontrados por participante e qualidade do feedback.
8. Debriefing: padrões de defeito não encontrados → onde focar estudo.

> **Instrução obrigatória para TEA:** Checklists explícitos com categorias fixas (bug, code smell, segurança, performance) reduzem sobrecarga de categorização espontânea.

### Marco de Independência
Participante identifica defeitos e propõe melhorias sem auxílio do facilitador, com comentário construtivo (ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Múltiplas linguagens | Times políglotas | Código em Python, JS, Java, etc. |
| Foco em padrões de design | Sênior | Identificar violações de SOLID, DRY, KISS |
| Análise estática auxiliar | Intermediário | Usar SonarLint/ESLint junto ao checklist |
| Código de produção real | Times avançados | Usar PR real do próprio time (anonimizado) |
| Foco em segurança | Times DevSecOps | Defeitos OWASP Top 10 específicos |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| num_defeitos | 5 | 3 | 10 |
| duracao_revisao | 55 min | 30 | 90 |
| tipo_defeito | bug | refatoracao | seguranca |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-GIT-001 | Git em Conflito | Similar / Complementar | Conflitos Git surgem naturalmente de revisões de código — prática complementar |
| DIN-TDD-001 | TDD Kata | Similar | Foco comum em qualidade; TDD e code review são práticas complementares de qualidade |

**Progressão recomendada:**
`DIN-GIT-001 → DIN-REV-001 → DIN-TDD-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Em validação interna |
| Nível de Qualidade | Médio — baseado em Ardic et al. (2025) e feedback de workshops |
| Revisão | Equipe de Qualidade e facilitadores internos |

### Critérios de Aceitação
- Participantes encontram ≥ 3 dos 5 defeitos intencionais
- Pelo menos 1 comentário reformulado para versão mais construtiva
- Participantes conseguem classificar defeitos por categoria (bug/smell/segurança)

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Número de defeitos encontrados | Aprendizado (E1.x) | ART-08D — contagem |
| KPI-2 | Qualidade do feedback escrito (1–5) | Confiança (E2.x) | ART-08D — avaliação do facilitador via rubrica |

### Referências
- Ardic, T. et al. (2025). *CRSG — Code Review Simulation Game*.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
