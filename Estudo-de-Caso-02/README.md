# ESTUDO DE CASO 02

Você é Analista de Dados na empresa PontoMaximo, uma rede de varejo que vende produtos eletrônicos e eletrodomésticos com lojas espalhadas por diversas cidades do Brasil. A 
empresa começou sua operação no Brasil em 2012 e atua nos quatro estados da região sudeste mais os estados do Paraná e Bahia. A empresa está montando a estratégia de vendas para o próximo ano e precisa saber qual  dos fabricantes dos produtos vendidos, apresenta melhor desempenho nas vendas. O objetivo é  descartar os fabricantes cujos produtos possuem poucas vendas e tentar negociar melhores condições com os principais fabricantes.

Em paralelo a isso, a empresa gostaria de ter diferentes visões das vendas realizadas nos  últimos 4 anos (período de 2012 a 2015). Deve ser possível segmentar os relatórios de vendas  por diferentes informações e por diferentes ângulos. Estas informações irão suportar as  estratégias da empresa para o próximo ano.

Sua fonte de dados é um arquivo Excel com dados coletados do sistema de vendas, CRM e ERP da empresa. O conjunto de dados foi entregue pelo departamento de TI com as seguintes 
colunas.

<div align="center">
<img src = "https://user-images.githubusercontent.com/94937578/154593428-8908cda4-c7bf-4cb6-ad67-d33cd876f51b.png" width="600px" />
</div>

Haverá diversas reuniões para definição da estratégia de vendas e os relatórios poderão ser extraídos sob demanda, de acordo com a necessidade dos gestores. Por conta disso, você deve criar um modelo de dados que permita a extração de relatórios a qualquer momento e que permita extrair dados por diferentes visões e ângulos.

#### Exercício

Responder as perguntas:
1. Qual dos fabricantes dos produtos vendidos, apresenta melhor desempenho nas vendas?
2. Qual o total de vendas por estado e por categoria? Use um mapa.
3. Qual o total de vendas por segmento?
4. Qual segmento tem maior influência no valor médio de venda?

#### Seu trabalho é fazer isso acontecer!

(Fonte: https://www.datascienceacademy.com.br/)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Construindo o dashboard e tirando insights

### Com base nos dados disponibilizados e nas informações solicitadas foi criado o dashboard abaixo:

<div align="center">
<img src = "https://user-images.githubusercontent.com/94937578/154601459-280550e2-a931-4f77-a54b-487f0437601b.png"/>
</div>

#### - Os principais pontos aprendidos na construção desse dashboard foram:
* Modelo Star Schema.
* Relacionamento entre tabelas.
* Desagregar uma tabela em várias outras e relacioná-las entre si.
* Criação de tabelas fato e dimensão:
  * Tabela DIM são as dimensões que representam as entidades em nosso problema de negócio e que classificam os dados.
  * Tabela FATO representa um fato, um detalhe, por exemplo, uma venda. Cada fato acontece a partir da junção das dimensões.
* Como excluir registros duplicados.

#### - Insights:


