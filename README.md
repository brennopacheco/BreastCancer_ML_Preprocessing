# 🏥 BreastCancer_ML_Preprocessing

📊 **Pré-processamento do conjunto de dados Wisconsin Diagnostic Breast Cancer (WDBC) para Aprendizado de Máquina.**  
Este repositório contém as etapas de preparação e análise dos dados, garantindo que possam ser utilizados em modelos de **Machine Learning** para diagnóstico de câncer de mama.

---

## 📀 **1. Descrição do Projeto**
Este projeto tem como objetivo **limpar, transformar e analisar** os dados do conjunto **WDBC** para melhorar a eficiência de modelos preditivos.  
As principais etapas de pré-processamento incluem:

✅ **Conversão de classes** (`M` → `1`, `B` → `0`).  
✅ **Remoção da coluna `id`**, eliminando dados irrelevantes.  
✅ **Análise exploratória e visualização dos dados**.  
✅ **Normalização e divisão do dataset para treino e teste**.  
✅ **Geração de matriz de correlação** para entender as relações entre atributos.  

---

## 📂 **2. Estrutura do Repositório**
```
📺 BreastCancer_ML_Preprocessing
│── 📄 README.md            # Descrição do projeto
│── 📄 requirements.txt      # Bibliotecas necessárias
│── 📄 wdbc.data             # Dataset original
│── 📄 wdbc_pre              # Dataset pré-processado
│── 📄 wdbc_normalizacao     # Dataset após normalização
│── 📄 correlations.png      # Matriz de correlação gerada
│── 📁 notebooks             # Notebooks Jupyter usados na análise
│   ├── pre_processamento.ipynb  # Notebook com código de pré-processamento
│── 📁 scripts               # Scripts Python para automação
│   ├── preprocess.py        # Código de pré-processamento
│   ├── correlation_analysis.py  # Código para matriz de correlação
```

---

## 🚀 **3. Como Executar**
### 👅 **1. Clone o Repositório**
```bash
git clone https://github.com/seu-usuario/BreastCancer_ML_Preprocessing.git
cd BreastCancer_ML_Preprocessing
```

### 📦 **2. Instale as Dependências**
```bash
pip install -r requirements.txt
```

### 🏃 **3. Execute os Scripts**
- Para pré-processar os dados:
  ```bash
  python scripts/preprocess.py
  ```
- Para gerar a matriz de correlação:
  ```bash
  python scripts/correlation_analysis.py
  ```

---

## 📊 **4. Dataset Utilizado**
O conjunto de dados **Wisconsin Diagnostic Breast Cancer (WDBC)** é um dataset público contendo características extraídas de imagens de células mamárias para classificação entre **tumores benignos e malignos**.  
📀 Fonte: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

**📝 Características do Dataset:**
- **569 amostras** e **32 colunas** (1 ID, 1 diagnóstico, 30 atributos numéricos).
- Atributos incluem **raio, textura, perímetro, área, suavidade, concavidade**, entre outros.

---

## 📈 **5. Resultados da Análise**
### 💡 **Distribuição das Classes**
- **357 amostras Benignas (63%)**
- **212 amostras Malignas (37%)**

### 💡 **Correlação entre Atributos**
Foi gerada uma **matriz de correlação** para entender a relação entre os 30 atributos.  
📀 **Observação:** Algumas características possuem **alta correlação**, o que pode indicar **redundância** e necessidade de redução de dimensionalidade.

🖼️ **Imagem da Matriz de Correlação**:
![Image](https://github.com/user-attachments/assets/3f1f8105-39a4-4485-8a08-282523229776)

---

## 🛠 **6. Tecnologias Utilizadas**
📀 **Linguagem**: Python 3.12  
📀 **Bibliotecas**:  
- `pandas` → Manipulação de dados  
- `numpy` → Cálculos matemáticos  
- `matplotlib` / `seaborn` → Visualizações  
- `sklearn` → Machine Learning  
- `dtale` → Análise exploratória interativa  

---

## 🔖 **7. Próximos Passos**
- Implementação de modelos de **Machine Learning** (MLP, Random Forest, SVM).
- Redução de dimensionalidade com **PCA**.
- Avaliação de diferentes técnicas de normalização.

---

## 👥 **8. Contribuições**
Quer contribuir com melhorias ou sugestões?  
📀 **Fork o repositório**, crie uma branch e abra um **Pull Request**!

---

## 🐝 **9. Licença**
Este projeto está sob a licença **MIT**.  
