# 👥 Modelagem de Dados

---

Existem diversos modelos de dados como: hierárquico, rede, relacional, orientado a objeto e não relacional, porém o que será abordado durante o curso é o relacional.

## Modelagem de Dados

Um modelo de dados é importante pra a criação de um sistema de informação com a aplicação de técnicas específicas de modelagem(nem sempre o projetista do banco de dados é o programador). O modelo de dados segue regras de negócio a fim de fornecer uma estrutura para os dados serem usados em um sistema de informação, aplicando definições e formatos específicos.

## Níveis de Modelagem de Dados

- Modelo conceitual: ideia abstrata, geral...
    - Primeira fase de modelagem, sem pensar em SGBD, linguagem...
    - Visão simplificada dos dados e relacionamentos
- Modelo lógico: detalhamento intermediário
    - Contém especificação detalhada
    - Tipos de dados definidos
- Modelo físico: alto nível de detalhamento final, amplo...
    - Contém até mesmo restrições na tabela, nos seus campos, valores...
    - Após a criação deste modelo é implementado o SGBD mais adequado

## Modelo Relacional

Neste modelo os dados são organizados em tabela(relações) bidimensionais, linhas e colunas. O modelo relacional é baseado em lógica e teoria dos conjuntos. Neste modelo um banco de dados é uma coleção de relações(tabelas bidimensionais) onde os dados são armazenados, por exemplo em um sistema acadêmico, para armazenar dados sobre os alunos são criadas tabelas para conter os dados dos alunos como: dados pessoais, disciplinas cursadas, notas...

## Componentes do Modelo Relacional

Dentre os componentes do modelo relacional serão abordados:

- Coleções de objetos que armazenam dados(relações - tabelas);
- Conjuntos de operadores que agem nas relações, produzindo outras relações;
- Conjuntos de regras que garantem a integridade de dados, precisão e consistência.

No modelo relacional existem **Tabelas**, que são a estrutura básica de armazenamento no SGBDR, armazenando dados necessários sobre o mundo real.

Também existem as **Tuplas**, que são linhas(registros), representando os dados de uma determinada ocorrência em particular, por exemplo, em uma tupla do banco de dados de uma escola existe os dados de um aluno. Cada linha deve conter uma informação única de modo que não seja duplicada.

Existem também **Colunas** que armazenam um tipo específico de dado(valor), por exemplo, a coluna que armazena nome do usuário em um banco de dados.

O **Relacionamento** é uma conexão existente entre tabelas conectadas por atributos(chave primária e estrangeira). Por exemplo: numa universidade existem banco de dados para alunos e para os dados de um curso, é possível relacionar o banco de dados dos alunos selecionando os que fazem certo curso com o banco de dados que contém os cursos.

## Etapas de Desenvolvimento do Banco de Dados

- Especificação e análise de requisitos
    - Documentação de requisitos
- Projeto conceitual(processo inicial)
- Projeto Lógico: expresso num modelo relacional
- Projeto Físico: 
    - Contém especificações para armazenar e acessar o banco de dados
    - Implementação, inserção e manutenção dos dados.
