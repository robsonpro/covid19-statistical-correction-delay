# Estimation of Reproduction Number for Covid-19 with Statistical Correction of Notifications Delay
Repositório das análises do artigo "Estimation of Reproduction Number for Covid-19 with Statistical Correction of Notifications Delay" a ser publicado na revista IEEE Latin America Transactions.
O arquivo "INFLUD-15-02-2021.csv" foi obtido do data SUS e podia ser lido diretamente da web no R antes do atque racker aos dados do SUS em 12/2021, via linah de código abaixo:

# Ler plainha do Banco de Dados de Síndrome Respiratória Aguda Grave - incluindo dados da COVID-19 (opendataSUS)
data <- read.csv("https://s3-sa-east-1.amazonaws.com/ckan.saude.gov.br/SRAG/2020/INFLUD-15-02-2021.csv", sep = ";")

Ele foi disponibilizado no github devido o limite de armazenamento. Caso queiram obter o arquivo gentileza solicitar via email (robsondutra@ufsj.edu.br) ou via google drive: https://drive.google.com/file/d/1pbDR2qNpXrm6xP7izkXlVJS9M3SChyJT/view?usp=sharing

