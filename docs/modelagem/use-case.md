# Casos de Uso

## Histórico de Versão

| Versão | Data | Descrição | Autor | Revisor |
|--------|------|-------|-----------| ------- |
| 0.1 | 02/12/2022 | Criação do Documento | Letícia Aires | Mateus Franco |
| 0.2 | 05/12/2022 | Adição de Conteúdo | Letícia Aires | Mateus Franco |
| 0.3 | 09/12/2022 | Adição do diagrama UML | Mateus Franco | Letícia Aires |
| 0.4 | 10/12/2022 | Adição das especificações de casos de uso | Mateus Franco | Letícia Aires |

## 1. Introdução

Os Casos de Uso consistem no detalhamento dos atores de um sistema e de sua interação com esse, ou seja, por meio do Diagrama de Caso de Uso UML (linguagem de modelagem unificada), são definidos os requisitos, escopo, bem como as interações padrão entre usuário e sistema e, por fim, também é modelado fluxo de acontecimentos.

## 2. Metodologia

Para a representação dos casos de uso do aplicativo LinkedIn, foi projetado um diagrama UML, por meio do software Figma, aonde foi representado os diversos cenários de uso na perspectiva dos usuários. 

Dessa forma, sistema e atores foram modelados com o objetivo de descrever atividades para atingir a meta de casos de uso.

## 3. Passos para Construção do Diagrama 

1. Inserção da forma de sistema;

2.  Adição de atores;

3.  Inserção de casos de uso;

4. Categorização de casos de uso;

5. Criação de relacionamentos entre atores e casos de uso.

## 4. Representação do Diagrama

| Símbolos | Descrição | Representação | 
| ------- | ----------- | -----------  |
| Caso de Uso | Diferentes funcionalidades que um usuário pode realizar | Formato oval na horizontal |
| Atores |  Pessoas que realmente implementam os casos de uso |  Bonecos palito |
| Associações | Nos diagramas complexos, é importante saber quais atores estão associados a quais casos de uso. | Linha entre atores e casos de uso. |
| Caixa de limite do sistema | Caixa que define um escopo do sistema para os casos de uso | Caixa |
| Pacote | Forma UML onde se colocam diferentes elementos em grupos | Pastas de arquivos |

## 5. Diagrama de Casos de Uso UML

Abaixo, representado pela figura 01, segue a representação do diagrama de casos de uso geral do aplicativo LinkedIn.

