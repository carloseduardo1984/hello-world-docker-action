# Ação do docker “Hello World” 

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=%20CONCLUIDO&color=GREEN&style=for-the-badge)

![actions](https://user-images.githubusercontent.com/33332202/174480390-8c18d233-e8b9-447a-90dd-9e959fa09be1.png)


Esta ação imprime "Hello World" ou "Hello" + o nome de uma pessoa para saudar no log.

## Entradas / Inputs

### `quem cumprimentar`

**Obrigatório** O nome da pessoa a ser cumprimentada. Padrão `"Mundo"`.

## Saídas

### `hora`

A hora em que te cumprimentamos.

## Exemplo de uso

uses: actions/hello-world-docker-action@v1
with:
   who-to-greet: Carlos Oliveira
   
   ==========================

