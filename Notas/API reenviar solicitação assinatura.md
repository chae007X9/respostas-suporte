---
Date Created: 2023-11-16T10:01
Last Updated: 2023-11-16T10:01
Created By: CChaline Reis
Last Edited By: CChaline Reis
---
Pra reenviar o email de assinatura é só rodar a seguinte requisição:

POST [https://api.autentique.com.br/documentos/](https://api.autentique.com.br/documentos/)_{idDocumento}_/reenviar.json

{"partes": ["emailsignatario@gmail.com"]}