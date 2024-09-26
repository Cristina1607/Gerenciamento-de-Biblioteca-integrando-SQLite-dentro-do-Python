# Sistema de Gerenciamento de Biblioteca

Este é um sistema de gerenciamento de biblioteca desenvolvido em Python utilizando SQLite como banco de dados. O sistema permite que usuários gerenciem livros, usuários e empréstimos, facilitando o controle de itens emprestados e a informação dos usuários.

## Funcionalidades

- Inserir novos livros na biblioteca.
- Inserir novos usuários.
- Realizar empréstimos de livros.
- Atualizar a data de devolução de um empréstimo.
- Exibir todos os livros atualmente emprestados.

## Estrutura do Banco de Dados

O banco de dados contém três tabelas principais:

1. **livros**: Armazena informações sobre os livros, como título, autor, editora, ano de publicação e ISBN.
2. **usuarios**: Armazena informações sobre os usuários, incluindo nome, sobrenome, endereço, e-mail e telefone.
3. **emprestimos**: Registra os empréstimos de livros, vinculando usuários e livros com datas de empréstimo e devolução.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git
2. Navegue até o diretório do projeto:
   ```bash
   cd Gerenciamento-de-Biblioteca-integrando-SQLite-dentro-do-Python

## Dependências
- Python 3.x
- SQLite3 (incluso na biblioteca padrão do Python)


