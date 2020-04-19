# Fleetman - Release 3  

## Novidades

O Microserviço Position Tracker passou a ser **stateless**.

> Isso significa que ele pode cair e reiniciar à vontade, sem que isso represente perca de dados.

Incluído novo microserviço **fleetman-mongodb**, responsável por realizar a persistência dos dados históricos dos veículos (mongo-stack.yaml).
Utilizado as features de persistência do Kubernetes

- O arquivo storage.yaml descreve de como deverá ser o volume montado para receber esses dados, e como será feita a implementação

	  Ex: Se o volume será um diretório na máquina Host, ou um volume EBS da AWS