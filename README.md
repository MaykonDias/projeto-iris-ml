# 🌸 Classificação de Flores Iris - Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-008080?style=for-the-badge&logo=python&logoColor=white)

## 📌 Sobre o Projeto

Este projeto consiste em um modelo de **Machine Learning** para classificação de espécies de flores **Iris** (Setosa, Versicolor e Virginica) utilizando o algoritmo **Random Forest**.

O dataset Iris é um dos mais famosos da história do Machine Learning, criado pelo estatístico Ronald Fisher em 1936.

## 📊 Principais Insights

- **97%** de acurácia no conjunto de teste
- **29 acertos** em 30 amostras (apenas 1 erro)
- **Setosa** foi 100% identificada (espécie mais distinta)
- **Versicolor** e **Virginica** são mais parecidas (único erro ocorreu entre elas)

## 📈 Resultados por Espécie

| Espécie | Precisão | Recall | F1-Score | Amostras |
|---------|----------|--------|----------|----------|
| Setosa | 1.00 | 1.00 | 1.00 | 11 |
| Versicolor | 1.00 | 0.92 | 0.96 | 13 |
| Virginica | 0.86 | 1.00 | 0.92 | 6 |


## 🛠️ Tecnologias Utilizadas

| Biblioteca | Finalidade |
|------------|------------|
| Python | Linguagem principal |
| pandas | Manipulação de dados |
| numpy | Operações matemáticas |
| scikit-learn | Random Forest e métricas |
| matplotlib | Criação de gráficos |
| seaborn | Matriz de confusão |
| jupyter | Ambiente de notebook |

## 📁 Estrutura do Projeto
```
ML_iris/
├── README.md # Documentação do projeto
├── analysis.ipynb # Notebook principal com todo o código
└── data/
└── iris.csv # Dataset (150 amostras, 4 features)
```

## 🚀 Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/MaykonDias/projeto-iris-m.git
cd projeto-iris-m
```
### 2. Instale as dependências
```
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```
### 3. Execute o notebook
```
jupyter notebook analysis.ipynb
```



