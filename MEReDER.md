### Modelo Entidade-Relacionamento (MER):
 - O **MER (Modelo Entidade-Relacionamento)** é o modelo conceitual utilizado para representar e organizar as informações que serão armazenadas em um banco de dados. Ele permite identificar quais objetos ou conceitos são importantes para o sistema, quais características precisam ser armazenadas sobre eles e como esses objetos se relacionam entre si.
 
 - O MER é utilizado principalmente durante a etapa de planejamento do banco de dados, antes da criação das tabelas. Dessa forma, ajuda a entender a estrutura e as regras do sistema sem se preocupar inicialmente com detalhes específicos de implementação.

    > **Entidades:** Representam os objetos ou conceitos que possuem importância para o sistema e sobre os quais serão armazenadas informações. Exemplo: Cliente, Produto ou Venda.
    
    > **Atributos:** Representam as características que descrevem uma entidade. Exemplo: um Cliente pode possuir nome, CPF, telefone e endereço.
    
    > **Relacionamentos:** Representam as associações existentes entre as entidades. Exemplo: um Cliente realiza uma Venda.
    
    > **Cardinalidades:** Determinam quantas ocorrências de uma entidade podem ou devem estar relacionadas com ocorrências de outra entidade. Exemplo: um Cliente pode realizar várias Vendas (1:N).

### Diagrama Entidade-Relacionamento (DER):
 - O **DER (Diagrama Entidade-Relacionamento)** é a representação gráfica do modelo conceitual definido pelo MER. Ele utiliza elementos visuais para facilitar a compreensão da estrutura do banco de dados e mostrar como as entidades, atributos e relacionamentos estão organizados.

 - Por meio do DER, é possível visualizar de forma mais clara as entidades existentes no sistema, suas características, os relacionamentos entre elas e as respectivas cardinalidades. Isso facilita a análise e a identificação de possíveis problemas na estrutura antes da implementação do banco de dados.

    > **Entidades:** São representadas graficamente para indicar os objetos ou conceitos existentes no sistema.
    
    > **Atributos:** São representados para indicar quais informações pertencem a cada entidade.
    
    > **Relacionamentos:** Mostram graficamente a associação entre duas ou mais entidades.
    
    > **Cardinalidades:** Indicam a quantidade mínima e máxima de ocorrências que podem participar de um relacionamento, como 1:1, 1:N ou N:M.

### Diferença entre MER e DER:
 - Apesar de estarem diretamente relacionados, **MER e DER não são a mesma coisa**. O MER corresponde ao **modelo conceitual**, ou seja, à definição dos elementos e das relações que fazem parte do banco de dados. Já o DER corresponde à **representação gráfica desse modelo**, permitindo visualizar esses elementos de maneira organizada.

 - Dessa forma, podemos considerar que o **MER define o que será representado**, enquanto o **DER mostra visualmente como essa estrutura está organizada**. Os dois são utilizados em conjunto para facilitar o planejamento, a análise e a construção de um banco de dados.

### Fonte: https://www.devmedia.com.br/mer-e-der-modelagem-de-bancos-de-dados/14332