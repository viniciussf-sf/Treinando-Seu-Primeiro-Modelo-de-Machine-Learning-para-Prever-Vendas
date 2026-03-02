🍦 Ice Cream Sales Predictor - Gelato Mágico
📌 Sobre o Projeto

Este projeto aplica conceitos fundamentais de Machine Learning para prever a quantidade de sorvetes vendidos com base na temperatura do dia.

A ideia surgiu a partir de um cenário real de negócio: a sorveteria Gelato Mágico, localizada em uma cidade litorânea, enfrenta dificuldades para planejar sua produção diária devido à variação na demanda causada pelo clima.

Utilizando um modelo de regressão, é possível prever as vendas com base na temperatura e, assim:

✅ Reduzir desperdícios

✅ Evitar perda de vendas

✅ Maximizar lucros

✅ Melhorar o planejamento da produção

🎯 Objetivo

Desenvolver um modelo de regressão preditiva capaz de:

Treinar um modelo para prever vendas com base na temperatura

Avaliar o desempenho com métricas apropriadas

Registrar experimentos utilizando MLflow

Criar um pipeline estruturado para garantir reprodutibilidade

Preparar o modelo para deploy em ambiente de cloud computing

🧠 Problema de Machine Learning

Tipo: Regressão Supervisionada

Feature (Entrada): Temperatura (°C)

Target (Saída): Quantidade de sorvetes vendidos

📊 Dataset

Exemplo de estrutura do dataset:

Temperatura (°C)	Vendas
20	150
25	250
30	400
35	500

Observação: Os dados demonstram forte correlação positiva entre temperatura e vendas.

🏗️ Estrutura do Projeto

ice-cream-sales-predictor/

├── inputs/
   
   └── dados_vendas.csv

├── notebooks/
   
   └── exploracao.ipynb

├── src/
   
   ├── train.py
   
   ├── predict.py
   
   └── pipeline.py

├── models/

├── requirements.txt

├── README.md

└── .gitignore

🔄 Pipeline do Projeto

📥 Coleta e carregamento dos dados

🔎 Análise exploratória

✂️ Separação treino/teste

🏋️ Treinamento do modelo

📈 Avaliação com métricas

📦 Registro no MLflow

🚀 Preparação para deploy

📈 Métricas Utilizadas

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² Score

Essas métricas permitem avaliar a qualidade das previsões do modelo.

🧪 Tecnologias Utilizadas

Python

Pandas

Scikit-learn

MLflow

Matplotlib / Seaborn

📦 Registro e Versionamento

Os experimentos foram registrados utilizando o MLflow, permitindo:

Comparar execuções

Versionar modelos

Armazenar métricas

Garantir rastreabilidade

☁️ Possível Deploy

O modelo pode ser implantado em ambiente de nuvem como:

Azure Machine Learning

API com FastAPI

Container Docker

Exemplo de requisição para previsão:

{
  "temperatura": 30
}

Resposta esperada:

{
  "vendas_previstas": 395
}
💡 Insights Obtidos

Existe forte correlação positiva entre temperatura e vendas.

Um modelo simples de regressão linear já apresenta bom desempenho.

A criação de um pipeline estruturado melhora a reprodutibilidade.

O uso de MLflow facilita o controle de experimentos.

Pequenos negócios podem se beneficiar muito de soluções de IA acessíveis.

🚀 Próximos Passos (Melhorias Futuras)

Adicionar variáveis como:

Dia da semana

Feriados

Sazonalidade

Implementar modelos mais robustos (Random Forest, Gradient Boosting)

Criar API para previsões em tempo real

Automatizar re-treinamento do modelo

Criar dashboard interativo com Streamlit

🏁 Conclusão

Este projeto demonstra como aplicar Machine Learning para resolver um problema real de negócio de forma prática e estruturada.

Além de desenvolver o modelo preditivo, o projeto também contempla boas práticas como:

Organização de código

Versionamento de experimentos

Pipeline reprodutível

Preparação para deploy

👨‍💻 Autor

Vinicius Saroldi

[[Seu GitHub](https://github.com/viniciussf-sf/Treinando-Seu-Primeiro-Modelo-de-Machine-Learning-para-Prever-Vendas/edit/main/README.md)]
