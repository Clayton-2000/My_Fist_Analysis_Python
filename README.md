# My_Fist_Analysis_Python
## Minha Primeira Análise de Dados com Python

### Introdução
Nesta análise irei lidar com uma seguradora fictícia que pretende elaborar produtos para o mercado imobiliário e para isso ela possui uma base de dados para ser trabalhada e desenvolver análises e relatórios. 

### Sequência de Visualização dos Relatórios 
1. Foi solicitado pela empresa o primeiro relátorio com informações gerais sobre a _**Base de Dados**_.
2. Foi solicitado pela empresa o segundo relátorio com _**Tipos de Imóveis**_.
3. Foi solicitado pela empresa uma base de dados que contenha apenas _**Imóveis Residenciais**_. 
4. Com base no novo banco de dados, a seguradora deseja que realizemos algumas _**Seleções**_ e retire a _**Frequência**_ de cada uma delas.
  *  Selecionar somente os imóveis classificados com tipo 'Apartamento'. 
  *  Selecionar os imóveis classificados com tipos 'Casa', 'Casa de Condomínio' e 'Casa de Vila'.
  *  Selecionar os imóveis com área entre 60 e 100 metros quadrados, incluindo os limites.
  *  Selecionar os imóveis que tenham pelo menos 4 quartos e aluguel menor que R$ 2.000,00.
5. Identificamos alguns problemas que precisam ser solucionados, sendo eles os missings ou _**Tratamento de Dados Faltantes**_.
6. Foi solicitado pela empresa a _**Criação de Novas Variáveis**_ para o conjunto de dados.
  * Variável que armazena o valor bruto do aluguel.
  * Variável que armazena o valor com base no metrô quadrado de um imóvel.
  * Variável de tipo que agregue casas e apartamentos.
  * **Obs.:** Com base nas análises realizadas, expomos para a empresa que a variável 'Valor Bruto' possui valores pouco confiáveis, pois a variável IPTU nem sempre possui valores declarados. Sendo assim a empresa decidiu que 'Valor Bruto' e 'Valor Bruto m2' fossem excluídas do banco de dados.
7. Com objetivo de continuar a verificação da base de dados a fim de encontrar problemas que possam prejudicar os resultados futuros, irei realizar análise de algumas estatísticas descritivas, sendo possível visualizar em _**Criando Agrupamentos**_.
8. Após realizar a análise de algumas estatísticas descritivas, identificamos divergências nos dados e iremos removê-las, sendo possível visualizar em _**Identificando e Removendo Outliers**_.

_Projeto realizado atráves da formação 'Python para Data Science', do curso 'Python Pandas: Tratando e analisando dados', da plataforma de aprendizagem 'Alura'._
