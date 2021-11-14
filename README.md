# Acción de docker Hello world

Esta acción imprime "Hello World" o "Hello" + el nombre de una persona a quien saludar en el registro.

## Inputs

## `who-to-greet`

**Required** El nombre de la persona a la cual saluda. Por defecto `"Mundo"`.

## Outputs

## `time`

La fecha en la que se saludo.

## Ejemplo de uso

uses: aristi09/hello-world-docker-action@v1
with:
  who-to-greet: 'David Aristizabal'
