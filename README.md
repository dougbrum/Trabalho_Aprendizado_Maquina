# Análise da Personalidade do Cliente para Campanhas de Marketing - iFood CRM Data Analyst Case

## Visão Geral

Este projeto foi desenvolvido como parte da disciplina de Aprendizado de Máquina, sob a orientação da Professora Dr. Flávia Bernardini, no Instituto de Computação da Universidade Federal Fluminense. Os alunos responsáveis são: Douglas Brum, Lucas Mendonça e Tatiana Machado. O objetivo é utilizar técnicas de aprendizado de máquina para prever as respostas dos clientes em campanhas de marketing, com base no conjunto de dados "Customer Personality Analysis".

## Contexto do Projeto

O estudo é direcionado ao setor de varejo de alimentos, utilizando dados de 2.240 clientes, incluindo informações sócio-demográficas e comportamentais. O foco é a construção de um modelo preditivo para identificar clientes propensos a responder positivamente às campanhas.

## Conteúdo e Atributos do Conjunto de Dados

### Pessoas
- **ID**: Identificador único do cliente.
- **Year_Birth**: Ano de nascimento.
- **Education**: Nível de educação.
- **Marital_Status**: Estado civil.
- **Income**: Renda anual do domicílio.
- **Kidhome**: Número de crianças.
- **Teenhome**: Número de adolescentes.
- **Dt_Customer**: Data de inscrição.
- **Recency**: Dias desde a última compra.
- **Complain**: Reclamações nos últimos 2 anos.

### Produtos
- **Mnt[Product]**: Gastos em vários produtos nos últimos 2 anos.

### Promoção
- **NumDealsPurchases**: Compras com desconto.
- **AcceptedCmp[1-5]**: Aceitação das ofertas nas campanhas.
- **Response**: Resposta à última campanha.

### Lugar
- **Num[Medium]Purchases**: Compras por diferentes meios.

## Metodologia

O projeto envolve a análise exploratória de dados, segmentação de clientes e construção de um modelo preditivo usando classificadores como Random Forest, Logistic Regression, GradientBoostingClassifier e DecisionTreeClassifier.

## Modelagem e Avaliação

As métricas de desempenho são essenciais na avaliação de modelos de machine learning, oferecendo insights sobre como eles operam sob diferentes condições. Analisamos o desempenho de classificadores como Random Forest, Logistic Regression, GradientBoostingClassifier e DecisionTreeClassifier. O Random Forest se destaca por seu equilíbrio notável entre Precision e Recall, sendo uma escolha excelente para situações que exigem uma abordagem equilibrada e eficaz.

## Resultados e Conclusão

O modelo Random Forest se destacou, mostrando-se uma ferramenta poderosa para a segmentação eficaz de clientes e otimização de campanhas de marketing. O estudo fornece insights valiosos para estratégias de marketing direcionadas e personalizadas.

## Trabalhos Futuros

Explorar outros algoritmos de aprendizado de máquina e aprofundar na engenharia de recursos para aprimorar ainda mais o modelo.
