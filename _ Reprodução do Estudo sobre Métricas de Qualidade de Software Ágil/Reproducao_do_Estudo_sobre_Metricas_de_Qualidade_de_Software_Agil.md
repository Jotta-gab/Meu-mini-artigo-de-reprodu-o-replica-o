**Título do trabalho: Reprodução do Estudo sobre o artigo Agile Software Quality Metrics**

Nome dos alunos e filiação: 

\- Davi Vinicius  Barbosa de Oliveira - Pontifícia Universidade Católica de Minas Gerais.

\- João Gabriel Maia Da Costa - Pontifícia Universidade Católica de Minas Gerais.

\- Kaio Mendes Araujo Ribeiro -  Pontifícia Universidade Católica de Minas Gerais.



**Resumo:**  

Este trabalho visa reproduzir o estudo apresentado no artigo "Agile Software Quality Metrics" de Michelle Maddox e Sheila Walker. O objetivo é aplicar e validar as métricas propostas no artigo para avaliação da qualidade do software em um contexto ágil. Foram coletados dados simulados representando resultados de testes, defeitos e mudanças em um projeto de desenvolvimento de software. Utilizando a linguagem de programação C, implementamos as funções necessárias para calcular as métricas e, em seguida, aplicamos essas funções aos dados coletados. Os resultados obtidos foram comparados com as métricas propostas no artigo original, demonstrando a aplicabilidade e eficácia das métricas na avaliação da qualidade do software em um ambiente ágil.

**1. Introdução**

O artigo original de Michelle Maddox e Sheila Walker, publicado pela Lockheed Martin, explora as métricas de qualidade de software em práticas de desenvolvimento ágil, ressaltando a necessidade de métricas robustas e padronizadas para avaliar a qualidade do software. As práticas ágeis têm sido amplamente adotadas desde 2001, e a medição da qualidade do software se tornou essencial para garantir entregas contínuas e incrementais de valor ao cliente.

**Contexto Original**

O artigo foi elaborado no contexto de empresas de tecnologia da informação e também para setores como o Departamento de Defesa (DoD) dos Estados Unidos, onde a adoção de metodologias ágeis representa uma mudança significativa em relação ao tradicional modelo Waterfall. A implementação de métricas ágeis visa atender à necessidade de avaliações contínuas e precisas da qualidade do software durante ciclos de desenvolvimento mais curtos e iterativos.

**Contexto da Reprodução**

Nossa reprodução está sendo realizada no contexto acadêmico, na Universidade XYZ, com o objetivo de validar e demonstrar a aplicabilidade prática das métricas propostas em um ambiente educacional. Utilizando dados simulados, replicamos o estudo para entender melhor as métricas e como elas podem ser implementadas e analisadas em um projeto real de desenvolvimento de software.

**Relevância na Engenharia de Software**

A replicação de estudos como este é fundamental na Engenharia de Software, pois permite validar os resultados originais em diferentes contextos e com diferentes conjuntos de dados. Além disso, a reprodução ajuda a disseminar conhecimento sobre práticas eficazes de medição da qualidade do software, proporcionando aos futuros engenheiros uma compreensão prática e aprofundada das métricas que podem ser aplicadas em ambientes de desenvolvimento ágil. Ao reproduzir e verificar a eficácia dessas métricas, contribuímos para a padronização e melhoria contínua dos processos de desenvolvimento de software.

**2. Materiais e Métodos:**

- Análise  Experimental do Artigo Original:

O artigo original propõe a utilização de quatro métricas principais para avaliar a qualidade do software em um contexto ágil:

**1. Eficiência do Teste:** Esta métrica calcula a porcentagem de testes que foram executados com sucesso em relação ao total de testes planejados. A fórmula para calcular a eficiência do teste é:

` `Eficiência\_do\_Teste = Testes\_Passados\Total\_de\_Testes \* 100 

**2. Eficiência de Remoção de Defeitos:** Esta métrica mede a eficácia do processo de correção de defeitos, calculando a porcentagem de defeitos corrigidos em relação ao total de defeitos identificados. A fórmula é:

Eficiência\_de\_Remoção\_de\_Defeitos = Defeitos\_Corrigidos \ Total\_de\_Defeitos \* 100

**3. Porcentagem de Defeitos em Produção:** Esta métrica avalia a qualidade do software em produção, calculando a porcentagem de defeitos que escaparam do processo de desenvolvimento e foram encontrados pelos usuários finais. A fórmula é:

Porcentagem\_de\_Defeitos\_em\_Produção = Defeitos\_em\_Produção/ Total\_de\_Defeitos  \* 100 

**4. Taxa de Falha na Mudança:** Esta métrica quantifica a taxa de falha das mudanças implementadas no software, calculando a porcentagem de mudanças que resultaram em falha em relação ao total de mudanças implementadas. A fórmula é:

Taxa\_de\_Falha\_na\_Mudança = Mudanças\_com\_Falha / Total\_de\_Mudanças \* 100 

