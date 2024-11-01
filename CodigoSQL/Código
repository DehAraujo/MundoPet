CREATE DATABASE te;
USE te;

CREATE TABLE Cliente(
  id_cliente INT ,
  nome_cliente VARCHAR not null  notnull unsigned auto increment
  endereco_cliente VARCHAR  not null
  tel_cliente INT  not null
  data_cadastro_cliente DATE not null
);

CREATE TABLE Pet(
  id_pet INT notnull unsigned auto increment;
  nome_pet VARCHAR not null;
  especie_pet VARCHAR not null;
  raca_pet VARCHAR not null;
  idade_pet INT not null;
  sexo_pet VARCHAR not null;
  id_cliente VARCHAR not null;
);

CREATE TABLE Produto(
  id_produto INT notnull unsigned auto increment;
  nome_produto VARCHAR not null;
  categoria_produto VARCHAR not null;
  preco_produto FLOAT not null;
  quantidade_produto INT not null;
  fornecedor_produto VARCHAR;
);

CREATE TABLE Venda(
  id_venda CREATE DATABASE te;
USE te;

CREATE TABLE Cliente(
  id_cliente INT ,
  nome_cliente VARCHAR not null  notnull unsigned auto increment
  endereco_cliente VARCHAR  not null
  tel_cliente INT  not null
  data_cadastro_cliente DATE not null
);

CREATE TABLE Pet(
  id_pet INT notnull unsigned auto increment;
  nome_pet VARCHAR not null;
  especie_pet VARCHAR not null;
  raca_pet VARCHAR not null;
  idade_pet INT not null;
  sexo_pet VARCHAR not null;
  id_cliente VARCHAR not null;
);

CREATE TABLE Produto(
  id_venda INT notnull unsigned auto increment;
  id_cliente INT;
  data_venda DATE not null;
  total_venda INT not null;
);

CREATE TABLE Servico(
  id_servico INT notnull unsigned auto increment;
  nome_servico VARCHAR not null;
  preco_servico FLOAT not null;
  duracao_servico TIME not null;
);

CREATE TABLE Agendamento(
  id_agendamento INT notnull unsigned auto increment;
  id_cliente not null;
  id_pet not null;
  id_servico not null;
  data_agendamento DATE not null;
  status_agendamento VARCHAR not null;
);

CREATE TABLE Fornecedor(
  id_fornecedor INT notnull unsigned auto increment;
  nome_fornecedor VARCHAR not null;
  telefone_fornecedor INT not null;
  endereco_fornecedor VARCHAR not null;
);

CREATE TABLE Funcionario(
  id_funcionario notnull unsigned auto increment;
  nome_funcionario ;
);
