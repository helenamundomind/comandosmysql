# comandosmysql
# comandosmysql
## Criação do bando de dados 
-- Comandos básicos
CREATE DATABASE *nome do banco*
USE *nome do banco*;

--- Criando uma tabela no banco de dados
CREATE TABLE *nome do banco(
    id INT AURO_INCREMENT PRIMARY KEY,
    nome varchar(100),
    idade INT,
    email varchar(100),
    codigo INT,
    sala INT,
    cidade varchar(20)
);

-- Inserir dados tabela
INSERT INTO *nome do banco* ('nome', 20, '@', 25, 10 'nome da cidade',) VALUES ('..', ..., '..', , '..');

-- Verificar se o banco de dados foi criado na estrutura de tabela 
SHOW DATABASES;

-- Para adicionar coluna com novo atributo
ALTER TABLE *nome da dus tabela* ADD COLUMN *artibuto que vai adicionar*;

-- Vizualizar a tabela já atualizada
SELECT * FROM *nome da sua tabela*
