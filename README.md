# statistical_model

# Relatório do Projeto de Previsão de Vendas Semanais

## 1. Coleta de Dados

Os dados para este projeto foram fornecidos em um formato CSV e incluem informações de várias variáveis associadas às vendas semanais em diferentes lojas.

**Variáveis incluídas**:

- `Weekly_Sales`: Vendas semanais (variável alvo).
- `Holiday_Flag`: Indica se a semana inclui um feriado (1) ou não (0).
- `Temperature`: Temperatura média da semana (em Fahrenheit).
- `Fuel_Price`: Preço médio do combustível.
- `CPI`: Índice de Preços ao Consumidor.
- `Unemployment`: Taxa de desemprego.

## 2. Modelagem

### Pré-processamento de Dados

1. **Padronização**: Foi aplicado o método de padronização para a variável `Fuel_Price`, transformando-a com base em sua média e desvio padrão.
2. **Divisão dos Dados**: Os dados foram divididos em conjuntos de treino e teste com uma proporção de 75% para treino e 25% para teste.

### Treinamento do Modelo

Foi utilizado um modelo de regressão linear, o que permitiu prever `Weekly_Sales` com base nas variáveis independentes mencionadas. A métrica de avaliação foi o **Root Mean Squared Error (RMSE)**, que permite medir a precisão da previsão
**Resultados**:

- **RMSE**: Indica o erro médio das previsões. Um RMSE mais baixo indica um modelo mais preciso.

## 3. Conclusões

O modelo mostrou-se capaz de capturar parcialmente as tendências das vendas semanais.Sugestões para melhorar o modelo incluem:

- **Adicionar novas variáveis**: Outras variáveis sazonais ou econômicas podem aumentar a precisão.
- **Experimentar outros algoritmos**: Modelos mais complexos, como Regressão Ridge, ou até mesmo redes neurais, podem ser testados.
- **Análise de sazonalidade**: Incorporar variáveis relacionadas a sazonalidade pode aprimorar o desempenho preditivo.

---

