# Library_System_POO
Projeto final para disciplina de Programação Orientada a Objetos, do curso de Ciência da Computação, da Universidade Federal de Alagoas.
## Funcionalidades

O programa possui as seguintes funcionalidades:

1. **Cadastrar Estudantes**: Permite cadastrar estudantes com nome, CPF e senha.

2. **Cadastrar Livros**: Permite cadastrar livros com título e autor.

3. **Realizar Empréstimos**: Os estudantes podem emprestar livros. O empréstimo é registrado com a data de empréstimo.

4. **Listar Empréstimos**: Exibe uma lista de empréstimos de livros, incluindo informações sobre o livro, estudante e data de empréstimo.

5. **Gerar Relatório**: Gera um relatório que inclui informações sobre atrasos em empréstimos (aqueles com mais de 15 dias).

## Estrutura das Classes

O projeto é organizado em quatro classes principais:

- `Estudante`: Representa um estudante com atributos como ID, nome, CPF e senha.

- `Livro`: Representa um livro com atributos como ID, título e autor.

- `Emprestimo`: Representa um empréstimo de livro, relacionando um estudante, um livro e a data de empréstimo.

- `AppJava`: É a classe principal que contém a lógica do programa. Ela inclui funções para cadastrar estudantes, cadastrar livros, realizar empréstimos, listar empréstimos e gerar relatórios.

## Modo de Execução

Para executar o programa em sua máquina, siga estas etapas:

1. Certifique-se de que você tenha o ambiente Java Development Kit (JDK) instalado em sua máquina.

2. Baixe e extraia os arquivos do projeto em um diretório local.

3. Abra um terminal ou prompt de comando e navegue até o diretório onde você extraiu os arquivos.

4. Compile o programa executando o seguinte comando: javac AppJava.java
   
5. Execute o programa com o seguinte comando: java AppJava
   

