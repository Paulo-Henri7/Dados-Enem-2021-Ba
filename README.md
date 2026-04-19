# Projeto Enem - Análise de dados ENEM 2021 Bahia

Este projeto tem como objetivo analisar os dados do ENEM 2021 no estado da Bahia, com foco em identificar fatores que influenciam o desempenho dos participantes.

A partir de técnicas de análise exploratória de dados (EDA), são investigadas variáveis socioeconômicas e demográficas, como sexo, cor/raça, renda familiar e tipo de escolaridade, a fim de compreender suas relações com as notas obtidas nas diferentes áreas do exame.

# Perguntas de análise

- Existe correlação entre sexo e desempenho no ENEM?
- O tipo de escola (pública/privada) influencia a nota?
- A renda familiar impacta o desempenho?
- Existe relação entre cor/raça e desempenho?

# Respondendo perguntas levantadas

* Existe correlação entre sexo e desempenho no ENEM?

<p align="center">
  <img src="https://github.com/user-attachments/assets/e2b0cfc4-2079-44f5-954e-b2bcc9440b10" width="49%" />
  <img src="https://github.com/user-attachments/assets/7dacd853-8d51-47dd-a828-b66af289e830" width="49%" />
 </p>


A análise dos boxplots indica que, no conjunto de dados analisado, participantes do sexo masculino apresentaram medianas ligeiramente superiores na maioria das provas. No entanto, observa-se uma sobreposição significativa entre as distribuições, sugerindo que as diferenças entre os grupos não são tão acentuadas. Já o gráfico de barras complementa a análise ao evidenciar as médias das notas por sexo nas cinco provas, reforçando a tendência de desempenho ligeiramente superior dos participantes do sexo masculino.

* O tipo de escola (pública/privada) influencia a nota?
 
<p align="center">
  <img src="https://github.com/user-attachments/assets/84f73d78-0b26-4618-984a-b6194809c85d" width="49%" />
  <img src="https://github.com/user-attachments/assets/ac7c88cc-e511-4e89-a4e7-7e3e06365417" width="49%" />
  </p>

A análise dos boxplots revela que essa diferença não se limita apenas à média, mas também à distribuição das notas, com maior concentração de valores mais altos entre alunos da rede privada. Esse padrão também se reflete na mediana (linha central da caixa), que é consistentemente inferior entre os alunos de escolas públicas em comparação aos de escolas privadas. Os histogramas reforçam essa interpretação, evidenciando que as distribuições das escolas privadas tendem a estar mais deslocadas para a direita, com maior frequência de notas elevadas, enquanto as escolas públicas apresentam maior concentração em faixas intermediárias.


* A renda familiar impacta o desempenho?

  <p align="center">
  <img src="https://github.com/user-attachments/assets/872997bf-2031-4034-9735-3e3f3e4936c2" width="49%" />
  <img src="https://github.com/user-attachments/assets/48792062-6c7d-4734-9f63-96eb665134c8" width="49%" />
  </p>

  <p align="center">
  <img src="https://github.com/user-attachments/assets/521c4922-9cea-4852-8c4b-972fc5fe1dcb" width="49%" />
  <img src="https://github.com/user-attachments/assets/960852a5-0cd9-48f8-a797-82585c60b9a4" width="49%" />
  </p>

  <p align="center">
  <img src="https://github.com/user-attachments/assets/cd1dec5e-98ee-4302-b4c1-6f9d367a158f" width="90%" />
  </p>

A análise dos boxplots evidencia uma relação consistente entre renda familiar e desempenho nas provas do ENEM. Em todas as áreas, observa-se um deslocamento da distribuição das notas para valores mais altos à medida que a renda aumenta, refletido tanto na elevação da mediana quanto na redução relativa da concentração de notas mais baixas. Esse padrão é particularmente acentuado na prova de redação, sugerindo que fatores socioeconômicos podem influenciar mais intensamente habilidades que dependem de repertório cultural, acesso à educação de qualidade e suporte educacional.

* Existe relação entre cor/raça e desempenho?

  <p align="center">
    <img src="https://github.com/user-attachments/assets/098fdafc-469e-40b4-acd3-d2f5fe665196" width="49%" />
    <img src="https://github.com/user-attachments/assets/60f409d4-5c90-4294-8912-84b903796319" width="49%" />
  </p>

  <p align="center">
    <img src="https://github.com/user-attachments/assets/b01212dd-597f-4480-a9f4-490859118558" width="49%" />
    <img src="https://github.com/user-attachments/assets/6bf29f6d-b3e9-4c84-aa15-c5add4df57b1" width="49%" />
  </p>
  
  <p align="center">
    <img src="https://github.com/user-attachments/assets/c5f17951-a46b-43a0-980c-7d65d4da61d7" width="90%" />
  </p>
  
A análise dos boxplots indica a existência de diferenças no desempenho entre os grupos de cor/raça. Observa-se que participantes brancos e amarelos tendem a apresentar medianas ligeiramente superiores na maioria das provas, enquanto participantes pardos e pretos apresentam desempenhos intermediários, e indígenas apresentam as menores medianas. Além disso, a prova de redação se destaca por apresentar maior variabilidade e maior diferença entre os grupos, sugerindo maior sensibilidade a fatores socioeconômicos e educacionais.
