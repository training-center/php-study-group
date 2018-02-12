# Projeto: Banco de questões para certificação


## Nível: Intermediário  


### Banco de questões para certificação 

__Descrição__

Desenvolver uma aplicação de um banco de questões utilizando os conhecimentos adquiridos referente ao [RoadMap de nível Intermediário.](https://github.com/training-center/php-study-group/blob/master/material_de_apoio/roadmap/intermediario.md)
Caso você desconheça ou ainda não tenha feito, pode acessar o [RoadMap do grupo de estudos de PHP/POO.](https://github.com/training-center/php-study-group/tree/master/material_de_apoio/roadmap)

__Objetivo__
Construção de uma aplicação que possibilite os usuários fazer as provas de certificação.

## Material de apoio
Para realização do projeto, [encontra-se disponível o diagrama entidade relacionamento](/material_de_apoio/desafios/projetos/) para implementação do banco de dados do projeto.
Como o objetivo é a implementação do backend, deixo como sugestão o template [AdminLTE](https://adminlte.io/), porém fica ao seu critério usar ou não o template. Nessa primeira etapa, vamos fazer os CRUDs de certificação, questões e usuários de acesso ao sistema.

__Metodologia para desenvolvimento__

* Implementar formulário para inclusão dos usuários (CREATE)
	- campo status
	- campo nome
	- campo e-mail
	- campo senha
	- campo confirmação de senha
* Listagem dos usuários cadastrados (READ)
	- Filtro de busca
		- Buscar por nome
		- Buscar por e-mail
		- Buscar por status
* Funcionalidade de editar informações do usuário escolhido (UPDATE)
* Funcionalidade para excluir o usuário escolhido (DELETE)


* Implementar formulário para inclusão das certificações (CREATE)
	- campo status
	- campo titulo
	- campo descrição
	- campo quantidade de questões
	- campo tempo de prova (em minutos)
* Listagem das certificações cadastradas (READ)
	- Filtro de busca
		- Buscar por titulo
		- Buscar por status
* Funcionalidade de editar informações da certificação escolhida (UPDATE)
* Funcionalidade para excluir a certificação escolhida (DELETE)


* Implementar formulário para inclusão das questões (CREATE)
	- campo status
	- campo certificação
	- campo titulo
	- campo tipo da questão (múltipla escolha com 1 alternativa correta ou múltipla escolha com mais de 1 alternativa correta)
	- campo de alternativas
	- campo de alternativa(s) correta(s)
	- campo de dificuldade da questão (Vai de 1 até 5)
* Listagem das questões cadastradas (READ)
	- Filtro de busca
		- Buscar por certificação
		- Buscar por titulo
		- Buscar por dificuldade da questão
		- Buscar por status
* Funcionalidade de editar informações da questão escolhida (UPDATE)
* Funcionalidade para excluir a questão escolhida (DELETE)

__Em caso de dúvida:__

- Acessar o o grupo de estudos no [Slack do Training Center](https://github.com/training-center/slack)
    - Channel: #php-studies   
        - Buscar por `@reenesoares`

__Repositórios de membros do grupo de estudos que implementaram o projeto__
