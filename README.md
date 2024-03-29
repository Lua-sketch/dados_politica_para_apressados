# Dados - Política para Apressados

[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/Lua-sketch/dados_politica_para_apressados/blob/main/README.md)
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/Lua-sketch/dados_politica_para_apressados/blob/main/README.en.md)

## Política para Apressados
Política para Apressados é um site que facilita a navegação de dados da Câmara dos Deputados e do Senado. [Você pode acessar o site aqui](https://lua-sketch.github.io/politica_para_apressados/) e, caso queira ver o código usado para criá-lo, [você pode acessar o repositório correspondente aqui](https://github.com/Lua-sketch/politica_para_apressados).

## Esse Repositório
Nesse repositório, você encontra o código utilizado para obter e formatar os dados exibidos no site Política para Apressados. Note que todos os arquivos csv, com exceção de proposicoesSenado.csv, foram baixados do [site da API de Dados Abertos da Câmara dos Deputados](https://dadosabertos.camara.leg.br/swagger/api.html#staticfile) e formatados para obter proposicoesCamaraFinal.json. Já os dados do Senado foram obtidos diretamente da [API de Dados Abertos do Senado](https://legis.senado.leg.br/dadosabertos/docs/resource_MateriaService.html?_gl=1*5bi45k*_ga*MTk3OTE4Njc3MS4xNjc2NjYxNjQx*_ga_CW3ZH25XMK*MTY4MDc4NzE3NC43LjAuMTY4MDc4NzE4My4wLjAuMA..#resource_MateriaService_listaMateriasTramitando_GET) utilizando a [biblioteca requests](https://requests.readthedocs.io/en/latest/) e formatados para obter proposicoesSenadoFinal.json. Esses dois arquivos json servem como a fonte dos dados exibidos no site Política para Apressados e você pode encontrá-los também no repositório do site.
