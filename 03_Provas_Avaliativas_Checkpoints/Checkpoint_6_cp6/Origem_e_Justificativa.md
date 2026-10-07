# Origem e Justificativa do Problema

**Disciplina:** Advanced Database & Big Data
**Ano Letivo:** 2024 | **Turma:** 3ECR
**Avaliação:** Checkpoint 6

### Enunciado do Problema
Implementar pipeline completo Medallion Architecture para transformar dados brutos não estruturados (Bronze), aplicar saneamento e tipagem (Silver) e agregar métricas de KPIs (Gold).

### Formulação Formal
$$\text{Bronze (Raw JSON)} \xrightarrow{\text{Data Cleaning}} \text{Silver (Clean Parquet)} \xrightarrow{\text{Business Agg}} \text{Gold (Curated KPIs)}$$
