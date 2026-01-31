# 📦 Previsão de Estoque Inteligente com AWS SageMaker Canvas

## 📌 Visão Geral
Este projeto faz parte do desafio prático da **Digital Innovation One (DIO)** e tem como objetivo demonstrar a aplicação de **Machine Learning no-code** utilizando o **Amazon SageMaker Canvas** para a **previsão inteligente de estoque**, apoiando a tomada de decisão em cenários reais de negócios.

O projeto foi estruturado com foco em **clareza de processo**, **análise de dados** e **interpretação de resultados**, priorizando boas práticas de documentação para fins de portfólio profissional.

---

## 🎯 Objetivo do Projeto
Desenvolver um modelo de Machine Learning capaz de:
- Analisar dados históricos de estoque
- Identificar padrões de consumo e demanda
- Gerar previsões futuras de estoque
- Apoiar decisões estratégicas como reposição, redução de perdas e planejamento logístico

Tudo isso utilizando o **Amazon SageMaker Canvas**, sem necessidade de programação.

---

## 🛠️ Tecnologias e Ferramentas
- **Amazon Web Services (AWS)**
- **Amazon SageMaker Canvas**
- **Machine Learning No-Code**
- **GitHub para versionamento e documentação**
- **Dataset em formato CSV**

---

## 📂 Dataset Utilizado
O dataset utilizado está disponível na pasta `datasets` deste repositório, conforme fornecido no repositório base da DIO.

### Características gerais dos dados:
- Dados históricos de estoque
- Informações relacionadas à demanda e movimentação de produtos
- Estrutura compatível com modelos de previsão temporal

### Etapas realizadas com os dados:
1. Seleção do dataset mais adequado para previsão
2. Upload do arquivo CSV no SageMaker Canvas
3. Validação automática de tipos de dados
4. Análise exploratória inicial via interface do Canvas

---

## ⚙️ Construção e Treinamento do Modelo

O processo de criação do modelo seguiu as etapas abaixo dentro do SageMaker Canvas:

1. **Importação do Dataset**
   - Upload direto via interface
   - Verificação automática de inconsistências

2. **Definição da Variável Alvo**
   - Seleção da coluna relacionada ao estoque/demanda como target

3. **Configuração das Variáveis de Entrada**
   - Identificação automática das features relevantes
   - Tratamento interno de dados categóricos e numéricos

4. **Treinamento do Modelo**
   - Utilização do mecanismo automático do Canvas
   - Avaliação baseada em métricas internas da AWS

O SageMaker Canvas executa automaticamente a divisão entre dados de treino e validação, garantindo maior confiabilidade nos resultados.

---

## 📊 Análise de Performance do Modelo
Após o treinamento, foram analisados os seguintes aspectos:

- Métricas de desempenho apresentadas pelo Canvas
- Relevância das variáveis para o modelo
- Capacidade de generalização das previsões
- Comportamento do modelo frente a dados históricos

Essas análises permitem entender **como e por que o modelo gera determinadas previsões**, indo além do simples resultado numérico.

---

## 🔮 Exemplos de Avaliações e Previsões Realizadas

Com o modelo treinado, foi possível avaliar diferentes cenários de negócio. Abaixo estão **5 exemplos práticos de análises realizadas**:

### 1️⃣ Previsão de Demanda Futura
O modelo foi utilizado para prever a demanda de produtos em períodos futuros, auxiliando no planejamento antecipado de reposição de estoque.

### 2️⃣ Identificação de Picos de Consumo
A análise permitiu identificar períodos com maior volume de saída de produtos, indicando sazonalidade ou aumento pontual de demanda.

### 3️⃣ Risco de Ruptura de Estoque
Com base nas previsões, foi possível identificar cenários onde o estoque projetado não seria suficiente para atender a demanda futura.

### 4️⃣ Excesso de Estoque
O modelo também indicou situações onde a reposição poderia gerar acúmulo excessivo, ajudando a evitar custos desnecessários de armazenamento.

### 5️⃣ Impacto de Variáveis no Resultado
A análise das features revelou quais variáveis mais influenciam a previsão de estoque, como histórico de vendas e variações temporais.

---

## 🧠 Insights Obtidos
- Modelos preditivos são ferramentas estratégicas para gestão de estoque
- O SageMaker Canvas reduz significativamente a barreira técnica para uso de ML
- A análise correta das previsões é tão importante quanto o modelo em si
- Previsões bem interpretadas podem gerar economia e eficiência operacional

---

## ✅ Conclusão
Este projeto demonstrou, de forma prática, como é possível aplicar Machine Learning em problemas reais de negócio utilizando ferramentas no-code.

O Amazon SageMaker Canvas mostrou-se uma solução eficiente para:
- Criação rápida de modelos preditivos
- Análise de dados sem programação
- Apoio à tomada de decisão baseada em dados

Este projeto contribui para o desenvolvimento de competências em **Data Analysis**, **Machine Learning aplicado a negócios** e **documentação técnica**, sendo uma adição relevante ao portfólio profissional.

---

## 🔗 Repositório Base
Projeto desenvolvido a partir do repositório oficial da DIO:  
https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque

