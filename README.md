# Oficina-2.0
Olá, bem vindo ao projeto Oficina 2.0 - Sistema de cadastro de orçamentos

O projeto foi realizado utilizando a linguagem de programação PHP, Framework Laravel e banco de dados MySQL.

Para rodar o projeto é necessário ter instalado o PHP versão 8.2.4, Xampp, depêndencia Composer e o framework Laravel. Depois de ter realizado a instalação das depêndencias é necessário ir até a pasta onde esta instalada o PHP, abrir o arquivo php.ini e habilitar a opção extension=pdo_mysq removendo o ponto e virgula do iníco. Após realizar esse procedimento, você deve ativar os módulos de Apache e MySQL no Xampp, criar uma database MySQL no PhpMyAdmin e atualizar o arquivo .env na pagina do projeto com as informações: nome da database, username e password(Foi utlilizado a database oficina2 e usuario adminoficina password adminoficina no projeto).

Após a criação da database e configuração do arquivo .env é necessário executar no terminal o comando php artisan migrate para criar a tabela orcamentos na database. 

Depois de realizar a migração para a database, rodar o comando php artisan serve e acessar o sistema através do link http://127.0.0.1:8000/.


![Screenshot_4](https://github.com/matheuspereiramartinscd/Oficina-2.0/assets/136721687/ceba6883-4ee9-433d-a8ae-2101a7b1b725)

![Screenshot_5](https://github.com/matheuspereiramartinscd/Oficina-2.0/assets/136721687/7bc97778-ba88-4ecb-9788-2f32d0933775)

![Screenshot_6](https://github.com/matheuspereiramartinscd/Oficina-2.0/assets/136721687/b73af367-187b-41c5-b51f-ad3081ffbe6f)


