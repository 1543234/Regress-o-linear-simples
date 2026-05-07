# 📊 Comparação de Performance — Statsmodels vs Scikit-Learn

O objetivo deste teste foi verificar se existe diferença prática nos resultados da regressão linear simples utilizando `Statsmodels` e `Scikit-Learn`.

Foi utilizado o mesmo dataset e as mesmas variáveis em ambas as bibliotecas.

---

# 🔍 Resultado dos modelos

| Métrica                         | Statsmodels | Scikit-Learn |
| ------------------------------- | ----------- | ------------ |
| R²                              | 0.957       | 0.957        |
| Coeficiente (`YearsExperience`) | 9449.96     | 9449.96      |
| Intercepto                      | 24850       | 24850        |
| Adjusted R²                     | 0.955       | 0.955        |
| Log-Likelihood                  | -301.44     | -301.44      |
| F-Statistic                     | 622.5       | 622.5        |
| Prob (F-Statistic)              | 1.14e-20    | 1.14e-20     |
| P-value                         | < 0.001     | < 0.001      |

---

# 🧠 Conclusão

Os dois modelos apresentaram  os mesmos resultados preditivos:

Ou seja, matematicamente os modelos chegaram  à mesma solução.

