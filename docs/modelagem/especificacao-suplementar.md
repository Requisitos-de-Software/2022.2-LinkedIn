# Especficação suplementar

## Histórico de Versões

**Data** | **Versão** | **Descrição** | **Autor(es/as)** | **Revisor** |
:---: | :---: | :---: | :---: | :---: |
10/12/2022 | 0.1 | Abertura do documento | Guilherme Barbosa | Pedro Moraes |

## 1. Introdução

A finalidade da Especificação suplementar é definir os requisitos não-funcionais de um sistema. É complementar ao artefato de [casos de uso](../modelagem/casos-de-uso.md), pois, juntos, são definidos os requisitos de software, funcionais e não funcionais.

## 2. Metodologia

Para definir este artefato, foi utilizado o sistema FURPS+ para definir os requisitos não-funcionais. Este modelo de definição categoriza os requisitos de acordo com os atributos de qualidade de software. As categorias são:

### **F - Funcionalidade (Functionality):** 
São os principais requisitos funcionais do produto. Os que possuem impacto arquitetural. Podem incluir:

- Conjunto de recursos 
- Recursos 
- Segurança.

### **U - Usabilidade (Usability):** 
Considera os aspectos de interatividade, design e experiência de uso. Podem incluir: 

- Fatores humanos 
- Estética
- Consistência na interface com o usuário 
- Ajuda on-line e sensível ao contexto 
- Assistentes e agentes
- Documentação do usuário 
- Materiais de treinamento

### **R - Confiabilidade (Reliability):** 
Diz respeito à disponibilidade do sistema, precisão de cálculos e tolerância a falha. Podem incluir:

- Frequência e gravidade de falha 
- Possibilidade de recuperação 
- Possibilidade de previsão 
- Exatidão 
- Tempo médio entre falhas

### **P - Desempenho (Perfomance):** 
Diz respeito à capacidade do sistema em processar tarefas com o tempo de resposta de funcionalidades, localização, encerramento e restauração de backups e falhas. Podem incluir:
    
- Velocidade
- Eficiência
- Disponibilidade
- Exatidão
- Taxa de transferência
- Tempo de resposta
- Tempo de recuperação
- Uso de recurso
  
### **S - Suportabilidade (Supportability):** 
Está relacionado à capacidade do sistema em ser testado, adaptável, mantido, compatibilizado, parametrizado, escalado, internacionalizado e implantado. Podem incluir:

- Possibilidade de teste
- Extensibilidade
- Adaptabilidade
- Manutenibilidade
- Compatibilidade
- Possibilidade de configuração
- Possibilidade de serviço
- Possibilidade de instalação
- Possibilidade de localização (internacionalização)
  
### **+ (Mais)**
O "+" relacionado no modelo FURPS+, inclui alguns requisitos como:

- **Requisitos de design:** Relacionado ao projeto do sistema. Como especificar o BD que
será utilizado.

- **Implementação:** Especifica restrições de implementação, como uso de
bibliotecas nativas ou de terceiros.

- **Interface:** Especifica integrações e acessos externos. Por exemplo,
integração via WS, REST etc.

- **Físico:** Determina restrições de hardware e implantação, por
exemplo, HD, RAM etc.

## 3. Resultado

### 3.1 Funcionalidades
Os requisitos funcionais estão definidos por meio dos [Casos de Uso](casos-de-uso.md).

### 3.2 Usabilidade
**Resposta instântanea em troca de mensagens**

Durante as conversas entre usuários por meio de mensagens disponíveis no Linkedin, o recebimento e envio de mensagens deve ser instantâneo, para que haja uma troca de informações fluída e imediata.

### 3.3 Confiabilidade
**Estabilidade**

O Linkedin prioriza a estabilidade do conteúdo textual dos posts em detrimento dos vídeos ou imagens.

### 3.4 Desempenho
**Comunicação com o servidor**

O sistema deve ter um tempo de comunicação com o servidor de no máximo 10 segundos.

Rastro: [Brainstorm](../elicitacao/brainstorm.md)

**Armazenamento da aplicação (aplicativo)**

O usuário deverá possuir um espaço de 23.77MB para instalar o aplicativo em um dispositivo mobile.

**Capacidade**

O servidor do Linkedin deverá ser capaz de suportar milhares de usuários cadastrados, bem como suas postagens.

O servidor do Linkedin deverá ser capaz de suportar todas as ofertas de emprego cadastradas pelas empresas e/ou usuários.

O servidor do Linkedin deverá ser capaz de suportar todas as trocas de mensagens entre os usuários.
### 3.5 Suportabilidade
**A compatibilidade com o Linkedin aplicativo:**

iPhone e iPad - iTunes App Store

  - Apenas dispositivos Apple de 64 bits rodando o iOS 13.0 ou superior são suportados.

Android - Google Play

  - Apenas dispositivos com Android Oreo (8.0 / API nível 26) ou superior são suportados.

Rastro: [Brainstorm](../elicitacao/brainstorm.md)

**Internacionalização**

O Linkedin deverá estar disponível em 26 idiomas.

## 4. Referências
> GOIS, Samily; SOBRINHO, Francisco. Projeto de Software Floricultura Beija-Flor Especificação Suplementar. Disponível em: https://aprender3.unb.br/pluginfile.php/2307514/mod_resource/content/1/Especificacao_Suplementar_Exemplo.pdf. Acesso 10 dez. 2022.

> SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 13. Disponível em: https://aprender3.unb.br/pluginfile.php/2307510/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Acesso 10 dez. 2022.

> Rational Software Corporation. Conceitos: Requisitos. Disponível em: https://www.cin.ufpe.br/~rls2/processo_tg/Metodologia%20S&B/workproducts/resources/co_req.htm. Acesso 10 dez. 2022.

> Técnicas de arquitetura para trabalhar com requisitos de sistema. Disponível em: https://www.rcelebrone.com/2020/06/tecnicas-arquitetura-requisitos-sistema.html. Acesso 10 dez. 2022. 