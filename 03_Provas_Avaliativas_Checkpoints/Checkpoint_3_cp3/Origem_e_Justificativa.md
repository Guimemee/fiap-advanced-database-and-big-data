# Origem e Justificativa do Problema

**Disciplina:** Advanced Database & Big Data
**Ano Letivo:** 2024 | **Turma:** 3ECR
**Avaliação:** Checkpoint 3

### Enunciado do Problema
Dimensionar as tabelas CQL com chaves de partição e clustering keys balanceadas para assegurar escalabilidade linear e latência sub-milisegundo sob modelo AP (Disponibilidade e Tolerância à Partição).

### Formulação Formal
$$\text{PRIMARY KEY } ((id\_planta, ano\_mes), data\_hora, id\_sensor), \quad \text{Quorum} = \left\lfloor \frac{N}{2} \right\rfloor + 1$$
