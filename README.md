# <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"/> Projeto All For One
Para praticar todos os conceitos de SQL. Buscar, Filtrar, Adicionar, Modificar dados na tabela e Manipular e deletar a tabela.

## Tecnologias usadas
Back-end:
> Desenvolvido usando: Docker, docker-compose, SQL, MySQL Workbench

## Instalando Dependências
### Sem Docker

1. Instale as dependências [Caso existam]
```bash
npm install
``` 

> :warning: Para rodar o projeto desta forma, obrigatoriamente você deve ter o ```node``` instalado em seu computador e o avaliador espera que seja a versão 16.

## Com Docker :whale2:
#### Backend

1. Primeiro instale os containers: 
```bash
docker-compose up -d
``` 

2. Em seguida abra o terminal interativo do container: 
```bash
docker exec -it all_for_one bash
``` 

3. Instale as dependências dentro do container: 
```bash
npm install
``` 
#### Testes

1. Dentro do terminal do container:
```bash
npm test
``` 

> :warning: Atenção: O git dentro do container não vem configurado com suas credenciais;
