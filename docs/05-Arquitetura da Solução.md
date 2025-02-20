# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de Classes

![Class Diagram0](https://user-images.githubusercontent.com/91221827/161859264-c7aa24a6-477b-4b98-a9bc-7e7e9595cea3.png)

O diagrama de classes ilustra graficamente como será a estrutura do software, e como cada uma das classes da sua estrutura estarão interligadas. Essas classes servem de modelo para materializar os objetos que executarão na memória.

Neste Diagrama de Classes é possível observar as seguintes informações: o site Simbora possui zero ou n, vários (0..*) usuários e um (1) usuário pertence a 1 site Simbora. As subclasses PromoterArtista e Cliente, cada uma com seus atributos específicos, herdam os atributos da superclasse Usuário.Já a classe Evento está com relação de associação com a classe Simbora!, sendo que a classe Simbora! divulga zero ou n, vários (0..*) Eventos e um (1) Evento pertence a classe Simbora!. Um (1) Evento tem 1 ou vários (1..*) Convites, mas 1 Convite só pode ser de 1 Evento, e 1 Convite não existe sem 1 Evento por isto o losango preenchido, sendo uma relação de Agregação por Composição. Um (1) cliente pode ter zero a vários convites (0..*), mas 1 convite só pode ser de 1 cliente, e a classe Convite não existe sem a Classe Cliente, sendo esta também uma relação de Agregação por Composição. O Cliente escolhe participar de 1 Evento e assim é gerado 1 convite. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Classes”.

> - [Diagramas de Classes - Documentação da IBM](https://www.ibm.com/docs/pt-br/rational-soft-arch/9.6.1?topic=diagrams-class)
> - [O que é um diagrama de classe UML? | Lucidchart](https://www.lucidchart.com/pages/pt/o-que-e-diagrama-de-classe-uml)

## Modelo ER

O Modelo ER representa através de um diagrama como as entidades (coisas, objetos) se relacionam entre si na aplicação interativa.]

As referências abaixo irão auxiliá-lo na geração do artefato “Modelo ER”.

<img src="img\diagramaer.png">

> - [Como fazer um diagrama entidade relacionamento | Lucidchart](https://www.lucidchart.com/pages/pt/como-fazer-um-diagrama-entidade-relacionamento)

## Esquema Relacional

O Esquema Relacional corresponde à representação dos dados em tabelas juntamente com as restrições de integridade e chave primária.
 
As referências abaixo irão auxiliá-lo na geração do artefato “Esquema Relacional”.

<img src="img\sistemarelacional.png">

> - [Criando um modelo relacional - Documentação da IBM](https://www.ibm.com/docs/pt-br/cognos-analytics/10.2.2?topic=designer-creating-relational-model)

## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.

## Hospedagem

Explique como a hospedagem e o lançamento da plataforma foi feita.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)
