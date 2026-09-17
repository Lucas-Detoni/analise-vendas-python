📊 Análise de Vendas — Categoria, Vendedor, Região e Desconto

Projeto de análise exploratória de dados (EDA) usando Python, com o objetivo de identificar padrões de desempenho comercial e avaliar o impacto de descontos no volume de vendas.

🎯 Objetivo

Analisar uma base de 1.000 registros de vendas para responder perguntas de negócio como:

Quais categorias de produto vendem mais, em volume e em receita?
Quais vendedores têm melhor desempenho — e o que muda quando olhamos "ticket médio" em vez de receita total?
Quais regiões geram mais receita?
Descontos maiores realmente aumentam o volume de vendas?
🛠️ Ferramentas utilizadas
Python
pandas — manipulação e agregação de dados
matplotlib — visualização de dados
Google Colab — ambiente de desenvolvimento
📁 Estrutura do repositório
├── analise_vendas.ipynb    # Notebook com a análise completa
├── sales_data.csv          # Dataset utilizado
└── README.md
🔍 Principais achados
Categoria de produto: Clothing foi a categoria líder tanto em volume (6.922 unidades) quanto em receita (R$ 1.313.474,36), seguida por Furniture, Electronics e Food.
Desempenho por vendedor: David teve a maior receita total (R$ 1.141.737,36) e o maior número de vendas (222 transações). Porém, ao analisar o ticket médio (receita média por venda), Bob liderou com R$ 5.197,07 — mostrando que ele fecha vendas de maior valor, mesmo vendendo com menos frequência que David.
Desempenho por região: a região North concentrou a maior receita (R$ 1.369.612,51), à frente de East, West e South.
Impacto do desconto nas vendas: a correlação entre desconto e quantidade vendida foi praticamente nula (-0,008), e a quantidade média vendida se manteve estável entre as faixas de 0–10%, 10–20% e 20–30% de desconto. Isso sugere que, neste conjunto de dados, descontos maiores não geraram aumento de volume de vendas, podendo indicar perda de margem sem retorno proporcional.
💡 Recomendação de negócio

Revisar a política de descontos, já que ela não parece influenciar o volume de vendas nesta base — o esforço promocional talvez traga mais retorno se direcionado a ações de marketing ou expansão de vendedores com maior ticket médio, como o padrão observado em Bob.

🚀 Como reproduzir
Clone este repositório ou baixe os arquivos
Abra o analise_vendas.ipynb no Google Colab ou Jupyter Notebook
Faça upload do sales_data.csv quando solicitado
Execute as células em ordem (Runtime → Run all)


👤 Autor:

Lucas Detoni — Estudante de Análise e Desenvolvimento de Sistemas (ADS), com interesse em carreira na área de dados.
