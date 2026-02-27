# Organização da pasta 01_python

A `01_python/` é organizada em duas camadas:
- Camada A (agora): revisão do Python do zero (fundamentos + prática deliberada)
- Camada B (depois e em paralelo): projetos por fases (10–50), com entregáveis reproduzíveis

Regra de ouro:
- `01_basics/` e `02_practice/` = aprendizado e treino (leve)
- `10_` a `50_` = entregáveis (projetos), com execução reproduzível

## Visão geral

```text
01_python/
├── 00_setup/
├── 01_basics/
├── 02_practice/
├── 10_fundamentos/
├── 20_quantum/
├── 30_pqc_security/
├── 40_quantum_networks/
├── 50_research/
├── 90_shared/
└── 99_archive/
```

## Onde colocar cada coisa

### 00_setup/
Documentação de ambiente e padrão de execução.
- `env.md`: criação de venv, instalação, como rodar
- `tooling.md`: ruff/pytest e padrões (quando aplicável)

### 01_basics/ (Camada A)
Revisão do Python do zero, por tópicos.

Subpastas sugeridas:
```text
01_basics/
├── 01_sintaxe/
├── 02_tipos-colecoes/
├── 03_controle-fluxo/
├── 04_funcoes/
├── 05_modulos-pacotes/
├── 06_arquivos/
├── 07_excecoes/
└── 08_poo/
```

Conteúdo típico:
- `notes.md` (regras + exemplos mínimos)
- `examples.py` (scripts curtos)

### 02_practice/ (Camada A)
Exercícios numerados e repetíveis.

Exemplos:
```text
02_practice/
├── ex0001__input-output/
├── ex0002__loops/
├── ex0003__lists-dicts/
├── ex0004__functions/
├── ex0005__files/
└── ex0006__poo/
```

Conteúdo típico por exercício:
- `README.md` (enunciados + checklist)
- `solution.py`, `solution_v2.py` (se houver evolução)
- `tests/` (quando já estiver confortável com pytest)

## Trilhas por fase (Camada B)

As fases `10_` a `50_` guardam entregáveis: mini-projetos, benchmarks, simuladores, relatórios e artefatos reprodutíveis.

### 10_fundamentos/
Base aplicada: estruturas de dados, algoritmos, matemática computacional, cripto básica.
Subpastas sugeridas:
- `01_ds-estruturas/`
- `02_algoritmos/`
- `03_matematica-computacional/`
- `04_cripto-basica/`

### 20_quantum/
Qiskit/Cirq, algoritmos e simuladores.
Subpastas sugeridas:
- `01_qiskit-fundamentos/`
- `02_cirq-fundamentos/`
- `03_algoritmos/`
- `04_simuladores/`

### 30_pqc_security/
PQC e segurança: conceitos, benchmarking, engenharia e relatórios.
Subpastas sugeridas:
- `01_conceitos/`
- `02_benchmarks/`
- `03_engenharia/`
- `04_relatorios/`

### 40_quantum_networks/
QKD, correção de erros, simulações e métricas.
Subpastas sugeridas:
- `01_qkd/`
- `02_qec-correction/`
- `03_simulacoes/`
- `04_metricas/`

### 50_research/
“Quase paper”: experimentos reproduzíveis + escrita.
Subpastas sugeridas:
- `01_reproducible-experiments/`
- `02_writing/`
- `03_artifacts/`

### 90_shared/
Reuso e dados pequenos/versionáveis.
- `libs/`
- `datasets/`

Regra prática: só mover algo para `90_shared/` quando estiver repetindo (ex.: copiou 3 vezes).

### 99_archive/
Rascunhos, tentativas antigas e experimentos descartados.