<center>
![use-case-v2](https://user-images.githubusercontent.com/71900095/206858632-edbfbaab-a98e-465b-b392-052a1010b3dc.png)
</center>

<h6 align = "center"> Figura 01: Diagrama UML de casos de uso </h6>
<h6 align = "center"> Fonte: Mateus Franco </h6>

## 6. Especificação de Casos de Uso

Abaixo, representado pelas tabelas 01 à 08, segue as especificações para cada caso de uso do diagrama UML de casos de uso.

#### 6.1 Caso de Uso 01: Fazer Login

| Caso de Uso 01 | Informações |
| ---- | ----------- | 
| Descrição | O usuário, ao iniciar o aplicativo, pode efetuar o login para acessar sua conta no aplicativo |
| Pré-Condições | - Ter o aplicativo instalado  <br> - Possuir uma conta criada <br> - Possuir acesso à internet |
| Atores | Usuários cadastrados na plataforma |
| Fluxo | - Usuário abre o aplicativo do LinkedIn <br> - Insere suas credenciais de acesso <br> - Clica em **_Entrar_**
| Pós-Condições  | O usuário terá acesso as funcionalidades e ferramentas do aplicativo

<h6 align = "center"> Tabela 01: Especificação de casos de uso: Fazer Login </h6>

#### 6.2 Caso de Uso 02: Alterar Perfil de Usuário

| Caso de Uso 02 | Informações |
| ---- | ----------- | 
| Descrição | O usuário deve ser capaz de realizar alterações de informações em seu perfil próprio |
| Pré-Condições | Estar logado no aplicativo |
| Atores | Usuários cadastrados na plataforma |
| Fluxo | 1. O usuário clica em seu nome de perfil localizado na parte superior do aplicativo <br> 2. O usuário clica na área aonde deseja alterar as informações <br>  3. O usuário realiza as alterações <br> 4. O usuário clica em **_salvar alterações_** |
| Pós-Condições  | O usuário poderá ver suas informações alteradas |

<h6 align = "center"> Tabela 02: Especificação de casos de uso: Alterar perfil de usuário </h6>

#### 6.3 Caso de Uso 03: Interagir com outros usuários

| Caso de Uso 03 | Informações |
| ---- | ----------- | 
| Descrição | O usuário deve ser capaz de realizar interações com outros usuários cadastrados |
| Pré-Condições | Estar logado no aplicativo |
| Atores | Usuários cadastrados na plataforma |
| Fluxo | 1. O usuário clica em **_Minha Rede_** <br> 2. O usuário clica em **_Conexões_** <br> 3. O usuário seleciona a forma de interação que deseja |
| Pós-Condições | O usuário terá suas interações com outros usuários realizadas com sucesso |

<h6 align = "center"> Tabela 03: Especificação de casos de uso: Interagir com outros usuários </h6>

#### 6.4 Caso de Uso 04: Realizar publicações

| Caso de Uso 04 | Informações |
| ---- | ----------- | 
| Descrição | O usuário deve ser capaz de realizar publicações em seu perfil |
| Pré-Condições | Estar logado no aplicativo |
| Atores | Usuários cadastrados na plataforma |
| Fluxo | 1. O usuário clica em **_Começar publicação_** <br> 2. O usuário realiza a publicação da forma que deseja <br> 3. O usuário salva as informações da publicação |
| Pós-Condições | O usuário terá sua publicação realizada com sucesso |

<h6 align = "center"> Tabela 04: Especificação de casos de uso: Realizar publicações </h6>

#### 6.5 Caso de Uso 05: Interagir com publicações de outros usuários

| Caso de Uso 05 | Informações |
| ---- | ----------- | 
| Descrição | O usuário deve ser capaz de realizar interações com publicações de outros usuários |
| Pré-Condições | Estar logado no aplicativo |
| Atores | Usuários cadastrados na plataforma |
| Fluxo | 1. O usuário clica em **_Inicio_** para visualizar as publicações de outros usuários <br> 2. O usuário clica na interação que deseja: _Adicionar reação, comentar, compartilhar ou enviar_ |
| Pós-Condições | O usuário terá suas interações com publicações de outros usuários realizadas com sucesso |

<h6 align = "center"> Tabela 05: Especificação de casos de uso: Interagir com publicações de outros usuários </h6>

#### 6.6 Caso de Uso 06: Visualizar notificações

| Caso de Uso 06 | Informações |
| ---- | ----------- | 
| Descrição | O usuário deve ser capaz de visualizar suas notificações mais recentes |
| Pré-Condições | Estar logado no aplicativo |
| Atores | Usuários cadastrados na plataforma |
| Fluxo | 1. O usuário clica em **_Notificações_** <br> |
| Pós-Condições | O usuário poderá visualizar todas as notificações das mais recentes para as mais antigas |

<h6 align = "center"> Tabela 06: Especificação de casos de uso: Visualizar notificações </h6>

#### 6.7 Caso de Uso 07: Visualizar vagas de emprego

| Caso de Uso 07 | Informações |
| ---- | ----------- | 
| Descrição | O usuário deve ser capaz de visualizar diversas vagas de emprego |
| Pré-Condições | Estar logado no aplicativo |
| Atores | Usuários cadastrados na plataforma |
| Fluxo | 1. O usuário clica em **_Vagas_** <br>  2. O usuário poderá realizar filtros de pesquisa para o tipo de vaga que deseja|
| Pós-Condições | O usuário poderá visualizar todas as vagas de emprego de acordo com os filtros aplicados |

<h6 align = "center"> Tabela 07: Especificação de casos de uso: Visualizar vagas de emprego </h6>

#### 6.8 Caso de Uso 08: Visualizar notícias recentes

| Caso de Uso 08 | Informações |
| ---- | ----------- | 
| Descrição | O usuário deve ser capaz de visualizar as principais notícias com base na indicação para seu perfil |
| Pré-Condições | Estar logado no aplicativo |
| Atores | Usuários cadastrados na plataforma |
| Fluxo | 1. O usuário clica em **_Início_** <br>  2. No canto superior esquerda, o usuário poderá expandir entrando em **_LinkedIN notícias_** |
| Pós-Condições | O usuário poderá visualizar todas as notícias recentes baseadas em seu perfil |

<h6 align = "center"> Tabela 08: Especificação de casos de uso: Visualizar notícias recentes </h6>

## 7. Referência bibliográfica
> * Diagrama de caso de uso UML: o que é, como fazer e exemplos. Disponível em: https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml
