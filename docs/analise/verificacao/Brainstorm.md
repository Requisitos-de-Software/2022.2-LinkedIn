# Verificação do Observação

## Histórico de versões
| Data       | Versão | Descrição            | Autor                                         | Revisor                                      |
| ---------- | ------ | -------------------- | --------------------------------------------- | -------------------------------------------- |
| 09/01/2022 | 1.0    | Criação do documento | Letícia | Breno |
## 1. Introdução

O objetivo do presente documento é apresentar a verificação da Observação do Grupo 5 - [Google Maps](https://requisitos-de-software.github.io/2022.2-GoogleMaps/)  desenvolvido no nosso projeto e analisado por meio da técnica de inspeção, seguindo o planejamento detalhado na página de [Planejamento da verificação](../planejamento.md)
<br>A técnica de verificação tem como intuito definir se o modelo atende às expectativas estabelecidas pelo cliente, tendo como base os requisitos elicitados pelos engenheiros de software.


## 2. Preparação

&emsp;&emsp;Para fazer a inspeção vamos utilizar um "checklist" com algumas perguntas com base nas referências utilizadas para a elaboração do artefato e os critérios de avaliação do artefato adotados na disciplina, dessa forma, poderemos analisar se este está correto com base nessas perguntas. Quando o critério for atentido, terá um "check" confirmando e quando não estiver , terá um "X" dizendo que não está correto. Conforme a legenda abaixo:

- ✅ : Atendido
- ❌ : Não Atendido

&emsp;&emsp;Além disso, após identificarmos os erros presentes no artefato, iremos consertá-los, assim produzindo uma segunda versão do artefato.
## 3. Checklist

<figcaption align="center">Tabela 1: Requisitos Elicitados</figcaption>

| Descrição                                                                                             | Tipo  | id  |
| ----------------------------------------------------------------------------------------------------- | ----- | --- |
| Deve ser possível ver mapa                                                                            | RF01  | 01  |
| Deve ser possível dar Zoom In                                                                         | RF02  | 01  |
| Deve ser possível dar Zoom Out                                                                        | RF03  | 01  |
| Deve ser possível ver nome de ruas no mapa                                                            | RF04  | 01  |
| Deve ser possível ver localizações no mapa                                                            | RF05  | 01  |
| Deve ser possível selecionar localizações do mapa                                                     | RF06  | 01  |
| Deve ser possível ver distância da localização selecionada até o usuário                              | RF07  | 01  |
| Deve ser possível ver pontos de ônibus no mapa                                                        | RF08  | 01  |
| Deve ser possível ver saídas e entradas de metrô                                                      | RF09  | 01  |
| Deve ser possível pesquisar por localizações                                                          | RF10  | 01  |
| Deve ser possível ver localização destacada no mapa do local pesquisado                               | RF11  | 01  |
| Deve ser possível ligar para a localização pesquisada caso disponível                                 | RF12  | 01  |
| Deve ser possível selecionar filtros de pesquisa                                                      | RF13  | 01  |
| Deve ser possível ver lista de localizações filtradas                                                 | RF14  | 01  |
| Deve ser possível, caso seja restaurante, filtrar por opção de comida                                 | RF15  | 01  |
| Deve ser possível, caso seja restaurante, ver cifrões para demonstrar a faixa de preço do restaurante | RF16  | 01  |
| Deve ser possível ver horário de funcionamento da localização quando disponível                       | RF17  | 01  |
| Deve ser possível ver status de funcionamento da localização quando disponível                        | RF18  | 01  |
| Deve ser possível ver comentários de localizações                                                     | RF19  | 01  |
| Deve ser possível filtrar os comentários de localizações                                              | RF20  | 01  |
| Deve ser possível fazer comentários sobre localizações                                                | RF21  | 01  |
| Deve ser possível ver nota de localizações                                                            | RF22  | 01  |
| Deve ser possível dar uma nota a uma localização                                                      | RF23  | 01  |
| Deve ser possível ver fotos da localização pesquisada                                                 | RF24  | 01  |
| Deve ser possível navegar no modo street view do mapa                                                 | RF25  | 01  |
| Deve ser possível traçar rotas entre localizações                                                     | RF26  | 01  |
| Deve ser possível ver distância entre localizações após traçar rota                                   | RF27  | 01  |
| Deve ser possível selecionar meio de locomoção recomendado                                            | RF28  | 01  |
| Deve ser possível selecionar meio de locomoção a pé                                                   | RF29  | 01  |
| Deve ser possível selecionar meio de locomoção de carro                                               | RF30  | 01  |
| Deve ser possível selecionar meio de locomoção bicicleta                                              | RF31  | 01  |
| Deve ser possível selecionar meio de locomoção voos quando disponível                                 | RF32  | 01  |
| Deve ser possível após traçar rota ver horário de deslocamento                                        | RF33  | 01  |
| Deve ser possível, caso selecionado ônibus para a rota, ver linhas disponíveis                        | RF34  | 01  |
| Deve ser possível, caso selecionado ônibus para a rota, ver próximo horário de saída                  | RF35  | 01  |
| Deve ser possível, caso selecionado ônibus para a rota, ver preço da passagem                         | RF36  | 01  |
| Deve ser possível iniciar rota e acompanhamento pelo mapa                                             | RF37  | 01  |
| Deve ser possível escutar comandos de voz após rota iniciada                                          | RF38  | 01  |
| Deve ser possível, caso a localização seja perigosa, um aviso deve aparecer para o usuário            | RF39  | 01  |
| As rotas devem ser traçadas de acordo com as políticas de trânsito de cada cidade                     | RNF01 | 01  |
| Devem ser traçadas áreas de alerta de acordo com o perigo de cada região                              | RNF02 | 01  |
| O aplicativo deve funcionar 24h por dia                                                               | RNF03 | 01  |
| O aplicativo deve estar disponível tanto para Android como IOS                                        | RNF04 | 01  |
| O aplicativo deve ter um sistema de proteção as informações                                           | RNF05 | 01  |

<figcaption align="center">Fonte: Alexia</figcaption>

</center>

## 4. Inspeção Observação

&emsp;&emsp;A checklist após inspeção do [Brainstorm](../../elicitacao/brainstorm.md) pode ser encontrada abaixo:

<center>

|ID|Questão| Inspeção |
|-----------|-------------|-------------|
| 1 | O Artefato contem o objetivo do uso da técnica? | ✅ |
| 2 | O Artefato apresenta a metodologia? | ✅ |
| 3 | O documento está gramaticalmente correto?| ✅ |
| 4 | O documento apresenta data, hora e participantes da reunião de brainstorm? |✅ |
| 5 | O artefato está bem estruturado? |✅ |
| 6 | Conseguiu extrair Requisitos da técnica? |✅ |
| 7 | Apresenta uma tabela com os requisitos extraídos? |✅ |


</center>


### 3.1 Resultados da inspeção
&emsp;&emsp; A partir da inspeção do artefato verificamos que o documento atende com 7 dos critérios de avaliação definidos, dessa forma apresentando uma taxa e acertos de 100% como podemos ver a partir do gráfico abaixo:

<center>

![brainstormverificacao](https://user-images.githubusercontent.com/72623771/211176682-7306eeb1-d38c-4a79-abc8-5552d3875417.png)

</center>

<figcaption align='center'>
    <b>Figura 1: Gráfico Storytelling  </b>
    <br><small> Fonte: Elaboração Própria </small>
</figcaption>


&emsp;&emsp; A partir da inspeção do artefato verificamos que o documento atendia com todos os critérios de avaliação definidos na checklist, não precisando ser modificado ou alterado.


## Referências

> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 23. 1º/2022. Material apresentado para a disciplina de IHC no curso de Engenharia de Software da UnB, FGA.
