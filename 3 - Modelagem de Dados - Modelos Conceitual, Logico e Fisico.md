# Modelagem de Dados - Modelos Conceitual, Lógico e Físico

## Modelagem de Dados - Níveis
Classificamos o processo de modelagem de dados em três níveis:
* Modelo Conceitual (alto nível) - MCD
* Modelo Lógico - MLD
* Modelo Físico (baixo nível) - MFD

## Modelo Conceitual
Esta é a primeira fase da modelagem, onde representaremos o mundo real por meio de uma visão simplificada dos dados e seus relacionamentos. Assim poderemos determinar quais informações serão armazenadas no BD.
Neste nível o projeto é independente de SGBD.

Exemplo:
**Cadastro de Produtos em uma Loja**
Dados necessários: Nome do produto, categoria de produto (limpeza, higiene, etc), código do fornecedor, tipo de embalagem, tamanho, quantidade.

Neste nível, detalhes da implementação não aparecem, porém é suficientemente detalhado para a ponto de ser possível descrever os tipos de dados requeridos, seus relacionamentos entre si e regras de consistência.

## Modelo Lógico
* Um modelo lógico possui conceitos que os usuários são capazes de entender, ao mesmo tempo em que não está distante do físico do banco de dados.
* Neste nível o projeto é independente de SGBD.
* Consiste na especificação lógica dos dados em um formato adequado ao SGBD escolhido. Os tipos de dados são completamente definidos.

## Modelo Físico
* A partir de um modelo lógico nós derivamos o modelo físico, onde se detalham os componentes de estrutura física do banco de dados, incluindo as tabelas, campos, tipos de valores, restrições, etc.
* Ao criarmos o modelo físico, poderemos partir para a implementação física do banco de adados, utilizando o SGBD mais adequado.

## Arquitetura de Três Níveis
Mundo observado --> Modelo Conceitual --> Modelo Lógico --> Modelo Físico.

## Esquema do Banco de Dados
* Um Esquema é uma definição do Banco de Dados especificada durante o projeto, armazenada no **Dicionário de Dados**.
* Um Esquema (Schema) raramente muda durante a vida do BD.
* Trata-se da organização dos dados em um plano que mostra como o banco é construído.
* O esquema define tabelas, campos, relacionamentos, visões, finções e muitos outros elementos que compõem o BD.

## Etapas do desenvolvimento de um BD
As principais etapas no desenvolvimento de um BD são:
1. Especificações e Análise de Requisitos
    * Os requisistos são documentados
2. Projeto Conceitual
    * Baseado nos requisitos
3. Projeto Lógico
    * Expresso em um modelo de dados, como o relacional
4. Projeto Físico
    * Especificações para armazenar e acessar o banco de dados
    * Implementação do BD, inserção de dados reais e manutenção

## Tarefas para Modelagem
As tarefas a seguir devem ser realizadas para que seja possível efetuar modelagem de dados e projeto de BD funcional:
* Identificar os tipos de entidade
* Identificar atributos
* Identificar relacionamentos
* Criar e associar chaves
* Normalizar para reduzir redundância
* Desnormalizar para aumentar perfomance

## MER
Após o levantamento de requisitos, estes são transformados em um **Modelo Entidade-Relacionamento**(MER), o qual consiste dos seguintes elementos:
* Entidades
* Relacionamentos
* Atributos

O modelo é posteriormente refinado com o uso de técnicas específicas,  e finalmente implementado em um banco de dados físico.