# Desafio 1 - Maratona FullCycle 2.0

Para maiores informações sobre o desafio, leia este [link](https://github.com/codeedu/maratona2-desafios#desafio-1).

## Como rodar para desenvolvimento?

Você deverá ter o `docker` instalado em seu sistema operacional.

Com o `docker` instalado, faça o build da imagem:

`docker build -t luisbilecki/maratonafullcycle2-desafio1 . `

Rode o container usando:

`docker run -d -p 3000:3000 luisbilecki/maratonafullcycle2-desafio1`

Acesse a URL `localhost:3000` no seu *browser* e visualize:

`Maratona Full Cycle 2.0`

## Como executar a partir da imagem no Dockerhub?

Você deverá ter o `docker` instalado em seu sistema operacional.

Baixe a imagem usando:

`docker pull luisbilecki/maratonafullcycle2-desafio1:latest`

Crie um container com:

`docker run -d -p 3000:3000 luisbilecki/maratonafullcycle2-desafio1`

Acesse a URL `localhost:3000` no seu *browser* e visualize:

`Maratona Full Cycle 2.0`
