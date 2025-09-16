# MVP-1-privacidade-ciberseguranca
MVP de Machine Learning aplicado ao dataset Online Retail II

# MVP: Análise de Vendas do Online Retail II

## Objetivo
Este MVP tem como objetivo analisar dados de transações de varejo e construir modelos de **machine learning** para prever padrões de compra, identificar comportamento de clientes e gerar insights sobre vendas.  
O foco é trabalhar com **pré-processamento de dados, modelagem, avaliação de modelos e interpretação de resultados**.

## Dataset Utilizado
- **Nome:** Online Retail II  
- **Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)  
- **Descrição:**  
  O dataset contém transações de um varejista online no Reino Unido, com informações sobre:  
  - InvoiceNo: número da fatura  
  - StockCode: código do produto  
  - Description: descrição do produto  
  - Quantity: quantidade comprada  
  - InvoiceDate: data da fatura  
  - UnitPrice: preço unitário  
  - CustomerID: identificador do cliente  
  - Country: país do cliente  

---

## Tecnologias Usadas
- **Linguagem:** Python  
- **Ambiente:** Google Colab  
- **Bibliotecas:**  
  - Pandas, Numpy (manipulação de dados)  
  - Matplotlib, Seaborn (visualização)  
  - Scikit-learn (pré-processamento, modelagem e métricas)  
  - XGBoost, Random Forest (modelos de aprendizado supervisionado)  

---

## Etapas para Execução do Código
1. **Carregamento do dataset:**  
   - Importar o arquivo CSV e verificar os dados.
2. **Pré-processamento de dados:**  
   - Limpeza de valores nulos e duplicados  
   - Conversão de colunas para tipos adequados  
   - Tratamento de variáveis categóricas (one-hot encoding)  
   - Normalização de variáveis numéricas
3. **Divisão do dataset:**  
   - Separação em treino, validação e teste  
   - Garantia de ausência de vazamento de dados  
4. **Engenharia de atributos:**  
   - Criação de variáveis derivadas como total da compra, frequência de compra, etc.
5. **Modelagem:**  
   - Treinamento de diferentes algoritmos de classificação/regressão, como Logistic Regression, Random Forest e XGBoost  
   - Otimização inicial de hiperparâmetros  
6. **Avaliação de modelos:**  
   - Métricas utilizadas: Accuracy, Precision, Recall, F1-score, ROC-AUC  
   - Comparação entre modelos para identificar o melhor desempenho  
7. **Conclusão:**  
   - Seleção do modelo final e análise de resultados  
   - Discussão sobre limitações e melhorias futuras

---

## Conclusão
O MVP permitiu:  
- Explorar e tratar dados reais de varejo do dataset Online Retail II  
- Construir pipelines de **pré-processamento, modelagem e avaliação**  
- Comparar diferentes modelos de machine learning e selecionar o melhor para análise de comportamento de clientes  
- Documentar todo o processo, garantindo **reprodutibilidade** e **boas práticas**  

O projeto serve como base para análises mais avançadas, como previsão de vendas, segmentação de clientes e recomendações de produtos.

