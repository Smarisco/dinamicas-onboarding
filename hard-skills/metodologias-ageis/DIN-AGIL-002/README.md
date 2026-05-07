# DIN-AGIL-002 — Construção com Blocos

> **Grupo:** Hard Skills | **Temática:** Metodologias Ágeis | **Momento:** Início de Sprint

---

## 1. Identificação

| Campo | Valor |
|-------|-------|
| **Asset ID** | DIN-AGIL-002 |
| **Nome** | Construção com Blocos (Block Building) |
| **Versão RAS** | 3.0 |
| **Autor** | Equipe RAS — ras-dinamicas@institucional.br |
| **Domínio** | Hard Skills |
| **Subdomínio** | Metodologias Ágeis |
| **Status** | Em validação interna |
| **Criação** | 2025-01-01 |
| **Última Atualização** | 2026-05-05 |
| **Licença** | CC-BY 4.0 |

**Tags:** `Scrum` `Arquitetura` `Integração` `LEGO` `Onboarding`

---

## 2. Contexto

Simulação de projeto modular com kits LEGO® em que três equipes constroem componentes separados que devem se integrar a uma estrutura-gabarito comum. A dinâmica expõe empiricamente como falhas de comunicação entre subequipes de software geram retrabalho e conflitos de integração.

**Objetivo de aprendizagem:** Vivenciar a diferença entre "construir corretamente o componente" e "construir o componente que se integra ao sistema". Fundamentado nos construtos E1.4 (Aprendizado — Big Picture) e E3.3 (Socialização — Comunicação entre Equipes), conforme Ju et al., ICSE 2021, Tabela III. Estratégia Simple-Complex (§III-B1, p.619).

**Cenário de uso:** Workshops de arquitetura modular; onboarding de times de desenvolvimento; treinamentos de integração de sistemas.

**Problema endereçado:** Falhas de integração por comunicação insuficiente entre subequipes. No onboarding: falta de compreensão da big picture do sistema (E1.4, p.618 — ICSE 2021).

**Referências:** Steghofer et al. (2017), JSS v.131, pp.230–247; Verwijs, C. (2012), LEGO4SCRUM.

---

## 3. Artefatos

| ID | Artefato | Tipo | Papel | Localização |
|----|----------|------|-------|-------------|
| ART-02A | Imagem Gabarito | PDF | Entrada | DIN-AGIL-002/gabarito_estrutura.pdf |
| ART-02B | Cartas de Restrição | PDF | Entrada | DIN-AGIL-002/cartas_restricao.pdf |
| ART-02C | Guia do Facilitador | PDF | Entrada | DIN-AGIL-002/guia_facilitador.pdf |
| ART-02D | Lista de Peças (Kit) | Markdown | Entrada | DIN-AGIL-002/lista_pecas.md |
| ART-02E | Customization Guide | Markdown | Entrada | DIN-AGIL-002/customization_guide.md |
| ART-02F | Ficha KPI | XLSX | Saída | DIN-AGIL-002/registro_kpi.xlsx |
| ART-02G | Diagrama de Fluxo Modular | PDF | Referência | DIN-AGIL-002/models/fluxo_modular.pdf |
| ART-02H | Params | YAML | Metadados | DIN-AGIL-002/params.yaml |
| ART-02I | Relacionamentos | JSON | Metadados | DIN-AGIL-002/relationships.json |
| ART-02J | Profile Info | JSON | Metadados | DIN-AGIL-002/profile_info.json |

**Materiais físicos:** 3 kits LEGO® separados; gabarito A3 impresso e lacrado; cartas de restrição; fita adesiva; cronômetro; quadro branco.

---

## 4. Dependências

| Asset ID | Nome | Tipo | Justificativa do Encadeamento |
|----------|------|------|-------------------------------|
| — | Nenhum pré-requisito obrigatório | — | — |

**Recomendado (não obrigatório):** DIN-AGIL-001 — Jogo das Bolinhas. Estabelece base de segurança psicológica e pensamento iterativo antes de introduzir complexidade de integração modular.

**Dependências externas:**
- Steghofer, J.-P. et al. (2017). *No silver brick*. JSS, v.131, pp.230–247.
- Verwijs, C. (2012). *LEGO4SCRUM*. https://www.lego4scrum.com.

---

## 5. Guia de Uso

### Pré-requisitos
- **Espaço físico:** Sala com mesas separadas por equipe; espaço central de integração (mín. 4 m²)
- **Participantes:** 9–12 (3 equipes de 3–4 pessoas)
- **Facilitador:** 1 (suporte ativo — media conflitos entre equipes)
- **Nível de experiência:** Nenhuma experiência prévia
- **Time-box total:** ~35 minutos

### Time-box por fase

| Fase | Duração | Descrição |
|------|---------|-----------|
| Setup | 5 min | Separar LEGO por equipe; distribuir cartas de restrição; gabarito lacrado no centro |
| Definição do Produto | 5 min | Arquiteto descreve verbalmente o sistema-alvo sem revelar o gabarito |
| Construção Paralela | 15 min | Cada equipe constrói seu módulo simultaneamente |
| Integração | 5 min | Equipes levam módulos ao espaço central e tentam encaixar |
| Validação | 5 min | Gabarito A3 revelado; comparar resultado vs. esperado |
| Debriefing | 10 min | "Onde ocorreu a falha de integração? Comunicação ou requisito?" |

