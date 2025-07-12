# 🎓 Análise de Fatores de Desempenho Estudantil

Este projeto analisa dados simulados de desempenho escolar com o objetivo de entender como fatores internos e externos — como tempo de estudo, renda, motivação e histórico acadêmico — influenciam a nota final de estudantes. A análise combina estatística descritiva, visualização exploratória e modelagem preditiva via regressão linear.

---

## 🎯 Objetivo

Investigar, com apoio estatístico e interpretável, **quais variáveis influenciam o desempenho final de um estudante**, aplicando regressão linear e análise exploratória.

---

## 📁 Dataset

- Arquivo: `StudentPerformanceFactors.csv`
- Registros: 6.607 estudantes
- Atributo alvo: `Exam_Score`

Principais variáveis incluídas:
- `Hours_Studied`, `Previous_Scores`, `Parental_Involvement`, `Motivation_Level`
- `Access_to_Resources`, `Family_Income`, `School_Type`
- `Learning_Disabilities`, `Gender`

---

## 📊 Etapas da Análise

1. **Exploração inicial:** uso de gráficos (`seaborn`, `matplotlib`) para examinar padrões e distribuições
2. **Limpeza e codificação de dados:** aplicação de `LabelEncoder` para variáveis categóricas
3. **Construção do modelo:** regressão linear com `LinearRegression` da `sklearn`
4. **Avaliação da performance:** cálculo de MSE, MAE, RMSE e R²

---

## 📈 Resultados da Modelagem

- **Erro quadrático médio (MSE):** 3.24  
- **Erro médio absoluto (MAE):** 0.44  
- **Raiz do erro quadrático médio (RMSE):** 1.80  
- **Coeficiente de determinação (R²):** 0.77

Estes valores indicam que o modelo tem boa capacidade de explicação da nota final, com erros moderados e um R² robusto.

---

## 🧠 Insights Relevantes

- Estudantes com **maior tempo de estudo e histórico escolar forte** tiveram melhores notas
- Fatores como **motivação, envolvimento parental e acesso a recursos** contribuíram positivamente
- **Dificuldades de aprendizagem** e **baixa renda familiar** apresentaram relação negativa

---

## 📂 Estrutura

```
analise-fatores-desempenho-estudantil/
├── StudentPerformance.ipynb
├── StudentPerformanceFactors.csv
├── requirements.txt
└── README.md
```

---

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/analise-fatores-desempenho-estudantil.git
cd analise-fatores-desempenho-estudantil
```

2. Instale os pacotes:
```bash
pip install -r requirements.txt
```

3. Execute o notebook:
Abra `StudentPerformance.ipynb` no Jupyter

---

## 👤 Autor

Projeto desenvolvido por **Isac Vieira**, com foco em estatística aplicada à educação e análise interpretável.

---

## 📄 Licença

Uso educacional e demonstrativo. Dados simulados e sem associação real.

