# Desafio Cientista de Dados

## 📌 Contexto
Você foi alocada em um time que está trabalhando atualmente junto a um cliente no processo de criação de uma plataforma de **aluguéis temporários na cidade de Nova York**. Para o desenvolvimento de sua estratégia de precificação, pediu-se que fizesse uma **análise exploratória dos dados** de seu maior concorrente, assim como um **teste de validação de um modelo preditivo**.

## 🎯 Objetivo 
Desenvolver um **modelo de previsão de preços** a partir do dataset `teste_indicium_precificacao.csv`, e avaliar tal modelo utilizando as **métricas de avaliação** que mais fazem sentido para o problema.

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
📂 projeto-cientista-dados  
│── 📜 [README.md](README.md)               # 📖 Documentação do projeto  
│── 📜 [requirements.txt](requirements.txt) # 📦 Pacotes e dependências  
│── 📂 data                    # 📊 Dados utilizados  
│   ├── 📜 raw/                # 🔹 Dados brutos  
│   ├── 📜 processed/          # 🔸 Dados tratados  
│── 📂 notebooks               # 📓 Jupyter Notebooks  
│   ├── 📜 [01-EDA.ipynb](notebooks/01-EDA.ipynb)        # 📊 Análise exploratória dos dados  
│   ├── 📜 [02-Modelagem.ipynb](notebooks/02-Modelagem.ipynb)  # 🤖 Construção e avaliação dos modelos  
│── 📂 reports                 # 📑 Relatórios das análises  
│   ├── 📜 [EDA-analise.pdf](reports/EDA-analise.pdf)     # 📋 Relatório em PDF da EDA  
│   ├── 📜 [Modelagem.pdf](reports/Modelagem.pdf)       # 📜 Relatório em PDF da modelagem  
│── 📂 models                  # 🏗️ Modelos treinados  
│   ├── 📜 [modelo_final.pkl](models/modelo_final.pkl)    # 🎯 Modelo serializado (.pkl)  
│── 📂 scripts                 # ⚙️ Scripts auxiliares  
│   ├── 📜 [preprocess.py](scripts/preprocess.py)       # 🔄 Funções para pré-processamento  
│   ├── 📜 [train.py](scripts/train.py)            # 🎯 Script para treinamento do modelo  
│   ├── 📜 [predict.py](scripts/predict.py)          # 🔍 Script para gerar previsões  
```

## 📝 Relatórios e Notebooks
**📊 [LH_CD_LudmyllaMartinsCaetano.ipynb](LH_CD_Ludmylla/notebooks/LH_CD_LudmyllaMartinsCaetano.ipynb)**
* Contém as análises realizadas no dataset
## 📦 Modelo treinado
**🏗️ [modelo_final](LH_CD_Ludmylla/models/modelo_final.pkl)**
* Contém o modelo treinado para previsões futuras.

<!--
## Apresentação em Vídeo
-->
