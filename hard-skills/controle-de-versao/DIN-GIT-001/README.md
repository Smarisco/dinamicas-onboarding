# DIN-GIT-001 — Git em Conflito

> **Grupo:** Hard Skills | **Temática:** Controle de Versão | **Momento:** Meio de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-GIT-001 |
| **Nome** | Git em Conflito (Git in Conflict) |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Hard Skills |
| **Subdomínio** | Controle de Versão |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Git` `branches` `merge` `rebase` `Resolução de Conflitos` `Code Review` `Onboarding`

---

## 2. Contexto

Prática orientada em que duplas ou trios resolvem conflitos de merge pré-fabricados em um repositório Git de treinamento. Cada conflito simula uma situação real de colaboração: dois devs editaram o mesmo arquivo em branches divergentes. O participante deve decidir merge vs. rebase, resolver o conflito e garantir que os testes passem.

**Objetivo de aprendizagem:** Desenvolver confiança e fluência na resolução de conflitos Git, eliminando o medo de "quebrar o repositório". Fundamentado nos construtos E1.x (Aprendizado) e E2.x (Confiança), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Problem-Based Learning (§III-B3).

**Cenário de uso:** Workshops de Git para devs novos; onboarding técnico de desenvolvedores; treinamentos de boas práticas de colaboração em repositório.

**Problema endereçado:** Conflitos frequentes em merges; medo de "quebrar o código" no onboarding; comunicação técnica insuficiente sobre alterações no código (E2.x — ICSE 2021).

**Referência:** Chang, K. & Dow, K. (2024). *Git conflict resolution study*.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-07A | Repositório Git de Treinamento | Git | Entrada | DIN-GIT-001/repositorio_conflito.git |
| ART-07B | Guia do Facilitador | Markdown | Entrada | DIN-GIT-001/guia_facilitador.md |
| ART-07C | Ficha KPI | XLSX | Saída | DIN-GIT-001/registro_kpi.xlsx |
| ART-07D | Params | YAML | Metadados | DIN-GIT-001/params.yaml |
| ART-07E | Relacionamentos | JSON | Metadados | DIN-GIT-001/relationships.json |
| ART-07F | Profile Info | JSON | Metadados | DIN-GIT-001/profile_info.json |

**Materiais digitais:** Computadores com Git instalado; acesso a repositório compartilhado (GitHub/GitLab/Bitbucket); IDE com suporte a visualização de conflitos.

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Conhecimento básico de Git (add, commit, push, pull) | Conceitual | Pré-requisito de conhecimento, não de ativo |

**Dependências externas:**
- Chang, K. & Dow, K. (2024). *Git conflict resolution study*.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala com computadores (1 por participante ou por dupla)
- **Participantes:** 2–6 (duplas ou trios)
- **Facilitador:** 1 (suporte ativo — oferece dicas e orientação)
- **Nível de experiência:** Conhecimento básico de Git
- **Time-box total:** ~60 minutos

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Setup | 10 min | Clonar repositório; configurar ambiente; apresentar o cenário |
| Prática — Conflito 1 | 15 min | Resolver primeiro conflito (merge simples) |
| Revisão coletiva | 5 min | Discutir estratégia usada |
| Prática — Conflito 2 | 15 min | Resolver segundo conflito (merge com lógica conflitante) |
| Prática — Conflito 3 | 10 min | Rebase interativo ou cherry-pick (avançado) |
| Debriefing | 5 min | "Como evitar conflitos no futuro? Qual a melhor prática?" |

### Papéis

| Papel | Responsabilidade |
|-------|-----------------|
| Dev A / Dev B (par) | Resolvem conflito colaborativamente |
| Facilitador | Observa, oferece dicas, registra tempo e acertos na Ficha KPI |

### Passo a passo do facilitador

1. Clonar repositório de treinamento com conflitos pré-existentes.
2. Apresentar o cenário narrativo: "Dev A fez feature/login, Dev B fez feature/auth — ambos editaram `auth.js`."
3. Duplas executam `git merge` e observam o conflito.
4. Resolver usando editor de texto ou IDE (VS Code: 3-way merge view).
5. Garantir que `git status` está limpo e testes passam antes de commitar.
6. Facilitador registra tempo e erros na Ficha KPI.
7. Revisão coletiva: qual estratégia cada dupla usou?
8. Conflito 2 (mais complexo); conflito 3 opcional (rebase).
9. Debriefing: "O que a mensagem de conflito estava dizendo? Como comunicar melhor ao fazer o PR?"

> **Instrução obrigatória para TEA:** Fornecer checklist de passos impressa ou digital: 1. Identificar arquivos em conflito. 2. Abrir em editor. 3. Escolher/combinar versões. 4. Remover marcadores `<<<<<<<`, `=======`, `>>>>>>>`. 5. Commitar.

### Marco de Independência
Participante resolve conflito de merge sem auxílio do facilitador, commit limpo com testes passando (ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Conflito em arquivo binário | Perfil avançado | Adicionar imagem ou PDF em conflito |
| Conflito em múltiplas linguagens | Times políglotas | Repositório com Python, JS, Java em conflito |
| Rebase interativo (avança) | Sênior | Focar em `git rebase -i` para squash e reordenação |
| Visualizador gráfico | Iniciantes absolutos | Usar GitKraken ou VS Code Source Control View |
| Ambiente offline | Sem acesso à internet | Usar repositório local bare |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx |
|-----------|--------|-----|-----|
| num_conflitos | 3 | 1 | 5 |
| duracao_resolucao | 60 min | 30 | 90 |
| tipo_conflito | merge | rebase | cherry-pick |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-REV-001 | CRSG | Similar / Complementar | Code review é o contexto natural que gera conflitos — DIN-REV-001 complementa com práticas de revisão |
| DIN-TDD-001 | TDD Kata | Similar | Foco comum em qualidade de código; TDD reduz conflitos por estabelecer contrato de testes |

**Progressão recomendada:**
`DIN-AGIL-001 → DIN-PLAN-001 → DIN-GIT-001 → DIN-REV-001 → DIN-TDD-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Em validação interna |
| Nível de Qualidade | Médio — baseado em Chang & Dow (2024) e feedback de workshops |
| Revisão | Equipe de Desenvolvimento e facilitadores internos |

### Critérios de Aceitação
- Todos os participantes completam pelo menos 1 conflito com commit limpo
- Participantes conseguem descrever a diferença entre merge e rebase
- Tempo de resolução diminui entre conflito 1 e conflito 2

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Tempo médio para resolução de conflitos (min) | Aprendizado (E1.x) | ART-07C — cronômetro |
| KPI-2 | Número de conflitos resolvidos corretamente | Confiança (E2.x) | ART-07C — verificação de commit limpo |

### Referências
- Chang, K. & Dow, K. (2024). *Git conflict resolution study*.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