### Papéis

| Papel | Quantidade | Responsabilidade |
|-------|------------|-----------------|
| Arquiteto | 1 | Descreve verbalmente o gabarito sem mostrá-lo |
| Equipe A / B / C | 3–4 cada | Constrói seu módulo com base nas instruções recebidas |
| Facilitador | 1 | Observa, media conflitos, não intervém na construção |

### Passo a passo do facilitador

1. Separar kits LEGO por equipe; colocar gabarito A3 lacrado no centro da sala.
2. Distribuir cartas de restrição — cada equipe recebe uma diferente.
3. Marcar espaço de integração com fita adesiva.
4. Arquiteto descreve o sistema (5 min): explica como os módulos devem se conectar.
5. Iniciar cronômetro: 15 min de construção paralela — equipes não podem ver as outras.
6. Sinal de "parar": cada equipe traz seu módulo ao espaço central.
7. Tentativa de integração; registrar na Ficha KPI (ART-02F).
8. Revelar gabarito A3; comparar resultado real vs. esperado.
9. Debriefing: explorar causas da falha de integração.

### Marco de Independência
Equipe integra módulos na primeira tentativa sem intervenção do facilitador (ICSE 2021 §III-A, p.617).

---

## 6. Customização

| Variante | Perfil-Alvo | Ajuste |
|----------|-------------|--------|
| Gabarito simples | Júnior / onboarding inicial | Menos peças; aumentar construção para 20 min |
| Gabarito complexo + restrições múltiplas | Pleno / sênior | Cartas de restrição conflitantes; simula dívida técnica |
| LEGO Duplo | TEA / necessidades motoras finas | Substituir LEGO standard por Duplo (blocos maiores) |
| Versão papel quadriculado | Sem orçamento LEGO | Papel quadriculado + régua; desenhos de componentes |
| Times distribuídos | Remote onboarding | Videoconferência; comunicação apenas por texto/chat |

**Parâmetros ajustáveis:**

| Parâmetro | Padrão | Mín | Máx | Descrição |
|-----------|--------|-----|-----|-----------|
| num_equipes | 3 | 2 | 6 | Equipes construtoras |
| tamanho_equipe | 3–4 | 2 | 5 | Pessoas por equipe |
| duracao_construcao | 15 min | 10 | 30 | Construção paralela |
| num_tentativas_integracao | 1 | 1 | 3 | Tentativas de integração |
| complexidade_gabarito | média | simples | complexa | Dificuldade do gabarito |

---

## 7. Relacionamentos

| Asset ID | Nome | Tipo | Justificativa |
|----------|------|------|---------------|
| DIN-AGIL-001 | Jogo das Bolinhas | Similar / Precedente | Estabelece base de auto-organização; recomendado antes de DIN-AGIL-002 |
| DIN-COM-001 | O Campo Minado | Similar / Complementar | Aprofunda comunicação bilateral sob restrição após vivência de integração modular |

**Progressão recomendada:**
`DIN-AGIL-001 → DIN-AGIL-002 → DIN-PLAN-001 → DIN-COM-001 → DIN-SOFT-001`

---

## 8. Qualidade

### Status

| Campo | Valor |
|-------|-------|
| Status de Validação | Em validação interna (pós-graduação e workshops corporativos) |
| Nível de Qualidade | Alto — baseado em Steghofer et al. (2017) e LEGO4SCRUM (Verwijs, 2012) |
| Revisão | Facilitadores CSM/PSM; v1.3.0 auditada 2026-04-28 |

### Critérios de Aceitação
- Time-box respeitado (±2 min por fase)
- Pelo menos 1 falha de integração identificada e discutida no debriefing
- Todos os participantes conseguem nomear a causa da falha após o debriefing

### KPIs de Eficácia

| KPI | Métrica | Construto | Instrumento |
|-----|---------|-----------|-------------|
| KPI-1 | Similaridade com gabarito (%) | Aprendizado (E1.4) | ART-02F — inspeção visual |
| KPI-2 | Tempo de integração (s) | Confiança (E2.1) | ART-02F — cronômetro |
| KPI-3 | Tentativas de reencaixe | Confiança | ART-02F — contagem |
| KPI-4 | Consultas entre equipes | Socialização (E3.3) | ART-02F — observador |

### Referências
- Steghofer, J.-P. et al. (2017). *No silver brick*. JSS, v.131, pp.230–247.
- Verwijs, C. (2012). *LEGO4SCRUM*.
- Ju, A. et al. (2021). *A Case Study of Onboarding in Software Teams*. ICSE 2021.
- Hause, M. et al. (2025). *RAS 3.0*. INCOSE INSIGHT, Vol.28/5.
- Object Management Group. *Reusable Asset Specification v2.2*. OMG, 2005.
