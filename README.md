# 🚀 Desafio Controle de Fluxo — DIO

Projeto desenvolvido como parte do módulo de **Controle de Fluxo** do bootcamp de Java da [Digital Innovation One (DIO)](https://www.dio.me), ministrado pelo instrutor **Gleyson Sampaio**.

---

## 📌 Sobre o Desafio

O objetivo é exercitar conceitos fundamentais da linguagem Java, tais como:
- Entrada e saída de dados via terminal (`Scanner`);
- Estruturas condicionais (`if`, `try-catch`);
- Estruturas de repetição (`for`);
- Criando e lançando **Exceções Customizadas** (`ParametrosInvalidosException`).

---

## ⚙️ Regras do Negócio

1. O sistema deve receber dois números inteiros via terminal.
2. Com base nesses valores, o programa calcula a quantidade de iterações (`parametroDois - parametroUm`) e imprime no console a contagem dos números.
   - *Exemplo:* Se o primeiro parâmetro for `12` e o segundo for `30`, teremos **18 ocorrências**, imprimindo:
     ```text
     Imprimindo o número 1
     Imprimindo o número 2
     ...
     Imprimindo o número 18
     ```
3. Se o **primeiro parâmetro for MAIOR que o segundo**, o sistema dispara uma exceção customizada chamada `ParametrosInvalidosException` com a mensagem:
   > *"O segundo parâmetro deve ser maior que o primeiro"*

---

## 📂 Estrutura do Projeto

```text
DesafioControleFluxo/
├── src/
│   ├── Contador.java                     # Classe principal (main e lógica de contagem)
└── README.md
