# Análise do IDHM e do ENEM 2020

- Neste projeto, analisamos os dados do ENEM e do IDH para uma instituição filantrópica, que atua com projetos visando a melhoria da educação no ensino médio e do IDHM dos municípios com nível baixo ou muito baixo.
- Nosso objetivo era selecionar 100 escolas para receber 10 dólares por aluno/mês durante 12 meses, para turmas do ensino médio.
- O critério de escolha das escolas foi: municípios que possuem menores valores de IDHM, mas que tenham escolas de ensino médio com alunos que fizeram o ENEM. Em caso de empate no valor do IDHM, escolheremos as cidades que possuírem menor média do ENEM. Como nos microdados do ENEM não podemos ter acesso às notas das escolas, utilizaremos os microdados do Censo Escolar da Educação Básica 2020 para selecionar as escolas que possuem mais alunos matriculados no Ensino Médio das cidades que escolhemos anteriormente.
- Também foram propostas algumas questões que respondemos ao longo do projeto:
  - Qual o valor total a ser investido, considerando que cada escola possui apenas 1 turma com 30 alunos para cada série do ensino médio? Quanto seria esse valor com a     - cotação do dólar de janeiro de 2019 e dezembro de 2020?
  - Quais dados (arquivos) você utilizou, onde e como os coletou?
  - Que tipo de tratamento você aplicou na base de dados?
  - Qual a proporção de missing nas bases e o que você fará com esses casos? Na sua opinião, quais os mais relevantes?
  - Qual o número de inscritos por ano? Existe alguma tendência a ser observada nos dados?
  - Quais as notas médias por ano de realização da prova?
    a. Nota da prova de Ciências da Natureza
    b. Nota da prova de Ciências Humanas
    c. Nota da prova de Linguagens e Códigos
    d. Nota da prova de Matemática
    e. Redação
    f. Nota total (soma a+b+c+d+e)
  - Quais escolas devem receber o investimento?
- Na Coleta de dados, apresentamos as cinco principais fontes de dados utilizadas (cotação do dólar para real, IDHM dos municípios do Brasil, microdados do ENEM 2020, microdados do Censo Escolar 2020 e Sinopses Estatísticas do ENEM 2017 a 2020).
- No Tratamento de dados, utilizamos vários métodos, como transformações de tipo, criação de filtros, classificação, separação por expressões regulares, agrupamento e mesclagem. Ao final, terminamos a seleção das 100 escolas que receberão o benefício e criamos uma tabela com elas e outras informações relevantes.
- Na Análise Exploratória, visualizamos e analisamos os dados das sinopses do ENEM 2017-2020, dos municípios e das escolas selecionadas.
- Na Visualização de dados, resumimos a análise em três figuras com os gráficos das notas (por área e geral) e inscritos do ENEM 2017-2020. Também destacamos as principais características das escolas e dos municípios selecionados a partir dos seus estados.
- Como conclusão, podemos destacar que as regiões que possuem menores notas médias no ENEM são Norte e Nordeste, também todas as cidades selecionadas com menores índices de IDHM são dessas regiões. O projeto dessa instituição é importante porque vai atuar nessas áreas mais necessitadas, ajudando a diminuir as disparidades regionais no Brasil.
