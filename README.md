# mongoDB-vs-couchDB
Trabalho comparativo que envolve implementação e teste de carga de duas tecnologias relacionadas ao armazenamento de dados: MongoDB x CouchDB.

Disciplina: Banco de Dados 2 - 2017


Alunos: Allison Sampaio / Mara Goulart

<head>
  <meta charset="UTF-8">


# Tecnologia

Em meados dos anos 60 foi introduzido o termo banco de dados que serviria para armazenar
informações, uma camada de suporte para os sistemas de informações. O conceito de separar
aplicações dos dados era novo e abria possibilidades para aumentar a robustez das aplicações. Em
1970 Edgar Codd propos o modelo relacional que substituiu os modelos hierárquicos e de rede da
época, o modelo de Codd tornou-se base para o uso de SQL que permite que os dados sejam
armazenados em tabelas.
Por volta dos anos 2000, as aplicações começaram a produzir um vasto volume de dados por
meio de de aplicações complexas.
Segundo Juravich(2012),  termo NoSQL não é a abreviação de “no SQL” – sem SQL, significa “not only SQL”, não
apenas SQL, bancos de dados NoSQL são soluções de persistência de dados que não seguem o
modelo relacional e não utiliza SQL para querying.
A primeira característica que faz os bancos de dados NoSQL diferente é a sua estrutura de
dados. Dentre as estruturas disponíveis, há a orientada a documentos, que salva os itens sem serem
estruturados em um esquema. Essa estrutura de dados é remanescente de um array associativo em
PHP.
Juravich (2012) acrescenta  que o NoSQL deve ser utilizado quando o esquema e a estrutura dos dados mudam
constantemente.

# CouchDB 

Em abril de 2005, Damien Katz fez um post em seu blog sobre uma nova ferramenta de
banco de dados que o mesmo estava desenvolvendo, chamada CouchDB, que é o acrônimo de
Cluster of Unreliable Commodity Hardware. Em 2008 o projeto foi introduzido na incubadora da
Apache (JURAVICH, 2012). Em 2011 o time de desenvolvimento se uniu ao time do Membase o que melhorou a
documentação e visibilidade do produto.
No início de 2012 foi criado o Couchbase Server 2.0, que trazia novos recursos para o banco
de dados.
Dentre as principais características do CouchDB, estão:
a) um servidor de banco de dados de documento, acessível via RESTful JSON API,
b) ad-hoc e esquema com um largo espaço de endereço, c) queries feitas a partir do JavaScript.

# MongoDB

Em meados de 2007, uma startup na cidade de Nova York chamada 10GEN começou a trabalhar em “Platform as a Service”(PaaS), que consiste no serviço de hospedagem e implementação de hardware e software usado para prover aplicações por meio da Internet. Como o Google App Engine, a plataforma 10GEN foi projetada para lidar com o dimensionamento e gerenciamento de infra-estrutura de hardware e software automaticamente, liberando os desenvolvedores para se concentrar apenas no código de sua aplicação. De acordo com Garrett et all (2016), posteriormente descobriu-se que a maioria dos desenvolvedores não se sentiram à vontade com essa mudança, em contra partida, os usuários aprovaram e queriam a nova tecnologia de banco de dados do 10GEN. Isso levou a 10GEN concentrar seus esforços exclusivamente no banco de dados que se tornou o MongoDB.
 Para Garrett et all (2016) internamente, o MongoDB armazena documentos em um formato chamado Binary JSON, ou BSON, o terminal do MongoDB usa JavaScript e obtém documentos através do JSON. Enquanto os bancos de dados relacionais possuem tabelas, o MongoDB possui coleções.

</head>

# Referências e Softwares Utilizados

<a href="https://www.sharelatex.com/">ShareLatex</a>  
<a href="https://pt.sharelatex.com/templates/journals/sbc">SBC Template</a>  
MongoDB  
CouchDB  
Garret, D. (2016).Mongo in Action. Manning Publications, 1th edition.  
Juravich, T. (2012).CouchDB and PHP Web Development. Packt Publishing, 1th edition.  
Redmond,  E.  and  Wilson,  J.  R.  (2012).Seven  Databases  in  Seven  Weeks.   LLC,  1th edition.  
Jmitter


