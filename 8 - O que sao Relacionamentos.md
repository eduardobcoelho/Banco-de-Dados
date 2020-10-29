# Relacionamentos
As Entidades podem ser conectadas entre si por meio de Relacionamentos. Trata-se de uma estrutura que indica a associação de elementos de uma ou mais entidades.

## Por que precisamos de relacionamentos?
* Como os dados de diferentes entidades são armazenados em tabelas distintas, geralmente precisamos combinar duas ou mais tabelas para responder às perguntas específicas dos usuários.
* Por exemplo, podemos querer saber quais produtos, e em qual quantidade, foram adquiridos por um cliente em particular. Precisaremos então de dados das tabelas de clientes, de pedidos e produtos para obter essa informação.
* Representamos um Relacionamento em um DER por meio de um Losango que conecta uma ou mais Entidades.

## Grau de um Relacionamento
O grau de um relacionamento define o número de entidades que participam do relacionamento. Assim, um relacionamento pode ser:
* Unário
* Binário
* Ternário
Os relacionamentos mais comuns são os de grau 2 (binários).

## Relacionamentos entre Tabelas
Uma tabela é relacionada com outras tabelas. Por exemplo, um produto é vendido em uma loja.
O grau de um Relacionamento indica o número de entidades envolvidas no relacionamento, como por exemplo unário, binário e ternário.

## Efetuando relacionamento entre múltiplas tabelas
* Cada linha de dados em uma tabela deve ser identificada de forma única usando-se uma Chave Primária (identificador exclusivo).
* Usamos uma Chave Estrangeira para relacionar os dados entre múltiplas tabelas.
* Usamos para isso o relacionamento entre chave primária de uma tabela com a chave estrangeira em outra tabela.