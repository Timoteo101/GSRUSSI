# GSRUSSI
# Mission Control AI

## Descrição do Projeto

O Mission Control AI é um sistema de monitoramento de uma missão espacial simulada. O programa analisa dados coletados em diferentes ciclos operacionais e avalia o estado geral da missão com base em cinco áreas críticas, como, temperatura interna, Comunicação com a base, Sistema de energia, Suporte de oxigênio, Estabilidade operacional.

Para cada ciclo, o sistema identifica possíveis falhas, calcula uma pontuação de risco e gera recomendações automáticas para auxiliar a tomada de decisão.

Objetivo

O objetivo do projeto é demonstrar a aplicação de estruturas de programação em Python, utilizando:

* Variáveis
* Listas
* Funções
* Estruturas condicionais
* Estruturas de repetição
* Cálculo de médias
* Análise de dados
* Geração automática de relatórios

Os dados são armazenados em uma matriz chamada dados_missao, onde cada linha representa um ciclo de monitoramento.

Critérios de Avaliação:
 Temperatura:
* Normal: 18°C a 30°C
* Atenção: abaixo de 18°C ou entre 31°C e 35°C
* Crítico: acima de 35°C

Comunicação:
* Normal: 60% ou mais
* Atenção: entre 30% e 59%
* Crítico: abaixo de 30%

Energia:
* Normal: 50% ou mais
* Atenção: entre 20% e 49%
* Crítico: abaixo de 20%

Oxigênio
* Normal: 90% ou mais
* Atenção: entre 80% e 89%
* Crítico: abaixo de 80%

Estabilidade Operacional
* Normal: 70% ou mais
* Atenção: entre 40% e 69%
* Crítico: abaixo de 40%

Sistema de Pontuação
Cada indicador recebe uma pontuação de risco:
* Normal = 0 pontos
* Atenção = 1 ponto
* Crítico = 2 pontos

A soma dos pontos determina a classificação do ciclo.

Classificação do Ciclo

0 a 2  = Missão Estável    
3 a 5   = Missão em Atenção 
6 ou mais = Missão Crítica    

Recomendações Automáticas
O sistema gera recomendações de acordo com a situação identificada , com manter operação normal, verificar sistema de controle térmico, preparar plano de contingência e Ativar modo de segurança da missão.

Relatório Final
Ao término da execução, o programa apresenta:

* Quantidade de ciclos analisados
* Média de cada indicador
* Ciclo mais crítico
* Maior pontuação de risco encontrada
* Risco médio da missão
* Quantidade de ciclos críticos
* Tendência da missão (melhora, piora ou estabilidade)
* Área mais afetada
* Classificação final da missão
* Conclusão geral da operação

Tecnologias Utilizadas:
Linguagem Python, estruturas básicas da programação, programação procedural e análise de dados simulados.

