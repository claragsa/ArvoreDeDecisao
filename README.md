# Diagnóstico Cancêr de Mama - Árvore de Decisão para Classificação
O projeto foi desenvolvido com o objetivo de entender melhor como funciona e para que serve o modelo de Machine Learning de árvore de decisão. 

### Dataset:
Foram utilizados os dados de diagnóstico de câncer de mama em Wisconsin do repositório de ML da UC Irvine.
Link: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

### Metadados:

1) ID number 2) Diagnosis (M = malignant, B = benign) 3-32)

Ten real-valued features are computed for each cell nucleus:
  a) radius (mean of distances from center to points on the perimeter)
  b) texture (standard deviation of gray-scale values)
  c) perimeter
  d) area
  e) smoothness (local variation in radius lengths)
  f) compactness (perimeter^2 / area - 1.0)
  g) concavity (severity of concave portions of the contour)
  h) concave points (number of concave portions of the contour)
  i) symmetry
  j) fractal dimension ("coastline approximation" - 1)

### Métricas do modelo
Para fazer a avaliação do modelo de classificação, foram utilizadas as métricas de acurácia, recall e precisão.
Assim, foram obtidos como resultados:
1. Acurácia: 95%
2. Recall: 93%
3. Precisão: 93%

Desse modo, é entendido que esse modelo tenha uma baixa variancia e um baixo viés, chegando ao trade off ideal, onde a acurácia e a precisão apresentam um alto nível, deixando uma margem pequena para erros sistemáticos.
Além disso, ter um recall alto é muito importante no contexto médico, visto que é essencial que se tenha uma preocupação maior em identificar casos de tumores malignos, já que falsos positivos (malignos classificados como benignos) são muito perigosos.
