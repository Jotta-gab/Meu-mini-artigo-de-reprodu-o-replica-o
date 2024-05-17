include <stdio.h>

// Função para calcular a eficiência do teste

float calculateTestEfficiency(int totalTests, int passedTests, int failedTests) {

    if (totalTests == 0) return 0.0;

    return (float) passedTests / totalTests * 100;

}

// Função para calcular a eficiência de remoção de defeitos

float calculateDefectRemovalEfficiency(int totalDefects, int fixedDefects) {

    if (totalDefects == 0) return 0.0;

    return (float) fixedDefects / totalDefects * 100;

}

// Função para calcular a porcentagem de escape de produção

float calculateProductionEscapePercentage(int totalDefects, int productionEscapes) {

    if (totalDefects == 0) return 0.0;

    return (float) productionEscapes / totalDefects * 100;

}

// Função para calcular a taxa de falha na mudança

float calculateChangeFailureRate(int totalChanges, int failedChanges) {

    if (totalChanges == 0) return 0.0;

    return (float) failedChanges / totalChanges * 100;

}

int main() {

    // Simulando dados de testes e defeitos

    int totalTests = 100;

    int passedTests = 90;

    int failedTests = 10;

    int totalDefects = 50;

    int fixedDefects = 40;

    int productionEscapes = 5;

    int totalChanges = 20;

    int failedChanges = 2;

    // Calculando métricas

    float testEfficiency = calculateTestEfficiency(totalTests, passedTests, failedTests);

    float defectRemovalEfficiency = calculateDefectRemovalEfficiency(totalDefects, fixedDefects);

    float productionEscapePercentage = calculateProductionEscapePercentage(totalDefects, productionEscapes);

    float changeFailureRate = calculateChangeFailureRate(totalChanges, failedChanges);

    // Exibindo resultados

    printf("Test Efficiency: %.2f%%\n", testEfficiency);

    printf("Defect Removal Efficiency: %.2f%%\n", defectRemovalEfficiency);

    printf("Production Escape Percentage: %.2f%%\n", productionEscapePercentage);

    printf("Change Failure Rate: %.2f%%\n", changeFailureRate);

    return 0;

}
