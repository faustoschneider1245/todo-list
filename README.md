# Todo List

Desenvolvimento de sistema para gestão de tarefas no formato "to do". Deve contemplar no minimo as funcionalidades de:
- Login de usuários diferentes;
- Listas: Criação, leitura, edição e exclusão;
- Tarefas: Criação, leitura, edição e exclusão;

## Framework

O sistema deve ser desenvolvido para versão >= PHP 7.2 e banco de dados MySQL >= 5.7. O ideal é a utilização do framework Code Igniter 3.0 ou Laravel 5.8, livre para escolha de packages. A ideia é criação de um sistema mais rápido possível, podendo usar o máximo de packages prontos.

Recomenda-se usar o Bootstrap >= 4 ou tema pronto para admin, como o SB Admin ou Admin LTE.

## Estrutura de dados

Abaixo segue a estrutura de dados que o sistema deve contemplar.

### Listas de Tarefas

Columns       | Type
------------- | ------
User          | FK
Name          | String
Description   | Short Text
Created       | Datetime
Updated       | Datetime

### Tarefas

Columns       | Type
------------- | ------
ListID        | FK
Description   | Short Text
Due           | Date
Completed     | Datetime
Created       | Datetime
Updated       | Datetime

### Usuários

Columns       | Type
------------- | ------
Name          | String
Email         | String
Password      | String
Created       | Datetime
Updated       | Datetime

Após concluir o projeto, o mesmo será publicado em um ambiente Ubuntu, com Nginx para webserver na empresa Digital Ocean. 

Será avaliado a praticidade nas escolhas para desenvolvimento, <a href="https://owasp.org/www-project-top-ten/">ítens básicos de segurança</a> e respeito a padrões de projeto DRY, MVC, SOLID e <a href="https://www.php-fig.org/">PSR</a>.
