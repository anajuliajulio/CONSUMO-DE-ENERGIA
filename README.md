# CALCULADORA - CONSUMO ELÉTRICO

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)
![Energia](https://img.shields.io/badge/Energia-Consumo%20El%C3%A9trico-yellow)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)

## SOBRE O PROJETO

A **Calculadora de Consumo Elétrico** é um programa desenvolvido em Python com o objetivo de estimar o consumo mensal de energia elétrica de um aparelho.

O sistema solicita informações simples ao usuário, como o nome do aparelho, sua potência em watts e o tempo médio de utilização diária. A partir desses dados, calcula o consumo estimado em **kWh por mês**.

O programa também apresenta uma estimativa de custo mensal utilizando o valor fixo de **R$ 0,75 por kWh**.

## OBJETIVO

Desenvolver um algoritmo simples utilizando programação estruturada para:

* Receber dados informados pelo usuário;
* Realizar cálculos matemáticos;
* Calcular o consumo mensal de energia;
* Estimar o custo mensal;
* Apresentar os resultados de forma organizada.

## TECNOLOGIAS UTILIZADAS

* Python
* Visual Studio Code


## FORMULA UTILIZADA

O consumo mensal é calculado utilizando a seguinte fórmula:

```text
consumoMensal = (potencia × horasDia × 30) / 1000
```

Onde:

* **potencia** = potência do aparelho em watts (W);
* **horasDia** = quantidade média de horas de utilização por dia;
* **30** = quantidade aproximada de dias no mês;
* **1000** = conversão de watts para quilowatts.

### 💰 Cálculo do custo

O custo estimado é calculado utilizando:

```text
custoMensal = consumoMensal × 0,75
```

Neste projeto, foi considerado o valor fixo de **R$ 0,75 por kWh**.

> O valor utilizado é apenas uma estimativa e pode variar de acordo com a tarifa de energia elétrica.
