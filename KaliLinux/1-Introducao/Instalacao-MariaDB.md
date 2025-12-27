# INSTALAÇÃO DO MARIADB

## Instalação MariaDB no CentOS
Sistemas especializados na persistência de dados que oferecem recursos mais sofisticados e eficientes. Um sistema gerenciador de banco de dados é capaz de gerenciar informações de diversos sistemas ao mesmo tempo.

- Lista de SGBDs mais utilizados:
  - MySQL Server
  - Oracle Database
  - SQL Server
  - MariaDB
  - PostgreSQL

## MariaDB Server
Nossa parte prática será realizada em um **sistema operacional baseado em Linux**, utilizando como SGBD o MariaDB Server, essa ferramenta de banco de dados é capaz de:

#### Passo 1 - Instalando o MariaDB

```
$ sudo dnf install mariadb-server
```

ou ...

```
$ sudo yum install mariadb-server
```

Assim que a instalação terminar, inicie o serviço com o _systemctl_:

```
$ sudo systemctl start mariadb
```

Após isso, verifique o status do serviço:

```
$ sudo systemctl status mariadb
```

![Status MariaDB](/imagens/1.png)



---
📌 Este material é destinado a fins educacionais e introdutórios.

