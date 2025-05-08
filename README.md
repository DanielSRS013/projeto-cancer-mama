# projeto-cancer-mama
🧠 Classificação de Tumores com Machine Learning usando Scikit-Learn. Projeto acadêmico que aplica Random Forest e SVM ao dataset Breast Cancer Wisconsin para prever se um tumor é benigno ou maligno.


## 📁 Estrutura do Projeto

O notebook segue as seguintes etapas:

1. **Importação de bibliotecas**
2. **Carregamento e visualização do dataset**
3. **Seleção de variáveis para análise**
4. **Visualizações exploratórias**
   - Gráfico de dispersão (`pairplot`)
   - Matriz de correlação com `heatmap`
5. **Pré-processamento**
   - Normalização com `MinMaxScaler`
6. **Divisão em treino e teste**
7. **Modelagem com algoritmos supervisionados:**
   - Random Forest
   - Support Vector Machine (SVM)
8. **Avaliação dos modelos**
   - Acurácia
   - Matriz de confusão
9. **Análise comparativa dos resultados**

---

## 🧠 Modelos Utilizados

### 🌲 Random Forest
- Acurácia: **93,7%**
- Forte desempenho na classificação correta de tumores
- Baixo número de falsos positivos/negativos

### ⚙️ SVM (Support Vector Machine)
- Acurácia: **90,9%**
- Classificador robusto, porém com desempenho ligeiramente inferior ao Random Forest

---

## 📊 Tecnologias e Bibliotecas

- Python 3
- `pandas`, `numpy` — manipulação de dados
- `matplotlib`, `seaborn` — visualização
- `scikit-learn` — machine learning:
  - `load_breast_cancer`
  - `train_test_split`
  - `MinMaxScaler`
  - `RandomForestClassifier`
  - `SVC`
  - `accuracy_score`, `confusion_matrix`

---

📌 Resultados
O modelo Random Forest apresentou melhor desempenho geral, com menor taxa de erro em comparação com o SVM. Isso demonstra sua eficácia em problemas de classificação com múltiplas variáveis correlacionadas.

--- 

👨‍🎓 Autor
Daniel Souza da Rocha Silva
Linkedin: https://www.linkedin.com/in/daniel-souza-8b94b4252/


## ▶️ Como Executar

Você pode rodar este notebook no [Google Colab](https://colab.research.google.com/) ou localmente com Jupyter Notebook.

### Executar localmente:

1. Clone este repositório:
```bash
git clone https://github.com/seuusuario/classificacao-tumores.git
cd classificacao-tumores

2. Instale os pacotes necessários:

pip install pandas matplotlib seaborn scikit-learn

3. Abra o Jupyter Notebook:

jupyter notebook

Execute o arquivo projeto-cancer-mama.ipynb
