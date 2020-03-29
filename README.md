# COVID-19 - Brazilian States
Data, analysis and graphs of the advancement of COVID-19 in Brazil

## Description

The dataset *COVID-19_Brazil_States_CONFIRMED.csv* was generated thanks to the joint effort of researchers and students of the School of Electrical and Computer Engineering of the University of Campinas (UNICAMP) and researchers of the University of Brasília (UnB).

Our methodology consisted of dividing the country into regions and states and looking for sources of information regarding confirmed cases of COVID-19 in that region. This procedure was necessary because we realized that the numbers provided by the  Ministry of Health in Brazil, for some regions, were outdated or discrepant.

Since March, 19th 2020, the Brazilian Ministry of Health is not sharing any CSV file or any other dataset format that researchers could use to process the data. This is the reason that we decided to generate our own dataset.

## *COVID-19_Brazil_States_CONFIRMED.csv* Dictionary

* Column 1 - Region - Brazil is divided into five regions: South, Southeast, Midwest, North, Norteast
* Column 2 - States - Brazil is divided into 27 states. The dataset presents the acronym for each state: AC (Acre), AL (Alagoas),   AM (Amazonas), AP (Amapá), Bahia (BA), Ceará (CE), DF (Distrito Federal), ES (Espírito Santo), GO (Goiás), MA (Maranhão), MG (Minas Gerais), MS (Mato Grosso do Sul), MT (Mato Grosso), PA (Pará), PB (Paraíba), PE (Pernambuco), PI (Piauí), PR (Paraná), RJ (Rio de Janeiro), RN (Rio Grande do Norte), RO (Rondônia), RR (Roraima), RS (Rio Grande do Sul), SC (Santa Catarina), SE (Sergipe), SP (São Paulo), TO (Tocantins)
* Column 3 - Date - Format YYYY-MM-DD
* Column 4 - Number of confirmed cases on date (maximum number found in the multiple sources of information)

## *COVID-19_Brazil_States_DEATH.csv* Dictionary

* Column 1 - Region - Brazil is divided into five regions: South, Southeast, Midwest, North, Norteast
* Column 2 - States - Brazil is divided into 27 states. The dataset presents the acronym for each state: AC (Acre), AL (Alagoas),   AM (Amazonas), AP (Amapá), Bahia (BA), Ceará (CE), DF (Distrito Federal), ES (Espírito Santo), GO (Goiás), MA (Maranhão), MG (Minas Gerais), MS (Mato Grosso do Sul), MT (Mato Grosso), PA (Pará), PB (Paraíba), PE (Pernambuco), PI (Piauí), PR (Paraná), RJ (Rio de Janeiro), RN (Rio Grande do Norte), RO (Rondônia), RR (Roraima), RS (Rio Grande do Sul), SC (Santa Catarina), SE (Sergipe), SP (São Paulo), TO (Tocantins)
* Column 3 - Date - Format YYYY-MM-DD
* Column 4 - Number of deaths by coronavirus on date (maximum number found in the multiple sources of information)

## *COVID-19_Brazil_States_CONFIRMED_DEATH.csv* Dictionary

* Column 1 - Region - Brazil is divided into five regions: South, Southeast, Midwest, North, Norteast
* Column 2 - States - Brazil is divided into 27 states. The dataset presents the acronym for each state: AC (Acre), AL (Alagoas),   AM (Amazonas), AP (Amapá), Bahia (BA), Ceará (CE), DF (Distrito Federal), ES (Espírito Santo), GO (Goiás), MA (Maranhão), MG (Minas Gerais), MS (Mato Grosso do Sul), MT (Mato Grosso), PA (Pará), PB (Paraíba), PE (Pernambuco), PI (Piauí), PR (Paraná), RJ (Rio de Janeiro), RN (Rio Grande do Norte), RO (Rondônia), RR (Roraima), RS (Rio Grande do Sul), SC (Santa Catarina), SE (Sergipe), SP (São Paulo), TO (Tocantins)
* Column 3 - Date - Format YYYY-MM-DD
* Column 4 - Number of confirmed cases on date (maximum number found in the multiple sources of information)
* Column 5 - Number of deaths by coronavirus on date (maximum number found in the multiple sources of information)

ShinyApp for Brazil: https://kirtisundarsahu.shinyapps.io/BRAZIL_shinyapp/ 
Shiny Dashboard for Brazil: https://kirtisundarsahu.shinyapps.io/Brazil_DashBoard/

## Updates

2020-03-27 - Datasets updated and added dataset with death numbers
2020-03-28 - Datasets updated but still with some missing points in death numbers

## Contributors
Maria Giulia Martins (FEEC-Unicamp)

João Luís Carvalho de Abreu (FEEC-Unicamp)

Guilherme Lisboa (IMECC-Unicamp)

Thiago Ribas Bella (FEEC-Unicamp)

JHictor Macchini (FEEC - Unicamp)

Prof. Paula Dornhofer Paro Costa (FEEC-Unicamp)

Prof. Dalton Martins (Faculty of Information Sciences - UnB)

Kirti Sundar Sahu (University of Waterloo, Canada)

## Special Thanks

To Helena (2), Laura (11) and Ana Luiza (14) for being very patient while their mother check datasets.
