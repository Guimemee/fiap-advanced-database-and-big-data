# Origem e Justificativa do Problema

**Disciplina:** Advanced Database & Big Data
**Ano Letivo:** 2024 | **Turma:** 3ECR
**Avaliação:** Checkpoint 4

### Enunciado do Problema
Implementar job distribuído em PySpark para computar a correlação de Pearson e matriz de covariância entre variáveis de processo de 100 GB de logs industriais.

### Formulação Formal
$$\text{DataFrame.groupBy}(\text{'lote'}).agg(\text{avg}('pressao'), \text{stddev}('temperatura')), \quad T_{Spark} \approx 0,1 \times T_{MapReduce}$$
