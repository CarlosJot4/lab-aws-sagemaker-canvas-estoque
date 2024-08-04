# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Utilizei o arquivo com 500 registros: dataset-500-curso-sagemaker-canvas-dio.csv 

### 2. Construir/Treinar

-   Criei um novo modelo de analise preditiva
-   Utilizei o quick build (apesar de perder precisão em comparação a build padrão) para uma contrução mais rapida (demorou + ou - 10 minutos)

### 3. Analisar

-   Após o treinamento, examine as métricas de performance do modelo.
-   Verifique as principais características que influenciam as previsões.
-   Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

### 4. Prever

-   Sobre alguns status do modelo:

Avg. wQL: que seria a perda média ponderada em quantil. Quanto menor 
melhor.

MAPE: que seria o erro percentual médio absoluto. Quanto menor mais preciso
e se for igual a zero é sem erros.

WAPE: que seria o erro percentual absoluto ponderado. Muito pareciso com
o MAPE, quanto menor o número melhor e mais preciso.

Na no gráfico de predição o interessante era que eu podia ver como seria um modo
otimista para o estoque de cada produto para o dia seguinte.

## 🤔 insights?

O ruim foi ter de limpar todo esse progresso e aprendizado do SageMaker para que eles pudessem reembolsar o que cobraram, existem muitas métricas de cobrança nessa utilização. Mas tirando isso é uma ferramenta muito boa que pode ser utilizada sem codificar uam linha sequer e aprendiz muito sobre elae sobre  ML.
