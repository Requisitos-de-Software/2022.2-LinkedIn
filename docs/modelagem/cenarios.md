# Cenarios

## Histórico de Versão

| Versão | Data | Descrição | Autor | Revisor |
|--------|------|-------|-----------| ------- |
| 0.1 | 09/12/2022 | Criação do Documento | Samuel Macedo | Breno Henrique |
| 0.2 | 10/12/2022 | implementação dos cenários 3 a 8 | Samuel Macedo | Breno Henrique |

## 1.Introdução

&emsp;&emsp;A criação de Cenários na modelagem de requisitos, é uma etapa importante e de grande valor. A modelagem de requisitos por Cenários, é utilizada como uma forma de compreender melhor, as interações entre o usuário e sistema , buscando dessa forma obter uma descrição completa de uma atividade que o usuário utiliza.

## 2.Metodologia

|      Elementos      | Respostas |
| :-----------------: | :-------: |
|    **Objetivo**     |     -     |
|    **Contexto**     |     -     |
|     **Atores**      |     -     |
|    **Recursos**     |     -     |
|     **Exceção**     |     -     |
|    **Episódios**    |     -     |
| **Rastreabilidade** |     -     |

## 3.Cenarios

### C01: Criar conta

| elementos |respostas|
|:----------:|----------|
|    **Objetivo**     | - Usuário do linkedin criar uma conta    |
|    **Contexto**     | - Local: Tela de inicio no ícone da sua conta, ou logo depois que baixou na tela de inicio;<br> -  Tempo: 3 a 5 minutos;<br> - Pré-condição: Possuir acesso a internet e aplicativo aberto. |
|     **Atores**      | - Usuário do Linkedin |
|    **Recursos**     | - Dispositivo com acesso à internet;<br>- Dispositivo com bateria <br>- Dispositivo suportado pelo Linkedin |
|     **Exceção**     | - Falta de internet |
|    **Episódios**    | - Ao abrir o aplicativo pela primeira vez o usuário clica em cadastre-se  ou prosseguir com o google; <br>- Usuário clica e coloca seu nome e senha; 
| **Rastreabilidade** | RF01; RF15 |

### C02: entrar em uma conta já existente

| elementos |respostas|
| :----------: |---|
|    **Objetivo**     | - Usuário do Linkedin logar em uma conta já existente |
|    **Contexto**     | - Local: Tela de início no ícone da sua conta;<br> - Tempo: 1 a 2 minutos;<br>- Pré condição: Possuir conta cadastrada. |
|     **Atores**      | - Usuário do linkedin |
|    **Recursos**     | - Dispositivo com acesso à internet;<br> - Dispositivo com bateria
|     **Exceção**     | - Falta de internet;<br>- Dispositivo não suporta o Linkedin |
|    **Episódios**    | - ao abrir o aplicativo o usuário clica em entrar no canto inferior central;<br>- Usuário coloca email e senha
| **Rastreabilidade** | RF16 |


### C03: Publicar em seu perfil

| elementos |respostas|
| :----------: |---|
|    **Objetivo**     | - Usuário do linkedin fazer publicações em seu perfil |
|    **Contexto**     | - Local: Tela de perfil;<br> - Tempo: 3 a 5 minutos;<br>- Pré condição: Estar logando em sua conta linkedin. |
|     **Atores**      | - Usuário do linkedin |
|    **Recursos**     | - Dispositivo com acesso à internet;<br> - Dispositivo com bateria
|     **Exceção**     | - Falta de internet;<br>- Dispositivo não suporta o Linkedin <br>- queda do sistema  |
|    **Episódios**    | - Usuário tem o desejo de postar algo em seu perfil;<br>- Usuário clica em publicações no setor inferior central;<br>- Usuário publica o que deseja
| **Rastreabilidade** | RF03 |

### C04: Visualizar publicações de outros usuários

| elementos |respostas|
| :----------: |---|
|    **Objetivo**     | - Usuário do linkedin ver o que outros usuários estão publicando |
|    **Contexto**     | - Local: início;<br> - Tempo: 1 a 3 minutos;<br>- Pré condição: Estar logando em sua conta linkedin <br>- estar seguindo outros usuários. |
|     **Atores**      | - Usuários do linkedin |
|    **Recursos**     | - Dispositivo com acesso à internet;<br> - Dispositivo com bateria
|     **Exceção**     | - Falta de internet;<br>- Dispositivo não suporta o Linkedin <br>- queda do sistema  |
|    **Episódios**    | - Usuário quer ver as publicações dos usuário que segue;<br>- Usuário navega pelo inicio do linkedin;<br>- Usuário vê as publicações dos outros usuários
| **Rastreabilidade** | RF05, RF29 |

