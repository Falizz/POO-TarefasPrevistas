A string de conexão com o banco de dados do código deve ser configurada na main e nos testes para que o código funcione

O script de criação da base de dados pode ser usado

o usuário criado como exemplo:

CREATE USER 'TarefasPrevistasTester'@'localhost' IDENTIFIED BY '1234';
GRANT ALL PRIVILEGES ON POO_TarefasPrevistas.* TO 'TarefasPrevistasTester'@'localhost';
FLUSH PRIVILEGES;
