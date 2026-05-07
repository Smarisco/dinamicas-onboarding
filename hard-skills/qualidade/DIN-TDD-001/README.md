# DIN-TDD-001 — TDD Kata

> **Grupo:** Hard Skills | **Temática:** Qualidade | **Momento:** Meio de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-TDD-001 |
| **Nome** | TDD Kata |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Hard Skills |
| **Subdomínio** | Qualidade |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Test-Driven Development` `Red-Green-Refactor` `Cobertura de Testes` `Disciplina de Processo` `Onboarding`

---

## 2. Contexto

Prática repetitiva (kata) em que o participante implementa um problema simples e bem definido seguindo estritamente o ciclo TDD: escrever um teste que falha (Red) → implementar o mínimo para passar (Green) → refatorar sem quebrar testes (Refactor). A repetição ritual cria memória muscular do processo.

**Objetivo de aprendizagem:** Internalizar a disciplina do ciclo Red-Green-Refactor e desenvolver hábito de escrever testes antes do código de produção. Fundamentado nos construtos E1.x (Aprendizado) e E2.x (Confiança), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Practice-Based Learning (§III-B3).

**Cenário de uso:** Workshops de TDD; onboarding técnico de desenvolvedores; treinamentos de qualidade de software.

**Problema endereçado:** Baixa cobertura de testes; dificuldade em refatorar código com segurança. No onboarding: falta de prática e disciplina em TDD (E1.x — ICSE 2021).

**Referências:** Osherove, R. (2009), *The Art of Unit Testing*; Ren, X. et al. (2023), *TDD, engagement in activity, and maintainability*.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-09A | Descrição do Kata | Markdown | Entrada | DIN-TDD-001/descricao_kata.md |
| ART-09B | Guia do Facilitador | Markdown | Entrada | DIN-TDD-001/guia_facilitador.md |
| ART-09C | Ficha KPI | XLSX | Saída | DIN-TDD-001/registro_kpi.xlsx |
| ART-09D | Params | YAML | Metadados | DIN-TDD-001/params.yaml |
| ART-09E | Relacionamentos | JSON | Metadados | DIN-TDD-001/relationships.json |
| ART-09F | Profile Info | JSON | Metadados | DIN-TDD-001/profile_info.json |

**Materiais digitais:** Computadores com IDE configurada; framework de testes instalado (JUnit, pytest, Jest, etc.); kata definida (ex.: FizzBuzz, String Calculator, Roman Numerals).

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Conhecimento básico de programação e testes unitários | Conceitual | Pré-requisito de conhecimento, não de ativo |

**Recomendado (não obrigatório):** DIN-REV-001 — consolida percepção de qualidade de código antes de internalizar TDD como disciplina.

**Dependências externas:**
- Osherove, R. (2009). *The Art of Unit Testing*. Manning Publications.
- Ren, X. et al. (2023). *TDD, engagement in activity, and maintainability*. IET Software.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala com computadores (1 por participante ou pair)
- **Participantes:** 1–4 (individual ou pair programming)
- **Facilitador:** 1 (suporte ativo — oferece dicas sobre o ciclo TDD)
- **Nível de experiência:** Conhecimento básico de programação e testes unitários
- **Time-box total:** ~60 minutos

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Setup e Briefing | 10 min | Configurar ambiente; explicar ciclo Red-Green-Refactor; apresentar kata |
| Demonstração ao vivo | 10 min | Facilitador demonstra 1 ciclo completo ao vivo |
| Prática guiada | 20 min | Participantes implementam primeiros ciclos com facilitador disponível |
| Prática autônoma | 15 min | Participantes continuam sem intervenção |
| Retrospectiva da kata | 5 min | "Como o TDD mudou sua abordagem ao problema?" |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Desenvolvedor | Implementa o kata seguindo estritamente Red → Green → Refactor |
| Facilitador | Demonstra, observa, oferece dicas sobre o ciclo |

### Passo a passo do facilitador

1. Configurar ambiente com IDE + framework de testes. Verificar que testes básicos rodam.
2. Apresentar kata escolhida: problema simples com requisitos incrementais claros.
3. Explicar ciclo com quadro visual: 🔴 Red → 🟢 Green → 🔵 Refactor.
4. **Demonstração ao vivo (10 min):** Facilitador implementa primeiro requisito ao vivo, comentando cada passo.
5. Participantes implementam próximos requisitos. Facilitador circula e observa.
6. Regra crítica: **nunca escrever código de produção sem teste falhando antes**.
7. Registrar na Ficha KPI: número de ciclos Red-Green-Refactor completados; cobertura final.
8. Retrospectiva: "Quando você quis pular o teste? O que te impediu?"

> **Instrução obrigatória para TEA:** Ciclo TDD como ritual explícito: antes de cada linha de produção, verificar se existe um teste falhando. Poster visual do ciclo disponível na tela durante toda a prática.

### Marco de Independência
Participante completa kata inteira seguindo ciclo TDD sem nenhuma linha de produção sem teste falhando antes (Osherove, 2009; ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| FizzBuzz Kata | Iniciantes absolutos | Problema mais simples; menos de 10 ciclos |
| String Calculator Kata | Intermediário | Requisitos incrementais; boa prática de TDD puro |
| Roman Numerals Kata | Avançado | Mais complexo; introduz refatoração significativa |
| Pair Programming (Ping-Pong TDD) | Times | Dev A escreve teste → Dev B implementa → alternando |
| Foco em refatoração | Sênior | Omitir fase Red; focar em Refactor com testes passando |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| num_katas | 1 | 1 | 3 |
| duracao_kata | 60 min | 30 | 90 |
| linguagem_prog | Python | Java | C# |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-REV-001 | CRSG | Similar / Precedente | Code review e TDD são práticas complementares de qualidade |
| DIN-GIT-001 | Git em Conflito | Similar | Código com testes TDD reduz conflitos de integração |

**Progressão recomendada:**
`DIN-GIT-001 → DIN-REV-001 → DIN-TDD-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Em validação interna |
| Nível de Qualidade | Médio — baseado em Osherove (2009) e Ren et al. (2023) |
| Revisão | Equipe de Qualidade e facilitadores internos |

### Critérios de Aceitação
- Participante não escreve nenhuma linha de produção sem teste falhando antes
- Pelo menos 3 ciclos Red-Green-Refactor completos por sessão
- Cobertura final ≥ 80% medida pelo framework

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Cobertura de testes alcançada (%) | Aprendizado (E1.x) | ART-09C — ferramenta de cobertura do framework |
| KPI-2 | Número de ciclos Red-Green-Refactor completos | Confiança (E2.x) | ART-09C — observação do facilitador |

### Referências
- Osherove, R. (2009). *The Art of Unit Testing*. Manning Publications.
- Ren, X. et al. (2023). *TDD, engagement in activity, and maintainability*. IET Software.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
