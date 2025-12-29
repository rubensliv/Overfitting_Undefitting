# Classificação com Balanceamento de Classes (UnderSampling e OverSampling)

Este projeto demonstra, de forma **didática e prática**, como lidar com **bases de dados desbalanceadas** em problemas de **classificação supervisionada**, utilizando técnicas de **UnderSampling** e **OverSampling**, além da comparação de métricas de desempenho.

O código foi desenvolvido com foco educacional, sendo ideal para disciplinas de **Machine Learning**, **Ciência de Dados** e **Estatística Aplicada**.

---

## 📌 Objetivos do Projeto

- Demonstrar o impacto do **desbalanceamento de classes** em modelos de classificação
- Aplicar técnicas de:
  - **UnderSampling**
  - **OverSampling**
- Treinar e comparar modelos antes e depois do balanceamento
- Avaliar os modelos utilizando métricas adequadas

---

## 🧠 Conceitos Trabalhados

- Classificação supervisionada
- Divisão de dados em treino e teste
- Balanceamento de classes
- Avaliação de modelos preditivos
- Métricas de erro e desempenho

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.x**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**
- **Pillow (PIL)**

As dependências estão listadas no arquivo `requirements.txt`.

---

## 📂 Estrutura do Projeto

├── UnderOver.ipynb # Notebook com todo o experimento

├── requirements.txt # Dependências do projeto

└── README.md # Documentação do projeto

## ▶️ Como Executar o Projeto

### 1️⃣ Criar um ambiente virtual (opcional, mas recomendado)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

📊 Fluxo do Experimento

Carregamento e inspeção dos dados

Separação em conjunto de treino e teste

Treinamento do modelo sem balanceamento

Avaliação inicial do desempenho

Aplicação de técnicas de:

UnderSampling

OverSampling

Novo treinamento do modelo

Comparação das métricas obtidas

📈 Métricas Avaliadas

Erro Médio Percentual Absoluto (MAPE)

Outras métricas de classificação disponíveis no scikit-learn

⚠️ Observação: o foco não é apenas a métrica final, mas entender o comportamento do modelo frente ao desbalanceamento.
