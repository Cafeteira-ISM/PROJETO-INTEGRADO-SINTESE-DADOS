Sistema de Gerenciamento de Biblioteca em Python


Este é um projeto acadêmico desenvolvido como parte dos requisitos para o curso superior de Tecnologia em Ciência de Dados da Universidade Anhanguera. O objetivo principal é criar um sistema de gerenciamento de biblioteca simples e funcional, utilizando a linguagem Python e o paradigma de Programação Orientada a Objetos (POO).


O sistema visa otimizar as operações de uma biblioteca, oferecendo funcionalidades para a catalogação de livros, cadastro de usuários e gestão de empréstimos e devoluções.


Funcionalidades Implementadas:

O sistema abrange as seguintes funcionalidades principais:

Cadastro de Livros: Permite registrar novos livros com informações como título, autor, ano de publicação e número total de cópias.

Cadastro de Usuários: Possibilita o cadastro de novos usuários da biblioteca, incluindo nome, número de identificação único e informações de contato.

Empréstimo de Livros: Gerencia o processo de empréstimo, verificando a disponibilidade do livro e associando-o ao perfil do usuário. Atualiza automaticamente o número de cópias disponíveis.

Devolução de Livros: Processa a devolução, incrementando o número de cópias disponíveis e removendo o livro da lista de empréstimos do usuário.

Consulta de Livros: Permite buscar livros no acervo por título, autor ou ano de publicação.

Geração de Relatórios: Oferece relatórios para visualização de livros disponíveis, livros emprestados (com indicação do usuário) e lista completa de usuários cadastrados.

Arquitetura do Sistema
A arquitetura do sistema foi concebida sob o paradigma da Programação Orientada a Objetos (POO), visando modularidade, escalabilidade e facilidade de manutenção.

As principais classes que compõem o sistema são:

Livro: Representa a entidade Livro, com atributos como titulo, autor, ano_publicacao, total_copias e copias_disponiveis. Possui métodos para emprestar() e devolver() o livro.
Usuario: Representa um usuário registrado na biblioteca, com atributos como nome, numero_identificacao e contato. Gerencia uma lista de livros_emprestados.
Biblioteca: Atua como a classe controladora principal, gerenciando o acervo de livros (acervo_livros) e o cadastro de usuários (lista_usuarios). Orquestra todas as operações de cadastro, empréstimo, devolução, consulta e geração de relatórios.

A interação com o sistema ocorre por meio de uma interface de linha de comando (CLI - Command Line Interface), com um menu interativo para seleção das funcionalidades.


Como Executar o Projeto
Este projeto foi desenvolvido para ser facilmente executado em ambientes de notebook, como o Google Colaboratory (Google Colab), sem a necessidade de configurações complexas.

Para rodar o sistema, siga os passos abaixo:

Acesse um Ambiente de Notebook:

Abra o Google Colaboratory em seu navegador (requer uma conta Google).
Crie um Novo Notebook:

No Google Colab, clique em Arquivo > Novo notebook.
Copie e Cole o Código:

Copie todo o conteúdo do arquivo [Sistema de Gerenciamento de Biblioteca].
Cole o código completo em uma célula vazia do seu novo notebook.

Clique no botão "Play" (ou "Executar célula") ao lado da célula onde você colou o código.
O programa será executado diretamente na saída da célula, e você verá o menu interativo para começar a utilizar o sistema.

Ao executar o programa, você verá um menu interativo:
![0 Menu](https://github.com/user-attachments/assets/7cc9a916-0502-4351-a301-c25db5c6a95d)

Você pode interagir digitando o número da opção desejada e seguindo as instruções na tela, como exemplificado nas imagens do Projeto Integrado.



