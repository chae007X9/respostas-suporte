---
Date Created: 2023-11-16T10:42
Last Updated: 2023-11-16T10:42
Created By: CChaline Reis
Last Edited By: CChaline Reis
---
Infelizmente o webhook só avisa quando o documento é assinado por um signatário, ele não envia quando alguém rejeita ele

  

A única forma de saber seria buscar as informações do documento normalmente e verificar no array de "signatures" se alguém tem o evento "rejected"

  

Nós temos planos de melhorar os webhooks e adicionar mais eventos nele, incluído o de recusado, mas no momento só envia ao assinar