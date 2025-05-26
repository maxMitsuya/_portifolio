# Max Mitsuya - Portfólio Profissional
## Cientista de Dados

👋 Bem-vindo ao meu portfólio profissional! Aqui você encontrará uma coleção dos meus principais projetos em Ciência de Dados

### Projeto 01 - Aplicação de modelos de ML para previsão de churn

**Descrição**:

Neste projeto, implementei três modelos de machine learning (Regressão Logística, Random Forest e XGBoost) para prever churn (cancelamento) de clientes em um e-commerce. Com dados de comportamento dos usuários, como tempo no app, satisfação e histórico de compras, otimizei cada algoritmo usando GridSearchCV e técnicas como SMOTE para lidar com o desbalanceamento dos dados.

O XGBoost se destacou como o melhor modelo, alcançando 74,2% de recall (detectando a maioria dos clientes que realmente cancelariam) e 91,2% de AUC-ROC, demonstrando alta capacidade de classificação. Além disso, identifiquei que o tempo sem comprar e o valor de cashback são os fatores mais relevantes para prever churn.

Essa solução tem aplicação direta em estratégias de retenção de clientes, permitindo que empresas ajam preventivamente com ofertas personalizadas, melhorando a experiência do usuário e reduzindo perdas. A análise não apenas compara modelos, mas também gera insights acionáveis, tornando-a valiosa para áreas de CRM e marketing.

**Principais características**:
  - Análise Exploratória Detalhada com identificação de correlações chave 
  - Pipeline de Processamento integrando balanceamento e modelagem 
  - Otimização Sistemática dos hiperparâmetros para cada algoritmo 
  - Comparação Quantitativa usando múltiplas métricas (F1-Score, Recall, ROC AUC) 
  - Explicabilidade com análise de importância de variáveis 

**Link**: [Acesse aqui](https://github.com/maxMitsuya/analise-lr-rf-xgboost)

### Projeto 02 - Projeto de Segmentação RFV para E-Commerce

**Descrição**:

Neste projeto, implementei uma análise de clustering RFV (Recência, Frequência, Valor) para segmentar clientes de um e-commerce com base em seu comportamento de compra. Utilizei diferentes algoritmos de clusterização (K-Means, Hierárquico, DBSCAN e MeanShift) para identificar grupos de clientes com padrões distintos, permitindo estratégias de marketing mais direcionadas e eficientes.

**Aplicação Prática**:
Essa segmentação permite:
- Reduzir custos de marketing ao direcionar campanhas apenas para públicos relevantes.
- Aumentar a retenção com ações personalizadas para cada perfil.
- Maximizar receita ao identificar oportunidades de upselling e fidelização.

**Link**: [Acesse aqui](https://github.com/maxMitsuya/clustering_models)
