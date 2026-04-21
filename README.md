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
 
# Análise exploratória de dados(EDA)

* Correlação entre provas de exatas: Matemática e Ciências da Natureza | Correlação entre provas de humanas: Linguagens e Ciências Humanas

  <p align="center">
    <img src="https://github.com/user-attachments/assets/a895673b-8045-441f-898e-29944039586c" width="49%" />
    <img src="https://github.com/user-attachments/assets/eb998565-adb8-4871-8764-3bbb94ebd9e2" width="49%" />
  </p>

Observa-se uma correlação positiva entre as provas analisadas, indicando que alunos com bom desempenho em uma área tendem a apresentar resultados semelhantes em áreas correlatas, especialmente nas disciplinas de exatas, onde a relação se mostra mais consistente. Além disso, há uma diferença clara entre tipos de escola, com alunos de escolas privadas concentrando-se em faixas de notas mais elevadas e apresentando menor dispersão, enquanto alunos de escolas públicas demonstram maior variabilidade no desempenho.

* Comparação da distribuição das notas entre escolas privadas e públicas

  <p align="center">
    <img src="https://github.com/user-attachments/assets/29b972e2-5bcb-47f5-a573-cecc2ac0fd09" width="49%" />
    <img src="https://github.com/user-attachments/assets/60f29e56-d4e8-45df-9eb8-09449dacfcb4" width="49%" />
  </p>
  
A análise evidencia uma diferença consistente de desempenho entre alunos de escolas públicas e privadas em todas as disciplinas, com vantagem para as escolas privadas. No entanto, a prova de Redação se destaca de forma mais expressiva, apresentando medianas mais elevadas e maior variabilidade em ambos os grupos.

* Correlação entre as provas do ENEM
 
<img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/303b333e-04d3-483c-9a94-c6eef96657b9" />

As provas objetivas do ENEM apresentam correlações moderadas entre si, indicando que o desempenho dos alunos tende a ser relativamente consistente entre diferentes áreas do conhecimento, com destaque para a forte relação entre Linguagens e Ciências Humanas, possivelmente devido à similaridade nas habilidades exigidas, como interpretação e análise textual. As demais combinações, incluindo Matemática e Ciências da Natureza, também demonstram correlações relevantes, sugerindo uma base comum de competências. Por outro lado, a Redação apresenta correlações mais baixas com todas as provas, variando entre 0.44 e 0.49, o que indica que essa avaliação mede habilidades mais específicas, como argumentação, coesão textual e repertório sociocultural.

* Análise geográfica

  <img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/65f4a325-9f96-4879-9c3d-e5a873e3ab19" />

# Relatório Power BI



<img width="1920" height="1080" alt="Gif_projeto_ENEM_1" src="https://github.com/user-attachments/assets/e9f51e5e-acf2-4850-97ee-79f69d88b97e" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/667da114-5908-4939-8312-7cc6b7a4e5da" />

<img width="1920" height="1080" alt="Gif_projeto_ENEM_2" src="https://github.com/user-attachments/assets/ad9b3dc8-9145-48cf-929c-fe294dc5fdf1" />

