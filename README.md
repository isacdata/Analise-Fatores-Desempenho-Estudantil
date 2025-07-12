# 🎓 Student Performance Factors – Análise de Fatores que Influenciam Notas em Exames

Este projeto analisa dados fictícios sobre estudantes e investiga **quais fatores internos e externos impactam seu desempenho em exames**. Através de análise exploratória e regressão linear, buscamos entender como variáveis como tempo de estudo, renda, apoio familiar e dificuldades de aprendizagem se relacionam com a nota final.

---

## 🎯 Objetivo

> Identificar os fatores mais relevantes para o desempenho acadêmico de alunos, com foco interpretativo e estatístico, utilizando regressão linear.

---

## 📁 Dataset

- Arquivo: `StudentPerformanceFactors.csv`
- Total de registros: 6.607 estudantes
- Total de colunas: 20 atributos
- Atributo alvo (target): `Exam_Score`

Principais variáveis analisadas:

| Variável                   | Tipo                        |
|----------------------------|-----------------------------|
| `Hours_Studied`            | Quantitativa (horas)        |
| `Parental_Involvement`     | Categórica ordinal          |
| `Access_to_Resources`      | Categórica ordinal          |
| `Previous_Scores`          | Numérica contínua           |
| `Motivation_Level`         | Categórica ordinal          |
| `Family_Income`            | Categórica ordinal          |
| `School_Type`              | Categórica nominal          |
| `Learning_Disabilities`    | Binária                     |
| `Gender`                   | Categórica nominal          |

---

## 📊 Técnicas Utilizadas

- Análise descritiva com `pandas` e `seaborn`
- Visualizações de dispersão, correlação e boxplots
- Codificação categórica com `LabelEncoder`
- Regressão linear com `statsmodels`
- Interpretação de coeficientes e significância estatística
- Avaliação do modelo com R² (~0.32)

---

## 📂 Estrutura

```
student-performance-factors/
├── StudentPerformance.ipynb
├── StudentPerformanceFactors.csv
├── requirements.txt
└── README.md
```

---

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/student-performance-factors.git
cd student-performance-factors
```

2. Instale os pacotes:
```bash
pip install -r requirements.txt
```

3. Execute o notebook:
Abra `StudentPerformance.ipynb` em seu ambiente Jupyter

---

## 👤 Autor

Projeto desenvolvido por **Isac Vieira**, com foco em análise educacional, regressão e interpretação de dados.

---

## 📄 Licença

Disponível para fins educacionais e demonstrativos.
