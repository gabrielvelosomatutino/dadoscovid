**Introdução**

Este projeto consiste em uma análise exploratória de dados dos casos da COVID-19. A análise tem como objetivo extrair insights e compreender os padrões e tendências relacionados à propagação da doença.

**Dados Utilizados**
 - Dashboard: 
  - Google Data Studio ([link](https://lookerstudio.google.com/reporting/c4dfd97e-89fc-4b36-ab1c-87527e9d58e6)).
 - Fontes: 
  - Casos pela universidade John Hopkins ([link](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports));
  - Vacinação pela universidade de Oxford ([link](https://covid.ourworldindata.org/data/owid-covid-data.csv)).

Os dados sobre **casos da COVID-19** são compilados pelo centro de ciência de sistemas e engenharia da universidade americana **John Hopkins** ([link](https://www.jhu.edu)). Os dados são atualizados diariamente deste janeiro de 2020 com uma granularidade temporal de dias e geográfica de regiões de países (estados, condados, etc.). O website do projeto pode ser acessado neste [link](https://systems.jhu.edu/research/public-health/ncov/) enquanto os dados, neste [link](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports). Abaixo estão descritos os dados derivados do seu processamento.
 - **date**: data de referência;
 - **state**: estado;
 - **country**: país; 
 - **population**: população estimada;
 - **confirmed**: número acumulado de infectados;
 - **confirmed_1d**: número diário de infectados;
 - **confirmed_moving_avg_7d**: média móvel de 7 dias do número diário de infectados;
 - **confirmed_moving_avg_7d_rate_14d**: média móvel de 7 dias dividido pela média móvel de 7 dias de 14 dias atrás;
 - **deaths**: número acumulado de mortos;
 - **deaths_1d**: número diário de mortos;
 - **deaths_moving_avg_7d**: média móvel de 7 dias do número diário de mortos;
 - **deaths_moving_avg_7d**: média móvel de 7 dias dividido pela média móvel de 7 dias de 14 dias atrás;
 - **month**: mês de referência;
 - **year**: ano de referência.

Os dados sobre vacinação da COVID-19 são compilados pelo projeto Nosso Mundo em Dados (Our World in Data ou OWID) da universidade britânica de Oxford (link). Os dados são atualizados diariamente deste janeiro de 2020 com uma granularidade temporal de dias e geográfica de países. O website do projeto pode ser acessado neste link enquanto os dados, neste link. Abaixo estão descritos os dados derivados do seu processamento.
date: data de referência;
country: país;
population: população estimada;
total: número acumulado de doses administradas;
one_shot: número acumulado de pessoas com uma dose;
one_shot_perc: número acumulado relativo de pessoas com uma dose;
two_shots: número acumulado de pessoas com duas doses;
two_shot_perc: número acumulado relativo de pessoas com duas doses;
three_shots: número acumulado de pessoas com três doses;
three_shot_perc: número acumulado relativo de pessoas com três doses;
month: mês de referência;
year: ano de referência.

**Objetivos da Análise**

Os principais objetivos desta análise exploratória são:

Identificar padrões e tendências de propagação da COVID-19 em diferentes regiões geográficas.
Analisar a evolução temporal dos casos confirmados, recuperados e óbitos.
Explorar a relação entre fatores demográficos e a disseminação da doença.
Visualizar os dados por meio de gráficos e mapas interativos para uma melhor compreensão dos resultados.

**Resultados e Conclusões**

Os resultados obtidos fornecem uma visão abrangente sobre a propagação da COVID-19 e suas implicações. Através da análise exploratória, é possível identificar áreas com maior incidência da doença, padrões sazonais, impactos de medidas de contenção e fatores que podem influenciar a disseminação.

**Como Utilizar Este Repositório**

Este repositório contém o código fonte em Python utilizado para realizar a análise exploratória de dados. Os dados utilizados também estão disponíveis no diretório "data". Siga as instruções do README.md para configurar o ambiente e executar o código em sua máquina.

**Contribuições**

Contribuições para a melhoria deste projeto são bem-vindas. Sinta-se à vontade para enviar pull requests com correções de bugs, sugestões de novas análises ou melhorias na documentação.
**Contato**
Para mais informações ou dúvidas relacionadas a este projeto, entre em contato com [Gabriel Veloso] via e-mail: [velosogabriel5@gmail.com].
