# Plano de Metodologias

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| --- | --- | --- | --- | --- |
| 0.1 | 08/11/2022 | Criação do Artefato | Mateus Franco | Guilherme Barbosa |
| 0.2 | 08/11/2022 | Desenvolvimento do Artefato | Mateus Franco | Guilherme Barbosa |
| 0.3 | 18/11/2022 | Ajustes em Políticas e Regras | Letícia Aires | Guilherme Barbosa |

## 1. Introdução

A fim de se atingir resultado previsto ao projeto, elaboraram-se metodologias organizacionais a fim de guiar ações e padronizar processos. Desse modo, entregas de resultado são apresentadas de forma mais rápida e sistemática, assim como a dinâmica do grupo. 

Nesse sentido, o presente documento visa informar metodologias, processos e práticas a serem utilizadas ao longo da avaliação.

## 2. Metodologias

### 2.1. Gerenciamento de Projetos (SCRUM)

Com o fito de tornar mais eficiente o gerenciamento da equipe, optou-se pela utilização de metodologias ágeis, em especial o SCRUM, o qual se fundamenta nos seguintes princípios:

* Desenvolvimento iterativo com base em sprints
* Priorização orientada a valor
* Estabelecimento de prazos
* Colaboração
* Controle empírico do processo
* Auto-organização

Desse modo, em se estabelecendo períodos iterativos com prazos e objetivos determinados, são quantificados o andamento e as metas do projeto. Nessa ótica, a dinâmica é otimizada e se pode observar colaboração em grupo e entregas de valor quantitativo mais expressivo.

## 3. Políticas e regras

### 3.1. Política de Commit

Os commits realizados devem ser pequenos e significativos, de forma que cada um possua uma única funcionalidade (commits atômicos). Ademais, estes devem seguir estrutura padronizada pré-acordada. Isto é, deve-se realizar o commit da seguinte forma:

#### Estrutura

<tipo> (#n° da issue): descrição sucinta do commit em letras minúsculas
Co-authored-by: user <email>

#### Tipos:

* 🔁 quando alguma alteração for feita `:repeat:`
* 🆒 quando melhorias de formato/estrutura do código `:cool:`
* 📝 quando escrever documentação `:pencil:`
* 🐛 quando consertar um problema `:bug:`
* 🆕 quando adicionar algum arquivo `:new:`
* 🔥 quando remover código ou arquivos `:fire:`
* 💚 quando consertar problemas de Integração Contínua `:green_heart:`
* ⬆️ quando realizar o upgrade de dependências `:arrow_up:`
* ⬇️ quando realizar downgrade de dependências `:arrow_down:`

#### Exemplo de commit
`🔁(#10): inserção de novo tópico`

### 3.2. Política de Branch

#### Main

A branch main deve abarcar somente o código já testado, versionado e revisado, ou seja, pronto para ser entregue ao usuário final. Alem disso, a branch deve originar da branch develop por meio de Pull Requests.

#### Development

Nesta branch consta a versão mais atualizada do código e deve sempre se manter atualizada com a main. Vale ressaltar que esta branch é base para as branches feature.

#### Feature

As branches feature são mecanismos temporários de desenvolvimento de código com função específica de cumprir determinado objetivo de uma issue, assim, a branch development deve ser sua origem e fim.

## 4. Referências

> COHN, Mike. **Desenvolvimento de Software com Scrum**: Aplicando Métodos Ágeis com Sucesso. 2021. Disponível em: [https://books.google.com.br/books](https://books.google.com.br/books?hl=pt-BR&lr=&id=gbgpDwAAQBAJ&oi=fnd&pg=PP1&dq=scrum&ots=LKeHqsPUgZ&sig=K6qMsH0Oq#v=onepage&q=scrum&f=false). Acesso em: 10 de jul. de 2022.
