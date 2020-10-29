# Atributos
* Os atributos descrevem características da entidade, como por exemplo: fabricante, modelo, cor, placa, etc.
* Os atributos possuem um tipo de dados (domínio) nome e valor específico.

## Representando Atributos
* Os atributos podem ser representados por uma elipse contendo o seu nome, ligada à entidade que qualifica.
* Opcionalmente, podemos representar um atributo apenas pelo seu nome ligado à entidade, sem utilizar a elipse.

## Tipos de Atributos
Os atributos podem ser de vários tipos, tais como:
* Simples
* Composto
* Multivalorado
* Determinante
* Identificador
entre outros.

### Atributo Simples / Atômico
Não possui características especiais, e são indivisíveis.
    Ex.: Nome da empresa, CPF, CNPJ.

### Atributo Composto
É formado por itens menores; pode ser subdividido em outros atributos.
    Ex.: Endereço da empresa.

### Atributo Multivalorado
Pode conter mais de um valor para um mesmo registro (informação).
    Ex.: *Telefone da empresa.

### Atributo Determinante
Define de forma única as instâncias de uma entidade.
Não podem existir duas intâncias com o mesmo valor nesse atributo. Ou seja, os valores nunca se repetem para diferentes instâncias.
    Ex.: CNPJ da empresa, Código de Produto.

### Atributo Identificador ("Chaves")
Uma **chave** identifica uma instância específica na classe de entidade.
    Ex.: CPF, CódigoProduto, Matrícula, ID_Setor

As chaves podem ser únicas ou não-únicas:
- Únicas: O valor dos dados da chave é única na entidade
- Não-única: Usada para agrupar instâncias de classe em categorias.
As chaves podem ser compostas, consistindo de dois ou mais atributos combinados.