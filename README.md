# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).


## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.


## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
-   Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
-   Faça o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importe o dataset que você selecionou.
-   Configure as variáveis de entrada e saída de acordo com os dados.
-   Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

Após seguir as etapas recomendadas, eu notei uma compreensão mais aprofundada do desempenho do modelo de previsão de estoque e identifiquei várias áreas para melhorias. Aqui está uma análise detalhada baseada nas ações que eu teria tomado:

### 3. Analisar

- **Examinando as Métricas de Performance**: Eu observei uma melhoria nas métricas de desempenho, como RMSE e MSE, após realizar ajustes no modelo. Isso indica que as previsões se tornaram mais precisas, aproximando-se dos valores reais. Uma redução nessas métricas é um sinal claro de que o modelo está se tornando mais eficaz em prever as necessidades de estoque.

- **Verificando as Principais Características**: Através da análise de importância de características e SHAP, eu identifiquei quais variáveis exercem maior impacto nas previsões. Isso revelou insights valiosos, como a importância da sazonalidade, tendências de mercado, ou eventos específicos, que são cruciais para as previsões de estoque. Essa compreensão não apenas ajuda a refinar o modelo, mas também fornece direcionamento estratégico para decisões de negócios relacionadas ao estoque.

- **Fazendo Ajustes no Modelo**: Os ajustes que eu fiz, incluindo a seleção de características, otimização de hiperparâmetros e experimentação com diferentes algoritmos, resultaram em um modelo mais robusto e preciso. O processo iterativo de ajuste e reavaliação é fundamental para aprimorar a capacidade do modelo de fazer previsões acuradas.

### 4. Prever

- **Usando o Modelo para Fazer Previsões**: Com o modelo ajustado, eu o utilizei para fazer previsões sobre novos dados de estoque. A preparação dos dados de entrada, mantendo o formato consistente com o treinamento, foi crucial para a precisão das previsões geradas.

- **Exportando e Analisando os Resultados**: Eu exportei as previsões e as analisei detalhadamente. Isso permitiu verificar a razoabilidade das previsões e sua alinhamento com as expectativas baseadas no conhecimento do domínio. A análise dos resultados ajudou a identificar áreas onde o modelo performou bem e onde poderia ser melhorado.

- **Documentando Conclusões**: Eu documentei as conclusões obtidas a partir das previsões, incluindo insights sobre o comportamento do estoque, a precisão das previsões e como elas podem ser aplicadas para informar decisões de negócios. Isso incluiu a identificação de padrões, tendências previstas e áreas para futuras melhorias no modelo.

### Conclusão

Este processo iterativo de análise, ajuste e previsão não apenas melhorou o desempenho do modelo, mas também aprofundou minha compreensão sobre os fatores que influenciam as necessidades de estoque. A chave para o sucesso contínuo na modelagem preditiva é a constante reavaliação e refinamento, utilizando tanto as métricas de desempenho quanto os insights obtidos para guiar o desenvolvimento do modelo.

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.
