# Análise de Fatores no Conjunto de Dados Iris

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Latest-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Latest-013243?style=for-the-badge&logo=numpy)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Latest-F7931E?style=for-the-badge&logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)

Análise estatística e de machine learning do conjunto de dados Iris utilizando técnicas de redução de dimensionalidade, detecção de outliers e clusterização.

[Sobre o Projeto](#sobre-o-projeto) •
[Funcionalidades](#funcionalidades) •
[Tecnologias](#tecnologias) •
[Instalação](#instalação) •
[Uso](#uso) •
[Resultados](#resultados) •
[Contribuir](#contribuindo)

</div>

---

## Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias](#tecnologias)
- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Metodologia](#metodologia)
- [Resultados](#resultados)
- [Visualizações](#visualizações)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Contato](#contato)

---

## Sobre o Projeto

Este projeto realiza uma análise completa do conjunto de dados **Iris**, um dos datasets mais famosos em machine learning. A análise explora padrões, estrutura dos dados e relações entre as características das flores utilizando técnicas estatísticas avançadas e algoritmos de aprendizado de máquina.

### Principais Características

- **Análise Exploratória** - Estatísticas descritivas e visualizações detalhadas
- **PCA (Principal Component Analysis)** - Redução de dimensionalidade e interpretação de variância
- **Detecção de Outliers** - Múltiplas técnicas (Boxplot, Tukey, DBSCAN)
- **Clusterização K-Means** - Agrupamento não supervisionado das espécies
- **Visualizações Interativas** - Gráficos profissionais com Matplotlib e Seaborn
- **Análise de Correlação** - Matriz de correlação entre variáveis
- **Comparação de Modelos** - Avaliação de diferentes abordagens de clustering

---

## Funcionalidades

### Análise Exploratória de Dados

- Carregamento e inspeção do dataset Iris
- Estatísticas descritivas completas
- Identificação de valores faltantes
- Análise de distribuição das variáveis
- Visualização das relações entre features

### Redução de Dimensionalidade

- Implementação de PCA (Principal Component Analysis)
- Análise de variância explicada
- Transformação de dados para 2D/3D
- Interpretação dos componentes principais
- Visualização do espaço transformado

### Detecção de Outliers

- **Método Boxplot** - Identificação visual de outliers
- **Método de Tukey** - Cálculo de limites IQR
- **DBSCAN** - Detecção baseada em densidade
- Análise comparativa dos métodos
- Marcação de observações atípicas

### Clusterização

- Implementação do algoritmo K-Means
- Determinação do número ideal de clusters
- Avaliação com Silhouette Score
- Comparação com classificação real
- Visualização dos clusters formados

---

## Tecnologias

| Tecnologia       | Versão | Descrição                       |
| ---------------- | ------ | ------------------------------- |
| **Python**       | 3.x    | Linguagem de programação        |
| **Pandas**       | Latest | Manipulação de dados            |
| **NumPy**        | Latest | Computação numérica             |
| **Matplotlib**   | Latest | Visualização de dados           |
| **Seaborn**      | Latest | Visualizações estatísticas      |
| **Scikit-learn** | Latest | Algoritmos de Machine Learning  |
| **Jupyter**      | Latest | Ambiente de notebook interativo |

---

## Instalação

### Pré-requisitos

- **Python 3.x** - [Download](https://www.python.org/downloads/)
- **Pip** - Gerenciador de pacotes Python
- **Jupyter Notebook** ou **JupyterLab** (opcional)

### Instalação das Dependências

#### 1. Clone o repositório

```bash
git clone https://github.com/nevesmarcos42/Analise-de-Fatores.git
cd Analise-de-Fatores
```

#### 2. Instale as bibliotecas necessárias

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Ou use o arquivo requirements.txt (se disponível):

```bash
pip install -r requirements.txt
```

#### 3. Inicie o Jupyter Notebook

```bash
jupyter notebook
```

O navegador abrirá automaticamente com a interface do Jupyter.

---

## Uso

### Executar a Análise

1. **Abra o notebook**: Clique em `Análise_de_fatores_no_conjunto_de_dados_Iris.ipynb`

2. **Execute as células**: Use `Shift + Enter` para executar cada célula sequencialmente

3. **Explore os resultados**: Visualize gráficos, tabelas e métricas geradas

### Estrutura do Notebook

O notebook está organizado nas seguintes seções:

1. **Importação de Bibliotecas** - Carregamento das dependências necessárias
2. **Carregamento dos Dados** - Leitura do dataset Iris
3. **Análise Exploratória** - Estatísticas e visualizações iniciais
4. **Análise de Correlação** - Matriz de correlação entre variáveis
5. **PCA** - Redução de dimensionalidade
6. **Detecção de Outliers** - Aplicação de múltiplas técnicas
7. **Clusterização K-Means** - Agrupamento não supervisionado
8. **Conclusões** - Resumo dos principais achados

---

## Estrutura do Projeto

```
Analise-de-Fatores/
├── Análise_de_fatores_no_conjunto_de_dados_Iris.ipynb
└── README.md
```

---

## Metodologia

### 1. Análise Exploratória

- Inspeção inicial dos dados (shape, tipos, valores faltantes)
- Estatísticas descritivas (média, mediana, desvio padrão)
- Visualizações de distribuição (histogramas, boxplots)
- Análise de correlação entre variáveis

### 2. PCA (Análise de Componentes Principais)

- Padronização dos dados
- Aplicação do PCA
- Análise de variância explicada
- Redução para 2 ou 3 componentes
- Interpretação dos componentes principais

### 3. Detecção de Outliers

- **Boxplot**: Identificação visual de valores extremos
- **Método de Tukey**: Cálculo de limites usando IQR (Interquartile Range)
- **DBSCAN**: Detecção baseada em densidade de pontos
- Comparação e análise dos outliers identificados

### 4. Clusterização K-Means

- Seleção do número de clusters (k=3)
- Treinamento do modelo K-Means
- Avaliação com Silhouette Score
- Comparação com a classificação real das espécies
- Visualização dos clusters no espaço 2D/3D

---

## Resultados

### PCA - Redução de Dimensionalidade

- ✅ Os primeiros 2 componentes principais explicam aproximadamente **95.8%** da variância total
- ✅ A redução de 4 para 2 dimensões preserva a maior parte da informação
- ✅ Visualização clara da separação entre as espécies no espaço transformado

### Detecção de Outliers

- ✅ **Boxplot**: Identificou observações com valores extremos em algumas features
- ✅ **Método de Tukey**: Detectou outliers baseados em limites IQR
- ✅ **DBSCAN**: Identificou pontos de baixa densidade como outliers
- ✅ Algumas observações foram consistentemente marcadas como atípicas

### Clusterização K-Means

- ✅ O K-Means formou 3 clusters correspondentes às espécies
- ✅ Alta concordância com a classificação real das espécies
- ✅ Algumas observações foram reclassificadas (casos de fronteira)
- ✅ Silhouette Score indica boa separação entre clusters

### Conclusões Principais

- O dataset Iris apresenta boa separabilidade entre as espécies
- A espécie _Setosa_ é claramente distinguível das outras duas
- _Versicolor_ e _Virginica_ apresentam alguma sobreposição
- PCA é eficaz para redução de dimensionalidade mantendo informação
- K-Means consegue agrupar as espécies com boa precisão

---

## Visualizações

O notebook inclui diversas visualizações profissionais:

- 📊 **Histogramas** - Distribuição de cada variável
- 📦 **Boxplots** - Identificação de outliers e quartis
- 🎯 **Scatter Plots** - Relações entre pares de variáveis
- 🔥 **Heatmap** - Matriz de correlação
- 🎨 **Pair Plot** - Visualização multidimensional
- 📈 **PCA Plots** - Componentes principais 2D/3D
- 🔵 **Cluster Plots** - Visualização dos grupos K-Means

---

## Contribuindo

Contribuições são bem-vindas! Siga os passos:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

### Ideias para Contribuições

- Adicionar outros algoritmos de clustering (DBSCAN completo, Hierarchical)
- Implementar validação cruzada
- Adicionar análise de discriminantes (LDA)
- Criar visualizações interativas com Plotly
- Adicionar testes estatísticos (ANOVA, t-test)
- Implementar outros métodos de detecção de outliers

---

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## Contato

**Marcos Neves**

- Email: nevesmarcos42@gmail.com
- LinkedIn: [linkedin.com/in/nevesmarcos](https://linkedin.com/in/nevesmarcos)
- GitHub: [@nevesmarcos42](https://github.com/nevesmarcos42)

---

Desenvolvido como projeto de estudo em Data Science e Machine Learning

---

**Versão**: 1.0.0

**Última Atualização**: Novembro 2024

---

⭐ Se você achou este projeto interessante, deixe uma estrela no repositório!
