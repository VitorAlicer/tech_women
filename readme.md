// Comandos Usados //

CREATE KEYSPACE tech_women
WITH replication = {'class': 'SimpleStrategy', 'replication_factor': 1};

USE tech_women

CREATE TABLE tech_women.professionals_woman (
  id UUID PRIMARY KEY,
  name TEXT,
  birth_year INT,
  country TEXT,
  area TEXT,
  contribuition TEXT
);

INSERT INTO tech_women.professionals_woman (id, name, birth_year, country, area, contribuition) VALUES (uuid(), 'Ada Lovelace', 1815, 'Reino Unido', 'Matemática, Programação', 'Primeira programadora de computadores');

INSERT INTO tech_women.professionals_woman (id, name, birth_year, country, area, contribuition) VALUES (uuid(), 'Grace Hopper', 1906, 'Estados Unidos', 'Ciência da Computação, Linguagens de Programação', 'Criadora do primeiro compilador e da linguagem COBOL');

INSERT INTO tech_women.professionals_woman (id, name, birth_year, country, area, contribuition) VALUES (uuid(), 'Hedy Lamarr', 1914, 'Áustria', 'Inventora, Comunicações sem fio', 'Co-inventora de uma técnica que serviu de base para Wi-Fi e Bluetooth');

INSERT INTO tech_women.professionals_woman (id, name, birth_year, country, area, contribuition) VALUES (uuid(), 'Radia Perlman', 1951, 'Estados Unidos', 'Redes de Computadores', 'Criadora do Spanning Tree Protocol (STP), fundamental para o funcionamento da Internet');

INSERT INTO tech_women.professionals_woman (id, name, birth_year, country, area, contribuition) VALUES (uuid(), 'Katherine Johnson', 1918, 'Estados Unidos', 'Matemática, Ciência da Computação', 'Cálculos cruciais para missões espaciais da NASA');
