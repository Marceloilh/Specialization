### 📖 Sobre o Repositório

Este repositório é um espaço de aprendizado prático e contínuo focado em **Machine Learning Tradicional** e **Fundamentos de Redes Neurais**.

O projeto é dividido em dois pilares principais:

1. **Aprendizado Clássico & Ciência de Dados:** Implementações baseadas no livro _"Machine Learning e Python: Um Guia Prático à Ciência de Dados"_ (1ª Ed.), cobrindo desde a manipulação fundamental de dados com NumPy e Pandas, análise exploratória (EDA) e visualização gráfica, até a aplicação de algoritmos de aprendizado supervisionado (Regressão, Classificação) e validação de modelos.
2. **Especialização em Redes Neurais (Do Zero):** Módulo complementar dedicado à construção manual de arquiteturas neurais em Python puro e NumPy. O foco é desenvolver a intuição geométrica e matemática por trás do _Forward Propagation_, cálculo do erro (_Cost Function_) e otimização por gradiente sem o uso de abordagens abstratas ou bibliotecas de alto nível.

Todo o ambiente de desenvolvimento é isolado e gerenciado via `uv`, garantindo reprodutibilidade, performance e organização de dependências.

Este repositório contém a implementação prática, códigos e exercícios baseados no livro **"Machine Learning e Python: Um Guia Prático à Ciência de Dados"** (_1ª Edição_), de **Rodrigo Barbosa de Santis** e **Tiago Silveira Gontijo**, além de projetos práticos e simulações de redes neurais desenvolvidas do zero durante a trilha de especialização.

O objetivo deste projeto é construir e consolidar uma base sólida nos algoritmos e metodologias clássicas de Machine Learning (Aprendizado Tradicional) e Engenharia de IA utilizando Python.

---

## 🎯 Objetivos de Aprendizado

- Compreender o ciclo de vida completo de um projeto de Machine Learning.
- Praticar o pré-processamento de dados e análise exploratória (EDA).
- Implementar e comparar algoritmos de **Aprendizado Superviscionado** (Classificação e Regressão) e **Não Superviscionado**.
- Construir e entender o funcionamento interno de **Redes Neurais** (Forward Propagation, Loss Functions e Gradientes) codificadas do zero.
- Aplicar métricas adequadas para avaliação e validação de modelos (_Cross-Validation_, _Grid Search_, etc.).

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Linguagem:** Python 3.x
- **Gerenciador de Ambientes:** `uv` / `venv`
- **Análise e Manipulação de Dados:** `pandas`, `numpy`
- **Visualização de Dados:** `matplotlib`, `seaborn`
- **Machine Learning & Modelagem:** `scikit-learn`
- **Ambientes de Desenvolvimento:** Jupyter Notebook / VS Code

---

## 📂 Estrutura do Repositório

```text
.
├── data/                                    # Conjuntos de dados utilizados nos capítulos e simulações
├── notebooks/                               # Notebooks organizados pelos capítulos do livro
│   ├── 02_comandos_basicos_python.ipynb     # Cap 2: Entrada/Saída, Listas, Strings, Controle, Classes
│   ├── 03_numpy.ipynb                       # Cap 3: Arrays, Inicialização, Operações e Métodos
│   ├── 04_analise_exploratoria_dados.ipynb  # Cap 4: Leitura de arquivos e Gráficos (EDA)
│   └── 05_aprendizado_supervisionado.ipynb  # Cap 5: Split Treino/Teste, Modelo Linear e Classificadores
├── notebooks_especialização_network_Neural/ # Módulo prático de Redes Neurais e Deep Learning
│   ├── 01_forward_propagation_from_scratch.ipynb
│   └── 02_cost_function_and_gradients.ipynb
├── src/                                     # Scripts Python reutilizáveis e módulos auxiliares
├── .gitignore                               # Arquivos e pastas ignorados pelo Git
├── pyproject.toml                           # Configuração do ambiente e dependências (uv)
└── README.md                                # Documentação do repositório
```