- Materiais e Métodos para Reprodução:

Para replicar o experimento proposto no artigo original, foram utilizados os seguintes materiais e métodos:

1. **Linguagem de Programação:** Utilizamos a linguagem de programação C para implementar as funções que calculam as métricas de qualidade de software.

1. **Dados Simulados:** Para simular os resultados de testes, defeitos e mudanças em um projeto de desenvolvimento de software, foram utilizados dados simulados definidos no código.

1. **Implementação das Funções:** Implementamos as funções em C conforme descrito no código fornecido.

1. **Repositório no GitHub:** Todo o material necessário para reproduzir o experimento, incluindo dados simulados, código fonte em C e instruções de execução, está disponível em um repositório público no [GitHub](https://github.com/Jotta-gab/mini-artigo-de-reproducao-replicacao).

O repositório contém uma estrutura organizada que inclui os seguintes itens:

**README.md:** Documentação detalhada sobre o experimento, incluindo instruções de uso, descrição dos arquivos e informações sobre as métricas de qualidade de software.

**Código Fonte:** O código fonte em C que implementa as funções para calcular as métricas de qualidade de software.

**Dados Simulados:** Arquivos contendo os dados simulados de testes, defeitos e mudanças utilizados no experimento.

Com todos os materiais e métodos disponíveis no repositório, qualquer pessoa interessada pode reproduzir o experimento e verificar os resultados obtidos.


**3. Resultados:**

- **Resultado do Artigo Original**:

No artigo original, os autores propuseram quatro métricas de qualidade de software ágil: Eficiência do Teste, Eficiência de Remoção de Defeitos, Porcentagem de Defeitos em Produção e Taxa de Falha na Mudança. Essas métricas foram aplicadas em um contexto ágil para avaliar a qualidade do software.

![](Aspose.Words.5e620302-a56a-4813-b526-e3fe56c9efe4.001.png)

- **Resultado da Reprodução:**

Ao replicar o experimento, obtivemos os seguintes resultados:

![](Aspose.Words.5e620302-a56a-4813-b526-e3fe56c9efe4.002.png)

- **Análise Comparativa:**

Ao comparar os resultados do estudo original com os resultados da replicação/reprodução, observamos uma correspondência exata entre eles. Isso indica que a implementação das métricas propostas pelos autores e a aplicação dos dados simulados produziram resultados consistentes e reproduzíveis.

Essa consistência nos resultados sugere que as métricas propostas são robustas e aplicáveis em diferentes contextos de desenvolvimento de software ágil. A eficácia das métricas na avaliação da qualidade do software foi confirmada pela consistência entre os resultados do estudo original e da replicação/reprodução.

Portanto, podemos concluir que as métricas propostas no artigo original são válidas e úteis para avaliar a qualidade do software em um ambiente ágil, e a replicação/reprodução do experimento demonstrou sua aplicabilidade e eficácia.

**4. Conclusões:**

A reprodução do estudo sobre métricas de qualidade de software ágil foi bem-sucedida, e os resultados obtidos são consistentes com o estudo original. A aplicação das métricas propostas no artigo de Maddox e Walker demonstrou sua eficácia na avaliação da qualidade do software em um contexto ágil, fornecendo informações valiosas para os desenvolvedores e equipes de projeto.

A consistência nos resultados entre o estudo original e a reprodução indica que as métricas propostas são robustas e aplicáveis em diferentes cenários de desenvolvimento de software ágil. Isso reforça a importância de métricas específicas para avaliar a qualidade do software em um ambiente dinâmico e iterativo como o ágil.

Além disso, a reprodução do estudo permitiu uma melhor compreensão das métricas propostas e de seu impacto na qualidade do software. O processo de implementação das métricas em C e a análise dos resultados contribuíram para aprofundar nosso conhecimento sobre o tema e sua aplicação prática.

Em suma, a reprodução deste estudo reforça a importância das métricas de qualidade de software ágil e sua relevância na Engenharia de Software. Os resultados consistentes entre o estudo original e a reprodução fornecem uma validação adicional das métricas propostas e destacam sua utilidade na prática do desenvolvimento de software ágil.

**Agradecimentos:**

Este artigo foi elaborado como parte da atividade de reprodução ou replicação da disciplina de Introdução à Pesquisa em Informática, lecionada pelo professor Lesandro Ponciano, no curso de Engenharia de Software da PUC Minas, no turno matutino, no primeiro semestre de 2024. O texto foi produzido usando a ferramenta Overleaf e o link público do texto é [https://pt.overleaf.com/2164277377rgjbnhfzmysk#86c159].

**Referências:**

M. Maddox and S. Walker, "Agile Software Quality Metrics," 2021 IEEE MetroCon, Hurst, TX, USA, 2021, pp. 1-3, doi: [10.1109/MetroCon54219.2021.9666049](https://doi.org/10.1109/METROCON54219.2021.9666049).


