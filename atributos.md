### Entidades:
 - Entidades  Representam objetos, coisas ou conceitos do mundo real sobre os quais o sistema precisa armazenar dados. Elas podem ser classificadas segundo a sua dependência e motivo de existência: 
    > Entidades fortes: Possuem total sentido de existir por si só, independentemente de qualquer outra entidade. Exemplo: Produto ou Cliente.
    > Entidades fracas: Dependem de outras entidades para existirem e não fazem sentido isoladamente. Exemplo: A entidade Venda depende da existência de um Produto (uma venda sem itens não faz sentido).
    > Entidades associativas: Surgem para transformar um relacionamento em uma entidade, geralmente quando precisamos relacionar algo a uma associação que já existe. Exemplo: O relacionamento N:N entre Venda e Produto gera a entidade associativa Item da Venda. Se a loja quiser dar um brinde por um produto específico de uma compra, a entidade Brinde se conectará a essa entidade associativa.

### Atributos:
 - São as características e propriedades que descrevem cada entidade. Eles detalham as informações exatas que serão guardadas. Os atributos possuem classificações quanto à sua função e à sua estrutura:
    > Quanto à função:
    > Descritivos: Representam características intrínsecas da entidade (ex: nome, cor).  
    > Nominativos: Além de descreverem, servem para definir e identificar um objeto (ex: código, número).
    > Referenciais: Indicam a ligação de uma entidade com a outra em um relacionamento (ex: o CPF do cliente registrado dentro da entidade Venda).  

    > Quanto à estrutura:  
    > Simples: Definidos por uma única característica direta (ex: peso, idade).  
    > Compostos: Dividem-se em várias informações menores que formam o todo (ex: o endereço, que é composto por rua, número e bairro).  

### Relacionamentos:
 - São as associações ou a interação lógica entre as entidades. Quando a referência de uma entidade existe dentro de outra, temos um relacionamento. A quantidade de objetos envolvidos de cada lado dessa ligação é definida pelas cardinalidades: 
    > Um para um (1..1): Cada instância de uma entidade referencia obrigatoriamente apenas uma unidade da outra. Exemplo: 1 Usuário possui 1 Currículo na base.  
    > Um para muitos (1..N): Uma instância da primeira entidade pode se relacionar a várias da segunda. Exemplo: 1 Usuário pode fazer N Empréstimos.
    > Muitos para muitos (N..M): Várias instâncias de uma entidade se relacionam com várias da outra. Exemplo: N Empréstimos podem conter N Livros. (Na prática do banco de dados relacional, esse tipo de relacionamento exige a criação de uma tabela/entidade associativa para funcionar corretamente).

### Fonte: https://www.devmedia.com.br/mer-e-der-modelagem-de-bancos-de-dados/14332