# IncomePerMouth

![image](https://github.com/user-attachments/assets/290eb2aa-e51f-4526-85c9-6e1ae045b66a)

# Worker Contract Income Calculator

A C# console application to manage departments, workers, and contracts, with functionality to calculate monthly income based on contracts. Built using object-oriented principles and **composition** (e.g., `Worker` composed of multiple `Contract` objects).

## UML

![image](https://github.com/user-attachments/assets/e64e921c-d9d4-4f56-b26d-c3872459bbd4)


## Features
- Create departments and workers with base salaries.
- Add multiple contracts to workers, each with a date, hourly value, and duration.
- Calculate total income for a specific month/year, including base salary and contract payments.

## Classes Overview
- **Department**: Represents a department (e.g., "TI").
- **Worker**: Stores worker details (name, level, base salary) and a list of `Contract` objects.
- **Contract**: Defines contract data (date, value per hour, duration).

## How It Works
1. **Input Data**:
   - Department name and worker details.
   - Contracts with dates and payment terms.
2. **Income Calculation**:
   - Sums the base salary with contracts active in the specified month/year.
   - Contracts are filtered by date to calculate total income.

## Installation & Usage
1. **Prerequisites**: .NET SDK installed.
2. **Clone the Repository**: https://github.com/LucasChagasLima/IncomePerMouth.git

# PT-BR

# Calculadora de Renda por Contratos de Trabalho

Aplicativo de console em C# para gerenciar departamentos, trabalhadores e contratos, com cálculo de renda mensal baseado em contratos. Desenvolvido com princípios de orientação a objetos e **composição** (ex: `Worker` contém múltiplos objetos `Contract`).

## Funcionalidades
- Criar departamentos e trabalhadores com salário base.
- Adicionar múltiplos contratos a um trabalhador (data, valor por hora, duração).
- Calcular renda total em um mês/ano específico (salário base + contratos).

## Principais Classes
- **Department**: Representa um departamento (ex: TI).
- **Worker**: Armazena dados do trabalhador (nome, nível, salário) e lista de `Contract`.
- **Contract**: Define contrato (data, valor por hora, horas trabalhadas).

## Funcionamento
1. **Entrada de Dados**:
   - Nome do departamento e dados do trabalhador.
   - Contratos (data, valor por hora, duração).
2. **Cálculo da Renda**:
   - Soma salário base + contratos do mês/ano selecionado.
   - Filtra contratos pela data especificada.

## Instalação e Execução
1. **Pré-requisitos**: .NET SDK instalado.
2. **Clonar o Repositório**: https://github.com/LucasChagasLima/IncomePerMouth.git
   
