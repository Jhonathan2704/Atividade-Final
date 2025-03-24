Análise de Dados de E-commerce Brasileiro (Olist)
<div align="center"> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"> <img src="https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Looker Studio"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"> </div>
📌 Visão Geral
Análise de dados de vendas da Olist (2016-2018) para identificar padrões de compra, desempenho logístico e satisfação dos clientes.

🔗 Dataset: Brazilian E-Commerce Public Dataset (Kaggle)

🛠️ Tecnologias
Análise: Python (Pandas, Matplotlib, Seaborn) no Google Colab

Visualização: Looker Studio

Versionamento: GitHub

📊 Principais Análises
Top categorias por vendas: beleza_saude, esporte_lazer e informatica_acessorios.

Estados com maior tempo de entrega: RR (30 dias), AM (28 dias).

Correlação negativa entre preço e frete (-0.34).

📂 Estrutura do Projeto
Copy
olist-ecommerce-analysis/  
├── data/  
│   ├── raw/                  # Dados originais  
│   └── processed/            # Dados tratados  
├── notebooks/  
│   └── analysis.ipynb        # Análise no Colab  
└── README.md                 # Documentação  
🚀 Como Executar
Baixe os dados do Kaggle.

Execute o notebook analysis.ipynb no Google Colab.

Importe os CSVs tratados para o Looker Studio.

bash
Copy
git clone [seu-repositorio]  
pip install pandas matplotlib seaborn  # Dependências  
📈 Dashboard
Acesse o dashboard interativo: [Link do Looker Studio] (adicione após publicação)

📝 Insights
⚠️ Problema: Frete alto em categorias de baixo valor.

💡 Oportunidade: Pacotes promocionais para categorias com alta avaliação.

<div align="center"> <img src="https://via.placeholder.com/600x400?text=Exemplo+de+Gráfico" alt="Dashboard Preview"> </div>
📜 Licença
Este projeto utiliza dados públicos sob a licença CC BY-NC-SA 4.0.

Feito com ❤️ por Jhonathan Willian Silva. Contribuições são bem-vindas!
