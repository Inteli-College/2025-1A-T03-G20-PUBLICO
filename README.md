# 2025-1A-T03-G20-PUBLICO
Repository for group 20 of class T03 (2025/1A)

Relatório Público do Projeto SRM

Introdução
O projeto tem como objetivo gerar dados que forneçam à SRM uma visão clara do desempenho das empresas em que investem. Através da análise de dados financeiros, buscamos oferecer insights que auxiliem na tomada de decisões estratégicas.

Status do Projeto
Sprint 3: Coleta e Preparação de Dados
Atividades Realizadas:
Coleta de dados financeiros a partir de um arquivo Excel.
Limpeza e preparação dos dados, incluindo:
Remoção de linhas e colunas vazias.
Preenchimento de valores nulos.
Renomeação de colunas para melhor entendimento.

Estrutura do Dataset:
O conjunto de dados compreende 10,272 entradas com 15 colunas. As principais colunas incluem Nome, CNPJ/CPF, Ingresso, Vencimento, Operação, Valor e Status do Título.
Criação da Variável Target:
Uma nova variável binária foi criada para indicar auditoria: "1" para títulos liquidáveis e "0" para outros.
Sprint 4: Desenvolvimento e Treinamento do Modelo de Machine Learning

Objetivo:
Desenvolver um modelo preditivo para prever a liquidez dos títulos.
Métodos Utilizados:
Algorithms: Logistic Regression e Random Forest.
Preparação dos dados e análise da importância das features.

Resultados Obtidos:
O desempenho do modelo foi avaliado com métricas como acurácia, precisão e recall. A comparação entre os métodos identificou o melhor modelo para aplicação.

Próximos Passos

Otimização do Modelo:
Realizar a otimização de hiperparâmetros para aumentar a precisão e a eficácia do modelo.
Implementação em Produção:
Preparar o modelo para deployment e integrá-lo aos sistemas de decisão da SRM.

Monitoramento Contínuo:
Estabelecer mecanismos de monitoramento e ajuste do modelo à medida que novos dados se tornam disponíveis.

Reunião com Stakeholders:
Realizar uma apresentação formal dos resultados e do plano de implementação para os stakeholders da SRM.
