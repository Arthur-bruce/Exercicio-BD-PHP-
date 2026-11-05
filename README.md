Sistema de Consulta de Produtos — PHP e MySQL

Sobre o projeto

Este projeto consiste em um sistema de consulta de produtos desenvolvido utilizando PHP e MySQL, com o objetivo de estabelecer uma conexão com o banco de dados e apresentar os produtos cadastrados em uma página web.

O sistema realiza consultas SQL utilizando "SELECT", relacionando informações de produtos e categorias para exibi-las de forma organizada em uma tabela HTML.

Tecnologias utilizadas

- PHP: Linguagem utilizada para desenvolver a conexão e as consultas ao banco de dados.
- MySQL: Sistema de gerenciamento do banco de dados.
- HTML5: Estruturação da página.
- CSS3: Estilização da interface.
- MySQLi: Biblioteca utilizada para comunicação entre PHP e MySQL.

Estrutura do projeto

trabalho_03_11/
│
├── conexao.php   # Configuração da conexão com o banco de dados
├── index.php     # Página de consulta e exibição dos produtos
└── fisico.sql    # Script SQL para criação e população do banco

Funcionalidades

- Conexão entre PHP e MySQL.
- Consulta de produtos cadastrados.
- Relacionamento entre produtos e categorias.
- Exibição dos dados em uma tabela HTML.
- Formatação dos preços em reais (R$).
- Exibição da quantidade disponível em estoque.
- Organização dos produtos pelo código identificador (ID).

Banco de dados

O projeto utiliza o banco de dados "db_sistema_vendas", que contém tabelas destinadas ao gerenciamento de informações comerciais.

Entre as principais tabelas estão:

- "tbl_clientes": Armazena informações dos clientes.
- "tbl_vendedores": Armazena informações dos vendedores.
- "tbl_produtos": Armazena os produtos, preços e quantidades.
- "tbl_pedidos": Armazena informações dos pedidos.
- "tbl_categorias": Armazena as categorias dos produtos.

O banco utiliza o mecanismo InnoDB e o conjunto de caracteres UTF-8 ("utf8mb4").

Como executar o projeto

1. Instale um ambiente de desenvolvimento local, como XAMPP.
2. Inicie os serviços Apache e MySQL.
3. Coloque a pasta do projeto dentro do diretório "htdocs".
4. Acesse o phpMyAdmin.
5. Importe o arquivo "fisico.sql" para criar e popular o banco de dados.
6. Verifique as configurações de conexão no arquivo "conexao.php".
7. Acesse o projeto pelo navegador:

http://localhost/trabalho_03_11/

Objetivo acadêmico

Projeto desenvolvido como atividade prática da disciplina de Banco de Dados II, envolvendo conceitos de integração entre PHP e MySQL, consultas SQL, relacionamentos entre tabelas e apresentação de informações em páginas web.

---

Desenvolvido para fins educacionais.
