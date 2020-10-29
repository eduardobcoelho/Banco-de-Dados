# Conceitos de Bancos de Dados

## Dados x Informação
Dados: são fatos em uma forma primária, que podem ser armazenados em algum meio.
* Ex.: CPF, Nome, Data.

Informação: São os fatos organizados de maneira a produzir um significado --> Dados colocados em contexto.
* Ex.: Lista de clientes com seus números de CPF em ordem de cadastro.

## Metadados
* Definimos Metadados como sendo "Dados sobre os dados".
* Permitem efetuar a representação e identificação dos dados, garantindo sua consistência e persistência.
* Os Metadados são mantidos no Dicionário de Dados (ou em um Catálogo de Dados).

## Banco de Dados
Um Banco de Dados (BD) é uma coleção organizada de dados. Esses dados são organizados de modo a modelar aspectos do mundo real, para que seja possível efetuar processamento que gere informações relevantes para os usuários a partir desse dados.

Um BD é composto por diversos objetos tais como: tabelas, esquemas, visões, consulstas, relatórios, procedimentos, triggers, entre outros.

## Aplicações dos Bancos de Dados
Bancos de dados encontram aplicações em inúmeras áreas, como:

* Sistemas bancários
* Reservas em hotéis
* Controle de estoque em supermercados
* Catálogo de livros em bibliotecas
* E-commerce
* Receita Federal
* Youtube

## SGBD
Sistema de Gerenciamento de Bancos de Dados

* Um SGBD é uma coleção de softwares que permite aos usuários criarem e manterem um ou mais bancos de dados.
* São usados nas tarefas de definição, contrução, manipução e compartilhamento dos bancos de dados entre aplicações e usuários.
* Permitem proteger o banco de dados e mantê-lo ao longo do tempo.

### Exemplos de SGBDs
* Oracle Database
* MIcrosoft SQL Server
* MySQL
* IBM DB2
* SAP Sybase
* MongoDB
* Teradata
* PostgreSQL
* SQLite

## Sistema de Bancos de Dados
É um sistema que contém o SGBD, o banco de dados, aplicativos de acesso e os usuários.

Exemplificação: Usuários <--> Aplicativos de acesso <--> SGBD <--> Banco de Dados + Metadados

## Usuários de Bancos de Dados
* Administrador (DBA)
* Projetista / Desenvolvedor
* Usuário Final

## Características e Funcionalidades
* Controle de Redundância: Evitar duplicidade dos dados.
* Múltiplas Visões dos Dados: Exibir aos usuários as informações de maneiras distinta.
* Controle de Concorrência: Se duas pessoas tentam acessar o mesmo dado, esse acesso há de ser controlado pelo BD. 
* Backup e Restauração.
* Autenticação e Autorização de acesso: Apenas pessoas autorizadas tenham acesso aos dados.
* Restrições de integridade: Regras de integração.

## Modelos de Bancos de Dados
### Modelo Hierárquico
* Neste modelo os dados são organizados de forma hierárquica, com conjuntos de tipos de registros interconectados por meio de ligações.
* Uma ligação representa uma relação entre dois tipos de registros: pai e filhos.
* Um esquema no modelo hirárquico é um diagrama de estrutura em árvore.
* O acesso aos dados é sempre unidirecional, a partir do pai ao filho.

### Modelo em Rede
* No modelo em Redes os dados são organizados em tipos e ligações entre dois registros.
* Não há retrição hierárquica.
* Tanto o esquema quanto ocorrências de dados são visualizados como um grafo direcionado.

### Modelo Relacional
* Neste modelo, os dados são separados em entidades, conforme cada assunto, e registrados como atributos dessas entidades.
* As entidades se relacionam entre si e permitem que os dados sejam armazenados e recuperados de forma rápida e segura.