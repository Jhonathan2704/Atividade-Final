Documentação do Projeto: Análise de E-commerce Brasileiro (Olist)
Repositório no GitHub: [Link do seu repositório] (adicione depois)
Conjunto de Dados: Brazilian E-Commerce Dataset (Kaggle)

📌 1. Objetivo do Projeto
Analisar o desempenho de vendas, entregas e satisfação de clientes do marketplace Olist (2016-2018) para identificar:

Tendências de vendas por categoria/estado.

Desempenho logístico (tempo de entrega).

Relação entre preço, frete e avaliações.

🛠️ 2. Ferramentas Utilizadas
Ferramenta	Finalidade
Google Colab	Limpeza e análise dos dados (Python/Pandas).
Looker Studio	Visualização e dashboard interativo.
GitHub	Documentação e versionamento.

📊 3. Metodologia
3.1. Coleta e Pré-processamento
Fonte: Dados públicos da Olist (Kaggle) com 9 tabelas relacionadas.

Tratamento no Colab:

Unificação de tabelas (ex: pedidos + clientes + produtos).

Cálculo de novas métricas (delivery_time, total_price).

Tratamento de missing values e outliers.

3.2. Análise Exploratória (EDA)
Principais descobertas:

Top 3 categorias mais vendidas:

beleza_saude (23%), esporte_lazer (15%), informatica_acessorios (12%).

Estados com maior tempo de entrega:

RR (30 dias), AM (28 dias), AP (26 dias).

Correlação negativa entre preço e frete (-0.34).

(Inclua prints dos gráficos do Colab/Looker Studio no GitHub.)

3.3. Visualização no Looker Studio
Dashboard público: [Link do seu dashboard] (adicione depois)

Filtros interativos: Período, estado, categoria.

Visualizações-chave:

Mapa de calor de vendas por estado.

Linha do tempo de cancelamentos.

Tabela dinâmica de produtos.

📂 4. Estrutura do Repositório (GitHub)
markdown

olist-ecommerce-analysis/  
├── data/  
│   ├── raw/                  # Dados brutos (CSVs originais)  
│   └── processed/            # Dados tratados (orders_clean.csv, etc.)  
├── notebooks/  
│   └── olist_analysis.ipynb  # Código completo do Colab  
├── docs/  
│   └── report.md             # Relatório técnico (esta documentação)  
└── README.md                 # Visão geral do projeto  

📌 5. Como Reproduzir o Projeto
Baixe os dados do Kaggle.

Execute o notebook olist_analysis.ipynb no Google Colab.

Importe os CSVs tratados para o Looker Studio.

bash

# Comandos úteis para o GitHub (opcional)  
git clone [seu-repositório]  
pip install -r requirements.txt  # Se usar virtualenv  

🔍 6. Insights e Recomendações
Oportunidade: Categorias premium (informática) têm menor frete proporcional.

Alerta: Clientes do Norte/Nordeste apresentam maior taxa de cancelamento (+15%).

Ação: Criar promoções para categorias com alta avaliação (>4.5) mas baixo volume.

📜 7. Referências
Base de Dados Olist (Kaggle).

Documentação do Looker Studio.
