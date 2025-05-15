# 📶 Qual é o Melhor Plano? Análise dos Planos Surf e Ultimate da Megaline

## 📋 Descrição do Projeto

A Megaline, empresa de telecomunicações, oferece dois planos pré-pagos: **Surf** e **Ultimate**. O departamento comercial deseja saber qual plano gera mais receita para otimizar os investimentos em publicidade.

Como analista de dados, **avaliei o comportamento de 500 clientes** e **identifiquei qual dos planos oferece maior rentabilidade** com base nos dados de uso de 2018 (chamadas, mensagens e internet).

---

## 🎯 Objetivo

📊 **Determinar qual plano (Surf ou Ultimate) gera mais receita** para a empresa, com base na análise de comportamento dos clientes e testes estatísticos.

---

## 🧪 Hipóteses Avaliadas

- Existe diferença significativa no comportamento dos usuários entre os planos?
- Um dos planos gera sistematicamente mais receita?
- Existe diferença de uso por localização geográfica?

---

## 🛠️ Etapas do Projeto

1. **Exploração dos Dados:**  
   Análise inicial dos dados de 500 clientes — plano utilizado, chamadas, mensagens e uso de dados.

2. **Limpeza e Pré-processamento:**  
   - Remoção de valores ausentes  
   - Tratamento de tipos de dados  
   - Verificação e eliminação de duplicatas

3. **Integração dos Dados:**  
   Combinação de tabelas relacionadas para análise unificada.

4. **Análise Exploratória (EDA):**  
   Visualização e estatísticas para entender o comportamento dos clientes por plano.

5. **Testes Estatísticos:**  
   Aplicação de testes para verificar se as diferenças de receita entre os planos são estatisticamente significativas.

---

## 📈 Principais Ferramentas

- `pandas`  
- `matplotlib` / `seaborn`  
- `scipy.stats`  
- `numpy`  
- Jupyter Notebook

---

## 📊 Resultado Esperado

Identificar com **embasamento estatístico** qual plano é mais lucrativo, orientando decisões estratégicas de **marketing e orçamento**.

---

## 📁 Estrutura do Projeto
├── 📘 README.md

├── 📓 plano-megaline.ipynb

├── 📊 data/

   │ ├── users.csv

   │ ├── calls.csv

   │ ├── messages.csv
   
   │ └── internet.csv
