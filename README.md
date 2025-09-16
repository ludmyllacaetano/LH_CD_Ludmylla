# Desafio Cientista de Dados

## 📌 Contexto
Você foi alocado em um time da Indicium contratado por um estúdio de Hollywood chamado PProductions, e agora deve fazer uma análise em cima de um banco de dados cinematográfico para orientar **qual tipo de filme deve ser o próximo a ser desenvolvido**.

Lembre-se que há muito dinheiro envolvido, então a análise deve ser muito detalhada e levar em consideração o máximo de fatores possíveis.

## 🎯 Objetivo 
Desenvolver um **modelo de previsão de filmes** a partir do dataset `desafio_indicium_imdb.csv`, e determinar a nota do imdb de um filme a partir de suas características.

## 🚀 Como Instalar e Executar
1. Clone este repositório:
```bash
git clone https://github.com/ludmyllacaetano/LH_CD_Ludmylla.git
 ```
2. Acesse o diretório do projeto:
 ```bash
 cd LH_CD_Ludmylla
 ```
3. Crie e ative um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # Para Linux/macOS
venv\Scripts\activate  # Para Windows
```
4. Instale as dependências:
```bash
pip install -r requirements.txt
 ```
5. Use os scripts conforme a necessidade!

## Estrutura do Repositório
```bash
📂 LH_CD_Ludmylla  
│── 📜 [README.md](README.md)               # 📖 Documentação do projeto  
│── 📜 [requirements.txt](requirements.txt) # 📦 Pacotes e dependências  
├── 📜 [desafio_indicium_imdb.csv](desafio_indicium_imdb.csv) # 📊 Dados utilizados 
│── 📂 notebooks               # 📓 Jupyter Notebooks  
│   ├── 📜 [LH_CD_Ludmylla.ipynb](notebooks/LH_CD_Ludmylla.ipynb) # 📊 Análise exploratória dos dados e construção do modelo 
│── 📂 models                  # 🏗️ Modelos treinados  
│   ├── 📜 [LH_CD_Ludmylla.pkl](models/LH_CD_Ludmylla.pkl)    # 🎯 Modelo (.pkl)   
```

## 📝 Relatórios e Notebooks
**📊 [LH_CD_Ludmylla.ipynb](/notebooks/LH_CD_Ludmylla.ipynb)**
* Contém as análises realizadas no dataset
## 📦 Modelo treinado
**🏗️ [modelo_final](/models/LH_CD_Ludmylla.pkl)**
* Contém o modelo treinado para previsões futuras.
