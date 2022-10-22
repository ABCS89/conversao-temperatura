# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Aplicando app

1 - criando cluster com k3d
     k3d cluster create K8S -p "80:30000@loadbalancer"

2 - criar imagem conversao-temperatura e exportar para docker-hub

3 - criar Dockerfile

4 - criar deployment.YAML

5 - criar deploy kubernetes

6 - verificar localhost:80