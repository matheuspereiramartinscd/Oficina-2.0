# Oficina-2.0
Olá, bem vindo ao projeto Oficina 2.0 - Sistema de cadastro de orçamentos
![image](https://github.com/matheuspereiramartinscd/Oficina-2.0/assets/136721687/71c57e8b-be50-451a-930c-9e079a88a9ba)

![image](https://github.com/matheuspereiramartinscd/Oficina-2.0/assets/136721687/517bc1c2-db9d-47b7-bdf7-51d2e94b4a9e)


O projeto foi realizado utilizando a linguagem de programação PHP, Framework Laravel e banco de dados MySQL.

Para rodar o projeto é necessário ter instalado o PHP versão 8.2.4, Xampp, depêndencia Composer e o framework Laravel. Depois de ter realizado a instalação das depêndencias é necessário ir até a pasta onde esta instalada o PHP, abrir o arquivo php.ini e habilitar a opção extension=pdo_mysq removendo o ponto e virgula do iníco. Após realizar esse procedimento, você deve ativar os módulos de Apache e MySQL no Xampp, criar uma database MySQL no PhpMyAdmin e atualizar o arquivo .env na pagina do projeto com as informações: nome da database, username e password(Foi utlilizado a database oficina2 e usuario adminoficina password adminoficina no projeto).

![image](https://github.com/matheuspereiramartinscd/Oficina-2.0/assets/136721687/021f14ca-4c7b-4ec0-8edb-4e8b95e9f9d9)

Após a criação da database e configuração do arquivo .env é necessário executar no terminal o comando php artisan migrate para criar a tabela orcamentos na database. 

Depois de realizar a migração para a database rodar o comando php artisan serve e acessar o sistema através do link http://127.0.0.1:8000/.



