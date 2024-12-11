# Análise de Dados de Qualidade de Vinho 🍷

**Objetivo:** Analisar um conjunto de dados de qualidade de vinho tinto (winequality-red.csv) usando a biblioteca pandas do Python para responder as seguintes perguntas:

1. O que representam os dados em cada coluna?
2. Quantas linhas há no dataset?
3. Quantas colunas há no dataset?
4. Quais os tipos de dados em cada coluna?
5. Há dados nulos (null, missing) na base de dados?

-----------
**📄 Informações sobre os dados:**

Os dados fornecidos incluem medidas de 11 variáveis físico-químicas que caracterizam cada amostra de vinho. Essas variáveis são:

1. **fixed acidity:** medida da acidez devido à presença de ácidos orgânicos de baixa volatilidade (ácido málico, lático, tartárico ou cítrico) no vinho.
2. **volatile acidity:** medida da acidez devido a ácidos de baixo peso molecular (sobretudo ácido acético) presentes no vinho, responsáveis pelo aroma e gosto de vinagre.
3. **citric acid:** medida de ácido cítrico no vinho.
4. **residual sugar:** medida de açúcar residual presente no vinho, com origem nos resíduos de açúcar da uva que permanecem no vinho após o fim da fermentação.
5. **chlorides:** medida de cloretos (íons de cloro) no vinho.
6. **free sulfur dioxide:** medida de dióxido de enxofre livre (isto é, que não está ligado a outras moléculas) no vinho.
7. **total sulfur dioxide:** medida de dióxido de enxofre total (livre + porção ligada a outras moléculas) no vinho.
8. **density:** medida da densidade do vinho.
9. **pH:** medida do pH do vinho.
10. **sulphates:** medida de sulfatos (íons SO₄²⁻) no vinho.
11. **alcohol:** medida da graduação alcoólica do vinho.
12. **quality:** score numérico de qualidade (de 0 a 10), produzido com base em dados sensoriais.

-------------
**🕵️‍♂️ Problema a ser investigado:**

Será que é possível descrever a qualidade do vinho (variável "quality") usando as demais 11 variáveis físico-químicas?  A análise dos dados irá tentar responder a esta questão.
