Análise de Dados de Heróis
Este projeto é uma introdução à análise de dados com Python, explorando um dataset sobre heróis, suas características físicas, habilidades e aparições. É a minha primeira experiência com Python, por isso o projeto ainda está em um estágio inicial e em aprendizado.

Descrição do Projeto
O objetivo do projeto é explorar os dados e criar visualizações gráficas que facilitem a interpretação de informações como:

Distribuição dos heróis por editora (Marvel, DC, etc.).

Relação entre altura, peso e força dos heróis.

Evolução do número de personagens ao longo dos anos.

Distribuição de gêneros e outras características relevantes.

Tecnologias Utilizadas
Linguagem: Python

Bibliotecas:

pandas: Manipulação e limpeza de dados.
matplotlib e seaborn: Criação de gráficos estáticos.
plotly: Geração de gráficos interativos.
Funcionalidades
Gráficos estáticos com Matplotlib e Seaborn:

Gráfico de barras para distribuição por editora.
Gráfico de dispersão para altura e peso.
Boxplot para análise de alturas por gênero
Gráficos interativos com Plotly:

Comparação de força, altura e peso dos personagens.
Visualização 3D das características principais.
Análise da distribuição por editora e gênero.
Estrutura do Projeto
├── data/                    # Pasta para o dataset
│   └── heroes.csv
├── venv/                    # Ambiente virtual (ignorado no Git)
├── README.md                
├── requirements.txt         # Dependências do projeto
├── analise.py               # Código principal de análise
└── .gitignore               
Como Rodar o Projeto
Clone o repositório:

git clone https://github.com/seu-usuario/analise-heroes.git
cd analise-heroes
Crie o ambiente virtual e ative-o:

python -m venv venv
source venv/bin/activate     # Linux/Mac
venv\Scripts\activate        # Windows
Instale as dependências:

pip install -r requirements.txt
Adicionar o dataset:

Faça o download do dataset aqui
Coloque o arquivo heroes.csv no diretório data/ do projeto.
Execute o código:

python analise.py
Observação sobre o Dataset
O dataset foi obtido do repositório dariomalchiodi/superhero-datascience. Durante o desenvolvimento, o Kaggle estava fora do ar, e este dataset foi encontrado pesquisando por "heroes" no GitHub. Apenas o arquivo heroes.csv foi utilizado deste repositório.#   H e r o e s - a n a l i s e  
 