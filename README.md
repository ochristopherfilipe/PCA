# PCA - Principal Component Analysis

PCA, que significa Análise de Componentes Principais (do inglês Principal Component Analysis), é uma técnica estatística utilizada na área de aprendizado de máquina para redução de dimensionalidade. O objetivo da redução de dimensionalidade é simplificar a representação de dados em conjuntos de dados de alta dimensionalidade, mantendo o máximo possível da variabilidade original.

Em termos simples, o PCA transforma um conjunto de variáveis correlacionadas em um novo conjunto de variáveis não correlacionadas, chamadas componentes principais. Esses componentes principais são ordenados por sua importância, de modo que o primeiro componente principal captura a maior variação nos dados, o segundo componente principal captura a segunda maior variação, e assim por diante.

## O processo de redução de dimensionalidade por meio do PCA envolve os seguintes passos:

1. Padronização dos Dados: Os dados são geralmente padronizados para ter média zero e desvio padrão um, para garantir que todas as variáveis tenham a mesma escala.

2. Cálculo da Matriz de Covariância ou Correlação: Com base nos dados padronizados, é calculada a matriz de covariância ou correlação. A escolha entre covariância e correlação depende da escala das variáveis e dos objetivos específicos da análise.

3. Cálculo dos Autovetores e Autovalores: Os autovetores e autovalores da matriz de covariância ou correlação são calculados. Os autovetores representam as direções principais dos dados, enquanto os autovalores indicam a quantidade de variância ao longo dessas direções.

4. Ordenação dos Componentes Principais: Os autovetores são ordenados de acordo com seus autovalores, de forma que o primeiro componente principal corresponde ao autovetor com o maior autovalor, o segundo componente principal corresponde ao segundo maior autovalor, e assim por diante.

5. Projeção dos Dados nos Novos Componentes Principais: Os dados originais são projetados nos novos componentes principais, criando assim um conjunto de dados de menor dimensionalidade.

A redução de dimensionalidade por meio do PCA é útil em diversas situações, como na visualização de dados, na remoção de multicolinearidade em modelos de regressão, na aceleração do treinamento de modelos de machine learning e na eliminação de ruídos nos dados. No entanto, é importante notar que a interpretação dos resultados pode se tornar mais desafiadora após a aplicação do PCA, pois os novos componentes principais podem não ter significado direto nas unidades originais dos dados.
