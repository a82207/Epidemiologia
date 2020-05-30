# ***COVID-19*** - Mapeamento de dados e Análise Estatística


### Dados
O projeto realizado teve essencialmente em conta as seguintes fontes de dados:

| Fontes  |  Descrição  |
| ------------------- | ------------------- |
|  [GitHub - jgrocha](https://github.com/jgrocha/covid-pt) |  Dados relativos à situação epidemiológica de Portugal |
|  [GitHub - mdipietro09](https://github.com/mdipietro09/DataScience_ArtificialIntelligence_Utils/blob/master/time_series/example_parametric_fit.ipynb) |  Notebook de auxílio na implementação de ajuste dos parâmetros, através de diversas funções |
| [data.world - COVID-19 in Spain](https://data.world/liz-friedman/covid-19-in-spain)  | Dados em formato csv referentes à situação epidemiológica em Espanha, descrevendo os casos a nível nacional |
| [CSSE - Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data)  | Dados em formato csv referentes à situação epidemiológica mundial e dos Estados Unidos |
| [The New York Times - COVID-19_data](https://github.com/nytimes/covid-19-data)  | Dados em formato csv referentes aos Counties e Estados dos US  |

### Notebooks
No âmbito da explração dos dados anteriores, relativos a casos de COVID-19, implementou-se um conjunto de notebooks:

- Mapeamento dos dados a nível mundial, a nível nacional, em Espanha e nos Estados Unidos da América
  -[Mapas](/COVID_19/dados_estatísticos/Mapas.ipynb)

- Análise estatística a nível mundial - casos confirmados/ativos/recuperados e número de mortes
  -[Situação_Mundo](/COVID_19/dados_estatísticos/Situacao_Mundo.ipynb)

- Análise estatística a nível nacional - casos, influência do sexo/idade e sintomas desenvolvidos
  -[Situação PT](/COVID_19/dados_estatísticos/Situação_PT.ipynb)

- Análise estatística em Espanha - casos confirmados/recuperados/hospitalizados, casos nos cuidados intensivos, número de mortes e número de testes realizados
  -[Situação ESP](/COVID_19/dados_estatísticos/Situacao_SP.ipynb)

- Análise estatística nos Estados Unidos - casos confirmados
  -[Situação US](/COVID_19/dados_estatísticos/Situação_US.ipynb)

### Resultados
Obteram-se figuras que descrevem os mapas relativos:

- ao número de casos confirmados no mundo:
![confirmados_mundo](/COVID_19/figuras/confirmados_mundo.png)

- ao número de casos confirmados em Portugal (por distrito):
![confirmados_portugal](/COVID_19/figuras/confirmados_distrito.png)

- ao número de casos confirmados em Espanha:
![confirmados_espanha](/COVID_19/figuras/confirmados_esp.png)

- ao número de casos confirmados nos Estados Unidos:
![confirmados_usa](/COVID_19/figuras/confirmados_usa.png)

Assim como figuras alusivas a dados estatíscos de casos de COVID-19:

- Países com maior número de casos confirmados:
![confirmados_mundo](/COVID_19/figuras/dados1_mundo.png)

- Número de casos confirmados por distrito em Portugal:
![confirmados_pt](/COVID_19/figuras/dados1_pt.png)

- Número de casos confirmados em Espanha:
![confirmados_sp](/COVID_19/figuras/dados1_esp.png)

- Counties com maior número de casos confirmados nos US:
![confirmados_us](/COVID_19/figuras/dados2_us.png)

- Número de casos confirmados vs Número de mortes:
![confirmados_mundo](/COVID_19/figuras/dados1_us.png)

##### Autores:

- [José Lopes](https://github.com/a82207)
