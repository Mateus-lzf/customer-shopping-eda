# 🛍️ Análise Exploratória de Dados — Comportamento de Compras de Clientes

## 📌 Sobre o Projeto
Análise exploratória de um dataset com 5.000 registros de compras de clientes,
com o objetivo de identificar padrões de comportamento e insights de negócio.

## 🗂️ Estrutura do Projeto
projeto/
│
├── data/                               # Dataset utilizado
│   └── customer_shopping_behavior.csv 
│
├── aed.ipynb                           # Notebook com a análise completa
├── .gitignore                          # Arquivos ignorados pelo Git
└── README.md                           # Documentação do projeto   

## 🎯 Objetivos da Análise
- Entender o perfil dos clientes (idade, gênero, localização)
- Identificar categorias e produtos mais vendidos
- Analisar ticket médio por método de pagamento
- Verificar sazonalidade nas vendas

## 📊 Principais Insights
🧑 **Perfil etário:** distribuição uniforme entre 18 e 70 anos

👨 **Gênero:** 60% dos clientes são masculinos

📍 **Localização:** New York lidera com 40% mais clientes que Los Angeles

👕 **Categoria:** Clothing lidera a receita com $266k

💳 **Pagamento:** Cartão de débito tem ticket médio 3x maior que Venmo ($178 vs $59)

## 🛠️ Tecnologias Utilizadas
- **Python**
- **Pandas**
- **Seaborn / Matplotlib**
- **Jupyter Notebook**

## 📁 Fonte dos Dados
Dataset: [Customer Shopping Behaviour Analysis](https://www.kaggle.com/datasets/ankitrajmishra/customer-shopping-behaviour-analysis)

## 🚀 Como Executar
1. Clone o repositório:
git clone https://github.com/seu-usuario/customer-shopping-eda.git

2. Instale as dependências:
pip install pandas seaborn matplotlib jupyter

3. Abra o notebook:
jupyter notebook aed.ipynb

## 📈 Análises Realizadas
- ✅ Limpeza e tratamento de dados
- ✅ Distribuição de idade e gênero
- ✅ Top 10 cidades com mais clientes
- ✅ Receita por categoria
- ✅ Ticket médio por método de pagamento
- ✅ Sazonalidade das vendas
- ✅ Top 10 produtos mais vendidos