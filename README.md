
# Java com Docker

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://choosealicense.com/licenses/mit/) 
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

## Tabela de Conteúdo
- [Sobre o projeto](#sobre-o-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Aprendizados](#aprendizados)
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

<a id="rodando-localmente"></a>
## Rodando localmente

Clone o projeto

```bash
  git clone https://link-para-o-projeto
```

Entre no diretório do projeto

```bash
  cd my-project
```

Instale as dependências

```bash
  npm install
```

Rode a aplicação

```bash
  ./mvnw spring-boot:run
```

<a id="autores"></a>
## Autores

- [@hakkinenT](https://github.com/hakkinenT)
