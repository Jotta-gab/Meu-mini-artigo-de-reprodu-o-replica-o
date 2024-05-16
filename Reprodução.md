Reproduzindo o trabalho apresentado no artigo "Agile Software Quality Metrics" de Michelle Maddox e Sheila Walker, primeiro para entender os conceitos e métricas propostas no artigo. Vamos simplificar o processo e criar um sistema simples em C para demonstrar a aplicação das métricas de qualidade de software propostas no artigo.

Vamos começar com a implementação das métricas propostas: test efficiency, defect removal efficiency, production escape percentage e change failure rate.

//Codigo:

#include <stdio.h>

// Função para calcular a eficiência do teste

float calculateTestEfficiency(int totalTests, int passedTests, int failedTests) {

`    `if (totalTests == 0) return 0.0;

`    `return (float) passedTests / totalTests \* 100;

}

// Função para calcular a eficiência de remoção de defeitos

float calculateDefectRemovalEfficiency(int totalDefects, int fixedDefects) {

`    `if (totalDefects == 0) return 0.0;

`    `return (float) fixedDefects / totalDefects \* 100;

}

// Função para calcular a porcentagem de escape de produção

float calculateProductionEscapePercentage(int totalDefects, int productionEscapes) {

`    `if (totalDefects == 0) return 0.0;

`    `return (float) productionEscapes / totalDefects \* 100;

}

// Função para calcular a taxa de falha na mudança

float calculateChangeFailureRate(int totalChanges, int failedChanges) {

`    `if (totalChanges == 0) return 0.0;

`    `return (float) failedChanges / totalChanges \* 100;

}

int main() {

`    `// Simulando dados de testes e defeitos

`    `int totalTests = 100;

`    `int passedTests = 90;

`    `int failedTests = 10;

`    `int totalDefects = 50;

`    `int fixedDefects = 40;

`    `int productionEscapes = 5;

`    `int totalChanges = 20;

`    `int failedChanges = 2;

`    `// Calculando métricas

`    `float testEfficiency = calculateTestEfficiency(totalTests, passedTests, failedTests);

`    `float defectRemovalEfficiency = calculateDefectRemovalEfficiency(totalDefects, fixedDefects);

`    `float productionEscapePercentage = calculateProductionEscapePercentage(totalDefects, productionEscapes);

`    `float changeFailureRate = calculateChangeFailureRate(totalChanges, failedChanges);

`    `// Exibindo resultados

`    `printf("Test Efficiency: %.2f%%\n", testEfficiency);

`    `printf("Defect Removal Efficiency: %.2f%%\n", defectRemovalEfficiency);

`    `printf("Production Escape Percentage: %.2f%%\n", productionEscapePercentage);

`    `printf("Change Failure Rate: %.2f%%\n", changeFailureRate);

`    `return 0;

}

Este código C é uma implementação simples das métricas propostas no artigo. Ele calcula as métricas com base nos dados de teste, defeitos e mudanças fornecidos e exibe os resultados. Obtendo resultados desse código, ao compilar e executá-lo em qualquer ambiente de desenvolvimento C. Os resultados serão exibidos no console, mostrando as métricas calculadas com base nos dados de entrada simulados.


1\. Coleta de Dados:

Para replicar o trabalho, precisamos de dados de teste, defeitos e mudanças que serão usados para calcular as métricas de qualidade de software. 

Para este exemplo, Iremos usar dados simulados:

//Codigo:

// Dados simulados

int totalTests = 100;

int passedTests = 90;

int failedTests = 10;

int totalDefects = 50;

int fixedDefects = 40;

int productionEscapes = 5;

int totalChanges = 20;

int failedChanges = 2;

2\. Implementação das Métricas:

Agora, implementando as funções para calcular as métricas propostas no artigo, como ja foi feito anteriormente.

//Codigo:

// Função para calcular a eficiência do teste

float calculateTestEfficiency(int totalTests, int passedTests, int failedTests) {

`    `if (totalTests == 0) return 0.0;

`    `return (float) passedTests / totalTests \* 100;

}

// Função para calcular a eficiência de remoção de defeitos

float calculateDefectRemovalEfficiency(int totalDefects, int fixedDefects) {

`    `if (totalDefects == 0) return 0.0;

`    `return (float) fixedDefects / totalDefects \* 100;

}

// Função para calcular a porcentagem de escape de produção

float calculateProductionEscapePercentage(int totalDefects, int productionEscapes) {

`    `if (totalDefects == 0) return 0.0;

`    `return (float) productionEscapes / totalDefects \* 100;

}

// Função para calcular a taxa de falha na mudança

float calculateChangeFailureRate(int totalChanges, int failedChanges) {

`    `if (totalChanges == 0) return 0.0;

`    `return (float) failedChanges / totalChanges \* 100;

}

3\. Aplicação das Métricas:

Agora, calculando as métricas usando os dados coletados e as funções implementadas.

//Codigo:

// Calculando métricas

float testEfficiency = calculateTestEfficiency(totalTests, passedTests, failedTests);

float defectRemovalEfficiency = calculateDefectRemovalEfficiency(totalDefects, fixedDefects);

float productionEscapePercentage = calculateProductionEscapePercentage(totalDefects, productionEscapes);

float changeFailureRate = calculateChangeFailureRate(totalChanges, failedChanges);

4\. Exibição dos Resultados:

Por fim, iremos exibir os resultados das métricas calculadas.

//Codigo:

// Exibindo resultados

printf("Test Efficiency: %.2f%%\n", testEfficiency);

printf("Defect Removal Efficiency: %.2f%%\n", defectRemovalEfficiency);

printf("Production Escape Percentage: %.2f%%\n", productionEscapePercentage);

printf("Change Failure Rate: %.2f%%\n", changeFailureRate);