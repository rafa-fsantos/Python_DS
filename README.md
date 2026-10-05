# 🐍 Estudos: Python para Ciência de Dados - Yuri Vasiliev

Repositório dedicado ao acompanhamento prático, anotações conceituais, exercícios e projetos desenvolvidos ao longo do estudo do livro **Python para Ciência de Dados - Uma Introdução Prática**, de autoria de Yuri Vasiliev (Novatec Editora).

## 🎯 Objetivos de Aprendizado

- Dominar as estruturas fundamentais e a sintaxe de Python aplicada a pipelines analíticos.
- Realizar manipulação, transformação e limpeza de dados utilizando bibliotecas padrão e ecossistema científico.
- Aplicar computação matricial e vetorizada eficiente.
- Construir visualizações gráficas explicativas e exploratórias de alto impacto.
- Implemetar modelos básicos de aprendizado de máquina para classificação, regressão e agrupamento.


## 📁 Estrutura do Repositório

```plaintext
├── notebooks/              # Jupyter Notebooks organizados por módulos temáticos
│   ├── 01_fundamentos/     # Tipos nativos, estruturas de controle e funções
│   ├── 02_numpy/           # Vetores, matrizes e computação numérica
│   ├── 03_pandas/          # Séries, DataFrames, agregação e mesclagem
│   ├── 04_visualizacao/    # Gráficos com Matplotlib e Seaborn
│   └── 05_machine_learning/# Modelos preditivos e métricas com scikit-learn
├── data/                   # Conjuntos de dados utilizados nos estudos
│   ├── raw/                # Dados brutos originais
│   └── processed/          # Dados tratados e prontos para modelagem
├── src/                    # Módulos Python (.py) e funções utilitárias reutilizáveis
├── notes/                  # Resumos teóricos, insights e anotações conceituais
├── .gitignore              # Arquivos e diretórios ignorados pelo Git
├── requirements.txt        # Especificação das dependências e versões
└── README.md               # Documentação principal do repositório
```

## 🛠️ Tecnologias e Dependências

- **Linguagem:** Python 3.14+
- **Bibliotecas Centrais:**
  - `numpy`: Vetorização e operações numéricas de alta performance.
  - `pandas`: Estruturas tabulares (Series e DataFrames) e manipulação analítica.
  - `matplotlib`: Criação e customização detalhada de gráficos.
  - `seaborn`: Visualização estatísticas e paletas visuais integradas ao **Pandas**.
- **Ambiente de Trabalho:** Jupyter Lab / VS Code.


## 🚀 Como Executar o Projeto Localmente

### 1. Clonar o repositório
```Bash
git clone https://github.com/rafa-fsantos/Python_DS.git
cd Python_DS
```
### 2. Criar e ativar o ambiente virtual
 
No Linux ou macOS:
 ```Bash
python3 -m venv. venv
source .venv/bin/activate
```

No Windows (PowerShell):

```Bash 
python -m venv .venv
.venv\Scripts\Activate.ps1
```

### 3. Instalar as dependências 

```Bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Abrir o ambiente de desenvolvimento

```Bash
jupyter lab
```

## 📋Checklist de Progresso do Livro

- [ ] Capítulo 01 - Bla




## 📚 Referência Bibliográfica

- **Livro:** Python para Ciência de Dados - Uma Introdução Prática.
- **Autor:** Yuli Vasiliev.
- **Editora:** Novatec Editora (2023).
## 📄 Licença

Este projeto é desenvolvido para fins estritamente acadêmicos e de estudo pessoal. O código autoral deste repositório está sob licença [MIT](LICENSE).