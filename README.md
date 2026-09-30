# prova 1 de Computação em Nuvem

Nome: Sabrina Lemos Lopes dos Santos
RA: a057a94a54b7027b3896

## O que fiz

Executei uma página web em um contêiner Docker chamado atendimento.
Usei a imagem nginx:alpine e a porta 8082 do ambiente.

## Verificação do contêiner
CONTAINER ID   IMAGE          COMMAND                  CREATED              STATUS              PORTS                                     NAMES
8dde666666e6   nginx:alpine   "/docker-entrypoint.…"   About a minute ago   Up About a minute   0.0.0.0:8082->80/tcp, [::]:8082->80/tcp   atendimento

## Teste da página
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>Atendimento</title>
</head>
<body>
<h1>Atendimento disponivel</h1>
</body>
</html>

## Explicação

a imagem nginx:alpine é um modelo e o contêiner atendimento a execução. o mapeamento 8082:80 serviu para ligar a porta do ambiente para a porta do contêiner
