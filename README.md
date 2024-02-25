# Análise Exploratória de Dados da Zuber


### Descrição do Projeto
Como analista da Zuber, nosso objetivo é identificar padrões vitais nos dados disponíveis, compreendendo as preferências dos passageiros e os impactos de variáveis externas nas corridas. Esta análise se concentra em examinar informações obtidas e testar hipóteses relevantes para a Zuber, aplicando técnicas de análise de dados em Python.

### Inicialização
Nossa análise começa importando bibliotecas necessárias como pandas, matplotlib e scipy.stats. Em seguida, carregamos os dados CSV fornecidos e realizamos uma renomeação de colunas para facilitar a análise.

### Análise Exploratória de Dados
Realizamos uma análise exploratória dos dados, identificando as 10 principais empresas de táxi por número de corridas e os top 10 bairros por número médio de viagens. Utilizamos visualizações de gráficos de barras para facilitar a compreensão desses dados.

### Teste de Hipóteses
Formulamos hipóteses sobre o impacto do clima nas durações das viagens e realizamos um teste t independente para comparar as médias de duração das viagens em sábados chuvosos e não chuvosos. Os resultados do teste nos permitem tirar conclusões sobre a diferença nas durações médias das viagens entre esses dois grupos.

### Conclusão
Com base nos resultados do teste de hipóteses, concluímos que há evidências estatísticas suficientes para rejeitar a hipótese nula, sugerindo que as durações médias das viagens em sábados chuvosos diferem estatisticamente das durações em sábados não chuvosos.

Este projeto fornece insights valiosos para a Zuber, permitindo uma melhor compreensão do comportamento dos passageiros e aprimorando os serviços oferecidos pela empresa.
