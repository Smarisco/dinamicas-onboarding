# Repositório de Dinâmicas de Onboarding

> Repositório de dinâmicas estruturadas como ativos reutilizáveis para o ensino e integração de engenheiros de software com Transtorno do Espectro Autista (TEA).

---

## Sobre este repositório

Este repositório organiza dinâmicas de onboarding modeladas segundo o padrão **Reusable Asset Specification (RAS)** da OMG. Cada dinâmica é um ativo versionado, descrito por metadados estruturados que permitem ao gestor **descobrir, selecionar e aplicar** a prática adequada ao perfil do profissional e ao momento da sprint — sem depender de memória institucional.

A abordagem transforma práticas de integração isoladas em ativos **descobríveis, versionados e reproduzíveis** por qualquer equipe, com ou sem experiência prévia em neurodiversidade.

---

## Estrutura do repositório

```
dinamicas-onboarding/
│
├── hard-skills/
│   ├── metodologias-ageis/
│   │   ├── DIN-AGIL-001/               → Jogo das Bolinhas
│   │   │   ├── README.md
│   │   │   ├── params.yaml
│   │   │   ├── profile_info.json
│   │   │   └── relationships.json
│   │   └── DIN-AGIL-002/               → Construção com Blocos
│   ├── controle-de-versao/
│   │   └── DIN-GIT-001/                → Git em Conflito
│   ├── revisao-de-codigo/
│   │   └── DIN-REV-001/                → CRSG — Revisão de Código
│   ├── estimativa-agil/
│   │   └── DIN-PLAN-001/               → Planning Poker
│   └── qualidade/
│       └── DIN-TDD-001/                → TDD Kata
│
├── soft-skills/
│   ├── comunicacao/
│   │   └── DIN-COM-001/                → O Campo Minado
│   ├── colaboracao-em-pares/
│   │   └── DIN-SOFT-001/               → A Moeda de Duas Faces
│   ├── autoadvocacia/
│   │   └── DIN-MAND-001/               → Peço, Logo Recebo
│   ├── cerimonias-ageis/
│   │   └── DIN-RETRO-001/              → Retrospectiva Guiada
│   ├── feedback/
│   │   └── DIN-FEED-001/               → Feedback em 4 Passos
│   └── seguranca-psicologica/
│       └── DIN-PSAF-001/               → Termômetro Psicológico
│
├── SUMMARY.md
├── README.md
└── .gitignore
```

---

## Classificação tridimensional

Cada dinâmica é classificada segundo três eixos ortogonais que permitem filtragem precisa:

| Eixo | O que classifica | Exemplo |
|------|-----------------|---------|
| **Habilidades** | Hard e soft skills desenvolvidas | Comunicação assertiva, controle de versão |
| **Perfil Sensorial** | Dimensões de neurodiversidade endereçadas | Sensibilidade auditiva, previsibilidade |


---

## Estrutura de cada ativo RAS

Cada diretório em `assets/` contém:

```
DIN-AGIL-001/
├── params.yaml           ← Metadados RAS: Classification + Usage
├── profile_info.json     ← Extensão semântica: variability-points TEA
├── relationships.json    ← Related Assets: pré-requisitos e complementares
├── guia-facilitador.pdf  ← Artefato Solution: roteiro de execução
├── checklist.md          ← Artefato Solution: materiais necessários
└── customization-guide.md ← Artefato Solution: guia de adaptações
```

---

## Como usar este repositório

### Para gestores e mentores

Acesse a documentação navegável no **GitBook** (link abaixo) e filtre as dinâmicas por:
- Momento da sprint (início, meio ou fim)
- Habilidade que deseja desenvolver
- Perfil sensorial do profissional

### Para contribuidores

Siga o fluxo de branches:

```
feat/<grupo>/<nome-da-dinamica>  →  develop  →  main
```

Antes de abrir um Pull Request, certifique-se de que:
- [ ] O arquivo segue o template padrão de dinâmica
- [ ] O `params.yaml` está preenchido com todos os campos RAS
- [ ] O `SUMMARY.md` foi atualizado com a nova dinâmica
- [ ] O README da temática foi atualizado

---

## Ativos instanciados

| ID | Nome | Grupo | Momento | Hard Skills | Soft Skills |
|----|------|-------|---------|-------------|-------------|
| DIN-AGIL-001 | Jogo das Bolinhas | Hard | Início | Estimativa (Velocity), Pensamento Sistêmico | Auto-organização, Segurança Psicológica |
| DIN-AGIL-002 | Construção com Blocos | Hard | Início | Arquitetura Modular | Comunicação entre equipes |
| DIN-COM-001 | O Campo Minado | Soft | Meio | — | Comunicação precisa, Confiança em pares |
| DIN-SOFT-001 | A Moeda de Duas Faces | Soft | Fim | — | Empatia técnica Dev/QA |

---

## Branches

| Branch | Finalidade |
|--------|-----------|
| `main` | Conteúdo revisado e publicado — sincronizado com o GitBook |
| `develop` | Branch de integração antes da publicação |
| `feat/<grupo>/<nome>` | Branch de trabalho para nova dinâmica |
| `fix/<grupo>/<nome>` | Branch de correção de conteúdo existente |
| `update/<grupo>/<nome>` | Branch de atualização de dinâmica existente |

---

## Convenção de commits

```
feat(soft-skills/comunicacao): adiciona dinâmica de escuta ativa
fix(hard-skills/controle-de-versao): corrige passo 3 da dinâmica git-na-pratica
update(assets/DIN-AGIL-001): revisa variability-points auditivos
docs(root): atualiza SUMMARY.md com nova dinâmica
```

---

## Documentação

A versão navegável deste repositório está publicada no GitBook:  
🔗 *(link será adicionado após integração)*

---

## Referência

Este repositório é o artefato de suporte ao artigo:

> **Repositório de Dinâmicas Estruturadas como Ativo Reutilizável para o Ensino e Integração de Engenheiros de Software com TEA**  
> Submetido ao SBES 2025.

O protocolo RAS utilizado segue a especificação:  
> Object Management Group. *Reusable Asset Specification, Version 2.2*. OMG, 2005.

---

## Disponibilidade

Os artefatos completos (manifestos YAML, guias de customização e `profile_info.json`) estão disponíveis neste repositório.  
Os dados serão tornados públicos com identificação completa após a aceitação do artigo.
