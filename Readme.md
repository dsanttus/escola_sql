-- Instruções do projeto
/*
De acordo com os comandos aprendidos, programe códigos SQL para criar um banco de dados
chamado ESCOLA e deixe-o pronto para o uso. Depois, pesquise qual é o comando utilizado
para inserir uma tabela no banco de dados e siga as instruções:

1. crie uma tabela chamada ALUNO;  
2. defina os atributos da tabela;
3. adicione a chave primária de nome ID (identificador);
4. adicione um atributo nome do tipo varchar;
5. adicione um atributo e-mail do tipo varchar;
6. adicione um atributo endereço do tipo varchar.

Trabalhe esse código em seu IDE, suba ele para sua conta no GitHub e compartilhe
o link desse projeto no campo ao lado para que outros desenvolvedores possam analisá-lo.
*/

--RESPOSTA DA ATIVIDADE

CREATE DATABASE escola;

USE escola;

CREATE TABLE aluno (
id_aluno SERIAL PRIMARY KEY,
nome_aluno VARCHAR(40) NOT NULL,
email_aluno VARCHAR(50),
endereco_aluno VARCHAR(100) NOT NULL
);
