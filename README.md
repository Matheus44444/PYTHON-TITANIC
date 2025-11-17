# 🚢 Projeto: Análise de Sobrevivência no Titanic

Este projeto foca na Análise Exploratória de Dados (EDA) do clássico dataset do Titanic, buscando entender os fatores que influenciaram a sobrevivência dos passageiros.

## 🎯 Objetivo

O objetivo principal é visualizar e quantificar a relação entre variáveis categóricas (como classe, sexo e porto de embarque) e a variável alvo (`Survived`), utilizando gráficos estatísticos para extrair *insights* de forma clara.

## 🛠️ Tecnologias e Técnicas de Destaque

| Categoria | Técnica | Descrição |
| :--- | :--- | :--- |
| **Visualização** | **Gráficos de Contagem (`seaborn.catplot`)** | Utilização de gráficos de barras agrupadas para comparar a contagem de sobreviventes e não-sobreviventes em diferentes categorias (ex: por Classe e Porto de Embarque). |
| **Visualização** | **Configuração de Estilo** | Uso de `matplotlib` para ajustar títulos e *layouts* dos gráficos, garantindo uma apresentação profissional e informativa. |
| **Aquisição de Dados** | **Carregamento Direto** | Demonstração da prática de carregar o dataset diretamente de uma URL pública (do repositório do Seaborn), garantindo a reprodutibilidade. |
| **Análise Categórica** | **Variáveis de Fator** | Análise de como fatores como `sex` (sexo) e `class` (classe de viagem) foram os principais preditores de sobrevivência. |

## 📂 Estrutura do Projeto

O projeto é contido no notebook `titanicimports.ipynb`.

## 🚀 Como Executar

1.  **Instale as dependências:**
    ```bash
    pip install pandas numpy seaborn matplotlib
    ```
2.  Abra o notebook `titanicimports.ipynb` e execute as células sequencialmente. O notebook carrega os dados automaticamente da internet.

## 📈 Resultados Chave

A análise visual confirma que o **sexo** e a **classe de viagem** foram os fatores mais determinantes para a sobrevivência, seguindo a regra de "Mulheres e Crianças Primeiro" e a prioridade dada às classes mais altas.

---
*Autor: Manus AI*
*Notebook: titanicimports.ipynb*
