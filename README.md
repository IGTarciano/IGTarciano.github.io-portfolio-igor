## Projeto de Análise Temporal de Vendas

Projeto de Análise Temporal de Vendas

Neste projeto, desenvolvi um modelo preditivo para séries temporais com o objetivo de prever vendas futuras, especificamente para o primeiro semestre de 2025. O diferencial deste trabalho está na abordagem híbrida que implementei, combinando análise endógena (baseada apenas no histórico da série) com variáveis exógenas para criar um modelo mais robusto e menos determinístico.

O coração do projeto é a implementação do modelo SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous variables), que permite incorporar tanto a sazonalidade inerente às vendas quanto fatores externos que influenciam o comportamento do mercado. Para garantir a qualidade das previsões, realizei um tratamento cuidadoso para tornar a série temporal estacionária através de diferenciação e análise de média móvel.

Um aspecto inovador foi a integração com banco de dados, extraindo informações de vendas mensais e registros de transações para alimentar o modelo. Isso demonstra minha capacidade de trabalhar com fontes de dados estruturadas e criar pipelines de dados completos para análises avançadas.

Os resultados do modelo foram validados através de métricas de desempenho e análise visual das previsões contra dados reais, confirmando a eficácia da abordagem para capturar tendências e padrões sazonais nas vendas. Este projeto exemplifica minha habilidade em aplicar técnicas estatísticas avançadas e modelagem preditiva para gerar insights acionáveis em contextos de negócios.



**Tecnologias utilizadas:** Python, pandas, statsmodels, SARIMAX, matplotlib, seaborn

**Arquivos do projeto:**
- [Notebook de Análise](./Modelo_temporal_vendas_analise.ipynb)
- [Visualizações](./images/dashboard_vendas.png)

---

## Projeto de Previsão de Nível de Estoque

Projeto de Previsão de Nível de Estoque

Este projeto aborda um desafio crucial no varejo: a otimização de níveis de estoque através de técnicas avançadas de aprendizado de máquina. Utilizando um conjunto de dados do Kaggle sobre previsão de estoque em lojas de varejo, desenvolvi um pipeline completo de ciência de dados que abrange desde a extração e tratamento dos dados até a implementação de modelos preditivos sofisticados.

O processo iniciou com uma análise exploratória detalhada dos dados, investigando padrões de vendas, níveis de estoque e fatores influenciadores como sazonalidade, promoções e condições climáticas. Após a preparação dos dados, implementei diversos modelos de aprendizado de máquina, com destaque para redes neurais utilizando MLPRegressor, que demonstraram capacidade de capturar relações complexas entre as variáveis.

A avaliação do modelo foi realizada através de métricas rigorosas como erro absoluto médio e raiz do erro quadrático médio, permitindo quantificar a precisão das previsões. Os resultados demonstram que o modelo consegue prever níveis de estoque com margem de erro aceitável para aplicações práticas, oferecendo uma ferramenta valiosa para gestores de varejo otimizarem suas decisões de reposição e evitarem tanto excesso quanto falta de produtos.

Este projeto evidencia minha capacidade de aplicar técnicas avançadas de ciência de dados para resolver problemas reais de negócios, combinando conhecimentos em programação Python, estatística, aprendizado de máquina e análise de dados.


**Tecnologias utilizadas:** Python, scikit-learn, redes neurais, pandas, matplotlib

**Arquivos do projeto:**
- [Notebook de Análise](./Nivel_estoque_prev.ipynb)
- [Resultados](./Df_resultado.xlsx)
- [Visualizações](./images/dashboard_estoque.png)
