# Docker Compose para Icecast com Nginx como Proxy Reverso

Este projeto configura o Icecast para rodar em um contêiner Docker, com o Nginx atuando como um proxy reverso. A configuração foi realizada utilizando Docker Compose para facilitar o gerenciamento dos contêineres.

## Estrutura do Projeto

O projeto consiste em dois serviços principais:

1. **Icecast**: Um servidor de streaming de áudio.
2. **Nginx**: Um servidor web que atua como proxy reverso para o Icecast.

## Arquivo `docker-compose.yml`

O arquivo `docker-compose.yml` é utilizado para definir e rodar os contêineres do Icecast e do Nginx.

### Versão

```yaml
version: '3.8'

### Referencias

https://www.youtube.com/watch?v=mv6XLFF_Frg
https://danielnoethen.de/butt/release/1.43.0/butt-1.43.0_manual.html#_streaming
