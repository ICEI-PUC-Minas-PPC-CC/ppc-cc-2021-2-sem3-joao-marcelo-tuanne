# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

A definição exata do problema e os pontos mais relevantes a serem tratados neste projeto foi consolidada com a participação dos representantes da Fênix Fundação em pesquisas por eles realizadas junto a Escola Municipal Ismael Junqueira de Souza e Escola Estadual Antônio Magalhães Alves (Polivalente), ambas de ensino fundamental I e II do município de São Lourenço, junto aos alunos que apresentaram as dificuldades de aprendizagem previamente relatadas. Os detalhes levantados nesse processo foram consolidados na forma de personas e histórias de usuários.

## Personas

As personas levantadas durante o processo de entendimento do problema são apresentadas na Figuras que se seguem.

![Carina Furtado](img/carina-furtado.jfif)

Carina Furtado tem 10 anos de idade, é estudante do Ensino fundamental I. Utiliza os aplicativos Instagram, TikTok e YouTube. Suas motivações são pelas causas sociais e a Greta Thunberg. Frustrações: Diferenciação de classes sociais; Falta de acolhimento e incentivo; Sistema educacional. Seus hobbies são: Esportes; Artes.

![Elton Campelo](img/elton-campelo2.jfif)

Elton Campelo tem 13 anos de idade, é estudante do Ensino fundamental II. Utiliza os aplicativos Discord, Twitch e YouTube. Suas motivações são Richard Tyler Blevins e LeBron James . Frustrações: Disciplinas escolares; Desamparo emocional e psicológico; Falta de acolhimento e incentivo. Seus hobbies são: Jogos online; Luta; Basquete.

![Fausto Goulart](img/fausto-goulart.jfif)

Fausto Goulart tem 14 anos de idade, é estudante do Ensino fundamental II. Utiliza os aplicativos TikTok, Twitch, Discord e Instagram. Suas motivações são Neymar Jr. e Michael Phelps . Frustrações: Disciplinas escolares; Insegurança quanto ao desempenho escolar; Falta de acolhimento e incentivo. Seus hobbies são: Jogos FPS; Tênis de mesa; Nataçãp; Futebol.


Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

A partir da compreensão do dia a dia das personas identificadas para o projeto, foram registradas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Carina Furtado | Ter um desempenho melhor na escola | Aprender e melhorar na disciplina de português |
|Elton Campelo | Ampliar meu vocabulário | Poder ter uma melhor escrita |
|Fausto Goulart | Compreender melhor os princípios da Matemática | Conseguir resolver exercícios mais complexos |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

O escopo funcional do projeto é definido por meio dos requisitos funcionais que descrevem as possibilidades interação dos usuários, bem como os requisitos não funcionais que descrevem os aspectos que o sistema deverá apresentar de maneira geral. Estes requisitos são apresentados a seguir.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos do projeto, identificando a prioridade em que os mesmos devem ser entregues.

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Criação de um aplicativo mobile (Android) de jogos educacionais | ALTA |
|RF-002| O aplicativo deve apresentar um menu inicial para seleção do nível das atividades a serem executadas pelos alunos   | MÉDIA |
|RF-003| O aplicativo deve permitir ao usuário interação com imagens e textos apresentados  | MÉDIA |
|RF-004| O aplicativo pode oferecer suporte para emissão de som quando o aluno clicar em uma letra, palavra, número, etc  | MÉDIA |
|RF-005| O aplicativo pode permitir aplicação de teste simples, com o retorno de uma avaliação de aproveitamento  | ALTA |
|RF-006| O aplicativo pode oferecer a possibilidade de testes em formato de jogos para formação de palavras e/ou cálculos  | MÉDIA |

### Requisitos não Funcionais

A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O arquivo instalável do aplicativo deve ser compartilhado com a instituição para utilização | ALTA |
|RNF-002| O aplicativo será utilizado em somente um aparelho mobile com SO Android que será disponibilizado para as atividades de ensino  |  ALTA |
|RNF-003| O aplicativo deve ter bom nível de contraste entre os elementos da tela em conformidade   |  MÉDIA |

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 22/12/2021 |
|02| O aplicativo deve se restringir às tecnologias básicas fornecidas pelo App Inventor |
|03| A equipe não pode subcontratar o desenvolvimento do trabalho |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
