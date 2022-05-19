# Dashboard-RH

Fiz esse painel em uma noite de terça-feira com uma base de dados fictícia que recebi.

O foco dessa dashboard é acompanhar os números da área de People(RH), mostrando quantidade de admissões, desligamentos, salários, detalhes dos colaboradores e etc.

No arquivo anexado no formato reconhecido pelo Power BI, temos 3 relatórios:
  * Visão geral
  * Admissões
  * Desligamentos

## Visão geral

**Totalizadores:**
* TOTAL DE FUNCIONÁRIOS
* ADMISSÕES NO ANO
* DESLIGAMENTOS NO ANO 
* IDADE MÉDIA DOS FUNCIONÁRIOS
* FOLHA SALARIAL

Note: os totalizadores ADMISSÕES NO ANO e DESLIGAMENTOS NO ANO fazem uma comparação do último ano com o ano anterior, onde temos uma formula que permite a cor vermelha pra indicar uma decaída e verde indicando uma subida. 

O valor obtido no totalizador DESLIGAMENTOS NO ANO é maior comparado com o ano anterior, porém mesmo sendo um aumento, o número maior não indica um resultado bom, afinal um desligamento é algo ruim, estou certo ? Visto isso, resolvi que a cor verde fosse apenas quando existir um decaimento no número de desligamentos comparados com o ano anterior.

O ideal seria a comparação do mês atual com o mês anterior, porém como não temos esses dados, resolvi comparar os anos.

**Gráficos:**
* Funcionários ativos por gênero
* Ranking de média salarial por setor
* Salários por cargo
* Total de admissões por ano 
* Total de desligamentos por ano 

## Admissões
**Totalizadores:**
* TOTAL DE ADMISSÕES
* PERCENTUAL DE ADMISSÕES
* IDADE MÉDIA DOS FUNCIONÁRIOS
* MASSA SALARIAL

Note: o totalizador PERCENTUAL DE ADMISSÕES foi feito através do total de admissões, em uma determinada data filtrada, com relação ao total geral de funcionário que temos em nossa base de dados.

**Gráficos:**
* Admissões (%) por gênero
* Admissões por gênero
* Massa salarial por cargo
* Admissões por faixa etária
* Tipo de admissões
* Total de admissões por mês
 
## Desligamentos
**Totalizadores:**
* TOTAL DE DESLIGAMENTOS
* PERCENTUAL DE DESLIGAMENTOS
* IDADE MÉDIA DOS FUNCIONÁRIOS
* ALÍVIO SALARIAL

Note: o totalizador "PERCENTUAL DE DESLIGAMENTOS" foi feito através do total de desligamentos, em uma determinada data filtrada, com relação ao total geral de funcionário que temos em nossa base de dados.

**Gráficos:**
* Desligamentos (%) por gênero
* Desligamentos por gênero
* Alívio salarial por cargo
* Desligamentos por faixa etária
* Tipo de desligamentos
* Total de desligamentos por mês

## Note

Aqui está o relatório em PDF ! 

Indico que baixe o outro arquivo anexado (.pbix), pois em PDF o Power BI só exporta com o Background branco.

[BaseRH.pdf](https://github.com/Isaque-Chaves/Dashboard-RH/files/8730353/BaseRH.pdf)
Arquivo em Power BI: https://github.com/Isaque-Chaves/Dashboard-RH/blob/main/BaseRH.pbix

