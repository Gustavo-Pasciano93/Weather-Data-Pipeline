# 🌦️ Weather Data Pipeline

**Weather Data Pipeline** é um projeto de ETL (Extract, Transform, Load) que coleta dados climáticos em tempo real de diferentes cidades, transforma os dados em um formato estruturado e os armazena em um banco de dados MySQL. Este pipeline demonstra o uso de **Python**, **MongoDB**, **Pandas** e **MySQL** em um fluxo de trabalho de dados completo.

---

## 🗂️ Estrutura do Projeto

Weather Data Pipeline 
├── extract_and_save_data.py # Script para coletar dados da API e salvar no MongoDB 
├── transform_and_save.py # Script para transformar os dados e salvar em CSV 
├── save_mysql.py # Script para carregar os dados no MySQL 
├── tabela_clima.csv # Arquivo CSV gerado no pipeline 
└── README.md # Documentação do projeto



---

## 🚀 Funcionalidades

- **Extração de dados:** Coleta dados climáticos de cidades via API OpenWeather.
- **Transformação de dados:** Organiza os dados coletados em um formato tabular com o auxílio do Pandas.
- **Carga de dados:** Armazena os dados transformados em um banco de dados MySQL.

---

## 📋 Pré-requisitos

Certifique-se de ter instalado os seguintes itens antes de rodar o projeto:

- Python 3.10+
- MongoDB
- MySQL Server
- Bibliotecas Python:
  - `pandas`
  - `requests`
  - `pymongo`
  - `mysql-connector-python`

---

## 🛠️ Configuração

1. **Clone este repositório:**

   ```bash
   git clone https://github.com/seu-usuario/weather-data-pipeline.git
   cd weather-data-pipeline


2. **Configure a conexão MongoDB**
   Atualize a URI no script extract_and_save_data.py com suas credenciais MongoDB.

3.**Configure a conexão MySQL:**
   Atualize o host, usuário e senha no script save_mysql.py.




## 🏃‍♂️ Como Executar

1. **Extraia os dados da API para o MongoDB:**
   python extract_and_save_data.py

2. **Transforme os dados e salve em CSV:**
   python transform_and_save.py

3.**Carregue os dados no MySQL:**
    python save_mysql.py





## 📝 Notas

API OpenWeather: Certifique-se de substituir a API_KEY nos scripts pelos seus próprios valores.
Banco MySQL: O script cria automaticamente a tabela caso ela não exista





📧 Contato
Autor: Gustavo Pasciano
📩 E-mail: gpasciano@example.com
🔗 LinkedIn:https://www.linkedin.com/gustavo-pasciano/



