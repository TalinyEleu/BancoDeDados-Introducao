# MariaDB

## O que é MariaDB?
MariaDB é um Sistema de Gerenciamento de Banco de Dados Relacional (RDBMS) de código aberto, criado pelos desenvolvedores originais do MySQL.
Surgiu como um "fork" (derivação) do MySQL para garantir que o banco de dados permanecesse livre e aberto, após a aquisição do MySQL pela Oracle.

- Em resumo, ele é:
  - Open Source
  - Um fork do MySQL (criado pelos mesmos desenvolvedores originais)
  - Muito usado em aplicações web, sistemas acadêmicos e corporativos
 
## Conceitos básicos

### Banco de dados

Um banco de dados é um conjunto de informações organizadas.

```
CREATE DATABASE escola;
```

### Tabelas

As tabelas armazenam os dados em linhas e colunas.

```
CREATE TABLE alunos (
  id INT PRIMARY KEY,
  nome VARCHAR(100),
  email VARCHAR(100)
);
```

### Registros

Cada linha da tabela é um registro (um aluno, por exemplo).

```
INSERT INTO alunos VALUES (1, 'Ana', 'ana@email.com');
```

### Consultas (SELECT)

Usadas para buscar dados.

```
SELECT * FROM alunos;
```

## SQL no MariaDB

O MariaDB utiliza SQL (Structured Query Language) para:

- CREATE → criar
- INSERT → inserir
- SELECT → consultar
- UPDATE → atualizar
- DELETE → remover

```
SELECT nome FROM alunos WHERE id = 1;
```

- [Instalação do MariaDB](Instalacao-MariaDB.md) 

---
📌 Este material é destinado a fins educacionais e introdutórios.