# Estimation of Reproduction Number for Covid-19 with Statistical Correction of Notifications Delay
Repositório das análises do artigo "Estimation of Reproduction Number for Covid-19 with Statistical Correction of Notifications Delay" a ser publicado na revista IEEE Latin America Transactions.
O arquivo "INFLUD-15-02-2021.csv" foi obtido do data SUS e podia ser lido diretamente da web via linguagem R antes do dito ataque hacker aos dados do SUS em 12/2021. A seguir o código para leitura do arquivo.

data <- read.csv("https://s3-sa-east-1.amazonaws.com/ckan.saude.gov.br/SRAG/2020/INFLUD-15-02-2021.csv", sep = ";")

Por sorte baixamos o dataset antes, porém este não foi disponibilizado aqui no github devido limite de armazenamento. Interessados gentileza solicitar via email (robsondutra@ufsj.edu.br) ou via google drive: https://drive.google.com/file/d/1pbDR2qNpXrm6xP7izkXlVJS9M3SChyJT/view?usp=sharing

## Estimativa de R0

A seguir o código e resultados para estimativa de R0 para o estado de Minas Gerais.

https://robsonpro.github.io/covid19-statistical-correction-delay/R0_MG.html

## Deconvolução
A seguir o código e resultados para deconvolução para a cidade de Ouro Branco. O procedimento pode ser realizado de forma análoga para as outras cidades consideradas no artigo além de outras de interesse.

https://robsonpro.github.io/covid19-statistical-correction-delay/Rt_deconv_OB.html

## Validação da deconvolução para Belo Horizonte
A validação da deconvolução foi realizada para a cidade de Belo Horizonte, conforme segue. A capital foi considerada, visto que as do interior tem dados mais esparços.

https://robsonpro.github.io/covid19-statistical-correction-delay/Validacao_deconv_BH.html

## Rt corrigido e plano Minas Consciente
Finalmente, o efeito da mudança no Rt considerando as mudanças de onda no Minas Consciente foi realizado conforme segue.

