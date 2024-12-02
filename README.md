# **Análise de Dados: Preços de Imóveis em São Paulo**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) 
![Plotly](https://img.shields.io/badge/Plotly-5.24.1-brightgreen)
![NumPy](https://img.shields.io/badge/NumPy-2.1.3-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.2.3-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.9.2-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.2-orange)
![Status](https://img.shields.io/badge/status-finalizado-orange)

## **Introdução**

Neste estudo, a meta é mergulhar fundo nas relações que existem entre as características físicas de um imóvel, como metragem e número de cômodos, com seu preço e localização. A ideia é entender, principalmente, o que está por trás dos preços dos imóveis de São Paulo, uma das metrópoles mais agitadas e desafiadoras do Brasil.

Os dados aqui analisados foram baixados da plataforma do **Kaggle**, bastante popular por suas competições de Machine Learning, e são provenientes de uma raspagem realizada no site do **Quinto Andar** em março de 2023.

---

## **Estrutura do Projeto**

Abaixo está a organização dos diretórios e arquivos do projeto:

- `data`               # Dados
  - `plotly-imgs/`        # Imagens geradas com Plotly para visualização no GitHub
  - `data.csv`            # Dataset
- `notebooks`
  - `preco-imoveis-sp.ipynb`  # Notebook principal do projeto
- `venv/`                   # Ambiente virtual (não incluído no repositório)
- `requirements.txt`        # Lista de dependências do projeto
- `.gitignore`              # Arquivos e pastas ignorados pelo Git

---

## **Pré-requisitos**

Certifique-se de ter as seguintes ferramentas instaladas:

- Python 3.8 ou superior
- Git
- Um ambiente virtual configurado (opcional, mas recomendado)

---

## **Configuração do Ambiente**

Siga os passos abaixo para configurar o ambiente do projeto:

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_REPOSITORIO>
2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # ou
   venv\Scripts\activate     # Windows
3. Instale as dependências listadas no requirements.txt::
   ```bash
   pip install -r requirements.txt
---

## **Análise e Visualização**

O que você encontrará no notebook:

O notebook `notebooks/preco-imoveis-sp.ipynb` inclui:

- **Análise exploratória dos dados (EDA)**: Visualizações que ajudam a entender os padrões dos imóveis em São Paulo.
- **Insights detalhados sobre como características físicas dos imóveis**, como número de cômodos e localização, afetam os preços.
- **Gráficos interativos criados com Plotly** para explorar os dados de forma dinâmica.

---

## **Visualizações com Plotly**

Para compatibilidade com o GitHub, todas as visualizações interativas geradas pelo Plotly foram salvas como imagens estáticas no diretório `data/plotly-imgs/`.

---

## **Fontes dos Dados**

Os dados utilizados foram obtidos na plataforma Kaggle, a partir de uma raspagem realizada no site Quinto Andar, em março de 2023.

---

## **Contribuições**

Contribuições são sempre bem-vindas! Se você deseja melhorar o projeto ou propor algo novo, siga os passos:

1. Faça um fork do repositório.
2. Crie uma branch para sua funcionalidade:
   ```bash
   git checkout -b nome-da-branch
3. Envie suas alterações:
    ```bash
    git push origin minha-nova-funcionalidade
4. Abra um Pull Request.
  
---

## **Contato**

Se você tiver dúvidas ou sugestões, entre em contato: [LinkedIn](https://www.linkedin.com/in/joao-holanda).
