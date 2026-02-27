# ===== 01_python/PADROES.md =====
# (Nomenclatura + template mínimo de projeto)

# Padrões de projetos (01_python)

Este documento define padrões para manter consistência na trilha de Python, especialmente para entregáveis nas fases 10–50.

## Nomenclatura (obrigatória em 10–50)

Projetos nas fases 10–50 devem seguir:

`pYYYY_NNN__tag1-tag2__nome-curto/`

Exemplos:
```text
10_fundamentos/02_algoritmos/p2026_003__algo__sorting-lab/
20_quantum/01_qiskit-fundamentos/p2026_010__qiskit__bell-states/
30_pqc_security/02_benchmarks/p2026_021__pqc-bench__mlkem-vs-x25519/
40_quantum_networks/01_qkd/p2026_030__qkd__bb84-sim/
50_research/01_reproducible-experiments/p2026_040__paperlike__experiment-01/
```

Regras:
- tudo em `kebab-case` (sem espaços e sem acento)
- `YYYY` = ano
- `NNN` = contador sequencial do portfólio
- `tag1-tag2` = categoria/subcategoria (ex.: `qiskit`, `bench`, `qkd`, `paperlike`)

## Template mínimo de projeto (10–50)

Todo projeto `pYYYY...` deve conter:

```text
pYYYY_NNN__.../
├── README.md
├── pyproject.toml
├── src/
├── tests/
├── scripts/
└── reports/
    ├── results.md
    └── figures/
```

## Checklist do README do projeto

O `README.md` do projeto deve conter:

```text
# Objetivo
# Como rodar (setup + comando)
# Input/Output esperado
# Resultados (ou link para reports/results.md)
# Próximos passos
```
