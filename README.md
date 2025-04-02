📊 Projeto de ETL e Visualização de Dados

📌 Descrição

Este repositório contém um projeto de ETL (Extração, Transformação e Carga de Dados) e visualização de dados, utilizando Python e PostgreSQL. Além disso, inclui uma apresentação em PowerPoint para demonstrar os insights obtidos.

📂 Estrutura do Repositório

Case_ETL.ipynb → Notebook responsável pelo processo de ETL, incluindo a extração de dados da API, transformação e carga no banco de dados PostgreSQL.

Case_dataviz.ipynb → Notebook dedicado à análise exploratória e visualização de dados, utilizando gráficos para interpretar os resultados.

Case Trainee.pptx → Slides explicativos com os principais insights obtidos a partir dos dados.

🛠️ Tecnologias Utilizadas

📌 Linguagem e Bibliotecas

Python 3.13

Requests → Para buscar dados de APIs.

Pandas → Manipulação e análise de dados.

JSON → Tratamento de arquivos e dados em formato JSON.

SQLAlchemy → Conexão com o PostgreSQL.

Matplotlib e Seaborn → Criação de gráficos e visualizações.

🗄️ Banco de Dados

PostgreSQL 17 → Armazenamento dos dados processados.

pgAdmin 4 → Gerenciamento do banco de dados PostgreSQL.

🖥️ Versionamento de Código

GitHub → Hospedagem e controle de versão do projeto.

🚀 Como Executar o Projeto

Clone o repositório:

git clone https://github.com/seu_usuario/nome_do_repositorio.git
cd nome_do_repositorio

Crie e ative um ambiente virtual:

python -m venv venv
source venv/bin/activate  # No Windows, use: venv\Scripts\activate

Instale as dependências:

pip install -r requirements.txt

Configure o banco de dados PostgreSQL no ETL.ipynb com suas credenciais.

Execute os notebooks Jupyter na ordem:

Primeiro: ETL.ipynb

Depois: Visualizacao_Dados.ipynb
