# ATV3 - Regressão Linear Multivariada (Google Colab)

## 📌 Visão Geral
Implementação em Python de regressão linear multivariada comparando:
- **Gradiente Descendente** (GD)
- **Equação Normal** (NE)
com análise do impacto da normalização de features.

## 🔗 Acesso ao Projeto
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Fofli21-e1mzq6DJ-Q0Dh3j9OXdgPIfL?usp=sharing
)

## 📋 Principais Componentes
1. **Dataset**: Preços de imóveis (tamanho × quartos × preço)
2. **Pré-processamento**:
   - Normalização Z-score (`features_normalize_by_std`)
3. **Métodos Implementados**:
   - `gradient_descent_multi.py` (GD com histórico)
   - `normal_eqn.py` (solução analítica)
4. **Visualizações**:
   - Convergência do custo
   - Superfície 3D e curvas de nível
   - Plano de regressão ajustado


## 🛠 Como Utilizar
1. Acesse o notebook no Colab pelo link acima
2. Execute todas as células sequencialmente
3. Os gráficos serão gerados automaticamente na pasta `Figures/`

## 📚 Documentação Complementar
[Relatório Detalhado](https://docs.google.com/document/d/1T-ISaefc55AwssbvcC8cSEZALqLrgjqUoqU-rHb-nIc/edit)


Desenvolvido por Antonio Fialho da Silva Neto | Última atualização: OUT 2023
