# Integração de câmera IP com o software Insomnia

Este repositório contém exemplos de código para integrar e utilizar APIs de câmeras IP utilizando o software Insomnia. Insomnia é uma ferramenta de teste de API que permite criar e gerenciar requisições HTTP de forma fácil e intuitiva.

## Sumário

- [Introdução](#introdução)
- [Pré-requisitos](#pré-requisitos)
- [Configuração do Insomnia](#configuração-do-insomnia)
- [Exemplos de Requisições](#exemplos-de-requisições)
  - [Autenticação](#autenticação)
  - [Obter Snapshot](#obter-snapshot)
  - [Controlar PTZ](#controlar-ptz)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Introdução

Este documento fornece instruções detalhadas sobre como configurar e utilizar o Insomnia para interagir com APIs de câmeras IP. Exemplos incluem autenticação, captura de snapshots e controle PTZ (Pan, Tilt, Zoom).

## Pré-requisitos

Antes de começar, você precisará do seguinte:

- Insomnia instalado. Você pode baixá-lo [aqui](https://insomnia.rest/download).
- Uma câmera IP compatível com a API que você deseja utilizar.
- Credenciais de acesso à câmera IP (usuário e senha).
- Endereço IP da câmera.

## Configuração do Insomnia

1. Abra o Insomnia.
2. Crie um novo projeto ou abra um projeto existente.
3. Adicione um novo ambiente para armazenar variáveis como URL da câmera, usuário e senha.

```json
{
  "base_url": "http://<IP_DA_CAMERA>",
  "username": "<USUARIO>",
  "password": "<SENHA>"
}
