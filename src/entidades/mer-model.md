# 🏗️ Modelo Entidade-Relacionamento(MER)

---

É um modelo de dados conceitual de alto nível, ou seja, seus conceitos foram projetados para serem compreensíveis aos usuários descartando métodos de armazenamento de dados, etc.

Pode ser expresso graficamente por meio do Diagrama Entidade Relacionamento(DER). Cada elemento do MER pode ser representado usando o DER.


<div style="text-align:center">

<img src="../images/der-image.png" alt="der-image">

</div>

A partir do MER podemos criar um DER de acordo com as especificações definidas nas análises de requisitos, permitindo ilustrar as entidades e relacionamentos entre elas. O MER ajuda a separar as informações do negócio das atividades realizadas no mesmo.

## Componentes do MER

A **Entidade** (tabela, registros,...) é algo significativo sobre o qual devemos possuir informações como por exemplo a tabela de clientes, já o **Atributo** descreve uma entidade e o **Relacionamento** é uma associação entre as Entidades.

## A Entidade

- Uma entidade é algo com importância para um usuário ou organização que precisa ser representado no banco de dados. 
- Uma entidade pode ter existência física ou abstrata. 
- As entidades modeladas no MER serão tabelas dos bancos de dados. 
- Cada objeto de uma entidade é chamado de instância de entidade. 
- Cada instância/ocorrência de entidade será uma linha da tabela ou registro ou ainda tupla.

A representação da entidade no diagrama deve ser representada por um RETÂNGULO. Para identificar uma identidade fazemos a pergunta: "a respeito de quem eu quero guardar informações ?"

## Regras para Nomeação de Entidades

Existem regras para a nomeação de entidades como:

- Começam com letra;
- Usam palavras no singular;
- Não têm espaço;
- Evitam caracteres especiais;
- Devem ser únicos no banco de dados. 