### C05: Comunicar com outros usuários

| elementos |respostas|
| :----------: |---|
|    **Objetivo**     | - Usuário do linkedin fazer comunicações com outros usuários |
|    **Contexto**     | - Local: publicações e chats;<br> - Tempo: 1 a 3 minutos;<br>- Pré condição: Estar logando em sua conta linkedin <br>- ter outro usuário para se comunicar. |
|     **Atores**      | - Usuários do linkedin |
|    **Recursos**     | - Dispositivo com acesso à internet;<br> - Dispositivo com bateria
|     **Exceção**     | - Falta de internet;<br>- Dispositivo não suporta o Linkedin <br>- queda do sistema  |
|    **Episódios**    | - Usuário tem o desejo de se comunicar com uma pessoa de uma publicação por meio da publicação ou por meio de um chat privado;<br>- Usuário manda uma mensagem direta ou comenta na publicação;<br>- Usuário se comunica com outros usuários
| **Rastreabilidade** | RF04, RF06, RF07 |

### C06: Visualizar vagas de emprego

| elementos |respostas|
| :----------: |---|
|    **Objetivo**     | - Usuário do linkedin visualizar vagas disponíveis de emprego |
|    **Contexto**     | - Local: vagas localizado no canto inferio direito do aplicativo;<br> - Tempo: 1 a 3 minutos;<br>- Pré condição: Estar logando em sua conta linkedin. |
|     **Atores**      | - Usuários do linkedin |
|    **Recursos**     | - Dispositivo com acesso à internet;<br> - Dispositivo com bateria
|     **Exceção**     | - Falta de internet;<br>- Dispositivo não suporta o Linkedin <br>- queda do sistema  |
|    **Episódios**    | - Usuário quer ver as vagas disponíveis de emprego no dia;<br>- Usuário clica no botão vagas localizado no canto inferior direito;<br>- Usuário encontra vagas relacionadas ao seu perfil
| **Rastreabilidade** | RF09, RF10, RF18 |


### C07: Candidatar a vagas de emprego

| elementos |respostas|
| :----------: |---|
|    **Objetivo**     | - Usuário do linkedin se candidatar nas vagas disponíveis de emprego |
|    **Contexto**     | - Local: vagas localizado no canto inferio direito do aplicativo;<br> - Tempo: 5 a 10 minutos;<br>- Pré condição: Estar logado em sua conta linkedin. |
|     **Atores**      | - Usuários do linkedin |
|    **Recursos**     | - Dispositivo com acesso à internet;<br> - Dispositivo com bateria;<br> - vagas disponíveis
|     **Exceção**     | - Falta de internet;<br>- Dispositivo não suporta o Linkedin; <br>- queda do sistema;<br>- Não ter vagas disponíveis no sistema  |
|    **Episódios**    | - Usuário quer ver as vagas disponíveis de emprego no dia;<br>- Usuário clica no botão vagas localizado no canto inferior direito;<br>- Usuário encontra vagas relacionadas ao seu perfil;<br>- usuário se candidata na vaga.
| **Rastreabilidade** | RF23|

### C08: Visualizar perfis de usuários linkedin

| elementos |respostas|
| :----------: |---|
|    **Objetivo**     | - Usuário do linkedin visualizar o perfil de outro usuário |
|    **Contexto**     | - Local: pesquisar;<br> - Tempo: 2 a 5 minutos;<br>- Pré condição: Estar logado em sua conta linkedin <br>- ter outro usuário para visualizar. |
|     **Atores**      | - Usuários do linkedin |
|    **Recursos**     | - Dispositivo com acesso à internet;<br> - Dispositivo com bateria
|     **Exceção**     | - Falta de internet;<br>- Dispositivo não suporta o Linkedin <br>- queda do sistema  |
|    **Episódios**    | - Usuário tem o desejo de visualizar um perfil de outro usuário;<br>- Usuário pesquisa o perfil que deseja na barra de procurar;<br>- Usuário visualiza o perfil.
| **Rastreabilidade** | RF24, RF05, RF07, RF11 |

## Referências

>SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;

>https://github.com/Requisitos-de-Software