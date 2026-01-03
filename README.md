# Teoria do Aprendizado Estatístico (Statistical Learning) - UFPR

Este repositório contém as listas de exercícios e avaliações desenvolvidas para a disciplina de Teoria do Aprendizado Estatístico. O foco central é o estudo de métodos para estimar funções $f(X)$ a partir de dados, balanceando o *trade-off* entre viés e variância para maximizar a capacidade preditiva.



## 🛠️ Conteúdo Técnico

Os trabalhos exploram o arsenal do livro *The Elements of Statistical Learning* (Hastie et al.) e *ISLR* (James et al.):

### 1. Seleção e Avaliação de Modelos (Listas e Avaliações)
* **Trade-off Viés-Variância:** Análise teórica e prática do comportamento dos erros de teste e treinamento.
* **Métodos de Reamostragem:** Implementação de Cross-Validation (K-Fold, LOOCV) e Bootstrap para estimar a precisão dos modelos.

### 2. Regressão e Regularização
* **Shrinkage Methods:** Aplicação de Regressão **Ridge** e **Lasso** para lidar com multicolinearidade e realizar seleção automática de variáveis em alta dimensão.
* **Dimension Reduction:** Regressão de Componentes Principais (PCR) e PLS.

### 3. Métodos Não Lineares e Árvores
* **Modelos Aditivos Generalizados (GAMs):** Flexibilização da linearidade.
* **Métodos Baseados em Árvores:** Árvores de Decisão, Bagging, Random Forests e Boosting para tarefas de classificação e regressão.
* **Support Vector Machines (SVM):** Classificação com margens máximas e *kernels*.

---

## 🚀 Tecnologias e Implementação

* **Linguagem:** R.
* **Pacotes Principais:** `glmnet` (Regularização), `randomForest`/`gbm` (Árvores), `boot` (Resampling).
* **Relatórios:** Análises reprodutíveis em R Markdown, combinando fundamentação matemática com resultados empíricos.

---

## 📂 Arquivos

* `TAE2` a `TAE4`: Listas de exercícios práticos cobrindo tópicos específicos da ementa.
* `TAEAV1` e `TAEAV2`: Avaliações completas (Provas/Trabalhos) consolidando o conhecimento de múltiplos módulos.

---
**Autor:** Luiz Henrique Barretta Francisco  
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*
