# 🏡 Prevendo Valores de Casas em Boston

Este projeto foi desenvolvido para explorar e criar um modelo de **regressão linear múltipla**, utilizando dados do famoso conjunto de dados de **Boston Housing**. O objetivo principal é prever o **valor médio de casas** em uma determinada região com base em várias características socioeconômicas e ambientais. 🏘️📈

---

## 📝 Descrição do Projeto

A partir do conjunto de dados do Boston Housing, este projeto passa por etapas de análise exploratória, criação e treinamento de um modelo de regressão linear, e avaliação de sua performance. 

Os principais passos incluem:
1. **Análise exploratória dos dados** 🔍
2. **Preparação dos dados para o modelo** 🛠️
3. **Criação e treinamento do modelo de regressão linear** 🧮
4. **Avaliação do modelo** 📊

---

## 📂 Estrutura dos Dados

### Variáveis Importantes:
- **CRIM**: Taxa de criminalidade per capita.
- **ZN**: Proporção de terrenos residenciais para lotes maiores que 25.000 pés quadrados.
- **INDUS**: Proporção de acres comerciais não varejistas por cidade.
- **CHAS**: Variável fictícia de proximidade ao rio Charles (1 se próximo, 0 caso contrário).
- **RM**: Número médio de quartos por residência.
- **AGE**: Proporção de unidades ocupadas por proprietários construídas antes de 1940.
- **MEDV**: Valor médio das casas (variável alvo).

---

## 📂 Etapas de Desenvolvimento

### 1️⃣ Análise Exploratória
- Inspeção das estatísticas descritivas.
- Criação de gráficos como **histogramas** e **gráficos de dispersão** para identificar padrões e relações entre variáveis.

### 2️⃣ Pré-processamento dos Dados
- Verificação de valores ausentes e tratamento de outliers.
- Padronização das variáveis para melhor desempenho do modelo.

### 3️⃣ Criação do Modelo
O modelo foi criado utilizando **regressão linear múltipla** da biblioteca **Scikit-learn** com a fórmula básica:

> Y = β<sub>0</sub> + β<sub>1</sub>X<sub>1</sub> + β<sub>2</sub>X<sub>2</sub> + ... + β<sub>n</sub>X<sub>n</sub>

Onde:
- \( Y \): Valor médio da casa (**MEDV**)
- \( X<sub>1</sub>, X<sub>2</sub>, ..., X<sub>n</sub> \): Variáveis preditoras
- β<sub>0</sub>, β<sub>1</sub>, ..., β<sub>n</sub>: Coeficientes do modelo

### 4️⃣ Treinamento e Avaliação
- **Métricas utilizadas**: R², MSE (Erro Quadrático Médio) e MAE (Erro Médio Absoluto).
- Avaliação do modelo em dados de teste para verificar sua capacidade preditiva.

---

## 🧰 Tecnologias Utilizadas

- **Python** 🐍
- **Pandas** para manipulação de dados
- **Matplotlib** e **Seaborn** para visualização
- **Scikit-learn** para modelagem e avaliação

---

## 📈 Resultados Obtidos

- O modelo ajustou-se adequadamente aos dados de treinamento, explicando uma proporção significativa da variação no valor das casas.
- As métricas de avaliação indicaram bom desempenho, com erros dentro de margens aceitáveis.

---

## 🤝 Contribuições

Sinta-se à vontade para explorar, melhorar e sugerir alterações neste projeto! Clone o repositório e experimente. 😄

---

## 🛡️ Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE](../../LICENSE) para mais detalhes.
