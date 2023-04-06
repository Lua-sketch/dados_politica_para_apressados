# Data - Política para Apressados (Politics for People in a Hurry)

[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/Lua-sketch/dados_politica_para_apressados/blob/main/README.md)
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/Lua-sketch/dados_politica_para_apressados/blob/main/README.en.md)

## Política para Apressados (Politics for People in a Hurry)
Política para Apressados (which roughly translates to Politics for People in a Hurry) is a website which makes data from the Brazilian Chamber of Deputies and 
Senate easier to navegate. [You can access the website here](https://lua-sketch.github.io/politica_para_apressados/) and, if you want to take a look at the code used 
to create it, [you can access the corresponding repository here](https://github.com/Lua-sketch/politica_para_apressados).

## This Repository
In this repository, you will find the code used to obtain and format the data displayed on the website Política para Apressados. All csv files, with the exception of 
proposicoesSenado.csv, were downloaded from [the Chamber of Deputies' Open Data API website](https://dadosabertos.camara.leg.br/swagger/api.html#staticfile) and formatted 
to obtain proposicoesCamaraFinal.json. All data from the Brazilian Senate was obtained directly from the [Senate's Open Data API](https://legis.senado.leg.br/dadosabertos/docs/resource_MateriaService.html?_gl=1*5bi45k*_ga*MTk3OTE4Njc3MS4xNjc2NjYxNjQx*_ga_CW3ZH25XMK*MTY4MDc4NzE3NC43LjAuMTY4MDc4NzE4My4wLjAuMA..#resource_MateriaService_listaMateriasTramitando_GET)
using the [Python requests library](https://requests.readthedocs.io/en/latest/) and formatted to obtain proposicoesSenadoFinal.json. These two json files serve as the source of the data displayed on the Política para Apressados website, and you can find them in the website's repository as well.
