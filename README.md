# Projeto Aplicado - Grupo 1
<h1 align="center"> Qual canal de vendas mais atrai os perfis analisados? </h1>

![Analise](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/746a4507-a9be-4d5e-b389-7931840029dc)

Em uma época onde os algoritmos são cada vez mais específicos e a busca por conteúdos especializados cresce de forma exponencial, é essencial que as empresas se adaptem e entendam o perfil de seus consumidores para garantir um posicionamento estratégico no mercado.  

O presente projeto busca discorrer sobre o comportamento de diferentes perfis e seu potencial de compra considerando canais de vendas diversos. Serão considerados para esse projeto dados demográficos, de visualização de sites e adesão a campanhas de marketing. A partir dos dados analisados o estudo buscará responder a seguinte pergunta: "qual canal de venda mais atrai os perfis analisados?" 


# Índice 

* [Descrição do Dataset](#descrição-do-dataset)
* [Objetivos e Metas](#objetivos-e-metas)
* [Mapa  Mental](#mapa-mental)
* [Conclusão](#conclusão)
* [Desenvolvedores do Projeto] (#desenvolvedores-do-projeto)


# Descrição do Dataset
O relatório Customer Personality Analysis será utilizado como o DataSet que guiará as análises realizadas ao longo desse projeto. A empresa e o período de análise não foram divulgados. Akash Patel, Cientista Executivo de Dados na NielsenIQ, é o responsável pela disponibilização do projeto na plataforma Kaggle. O autor mantém um perfil ativo no github.
O contexto dos dados coletados pelo autor é o da crescente busca por conteúdo personalizado que tem levado as empresas a tentarem entender melhor os gostos dos consumidores em busca de criar anúncios e promoções com  targets mais específicos, além de realizar ajustes na comunicação para proporcionar maior apelo para cada consumidor.

O dataset para a análise de personalidade do comprador contém dados demográficos como ano de nascimento do entrevistado, nível de educação, estado civil, renda familiar anual, entre outros. Também inclui informações como cadastro do cliente na empresa; número de dias desde a última compra e reclamações feitas nos últimos dois anos.
Além disso, são fornecidos dados sobre os produtos comercializados pela empresa, visitas realizadas ao site, número de campanhas de marketing realizadas e se os clientes aderiram às campanhas efetuando compras. A pesquisa também aborda os tipos de venda por canal, considerando as seguintes plataformas: site; loja física e catálogo. 

Para o desenvolvimento do projeto, serão utilizadas as colunas: Id do cliente; Age - idade do cliente ; NumWebPurchases - número de compras realizadas através do site da empresa; NumCatalogPurchases - número de compras feitas usando um catálogo; NumStorePurchases - número de compras feitas diretamente nas lojas físicas e NumWebVisitsMonth - número de visitas ao site da empresa no último mês. Os dados apresentados são do tipo Float64, int64 e object. A única coluna que possui dados nulos é a Income.
Também serão utilizadas técnicas de análise exploratória com as bibliotecas da linguagem Python e serão realizadas alterações nos nomes das colunas para melhor entendimento dos dados.

# Objetivos e Metas
A partir do entendimento de que a personalização de produtos pode alavancar o volume de vendas, pode-se supor que perfis diferentes também se sentirão atraídos por diferentes tipos de canais de venda. Entender os perfis que cada canal atrai e o porquê contribuirá com a elaboração de uma estratégia de vendas mais eficiente

A partir do exposto estabelece-se como objetivo do estudo entender qual é o meio de venda que mais atrai o público observado, considerando os diferentes perfis apresentados.  A partir das respostas encontradas poderão surgir recomendações mais eficientes para a criação de uma estratégia de vendas que proporcione maior personalização aos clientes e atraia maior volume de vendas.
Para isso, ao longo do desenvolvimento do projeto serão analisados dados de compra para entender qual o canal de venda preferido pelo público entrevistado, dados demográficos para compreensão do nível socioeconômico e estrutura familiar dos adeptos desse canal, bem como o impacto que as campanhas de marketing geram nesse público. Dessa forma, será possível compreender como a empresa pode gerar melhores promoções, bem como uma comunicação mais efetiva para o público dominante do ponto de venda observado. Também será observada a existência de pontos de venda em possível ascensão entre o público analisado

# Mapa Mental
![Mapa Mental ](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/b11635e6-f080-401b-a67a-d980a6bda05c)

# Conclu
Para entender a relação entre o perfil dos consumidores e os canais de compra preferidos, foram  utilizadas análises da média de idade e renda, bem como o número de ocorrências de pessoas com filhos. Além disso, também foram observados os outlier para os atributos analisados.

Através da observação dos gráficos pode-se inferir que a amostra se concentra em pessoas entre 44 e 69 anos (gráfico 1) com preferência por compras físicas em lojas (gráfico 8). Entretanto, também é possível observar alta taxa de visitas aos sites. O núcleo familiar de 42,88% dos clientes é constituído por até 1 filho criança e 57,12% possuem até 1 filho adolescente (gráficos 2 e 3).

Grafico 1
![Grafico 1](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/e8273b15-bd21-46af-9904-e0c81619e1e8)

Gráfico 2 e 3 
![Grafico 2 e 3](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/6c6761a7-fcb9-4371-96c6-490c491c7d27)

 Em relação a renda, pessoas sem filhos representam 28,5% da amostra e  apresentam renda maior (até 100.000) que pessoas com filhos, enquanto pessoas com adolescentes tendem a apresentar renda acima da média (gráficos 4, 5, 6, 7)

Grafico 4 e 5 
![Grafico 4](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/f5bddda6-b09a-4dc0-9459-552cbe410d75)
![Grafico 5](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/f4f79adc-958b-4250-a2c7-e7ec8347774d)

Gráfico 6 e 7 
![Grafico 6](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/b8ebc957-57f9-49d8-9358-6652ea4d5deb)

Gráfico 8 
![Grafico 8](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/fe627506-a148-4e94-81f7-3e9cffdd99af)


A presença de filhos altera o comportamento de compra das pessoas analisadas. Pessoas com até 1 filho adolesente apresentam maior consumo médio e maior consumo através do site, enquanto casais com até 1 criança utilizam menos o e-commerce e mais as lojas físicas (gráficos 9 e 10).

Gráfico 9 
![Grafico 9](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/1ba6c904-6128-41e4-9630-0c8f9b38aed0)

Gráfico 10 
![Grafico 10](https://github.com/JuliaRodrigs/projeto-aplicado-grupo-1/assets/131941832/bb9c6bb9-21f9-4db1-83a8-ea7ef6a73c99)

Em conclusão, lojas físicas ainda são a preferência das pessoas, especialmente entre 40 e 60 anos, mas as taxas de visitas aos sites ainda são altas mesmo para essa faixa etária.  Também é possível concluir que o  e-commerce é impulsionado, dentro dessa faixa etária, pela presença de filhos adolescentes.

Através dessa conclusão as lojas poderão ajustar seu trabalho de comunicação dentro do e-commerce para impulsionar as compras através deste canal, além de poder atingir um público maior considerando núcleos familiares com adolescentes.

# Desenvolvedores do Projeto 
Aparecida Vânia de 

Bruno Gomes

Julia Rodrigue

Lara Cabral 

Lucas Gomes Porfirio




