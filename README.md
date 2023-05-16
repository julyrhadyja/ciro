# API-ESCOLA

## Atividade Escolar
> July Rhadyja

## Descrição

Esse projeto possui uma proposta inicial de desenvolvimento para 3 serviços: Escola, Autenticação e biblioteca (os 3 devem interagir).

## Arquitetura do Projeto:

### Proposta: 

- A escola deve fazer um cadastro de alunos, professores e da turma. O serviço da escola deverá interagir com a Biblioteca, mostrando quais livros foram alugados, diferenciando os professores e alunos.

- A biblioteca deve realizar os empréstimos dos livros para os usuários. Sua função é criar e controlar o cadastro de livros e usuários. Para criar um cadastro da biblioteca, não necessariamente precisa ser aluno ou docente da escola (A biblioteca é independente da escola). Ela tem que diferenciar os usuários, que podem ser: alunos, professores ou usuários comuns.

- A autenticação é responsável por armazenar as credenciais, que são (login, senha, chave de acesso) e fazer a autenticação dos usuários. 

## Desenvolvimento:
> Dependencias: Laravel

- O projeto será desenvolvido utilizando o framework Laravel, escrito na linguagem PHP. Ele traz inúmeros benefícios para o desenvolvimento, tornando mais rápido e fácil de manter a codificação do projeto.

### *Para utilizar o framework Laravel acesse: https://laravel.com/

## Projeto atualmente:

Atualmente, o projeto possui (além do projeto do laravel criado) duas rotas definidas:

> rota "/" -> {“hello_url” : “/hello”}.

> rota "/hello"  -> Hello, World!



## Testar o projeto:

Para testar o projeto deve-se utilizar o terminal da sua máquina e executar o seguinte comando:

> php artisan serve  --port 8001

### O usuário pode utilizar a porta que desejar. 
