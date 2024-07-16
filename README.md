
# Java com Docker

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://github.com/hakkinenT/docker-java/blob/main/LICENSE) 
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

## Tabela de Conteúdo
- [Sobre o projeto](#sobre-o-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Aprendizados](#aprendizados)
- [Docker Hub](#docker-hub)
- [Rodando localmente](#rodando-localmente)
- [Autores](#autores)

<a id="sobre-o-projeto"></a>
## Sobre o projeto
O objetivo desse projeto foi por em prática os conhecimentos adquiridos no curso **Docker - Dominando a Criação e o Gerenciamento de Containers** da Udemy.
Foram criadas duas Imagens no Docker, uma para rodar uma simples aplicação Java e outra para rodar uma aplicação utilizando o Java Spring Boot.

<a id="tecnologias-utilizadas"></a>
## Tecnologias Utilizadas

- Java
- Spring Boot
- Docker

<a id="aprendizados"></a>
## Aprendizados

Nesse projeto foi possível aprender como se dá a criação de Imagens no Docker a partir de uma imagem de um Sistema Operacional vazio, 
instalando as dependências necessárias e também configurando as variáveis de ambientes nesse S.O. 
Também foi possível por em prática o conceito de Multi-Stage Build para construir uma das Imagens no Docker.

<a id="docker-hub"></a>
## Docker Hub

A imagem do projeto Spring Boot está publicada no Docker Hub. Basta acessar o link abaixo.

```bash
  https://hub.docker.com/r/tholhakk/spring-boot-hello-world
```

<a id="rodando-localmente"></a>
## Rodando localmente

Clone o projeto

```bash
  git clone https://github.com/hakkinenT/docker-java.git
```

Entre no diretório do projeto

```bash
  cd docker-java
```

Entre no diretório do projeto Java

```bash
  cd java21-example-docker
```
Crie a Imagem

```bash
  docker build -t java-example .
```

Obtenha o ID da Imagem

```bash
  docker images
```

Crie um Container a partir da Imagem

```bash
  docker run ID-da-imagem
```

Entre no diretório do projeto Java Spring Boot

```bash
  cd dockerfile-spring-boot
```
Crie a Imagem

```bash
  docker build -t spring-example .
```

Obtenha o ID da Imagem

```bash
  docker images
```

Crie um Container a partir da Imagem

```bash
  docker run -p 8080:8080 ID-da-imagem
```

Abra um Navegador da Web com a seguinte URL
```bash
  http://localhost:8080/
```

<a id="autores"></a>
## Autores

- [@hakkinenT](https://github.com/hakkinenT)
